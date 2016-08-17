#### Test 808075738e7a0be_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-17 19:18:00.107  1600  1600 I [SystemUI]Clock: called onTimeUpdated()
08-17 19:18:00.116  1600  1600 I LgeClockWidgetControlView: called onTimeUpdated()
08-17 19:18:00.117  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-17 19:18:00.119  1600  1600 I [SystemUI]DateView: called onTimeUpdated()
08-17 19:18:00.121  1600  1600 D KeyguardUpdateMonitor: handleTimeUpdate
,08-17 19:18:23.730  6739  6739 D AndroidRuntime: 
08-17 19:18:23.730  6739  6739 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 19:18:23.736  6739  6739 D AndroidRuntime: CheckJNI is OFF
08-17 19:18:23.861  6739  6739 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 19:18:23.866  1052  2041 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 19:18:23.876  1938  3965 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-17 19:18:23.880  1052  2041 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-17 19:18:23.881  1052  2041 D ActivityManager: setTaskToReturnTo : TaskRecord{3bb1c97f #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 19:18:23.881  1052  2041 D ActivityManager: setTaskToReturnTo : TaskRecord{3bb1c97f #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 19:18:23.882  1052  2041 D WindowStateEx: AppWindowTokenEx init.. 
08-17 19:18:23.883   342   368 E GBMv2   : DFP En is all cleared set to be enabled
08-17 19:18:23.921  1052  2041 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6758 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 19:18:23.923  6739  6739 D AndroidRuntime: Shutting down VM
08-17 19:18:23.985  1938  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-17 19:18:23.985  1938  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3b6b0d3e co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 19:18:23.987  1938  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-17 19:18:23.987  1938  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2691b79f co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 19:18:24.036  6758  6758 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-17 19:18:24.098  6758  6758 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 19:18:24.105  6758  6758 I LibraryLoader: Loading: webviewchromium
08-17 19:18:24.107  6758  6758 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8751-8754)
08-17 19:18:24.107  6758  6758 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:18:24.139  6758  6758 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {217f3b9c}
,08-17 19:18:24.141  6758  6758 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:18:24.141  6758  6758 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 19:18:24.154  6758  6758 I BrowserStartupController: Initializing chromium process, renderers=0
,08-17 19:18:24.155  6758  6758 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:18:24.171   320  1381 V AudioPolicyService: registerClient() client 0xb57d3de0, uid 10118
,08-17 19:18:24.176  6758  6758 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-17 19:18:24.176  1052  1134 D BluetoothManagerService: Message: 20
08-17 19:18:24.176  1052  1134 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13aa4211:true
08-17 19:18:24.177  6758  6758 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-17 19:18:24.177  6758  6758 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-17 19:18:24.199  6758  6758 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 19:18:24.199  6758  6758 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 19:18:24.199  6758  6758 I Adreno-EGL: Build Date: 12/12/14 금
08-17 19:18:24.199  6758  6758 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 19:18:24.199  6758  6758 I Adreno-EGL: Remote Branch: 
08-17 19:18:24.199  6758  6758 I Adreno-EGL: Local Patches: 
08-17 19:18:24.199  6758  6758 I Adreno-EGL: Reconstruct Branch: 
,08-17 19:18:24.281  6758  6794 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-17 19:18:24.286  6758  6758 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-17 19:18:24.305  6758  6758 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 19:18:24.309  6758  6758 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 19:18:24.313  6758  6758 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-17 19:18:24.316  6758  6758 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-17 19:18:24.316  6758  6758 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-17 19:18:24.330  6758  6758 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-17 19:18:24.337  6758  6758 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:18:24.337  6758  6758 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 19:18:24.378  6758  6807 D OpenGLRenderer: Render dirty regions requested: true
08-17 19:18:24.379  6758  6807 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 19:18:24.410  6758  6807 D OpenGLRenderer: Enabling debug mode 0
,08-17 19:18:24.424  6758  6758 D Atlas   : Validating map...
,08-17 19:18:24.430  1052  2009 D SplitWindow: check instance of lgWin Window{1317ba03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 19:18:24.478  6758  6805 D LgDataFeature: LgDataFeature() Constructor: none
08-17 19:18:24.478  6758  6805 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 19:18:24.594  1052  1135 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +611ms (total +710ms)
08-17 19:18:24.595  1052  1135 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d51ad4c u0 com.test.thalitest/.MainActivity t6} time:229242
,08-17 19:18:24.600  6758  6758 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33c2671b time:229247
,08-17 19:18:24.731  6758  6758 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-17 19:18:24.731  6758  6758 I chromium: 
,08-17 19:18:24.804  6758  6758 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 19:18:25.034  6758  6821 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-17 19:18:25.051  6758  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 19:18:25.051  6758  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 19:18:25.051  6758  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 19:18:25.051  6758  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 19:18:25.051  6758  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 19:18:25.051  6758  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@279890ef added. We now have 1 listener(s)
08-17 19:18:25.058  1052  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 19:18:25.063  6758  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-17 19:18:25.067  6758  6821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 19:18:25.069  6758  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:18:25.070  6758  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 19:18:25.081  6758  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350524da added. We now have 1 listener(s)
08-17 19:18:25.082  6758  6821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:18:25.086  1052  1541 D WifiService: New client listening to asynchronous messages
,08-17 19:18:25.093  6758  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:18:25.093  6758  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 19:18:25.095  6758  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 19:18:25.096  6758  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 19:18:25.096  6758  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-17 19:18:25.104  6758  6821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:18:25.107  1052  1574 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 19:18:25.110  6758  6821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-17 19:18:25.122  6758  6821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-17 19:18:25.126  6758  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:18:25.126  6758  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:18:25.126  6758  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 19:18:25.126  6758  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:18:25.126  6758  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:18:25.126  6758  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:18:25.126  6758  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:18:25.126  6758  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:18:25.126  6758  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 19:18:25.126  6758  6821 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:18:25.129  6758  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:18:25.130  6758  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:18:25.133  6758  6821 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 19:18:25.188  6758  6758 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 19:18:25.216  6758  6805 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-17 19:18:25.216  6758  6805 I chromium: 
,08-17 19:18:25.272   342   370 E GBMv2   : DFP En is all cleared set to be enabled
08-17 19:18:25.272   342   370 E GBMv2   : Set value is all cleared set the max
08-17 19:18:25.272   342   370 I GBMv2   : DFP Enabled. Ignore VFP set
,08-17 19:18:26.147  6758  6827 W jxcore-log: Initializing JXcore engine
08-17 19:18:26.147  6758  6827 W jxcore-log: JXcore engine is ready
,08-17 19:18:26.173  6827  6827 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7495]" dev="sockfs" ino=7495 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-17 19:18:26.173  6827  6827 W Thread-777: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-17 19:18:26.173  6827  6827 W Thread-777: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8973]" dev="sockfs" ino=8973 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 19:18:26.173  6827  6827 W Thread-777: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-17 19:18:26.173  6827  6827 W Thread-777: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33038]" dev="sockfs" ino=33038 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-17 19:18:26.199  6758  6827 W jxcore-log: Starting JXcore engine
,08-17 19:18:26.276  6758  6827 W jxcore-log: Platform android
08-17 19:18:26.276  6758  6827 W jxcore-log: 
08-17 19:18:26.277  6758  6827 W jxcore-log: Process ARCH arm
08-17 19:18:26.277  6758  6827 W jxcore-log: 
,08-17 19:18:26.516  6758  6827 I jxcore-log: JXcore Cordova bridge is ready!
08-17 19:18:26.516  6758  6827 I jxcore-log: 
08-17 19:18:26.516  6758  6827 W jxcore-log: JXcore engine is started

```
