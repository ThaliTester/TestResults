#### Test 8080757327567ab_thali02_LGE-LG-D855 Logs


```
--------- beginning of system
08-12 12:55:34.475  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=561954986 [*alarm*], flags=0x0
,--------- beginning of main
08-12 12:55:38.534  6776  6776 D AndroidRuntime: 
08-12 12:55:38.534  6776  6776 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 12:55:38.540  6776  6776 D AndroidRuntime: CheckJNI is OFF
08-12 12:55:38.743  6776  6776 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 12:55:38.754  1036  2021 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 12:55:38.771  1979  2004 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 12:55:38.776  1036  2021 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 12:55:38.778  1036  2021 D ActivityManager: setTaskToReturnTo : TaskRecord{e7d7742 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 12:55:38.778  1036  2021 D ActivityManager: setTaskToReturnTo : TaskRecord{e7d7742 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 12:55:38.780  1036  2021 D WindowStateEx: AppWindowTokenEx init.. 
08-12 12:55:38.780   334   340 E GBMv2   : DFP En is all cleared set to be enabled
08-12 12:55:38.809  1036  2021 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6791 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 12:55:38.811  6776  6776 D AndroidRuntime: Shutting down VM
08-12 12:55:38.865  1979  2003 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 12:55:38.865  1979  2003 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2e52a7cf co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 12:55:38.866  1979  2568 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 12:55:38.867  1979  2568 D SplitWindowPolicy: topRunningActivity=ActivityInfo{16cb55c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 12:55:38.922  6791  6791 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-12 12:55:38.997  6791  6791 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 12:55:39.003  6791  6791 I LibraryLoader: Loading: webviewchromium
08-12 12:55:39.006  6791  6791 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8277-8279)
08-12 12:55:39.006  6791  6791 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 12:55:39.022  6791  6791 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9276955}
08-12 12:55:39.023  6791  6791 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 12:55:39.023  6791  6791 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-12 12:55:39.033  6791  6791 I BrowserStartupController: Initializing chromium process, renderers=0
08-12 12:55:39.034  6791  6791 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 12:55:39.044  6791  6791 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 12:55:39.045  6791  6791 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-12 12:55:39.045  6791  6791 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 12:55:39.056   314   314 V AudioPolicyService: registerClient() client 0xb558a380, uid 10118
,08-12 12:55:39.057  6791  6791 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 12:55:39.057  6791  6791 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 12:55:39.057  6791  6791 I Adreno-EGL: Build Date: 12/12/14 금
08-12 12:55:39.057  6791  6791 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 12:55:39.057  6791  6791 I Adreno-EGL: Remote Branch: 
08-12 12:55:39.057  6791  6791 I Adreno-EGL: Local Patches: 
08-12 12:55:39.057  6791  6791 I Adreno-EGL: Reconstruct Branch: 
08-12 12:55:39.069  1036  1118 D BluetoothManagerService: Message: 20
08-12 12:55:39.069  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@206789bc:true
,08-12 12:55:39.151  6791  6831 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 12:55:39.158  6791  6791 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-12 12:55:39.173  6791  6791 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 12:55:39.178  6791  6791 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 12:55:39.181  6791  6791 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 12:55:39.184  6791  6791 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 12:55:39.184  6791  6791 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 12:55:39.199  6791  6791 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 12:55:39.208  6791  6791 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 12:55:39.208  6791  6791 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 12:55:39.243  6791  6844 D OpenGLRenderer: Render dirty regions requested: true
08-12 12:55:39.244  6791  6844 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 12:55:39.252  6791  6844 D OpenGLRenderer: Enabling debug mode 0
,08-12 12:55:39.268  6791  6791 D Atlas   : Validating map...
,08-12 12:55:39.273  1036  1052 D SplitWindow: check instance of lgWin Window{4604716 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 12:55:39.360  6791  6842 D LgDataFeature: LgDataFeature() Constructor: none
08-12 12:55:39.360  6791  6842 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-12 12:55:39.404  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +539ms (total +622ms)
08-12 12:55:39.404  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{24ce1353 u0 com.test.thalitest/.MainActivity t6} time:298678
,08-12 12:55:39.416  6791  6791 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d09a428 time:298690
08-12 12:55:39.531  6791  6791 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 12:55:39.531  6791  6791 I chromium: 
,08-12 12:55:39.585  6791  6791 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 12:55:39.657  6791  6842 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 12:55:39.657  6791  6842 I chromium: 
,08-12 12:55:39.799  6791  6857 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,08-12 12:55:39.811  6791  6857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 12:55:39.811  6791  6857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 12:55:39.811  6791  6857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 12:55:39.811  6791  6857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 12:55:39.811  6791  6857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 12:55:39.811  6791  6857 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b44b06c added. We now have 1 listener(s)
08-12 12:55:39.817  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 12:55:39.819  6791  6857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-12 12:55:39.821  6791  6857 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 12:55:39.823  6791  6857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 12:55:39.823  6791  6857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 12:55:39.830  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 12:55:39.831  6791  6857 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e0343b added. We now have 1 listener(s)
08-12 12:55:39.831  6791  6857 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 12:55:39.835  1036  1457 D WifiService: New client listening to asynchronous messages
,08-12 12:55:39.841  6791  6857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 12:55:39.841  6791  6857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 12:55:39.841  6791  6857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 12:55:39.841  6791  6857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 12:55:39.841  6791  6857 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 12:55:39.847  6791  6857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 12:55:39.847  1036  2096 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-12 12:55:39.850  6791  6857 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 12:55:39.862  6791  6857 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-12 12:55:39.864  6791  6857 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 12:55:39.864  6791  6857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 12:55:39.864  6791  6857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 12:55:39.864  6791  6857 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 12:55:39.864  6791  6857 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 12:55:39.864  6791  6857 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 12:55:39.864  6791  6857 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-12 12:55:39.864  6791  6857 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 12:55:39.864  6791  6857 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 12:55:39.864  6791  6857 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 12:55:39.866  6791  6857 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 12:55:39.867  6791  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 12:55:39.868  6791  6791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 12:55:39.896  6791  6791 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 12:55:40.485   334   342 E GBMv2   : DFP En is all cleared set to be enabled
08-12 12:55:40.485   334   342 E GBMv2   : Set value is all cleared set the max
08-12 12:55:40.485   334   342 I GBMv2   : DFP Enabled. Ignore VFP set
,08-12 12:55:41.342  6791  6860 W jxcore-log: Initializing JXcore engine
08-12 12:55:41.342  6791  6860 W jxcore-log: JXcore engine is ready
,08-12 12:55:41.411  6860  6860 W Thread-771: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6100]" dev="sockfs" ino=6100 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 12:55:41.411  6860  6860 W Thread-771: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 12:55:41.411  6860  6860 W Thread-771: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10375]" dev="sockfs" ino=10375 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 12:55:41.411  6860  6860 W Thread-771: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 12:55:41.411  6860  6860 W Thread-771: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33287]" dev="sockfs" ino=33287 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 12:55:41.445  6791  6860 W jxcore-log: Starting JXcore engine
,08-12 12:55:41.596  6791  6860 W jxcore-log: Platform android
08-12 12:55:41.596  6791  6860 W jxcore-log: 
08-12 12:55:41.596  6791  6860 W jxcore-log: Process ARCH arm
08-12 12:55:41.596  6791  6860 W jxcore-log: 

```
