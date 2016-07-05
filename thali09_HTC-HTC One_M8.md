#### Test 72145431fb64fa4_thali09_HTC-HTC One_M8 Logs


```
--------- beginning of main
07-05 12:50:23.431   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,--------- beginning of system
07-05 12:50:23.811   904  1068 D PMS     : acquireWL(111324f0): PARTIAL_WAKE_LOCK  *alarm* 0x1 904 1000 WorkSource{10075}
07-05 12:50:23.811   904  1068 V AlarmManager: sending alarm PendingIntent{1c080a69: PendingIntentRecord{1a7f2dcb com.android.vending startService}}, i=null, t=0, cnt=1, w=1467715823781, Int=0
07-05 12:50:23.811   904   904 D PMS     : releaseWL(111324f0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
07-05 12:50:24.101  7050  7050 E cutils-trace: Error opening trace file: No such file or directory (2)
07-05 12:50:24.131  7050  7050 D CustomizationManager: ====startRecUseTime====
07-05 12:50:24.131  7050  7050 D htc.customization.log.level:  is 
07-05 12:50:24.131  7050  7050 W CustomizationLogLevel: Level value is invalid, use default level 2
07-05 12:50:24.201  1782  1782 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 12:50:24.221  1782  1878 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
07-05 12:50:24.221  1782  1878 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:50:24.221  1782  1878 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:50:24.221  1782  1878 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 12:50:24.221  7050  7050 D CustomizationManager:  Read ACC file spent 0.046 (s)
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__001
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__102
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__203
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__405
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__304
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-05 12:50:24.221  1782  1878 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__032
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__016
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__A48
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__K18
07-05 12:50:24.221  7050  7050 D CIDMapFileReader: Parsing tag item name = HTC__002
07-05 12:50:24.221  7050  7050 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
07-05 12:50:24.221  7050  7050 I CustomizationCIDLoader: Parsing tag category name = system
07-05 12:50:24.231  7050  7050 I CustomizationCIDLoader: Parsing tag category name = application
07-05 12:50:24.231  7050  7050 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-05 12:50:24.231  7050  7050 I CustomizationCIDLoader: Parsing tag category name = Settings
07-05 12:50:24.231  7050  7050 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-05 12:50:24.231  7050  7050 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-05 12:50:24.231  7050  7050 I CustomizationCIDLoader: Parsing tag category name = ACC
07-05 12:50:24.231  7050  7050 D CustomizationManager:  Read CID file spent 0.095 (s)
07-05 12:50:24.231  7050  7050 D CustomizationManager:  All configurations done spent 0.096 (s)
07-05 12:50:24.231  6080  6080 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 12:50:24.231  6080  6080 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:50:24.231  6080  6080 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
07-05 12:50:24.251  7050  7050 E ActTriggerJNI: open library fail.
07-05 12:50:24.261  2320  2335 E MP-Decision: Update arg 2
07-05 12:50:24.261   904  1478 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 12:50:24.261  2320  2335 E MP-Decision: Update arg 4
07-05 12:50:24.261   904  1016 D PMS     : acquireHCC(319b2523): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 904 1000 null
07-05 12:50:24.261   904  1016 D PMS     : acquireHCC(71aa20): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 904 1000 null
07-05 12:50:24.271  2320  2335 E MP-Decision: Update arg "0 190 240 240".
07-05 12:50:24.271  2320  2335 E MP-Decision: Update arg "0 75 400 400".
07-05 12:50:24.281   904  1478 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7083 uid=10192 gids={50192, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:50:24.301   904   904 V ActivityManager: Display changed displayId=0
07-05 12:50:24.301  1202  1202 D DotMatrix: [EventService]  onDisplayChanged: 0
07-05 12:50:24.301  1202  1202 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
07-05 12:50:24.341  1483  1483 I TrimMemoryManager: [trimMemory] 20
07-05 12:50:24.371  7083  7083 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-05 12:50:24.381  7083  7083 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1595-1596)
07-05 12:50:24.381  7083  7083 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:24.391  7083  7083 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4282f14}
07-05 12:50:24.391  7083  7083 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:50:24.391  7083  7083 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:50:24.411  7083  7083 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 12:50:24.411  7083  7083 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:24.411  7083  7083 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 12:50:24.421  7083  7083 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-05 12:50:24.431  7083  7083 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:50:24.431  7083  7083 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:50:24.431  7083  7083 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
07-05 12:50:24.431  7083  7083 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-05 12:50:24.431  7083  7083 I Adreno-EGL: Build Date: 12/11/14 Thu
07-05 12:50:24.431  7083  7083 I Adreno-EGL: Local Branch: 
07-05 12:50:24.431  7083  7083 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
07-05 12:50:24.431  7083  7083 I Adreno-EGL: Local Patches: NONE
07-05 12:50:24.431  7083  7083 I Adreno-EGL: Reconstruct Branch: NOTHING
07-05 12:50:24.481   904  1613 W System.err: java.lang.Throwable: stack dump
07-05 12:50:24.481   904  1006 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-05 12:50:24.481   904  1006 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33b454e4:true
07-05 12:50:24.481   904  1613 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-05 12:50:24.481   904  1613 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
07-05 12:50:24.481   904  1613 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-05 12:50:24.481   904  1613 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-05 12:50:24.481  7083  7115 D BluetoothAdapter: 644133630: getState(). Returning 12
07-05 12:50:24.541  7083  7083 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:24.551  7083  7083 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 12:50:24.561  7083  7083 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
07-05 12:50:24.561  7083  7083 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:24.561  7083  7083 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:50:24.601  7083  7083 D Atlas   : Validating map...
07-05 12:50:24.601  7083  7113 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-05 12:50:24.601   904  1545 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-05 12:50:24.621   904  1005 D StatusBarManagerService: setSystemUiVisibility(0xc0000600)
07-05 12:50:24.621   904  1005 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:50:24.621   904  1005 D StatusBarManagerService: hiding MENU key
07-05 12:50:24.621   904  1005 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-05 12:50:24.621   904  1005 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:50:24.621   904  1005 D StatusBarManagerService: hiding MENU key
07-05 12:50:24.651  7083  7083 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@37cb6de5, mServedView=org.apache.cordova.engine.SystemWebView{2137c0ba VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2b51eb6b
07-05 12:50:24.651   904  1610 I InputMethodManagerService: Disable input method client, pid=1483
07-05 12:50:24.651   904  1610 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-05 12:50:24.661  7083  7083 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
07-05 12:50:24.681   904  1007 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +376ms (total +419ms)
07-05 12:50:24.711  7083  7083 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7083
07-05 12:50:24.781  7083  7083 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-05 12:50:24.871  7083  7130 D jxcore_app_log: JniHelper::setJavaVM(0xb7abeb98), pthread_self() = -1193815088
07-05 12:50:24.871  7083  7130 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:50:24.871  7083  7130 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:50:24.871  7083  7130 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:50:24.871  7083  7130 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:50:24.871  7083  7130 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-05 12:50:24.871  7083  7130 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e89885e added. We now have 1 listener(s)
07-05 12:50:24.871   904  1539 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:50:24.871  7083  7130 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 50:2E:6C:AC:21:50
07-05 12:50:24.871  7083  7130 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "50:2E:6C:AC:21:50"
07-05 12:50:24.871  7083  7130 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 12:50:24.871  7083  7130 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 50:2E:6C:AC:21:50
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@244c9a55 added. We now have 1 listener(s)
07-05 12:50:24.881  7083  7130 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-05 12:50:24.881   904   904 E WifiTrafficPoller: ADD_CLIENT: 8
07-05 12:50:24.881   904  1080 D WifiService: New client listening to asynchronous messages
07-05 12:50:24.881  7083  7130 D BluetoothAdapter: 644133630: getState(). Returning 12
07-05 12:50:24.881  7083  7130 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-05 12:50:24.881  7083  7130 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-05 12:50:24.881  7083  7130 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-05 12:50:24.891  7083  7130 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 12:50:24.891   904  1613 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:50:24.891  7083  7130 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 50:2E:6C:AC:21:50
07-05 12:50:24.891  7083  7130 D BluetoothAdapter: 644133630: getState(). Returning 12
07-05 12:50:24.891  7083  7130 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:50:24.891  7083  7130 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:24.891  7083  7130 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 12:50:24.891  7083  7130 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:24.891  7083  7130 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:50:24.891  7083  7130 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:50:24.891  7083  7130 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:50:24.891  7083  7130 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 12:50:24.891  7083  7130 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:50:24.891  7083  7130 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 12:50:24.891  7083  7130 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 12:50:24.901  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 12:50:24.901  7083  7083 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-05 12:50:24.911  7083  7083 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:50:25.641  7083  7137 W jxcore-log: Initializing JXcore engine
07-05 12:50:25.641  7083  7137 W jxcore-log: JXcore engine is ready
,07-05 12:50:25.711  7083  7137 W jxcore-log: Starting JXcore engine
,07-05 12:50:25.801  7083  7137 W jxcore-log: Platform android
07-05 12:50:25.801  7083  7137 W jxcore-log: 
07-05 12:50:25.801  7083  7137 W jxcore-log: Process ARCH arm
07-05 12:50:25.801  7083  7137 W jxcore-log: 
,07-05 12:50:26.011  7083  7137 I jxcore-log: JXcore Cordova bridge is ready!,
07-05 12:50:26.011  7083  7137 I jxcore-log: 
07-05 12:50:26.011  7083  7137 W jxcore-log: JXcore engine is started
,07-05 12:50:26.021  7083  7130 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 12:50:26.021  7083  7083 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 12:50:26.261   904  1016 D PMS     : releaseHCC(319b2523): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,07-05 12:50:26.261   904  1016 D PMS     : releaseHCC(71aa20): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-05 12:50:26.261  2320  2335 E MP-Decision: Update arg 1
,07-05 12:50:34.011   904  1000 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA
,07-05 12:50:34.011   904  1000 D PMS     : acquireWL(136e7d7b): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 904 1000 null,
,07-05 12:50:34.011   904  1000 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,07-05 12:50:34.041   904  7144 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 4,
,07-05 12:50:34.041   904  7144 D libc    : [NET] android_getaddrinfofornet-, err=8,
,07-05 12:50:34.051   904  7144 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 1024,
,07-05 12:50:34.051   904  7144 D libc    : [NET] android_getaddrinfofornet-, pass to proxy,
,07-05 12:50:34.051   904  7144 D libc    : [NET] android_getaddrinfo_proxy+,
,07-05 12:50:34.061   904  7144 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
,07-05 12:50:34.061   461  7146 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 1024,
07-05 12:50:34.061   461  7146 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604,
,07-05 12:50:34.121   461  7146 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
07-05 12:50:34.121   461  7146 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,07-05 12:50:34.121   904  7144 D libc    : [NET] android_getaddrinfo_proxy-, success,
,07-05 12:50:34.131   904  7144 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35322e38342e31),sn(),hints(known),family 0,flags 4,
,07-05 12:50:34.131   904  7144 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,07-05 12:50:34.201   904  7144 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data,
,07-05 12:50:34.691   904  1402 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0,
07-05 12:50:34.691   904  1402 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0,
,07-05 12:50:34.691   904  7144 D GpsLocationProvider:  [handleDownloadXtraData]inject done.,
,07-05 12:50:34.691   904  7144 D PMS     : acquireWL(15a41544): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null,
,07-05 12:50:34.701   904  7144 D PMS     : releaseWL(136e7d7b): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null,
07-05 12:50:34.701   904  1000 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
,07-05 12:50:34.701   904  1000 D PMS     : releaseWL(15a41544): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,07-05 12:50:35.521  7083  7137 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
07-05 12:50:35.521  7083  7137 I jxcore-log: 
,07-05 12:50:35.521  7083  7137 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
07-05 12:50:35.521  7083  7137 I jxcore-log: ,
,07-05 12:50:35.531  7083  7137 D BluetoothAdapter: 644133630: getState(). Returning 12
07-05 12:50:35.531  7083  7137 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
07-05 12:50:35.531  7083  7137 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:50:35.531  7083  7137 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
07-05 12:50:35.531  7083  7137 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:50:35.531  7083  7137 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
07-05 12:50:35.531  7083  7137 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,07-05 12:50:35.531  7083  7137 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:50:35.531  7083  7137 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
,07-05 12:50:35.531  7083  7137 D BluetoothAdapter: 644133630: getState(). Returning 12,
,07-05 12:50:35.531  7083  7137 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,07-05 12:50:35.531  7083  7137 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
07-05 12:50:35.531  7083  7137 I jxcore-log: 
,07-05 12:50:35.531  7083  7137 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
07-05 12:50:35.531  7083  7137 I jxcore-log: 
,07-05 12:50:35.901  7083  7137 I jxcore-log: Unit Test app is loaded,
,07-05 12:50:35.901  7083  7137 I jxcore-log: ,
07-05 12:50:35.901  7083  7137 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 12:50:35.901  7083  7137 I jxcore-log: 
,07-05 12:50:35.901  7083  7137 I jxcore-log: My device name is: HTC-HTC One_M8
07-05 12:50:35.901  7083  7137 I jxcore-log: 
07-05 12:50:35.911  7083  7137 I jxcore-log: WARN testUtils: myNameCallback not set!
07-05 12:50:35.911  7083  7137 I jxcore-log: 
07-05 12:50:35.921  7083  7083 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 12:50:38.431   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,07-05 12:50:39.551  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
07-05 12:50:39.551  7083  7137 I jxcore-log: 
,07-05 12:50:39.931  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
07-05 12:50:39.931  7083  7137 I jxcore-log: 
,07-05 12:50:39.961  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
07-05 12:50:39.961  7083  7137 I jxcore-log: ,
,07-05 12:50:39.961  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
07-05 12:50:39.961  7083  7137 I jxcore-log: ,
,07-05 12:50:39.971  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
07-05 12:50:39.971  7083  7137 I jxcore-log: ,
,07-05 12:50:39.981  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 12:50:39.981  7083  7137 I jxcore-log: 
,07-05 12:50:40.891  1529  1775 D AutoSetting: service - handleMessage() stop self,
,07-05 12:50:40.971  1529  1529 D AutoSetting: service - onDestroy() END,
07-05 12:50:40.971  1529  1775 D AutoSetting: service - handleMessage() quit looper
,07-05 12:50:41.871  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
07-05 12:50:41.871  7083  7137 I jxcore-log: 
,07-05 12:50:41.881  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
07-05 12:50:41.881  7083  7137 I jxcore-log: 
,07-05 12:50:41.891  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
07-05 12:50:41.891  7083  7137 I jxcore-log: 
,07-05 12:50:42.041  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
07-05 12:50:42.041  7083  7137 I jxcore-log: 
,07-05 12:50:42.121  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
07-05 12:50:42.121  7083  7137 I jxcore-log: 
,07-05 12:50:42.171  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
07-05 12:50:42.171  7083  7137 I jxcore-log: 
,07-05 12:50:42.171  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js,
07-05 12:50:42.171  7083  7137 I jxcore-log: 
,07-05 12:50:42.361  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
07-05 12:50:42.361  7083  7137 I jxcore-log: 
,07-05 12:50:42.381  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
07-05 12:50:42.381  7083  7137 I jxcore-log: 
,07-05 12:50:42.381  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
07-05 12:50:42.381  7083  7137 I jxcore-log: 
,07-05 12:50:42.391  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
07-05 12:50:42.391  7083  7137 I jxcore-log: 
,07-05 12:50:42.401  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
07-05 12:50:42.401  7083  7137 I jxcore-log: 
,07-05 12:50:42.421  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
07-05 12:50:42.421  7083  7137 I jxcore-log: ,
,07-05 12:50:42.501  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
07-05 12:50:42.501  7083  7137 I jxcore-log: 
,07-05 12:50:42.511  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
07-05 12:50:42.511  7083  7137 I jxcore-log: 
,07-05 12:50:42.531  7083  7137 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 12:50:42.531  7083  7137 I jxcore-log: 
,07-05 12:50:42.541  7083  7137 D BluetoothAdapter: 644133630: getState(). Returning 12
07-05 12:50:42.541  7083  7137 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED,
,07-05 12:50:42.541  7083  7137 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported,
07-05 12:50:42.541  7083  7137 I jxcore-log: 
,07-05 12:50:44.231   904  1068 D PMS     : acquireWL(2beff62d): PARTIAL_WAKE_LOCK  *alarm* 0x1 904 1000 WorkSource{10025}
07-05 12:50:44.241   904  1068 V AlarmManager: sending alarm PendingIntent{25fbb762: PendingIntentRecord{15d920f3 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=148077, Int=0,
07-05 12:50:44.251   904  1068 V AlarmManager: sending alarm PendingIntent{2782c829: PendingIntentRecord{1a7f2dcb com.android.vending startService}}, i=null, t=0, cnt=1, w=1467715844241, Int=0,
07-05 12:50:44.271   904   904 D PMS     : releaseWL(2beff62d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10025}
,07-05 12:50:44.531  1782  1782 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:50:44.551  1782  1809 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
07-05 12:50:44.551  1782  1809 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:50:44.551  1782  1809 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:50:44.551  1782  1809 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:50:44.551  1782  1809 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:50:44.561  6080  6080 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-05 12:50:44.561  6080  6080 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:50:44.561  6080  6080 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 4.
,07-05 12:50:46.121   904   904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:817 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,07-05 12:50:46.301  1422  1580 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
,07-05 12:50:46.331  1422  1580 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<,
,07-05 12:50:56.171   904  1269 D PMS     : acquireWL(f0c2ce3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:50:56.171   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:50:56.171   904  1269 I BatteryService: n_update end,
07-05 12:50:56.171   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:50:56.171   904   904 D NotificationService: plugged=true pluggin=true,
07-05 12:50:56.171   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:50:56.171   904  1080 D WifiController: battery changed pluggedType: 2
,07-05 12:50:56.171   904   904 D UsbnetService: BroadcastReceiver::onReceive-
,07-05 12:50:56.181  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:50:56.181  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:50:56.181  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:50:56.181  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
07-05 12:50:56.181   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:50:56.181  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,07-05 12:50:56.181   904   904 D PMS     : runPSCheck
07-05 12:50:56.181  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,07-05 12:50:56.181   904   904 D HtcPowerSaver: Checking...
07-05 12:50:56.181  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:50:56.181   904   904 I HtcPowerSaver: >> updateStatus
,07-05 12:50:56.191   904  1269 D PMS     : releaseWL(f0c2ce3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:50:56.191   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,07-05 12:50:56.191   904   904 I HtcPowerSaver: << updateStatus
,07-05 12:50:56.231  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:50:58.431   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,07-05 12:51:04.561   904  1068 D PMS     : acquireWL(386e76e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 904 1000 WorkSource{1000},
,07-05 12:51:04.571   904  1068 V AlarmManager: sending alarm PendingIntent{353c8f72: PendingIntentRecord{2a9ffc3 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=167196, Int=0
,07-05 12:51:04.601   904  1068 V AlarmManager: sending alarm PendingIntent{266d985e: PendingIntentRecord{1a7f2dcb com.android.vending startService}}, i=null, t=0, cnt=1, w=1467715864571, Int=0
07-05 12:51:04.631   904   904 D PMS     : releaseWL(386e76e0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,07-05 12:51:04.651  1122  2268 D WeatherUtility: Weather sync is On,
,07-05 12:51:04.821   904  1478 I art     : Explicit concurrent mark sweep GC freed 22114(1186KB) AllocSpace objects, 3(91KB) LOS objects, 33% free, 17MB/25MB, paused 1.155ms total 80.364ms
,07-05 12:51:04.841  1122  2268 D WeatherUtility: Weather sync is On
,07-05 12:51:04.901  1782  1782 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:51:04.911  1782  1875 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
,07-05 12:51:04.911  1782  1875 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:51:04.911  1782  1875 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:51:04.911  1782  1875 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:51:04.911  1782  1875 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:51:04.921  6080  6080 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
07-05 12:51:04.921  6080  6080 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:51:04.921  6080  6080 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 5.
,07-05 12:51:20.351  1422  1422 D TelephonyReceiver: switchBindHtcMsgCursor: null,
,07-05 12:51:23.441   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,07-05 12:51:24.941   904  1068 D PMS     : acquireWL(3f138f09): PARTIAL_WAKE_LOCK  *alarm* 0x1 904 1000 WorkSource{10075},
,07-05 12:51:24.951   904  1068 V AlarmManager: sending alarm PendingIntent{3aded50e: PendingIntentRecord{1a7f2dcb com.android.vending startService}}, i=null, t=0, cnt=1, w=1467715884930, Int=0
07-05 12:51:24.961   904   904 D PMS     : releaseWL(3f138f09): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
,07-05 12:51:25.191  1782  1782 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:51:25.211  1782  1878 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure,
,07-05 12:51:25.211  1782  1878 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:51:25.211  1782  1878 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:51:25.211  1782  1878 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 12:51:25.211  1782  1878 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 12:51:25.221  6080  6080 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 12:51:25.221  6080  6080 D Finsky  : [1] 5.onFinished: Installation state replication failed.
07-05 12:51:25.221  6080  6080 D Finsky  : [1] 5.onFinished: Giving up after 6 failures.
,07-05 12:51:38.451  1122  2345 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,07-05 12:51:38.461  1529  1529 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@164808f4,
,07-05 12:51:38.481   904  1617 D Process : killProcessQuiet, pid=6521,
,07-05 12:51:38.481   904  1617 I ActivityManager: Killing 6521:com.htc.mms.backupagent/u0a79 (adj 15): empty #17,
07-05 12:51:38.481   904  1617 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 ,
,07-05 12:51:38.501  1122  2345 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,07-05 12:51:38.511   904  1612 I ActivityManager: Recipient 6521,
,07-05 12:51:38.541   904  1612 D Process : killProcessQuiet, pid=6521
,07-05 12:51:38.541   904  1612 W libprocessgroup: failed to open /acct/uid_10079/pid_6521/cgroup.procs: No such file or directory
07-05 12:51:38.541   904  1612 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 ,
,07-05 12:51:45.831   904  1068 D PMS     : acquireWL(315ee540): PARTIAL_WAKE_LOCK  *alarm* 0x1 904 1000 WorkSource{1000},
,07-05 12:51:45.831   904  1068 V AlarmManager: sending alarm PendingIntent{3ec14c79: PendingIntentRecord{3c309dbe android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1467715873839, Int=0
,07-05 12:51:45.831   904   904 D PMS     : acquireWL(2fb73e1f): PARTIAL_WAKE_LOCK  *backup* 0x1 904 1000 null
07-05 12:51:45.841   904  1068 V AlarmManager: sending alarm PendingIntent{10ed156c: PendingIntentRecord{2f013735 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=188516, Int=0
,07-05 12:51:45.841   904  1544 D PMS     : acquireWL(a54d7ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
07-05 12:51:45.851   904  1068 V AlarmManager: sending alarm PendingIntent{301b9d3b: PendingIntentRecord{3c4c1c58 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=213032, Int=0
07-05 12:51:45.851   904   904 D PMS     : releaseWL(315ee540): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
07-05 12:51:45.881   904  1612 D PMS     : acquireWL(211b11b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
07-05 12:51:45.911   904  1539 D PMS     : releaseWL(a54d7ca): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,07-05 12:51:45.921   904  1091 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
,07-05 12:51:45.921   904  1091 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
,07-05 12:51:45.921   904  1091 D PMS     : releaseWL(2fb73e1f): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
07-05 12:51:45.931  1782  1782 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:51:45.951   904  1612 D PMS     : acquireWL(3f9278b3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms},
07-05 12:51:45.951   904  1611 D PMS     : releaseWL(3f9278b3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,07-05 12:51:45.961   904  1539 D PMS     : releaseWL(211b11b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
07-05 12:51:45.961   904  1478 D PMS     : acquireWL(3f961e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
07-05 12:51:45.961   904  1612 D PMS     : releaseWL(3f961e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
07-05 12:51:45.961   904  1618 D PMS     : acquireWL(ad145e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
,07-05 12:51:46.001   904  1617 D PMS     : acquireWL(199df26e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms},
,07-05 12:51:46.031   904  1539 D PMS     : acquireWL(1f16b19c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms},
07-05 12:51:46.031   904  1527 D PMS     : releaseWL(ad145e9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
07-05 12:51:46.041  1782  7209 I VacuumService: Vacuum at: now=1467715906052 tag=VacuumService,
,07-05 12:51:46.051  1782  7210 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-05 12:51:46.071   904  1089 D PMS     : releaseWL(199df26e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
07-05 12:51:46.061  1782  7210 W Uploader: No account for auth token provided
07-05 12:51:46.071   904  1478 D PMS     : acquireWL(17bac77a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
,07-05 12:51:46.091  1782  7210 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
07-05 12:51:46.091   904  1610 D PMS     : releaseWL(17bac77a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
07-05 12:51:46.091  1782  7210 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 12:51:46.091   904  1089 D PMS     : acquireWL(2b9de146): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
,07-05 12:51:46.091   904   919 D PMS     : releaseWL(2b9de146): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
07-05 12:51:46.101  1782  7210 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-05 12:51:46.101  1782  7210 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 12:51:46.101  1782  7210 D libc    : [NET] android_getaddrinfo_proxy+
07-05 12:51:46.101  1782  7210 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-05 12:51:46.101   461  7222 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-05 12:51:46.101   461  7222 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-05 12:51:46.161   461  7222 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
07-05 12:51:46.161   461  7222 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,07-05 12:51:46.161  1782  7210 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 12:51:47.531  1782  7210 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
07-05 12:51:47.541  1782  7210 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 12:51:47.541  1782  7210 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,07-05 12:51:47.541  1782  7210 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 12:51:47.781  1782  7210 W Uploader: No account for auth token provided,
,07-05 12:51:47.921  1782  7210 W Uploader: No account for auth token provided,
,07-05 12:51:48.311  1782  7210 W Uploader:  no longer exists, so no auth token.,
,07-05 12:51:48.501  1782  7210 W Uploader: No account for auth token provided,
,07-05 12:51:48.751  1782  7210 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,07-05 12:51:48.751  1782  7210 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:51:48.751  1782  7210 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:51:48.751  1782  7210 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 12:51:48.751  1782  7210 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:51:48.791  1202  1223 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,07-05 12:51:48.791  1122  1122 I RemoteViews: reapply : com.google.android.gms 2 40,
07-05 12:51:48.801  1202  1223 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
07-05 12:51:48.811  1782  7210 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 12:51:48.811  1782  7210 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
07-05 12:51:48.811  1782  7210 E Uploader: ,	at com.google.android.gms.auth.p.c(SourceFile:550)
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
07-05 12:51:48.811  1782  7210 E Uploader: 	,at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
07-05 12:51:48.811  1782  7210 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,07-05 12:51:48.871   904   920 D PMS     : releaseWL(1f16b19c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
07-05 12:51:48.881   904  1305 D PMS     : acquireWL(13f8551b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
,07-05 12:51:48.901   904  1618 D PMS     : releaseWL(13f8551b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms},
07-05 12:51:48.911   904  1544 D PMS     : acquireWL(188ca6b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
,07-05 12:51:48.921   904  1539 D PMS     : releaseWL(188ca6b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,07-05 12:51:56.211   904  1611 D PMS     : acquireWL(38ff3c91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:51:56.251  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:51:56.221   904  1611 I BatteryService: n_update end
07-05 12:51:56.251  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:51:56.251  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
07-05 12:51:56.251  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:51:56.251   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:51:56.251  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,07-05 12:51:56.251   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:51:56.251   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:51:56.251   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,07-05 12:51:56.251   904  1080 D WifiController: battery changed pluggedType: 2
07-05 12:51:56.251   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:51:56.261   904  1012 D HtcPowerSaver: updateBatteryInfo
,07-05 12:51:56.251  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:51:56.261   904   904 D PMS     : runPSCheck
07-05 12:51:56.261  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:51:56.261   904   904 D HtcPowerSaver: Checking...
07-05 12:51:56.261   904   904 I HtcPowerSaver: >> updateStatus
,07-05 12:51:56.261   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:51:56.271   904  1611 D PMS     : releaseWL(38ff3c91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:51:56.271   904   904 I HtcPowerSaver: << updateStatus
,07-05 12:51:56.301  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:52:03.441   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 12:52:13.451   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:52:28.451   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,07-05 12:52:47.131   904   919 D PMS     : acquireWL(324727f6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:52:47.131   904   919 I BatteryService: n_update end
07-05 12:52:47.141   904   919 D PMS     : releaseWL(324727f6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:52:48.461   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,07-05 12:52:56.361   904   920 D PMS     : acquireWL(34bd27f7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:52:56.391   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:52:56.371   904   920 I BatteryService: n_update end
07-05 12:52:56.391   904   904 D UsbnetService: onReceive BATTERY_CHANGED
,07-05 12:52:56.381   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:52:56.391   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:52:56.391   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:52:56.391   904  1080 D WifiController: battery changed pluggedType: 2
,07-05 12:52:56.391  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:52:56.391  1122  1122 D PowerUI : closing low battery warning: level=100
,07-05 12:52:56.391  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:52:56.391  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:52:56.391  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 12:52:56.391   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:52:56.391  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:52:56.401   904   904 D PMS     : runPSCheck
,07-05 12:52:56.391  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 12:52:56.401   904   904 D HtcPowerSaver: Checking...
,07-05 12:52:56.401   904   904 I HtcPowerSaver: >> updateStatus
07-05 12:52:56.401   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:52:56.401   904   904 I HtcPowerSaver: << updateStatus
,07-05 12:52:56.401   904   920 D PMS     : releaseWL(34bd27f7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:52:56.441  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:52:59.401   904  1478 D PMS     : acquireWL(36c17664): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
,07-05 12:52:59.431   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:52:59.411   904  1478 I BatteryService: n_update end
07-05 12:52:59.431   904   904 D UsbnetService: onReceive BATTERY_CHANGED
,07-05 12:52:59.431   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:52:59.431   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:52:59.431   904   904 D UsbnetService: BroadcastReceiver::onReceive-
,07-05 12:52:59.431   904  1080 D WifiController: battery changed pluggedType: 2
07-05 12:52:59.441  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:52:59.441  1122  1122 D PowerUI : closing low battery warning: level=100
,07-05 12:52:59.441  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:52:59.441  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:52:59.441  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,07-05 12:52:59.441   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:52:59.441  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 12:52:59.451   904   904 D PMS     : runPSCheck
,07-05 12:52:59.441  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
07-05 12:52:59.451   904   904 D HtcPowerSaver: Checking...
07-05 12:52:59.451   904   904 I HtcPowerSaver: >> updateStatus
07-05 12:52:59.481  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,07-05 12:52:59.461   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:52:59.481  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:52:59.461   904   904 I HtcPowerSaver: << updateStatus
07-05 12:52:59.481  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,07-05 12:52:59.461   904  1478 D PMS     : releaseWL(36c17664): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:52:59.481  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 12:52:59.481   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:52:59.481   904  1617 D PMS     : acquireWL(37ca10cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null
07-05 12:52:59.481   904   904 D UsbnetService: onReceive BATTERY_CHANGED
,07-05 12:52:59.481   904  1617 I BatteryService: n_update end
07-05 12:52:59.481   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:52:59.481   904  1617 D PMS     : releaseWL(37ca10cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:52:59.481   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:52:59.481  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:52:59.481   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:52:59.491  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true
07-05 12:52:59.481   904  1080 D WifiController: battery changed pluggedType: 2
07-05 12:52:59.491  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:52:59.481  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:52:59.481   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:52:59.491   904   904 D PMS     : runPSCheck
07-05 12:52:59.491   904   904 D HtcPowerSaver: Checking...
07-05 12:52:59.491   904   904 I HtcPowerSaver: >> updateStatus
07-05 12:52:59.491   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:52:59.491   904   904 I HtcPowerSaver: << updateStatus
,07-05 12:52:59.541  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:53:13.461   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 7 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age,
07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 15 BSSID 84:b2:61:1a:ce:7f SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 16 BSSID 84:b2:61:1a:ce:7b SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age,
07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
,07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 3 BSSID 84:b2:61:1a:ce:74 SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 4 BSSID 84:b2:61:1a:ce:72 SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 8 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
,07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 22 BSSID 84:b2:61:1a:ce:70 SSID '\x00' due to wpa_bss_flush_by_age
07-05 12:53:14.371  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 17 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age,
07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 18 BSSID 84:b2:61:12:64:9f SSID '\x00' due to wpa_bss_flush_by_age,
07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 19 BSSID 84:b2:61:12:64:9b SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 9 BSSID e4:aa:5d:fc:5b:f0 SSID '\x00' due to wpa_bss_flush_by_age,
,07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 10 BSSID 00:fe:c8:73:02:04 SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 11 BSSID 00:fe:c8:73:02:02 SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 12 BSSID 00:fe:c8:73:02:00 SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 20 BSSID 84:b2:61:21:47:52 SSID '\x00' due to wpa_bss_flush_by_age
,07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 5 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
,07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 13 BSSID 84:b2:61:21:47:53 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 21 BSSID 84:b2:61:12:64:93 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 6 BSSID 00:fe:c8:73:02:03 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
07-05 12:53:14.381  1356  1356 D wpa_supplicant: wlan0: BSS: Remove id 14 BSSID e4:aa:5d:fc:5b:f3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
07-05 12:53:14.381   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 f0:f2:6d:22:99:3e]
07-05 12:53:14.381   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 f0:f2:6d:22:99:3e
,07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 84:b2:61:1a:ce:7f]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 15 84:b2:61:1a:ce:7f
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 16 84:b2:61:1a:ce:7b]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-BSS-REMOVED 16 84:b2:61:1a:ce:7b
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1
,07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 84:b2:61:1a:ce:74]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 84:b2:61:1a:ce:74
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 84:b2:61:1a:ce:72]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=66 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 84:b2:61:1a:ce:72
,07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:16:a6:1f:06:5c]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=67 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:16:a6:1f:06:5c
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 22 84:b2:61:1a:ce:70]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=68 dispatchEvent: CTRL-EVENT-BSS-REMOVED 22 84:b2:61:1a:ce:70
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 17 00:16:a6:1e:e0:a4]
,07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=69 dispatchEvent: CTRL-EVENT-BSS-REMOVED 17 00:16:a6:1e:e0:a4
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 18 84:b2:61:12:64:9f]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=70 dispatchEvent: CTRL-EVENT-BSS-REMOVED 18 84:b2:61:12:64:9f
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 19 84:b2:61:12:64:9b]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=71 dispatchEvent: CTRL-EVENT-BSS-REMOVED 19 84:b2:61:12:64:9b
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 e4:aa:5d:fc:5b:f0]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=72 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 e4:aa:5d:fc:5b:f0
,07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:fe:c8:73:02:04]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=73 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:fe:c8:73:02:04
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:fe:c8:73:02:02]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=74 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:fe:c8:73:02:02
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:fe:c8:73:02:00]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=75 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:fe:c8:73:02:00,
07-05 12:53:14.391   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 20 84:b2:61:21:47:52]
07-05 12:53:14.391   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=76 dispatchEvent: CTRL-EVENT-BSS-REMOVED 20 84:b2:61:21:47:52
07-05 12:53:14.411   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 84:b2:61:1a:ce:73]
07-05 12:53:14.411   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=77 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 84:b2:61:1a:ce:73
07-05 12:53:14.411   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 84:b2:61:21:47:53]
,07-05 12:53:14.411   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=78 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 84:b2:61:21:47:53
07-05 12:53:14.411   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 21 84:b2:61:12:64:93]
07-05 12:53:14.411   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=79 dispatchEvent: CTRL-EVENT-BSS-REMOVED 21 84:b2:61:12:64:93
07-05 12:53:14.411   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:fe:c8:73:02:03]
07-05 12:53:14.411   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=80 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:fe:c8:73:02:03
,07-05 12:53:14.411   904  1565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 e4:aa:5d:fc:5b:f3]
07-05 12:53:14.411   904  1565 E WifiMonitor: WifiMonitor:wlan0 cnt=81 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 e4:aa:5d:fc:5b:f3
,07-05 12:53:56.581   904   919 D PMS     : acquireWL(1db5cd82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:53:56.611   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:53:56.581   904   919 I BatteryService: n_update end
07-05 12:53:56.611   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:53:56.601  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:53:56.611   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:53:56.611   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:53:56.611   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:53:56.611  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,07-05 12:53:56.611   904  1080 D WifiController: battery changed pluggedType: 2
07-05 12:53:56.611  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:53:56.611  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:53:56.621  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:53:56.621   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:53:56.621  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 12:53:56.621   904   904 D PMS     : runPSCheck
07-05 12:53:56.621  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
07-05 12:53:56.621   904   904 D HtcPowerSaver: Checking...
07-05 12:53:56.621   904   904 I HtcPowerSaver: >> updateStatus
07-05 12:53:56.631   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:53:56.631   904   904 I HtcPowerSaver: << updateStatus
07-05 12:53:56.631   904   919 D PMS     : releaseWL(1db5cd82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:53:56.631  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,07-05 12:53:56.661  6954  6954 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
07-05 12:53:56.671  6954  6954 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
07-05 12:53:56.661  6954  6954 D         : Cust_ConnectToPC   : Internet_Sharing>true
07-05 12:53:56.671  6954  6954 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
07-05 12:53:56.661  6954  6954 D         : Cust_ConnectToPC   : Modem_Link>false
07-05 12:53:56.661  6954  6954 D         : Cust_ConnectToPC   : spcsc>false
07-05 12:53:56.661  6954  6954 D         : Cust_ConnectToPC   : IPT>true
07-05 12:53:56.661  6954  6954 D         : Cust_ConnectToPC   : Singel_USB>false,
07-05 12:53:56.661  6954  6954 D SmartNS_NSReceiver: project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
07-05 12:53:56.661  6954  6954 D SmartNS_NSReceiver: Index of the first 1 = 3
07-05 12:53:56.661  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-05 12:53:56.671  6954  6954 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 12:53:56.671  6954  6954 E SmartNS_Utility: hasRemovableStorageSlot: true,
07-05 12:53:56.681  6954  6954 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
07-05 12:53:56.681  6954  6954 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,07-05 12:53:56.681  6954  6954 D SmartNS_Utility: [ACC]android_networking:tethering_guard_support=false,
07-05 12:53:56.681  6954  6954 W SystemReader: Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,07-05 12:53:58.471   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,07-05 12:54:08.471   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 12:54:13.851   904  1068 D PMS     : acquireWL(315194d0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 904 1000 WorkSource{1000},
07-05 12:54:13.851   904  1068 V AlarmManager: sending alarm PendingIntent{353c8f72: PendingIntentRecord{2a9ffc3 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=227195, Int=0
07-05 12:54:13.861   904  1068 V AlarmManager: sending alarm PendingIntent{2d773fce: PendingIntentRecord{188b1eef com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1467716053854, Int=0
07-05 12:54:13.941   904   904 D PMS     : releaseWL(315194d0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,07-05 12:54:13.951  1122  2268 D WeatherUtility: Weather sync is On,
,07-05 12:54:14.071  1122  2268 I art     : Explicit concurrent mark sweep GC freed 4632(212KB) AllocSpace objects, 8(480KB) LOS objects, 39% free, 9MB/16MB, paused 507us total 31.989ms,
,07-05 12:54:14.101  1122  2268 D WeatherUtility: Weather sync is On,
,07-05 12:54:23.471   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,07-05 12:54:24.101  1782  1782 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:54:24.201  1782  2130 I art     : Explicit concurrent mark sweep GC freed 37736(2MB) AllocSpace objects, 6(444KB) LOS objects, 47% free, 4MB/8MB, paused 1.167ms total 71.163ms,
,07-05 12:54:24.221  1782  1875 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
07-05 12:54:24.221  1782  1875 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:54:24.221  1782  1875 I GLSUser : [GLSUser] Extracting token using key: Auth
07-05 12:54:24.221  1782  1875 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-05 12:54:24.231  1782  1875 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 12:54:24.271  1202  1688 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
07-05 12:54:24.271  1202  1688 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
07-05 12:54:24.281  1122  1122 I RemoteViews: reapply : com.google.android.gms 2 40
07-05 12:54:24.281  1782  1875 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
07-05 12:54:24.281  1782  1875 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
07-05 12:54:24.281  1782  1875 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
07-05 12:54:24.281  1782  1875 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
07-05 12:54:24.281  1782  1875 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
07-05 12:54:24.281  1782  1875 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 12:54:24.281  1782  1875 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:454)
,07-05 12:54:24.291  6080  6115 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 12:54:24.291  6080  6115 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 12:54:24.291  6080  6115 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
07-05 12:54:24.291  6080  6115 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144),
07-05 12:54:24.291  6080  6115 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
07-05 12:54:24.291  6080  6115 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 12:54:24.291  6080  6115 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:454)
,07-05 12:54:24.331  6080  6115 W System  : Ignoring header User-Agent because its value was null.,
07-05 12:54:24.331  6080  6115 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
07-05 12:54:24.331  6080  6115 D libc    : [NET] android_getaddrinfofornet-, err=8,
07-05 12:54:24.331  6080  6115 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-05 12:54:24.331  6080  6115 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 12:54:24.331  6080  6115 D libc    : [NET] android_getaddrinfo_proxy+,
07-05 12:54:24.331  6080  6115 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-05 12:54:24.341   461  7275 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
,07-05 12:54:24.341   461  7275 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
07-05 12:54:24.341   461  7275 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-05 12:54:24.341   461  7275 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,07-05 12:54:24.341  6080  6115 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 12:54:43.481   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,07-05 12:54:56.741   904  1611 D PMS     : acquireWL(26549a39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null
07-05 12:54:56.741   904  1611 I BatteryService: n_update end,
07-05 12:54:56.761   904  1611 D PMS     : releaseWL(26549a39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:55:08.481   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,07-05 12:55:56.901   904  1305 D PMS     : acquireWL(1a19387e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:55:56.901   904  1305 I BatteryService: n_update end
07-05 12:55:56.921  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:55:56.921  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:55:56.921  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:55:56.921  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 12:55:56.931  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:55:56.931   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:55:56.931   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:55:56.931   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:55:56.931   904  1080 D WifiController: battery changed pluggedType: 2
,07-05 12:55:56.931   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:55:56.931   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:55:56.931   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:55:56.931   904   904 D PMS     : runPSCheck
07-05 12:55:56.931  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:55:56.931   904   904 D HtcPowerSaver: Checking...
07-05 12:55:56.931  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:55:56.931   904   904 I HtcPowerSaver: >> updateStatus
,07-05 12:55:56.941   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:55:56.941   904   904 I HtcPowerSaver: << updateStatus
07-05 12:55:56.941   904  1305 D PMS     : releaseWL(1a19387e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:55:56.981  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:55:58.491   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,07-05 12:56:08.491   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,07-05 12:56:23.501   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,07-05 12:56:43.501   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,07-05 12:56:57.051   904  1617 D PMS     : acquireWL(3b67a1df): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:56:57.081  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:56:57.061   904  1617 I BatteryService: n_update end
07-05 12:56:57.081  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:56:57.081  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 12:56:57.081   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:56:57.091   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:56:57.091  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:56:57.091   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:56:57.101   904  1080 D WifiController: battery changed pluggedType: 2
,07-05 12:56:57.091   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:56:57.101  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:56:57.091   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:56:57.111   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:56:57.101  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 12:56:57.111   904   904 D PMS     : runPSCheck
07-05 12:56:57.111  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:56:57.111   904   904 D HtcPowerSaver: Checking...,
07-05 12:56:57.111   904   904 I HtcPowerSaver: >> updateStatus
07-05 12:56:57.111   904  1617 D PMS     : releaseWL(3b67a1df): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:56:57.111   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:56:57.111   904   904 I HtcPowerSaver: << updateStatus
,07-05 12:56:57.151  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:57:08.511   481   481 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,07-05 12:57:57.231   904  1269 D PMS     : acquireWL(2fec0e2c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:57:57.251   904  1269 I BatteryService: n_update end
07-05 12:57:57.271   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:57:57.271   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:57:57.271   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:57:57.271   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:57:57.271   904  1080 D WifiController: battery changed pluggedType: 2
07-05 12:57:57.271   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:57:57.281  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:57:57.281  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,07-05 12:57:57.281  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:57:57.281  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:57:57.291   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:57:57.281  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:57:57.291   904   904 D PMS     : runPSCheck
07-05 12:57:57.281  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
07-05 12:57:57.291   904   904 D HtcPowerSaver: Checking...,
07-05 12:57:57.281  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
07-05 12:57:57.291   904   904 I HtcPowerSaver: >> updateStatus
07-05 12:57:57.311   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:57:57.311   904   904 I HtcPowerSaver: << updateStatus
07-05 12:57:57.311   904  1269 D PMS     : releaseWL(2fec0e2c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 12:57:57.331  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:58:19.951   367   390 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,07-05 12:58:36.491  1422  1580 D ContactMessageStore: MSG_CHECK_DELETION >>,
,07-05 12:58:36.491  1422  1580 D ContactMessageStore: mDeleteTask = null, bDeleting = false
,07-05 12:58:36.501  1422  1580 D AccFlag : sku_id=99,
,07-05 12:58:36.501  1422  1580 D ContactMessageStore: MSG_CHECK_DELETION <<
,07-05 12:58:36.511  1422  7277 D ContactMessageStore: start background delete task...,
,07-05 12:58:36.521  1422  7277 D ContactMessageStore: size: 0 , 0,
,07-05 12:58:36.521  1422  7277 D ContactMessageStore: Background delete complete
,07-05 12:58:57.401   904  1611 D PMS     : acquireWL(35dba0f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 12:58:57.421   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:58:57.421   904  1611 I BatteryService: n_update end
07-05 12:58:57.421   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:58:57.421   904   904 D NotificationService: plugged=true pluggin=true
07-05 12:58:57.421   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
07-05 12:58:57.431  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:58:57.431  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:58:57.431  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:58:57.431  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
07-05 12:58:57.431   904  1080 D WifiController: battery changed pluggedType: 2
07-05 12:58:57.431  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:58:57.441   904  1012 D HtcPowerSaver: updateBatteryInfo,
07-05 12:58:57.431  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:58:57.441   904   904 D PMS     : runPSCheck
07-05 12:58:57.431  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,07-05 12:58:57.441   904   904 D HtcPowerSaver: Checking...
07-05 12:58:57.431   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:58:57.441   904   904 I HtcPowerSaver: >> updateStatus
07-05 12:58:57.441   904  1611 D PMS     : releaseWL(35dba0f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,07-05 12:58:57.451   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:58:57.451   904   904 I HtcPowerSaver: << updateStatus
,07-05 12:58:57.481  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 12:59:57.531  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
07-05 12:59:57.531   904  1607 D PMS     : acquireWL(c0c5e8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null
07-05 12:59:57.531  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:59:57.531   904  1607 I BatteryService: n_update end
07-05 12:59:57.531  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 12:59:57.531   904  1607 D PMS     : releaseWL(c0c5e8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 12:59:57.531  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 12:59:57.531  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 12:59:57.531  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 12:59:57.531   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 12:59:57.531   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 12:59:57.531   904   904 D NotificationService: plugged=true pluggin=true
,07-05 12:59:57.531   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 12:59:57.531   904   904 D PMS     : runPSCheck
07-05 12:59:57.531   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 12:59:57.541   904  1080 D WifiController: battery changed pluggedType: 2
07-05 12:59:57.531   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 12:59:57.541  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 12:59:57.541   904   904 D HtcPowerSaver: Checking...
07-05 12:59:57.541   904   904 I HtcPowerSaver: >> updateStatus
07-05 12:59:57.541   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 12:59:57.541   904   904 I HtcPowerSaver: << updateStatus
,07-05 12:59:57.581  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:00:57.711   904  1527 D PMS     : acquireWL(ece7cfb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:00:57.721   904  1527 I BatteryService: n_update end
07-05 13:00:57.751  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:00:57.751  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:00:57.751  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:00:57.751  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:00:57.751   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:00:57.751   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:00:57.761   904  1080 D WifiController: battery changed pluggedType: 2
,07-05 13:00:57.751   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 13:00:57.761  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:00:57.751   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:00:57.771   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:00:57.751   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 13:00:57.771   904   904 D PMS     : runPSCheck
07-05 13:00:57.761  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:00:57.771   904   904 D HtcPowerSaver: Checking...
,07-05 13:00:57.761  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:00:57.771   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:00:57.771   904  1527 D PMS     : releaseWL(ece7cfb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 13:00:57.771   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:00:57.771   904   904 I HtcPowerSaver: << updateStatus
,07-05 13:00:57.811  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:01:57.871   904  1089 D PMS     : acquireWL(1d21e118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:01:57.871   904  1089 I BatteryService: n_update end
07-05 13:01:57.901  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:01:57.901  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:01:57.901  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:01:57.901  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:01:57.901  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:01:57.901   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:01:57.901   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:01:57.901   904   904 D UsbnetService: onReceive BATTERY_CHANGED
,07-05 13:01:57.901   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:01:57.901   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:01:57.911   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:01:57.901   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 13:01:57.911   904   904 D PMS     : runPSCheck
07-05 13:01:57.901  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:01:57.911   904   904 D HtcPowerSaver: Checking...
,07-05 13:01:57.911  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:01:57.911   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:01:57.921   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:01:57.921   904   904 I HtcPowerSaver: << updateStatus
07-05 13:01:57.921   904  1089 D PMS     : releaseWL(1d21e118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 13:01:57.951  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:02:58.021   904  1478 D PMS     : acquireWL(2a925771): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:02:58.041   904  1478 I BatteryService: n_update end
07-05 13:02:58.051  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:02:58.051  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:02:58.051  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:02:58.051  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,07-05 13:02:58.051   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:02:58.051  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:02:58.051   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:02:58.051   904   904 D UsbnetService: BroadcastReceiver::onReceive+,
07-05 13:02:58.061  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:02:58.051   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 13:02:58.061   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:02:58.051   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:02:58.061   904   904 D PMS     : runPSCheck
07-05 13:02:58.051   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 13:02:58.061   904   904 D HtcPowerSaver: Checking...
,07-05 13:02:58.061  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:02:58.061   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:02:58.071   904  1478 D PMS     : releaseWL(2a925771): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 13:02:58.071   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:02:58.071   904   904 I HtcPowerSaver: << updateStatus
,07-05 13:02:58.101  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:03:58.191   904  1612 D PMS     : acquireWL(959d956): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:03:58.201   904  1612 I BatteryService: n_update end
07-05 13:03:58.221  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:03:58.221  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:03:58.221  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:03:58.221  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:03:58.221  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:03:58.221  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:03:58.221   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:03:58.221  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,07-05 13:03:58.221   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:03:58.221   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:03:58.221   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:03:58.221   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 13:03:58.221   904   904 D PMS     : runPSCheck
07-05 13:03:58.221   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:03:58.221   904   904 D HtcPowerSaver: Checking...
07-05 13:03:58.221   904   904 D UsbnetService: BroadcastReceiver::onReceive-
,07-05 13:03:58.221   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:03:58.231   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:03:58.231   904   904 I HtcPowerSaver: << updateStatus
07-05 13:03:58.231   904  1612 D PMS     : releaseWL(959d956): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 13:03:58.271  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:04:19.481   904  1068 D PMS     : acquireWL(9fdedd7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 904 1000 WorkSource{1000},
,07-05 13:04:19.491   904  1068 V AlarmManager: sending alarm PendingIntent{353c8f72: PendingIntentRecord{2a9ffc3 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=407196, Int=0
07-05 13:04:19.491   904  1068 V AlarmManager: sending alarm PendingIntent{ec97db: PendingIntentRecord{9639278 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=800844, Int=0,
07-05 13:04:19.491   904  1068 V AlarmManager: sending alarm PendingIntent{2adff6c4: PendingIntentRecord{1e23f9ad com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=930483, Int=0
,07-05 13:04:19.591   904  1068 I ActivityManager: Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=7281 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
07-05 13:04:19.591   904  1068 V AlarmManager: sending alarm PendingIntent{143234e2: PendingIntentRecord{2e499073 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1467716407973, Int=0
07-05 13:04:19.591   904  1068 V AlarmManager: sending alarm PendingIntent{b47bb30: PendingIntentRecord{1e4f868a com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1467716659491, Int=0,
07-05 13:04:19.601   904   920 D PMS     : acquireWL(1fb383a9): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
07-05 13:04:19.661  1782  2907 D GCM     : Message class com.google.f.a.a.i
07-05 13:04:19.621   904  1613 D PMS     : releaseWL(1fb383a9): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10025 com.google.android.gms}
07-05 13:04:19.631  6761  6761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
07-05 13:04:19.661   904   904 D PMS     : releaseWL(9fdedd7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
07-05 13:04:19.661   904  1269 D PMS     : acquireWL(34a2c0cf): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
07-05 13:04:19.661   904  1478 D PMS     : releaseWL(34a2c0cf): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10025 com.google.android.gms},
07-05 13:04:19.671  6761  7303 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,07-05 13:04:19.671  6761  7303 D PowerUsageService: repeat time = 1467717559678,
,07-05 13:04:19.671   904  1527 W BatSI   : Couldn't get kernel wake lock stats
07-05 13:04:19.681  1122  2268 D WeatherUtility: Weather sync is On
,07-05 13:04:19.741  7316  7316 E cutils-trace: Error opening trace file: No such file or directory (2)
07-05 13:04:19.741  7316  7316 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=21 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-05 13:04:19.761  6761  7303 D PowerUsageList:PowerUsageHelper: [CMD_CURRENT_TIME] rec.currentTime < startCurTime, impossible,
,07-05 13:04:19.761   904  1305 W BatSI   : Couldn't get kernel wake lock stats
,07-05 13:04:19.811  1122  2268 D WeatherUtility: Weather sync is On
,07-05 13:04:19.831  6761  7303 I PowerUsageList:PowerUsageHelper: PowerProfile::POWER_SCREEN_FULL = 154.8,
,07-05 13:04:19.921  6761  7303 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-05 13:04:20.021  6761  7303 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,07-05 13:04:20.041  6761  7303 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-05 13:04:20.371  7316  7316 I dex2oat : dex2oat took 626.472ms (threads: 4),
,07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): VersionName:             1.2.848061
,07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): VersionCode:             148001212
07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,07-05 13:04:20.381  7281  7281 I PushClient: ApplicationMonitor {3ee32880}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,07-05 13:04:20.381  7281  7325 I PushClient: PnsModel {16c42103}: update(): Update registration caused by: alarm,
,07-05 13:04:20.391  7281  7325 I PushClient: PnsConfigModel {1f4a23d6}: <init>(): Use dm-client for provisioning.,
,07-05 13:04:20.401  7281  7325 W System.err: SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
07-05 13:04:20.401  7281  7325 W System.err: SLF4J: Defaulting to no-operation (NOP) logger implementation
07-05 13:04:20.401  7281  7325 W System.err: SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,07-05 13:04:20.411  7281  7325 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,07-05 13:04:20.441   904   919 I ActivityManager: Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7327 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
,07-05 13:04:20.491  7327  7327 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=7327 dbg=false s=true,
,07-05 13:04:20.491  7327  7343 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,07-05 13:04:20.491  7327  7343 I DeviceManagement: ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10074) packages=[com.htc.cs.pns]
,07-05 13:04:20.491  7327  7345 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,07-05 13:04:20.501  7327  7327 I DeviceManagement: WorkflowService: Starting workflow service,
,07-05 13:04:20.501  7327  7347 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@16c42103] args=[Bundle[mParcelledData.dataSize=88]]
,07-05 13:04:20.501  7327  7347 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,07-05 13:04:20.501  7327  7347 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,07-05 13:04:20.521  7327  7347 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,07-05 13:04:20.531  7327  7348 I DeviceManagement: SessionStateController: Checking invariants...
,07-05 13:04:20.711  7327  7348 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,07-05 13:04:20.781  7327  7347 I DeviceManagement: SessionStateController: Checking invariants...
,07-05 13:04:20.841  7327  7347 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,07-05 13:04:20.841  7327  7347 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@16c42103]
,07-05 13:04:20.871  7327  7327 I DeviceManagement: WorkflowService: Stopping workflow service,
,07-05 13:04:20.871   904  1527 D Process : killProcessQuiet, pid=6680,
07-05 13:04:20.871   904  1527 I ActivityManager: Killing 6680:com.google.android.setupwizard/u0a80 (adj 15): empty #17
07-05 13:04:20.871   904  1527 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,07-05 13:04:20.881   904  1607 I ActivityManager: Recipient 6680,
,07-05 13:04:20.921   904  1607 D Process : killProcessQuiet, pid=6680,
07-05 13:04:20.921   904  1607 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-05 13:04:20.921   904  1607 W libprocessgroup: failed to open /acct/uid_10080/pid_6680/cgroup.procs: No such file or directory
,07-05 13:04:20.931  7281  7325 I PushClient: PnsModel {16c42103}: update(): Start updating since the registration has expired.,
,07-05 13:04:20.941  7281  7325 W PushClient: GCMRegistrator {2fca0361}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.
07-05 13:04:20.941  7281  7325 W PushClient:   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
07-05 13:04:20.941  7281  7325 W PushClient:   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
,07-05 13:04:20.941  7281  7325 W PushClient:   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
07-05 13:04:20.941  7281  7325 W PushClient:   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:237)
07-05 13:04:20.941  7281  7325 W PushClient:   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:375)
07-05 13:04:20.941  7281  7325 W PushClient:   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:55)
07-05 13:04:20.941  7281  7325 W PushClient:   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-05 13:04:20.941  7281  7325 W PushClient:   	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:04:20.941  7281  7325 W PushClient:   	at android.os.Looper.loop(Looper.java:155)
07-05 13:04:20.941  7281  7325 W PushClient:   	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:04:20.941  7281  7325 W PushClient:   
,07-05 13:04:20.961  1782  2841 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-05 13:04:20.971  1782  2841 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 13:04:20.971  1782  2841 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 13:04:20.971  1782  2841 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-05 13:04:20.971  1782  2841 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 13:04:20.971  1782  2841 D libc    : [NET] android_getaddrinfo_proxy+
,07-05 13:04:20.971  1782  2841 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-05 13:04:20.971   461  7360 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-05 13:04:20.971   461  7360 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-05 13:04:21.011   461  7360 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
07-05 13:04:21.011   461  7360 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-05 13:04:21.011  1782  2841 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 13:04:21.081  1782  2841 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 13:04:21.081  1782  2841 D libc    : [NET] android_getaddrinfofornet-, err=8,
,07-05 13:04:21.211  1782  2841 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 13:04:21.211  1782  2841 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 13:04:21.211  1782  2841 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 13:04:21.211  1782  2841 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 13:04:21.361  7281  7364 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 4,
07-05 13:04:21.361  7281  7364 D libc    : [NET] android_getaddrinfofornet-, err=8,
,07-05 13:04:21.361  7281  7364 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024,
07-05 13:04:21.361  7281  7364 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,07-05 13:04:21.361  7281  7364 D libc    : [NET] android_getaddrinfo_proxy+
,07-05 13:04:21.361  7281  7364 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
,07-05 13:04:21.371   461  7366 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x706e732e687463),sn(),hints(known),family 0,flags 1024,
07-05 13:04:21.371   461  7366 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,07-05 13:04:21.411   461  7366 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
07-05 13:04:21.411   461  7366 D libc    : [NET] android_getaddrinfofornet-, SUCCESS,
,07-05 13:04:21.421  7281  7364 D libc    : [NET] android_getaddrinfo_proxy-, success,
,07-05 13:04:21.961  7281  7325 I PushClient: PnsModel {16c42103}: update(): Update registration succeeded.,
,07-05 13:04:21.971   904  1611 D Process : killProcessQuiet, pid=6587,
07-05 13:04:21.971   904  1611 I ActivityManager: Killing 6587:com.google.android.gms.unstable/u0a25 (adj 15): empty #17
07-05 13:04:21.971   904  1611 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,07-05 13:04:21.991   904  1613 I ActivityManager: Recipient 6587,
,07-05 13:04:22.001   904  1613 D Process : killProcessQuiet, pid=6587,
07-05 13:04:22.001   904  1613 W libprocessgroup: failed to open /acct/uid_10025/pid_6587/cgroup.procs: No such file or directory
07-05 13:04:22.001   904  1613 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,07-05 13:04:58.341   904  1305 D PMS     : acquireWL(2b22128c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:04:58.341   904  1305 I BatteryService: n_update end
07-05 13:04:58.361   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:04:58.361   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 13:04:58.361   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:04:58.361   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:04:58.361   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:04:58.361   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 13:04:58.371  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:04:58.371  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:04:58.371  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
07-05 13:04:58.371  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:04:58.371   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:04:58.371  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:04:58.371   904   904 D PMS     : runPSCheck
07-05 13:04:58.371  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:04:58.371   904   904 D HtcPowerSaver: Checking...
07-05 13:04:58.371  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:04:58.371   904   904 I HtcPowerSaver: >> updateStatus
,07-05 13:04:58.381   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:04:58.381   904   904 I HtcPowerSaver: << updateStatus
07-05 13:04:58.381   904  1305 D PMS     : releaseWL(2b22128c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 13:04:58.421  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:05:11.121   904  1068 D PMS     : acquireWL(2370bdd5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 904 1000 WorkSource{1000},
,07-05 13:05:11.121   904  1068 V AlarmManager: sending alarm PendingIntent{353c8f72: PendingIntentRecord{2a9ffc3 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1007195, Int=0
07-05 13:05:11.171  6761  6761 D SmartSyncUtils: isEpsOn(), nState = 0
07-05 13:05:11.131   904  1068 V AlarmManager: sending alarm PendingIntent{1895e9ea: PendingIntentRecord{3a1614db com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1467716711124, Int=0
07-05 13:05:11.181   904   904 D PMS     : releaseWL(2370bdd5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,07-05 13:05:11.191   904  1612 D PMS     : acquireWL(3223cb78): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6761 1000 null,
07-05 13:05:11.191  1122  2268 D WeatherUtility: Weather sync is On
,07-05 13:05:11.201  6761  7369 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false,
,07-05 13:05:11.211  6761  7369 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,07-05 13:05:11.231  6761  7369 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1,
07-05 13:05:11.231  6761  7369 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1467781200000, randomSettingOnTime = 1467779496000
,07-05 13:05:11.231  6761  7369 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1467759600000, randomSettingOffTime = 1467763853000
,07-05 13:05:11.241  6761  7369 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false,
,07-05 13:05:11.241  6761  7369 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true,
,07-05 13:05:11.251  6761  7369 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false,
,07-05 13:05:11.251   904  1527 D PMS     : releaseWL(3223cb78): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,07-05 13:05:11.301  1122  2268 D WeatherUtility: Weather sync is On
,07-05 13:05:58.521   904  1617 D PMS     : acquireWL(180c6251): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:05:58.521   904  1617 I BatteryService: n_update end
07-05 13:05:58.531  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:05:58.531  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:05:58.531  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:05:58.531  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:05:58.541  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:05:58.531  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:05:58.541   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:05:58.531  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
07-05 13:05:58.541   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:05:58.541   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:05:58.541   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:05:58.541   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 13:05:58.541   904   904 D PMS     : runPSCheck
07-05 13:05:58.541   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:05:58.541   904   904 D HtcPowerSaver: Checking...
07-05 13:05:58.541   904   904 D UsbnetService: BroadcastReceiver::onReceive-
,07-05 13:05:58.541   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:05:58.551   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:05:58.551   904   904 I HtcPowerSaver: << updateStatus
07-05 13:05:58.551   904  1617 D PMS     : releaseWL(180c6251): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 13:05:58.581  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:06:58.641   904   920 D PMS     : acquireWL(1ee0bab6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:06:58.651   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:06:58.641   904   920 I BatteryService: n_update end
07-05 13:06:58.651   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 13:06:58.641   904   920 D PMS     : releaseWL(1ee0bab6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 13:06:58.651   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:06:58.651  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:06:58.651   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:06:58.651  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:06:58.651   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:06:58.651  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:06:58.651  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:06:58.651  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:06:58.651   904   904 D PMS     : runPSCheck
,07-05 13:06:58.651  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:06:58.651   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:06:58.651   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 13:06:58.651  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:06:58.651   904   904 D HtcPowerSaver: Checking...
07-05 13:06:58.651   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:06:58.661   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:06:58.661   904   904 I HtcPowerSaver: << updateStatus
,07-05 13:06:58.701  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:07:58.821   904  1527 D PMS     : acquireWL(3d5723b7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:07:58.841   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:07:58.821   904  1527 I BatteryService: n_update end
07-05 13:07:58.841  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:07:58.841   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:07:58.851  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,07-05 13:07:58.851  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:07:58.851  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:07:58.851  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:07:58.851  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,07-05 13:07:58.851  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:07:58.851   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:07:58.851   904   904 D UsbnetService: onReceive BATTERY_CHANGED
,07-05 13:07:58.861   904  1012 D HtcPowerSaver: updateBatteryInfo
,07-05 13:07:58.851   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:07:58.861   904   904 D PMS     : runPSCheck
,07-05 13:07:58.851   904   904 D UsbnetService: BroadcastReceiver::onReceive-
,07-05 13:07:58.861   904   904 D HtcPowerSaver: Checking...
07-05 13:07:58.861   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:07:58.861   904  1527 D PMS     : releaseWL(3d5723b7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 13:07:58.871   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,07-05 13:07:58.871   904   904 I HtcPowerSaver: << updateStatus
,07-05 13:07:58.901  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:08:19.951   367   390 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,07-05 13:08:32.521   904  1000 I UsageStatsService: User[0] Flushing usage stats to disk,
,07-05 13:08:58.971   904  1612 D PMS     : acquireWL(1862724): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:08:58.971   904  1612 I BatteryService: n_update end
07-05 13:08:58.971   904  1612 D PMS     : releaseWL(1862724): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 13:10:59.291   904  1607 D PMS     : acquireWL(2fe3d28d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:10:59.301  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:10:59.291   904  1607 I BatteryService: n_update end
07-05 13:10:59.311  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:10:59.301  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:10:59.311  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
07-05 13:10:59.311  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:10:59.311   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:10:59.311  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:10:59.311   904  1080 D WifiController: battery changed pluggedType: 2,
07-05 13:10:59.311   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:10:59.311  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:10:59.311   904   904 D UsbnetService: onReceive BATTERY_CHANGED,
07-05 13:10:59.311   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:10:59.311   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:10:59.311   904   904 D PMS     : runPSCheck
,07-05 13:10:59.311   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 13:10:59.311   904   904 D HtcPowerSaver: Checking...
07-05 13:10:59.321   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:10:59.321   904  1607 D PMS     : releaseWL(2fe3d28d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,07-05 13:10:59.321   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:10:59.321   904   904 I HtcPowerSaver: << updateStatus
,07-05 13:10:59.361  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:11:59.471   904   920 D PMS     : acquireWL(3435cc42): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:11:59.491   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:11:59.471   904   920 I BatteryService: n_update end
07-05 13:11:59.491   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 13:11:59.491   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:11:59.491   904   904 D NotificationService: plugged=true pluggin=true
07-05 13:11:59.491   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 13:11:59.501   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:11:59.501  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:11:59.501  1122  1122 D PowerUI : closing low battery warning: level=100
,07-05 13:11:59.501  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:11:59.501  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:11:59.501  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:11:59.501   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:11:59.501  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:11:59.501   904   904 D PMS     : runPSCheck
07-05 13:11:59.501  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:11:59.501   904   904 D HtcPowerSaver: Checking...,
07-05 13:11:59.501   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:11:59.511   904   920 D PMS     : releaseWL(3435cc42): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 13:11:59.511   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:11:59.511   904   904 I HtcPowerSaver: << updateStatus
,07-05 13:11:59.551  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,07-05 13:12:59.621   904   919 D PMS     : acquireWL(1c304453): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 904 1000 null,
07-05 13:12:59.661  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:12:59.641   904   919 I BatteryService: n_update end
07-05 13:12:59.661  3155  3238 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 13:12:59.661  1122  1300 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-05 13:12:59.661  1122  1122 D PowerUI : closing low battery warning: level=100
07-05 13:12:59.661  1202  1202 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-05 13:12:59.661   904   904 D NotificationService: plugged=true pluggin=true,
07-05 13:12:59.661  1202  1202 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-05 13:12:59.661   904  1080 D WifiController: battery changed pluggedType: 2
07-05 13:12:59.661   904   904 D UsbnetService: BroadcastReceiver::onReceive+
07-05 13:12:59.661  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-05 13:12:59.661   904   904 D UsbnetService: onReceive BATTERY_CHANGED
07-05 13:12:59.661   904  1012 D HtcPowerSaver: updateBatteryInfo
07-05 13:12:59.661   904   904 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-05 13:12:59.661   904   904 D PMS     : runPSCheck
,07-05 13:12:59.661   904   904 D UsbnetService: BroadcastReceiver::onReceive-
07-05 13:12:59.671   904   904 D HtcPowerSaver: Checking...
07-05 13:12:59.671   904   904 I HtcPowerSaver: >> updateStatus
07-05 13:12:59.671   904   919 D PMS     : releaseWL(1c304453): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-05 13:12:59.671   904   904 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
07-05 13:12:59.671   904   904 I HtcPowerSaver: << updateStatus
,07-05 13:12:59.711  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,TIME-OUT KILL (timeout was 1400000ms),07-05 13:13:55.641  7400  7410 E cutils-trace: Error opening trace file: No such file or directory (2)
07-05 13:13:55.681  7400  7400 D CustomizationManager: ====startRecUseTime====
07-05 13:13:55.681  7400  7400 D htc.customization.log.level:  is 
07-05 13:13:55.681  7400  7400 W CustomizationLogLevel: Level value is invalid, use default level 2
07-05 13:13:55.771  7400  7400 D CustomizationManager:  Read ACC file spent 0.050 (s)
07-05 13:13:55.771  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__001
07-05 13:13:55.771  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-05 13:13:55.771  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__102
07-05 13:13:55.771  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__203
07-05 13:13:55.771  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__405
07-05 13:13:55.771  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-05 13:13:55.771  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__304
07-05 13:13:55.771  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-05 13:13:55.781  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__032
07-05 13:13:55.781  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-05 13:13:55.781  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__016
07-05 13:13:55.781  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-05 13:13:55.781  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__A48
07-05 13:13:55.781  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__K18
07-05 13:13:55.781  7400  7400 D CIDMapFileReader: Parsing tag item name = HTC__002
07-05 13:13:55.781  7400  7400 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
07-05 13:13:55.781  7400  7400 I CustomizationCIDLoader: Parsing tag category name = system
07-05 13:13:55.781  7400  7400 I CustomizationCIDLoader: Parsing tag category name = application
07-05 13:13:55.781  7400  7400 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-05 13:13:55.781  7400  7400 I CustomizationCIDLoader: Parsing tag category name = Settings
07-05 13:13:55.781  7400  7400 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-05 13:13:55.781  7400  7400 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-05 13:13:55.781  7400  7400 I CustomizationCIDLoader: Parsing tag category name = ACC
07-05 13:13:55.781  7400  7400 D CustomizationManager:  Read CID file spent 0.101 (s)
07-05 13:13:55.781  7400  7400 D CustomizationManager:  All configurations done spent 0.101 (s)
07-05 13:13:55.801  7400  7400 E ActTriggerJNI: open library fail.
07-05 13:13:55.811   904  1305 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=7400, uid=2000 userid=0
07-05 13:13:55.821   904  1001 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=-1: uninstall pkg
07-05 13:13:55.821   904  1001 D Process : killProcessQuiet, pid=7083
07-05 13:13:55.821   904  1001 I ActivityManager: Killing 7083:com.test.thalitest/u0a192 (adj 0): stop com.test.thalitest
07-05 13:13:55.821   904  1001 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
07-05 13:13:55.871   904  1053 W PackageSettings: Skipping PackageSetting{30f03113 com.example.hello/10380} due to missing metadata
07-05 13:13:55.871   904  1617 I ActivityManager: Recipient 7083
07-05 13:13:55.871   904  1544 I WindowState: WIN DEATH: Window{2c48bf14 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-05 13:13:55.871   904  1080 D WifiService: Client connection lost with reason: 4
07-05 13:13:56.061   904  1001 I ActivityManager:   Force finishing activity ActivityRecord{6fb5fd9 u0 com.test.thalitest/.MainActivity t33}
07-05 13:13:56.071   904  1617 W ActivityManager: Spurious death for ProcessRecord{20909190 7083:com.test.thalitest/u0a192}, curProc for 7083: null
07-05 13:13:56.071   904  1053 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=0: pkg removed
07-05 13:13:56.081   904  1053 I ActivityManager:   Force finishing activity ActivityRecord{6fb5fd9 u0 com.test.thalitest/.MainActivity t33 f}
07-05 13:13:56.081   904  1053 W ActivityManager: Duplicate finish request for ActivityRecord{6fb5fd9 u0 com.test.thalitest/.MainActivity t33 f}
07-05 13:13:56.181  1483  1483 I art     : Explicit concurrent mark sweep GC freed 3041(151KB) AllocSpace objects, 3(239KB) LOS objects, 40% free, 18MB/31MB, paused 931us total 66.577ms
07-05 13:13:56.191  1483  1865 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-05 13:13:56.201  1422  1422 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 13:13:56.191  1483  1865 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-05 13:13:56.191  1202  1202 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-05 13:13:56.191  1202  1202 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-05 13:13:56.191  1202  1202 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
07-05 13:13:56.201  1483  1483 I Launcher: Deferring update until onResume
07-05 13:13:56.201  1483  1483 D Launcher: waitUntilResume // bindAppsRemoved
07-05 13:13:56.231  1587  2044 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-05 13:13:56.241  1422  1422 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-05 13:13:56.241  1587  2044 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-05 13:13:56.241   904  1077 V NetworkPolicy: ACTION_UID_REMOVED for uid=10192
07-05 13:13:56.241   904  1077 V NetworkPolicy: writePolicyLocked()
07-05 13:13:56.241  1571  7432 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-05 13:13:56.251  1483  1483 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
07-05 13:13:56.261  5978  5978 I art     : Explicit concurrent mark sweep GC freed 20108(1374KB) AllocSpace objects, 0(0B) LOS objects, 43% free, 2MB/4MB, paused 202us total 161.213ms
07-05 13:13:56.261  1587  2044 E ExternalAccountType: Unsupported attribute readOnly
07-05 13:13:56.271  1529  7434 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
07-05 13:13:56.281   904  1607 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
07-05 13:13:56.291  1529  7434 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-05 13:13:56.291   904   904 I art     : Explicit concurrent mark sweep GC freed 40466(2MB) AllocSpace objects, 12(834KB) LOS objects, 33% free, 17MB/25MB, paused 1.146ms total 145.053ms
07-05 13:13:56.291   904  1089 I art     : WaitForGcToComplete blocked for 79.265ms for cause Explicit
07-05 13:13:56.351   904   904 W PackageManager: Unable to load service info ResolveInfo{2baa65d8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-05 13:13:56.351   904   904 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-05 13:13:56.351   904   904 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
07-05 13:13:56.351   904   904 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
07-05 13:13:56.351   904   904 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-05 13:13:56.351   904   904 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-05 13:13:56.351   904   904 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-05 13:13:56.351   904   904 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-05 13:13:56.351   904   904 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 13:13:56.351   904   904 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 13:13:56.351   904   904 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-05 13:13:56.351   904   904 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-05 13:13:56.351   904   904 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-05 13:13:56.351   904   904 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 13:13:56.351   904   904 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 13:13:56.351   904   904 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
07-05 13:13:56.351   904   904 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
07-05 13:13:56.381   904  1089 I art     : Explicit concurrent mark sweep GC freed 6817(400KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 1.402ms total 89.916ms
07-05 13:13:56.381   904  1053 I art     : WaitForGcToComplete blocked for 136.839ms for cause Explicit
07-05 13:13:56.381   904  1089 D PMS     : acquireWL(a328b02): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1745 10025 WorkSource{10025 com.google.android.gms}
07-05 13:13:56.381   904  1076 D PMS     : acquireWL(257a4e50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
07-05 13:13:56.401   904  1618 D PMS     : releaseWL(a328b02): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
07-05 13:13:56.421   904   904 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 13:13:56.431   904  1102 D TaskPersister: removeObsoleteFile: deleting file=33_task.xml
07-05 13:13:56.431   904  1077 V NetworkPolicy: updateNetworkEnabledLocked()
07-05 13:13:56.431   904  1077 V NetworkPolicy: updateNotificationsLocked()
07-05 13:13:56.441   904  1005 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-05 13:13:56.441   904  1005 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 13:13:56.441   904  1005 D StatusBarManagerService: hiding MENU key
07-05 13:13:56.451   904  1005 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
07-05 13:13:56.451   904  1005 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 13:13:56.451   904  1005 D StatusBarManagerService: hiding MENU key
07-05 13:13:56.451   904  1076 D PMS     : releaseWL(257a4e50): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-05 13:13:56.451  7435  7435 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
07-05 13:13:56.461   904  1610 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7083 uid 10192
07-05 13:13:56.461   904  1610 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-05 13:13:56.471   904  1618 D Process : killProcessQuiet, pid=6734
07-05 13:13:56.471   904  1618 I ActivityManager: Killing 6734:com.htc.bgp/u0a11 (adj 15): empty #17
07-05 13:13:56.471   904  1618 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-05 13:13:56.481   904  1539 I ActivityManager: Recipient 6734
07-05 13:13:56.511   904  1053 I art     : Explicit concurrent mark sweep GC freed 8509(842KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 895us total 121.590ms
07-05 13:13:56.531   904  1539 D Process : killProcessQuiet, pid=6734
07-05 13:13:56.531   904  1539 W libprocessgroup: failed to open /acct/uid_10011/pid_6734/cgroup.procs: No such file or directory
07-05 13:13:56.531   904  1539 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-05 13:13:56.531  1782  1782 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-05 13:13:56.531  1782  1782 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-05 13:13:56.531   904  1544 D PMS     : acquireWL(1896d844): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1782 10025 WorkSource{10025 com.google.android.gms}
07-05 13:13:56.531   904   920 D PMS     : releaseWL(1896d844): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
07-05 13:13:56.541  2046  2046 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 13:13:56.541  2046  2046 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 13:13:56.541  2046  7462 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-05 13:13:56.551  2046  7462 D AccountUtils: Clearing selected account for com.test.thalitest
07-05 13:13:56.551  2046  2046 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-05 13:13:56.551  2046  2046 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-05 13:13:56.591   904  1613 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7466 uid=10107 gids={50107, 9997, 1028, 3003, 1015} abi=armeabi-v7a
07-05 13:13:56.591  5978  7465 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-05 13:13:56.651   904  1053 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7484 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=armeabi-v7a
07-05 13:13:56.661  2046  7462 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-05 13:13:56.671   904   919 D PMS     : acquireWL(29f45247): PARTIAL_WAKE_LOCK  Icing 0x1 2046 10025 WorkSource{10025 com.google.android.gms}
07-05 13:13:56.681   904  1000 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
07-05 13:13:56.691   904  1269 D PMS     : releaseWL(29f45247): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
07-05 13:13:56.691  2046  7503 W BaseAppContext: Using Auth Proxy for data requests.
07-05 13:13:56.701  2046  7503 W BaseAppContext: Using Auth Proxy for data requests.
07-05 13:13:56.701  1782  1782 I ConfigService: onCreate
07-05 13:13:56.701   904  1613 D PMS     : acquireWL(2e662036): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 2046 10025 null
07-05 13:13:56.701  2046  2046 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-05 13:13:56.701  2046  7501 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-05 13:13:56.701  2046  7501 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-05 13:13:56.701  2046  7501 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-05 13:13:56.701  2046  7501 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-05 13:13:56.711   904  1617 D PMS     : releaseWL(2e662036): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
07-05 13:13:56.711   904  1000 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-05 13:13:56.721  2046  7501 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-05 13:13:56.721  2046  7501 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-05 13:13:56.721  2046  7501 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-05 13:13:56.731  2046  7501 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-05 13:13:56.731  2046  7501 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-05 13:13:56.731  2046  7501 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-05 13:13:56.731  2046  7501 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
07-05 13:13:56.731  2046  7501 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
07-05 13:13:56.731  2046  7501 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
07-05 13:13:56.731   904  1305 D PMS     : acquireWL(3d60ed41): PARTIAL_WAKE_LOCK  Icing 0x1 2046 10025 WorkSource{10025 com.google.android.gms}
07-05 13:13:56.731  2046  7509 I PeopleContactsSync: CP2 sync disabled
07-05 13:13:56.731   904  1613 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2046, uid=10025, userID:0
07-05 13:13:56.731  2046  3352 I Icing   : doRemovePackageData com.test.thalitest
07-05 13:13:56.741  5978  7465 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
07-05 13:13:56.921  7466  7466 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
07-05 13:13:56.921  7466  7466 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 13:13:56.921  7466  7466 I GAv4    :   adb logcat -s GAv4
07-05 13:13:56.931  7466  7466 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-05 13:13:56.951  7466  7466 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-05 13:13:56.961  7466  7518 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-05 13:13:56.961  7466  7466 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
07-05 13:13:57.011  7466  7520 E SQLiteLog: (3850) statement aborts at 2: [PRAGMA journal_mode=PERSIST] 
07-05 13:13:57.011  7466  7520 E SQLiteDBG: func: executeOneRowQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/DocList.db, handle: 0xb8bd3990
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForString(Native Method)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:671)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:353)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:324)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:243)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at ael.a(PG:1521)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at hix$a.a(PG:125)
07-05 13:13:57.021  7466  7520 E SQLiteDatabase: 	at aen.run(PG:536)
07-05 13:13:57.081   364   410 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
07-05 13:13:57.081   364   410 W Vold    : Returning OperationFailed - no handler for errno 0
07-05 13:13:57.081  7466  7525 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
07-05 13:13:57.081  7466  7518 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-05 13:13:57.081  7466  7518 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0xb8baea10
07-05 13:13:57.081  7466  7518 E GAv4    : Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-05 13:13:57.081   904  1611 D PMS     : acquireWL(150fbc0f): PARTIAL_WAKE_LOCK  AsyncService 0x1 6126 10176 null
07-05 13:13:57.081  7466  7517 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 13:13:57.081  7466  7517 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at ael.a(PG:1521)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at hix$a.a(PG:125)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at aej.c(PG:139)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at aej.b(PG:398)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at agf.f(PG:417)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at oe.run(PG:1112)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 13:13:57.081  7466  7525 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: Failed to delete from CachedSearch133
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at aej.c(PG:139)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at aej.b(PG:398)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at agf.f(PG:417)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at oe.run(PG:1112)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 13:13:57.091  7466  7525 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
07-05 13:13:57.091   904  1618 D PMS     : releaseWL(150fbc0f): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-05 13:13:57.091  7466  7518 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-05 13:13:57.091   904  1612 D PMS     : acquireWL(def3ea5): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6126 10176 null
07-05 13:13:57.091  7466  7518 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0xb8baea10
07-05 13:13:57.091   904  1544 D PMS     : releaseWL(def3ea5): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
07-05 13:13:57.091  7466  7518 E GAv4    : Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-05 13:13:57.091  7466  7517 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 13:13:57.091  7327  7327 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForString(Native Method)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:671)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.setJournalMode(SQLiteConnection.java:353)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.setWalModeFromConfiguration(SQLiteConnection.java:324)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:243)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
07-05 13:13:57.091  7466  7520 E CAKEMIX_CRASHED: 	at aen.run(PG:536)
07-05 13:13:57.091  7327  7327 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
07-05 13:13:57.091  7327  7327 I DeviceManagement: WorkflowService: Starting workflow service
07-05 13:13:57.101  7327  7529 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@4823c85] args=[Bundle[mParcelledData.dataSize=112]]
07-05 13:13:57.101  7327  7529 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-05 13:13:57.101  7327  7529 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
07-05 13:13:57.101  7327  7529 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-05 13:13:57.101  7327  7529 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
07-05 13:13:57.101  7327  7529 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
07-05 13:13:57.101  7327  7529 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-05 13:13:57.101  7327  7529 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0xb8baf168
07-05 13:13:57.101  2320  2335 E MP-Decision: Update arg 2
07-05 13:13:57.111  7466  7526 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 13:13:57.111  7466  7526 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 13:13:57.111  7327  7529 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@4823c85]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
07-05 13:13:57.111  7327  7529 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 13:13:57.131   904  1607 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7531 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
07-05 13:13:57.131  7327  7327 I DeviceManagement: WorkflowService: Stopping workflow service
07-05 13:13:57.131   904  1607 D Process : killProcessQuiet, pid=6789
07-05 13:13:57.131   904  1607 I ActivityManager: Killing 6789:com.htc.mobiledata/u0a48 (adj 15): empty #17
07-05 13:13:57.131   904  1607 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
07-05 13:13:57.141   904  1611 I ActivityManager: Recipient 6789
07-05 13:13:57.161  7466  7526 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
07-05 13:13:57.191  7466  7526 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /system/lib, /vendor/lib, system/vendor/lib, system/vendor/lib/egl, system/lib/hw]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 13:13:57.191  7466  7526 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at ael.a(PG:1521)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at hix$a.a(PG:125)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at aej.c(PG:139)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at aej.a(PG:358)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at aej.a(PG:345)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at agf.c(PG:884)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at aii.doInBackground(PG:1063)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 13:13:57.201  7466  7548 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: Failed to query Account133 object
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at aev.getWritableDatabase(PG:238)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at ael.a(PG:1521)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at hix$a.a(PG:125)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at aej.c(PG:139)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at aej.a(PG:358)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at aej.a(PG:345)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at agf.c(PG:884)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at aii.doInBackground(PG:1063)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 13:13:57.201  7466  7548 E AbstractDatabaseInstance: 	at java.lang.Thread.run(Thread.java:818)
07-05 13:13:57.201  7466  7518 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-05 13:13:57.201  7466  7518 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0xb8baea10
07-05 13:13:57.201  7466  7518 E GAv4    : Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-05 13:13:57.201  7466  7517 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 13:13:57.201  7466  7517 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 13:13:57.201  7466  7518 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-05 13:13:57.201  7466  7518 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.apps.docs/databases/google_analytics_v4.db, handle: 0xb8baea10
07-05 13:13:57.201  7466  7518 E GAv4    : Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
07-05 13:13:57.201  7466  7517 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: java.lang.RuntimeException: An error occured while executing doInBackground()
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at java.lang.Thread.run(Thread.java:818)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at aev.getWritableDatabase(PG:238)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at ael.a(PG:1521)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at hix$a.a(PG:125)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at aej.c(PG:139)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at aej.a(PG:358)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at aej.a(PG:345)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at agf.c(PG:884)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at aii.doInBackground(PG:1063)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 13:13:57.201  7466  7548 E CAKEMIX_CRASHED: 	... 4 more
07-05 13:13:57.211   904  1611 D Process : killProcessQuiet, pid=6789
07-05 13:13:57.211   904  1611 W libprocessgroup: failed to open /acct/uid_10048/pid_6789/cgroup.procs: No such file or directory
07-05 13:13:57.211   904  1611 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
07-05 13:13:57.211   904  1478 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
07-05 13:13:57.211  1782  1782 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 13:13:57.231  7466  7520 D Process : killProcess, pid=7466
07-05 13:13:57.231  7466  7520 D Process : vf.uncaughtException:213 fct.uncaughtException:0 java.lang.ThreadGroup.uncaughtException:693 
07-05 13:13:57.231   904  1618 I ActivityManager: START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10107 on display 0
07-05 13:13:57.241  1483  1883 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
07-05 13:13:57.251   904   920 I ActivityManager: Recipient 7466

```
