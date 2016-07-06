#### Test 757892685041341_thali09_HTC-HTC One_M8 Logs


```
--------- beginning of main,
07-06 14:35:11.323   485   485 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
07-06 14:35:11.693  6848  6858 E cutils-trace: Error opening trace file: No such file or directory (2)
07-06 14:35:11.713  6848  6848 D CustomizationManager: ====startRecUseTime====
07-06 14:35:11.713  6848  6848 D htc.customization.log.level:  is 
07-06 14:35:11.713  6848  6848 W CustomizationLogLevel: Level value is invalid, use default level 2
07-06 14:35:11.783  6848  6848 D CustomizationManager:  Read ACC file spent 0.041 (s)
07-06 14:35:11.783  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__001
07-06 14:35:11.783  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__E11
07-06 14:35:11.783  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__102
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__203
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__405
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__304
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__032
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__016
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__A48
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__K18
07-06 14:35:11.793  6848  6848 D CIDMapFileReader: Parsing tag item name = HTC__002
07-06 14:35:11.793  6848  6848 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__032.xml
07-06 14:35:11.793  6848  6848 I CustomizationCIDLoader: Parsing tag category name = system
07-06 14:35:11.793  6848  6848 I CustomizationCIDLoader: Parsing tag category name = application
07-06 14:35:11.803  6848  6848 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-06 14:35:11.803  6848  6848 I CustomizationCIDLoader: Parsing tag category name = Settings
07-06 14:35:11.803  6848  6848 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-06 14:35:11.803  6848  6848 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-06 14:35:11.803  6848  6848 I CustomizationCIDLoader: Parsing tag category name = ACC
07-06 14:35:11.803  6848  6848 D CustomizationManager:  Read CID file spent 0.088 (s)
07-06 14:35:11.803  6848  6848 D CustomizationManager:  All configurations done spent 0.089 (s)
07-06 14:35:11.823  6848  6848 E ActTriggerJNI: open library fail.
07-06 14:35:11.833  2302  2317 E MP-Decision: Update arg 2
--------- beginning of system
07-06 14:35:11.833   976  1600 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-06 14:35:11.843  2302  2317 E MP-Decision: Update arg 4
07-06 14:35:11.843   976  1046 D PMS     : acquireHCC(26e0ad19): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 976 1000 null
07-06 14:35:11.843   976  1046 D PMS     : acquireHCC(3cbd81de): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 976 1000 null
07-06 14:35:11.843  2302  2317 E MP-Decision: Update arg "0 190 240 240".
07-06 14:35:11.843  2302  2317 E MP-Decision: Update arg "0 75 400 400".
07-06 14:35:11.873   976  1600 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6878 uid=10192 gids={50192, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-06 14:35:11.893   976   976 V ActivityManager: Display changed displayId=0
07-06 14:35:11.893  1200  1200 D DotMatrix: [EventService]  onDisplayChanged: 0
07-06 14:35:11.893  1200  1200 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
07-06 14:35:11.933  1493  1493 I TrimMemoryManager: [trimMemory] 20
07-06 14:35:11.973  6878  6878 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-06 14:35:11.983  6878  6878 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1156-1158)
07-06 14:35:11.983  6878  6878 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 14:35:11.993  6878  6878 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d337abc}
07-06 14:35:11.993  6878  6878 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 14:35:12.003  6878  6878 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-06 14:35:12.013  6878  6878 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-06 14:35:12.013  6878  6878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 14:35:12.013  6878  6878 E SysUtils: ApplicationContext is null in ApplicationStatus
07-06 14:35:12.023  6878  6878 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-06 14:35:12.033  6878  6878 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-06 14:35:12.033  6878  6878 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-06 14:35:12.033  6878  6878 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
07-06 14:35:12.033  6878  6878 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-06 14:35:12.033  6878  6878 I Adreno-EGL: Build Date: 12/11/14 Thu
07-06 14:35:12.033  6878  6878 I Adreno-EGL: Local Branch: 
07-06 14:35:12.033  6878  6878 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
07-06 14:35:12.033  6878  6878 I Adreno-EGL: Local Patches: NONE
07-06 14:35:12.033  6878  6878 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-06 14:35:12.083   976  1596 W System.err: java.lang.Throwable: stack dump
07-06 14:35:12.083   976  1596 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-06 14:35:12.083   976  1596 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
07-06 14:35:12.083   976  1596 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-06 14:35:12.083   976  1596 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-06 14:35:12.083   976  1015 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-06 14:35:12.083   976  1015 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f1d968d:true
,07-06 14:35:12.093  6878  6913 D BluetoothAdapter: 565163457: getState(). Returning 12
,07-06 14:35:12.153  6878  6878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 14:35:12.153  6878  6878 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-06 14:35:12.163  6878  6878 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-06 14:35:12.173  6878  6878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-06 14:35:12.173  6878  6878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 14:35:12.223  6878  6878 D Atlas   : Validating map...
,07-06 14:35:12.223   976  1541 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-06 14:35:12.223  6878  6911 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-06 14:35:12.243   976  1014 D StatusBarManagerService: setSystemUiVisibility(0xc0000600)
07-06 14:35:12.243   976  1014 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-06 14:35:12.243   976  1014 D StatusBarManagerService: hiding MENU key
,07-06 14:35:12.253   976  1014 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-06 14:35:12.253   976  1014 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-06 14:35:12.253   976  1014 D StatusBarManagerService: hiding MENU key
,07-06 14:35:12.283  6878  6878 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@20c0f6d, mServedView=org.apache.cordova.engine.SystemWebView{2723f7a2 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@90ffc33
,07-06 14:35:12.283   976  1088 I InputMethodManagerService: Disable input method client, pid=1493
,07-06 14:35:12.283   976  1088 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,07-06 14:35:12.303  6878  6878 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-06 14:35:12.323   976  1020 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +420ms (total +480ms)
,07-06 14:35:12.373  6878  6878 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6878
,07-06 14:35:12.453  6878  6878 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-06 14:35:12.513  6878  6878 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
,07-06 14:35:12.543  6878  6928 D jxcore_app_log: JniHelper::setJavaVM(0xb745fb98), pthread_self() = -1200563632
,07-06 14:35:12.553  6878  6928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-06 14:35:12.553  6878  6928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-06 14:35:12.553  6878  6928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-06 14:35:12.553  6878  6928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-06 14:35:12.553  6878  6928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-06 14:35:12.553  6878  6928 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b438ac6 added. We now have 1 listener(s)
07-06 14:35:12.553   976  1602 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-06 14:35:12.553  6878  6928 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 50:2E:6C:AC:21:50
07-06 14:35:12.563  6878  6928 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "50:2E:6C:AC:21:50"
07-06 14:35:12.563  6878  6928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-06 14:35:12.563  6878  6928 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 50:2E:6C:AC:21:50
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-06 14:35:12.563  6878  6928 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a5caddd added. We now have 1 listener(s)
07-06 14:35:12.563  6878  6928 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-06 14:35:12.563   976  1077 D WifiService: New client listening to asynchronous messages
07-06 14:35:12.563   976   976 E WifiTrafficPoller: ADD_CLIENT: 8
,07-06 14:35:12.563  6878  6928 D BluetoothAdapter: 565163457: getState(). Returning 12
,07-06 14:35:12.573  6878  6928 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-06 14:35:12.573  6878  6928 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-06 14:35:12.573  6878  6928 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-06 14:35:12.573  6878  6928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-06 14:35:12.573   976  1316 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-06 14:35:12.573  6878  6928 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 50:2E:6C:AC:21:50
,07-06 14:35:12.573  6878  6928 D BluetoothAdapter: 565163457: getState(). Returning 12
07-06 14:35:12.573  6878  6928 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 14:35:12.573  6878  6928 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 14:35:12.573  6878  6928 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-06 14:35:12.573  6878  6928 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 14:35:12.573  6878  6928 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 14:35:12.573  6878  6928 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 14:35:12.573  6878  6928 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 14:35:12.573  6878  6928 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-06 14:35:12.573  6878  6928 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-06 14:35:12.573  6878  6928 D io.jxcore.node.ConnectivityMonitor: start: OK
07-06 14:35:12.573  6878  6928 I io.jxcore.node.LifeCycleMonitor: start: OK
07-06 14:35:12.573  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-06 14:35:12.583  6878  6878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,07-06 14:35:12.593  6878  6878 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,07-06 14:35:13.303  6878  6935 W jxcore-log: Initializing JXcore engine,
07-06 14:35:13.303  6878  6935 W jxcore-log: JXcore engine is ready
,07-06 14:35:13.353  6878  6935 W jxcore-log: Starting JXcore engine
,07-06 14:35:13.423  6878  6935 W jxcore-log: Platform android,
07-06 14:35:13.423  6878  6935 W jxcore-log: 
07-06 14:35:13.423  6878  6935 W jxcore-log: Process ARCH arm
07-06 14:35:13.423  6878  6935 W jxcore-log: 
,07-06 14:35:13.603  6878  6935 I jxcore-log: JXcore Cordova bridge is ready!,
07-06 14:35:13.603  6878  6935 I jxcore-log: 
07-06 14:35:13.613  6878  6935 W jxcore-log: JXcore engine is started
,07-06 14:35:13.833   976  1046 D PMS     : releaseHCC(26e0ad19): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
07-06 14:35:13.833   976  1046 D PMS     : releaseHCC(3cbd81de): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
07-06 14:35:13.833  2302  2317 E MP-Decision: Update arg 1
,07-06 14:35:14.273   976  2203 D PMS     : acquireWL(35fd79d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 976 1000 null,
07-06 14:35:14.303   976   976 D UsbnetService: BroadcastReceiver::onReceive+
07-06 14:35:14.273   976  2203 I BatteryService: n_update end
07-06 14:35:14.303  1200  1200 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-06 14:35:14.303  1200  1200 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
07-06 14:35:14.303   976   976 D NotificationService: plugged=true pluggin=true
07-06 14:35:14.303  1200  1200 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
07-06 14:35:14.313  1122  1122 D PowerUI : closing low battery warning: level=100
07-06 14:35:14.313   976   976 D UsbnetService: onReceive BATTERY_CHANGED
07-06 14:35:14.313   976  1077 D WifiController: battery changed pluggedType: 2,
07-06 14:35:14.313   976   976 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
07-06 14:35:14.313  1122  1122 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
07-06 14:35:14.313   976   976 D UsbnetService: BroadcastReceiver::onReceive-
,07-06 14:35:14.333   976  1038 D HtcPowerSaver: updateBatteryInfo
07-06 14:35:14.323  1122  1305 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
07-06 14:35:14.333   976   976 D PMS     : runPSCheck
07-06 14:35:14.323  3079  3158 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-06 14:35:14.333   976   976 D HtcPowerSaver: Checking...
07-06 14:35:14.333   976   976 I HtcPowerSaver: >> updateStatus
07-06 14:35:14.333   976  2203 D PMS     : releaseWL(35fd79d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
07-06 14:35:14.333   976   976 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1),
07-06 14:35:14.333   976   976 I HtcPowerSaver: << updateStatus
07-06 14:35:14.343  6541  6541 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,07-06 14:35:14.363  6376  6376 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
07-06 14:35:14.363  6376  6376 D         : Cust_ConnectToPC   : Internet_Sharing>true,
,07-06 14:35:14.363  6376  6376 D         : Cust_ConnectToPC   : Modem_Link>false
07-06 14:35:14.363  6376  6376 D         : Cust_ConnectToPC   : spcsc>false
07-06 14:35:14.363  6376  6376 D         : Cust_ConnectToPC   : IPT>true,
07-06 14:35:14.363  6376  6376 D         : Cust_ConnectToPC   : Singel_USB>false
,07-06 14:35:14.363  6376  6376 D SmartNS_NSReceiver: project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
07-06 14:35:14.363  6376  6376 D SmartNS_NSReceiver: Index of the first 1 = 3
,07-06 14:35:14.373  6376  6376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 ,
,07-06 14:35:14.373  1122  1122 I BatteryController: status:5 level:100 unsupport:false plugged:true
,07-06 14:35:14.373  6376  6376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
,07-06 14:35:14.383  6376  6376 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,07-06 14:35:14.383  6376  6376 E SmartNS_Utility: hasRemovableStorageSlot: true,
07-06 14:35:14.383  6376  6376 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
07-06 14:35:14.383  6376  6376 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false,
,07-06 14:35:14.393  6376  6376 D SmartNS_Utility: [ACC]android_networking:tethering_guard_support=false,
07-06 14:35:14.393  6376  6376 W SystemReader: Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 8 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age,
07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 1 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age,
,07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 3 BSSID 34:4d:f7:73:42:46 SSID '_Aya' due to wpa_bss_flush_by_age
07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 13 BSSID 00:1a:ef:42:f2:b0 SSID 'Conrad_AP' due to wpa_bss_flush_by_age,
07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 5 BSSID 84:b2:61:1a:ce:70 SSID '\x00' due to wpa_bss_flush_by_age
,07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 12 BSSID dc:09:4c:a5:12:54 SSID 'WLAN-MTF90F' due to wpa_bss_flush_by_age
07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 14 BSSID e4:aa:5d:fc:5b:f4 SSID '\x00' due to wpa_bss_flush_by_age,
07-06 14:35:22.343  1361  1361 D wpa_supplicant: wlan0: BSS: Remove id 6 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS' due to wpa_bss_flush_by_age,
07-06 14:35:22.343   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 f0:f2:6d:22:99:3e]
,07-06 14:35:22.343   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 f0:f2:6d:22:99:3e
,07-06 14:35:22.343   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1]
07-06 14:35:22.343   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 00:1f:27:54:70:c1,
07-06 14:35:22.343   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0]
,07-06 14:35:22.343   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c0
,07-06 14:35:22.343   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 34:4d:f7:73:42:46]
07-06 14:35:22.343   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 34:4d:f7:73:42:46,
,07-06 14:35:22.343   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1a:ef:42:f2:b0],
,07-06 14:35:22.343   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:1a:ef:42:f2:b0
,07-06 14:35:22.343   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 84:b2:61:1a:ce:70]
,07-06 14:35:22.343   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 84:b2:61:1a:ce:70
,07-06 14:35:22.353   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 dc:09:4c:a5:12:54]
07-06 14:35:22.353   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 dc:09:4c:a5:12:54,
07-06 14:35:22.353   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 e4:aa:5d:fc:5b:f4]
,07-06 14:35:22.353   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 e4:aa:5d:fc:5b:f4
,07-06 14:35:22.353   976  1551 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 84:b2:61:1a:ce:73]
,07-06 14:35:22.353   976  1551 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 84:b2:61:1a:ce:73

```
