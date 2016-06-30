#### Test 72145431fdae11f_thali09_HTC-HTC One_M8 Logs


```
--------- beginning of system
06-30 10:35:37.173   906  1068 D PMS     : acquireWL(3cc7951b): PARTIAL_WAKE_LOCK  *alarm* 0x1 906 1000 WorkSource{10075}
06-30 10:35:37.183   906  1068 V AlarmManager: sending alarm PendingIntent{1e4ae6b8: PendingIntentRecord{1b9a54ce com.android.vending startService}}, i=null, t=0, cnt=1, w=1467275737180, Int=0
06-30 10:35:37.183   906   906 D PMS     : releaseWL(3cc7951b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
--------- beginning of main
06-30 10:35:37.463  1748  1748 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 10:35:37.483  1748  1765 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidsecure
06-30 10:35:37.483  1748  1765 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
06-30 10:35:37.483  1748  1765 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:35:37.483  1748  1765 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-30 10:35:37.483  1748  1765 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 10:35:37.493  5067  5067 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 10:35:37.493  5067  5067 D Finsky  : [1] 5.onFinished: Installation state replication failed.
06-30 10:35:37.493  5067  5067 D Finsky  : [1] 5.onFinished: Scheduling replication attempt 3.
,06-30 10:35:38.143  5684  5697 E cutils-trace: Error opening trace file: No such file or directory (2)
06-30 10:35:38.183  5684  5684 D CustomizationManager: ====startRecUseTime====
06-30 10:35:38.193  5684  5684 D htc.customization.log.level:  is 
06-30 10:35:38.193  5684  5684 W CustomizationLogLevel: Level value is invalid, use default level 2
06-30 10:35:38.273  5684  5684 D CustomizationManager:  Read ACC file spent 0.052 (s)
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__001
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__E11
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__102
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__203
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__405
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__304
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__032
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__016
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__A48
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__K18
06-30 10:35:38.273  5684  5684 D CIDMapFileReader: Parsing tag item name = HTC__002
06-30 10:35:38.273  5684  5684 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
06-30 10:35:38.273  5684  5684 I CustomizationCIDLoader: Parsing tag category name = system
06-30 10:35:38.283  5684  5684 I CustomizationCIDLoader: Parsing tag category name = application
06-30 10:35:38.283  5684  5684 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 10:35:38.283  5684  5684 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 10:35:38.283  5684  5684 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 10:35:38.283  5684  5684 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 10:35:38.283  5684  5684 I CustomizationCIDLoader: Parsing tag category name = ACC
06-30 10:35:38.283  5684  5684 D CustomizationManager:  Read CID file spent 0.096 (s)
06-30 10:35:38.283  5684  5684 D CustomizationManager:  All configurations done spent 0.096 (s)
06-30 10:35:38.303  5684  5684 E ActTriggerJNI: open library fail.
06-30 10:35:38.313  2295  2311 E MP-Decision: Update arg 2
06-30 10:35:38.323  2295  2311 E MP-Decision: Update arg 4
06-30 10:35:38.323   906  1032 D PMS     : acquireHCC(29dfcada): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 906 1000 null
06-30 10:35:38.323   906   993 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 10:35:38.323   906  1032 D PMS     : acquireHCC(2b3fb0b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 906 1000 null
06-30 10:35:38.333  2295  2311 E MP-Decision: Update arg "0 190 240 240".
06-30 10:35:38.333  2295  2311 E MP-Decision: Update arg "0 75 400 400".
06-30 10:35:38.353   906   993 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5718 uid=10192 gids={50192, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 10:35:38.373  1200  1200 D DotMatrix: [EventService]  onDisplayChanged: 0
06-30 10:35:38.373   906   906 V ActivityManager: Display changed displayId=0
06-30 10:35:38.373  1200  1200 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
06-30 10:35:38.413  1492  1492 I TrimMemoryManager: [trimMemory] 20
06-30 10:35:38.443  5718  5718 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
06-30 10:35:38.473  5718  5718 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 6653-6661)
06-30 10:35:38.473  5718  5718 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:38.483  5718  5718 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8d223ed}
06-30 10:35:38.483  5718  5718 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:38.483  5718  5718 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:35:38.503  5718  5718 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 10:35:38.503  5718  5718 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:38.503  5718  5718 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 10:35:38.513  5718  5742 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-30 10:35:38.523  5718  5718 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 10:35:38.533  5718  5718 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:35:38.533  5718  5718 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:35:38.533  5718  5718 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
06-30 10:35:38.533  5718  5718 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 10:35:38.533  5718  5718 I Adreno-EGL: Build Date: 12/11/14 Thu
06-30 10:35:38.533  5718  5718 I Adreno-EGL: Local Branch: 
06-30 10:35:38.533  5718  5718 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
06-30 10:35:38.533  5718  5718 I Adreno-EGL: Local Patches: NONE
06-30 10:35:38.533  5718  5718 I Adreno-EGL: Reconstruct Branch: NOTHING
06-30 10:35:38.573   906  2159 W System.err: java.lang.Throwable: stack dump
06-30 10:35:38.573   906  1006 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
06-30 10:35:38.573   906  1006 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bf21200:true
06-30 10:35:38.573   906  2159 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
06-30 10:35:38.573   906  2159 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
06-30 10:35:38.573   906  2159 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
06-30 10:35:38.573   906  2159 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:38.573  5718  5753 D BluetoothAdapter: 11704944: getState() :  mService = null. Returning STATE_OFF
,06-30 10:35:38.633  5718  5718 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:38.643  5718  5718 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:35:38.653  5718  5718 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,06-30 10:35:38.653  5718  5718 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 10:35:38.653  5718  5718 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 10:35:38.693  5718  5718 D Atlas   : Validating map...
,06-30 10:35:38.703   906  1524 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
06-30 10:35:38.703  5718  5751 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-30 10:35:38.723   906  1005 D StatusBarManagerService: setSystemUiVisibility(0xc0000600)
06-30 10:35:38.723   906  1005 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-30 10:35:38.723   906  1005 D StatusBarManagerService: hiding MENU key
06-30 10:35:38.723   906  1005 D StatusBarManagerService: setSystemUiVisibility(0x8600)
06-30 10:35:38.723   906  1005 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 10:35:38.723   906  1005 D StatusBarManagerService: hiding MENU key
,06-30 10:35:38.743  5718  5718 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@264b9f2a, mServedView=org.apache.cordova.engine.SystemWebView{1d2dc11b VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1333a2b8
,06-30 10:35:38.753   906  1605 I InputMethodManagerService: Disable input method client, pid=1492
06-30 10:35:38.753   906  1605 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,06-30 10:35:38.763  5718  5718 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,06-30 10:35:38.783   906  1007 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +403ms (total +456ms)
,06-30 10:35:38.823  5718  5718 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5718
,06-30 10:35:38.893  5718  5718 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:35:38.983  5718  5768 D jxcore_app_log: JniHelper::setJavaVM(0xb757db98), pthread_self() = -1199379792
,06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2404caef added. We now have 1 listener(s),
06-30 10:35:38.993   906  1054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:38.993  5718  5768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 50:2E:6C:AC:21:50
,06-30 10:35:38.993  5718  5768 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "50:2E:6C:AC:21:50"
,06-30 10:35:38.993  5718  5768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:35:38.993  5718  5768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 50:2E:6C:AC:21:50
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
,06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:35:38.993  5718  5768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2226da added. We now have 1 listener(s)
06-30 10:35:38.993  5718  5768 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:35:39.003   906   906 E WifiTrafficPoller: ADD_CLIENT: 7
06-30 10:35:39.003   906  1080 D WifiService: New client listening to asynchronous messages
06-30 10:35:39.003  5718  5768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:39.003  5718  5768 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:35:39.003  5718  5768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:35:39.003  5718  5768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:35:39.003  5718  5768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:35:39.003  5718  5768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 10:35:39.003  5718  5768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 10:35:39.003   906   926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 10:35:39.003  5718  5768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 50:2E:6C:AC:21:50
,06-30 10:35:39.003  5718  5768 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:39.003  5718  5768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:39.003  5718  5768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:39.003  5718  5768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:39.003  5718  5768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:39.003  5718  5768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:39.003  5718  5768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:39.003  5718  5768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:39.003  5718  5768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:35:39.003  5718  5768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:39.003  5718  5768 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:35:39.003  5718  5768 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:35:39.023  5718  5718 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:39.733  5718  5774 W jxcore-log: Initializing JXcore engine
,06-30 10:35:39.733  5718  5774 W jxcore-log: JXcore engine is ready
,06-30 10:35:39.803  5718  5774 W jxcore-log: Starting JXcore engine
,06-30 10:35:39.883  5718  5774 W jxcore-log: Platform android
06-30 10:35:39.883  5718  5774 W jxcore-log: 
,06-30 10:35:39.883  5718  5774 W jxcore-log: Process ARCH arm
06-30 10:35:39.883  5718  5774 W jxcore-log: 
,06-30 10:35:40.083  5718  5774 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:35:40.083  5718  5774 I jxcore-log: 
06-30 10:35:40.083  5718  5774 W jxcore-log: JXcore engine is started
,06-30 10:35:40.093  5718  5768 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:35:40.093  5718  5718 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 10:35:40.093  5718  5774 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
06-30 10:35:40.093  5718  5774 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-30 10:35:40.103  5718  5718 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
06-30 10:35:40.103  5718  5718 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-30 10:35:40.103   906   993 D Process : killProcessQuiet, pid=5368
06-30 10:35:40.103   906   993 I ActivityManager: Killing 5368:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
06-30 10:35:40.103   906   993 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityStack.destroyActivityLocked:3417 
,06-30 10:35:40.113   906  1054 I ActivityManager: Recipient 5368
,06-30 10:35:40.133  5718  5768 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 30ms. Plugin should use CordovaInterface.getThreadPool().
06-30 10:35:40.133   906  1054 W libprocessgroup: failed to open /acct/uid_10013/pid_5368/cgroup.procs: No such file or directory
06-30 10:35:40.133  5718  5718 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-30 10:35:40.133   906  1054 D Process : killProcessQuiet, pid=5368
06-30 10:35:40.133   906  1054 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 10:35:40.133  5718  5718 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
06-30 10:35:40.133  5718  5718 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-30 10:35:40.133  5718  5718 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 10:35:40.133  5718  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 10:35:40.133  5718  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-30 10:35:40.133  5718  5718 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2404caef removed from the list
06-30 10:35:40.133  5718  5718 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 10:35:40.133  5718  5718 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2226da removed from the list
06-30 10:35:40.133  5718  5718 D io.jxcore.node.ConnectivityMonitor: stop
06-30 10:35:40.133  5718  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
06-30 10:35:40.133  5718  5718 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 10:35:40.323   906  1032 D PMS     : releaseHCC(29dfcada): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
06-30 10:35:40.323  2295  2311 E MP-Decision: Update arg 1
06-30 10:35:40.323   906  1032 D PMS     : releaseHCC(2b3fb0b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,06-30 10:35:40.353  5775  5778 E cutils-trace: Error opening trace file: No such file or directory (2),
,06-30 10:35:40.393  5775  5775 D CustomizationManager: ====startRecUseTime====,
06-30 10:35:40.393  5775  5775 D htc.customization.log.level:  is 
06-30 10:35:40.393  5775  5775 W CustomizationLogLevel: Level value is invalid, use default level 2
,06-30 10:35:40.463  5775  5775 D CustomizationManager:  Read ACC file spent 0.041 (s),
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__001,
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__E11,
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__102
,06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__203,
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__405,
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__304
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__032
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__016
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__A48
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__K18
06-30 10:35:40.463  5775  5775 D CIDMapFileReader: Parsing tag item name = HTC__002
06-30 10:35:40.463  5775  5775 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
06-30 10:35:40.463  5775  5775 I CustomizationCIDLoader: Parsing tag category name = system
06-30 10:35:40.463  5775  5775 I CustomizationCIDLoader: Parsing tag category name = application
,06-30 10:35:40.463  5775  5775 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 10:35:40.463  5775  5775 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 10:35:40.463  5775  5775 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 10:35:40.463  5775  5775 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 10:35:40.463  5775  5775 I CustomizationCIDLoader: Parsing tag category name = ACC
06-30 10:35:40.473  5775  5775 D CustomizationManager:  Read CID file spent 0.079 (s)
,06-30 10:35:40.473  5775  5775 D CustomizationManager:  All configurations done spent 0.079 (s)
,06-30 10:35:40.483  5775  5775 E ActTriggerJNI: open library fail.
,06-30 10:35:40.503   906  1001 D Process : killProcessQuiet, pid=5718,
06-30 10:35:40.503   906  1607 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=5775, uid=2000 userid=0
06-30 10:35:40.503   906  1001 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=-1: uninstall pkg
06-30 10:35:40.503   906  1001 I ActivityManager: Killing 5718:com.test.thalitest/u0a192 (adj 9): stop com.test.thalitest
,06-30 10:35:40.503   906  1001 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,06-30 10:35:40.533   906  1080 D WifiService: Client connection lost with reason: 4,
,06-30 10:35:40.533   906   993 I ActivityManager: Recipient 5718
,06-30 10:35:40.603   906  1053 W PackageSettings: Skipping PackageSetting{1091f540 com.example.hello/10380} due to missing metadata
,06-30 10:35:40.613   906   993 W ActivityManager: Spurious death for ProcessRecord{2591da92 5718:com.test.thalitest/u0a192}, curProc for 5718: null
,06-30 10:35:40.623   906  1053 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=0: pkg removed
,06-30 10:35:40.633  1200  1200 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
06-30 10:35:40.633   906  1076 D PMS     : acquireWL(e9ebc63): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
06-30 10:35:40.633  1200  1200 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
06-30 10:35:40.633   906  1077 V NetworkPolicy: ACTION_UID_REMOVED for uid=10192
06-30 10:35:40.633  1200  1200 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,06-30 10:35:40.653   906  1302 D PMS     : acquireWL(cf0e919): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1701 10025 WorkSource{10025 com.google.android.gms}
06-30 10:35:40.663   906  2155 D PMS     : releaseWL(cf0e919): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
06-30 10:35:40.663   906  1076 D PMS     : releaseWL(e9ebc63): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
06-30 10:35:40.673  1492  1492 I art     : Explicit concurrent mark sweep GC freed 18840(1333KB) AllocSpace objects, 19(1424KB) LOS objects, 39% free, 18MB/31MB, paused 548us total 36.687ms
06-30 10:35:40.663  1447  1447 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 10:35:40.673  1492  1821 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
06-30 10:35:40.663   906  1077 V NetworkPolicy: writePolicyLocked()
06-30 10:35:40.673  1492  1821 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
06-30 10:35:40.673   906  1077 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
06-30 10:35:40.673   906  1077 V NetworkPolicy: updateNetworkEnabledLocked()
06-30 10:35:40.673   906  1077 D libc    : [NET] android_getaddrinfofornet-, err=8
06-30 10:35:40.673   906  1077 V NetworkPolicy: updateNotificationsLocked()
06-30 10:35:40.673   906  1077 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
06-30 10:35:40.673   906  1077 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-30 10:35:40.673   906  1077 D libc    : [NET] android_getaddrinfo_proxy+
06-30 10:35:40.673   906  1077 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-30 10:35:40.673  1492  1492 I Launcher: Deferring update until onResume
06-30 10:35:40.673  1492  1492 D Launcher: waitUntilResume // bindAppsRemoved,
,06-30 10:35:40.673   459  5792 D libc    : [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
06-30 10:35:40.673   459  5792 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
06-30 10:35:40.673   459  5792 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
06-30 10:35:40.673   459  5792 D libc    : [NET] android_getaddrinfofornet-, err=7
06-30 10:35:40.673   906  1077 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
06-30 10:35:40.683  1492  1492 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
06-30 10:35:40.683  1584  1975 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
06-30 10:35:40.693  1543  5794 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
06-30 10:35:40.693  1447  1447 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
06-30 10:35:40.703  1584  1975 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
06-30 10:35:40.713   906  1607 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5799 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,06-30 10:35:40.733   471   471 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 3.931ms total 22.880ms,
,06-30 10:35:40.743  1415  5793 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,06-30 10:35:40.743   471   471 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 151us total 9.550ms
,06-30 10:35:40.763   906  1000 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
06-30 10:35:40.743   906   906 I art     : Explicit concurrent mark sweep GC freed 24765(1780KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 16MB/25MB, paused 1.066ms total 121.355ms
06-30 10:35:40.753  1415  5793 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
06-30 10:35:40.753   906  1053 I art     : WaitForGcToComplete blocked for 122.109ms for cause Explicit
06-30 10:35:40.753   471   471 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 129us total 8.975ms
06-30 10:35:40.753  4993  4993 I art     : Explicit concurrent mark sweep GC freed 11151(833KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 200us total 129.706ms
06-30 10:35:40.763  1584  1975 E ExternalAccountType: Unsupported attribute readOnly
,06-30 10:35:40.803  5799  5799 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,06-30 10:35:40.803   906  1005 D StatusBarManagerService: setSystemUiVisibility(0x8700)
,06-30 10:35:40.803   906  1005 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 10:35:40.803   906  1005 D StatusBarManagerService: hiding MENU key,
,06-30 10:35:40.803   906  1005 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
,06-30 10:35:40.803   906  1005 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 10:35:40.803   906  1005 D StatusBarManagerService: hiding MENU key,
06-30 10:35:40.813   906  1607 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5718 uid 10192
06-30 10:35:40.813   906  1607 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,06-30 10:35:40.823   906   906 W PackageManager: Unable to load service info ResolveInfo{3fa09f2 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
06-30 10:35:40.823   906   906 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-30 10:35:40.823   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
06-30 10:35:40.823   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
06-30 10:35:40.823   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
06-30 10:35:40.823   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
06-30 10:35:40.823   906   906 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
06-30 10:35:40.823   906   906 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
06-30 10:35:40.823   906   906 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 10:35:40.823   906   906 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 10:35:40.823   906   906 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:40.823   906   906 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
06-30 10:35:40.823   906   906 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
06-30 10:35:40.823   906   906 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 10:35:40.823   906   906 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 10:35:40.823   906   906 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
06-30 10:35:40.823   906   906 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,06-30 10:35:40.833  1748  1748 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
06-30 10:35:40.833   906   993 D PMS     : acquireWL(1f1d3508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1748 10025 WorkSource{10025 com.google.android.gms}
06-30 10:35:40.833  1748  1748 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
06-30 10:35:40.843   906  1310 D PMS     : releaseWL(1f1d3508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
06-30 10:35:40.863  4043  5827 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-30 10:35:40.863   906  1000 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
06-30 10:35:40.863  4043  4043 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 10:35:40.863  4043  5827 D AccountUtils: Clearing selected account for com.test.thalitest
06-30 10:35:40.863  4043  4043 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,06-30 10:35:40.873  4043  4043 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 10:35:40.873  4043  4043 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,06-30 10:35:40.873  4993  5829 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,06-30 10:35:40.893   906  2159 D PMS     : acquireWL(22dec0a): PARTIAL_WAKE_LOCK  AsyncService 0x1 5137 10176 null,
,06-30 10:35:40.893   906   906 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 10:35:40.903   906  2101 D PMS     : acquireWL(17c6bed6): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5137 10176 null
,06-30 10:35:40.903  5329  5329 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
06-30 10:35:40.903  5329  5329 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,06-30 10:35:40.903   906  2152 D PMS     : releaseWL(22dec0a): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,06-30 10:35:40.903  5329  5329 I DeviceManagement: WorkflowService: Starting workflow service
,06-30 10:35:40.903   906  1266 D PMS     : releaseWL(17c6bed6): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,06-30 10:35:40.913  5329  5832 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@2c0e842] args=[Bundle[mParcelledData.dataSize=112]]
,06-30 10:35:40.913  5329  5832 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-30 10:35:40.913  5329  5832 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
06-30 10:35:40.913  5329  5832 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,06-30 10:35:40.913  5329  5832 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,06-30 10:35:40.933   906  2159 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=5835 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
06-30 10:35:40.933  5329  5833 I DeviceManagement: SessionStateController: Checking invariants...
,06-30 10:35:40.953  4043  5827 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,06-30 10:35:40.963  4043  5853 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
06-30 10:35:40.963  4043  5853 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,06-30 10:35:40.963  4043  5853 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
06-30 10:35:40.963  4043  5853 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,06-30 10:35:40.973  4043  5853 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
06-30 10:35:40.973  4043  5853 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,06-30 10:35:40.973  4043  5853 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,06-30 10:35:40.983  4043  5853 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,06-30 10:35:40.983  4043  5853 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,06-30 10:35:40.983  4043  5853 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
06-30 10:35:40.983  4043  5853 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,06-30 10:35:40.983  4043  5853 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
06-30 10:35:40.983  4043  5853 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,06-30 10:35:40.993   906  1053 I art     : Explicit concurrent mark sweep GC freed 11537(622KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.660ms total 232.986ms,
,06-30 10:35:40.993   906   926 D PMS     : acquireWL(2b8c376a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4043 10025 null
,06-30 10:35:41.003  1748  1748 I ConfigService: onCreate,
,06-30 10:35:41.003  4043  4043 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
06-30 10:35:41.003   906   926 D PMS     : releaseWL(2b8c376a): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,06-30 10:35:41.013  4043  5855 W BaseAppContext: Using Auth Proxy for data requests.
,06-30 10:35:41.013  5329  5833 I DeviceManagement: ConfigManagerController: There is no cached content available: appID=com.htc.cs.dm
06-30 10:35:41.013  4043  5857 I PeopleContactsSync: CP2 sync disabled
,06-30 10:35:41.013   906  2101 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4043, uid=10025, userID:0
06-30 10:35:41.013   906  1607 D PMS     : acquireWL(2405400e): PARTIAL_WAKE_LOCK  Icing 0x1 4043 10025 WorkSource{10025 com.google.android.gms}
06-30 10:35:41.013  4043  4043 I ConfigFetchService: service connected
06-30 10:35:41.023  4043  4126 I Icing   : doRemovePackageData com.test.thalitest
06-30 10:35:41.023  4043  5855 W BaseAppContext: Using Auth Proxy for data requests.
,06-30 10:35:41.023  5329  5833 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
,06-30 10:35:41.023  5329  5832 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: <com.htc.cs.dm.config.UnavailableException: reasonCode=1150, message=[There is no cached content available.]>
06-30 10:35:41.023  5329  5832 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,06-30 10:35:41.023  5329  5832 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@2c0e842]
06-30 10:35:41.023  5329  5329 I DeviceManagement: WorkflowService: Stopping workflow service
,06-30 10:35:41.033   906  1302 D PMS     : releaseWL(2405400e): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10025 com.google.android.gms}
,06-30 10:35:41.073   906  1605 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=5863 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a
06-30 10:35:41.073  5558  5558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
06-30 10:35:41.073   906  1266 D PMS     : acquireWL(2d47c8be): PARTIAL_WAKE_LOCK  Icing 0x1 4043 10025 WorkSource{10025 com.google.android.gms}
06-30 10:35:41.073   906  1068 D PMS     : acquireWL(27ae8d1f): PARTIAL_WAKE_LOCK  *alarm* 0x1 906 1000 WorkSource{10025}
06-30 10:35:41.073   906  1068 V AlarmManager: sending alarm PendingIntent{194bb86c: PendingIntentRecord{36da9603 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=129233, Int=0
,06-30 10:35:41.083  4993  5829 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] ,
,06-30 10:35:41.083  5558  5873 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,06-30 10:35:41.083  5558  5873 D PowerUsageService: removed uid = 10192
,06-30 10:35:41.123   906  2159 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=5882 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 10:35:41.133   906  1603 D Process : killProcessQuiet, pid=5465
06-30 10:35:41.133   906  1603 I ActivityManager: Killing 5465:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
06-30 10:35:41.133   906  1603 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-30 10:35:41.143   906  2101 I ActivityManager: Recipient 5465
,06-30 10:35:41.143  5863  5863 D ExternalStorage: After updating volumes, found 1 active roots
,06-30 10:35:41.173   906  2101 D Process : killProcessQuiet, pid=5465
,06-30 10:35:41.173   906  2101 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 10:35:41.173   906  2101 W libprocessgroup: failed to open /acct/uid_10079/pid_5465/cgroup.procs: No such file or directory
,06-30 10:35:41.173  5882  5882 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,06-30 10:35:41.193   906  1605 D PMS     : acquireWL(7fe8b1): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1748 10025 WorkSource{10025 com.google.android.gms},
06-30 10:35:41.193   906   906 D PMS     : releaseWL(27ae8d1f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10025}
06-30 10:35:41.193  1748  5903 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
06-30 10:35:41.193  1748  5903 D libc    : [NET] android_getaddrinfofornet-, err=8
06-30 10:35:41.193  1748  5903 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
06-30 10:35:41.193  1748  5903 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-30 10:35:41.193  1748  5903 D libc    : [NET] android_getaddrinfo_proxy+
06-30 10:35:41.193  1748  5903 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,06-30 10:35:41.193   459  5904 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
06-30 10:35:41.193   459  5904 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
06-30 10:35:41.203   459  5904 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
06-30 10:35:41.203   459  5904 D libc    : [NET] android_getaddrinfofornet-, err=7
06-30 10:35:41.203  1748  5903 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,06-30 10:35:41.203   906  2155 D PMS     : releaseWL(7fe8b1): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10025 com.google.android.gms}
,06-30 10:35:41.233   906  1001 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5906 uid=10120 gids={50120, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,06-30 10:35:41.263  5403  5403 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 10:35:41.263   906  1306 I ActivityManager: Killing 5512:com.htc.bgp/u0a11 (adj 15): empty #17
06-30 10:35:41.263   906  1306 D Process : killProcessQuiet, pid=5512
06-30 10:35:41.263   906  1306 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
06-30 10:35:41.263  5403  5403 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 10:35:41.263  5906  5906 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 10:35:41.273   906  1310 I ActivityManager: Recipient 5512
,06-30 10:35:41.323   906  1310 D Process : killProcessQuiet, pid=5512
,06-30 10:35:41.323   906  1310 W libprocessgroup: failed to open /acct/uid_10011/pid_5512/cgroup.procs: No such file or directory
06-30 10:35:41.323   906  1310 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-30 10:35:41.333  5835  5860 D Documents: Update found 7 roots in 296ms
,06-30 10:35:41.333  5835  5900 D Documents: Update found 7 roots in 189ms
,06-30 10:35:41.383  4043  5852 W DriveInitializer: Awaiting to be initialized
,06-30 10:35:41.383  4043  5927 W DriveInitializer: Background init thread started
,06-30 10:35:41.413  5906  5932 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
06-30 10:35:41.413  5906  5932 I Babel_SMS: MmsConfig.loadMmsSettings
,06-30 10:35:41.453   906  1605 I ActivityManager: Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=5935 uid=10067 gids={50067, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,06-30 10:35:41.453   906  2159 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=5906, uid=10120, userID:0
,06-30 10:35:41.463   363   408 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/
,06-30 10:35:41.463   363   408 W Vold    : Returning OperationFailed - no handler for errno 0,
,06-30 10:35:41.463  4043  5927 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,06-30 10:35:41.493  5935  5935 W HtcWrapAdjustableCursorFactory: HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.,
,06-30 10:35:41.503  5935  5935 D MessageFrequencyProvider: onCreate,
,06-30 10:35:41.503  5935  5951 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_string
,06-30 10:35:41.503  5935  5935 V GetPrviateResource: GetPrviateResource
06-30 10:35:41.503  5935  5935 V GetPrviateResource: GetPrviateResource
,06-30 10:35:41.513  5935  5950 D MmsCustomizationProvider: query uri: content://htc-mms-customization/mms-ua/ua_profile
,06-30 10:35:41.513  5906  5932 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_One_M8/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/fL0fd1AcEY/ua-profile.xml,
06-30 10:35:41.513  5906  5932 I Babel_SMS: MmsConfig.loadFromDatabase
,06-30 10:35:41.513  5906  5932 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
,06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at alg.<init>(SourceFile:161)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at alj.a(SourceFile:1015)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at gvf.d(SourceFile:408)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at gvf.b(SourceFile:238)
,06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at gvf.a(SourceFile:204)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at gvf.a(SourceFile:485)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at alg.a(SourceFile:167)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at dnm.c(SourceFile:606)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at dnm.b(SourceFile:570)
06-30 10:35:41.513  5906  5932 E SQLiteDatabase: 	at dnn.run(SourceFile:221)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: FATAL EXCEPTION: Thread-801
06-30 10:35:41.513  5906  5932 E AndroidRuntime: Process: com.google.android.talk, PID: 5906
06-30 10:35:41.513  5906  5932 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at alg.<init>(SourceFile:161)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at alj.a(SourceFile:1015)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at gvf.d(SourceFile:408)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at gvf.b(SourceFile:238)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at gvf.a(SourceFile:204)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at gvf.a(SourceFile:485)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at alg.a(SourceFile:167)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at dnm.c(SourceFile:606)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at dnm.b(SourceFile:570)
06-30 10:35:41.513  5906  5932 E AndroidRuntime: 	at dnn.run(SourceFile:221)
06-30 10:35:41.513   906   993 E ActivityManager: App crashed! Process: com.google.android.talk
06-30 10:35:41.523  5935  5935 D MessageCustFlag: sense_version=6.0
06-30 10:35:41.523  5906  5932 D Process : killProcess, pid=5906
06-30 10:35:41.523  5906  5932 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,06-30 10:35:41.523  5935  5935 D BTAccessoryUtil: createReceiver
06-30 10:35:41.523  5935  5935 D BTAccessoryUtil: registerReceiver return intent = null
06-30 10:35:41.523  5935  5935 D MessageCustFlag: sku_id=99
06-30 10:35:41.523   906  5965 E DropBoxManagerService: Can't write: system_app_crash
06-30 10:35:41.523   906  5965 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:41.523   906  5965 E DropBoxManagerService: 	... 5 more
06-30 10:35:41.523  5935  5935 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
06-30 10:35:41.533  5935  5935 W SystemReader: Cannot find qct_8960_interface, use default value instead
06-30 10:35:41.533   906  1605 D Process : killProcessQuiet, pid=5906
06-30 10:35:41.533   906  1605 I ActivityManager: Recipient 5906
06-30 10:35:41.533   906  1605 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 10:35:41.543  4043  5953 E SQLiteLog: (3850) statement aborts at 167: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
06-30 10:35:41.543  4043  5953 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0xb86d3d20
06-30 10:35:41.543  4043  5953 E DocListDatabase: Failed to delete from FileContent112
06-30 10:35:41.543  4043  5953 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 10:35:41.543  4043  5953 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:41.543  4043  5927 W DriveInitializer: Background init thread ended
06-30 10:35:41.543  4043  5852 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 10:35:41.543  4043  5852 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0xb86d3d20
06-30 10:35:41.543  4043  5953 E AndroidRuntime: FATAL EXCEPTION: pool-12-thread-1
06-30 10:35:41.543  4043  5953 E AndroidRuntime: Process: com.google.android.gms, PID: 4043
06-30 10:35:41.543  4043  5953 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 10:35:41.543  4043  5953 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: disk I/O error (code 3850)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:585)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 10:35:41.543  4043  5852 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:41.553   906  1605 I ActivityManager: Process com.google.android.talk (pid 5906) has died
06-30 10:35:41.553   906  1605 I ActivityManager: Killing 5586:com.htc.mobiledata/u0a48 (adj 15): empty #17
06-30 10:35:41.553   906  1605 D Process : killProcessQuiet, pid=5586
06-30 10:35:41.553   906  1605 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.appDiedLocked:5120 
,06-30 10:35:41.553   906  2159 I ActivityManager: Recipient 5586
06-30 10:35:41.573   906  1302 E ActivityManager: App crashed! Process: com.google.android.gms
06-30 10:35:41.573   906  2159 D Process : killProcessQuiet, pid=5586
06-30 10:35:41.573   906  2159 W libprocessgroup: failed to open /acct/uid_10048/pid_5586/cgroup.procs: No such file or directory
06-30 10:35:41.573  4043  5953 D Process : killProcess, pid=4043
06-30 10:35:41.573   906  2159 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 10:35:41.573  4043  5953 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
06-30 10:35:41.573   906  5967 E DropBoxManagerService: Can't write: system_app_crash
06-30 10:35:41.573   906  5967 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:41.573   906  5967 E DropBoxManagerService: 	... 5 more
06-30 10:35:41.593   906  1310 D Process : killProcessQuiet, pid=4043
06-30 10:35:41.593   906  1310 I ActivityManager: Recipient 4043
06-30 10:35:41.593   906  1310 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 10:35:41.593   906  1603 D PMS     : handleWLDeath(2d47c8be): PARTIAL_WAKE_LOCK  Icing 0x1
,06-30 10:35:41.673   906  1310 I ActivityManager: Process com.google.android.gms (pid 4043) has died
,06-30 10:35:41.673  1748  1748 I ConfigService: onDestroy
06-30 10:35:41.673   906  1310 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
06-30 10:35:41.673   906  1310 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
06-30 10:35:41.673   906  1310 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
06-30 10:35:41.673   906  1310 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
,06-30 10:35:42.183  1492  1821 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
06-30 10:35:42.183  1492  1821 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@28bb56e3 +
06-30 10:35:42.313  1492  1821 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
06-30 10:35:42.183  1492  1821 I Prism.WidgetManager: onLoadItems() +
06-30 10:35:42.273   479   479 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 10:35:42.433  1492  1821 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,06-30 10:35:42.493  1492  1821 E Prism.WidgetManager: The same lists. No need to update. skip it.
06-30 10:35:42.493  1492  1821 I Prism.WidgetManager: onLoadItems() -
06-30 10:35:42.493  1492  1821 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@28bb56e3 -
,06-30 10:35:42.503  1492  1821 E SQLiteLog: (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=73] disk I/O error
06-30 10:35:42.503  1492  1821 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xb862dc18
,06-30 10:35:42.503  1492  1821 E AndroidRuntime: FATAL EXCEPTION: TaskWorker
06-30 10:35:42.503  1492  1821 E AndroidRuntime: Process: com.htc.launcher, PID: 1492
06-30 10:35:42.503  1492  1821 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 10:35:42.503  1492  1821 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 10:35:42.503   906   993 E ActivityManager: App crashed! Process: com.htc.launcher
,06-30 10:35:42.503   906   993 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,06-30 10:35:42.513   906  1524 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.513   906  1524 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.513   906  1524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.513   906  1524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.513   906  1524 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.513   906  1524 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 10:35:42.513   906  1524 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 10:35:42.513   906  1524 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 10:35:42.513   906  1524 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 10:35:42.513   906  1524 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 10:35:42.513   906  1524 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 10:35:42.513   906  1524 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 10:35:42.513   906  1524 W System.err: 	,at android.os.Looper.loop(Looper.java:155),
,06-30 10:35:42.513   906  1524 W System.err: ,	at android.os.HandlerThread.run(HandlerThread.java:61),
,06-30 10:35:42.513   906  1524 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.513   906  1524 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.513   906  1524 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.513   906  1524 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.513   906  1524 W System.err: 	... 12 more
06-30 10:35:42.513   906   993 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,06-30 10:35:42.523   906   993 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.523   906   993 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.523   906   993 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.523   906   993 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.523   906   993 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
06-30 10:35:42.523   906   993 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
06-30 10:35:42.523   906   993 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
06-30 10:35:42.523   906   993 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
06-30 10:35:42.523   906   993 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
06-30 10:35:42.523   906   993 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
06-30 10:35:42.523   906   993 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
06-30 10:35:42.523   906   993 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
06-30 10:35:42.523   906   993 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
06-30 10:35:42.523   906   993 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
06-30 10:35:42.523   906   993 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:42.523   906   993 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.523   906   993 W System.err: 	at libcore.io.Posix.open(Native Method)
,06-30 10:35:42.523   906   993 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.523   906   993 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.523   906   993 W System.err: 	... 14 more
,06-30 10:35:42.523   906   993 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 10:35:42.523   906   993 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.533   906   993 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.533   906   993 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 10:35:42.533   906   993 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 10:35:42.533   906   993 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
06-30 10:35:42.533   906   993 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
06-30 10:35:42.533   906   993 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
06-30 10:35:42.533   906   993 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
06-30 10:35:42.533   906   993 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
06-30 10:35:42.533   906   993 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
,06-30 10:35:42.533   906   993 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
06-30 10:35:42.533   906   993 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
06-30 10:35:42.533   906   993 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
06-30 10:35:42.533   906   993 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
06-30 10:35:42.533   906   993 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 10:35:42.533   906   993 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.533   906   993 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.533   906   993 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.533   906   993 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.533   906   993 W System.err: 	... 14 more
,06-30 10:35:42.533   906   993 W ActivityManager:   Force finishing activity com.htc.launcher/.Launcher
,06-30 10:35:42.533  1492  1492 I OrientationManager: [release]
,06-30 10:35:42.533  1492  1492 I Prism.IndicatorPagedVi_: IndicatorPagedView.nCapability with type count = 1 and capability = 20
06-30 10:35:42.533  1492  1821 D Process : killProcess, pid=1492
06-30 10:35:42.533  1492  1821 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,06-30 10:35:42.533   906  5995 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 10:35:42.533   906  5995 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1467275742546.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 10:35:42.533   906  5995 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 10:35:42.533   906  5995 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 10:35:42.533   906  5995 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 10:35:42.533   906  5995 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
06-30 10:35:42.533   906  5995 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:35:42.533   906  5995 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 10:35:42.533   906  5995 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 10:35:42.533   906  5995 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 10:35:42.533   906  5995 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 10:35:42.533   906  5995 E ErrorReport: 	... 4 more
,06-30 10:35:42.563   906  2155 D Process : killProcessQuiet, pid=1492
,06-30 10:35:42.563   906  2155 I ActivityManager: Recipient 1492
06-30 10:35:42.563   906  2155 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 10:35:42.563   906  1607 I WindowState: WIN DEATH: Window{2c46706f u0 com.htc.launcher/com.htc.launcher.Launcher}
,06-30 10:35:42.593   906  2155 I ActivityManager: Process com.htc.launcher (pid 1492) has died
,06-30 10:35:42.593   906  2155 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
,06-30 10:35:42.593  2295  2311 E MP-Decision: Update arg "0 380 380 380".
06-30 10:35:42.593  2295  2311 E MP-Decision: Update arg "0 400 400 400".
,06-30 10:35:42.613   906  2155 I ActivityManager: Start proc com.htc.launcher for activity com.htc.launcher/.Launcher: pid=5998 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a

```
