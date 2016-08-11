#### Test 80912877b687439_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-11 10:50:00.089  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
08-11 10:50:00.100  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 10:50:00.100  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-11 10:50:00.101  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-11 10:50:00.102  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 10:50:10.856  6826  6826 D AndroidRuntime: 
08-11 10:50:10.856  6826  6826 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 10:50:10.861  6826  6826 D AndroidRuntime: CheckJNI is OFF
08-11 10:50:10.989  6826  6826 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 10:50:10.995  1036  1775 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 10:50:11.003  1974  3997 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-11 10:50:11.007  1036  1775 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-11 10:50:11.008  1036  1775 D ActivityManager: setTaskToReturnTo : TaskRecord{1130d35 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 10:50:11.008  1036  1775 D ActivityManager: setTaskToReturnTo : TaskRecord{1130d35 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 10:50:11.008  1036  1775 D WindowStateEx: AppWindowTokenEx init.. 
08-11 10:50:11.009   348   365 E GBMv2   : DFP En is all cleared set to be enabled
08-11 10:50:11.029  1036  1775 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6847 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 10:50:11.031  6826  6826 D AndroidRuntime: Shutting down VM
08-11 10:50:11.077  1974  1989 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-11 10:50:11.077  1974  1989 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a5fc26a co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 10:50:11.078  1974  1993 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-11 10:50:11.078  1974  1993 D SplitWindowPolicy: topRunningActivity=ActivityInfo{ffe435b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 10:50:11.132  6847  6847 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 10:50:11.198  6847  6847 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-11 10:50:11.210  6847  6847 I LibraryLoader: Loading: webviewchromium
08-11 10:50:11.214  6847  6847 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1060-1064)
08-11 10:50:11.215  6847  6847 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 10:50:11.232  6847  6847 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {215e05a8}
,08-11 10:50:11.234  6847  6847 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 10:50:11.234  6847  6847 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 10:50:11.243  6847  6847 I BrowserStartupController: Initializing chromium process, renderers=0
08-11 10:50:11.244  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 10:50:11.264  6847  6847 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-11 10:50:11.266  6847  6847 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-11 10:50:11.266  6847  6847 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-11 10:50:11.269   331  1398 V AudioPolicyService: registerClient() client 0xb558aae0, uid 10118
08-11 10:50:11.280  1036  1118 D BluetoothManagerService: Message: 20
08-11 10:50:11.280  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@faff817:true
,08-11 10:50:11.291  6847  6847 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 10:50:11.291  6847  6847 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 10:50:11.291  6847  6847 I Adreno-EGL: Build Date: 12/12/14 금
08-11 10:50:11.291  6847  6847 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 10:50:11.291  6847  6847 I Adreno-EGL: Remote Branch: 
08-11 10:50:11.291  6847  6847 I Adreno-EGL: Local Patches: 
08-11 10:50:11.291  6847  6847 I Adreno-EGL: Reconstruct Branch: 
,08-11 10:50:11.361  6847  6876 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-11 10:50:11.365  6847  6847 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-11 10:50:11.383  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 10:50:11.388  6847  6847 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 10:50:11.392  6847  6847 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 10:50:11.395  6847  6847 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 10:50:11.395  6847  6847 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 10:50:11.411  6847  6847 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-11 10:50:11.418  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 10:50:11.418  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 10:50:11.450  6847  6888 D OpenGLRenderer: Render dirty regions requested: true
08-11 10:50:11.450  6847  6888 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 10:50:11.458  6847  6888 D OpenGLRenderer: Enabling debug mode 0
08-11 10:50:11.474  6847  6847 D Atlas   : Validating map...
08-11 10:50:11.478  1036  2094 D SplitWindow: check instance of lgWin Window{273df159 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 10:50:11.517  6847  6886 D LgDataFeature: LgDataFeature() Constructor: none
08-11 10:50:11.518  6847  6886 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 10:50:11.616  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +541ms (total +607ms)
08-11 10:50:11.617  6847  6847 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2db1a897 time:171467
08-11 10:50:11.617  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f20f5ca u0 com.test.thalitest/.MainActivity t6} time:171467
08-11 10:50:11.737  6847  6847 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-11 10:50:11.737  6847  6847 I chromium: 
08-11 10:50:11.770  6847  6847 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-11 10:50:11.855  6847  6886 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-11 10:50:11.855  6847  6886 I chromium: 
08-11 10:50:11.982  6847  6899 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
08-11 10:50:11.998  6847  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 10:50:11.998  6847  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 10:50:11.998  6847  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 10:50:11.998  6847  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 10:50:11.998  6847  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 10:50:11.998  6847  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65f59ab added. We now have 1 listener(s)
08-11 10:50:12.004  1036  1994 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 10:50:12.011  6847  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-11 10:50:12.013  6847  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 10:50:12.015  6847  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 10:50:12.015  6847  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 10:50:12.017   348   367 E GBMv2   : DFP En is all cleared set to be enabled
08-11 10:50:12.017   348   367 E GBMv2   : Set value is all cleared set the max
08-11 10:50:12.017   348   367 I GBMv2   : DFP Enabled. Ignore VFP set
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 10:50:12.027  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 10:50:12.028  6847  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36c721c6 added. We now have 1 listener(s)
08-11 10:50:12.028  6847  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 10:50:12.033  1036  1469 D WifiService: New client listening to asynchronous messages
08-11 10:50:12.038  6847  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 10:50:12.038  6847  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 10:50:12.040  6847  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 10:50:12.040  6847  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 10:50:12.040  6847  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 10:50:12.045  6847  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 10:50:12.045  1036  1775 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 10:50:12.047  6847  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-11 10:50:12.055  6847  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 10:50:12.056  6847  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 10:50:12.056  6847  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 10:50:12.056  6847  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 10:50:12.056  6847  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 10:50:12.056  6847  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 10:50:12.056  6847  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 10:50:12.056  6847  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 10:50:12.056  6847  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 10:50:12.056  6847  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 10:50:12.056  6847  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 10:50:12.058  6847  6899 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 10:50:12.059  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 10:50:12.061  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 10:50:12.104  6847  6847 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 10:50:12.855  6847  6902 W jxcore-log: Initializing JXcore engine
08-11 10:50:12.855  6847  6902 W jxcore-log: JXcore engine is ready
,08-11 10:50:12.879  6902  6902 W Thread-782: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6120]" dev="sockfs" ino=6120 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 10:50:12.879  6902  6902 W Thread-782: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-11 10:50:12.879  6902  6902 W Thread-782: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9439]" dev="sockfs" ino=9439 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 10:50:12.879  6902  6902 W Thread-782: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-11 10:50:12.879  6902  6902 W Thread-782: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33048]" dev="sockfs" ino=33048 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-11 10:50:12.906  6847  6902 W jxcore-log: Starting JXcore engine
08-11 10:50:12.981  6847  6902 W jxcore-log: Platform android
08-11 10:50:12.981  6847  6902 W jxcore-log: 
08-11 10:50:12.981  6847  6902 W jxcore-log: Process ARCH arm
08-11 10:50:12.981  6847  6902 W jxcore-log: 
,08-11 10:50:13.143  6847  6902 I jxcore-log: JXcore Cordova bridge is ready!
08-11 10:50:13.143  6847  6902 I jxcore-log: 
,08-11 10:50:13.144  6847  6902 W jxcore-log: JXcore engine is started
08-11 10:50:13.157  6847  6899 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION

```
