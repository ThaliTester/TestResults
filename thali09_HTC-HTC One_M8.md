#### Test 757892682551a10_thali09_HTC-HTC One_M8 Logs


```
--------- beginning of main
06-30 13:52:34.423   892   986 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA
--------- beginning of system
06-30 13:52:34.433   892   986 D PMS     : acquireWL(63b5d71): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 892 1000 null
06-30 13:52:34.433   892   986 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
06-30 13:52:34.503   892  6741 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 4
06-30 13:52:34.513   892  6741 D libc    : [NET] android_getaddrinfofornet-, err=8
06-30 13:52:34.513   892  6741 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 1024
06-30 13:52:34.513   892  6741 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
06-30 13:52:34.513   892  6741 D libc    : [NET] android_getaddrinfo_proxy+
06-30 13:52:34.523   892  6741 D libc    : [NET] android_getaddrinfo_proxy get netid:0
06-30 13:52:34.523   460  6743 D libc    : [NET] android_getaddrinfofornet+,hn 20(0x78747261332e67),sn(),hints(known),family 0,flags 1024
06-30 13:52:34.523   460  6743 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
06-30 13:52:34.593   460  6743 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
06-30 13:52:34.593   460  6743 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-30 13:52:34.593   892  6741 D libc    : [NET] android_getaddrinfo_proxy-, success
06-30 13:52:34.593   892  6741 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
06-30 13:52:34.593   892  6741 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
06-30 13:52:34.643   892  6741 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data
,06-30 13:52:35.093  6744  6754 E cutils-trace: Error opening trace file: No such file or directory (2)
06-30 13:52:35.123  6744  6744 D CustomizationManager: ====startRecUseTime====
06-30 13:52:35.123  6744  6744 D htc.customization.log.level:  is 
06-30 13:52:35.123  6744  6744 W CustomizationLogLevel: Level value is invalid, use default level 2
06-30 13:52:35.133   892  1440 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0
06-30 13:52:35.133   892  1440 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0
06-30 13:52:35.133   892  6741 D GpsLocationProvider:  [handleDownloadXtraData]inject done.
06-30 13:52:35.133   892  6741 D PMS     : acquireWL(3b28a2e2): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 892 1000 null
06-30 13:52:35.133   892  6741 D PMS     : releaseWL(63b5d71): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
06-30 13:52:35.133   892   986 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
06-30 13:52:35.133   892   986 D PMS     : releaseWL(3b28a2e2): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
06-30 13:52:35.193  6744  6744 D CustomizationManager:  Read ACC file spent 0.044 (s)
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__001
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__E11
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__102
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__203
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__405
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__304
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__032
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__016
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__A48
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__K18
06-30 13:52:35.203  6744  6744 D CIDMapFileReader: Parsing tag item name = HTC__002
06-30 13:52:35.203  6744  6744 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
06-30 13:52:35.203  6744  6744 I CustomizationCIDLoader: Parsing tag category name = system
06-30 13:52:35.203  6744  6744 I CustomizationCIDLoader: Parsing tag category name = application
06-30 13:52:35.203  6744  6744 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 13:52:35.203  6744  6744 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 13:52:35.203  6744  6744 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 13:52:35.213  6744  6744 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 13:52:35.213  6744  6744 I CustomizationCIDLoader: Parsing tag category name = ACC
06-30 13:52:35.213  6744  6744 D CustomizationManager:  Read CID file spent 0.088 (s)
06-30 13:52:35.213  6744  6744 D CustomizationManager:  All configurations done spent 0.088 (s)
06-30 13:52:35.223  6744  6744 E ActTriggerJNI: open library fail.
06-30 13:52:35.243  2358  2374 E MP-Decision: Update arg 2
06-30 13:52:35.243  2358  2374 E MP-Decision: Update arg "0 190 240 240".
06-30 13:52:35.243   892  1607 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 13:52:35.243  2358  2374 E MP-Decision: Update arg "0 75 400 400".
06-30 13:52:35.243   892  1014 D PMS     : acquireHCC(1ab749a9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 892 1000 null
06-30 13:52:35.253  2358  2374 E MP-Decision: Update arg 4
06-30 13:52:35.253   892  1014 D PMS     : acquireHCC(1a320b2e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 892 1000 null
06-30 13:52:35.283   892  1607 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6774 uid=10192 gids={50192, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 13:52:35.293   892   892 V ActivityManager: Display changed displayId=0
06-30 13:52:35.293  1197  1197 D DotMatrix: [EventService]  onDisplayChanged: 0
06-30 13:52:35.303  1197  1197 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
06-30 13:52:35.343  1504  1504 I TrimMemoryManager: [trimMemory] 20
06-30 13:52:35.373  6774  6774 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
06-30 13:52:35.383  6774  6774 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2525-2526)
06-30 13:52:35.383  6774  6774 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:35.393  6774  6774 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f0770a9}
06-30 13:52:35.393  6774  6774 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:35.393  6774  6774 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:52:35.413  6774  6774 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:52:35.413  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:35.413  6774  6774 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 13:52:35.423  6774  6774 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 13:52:35.423  6774  6774 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:35.423  6774  6774 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:35.423  6774  6774 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
06-30 13:52:35.423  6774  6774 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 13:52:35.423  6774  6774 I Adreno-EGL: Build Date: 12/11/14 Thu
06-30 13:52:35.423  6774  6774 I Adreno-EGL: Local Branch: 
06-30 13:52:35.423  6774  6774 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
06-30 13:52:35.423  6774  6774 I Adreno-EGL: Local Patches: NONE
06-30 13:52:35.423  6774  6774 I Adreno-EGL: Reconstruct Branch: NOTHING
06-30 13:52:35.473   892  1607 W System.err: java.lang.Throwable: stack dump
06-30 13:52:35.473   892   992 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
06-30 13:52:35.473   892  1607 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
06-30 13:52:35.473   892   992 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30c556f4:true
06-30 13:52:35.473   892  1607 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
06-30 13:52:35.473   892  1607 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
06-30 13:52:35.473   892  1607 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:35.473  6774  6809 D BluetoothAdapter: 683503205: getState(). Returning 12
,06-30 13:52:35.563  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:52:35.563  6774  6774 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 13:52:35.573  6774  6774 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,06-30 13:52:35.583  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:52:35.583  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 13:52:35.623  6774  6774 D Atlas   : Validating map...
,06-30 13:52:35.633   892  1549 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,06-30 13:52:35.633  6774  6807 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-30 13:52:35.653   892   991 D StatusBarManagerService: setSystemUiVisibility(0xc0000600),
06-30 13:52:35.653   892   991 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 13:52:35.653   892   991 D StatusBarManagerService: hiding MENU key
,06-30 13:52:35.653   892   991 D StatusBarManagerService: setSystemUiVisibility(0x8600)
06-30 13:52:35.653   892   991 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-30 13:52:35.653   892   991 D StatusBarManagerService: hiding MENU key
,06-30 13:52:35.723  6774  6774 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@311b03b6, mServedView=org.apache.cordova.engine.SystemWebView{386638b7 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@3d581824
,06-30 13:52:35.723   892  1090 I InputMethodManagerService: Disable input method client, pid=1504
06-30 13:52:35.723   892  1090 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,06-30 13:52:35.733  6774  6774 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,06-30 13:52:35.733   892   993 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +431ms (total +491ms)
,06-30 13:52:35.783  6774  6774 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6774
,06-30 13:52:35.863  6774  6774 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,06-30 13:52:35.953  6774  6825 D jxcore_app_log: JniHelper::setJavaVM(0xb86d4b98), pthread_self() = -1181116680
,06-30 13:52:35.963  6774  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:35.963  6774  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:35.963  6774  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:35.963  6774  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:35.963  6774  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:52:35.963  6774  6825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2454efcb added. We now have 1 listener(s)
,06-30 13:52:35.963   892   907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,06-30 13:52:35.963  6774  6825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 50:2E:6C:AC:21:50
,06-30 13:52:35.973  6774  6825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "50:2E:6C:AC:21:50"
,06-30 13:52:35.973  6774  6825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:35.973  6774  6825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 50:2E:6C:AC:21:50
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d49c666 added. We now have 1 listener(s)
06-30 13:52:35.973  6774  6825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:52:35.973   892  1079 D WifiService: New client listening to asynchronous messages
06-30 13:52:35.973   892   892 E WifiTrafficPoller: ADD_CLIENT: 8
06-30 13:52:35.973  6774  6825 D BluetoothAdapter: 683503205: getState(). Returning 12
06-30 13:52:35.973  6774  6825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-30 13:52:35.983  6774  6825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
06-30 13:52:35.983  6774  6825 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
06-30 13:52:35.983  6774  6825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 13:52:35.983   892  2073 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 13:52:35.983  6774  6825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 50:2E:6C:AC:21:50
06-30 13:52:35.983  6774  6825 D BluetoothAdapter: 683503205: getState(). Returning 12
06-30 13:52:35.983  6774  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:35.983  6774  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:35.983  6774  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 13:52:35.983  6774  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 13:52:35.983  6774  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 13:52:35.983  6774  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 13:52:35.983  6774  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 13:52:35.983  6774  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 13:52:35.983  6774  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:35.983  6774  6825 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:35.983  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:52:35.983  6774  6825 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 13:52:35.983  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 13:52:36.023  6774  6774 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:52:36.743  6774  6831 W jxcore-log: Initializing JXcore engine
,06-30 13:52:36.743  6774  6831 W jxcore-log: JXcore engine is ready
,06-30 13:52:36.803  6774  6831 W jxcore-log: Starting JXcore engine
,06-30 13:52:36.883  6774  6831 W jxcore-log: Platform android
06-30 13:52:36.883  6774  6831 W jxcore-log: 
,06-30 13:52:36.883  6774  6831 W jxcore-log: Process ARCH arm
06-30 13:52:36.883  6774  6831 W jxcore-log: 
,06-30 13:52:37.093  6774  6831 I jxcore-log: JXcore Cordova bridge is ready!,
06-30 13:52:37.093  6774  6831 I jxcore-log: 
06-30 13:52:37.093  6774  6831 W jxcore-log: JXcore engine is started
,06-30 13:52:37.093  6774  6825 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:52:37.093  6774  6774 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 13:52:37.103  6774  6831 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
06-30 13:52:37.103  6774  6831 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-30 13:52:37.113  6774  6774 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,06-30 13:52:37.113  6774  6774 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-30 13:52:37.113   892  1091 I ActivityManager: Killing 6215:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
06-30 13:52:37.113   892  1091 D Process : killProcessQuiet, pid=6215
06-30 13:52:37.113   892  1091 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityStack.destroyActivityLocked:3417 
,06-30 13:52:37.123   892  2082 I ActivityManager: Recipient 6215
,06-30 13:52:37.143  6774  6825 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
06-30 13:52:37.143   892  2082 D Process : killProcessQuiet, pid=6215
06-30 13:52:37.143   892  2082 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 13:52:37.143  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-30 13:52:37.143   892  2082 W libprocessgroup: failed to open /acct/uid_10013/pid_6215/cgroup.procs: No such file or directory
,06-30 13:52:37.143  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,06-30 13:52:37.143  6774  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-30 13:52:37.143  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:52:37.143  6774  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:52:37.143  6774  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-30 13:52:37.143  6774  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2454efcb removed from the list
,06-30 13:52:37.143  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:52:37.143  6774  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d49c666 removed from the list
06-30 13:52:37.143  6774  6774 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:52:37.143  6774  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,06-30 13:52:37.143  6774  6774 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 13:52:37.243   892  1014 D PMS     : releaseHCC(1ab749a9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
06-30 13:52:37.243   892  1014 D PMS     : releaseHCC(1a320b2e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
06-30 13:52:37.243  2358  2374 E MP-Decision: Update arg 1
,06-30 13:52:37.353  6832  6835 E cutils-trace: Error opening trace file: No such file or directory (2),
,06-30 13:52:37.473  6832  6832 D CustomizationManager: ====startRecUseTime====,
06-30 13:52:37.473  6832  6832 D htc.customization.log.level:  is ,
06-30 13:52:37.473  6832  6832 W CustomizationLogLevel: Level value is invalid, use default level 2,
,06-30 13:52:37.643  6832  6832 D CustomizationManager:  Read ACC file spent 0.073 (s)
,06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__001
,06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__E11
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__102
,06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__203
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__405
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__Y13
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__304
,06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__A07
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__032
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__J15
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__016
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__M27
06-30 13:52:37.653  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__A48
,06-30 13:52:37.663  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__K18
06-30 13:52:37.663  6832  6832 D CIDMapFileReader: Parsing tag item name = HTC__002
,06-30 13:52:37.663  6832  6832 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
,06-30 13:52:37.663  6832  6832 I CustomizationCIDLoader: Parsing tag category name = system
,06-30 13:52:37.673  6832  6832 I CustomizationCIDLoader: Parsing tag category name = application
,06-30 13:52:37.673  6832  6832 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,06-30 13:52:37.673  6832  6832 I CustomizationCIDLoader: Parsing tag category name = Settings
,06-30 13:52:37.673  6832  6832 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
,06-30 13:52:37.683  6832  6832 I CustomizationCIDLoader: Parsing tag category name = AudioService
,06-30 13:52:37.683  6832  6832 I CustomizationCIDLoader: Parsing tag category name = ACC
,06-30 13:52:37.683  6832  6832 D CustomizationManager:  Read CID file spent 0.210 (s),
06-30 13:52:37.683  6832  6832 D CustomizationManager:  All configurations done spent 0.210 (s)
,06-30 13:52:37.713  6832  6832 E ActTriggerJNI: open library fail.,
,06-30 13:52:37.733   892  1265 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=6832, uid=2000 userid=0,
,06-30 13:52:37.733   892   987 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=-1: uninstall pkg
06-30 13:52:37.733   892   987 I ActivityManager: Killing 6774:com.test.thalitest/u0a192 (adj 9): stop com.test.thalitest
,06-30 13:52:37.733   892   987 D Process : killProcessQuiet, pid=6774
06-30 13:52:37.733   892   987 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,06-30 13:52:37.763   892  1607 I ActivityManager: Recipient 6774,
06-30 13:52:37.763   892  1079 D WifiService: Client connection lost with reason: 4
,06-30 13:52:37.783   892  1051 W PackageSettings: Skipping PackageSetting{1a6f332c com.example.hello/10380} due to missing metadata,
,06-30 13:52:37.843   892  1051 I ActivityManager: Force stopping com.test.thalitest appid=10192 user=0: pkg removed,
,06-30 13:52:37.873  6272  6272 I art     : Explicit concurrent mark sweep GC freed 413(28KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 260us total 22.377ms,
06-30 13:52:37.883  1504  1504 I art     : Explicit concurrent mark sweep GC freed 18307(1266KB) AllocSpace objects, 18(1343KB) LOS objects, 40% free, 18MB/31MB, paused 670us total 43.121ms
,06-30 13:52:37.903   892  1607 W ActivityManager: Spurious death for ProcessRecord{8fa80cb 6774:com.test.thalitest/u0a192}, curProc for 6774: null,
06-30 13:52:37.903   892   907 D PMS     : acquireWL(a8b07c1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1744 10025 WorkSource{10025 com.google.android.gms}
06-30 13:52:37.913  1197  1197 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
06-30 13:52:37.903   892  1091 D PMS     : releaseWL(a8b07c1): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
06-30 13:52:37.913  1197  1197 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
06-30 13:52:37.913  1197  1197 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
06-30 13:52:37.913  1504  1864 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
06-30 13:52:37.913  1504  1864 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
06-30 13:52:37.913  1504  1504 I Launcher: Deferring update until onResume
06-30 13:52:37.913  1504  1504 D Launcher: waitUntilResume // bindAppsRemoved
06-30 13:52:37.933  1617  2049 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,06-30 13:52:37.953  1458  1458 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
06-30 13:52:37.953  1504  1504 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
06-30 13:52:37.963  1617  2049 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
06-30 13:52:37.963  1578  6865 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
06-30 13:52:37.963  1387  6864 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,06-30 13:52:37.973  1387  6864 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,06-30 13:52:37.983   892   892 I art     : Explicit concurrent mark sweep GC freed 23399(1512KB) AllocSpace objects, 3(90KB) LOS objects, 33% free, 17MB/25MB, paused 1.635ms total 116.437ms
06-30 13:52:37.983   892  2079 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6866 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
06-30 13:52:37.993  1617  2049 E ExternalAccountType: Unsupported attribute readOnly
,06-30 13:52:37.993   892   986 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,06-30 13:52:38.003   892  1076 V NetworkPolicy: ACTION_UID_REMOVED for uid=10192
,06-30 13:52:38.003   892  1076 V NetworkPolicy: writePolicyLocked()
06-30 13:52:38.003   892  1075 D PMS     : acquireWL(3f58613e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 892 1000 null
,06-30 13:52:38.033   892   892 W PackageManager: Unable to load service info ResolveInfo{1a9ff125 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
06-30 13:52:38.033   892   892 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-30 13:52:38.033   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
06-30 13:52:38.033   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
06-30 13:52:38.033   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
06-30 13:52:38.033   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
06-30 13:52:38.033   892   892 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
06-30 13:52:38.033   892   892 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
06-30 13:52:38.033   892   892 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:52:38.033   892   892 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 13:52:38.033   892   892 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.033   892   892 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
06-30 13:52:38.033   892   892 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
06-30 13:52:38.033   892   892 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:52:38.033   892   892 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:38.033   892   892 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
06-30 13:52:38.033   892   892 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,06-30 13:52:38.043   892  1076 V NetworkPolicy: updateNetworkEnabledLocked()
06-30 13:52:38.043   892  1076 V NetworkPolicy: updateNotificationsLocked()
06-30 13:52:38.053  6866  6866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
06-30 13:52:38.063   892  1075 D PMS     : releaseWL(3f58613e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-30 13:52:38.063   892   991 D StatusBarManagerService: setSystemUiVisibility(0x8700)
06-30 13:52:38.063   892   991 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 13:52:38.063   892   991 D StatusBarManagerService: hiding MENU key
06-30 13:52:38.063   892   991 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
06-30 13:52:38.063   892   991 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 13:52:38.063   892   991 D StatusBarManagerService: hiding MENU key
,06-30 13:52:38.073   892  2080 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6774 uid 10192
06-30 13:52:38.073   892  2080 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,06-30 13:52:38.083  1767  1767 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,06-30 13:52:38.083  1767  1767 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
06-30 13:52:38.083   892  1091 D PMS     : acquireWL(285c1644): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1767 10025 WorkSource{10025 com.google.android.gms}
06-30 13:52:38.093   892  1321 D PMS     : releaseWL(285c1644): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10025 com.google.android.gms}
,06-30 13:52:38.103   892   892 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,06-30 13:52:38.103   892   986 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-30 13:52:38.123  4372  4372 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,06-30 13:52:38.123  4372  4372 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
06-30 13:52:38.123  4372  6891 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-30 13:52:38.123  4372  6891 D AccountUtils: Clearing selected account for com.test.thalitest
06-30 13:52:38.123  4372  4372 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-30 13:52:38.123  4372  4372 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,06-30 13:52:38.133  6272  6893 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,06-30 13:52:38.143   892  2082 D PMS     : acquireWL(21164c09): PARTIAL_WAKE_LOCK  AsyncService 0x1 6334 10176 null,
,06-30 13:52:38.143   892  1595 D PMS     : acquireWL(a063d1a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6334 10176 null
06-30 13:52:38.143   892  2073 D PMS     : releaseWL(21164c09): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,06-30 13:52:38.153  4372  6891 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,06-30 13:52:38.153   892  2080 D PMS     : releaseWL(a063d1a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,06-30 13:52:38.183   892  1321 I ActivityManager: Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6899 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a,
,06-30 13:52:38.193   892  1051 I art     : Explicit concurrent mark sweep GC freed 15282(1088KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 2.879ms total 192.312ms
,06-30 13:52:38.203  4372  6898 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1,
06-30 13:52:38.203  4372  6898 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,06-30 13:52:38.203  4372  6898 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.,
06-30 13:52:38.203  4372  6898 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,06-30 13:52:38.213  4372  6898 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
06-30 13:52:38.213  4372  6898 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
06-30 13:52:38.213  4372  6898 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,06-30 13:52:38.223  4372  6898 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
06-30 13:52:38.223  4372  6898 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,06-30 13:52:38.223  4372  6898 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1,
06-30 13:52:38.223  4372  6898 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0,
06-30 13:52:38.223  4372  6898 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0,
06-30 13:52:38.223  4372  6898 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0,
,06-30 13:52:38.233  1767  1767 I ConfigService: onCreate
06-30 13:52:38.233   892   908 D PMS     : acquireWL(3c8156be): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4372 10025 null,
,06-30 13:52:38.233  1767  2126 I art     : Explicit concurrent mark sweep GC freed 12153(670KB) AllocSpace objects, 5(275KB) LOS objects, 48% free, 4MB/8MB, paused 486us total 22.321ms
,06-30 13:52:38.233  4372  4372 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 13:52:38.243   892  2073 D PMS     : releaseWL(3c8156be): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,06-30 13:52:38.243  4372  4372 I ConfigFetchService: service connected
,06-30 13:52:38.253  4372  6916 W BaseAppContext: Using Auth Proxy for data requests.,
06-30 13:52:38.253  6899  6899 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.821083;250001186] pid=6899 dbg=false s=true,
06-30 13:52:38.253  4372  6919 I PeopleContactsSync: CP2 sync disabled
06-30 13:52:38.253   892  1265 D PMS     : acquireWL(7984ed): PARTIAL_WAKE_LOCK  Icing 0x1 4372 10025 WorkSource{10025 com.google.android.gms}
,06-30 13:52:38.253   892  2072 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4372, uid=10025, userID:0,
,06-30 13:52:38.263  6899  6899 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest],
,06-30 13:52:38.263  4372  6916 W BaseAppContext: Using Auth Proxy for data requests.
,06-30 13:52:38.263  4372  4448 I Icing   : doRemovePackageData com.test.thalitest
,06-30 13:52:38.263  6899  6899 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,06-30 13:52:38.263  6899  6899 I DeviceManagement: WorkflowService: Starting workflow service
,06-30 13:52:38.273  6899  6923 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@1634a62e] args=[Bundle[mParcelledData.dataSize=112]],
,06-30 13:52:38.273  6899  6923 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-30 13:52:38.273  6899  6923 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
06-30 13:52:38.273  6899  6923 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,06-30 13:52:38.273  6899  6923 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,06-30 13:52:38.293  6899  6923 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,06-30 13:52:38.293   892  1265 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6924 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,06-30 13:52:38.303  6899  6930 I DeviceManagement: SessionStateController: Checking invariants...
06-30 13:52:38.313  6272  6893 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 177 ms] updated apps [took 177 ms] 
,06-30 13:52:38.373   892  1051 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6943 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=armeabi-v7a
,06-30 13:52:38.423   892  1321 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=6962 uid=10072 gids={50072, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a,
06-30 13:52:38.423   892  1321 I ActivityManager: Killing 6362:com.google.android.talk/u0a120 (adj 15): empty #17
06-30 13:52:38.423   892  1321 D Process : killProcessQuiet, pid=6362
,06-30 13:52:38.423   892  1321 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,06-30 13:52:38.443  6899  6930 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,06-30 13:52:38.453   892  1358 I ActivityManager: Recipient 6362
,06-30 13:52:38.463   479   479 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 13:52:38.543   892  2072 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=6980 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,06-30 13:52:38.543   892  1358 D Process : killProcessQuiet, pid=6362
06-30 13:52:38.553   892  1358 W libprocessgroup: failed to open /acct/uid_10120/pid_6362/cgroup.procs: No such file or directory
06-30 13:52:38.553   892  1358 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-30 13:52:38.553  6962  6962 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 13:52:38.563  6899  6923 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
06-30 13:52:38.563   892  1321 D Process : killProcessQuiet, pid=6388
06-30 13:52:38.563   892  1321 I ActivityManager: Killing 6388:com.htc.sense.mms/u0a67 (adj 15): empty #17
06-30 13:52:38.563   892  1321 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.attachApplicationLocked:6627 
,06-30 13:52:38.563   470   470 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 245us total 19.231ms
,06-30 13:52:38.563  6899  6923 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@1634a62e],
,06-30 13:52:38.573   892  2082 I ActivityManager: Recipient 6388
,06-30 13:52:38.583   470   470 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 225us total 16.084ms
,06-30 13:52:38.593   470   470 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 130us total 14.940ms
,06-30 13:52:38.613   892  2082 D Process : killProcessQuiet, pid=6388
,06-30 13:52:38.613   892  2082 W libprocessgroup: failed to open /acct/uid_10067/pid_6388/cgroup.procs: No such file or directory
06-30 13:52:38.613  6899  6899 I DeviceManagement: WorkflowService: Stopping workflow service
06-30 13:52:38.613   892  2082 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 13:52:38.613   892  1350 I ActivityManager: Killing 6485:com.htc.mms.backupagent/u0a79 (adj 15): empty #17
06-30 13:52:38.613   892  1350 D Process : killProcessQuiet, pid=6485
,06-30 13:52:38.613   892  1350 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-30 13:52:38.623   892   908 I ActivityManager: Recipient 6485,
,06-30 13:52:38.623  6980  6980 D ExternalStorage: After updating volumes, found 1 active roots
,06-30 13:52:38.643   892   908 D Process : killProcessQuiet, pid=6485
06-30 13:52:38.643   892   908 W libprocessgroup: failed to open /acct/uid_10079/pid_6485/cgroup.procs: No such file or directory
06-30 13:52:38.643   892   908 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-30 13:52:38.643  6583  6583 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,06-30 13:52:38.643  6583  7003 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,06-30 13:52:38.643  6583  7003 D PowerUsageService: removed uid = 10192
,06-30 13:52:38.673   892  1350 I ActivityManager: Killing 6553:com.htc.bgp/u0a11 (adj 15): empty #17,
06-30 13:52:38.673   892  1350 D Process : killProcessQuiet, pid=6553
06-30 13:52:38.673   892  1350 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,06-30 13:52:38.683   892  1585 I ActivityManager: Recipient 6553,
,06-30 13:52:38.693   892  1585 D Process : killProcessQuiet, pid=6553,
06-30 13:52:38.693   892  1585 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 13:52:38.693   892  1585 W libprocessgroup: failed to open /acct/uid_10011/pid_6553/cgroup.procs: No such file or directory
,06-30 13:52:38.693  4372  6896 W DriveInitializer: Awaiting to be initialized
,06-30 13:52:38.693  4372  7008 W DriveInitializer: Background init thread started
,06-30 13:52:38.743   363   409 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.gms/files/,
,06-30 13:52:38.753   363   409 W Vold    : Returning OperationFailed - no handler for errno 0
06-30 13:52:38.753  4372  7008 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.gms/files
,06-30 13:52:38.763  4372  7010 E SQLiteLog: (3850) statement aborts at 167: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,06-30 13:52:38.763  4372  7010 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0xb98de108
,06-30 13:52:38.763  6293  6293 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 13:52:38.763  6293  6293 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 13:52:38.773  4372  7010 E DocListDatabase: Failed to delete from FileContent112,
06-30 13:52:38.773  4372  7010 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 13:52:38.773  4372  7010 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: FATAL EXCEPTION: pool-12-thread-1
06-30 13:52:38.773  4372  7010 E AndroidRuntime: Process: com.google.android.gms, PID: 4372
06-30 13:52:38.773  4372  7010 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
,06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 13:52:38.773  4372  7010 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:38.773   892  1265 E ActivityManager: App crashed! Process: com.google.android.gms
06-30 13:52:38.773  4372  7010 D Process : killProcess, pid=4372
06-30 13:52:38.783  4372  7010 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
06-30 13:52:38.783   892  7015 E DropBoxManagerService: Can't write: system_app_crash
06-30 13:52:38.783   892  7015 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.783   892  7015 E DropBoxManagerService: 	... 5 more
06-30 13:52:38.803   892  2082 D Process : killProcessQuiet, pid=4372
06-30 13:52:38.803   892  2082 I ActivityManager: Recipient 4372
06-30 13:52:38.803   892  2082 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
06-30 13:52:38.803   892  1091 D PMS     : handleWLDeath(7984ed): PARTIAL_WAKE_LOCK  Icing 0x1
06-30 13:52:38.803   892  1079 D WifiService: Client connection lost with reason: 4
06-30 13:52:38.803  6924  6960 D Documents: Update found 7 roots in 414ms
,06-30 13:52:38.823   892  2082 I ActivityManager: Process com.google.android.gms (pid 4372) has died
06-30 13:52:38.823  1767  1767 I ConfigService: onDestroy
06-30 13:52:38.823   892  2082 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
06-30 13:52:38.823   892  2082 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
06-30 13:52:38.823   892  2082 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
06-30 13:52:38.823   892  2082 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
,06-30 13:52:38.863  6924  7001 D Documents: Update found 7 roots in 237ms
,06-30 13:52:39.413  1504  1864 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
06-30 13:52:39.413  1504  1864 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@24181af7 +,
,06-30 13:52:39.413  1504  1864 I Prism.WidgetManager: onLoadItems() +,
,06-30 13:52:39.543  1504  1864 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,06-30 13:52:39.683  1504  1864 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,06-30 13:52:39.753  1504  1864 E Prism.WidgetManager: The same lists. No need to update. skip it.,
06-30 13:52:39.753  1504  1864 I Prism.WidgetManager: onLoadItems() -
06-30 13:52:39.753  1504  1864 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@24181af7 -
,06-30 13:52:39.763  1504  1864 E SQLiteLog: (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=73] disk I/O error,
06-30 13:52:39.763  1504  1864 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xb97966f0
,06-30 13:52:39.763  1504  1864 E AndroidRuntime: FATAL EXCEPTION: TaskWorker,
06-30 13:52:39.763  1504  1864 E AndroidRuntime: Process: com.htc.launcher, PID: 1504
06-30 13:52:39.763  1504  1864 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	,at android.content.ContentResolver.delete(ContentResolver.java:1320)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156),
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: ,	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:39.763  1504  1864 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:39.763   892   908 E ActivityManager: App crashed! Process: com.htc.launcher,
06-30 13:52:39.773   892   908 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 13:52:39.773   892   908 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:39.793   892   908 W ActivityManager:   Force finishing activity com.htc.launcher/.Launcher
06-30 13:52:39.773   892  1549 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 13:52:39.793   892  7029 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 13:52:39.793   892  7029 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1467287559799.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 13:52:39.793   892  7029 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:39.793   892  7029 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:39.793   892  7029 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:39.793   892  7029 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:460)
06-30 13:52:39.793   892  7029 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:39.793   892  7029 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:39.793   892  7029 E ErrorReport: 	at libcore.io.Posix.open(Native Method),
06-30 13:52:39.793   892  7029 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:39.793   892  7029 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:39.793   892  7029 E ErrorReport: 	... 4 more
06-30 13:52:39.783   892   908 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:39.783   892   908 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:39.783   892   908 W System.err: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:39.783   892   908 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:39.783   892   908 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
,06-30 13:52:39.783   892   908 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
06-30 13:52:39.783   892   908 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:309)
06-30 13:52:39.783   892   908 W System.err: ,	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
06-30 13:52:39.783   892   908 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
06-30 13:52:39.783   892   908 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:39.783   892   908 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system),
06-30 13:52:39.783   892   908 W System.err: 	at libcore.io.Posix.open(Native Method)
,06-30 13:52:39.783   892   908 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:39.783   892   908 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:39.783   892   908 W System.err: 	... 14 more
06-30 13:52:39.783   892   908 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:39.783   892   908 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:39.783   892   908 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:39.783   892   908 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:39.783   892   908 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:39.783   892   908 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
06-30 13:52:39.783   892   908 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
06-30 13:52:39.783   892   908 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:310)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:262)
06-30 13:52:39.783   892   908 W System.err: ,	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12555)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12219)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12191)
06-30 13:52:39.783   892   908 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
06-30 13:52:39.783   892   908 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2572)
06-30 13:52:39.783   892   908 W System.err: 	,at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:39.783   892   908 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:39.783   892   908 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:39.783   892   908 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:39.783   892   908 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:39.783   892   908 W System.err: 	... 14 more
06-30 13:52:39.793  1504  1864 D Process : killProcess, pid=1504
06-30 13:52:39.793  1504  1864 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
,06-30 13:52:39.803   892  1549 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:39.803   892  1549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:39.803   892  1549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,06-30 13:52:39.803   892  1549 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,06-30 13:52:39.803   892  1549 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 13:52:39.803   892  1549 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 13:52:39.803   892  1549 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 13:52:39.803   892  1549 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 13:52:39.803   892  1549 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 13:52:39.803   892  1549 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 13:52:39.803   892  1549 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:39.803   892  1549 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:39.803   892  1549 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:39.803   892  1549 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:39.803   892  1549 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:39.803   892  1549 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:39.803   892  1549 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:39.803   892  1549 W System.err: 	... 12 more
,06-30 13:52:39.833   892  1585 I ActivityManager: Recipient 1504
,06-30 13:52:39.833   892  2073 I WindowState: WIN DEATH: Window{3f5a6b46 u0 com.htc.launcher/com.htc.launcher.Launcher}
06-30 13:52:39.843   892   987 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.icing.service.IndexWorkerService: pid=7033 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
06-30 13:52:39.843   892  1585 D Process : killProcessQuiet, pid=1504
06-30 13:52:39.843   892  1585 D Process : com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,06-30 13:52:39.863   892  1585 I ActivityManager: Process com.htc.launcher (pid 1504) has died
,06-30 13:52:39.863   892  1585 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 on display 0
06-30 13:52:39.863  2358  2374 E MP-Decision: Update arg "0 380 380 380".
06-30 13:52:39.863  2358  2374 E MP-Decision: Update arg "0 400 400 400".
,06-30 13:52:39.903   892  1585 I ActivityManager: Start proc com.htc.launcher for activity com.htc.launcher/.Launcher: pid=7061 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 5001, 1023} abi=armeabi-v7a

```
