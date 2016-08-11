#### Test 8091062436177d0_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-11 09:07:00.089  1604  1604 I [SystemUI]Clock: called onTimeUpdated()
08-11 09:07:00.098  1604  1604 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 09:07:00.099  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-11 09:07:00.101  1604  1604 I [SystemUI]DateView: called onTimeUpdated()
08-11 09:07:00.103  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 09:07:21.631  6803  6803 D AndroidRuntime: 
08-11 09:07:21.631  6803  6803 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 09:07:21.638  6803  6803 D AndroidRuntime: CheckJNI is OFF
08-11 09:07:21.838  6803  6803 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 09:07:21.848  1036  2015 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 09:07:21.863  1943  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-11 09:07:21.869  1036  2015 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-11 09:07:21.871  1036  2015 D ActivityManager: setTaskToReturnTo : TaskRecord{32968e97 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 09:07:21.871  1036  2015 D ActivityManager: setTaskToReturnTo : TaskRecord{32968e97 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 09:07:21.873  1036  2015 D WindowStateEx: AppWindowTokenEx init.. 
08-11 09:07:21.874   337   347 E GBMv2   : DFP En is all cleared set to be enabled
08-11 09:07:21.903  1036  2015 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6818 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 09:07:21.906  6803  6803 D AndroidRuntime: Shutting down VM
08-11 09:07:21.957  1943  2565 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-11 09:07:21.957  1943  2565 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ca32478 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 09:07:21.958  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-11 09:07:21.958  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23634751 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-11 09:07:21.994  6818  6818 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 09:07:22.068  6818  6818 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-11 09:07:22.076  6818  6818 I LibraryLoader: Loading: webviewchromium
08-11 09:07:22.078  6818  6818 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1749-1752)
08-11 09:07:22.078  6818  6818 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:07:22.101  6818  6818 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31da38e6}
08-11 09:07:22.103  6818  6818 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:07:22.103  6818  6818 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 09:07:22.123  6818  6818 I BrowserStartupController: Initializing chromium process, renderers=0
08-11 09:07:22.123  6818  6818 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:07:22.135  6818  6818 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-11 09:07:22.135  6818  6818 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-11 09:07:22.135  6818  6818 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-11 09:07:22.158   311  1385 V AudioPolicyService: registerClient() client 0xb57efd00, uid 10118
08-11 09:07:22.169  1036  1118 D BluetoothManagerService: Message: 20
08-11 09:07:22.169  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fc91e69:true
08-11 09:07:22.191  6818  6818 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 09:07:22.191  6818  6818 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 09:07:22.191  6818  6818 I Adreno-EGL: Build Date: 12/12/14 금
08-11 09:07:22.191  6818  6818 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-11 09:07:22.191  6818  6818 I Adreno-EGL: Remote Branch: 
08-11 09:07:22.191  6818  6818 I Adreno-EGL: Local Patches: 
08-11 09:07:22.191  6818  6818 I Adreno-EGL: Reconstruct Branch: 
08-11 09:07:22.252  6818  6852 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-11 09:07:22.257  6818  6818 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-11 09:07:22.283  6818  6818 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:07:22.289  6818  6818 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 09:07:22.293  6818  6818 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 09:07:22.296  6818  6818 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 09:07:22.296  6818  6818 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 09:07:22.313  6818  6818 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-11 09:07:22.322  6818  6818 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:07:22.322  6818  6818 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:07:22.358  6818  6875 D OpenGLRenderer: Render dirty regions requested: true
08-11 09:07:22.358  6818  6875 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 09:07:22.369  6818  6875 D OpenGLRenderer: Enabling debug mode 0
08-11 09:07:22.376  6818  6818 D Atlas   : Validating map...
08-11 09:07:22.382  1036  1707 D SplitWindow: check instance of lgWin Window{94b899b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 09:07:22.454  6818  6872 D LgDataFeature: LgDataFeature() Constructor: none
08-11 09:07:22.454  6818  6872 D LgDataFeature: LgDataFeature() Constructor Done, null
08-11 09:07:22.495  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +539ms (total +620ms)
08-11 09:07:22.495  6818  6818 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@242cced time:172169
08-11 09:07:22.496  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{956e884 u0 com.test.thalitest/.MainActivity t6} time:172170
08-11 09:07:22.611  6818  6818 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-11 09:07:22.611  6818  6818 I chromium: 
08-11 09:07:22.624  6818  6818 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-11 09:07:22.796  6818  6893 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435157504
08-11 09:07:22.811  6818  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 09:07:22.811  6818  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 09:07:22.811  6818  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 09:07:22.811  6818  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 09:07:22.811  6818  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 09:07:22.812  6818  6893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a196e21 added. We now have 1 listener(s)
08-11 09:07:22.817  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 09:07:22.820  6818  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-11 09:07:22.823  6818  6893 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-11 09:07:22.825  6818  6893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 09:07:22.825  6818  6893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 09:07:22.834  6818  6893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfc4134 added. We now have 1 listener(s)
08-11 09:07:22.835  6818  6893 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 09:07:22.841  1036  1545 D WifiService: New client listening to asynchronous messages
08-11 09:07:22.850  6818  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 09:07:22.850  6818  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 09:07:22.852  6818  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 09:07:22.853  6818  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 09:07:22.853  6818  6893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 09:07:22.859  6818  6893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 09:07:22.861  1036  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 09:07:22.862  6818  6893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-11 09:07:22.872  6818  6893 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 09:07:22.873  6818  6893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:07:22.873  6818  6893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:07:22.873  6818  6893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 09:07:22.873  6818  6893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:07:22.873  6818  6893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:07:22.873  6818  6893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:07:22.873  6818  6893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:07:22.873  6818  6893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:07:22.873  6818  6893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 09:07:22.873  6818  6893 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 09:07:22.877  6818  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 09:07:22.877  6818  6893 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 09:07:22.880  6818  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 09:07:22.915  6818  6818 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-11 09:07:22.938  6818  6872 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-11 09:07:22.938  6818  6872 I chromium: 
08-11 09:07:23.121   337   349 E GBMv2   : DFP En is all cleared set to be enabled
08-11 09:07:23.121   337   349 E GBMv2   : Set value is all cleared set the max
08-11 09:07:23.121   337   349 I GBMv2   : DFP Enabled. Ignore VFP set
,08-11 09:07:23.966  6818  6896 W jxcore-log: Initializing JXcore engine
08-11 09:07:23.966  6818  6896 W jxcore-log: JXcore engine is ready
,08-11 09:07:24.012  6896  6896 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8566]" dev="sockfs" ino=8566 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-11 09:07:24.012  6896  6896 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-11 09:07:24.012  6896  6896 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8730]" dev="sockfs" ino=8730 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-11 09:07:24.012  6896  6896 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-11 09:07:24.012  6896  6896 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31511]" dev="sockfs" ino=31511 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-11 09:07:24.035  6818  6896 W jxcore-log: Starting JXcore engine
,08-11 09:07:24.130  6818  6896 W jxcore-log: Platform android
08-11 09:07:24.130  6818  6896 W jxcore-log: 
08-11 09:07:24.130  6818  6896 W jxcore-log: Process ARCH arm
08-11 09:07:24.130  6818  6896 W jxcore-log: 
,08-11 09:07:24.307  6818  6896 I jxcore-log: JXcore Cordova bridge is ready!
08-11 09:07:24.307  6818  6896 I jxcore-log: 
08-11 09:07:24.307  6818  6896 W jxcore-log: JXcore engine is started
,08-11 09:07:24.313  6818  6893 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 09:07:24.315  6818  6818 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 09:07:34.131  6818  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 09:07:34.131  6818  6896 I jxcore-log: 
,08-11 09:07:34.134  6818  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 09:07:34.134  6818  6896 I jxcore-log: 
08-11 09:07:34.139  6818  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:07:34.139  6818  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:07:34.139  6818  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 09:07:34.139  6818  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:07:34.139  6818  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:07:34.139  6818  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:07:34.139  6818  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:07:34.139  6818  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:07:34.141  6818  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 09:07:34.143  6818  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 09:07:34.143  6818  6896 I jxcore-log: 
08-11 09:07:34.145  6818  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 09:07:34.145  6818  6896 I jxcore-log: 
,08-11 09:07:34.472  6818  6896 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-11 09:07:34.473  6818  6896 I jxcore-log: Failed to execute UT.,
08-11 09:07:34.473  6818  6896 I jxcore-log: 
,08-11 09:07:34.473  6818  6896 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 09:07:34.473  6818  6896 I jxcore-log: ,
08-11 09:07:34.475  6818  6896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 09:07:34.475  6818  6896 I jxcore-log: 
,08-11 09:07:34.489  6818  6818 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-11 09:07:34.837  6898  6898 D AndroidRuntime: 
08-11 09:07:34.837  6898  6898 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 09:07:34.844  6898  6898 D AndroidRuntime: CheckJNI is OFF
08-11 09:07:35.052  6898  6898 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 09:07:35.217  1036  2034 I art     : Explicit concurrent mark sweep GC freed 28574(1412KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.035ms total 142.087ms
,08-11 09:07:35.244  1036  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-11 09:07:35.244  1036  1114 I ActivityManager: Killing 6818:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-11 09:07:35.319  1036  2007 I WindowState: WIN DEATH: Window{94b899b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:07:35.324  1036  1545 D WifiService: Client connection lost with reason: 4
08-11 09:07:35.328  1036  2007 D InputDispatcher: Window went away: Window{94b899b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 09:07:35.398  1036  1114 I ActivityManager:   Force finishing activity ActivityRecord{956e884 u0 com.test.thalitest/.MainActivity t6}
,08-11 09:07:35.444   337   347 E GBMv2   : DFP En is all cleared set to be enabled
08-11 09:07:35.446  1036  1051 W ActivityManager: Spurious death for ProcessRecord{18c20549 6818:com.test.thalitest/u0a118}, curProc for 6818: null
08-11 09:07:35.447  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-11 09:07:35.447  1943  2565 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-11 09:07:35.448  1943  2565 D SplitWindowPolicy: topRunningActivity=ActivityInfo{aa63bb6 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-11 09:07:35.449  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-11 09:07:35.451  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13bd10b7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-11 09:07:35.453  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{956e884 u0 com.test.thalitest/.MainActivity t6 f}
08-11 09:07:35.453  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{956e884 u0 com.test.thalitest/.MainActivity t6 f}
,08-11 09:07:35.479  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-11 09:07:35.481  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-11 09:07:35.483  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-11 09:07:35.491  3944  3944 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-11 09:07:35.491  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-11 09:07:35.492  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-11 09:07:35.492  2477  2625 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 09:07:35.494  3877  3877 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-11 09:07:35.494  4547  4547 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 09:07:35.495  4547  4547 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 09:07:35.495  4547  4547 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 09:07:35.495  4547  4547 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-11 09:07:35.495  4547  4547 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 09:07:35.495  4547  4547 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 09:07:35.495  4547  4547 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:07:35.495  4547  4547 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-11 09:07:35.495  4547  4547 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:07:35.501  4547  4547 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 09:07:35.501  4547  4547 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-11 09:07:35.501  4547  4547 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-11 09:07:35.503  6523  6523 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-11 09:07:35.505  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-11 09:07:35.507  2035  2110 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-11 09:07:35.511  1036  1455 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 09:07:35.550  1036  1113 W InputMethodInfo: Duplicated subtype definition found: , voice
08-11 09:07:35.552  4656  4656 I art     : Explicit concurrent mark sweep GC freed 490(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 674us total 90.062ms
,08-11 09:07:35.560  1036  1905 V SIM_STK : Menu title from STK is T-Mobile
08-11 09:07:35.576  1036  1036 D administrator: Handling package changes for user 0
,08-11 09:07:35.598  1819  1819 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-11 09:07:35.599  1604  1604 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-11 09:07:35.602  1907  1907 D ActionManagerService: notifyUserLog: 1000003
08-11 09:07:35.602  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-11 09:07:35.603  3877  4536 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-11 09:07:35.603  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 09:07:35.606  1604  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 09:07:35.606  1604  1659 D KeyguardModel: createShortcutInfo...
08-11 09:07:35.609  2192  2192 I ConfigService: onCreate
08-11 09:07:35.610  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-11 09:07:35.611  2192  2192 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-11 09:07:35.611  1604  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 09:07:35.611  1604  1659 D KeyguardModel: createShortcutInfo...
08-11 09:07:35.617  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-11 09:07:35.620  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-11 09:07:35.621  3877  3893 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 09:07:35.621  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 09:07:35.622  1604  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 09:07:35.622  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , display: false
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , animation: false }
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , display: false
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , animation: false }
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , create_time: 1470393743569
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , display: false
08-11 09:07:35.623  2035  2035 I GBoardWebViewUtils: , animation: false }
08-11 09:07:35.623  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 09:07:35.625  2192  2192 I ConfigService: onBind returning update interface
08-11 09:07:35.626  1819  1819 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-11 09:07:35.626  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:35.626  1907  1907 D ActionManagerService: notifyUserLog: 1000004
08-11 09:07:35.626  1604  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 09:07:35.627  3877  4536 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-11 09:07:35.632  2192  2192 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-11 0,9:07:35.632  1604  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 09:07:35.632  1604  1659 D KeyguardModel: createShortcutInfo...
08-11 09:07:35.632  2192  2192 I ConfigService: onBind returning config service
,08-11 09:07:35.639  1604  1604 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 09:07:35.643  2035  6934 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-11 09:07:35.645  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-11 09:07:35.645  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 09:07:35.647  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:35.647  1604  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 09:07:35.648  1604  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 09:07:35.648  1604  1659 D KeyguardModel: createShortcutInfo...
08-11 09:07:35.651  1604  1604 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-11 09:07:35.654  1604  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 09:07:35.654  1604  1659 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-11 09:07:35.655  1036  1927 V SIM_STK : Menu title from STK is T-Mobile
08-11 09:07:35.655  1036  1927 V SIM_STK : Menu title from STK is T-Mobile
08-11 09:07:35.656  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-11 09:07:35.656  1604  1659 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-11 09:07:35.659  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:35.659  1604  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-11 09:07:35.661  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 09:07:35.662  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-11 09:07:35.668  1604  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 09:07:35.668  1604  1659 D KeyguardModel: createShortcutInfo...
08-11 09:07:35.672  2192  2192 I ConfigService: onDestroy
08-11 09:07:35.674  1819  6936 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-11 09:07:35.678  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-11 09:07:35.678  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-11 09:07:35.690  1604  1659 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 09:07:35.690  1604  1659 D KeyguardModel: createShortcutInfo...
,08-11 09:07:35.694  1604  1659 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 09:07:35.694  1604  1659 D KeyguardModel: createShortcutInfo...
08-11 09:07:35.695  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:35.695  1604  1659 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 09:07:35.701  1604  1659 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 09:07:35.701  1604  1659 D KeyguardModel: createShortcutInfo...
08-11 09:07:35.702  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-11 09:07:35.702  1871  1871 D SplitUIService: removed split : 
08-11 09:07:35.704  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:35.704  1604  1659 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-11 09:07:35.745  1604  1659 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 09:07:35.745  1604  1659 D KeyguardModel: createShortcutInfo...
,08-11 09:07:35.748  1036  1942 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-11 09:07:35.750  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-11 09:07:35.751  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-11 09:07:35.751  3944  3944 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-11 09:07:35.757  1604  1659 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:35.757  1604  1659 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 09:07:35.758  6011  6943 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-11 09:07:35.761  1604  1659 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 09:07:35.761  1604  1659 D KeyguardModel: createShortcutInfo...
08-11 09:07:35.761  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-11 09:07:35.762  1819  6944 I PeopleContactsSync: CP2 sync disabled
08-11 09:07:35.781  1871  1871 D SplitUIManager: split_name #11 / not available #0
08-11 09:07:35.781  6080  6080 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-11 09:07:35.781  1871  1871 I SplitUIService: split app #11
,08-11 09:07:35.791  1819  4814 I Icing   : doRemovePackageData com.test.thalitest
08-11 09:07:35.800  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-11 09:07:35.800  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 09:07:35.803  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 09:07:35.805  1604  1604 D KeyguardModel: handleShortcutListChanged...
08-11 09:07:35.805  1604  1604 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-11 09:07:35.806  6625  6625 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-11 09:07:35.806  1036  1981 V SIM_STK : Menu title from STK is T-Mobile
08-11 09:07:35.806  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-11 09:07:35.807  1819  6942 W GmsApplication: Using Auth Proxy for data requests.
08-11 09:07:35.816  1819  6942 W GmsApplication: Using Auth Proxy for data requests.
,08-11 09:07:35.825  2378  6947 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-11 09:07:35.826  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-11 09:07:35.826  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-11 09:07:35.827  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-11 09:07:35.842  6523  6523 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-11 09:07:35.857  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-11 09:07:35.861  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:07:35.863  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-11 09:07:35.864  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-11 09:07:35.865  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-11 09:07:35.866  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-11 09:07:35.872  1036  2015 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6950 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-11 09:07:35.879  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2564def9 u0 com.lge.launcher2/.Launcher t5} time:185553
,08-11 09:07:35.883  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-11 09:07:35.883  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:07:35.883  2035  2161 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-11 09:07:35.883  2035  2161 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-11 09:07:35.897  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-11 09:07:35.897  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 09:07:35.898  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:07:35.905  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-11 09:07:35.906  2603  2603 D [Concierge]Service: onStartCommand(). Type : 8
08-11 09:07:35.906  2603  2603 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-11 09:07:35.907  2603  2603 D [Concierge]Service: Update widget ID : 11
08-11 09:07:35.909  2035  2035 D [Concierge]WidgetView: change position of spinner
,08-11 09:07:35.912  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1470899255912
08-11 09:07:35.912  2603  2603 D [Concierge]Service: onStartCommand(). Type : 0
08-11 09:07:35.916   326   400 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-11 09:07:35.916  3202  6969 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-11 09:07:35.922  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 275336901
08-11 09:07:35.922  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-11 09:07:35.922  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-11 09:07:35.925  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3814e2bc
08-11 09:07:35.925  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-11 09:07:35.926  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-11 09:07:35.926  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:07:35.931  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-11 09:07:35.932  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-11 09:07:35.932  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 09:07:35.932  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470899098191, New one : 1470899255912
08-11 09:07:35.932  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-11 09:07:35.933  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-11 09:07:35.933  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:07:35.934  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-11 09:07:35.935  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-11 09:07:35.937  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-11 09:07:35.938  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
,08-11 09:07:35.939  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-11 09:07:35.945  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:07:35.945  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:07:35.968  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 09:07:35.972  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 09:07:35.991  6950  6950 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-11 09:07:35.991  6950  6950 W LG Account v2.2: No ProfileInfo entries
08-11 09:07:35.991  6950  6950 I LG Account v2.2: isEnabled: false
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Country: EU
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Operator: OPEN
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Ranking support: false
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Comfort support: false
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Accessory: true
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Health device: true
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Extra Pedometer: false
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Blood glucose device: false
08-11 09:07:35.991  6950  6950 I Feature : [Lifetracker]Device Number: 3
08-11 09:07:35.992  6950  6950 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-11 09:07:35.995  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-11 09:07:36.006  1036  1124 I art     : Explicit concurrent mark sweep GC freed 24534(1769KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.888ms total 305.484ms
,08-11 09:07:36.005  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-11 09:07:36.007  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-11 09:07:36.008  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 09:07:36.009  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-11 09:07:36.026  1036  2015 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6973 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 09:07:36.039  6898  6898 D AndroidRuntime: Shutting down VM
,08-11 09:07:36.051  1036  2015 I ActivityManager: Killing 6295:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-11 09:07:36.052  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a8ada56 time:185726
,08-11 09:07:36.119  1036  1942 W libprocessgroup: failed to open /acct/uid_10014/pid_6295/cgroup.procs: No such file or directory
08-11 09:07:36.130  6973  6973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 09:07:36.130  6973  6973 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-11 09:07:36.130  6973  6973 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-11 09:07:36.130  6973  6973 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-11 09:07:36.131  6973  6973 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 09:07:36.131  6973  6973 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-11 09:07:36.135  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-11 09:07:36.171  2035  2956 I GBoardtInterface: onReloaded()
,08-11 09:07:36.174  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-11 09:07:36.174  3877  4531 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 09:07:36.176  3877  3893 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 09:07:36.181  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-11 09:07:36.182  3877  4536 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-11 09:07:36.182  3877  4536 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 09:07:36.185  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-11 09:07:36.186  3877  4536 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-11 09:07:36.186  3877  4536 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-11 09:07:36.186  3877  4536 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-11 09:07:36.186  3877  4536 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-11 09:07:36.186  3877  4531 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-11 09:07:36.188  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-11 09:07:36.188  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-11 09:07:36.189  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-11 09:07:36.189  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-11 09:07:36.191  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-11 09:07:36.191  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-11 09:07:36.202  6973  6973 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-11 09:07:36.208  6973  6973 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-11 09:07:36.208  6973  6973 D HideNavigationAppsReceiver: replacing : false
08-11 09:07:36.210  6973  6973 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-11 09:07:36.212  6973  6973 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-11 09:07:36.212  6973  6973 D ButtonCombinationReceiver: replacing : false
,08-11 09:07:36.217  1036  1942 I ActivityManager: Killing 6402:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-11 09:07:36.338  1036  1927 W libprocessgroup: failed to open /acct/uid_10004/pid_6402/cgroup.procs: No such file or directory
,08-11 09:07:36.368  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6995 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-11 09:07:36.374  4656  7001 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-11 09:07:36.399  1036  1905 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7012 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-11 09:07:36.407   341   341 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 196us total 9.178ms
08-11 09:07:36.416   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 8.965ms
,08-11 09:07:36.426   341   341 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 180us total 8.735ms
08-11 09:07:36.429  1036  1780 V SIM_STK : Menu title from STK is T-Mobile

```
