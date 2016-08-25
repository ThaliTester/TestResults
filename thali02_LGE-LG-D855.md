#### Test 797638306764640_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 15:25:43.062  2237  2237 I ConfigService: onDestroy
,08-25 15:25:55.208  6817  6817 D AndroidRuntime: 
08-25 15:25:55.208  6817  6817 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 15:25:55.215  6817  6817 D AndroidRuntime: CheckJNI is OFF
08-25 15:25:55.416  6817  6817 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 15:25:55.427  1027  1568 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 15:25:55.443  1958  1973 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 15:25:55.448  1027  1568 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 15:25:55.450  1027  1568 D ActivityManager: setTaskToReturnTo : TaskRecord{368124ee #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 15:25:55.450  1027  1568 D ActivityManager: setTaskToReturnTo : TaskRecord{368124ee #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 15:25:55.452  1027  1568 D WindowStateEx: AppWindowTokenEx init.. 
08-25 15:25:55.452   329   352 E GBMv2   : DFP En is all cleared set to be enabled
08-25 15:25:55.481  1027  1568 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6832 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 15:25:55.483  6817  6817 D AndroidRuntime: Shutting down VM
08-25 15:25:55.523   333   333 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 301us total 33.493ms
08-25 15:25:55.549   333   333 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 248us total 18.121ms
08-25 15:25:55.569   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 17.986ms
08-25 15:25:55.590  1958  1973 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 15:25:55.590  1958  1973 D SplitWindowPolicy: topRunningActivity=ActivityInfo{272a8447 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 15:25:55.592  1958  3944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 15:25:55.593  1958  3944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37522474 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 15:25:55.641  6832  6832 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-25 15:25:55.741  6832  6832 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 15:25:55.752  6832  6832 I LibraryLoader: Loading: webviewchromium
,08-25 15:25:55.755  6832  6832 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9493-9498)
,08-25 15:25:55.756  6832  6832 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 15:25:55.777  6832  6832 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d79d5b7}
,08-25 15:25:55.779  6832  6832 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 15:25:55.779  6832  6832 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 15:25:55.791  6832  6832 I BrowserStartupController: Initializing chromium process, renderers=0
,08-25 15:25:55.792  6832  6832 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 15:25:55.808  6832  6832 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 15:25:55.809  6832  6832 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-25 15:25:55.809  6832  6832 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-25 15:25:55.813   311  1377 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-25 15:25:55.819  1027  1089 D BluetoothManagerService: Message: 20
08-25 15:25:55.819  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fd0ea08:true
08-25 15:25:55.835  6832  6832 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 15:25:55.835  6832  6832 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 15:25:55.835  6832  6832 I Adreno-EGL: Build Date: 12/12/14 금
08-25 15:25:55.835  6832  6832 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 15:25:55.835  6832  6832 I Adreno-EGL: Remote Branch: 
08-25 15:25:55.835  6832  6832 I Adreno-EGL: Local Patches: 
08-25 15:25:55.835  6832  6832 I Adreno-EGL: Reconstruct Branch: 
,08-25 15:25:55.929  6832  6878 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 15:25:55.931  6832  6832 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-25 15:25:55.947  6832  6832 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 15:25:55.952  6832  6832 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 15:25:55.956  6832  6832 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-25 15:25:55.960  6832  6832 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 15:25:55.960  6832  6832 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-25 15:25:55.974  6832  6832 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-25 15:25:55.979  6832  6832 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 15:25:55.979  6832  6832 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 15:25:56.079  6832  6895 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:25:56.079  6832  6895 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:25:56.088  1027  1085 W ActivityManager: Activity pause timeout for ActivityRecord{c516d8f u0 com.test.thalitest/.MainActivity t6}
08-25 15:25:56.091  1027  2104 I art     : Explicit concurrent mark sweep GC freed 28735(1380KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.901ms total 89.767ms
08-25 15:25:56.096  6832  6905 D OpenGLRenderer: Render dirty regions requested: true
08-25 15:25:56.096  6832  6905 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 15:25:56.103  6832  6905 D OpenGLRenderer: Enabling debug mode 0
,08-25 15:25:56.110  6832  6832 D Atlas   : Validating map...
08-25 15:25:56.113  1027  1044 D SplitWindow: check instance of lgWin Window{2bea1802 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 15:25:56.180  6832  6832 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@364823f2 time:169922
,08-25 15:25:56.194  1027  1090 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +607ms (total +741ms)
08-25 15:25:56.195  1027  1090 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c516d8f u0 com.test.thalitest/.MainActivity t6} time:169937
08-25 15:25:56.265  6832  6832 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 15:25:56.284  6832  6832 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 15:25:56.284  6832  6832 I chromium: 
,08-25 15:25:56.332  6832  6895 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 15:25:56.332  6832  6895 I chromium: 
,08-25 15:25:56.506  6832  6912 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435157504
,08-25 15:25:56.522  6832  6912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 15:25:56.522  6832  6912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 15:25:56.522  6832  6912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 15:25:56.522  6832  6912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 15:25:56.522  6832  6912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 15:25:56.522  6832  6912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d6f0616 added. We now have 1 listener(s)
,08-25 15:25:56.528  1027  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:25:56.532  6832  6912 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-25 15:25:56.534  6832  6912 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 15:25:56.536  6832  6912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:56.537  6832  6912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 15:25:56.545  6832  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27b99d6d added. We now have 1 listener(s)
08-25 15:25:56.546  6832  6912 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:56.552  1027  1537 D WifiService: New client listening to asynchronous messages
,08-25 15:25:56.559  6832  6912 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:25:56.559  6832  6912 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 15:25:56.561  6832  6912 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 15:25:56.561  6832  6912 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 15:25:56.562  6832  6912 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 15:25:56.572  6832  6912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:56.573  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 15:25:56.575  6832  6912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-25 15:25:56.586  6832  6912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 15:25:56.587  6832  6912 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:56.587  6832  6912 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:56.587  6832  6912 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:25:56.587  6832  6912 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:56.587  6832  6912 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:56.587  6832  6912 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:25:56.587  6832  6912 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:25:56.587  6832  6912 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:25:56.587  6832  6912 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 15:25:56.587  6832  6912 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:25:56.590  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:56.592  6832  6912 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 15:25:56.596  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:56.636  6832  6832 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 15:25:57.004   329   354 E GBMv2   : DFP En is all cleared set to be enabled
08-25 15:25:57.004   329   354 E GBMv2   : Set value is all cleared set the max
08-25 15:25:57.004   329   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-25 15:25:57.315  6832  6918 W jxcore-log: Initializing JXcore engine
08-25 15:25:57.315  6832  6918 W jxcore-log: JXcore engine is ready
,08-25 15:25:57.392  6918  6918 W Thread-791: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[9778]" dev="sockfs" ino=9778 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 15:25:57.392  6918  6918 W Thread-791: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-25 15:25:57.392  6918  6918 W Thread-791: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9945]" dev="sockfs" ino=9945 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-25 15:25:57.392  6918  6918 W Thread-791: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-25 15:25:57.392  6918  6918 W Thread-791: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33353]" dev="sockfs" ino=33353 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-25 15:25:57.427  6832  6918 W jxcore-log: Starting JXcore engine
,08-25 15:25:57.586  6832  6918 W jxcore-log: Platform android
08-25 15:25:57.586  6832  6918 W jxcore-log: 
08-25 15:25:57.586  6832  6918 W jxcore-log: Process ARCH arm
08-25 15:25:57.586  6832  6918 W jxcore-log: 
,08-25 15:25:57.976  6832  6918 I jxcore-log: JXcore Cordova bridge is ready!
08-25 15:25:57.976  6832  6918 I jxcore-log: 
,08-25 15:25:57.977  6832  6918 W jxcore-log: JXcore engine is started
08-25 15:25:57.983  6832  6912 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-25 15:25:57.987  6832  6832 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-25 15:26:00.042  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-25 15:26:00.042  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-25 15:26:00.042  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-25 15:26:00.042  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-25 15:26:00.048  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 15:26:00.048  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-25 15:26:00.050  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-25 15:26:00.052  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 15:26:08.844  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 15:26:08.844  6832  6918 I jxcore-log: 
,08-25 15:26:08.846  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 15:26:08.846  6832  6918 I jxcore-log: 
08-25 15:26:08.851  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:08.851  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:08.851  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:08.851  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:08.851  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:08.851  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:08.851  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:08.851  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:08.854  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:08.856  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 15:26:08.856  6832  6918 I jxcore-log: 
08-25 15:26:08.857  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 15:26:08.857  6832  6918 I jxcore-log: 
,08-25 15:26:09.357  6832  6918 D executeNativeTests: Running unit tests
,08-25 15:26:09.438  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:26:09.438  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 added. We now have 2 listener(s)
,08-25 15:26:09.438  1027  1957 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:09.440  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-25 15:26:09.440  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:26:09.440  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:09.441  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:26:09.441  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 added. We now have 2 listener(s)
08-25 15:26:09.441  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:26:09.441  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:26:09.443  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.445  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-25 15:26:09.445  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.445  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.445  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.445  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-25 15:26:09.445  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.445  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:09.445  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:26:09.446  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-25 15:26:09.446  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:09.448  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 15:26:09.449  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:09.452  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-25 15:26:09.454  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:26:09.454  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:26:09.456  6832  6918 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 15:26:09.457  6832  6918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 15:26:09.457  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 15:26:09.457  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:26:09.457  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:26:09.458  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.458  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.458  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.459  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.459  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.459  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:09.459  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:09.459  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 removed from the list
08-25 15:26:09.459  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.459  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 removed from the list
08-25 15:26:09.459  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.459  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.459  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.459  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.460  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.460  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.460  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.460  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.461  6832  6918 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 15:26:09.462  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.462  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.462  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.462  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.462  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.462  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.462  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.462  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.462  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.462  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.462  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.462  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.462  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.462  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:26:09.463  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.463  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.463  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.463  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.468  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 15:26:09.468  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 15:26:09.468  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 15:26:09.468  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 15:26:09.469  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 15:26:09.469  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.469  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.469  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.470  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.470  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.470  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.470  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.470  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.470  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.470  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.470  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.470  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.470  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.470  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.471  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.471  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.471  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.471  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.472  6832  6918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 15:26:09.473  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.475  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:09.475  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.475  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.475  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.475  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:09.475  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.475  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:09.475  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:09.476  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.476  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:09.478  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:09.479  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:09.479  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:26:09.479  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:26:09.480  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:26:09.480  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.480  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:26:09.483  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 15:26:09.483  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:09.486  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 15:26:09.490  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 15:26:09.491  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 15:26:09.492  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:26:09.492  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:09.493  6832  6918 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 15:26:09.493  6832  6918 I io.jxcore.node.ConnectionHelper: start: OK
08-25 15:26:09.495  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.495  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.495  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.495  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.495  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.495  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:09.495  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.495  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.495  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.495  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.495  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.496  6832  6918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 15:26:09.497  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.499  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:09.499  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.499  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.499  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.499  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:09.499  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.499  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:09.499  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:09.502  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.502  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:09.503  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:26:09.503  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:26:09.503  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:26:09.503  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.503  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:26:09.503  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:09.505  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:09.507  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:26:09.508  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:09.509  6832  6918 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 15:26:09.509  6832  6918 I io.jxcore.node.ConnectionHelper: start: OK
08-25 15:26:09.510  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:26:09.510  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.511  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.511  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.511  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.511  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:09.511  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.511  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.511  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.511  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.511  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.512  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.512  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.512  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.512  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.514  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.514  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.514  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.514  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.514  6832  6918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 15:26:09.515  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.517  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:09.517  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.517  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.517  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.517  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:09.517  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.517  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:09.517  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:09.518  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.518  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:09.518  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:26:09.518  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:26:09.518  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:26:09.519  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.519  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:26:09.520  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:09.521  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:09.524  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:26:09.524  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:09.525  6832  6918 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 15:26:09.525  6832  6918 I io.jxcore.node.ConnectionHelper: start: OK
08-25 15:26:09.525  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.525  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.525  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.526  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.526  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.526  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.526  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.526  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.526  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:09.526  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.526  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.526  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.526  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.526  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.527  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.527  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.527  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.527  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.528  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.528  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.528  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.528  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.528  6832  6918 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 15:26:09.528  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.528  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.528  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.528  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.528  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.528  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.528  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.528  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.529  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.529  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.529  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.529  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.529  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.529  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.529  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.529  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.529  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.529  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.529  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.529  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.530  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 15:26:09.530  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.530  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.530  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.530  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.530  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.530  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.530  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.530  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.530  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.531  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.531  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.531  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.531  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.531  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.531  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.531  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.531  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.531  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.531  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.531  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.532  6832  6918 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 15:26:09.532  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.532  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.532  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.532  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.532  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.532  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.532  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.532  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.532  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.532  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.532  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.532  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.532  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.532  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.535  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.536  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.538  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.538  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.538  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.538  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.539  6832  6918 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 15:26:09.539  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.539  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.539  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.539  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.539  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.539  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.539  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.539  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.540  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.540  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.540  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.540  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.540  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.540  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.540  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.540  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.541  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.541  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.541  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.541  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.542  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 15:26:09.544  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 15:26:09.544  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 15:26:09.544  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:26:09.544  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 15:26:09.544  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:26:09.544  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.544  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.544  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.545  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.545  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.545  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.545  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.546  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.546  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.546  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.546  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.546  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.547  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.547  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.548  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.548  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.548  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.548  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.548  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.548  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.549  6832  6918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:26:09.549  6832  6918 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 15:26:09.549  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 15:26:09.550  6832  6918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:26:09.551  6832  6918 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 15:26:09.551  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 15:26:09.551  6832  6918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 15:26:09.551  6832  6918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:26:09.551  6832  6918 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 15:26:09.552  6832  6918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:26:09.552  6832  6918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:26:09.552  6832  6918 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 15:26:09.552  6832  6918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:26:09.552  6832  6918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:26:09.552  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 15:26:09.553  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 15:26:09.553  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 15:26:09.553  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 15:26:09.554  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 15:26:09.554  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 15:26:09.554  6832  6918 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 15:26:09.554  6832  6918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:26:09.554  6832  6918 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 15:26:09.555  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.555  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.555  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.555  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.555  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.555  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.555  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 15:26:09.559  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.559  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.559  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.559  6832  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 855)
08-25 15:26:09.559  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.559  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.559  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.559  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.559  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.561  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.561  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.562  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.562  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.562  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.562  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.563  6832  6918 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 15:26:09.563  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.564  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.564  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.564  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.564  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.564  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.564  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.564  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.564  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.564  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.564  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.564  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.564  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.564  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.565  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.565  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.565  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.565  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.565  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.565  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.566  6832  6918 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 15:26:09.567  6832  6930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 855
08-25 15:26:09.567  6832  6930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 855)
08-25 15:26:09.568  6832  6930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 855)
08-25 15:26:09.568  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.568  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.568  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.569  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.569  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.569  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.569  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.569  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.569  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.569  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.569  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.569  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.569  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.569  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.577  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.577  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.578  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.578  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.578  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.578  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.578  6832  6918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 15:26:09.578  6832  6918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 15:26:09.578  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:26:09.578  6832  6918 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 15:26:09.579  6832  6918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 15:26:09.579  6832  6918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 15:26:09.579  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 15:26:09.579  6832  6918 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 15:26:09.579  6832  6918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 15:26:09.579  6832  6918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 15:26:09.579  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 15:26:09.579  6832  6918 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 15:26:09.579  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.579  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.579  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.579  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.579  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.579  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.579  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.579  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.580  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.580  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.580  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.580  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.580  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.580  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:26:09.580  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.580  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.581  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.581  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.581  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.581  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.581  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.581  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.581  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.581  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.581  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.581  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.581  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.581  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.581  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.581  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.582  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.582  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.582  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.582  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.582  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.582  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.582  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.582  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.582  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.582  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.582  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.582  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.582  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.582  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.582  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.582  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.582  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.582  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.582  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.583  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.583  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.583  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.583  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.584  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.584  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.585  6832  6918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 15:26:09.585  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.585  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 15:26:09.586  6832  6918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 15:26:09.586  6832  6918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 15:26:09.586  6832  6832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 15:26:09.586  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 15:26:09.586  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 15:26:09.587  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.587  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 15:26:09.587  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 15:26:09.587  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 15:26:09.587  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.587  6832  6918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 15:26:09.587  6832  6832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 15:26:09.587  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.587  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.587  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:26:09.587  6832  6918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:26:09.587  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:26:09.588  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:26:09.588  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:09.588  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:09.588  6832  6918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:26:09.588  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.588  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.589  6832  6918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:26:09.589  6832  6832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:26:09.589  6832  6832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:26:09.589  6832  6832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:26:09.589  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.589  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.589  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.589  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.589  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.589  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.590  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.590  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.590  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.590  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.590  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.590  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.590  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.590  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.590  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.590  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.590  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.590  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.590  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.591  6832  6918 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 15:26:09.591  6832  6931 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 15:26:09.591  6832  6931 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 15:26:09.591  6832  6918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 15:26:09.591  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 15:26:09.592  6832  6832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 15:26:09.592  6832  6918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:26:09.593  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.593  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.593  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.593  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.593  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.593  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.593  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.593  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.593  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.593  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.593  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.593  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.593  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.593  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.594  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.594  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.594  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.594  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.595  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:09.595  1027  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:09.596  1027  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:09.596  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.596  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.596  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.596  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.596  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.596  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.596  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.597  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.597  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.597  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.597  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.597  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.597  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.597  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.597  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.597  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.597  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.597  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.598  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:09.598  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:09.598  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:09.598  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:09.598  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.598  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.598  6832  6918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f132b66 not in the list
08-25 15:26:09.598  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.598  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.598  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:09.598  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.599  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.599  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:09.599  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:09.599  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:09.599  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:09.599  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:09.599  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2946bea7 not in the list
08-25 15:26:09.600  6832  6918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 15:26:09.600  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:26:09.600  6832  6918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 15:26:09.600  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:26:09.600  6832  6918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 15:26:09.601  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 15:26:09.603  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 15:26:09.603  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 15:26:09.604  6832  6918 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 15:26:09.604  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 15:26:09.604  6832  6918 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 15:26:09.604  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 15:26:09.604  6832  6918 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 15:26:09.604  6832  6918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 15:26:09.604  6832  6918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 15:26:09.605  6832  6918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 15:26:09.605  6832  6918 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 15:26:09.605  6832  6918 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 15:26:09.605  6832  6918 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 15:26:09.605  6832  6918 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 15:26:09.607  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:09.607  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@253424ec added. We now have 2 listener(s)
08-25 15:26:09.607  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:09.608  6832  6918 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 15:26:09.608  1027  1568 D WifiServiceImplEx: setWifiEnabled: true pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 15:26:09.609  1027  1568 D WifiService: setWifiEnabled: true pid=6832, uid=10118
08-25 15:26:09.609  1027  1568 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 15:26:09.610  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:09.610  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34fbd0b5 added. We now have 3 listener(s)
08-25 15:26:09.610  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:09.612  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:09.612  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29cd334a added. We now have 4 listener(s)
08-25 15:26:09.612  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:26:09.615  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:09.615  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@73b92bb added. We now have 5 listener(s)
08-25 15:26:09.615  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:09.616  1027  1044 D WifiServiceImplEx: setWifiEnabled: false pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 15:26:09.616  1027  1044 D WifiService: setWifiEnabled: false pid=6832, uid=10118
08-25 15:26:09.616  1027  1044 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 15:26:09.635  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 15:26:09.637  1027  1532 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 15:26:09.638  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 15:26:09.638  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 15:26:09.638  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 15:26:09.638  1027  1532 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 15:26:09.638  1027  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:09.638  1027  1982 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2f51e2d mBinding = false
08-25 15:26:09.638  1027  1532 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 15:26:09.639  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 15:26:09.639  1027  1532 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 15:26:09.639  1027  1532 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:26:09.639  1027  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 15:26:09.640  1027  1532 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 15:26:09.640  1027  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 15:26:09.653  1027  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 15:26:09.658  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 15:26:09.659  1027  1530 D LGWifiP2pService: InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.659  2656  2656 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 15:26:09.659  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.660  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 15:26:09.660  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 15:26:09.662  1027  1089 D BluetoothManagerService: Message: 2
08-25 15:26:09.660  1027  1532 D WifiNative-wlan0: SET ps 1: returned true
08-25 15:26:09.662  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 15:26:09.663  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 15:26:09.663  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 15:26:09.664  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:09.664  1027  1089 D BluetoothManagerService: Sending off request.
08-25 15:26:09.665  1027  2809 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.666  3855  3877 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 15:26:09.667  3855  3951 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 15:26:09.667  3855  3951 D BluetoothAdapterProperties: Setting state to 13
08-25 15:26:09.667  3855  3951 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 15:26:09.668  3855  3951 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 15:26:09.668  3855  3951 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 15:26:09.669  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:09.669  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.669  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.669  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.669  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:09.669  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.669  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:09.669  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:26:09.671  3855  3955 D BluetoothAdapterProperties: Scan Mode:20
08-25 15:26:09.671  3855  3951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 15:26:09.672  3855  3951 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 15:26:09.673  3855  4228 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 15:26:09.673  3855  4228 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:09.673  3855  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 15:26:09.673  3855  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 15:26:09.673  3855  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 15:26:09.673  3855  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 15:26:09.673  3855  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 15:26:09.673  3855  4228 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 15:26:09.674   305   886 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:26:09.674  3855  4229 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:09.674  3855  4306 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:09.675  3855  4278 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:09.675  3855  4303 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:09.675  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 15:26:09.675  3855  4037 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 15:26:09.676  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 15:26:09.676  3855  4037 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 15:26:09.681  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.681  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.681  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:09.682  1027  1089 D BluetoothManagerService: Message: 60
08-25 15:26:09.682  1027  1089 D BluetoothManagerS,ervice: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 15:26:09.682  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-25 15:26:09.685  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.685  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:09.685  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.685  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.685  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.685  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:09.685  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.685  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:09.685  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:09.686  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.686  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.688  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:09.690  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.690  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:09.690  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.690  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.690  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.690  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:09.690  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.690  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:09.690  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:09.690  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.690  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:09.692  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:09.699  6832  6929 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-25 15:26:09.708  6832  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 855)
08-25 15:26:09.710  1027  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 15:26:09.710  1027  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-25 15:26:09.724  1027  1085 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6946 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 15:26:09.729  3855  3855 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:09.729  3855  3855 D BluetoothMapService: STATE_TURNING_OFF
08-25 15:26:09.729  3855  3855 V BluetoothMapService: Handler(): got msg=4
08-25 15:26:09.729  3855  3855 D BluetoothMapService: MAP Service closeService in
08-25 15:26:09.729  3855  3855 D BluetoothMapMasInstance: MAP Service shutdown
08-25 15:26:09.729  3855  3855 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 15:26:09.729  3855  3855 V BluetoothMapService: MAP Service closeService out
08-25 15:26:09.730  3855  3855 V BtOppService: Receiver DISABLED_ACTION 
08-25 15:26:09.730  3855  3855 I BtOppRfcommListener: stopping Accept Thread
08-25 15:26:09.730  3855  3855 V BtOppRfcommListener: close mBtServerSocket
08-25 15:26:09.731  3855  3855 V BtOppRfcommListener: waiting for thread to terminate
08-25 15:26:09.731  3855  4278 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 15:26:09.731  3855  3855 V BtOppRfcommListener: done waiting for thread to terminate
08-25 15:26:09.731  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 15:26:09.732  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:09.733  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.733  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:09.733  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.733  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.733  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.733  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:09.733  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:09.733  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:09.733  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:09.733  1027  2010 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-25 15:26:09.733  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.733  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.734  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 15:26:09.734  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.734  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-25 15:26:09.735  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.736  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:09.737  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.737  6832  6832 V io.jxcore.node.ConnectivityMonitor: upd,ateConnectivityInfo: State changed:
08-25 15:26:09.737  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.737  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.737  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:09.737  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:09.737  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:09.737  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:09.737  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:26:09.738  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.738  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:09.755  1027  1538 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 15:26:09.756  1027  1538 D DSQN    : disableDataServiceNotify
,08-25 15:26:09.756  1027  1538 D DSQN    : stop dsqn bin
08-25 15:26:09.757   305  6967 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 15:26:09.758  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-25 15:26:09.758  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 15:26:09.766  1027  1538 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 15:26:09.767  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:09.767  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:09.767  1027  1538 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:09.767  1027  1538 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,08-25 15:26:09.767  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.767  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.767  1027  2807 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 15:26:09.768  1027  1538 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 15:26:09.768  1027  1538 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 15:26:09.768  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 15:26:09.768  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 15:26:09.769  1027  1085 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6968 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 15:26:09.770  3855  3855 V BtOppService: onDestroy
08-25 15:26:09.771  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 15:26:09.772  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:09.773  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:09.773  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 15:26:09.773  1958  1958 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 15:26:09.776  1027  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:09.776  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 15:26:09.777  1027  1529 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 15:26:09.777  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 15:26:09.777  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 15:26:09.778  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 15:26:09.778  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-25 15:26:09.778  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 15:26:09.783  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:09.783  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:09.783  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 15:26:09.783  1027  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:09.783  1027  1529 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 15:26:09.783  1027  1538 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:09.783  1027  1538 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:09.784  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 15:26:09.784  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:09.784  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:09.784  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 15:26:09.784  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 15:26:09.784  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 15:26:09.788  1027  1538 D NetworkManagementService: Removing idletimer
08-25 15:26:09.788  1027  1538 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:09.788  1027  1538 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 15:26:09.789  1871  1871 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:09.789  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 15:26:09.790  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:09.790  3855  3855 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 15:26:09.791  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.791  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.791  1027  1532 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.791  1027  1530 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f0bb52d
08-25 15:26:09.791  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.792  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.792  1027  1532 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.792  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 15:26:09.792  1027  1027 D RttServi,ce: SCAN_AVAILABLE : 1
08-25 15:26:09.792  1027  1530 D LGWifiP2pService: P2pDisablingState
08-25 15:26:09.792  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.792  1027  1530 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.792  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.792  1027  1530 D LGWifiP2pService: p2p socket connection lost
08-25 15:26:09.792  1027  1530 D LGWifiP2pService: P2pDisabledState
08-25 15:26:09.792  1027  1549 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.793  1027  1532 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 15:26:09.793  1027  1550 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.793  1027  1532 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.793  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.793  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:09.793  1027  1532 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:09.793  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 15:26:09.793  1027  1532 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:09.794  1958  1958 D WfdsService: WifiP2pState is changed : false
08-25 15:26:09.794  1958  2313 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 15:26:09.794  1958  2313 D WfdsService: Set the WFDS Monitor: false
08-25 15:26:09.794  1027  1532 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 15:26:09.794  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 15:26:09.794  2656  2656 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 15:26:09.794  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 15:26:09.794  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 15:26:09.795  1027  1532 D WifiNative-wlan0: SET ps 1: returned true
08-25 15:26:09.795   305   886 D CommandListener: Clearing all IP addresses on wlan0
,08-25 15:26:09.797  1958  2313 D WfdsMonitor: WFDS Monitor is stopped
08-25 15:26:09.797  1958  2313 D WfdsService: STATE : WfdsDisabledState - enter
08-25 15:26:09.797  1958  2734 D CtrlSupplicant: Received on exit socket, terminate
08-25 15:26:09.797  1958  2734 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 15:26:09.797  1958  2314 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 15:26:09.797  1958  2734 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 15:26:09.797  1958  2734 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 15:26:09.798  1958  2313 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 15:26:09.798  1027  1530 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.798  1027  1530 D LGWifiP2pService: DefaultState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:09.803  1027  1532 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 15:26:09.804  1027  1532 D WifiNative-p2p0: TERMINATE: returned true
08-25 15:26:09.804  1027  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 15:26:09.804  1027  1532 E WifiStateMachine: useWiFiOffloading() : false
08-25 15:26:09.804  1027  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 15:26:09.804  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 15:26:09.805  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:09.805  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:09.805  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-25 15:26:09.808  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 15:26:09.808  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 15:26:09.808  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:09.808  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 15:26:09.813  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.814  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:09.814  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.814  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.814  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:09.814  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:09.814  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:09.814  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:09.814  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:09.814  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.814  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:09.817  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.817  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:09.817  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:09.817  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:09.817  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:09.817  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:09.817  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:09.817  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:09.817  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:09.817  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:09.817  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:09.823  6968  6968 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:26:09.823  6968  6968 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 15:26:09.824  6968  6968 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 15:26:09.824  6968  6968 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-25 15:26:09.825  6968  6968 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 15:26:09.826  6968  6968 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 15:26:09.826  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 15:26:09.827  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:09.828  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:09.828  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:09.828  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:09.829  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:09.854  6946  6946 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 15:26:09.854  6946  6946 W LG Account v2.2: No ProfileInfo entries
08-25 15:26:09.854  6946  6946 I LG Account v2.2: isEnabled: false
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]Country: EU
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]Operator: OPEN
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]Ranking support: false
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]Comfort support: false
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]Accessory: true
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]Health device: true
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]Extra Pedometer: false
08-25 15:26:09.854  6946  6946 I Feature : [Lifetracker]Blood glucose device: false
08-25 15:26:09.855  6946  6946 I Feature : [Lifetracker]Device Number: 3
,08-25 15:26:09.863  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:09.882  1027  2809 D DhcpStateMachine: StoppedState
08-25 15:26:09.882  1027  2809 D DhcpStateMachine: StoppedState{ when=-88ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:26:09.896  1027  2010 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6989 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 15:26:09.897  1027  2010 I ActivityManager: Killing 5872:com.google.android.talk/u0a72 (adj 15): empty #17
,08-25 15:26:09.898  2656  2656 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 15:26:09.898  2656  2656 I wpa_supplicant: monitor socket send errors count : 1
08-25 15:26:09.898  2656  2656 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1958-2\x00 that cannot receive messages
,08-25 15:26:09.899  1027  2724 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 15:26:09.899  1027  2724 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 15:26:09.928  1027  1532 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 15:26:09.929  1027  1043 W libprocessgroup: failed to open /acct/uid_10072/pid_5872/cgroup.procs: No such file or directory
08-25 15:26:09.929  1027  1532 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-25 15:26:09.937  2656  2656 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 15:26:09.937  1027  2724 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 15:26:09.937  1027  2724 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 15:26:09.937  1027  2724 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 15:26:09.937  1027  2724 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 15:26:09.937  2656  2656 W wpa_supplicant: USIM:  scard_deinit function
08-25 15:26:09.938  1027  1532 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183666
08-25 15:26:09.938  1027  1089 D Tethering: InitialState.processMessage what=4
08-25 15:26:09.938  1027  1532 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=183667
08-25 15:26:09.938  1027  2724 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:09.938  1027  2724 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:09.939  1027  1532 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=183668  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 15:26:09.939  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:26:09.940  1027  1532 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=183668  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 15:26:09.940  1027  1532 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:09.940  1027  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-25 15:26:09.944  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-25 15:26:09.945  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:09.946  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:09.946  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 15:26:09.946  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:09.947  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:09.948  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:09.971  6989  6989 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 15:26:09.980  6989  6989 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 15:26:09.981  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:09.982  1027  1044 I ActivityManager: Killing 6307:com.android.defcontainer/u0a4 (adj 15): empty #17
08-25 15:26:10.013  6968  6968 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 15:26:10.020  1027  2010 W libprocessgroup: failed to open /acct/uid_10004/pid_6307/cgroup.procs: No such file or directory
08-25 15:26:10.037  3855  3855 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 15:26:10.037  3855  3855 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:10.037  3855  3855 V BluetoothPbapReceiver: ***********state = 13
08-25 15:26:10.039  3855  3855 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-25 15:26:10.041  3855  3855 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:10.041  3855  3855 V BluetoothPbapService: state: 13
08-25 15:26:10.041  3855  3855 V BluetoothPbapService: Pbap Service closeService in
08-25 15:26:10.046  3855  3855 V BluetoothPbapService: successfully stopped pbap service
08-25 15:26:10.046  3855  3855 V BluetoothPbapService: Pbap Service closeService out
08-25 15:26:10.046  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 15:26:10.046  3855  3855 V BluetoothPbapService: Pbap Service onDestroy
08-25 15:26:10.046  3855  3855 V BluetoothPbapService: Pbap Service closeService in
08-25 15:26:10.046  3855  3855 V BluetoothPbapService: Pbap Service closeService out
08-25 15:26:10.046  3855  3855 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 15:26:10.064  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:10.069  2656  2656 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-25 15:26:10.070  1027  2724 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 15:26:10.070  1027  2724 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 15:26:10.070  1027  2724 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 15:26:10.071  1027  1532 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-25 15:26:10.090  6832  6832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 15:26:10.112  6968  6968 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:10.112  6968  6968 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:26:10.123  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:10.131  1027  1089 D BluetoothManagerService: Message: 20
08-25 15:26:10.132  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@49090dc:true
,08-25 15:26:10.145  1027  1089 D BluetoothManagerService: Message: 30
,08-25 15:26:10.155  1027  1089 D BluetoothManagerService: Message: 30
08-25 15:26:10.160  6968  6968 D LocalBluetoothProfileManager: Adding local MAP profile
,08-25 15:26:10.164  6968  6968 D BluetoothMap: Create BluetoothMap proxy object
,08-25 15:26:10.165  1027  1089 D BluetoothManagerService: Message: 30
08-25 15:26:10.173  1027  1532 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 15:26:10.173  1027  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 15:26:10.173  1027  1532 E WifiStateMachine: useWiFiOffloading() : false
08-25 15:26:10.173  1027  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 15:26:10.174  1958  1958 D WfdsService: Supplicant Connection state is changed : false
08-25 15:26:10.174  1958  2313 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 15:26:10.174  1027  1089 D BluetoothManagerService: Message: 30
,08-25 15:26:10.174  1958  2313 D WfdsService: Set the WFDS Monitor: false
08-25 15:26:10.175  1958  2313 D WfdsMonitor: WFDS Monitor is stopped
08-25 15:26:10.178  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:10.180  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 15:26:10.181  2455  2455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:10.181  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 15:26:10.181  1027  1536 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 15:26:10.182  1027  1536 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 15:26:10.184  6968  6968 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 15:26:10.184  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:10.186  6968  6968 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-25 15:26:10.186  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:10.209  6968  6968 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 15:26:10.213  6968  6968 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-25 15:26:10.226  6968  6968 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:26:10.251  6968  6968 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 15:26:10.255  6968  6968 D BluetoothInputDevice: Proxy object connected
08-25 15:26:10.258  6968  6968 D HidProfile: Bluetooth service connected
08-25 15:26:10.260  6968  6968 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 15:26:10.261  6968  6968 D PanProfile: Bluetooth service connected
08-25 15:26:10.262  6968  6968 D BluetoothMap: Proxy object connected
08-25 15:26:10.263  6968  6968 D MapProfile: Bluetooth service connected
08-25 15:26:10.263  6968  6968 D BluetoothMap: getConnectedDevices()
,08-25 15:26:10.264  6968  6968 D BluetoothMap: Bluetooth is Not enabled
08-25 15:26:10.264  6968  6968 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 15:26:10.266  6968  6968 D BluetoothPermissionRequest: onReceive
08-25 15:26:10.270  6968  6968 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 15:26:10.280  1027  2104 I ActivityManager: Killing 6583:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-25 15:26:10.283  6968  6968 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-25 15:26:10.312  1027  1043 W libprocessgroup: failed to open /acct/uid_10008/pid_6583/cgroup.procs: No such file or directory
08-25 15:26:10.313  3855  3855 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-25 15:26:10.314  3855  3855 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 15:26:10.315  3855  3855 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-25 15:26:10.410  1027  2104 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7018 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 15:26:10.411  3855  3855 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:10.411  3855  3855 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 15:26:10.412  3855  3855 V BluetoothFtpService: Ftp Service onStartCommand
08-25 15:26:10.412  3855  3855 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:10.413  3855  3855 V BluetoothFtpService: Ftp Service closeService
08-25 15:26:10.413  3855  3855 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 15:26:10.417  3855  3855 V BluetoothFtpService: successfully stopped ftp service
08-25 15:26:10.417  3855  3855 V BluetoothFtpService: Ftp Service onDestroy
08-25 15:26:10.417  3855  3855 V BluetoothFtpService: Ftp Service closeService
08-25 15:26:10.419  3855  3855 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 15:26:10.419  3855  3855 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 15:26:10.419  3855  3855 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 15:26:10.420  3855  3855 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:10.420  3855  3855 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 15:26:10.420  3855  3855 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 15:26:10.422  3855  3855 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:10.422  3855  3855 V BluetoothSapService: state: 13
08-25 15:26:10.422  3855  3855 V BluetoothSapService: Stopping SAP server process
08-25 15:26:10.424  3855  3855 V BluetoothSapService: Sap Service closeSapService in
08-25 15:26:10.424  3855  3855 V BluetoothSapService: Close listen Socket : 
08-25 15:26:10.424  3855  3855 V BluetoothSapService: Close rfcomm Socket : 
08-25 15:26:10.424  3855  3855 V BluetoothSapService: Close sapd  Socket : 
,08-25 15:26:10.491  1027  2104 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7038 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 15:26:10.493  3855  3855 V BluetoothSapService: Sap Service closeSapService out
08-25 15:26:10.493  3855  3855 V BluetoothSapService: Sap Service onDestroy
08-25 15:26:10.493  3855  3855 V BluetoothSapService: Sap Service closeSapService in
08-25 15:26:10.493  3855  3855 V BluetoothSapService: Close listen Socket : 
08-25 15:26:10.493  3855  3855 V BluetoothSapService: Close rfcomm Socket : 
08-25 15:26:10.493  3855  3855 V BluetoothSapService: Close sapd  Socket : 
,08-25 15:26:10.501  3855  3855 V BluetoothSapService: Sap Service closeSapService out
08-25 15:26:10.540  7018  7018 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 15:26:10.561  7038  7038 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 15:26:10.580  1027  1043 I ActivityManager: Killing 6356:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-25 15:26:10.620  1027  2105 W libprocessgroup: failed to open /acct/uid_10011/pid_6356/cgroup.procs: No such file or directory
,08-25 15:26:10.627  7018  7018 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-25 15:26:10.675  7018  7018 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 15:26:10.676  7018  7018 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-25 15:26:10.676  7018  7018 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-25 15:26:10.677  7018  7018 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 15:26:10.677  7018  7018 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 15:26:10.679  7018  7018 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 15:26:10.682  3855  3955 D bt_hci_bdroid: cleanup
,08-25 15:26:10.682  3855  4037 W bt-btif : ag scb idx 1 not allocated
08-25 15:26:10.682  3855  4037 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:10.682  3855  4040 I bt_lpm  : LPM is already off!!!
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:26:10.682  3855  4203 I bt_userial_mct: exiting userial_read_thread
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:10.682  3855  4203 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:26:10.682  3855  3955 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 15:26:10.682  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:10.683  3855  4037 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:26:10.683  3855  4040 I bt_vendor: hw_epilog_process
08-25 15:26:10.683  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:10.683  3855  4037 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:26:10.683  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:10.683  3855  4037 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:26:10.683  3855  4037 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:10.683  3855  4037 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:26:10.683  3855  3955 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 15:26:10.683  3855  3955 D bt_userial_mct: userial_close
08-25 15:26:10.683  3855  3955 E bt_userial_mct: pthread_join() FAILED result:3
08-25 15:26:10.683  3855  4037 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 15:26:10.683  3855  3955 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 15:26:10.686  7018  7018 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 15:26:10.694  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:10.700  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 15:26:10.733  7018  7018 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 15:26:10.739  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:10.743  7018  7018 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 15:26:10.744  6989  6989 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 15:26:10.744  6989  6989 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 15:26:10.744  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:10.749  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:10.751  7018  7018 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-25 15:26:10.759  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:10.767  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:10.768  3855  3955 D bt_hci_bdroid: set_power 0
08-25 15:26:10.768  3855  3955 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 15:26:10.768  3855  3955 I bt_vendor: bluetooth satus is on
08-25 15:26:10.768  3855  3955 I bt_vendor: bt-vendor : resetting BT status
08-25 15:26:10.768  3855  3955 I bt_vendor: Starting hciattach daemon
08-25 15:26:10.768  3855  3955 I bt_vendor: try to set false
08-25 15:26:10.771  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:10.773  7018  7018 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 15:26:10.776  3855  3955 I bt_vendor: Starting hciattach daemon
08-25 15:26:10.776  3855  3955 I bt_vendor: try to set false
08-25 15:26:10.776  3855  3955 I bt_vendor: cleanup
08-25 15:26:10.776  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:10.777  3855  4037 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 15:26:10.777  3855  3955 I GKI_LINUX: GKI_exit_task 0 done
08-25 15:26:10.777  3855  3955 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 15:26:10.780  3855  3951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 15:26:10.780  6989  6989 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 15:26:10.780  6989  6989 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 15:26:10.780  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:10.786  3855  3855 D HeadsetService: Received stop request...Stopping profile...
,08-25 15:26:10.789  3855  3855 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 15:26:10.789  3855  3855 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:26:10.789  3855  3855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e87f124
08-25 15:26:10.790  3855  3964 D HeadsetStateMachine: Exit Disconnected: -1
08-25 15:26:10.790  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-25 15:26:10.791  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 15:26:10.791  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-25 15:26:10.791  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-25 15:26:10.792  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:10.793  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-25 15:26:10.795  3855  3855 D A2dpService: Received stop request...Stopping profile...
08-25 15:26:10.795  3855  4016 D A2dpStateMachine: Exit Disconnected: -1
08-25 15:26:10.798  3855  3855 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 15:26:10.799  3855  3951 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-25 15:26:10.802  3855  3855 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 15:26:10.802  3855  3855 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:26:10.802  3855  3855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e87f124
08-25 15:26:10.804  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-25 15:26:10.804  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 15:26:10.804  3855  3855 D HidService: Received stop request...Stopping profile...
08-25 15:26:10.804  3855  3855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e87f124
08-25 15:26:10.806  3855  3855 D HeadsetStateMachine: Unbinding service...
08-25 15:26:10.807  3855  3855 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 15:26:10.807  3855  3855 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 15:26:10.807  3855  3855 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 15:26:10.807  3855  3855 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 15:26:10.808  3855  3855 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 15:26:10.808  3855  3855 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:26:10.808  3855  3855 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 15:26:10.808  3855  3855 D HealthService: Received stop request...Stopping profile...
08-25 15:26:10.808  3855  3855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e87f124
08-25 15:26:10.810  3855  3855 D PanService: Received stop request...Stopping profile...
08-25 15:26:10.810  3855  3855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e87f124
08-25 15:26:10.811  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:10.813  3855  3855 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 15:26:10.813  3855  3855 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 15:26:10.813  3855  3855 D BtGatt.GattService: stop()
08-25 15:26:10.813  3855  3855 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 15:26:10.814  3855  3855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e87f124
,08-25 15:26:10.815  3855  3855 D BluetoothMapService: Received stop request...Stopping profile...
08-25 15:26:10.816  3855  3855 D BluetoothMapService: stop()
08-25 15:26:10.816  3855  3855 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 15:26:10.817  3855  3855 D BluetoothMapEmailAppObserver: removeReceiver()
,08-25 15:26:10.817  6968  6968 D BluetoothInputDevice: Proxy object disconnected
08-25 15:26:10.817  3855  3855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e87f124
08-25 15:26:10.817  6968  6968 D HidProfile: Bluetooth service disconnected
08-25 15:26:10.818  6968  6968 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 15:26:10.818  6968  6968 D PanProfile: Bluetooth service disconnected
08-25 15:26:10.819  3855  3855 I BluetoothA2dpServiceJni: cleanupNative
08-25 15:26:10.819  6968  6968 D BluetoothMap: Proxy object disconnected
08-25 15:26:10.819  6968  6968 D MapProfile: Bluetooth service disconnected
08-25 15:26:10.820  3855  4018 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 15:26:10.820  3855  3855 I GKI_LINUX: GKI_exit_task 2 done
08-25 15:26:10.820  3855  3855 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 15:26:10.821  3855  3855 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 15:26:10.821  3855  3855 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 15:26:10.821  3855  3855 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 15:26:10.821  3855  3855 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 15:26:10.821  3855  3855 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 15:26:10.822  3855  3855 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 15:26:10.822  3855  3855 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 15:26:10.824  3855  3855 V BluetoothMapService: Handler(): got msg=4
08-25 15:26:10.824  3855  3855 D BluetoothMapService: MAP Service closeService in
08-25 15:26:10.824  3855  3855 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 15:26:10.824  3855  3855 V BluetoothMapService: MAP Service closeService out
08-25 15:26:10.825  3855  3951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 15:26:10.825  3855  3951 D BluetoothAdapterProperties: Setting state to 10
08-25 15:26:10.825  3855  3951 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 15:26:10.826  1027  1089 D BluetoothManagerService: Message: 60
08-25 15:26:10.826  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 15:26:10.826  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-25 15:26:10.826  3855  3855 D BluetoothMapService: cleanup()
08-25 15:26:10.826  3855  3855 D BluetoothMapService: MAP Service closeService in
08-25 15:26:10.826  3855  3855 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 15:26:10.826  3855  3855 V BluetoothMapService: MAP Service closeService out
08-25 15:26:10.827  1871  1887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:10.828  3855  3951 I BluetoothAdapterState: Entering OffState
,08-25 15:26:10.829  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:10.830  1871  1886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:10.830  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:10.831  6968  6984 D BluetoothPan: onBluetoothStateChange on: false
08-25 15:26:10.832  6968  6983 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 15:26:10.832  7018  7018 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 15:26:10.832  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:10.832  1871  2475 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:10.833  6968  6984 D BluetoothMap: onBluetoothStateChange: up=false
08-25 15:26:10.833  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 15:26:10.834  6968  6983 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 15:26:10.836  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 15:26:10.836  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 15:26:10.841  1027  1089 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,08-25 15:26:10.843  1027  1089 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 15:26:10.843  1027  1089 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2f51e2d mBinding = false
08-25 15:26:10.843  1027  1089 D BluetoothManagerService: Sending unbind request.
08-25 15:26:10.894  1027  2029 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7062 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 15:26:10.910  3855  3955 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-25 15:26:10.910  3855  3855 I GKI_LINUX: GKI_exit_task 1 done
08-25 15:26:10.910  3855  3855 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 15:26:10.911  3855  3855 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 15:26:10.911  3855  3855 I art     : --- WEIRD: removing null entry 246
08-25 15:26:10.911  3855  3855 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 15:26:10.911  3855  3855 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 15:26:10.912  3855  3855 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 15:26:10.913  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 15:26:10.915  3855  3855 I art     : System.exit called, status: 0
08-25 15:26:10.915  3855  3855 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 15:26:10.920  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:10.921  1958  2184 D LGBluetoothAPIService: Message: 2
08-25 15:26:10.921  1958  2184 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3acd0d9d mBinding = false
08-25 15:26:10.921  1958  2184 D LGBluetoothAPIService: Sending unbind request.
08-25 15:26:10.923  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:10.924  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:10.924  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 15:26:10.934   311  1377 V AudioFlinger: 3855 died, releasing its sessions
08-25 15:26:10.934   311  1377 V AudioFlinger:  pid 1871 @ 0
08-25 15:26:10.934   311  1377 V AudioFlinger:  pid 3276 @ 1
08-25 15:26:10.934   311  1377 V AudioFlinger:  pid 3276 @ 2
,08-25 15:26:10.937  6968  6968 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 15:26:10.938  6968  6968 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 15:26:10.938  6968  6968 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 15:26:10.939  1597  1597 D BluetoothAdapter: 305571086: getState() :  mService = null. Returning STATE_OFF,
08-25 15:26:10.939  1597  1597 D BluetoothAdapter: 305571086: getState() :  mService = null. Returning STATE_OFF
08-25 15:26:10.942  6968  6968 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 15:26:10.957  1027  1734 I ActivityManager: Process com.android.bluetooth (pid 3855) has died
,08-25 15:26:10.958  1027  1734 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-25 15:26:10.965  6968  6968 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 15:26:11.014  1027  1043 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7090 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 15:26:11.020  6968  6968 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:26:11.062  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 15:26:11.065  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 15:26:11.070  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:11.072  7090  7090 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 15:26:11.073  7090  7090 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 15:26:11.073  7090  7090 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 15:26:11.074  7090  7090 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 15:26:11.088  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 15:26:11.088  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 15:26:11.088  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 15:26:11.088  6968  6968 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 15:26:11.088  7062  7111 W FormManager: Network not available. Please check & try again.
08-25 15:26:11.089  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-25 15:26:11.095  7090  7090 D BluetoothAdapterApp: Loading JNI Library
08-25 15:26:11.096  7062  7112 V FormManager: Network unavailable.
08-25 15:26:11.098  6968  6968 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 15:26:11.098  7062  7112 V FormManager: Network unavailable.
08-25 15:26:11.098  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 15:26:11.098  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 15:26:11.098  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 15:26:11.098  6968  6968 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 15:26:11.098  6968  6968 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 15:26:11.101  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 15:26:11.102  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 15:26:11.104  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:11.107  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 15:26:11.113  4348  7115 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 15:26:11.114  4348  7116 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 15:26:11.115  4348  7116 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 15:26:11.116  6989  6989 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 15:26:11.116  6989  6989 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 15:26:11.116  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:11.118  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:26:11.124  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:11.128  7062  7118 W FormManager: Network not available. Please check & try again.
08-25 15:26:11.135  7090  7090 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@12a97fd5 Instance Count = 1
,08-25 15:26:11.139  7062  7119 V FormManager: Network unavailable.
08-25 15:26:11.139  7090  7090 D BluetoothAdapterApp: onCreate
08-25 15:26:11.140  7018  7018 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 15:26:11.141  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 15:26:11.142  7018  7018 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 15:26:11.143  7062  7119 V FormManager: Network unavailable.
08-25 15:26:11.149  1027  2022 I ActivityManager: Killing 5945:com.android.contacts/u0a19 (adj 15): empty #17
,08-25 15:26:11.158  7090  7090 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 15:26:11.158  7090  7090 D ProfileConfigQcom: Adding HeadsetService
08-25 15:26:11.158  7090  7090 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 15:26:11.158  7090  7090 D ProfileConfigQcom: Adding A2dpService
08-25 15:26:11.159  7090  7090 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 15:26:11.159  7090  7090 D ProfileConfigQcom: Adding HidService
08-25 15:26:11.159  7090  7090 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 15:26:11.159  7090  7090 D ProfileConfigQcom: Adding HealthService
08-25 15:26:11.160  7090  7090 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 15:26:11.160  7090  7090 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 15:26:11.161  7090  7090 D ProfileConfigQcom: Adding PanService
08-25 15:26:11.161  7090  7090 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 15:26:11.161  7090  7090 D ProfileConfigQcom: Adding GattService
08-25 15:26:11.161  7090  7090 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 15:26:11.161  7090  7090 D ProfileConfigQcom: Adding BluetoothMapService
08-25 15:26:11.162  7090  7090 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-25 15:26:11.162  7090  7090 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 15:26:11.163  7090  7090 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:11.164  7090  7090 V BluetoothPbapReceiver: ***********state = 10
08-25 15:26:11.166  7090  7090 V LGMDMManagerInternal: Create singleton instance
08-25 15:26:11.170  7018  7018 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:11.170  7018  7018 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 15:26:11.175  7018  7018 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-25 15:26:11.175  7018  7018 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 15:26:11.175  7018  7018 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-25 15:26:11.175  7018  7018 V SoundPool: doLoad: loading sample sampleID=1
08-25 15:26:11.177  7018  7124 V SoundPool: Start decode
08-25 15:26:11.177  7018  7124 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-25 15:26:11.177   311  1377 V MediaPlayerService: decode(22, 10857164, 17813)
08-25 15:26:11.177   311  1377 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 15:26:11.177   311  1377 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 15:26:11.177   311  1377 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 15:26:11.177   311  1377 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 15:26:11.177   311  1377 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 15:26:11.177   311  1377 V MediaPlayerService: player type = 3
08-25 15:26:11.177   311  1377 V AwesomePlayer: AwesomePlayer create()
08-25 15:26:11.177   311  1377 V AwesomePlayer: reset_l() 
08-25 15:26:11.177   311  1377 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:11.178   311  1377 V AwesomePlayer: setAudioSink() 
08-25 15:26:11.178   311  1377 V AwesomePlayer: reset_l() 
08-25 15:26:11.178   311  1377 V AudioCache: notify(0xb5474b80, 8, 0, 0)
08-25 15:26:11.178   311  1377 V AudioCache: ignored
08-25 15:26:11.178   311  1377 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:11.178   311  1377 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 15:26:11.178   311  1377 V AwesomePlayer: setDataSource_l dataSource
08-25 15:26:11.178   311  1377 V LGParserOSAL: SniffLGParser start
08-25 15:26:11.178   311  1377 V LGParserOSAL: MainType:5, SubType=0
08-25 15:26:11.178   311  1377 V LGParserOSAL: #### check Mime : application/ogg
08-25 15:26:11.178   311  1377 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 15:26:11.178   311  1377 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 15:26:11.184  7018  7018 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 15:26:11.203   311  1377 V LGParserOSAL: supported mime: application/ogg
08-25 15:26:11.203   311  1377 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 15:26:11.203   311  1377 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 15:26:11.203   311  1377 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 15:26:11.203   311  1377 V AwesomePlayer: AudioTrack Setting
08-25 15:26:11.203   311  1377 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 15:26:11.203   311  1377 V AwesomePlayer: setAudioSource() 
08-25 15:26:11.203   311  1377 V MediaPlayerService: prepare
08-25 15:26:11.203   311  1377 V AwesomePlayer: prepareAsync_l() 
08-25 15:26:11.204   311  1377 V MediaPlayerService: wait for prepare
08-25 15:26:11.204   311  7125 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 15:26:11.204   311  7125 V AwesomePlayer: initAudioDecoder() 
08-25 15:26:11.204   311  7125 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 15:26:11.204   311  7125 V AudioSystem: isOffloadSupported()
08-25 15:26:11.204   311  7125 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 15:26:11.204   311  7125 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 15:26:11.204   311  7125 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 15:26:11.204   311  7125 V AwesomePlayer: getUseOffload() = 0 
08-25 15:26:11.204   311  7125 V OMXCodec: OMXCodec::Create
08-25 15:26:11.204   311  7125 V OMXCodec: findMatchingCodecs()
08-25 15:26:11.204   311  7125 V OMXCodec: matching 'OMX.google.vorbis.decoder' quir,ks 0x00000000
08-25 15:26:11.204   311  7125 V OMXCodec: matchingCodecs.size()=1
08-25 15:26:11.204   311  7125 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-25 15:26:11.206   311  7125 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 15:26:11.206   311  7125 V LGCodecAdapter: LG Codec Adapter start
08-25 15:26:11.206   311  7125 V OMXCodec: OMXCodec Createtor
08-25 15:26:11.206   311  7125 V OMXCodec: setComponentRole
08-25 15:26:11.206   311  7125 V OMXCodec: configureCodec protected=0
08-25 15:26:11.206   311  7125 V LGCodecAdapter: called getLGCodecSpecificData
08-25 15:26:11.206   311  7125 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 15:26:11.206   311  7125 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 15:26:11.206   311  7125 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 15:26:11.206   311  7125 V LGCodecOSAL: Not support LGCodec
08-25 15:26:11.206   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 15:26:11.206   311  7125 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 15:26:11.206   311  7125 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 15:26:11.207   311  7125 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 15:26:11.207   311  7125 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 15:26:11.207   311  7125 V AudioSystem: isOffloadSupported()
08-25 15:26:11.207   311  7125 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 15:26:11.207   311  7125 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 15:26:11.207   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 15:26:11.207   311  7125 V OMXCodec: init()
08-25 15:26:11.207   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 15:26:11.207   311  7125 V OMXCodec: allocateBuffers
08-25 15:26:11.207   311  7125 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 15:26:11.207   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 15:26:11.208   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04080b0 on input port
08-25 15:26:11.208   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408100 on input port
08-25 15:26:11.208   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408150 on input port
08-25 15:26:11.208   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04081a0 on input port
08-25 15:26:11.208   311  7125 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 15:26:11.208   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 15:26:11.209   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04081f0 on output port
08-25 15:26:11.209   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408290 on output port
08-25 15:26:11.209   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04082e0 on output port
08-25 15:26:11.209   311  7125 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408510 on output port
08-25 15:26:11.209   311  7125 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 15:26:11.209   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 15:26:11.209   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 15:26:11.209   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 15:26:11.209   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 15:26:11.209   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 15:26:11.209   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-25 15:26:11.209   311  7125 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 15:26:11.209   311  7125 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 15:26:11.209   311  7125 V AudioCache: notify(0xb5474b80, 5, 0, 0)
08-25 15:26:11.209   311  7125 V AudioCache: ignored
08-25 15:26:11.209   311  7125 V AudioCache: notify(0xb5474b80, 1, 0, 0)
08-25 15:26:11.209   311  7125 V AudioCache: prepared
08-25 15:26:11.209   311  1377 V AudioCache: wait - success
08-25 15:26:11.209   311  1377 V MediaPlayerService: start
08-25 15:26:11.209   311  1377 V AwesomePlayer: play_l() 
08-25 15:26:11.209   311  1377 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 15:26:11.209   311  1377 V AwesomePlayer: createAudioPlayer_l
08-25 15:26:11.209   311  1377 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 15:26:11.209   311  1377 V AwesomePlayer: startAudioPlayer_l() 
08-25 15:26:11.209   311  1377 D AudioPlayer: start of Playback, useOffload 0
08-25 15:26:11.209   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 15:26:11.209   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957017584
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957017744
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0,
,08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957017824
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957018384
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 15:26:11.211   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 15:26:11.211   311  7127 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-25 15:26:11.212   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 15:26:11.212   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04082e0 on output port
08-25 15:26:11.212   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408290 on output port
08-25 15:26:11.212   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04081f0 on output port
08-25 15:26:11.212   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
,08-25 15:26:11.212   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 15:26:11.212   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 15:26:11.212   311  1377 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 15:26:11.212   311  1377 V AudioCache: notify(0xb5474b80, 6, 0, 0)
08-25 15:26:11.212   311  1377 V AudioCache: ignored
,08-25 15:26:11.213   311  1377 V MediaPlayerService: wait for playback complete
08-25 15:26:11.213   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.213   311  7128 V AudioCache: memcpy(0xaf006000, 0xb1015000, 4096)
08-25 15:26:11.214   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.214   311  7128 V AudioCache: memcpy(0xaf007000, 0xb1015000, 4096)
08-25 15:26:11.214   311  7128 V AudioCache: write(0xb1015000, 4096)
,08-25 15:26:11.214   311  7128 V AudioCache: memcpy(0xaf008000, 0xb1015000, 4096)
08-25 15:26:11.214   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.214   311  7128 V AudioCache: memcpy(0xaf009000, 0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: memcpy(0xaf00a000, 0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: write(0xb1015000, 4096)
,08-25 15:26:11.215   311  7128 V AudioCache: memcpy(0xaf00b000, 0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: memcpy(0xaf00c000, 0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: memcpy(0xaf00d000, 0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: memcpy(0xaf00e000, 0xb1015000, 4096)
,08-25 15:26:11.215   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.215   311  7128 V AudioCache: memcpy(0xaf00f000, 0xb1015000, 4096)
08-25 15:26:11.216   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.216   311  7128 V AudioCache: memcpy(0xaf010000, 0xb1015000, 4096)
08-25 15:26:11.216   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.216   311  7128 V AudioCache: memcpy(0xaf011000, 0xb1015000, 4096)
,08-25 15:26:11.216   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.216   311  7128 V AudioCache: memcpy(0xaf012000, 0xb1015000, 4096)
08-25 15:26:11.217   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.217   311  7128 V AudioCache: memcpy(0xaf013000, 0xb1015000, 4096)
08-25 15:26:11.217   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.217   311  7128 V AudioCache: memcpy(0xaf014000, 0xb1015000, 4096)
08-25 15:26:11.218   311  7128 V AudioCache: write(0xb1015000, 4096)
,08-25 15:26:11.218   311  7128 V AudioCache: memcpy(0xaf015000, 0xb1015000, 4096)
08-25 15:26:11.219   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.219   311  7128 V AudioCache: memcpy(0xaf016000, 0xb1015000, 4096)
08-25 15:26:11.219   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.219   311  7128 V AudioCache: memcpy(0xaf017000, 0xb1015000, 4096)
08-25 15:26:11.219   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.219   311  7128 V AudioCache: memcpy(0xaf018000, 0xb1015000, 4096)
,08-25 15:26:11.220   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.220   311  7128 V AudioCache: memcpy(0xaf019000, 0xb1015000, 4096)
08-25 15:26:11.220   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.220   311  7128 V AudioCache: memcpy(0xaf01a000, 0xb1015000, 4096)
08-25 15:26:11.220   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.220   311  7128 V AudioCache: memcpy(0xaf01b000, 0xb1015000, 4096)
08-25 15:26:11.220   311  7128 V AudioCache: write(0xb1015000, 4096)
,08-25 15:26:11.220   311  7128 V AudioCache: memcpy(0xaf01c000, 0xb1015000, 4096)
08-25 15:26:11.221   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.221   311  7128 V AudioCache: memcpy(0xaf01d000, 0xb1015000, 4096)
08-25 15:26:11.221   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.221   311  7128 V AudioCache: memcpy(0xaf01e000, 0xb1015000, 4096)
08-25 15:26:11.221   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.221   311  7128 V AudioCache: memcpy(0xaf01f000, 0xb1015000, 4096)
,08-25 15:26:11.222   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.222   311  7128 V AudioCache: memcpy(0xaf020000, 0xb1015000, 4096)
08-25 15:26:11.222   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.222   311  7128 V AudioCache: memcpy(0xaf021000, 0xb1015000, 4096)
08-25 15:26:11.222   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.222   311  7128 V AudioCache: memcpy(0xaf022000, 0xb1015000, 4096)
08-25 15:26:11.222   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.223   311  7128 V AudioCache: memcpy(0xaf023000, 0xb1015000, 4096)
,08-25 15:26:11.223   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.223   311  7128 V AudioCache: memcpy(0xaf024000, 0xb1015000, 4096)
08-25 15:26:11.223   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.223   311  7128 V AudioCache: memcpy(0xaf025000, 0xb1015000, 4096)
08-25 15:26:11.223   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.223   311  7128 V AudioCache: memcpy(0xaf026000, 0xb1015000, 4096)
08-25 15:26:11.224   311  7128 V AudioCache: write(0xb1015000, 4096)
,08-25 15:26:11.224   311  7128 V AudioCache: memcpy(0xaf027000, 0xb1015000, 4096)
08-25 15:26:11.224   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.224   311  7128 V AudioCache: memcpy(0xaf028000, 0xb1015000, 4096)
08-25 15:26:11.224   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.224   311  7128 V AudioCache: memcpy(0xaf029000, 0xb1015000, 4096)
08-25 15:26:11.225   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.225   311  7128 V AudioCache: memcpy(0xaf02a000, 0xb1015000, 4096)
,08-25 15:26:11.225   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.225   311  7128 V AudioCache: memcpy(0xaf02b000, 0xb1015000, 4096)
08-25 15:26:11.225   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.225   311  7128 V AudioCache: memcpy(0xaf02c000, 0xb1015000, 4096)
08-25 15:26:11.226   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.226   311  7128 V AudioCache: memcpy(0xaf02d000, 0xb1015000, 4096)
08-25 15:26:11.226   311  7128 V AudioCache: write(0xb1015000, 4096)
,08-25 15:26:11.226   311  7128 V AudioCache: memcpy(0xaf02e000, 0xb1015000, 4096)
08-25 15:26:11.226   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.226   311  7128 V AudioCache: memcpy(0xaf02f000, 0xb1015000, 4096)
08-25 15:26:11.227   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.227   311  7128 V AudioCache: memcpy(0xaf030000, 0xb1015000, 4096)
08-25 15:26:11.227   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.227   311  7128 V AudioCache: memcpy(0xaf031000, 0xb1015000, 4096)
,08-25 15:26:11.228   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.228   311  7128 V AudioCache: memcpy(0xaf032000, 0xb1015000, 4096)
08-25 15:26:11.228   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.228   311  7128 V AudioCache: memcpy(0xaf033000, 0xb1015000, 4096)
08-25 15:26:11.228   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.228   311  7128 V AudioCache: memcpy(0xaf034000, 0xb1015000, 4096)
08-25 15:26:11.230   311  7128 V AudioCache: write(0xb1015000, 4096)
,08-25 15:26:11.230   311  7128 V AudioCache: memcpy(0xaf035000, 0xb1015000, 4096)
08-25 15:26:11.230   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.230   311  7128 V AudioCache: memcpy(0xaf036000, 0xb1015000, 4096)
08-25 15:26:11.230   311  7128 V AudioCache: write(0xb1015000, 4096)
08-25 15:26:11.230   311  7128 V AudioCache: memcpy(0xaf037000, 0xb1015000, 4096)
08-25 15:26:11.230   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 15:26:11.230   311  7128 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-25 15:26:11.230   311  7128 V AwesomePlayer: postAudioEOS() 
08-25 15:26:11.230   311  7128 V AudioCache: write(0xb1015000, 280)
08-25 15:26:11.231   311  7128 V AudioCache: memcpy(0xaf038000, 0xb1015000, 280)
08-25 15:26:11.232   311  7125 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 15:26:11.232   311  7125 V AwesomePlayer: onStreamDone
08-25 15:26:11.232   311  7125 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 15:26:11.232   311  7125 V AudioCache: notify(0xb5474b80, 2, 0, 0)
,08-25 15:26:11.232   311  7125 V AudioCache: playback complete
08-25 15:26:11.232   311  7125 V AwesomePlayer: pause_l() 
08-25 15:26:11.232   311  7125 V AudioCache: notify(0xb5474b80, 7, 0, 0)
08-25 15:26:11.232   311  7125 V AudioCache: ignored
08-25 15:26:11.232   311  7125 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:11.232   311  1377 V AudioCache: wait - success
08-25 15:26:11.232   311  1377 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,08-25 15:26:11.232   311  7125 D AudioPlayer: Pause Playback at 1068125
08-25 15:26:11.233   311  1377 V AwesomePlayer: reset_l() 
08-25 15:26:11.233   311  1377 V AudioCache: notify(0xb5474b80, 8, 0, 0)
08-25 15:26:11.233   311  1377 V AudioCache: ignored
08-25 15:26:11.233   311  1377 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:11.233   311  1377 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,08-25 15:26:11.233   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 15:26:11.233   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 15:26:11.233   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 15:26:11.233   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04081a0 on port 0
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0408150 on port 0
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
,08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0408100 on port 0
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04080b0 on port 0
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04081f0 on port 1
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
,08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0408290 on port 1
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04082e0 on port 1
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 15:26:11.233   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 15:26:11.233   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
,08-25 15:26:11.233   311  7127 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 15:26:11.234   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 15:26:11.234   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 15:26:11.234   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 15:26:11.234   311  1377 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 15:26:11.234   311  1377 D AudioPlayer: AudioPlayer releasing audio source
08-25 15:26:11.234   311  1377 D AudioPlayer: AudioPlayer done releasing audio source
08-25 15:26:11.234   311  1377 V AwesomePlayer: reset_l() 
08-25 15:26:11.234   311  1377 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:11.234   311  1377 V AwesomePlayer: ~AwesomePlayer call
,08-25 15:26:11.234   311  1377 V AwesomePlayer: reset_l() 
08-25 15:26:11.234   311  1377 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:11.235  7018  7124 V SoundPool: close(32)
08-25 15:26:11.235  7018  7124 V SoundPool: pointer = 0x9ff2d000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 15:26:11.239  1027  1044 W libprocessgroup: failed to open /acct/uid_10019/pid_5945/cgroup.procs: No such file or directory
,08-25 15:26:11.245  6668  6668 D UEI.SmartControl: QS Service created
08-25 15:26:11.246  7018  7018 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 15:26:11.248  7018  7018 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-25 15:26:11.248  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 15:26:11.260  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 15:26:11.260  6968  6968 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 15:26:11.262  7018  7018 V LGMDMManager: Create singleton instance
08-25 15:26:11.265  6668  6668 I UEI.SmartControl: Service initServices...
08-25 15:26:11.265  6668  6668 D UEI.SmartControl: QS start get config
,08-25 15:26:11.269  6968  6968 D BluetoothPermissionRequest: onReceive
08-25 15:26:11.271  6968  6968 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 15:26:11.272  6968  6968 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 15:26:11.274  6968  6968 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 15:26:11.276  7090  7090 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-25 15:26:11.280  7090  7090 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:11.282  7090  7090 V BluetoothSapReceiver: [BTUI] checkServiceStart,
08-25 15:26:11.282  7090  7090 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 15:26:11.283  7090  7090 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 15:26:11.284  7090  7090 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:11.284  7090  7090 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 15:26:11.291  7038  7038 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-25 15:26:11.318  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-25 15:26:11.318  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 15:26:11.320  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5415
08-25 15:26:11.549  6668  6668 I UEI.SmartControl: Supports setup maps: true
08-25 15:26:11.552  6668  6668 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 15:26:11.552  6668  6668 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 15:26:11.552  6668  6668 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 15:26:11.552  6668  6668 I UEI.SmartControl: ### init IR Blaster...
08-25 15:26:11.555  6668  6668 D serial_port: Configuring serial port
08-25 15:26:11.556  6668  6668 E UEI.SmartControl: UEIBLaster setting for 616
08-25 15:26:11.556  6668  6668 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 15:26:11.556  6668  6668 I UEI.SmartControl: configuring settings for MAXQ616
08-25 15:26:11.556  6668  6668 I UEI.SmartControl: Get version...
,08-25 15:26:11.574  6668  7133 D UEI.SmartControl: serial port data available: 21
,08-25 15:26:11.601  6668  6668 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 15:26:11.601  6668  6668 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-25 15:26:11.601  6668  6668 I UEI.SmartControl: QS saving settings...
,08-25 15:26:11.604  6668  6668 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 15:26:11.619  6668  7133 D UEI.SmartControl: serial port data available: 4
08-25 15:26:11.650  6668  7139 I UEI.SmartControl: Device manager: loading config....
,08-25 15:26:11.665  6668  6668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-25 15:26:11.668  6668  7139 D UEI.SmartControl: ----------- loading internal config...
08-25 15:26:11.671  6668  6668 E UEI.SmartControl: Services init done
08-25 15:26:11.671  6668  6668 D UEI.SmartControl: QS Service init finished
08-25 15:26:11.673  6668  6668 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 15:26:11.673  6668  6668 D UEI.SmartControl: QS Service version code: 201091
,08-25 15:26:11.676  6668  6668 D UEI.SmartControl: Service requested: Control
08-25 15:26:11.679  6668  7139 E UEI.SmartControl: Loading SETTINGS...
08-25 15:26:11.681  6668  6668 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 15:26:11.685  7018  7018 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 15:26:11.687  6668  6684 I UEI.SmartControl: ------ IControl API: 11
08-25 15:26:11.687  6668  6684 D UEI.SmartControl: File observer start...
,08-25 15:26:11.689  6668  6684 E UEI.SmartControl: IR Port is disabled: false
08-25 15:26:11.689  6668  6684 D UEI.SmartControl: Starting file observer...
08-25 15:26:11.690  6668  6684 I UEI.SmartControl: Registering callback...
08-25 15:26:11.690  6668  6668 D UEI.SmartControl: Internal service binding...
08-25 15:26:11.691  6668  6685 I UEI.SmartControl: ------ IControl API: 19
08-25 15:26:11.692  6668  6685 I UEI.SmartControl: Registering Services Ready callback...
08-25 15:26:11.695  6668  7139 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 15:26:11.710  6668  7138 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-25 15:26:11.715  7018  7033 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 15:26:11.716  6668  7138 D UEI.SmartControl: -----service ready thread exits
08-25 15:26:11.717  7018  7122 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 15:26:11.718  7018  7122 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 15:26:11.719  7018  7018 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 15:26:11.719  7018  7018 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 15:26:11.720  6668  6684 I UEI.SmartControl: ------ IControl API: 8
08-25 15:26:11.722  7018  7018 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 15:26:11.723  7018  7018 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 15:26:11.723  7018  7018 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 15:26:11.724  7018  7018 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 15:26:11.725  7018  7018 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 15:26:11.726  7018  7018 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-25 15:26:11.734  7018  7018 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 15:26:11.736  7018  7018 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 15:26:11.737  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 15:26:11.737  7018  7018 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 15:26:11.738  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 15:26:11.739  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 15:26:11.741  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 15:26:11.742  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 15:26:11.743  7018  7018 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472131571743]
,08-25 15:26:11.749  7018  7018 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 15:26:11.752  1027  2029 I ActivityManager: Killing 6381:com.android.gallery3d/u0a27 (adj 15): empty #17
08-25 15:26:11.792  7018  7144 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 15:26:11.796  1027  2029 I ActivityManager: Killing 6633:com.lge.email/u0a23 (adj 15): empty #18
08-25 15:26:11.828  1027  2104 W libprocessgroup: failed to open /acct/uid_10027/pid_6381/cgroup.procs: No such file or directory
,08-25 15:26:11.835  1027  1982 W libprocessgroup: failed to open /acct/uid_10023/pid_6633/cgroup.procs: No such file or directory
08-25 15:26:11.840  7018  7018 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-25 15:26:11.841  7018  7018 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 15:26:11.842  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 15:26:11.842  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 15:26:11.842  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 15:26:11.842  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 15:26:11.843  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-25 15:26:11.854  7018  7018 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-25 15:26:12.253  1027  1406 D PowerManagerServiceEx: acquireWakeLockInternal: lock=793809856, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
,08-25 15:26:12.276  1027  1406 V AlarmManager: ELAPSED_WAKEUP set : Alarm{22bffe6 type 2 when 185978 com.google.android.gms} when 185978
,08-25 15:26:12.287   305  7146 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-25 15:26:12.295  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 15:26:12.335  2657  2657 D [Concierge]Service: onStartCommand(). Type : 9
,08-25 15:26:12.364  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=793809856 [*alarm*], flags=0x0
,08-25 15:26:12.697  1027  1043 D WifiServiceImplEx: setWifiEnabled: true pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-25 15:26:12.706  1027  1043 D WifiService: setWifiEnabled: true pid=6832, uid=10118
08-25 15:26:12.706  1027  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 15:26:12.733  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 15:26:12.733  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 15:26:12.733  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 15:26:12.735  1027  1532 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 15:26:12.735  1027  1532 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 15:26:12.744  1027  1532 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 15:26:12.744  1027  1532 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 15:26:12.744  1027  1532 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 15:26:12.744  1027  1532 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 15:26:12.744  1027  1532 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 15:26:12.744  1027  1532 E WifiHW  : unknown target_country: EU , set to default
08-25 15:26:12.744  1027  1532 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 15:26:12.744  1027  1532 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 15:26:12.745  1027  1532 I WifiUtil: gEnableBmps=1
,08-25 15:26:12.779  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:12.786  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-25 15:26:12.800  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:12.806  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:12.806  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:12.810  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:12.814  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 15:26:12.820  6544  6988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 15:26:12.823  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-25 15:26:12.834  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:12.839  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:12.849  5781  5781 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 15:26:12.858  5781  5781 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 15:26:12.880  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:12.913  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:12.963  1027  2105 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7148 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 15:26:12.969  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:12.969  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 15:26:13.054  7148  7148 I AppUp4:AppBoxCP: onCreate
,08-25 15:26:13.055  7148  7148 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-25 15:26:13.066  7148  7148 I AppUp4:DB:  setFingerPrint start
08-25 15:26:13.066  7148  7148 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 15:26:13.076  7148  7148 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 15:26:13.076  7148  7148 I AppUp4:DB:  SDK version = 21
08-25 15:26:13.076  7148  7148 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-25 15:26:13.079  7148  7148 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-25 15:26:13.080  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-25 15:26:13.080  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:13.083  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 15:26:13.084  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 15:26:13.091  7148  7148 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 15:26:13.137  7148  7148 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:13.138  7148  7148 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:26:13.146  7148  7148 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d79d5b7
08-25 15:26:13.146  7148  7148 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 15:26:13.146  7148  7148 D AppUp4:CustFacade: isPhone : true
08-25 15:26:13.147  7148  7148 D AppUp4:CustModeStarterReceiver: begin check event
08-25 15:26:13.148  7148  7148 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-25 15:26:13.149  7148  7148 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 15:26:13.150  7148  7182 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 15:26:13.150  7148  7182 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 15:26:13.151  7148  7182 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 15:26:13.153  1027  1979 I ActivityManager: Killing 6406:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-25 15:26:13.320  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:13.322  1027  2022 W libprocessgroup: failed to open /acct/uid_10080/pid_6406/cgroup.procs: No such file or directory
,08-25 15:26:13.331  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 15:26:13.335  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:13.342  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 15:26:13.352  4348  7196 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 15:26:13.362  4348  7197 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:13.362  4348  7197 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 15:26:13.392  1027  2010 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7199 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 15:26:13.472  7199  7199 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:26:13.472  7199  7199 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 15:26:13.474  7199  7199 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 15:26:13.474  7199  7199 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 15:26:13.511  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:26:13.511  1027  1089 D Tethering: InitialState.processMessage what=4
,08-25 15:26:13.517   305   886 D SoftapController: Softap fwReload - Ok
08-25 15:26:13.522  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:26:13.529  1027  1532 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (771ms)
,08-25 15:26:13.540   305   886 D CommandListener: Setting iface cfg
08-25 15:26:13.540   305   886 D CommandListener: Trying to bring down wlan0
08-25 15:26:13.541   305   886 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:26:13.543  1027  1532 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-25 15:26:13.548  1027  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 15:26:13.548  1027  1532 E WifiStateMachine: useWiFiOffloading() : false
08-25 15:26:13.548  1027  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 15:26:13.542  7217  7217 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:13.542  7217  7217 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:13.551  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 15:26:13.554  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:13.555  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 15:26:13.557  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:13.558  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:13.560  1027  1532 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 15:26:13.561  1027  1532 D WifiMonitor: connecting to supplicant
08-25 15:26:13.578  7217  7217 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 15:26:13.611  7217  7217 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 15:26:13.611  7217  7217 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 15:26:13.641  7199  7199 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 15:26:13.658  7199  7199 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 15:26:13.701  7217  7217 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 15:26:13.703  7199  7199 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 15:26:13.739  7199  7199 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:13.739  7199  7199 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:26:13.760  7217  7217 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 15:26:13.764  7217  7217 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-25 15:26:13.765  7217  7217 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 15:26:13.766  1027  1532 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 15:26:13.766  1027  1532 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 15:26:13.767  1027  7230 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 15:26:13.767  1027  1532 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 15:26:13.767  1027  7230 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 15:26:13.767  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 15:26:13.767  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 15:26:13.767  1027  7230 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 15:26:13.767  1027  1532 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 15:26:13.767  1027  7230 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 15:26:13.768  1027  1532 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:13.768  1027  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:13.769  1027  1532 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 15:26:13.769  1027  1532 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 15:26:13.769  1027  1532 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 15:26:13.769  1027  1532 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 15:26:13.769  1027  1532 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 15:26:13.770  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:13.770  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:13.771  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:13.771  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:13.771  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 15:26:13.771  1027  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 15:26:13.771  1027  1532 E WifiStateMachine: useWiFiOffloading() : false
08-25 15:26:13.771  1027  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 15:26:13.775  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:13.777  1958  1958 D WfdService: Waiting for WifiP2p enabling
08-25 15:26:13.778  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 15:26:13.778  1027  1536 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 15:26:13.778  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:13.778  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:13.778  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:13.778  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:13.778  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:13.778  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:13.778  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:13.778  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:13.778  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:13.778  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:13.778  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:13.779  1027  1532 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 15:26:13.779  1027  1532 D WifiNative-wlan0: SET update_config 1: returned true
08-25 15:26:13.780  1027  1532 D WifiConfigStore: Loading config and enabling all networks 
08-25 15:26:13.780  1027  1532 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 15:26:13.780  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:13.780  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:13.780  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:13.780  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:13.780  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:13.780  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:13.780  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:13.780  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:13.780  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:13.781  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:13.781  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:13.788  1027  1532 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-25 15:26:13.794  1027  1532 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 15:26:13.803  1027  1532 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-25 15:26:13.804  1027  1532 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 15:26:13.805  1027  1532 D WifiStateMachine: enableVerboseLogging : level 2
08-25 15:26:13.805  1027  1532 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 15:26:13.806  1027  1532 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 15:26:13.806  1027  1532 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 15:26:13.806  1027  1532 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 15:26:13.806  1027  1532 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 15:26:13.807  1027  1532 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 15:26:13.807  1027  1532 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 15:26:13.807  1027  1532 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 15:26:13.807  1027  1532 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 15:26:13.808  1027  1532 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 15:26:13.808  1027  1532 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 15:26:13.808  1027  1532 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 15:26:13.808  1027  1532 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 15:26:13.809  1027  1532 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 15:26:13.810  1027  1532 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 15:26:13.810  1027  1532 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 15:26:13.810  1027  1532 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 15:26:13.810  1027  1532 D WifiNative-HAL: Setting external_sim to 1
08-25 15:26:13.810  1958  1958 D WfdsService: Supplicant Connection state is changed : true
08-25 15:26:13.810  1027  1532 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 15:26:13.810  1958  2313 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 15:26:13.810  1958  2313 D WfdsService: Set the WFDS Monitor: true
08-25 15:26:13.810  1958  2313 D WfdsMonitor: WfdsMonitorThread create
08-25 15:26:13.811  1958  2313 D WfdsMonitor: WFDS Monitor is created and started
08-25 15:26:13.811  1958  2313 D WfdsService: WiFi: Supplicant connection re-established
08-25 15:26:13.811  1027  1532 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 15:26:13.811  1027  1532 I WifiNative-HAL: startHal
08-25 15:26:13.811  1027  1532 D wifi    : setting scan oui 0xaf6d1e80
08-25 15:26:13.811  1027  1532 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 15:26:13.811  1027  1532 I WifiNative-HAL: startHal
08-25 15:26:13.811  1027  1532 D wifi    : setting scan oui 0xaf6d1e80
08-25 15:26:13.811  1027  1532 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 15:26:13.812  1027  1532 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 15:26:13.812  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 15:26:13.812  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 15:26:13.812  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 15:26:13.812  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 15:26:13.813  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 15:26:13.813  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 15:26:13.813  1958  7234 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 15:26:13.813  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 15:26:13.813  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 15:26:13.813  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 15:26:13.813  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-S,TART
08-25 15:26:13.813  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 15:26:13.814  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 15:26:13.814  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 15:26:13.814  1958  7234 E CtrlSupplicant: Succeed to open control connection
08-25 15:26:13.814  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 15:26:13.814  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 15:26:13.814  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 15:26:13.814  7217  7217 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 15:26:13.814  1958  7234 E CtrlSupplicant: Succeed to open monitor connection
08-25 15:26:13.814  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 15:26:13.814  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 15:26:13.815  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 15:26:13.815  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 15:26:13.815  1958  7234 D WfdsMonitor: Supplicant connection established
08-25 15:26:13.816  1027  1532 E WifiNative: : [187,544,166 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 15:26:13.816  1027  1532 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 15:26:13.816  1958  2313 D WfdsService: Connected to the supplicant for wfds
08-25 15:26:13.816  1027  1532 D WifiNative-wlan0: RECONNECT: returned true
08-25 15:26:13.816  1027  1532 D WifiNative-wlan0: doString: [STATUS]
08-25 15:26:13.818  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 15:26:13.818  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 15:26:13.819  1027  1532 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 15:26:13.819  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 1
,08-25 15:26:13.820  1027  1532 D WifiNative-wlan0: SET ps 1: returned true
08-25 15:26:13.820  1027  1530 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:26:13.824  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 15:26:13.824  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-25 15:26:13.824  1027  1549 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.824  1027  1549 I WifiNative-HAL: startHal
08-25 15:26:13.824  1027  1549 D wifi    : getting scan capabilities on interface[1] = 0xaf6d1e80
08-25 15:26:13.824  1027  1549 D wifi    : failed to get capabilities : -3
08-25 15:26:13.824  1027  1549 E WifiScanningService: could not get scan capabilities
08-25 15:26:13.824  1027  1532 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 15:26:13.824  1027  1550 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.824  1027  1532 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 15:26:13.826  1027  1532 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 15:26:13.826  1027  1532 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 15:26:13.826   305   886 D CommandListener: Setting iface cfg
08-25 15:26:13.826   305   886 D CommandListener: Trying to bring up p2p0
08-25 15:26:13.826  1027  1532 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 15:26:13.827  1027  1532 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 15:26:13.827  1027  1530 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 15:26:13.827  1027  1530 D LGWifiP2pService: P2pEnablingState
08-25 15:26:13.827  1027  1530 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.827  1027  1532 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 15:26:13.827  1027  1530 D LGWifiP2pService: P2p socket connection successful
08-25 15:26:13.827  1027  1532 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-25 15:26:13.827  7217  7217 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 15:26:13.828  1027  1530 D LGWifiP2pService: P2pEnabledState
08-25 15:26:13.828  1027  1532 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 15:26:13.829  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 15:26:13.829  1958  1958 D WfdsService: WifiP2pState is changed : true
08-25 15:26:13.829  1958  2313 D WfdsService: Receive the WFDS_ENABLE Method
08-25 15:26:13.829  1958  2313 D WfdsService: Set the WFDS Monitor: true
08-25 15:26:13.829  1958  2313 D WfdsService: Connected to the supplicant for wfds
08-25 15:26:13.829  1958  2313 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 15:26:13.830  7217  7217 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 15:26:13.830  1958  2313 D WfdsService: selectPreferredScanChannel [36]
08-25 15:26:13.830  1958  2313 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 15:26:13.830  1027  1530 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 15:26:13.830  1027  1532 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 15:26:13.831  1027  1532 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 15:26:13.831  1027  1532 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 15:26:13.831  7217  7217 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 15:26:13.831  1027  1530 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 15:26:13.831  1027  1530 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 15:26:13.832  1027  1530 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 15:26:13.832  1027  1530 D WifiNative-p2p0: SET device_name G3: returned true
08-25 15:26:13.832  1027  1530 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 15:26:13.832  1027  1530 D LGWifiP2pService: before postfix = G3
08-25 15:26:13.832  1027  1530 D WifiServerServiceExt: postfix byte check : 2
08-25 15:26:13.832  1027  1530 D LGWifiP2pService: after postfix = G3
08-25 15:26:13.832  1027  1530 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 15:26:13.832  1027  1530 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 15:26:13.833  1027  1530 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 15:26:13.833  1958  1958 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,08-25 15:26:13.834  1958  1958 D WfdsService: isConnected: false
08-25 15:26:13.834  1027  1530 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 15:26:13.834  1027  1530 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 15:26:13.834  1027  1532 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 15:26:13.835  1027  1532 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 15:26:13.835  1027  1532 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 15:26:13.835  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 15:26:13.835  1027  1530 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 15:26:13.835  1027  1530 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 15:26:13.836  1027  1530 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 15:26:13.836  1027  1530 D WifiNative-HAL: p2pGetDeviceAddress
08-25 15:26:13.836  1027  1530 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 15:26:13.836  1027  1530 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 15:26:13.836  1027  1530 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 15:26:13.837  1027  1530 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 15:26:13.837  1027  1530 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 15:26:13.837  1958  1958 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 15:26:13.837  1958  1958 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 15:26:13.838  1958  1958 D WfdsService: Update P2p Interface State: 3
08-25 15:26:13.839  1027  1530 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 15:26:13.839  1027  1530 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 15:26:13.839  1027  1530 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 15:26:13.839  1027  1530 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 15:26:13.860  1027  1530 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 15:26:13.860  1027  1530 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 15:26:13.860  1027  1530 D LGWifiP2pService: InactiveState
08-25 15:26:13.860  1027  1530 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.860  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.860  1027  1530 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-25 15:26:13.862  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 15:26:13.862  7217  7217 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:13.862  1027  7230 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 15:26:13.863  1027  7230 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:13.863  1027  7230 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:13.863  1027  7230 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:13.863  1958  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 15:26:13.863  7217  7217 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 15:26:13.863  7217  7217 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.864  7217  7217 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.864  1958  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:13.864  1958  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:13.864  1027  7230 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:13.864  1027  7230 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.864  1027  7230 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.864  1027  7230 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.864  1027  7230 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:13.864  1027  7230 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.865  1027  7230 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.865  1027  7230 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.865  1027  1530 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 15:26:13.865  1027  1530 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.865  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.865  1027  1530 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.865  1027  1530 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.865  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.865  1027  1530 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.866  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 15:26:13.866  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 15:26:13.866  1958  2313 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 15:26:13.866  1027  1530 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.866  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.866  1027  1530 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 1,5:26:13.866  7217  7217 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:13.867  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 15:26:13.867  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:13.867  1027  7230 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:13.867  1027  7230 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:13.867  1027  1530 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.867  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.867  1027  1530 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.867  1027  1027 E WifiServerServiceExt: No p2p device connected
08-25 15:26:13.867  7217  7217 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 15:26:13.867  7217  7217 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.868  1958  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:13.868  1027  7230 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:13.868  1027  7230 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.868  1027  7230 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.868  1027  7230 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.868  7217  7217 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.868  1958  7234 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:13.869  1027  7230 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:13.869  1027  7230 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.869  1027  7230 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:13.869  1027  7230 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 15:26:13.869  1027  1532 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 15:26:13.869  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.869  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:13.870  1027  1532 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 15:26:13.871  1027  1532 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 15:26:13.871  1027  1532 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 15:26:13.872  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-25 15:26:13.872  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 15:26:13.872  7217  7217 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 15:26:13.872  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 15:26:13.872  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 15:26:13.872  1027  7230 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 15:26:13.872  1027  7230 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-25 15:26:13.873  1027  1532 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 15:26:13.873  1027  1532 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 15:26:13.873  1027  1532 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 15:26:13.873  1027  1532 D WifiNative-wlan0: doBoolean: SCAN
08-25 15:26:13.873  1027  1532 D WifiNative-wlan0: SCAN: returned false
,08-25 15:26:13.877  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=187605  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 15:26:13.879  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=187608  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 15:26:13.879  1027  1532 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:13.880  1027  1532 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:13.880  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:13.880  1027  1532 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:13.880  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:13.880  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 15:26:13.881  1027  1532 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:13.881  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:13.881  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:13.882  1027  1532 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:13.882  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:13.882  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 15:26:13.882  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:13.896  3276  3276 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 15:26:13.896  3276  3276 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:13.897  3276  3276 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-25 15:26:13.905  7199  7199 I HubEmail: JNI_OnLoad()
08-25 15:26:13.905  7199  7199 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 15:26:13.905  7199  7199 I HubEmail: registerNatives()
08-25 15:26:13.905  7199  7199 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-25 15:26:13.905  7199  7199 I HubEmail: registerNativeMethods()
08-25 15:26:13.905  7199  7199 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 15:26:13.905  7199  7199 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-25 15:26:13.947  1027  2010 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7240 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-25 15:26:13.958  7199  7239 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:26:13.958  7062  7237 W FormManager: Network not available. Please check & try again.
08-25 15:26:13.965  7062  7238 V FormManager: Network unavailable.
,08-25 15:26:13.969  7062  7238 V FormManager: Network unavailable.
,08-25 15:26:13.974  1027  2029 I ActivityManager: Killing 6687:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-25 15:26:14.018  1027  2010 W libprocessgroup: failed to open /acct/uid_10061/pid_6687/cgroup.procs: No such file or directory
,08-25 15:26:14.101  7240  7240 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:14.101  7240  7240 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:26:14.104  7240  7240 D PhoneMonitor: Register our PhoneStateListener
08-25 15:26:14.132  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 15:26:14.135  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 15:26:14.156  7240  7240 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-25 15:26:14.157  7240  7240 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 15:26:14.158  7240  7240 D TelephonyAutoProfiling: [parse] Load xml
,08-25 15:26:14.166  7240  7240 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-25 15:26:14.166  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
,08-25 15:26:14.166  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-25 15:26:14.166  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 15:26:14.166  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 15:26:14.166  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 15:26:14.167  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 15:26:14.167  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 15:26:14.167  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 15:26:14.167  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 15:26:14.167  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 15:26:14.168  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 15:26:14.168  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 15:26:14.168  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 15:26:14.168  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 15:26:14.168  7240  7240 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 15:26:14.168  7240  7240 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-25 15:26:14.176  7240  7240 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-25 15:26:14.192  1027  1982 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7260 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:26:14.193  1027  1982 I ActivityManager: Killing 6429:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-25 15:26:14.215   333   333 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.952ms
,08-25 15:26:14.240   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 630us total 24.785ms
,08-25 15:26:14.265   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 23.137ms
,08-25 15:26:14.268  1027  2029 W libprocessgroup: failed to open /acct/uid_10097/pid_6429/cgroup.procs: No such file or directory
08-25 15:26:14.363  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 15:26:14.363  1027  7230 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 15:26:14.363  7217  7217 E wpa_supplicant: USIM:  scard_init function
08-25 15:26:14.363  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-25 15:26:14.363  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-25 15:26:14.363  1027  7230 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 15:26:14.364  7217  7217 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 15:26:14.365  1027  1532 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 15:26:14.366  1027  1532 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 15:26:14.367  1027  1532 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 15:26:14.368  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 15:26:14.368  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 15:26:14.369  1027  1532 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-25 15:26:14.369  1027  1532 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 15:26:14.383  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=188111  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 15:26:14.386  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.386  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:14.387  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.387  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.387  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 15:26:14.389  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.389  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.389  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 15:26:14.389  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.391  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=188119  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 15:26:14.392  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:14.392  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 15:26:14.392  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.392  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:14.394  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:14.453  1027  1957 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7278 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-25 15:26:14.454  1027  1957 I ActivityManager: Killing 6729:com.lge.eula/1000 (adj 15): empty #17
08-25 15:26:14.479  7217  7217 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 15:26:14.481  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 15:26:14.481  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 15:26:14.481  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 15:26:14.481  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 15:26:14.482  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:14.482  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:14.482  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=188211  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 15:26:14.482  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=188211  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 15:26:14.483  1027  1532 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188211
,08-25 15:26:14.483  1027  1532 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188212
08-25 15:26:14.483  1027  1532 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188212
,08-25 15:26:14.484  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188212
08-25 15:26:14.484  1027  1532 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=188213
08-25 15:26:14.484  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=188213  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 15:26:14.495  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:14.496  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:14.496  7217  7217 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 15:26:14.496  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 15:26:14.496  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 15:26:14.496  1027  7230 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 15:26:14.496  7217  7217 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 15:26:14.497  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 15:26:14.497  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 15:26:14.497  1027  7230 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-25 15:26:14.499  1027  2023 W libprocessgroup: failed to open /acct/uid_1000/pid_6729/cgroup.procs: No such file or directory
08-25 15:26:14.501  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:14.501  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:14.502  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 15:26:14.504  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.504  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.504  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 15:26:14.506  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.506  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:14.511  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.511  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.511  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-25 15:26:14.514  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.518  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=188247  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 15:26:14.520  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.520  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:14.520  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=188249  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 15:26:14.522  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=188250  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 15:26:14.522  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.523  1027  1532 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=188251
08-25 15:26:14.523  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:14.523  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 15:26:14.524  1027  1532 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=188252
08-25 15:26:14.525  1027  1532 D WifiNative-wlan0: doString: [STATUS]
08-25 15:26:14.526  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:14.526  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:14.526  1027  1532 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 15:26:14.529  1027  1532 I WifiServiceExtension: setVHTCapabilityType  : false
,08-25 15:26:14.534  1027  1532 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 15:26:14.534  1027  1532 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-25 15:26:14.536  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.536  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:14.538  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.538  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.538  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.538  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 15:26:14.540  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.540  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:14.541  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.541  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.541  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 15:26:14.541  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:14.544  1027  1532 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 15:26:14.544  1027  1538 D ConnectivityService: Got NetworkAgent Messenger
08-25 15:26:14.544  1027  1532 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:26:14.544  1027  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 15:26:14.544  1027  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 15:26:14.544  1027  1538 D ConnectivityService: NetworkAgent connected
08-25 15:26:14.544  1027  1532 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 15:26:14.544  1027  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 15:26:14.555  1027  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 15:26:14.556  1027  1532 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:26:14.556  1027  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 15:26:14.556  1027  1532 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 15:26:14.556  1027  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-25 15:26:14.565  1027  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 15:26:14.566   305   886 D CommandListener: Setting iface cfg
08-25 15:26:14.594  1027  1979 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7297 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 15:26:14.595  1027  1979 I ActivityManager: Killing 6748:com.lge.bnr/1000 (adj 15): empty #17
,08-25 15:26:14.669  1027  1982 W libprocessgroup: failed to open /acct/uid_1000/pid_6748/cgroup.procs: No such file or directory
,08-25 15:26:14.679  1027  1532 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 15:26:14.679  1027  7296 D DhcpStateMachine: StoppedState
08-25 15:26:14.680  1027  7296 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.680  1027  7296 D DhcpStateMachine: WaitBeforeStartState
08-25 15:26:14.680  1027  1532 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=188408  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:14.681  1027  1532 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=188409  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:14.681  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=188410  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:14.682  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:14.682  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:14.683  1027  1532 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:14.683  1027  1532 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:14.685  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-25 15:26:14.685  1027  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-25 15:26:14.686  1027  1532 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=188415  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:14.687  1027  1532 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=188416  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-25 15:26:14.688  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=188416  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:14.690  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:142389] from screen [on:0 period:-1042207839] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 15:26:14.691  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1042207837] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 15:26:14.691  1027  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 15:26:14.696  1027  1538 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-25 15:26:14.697  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 15:26:14.698  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.699  1027  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.700  1027  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.700  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.701  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.702  1027  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 15:26:14.702  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=201,0,0
,08-25 15:26:14.702  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=201,0,0
08-25 15:26:14.703  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 15:26:14.703  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 15:26:14.704  1027  1532 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 15:26:14.704  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 15:26:14.705  1027  1532 D WifiNative-wlan0: SET ps 0: returned true
08-25 15:26:14.705  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 15:26:14.706  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 15:26:14.707  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 15:26:14.707  1027  1532 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 15:26:14.707  1027  1532 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 15:26:14.707  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b300894 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.707  1027  1532 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 15:26:14.707  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2b300894 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.708  1027  7296 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.708  1027  7296 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 15:26:14.709   305   886 D CommandListener: Setting iface cfg
08-25 15:26:14.710   305   886 D CommandListener: Trying to bring up wlan0
08-25 15:26:14.712  1027  1532 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 15:26:14.713  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.713  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.714  1027  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 15:26:14.715  1027  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.715  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.716  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:14.716  1027  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 15:26:14.717  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 15:26:14.717  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 15:26:14.717  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 15:26:14.717  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.717  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.717  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 15:26:14.718  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 15:26:14.718  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 15:26:14.718  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 15:26:14.719  1027  1532 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 15:26:14.719  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 15:26:14.729  7297  7297 I art     : Almond Protected OAT
,08-25 15:26:14.734  1027  1532 D WifiNative-wlan0: SET ps 1: returned true
08-25 15:26:14.735  1027  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 15:26:14.736  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-25 15:26:14.736  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 15:26:14.736  1027  1532 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 15:26:14.736  1027  1538 D ConnectivityService: ignoring duplicate network state non-change
08-25 15:26:14.737  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:14.737  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 15:26:14.738  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.739  1027  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 15:26:14.739  1027  1538 D ConnectivityService: Adding iface wlan0 to network 101
08-25 15:26:14.740  1027  1532 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 15:26:14.744  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.744  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:14.745  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:14.748  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.748  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.749  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 15:26:14.756  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.756  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.756  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 15:26:14.758  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-25 15:26:14.761  1958  1958 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 15:26:14.763  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.763  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.763  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 15:26:14.765  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 15:26:14.766  1027  1538 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 15:26:14.767  1027  1538 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 15:26:14.768  1027  1538 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 15:26:14.768   305   886 E Netd    : netlink response contains error (File exists)
08-25 15:26:14.768  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.768  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:14.769  1027  1538 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 15:26:14.769  1027  1538 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 15:26:14.769  1027  1538 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-25 15:26:14.770  1027  1538 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-25 15:26:14.770  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.770  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.770  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:14.770  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-25 15:26:14.771  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.771  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 15:26:14.771  1027  1538 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 15:26:14.771  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.771  1027  1538 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 15:26:14.771  1027  1538 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 15:26:14.772  1027  1538 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 15:26:14.772  1027  1538 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:14.772  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.772  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 15:26:14.772  1027  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:14.772  1027  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 15:26:14.772  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.772  1027  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:14.772  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 15:26:14.772  1027  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 15:26:14.772  1027  1538 D ConnectivityService: currentScore = 0, newScore = 20
08-25 15:26:14.772  1027  1538 D ConnectivityService:    accepting network in place of null
08-25 15:26:14.772  1027  1538 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:14.773  1027  1532 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:14.773  1027  1532 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:14.774   305  7317 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 15:26:14.774  1027  1538 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 15:26:14.774  1027  1538 D CSLegacyTypeTracker: Sending connected broad,cast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 15:26:14.774  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 15:26:14.774  1027  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:14.774  1027  1538 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 15:26:14.774  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:14.775  1871  1871 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:14.775  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 15:26:14.775  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 15:26:14.775  1027  1538 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 15:26:14.775  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.779  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 15:26:14.779  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 15:26:14.779  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 15:26:14.779  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 15:26:14.780  1027  1538 D ConnectivityService: validation of new default Network = false
08-25 15:26:14.780  1027  1538 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 15:26:14.780  1027  1538 D DSQN    : enableDataServiceNotify 
08-25 15:26:14.780  1027  1538 D DSQN    : start dsqn bin
,08-25 15:26:14.793  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.793  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:26:14.793  1027  1530 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:14.796  7297  7297 D WeatherApplication: removeAccount
08-25 15:26:14.798  7297  7297 D WeatherApplication: Account.length = 0
08-25 15:26:14.798  7297  7297 E WeatherApplication: OPERATOR:OPEN
08-25 15:26:14.804  1027  1532 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 15:26:14.804  1027  1529 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 15:26:14.804  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 15:26:14.804  1027  1532 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 15:26:14.805  1027  1532 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 15:26:14.805  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 15:26:14.805  1027  1532 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-25 15:26:14.810  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:14
08-25 15:26:14.817  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 15:26:14.817  1835  7318 I CheckinService: active receiver: enabled
08-25 15:26:14.817  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
08-25 15:26:14.818  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 15:26:14.819  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:14.820  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:14.850  1027  1538 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,08-25 15:26:14.851  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:14.851  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:14.851  1027  1538 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:14.852  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 15:26:14.842  7319  7319 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:14.842  7319  7319 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:14.853  1835  7318 I CheckinService: Preparing to send checkin request
08-25 15:26:14.853  1835  7318 I EventLogService: Accumulating logs since 1472131463849
08-25 15:26:14.857  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 15:26:14.859  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 15:26:14.860  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-25 15:26:14.864  7319  7319 E DSQN    : DSQN ssw
08-25 15:26:14.868  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 15:26:14.868  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 15:26:14.868  7297  7297 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-25 15:26:14.883  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 15:26:14.883  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:14
08-25 15:26:14.911  1027  7296 D DhcpStateMachine: DHCPV4 request on wlan0
,08-25 15:26:14.913  1027  7296 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 15:26:14.913  1027  7296 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 15:26:14.912  7325  7325 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:14.912  7325  7325 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:14.925  7325  7325 I dhcpcd  : version 5.5.6 starting
,08-25 15:26:14.927  7325  7325 E dhcpcd  : get_duid: m
08-25 15:26:14.927  7325  7325 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 15:26:14.927  7325  7325 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 15:26:14.938  1027  2105 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7326 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 15:26:14.939  1027  2105 I ActivityManager: Killing 2166:com.lge.music/u0a34 (adj 15): empty #17
,08-25 15:26:14.957   311   311 V AudioFlinger: 2166 died, releasing its sessions
08-25 15:26:14.957   311   311 V AudioFlinger:  pid 1871 @ 0
08-25 15:26:14.957   311   311 V AudioFlinger:  pid 3276 @ 1
08-25 15:26:14.957   311   311 V AudioFlinger:  pid 3276 @ 2
,08-25 15:26:14.958   305  7317 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 15:26:15.003   305  7317 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 15:26:15.006  7325  7325 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 15:26:15.006  7325  7325 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 15:26:15.006  7325  7325 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 15:26:15.006  7325  7325 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 15:26:15.007  7325  7325 D dhcpcd  : wlan0: sending REQUEST (xid 0x51c10caa), next in 4.64 seconds
08-25 15:26:15.008  1835  7318 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-25 15:26:15.008  1027  2029 W libprocessgroup: failed to open /acct/uid_10034/pid_2166/cgroup.procs: No such file or directory
,08-25 15:26:15.031  7325  7325 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-25 15:26:15.035   305   885 D LGDataListener: argv[0]=dsqncommand
08-25 15:26:15.035   305   885 D LGDataListener: argv[1]=wlan0
08-25 15:26:15.035   305   885 D LGDataListener: argv[2]=1
08-25 15:26:15.035   305   885 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 15:26:15.035  1027  1087 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 15:26:15.035  1027  1087 D DSQN    : start to monitor internet connection
,08-25 15:26:15.060  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 13:26:15 GMT], X-Android-Received-Millis=[1472131575059], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472131575034]}
08-25 15:26:15.060  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 15:26:15.060  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 15:26:15.060  1027  1538 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 15:26:15.061  1027  1538 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 15:26:15.061  1027  1538 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:15.061  1027  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:15.061  1027  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 15:26:15.061  1027  1538 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 15:26:15.061  1027  1538 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 15:26:15.061  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.061  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:15.062  1027  1538 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:15.062  1027  1538 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.062  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 15:26:15.062  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 15:26:15.063  1027  1532 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.063  1027  1532 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:15.063  1871  1871 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.064  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-25 15:26:15.068  7325  7325 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 15:26:15.068  7325  7325 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 15:26:15.068  7325  7325 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 15:26:15.068  7325  7325 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 15:26:15.068  7325  7325 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 15:26:15.068  7325  7325 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 15:26:15.068  7325  7325 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 15:26:15.068  7325  7325 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 15:26:15.087   278   467 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 15:26:15.087   278   467 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 15:26:15.087   278   467 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 15:26:15.098  7326  7353 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 15:26:15.100   278   467 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 15:26:15.100   278   467 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 15:26:15.100   278   467 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 15:26:15.102  7326  7353 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 15:26:15.106   278   467 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 15:26:15.106   278   467 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 15:26:15.106   278   467 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 15:26:15.106  7326  7359 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 15:26:15.110   278   467 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 15:26:15.110   278   467 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 15:26:15.110   278   467 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 15:26:15.111  7326  7359 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-25 15:26:15.115  1027  1982 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7361 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-25 15:26:15.128  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-25 15:26:15.129  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:15.129  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:15.167  7361  7361 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-25 15:26:15.167  7361  7361 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 15:26:15.194  7361  7361 I MultiDex: VM with version 2.1.0 has multidex support
08-25 15:26:15.194  7361  7361 I MultiDex: install
08-25 15:26:15.194  7361  7361 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 15:26:15.203  7361  7361 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-25 15:26:15.284  1027  1757 I art     : Explicit concurrent mark sweep GC freed 104950(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.255ms total 103.625ms
,08-25 15:26:15.318  1027  7296 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 15:26:15.319  1027  7296 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 15:26:15.319  1027  7296 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 15:26:15.320  1027  7296 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 15:26:15.320  1027  7296 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 15:26:15.320  1027  7296 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 15:26:15.320  1027  7296 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 15:26:15.320  1027  7296 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 15:26:15.320  1027  7296 D DhcpStateMachine: RunningState
,08-25 15:26:15.394  7326  7326 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 15:26:15.407  7326  7326 I LibraryLoader: Loading: webviewchromium
,08-25 15:26:15.411  7326  7326 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9148-9153)
08-25 15:26:15.411  7326  7326 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 15:26:15.417  7326  7326 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eb08d3e}
08-25 15:26:15.419  7326  7326 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 15:26:15.419  7326  7326 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 15:26:15.432  7326  7326 I BrowserStartupController: Initializing chromium process, renderers=0
,08-25 15:26:15.433  7326  7326 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 15:26:15.448  7326  7326 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-25 15:26:15.449  7326  7326 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-25 15:26:15.449  7326  7326 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-25 15:26:15.461   311  1376 V AudioPolicyService: registerClient() client 0xb0410540, uid 10093
,08-25 15:26:15.466  7326  7417 W AudioManagerAndroid: Requires BLUETOOTH permission
08-25 15:26:15.489  7326  7326 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 15:26:15.489  7326  7326 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 15:26:15.489  7326  7326 I Adreno-EGL: Build Date: 12/12/14 금
08-25 15:26:15.489  7326  7326 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 15:26:15.489  7326  7326 I Adreno-EGL: Remote Branch: 
08-25 15:26:15.489  7326  7326 I Adreno-EGL: Local Patches: 
08-25 15:26:15.489  7326  7326 I Adreno-EGL: Reconstruct Branch: 
,08-25 15:26:15.575  7326  7326 I NSApplication: Starting up...
,08-25 15:26:15.656  1027  1757 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7430 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-25 15:26:15.658  1027  1044 I ActivityManager: Killing 5990:com.android.vending/u0a44 (adj 15): empty #17
08-25 15:26:15.698  1027  1532 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 15:26:15.699  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 15:26:15.699  1027  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:15.700  1027  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:15.700  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:15.701  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:15.701  1027  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-25 15:26:15.701  1027  1538 D ConnectivityService: identical MTU - not setting
08-25 15:26:15.702  1027  1538 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 15:26:15.702  1027  1538 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 15:26:15.702  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.702  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:15.702  1027  1538 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:15.703  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 15:26:15.740  1027  2010 W libprocessgroup: failed to open /acct/uid_10044/pid_5990/cgroup.procs: No such file or directory
,08-25 15:26:15.754  1027  1771 D WifiServiceImplEx: setWifiEnabled: false pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 15:26:15.755  1027  1771 D WifiService: setWifiEnabled: false pid=6832, uid=10118
08-25 15:26:15.755  1027  1771 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 15:26:15.769  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 15:26:15.770  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 15:26:15.770  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 15:26:15.770  1027  1532 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 15:26:15.771  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-25 15:26:15.771  1027  1532 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-25 15:26:15.772  1027  1532 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 15:26:15.772  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 15:26:15.772  1027  1532 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 15:26:15.772  1027  1532 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:26:15.772  1027  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 15:26:15.773  1027  1532 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 15:26:15.773  1027  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 15:26:15.782  1027  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 15:26:15.782  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 15:26:15.782  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.782  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.782  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 15:26:15.782  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 15:26:15.782  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 15:26:15.783  1027  1532 D WifiNative-wlan0: SET ps 1: returned true
08-25 15:26:15.783  1027  7296 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.783   305   886 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:26:15.788  7430  7430 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 15:26:15.819  1027  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 15:26:15.820  1027  1538 D ConnectivityService: ignoring duplicate network state non-change
08-25 15:26:15.820  1027  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-25 15:26:15.821  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 15:26:15.824  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:15.824  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:15.824  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 15:26:15.825  1027  1532 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:15.825  1958  1958 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-25 15:26:15.825  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:15.826  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:15.826  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:15.826  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:15.827  1027  1530 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.827  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.827  1027  1530 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f0bb52d
08-25 15:26:15.828  1027  1530 D LGWifiP2pService: P2pDisablingState
08-25 15:26:15.828  1027  1530 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.828  1027  1530 D LGWifiP2pService: p2p socket connection lost
08-25 15:26:15.828  1027  1530 D LGWifiP2pService: P2pDisabledState
08-25 15:26:15.828  1027  1532 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:15.829  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:15.829  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:15.829  1027  1532 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 15:26:15.830  1027  1532 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 15:26:15.830  1027  1530 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.830  1027  1530 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.830  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 15:26:15.830  7217  7217 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 15:26:15.831  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:15.834  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 15:26:15.834  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 15:26:15.835  1027  1532 D WifiNative-wlan0: SET ps 1: returned true
,08-25 15:26:15.843  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 15:26:15.844  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:15.844  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:15.845  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 15:26:15.845  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 15:26:15.845  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-25 15:26:15.845  1027  1549 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.845  1027  1550 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:26:15.845  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 15:26:15.845  1958  1958 D WfdsService: WifiP2pState is changed : false
08-25 15:26:15.846  1958  2313 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 15:26:15.846  1958  2313 D WfdsService: Set the WFDS Monitor: false
08-25 15:26:15.846  1958  2313 D WfdsMonitor: WFDS Monitor is stopped
08-25 15:26:15.846  1958  2313 D WfdsService: STATE : WfdsDisabledState - enter
08-25 15:26:15.846  1958  7234 D CtrlSupplicant: Received on exit socket, terminate
08-25 15:26:15.846  1958  2314 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 15:26:15.847  1958  7234 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 15:26:15.847  1958  7234 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 15:26:15.847  1958  7234 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 15:26:15.847  1958  2313 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 15:26:15.852  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:15.852  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:15.853  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:15.874   305   886 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:26:15.874  1027  1538 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 15:26:15.874  1027  1538 D DSQN    : disableDataServiceNotify
08-25 15:26:15.874  1027  1538 D DSQN    : stop dsqn bin
,08-25 15:26:15.875  1027  1532 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 15:26:15.876  1027  1532 D WifiNative-p2p0: TERMINATE: returned true
08-25 15:26:15.876  1027  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 15:26:15.876  1027  1532 E WifiStateMachine: useWiFiOffloading() : false
08-25 15:26:15.876  1027  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 15:26:15.876  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 15:26:15.876  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:15.876  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-25 15:26:15.877  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:15.878  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:26:15.878  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:15.878  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 15:26:15.880  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 15:26:15.880  7361  7379 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:15.880  7361  7379 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 15:26:15.882  1027  1538 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 15:26:15.882  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.882  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:15.882  1027  1538 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:15.882  1027  1538 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 15:26:15.882  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 15:26:15.883  1027  1538 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 15:26:15.883  1027  1538 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 15:26:15.883  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:15.883  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 15:26:15.883  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:15.883  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:15.883  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:15.883  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:15.883  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:15.883  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:15.883  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:15.883  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:15.883  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:15.883  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:26:15.883  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.883  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.883  1027  7295 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 15:26:15.884  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 15:26:15.884  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:15.885  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 15:26:15.885  1027  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:15.885  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 15:26:15.886  1027  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:15.886  1027  1538 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.886  1027  1538 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.886  1027  1538 D NetworkManagementService: Removing idletimer
08-25 15:26:15.886  1027  1538 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:15.887  1027  1532 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.887  1027  1532 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:15.887  1027  1538 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-25 15:26:15.887  1871  1871 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:15.887  1027  1529 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 15:26:15.887  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 15:26:15.888  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 15:26:15.888  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 15:26:15.888  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 15:26:15.888  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 15:26:15.888  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:15.888  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:15.888  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:15.888  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:15.888  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: fal,se
08-25 15:26:15.888  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:15.888  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:15.888  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:15.888  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:15.888  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:15.888  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:15.890  1027  1529 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 15:26:15.890  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 15:26:15.890  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 15:26:15.890  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 15:26:15.890  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-25 15:26:15.897  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:15.914  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 15:26:15.915  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:15.916  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:15.932  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 15:26:15.933  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:15.933  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:15.939  7454  7454 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-25 15:26:15.975  7217  7217 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 15:26:15.975  7217  7217 I wpa_supplicant: monitor socket send errors count : 1
08-25 15:26:15.975  7217  7217 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1958-4\x00 that cannot receive messages
08-25 15:26:15.977  1027  7230 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 15:26:15.977  1027  7230 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-25 15:26:15.986  7454  7454 I dex2oat : dex2oat took 47.275ms (threads: 4)
08-25 15:26:15.990  1027  7296 D DhcpStateMachine: StoppedState
08-25 15:26:15.990  1027  7296 D DhcpStateMachine: StoppedState{ when=-155ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:15.990  1027  1532 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 15:26:15.990  1027  1532 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-25 15:26:15.998  7217  7217 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 15:26:15.999  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 15:26:15.999  7217  7217 W wpa_supplicant: USIM:  scard_deinit function
08-25 15:26:15.999  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 15:26:15.999  1027  7230 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 15:26:16.000  1027  7230 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 15:26:16.000  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:16.000  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:16.000  1027  1532 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189729
08-25 15:26:16.000  1027  1532 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=189729
08-25 15:26:16.000  1027  1532 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=189729  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 15:26:16.001  1027  1532 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=189729  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 15:26:16.001  1027  1089 D Tethering: InitialState.processMessage what=4
08-25 15:26:16.002  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:26:16.003  7361  7379 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 15:26:16.003  7361  7379 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 15:26:16.003  7361  7379 I Adreno-EGL: Build Date: 12/12/14 금
08-25 15:26:16.003  7361  7379 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 15:26:16.003  7361  7379 I Adreno-EGL: Remote Branch: 
08-25 15:26:16.003  7361  7379 I Adreno-EGL: Local Patches: 
08-25 15:26:16.003  7361  7379 I Adreno-EGL: Reconstruct Branch: 
,08-25 15:26:16.004  1027  1532 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:16.005  1027  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-25 15:26:16.064  2237  2265 I art     : Explicit concurrent mark sweep GC freed 8376(499KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 688us total 30.582ms
,08-25 15:26:16.072  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 15:26:16.075  6544  6988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 15:26:16.087  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:16.095  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 15:26:16.096  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:16.096  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 15:26:16.096  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 15:26:16.097  7148  7148 I AppUp4:CustModeStarterReceiver: onReceive
,08-25 15:26:16.101  7148  7148 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d79d5b7
08-25 15:26:16.101  7148  7148 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 15:26:16.101  7148  7148 D AppUp4:CustFacade: isPhone : true
08-25 15:26:16.101  7148  7148 D AppUp4:CustModeStarterReceiver: begin check event
08-25 15:26:16.101  7148  7148 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 15:26:16.104  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:16.105  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 15:26:16.106  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:16.109  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:16.116  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 15:26:16.122  4348  7467 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 15:26:16.127  4348  7469 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:16.128  4348  7469 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 15:26:16.131  7199  7470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:16.135  7361  7379 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 15:26:16.135  7361  7379 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 15:26:16.135  7361  7379 I Adreno-EGL: Build Date: 12/12/14 금
08-25 15:26:16.135  7361  7379 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 15:26:16.135  7361  7379 I Adreno-EGL: Remote Branch: 
08-25 15:26:16.135  7361  7379 I Adreno-EGL: Local Patches: 
08-25 15:26:16.135  7361  7379 I Adreno-EGL: Reconstruct Branch: 
08-25 15:26:16.139  7217  7217 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 15:26:16.141  1027  7230 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 15:26:16.141  1027  7230 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 15:26:16.141  1027  7230 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 15:26:16.141  7062  7472 W FormManager: Network not available. Please check & try again.
,08-25 15:26:16.141  1027  1532 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-25 15:26:16.146  3276  3276 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 15:26:16.146  3276  3276 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:16.146  3276  3276 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 15:26:16.148  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 15:26:16.148  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 15:26:16.153  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:16
,08-25 15:26:16.154  7062  7473 V FormManager: Network unavailable.
08-25 15:26:16.155  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 15:26:16.155  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
08-25 15:26:16.155  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 15:26:16.155  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 15:26:16.155  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3132d48d
08-25 15:26:16.156  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 15:26:16.156  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 15:26:16.157  7297  7297 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 15:26:16.157  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-25 15:26:16.157  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:16
08-25 15:26:16.160  7062  7473 V FormManager: Network unavailable.
08-25 15:26:16.180  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 15:26:16.180  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 15:26:16.180  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 15:26:16.180  6968  6968 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 15:26:16.180  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-25 15:26:16.182  6968  6968 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 15:26:16.182  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 15:26:16.182  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 15:26:16.182  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 15:26:16.182  6968  6968 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 15:26:16.182  6968  6968 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 15:26:16.190  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:16.194  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:26:16.197  7062  7480 W FormManager: Network not available. Please check & try again.
,08-25 15:26:16.201  7062  7481 V FormManager: Network unavailable.
08-25 15:26:16.203  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:16.215  7062  7481 V FormManager: Network unavailable.
08-25 15:26:16.220  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:16.224  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:26:16.224  7361  7379 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 15:26:16.224  7361  7379 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 15:26:16.224  7361  7379 I Adreno-EGL: Build Date: 12/12/14 금
08-25 15:26:16.224  7361  7379 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 15:26:16.224  7361  7379 I Adreno-EGL: Remote Branch: 
08-25 15:26:16.224  7361  7379 I Adreno-EGL: Local Patches: 
08-25 15:26:16.224  7361  7379 I Adreno-EGL: Reconstruct Branch: 
08-25 15:26:16.226  7062  7482 W FormManager: Network not available. Please check & try again.
08-25 15:26:16.230  7062  7483 V FormManager: Network unavailable.
08-25 15:26:16.232  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.236  7062  7483 V FormManager: Network unavailable.
,08-25 15:26:16.243  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 15:26:16.244  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 15:26:16.245  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:16.248  1027  1532 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 15:26:16.248  1027  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 15:26:16.248  1027  1532 E WifiStateMachine: useWiFiOffloading() : false
08-25 15:26:16.248  1027  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 15:26:16.249  1958  1958 D WfdsService: Supplicant Connection state is changed : false
08-25 15:26:16.249  1958  2313 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 15:26:16.249  1958  2313 D WfdsService: Set the WFDS Monitor: false
08-25 15:26:16.249  1958  2313 D WfdsMonitor: WFDS Monitor is stopped
08-25 15:26:16.249  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:16.250  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 15:26:16.251  2455  2455 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:16.252  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:16.253  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:16.253  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:16.253  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:16.253  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:16.253  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:16.253  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:16.253  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:16.253  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:16.253  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:16.255  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 15:26:16.255  1027  1536 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 15:26:16.255  1027  1536 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 15:26:16.256  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:16.256  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:16.256  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:16.256  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:16.256  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:16.256  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:16.256  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:16.256  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:16.256  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:16.256  4348  7484 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 15:26:16.259  4348  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 15:26:16.259  4348  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 15:26:16.318  1027  2029 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7486 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 15:26:16.366   305  7504 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-25 15:26:16.366  1027  1087 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 15:26:16.367  1835  7318 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-25 15:26:16.378  1835  7318 I CheckinService: active receiver: disabled
,08-25 15:26:16.438  7486  7486 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 15:26:16.438  7486  7486 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 15:26:16.447  7486  7486 V [BNRBootReceiver]: Boot Receiver Return
08-25 15:26:16.447  7486  7486 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 15:26:16.454  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:16.470  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.483  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.500  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:16.501  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:16.502  7018  7018 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 15:26:16.509  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 15:26:16.516  6968  6968 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 15:26:16.522  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:16.541  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.554  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.564  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:16.565  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:16.568  7018  7018 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 15:26:16.572  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:16.582  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.595  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.611  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:16.611  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 15:26:16.612  7018  7018 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:16.619  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:16.628  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.640  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.649  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:16.649  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:16.650  6668  7140 D UEI.SmartControl: Internal timer expired: 2
08-25 15:26:16.650  6668  7140 D UEI.SmartControl: unbind internal service
,08-25 15:26:16.651  7018  7018 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:16.662  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:16.679  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.689  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:16.698  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:16.699  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:16.701  7018  7018 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 15:26:16.707  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:16.716  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.724  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:16.731  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:16.732  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:16.732  7018  7018 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 15:26:16.737  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:16.747  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.754  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.762  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:16.762  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 15:26:16.763  7018  7018 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.,
,08-25 15:26:16.771  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:16.779  6668  7137 D serial_port: close(fd = 24)
,08-25 15:26:16.784  6668  7137 I UEI.SmartControl: Serial port is closed.
08-25 15:26:16.789  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.799  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.812  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:16.813  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:16.820  7018  7018 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:16.826  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:16.836  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.849  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.862  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:16.863  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:16.865  7018  7018 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:16.873  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:16.880  6989  6989 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 15:26:16.889  1027  1537 D WifiService: New client listening to asynchronous messages
08-25 15:26:16.890  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:16.895  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.902  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:16.910  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:16.911  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 15:26:16.912  7018  7018 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 15:26:16.913  7018  7018 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 15:26:16.914  7018  7018 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 15:26:16.921  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:16.926  6989  6989 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 15:26:16.929  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:16.933  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:16.941  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:16.952  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:16.952  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:16.954  7018  7018 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 15:26:16.956  7018  7018 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-25 15:26:16.957  7018  7018 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-25 15:26:16.963  1027  1757 I ActivityManager: Killing 6946:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-25 15:26:17.000  1027  1982 W libprocessgroup: failed to open /acct/uid_10037/pid_6946/cgroup.procs: No such file or directory
,08-25 15:26:17.007  2237  2237 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 15:26:17.026  2237  2237 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-25 15:26:17.027  2237  2237 D c       : Getting all permits...
08-25 15:26:17.027  2237  2237 D a       : Opening database...
,08-25 15:26:17.031  2237  2237 D a       : Opening database auth.proximity.permit_store...
08-25 15:26:17.032  2237  2237 D a       : Closing database...
08-25 15:26:17.049  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:17.056  6989  6989 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 15:26:17.057  6989  6989 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 15:26:17.057  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:17.065  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:17.077  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:17.088  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:17.088  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 15:26:17.090  7018  7018 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 15:26:17.094  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:17.098  6989  6989 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 15:26:17.099  6989  6989 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 15:26:17.099  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:17.103  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:17.109  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:17.118  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:17.119  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:17.121  7018  7018 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 15:26:17.127  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:17.132  6989  6989 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 15:26:17.132  6989  6989 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 15:26:17.132  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:17.139  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:17.153  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:17.166  7018  7018 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:17.167  7018  7018 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 15:26:17.170  7018  7018 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 15:26:17.184  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 15:26:17.194  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 15:26:17.197  7062  7513 W FormManager: Network not available. Please check & try again.
,08-25 15:26:17.207  7062  7514 V FormManager: Network unavailable.
08-25 15:26:17.209  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:17.233  7062  7514 V FormManager: Network unavailable.
,08-25 15:26:17.238  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 15:26:17.238  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 15:26:17.242  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:17.248  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:17.257  4348  7515 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 15:26:17.264  4348  7516 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 15:26:17.264  6989  6989 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 15:26:17.264  6989  6989 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 15:26:17.264  6989  6989 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:17.265  4348  7516 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 15:26:17.271  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:26:17.279  7062  7518 W FormManager: Network not available. Please check & try again.
08-25 15:26:17.281  7062  7519 V FormManager: Network unavailable.
08-25 15:26:17.284  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:17.285  7062  7519 V FormManager: Network unavailable.
08-25 15:26:17.305  2237  2237 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-25 15:26:17.700  1027  1532 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1042204828] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 15:26:17.702  1027  1532 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1042204826] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 15:26:17.778  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:17.797  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:17.798  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-25 15:26:17.799  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:17.799  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:17.810  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 15:26:17.811  6544  6988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 15:26:17.823  5781  5781 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 15:26:17.854  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:17.869  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 15:26:17.869  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:17.869  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 15:26:17.869  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 15:26:17.874  7148  7148 I AppUp4:CustModeStarterReceiver: onReceive
08-25 15:26:17.878  7148  7148 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d79d5b7
08-25 15:26:17.878  7148  7148 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 15:26:17.878  7148  7148 D AppUp4:CustFacade: isPhone : true
08-25 15:26:17.878  7148  7148 D AppUp4:CustModeStarterReceiver: begin check event
08-25 15:26:17.878  7148  7148 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 15:26:17.883  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:17.883  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 15:26:17.885  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 15:26:17.891  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:17.899  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 15:26:17.923  4348  7528 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 15:26:17.943  4348  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:17.943  4348  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 15:26:17.947  7199  7527 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:17.948  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 15:26:17.961  3276  3276 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 15:26:17.961  3276  3276 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:17.961  3276  3276 I LgeMiscReceiver: networkInfo.isConnected() = true
,08-25 15:26:17.963  7062  7542 W FormManager: Network not available. Please check & try again.
08-25 15:26:17.963  3276  3276 D PhoneState: setPdpRejectCasuse : false
08-25 15:26:17.966  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 15:26:17.966  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 15:26:17.976  7062  7543 V FormManager: Network unavailable.
,08-25 15:26:17.981  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:17
,08-25 15:26:17.984  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-25 15:26:17.984  7062  7543 V FormManager: Network unavailable.
08-25 15:26:17.984  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
08-25 15:26:17.984  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-25 15:26:17.984  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 15:26:17.984  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3132d48d
08-25 15:26:17.985  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 15:26:17.985  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 15:26:17.985  7297  7297 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 15:26:17.985  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 15:26:17.985  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:17
08-25 15:26:18.772  1027  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:18.773  1027  2010 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 15:26:18.805  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 15:26:18.805  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 15:26:18.805  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 15:26:18.806  1027  1089 D BluetoothManagerService: Message: 1
08-25 15:26:18.806  1027  1089 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 15:26:18.833  1027  1089 D BluetoothManagerService: Message: 20
08-25 15:26:18.833  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fea6954:true
,08-25 15:26:18.838  7090  7090 D BluetoothAdapterState: make
08-25 15:26:18.843  7090  7090 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 15:26:18.843  7090  7090 I bluedroid-qcom: init
08-25 15:26:18.844  7090  7560 I BluetoothAdapterState: Entering OffState
08-25 15:26:18.845  7090  7090 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 15:26:18.845  7090  7090 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 15:26:18.845  7090  7090 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 15:26:18.845  7090  7090 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 15:26:18.845  7090  7090 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 15:26:18.847  7090  7090 I bluedroid-qcom: get_profile_interface socket
08-25 15:26:18.847  7090  7090 I bluedroid-qcom: get_profile_interface map_client
,08-25 15:26:18.853  7090  7564 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 15:26:18.842  7563  7563 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:18.852  7563  7563 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:18.867  7563  7563 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 15:26:18.867  7563  7563 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 15:26:18.867  7563  7563 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-25 15:26:18.872  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 15:26:18.872  1027  1089 D BluetoothManagerService: Message: 40
08-25 15:26:18.872  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 15:26:18.873  7090  7106 I bluedroid-qcom: config_hci_snoop_log
08-25 15:26:18.875  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 15:26:18.875  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 15:26:18.878  7563  7563 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 15:26:18.883  7090  7560 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-25 15:26:18.887  7563  7563 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 15:26:18.887  7563  7563 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 15:26:18.889  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:18.894  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:18.896  1027  1089 D Tethering: MasterInitialState.processMessage what=3
,08-25 15:26:18.900  7090  7564 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 15:26:18.907  1027  1089 D Tethering: MasterInitialState.processMessage what=3
08-25 15:26:18.913  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:18.917  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:18.918  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:18.919  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:18.924  7090  7564 D BluetoothAdapterProperties: Name is: G3
08-25 15:26:18.925  7090  7560 D BluetoothAdapterProperties: Setting state to 11
08-25 15:26:18.925  7090  7560 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 15:26:18.926  1027  1089 D BluetoothManagerService: Message: 60
08-25 15:26:18.926  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 15:26:18.926  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-25 15:26:18.931  7090  7560 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 15:26:18.931  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 15:26:18.932  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 15:26:18.932  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:18.935  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 15:26:18.937  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:18.938  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:18.944  6968  6968 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-25 15:26:18.949  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-25 15:26:18.951  6544  6988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 15:26:18.959  7090  7560 D BluetoothBondStateMachine: make
,08-25 15:26:18.975  7090  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:18.975  7090  7560 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 15:26:18.976  7090  7560 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:18.976  7090  7560 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-25 15:26:18.983  7090  7560 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 15:26:18.984  7090  7565 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 15:26:18.984  5781  5781 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 15:26:18.987  7090  7090 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 15:26:18.988  7090  7090 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:18.988  7090  7090 V BluetoothPbapReceiver: ***********state = 11
08-25 15:26:18.991  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:26:19.010  7090  7560 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 15:26:19.039  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:19.074  1027  1043 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7576 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 15:26:19.083  5781  5781 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 15:26:19.087  7090  7090 D HeadsetService: Received start request. Starting profile...
08-25 15:26:19.088  7090  7090 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 15:26:19.088  7090  7090 D LGBluetoothHfpAdapter: Version 1.6
08-25 15:26:19.090  7090  7560 E BluetoothAdapterService: File transfer profiles supported!!
08-25 15:26:19.091  7090  7090 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 15:26:19.092  7090  7090 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 15:26:19.093  7090  7090 D HeadsetStateMachine: make
,08-25 15:26:19.102  1027  1084 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.103  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:19.103  1027  1084 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:19.105  7090  7560 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 15:26:19.119  7090  7560 E BluetoothAdapterService: File transfer profiles supported!!
08-25 15:26:19.121  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.134  7090  7560 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 15:26:19.140  7090  7090 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:19.140  7090  7090 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 15:26:19.144  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 15:26:19.144  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.144  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 15:26:19.144  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 15:26:19.147  7090  7560 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 15:26:19.148  7090  7090 D HeadsetStateMachine: max_hf_connections = 1
,08-25 15:26:19.148  7090  7090 I bluedroid-qcom: get_profile_interface handsfree
08-25 15:26:19.151  7090  7090 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 15:26:19.151  7148  7148 I AppUp4:CustModeStarterReceiver: onReceive
08-25 15:26:19.152   311   311 V AudioPolicyService: registerClient() client 0xb1021b80, uid 1002
08-25 15:26:19.152   311  1376 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 15:26:19.152   311  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 15:26:19.152   311  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 15:26:19.153  7090  7090 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 15:26:19.153   311  3002 V AudioFlinger: registerClient() client 0xb101fd30, pid 7090
08-25 15:26:19.154   311  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:19.154   311  1372 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:19.154  1597  1615 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:19.154  1597  1615 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:19.154  3276  3295 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:19.154  3276  3295 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:19.154  1871  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:19.154  1871  1886 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:19.154  7090  7105 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:19.154  7090  7105 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 15:26:19.154  1027  1734 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:19.154  1027  1734 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:19.155   311  1369 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:19.155   311  1369 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:19.155  1027  1957 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:19.155  1027  1957 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:19.155  1871  4437 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:19.155  1871  4437 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:19.155  3276  3296 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:19.155  3276  3296 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:19.155  7090  7106 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:19.155  7090  7090 V ToneGenerator: Create Track: 0xb4928a80
08-25 15:26:19.155  7090  7106 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 15:26:19.155  7090  7090 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 15:26:19.155  7090  7090 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 15:26:19.157  1597  2553 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:19.157  1597  2553 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:19.158   311   311 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 15:26:19.158   311   311 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 15:26:19.158   311   311 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 15:26:19.158   311   311 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 15:26:19.159   311  1376 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 15,:26:19.158  7090  7560 E BluetoothAdapterService: File transfer profiles supported!!
08-25 15:26:19.159   311  3002 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 15:26:19.159   311  3002 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 15:26:19.159   311  3002 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 15:26:19.159   311  3002 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 15:26:19.159  7090  7090 V AudioSystem: getLatency() output 2, latency 50
08-25 15:26:19.159  7090  7090 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 15:26:19.159  7090  7090 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 15:26:19.160   311  1377 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 15:26:19.160   311  1377 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 15:26:19.160   311  1377 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 15:26:19.160   311  1377 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 15:26:19.160   311  1377 V AudioFlinger: createTrack() lSessionId: 22
08-25 15:26:19.162  7090  7090 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 15:26:19.162   311   311 V AudioFlinger: acquiring 22 from 7090, for 7090
08-25 15:26:19.162   311   311 V AudioFlinger:  added new entry for 22
08-25 15:26:19.163  7090  7090 V ToneGenerator: ToneGenerator INIT OK, time: 192905
08-25 15:26:19.163  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:19.163  7090  7596 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 15:26:19.164  7090  7596 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 15:26:19.164  7090  7596 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 15:26:19.164  7090  7596 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 15:26:19.165  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:19.167   311  1376 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7090
,08-25 15:26:19.168  7090  7090 D A2dpService: Received start request. Starting profile...
08-25 15:26:19.169   311  1376 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 15:26:19.169   311  1376 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 15:26:19.169   311  1376 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 15:26:19.169   311  1376 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 15:26:19.169   311  1376 V voice   : voice_set_parameters: exit with code(0)
08-25 15:26:19.169   311  1376 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 15:26:19.169   311  1376 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 15:26:19.169  7090  7090 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 15:26:19.169   311  1376 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 15:26:19.169   311  1376 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 15:26:19.169   311  1376 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 15:26:19.169   311  1376 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 15:26:19.170  7090  7090 V Avrcp   : make
08-25 15:26:19.171  7090  7090 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 15:26:19.171  7090  7090 I bluedroid-qcom: get_profile_interface avrcp
08-25 15:26:19.171  7090  7596 V ToneGenerator: ToneGenerator destructor
08-25 15:26:19.171  7090  7596 V ToneGenerator: stopTone
08-25 15:26:19.171  7090  7596 V ToneGenerator: Delete Track: 0xb4928a80
08-25 15:26:19.176  7148  7148 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d79d5b7
08-25 15:26:19.176  7148  7148 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 15:26:19.176  7090  7596 V AudioTrack: ~AudioTrack, releasing session id from 7090 on behalf of 7090
08-25 15:26:19.177   311  3002 V AudioFlinger: releasing 22 from 7090 for 7090
08-25 15:26:19.177   311  3002 V AudioFlinger:  decremented refcount to 0
08-25 15:26:19.177   311  3002 V AudioFlinger: purging stale effects
08-25 15:26:19.177   311  3002 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 15:26:19.177   311  3002 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 15:26:19.177   311  3002 V AudioFlinger: PlaybackThread::Track destructor
08-25 15:26:19.177   311  1220 V AudioPolicyService: AudioCommandThread() waking up
08-25 15:26:19.177   311  1220 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 15:26:19.177   311  1220 V AudioPolicyManager: releaseOutput() 2
08-25 15:26:19.177   311  1220 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 15:26:19.180   311  3002 V AudioFlinger: removeClient_l() pid 7090, calling pid 311
08-25 15:26:19.185  7148  7148 D AppUp4:CustFacade: isPhone : true
,08-25 15:26:19.187  7090  7560 V LGMDMManager: Create singleton instance
08-25 15:26:19.189  7090  7090 V AudioManager: registerRemoteController: size of Media player list: 0
08-25 15:26:19.189  7090  7560 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 15:26:19.190  7148  7148 D AppUp4:CustModeStarterReceiver: begin check event
08-25 15:26:19.190  7090  7090 E AudioManager: No RCC entry present to update
08-25 15:26:19.191  7090  7090 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 15:26:19.194  7090  7090 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 15:26:19.195  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 15:26:19.195  7090  7090 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 15:26:19.198  7148  7148 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-25 15:26:19.212  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 15:26:19.212  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.212  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-25 15:26:19.214  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:19.258  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 15:26:19.263  7576  7576 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 15:26:19.263  7576  7576 W LG Account v2.2: No ProfileInfo entries
08-25 15:26:19.263  7576  7576 I LG Account v2.2: isEnabled: false
08-25 15:26:19.263  7576  7576 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 15:26:19.263  7576  7576 I Feature : [Lifetracker]Country: EU
08-25 15:26:19.263  7576  7576 I Feature : [Lifetracker]Operator: OPEN
08-25 15:26:19.263  4348  7606 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 15:26:19.263  7576  7576 I Feature : [Lifetracker]Ranking support: false
08-25 15:26:19.264  7576  7576 I Feature : [Lifetracker]Comfort support: false
08-25 15:26:19.264  7576  7576 I Feature : [Lifetracker]Accessory: true
08-25 15:26:19.264  7576  7576 I Feature : [Lifetracker]Health device: true
08-25 15:26:19.264  7576  7576 I Feature : [Lifetracker]Extra Pedometer: false
08-25 15:26:19.264  7576  7576 I Feature : [Lifetracker]Blood glucose device: false
08-25 15:26:19.264  7576  7576 I Feature : [Lifetracker]Device Number: 3
08-25 15:26:19.267  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 15:26:19.269  4348  7607 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.269  4348  7607 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 15:26:19.283  6968  6968 D BluetoothPermissionRequest: onReceive
,08-25 15:26:19.291  6968  6968 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 15:26:19.296  7199  7609 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:26:19.304  7062  7611 W FormManager: Network not available. Please check & try again.
08-25 15:26:19.309  1027  1568 V SIM_STK : Menu title from STK is T-Mobile
08-25 15:26:19.309  1027  1568 V SIM_STK : Menu title from STK is T-Mobile
08-25 15:26:19.310  3276  3276 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 15:26:19.310  3276  3276 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.310  3276  3276 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-25 15:26:19.315  7062  7612 V FormManager: Network unavailable.
08-25 15:26:19.315  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 15:26:19.315  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 15:26:19.325  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:19
,08-25 15:26:19.326  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 15:26:19.326  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
,08-25 15:26:19.326  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 15:26:19.326  7062  7612 V FormManager: Network unavailable.
08-25 15:26:19.326  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 15:26:19.326  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3132d48d
08-25 15:26:19.327  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 15:26:19.327  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 15:26:19.328  7297  7297 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 15:26:19.328  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 15:26:19.328  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:19
08-25 15:26:19.346  6544  6544 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 15:26:19.347  6544  6988 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 15:26:19.357  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:26:19.361  1027  2022 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 15:26:19.366  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 15:26:19.369  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 15:26:19.369  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.369  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 15:26:19.369  7148  7148 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 15:26:19.369  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 15:26:19.369  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 15:26:19.369  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 15:26:19.369  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 15:26:19.369  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 15:26:19.369  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 15:26:19.369  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 15:26:19.369  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 15:26:19.370  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 15:26:19.370  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 15:26:19.370  7090  7090 I BluetoothA2dpServiceJni: classInitNative
08-25 15:26:19.370  7090  7090 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 15:26:19.370  7090  7090 D A2dpStateMachine: make
08-25 15:26:19.371  7148  7148 I AppUp4:CustModeStarterReceiver: onReceive
08-25 15:26:19.371  7090  7090 I bluedroid-qcom: get_profile_interface a2dp
08-25 15:26:19.371  7090  7615 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 15:26:19.373  7090  7090 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 15:26:19.373  7090  7090 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 15:26:19.373  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:19.374  7090  7614 D A2dpStateMachine: Enter Disconnected: -2
08-25 15:26:19.374  7090  7090 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 15:26:19.374  7148  7148 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d79d5b7
08-25 15:26:19.374  7148  7148 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 15:26:19.374  7148  7148 D AppUp4:CustFacade: isPhone : true
08-25 15:26:19.375  7148  7148 D AppUp4:CustModeStarterReceiver: begin check event
08-25 15:26:19.375  7148  7148 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 15:26:19.375  7090  7090 D HidService: Received start request. Starting profile...
08-25 15:26:19.375  7090  7090 I bluedroid-qcom: get_profile_interface hidhost
08-25 15:26:19.375  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:19.375  7090  7090 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 15:26:19.377  7090  7090 D HealthService: Received start request. Starting profile...
08-25 15:26:19.378  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.378  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 15:26:19.378  7090  7090 I bluedroid-qcom: get_profile_interface health
08-25 15:26:19.378  7090  7090 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 15:26:19.378  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:19.379  7090  7090 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 15:26:19.379  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 15:26:19.382  7090  7090 D PanService: Received start request. Starting profile...
08-25 15:26:19.382  7090  7090 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 15:26:19.382  7090  7090 I bluedroid-qcom: get_profile_interface pan
08-25 15:26:19.383  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:19.388  7090  7090 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 15:26:19.388  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:19.388  7090  7090 D HeadsetStateMachine: Proxy object connected
08-25 15:26:19.388  7090  7090 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 15:26:19.389  7090  7090 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 15:26:19.390  7090  7090 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 15:26:19.391  4348  7620 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 15:26:19.391  7199  7199 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-25 15:26:19.393  7090  7090 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 15:26:19.394  7090  7090 D BtGatt.GattService: Received start request. Starting profile...
08-25 15:26:19.395  7090  7090 D BtGatt.GattService: start()
08-25 15:26:19.395  7090  7090 I bluedroid-qcom: get_profile_interface gatt
08-25 15:26:19.395  7090  7090 D BtGatt.AdvertiseManager: advertise manager created
08-25 15:26:19.398  4348  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.399  4348  7621 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 15:26:19.402  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:19.403  7090  7596 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 15:26:19.404  7090  7596 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 15:26:19.404  7090  7596 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-25 15:26:19.407  7090  7090 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 15:26:19.408  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:19.408  7090  7090 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 15:26:19.409  7199  7625 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:19.409  7090  7090 V BluetoothMapService: BluetoothMapBinder()
08-25 15:26:19.410  7090  7090 D BluetoothMapService: Received start request. Starting profile...
08-25 15:26:19.410  7090  7090 D BluetoothMapService: start()
08-25 15:26:19.412  7090  7090 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 15:26:19.412  7090  7090 D BluetoothMapEmailAppObserver: createReceiver()
08-25 15:26:19.413  3276  3276 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 15:26:19.413  3276  3276 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:19.413  3276  3276 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 15:26:19.413  7090  7090 D BluetoothMapEmailAppObserver: initObservers()
08-25 15:26:19.413  7090  7090 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 15:26:19.416  7240  7240 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 15:26:19.416  7240  7240 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 15:26:19.420  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
,08-25 15:26:19.421  7062  7626 W FormManager: Network not available. Please check & try again.
08-25 15:26:19.423  7090  7090 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 15:26:19.425  7090  7090 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 15:26:19.426  7090  7090 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 15:26:19.427  7090  7090 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 15:26:19.429  7090  7090 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 15:26:19.431  7062  7627 V FormManager: Network unavailable.
08-25 15:26:19.431  7090  7090 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 15:26:19.432  7090  7090 V BluetoothMapService: Handler(): got msg=1
08-25 15:26:19.432  7090  7560 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 15:26:19.432  7090  7560 I bluedroid-qcom: enable
08-25 15:26:19.433  7090  7560 I bt_hci_bdroid: init
08-25 15:26:19.434  7090  7560 I bt_vendor: bt-vendor : init
08-25 15:26:19.434  7090  7560 I bt_vendor: bt-vendor : get_bt_soc_type
,08-25 15:26:19.434  7090  7560 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 15:26:19.434  7090  7560 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 15:26:19.434  7090  7560 D bt_userial_mct: userial_init
08-25 15:26:19.433  7090  7629 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 15:26:19.434  7090  7629 I bt-btu  : btu_task pending for preload complete event
08-25 15:26:19.434  7090  7560 D bt_hci_bdroid: set_power 1
08-25 15:26:19.434  7090  7560 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 15:26:19.434  7090  7560 I bt_vendor: Starting hciattach daemon
08-25 15:26:19.434  7090  7560 I bt_vendor: try to set true
08-25 15:26:19.422  7632  7632 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:19.436  7297  7297 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:19
08-25 15:26:19.422  7632  7632 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:19.437  7090  7090 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:19.438  7297  7297 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 15:26:19.438  7297  7297 D Weather.Utils: 2 : All the weather widget is gone.
08-25 15:26:19.438  7062  7627 V FormManager: Network unavailable.
08-25 15:26:19.439  7297  7297 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 15:26:19.439  7090  7090 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 15:26:19.439  7090  7090 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 15:26:19.439  7090  7090 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 15:26:19.439  7297  7297 D WeatherAncestor: connectivity changed - connection : true
08-25 15:26:19.439  7090  7090 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:19.439  7297  7297 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3132d48d
08-25 15:26:19.439  7090  7090 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 15:26:19.440  7297  7297 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 15:26:19.440  7297  7297 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 15:26:19.440  7297  7297 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 15:26:19.440  7297  7297 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 15:26:19.440  7297  7297 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:19
08-25 15:26:19.449  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 15:26:19.501  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 15:26:19.512  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-25 15:26:19.535  7642  7642 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 15:26:19.552  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 15:26:19.565  7644  7644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 15:26:19.578  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 15:26:19.600  7647  7647 I libmdmdetect: ESOC framework not supported
08-25 15:26:19.601  7647  7647 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 15:26:19.614  7647  7647 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 15:26:19.614  7647  7647 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 15:26:19.614  7647  7647 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 15:26:19.614  7647  7647 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 15:26:19.614  7647  7647 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 15:26:19.614  7647  7647 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 15:26:19.615  7647  7647 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-25 15:26:19.660  7647  7648 E QC-QMI  : qmi_client [7647] 14: failed to locate client data
,08-25 15:26:19.664   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 15:26:19.664   444   444 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-25 15:26:19.712  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 15:26:19.734  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 15:26:19.769  1027  1085 W ProcessCpuTracker: Skipping unknown process pid 7632
,08-25 15:26:19.788  7090  7560 I bt_vendor: bluetooth satus is on
,08-25 15:26:19.788  7090  7560 D bt_hci_bdroid: preload
08-25 15:26:19.788  7090  7631 D bt_userial_mct: userial_open(port:0)
08-25 15:26:19.788  7090  7631 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 15:26:19.792  7090  7631 I bt_vendor: Done intiailizing UART
,08-25 15:26:19.796  7090  7631 I bt_vendor: Done intiailizing UART
08-25 15:26:19.796  7090  7631 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 15:26:19.796  7090  7631 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-25 15:26:19.796  7090  7652 D bt_userial_mct: Entering userial_read_thread()
08-25 15:26:19.797  7090  7629 I bt-btu  : btu_task received preload complete event
,08-25 15:26:19.797  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 15:26:19.798  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 15:26:19.800  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 15:26:19.803  7090  7629 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 15:26:19.893  7090  7629 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-25 15:26:19.893  7090  7629 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d7061 
08-25 15:26:19.893  7090  7629 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d7061 
,08-25 15:26:19.942  7090  7564 E bt-btif : Calling BTA_HhEnable
,08-25 15:26:19.942  7090  7564 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 15:26:19.943  7090  7564 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 15:26:19.945  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 15:26:19.945  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 15:26:19.946  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 15:26:19.946  7090  7564 D BluetoothAdapterProperties: Name is: G3
08-25 15:26:19.946  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-25 15:26:19.946  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-25 15:26:19.951  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 15:26:19.952  7090  7564 D BluetoothAdapterProperties: Scan Mode:20
08-25 15:26:19.952  7090  7564 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 15:26:19.952  7090  7564 D bt_hci_bdroid: postload
08-25 15:26:19.953  7090  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 15:26:19.954  7090  7629 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 15:26:19.954  7090  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 15:26:19.954  7090  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 15:26:19.955  7090  7564 D bte_conf: Device ID record 1 : primary
,08-25 15:26:19.955  7090  7564 D bte_conf:   vendorId            = 00c4
08-25 15:26:19.955  7090  7564 D bte_conf:   vendorIdSource      = 0001
08-25 15:26:19.955  7090  7564 D bte_conf:   product             = 13a1
08-25 15:26:19.955  7090  7564 D bte_conf:   version             = 1000
08-25 15:26:19.955  7090  7564 D bte_conf:   clientExecutableURL = 
08-25 15:26:19.955  7090  7564 D bte_conf:   serviceDescription  = 
08-25 15:26:19.955  7090  7564 D bte_conf:   documentationURL    = 
08-25 15:26:19.955  7090  7564 D bte_conf: bte_load_did_conf no section named DID2.
08-25 15:26:19.955  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 15:26:19.956  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:19.958  7090  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 15:26:19.958  7090  7631 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 15:26:19.960  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:19.960  7090  7564 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 15:26:19.961  7090  7560 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 15:26:19.961  7090  7560 D BluetoothAdapterProperties: ScanMode =  20,
08-25 15:26:19.961  7090  7560 D BluetoothAdapterProperties: State =  11
08-25 15:26:19.962  7090  7560 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 15:26:19.962  7090  7560 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 15:26:19.962  7090  7560 D BluetoothAdapterProperties: Setting state to 12
,08-25 15:26:19.962  7090  7560 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 15:26:19.963  7090  7564 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 15:26:19.964  1027  1089 D BluetoothManagerService: Message: 60
08-25 15:26:19.964  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 15:26:19.952  7654  7654 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 15:26:19.965  7090  7560 I BluetoothAdapterState: Entering On State
08-25 15:26:19.952  7654  7654 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:19.968  7090  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:19.968  7090  7629 W bt-smp  : Plain text(LSB ~ MSB) = 71 12 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-25 15:26:19.968  7090  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 9c 3c fc 8f 01 f4 fe 03 c5 68 d0 b1 6f 79 bc 84 
08-25 15:26:19.968  7090  7629 W bt-btm  : Stopping oneshot timer
08-25 15:26:19.968  7090  7631 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 15:26:19.969  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-25 15:26:19.971  7090  7560 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 15:26:19.971  7090  7652 E bt_mct  : hci lib postload completed
08-25 15:26:19.971  7090  7560 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 15:26:19.972  7090  7560 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 15:26:19.973  1871  2475 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:26:19.974  7090  7560 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 15:26:19.979  1871  1887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:26:19.980  1871  1871 D BluetoothHeadset: Proxy object connected
,08-25 15:26:19.983  6968  6983 D BluetoothPan: onBluetoothStateChange on: true
08-25 15:26:19.983  1871  1871 D BluetoothHeadset: Proxy object connected
08-25 15:26:19.983  6968  6983 D BluetoothPan: onBluetoothStateChange call bindService
08-25 15:26:19.984  7090  7564 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 15:26:19.984  7090  7564 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 15:26:19.989  6968  6968 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 15:26:19.989  6968  6968 D PanProfile: Bluetooth service connected
08-25 15:26:19.989  6968  6984 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 15:26:19.990  7090  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:19.990  7090  7629 W bt-smp  : Plain text(LSB ~ MSB) = c3 37 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:19.990  7090  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = b5 b1 a0 41 6f 16 19 91 f4 6b a1 55 61 1a d3 9e 
08-25 15:26:19.991  7090  7629 W bt-btm  : Stopping oneshot timer
,08-25 15:26:19.993  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:26:19.994  6968  6968 D BluetoothInputDevice: Proxy object connected
08-25 15:26:19.994  6968  6968 D HidProfile: Bluetooth service connected
08-25 15:26:19.995  1027  1027 D BluetoothHeadset: Proxy object connected
08-25 15:26:19.995  1871  4437 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:26:19.998  1871  1871 D BluetoothHeadset: Proxy object connected
08-25 15:26:19.999  6968  7657 D BluetoothMap: onBluetoothStateChange: up=true
08-25 15:26:20.002  6968  6968 D BluetoothMap: Proxy object connected
,08-25 15:26:20.002  6968  6968 D MapProfile: Bluetooth service connected
08-25 15:26:20.002  6968  6968 D BluetoothMap: getConnectedDevices()
08-25 15:26:20.003  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 15:26:20.004  7090  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:20.004  7090  7629 W bt-smp  : Plain text(LSB ~ MSB) = 31 17 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:20.004  7090  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = a2 97 0e ca 4c c3 01 8e 17 fb e3 b2 6a 2c 21 21 
08-25 15:26:20.004  7090  7629 W bt-btm  : Stopping oneshot timer
08-25 15:26:20.004  6968  6984 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 15:26:20.005  1027  1027 D BluetoothA2dp: Proxy object connected
08-25 15:26:20.005  7090  7106 V BluetoothMapService: getConnectedDevices()
08-25 15:26:20.008  1027  1089 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 15:26:20.013  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 15:26:20.015  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-25 15:26:20.016  7090  7560 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 15:26:20.017  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:20.018  1027  1089 D BluetoothManagerService: Message: 40
08-25 15:26:20.018  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 15:26:20.018  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 15:26:20.019  1958  2184 D LGBluetoothAPIService: Message: 1
,08-25 15:26:20.019  1958  2184 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 15:26:20.020  7090  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:20.020  7090  7629 W bt-smp  : Plain text(LSB ~ MSB) = 99 78 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:20.020  7090  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = 80 a8 b0 db cb 65 7f 01 75 b9 84 de 34 e3 e0 55 
08-25 15:26:20.021  7090  7629 W bt-btm  : Stopping oneshot timer
08-25 15:26:20.028  6832  6832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 15:26:20.030  7661  7661 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 15:26:20.034  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:20.034  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:20.034  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:20.034  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:20.034  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:20.034  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:20.034  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:20.034  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:20.036  7090  7090 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:20.037  7090  7090 D BluetoothMapService: STATE_ON
08-25 15:26:20.037  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:20.040  1958  2184 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-25 15:26:20.041  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:20.041  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:20.041  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:20.041  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:20.041  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:20.041  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:20.041  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:20.041  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:20.042  6968  6968 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 15:26:20.043  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:20.044  7090  7629 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:20.044  7090  7629 W bt-smp  : Plain text(LSB ~ MSB) = 44 85 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:20.044  7090  7629 W bt-smp  : Encrypted text(LSB ~ MSB) = fb a3 aa 82 dc 74 34 ef f4 31 08 58 ce 3d 70 10 
08-25 15:26:20.044  7090  7629 W bt-btm  : Stopping oneshot timer
08-25 15:26:20.044  1027  1089 D BluetoothManagerService: Message: 30
08-25 15:26:20.048  6968  6968 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 15:26:20.051  1027  1089 D BluetoothManagerService: Message: 30
08-25 15:26:20.053  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
,08-25 15:26:20.053  7090  7090 V BluetoothPbapService: Pbap Service onCreate
08-25 15:26:20.053  7090  7090 V BluetoothPbapService: Starting PBAP service
08-25 15:26:20.054  7090  7090 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 15:26:20.055  7090  7090 V BluetoothPbapService: Pbap Service onBind
08-25 15:26:20.056  7090  7090 V BluetoothMapService: Handler(): got msg=1
08-25 15:26:20.056  7090  7090 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 15:26:20.057  7090  7090 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:20.057  6968  6968 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 15:26:20.057  7090  7090 V BluetoothPbapService: state: 12
08-25 15:26:20.058  7090  7664 D BluetoothMapMasInstance: MAS initSocket()
08-25 15:26:20.059  7090  7664 D BluetoothMapMasInstance:   masId = 00
08-25 15:26:20.059  7090  7664 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 15:26:20.059  7090  7664 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 15:26:20.059  7090  7664 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 15:26:20.059  7090  7090 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 15:26:20.059  7090  7090 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 15:26:20.059  6968  6968 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 15:26:20.060  7090  7090 V BluetoothPbapService: Handler(): got msg=1
08-25 15:26:20.060  1958  1958 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 15:26:20.060  1958  2184 D LGBluetoothAPIService: Message: 100
08-25 15:26:20.060  1958  2184 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 15:26:20.061  1027  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:20.061  7090  7090 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 15:26:20.062  7090  7664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:20.062  7090  7665 V BluetoothPbapService: Pbap Service initSocket
08-25 15:26:20.063  7090  7664 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 15:26:20.063  7090  7664 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 15:26:20.064  7090  7664 D BluetoothMapMasInstance: Accepting socket connection...
08-25 15:26:20.064  1027  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:20.064  6968  6968 D BluetoothA2dp: Proxy object connected
08-25 15:26:20.064  7090  7090 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 15:26:20.064  7090  7090 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:20.064  7090  7090 V BluetoothPbapReceiver: ***********state = 12
08-25 15:26:20.065  6968  6968 D A2dpProfile: Bluetooth service connected
08-25 15:26:20.066  7090  7564 D BluetoothAdapterProperties: Scan Mode:21
08-25 15:26:20.066  7090  7564 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-25 15:26:20.071  7090  7665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:20.072  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:20.072  6968  6968 D BluetoothHeadset: Proxy object connected
08-25 15:26:20.073  6968  6968 D HeadsetProfile: Bluetooth service connected
08-25 15:26:20.073  7090  7665 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 15:26:20.074  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 15:26:20.074  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:20.074  2237  2237 D c       : Getting all permits...
08-25 15:26:20.074  2237  2237 D a       : Opening database...
08-25 15:26:20.074  7090  7665 V BluetoothPbapService: Succeed to create listening socket 
08-25 15:26:20.074  7090  7665 V BluetoothPbapService: Accepting socket connection...
08-25 15:26:20.076  6968  6968 D BluetoothPbap: Proxy object connected
08-25 15:26:20.077  2237  2237 D a       : Opening database auth.proximity.permit_store...
08-25 15:26:20.077  6968  6968 D PbapServerProfile: Bluetooth service connected
08-25 15:26:20.078  2237  2237 D a       : Closing database...
08-25 15:26:20.081  6968  6968 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:26:20.088  6968  6968 D BluetoothPermissionRequest: onReceive
08-25 15:26:20.089  6968  6968 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 15:26:20.091  6968  6968 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 15:26:20.094  7090  7090 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-25 15:26:20.096  7090  7090 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 15:26:20.098  7326  7355 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-25 15:26:20.101  7090  7090 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-25 15:26:20.118  7090  7090 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 15:26:20.118  7090  7090 V BtOppService: onCreate
,08-25 15:26:20.121  7090  7090 V BluetoothOppNotification: send message
08-25 15:26:20.124  7090  7090 V BtOppService: Starting RfcommListener
08-25 15:26:20.127  7090  7090 D BluetoothOppPreference: Dumping Names:  
08-25 15:26:20.128  7090  7090 D BluetoothOppPreference: {}
08-25 15:26:20.128  7090  7090 D BluetoothOppPreference: Dumping Channels:  
08-25 15:26:20.128  7090  7090 D BluetoothOppPreference: {}
08-25 15:26:20.128  7090  7090 V BtOppService: onStartCommand
08-25 15:26:20.131  7090  7674 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 15:26:20.132  7090  7090 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:20.132  7090  7090 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-25 15:26:20.134  7090  7090 V BluetoothOppNotification: new notify threadi!
08-25 15:26:20.135  7090  7090 V BluetoothOppNotification: send delay message
08-25 15:26:20.136  7090  7090 V BtOppService: start RfcommListener
08-25 15:26:20.136  7090  7671 V BtOppService: Deleted complete outbound shares, number =  0
08-25 15:26:20.137  7090  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 15:26:20.137  7090  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 15:26:20.138  7090  7671 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 15:26:20.138  7090  7671 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 15:26:20.139  7090  7090 V BtOppService: RfcommListener started
08-25 15:26:20.140  7090  7671 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@214f829e on behalf of 
08-25 15:26:20.140  7090  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cdaf17f on behalf of 
08-25 15:26:20.141  7090  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3607b54c on behalf of 
08-25 15:26:20.145  7090  7675 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 15:26:20.147  7090  7676 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 15:26:20.148  7090  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 15:26:20.148  1027  1734 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:20.149  7090  7674 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 15:26:20.150  7090  7676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:20.150  7090  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f4d8995 on behalf of 
08-25 15:26:20.151  7090  7676 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-25 15:26:20.151  7090  7676 V BtOppRfcommListener: Started RFCOMM listener....
08-25 15:26:20.151  7090  7676 I BtOppRfcommListener: Accept thread started.
08-25 15:26:20.151  7090  7676 V BtOppRfcommListener: Accepting connection...
08-25 15:26:20.156  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:20.157  7090  7090 V BluetoothFtpService: Ftp Service onCreate
08-25 15:26:20.157  7090  7090 I BluetoothFtpService: Ftp Service onCreate
08-25 15:26:20.157  7090  7090 V BluetoothFtpService: Ftp Service onStartCommand
,08-25 15:26:20.157  7090  7090 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:26:20.157  7090  7090 V BluetoothFtpService: Starting Listening on sockets
08-25 15:26:20.158  7090  7090 V BtOppService: ContentObserver received notification
08-25 15:26:20.158  7090  7090 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 15:26:20.158  7090  7090 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 15:26:20.158  7090  7090 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 15:26:20.158  7090  7090 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:20.158  7090  7090 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 15:26:20.158  7090  7090 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 15:26:20.159  7090  7675 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 15:26:20.160  7090  7675 V BluetoothOppNotification: outbound notification was removed.
08-25 15:26:20.160  7090  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 15:26:20.161  7090  7090 V BtOppService: ContentObserver received notification
08-25 15:26:20.161  7090  7090 V BluetoothFtpService: Handler(): got msg=1
08-25 15:26:20.162  7090  7677 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 15:26:20.163  7090  7677 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 15:26:20.163  7090  7090 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 15:26:20.163  7090  7090 V BluetoothFtpService: Ftp Service initSocket
08-25 15:26:20.165  1027  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:20.166  7090  7090 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:20.166  7090  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9b7269b on behalf of 
08-25 15:26:20.167  7090  7675 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 15:26:20.167  7090  7090 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-25 15:26:20.168  7090  7090 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 15:26:20.169  7090  7678 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-25 15:26:20.193  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:20.194  7090  7090 V BluetoothSapService: Sap Service onCreate
,08-25 15:26:20.289  1027  1043 I art     : Explicit concurrent mark sweep GC freed 96303(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.744ms total 125.247ms
08-25 15:26:20.290  1027  1040 I art     : WaitForGcToComplete blocked for 5.345ms for cause HeapTrim
08-25 15:26:20.290  7090  7677 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f8b4776 on behalf of 
08-25 15:26:20.291  7090  7677 V BluetoothOppNotification: update too frequent, put in queue
,08-25 15:26:20.294  7090  7090 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:20.294  7090  7090 V BluetoothSapService: state: 12
08-25 15:26:20.294  7090  7090 V BluetoothSapService: Starting SAP server process
08-25 15:26:20.294  7090  7675 V BluetoothOppNotification: inbound notification was removed.
08-25 15:26:20.294  7090  7675 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 15:26:20.300  7090  7675 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31a561e4 on behalf of 
08-25 15:26:20.301  7090  7090 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 15:26:20.292  7679  7679 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:20.292  7679  7679 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:20.307  7090  7680 V BluetoothSapService: Sap Service initRfcommSocket
,08-25 15:26:20.308  1027  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 15:26:20.308  7090  7677 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 15:26:20.309  7090  7680 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:20.309  7090  7680 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=81
08-25 15:26:20.310  7090  7680 V BluetoothSapService: Succeed to create listening socket 
08-25 15:26:20.310  7090  7680 V BluetoothSapService: Accepting socket connection...
08-25 15:26:20.323  7679  7679 V BT_SAP  : Event pipe created
08-25 15:26:20.323  7679  7679 V BT_SAP  : create_server_socket qcom.sap.server
08-25 15:26:20.323  7679  7679 V BT_SAP  : created socket fd 6
,08-25 15:26:20.832  1027  1530 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:20.832  1027  1530 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:26:20.880  1027  1532 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 15:26:20.881  1027  1532 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 15:26:21.084  1027  2105 I ActivityManager: Killing 7486:com.lge.bnr/1000 (adj 15): empty #17
,08-25 15:26:21.118  1027  1734 W libprocessgroup: failed to open /acct/uid_1000/pid_7486/cgroup.procs: No such file or directory
,08-25 15:26:21.143  7090  7090 V BluetoothOppNotification: new notify threadi!
08-25 15:26:21.143  7090  7090 V BluetoothOppNotification: send delay message
,08-25 15:26:21.147  7090  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 15:26:21.148  7090  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2196564d on behalf of 
08-25 15:26:21.149  7090  7690 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 15:26:21.150  7090  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 15:26:21.151  7090  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27dc6502 on behalf of 
08-25 15:26:21.152  7090  7690 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 15:26:21.153  7090  7690 V BluetoothOppNotification: outbound notification was removed.
08-25 15:26:21.153  7090  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 15:26:21.154  7090  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@129ce13 on behalf of 
08-25 15:26:21.155  7090  7690 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 15:26:21.160  7090  7690 V BluetoothOppNotification: inbound notification was removed.
,08-25 15:26:21.161  7090  7690 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-25 15:26:21.162  7090  7690 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3148b850 on behalf of 
08-25 15:26:21.371  1027  2105 I ActivityManager: Killing 6668:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-25 15:26:21.410  7018  7018 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-25 15:26:21.411  7018  7018 W System.err: android.os.DeadObjectException
08-25 15:26:21.411  7018  7018 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 15:26:21.411  7018  7018 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 15:26:21.411  7018  7018 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-25 15:26:21.411  7018  7018 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-25 15:26:21.411  7018  7018 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 15:26:21.411  7018  7018 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 15:26:21.411  7018  7018 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 15:26:21.411  7018  7018 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 15:26:21.411  7018  7018 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 15:26:21.411  7018  7018 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 15:26:21.411  7018  7018 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:26:21.411  7018  7018 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:26:21.411  7018  7018 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 15:26:21.411  7018  7018 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 15:26:21.412  7018  7018 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-25 15:26:21.412  7018  7018 W System.err: android.os.DeadObjectException
08-25 15:26:21.412  7018  7018 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 15:26:21.412  7018  7018 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 15:26:21.412  7018  7018 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-25 15:26:21.412  7018  7018 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-25 15:26:21.412  7018  7018 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 15:26:21.412  7018  7018 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 15:26:21.412  7018  7018 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 15:26:21.412  7018  7018 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 15:26:21.413  7018  7018 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 15:26:21.413  7018  7018 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 15:26:21.413  7018  7018 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:26:21.413  7018  7018 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:26:21.413  7018  7018 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 15:26:21.413  7018  7018 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 15:26:21.413  7018  7018 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-25 15:26:21.413  7018  7018 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-25 15:26:21.448  1027  1734 W libprocessgroup: failed to open /acct/uid_1000/pid_6668/cgroup.procs: No such file or directory
08-25 15:26:21.448  1027  1734 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-25 15:26:21.455  7018  7018 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-25 15:26:21.455  7018  7018 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 15:26:21.506  1027  1957 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7691 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 15:26:21.556  7018  7018 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 15:26:21.584  7691  7691 D UEI.SmartControl: Quickset Services start...
08-25 15:26:21.586  7691  7691 I UEI.SmartControl: Manufacture = LGE
08-25 15:26:21.587  7691  7691 D UEI.SmartControl: Id = LGNevo
,08-25 15:26:21.591  7691  7691 D UEI.SmartControl: File observer start...
08-25 15:26:21.592  7691  7691 E UEI.SmartControl: IR Port is disabled: false
08-25 15:26:21.592  7691  7691 D UEI.SmartControl: Starting file observer...
08-25 15:26:21.592  7691  7691 D UEI.SmartControl: Extracting JNI libs...
08-25 15:26:21.592  7691  7691 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-25 15:26:21.701  7691  7691 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-25 15:26:21.701  7691  7691 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-25 15:26:21.701  7691  7691 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-25 15:26:21.740  7691  7691 I UEI.SmartControl: --- Selecting new region: 6
,08-25 15:26:21.742  7691  7691 I UEI.SmartControl: Model = LG-D855
08-25 15:26:21.744  7691  7691 D UEI.SmartControl: QS Service created
,08-25 15:26:21.762  7691  7691 I UEI.SmartControl: Service initServices...
,08-25 15:26:21.769  7691  7691 D UEI.SmartControl: QS start get config
08-25 15:26:21.811  7691  7691 D UEI.SmartControl: Loading JNI Libs...
,08-25 15:26:21.820  1027  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:21.820  1027  2029 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@11992b3f mBinding = false
,08-25 15:26:21.840  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 15:26:21.841  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 15:26:21.841  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 15:26:21.842  1027  1089 D BluetoothManagerService: Message: 2
08-25 15:26:21.844  1027  1089 D BluetoothManagerService: Sending off request.
08-25 15:26:21.845  7090  7662 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 15:26:21.847  7090  7560 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 15:26:21.847  7090  7560 D BluetoothAdapterProperties: Setting state to 13
08-25 15:26:21.847  7090  7560 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 15:26:21.848  7090  7560 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 15:26:21.848  7090  7560 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 15:26:21.851  7090  7564 D BluetoothAdapterProperties: Scan Mode:20
,08-25 15:26:21.853  7090  7560 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 15:26:21.854  7090  7680 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:21.854  7090  7560 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 15:26:21.854  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 15:26:21.854  7090  7629 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 15:26:21.855  1027  1089 D BluetoothManagerService: Message: 60
08-25 15:26:21.855  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 15:26:21.855  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 15:26:21.855  7090  7664 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 15:26:21.855  7090  7664 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:21.855  7090  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 15:26:21.855  7090  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 15:26:21.855  7090  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 15:26:21.855  7090  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 15:26:21.855  7090  7664 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 15:26:21.855  7090  7664 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 15:26:21.856  7090  7678 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:21.856  7090  7665 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:21.857  7090  7676 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:26:21.858  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:21.858  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:21.858  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:21.858  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:21.858  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:21.858  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:21.858  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:21.858  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:21.858  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:26:21.860  7090 , 7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 15:26:21.860  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 15:26:21.860  7090  7629 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 15:26:21.861  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:21.861  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:21.863  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:21.863  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:21.863  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:21.863  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:21.863  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:21.863  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:26:21.863  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-25 15:26:21.863  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:21.863  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:26:21.865  6832  6832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:26:21.865  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:21.867  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:21.869  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 15:26:21.870  7090  7090 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:21.871  7090  7090 D BluetoothMapService: STATE_TURNING_OFF
08-25 15:26:21.871  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:21.872  7090  7090 V BtOppService: Receiver DISABLED_ACTION 
08-25 15:26:21.872  7090  7090 V BluetoothMapService: Handler(): got msg=4
08-25 15:26:21.872  7090  7090 D BluetoothMapService: MAP Service closeService in
08-25 15:26:21.872  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:21.872  7090  7090 D BluetoothMapMasInstance: MAP Service shutdown
08-25 15:26:21.872  7090  7090 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 15:26:21.872  7090  7090 V BluetoothMapService: MAP Service closeService out
08-25 15:26:21.872  7090  7090 I BtOppRfcommListener: stopping Accept Thread
08-25 15:26:21.872  7090  7090 V BtOppRfcommListener: close mBtServerSocket
08-25 15:26:21.874  7090  7676 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 15:26:21.874  7090  7090 V BtOppRfcommListener: waiting for thread to terminate
08-25 15:26:21.875  7090  7090 V BtOppRfcommListener: done waiting for thread to terminate
08-25 15:26:21.875  7090  7090 V BtOppService: onDestroy
,08-25 15:26:21.876  6968  6968 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-25 15:26:21.877  7090  7090 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 15:26:21.879  6968  6968 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 15:26:21.883  7090  7090 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 15:26:21.883  7090  7090 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:21.883  7090  7090 V BluetoothPbapReceiver: ***********state = 13
08-25 15:26:21.884  7090  7090 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 15:26:21.885  7090  7090 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:21.885  7090  7090 V BluetoothPbapService: state: 13
08-25 15:26:21.885  7090  7090 V BluetoothPbapService: Pbap Service closeService in
08-25 15:26:21.887  7090  7090 V BluetoothPbapService: successfully stopped pbap service
08-25 15:26:21.887  6968  6968 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:26:21.887  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 15:26:21.888  7090  7090 V BluetoothPbapService: Pbap Service closeService out
08-25 15:26:21.888  6968  6968 D BluetoothPbap: Proxy object disconnected
08-25 15:26:21.888  6968  6968 D PbapServerProfile: Bluetooth service disconnected
08-25 15:26:21.888  7090  7090 V BluetoothPbapService: Pbap Service onDestroy
08-25 15:26:21.888  7090  7090 V BluetoothPbapService: Pbap Service closeService in
08-25 15:26:21.888  7090  7090 V BluetoothPbapService: Pbap Service closeService out
08-25 15:26:21.888  7090  7090 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-25 15:26:21.902  6968  6968 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 15:26:21.907  6968  6968 D BluetoothPermissionRequest: onReceive
08-25 15:26:21.907  6968  6968 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 15:26:21.914  6968  6968 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 15:26:21.917  7090  7090 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 15:26:21.917  7090  7090 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-25 15:26:21.917  7090  7090 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-25 15:26:21.921  7090  7090 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:21.921  7090  7090 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 15:26:21.922  7090  7090 V BluetoothFtpService: Ftp Service onStartCommand
08-25 15:26:21.922  7090  7090 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:21.922  7090  7090 V BluetoothFtpService: Ftp Service closeService
08-25 15:26:21.922  7090  7090 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 15:26:21.924  7090  7090 V BluetoothFtpService: successfully stopped ftp service
08-25 15:26:21.924  7090  7090 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 15:26:21.924  7090  7090 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 15:26:21.924  7090  7090 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 15:26:21.924  7090  7090 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:21.924  7090  7090 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 15:26:21.924  7090  7090 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 15:26:21.925  7090  7090 V BluetoothFtpService: Ftp Service onDestroy
08-25 15:26:21.925  7090  7090 V BluetoothFtpService: Ftp Service closeService
08-25 15:26:21.929  7090  7090 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:21.929  7090  7090 V BluetoothSapService: state: 13
08-25 15:26:21.929  7090  7090 V BluetoothSapService: Stopping SAP server process
,08-25 15:26:21.931  7090  7090 V BluetoothSapService: Sap Service closeSapService in
08-25 15:26:21.931  7090  7090 V BluetoothSapService: Close listen Socket : 
08-25 15:26:21.931  7090  7090 V BluetoothSapService: Close rfcomm Socket : 
08-25 15:26:21.931  7090  7090 V BluetoothSapService: Close sapd  Socket : 
08-25 15:26:21.933  7090  7090 V BluetoothSapService: Sap Service closeSapService out
08-25 15:26:21.933  7090  7090 V BluetoothSapService: Sap Service onDestroy
08-25 15:26:21.933  7090  7090 V BluetoothSapService: Sap Service closeSapService in
08-25 15:26:21.933  7090  7090 V BluetoothSapService: Close listen Socket : 
08-25 15:26:21.933  7090  7090 V BluetoothSapService: Close rfcomm Socket : 
08-25 15:26:21.933  7090  7090 V BluetoothSapService: Close sapd  Socket : 
08-25 15:26:21.933  7090  7090 V BluetoothSapService: Sap Service closeSapService out
08-25 15:26:22.151  7691  7691 I UEI.SmartControl: Supports setup maps: true
,08-25 15:26:22.154  7691  7691 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 15:26:22.155  7691  7691 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 15:26:22.155  7691  7691 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 15:26:22.155  7691  7691 I UEI.SmartControl: ### init IR Blaster...
,08-25 15:26:22.162  7691  7691 D serial_port: Configuring serial port
08-25 15:26:22.171  7691  7691 E UEI.SmartControl: UEIBLaster setting for 616
08-25 15:26:22.171  7691  7691 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 15:26:22.173  7691  7691 I UEI.SmartControl: configuring settings for MAXQ616
08-25 15:26:22.174  7691  7691 I UEI.SmartControl: Get version...
,08-25 15:26:22.192  7691  7729 D UEI.SmartControl: serial port data available: 21
,08-25 15:26:22.222  7691  7691 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 15:26:22.222  7691  7691 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 15:26:22.223  7691  7691 I UEI.SmartControl: QS saving settings...
08-25 15:26:22.225  7691  7691 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 15:26:22.240  7691  7729 D UEI.SmartControl: serial port data available: 4
,08-25 15:26:22.282  7691  7738 I UEI.SmartControl: Device manager: loading config....
,08-25 15:26:22.283  7691  7738 D UEI.SmartControl: ----------- loading internal config...
,08-25 15:26:22.287  7691  7691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 15:26:22.316  7691  7691 E UEI.SmartControl: Services init done
08-25 15:26:22.316  7691  7691 D UEI.SmartControl: QS Service init finished
,08-25 15:26:22.321  7691  7691 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 15:26:22.321  7691  7691 D UEI.SmartControl: QS Service version code: 201091
08-25 15:26:22.322  7691  7691 D UEI.SmartControl: Service requested: Control
08-25 15:26:22.325  7691  7738 E UEI.SmartControl: Loading SETTINGS...
08-25 15:26:22.327  7691  7691 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 15:26:22.331  1027  1757 I ActivityManager: Killing 7018:com.lge.qremote/u0a112 (adj 15): empty #17
,08-25 15:26:22.342  7691  7738 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 15:26:22.356  7691  7737 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 15:26:22.356  7691  7737 D UEI.SmartControl: -----service ready thread exits
,08-25 15:26:22.388  1027  1043 W libprocessgroup: failed to open /acct/uid_10112/pid_7018/cgroup.procs: No such file or directory
,08-25 15:26:22.393  7691  7691 D UEI.SmartControl: Internal service binding...
,08-25 15:26:22.813  7090  7564 D bt_hci_bdroid: cleanup
,08-25 15:26:22.823  7090  7631 I bt_lpm  : LPM is already off!!!
08-25 15:26:22.823  7090  7652 I bt_userial_mct: exiting userial_read_thread
08-25 15:26:22.823  7090  7652 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 15:26:22.824  7090  7629 W bt-btif : ag scb idx 1 not allocated
08-25 15:26:22.824  7090  7629 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 15:26:22.825  7090  7629 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:26:22.826  7090  7629 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 15:26:22.826  7090  7629 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:26:22.826  7090  7629 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 15:26:22.830  7090  7564 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0,
08-25 15:26:22.830  7090  7631 I bt_vendor: hw_epilog_process
08-25 15:26:22.830  7090  7564 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 15:26:22.830  7090  7564 D bt_userial_mct: userial_close
,08-25 15:26:22.830  7090  7564 E bt_userial_mct: pthread_join() FAILED result:3
08-25 15:26:22.831  7090  7564 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 15:26:22.838  7090  7564 D bt_hci_bdroid: set_power 0
08-25 15:26:22.838  7090  7564 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 15:26:22.838  7090  7564 I bt_vendor: bluetooth satus is on
08-25 15:26:22.838  7090  7564 I bt_vendor: bt-vendor : resetting BT status,
08-25 15:26:22.838  7090  7564 I bt_vendor: Starting hciattach daemon
08-25 15:26:22.838  7090  7564 I bt_vendor: try to set false
,08-25 15:26:22.847  7090  7564 I bt_vendor: Starting hciattach daemon
08-25 15:26:22.847  7090  7564 I bt_vendor: try to set false
08-25 15:26:22.850  7090  7564 I bt_vendor: cleanup
08-25 15:26:22.850  7090  7629 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 15:26:22.851  7090  7564 I GKI_LINUX: GKI_exit_task 0 done
08-25 15:26:22.851  7090  7564 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 15:26:22.852  7090  7560 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-25 15:26:22.859  7090  7090 D HeadsetService: Received stop request...Stopping profile...
08-25 15:26:22.861  7090  7090 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 15:26:22.861  7090  7090 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:26:22.861  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:22.862  7090  7596 D HeadsetStateMachine: Exit Disconnected: -1
08-25 15:26:22.866  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-25 15:26:22.866  1871  1871 D BluetoothHeadset: Proxy object disconnected
08-25 15:26:22.866  1871  1871 D BluetoothHeadset: Proxy object disconnected
,08-25 15:26:22.869  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-25 15:26:22.869  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 15:26:22.869  7090  7090 D A2dpService: Received stop request...Stopping profile...
08-25 15:26:22.870  7090  7614 D A2dpStateMachine: Exit Disconnected: -1
08-25 15:26:22.871  7090  7090 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 15:26:22.876  7090  7560 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 15:26:22.877  7090  7090 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 15:26:22.877  7090  7090 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:26:22.877  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:22.879  7090  7090 D HidService: Received stop request...Stopping profile...
08-25 15:26:22.879  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
,08-25 15:26:22.883  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-25 15:26:22.883  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 15:26:22.885  7090  7090 D HeadsetStateMachine: Unbinding service...
08-25 15:26:22.887  7090  7090 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 15:26:22.887  7090  7090 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 15:26:22.887  7090  7090 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 15:26:22.887  7090  7090 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 15:26:22.887  7090  7090 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 15:26:22.887  7090  7090 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:26:22.888  7090  7090 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 15:26:22.889  7090  7090 D HealthService: Received stop request...Stopping profile...
08-25 15:26:22.889  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:22.891  7090  7090 D PanService: Received stop request...Stopping profile...
,08-25 15:26:22.893  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:22.894  7090  7090 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 15:26:22.896  7090  7090 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 15:26:22.896  7090  7090 D BtGatt.GattService: stop()
08-25 15:26:22.896  7090  7090 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 15:26:22.898  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:22.899  7090  7090 D BluetoothMapService: Received stop request...Stopping profile...
08-25 15:26:22.899  7090  7090 D BluetoothMapService: stop()
08-25 15:26:22.900  7090  7090 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 15:26:22.900  7090  7090 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 15:26:22.900  7090  7090 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3132d48d
08-25 15:26:22.901  7090  7090 I BluetoothA2dpServiceJni: cleanupNative
08-25 15:26:22.901  7090  7615 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 15:26:22.902  7090  7090 I GKI_LINUX: GKI_exit_task 2 done
08-25 15:26:22.902  7090  7090 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 15:26:22.902  7090  7090 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 15:26:22.902  7090  7090 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 15:26:22.902  7090  7090 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 15:26:22.903  7090  7090 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 15:26:22.903  7090  7090 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 15:26:22.903  7090  7090 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 15:26:22.903  7090  7090 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 15:26:22.908  7090  7090 V BluetoothMapService: Handler(): got msg=4
08-25 15:26:22.908  7090  7090 D BluetoothMapService: MAP Service closeService in
08-25 15:26:22.908  7090  7090 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 15:26:22.908  7090  7090 V BluetoothMapService: MAP Service closeService out
08-25 15:26:22.909  7090  7560 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 15:26:22.910  7090  7560 D BluetoothAdapterProperties: Setting state to 10
08-25 15:26:22.910  7090  7560 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 15:26:22.911  1027  1089 D BluetoothManagerService: Message: 60
08-25 15:26:22.911  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 15:26:22.911  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-25 15:26:22.912  1871  1886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:22.913  7090  7560 I BluetoothAdapterState: Entering OffState
08-25 15:26:22.914  1871  4437 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:22.915  7090  7090 D BluetoothMapService: cleanup()
08-25 15:26:22.915  7090  7090 D BluetoothMapService: MAP Service closeService in
08-25 15:26:22.915  7090  7090 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 15:26:22.915  7090  7090 V BluetoothMapService: MAP Service closeService out
08-25 15:26:22.916  6968  7657 D BluetoothPan: onBluetoothStateChange on: false
,08-25 15:26:22.920  6968  7657 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 15:26:22.922  6968  7657 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:22.922  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:22.922  1871  2475 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 15:26:22.923  6968  7657 D BluetoothMap: onBluetoothStateChange: up=false
08-25 15:26:22.923  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 15:26:22.924  6968  7657 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 15:26:22.924  6968  7657 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 15:26:22.925  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 15:26:22.925  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 15:26:22.927  1027  1089 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 15:26:22.927  1027  1089 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 15:26:22.927  1027  1089 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@11992b3f mBinding = false
,08-25 15:26:22.931  1027  1089 D BluetoothManagerService: Sending unbind request.
08-25 15:26:22.935  7090  7564 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 15:26:22.936  7090  7090 I GKI_LINUX: GKI_exit_task 1 done
08-25 15:26:22.937  7090  7090 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 15:26:22.937  7090  7090 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 15:26:22.937  7090  7090 I art     : --- WEIRD: removing null entry 248
08-25 15:26:22.937  7090  7090 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 15:26:22.937  7090  7090 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 15:26:22.938  7090  7090 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 15:26:22.940  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-25 15:26:22.943  7090  7090 I art     : System.exit called, status: 0
08-25 15:26:22.943  7090  7090 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 15:26:22.963   311  1377 V AudioFlinger: 7090 died, releasing its sessions
08-25 15:26:22.963   311  1377 V AudioFlinger:  pid 1871 @ 0
08-25 15:26:22.963   311  1377 V AudioFlinger:  pid 3276 @ 1
08-25 15:26:22.963   311  1377 V AudioFlinger:  pid 3276 @ 2
,08-25 15:26:22.967  1958  1958 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-25 15:26:22.970  6968  6968 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 15:26:22.976  1958  2184 D LGBluetoothAPIService: Message: 101
08-25 15:26:22.976  1958  2184 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
,08-25 15:26:22.977  1958  2184 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-25 15:26:22.977  1958  2184 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-25 15:26:23.028  1027  1757 I ActivityManager: Process com.android.bluetooth (pid 7090) has died
08-25 15:26:23.028  1027  1757 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-25 15:26:23.028  1027  1757 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 13999ms
,08-25 15:26:23.037  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:23.038  1958  2184 D LGBluetoothAPIService: Message: 2
08-25 15:26:23.038  1958  2184 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-25 15:26:23.040  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 15:26:23.041  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:23.043  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:23.051  6968  6968 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 15:26:23.052  6968  6968 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 15:26:23.055  6968  6968 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 15:26:23.071  1597  1597 D BluetoothAdapter: 305571086: getState() :  mService = null. Returning STATE_OFF
08-25 15:26:23.071  1597  1597 D BluetoothAdapter: 305571086: getState() :  mService = null. Returning STATE_OFF
,08-25 15:26:23.107  1027  2023 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7762 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 15:26:23.109  6968  6968 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:26:23.183  7762  7762 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 15:26:23.183  7762  7762 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 15:26:23.184  7762  7762 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 15:26:23.185  7762  7762 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 15:26:23.214  7762  7762 D BluetoothAdapterApp: Loading JNI Library
,08-25 15:26:23.250  7762  7762 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@12a97fd5 Instance Count = 1
,08-25 15:26:23.258  7762  7762 D BluetoothAdapterApp: onCreate
08-25 15:26:23.284  7762  7762 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 15:26:23.285  7762  7762 D ProfileConfigQcom: Adding HeadsetService
,08-25 15:26:23.285  7762  7762 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 15:26:23.285  7762  7762 D ProfileConfigQcom: Adding A2dpService
08-25 15:26:23.285  7762  7762 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 15:26:23.285  7762  7762 D ProfileConfigQcom: Adding HidService
08-25 15:26:23.286  7762  7762 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 15:26:23.286  7762  7762 D ProfileConfigQcom: Adding HealthService
08-25 15:26:23.286  7762  7762 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 15:26:23.287  7762  7762 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 15:26:23.287  7762  7762 D ProfileConfigQcom: Adding PanService
08-25 15:26:23.288  7762  7762 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 15:26:23.288  7762  7762 D ProfileConfigQcom: Adding GattService
08-25 15:26:23.288  7762  7762 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 15:26:23.288  7762  7762 D ProfileConfigQcom: Adding BluetoothMapService
08-25 15:26:23.289  7762  7762 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 15:26:23.290  7762  7762 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 15:26:23.291  7762  7762 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:23.291  7762  7762 V BluetoothPbapReceiver: ***********state = 10
08-25 15:26:23.293  7762  7762 V LGMDMManagerInternal: Create singleton instance
08-25 15:26:23.439  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:26:23.450  7762  7762 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 15:26:23.450  7762  7762 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 15:26:23.455  6968  6968 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-25 15:26:23.462  1958  1958 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 15:26:23.463  1958  2184 D LGBluetoothAPIService: Message: 100
08-25 15:26:23.463  1958  2184 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 15:26:23.472  6968  6968 D BluetoothPermissionRequest: onReceive
,08-25 15:26:23.475  6968  6968 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 15:26:23.475  6968  6968 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-25 15:26:23.478  6968  6968 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 15:26:23.483  7762  7762 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 15:26:23.489  7762  7762 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:26:23.494  7762  7762 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 15:26:23.494  7762  7762 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 15:26:23.495  7762  7762 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 15:26:23.496  7762  7762 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:23.497  7762  7762 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 15:26:23.500  7038  7038 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-25 15:26:24.843  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:24.843  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:26:24.906  1027  1457 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 15:26:24.925  1597  1597 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-25 15:26:24.948  2084  2084 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 15:26:25.025  1027  1085 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7790 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 15:26:25.032  1597  1597 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 15:26:25.033  1597  1597 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-25 15:26:25.044  1027  1027 D administrator: Handling package changes for user 0
,08-25 15:26:25.094  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 15:26:25.127  7790  7790 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 15:26:25.190  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-25 15:26:25.190  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 15:26:25.219  7790  7790 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:25.219  7790  7790 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:26:25.256  1027  1084 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 15:26:25.262  1027  1084 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 15:26:25.269  2084  2084 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-25 15:26:25.271  2455  2455 V GmsNetworkLocationProvi: DISABLE
08-25 15:26:25.305  1027  1084 D LocationProviderProxy: applying state to connected service
,08-25 15:26:25.306  2455  2455 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-25 15:26:25.325  7790  7837 I Babel   : MmsConfig: mnc/mcc: 0/0
08-25 15:26:25.326  7790  7837 I Babel   : MmsConfig.loadMmsSettings
08-25 15:26:25.330  7790  7837 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 15:26:25.330  7790  7837 I Babel   : MmsConfig.loadFromDatabase
,08-25 15:26:25.353  7790  7837 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-25 15:26:25.353  7790  7837 I Babel   : MmsConfig.loadFromResources
08-25 15:26:25.355  7790  7837 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-25 15:26:25.355  7790  7837 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 15:26:25.358  7790  7790 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:25.359  7790  7835 W AudioCapabilities: Unsupported mime audio/evrc
08-25 15:26:25.360  7790  7835 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 15:26:25.361  7790  7835 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 15:26:25.377  7790  7835 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-25 15:26:25.378  7790  7835 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 15:26:25.379  7790  7835 W AudioCapabilities: Unsupported mime audio/evrc
08-25 15:26:25.387  7790  7835 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-25 15:26:25.389  1835  7839 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-25 15:26:25.389  1835  7839 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-25 15:26:25.389  7790  7835 W VideoCapabilities: Unsupported mime video/divx
08-25 15:26:25.390  7148  7148 I AppUp4:CustModeStarterReceiver: onReceive
08-25 15:26:25.395  7790  7835 W VideoCapabilities: Unsupported mime video/divx311
08-25 15:26:25.396  7148  7148 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d79d5b7
08-25 15:26:25.396  7148  7148 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 15:26:25.396  7148  7148 D AppUp4:CustFacade: isPhone : true
08-25 15:26:25.396  7148  7148 D AppUp4:CustModeStarterReceiver: begin check event
,08-25 15:26:25.396  7148  7148 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-25 15:26:25.409  7790  7835 W VideoCapabilities: Unsupported mime video/divx4
08-25 15:26:25.411  1835  4682 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-25 15:26:25.417  7790  7835 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-25 15:26:25.432  7790  7835 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-25 15:26:25.436  7790  7835 W AudioCapabilities: Unsupported mime audio/eac3
,08-25 15:26:25.437  7790  7835 W AudioCapabilities: Unsupported mime audio/ac3
08-25 15:26:25.440  1027  1771 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7841 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-25 15:26:25.452  1027  1044 I ActivityManager: Killing 6989:com.lge.sync/1000 (adj 15): empty #17
,08-25 15:26:25.453  7790  7835 W AudioCapabilities: Unsupported mime audio/g726
,08-25 15:26:25.454  7790  7835 W AudioCapabilities: Unsupported mime audio/wma-voice
08-25 15:26:25.455  7790  7835 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 15:26:25.455  7790  7835 W AudioCapabilities: Unsupported mime audio/adpcm
08-25 15:26:25.457  7790  7835 W VideoCapabilities: Unsupported mime video/theora
08-25 15:26:25.458  7790  7835 W VideoCapabilities: Unsupported mime video/mjpg
08-25 15:26:25.461   333   333 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 21.390ms
08-25 15:26:25.473  1027  1537 D WifiService: Client connection lost with reason: 4
,08-25 15:26:25.480   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 18.977ms
08-25 15:26:25.499   333   333 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 18.753ms
,08-25 15:26:25.619  1027  2105 W libprocessgroup: failed to open /acct/uid_1000/pid_6989/cgroup.procs: No such file or directory
08-25 15:26:25.649  7841  7841 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:26:25.649  7841  7841 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 15:26:25.650  7841  7841 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 15:26:25.651  7841  7841 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-25 15:26:25.651  7841  7841 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-25 15:26:25.730  7841  7841 I SystemConfig: BUILD Country: EU
08-25 15:26:25.731  7841  7841 I SystemConfig: BUILD Operator: OPEN
,08-25 15:26:25.805  1027  1734 I ActivityManager: Killing 7199:com.lge.email/u0a23 (adj 15): empty #17
,08-25 15:26:25.853  1027  1982 W libprocessgroup: failed to open /acct/uid_10023/pid_7199/cgroup.procs: No such file or directory
,08-25 15:26:25.901  1027  1734 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7862 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-25 15:26:25.910  7841  7860 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-25 15:26:25.910  7841  7860 I SystemConfig: existFile = false
08-25 15:26:25.910  7841  7860 I SystemConfig: canReadFile = false
08-25 15:26:25.910  7841  7860 I SystemConfig: systemFeature RCS result false
08-25 15:26:25.911  7841  7860 D SystemConfig: refreshRcsSupport() :false
,08-25 15:26:25.975  7862  7862 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 15:26:25.976  7862  7862 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 15:26:25.976  7862  7862 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 15:26:25.977  7862  7862 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 15:26:26.100  7862  7862 I AppConfig: Total System Memory = 2995761152
,08-25 15:26:26.111  7862  7862 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-25 15:26:26.213  1027  2029 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7887 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:26:26.216  1027  2029 I ActivityManager: Killing 7062:com.lge.formmanager/u0a26 (adj 15): empty #17
08-25 15:26:26.268  1027  2105 W libprocessgroup: failed to open /acct/uid_10026/pid_7062/cgroup.procs: No such file or directory
,08-25 15:26:26.475  7887  7887 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 15:26:26.546  7887  7887 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 15:26:26.546  7887  7887 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:26:26.598  7887  7887 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-25 15:26:26.617  7887  7887 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 15:26:26.618  7887  7887 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 15:26:26.633  7887  7887 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-25 15:26:26.633  7887  7887 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-25 15:26:26.651  1027  1982 I ActivityManager: Killing 6544:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-25 15:26:26.737  1027  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_6544/cgroup.procs: No such file or directory
,08-25 15:26:26.758  3389  3911 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-25 15:26:26.762  4597  7930 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-25 15:26:26.767  3389  3911 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@5e9bcab on behalf of 7887
08-25 15:26:26.805  1027  1771 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7931 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-25 15:26:26.831  7887  7887 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-25 15:26:26.847  7887  7887 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-25 15:26:26.907  7931  7931 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-25 15:26:26.933  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-25 15:26:26.933  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-25 15:26:26.933  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-25 15:26:26.933  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-25 15:26:26.933  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-25 15:26:26.933  7931  7931 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-25 15:26:26.956  1027  1757 I ActivityManager: Killing 7240:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-25 15:26:26.986  1027  1734 W libprocessgroup: failed to open /acct/uid_10046/pid_7240/cgroup.procs: No such file or directory
,08-25 15:26:27.191  1027  1771 V SIM_STK : Menu title from STK is T-Mobile
,08-25 15:26:27.218  4597  7930 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 456 ms] updated apps [took 456 ms] 
,08-25 15:26:27.281  7691  7739 D UEI.SmartControl: Internal timer expired: 1
,08-25 15:26:27.281  7691  7739 D UEI.SmartControl: unbind internal service
,08-25 15:26:27.292  7691  7691 D UEI.SmartControl: Service.onUnbind: IControl
,08-25 15:26:27.293  7691  7691 D UEI.SmartControl: Service.onDestroy
,08-25 15:26:27.293  7691  7691 D UEI.SmartControl: Lock is in USE false
08-25 15:26:27.294  7691  7691 D UEI.SmartControl: unbind internal service
08-25 15:26:27.296  7691  7691 D serial_port: close(fd = 25)
,08-25 15:26:27.303  7691  7691 I UEI.SmartControl: Serial port is closed.
,08-25 15:26:27.306  7691  7691 I UEI.SmartControl: Serial port is closed.
08-25 15:26:27.306  7691  7691 D UEI.SmartControl: Blaster closed
08-25 15:26:27.307  7691  7691 D UEI.SmartControl: Shut down QS...
08-25 15:26:27.308  7691  7691 D UEI.SmartControl: Stopping QS lib
,08-25 15:26:27.309  7691  7691 D UEI.SmartControl: QS lib stop result = true
08-25 15:26:27.309  7691  7691 D UEI.SmartControl: Stopped QS lib
08-25 15:26:27.310  7691  7691 D UEI.SmartControl: Stopped file observer...
08-25 15:26:27.310  7691  7691 D UEI.SmartControl: QS shutdown complete
,08-25 15:26:27.853  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,08-25 15:26:27.853  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31e5c331 added. We now have 6 listener(s)
,08-25 15:26:27.854  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-25 15:26:27.869  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:27.869  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29333a16 added. We now have 7 listener(s)
08-25 15:26:27.870  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:27.870  6832  6918 I System.out: IsBluetoothEnabled
08-25 15:26:27.871  1027  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:27.871  1027  1757 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 15:26:27.872  1027  1089 D BluetoothManagerService: Message: 2
08-25 15:26:27.876  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:27.879  1027  2104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:27.879  1027  2104 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 15:26:27.897  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 15:26:27.897  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 15:26:27.898  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 15:26:27.898  1027  1089 D BluetoothManagerService: Message: 1
08-25 15:26:27.898  1027  1089 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 15:26:27.923  1027  1089 D BluetoothManagerService: Message: 20
08-25 15:26:27.924  1027  1089 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3592bd8c:true
,08-25 15:26:27.928  7762  7762 D BluetoothAdapterState: make
08-25 15:26:27.932  7762  7762 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 15:26:27.933  7762  7762 I bluedroid-qcom: init
08-25 15:26:27.934  7762  7961 I BluetoothAdapterState: Entering OffState
08-25 15:26:27.934  7762  7762 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 15:26:27.935  7762  7762 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 15:26:27.935  7762  7762 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 15:26:27.935  7762  7762 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 15:26:27.935  7762  7762 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 15:26:27.937  7762  7762 I bluedroid-qcom: get_profile_interface socket
08-25 15:26:27.937  7762  7762 I bluedroid-qcom: get_profile_interface map_client
,08-25 15:26:27.941  7762  7965 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 15:26:27.932  7964  7964 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:27.932  7964  7964 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:27.950  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 15:26:27.951  1027  1089 D BluetoothManagerService: Message: 40
08-25 15:26:27.951  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,08-25 15:26:27.958  7762  7778 I bluedroid-qcom: config_hci_snoop_log
08-25 15:26:27.959  1027  1089 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 15:26:27.959  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 15:26:27.962  7762  7965 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 15:26:27.966  7964  7964 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 15:26:27.966  7964  7964 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 15:26:27.966  7964  7964 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 15:26:27.968  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 15:26:27.968  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 15:26:27.969  7762  7965 D BluetoothAdapterProperties: Name is: G3
08-25 15:26:27.969  7964  7964 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 15:26:27.974  7964  7964 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 15:26:27.974  7964  7964 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 15:26:27.978  7762  7961 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 15:26:27.978  7762  7961 D BluetoothAdapterProperties: Setting state to 11
08-25 15:26:27.978  7762  7961 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-25 15:26:27.983  7762  7961 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 15:26:27.986  1027  1089 D BluetoothManagerService: Message: 60
08-25 15:26:27.986  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 15:26:27.986  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 15:26:27.991  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:26:27.993  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 15:26:27.997  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:28.000  6968  6968 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 15:26:28.004  7762  7762 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 15:26:28.004  7762  7762 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:28.004  7762  7762 V BluetoothPbapReceiver: ***********state = 11
,08-25 15:26:28.015  7762  7961 D BluetoothBondStateMachine: make
08-25 15:26:28.017  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:26:28.027  7762  7961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:28.028  7762  7961 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 15:26:28.028  7762  7978 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 15:26:28.028  7762  7961 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:28.028  7762  7961 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 15:26:28.029  7762  7961 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-25 15:26:28.033  7762  7961 E BluetoothAdapterService: File transfer profiles supported!!
08-25 15:26:28.034  6968  6968 D BluetoothPermissionRequest: onReceive
08-25 15:26:28.038  6968  6968 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 15:26:28.041  7762  7762 D HeadsetService: Received start request. Starting profile...
08-25 15:26:28.041  7762  7762 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 15:26:28.041  7762  7762 D LGBluetoothHfpAdapter: Version 1.6
08-25 15:26:28.043  7762  7961 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 15:26:28.045  7762  7762 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 15:26:28.047  7762  7762 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 15:26:28.047  7762  7762 D HeadsetStateMachine: make
08-25 15:26:28.048  7762  7961 E BluetoothAdapterService: File transfer profiles supported!!
08-25 15:26:28.054  7762  7961 E BluetoothAdapterService: File transfer profiles supported!!
08-25 15:26:28.060  7762  7961 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 15:26:28.065  7762  7961 E BluetoothAdapterService: File transfer profiles supported!!
08-25 15:26:28.071  7762  7961 E BluetoothAdapterService: File transfer profiles supported!!
08-25 15:26:28.085  7762  7961 V LGMDMManager: Create singleton instance
,08-25 15:26:28.087  7762  7762 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 15:26:28.087  7762  7762 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 15:26:28.088  7762  7961 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 15:26:28.092  7762  7762 D HeadsetStateMachine: max_hf_connections = 1
08-25 15:26:28.092  7762  7762 I bluedroid-qcom: get_profile_interface handsfree
08-25 15:26:28.094  7762  7762 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 15:26:28.095   311  3002 V AudioPolicyService: registerClient() client 0xb0410660, uid 1002
08-25 15:26:28.095   311  1377 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 15:26:28.095   311  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 15:26:28.095   311  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 15:26:28.095  7762  7762 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 15:26:28.096   311   311 V AudioFlinger: registerClient() client 0xb101fc70, pid 7762
08-25 15:26:28.096   311  1369 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:28.096   311  1369 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:28.096  7762  7762 V ToneGenerator: Create Track: 0xb4928a80
08-25 15:26:28.096  7762  7762 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 15:26:28.096  7762  7762 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 15:26:28.096   311  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:28.096   311  1372 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:28.097   311  3002 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 15:26:28.097   311  3002 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 15:26:28.097  1597  2553 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:28.097   311  3002 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 15:26:28.097  1597  2553 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:28.097   311  3002 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 15:26:28.097  7762  7778 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:28.097  7762  7778 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 15:26:28.097  7762  7778 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:28.097  7762  7778 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 15:26:28.097  1597  1616 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:28.097  1597  1616 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:28.097   311   311 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 15:26:28.097  3276  3295 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:28.097  3276  3295 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:28.097  3276  3295 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:28.097  3276  3295 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:28.097   311  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 15:26:28.097   311  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 15:26:28.097   311  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 15:26:28.097   311  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 15:26:28.098  7762  7762 V AudioSystem: getLatency() output 2, latency 50
08-25 15:26:,28.098  7762  7762 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 15:26:28.098  7762  7762 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 15:26:28.098  1027  1043 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 15:26:28.098  1027  1043 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:28.098  1027  1043 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:28.098  1027  1043 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:28.098   311  3002 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 15:26:28.098   311  3002 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 15:26:28.098   311  3002 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 15:26:28.098   311  3002 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 15:26:28.098   311  3002 V AudioFlinger: createTrack() lSessionId: 23
08-25 15:26:28.099  7762  7762 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 15:26:28.099   311  1377 V AudioFlinger: acquiring 23 from 7762, for 7762
08-25 15:26:28.100   311  1377 V AudioFlinger:  added new entry for 23
,08-25 15:26:28.100  1871  1887 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-25 15:26:28.100  7762  7762 V ToneGenerator: ToneGenerator INIT OK, time: 201842
08-25 15:26:28.100  1871  1887 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 15:26:28.100  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:28.100  1871  1887 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 15:26:28.100  1871  1887 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 15:26:28.101  7762  7984 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 15:26:28.101  7762  7984 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 15:26:28.102  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
,08-25 15:26:28.103  7762  7984 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 15:26:28.103  7762  7984 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 15:26:28.104   311   311 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7762
08-25 15:26:28.104   311   311 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 15:26:28.104  7762  7762 D A2dpService: Received start request. Starting profile...
08-25 15:26:28.104   311   311 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 15:26:28.104   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 15:26:28.104   311   311 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 15:26:28.104   311   311 V voice   : voice_set_parameters: exit with code(0)
08-25 15:26:28.104   311   311 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 15:26:28.104   311   311 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 15:26:28.105   311   311 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 15:26:28.105   311   311 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 15:26:28.105   311   311 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 15:26:28.105   311   311 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 15:26:28.105  7762  7984 V ToneGenerator: ToneGenerator destructor
08-25 15:26:28.105  7762  7984 V ToneGenerator: stopTone
08-25 15:26:28.105  7762  7984 V ToneGenerator: Delete Track: 0xb4928a80
08-25 15:26:28.105  7762  7762 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 15:26:28.106   311  1376 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 15:26:28.106   311  1376 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 15:26:28.106   311  1376 V AudioFlinger: PlaybackThread::Track destructor
08-25 15:26:28.106   311  1220 V AudioPolicyService: AudioCommandThread() waking up
08-25 15:26:28.106   311  1376 V AudioFlinger: removeClient_l() pid 7762, calling pid 311
08-25 15:26:28.106   311  1220 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 15:26:28.106   311  1220 V AudioPolicyManager: releaseOutput() 2
08-25 15:26:28.106   311  1220 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 15:26:28.106  7762  7984 V AudioTrack: ~AudioTrack, releasing session id from 7762 on behalf of 7762
08-25 15:26:28.106   311   311 V AudioFlinger: releasing 23 from 7762 for 7762
08-25 15:26:28.106   311   311 V AudioFlinger:  decremented refcount to 0
08-25 15:26:28.106   311   311 V AudioFlinger: purging stale effects
08-25 15:26:28.106  7762  7762 V Avrcp   : make
08-25 15:26:28.107  7762  7762 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 15:26:28.107  7762  7762 I bluedroid-qcom: get_profile_interface avrcp
08-25 15:26:28.107  1027  1568 W Process : Unable to open /proc/7985/status
08-25 15:26:28.116  7762  7762 V AudioManager: registerRemoteController: size of Media player list: 0
08-25 15:26:28.117  7762  7762 E AudioManager: No RCC entry present to update
08-25 15:26:28.117  7762  7762 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 15:26:28.121  7762  7762 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 15:26:28.122  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-25 15:26:28.122  7762  7762 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 15:26:28.126  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 15:26:28.226  1027  2029 V SIM_STK : Menu title from STK is T-Mobile
08-25 15:26:28.226  1027  2029 V SIM_STK : Menu title from STK is T-Mobile
,08-25 15:26:28.299  1027  1568 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 15:26:28.307  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 15:26:28.311  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 15:26:28.312  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 15:26:28.312  7762  7762 I BluetoothA2dpServiceJni: classInitNative
08-25 15:26:28.312  7762  7762 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 15:26:28.312  7762  7762 D A2dpStateMachine: make
08-25 15:26:28.315  7762  7762 I bluedroid-qcom: get_profile_interface a2dp
08-25 15:26:28.315  7762  7991 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 15:26:28.318  7762  7762 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 15:26:28.318  7762  7762 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 15:26:28.319  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:28.320  7762  7762 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 15:26:28.320  7762  7990 D A2dpStateMachine: Enter Disconnected: -2
08-25 15:26:28.322  7762  7762 D HidService: Received start request. Starting profile...
08-25 15:26:28.322  7762  7762 I bluedroid-qcom: get_profile_interface hidhost
08-25 15:26:28.322  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:28.322  7762  7762 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 15:26:28.324  7762  7762 D HealthService: Received start request. Starting profile...
08-25 15:26:28.327  7762  7762 I bluedroid-qcom: get_profile_interface health
08-25 15:26:28.327  7762  7762 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 15:26:28.327  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:28.328  7762  7762 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 15:26:28.329  7762  7762 D PanService: Received start request. Starting profile...
08-25 15:26:28.329  7762  7762 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 15:26:28.329  7762  7762 I bluedroid-qcom: get_profile_interface pan
,08-25 15:26:28.339  7762  7762 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 15:26:28.339  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:28.342  7762  7762 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-25 15:26:28.358  7762  7762 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 15:26:28.358  7762  7762 D BtGatt.GattService: Received start request. Starting profile...
08-25 15:26:28.358  7762  7762 D BtGatt.GattService: start()
,08-25 15:26:28.358  7762  7762 I bluedroid-qcom: get_profile_interface gatt
08-25 15:26:28.359  7762  7762 D BtGatt.AdvertiseManager: advertise manager created
,08-25 15:26:28.375  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:28.380  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
,08-25 15:26:28.381  7762  7762 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-25 15:26:28.384  7762  7762 V BluetoothMapService: BluetoothMapBinder()
08-25 15:26:28.385  7762  7762 D BluetoothMapService: Received start request. Starting profile...
08-25 15:26:28.385  7762  7762 D BluetoothMapService: start()
08-25 15:26:28.392  7762  7762 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 15:26:28.392  7762  7762 D BluetoothMapEmailAppObserver: createReceiver()
,08-25 15:26:28.395  7762  7762 D BluetoothMapEmailAppObserver: initObservers()
08-25 15:26:28.395  7762  7762 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 15:26:28.412  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
,08-25 15:26:28.412  7762  7762 D HeadsetStateMachine: Proxy object connected
08-25 15:26:28.413  7762  7762 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 15:26:28.414  7762  7762 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 15:26:28.418  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 15:26:28.419  7762  7984 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 15:26:28.421  7762  7762 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:28.421  7762  7984 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 15:26:28.422  7762  7984 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 15:26:28.425  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 15:26:28.429  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 15:26:28.432  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 15:26:28.432  7762  7762 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 15:26:28.435  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 15:26:28.439  7762  7762 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-25 15:26:28.439  7762  7762 V BluetoothMapService: Handler(): got msg=1
08-25 15:26:28.440  7762  7762 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 15:26:28.440  7762  7762 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 15:26:28.440  7762  7762 V BluetoothSapReceiver: SapReceiver onReceive 
,08-25 15:26:28.440  7762  7762 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:28.440  7762  7762 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 15:26:28.441  7762  7961 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 15:26:28.442  7762  7961 I bluedroid-qcom: enable
08-25 15:26:28.442  7762  7961 I bt_hci_bdroid: init
08-25 15:26:28.446  7762  7961 I bt_vendor: bt-vendor : init
08-25 15:26:28.447  7762  7961 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 15:26:28.447  7762  7961 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 15:26:28.447  7762  7961 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 15:26:28.447  7762  7961 D bt_userial_mct: userial_init
08-25 15:26:28.448  7762  7961 D bt_hci_bdroid: set_power 1
08-25 15:26:28.448  7762  7961 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 15:26:28.448  7762  7961 I bt_vendor: Starting hciattach daemon
08-25 15:26:28.448  7762  7961 I bt_vendor: try to set true
,08-25 15:26:28.449  7762  8001 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 15:26:28.449  7762  8001 I bt-btu  : btu_task pending for preload complete event
08-25 15:26:28.442  8004  8004 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:28.442  8004  8004 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 15:26:28.489  8005  8005 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 15:26:28.563  8011  8011 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 15:26:28.582  8012  8012 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 15:26:28.623  8014  8014 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 15:26:28.649  8015  8015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 15:26:28.668  8016  8016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 15:26:28.683  8017  8017 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 15:26:28.717  8019  8019 I libmdmdetect: ESOC framework not supported
,08-25 15:26:28.719  8019  8019 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-25 15:26:28.731  8019  8019 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 15:26:28.731  8019  8019 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 15:26:28.731  8019  8019 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 15:26:28.731  8019  8019 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 15:26:28.731  8019  8019 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 15:26:28.731  8019  8019 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 15:26:28.731  8019  8019 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-25 15:26:28.773  8019  8022 E QC-QMI  : qmi_client [8019] 15: failed to locate client data
,08-25 15:26:28.789   444   444 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 15:26:28.789   444   444 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-25 15:26:28.824  8027  8027 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 15:26:28.841  8028  8028 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 15:26:28.856  7762  7961 I bt_vendor: bluetooth satus is on
08-25 15:26:28.856  7762  7961 D bt_hci_bdroid: preload
,08-25 15:26:28.859  7762  8003 D bt_userial_mct: userial_open(port:0)
08-25 15:26:28.859  7762  8003 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-25 15:26:28.866  7762  8003 I bt_vendor: Done intiailizing UART
08-25 15:26:28.867  7762  8003 I bt_vendor: Done intiailizing UART
08-25 15:26:28.867  7762  8003 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 15:26:28.867  7762  8003 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 15:26:28.868  7762  8001 I bt-btu  : btu_task received preload complete event
08-25 15:26:28.868  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 15:26:28.868  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 15:26:28.872  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 15:26:28.875  7762  8030 D bt_userial_mct: Entering userial_read_thread()
,08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 15:26:28.877  7762  8001 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 15:26:28.985  7762  8001 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-25 15:26:28.986  7762  8001 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01d7061 ,
08-25 15:26:28.986  7762  8001 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01d7061 ,
,08-25 15:26:29.022  7762  7965 E bt-btif : Calling BTA_HhEnable
08-25 15:26:29.022  7762  7965 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 15:26:29.022  7762  7965 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 15:26:29.026  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 15:26:29.026  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 15:26:29.026  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 15:26:29.026  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 15:26:29.026  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 15:26:29.029  7762  7965 D BluetoothAdapterProperties: Name is: G3
08-25 15:26:29.031  7762  7965 D BluetoothAdapterProperties: Scan Mode:20
08-25 15:26:29.031  7762  7965 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 15:26:29.032  7762  7965 D bt_hci_bdroid: postload
08-25 15:26:29.032  7762  8003 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 15:26:29.033  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 15:26:29.033  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 15:26:29.034  7762  8001 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 15:26:29.034  7762  7965 D bte_conf: Device ID record 1 : primary
08-25 15:26:29.035  7762  7965 D bte_conf:   vendorId            = 00c4
08-25 15:26:29.035  7762  7965 D bte_conf:   vendorIdSource      = 0001
08-25 15:26:29.035  7762  7965 D bte_conf:   product             = 13a1
08-25 15:26:29.035  7762  7965 D bte_conf:   version             = 1000
08-25 15:26:29.035  7762  7965 D bte_conf:   clientExecutableURL = 
08-25 15:26:29.035  7762  7965 D bte_conf:   serviceDescription  = 
08-25 15:26:29.035  7762  7965 D bte_conf:   documentationURL    = 
08-25 15:26:29.035  7762  7965 D bte_conf: bte_load_did_conf no section named DID2.
,08-25 15:26:29.040  7762  8001 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:29.040  7762  8001 W bt-smp  : Plain text(LSB ~ MSB) = dd 3a 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:29.040  7762  8001 W bt-smp  : Encrypted text(LSB ~ MSB) = fb f2 9b 60 04 1f 98 38 3c 45 9f 4e 7d 9b bc 92 
08-25 15:26:29.040  7762  8003 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 15:26:29.040  7762  8001 W bt-btm  : Stopping oneshot timer
08-25 15:26:29.043  7762  8003 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 15:26:29.044  7762  7961 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 15:26:29.044  7762  7961 D BluetoothAdapterProperties: ScanMode =  20
08-25 15:26:29.044  7762  7961 D BluetoothAdapterProperties: State =  11
08-25 15:26:29.044  7762  7961 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 15:26:29.045  7762  7961 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 15:26:29.045  7762  7961 D BluetoothAdapterProperties: Setting state to 12
08-25 15:26:29.045  7762  7961 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 15:26:29.045  7762  7965 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 15:26:29.046  7762  7965 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 15:26:29.042  8032  8032 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 15:26:29.042  8032  8032 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:29.058  1027  1089 D BluetoothManagerService: Message: 60
08-25 15:26:29.058  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 15:26:29.059  7762  7961 I BluetoothAdapterState: Entering On State
08-25 15:26:29.066  7762  8003 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 15:26:29.070  7762  8030 E bt_mct  : hci lib postload completed
08-25 15:26:29.080  7762  7961 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 15:26:29.080  7762  7961 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 15:26:29.080  7762  7961 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-25 15:26:29.083  7762  7961 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 15:26:29.084  7762  8001 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:29.084  7762  8001 W bt-smp  : Plain text(LSB ~ MSB) = 81 d0 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:29.084  7762  8001 W bt-smp  : Encrypted text(LSB ~ MSB) = c5 8b e5 3b 69 10 7f 3f d0 b3 22 da da 86 3a ae 
08-25 15:26:29.084  7762  8001 W bt-btm  : Stopping oneshot timer
08-25 15:26:29.094  7762  7965 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 15:26:29.094  7762  7965 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-25 15:26:29.096  1027  1089 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-25 15:26:29.097  1871  4437 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:26:29.108  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:29.108  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:29.108  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:29.108  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:29.108  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:29.108  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:29.108  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:29.108  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:26:29.110  7762  7961 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-25 15:26:29.113  7762  8001 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:29.113  7762  8001 W bt-smp  : Plain text(LSB ~ MSB) = c5 8f 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:29.113  7762  8001 W bt-smp  : Encrypted text(LSB ~ MSB) = 19 66 00 85 a8 28 03 ab 16 89 5a 2f cd 5c 27 a2 
08-25 15:26:29.113  7762  8001 W bt-btm  : Stopping oneshot timer
08-25 15:26:29.122  7762  8001 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:29.122  7762  8001 W bt-smp  : Plain text(LSB ~ MSB) = 98 51 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:29.122  7762  8001 W bt-smp  : Encrypted text(LSB ~ MSB) = fa fe 17 fe fd 29 db 02 14 f2 49 f7 da c0 94 b3 
,08-25 15:26:29.125  7762  8001 W bt-btm  : Stopping oneshot timer
08-25 15:26:29.125  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:29.145  1871  1871 D BluetoothHeadset: Proxy object connected
,08-25 15:26:29.148  7762  8001 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 15:26:29.148  7762  8001 W bt-smp  : Plain text(LSB ~ MSB) = 5f 7d 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 15:26:29.148  7762  8001 W bt-smp  : Encrypted text(LSB ~ MSB) = cf a1 12 fa 6e f4 ec b5 b7 27 ff a5 3a 7e c2 6f 
08-25 15:26:29.148  7762  8001 W bt-btm  : Stopping oneshot timer
08-25 15:26:29.149  1871  1887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:26:29.163  1871  1871 D BluetoothHeadset: Proxy object connected
,08-25 15:26:29.168  6968  7657 D BluetoothPan: onBluetoothStateChange on: true
08-25 15:26:29.168  6968  7657 D BluetoothPan: onBluetoothStateChange call bindService
08-25 15:26:29.176  8037  8037 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-25 15:26:29.186  6968  6983 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 15:26:29.192  6968  7657 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 15:26:29.199  1027  1089 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:26:29.200  1027  1027 D BluetoothHeadset: Proxy object connected
08-25 15:26:29.201  1871  2475 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 15:26:29.204  1871  1871 D BluetoothHeadset: Proxy object connected
,08-25 15:26:29.207  6968  6983 D BluetoothMap: onBluetoothStateChange: up=true
08-25 15:26:29.209  6968  6968 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 15:26:29.209  6968  6968 D PanProfile: Bluetooth service connected
08-25 15:26:29.211  1027  1089 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 15:26:29.213  1027  1027 D BluetoothA2dp: Proxy object connected
08-25 15:26:29.215  6968  6984 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 15:26:29.217  6968  6983 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 15:26:29.223  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 15:26:29.224  1027  1089 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 15:26:29.224  1027  1089 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-25 15:26:29.229  1958  1958 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:26:29.232  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 15:26:29.233  1958  2184 D LGBluetoothAPIService: Message: 1
08-25 15:26:29.233  1958  2184 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 15:26:29.233  1958  2184 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-25 15:26:29.233  1958  2184 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-25 15:26:29.238  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:29.246  7762  7762 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:29.246  7762  7762 D BluetoothMapService: STATE_ON
08-25 15:26:29.246  7762  7762 V BluetoothMapService: Handler(): got msg=1
,08-25 15:26:29.250  7762  7762 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 15:26:29.268  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:29.268  7762  7762 V BluetoothPbapService: Pbap Service onCreate
08-25 15:26:29.268  7762  7762 V BluetoothPbapService: Starting PBAP service
,08-25 15:26:29.272  7762  7762 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
,08-25 15:26:29.272  7762  7762 V BluetoothPbapService: Handler(): got msg=1
08-25 15:26:29.273  7762  7762 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 15:26:29.274  6968  6968 D BluetoothInputDevice: Proxy object connected
08-25 15:26:29.274  6968  6968 D HidProfile: Bluetooth service connected
08-25 15:26:29.275  7762  7762 V BluetoothPbapService: Pbap Service onBind
08-25 15:26:29.282  6968  6968 D BluetoothHeadset: Proxy object connected
08-25 15:26:29.282  6968  6968 D HeadsetProfile: Bluetooth service connected
08-25 15:26:29.285  6968  6968 D BluetoothMap: Proxy object connected
08-25 15:26:29.286  6968  6968 D MapProfile: Bluetooth service connected
08-25 15:26:29.286  6968  6968 D BluetoothMap: getConnectedDevices()
08-25 15:26:29.288  7762  7779 V BluetoothMapService: getConnectedDevices()
,08-25 15:26:29.298  7762  8040 V BluetoothPbapService: Pbap Service initSocket
08-25 15:26:29.300  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:29.302  7762  8040 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:29.304  6968  6968 D BluetoothA2dp: Proxy object connected
08-25 15:26:29.304  6968  6968 D A2dpProfile: Bluetooth service connected
,08-25 15:26:29.307  7762  8040 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 15:26:29.308  7762  8040 V BluetoothPbapService: Succeed to create listening socket 
08-25 15:26:29.308  7762  8040 V BluetoothPbapService: Accepting socket connection...
08-25 15:26:29.315  1027  1089 D BluetoothManagerService: Message: 40
08-25 15:26:29.315  1027  1089 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 15:26:29.318  7762  8039 D BluetoothMapMasInstance: MAS initSocket()
08-25 15:26:29.319  7762  8039 D BluetoothMapMasInstance:   masId = 00
08-25 15:26:29.319  7762  8039 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 15:26:29.319  7762  8039 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 15:26:29.319  7762  8039 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-25 15:26:29.321  1027  2022 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:29.448  1027  2105 I art     : Explicit concurrent mark sweep GC freed 27770(1372KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.702ms total 171.661ms
,08-25 15:26:29.450  7762  7965 D BluetoothAdapterProperties: Scan Mode:21
08-25 15:26:29.450  7762  7965 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 15:26:29.456  7762  8039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:29.461  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:29.468  7762  7762 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:29.468  7762  8039 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 15:26:29.468  7762  7762 V BluetoothPbapService: state: 12
08-25 15:26:29.468  7762  8039 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 15:26:29.468  7762  8039 D BluetoothMapMasInstance: Accepting socket connection...
08-25 15:26:29.469  6968  6968 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 15:26:29.470  6968  6968 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 15:26:29.475  6968  6968 D BluetoothPbap: Proxy object connected
08-25 15:26:29.475  6968  6968 D PbapServerProfile: Bluetooth service connected
,08-25 15:26:29.478  7762  7762 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 15:26:29.478  7762  7762 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:29.478  7762  7762 V BluetoothPbapReceiver: ***********state = 12
08-25 15:26:29.484  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 15:26:29.485  2237  2237 D c       : Getting all permits...
08-25 15:26:29.485  2237  2237 D a       : Opening database...
08-25 15:26:29.488  6968  6968 D DockEventReceiver: finishStartingService: stopping service
08-25 15:26:29.489  2237  2237 D a       : Opening database auth.proximity.permit_store...
,08-25 15:26:29.490  2237  2237 D a       : Closing database...
08-25 15:26:29.521  6968  6968 D BluetoothPermissionRequest: onReceive
,08-25 15:26:29.524  6968  6968 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 15:26:29.526  6968  6968 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 15:26:29.532  7762  7762 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 15:26:29.533  7762  7762 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-25 15:26:29.544  7762  7762 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-25 15:26:29.578  7762  7762 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 15:26:29.579  7762  7762 V BtOppService: onCreate
,08-25 15:26:29.584  7762  7762 V BluetoothOppNotification: send message
,08-25 15:26:29.588  7762  7762 V BtOppService: Starting RfcommListener
08-25 15:26:29.598  7762  7762 D BluetoothOppPreference: Dumping Names:  
08-25 15:26:29.598  7762  7762 D BluetoothOppPreference: {}
,08-25 15:26:29.599  7762  7762 D BluetoothOppPreference: Dumping Channels:  
08-25 15:26:29.599  7762  7762 D BluetoothOppPreference: {}
08-25 15:26:29.600  7762  7762 V BtOppService: onStartCommand
,08-25 15:26:29.608  7762  8065 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 15:26:29.610  7762  7762 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:29.610  7762  7762 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 15:26:29.613  7762  7762 V BluetoothOppNotification: new notify threadi!
,08-25 15:26:29.614  7762  7762 V BluetoothOppNotification: send delay message
08-25 15:26:29.615  7762  7762 V BtOppService: start RfcommListener
08-25 15:26:29.618  7762  8062 V BtOppService: Deleted complete outbound shares, number =  0
08-25 15:26:29.618  7762  8065 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 15:26:29.620  7762  8062 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 15:26:29.620  7762  8065 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@214f829e on behalf of 
08-25 15:26:29.621  7762  8062 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 15:26:29.622  7762  8062 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cdaf17f on behalf of 
08-25 15:26:29.622  7762  7762 V BtOppService: RfcommListener started
08-25 15:26:29.625  7762  8067 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 15:26:29.626  7762  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 15:26:29.626  1027  2104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:29.627  7762  8067 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:29.628  7762  8067 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
,08-25 15:26:29.629  7762  8067 V BtOppRfcommListener: Started RFCOMM listener....
08-25 15:26:29.629  7762  8067 I BtOppRfcommListener: Accept thread started.
08-25 15:26:29.629  7762  8067 V BtOppRfcommListener: Accepting connection...
08-25 15:26:29.630  7762  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3607b54c on behalf of 
08-25 15:26:29.631  7762  8066 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 15:26:29.631  7762  8065 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 15:26:29.633  7762  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 15:26:29.634  7762  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f4d8995 on behalf of 
08-25 15:26:29.638  7762  8066 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-25 15:26:29.646  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:29.646  7762  7762 V BluetoothFtpService: Ftp Service onCreate
08-25 15:26:29.646  7762  7762 I BluetoothFtpService: Ftp Service onCreate
08-25 15:26:29.646  7762  7762 V BluetoothFtpService: Ftp Service onStartCommand
08-25 15:26:29.646  7762  7762 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:29.646  7762  7762 V BluetoothFtpService: Starting Listening on sockets
08-25 15:26:29.647  7762  7762 V BtOppService: ContentObserver received notification
08-25 15:26:29.647  7762  7762 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 15:26:29.647  7762  7762 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 15:26:29.647  7762  7762 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 15:26:29.647  7762  7762 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:26:29.647  7762  7762 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 15:26:29.648  7762  7762 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 15:26:29.648  7762  8066 V BluetoothOppNotification: outbound notification was removed.
08-25 15:26:29.648  7762  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 15:26:29.650  7762  7762 V BtOppService: ContentObserver received notification
08-25 15:26:29.650  7762  7762 V BluetoothFtpService: Handler(): got msg=1
08-25 15:26:29.650  7762  7762 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 15:26:29.651  7762  7762 V BluetoothFtpService: Ftp Service initSocket
08-25 15:26:29.651  7762  8068 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 15:26:29.651  7762  8068 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 15:26:29.652  7762  8068 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9b7269b on behalf of 
08-25 15:26:29.653  1027  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 15:26:29.655  7762  7762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:29.655  7762  8068 V BluetoothOppNotification: update too frequent, put in queue
08-25 15:26:29.656  7762  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27a0da38 on behalf of 
08-25 15:26:29.657  7762  8068 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 15:26:29.658  7762  7762 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-25 15:26:29.658  7762  8066 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 15:26:29.659  7762  7762 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 15:26:29.663  7762  8069 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 15:26:29.668  7762  8066 V BluetoothOppNotification: inbound notification was removed.
08-25 15:26:29.668  7762  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 15:26:29.670  7762  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@214a2a11 on behalf of 
,08-25 15:26:29.694  7762  7762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2175a642
08-25 15:26:29.694  7762  7762 V BluetoothSapService: Sap Service onCreate
,08-25 15:26:29.698  7762  7762 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:26:29.698  7762  7762 V BluetoothSapService: state: 12
08-25 15:26:29.698  7762  7762 V BluetoothSapService: Starting SAP server process
08-25 15:26:29.701  7762  7762 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 15:26:29.692  8070  8070 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:29.692  8070  8070 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:29.703  7762  8071 V BluetoothSapService: Sap Service initRfcommSocket
08-25 15:26:29.703  1027  2104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:29.704  7762  8071 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:26:29.705  7762  8071 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-25 15:26:29.706  7762  8071 V BluetoothSapService: Succeed to create listening socket 
08-25 15:26:29.706  7762  8071 V BluetoothSapService: Accepting socket connection...
08-25 15:26:29.714  8070  8070 V BT_SAP  : Event pipe created
08-25 15:26:29.714  8070  8070 V BT_SAP  : create_server_socket qcom.sap.server
,08-25 15:26:29.714  8070  8070 V BT_SAP  : created socket fd 6
,08-25 15:26:29.927  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:29.927  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:29.927  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:29.927  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:26:29.927  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:29.927  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:29.927  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:29.927  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:26:29.933  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:29.938  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:29.938  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29869f97 added. We now have 8 listener(s)
08-25 15:26:29.938  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:29.950  1027  1982 D WifiServiceImplEx: setWifiEnabled: false pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 15:26:29.950  1027  1982 D WifiService: setWifiEnabled: false pid=6832, uid=10118
08-25 15:26:29.950  1027  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 15:26:29.962  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:29.964  1027  1043 D WifiServiceImplEx: setWifiEnabled: true pid=6832, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 15:26:29.965  1027  1043 D WifiService: setWifiEnabled: true pid=6832, uid=10118
08-25 15:26:29.965  1027  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 15:26:29.982  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-25 15:26:29.982  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-25 15:26:29.982  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-25 15:26:29.984  1027  1532 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 15:26:29.984  1027  1532 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 15:26:29.987  1027  1532 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 15:26:29.987  1027  1532 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 15:26:29.987  1027  1532 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 15:26:29.987  1027  1532 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 15:26:29.988  1027  1532 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 15:26:29.988  1027  1532 E WifiHW  : unknown target_country: EU , set to default
,08-25 15:26:29.988  1027  1532 E WifiHW  : [wifi_ensure_config_files] default country1 = GB,
08-25 15:26:29.988  1027  1532 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 15:26:29.988  1027  1532 I WifiUtil: gEnableBmps=1
,08-25 15:26:30.616  7762  7762 V BluetoothOppNotification: new notify threadi!
,08-25 15:26:30.634  7762  7762 V BluetoothOppNotification: send delay message
08-25 15:26:30.648  7762  8090 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-25 15:26:30.664  7762  8090 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2196564d on behalf of 
08-25 15:26:30.665  7762  8090 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 15:26:30.701   305   886 D SoftapController: Softap fwReload - Ok
,08-25 15:26:30.741  1027  1532 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (750ms)
,08-25 15:26:30.745  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:26:30.745  1027  1089 D Tethering: InitialState.processMessage what=4
08-25 15:26:30.746  1027  1089 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:26:30.759   305   886 D CommandListener: Setting iface cfg
08-25 15:26:30.759   305   886 D CommandListener: Trying to bring down wlan0
,08-25 15:26:30.763   305   886 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:26:30.766  1027  1532 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 15:26:30.762  8092  8092 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 15:26:30.782  8092  8092 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:30.789  1027  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 15:26:30.789  1027  1532 E WifiStateMachine: useWiFiOffloading() : false
08-25 15:26:30.789  1027  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 15:26:30.831  1027  1532 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 15:26:30.831  1027  1532 D WifiMonitor: connecting to supplicant
08-25 15:26:30.834  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:30.836  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 15:26:30.836  8092  8092 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 15:26:30.844  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 15:26:30.844  7762  8090 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 15:26:30.845  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:30.846  7762  8090 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27dc6502 on behalf of 
08-25 15:26:30.847  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 15:26:30.847  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 15:26:30.847  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 15:26:30.847  6968  6968 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 15:26:30.847  7762  8090 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 15:26:30.847  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 15:26:30.849  6968  6968 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 15:26:30.849  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 15:26:30.849  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 15:26:30.849  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 15:26:30.849  6968  6968 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 15:26:30.849  6968  6968 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 15:26:30.851  7762  8090 V BluetoothOppNotification: outbound notification was removed.
08-25 15:26:30.852  7762  8090 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 15:26:30.854  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 15:26:30.854  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 15:26:30.854  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 15:26:30.854  6968  6968 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 15:26:30.856  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 15:26:30.857  7762  8090 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@129ce13 on behalf of 
08-25 15:26:30.857  6968  6968 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 15:26:30.857  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 15:26:30.857  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 15:26:30.857  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 15:26:30.857  6968  6968 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 15:26:30.858  6968  6968 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 15:26:30.860  7762  8090 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-25 15:26:30.862  7762  8090 V BluetoothOppNotification: inbound notification was removed.
08-25 15:26:30.862  7762  8090 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 15:26:30.864  7762  8090 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3148b850 on behalf of 
08-25 15:26:30.872  8092  8092 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 15:26:30.873  8092  8092 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 15:26:30.898  1027  2029 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8109 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 15:26:30.956  8092  8092 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 15:26:31.004  8092  8092 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 15:26:31.016  8092  8092 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 15:26:31.017  8092  8092 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 15:26:31.019  1027  1532 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 15:26:31.021  1027  1532 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 15:26:31.022  1027  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
,08-25 15:26:31.022  1027  8130 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 15:26:31.022  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 15:26:31.022  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 15:26:31.022  1027  1532 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 15:26:31.022  1027  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 15:26:31.022  1027  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 15:26:31.023  1027  1532 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 15:26:31.025  1027  1532 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:31.026  1027  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-25 15:26:31.027  1027  1532 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 15:26:31.028  1027  1532 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 15:26:31.030  1027  1532 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 15:26:31.030  1027  1532 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 15:26:31.030  1027  1532 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 15:26:31.032  1027  1979 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8131 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 15:26:31.034  1027  1532 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 15:26:31.034  1027  1532 E WifiStateMachine: useWiFiOffloading() : false
08-25 15:26:31.034  1027  1532 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 15:26:31.034  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.034  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.034  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.035  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.035  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 15:26:31.037  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.037  1027  1532 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 15:26:31.038  1027  1532 D WifiNative-wlan0: SET update_config 1: returned true
08-25 15:26:31.038  1027  1532 D WifiConfigStore: Loading config and enabling all networks 
08-25 15:26:31.038  1027  1532 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 15:26:31.040  1958  1958 D WfdService: Waiting for WifiP2p enabling
,08-25 15:26:31.045  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:31.045  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:31.045  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:31.045  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:31.045  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:31.045  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:26:31.045  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:26:31.045  6832  6832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:26:31.046  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-25 15:26:31.046  1027  1536 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 15:26:31.046  1027  1532 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 15:26:31.048  6832  6832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:26:31.049  8109  8128 W FormManager: Network not available. Please check & try again.
08-25 15:26:31.054  1027  1532 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-25 15:26:31.060  8109  8129 V FormManager: Network unavailable.
08-25 15:26:31.062  8109  8129 V FormManager: Network unavailable.
,08-25 15:26:31.063  1027  1532 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-25 15:26:31.063  1027  1532 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 15:26:31.065  1027  1532 D WifiStateMachine: enableVerboseLogging : level 2
08-25 15:26:31.065  1027  1532 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 15:26:31.066  1027  1532 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 15:26:31.066  1027  1532 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 15:26:31.066  1027  1532 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 15:26:31.066  1027  1532 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 15:26:31.067  1027  1532 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 15:26:31.067  1027  1532 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 15:26:31.067  1027  1532 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 15:26:31.067  1027  1532 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 15:26:31.068  1027  1532 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 15:26:31.068  1027  1532 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 15:26:31.068  1027  1532 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 15:26:31.068  1027  1532 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 15:26:31.069  1027  1532 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 15:26:31.070  1958  1958 D WfdsService: Supplicant Connection state is changed : true
08-25 15:26:31.070  1958  2313 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 15:26:31.070  1958  2313 D WfdsService: Set the WFDS Monitor: true
08-25 15:26:31.070  1958  2313 D WfdsMonitor: WfdsMonitorThread create
08-25 15:26:31.071  1958  2313 D WfdsMonitor: WFDS Monitor is created and started
08-25 15:26:31.071  1958  2313 D WfdsService: WiFi: Supplicant connection re-established
08-25 15:26:31.071  7790  7790 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:26:31.072  1027  1532 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 15:26:31.072  1027  1532 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 15:26:31.072  1027  1532 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 15:26:31.072  1027  1532 D WifiNative-HAL: Setting external_sim to 1
08-25 15:26:31.072  1027  1532 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 15:26:31.073  1027  1532 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 15:26:31.073  1027  1532 I WifiNative-HAL: startHal
08-25 15:26:31.073  1027  1532 D wifi    : setting scan oui 0xaf6d1e80
08-25 15:26:31.073  1958  8150 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 15:26:31.074  1027  1532 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 15:26:31.074  1027  1532 I WifiNative-HAL: startHal
08-25 15:26:31.074  1958  8150 E CtrlSupplicant: Succeed to open control connection
08-25 15:26:31.074  1027  1532 D wifi    : setting scan oui 0xaf6d1e80
08-25 15:26:31.074  1027  1532 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 15:26:31.074  1958  8150 E CtrlSupplicant: Succeed to open monitor connection
08-25 15:26:31.075  1958  8150 D WfdsMonitor: Supplicant connection established
08-25 15:26:31.075  1958  2313 D WfdsService: Connected to the supplicant for wfds
08-25 15:26:31.075  1027  1532 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 15:26:31.075  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 15:26:31.075  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 15:26:31.076  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 15:26:31.076  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 15:26:31.076  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 15:26:31.077  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 15:26:31.077  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 15:26:31.078  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 15:26:31.079  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 15:26:31.079  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 15:26:31.080  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 15:26:31.080  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 15:26:31.080  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 15:26:31.080  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 15:26:31.081  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 15:26:31.081  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 15:26:31.081  8092  8092 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-25 15:26:31.081  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 15:26:31.081  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 15:26:31.081  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 15:26:31.082  1027  1532 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 15:26:31.083  1027  1532 E WifiNative: : [204,811,264 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 15:26:31.083  1027  1532 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 15:26:31.083  1027  1532 D WifiNative-wlan0: RECONNECT: returned true
08-25 15:26:31.083  1027  1532 D WifiNative-wlan0: doString: [STATUS]
08-25 15:26:31.084  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 15:26:31.084  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 15:26:31.084  1027  1532 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 15:26:31.084  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 15:26:31.085  1027  1982 I ActivityManager: Killing 7260:com.android.chrome/u0a57 (adj 15): empty #17
08-25 15:26:31.085  1027  1532 D WifiNative-wlan0: SET ps 1: returned true
08-25 15:26:31.085  1027  1530 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:26:31.087   305   886 D CommandListener: Setting iface cfg
,08-25 15:26:31.088   305   886 D CommandListener: Trying to bring up p2p0
08-25 15:26:31.088  1027  1530 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 15:26:31.088  1027  1530 D LGWifiP2pService: P2pEnablingState
08-25 15:26:31.088  1027  1530 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.088  1027  1530 D LGWifiP2pService: P2p socket connection successful
08-25 15:26:31.088  1027  1530 D LGWifiP2pService: P2pEnabledState
08-25 15:26:31.120  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 15:26:31.128  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 15:26:31.129  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-25 15:26:31.129  1027  1549 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.129  1027  1549 I WifiNative-HAL: startHal
,08-25 15:26:31.129  1027  1549 D wifi    : getting scan capabilities on interface[1] = 0xaf6d1e80
08-25 15:26:31.129  1027  1549 D wifi    : failed to get capabilities : -3
08-25 15:26:31.129  1027  1549 E WifiScanningService: could not get scan capabilities
08-25 15:26:31.129  1027  1530 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 15:26:31.129  1027  1532 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 15:26:31.129  1027  1550 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.129  1027  1532 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 15:26:31.130  1027  1532 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 15:26:31.130  1958  1958 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 15:26:31.130  1027  1532 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 15:26:31.130  1958  1958 D WfdsService: WifiP2pState is changed : true
08-25 15:26:31.130  1958  2313 D WfdsService: Receive the WFDS_ENABLE Method
08-25 15:26:31.130  1958  2313 D WfdsService: Set the WFDS Monitor: true
08-25 15:26:31.130  1958  2313 D WfdsService: Connected to the supplicant for wfds
08-25 15:26:31.130  1958  2313 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 15:26:31.130  8092  8092 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 15:26:31.131  1027  1532 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 15:26:31.131  1958  2313 D WfdsService: selectPreferredScanChannel [36]
08-25 15:26:31.131  1958  2313 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 15:26:31.131  1027  1532 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 15:26:31.132  1027  1532 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 15:26:31.132  1027  1532 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 15:26:31.132  8092  8092 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 15:26:31.132  1027  1532 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 15:26:31.132  1027  1532 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 15:26:31.133  1027  1532 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 15:26:31.133  1027  1532 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-25 15:26:31.133  8092  8092 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 15:26:31.133  1027  1532 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 15:26:31.134  1027  1532 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 15:26:31.134  1027  1979 W libprocessgroup: failed to open /acct/uid_10057/pid_7260/cgroup.procs: No such file or directory
08-25 15:26:31.134  1027  1532 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 15:26:31.134  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 15:26:31.134  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 15:26:31.135  8092  8092 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:31.135  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 15:26:31.135  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:31.135  1027  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:31.135  1027  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:31.135  8092  8092 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 15:26:31.135  8092  8092 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.136  8092  8092 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.136  1958  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:31.136  1958  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:31.136  1027  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:31.137  1027  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.137  1027  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.137  1027  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.137  1027  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:31.137  1027  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.137  1027  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.137  1027  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.137  1027  1532 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 15:26:31.137  1027  1532 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 15:26:31.138  1027  1532 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 15:26:31.138  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 15:26:31.138  1027  1532 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 15:26:31.138  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 15:26:31.138  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 15:26:31.138  8092  8092 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 15:26:31.139  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 15:26:31.139  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 15:26:31.139  1027  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 15:26:31.139  1027  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 15:26:31.140  1027  1532 D WifiNativ,e-wlan0: DRIVER SETBAND 0: returned true
08-25 15:26:31.140  1027  1532 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 15:26:31.140  1027  1532 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 15:26:31.140  1027  1532 D WifiNative-wlan0: doBoolean: SCAN
08-25 15:26:31.140  1027  1532 D WifiNative-wlan0: SCAN: returned false
08-25 15:26:31.141  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=204869  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 15:26:31.142  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:31.146  1027  1530 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 15:26:31.146  1027  1530 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 15:26:31.146  1027  1530 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 15:26:31.147  1958  1958 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 15:26:31.148  1958  1958 D WfdsService: isConnected: false
08-25 15:26:31.148  1027  1771 I ActivityManager: Killing 7278:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 15:26:31.149  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.149  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.149  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:31.149  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.149  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 15:26:31.149  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=204878  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 15:26:31.150  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:31.152  1027  1532 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:31.152  1027  1532 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:31.152  1027  1530 D WifiNative-p2p0: SET device_name G3: returned true
08-25 15:26:31.152  1027  1530 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 15:26:31.152  1027  1530 D LGWifiP2pService: before postfix = G3
08-25 15:26:31.152  1027  1530 D WifiServerServiceExt: postfix byte check : 2
08-25 15:26:31.152  1027  1530 D LGWifiP2pService: after postfix = G3
08-25 15:26:31.152  1027  1530 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 15:26:31.152  1027  1532 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:31.152  1027  1530 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 15:26:31.153  1027  1532 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:31.153  1027  1530 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 15:26:31.153  1027  1530 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 15:26:31.153  1027  1530 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 15:26:31.153  1027  1530 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 15:26:31.153  1027  1530 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 15:26:31.153  1027  1532 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 15:26:31.153  1027  1530 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 15:26:31.154  1027  1530 D WifiNative-HAL: p2pGetDeviceAddress
08-25 15:26:31.154  1027  1530 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 15:26:31.180  1027  2022 W libprocessgroup: failed to open /acct/uid_10062/pid_7278/cgroup.procs: No such file or directory
08-25 15:26:31.180  1027  1530 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 15:26:31.180  1027  1530 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 15:26:31.181  1027  1530 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 15:26:31.181  1027  1530 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 15:26:31.182  1027  1530 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 15:26:31.182  1027  1530 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,08-25 15:26:31.182  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:31.182  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 15:26:31.184  1958  1958 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 15:26:31.184  1958  1958 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 15:26:31.184  1958  1958 D WfdsService: Update P2p Interface State: 3
08-25 15:26:31.185  1027  1530 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 15:26:31.185  1027  1530 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 15:26:31.194  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 15:26:31.200  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 15:26:31.200  1027  1530 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 15:26:31.200  1027  1530 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 15:26:31.203  1027  1530 D LGWifiP2pService: InactiveState
08-25 15:26:31.204  1027  1530 D LGWifiP2pService: InactiveState{ when=-67ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.204  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-67ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.204  1027  1530 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 15:26:31.205  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 15:26:31.205  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:31.206  8092  8092 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:31.207  1027  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 15:26:31.207  1027  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:31.207  1027  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 15:26:31.207  1027  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-25 15:26:31.207  8109  8155 W FormManager: Network not available. Please check & try again.
08-25 15:26:31.208  8092  8092 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 15:26:31.208  1958  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 15:26:31.208  8092  8092 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.209  1027  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:31.209  1027  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.210  1027  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.210  1027  1530 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 15:26:31.210  1027  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.210  1027  1530 D LGWifiP2pService: InactiveState{ when=-29ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.210  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-29ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.210  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.210  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.210  1027  1530 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.210  8092  8092 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.211  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.211  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.211  1027  1530 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.211  1958  2313 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 15:26:31.211  1027  1530 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.211  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.211  1027  1530 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.212  1027  1530 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.212  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.212  1027  1530 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.212  1027  1027 E WifiServerServiceExt: No p2p device connected
08-25 15:26:31.212  1958  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:31.212  1958  8150 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:31.212  1027  8130 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 15:26:31.212  1027  8130 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.212  1027  8130 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.212  1027  8130 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 15:26:31.213  8109  ,8156 V FormManager: Network unavailable.
08-25 15:26:31.218  8109  8156 V FormManager: Network unavailable.
08-25 15:26:31.219  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 15:26:31.219  4348  4348 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 15:26:31.220  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 15:26:31.224  4348  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 15:26:31.229  4348  8157 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 15:26:31.230  4348  8158 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 15:26:31.230  4348  8158 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 15:26:31.280  1027  1957 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8159 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 15:26:31.394  8159  8159 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 15:26:31.394  8159  8159 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 15:26:31.404  8159  8159 V [BNRBootReceiver]: Boot Receiver Return
08-25 15:26:31.405  8159  8159 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 15:26:31.474  1027  2023 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8177 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 15:26:31.476  1027  2023 I ActivityManager: Killing 7297:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-25 15:26:31.529  1027  1757 W libprocessgroup: failed to open /acct/uid_10085/pid_7297/cgroup.procs: No such file or directory
,08-25 15:26:31.534  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-25 15:26:31.535  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
08-25 15:26:31.536  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-25 15:26:31.536  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-25 15:26:31.538  1027  1537 D WifiController: battery changed pluggedType: 2
08-25 15:26:31.539  1958  2156 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-25 15:26:31.539  1958  2156 D LEDHandler: Battery Level Remaining: 100%
08-25 15:26:31.539  1958  2156 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-25 15:26:31.540  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.540  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.541  8159  8159 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 15:26:31.541  7762  7984 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 15:26:31.541  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-25 15:26:31.575  8177  8177 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 15:26:31.596  8177  8177 D PluginManager: init()
,08-25 15:26:31.603  8092  8092 E wpa_supplicant: USIM:  scard_init function
,08-25 15:26:31.603  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 15:26:31.603  1027  8130 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 15:26:31.604  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 15:26:31.604  8092  8092 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 15:26:31.604  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-25 15:26:31.604  1027  8130 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 15:26:31.605  1027  1532 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 15:26:31.605  1027  1532 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 15:26:31.606  1027  1532 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 15:26:31.606  1027  1532 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-25 15:26:31.606  1027  1532 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 15:26:31.606  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 15:26:31.606  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 15:26:31.619  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=205348  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 15:26:31.621  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=205350  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 15:26:31.626  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.626  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 15:26:31.627  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.628  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:26:31.629  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.629  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 15:26:31.632  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.632  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.632  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 15:26:31.632  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:31.632  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 15:26:31.646  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.647  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:31.648  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:31.713  8092  8092 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 15:26:31.714  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 15:26:31.714  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 15:26:31.715  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 15:26:31.715  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 15:26:31.715  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:31.716  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:31.718  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=205446  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 15:26:31.720  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=205448  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 15:26:31.721  1027  1089 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 15:26:31.722  1027  1532 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205450
,08-25 15:26:31.723  1027  1532 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205451
08-25 15:26:31.724  1027  1532 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205452
08-25 15:26:31.726  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205454
08-25 15:26:31.727  8092  8092 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 15:26:31.728  8092  8092 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 15:26:31.731  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:31.731  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:31.731  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 15:26:31.731  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 15:26:31.731  1027  8130 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 15:26:31.732  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 15:26:31.732  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 15:26:31.732  1027  8130 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 15:26:31.732  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:31.732  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:31.733  1027  1532 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205462
08-25 15:26:31.734  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=205462  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-25 15:26:31.736  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.736  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:31.737  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.737  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.738  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 15:26:31.738  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.741  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.741  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.741  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 15:26:31.742  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=205471  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 15:26:31.744  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:31.744  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 15:26:31.744  1027  1532 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:31.745  1027  1532 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:31.745  1027  1532 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:31.746  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:31.746  1027  1532 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 15:26:31.747  1027  1532 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=205475  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-25 15:26:31.747  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=205476  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 15:26:31.748  1027  1532 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=205477
08-25 15:26:31.748  1027  1532 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=205477
,08-25 15:26:31.749  1027  1532 D WifiNative-wlan0: doString: [STATUS]
08-25 15:26:31.750  1027  8130 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 15:26:31.750  1027  8130 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 15:26:31.750  1027  1532 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 15:26:31.752  1027  1532 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 15:26:31.757  1027  1532 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 15:26:31.757  1027  1532 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-25 15:26:31.760  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.760  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.760  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-25 15:26:31.764  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.764  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.764  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 15:26:31.764  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.764  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:31.765  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.767  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.767  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:31.768  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.770  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.770  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 15:26:31.771  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.771  1027  1532 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 15:26:31.771  1027  1538 D ConnectivityService: Got NetworkAgent Messenger
08-25 15:26:31.771  1027  1532 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:26:31.771  1027  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 15:26:31.771  1027  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 15:26:31.772  1027  1538 D ConnectivityService: NetworkAgent connected
08-25 15:26:31.772  1027  1532 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 15:26:31.772  1027  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-25 15:26:31.777  1027  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 15:26:31.777  1027  1532 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:26:31.777  1027  1532 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 15:26:31.777  1027  1532 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 15:26:31.777  1027  1532 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 15:26:31.781  1027  1532 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 15:26:31.783   305   886 D CommandListener: Setting iface cfg
08-25 15:26:31.785  1027  1532 E WifiStateMachine: Start Dhcp Watchdog 3
,08-25 15:26:31.786  1027  1532 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=205514  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:31.786  1027  1532 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=205515  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:31.787  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=205515  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:31.787  1027  8195 D DhcpStateMachine: StoppedState
08-25 15:26:31.787  1027  8195 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.787  1027  8195 D DhcpStateMachine: WaitBeforeStartState
,08-25 15:26:31.787  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:31.787  1027  1027 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 15:26:31.788  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:31.788  1027  1027 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 15:26:31.789  1027  1532 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=205517  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:31.789  1027  1532 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=205518  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:31.790  1027  1532 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=205518  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 15:26:31.791  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14088] from screen [on:0 period:-1042190737] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 15:26:31.792  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1042190736] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 15:26:31.792  1027  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 15:26:31.795  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.796  1027  1538 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-25 15:26:31.796  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.797  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.797  1027  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.798  1027  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.798  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.799  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.799  1027  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-25 15:26:31.800  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:31.800  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 15:26:31.800  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=210,0,0
08-25 15:26:31.801  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=210,0,0
,08-25 15:26:31.801  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 15:26:31.801  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 15:26:31.801  1027  1532 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 15:26:31.801  1027  1532 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 15:26:31.802  1027  1532 D WifiNative-wlan0: SET ps 0: returned true
08-25 15:26:31.802  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 15:26:31.802  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 15:26:31.802  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 15:26:31.803  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35f07a9d target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.803  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35f07a9d target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.803  1027  8195 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.803  1027  8195 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 15:26:31.803  1027  1532 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 15:26:31.803  1027  1532 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 15:26:31.804  1027  1532 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 15:26:31.804   305   886 D CommandListener: Setting iface cfg
08-25 15:26:31.805   305   886 D CommandListener: Trying to bring up wlan0
08-25 15:26:31.806  1027  1532 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 15:26:31.807  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 15:26:31.807  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 15:26:31.807  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.808  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.808  1027  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.809  1027  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.809  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.810  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 15:26:31.810  1027  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 15:26:31.811  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 15:26:31.811  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 15:26:31.811  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 15:26:31.811  1027  1530 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.812  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 15:26:31.812  1027  1530 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.812  1027  1532 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 15:26:31.812  1027  1532 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 15:26:31.812  8092  8092 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 15:26:31.812  1027  1532 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 15:26:31.813  1027  1532 D WifiNative-wlan0: doBoolean: SET ,ps 1
,08-25 15:26:31.828  1027  1532 D WifiNative-wlan0: SET ps 1: returned true
,08-25 15:26:31.829  1027  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-25 15:26:31.829  1027  1532 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 15:26:31.830  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 15:26:31.830  1027  1532 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 15:26:31.830  1027  1538 D ConnectivityService: ignoring duplicate network state non-change
,08-25 15:26:31.833  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.833  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 15:26:31.835  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.837  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.838  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.838  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 15:26:31.839  1027  1538 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 15:26:31.839  1027  1538 D ConnectivityService: Adding iface wlan0 to network 102
08-25 15:26:31.841  1027  1532 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 15:26:31.846  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.846  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.846  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-25 15:26:31.849  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 15:26:31.852  1958  1958 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 15:26:31.854  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.854  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.854  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 15:26:31.856  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 15:26:31.859  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.859  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 15:26:31.862  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.863  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.863  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:26:31.863  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 15:26:31.867  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.867  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 15:26:31.868  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.868  1027  1538 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 15:26:31.868  1027  1538 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-25 15:26:31.869  1027  1538 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 15:26:31.870   305   886 E Netd    : netlink response contains error (File exists)
08-25 15:26:31.870  1027  1538 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 15:26:31.871  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:26:31.871  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 15:26:31.872  1027  1538 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 15:26:31.872  1027  1538 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-25 15:26:31.872  1027  1538 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 15:26:31.872  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.877  1027  1538 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 15:26:31.877  1027  1538 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 15:26:31.877  1027  1538 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-25 15:26:31.877  1027  1538 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 15:26:31.878  1027  1538 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:31.878  1027  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:31.878  1027  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 15:26:31.878  1027  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:31.878  1027  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 15:26:31.878  1027  1538 D ConnectivityService: currentScore = 0, newScore = 20
08-25 15:26:31.878  1027  1538 D ConnectivityService:    accepting network in place of null
08-25 15:26:31.878  1027  1538 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:31.878  1027  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.879  1027  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 15:26:31.879  1871  1871 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:31.879  1027  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:26:31.879  1027  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 15:26:31.879  1027  1532 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:31.879  1027  1532 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:31.879  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 15:26:31.881  1027  1538 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 15:26:31.881  1027  1538 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 15:26:31.881  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 15:26:31.882   305  8199 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-25 15:26:31.883  1027  1538 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:31.883  1027  1538 D CSLegacyTypeTracker: [,e] list.add(nai) empty : false size: 1
08-25 15:26:31.884  1027  1538 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 15:26:31.890  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 15:26:31.890  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 15:26:31.890  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 15:26:31.890  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-25 15:26:31.895  1027  1538 D ConnectivityService: validation of new default Network = false
08-25 15:26:31.895  1027  1538 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 15:26:31.895  1027  1538 D DSQN    : enableDataServiceNotify 
08-25 15:26:31.895  1027  1538 D DSQN    : start dsqn bin
08-25 15:26:31.903  1027  1538 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 15:26:31.903  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:31.903  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 15:26:31.903  1027  1538 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:31.903  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 15:26:31.892  8200  8200 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:31.892  8200  8200 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:31.910  1027  1529 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 15:26:31.912  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 15:26:31.913  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.914  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:31.918  8200  8200 E DSQN    : DSQN ssw
,08-25 15:26:31.940   305  8199 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-25 15:26:31.972   305  8199 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-25 15:26:31.998  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:26:31.998  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:31.998  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:31.998  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:31.998  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:31.998  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:31.998  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:31.998  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:26:32.001  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:32.005  6832  6918 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 15:26:32.005  1027  8195 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 15:26:32.006  6832  6918 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 15:26:32.007  1027  8195 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 15:26:32.008  1027  8195 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 15:26:32.008  6832  6918 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c58e3c1 Bundle[{}]
08-25 15:26:32.008  6832  6918 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 15:26:32.009  6832  6918 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 15:26:32.009   305   885 D LGDataListener: argv[0]=dsqncommand
08-25 15:26:32.009   305   885 D LGDataListener: argv[1]=wlan0
08-25 15:26:32.009   305   885 D LGDataListener: argv[2]=1
08-25 15:26:32.009   305   885 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 15:26:32.009  6832  6918 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 15:26:32.010  1027  1087 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 15:26:32.010  1027  1087 D DSQN    : start to monitor internet connection
08-25 15:26:32.010  6832  6918 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 15:26:32.010  6832  6918 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 15:26:32.011  6832  6918 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 15:26:32.015  6832  6918 I System.out: Running OutgoingSocketThread
,08-25 15:26:32.002  8206  8206 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:32.002  8206  8206 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 15:26:32.019  6832  8207 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 885)
08-25 15:26:32.022  6832  8207 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41805
08-25 15:26:32.022  6832  8207 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 15:26:32.023  8206  8206 I dhcpcd  : version 5.5.6 starting
08-25 15:26:32.024  8206  8206 E dhcpcd  : get_duid: m
08-25 15:26:32.024  8206  8206 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 15:26:32.024  8206  8206 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 15:26:32.042  1027  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 13:26:32 GMT], X-Android-Received-Millis=[1472131592041], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472131592007]}
08-25 15:26:32.042  1027  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 15:26:32.042  1027  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 15:26:32.042  1027  1538 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-25 15:26:32.042  1027  1538 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-25 15:26:32.042  1027  1538 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:32.042  1027  1538 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:32.042  1027  1538 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 15:26:32.042  1027  1538 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-25 15:26:32.042  1027  1538 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-25 15:26:32.042  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:32.042  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:32.043  1027  1538 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 15:26:32.043  1027  1538 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:32.043  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 15:26:32.044  1027  1532 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:32.044  1027  1532 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:26:32.044  1871  1871 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:32.044  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 15:26:32.045  1871  1871 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-25 15:26:32.059  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 15:26:32.061  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 15:26:32.062  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:32.096  8206  8206 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 15:26:32.096  8206  8206 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 15:26:32.096  8206  8206 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 15:26:32.096  8206  8206 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
,08-25 15:26:32.096  8206  8206 D dhcpcd  : wlan0: sending REQUEST (xid 0x2a9dfd43), next in 3.04 seconds
,08-25 15:26:32.137  8177  8177 W ExternalStrings: load override strings
08-25 15:26:32.137  8177  8177 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 15:26:32.137  8177  8177 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 15:26:32.140  8177  8177 D StatusProvider: onCreate
,08-25 15:26:32.149  8206  8206 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 15:26:32.182  8206  8206 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 15:26:32.182  8206  8206 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
,08-25 15:26:32.183  8206  8206 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 15:26:32.183  8206  8206 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 15:26:32.183  8206  8206 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 15:26:32.183  8206  8206 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 15:26:32.183  8206  8206 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 15:26:32.183  8206  8206 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 15:26:32.183  8177  8177 V Signer  : override build config not found
,08-25 15:26:32.184  8177  8177 D Signer  : value of property debug is false
,08-25 15:26:32.250  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-25 15:26:32.250  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-25 15:26:32.250  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-25 15:26:32.251  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-25 15:26:32.251  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-25 15:26:32.251  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-25 15:26:32.252  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-25 15:26:32.252  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-25 15:26:32.252  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-25 15:26:32.253  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-25 15:26:32.253  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-25 15:26:32.253  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-25 15:26:32.254  8177  8177 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-25 15:26:32.269  8177  8177 V LGMDMManager: Create singleton instance
,08-25 15:26:32.352  8177  8177 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-25 15:26:32.425  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:32.425  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-25 15:26:32.436  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:32.445  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:32.497  1027  1957 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8246 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 15:26:32.500  1027  1957 I ActivityManager: Killing 7326:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-25 15:26:32.615  1027  8195 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-25 15:26:32.619  1027  8195 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-25 15:26:32.619  1027  8195 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 15:26:32.620  1027  8195 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 15:26:32.620  1027  8195 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 15:26:32.620  1027  8195 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 15:26:32.620  1027  8195 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 15:26:32.620  1027  8195 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 15:26:32.621  1027  8195 D DhcpStateMachine: RunningState
08-25 15:26:32.643  8177  8233 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 15:26:32.797  1027  1771 W libprocessgroup: failed to open /acct/uid_10093/pid_7326/cgroup.procs: No such file or directory
,08-25 15:26:32.841  8246  8246 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 15:26:32.871  8246  8246 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-25 15:26:32.907  8246  8246 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-25 15:26:32.907  8246  8246 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-25 15:26:32.908  8246  8246 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 15:26:32.908  8246  8246 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 15:26:32.909  8246  8246 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 15:26:32.912  8246  8246 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 15:26:32.918  8246  8246 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 15:26:32.925  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:32.925  8177  8233 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:32.925  8177  8233 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 15:26:32.928  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 15:26:32.950  8246  8246 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 15:26:32.953  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 15:26:32.955  8246  8246 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 15:26:32.956  6968  6968 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 15:26:32.959  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:32.960  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:32.962  8246  8246 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 15:26:32.967  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:32.974  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 15:26:32.981  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:32.981  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 15:26:32.982  8246  8246 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 15:26:32.985  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:32.986  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:32.992  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:33.001  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.007  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:33.008  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.008  8246  8246 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:33.010  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 15:26:33.011  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 15:26:33.011  6968  6968 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 15:26:33.011  6968  6968 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 15:26:33.011  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 15:26:33.012  6968  6968 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 15:26:33.012  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 15:26:33.012  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 15:26:33.012  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 15:26:33.012  6968  6968 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 15:26:33.012  6968  6968 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 15:26:33.013  6968  6968 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 15:26:33.016  6832  6918 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 886)
08-25 15:26:33.017  6832  6918 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 886)
08-25 15:26:33.017  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.019  1027  1532 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:33.019  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:33.019  1027  1532 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 15:26:33.020  1027  1532 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:33.020  1027  1532 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:33.021  1027  1532 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 15:26:33.021  6832  6918 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 891)
08-25 15:26:33.022  6832  6918 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 15:26:33.022  6832  6918 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 892)
08-25 15:26:33.022  1027  1538 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-25 15:26:33.022  1027  1538 D ConnectivityService: identical MTU - not setting
08-25 15:26:33.022  1027  1538 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 15:26:33.022  1027  1538 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 15:26:33.022  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:26:33.023  1027  1538 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:33.023  1027  1538 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 15:26:33.024  1597  1805 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 15:26:33.025  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:33.026  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.026  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38bc2584 added. We now have 2 listener(s)
08-25 15:26:33.027  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:33.028  1027  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.031  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.031  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.031  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.031  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.031  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2616d added. We now have 9 listener(s)
08-25 15:26:33.031  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.031  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:26:33.037  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:26:33.039  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.043  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:33.043  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:33.043  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:33.043  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:33.043  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:33.043  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.043  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:33.043  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:33.046  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:33.046  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.047  8246  8246 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:33.048  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.048  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:33.049  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.049  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10b9e33 added. We now have 3 listener(s)
,08-25 15:26:33.050  1027  2104 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.052  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.054  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.054  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.054  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.054  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.054  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9815f0 added. We now have 10 listener(s)
08-25 15:26:33.055  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.055  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:33.055  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:33.055  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:33.055  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.055  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.055  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:33.055  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.055  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38bc2584 removed from the list
08-25 15:26:33.055  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:26:33.055  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2616d removed from the list
08-25 15:26:33.055  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.056  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:33.059  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.059  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:33.059  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.060  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.060  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.061  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.061  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.061  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.061  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a2616d not in the list
08-25 15:26:33.061  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.061  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.062  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.062  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.062  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.062  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9815f0 removed from the list
08-25 15:26:33.062  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.062  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.062  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.062  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.062  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10b9e33 removed from the list
08-25 15:26:33.063  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.063  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@110a769 added. We now have 2 listener(s)
08-25 15:26:33.063  1027  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 15:26:33.065  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.065  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.065  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.066  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.066  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4f75ee added. We now have 9 listener(s)
08-25 15:26:33.066  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.066  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:33.068  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:26:33.071  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:33.074  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:33.074  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:33.074  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:33.074  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:33.074  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:33.074  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.074  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:33.074  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:33.077  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.078  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:33.078  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.078  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2100a11c added. We now have 3 listener(s)
08-25 15:26:33.078  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 15:26:33.080  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.080  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.081  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.081  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.081  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.081  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.081  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36035125 added. We now have 10 listener(s)
08-25 15:26:33.081  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.081  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:26:33.081  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:26:33.081  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:26:33.081  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:33.081  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:26:33.084  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.086  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 15:26:33.090  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:33.090  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.091  8246  8246 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 15:26:33.091  1027  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 15:26:33.091  8177  8233 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-25 15:26:33.094  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.095  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:33.096  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 15:26:33.097  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 15:26:33.098  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:26:33.099  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:33.100  6832  6918 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 15:26:33.100  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:33.100  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:33.102  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:33.102  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:33.102  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:33.103  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:33.103  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.103  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.103  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:33.103  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.103  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@110a769 removed from the list
08-25 15:26:33.103  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:26:33.103  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4f75ee removed from the list
08-25 15:26:33.103  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:33.103  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.104  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.104  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.105  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.105  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.105  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.105  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4f75ee not in the list
08-25 15:26:33.105  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.105  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.106  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.106  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:33.106  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:33.106  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.106  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.107  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36035125 removed from the list
08-25 15:26:33.107  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.107  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.107  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.107  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.107  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2100a11c removed from the list
08-25 15:26:33.108  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.108  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2604b308 added. We now have 2 listener(s)
08-25 15:26:33.108  1027  1757 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.109  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.111  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.111  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.111  6832  6918 ,D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.111  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.111  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ebcdaa1 added. We now have 9 listener(s)
08-25 15:26:33.111  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.112  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:26:33.115  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:26:33.118  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:33.118  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.119  8246  8246 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:33.121  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.121  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:33.123  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:33.123  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:33.123  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:33.123  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:33.123  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:33.123  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.123  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:33.123  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:33.124  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.124  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:33.124  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.124  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b89c87 added. We now have 3 listener(s)
08-25 15:26:33.125  1027  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.127  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:26:33.129  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.129  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.129  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.130  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.130  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b5f7b4 added. We now have 10 listener(s)
08-25 15:26:33.130  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.130  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.130  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:26:33.131  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:26:33.131  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:26:33.131  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:26:33.131  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:33.131  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:26:33.131  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:33.134  8177  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-25 15:26:33.135  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 15:26:33.135  1027  1044 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.139  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.141  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:26:33.141  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 15:26:33.143  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:26:33.147  8177  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-25 15:26:33.147  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:33.147  8177  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 15:26:33.148  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:33.148  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.148  8246  8246 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:33.148  8177  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-25 15:26:33.149  8177  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-25 15:26:33.150  8177  8233 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-25 15:26:33.151  6832  6918 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 15:26:33.152  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:33.152  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:33.152  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:33.152  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.152  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.152  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:33.152  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 15:26:33.152  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2604b308 removed from the list
08-25 15:26:33.152  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.152  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ebcdaa1 removed from the list
08-25 15:26:33.153  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:33.153  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.153  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.153  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.154  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.154  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.154  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.154  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ebcdaa1 not in the list
08-25 15:26:33.154  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.154  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.155  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.155  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:33.155  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:33.156  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.156  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.156  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b5f7b4 removed from the list
08-25 15:26:33.156  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.156  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.156  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.156  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.156  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b89c87 removed from the list
08-25 15:26:33.157  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.157  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b787a23 added. We now have 2 listener(s)
08-25 15:26:33.157  1027  1771 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.158  8177  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-25 15:26:33.160  8177  8233 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryT,hread-1': Here about to commit perfs
08-25 15:26:33.160  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.161  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.161  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.161  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.161  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1194db20 added. We now have 9 listener(s)
,08-25 15:26:33.161  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.161  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:26:33.163  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:33.164  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:33.166  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.170  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:33.170  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:33.170  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:33.170  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:33.170  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:33.170  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.170  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:33.170  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:33.171  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.172  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:33.172  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.172  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ffb369e added. We now have 3 listener(s)
,08-25 15:26:33.172  1027  1982 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.174  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.176  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.176  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.176  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.176  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.177  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:26:33.177  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24ce957f added. We now have 10 listener(s)
08-25 15:26:33.177  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.177  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:26:33.177  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:26:33.177  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:26:33.177  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:33.177  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:26:33.179  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:33.181  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 15:26:33.181  1027  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.185  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.186  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 15:26:33.186  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 15:26:33.191  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:26:33.192  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 15:26:33.192  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:33.192  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.195  6832  6918 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 15:26:33.197  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:33.197  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:33.197  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:33.197  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.197  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.197  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:33.197  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.197  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b787a23 removed from the list
08-25 15:26:33.197  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.197  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1194db20 removed from the list
08-25 15:26:33.197  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:33.197  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.198  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.198  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.199  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.199  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.199  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.199  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1194db20 not in the list
08-25 15:26:33.199  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.199  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.200  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.200  8246  8246 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:33.200  6832  6918 D BluetoothLeScanner: could not find callback wrapper
08-25 15:26:33.200  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:26:33.200  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.200  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.200  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSett,ings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24ce957f removed from the list
08-25 15:26:33.200  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.200  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.200  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.201  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.201  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ffb369e removed from the list
08-25 15:26:33.202  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.202  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e01eaa added. We now have 2 listener(s)
08-25 15:26:33.208  1027  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 15:26:33.208  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:33.209  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:33.211  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.211  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.211  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.211  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.211  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17410a9b added. We now have 9 listener(s)
08-25 15:26:33.211  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:26:33.211  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:26:33.214  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:26:33.218  6832  6918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:26:33.218  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:26:33.218  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 15:26:33.218  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:26:33.218  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:26:33.218  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.218  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:26:33.218  6832  6918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:26:33.219  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:33.220  6832  6918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:26:33.220  6832  6918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:26:33.220  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:26:33.220  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a00ae11 added. We now have 3 listener(s)
08-25 15:26:33.221  1027  1734 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 15:26:33.223  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.225  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 15:26:33.225  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:26:33.225  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:26:33.225  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:26:33.225  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9797b76 added. We now have 10 listener(s)
08-25 15:26:33.225  6832  6918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:26:33.226  6832  6918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:26:33.226  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:33.226  6832  6918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:26:33.226  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.226  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.226  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:26:33.226  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.226  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e01eaa removed from the list
08-25 15:26:33.226  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.226  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.226  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17410a9b removed from the list
08-25 15:26:33.229  6832  6832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:26:33.229  6832  6918 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:26:33.229  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.229  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.229  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.230  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.230  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.230  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.230  6832  6918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17410a9b not in the list
08-25 15:26:33.230  6832  6918 W org.thaliprojec,t.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.230  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.232  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:26:33.232  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:26:33.232  6832  6918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:26:33.232  6832  6918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9797b76 removed from the list
,08-25 15:26:33.232  6832  6918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:26:33.232  6832  6918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:26:33.232  6832  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:26:33.232  6832  6918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:26:33.232  6832  6918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a00ae11 removed from the list
08-25 15:26:33.233  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 15:26:33.233  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 15:26:33.234  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:33.234  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 15:26:33.234  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:26:33.234  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.234  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 15:26:33.234  6832  6918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 15:26:33.235  8246  8246 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 15:26:33.242  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:33.240  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.248  8131  8131 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-25 15:26:33.249  6832  8287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 899, name: My test thread name)
08-25 15:26:33.249  6832  8287 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 899, thread name: My test thread name)
08-25 15:26:33.249  6832  8287 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 899, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 15:26:33.252  6832  8288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 901, name: My test thread name)
08-25 15:26:33.252  6832  8288 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 901, thread name: My test thread name)
08-25 15:26:33.252  6832  8288 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 901, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 15:26:33.254  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:33.254  6832  6918 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 15:26:33.254  6832  6918 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 15:26:33.254  6832  6918 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 15:26:33.255  6832  6918 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 15:26:33.255  6832  6918 D com.test.thalitest.ThaliTestRunner: Total duration: 23819 ms
08-25 15:26:33.256  6832  6918 I jxcore-log: Total number of executed tests:  80
08-25 15:26:33.256  6832  6918 I jxcore-log: 
08-25 15:26:33.256  6832  6918 I jxcore-log: Number of passed tests:  80
08-25 15:26:33.256  6832  6918 I jxcore-log: 
08-25 15:26:33.256  6832  6918 I jxcore-log: Number of failed tests:  0
08-25 15:26:33.256  6832  6918 I jxcore-log: 
08-25 15:26:33.256  6832  6918 I jxcore-log: Number of ignored tests:  0
08-25 15:26:33.256  6832  6918 I jxcore-log: 
08-25 15:26:33.257  6832  6918 I jxcore-log: Total duration:  23819
08-25 15:26:33.257  6832  6918 I jxcore-log: 
08-25 15:26:33.257  6832  6918 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 15:26:33.257  6832  6918 I jxcore-log: 
08-25 15:26:33.258  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 15:26:33.261  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.261  6832  6918 I jxcore-log: 
08-25 15:26:33.264  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.264  6832  6918 I jxcore-log: 
08-25 15:26:33.265  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.265  6832  6918 I jxcore-log: 
08-25 15:26:33.266  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.266  6832  6918 I jxcore-log: 
08-25 15:26:33.267  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.267  6832  6918 I jxcore-log: 
08-25 15:26:33.269  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.269  6832  6918 I jxcore-log: 
08-25 15:26:33.269  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.271  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.271  6832  6918 I jxcore-log: 
08-25 15:26:33.272  6832  6832 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 15:26:33.273  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.273  6832  6918 I jxcore-log: 
08-25 15:26:33.274  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:26:33.274  6832  6918 I jxcore-log: 
08-25 15:26:33.275  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:26:33.275  6832  6918 I jxcore-log: 
08-25 15:26:33.276  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.276  6832  6918 I jxcore-log: 
08-25 15:26:33.276  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:33.276  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.277  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.277  6832  6918 I jxcore-log: 
08-25 15:26:33.277  8246  8246 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 15:26:33.278  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:26:33.278  6832  6918 I jxcore-log: 
,08-25 15:26:33.278  8246  8246 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 15:26:33.279  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:26:33.279  6832  6918 I jxcore-log: 
08-25 15:26:33.279  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:26:33.279  6832  6918 I jxcore-log: 
08-25 15:26:33.280  8246  8246 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 15:26:33.280  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.280  6832  6918 I jxcore-log: 
08-25 15:26:33.281  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.281  6832  6918 I jxcore-log: 
08-25 15:26:33.282  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.282  6832  6918 I jxcore-log: 
08-25 15:26:33.282  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.282  6832  6918 I jxcore-log: 
08-25 15:26:33.283  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.283  6832  6918 I jxcore-log: 
08-25 15:26:33.284  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.284  6832  6918 I jxcore-log: 
08-25 15:26:33.284  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.284  6832  6918 I jxcore-log: 
08-25 15:26:33.285  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:26:33.285  6832  6918 I jxcore-log: 
08-25 15:26:33.286  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.286  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:26:33.286  6832  6918 I jxcore-log: 
08-25 15:26:33.286  8177  8234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-25 15:26:33.286  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.286  6832  6918 I jxcore-log: 
08-25 15:26:33.287  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.287  6832  6918 I jxcore-log: 
08-25 15:26:33.288  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.288  6832  6918 I jxcore-log: 
08-25 15:26:33.289  8131  8131 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNEC,TED
08-25 15:26:33.289  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.289  6832  6918 I jxcore-log: 
,08-25 15:26:33.290  8131  8131 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 15:26:33.290  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.290  6832  6918 I jxcore-log: 
08-25 15:26:33.290  6832  6918 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:26:33.290  6832  6918 I jxcore-log: 
08-25 15:26:33.292  6968  6968 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 15:26:33.299  6968  6968 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 15:26:33.306  8246  8246 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 15:26:33.306  8246  8246 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 15:26:33.307  8246  8246 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 15:26:33.308  8246  8246 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 15:26:33.309  8246  8246 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-25 15:26:33.311  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-25 15:26:33.318  8246  8246 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 15:26:33.319  8246  8246 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 15:26:33.319  8246  8246 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 15:26:33.354  8246  8246 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:33.354  8246  8246 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:26:33.363  8246  8246 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 15:26:33.364  8246  8246 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 15:26:33.365  8246  8246 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 15:26:33.365  8246  8246 V SoundPool: doLoad: loading sample sampleID=1
,08-25 15:26:33.365  8246  8246 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 15:26:33.367  8246  8296 V SoundPool: Start decode
08-25 15:26:33.367  8246  8296 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 15:26:33.369   311   311 V MediaPlayerService: decode(22, 10857164, 17813)
08-25 15:26:33.369   311   311 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 15:26:33.369   311   311 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 15:26:33.369   311   311 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 15:26:33.369   311   311 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 15:26:33.369   311   311 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 15:26:33.369   311   311 V MediaPlayerService: player type = 3
08-25 15:26:33.369   311   311 V AwesomePlayer: AwesomePlayer create()
08-25 15:26:33.370   311   311 V AwesomePlayer: reset_l() 
08-25 15:26:33.370   311   311 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:33.370   311   311 V AwesomePlayer: setAudioSink() 
08-25 15:26:33.370   311   311 V AwesomePlayer: reset_l() 
08-25 15:26:33.370   311   311 V AudioCache: notify(0xb14324c0, 8, 0, 0)
08-25 15:26:33.370   311   311 V AudioCache: ignored
08-25 15:26:33.370   311   311 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:33.370   311   311 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 15:26:33.370   311   311 V AwesomePlayer: setDataSource_l dataSource
08-25 15:26:33.370   311   311 V LGParserOSAL: SniffLGParser start
08-25 15:26:33.370   311   311 V LGParserOSAL: MainType:5, SubType=0
08-25 15:26:33.370   311   311 V LGParserOSAL: #### check Mime : application/ogg
08-25 15:26:33.370   311   311 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 15:26:33.370   311   311 E MediaExtractor: Use LGExtractor :application/ogg 
08-25 15:26:33.375  7691  7691 D UEI.SmartControl: QS Service created
08-25 15:26:33.378  8246  8246 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 15:26:33.409  8246  8246 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 15:26:33.409  8246  8246 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 15:26:33.414   311   311 V LGParserOSAL: supported mime: application/ogg
08-25 15:26:33.414   311   311 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 15:26:33.414   311   311 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 15:26:33.414   311   311 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 15:26:33.414   311   311 V AwesomePlayer: AudioTrack Setting
08-25 15:26:33.414   311   311 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 15:26:33.414   311   311 V AwesomePlayer: setAudioSource() 
08-25 15:26:33.414   311   311 V MediaPlayerService: prepare
08-25 15:26:33.414  7691  7691 I UEI.SmartControl: Service initServices...
08-25 15:26:33.414   311   311 V AwesomePlayer: prepareAsync_l() 
08-25 15:26:33.414   311   311 V MediaPlayerService: wait for prepare
08-25 15:26:33.414  7691  7691 D UEI.SmartControl: QS start get config
08-25 15:26:33.414   311  8297 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 15:26:33.414   311  8297 V AwesomePlayer: initAudioDecoder() 
08-25 15:26:33.415   311  8297 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 15:26:33.415   311  8297 V AudioSystem: isOffloadSupported()
08-25 15:26:33.415   311  8297 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 15:26:33.415   311  8297 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 15:26:33.415   311  8297 I AudioFlinger: isAud,ioPlaybackHookOn() false
08-25 15:26:33.415   311  8297 V AwesomePlayer: getUseOffload() = 0 
08-25 15:26:33.415   311  8297 V OMXCodec: OMXCodec::Create
08-25 15:26:33.415   311  8297 V OMXCodec: findMatchingCodecs()
08-25 15:26:33.415   311  8297 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 15:26:33.415   311  8297 V OMXCodec: matchingCodecs.size()=1
08-25 15:26:33.415   311  8297 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 15:26:33.416   311  8297 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 15:26:33.416   311  8297 V LGCodecAdapter: LG Codec Adapter start
08-25 15:26:33.416   311  8297 V OMXCodec: OMXCodec Createtor
08-25 15:26:33.416   311  8297 V OMXCodec: setComponentRole
,08-25 15:26:33.416   311  8297 V OMXCodec: configureCodec protected=0
08-25 15:26:33.416   311  8297 V LGCodecAdapter: called getLGCodecSpecificData
08-25 15:26:33.416   311  8297 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 15:26:33.416   311  8297 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 15:26:33.417   311  8297 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 15:26:33.417   311  8297 V LGCodecOSAL: Not support LGCodec
08-25 15:26:33.417   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 15:26:33.417   311  8297 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 15:26:33.417   311  8297 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 15:26:33.417   311  8297 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 15:26:33.417   311  8297 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 15:26:33.417   311  8297 V AudioSystem: isOffloadSupported()
08-25 15:26:33.417   311  8297 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 15:26:33.417   311  8297 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 15:26:33.417   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 15:26:33.417   311  8297 V OMXCodec: init()
08-25 15:26:33.417   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 15:26:33.417   311  8297 V OMXCodec: allocateBuffers
08-25 15:26:33.417   311  8297 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 15:26:33.417   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 15:26:33.417   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04080b0 on input port
08-25 15:26:33.417   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408100 on input port
08-25 15:26:33.417   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408150 on input port
08-25 15:26:33.418   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04081a0 on input port
08-25 15:26:33.418   311  8297 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 15:26:33.418   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 15:26:33.418   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04081f0 on output port
08-25 15:26:33.418   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408290 on output port
08-25 15:26:33.418   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04082e0 on output port
08-25 15:26:33.418   311  8297 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408470 on output port
08-25 15:26:33.418   311  8297 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 15:26:33.418   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 15:26:33.418   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 15:26:33.418   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 15:26:33.419   311  8297 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-25 15:26:33.419   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 15:26:33.419   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 15:26:33.419   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 15:26:33.419   311  8297 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 15:26:33.419   311  8297 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 15:26:33.419   311  8297 V AudioCache: notify(0xb14324c0, 5, 0, 0)
08-25 15:26:33.419   311  8297 V AudioCache: ignored
08-25 15:26:33.419   311  8297 V AudioCache: notify(0xb14324c0, 1, 0, 0)
08-25 15:26:33.419   311  8297 V AudioCache: prepared
08-25 15:26:33.419   311   311 V AudioCache: wait - success
08-25 15:26:33.419   311   311 V MediaPlayerService: start
08-25 15:26:33.419   311   311 V AwesomePlayer: play_l() 
08-25 15:26:33.419   311   311 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 15:26:33.419   311   311 V AwesomePlayer: createAudioPlayer_l
08-25 15:26:33.419   311   311 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 15:26:33.419   311   311 V AwesomePlayer: startAudioPlayer_l() 
08-25 15:26:33.419   311   311 D AudioPlayer: start of Playback, useOffload 0
08-25 15:26:33.419   311   311 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 15:26:33.419   311   311 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 15:26:33.423  8246  8246 V LGMDMManager: Create singleton instance
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957017584
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957017744
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957017824
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957018224
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:33.423   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 15:26:33.424   311  8299 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb04082e0 on output port
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408290 on output port
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocated buff,er 0xb04081f0 on output port
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0408600 on output port
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 15:26:33.424   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 15:26:33.425   311   311 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 15:26:33.426   311   311 V AudioCache: notify(0xb14324c0, 6, 0, 0)
08-25 15:26:33.426   311   311 V AudioCache: ignored
08-25 15:26:33.426   311   311 V MediaPlayerService: wait for playback complete
08-25 15:26:33.427   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.427   311  8300 V AudioCache: memcpy(0xaf006000, 0xb57bf000, 4096)
08-25 15:26:33.432   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.432   311  8300 V AudioCache: memcpy(0xaf007000, 0xb57bf000, 4096)
08-25 15:26:33.433   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.433   311  8300 V AudioCache: memcpy(0xaf008000, 0xb57bf000, 4096)
08-25 15:26:33.434   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.434   311  8300 V AudioCache: memcpy(0xaf009000, 0xb57bf000, 4096)
08-25 15:26:33.434   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.434   311  8300 V AudioCache: memcpy(0xaf00a000, 0xb57bf000, 4096)
08-25 15:26:33.435   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.435   311  8300 V AudioCache: memcpy(0xaf00b000, 0xb57bf000, 4096)
08-25 15:26:33.436   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.436   311  8300 V AudioCache: memcpy(0xaf00c000, 0xb57bf000, 4096)
08-25 15:26:33.436   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.436   311  8300 V AudioCache: memcpy(0xaf00d000, 0xb57bf000, 4096)
08-25 15:26:33.437   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.437   311  8300 V AudioCache: memcpy(0xaf00e000, 0xb57bf000, 4096)
08-25 15:26:33.438   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.438   311  8300 V AudioCache: memcpy(0xaf00f000, 0xb57bf000, 4096)
08-25 15:26:33.438   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.438   311  8300 V AudioCache: memcpy(0xaf010000, 0xb57bf000, 4096)
08-25 15:26:33.439   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.439   311  8300 V AudioCache: memcpy(0xaf011000, 0xb57bf000, 4096)
08-25 15:26:33.439   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.439   311  8300 V AudioCache: memcpy(0xaf012000, 0xb57bf000, 4096)
08-25 15:26:33.440   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.440   311  8300 V AudioCache: memcpy(0xaf013000, 0xb57bf000, 4096)
08-25 15:26:33.441   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.441   311  8300 V AudioCache: memcpy(0xaf014000, 0xb57bf000, 4096)
,08-25 15:26:33.441   311  8300 V AudioCache: write(0xb57bf000, 4096)
,08-25 15:26:33.441   311  8300 V AudioCache: memcpy(0xaf015000, 0xb57bf000, 4096)
08-25 15:26:33.444   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.444   311  8300 V AudioCache: memcpy(0xaf016000, 0xb57bf000, 4096)
08-25 15:26:33.444   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.444   311  8300 V AudioCache: memcpy(0xaf017000, 0xb57bf000, 4096)
08-25 15:26:33.445   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.445   311  8300 V AudioCache: memcpy(0xaf018000, 0xb57bf000, 4096)
08-25 15:26:33.446   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.446   311  8300 V AudioCache: memcpy(0xaf019000, 0xb57bf000, 4096)
08-25 15:26:33.447   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.447   311  8300 V AudioCache: memcpy(0xaf01a000, 0xb57bf000, 4096)
08-25 15:26:33.448   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.448   311  8300 V AudioCache: memcpy(0xaf01b000, 0xb57bf000, 4096)
08-25 15:26:33.449   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.449   311  8300 V AudioCache: memcpy(0xaf01c000, 0xb57bf000, 4096)
08-25 15:26:33.449   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.449   311  8300 V AudioCache: memcpy(0xaf01d000, 0xb57bf000, 4096)
08-25 15:26:33.449   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.449   311  8300 V AudioCache: memcpy(0xaf01e000, 0xb57bf000, 4096)
08-25 15:26:33.449   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.449   311  8300 V AudioCache: memcpy(0xaf01f000, 0xb57bf000, 4096)
08-25 15:26:33.452   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.452   311  8300 V AudioCache: memcpy(0xaf020000, 0xb57bf000, 4096)
08-25 15:26:33.452   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.452   311  8300 V AudioCache: memcpy(0xaf021000, 0xb57bf000, 4096)
08-25 15:26:33.452   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.452   311  8300 V AudioCache: memcpy(0xaf022000, 0xb57bf000, 4096)
08-25 15:26:33.452   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.452   311  8300 V AudioCache: memcpy(0xaf023000, 0xb57bf000, 4096)
08-25 15:26:33.454   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.454   311  8300 V AudioCache: memcpy(0xaf024000, 0xb57bf000, 4096)
08-25 15:26:33.455   311  8300 V AudioCache: write(0xb57bf000, 4096)
,08-25 15:26:33.455   311  8300 V AudioCache: memcpy(0xaf025000, 0xb57bf000, 4096)
08-25 15:26:33.455   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.455   311  8300 V AudioCache: memcpy(0xaf026000, 0xb57bf000, 4096)
08-25 15:26:33.456   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.456   311  8300 V AudioCache: memcpy(0xaf027000, 0xb57bf000, 4096)
08-25 15:26:33.456   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.456   311  8300 V AudioCache: memcpy(0xaf028000, 0xb57bf000, 4096)
08-25 15:26:33.458   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.458   311  8300 V AudioCache: memcpy(0xaf029000, 0xb57bf000, 4096)
08-25 15:26:33.459   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.459   311  8300 V AudioCache: memcpy(0xaf02a000, 0xb57bf000, 4096)
08-25 15:26:33.459   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.459   311  8300 V AudioCache: memcpy(0xaf02b000, 0xb57bf000, 4096)
08-25 15:26:33.460   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.460   311  8300 V AudioCache: memcpy(0xaf02c000, 0xb57bf000, 4096)
,08-25 15:26:33.460   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.460   311  8300 V AudioCache: memcpy(0xaf02d000, 0xb57bf000, 4096)
08-25 15:26:33.461   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.461   311  8300 V AudioCache: memcpy(0xaf02e000, 0xb57bf000, 4096)
08-25 15:26:33.461   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.461   311  8300 V AudioCache: memcpy(0xaf02f000, 0xb57bf000, 4096)
08-25 15:26:33.462   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.462   311  8300 V AudioCache: memcpy(0xaf030000, 0xb57bf000, 4096)
08-25 15:26:33.463   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.463   311  8300 V AudioCache: memcpy(0xaf031000, 0xb57bf000, 4096)
08-25 15:26:33.463   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.463   311  8300 V AudioCache: memcpy(0xaf032000, 0xb57bf000, 4096)
08-25 15:26:33.464   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.464   311  8300 V AudioCache: memcpy(0xaf033000, 0xb57bf000, 4096)
08-25 15:26:33.464   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.464   311  8300 V AudioCache: memcpy(0xaf034000, 0xb57bf000, 4096)
08-25 15:26:33.465   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.465   311  8300 V AudioCache: memcpy(0xaf035000, 0xb57bf000, 4096)
08-25 15:26:33.467   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.467   311  8300 V AudioCache: memcpy(0xaf036000, 0xb57bf000, 4096)
08-25 15:26:33.468   311  8300 V AudioCache: write(0xb57bf000, 4096)
08-25 15:26:33.468   311  8300 V AudioCache: memcpy(0xaf037000, 0xb57bf000, 4096)
08-25 15:26:33.469   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 15:26:33.469   311  8300 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 15:26:33.469   311  8300 V AwesomePlayer: postAudioEOS() 
08-25 15:26:33.469   311  8300 V AudioCache: write(0xb57bf000, 280)
08-25 15:26:33.469   311  8300 V AudioCache: memcpy(0xaf038000, 0xb57bf000, 280)
08-25 15:26:33.471   311  8297 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 15:26:33.471   311  8297 V AwesomePlayer: onStreamDone
08-25 15:26:33.471   311  8297 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 15:26:33.471   311  8297 V AudioCache: notify(0xb14324c0, 2, 0, 0)
08-25 15:26:33.471   311  8297 V AudioCache: playback complete
08-25 15:26:33.471   311  8297 V AwesomePlayer: pause_l() 
08-25 15:26:33.471   311   311 V AudioCache: wait - success
08-25 15:26:33.471   311  8297 V AudioCache: notify(0xb14324c0, 7, 0, 0)
08-25 15:26:33.471   311  8297 V AudioCache: ignored
08-25 15:26:33.471   311   311 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 15:26:33.471   311  8297 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:33.471   311  8297 D AudioPlayer: Pause Playback at 1068125
,08-25 15:26:33.471   311   311 V AwesomePlayer: reset_l() 
08-25 15:26:33.471   311   311 V AudioCache: notify(0xb14324c0, 8, 0, 0)
08-25 15:26:33.471   311   311 V AudioCache: ignored
08-25 15:26:33.471   311   311 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:33.471   311   311 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 15:26:33.471   311   311 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 15:26:33.471   311   311 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 15:26:33.471   311   311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 15:26:33.471   311   311 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 15:26:33.471   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 15:26:33.471   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 15:26:33.471   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 15:26:33.471   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04081a0 on port 0
08-25 15:26:33.471   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0408150 on port 0
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0408100 on port 0
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04080b0 on port 0
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0408600 on port 1
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04081f0 on port 1
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0408290 on port 1
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb04082e0 on port 1
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 15:26:33.472   311   311 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 15:26:33.472   311   311 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 15:26:33.472   311  8299 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 15:26:33.472   311   311 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 15:26:33.472   311   311 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 15:26:33.472   311   311 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 15:26:33.473   311   311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 15:26:33.473   311   311 D AudioPlayer: AudioPlayer releasing audio source
08-25 15:26:33.473   311   311 D AudioPlayer: AudioPlayer done releasing audio source
08-25 15:26:33.473   311   311 V AwesomePlayer: reset_l() 
08-25 15:26:33.473   311   311 V AwesomePlayer: cancelPlayerEvents
08-25 15,:26:33.473   311   311 V AwesomePlayer: ~AwesomePlayer call
08-25 15:26:33.473   311   311 V AwesomePlayer: reset_l() 
08-25 15:26:33.473   311   311 V AwesomePlayer: cancelPlayerEvents
08-25 15:26:33.473  8246  8296 V SoundPool: close(31)
08-25 15:26:33.473  8246  8296 V SoundPool: pointer = 0x9ff2d000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 15:26:33.491  8246  8246 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-25 15:26:33.491  8246  8246 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-25 15:26:33.493  8246  8246 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3604
08-25 15:26:33.495  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.512  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:33.515  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:33.517  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.518  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.520  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.522  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.524  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:33.527  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 15:26:33.530  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 15:26:33.567  8291  8291 D AndroidRuntime: 
08-25 15:26:33.567  8291  8291 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 15:26:33.570  8291  8291 D AndroidRuntime: CheckJNI is OFF
,08-25 15:26:33.705  8291  8291 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 15:26:33.716  1027  1085 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-25 15:26:33.718  1027  1085 I ActivityManager: Killing 6832:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-25 15:26:33.791  1027  2022 I WindowState: WIN DEATH: Window{2bea1802 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 15:26:33.792  1027  1537 D WifiService: Client connection lost with reason: 4
,08-25 15:26:33.806  1027  2022 D InputDispatcher: Window went away: Window{2bea1802 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 15:26:33.812  7691  7691 I UEI.SmartControl: Supports setup maps: true
08-25 15:26:33.815  7691  7691 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 15:26:33.815  7691  7691 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 15:26:33.815  7691  7691 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 15:26:33.815  7691  7691 I UEI.SmartControl: ### init IR Blaster...
08-25 15:26:33.819  7691  7691 D serial_port: Configuring serial port
08-25 15:26:33.819  7691  7691 E UEI.SmartControl: UEIBLaster setting for 616
08-25 15:26:33.819  7691  7691 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 15:26:33.819  7691  7691 I UEI.SmartControl: configuring settings for MAXQ616
08-25 15:26:33.819  7691  7691 I UEI.SmartControl: Get version...
,08-25 15:26:33.833  7691  8314 D UEI.SmartControl: serial port data available: 21
,08-25 15:26:33.860  7691  7691 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 15:26:33.860  7691  7691 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-25 15:26:33.860  7691  7691 I UEI.SmartControl: QS saving settings...
08-25 15:26:33.862  7691  7691 D UEI.SmartControl: IR Blaster version: 25672567
08-25 15:26:33.878  7691  8314 D UEI.SmartControl: serial port data available: 4
,08-25 15:26:33.910  7691  8317 I UEI.SmartControl: Device manager: loading config....
,08-25 15:26:33.912  7691  7691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 15:26:33.914  7691  8317 D UEI.SmartControl: ----------- loading internal config...
08-25 15:26:33.926  7691  8317 E UEI.SmartControl: Loading SETTINGS...
,08-25 15:26:33.941  7691  8317 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-25 15:26:33.944  1027  1085 I ActivityManager:   Force finishing activity ActivityRecord{c516d8f u0 com.test.thalitest/.MainActivity t6}
,08-25 15:26:33.969  7691  8316 I UEI.SmartControl: Notify AllClients services are ready: 0,
,08-25 15:26:33.969  7691  8316 D UEI.SmartControl: -----service ready thread exits
08-25 15:26:33.998   329   352 E GBMv2   : DFP En is all cleared set to be enabled
08-25 15:26:33.999  1027  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-25 15:26:34.002  1027  1101 I ActivityManager:   Force finishing activity ActivityRecord{c516d8f u0 com.test.thalitest/.MainActivity t6 f}
,08-25 15:26:34.002  1027  1101 W ActivityManager: Duplicate finish request for ActivityRecord{c516d8f u0 com.test.thalitest/.MainActivity t6 f}
,08-25 15:26:34.024  1027  1771 W ActivityManager: Spurious death for ProcessRecord{3e659817 6832:com.test.thalitest/u0a118}, curProc for 6832: null
08-25 15:26:34.026  7691  7691 E UEI.SmartControl: Services init done
08-25 15:26:34.027  7691  7691 D UEI.SmartControl: QS Service init finished
08-25 15:26:34.028  2084  2084 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 15:26:34.029  1958  3944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 15:26:34.029  1958  3944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35a713e0 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 15:26:34.031  2084  2084 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-25 15:26:34.032  1958  1974 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 15:26:34.033  1958  1974 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f71e699 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 15:26:34.034  7691  7691 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 15:26:34.034  7691  7691 D UEI.SmartControl: QS Service version code: 201091
08-25 15:26:34.035  7691  7691 D UEI.SmartControl: Service requested: Control
,08-25 15:26:34.037  2084  2084 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-25 15:26:34.039  2084  2186 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-25 15:26:34.040  7691  7691 D UEI.SmartControl: Internal service binding...
08-25 15:26:34.047  8246  8246 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 15:26:34.048  1597  1597 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-25 15:26:34.048  7691  7707 I UEI.SmartControl: ------ IControl API: 11
08-25 15:26:34.048  7691  7707 D UEI.SmartControl: File observer start...
,08-25 15:26:34.049  7691  7707 E UEI.SmartControl: IR Port is disabled: false
08-25 15:26:34.049  7691  7707 D UEI.SmartControl: Starting file observer...
08-25 15:26:34.050  7691  7707 I UEI.SmartControl: Registering callback...
08-25 15:26:34.053  2034  2034 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 15:26:34.053  3800  3800 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-25 15:26:34.057  1027  1457 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 15:26:34.057  7691  7706 I UEI.SmartControl: ------ IControl API: 19
08-25 15:26:34.058  7691  7706 I UEI.SmartControl: Registering Services Ready callback...
08-25 15:26:34.058  7691  7706 I UEI.SmartControl: Notify client services are ready...
08-25 15:26:34.060  7762  7762 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 15:26:34.060  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 15:26:34.064  2455  2585 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 15:26:34.067  4492  4492 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 15:26:34.068  4492  4492 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 15:26:34.068  4492  4492 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-25 15:26:34.068  4492  4492 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 15:26:34.068  4492  4492 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-25 15:26:34.068  4492  4492 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 15:26:34.068  4492  4492 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 15:26:34.068  4492  4492 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 15:26:34.068  4492  4492 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:26:34.068  4492  4492 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:26:34.068  4492  4492 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 15:26:34.067  8246  8262 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 15:26:34.068  4492  4492 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 15:26:34.073  8246  8294 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 15:26:34.073  8246  8294 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 15:26:34.074  8246  8246 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,08-25 15:26:34.084  8246  8246 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 15:26:34.084  7691  7707 I UEI.SmartControl: ------ IControl API: 8
08-25 15:26:34.086  8246  8246 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 15:26:34.086  8246  8246 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 15:26:34.086  8246  8246 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 15:26:34.087  8246  8246 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 15:26:34.105  4597  4597 I art     : Explicit concurrent mark sweep GC freed 8362(477KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 689us total 92.262ms
,08-25 15:26:34.111  1027  2029 V SIM_STK : Menu title from STK is T-Mobile
08-25 15:26:34.154  1027  1027 D administrator: Handling package changes for user 0
,08-25 15:26:34.172  8246  8246 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 15:26:34.172  8246  8246 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-25 15:26:34.180  8177  8177 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-25 15:26:34.184  1922  1922 D ActionManagerService: notifyUserLog: 1000003
08-25 15:26:34.185  3800  4491 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-25 15:26:34.187  2084  2084 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-25 15:26:34.219  8246  8246 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-25 15:26:34.220  1835  1835 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-25 15:26:34.220  1597  1597 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-25 15:26:34.222  2084  2084 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-25 15:26:34.223  2084  2084 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-25 15:26:34.226  2084  2084 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-25 15:26:34.229  1597  1636 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 15:26:34.229  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.230  2237  2237 I ConfigService: onCreate
,08-25 15:26:34.231  2237  2237 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-25 15:26:34.232  2084  2084 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 15:26:34.233  1922  1922 D ActionManagerService: notifyUserLog: 1000004
08-25 15:26:34.233  3800  4491 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 15:26:34.234  1597  1636 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 15:26:34.234  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.236  3800  3816 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , expire_time: 0
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , display: false
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , animation: false }
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , expire_time: 0
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , display: false
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , animation: false }
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , expire_time: 0
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , display: false
08-25 15:26:34.238  2084  2084 I GBoardWebViewUtils: , animation: false }
08-25 15:26:34.239  1835  1835 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-25 15:26:34.240  1597  1636 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 15:26:34.241  1597  1636 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:26:34.241  1597  1636 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 15:26:34.242  1597  1636 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 15:26:34.243  1888  1888 D SplitUIManager: split_name #11 / not available #0
08-25 15:26:34.243  1888  1888 D SplitUIService: r,emoved split : 
,08-25 15:26:34.246  1597  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 15:26:34.246  1597  1636 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 15:26:34.248  1597  1636 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 15:26:34.248  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.251  1597  1636 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 15:26:34.251  1597  1636 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 15:26:34.252  1597  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 15:26:34.253  1597  1636 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 15:26:34.253  2237  2237 I ConfigService: onBind returning update interface
08-25 15:26:34.254  2084  8320 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-25 15:26:34.256  1597  1636 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 15:26:34.256  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.260  2237  2237 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-25 15:26:34.260  2237  2237 I ConfigService: onBind returning config service
,08-25 15:26:34.264  1027  1771 V SIM_STK : Menu title from STK is T-Mobile
08-25 15:26:34.264  1027  1771 V SIM_STK : Menu title from STK is T-Mobile
08-25 15:26:34.269  8246  8246 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 15:26:34.271  2084  2084 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 15:26:34.271  2084  2084 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-25 15:26:34.274  1597  1636 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:26:34.274  1597  1636 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 15:26:34.274  1597  1636 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 15:26:34.274  1597  1636 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 15:26:34.278  1597  1597 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 15:26:34.278  1597  1597 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-25 15:26:34.278  1888  1888 D SplitUIManager: split_name #11 / not available #0
08-25 15:26:34.278  1888  1888 I SplitUIService: split app #11
08-25 15:26:34.278  1597  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 15:26:34.279  1597  1636 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 15:26:34.279  1597  1636 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 15:26:34.279  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.285  1027  1957 I ActivityManager: Killing 7361:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-25 15:26:34.326  1027  2010 V SIM_STK : Menu title from STK is T-Mobile
,08-25 15:26:34.328  1027  1084 W InputMethodInfo: Duplicated subtype definition found: , voice
08-25 15:26:34.345  1027  1101 I art     : Explicit concurrent mark sweep GC freed 80721(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 3.165ms total 310.133ms
,08-25 15:26:34.354  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 15:26:34.354  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-25 15:26:34.354  1027  1027 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 15:26:34.388  1597  1597 D KeyguardModel: handleShortcutListChanged...
08-25 15:26:34.388  1597  1597 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-25 15:26:34.399  1027  2023 W libprocessgroup: failed to open /acct/uid_10005/pid_7361/cgroup.procs: No such file or directory
08-25 15:26:34.399  2084  2084 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-25 15:26:34.402  1027  2029 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 15:26:34.402  1027  1572 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-25 15:26:34.403  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 15:26:34.403  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 15:26:34.403  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 15:26:34.403  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 15:26:34.404  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 15:26:34.404  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 15:26:34.404  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 15:26:34.404  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 15:26:34.404  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 15:26:34.404  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 15:26:34.404  7762  7762 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 15:26:34.405  1597  1636 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 15:26:34.405  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.406  2237  2237 I ConfigService: onDestroy
08-25 15:26:34.407  1597  1636 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 15:26:34.407  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.408  1597  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 15:26:34.408  1597  1636 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 15:26:34.409  1597  1636 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-25 15:26:34.409  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.410  1597  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 15:26:34.410  1597  1636 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 15:26:34.411  1835  8323 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-25 15:26:34.414  1597  1636 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 15:26:34.414  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.415  1597  1636 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 15:26:34.415  1597  1636 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 15:26:34.416  1597  1636 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 15:26:34.416  1597  1636 D KeyguardModel: createShortcutInfo...
08-25 15:26:34.428  1597  1597 D KeyguardModel: handleShortcutListChanged...
08-25 15:26:34.428  1597  1597 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-25 15:26:34.451  6109  8329 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-25 15:26:34.458  1835  8330 I PeopleContactsSync: CP2 sync disabled
,08-25 15:26:34.468  1835  4682 I Icing   : doRemovePackageData com.test.thalitest
08-25 15:26:34.477  7148  7148 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-25 15:26:34.500  1835  8328 I art     : Explicit concurrent mark sweep GC freed 32999(2MB) AllocSpace objects, 17(268KB) LOS objects, 51% free, 30MB/62MB, paused 1.824ms total 35.120ms
,08-25 15:26:34.517  2198  8333 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-25 15:26:34.518  2084  2084 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-25 15:26:34.522  8291  8291 D AndroidRuntime: Shutting down VM
08-25 15:26:34.522  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 15:26:34.525  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 15:26:34.527  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 15:26:34.529  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 15:26:34.531  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-25 15:26:34.538  1027  1568 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8334 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 15:26:34.565  2084  2084 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 15:26:34.565  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 15:26:34.567  2084  2310 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 15:26:34.568  2084  2310 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-25 15:26:34.574  1027  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8352 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-25 15:26:34.581  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-25 15:26:34.582  2084  2084 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 15:26:34.582  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 15:26:34.584  1027  1090 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1539d522 u0 com.lge.launcher2/.Launcher t5} time:208327
08-25 15:26:34.585  1835  8328 W GmsApplication: Using Auth Proxy for data requests.
08-25 15:26:34.590  2084  2084 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-25 15:26:34.591  2657  2657 D [Concierge]Service: onStartCommand(). Type : 8
08-25 15:26:34.591  2657  2657 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-25 15:26:34.592  2657  2657 D [Concierge]Service: Update widget ID : 11
08-25 15:26:34.594  2084  2084 D [Concierge]WidgetView: change position of spinner
08-25 15:26:34.594  1835  8328 W GmsApplication: Using Auth Proxy for data requests.
08-25 15:26:34.595  2084  2084 I [Concierge]WidgetView: initWebView(). Time : 1472131594595
,08-25 15:26:34.596  2657  2657 D [Concierge]Service: onStartCommand(). Type : 0
08-25 15:26:34.606  8334  8334 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:26:34.606  8334  8334 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 15:26:34.607  8334  8334 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 15:26:34.607  8334  8334 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 15:26:34.613  1027  1084 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:26:34.616  1027  1084 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 15:26:34.629  2084  2084 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 763076330
08-25 15:26:34.629  2084  2084 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-25 15:26:34.629  2084  2084 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 15:26:34.632  2084  2084 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1fa7ac6a
08-25 15:26:34.632  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-25 15:26:34.634  2084  2084 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 15:26:34.634  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 15:26:34.639  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 15:26:34.640  2084  2084 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-25 15:26:34.640  2084  2084 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 15:26:34.640  2084  2084 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472131415130, New one : 1472131594595
08-25 15:26:34.640  2084  2084 D [Concierge]WidgetView: Unregister all receivers
08-25 15:26:34.641  2084  2084 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 15:26:34.641  2084  2084 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 15:26:34.642  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 15:26:34.645  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-25 15:26:34.646  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 15:26:34.647  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-25 15:26:34.648  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 15:26:34.649  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-25 15:26:34.651  1027  1771 I ActivityManager: Killing 7790:com.google.android.talk/u0a72 (adj 15): empty #17
08-25 15:26:34.655  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 15:26:34.655  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 15:26:34.684  2084  2084 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-25 15:26:34.691  2084  2084 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 15:26:34.692  2084  2084 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-25 15:26:34.693  2084  2084 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 15:26:34.708  1027  1568 W libprocessgroup: failed to open /acct/uid_10072/pid_7790/cgroup.procs: No such file or directory
,08-25 15:26:34.711  8334  8334 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-25 15:26:34.713  2084  2084 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f19c667 time:208456
08-25 15:26:34.720  8334  8334 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 15:26:34.739  8334  8334 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 15:26:34.758  8334  8334 D LgDataFeature: LgDataFeature() Constructor: none
08-25 15:26:34.758  8334  8334 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 15:26:34.800  1027  1532 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2412 sc=60 link=72 tx=105.0, 0.0, 0.0  rx=99.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1042187728] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 15:26:34.802  1027  1532 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2412 sc=60 link=72 tx=105.0, 0.0, 0.0  rx=99.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1042187726] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 15:26:34.803  1027  1532 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 15:26:34.816  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 15:26:34.817  8334  8334 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-25 15:26:34.831  1027  1044 I ActivityManager: Killing 7887:com.android.vending/u0a44 (adj 15): empty #17
,08-25 15:26:34.851  1027  1533 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-25 15:26:34.879  2084  2084 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-25 15:26:34.886  1027  1538 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:26:34.926  2084  2940 I GBoardtInterface: onReloaded()

```
