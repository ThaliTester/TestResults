#### Test 82914073b1ed9e5_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-31 18:49:00.080  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-31 18:49:00.080  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-31 18:49:00.080  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-31 18:49:00.081  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-31 18:49:00.094  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-31 18:49:00.094  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-31 18:49:00.097  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-31 18:49:00.097  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 18:49:00.396  6718  6718 D AndroidRuntime: 
08-31 18:49:00.396  6718  6718 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 18:49:00.399  6718  6718 D AndroidRuntime: CheckJNI is OFF
08-31 18:49:00.523  6718  6718 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 18:49:00.528  1035  1740 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 18:49:00.538  1976  3994 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-31 18:49:00.541  1035  1740 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-31 18:49:00.542  1035  1740 D ActivityManager: setTaskToReturnTo : TaskRecord{29939dac #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 18:49:00.542  1035  1740 D ActivityManager: setTaskToReturnTo : TaskRecord{29939dac #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-31 18:49:00.543  1035  1740 D WindowStateEx: AppWindowTokenEx init.. 
08-31 18:49:00.544   331   345 E GBMv2   : DFP En is all cleared set to be enabled
08-31 18:49:00.577  1035  1740 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6733 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 18:49:00.578  6718  6718 D AndroidRuntime: Shutting down VM
08-31 18:49:00.633  1976  3994 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-31 18:49:00.634  1976  3994 D SplitWindowPolicy: topRunningActivity=ActivityInfo{34135d77 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 18:49:00.635  1976  1992 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-31 18:49:00.635  1976  1992 D SplitWindowPolicy: topRunningActivity=ActivityInfo{13c33de4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-31 18:49:00.695  6733  6733 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-31 18:49:00.795  6733  6733 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 18:49:00.805  6733  6733 I LibraryLoader: Loading: webviewchromium
,08-31 18:49:00.809  6733  6733 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 632-636)
08-31 18:49:00.809  6733  6733 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 18:49:00.826  6733  6733 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3938f53d}
,08-31 18:49:00.827  6733  6733 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 18:49:00.827  6733  6733 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 18:49:00.838  6733  6733 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 18:49:00.839  6733  6733 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 18:49:00.849  6733  6733 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 18:49:00.850  6733  6733 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-31 18:49:00.853  6733  6733 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-31 18:49:00.858   313  1383 V AudioPolicyService: registerClient() client 0xb558a220, uid 10118
08-31 18:49:00.863  1035  1097 D BluetoothManagerService: Message: 20
08-31 18:49:00.863  1035  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2118ecd6:true
,08-31 18:49:00.877  6733  6733 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 18:49:00.877  6733  6733 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 18:49:00.877  6733  6733 I Adreno-EGL: Build Date: 12/12/14 금
08-31 18:49:00.877  6733  6733 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 18:49:00.877  6733  6733 I Adreno-EGL: Remote Branch: 
08-31 18:49:00.877  6733  6733 I Adreno-EGL: Local Patches: 
08-31 18:49:00.877  6733  6733 I Adreno-EGL: Reconstruct Branch: 
,08-31 18:49:00.952  6733  6774 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-31 18:49:00.958  6733  6733 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-31 18:49:00.986  6733  6733 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 18:49:00.992  6733  6733 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 18:49:00.995  6733  6733 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-31 18:49:00.998  6733  6733 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-31 18:49:00.998  6733  6733 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-31 18:49:01.012  6733  6733 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-31 18:49:01.020  6733  6733 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 18:49:01.020  6733  6733 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 18:49:01.057  6733  6786 D OpenGLRenderer: Render dirty regions requested: true
08-31 18:49:01.058  6733  6786 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 18:49:01.063  6733  6786 D OpenGLRenderer: Enabling debug mode 0
,08-31 18:49:01.076  6733  6733 D Atlas   : Validating map...
,08-31 18:49:01.080  1035  1050 D SplitWindow: check instance of lgWin Window{10dfa7e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 18:49:01.145  6733  6784 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 18:49:01.146  6733  6784 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 18:49:01.211  1035  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +580ms (total +667ms)
,08-31 18:49:01.213  1035  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{cecba75 u0 com.test.thalitest/.MainActivity t6} time:181041
08-31 18:49:01.216  6733  6733 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1c4c130 time:181043
08-31 18:49:01.347  6733  6733 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 18:49:01.529  6733  6800 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,08-31 18:49:01.547  6733  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 18:49:01.547  6733  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 18:49:01.547  6733  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 18:49:01.547  6733  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 18:49:01.547  6733  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 18:49:01.547  6733  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@211ebef4 added. We now have 1 listener(s)
,08-31 18:49:01.554  1035  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:01.557  6733  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-31 18:49:01.561  6733  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-31 18:49:01.564  6733  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:01.564  6733  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 18:49:01.575  6733  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23205a63 added. We now have 1 listener(s)
08-31 18:49:01.576  6733  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:49:01.582  1035  1546 D WifiService: New client listening to asynchronous messages
08-31 18:49:01.586  6733  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:49:01.586  6733  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-31 18:49:01.589  6733  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 18:49:01.589  6733  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 18:49:01.589  6733  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 18:49:01.602  6733  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:01.602  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:01.604  6733  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-31 18:49:01.617  6733  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 18:49:01.618  6733  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:01.618  6733  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:01.618  6733  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:01.618  6733  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:01.618  6733  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:01.618  6733  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:01.618  6733  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:01.618  6733  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:01.619  6733  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 18:49:01.619  6733  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 18:49:01.623  6733  6800 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 18:49:01.626  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:01.630  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:01.668  6733  6784 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-31 18:49:01.668  6733  6784 I chromium: 
,08-31 18:49:01.739  6733  6733 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 18:49:01.826  6733  6733 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-31 18:49:01.826  6733  6733 I chromium: 
,08-31 18:49:02.049   331   347 E GBMv2   : DFP En is all cleared set to be enabled
08-31 18:49:02.049   331   347 E GBMv2   : Set value is all cleared set the max
08-31 18:49:02.049   331   347 I GBMv2   : DFP Enabled. Ignore VFP set
,08-31 18:49:02.374  6733  6803 W jxcore-log: Initializing JXcore engine
,08-31 18:49:02.374  6733  6803 W jxcore-log: JXcore engine is ready
08-31 18:49:02.439  6803  6803 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8337]" dev="sockfs" ino=8337 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-31 18:49:02.439  6803  6803 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-31 18:49:02.439  6803  6803 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8426]" dev="sockfs" ino=8426 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-31 18:49:02.439  6803  6803 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-31 18:49:02.449  6803  6803 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30172]" dev="sockfs" ino=30172 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-31 18:49:02.474  6733  6803 W jxcore-log: Starting JXcore engine
,08-31 18:49:02.606  6733  6803 W jxcore-log: Platform android
08-31 18:49:02.606  6733  6803 W jxcore-log: 
08-31 18:49:02.606  6733  6803 W jxcore-log: Process ARCH arm
08-31 18:49:02.606  6733  6803 W jxcore-log: 
,08-31 18:49:02.825  6733  6803 I jxcore-log: JXcore Cordova bridge is ready!
08-31 18:49:02.825  6733  6803 I jxcore-log: 
08-31 18:49:02.825  6733  6803 W jxcore-log: JXcore engine is started
,08-31 18:49:02.836  6733  6800 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-31 18:49:02.838  6733  6733 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 18:49:12.409  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 18:49:12.409  6733  6803 I jxcore-log: 
,08-31 18:49:12.412  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 18:49:12.412  6733  6803 I jxcore-log: 
08-31 18:49:12.416  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:12.416  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:12.416  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:12.416  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:12.416  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:12.416  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:12.416  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:12.416  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:12.418  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:12.420  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 18:49:12.420  6733  6803 I jxcore-log: 
08-31 18:49:12.422  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 18:49:12.422  6733  6803 I jxcore-log: 
,08-31 18:49:12.927  6733  6803 D executeNativeTests: Running unit tests
,08-31 18:49:13.007  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:13.007  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 added. We now have 2 listener(s)
08-31 18:49:13.008  1035  2115 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 18:49:13.009  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:13.009  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:13.009  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:13.010  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:13.010  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad added. We now have 2 listener(s)
08-31 18:49:13.010  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:13.010  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:49:13.013  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.016  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:13.016  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.016  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.016  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:13.016  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:13.016  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.016  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:13.016  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:13.017  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.017  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:13.019  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.020  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:13.029  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 18:49:13.032  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 18:49:13.032  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 18:49:13.034  6733  6803 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 18:49:13.036  6733  6803 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 18:49:13.036  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 18:49:13.036  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 18:49:13.036  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 18:49:13.037  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.038  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.038  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.038  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.038  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.038  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:13.038  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:13.039  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 removed from the list
08-31 18:49:13.039  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.039  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad removed from the list
08-31 18:49:13.039  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.039  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.039  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.039  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.040  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.040  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.040  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.040  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.042  6733  6803 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 18:49:13.042  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.042  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.042  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 18:49:13.043  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.043  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.043  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.043  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.043  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.043  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.043  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.043  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.043  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.043  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.043  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.043  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.043  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.043  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.043  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 18:49:13.047  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 18:49:13.048  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.048  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.048  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.048  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.048  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.048  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.048  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.048  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.048  6733  6803 E org.thaliproject.p2p.,btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.048  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.048  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.048  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.048  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.048  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.051  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.051  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.051  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.051  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.052  6733  6803 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 18:49:13.054  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.055  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:13.055  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.055  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.055  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:13.055  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:13.055  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.055  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:13.055  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:13.057  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.057  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:13.058  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.059  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.059  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:49:13.059  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 18:49:13.059  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:49:13.059  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.059  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 18:49:13.062  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 18:49:13.065  1035  2091 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:13.071  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 18:49:13.077  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 18:49:13.080  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-31 18:49:13.082  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:49:13.082  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:13.084  6733  6803 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 18:49:13.084  6733  6803 I io.jxcore.node.ConnectionHelper: start: OK
08-31 18:49:13.088  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 18:49:13.088  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.088  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.088  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.088  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.089  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:13.089  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.089  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.089  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.089  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.089  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.089  6733  6803 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 18:49:13.090  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.093  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:13.093  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.093  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.093  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:13.093  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:13.093  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.093  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:13.093  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:13.094  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.094  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:13.094  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:49:13.094  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 18:49:13.094  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:49:13.094  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.094  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 18:49:13.096  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.097  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.097  6733  6803 I org.tha,liproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:49:13.098  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:13.099  6733  6803 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 18:49:13.099  6733  6803 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 18:49:13.101  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.101  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.101  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.101  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.101  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.101  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:13.101  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.101  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.101  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.101  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.101  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.102  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.102  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.103  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.103  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.104  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.105  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.105  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.105  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.105  6733  6803 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 18:49:13.199  1035  1740 I art     : Explicit concurrent mark sweep GC freed 30610(1437KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.997ms total 87.536ms
,08-31 18:49:13.202  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.205  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:13.205  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.205  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.205  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:13.205  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:13.205  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.205  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:13.205  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:13.207  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.207  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:13.207  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:49:13.207  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 18:49:13.207  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:49:13.207  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.207  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 18:49:13.211  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.213  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:49:13.213  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.213  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 18:49:13.214  6733  6803 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 18:49:13.214  6733  6803 I io.jxcore.node.ConnectionHelper: start: OK
08-31 18:49:13.214  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.214  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.215  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.215  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.215  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.215  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.215  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.215  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.215  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:13.215  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.215  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.215  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.215  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.215  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.216  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.216  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.217  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.217  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.217  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.217  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.217  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.217  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.218  6733  6803 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 18:49:13.218  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.218  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.218  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipp,ing...
08-31 18:49:13.218  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.219  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.219  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.219  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.219  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.219  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.219  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.219  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.219  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.219  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.219  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.224  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.224  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:49:13.229  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.229  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.229  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.229  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.230  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 18:49:13.230  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.230  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.230  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.230  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.230  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.230  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.230  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.230  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.230  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.230  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:49:13.230  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.230  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.230  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.230  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.231  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.231  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.232  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.232  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.232  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.232  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.232  6733  6803 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 18:49:13.233  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.233  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.233  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.233  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.233  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.233  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.233  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.233  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.233  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.233  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.233  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.233  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.233  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.233  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.234  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.234  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.234  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.234  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.234  6733  6803 I org.thaliproject.p2p.btco,nnectorlib.DiscoveryManager: dispose
08-31 18:49:13.234  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.235  6733  6803 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 18:49:13.235  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.235  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.235  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.236  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.236  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.236  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.237  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.237  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.237  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.237  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.237  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.237  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.237  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.237  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.238  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.238  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.238  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.238  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.238  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.238  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.239  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 18:49:13.239  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 18:49:13.239  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 18:49:13.239  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 18:49:13.239  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 18:49:13.239  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 18:49:13.239  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.239  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.239  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.240  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.240  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.240  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.240  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.240  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.240  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.240  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.240  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.240  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.240  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.240  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.241  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.241  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.241  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.241  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.241  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.241  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.242  6733  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:49:13.242  6733  6803 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 18:49:13.242  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 18:49:13.245  6733  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:49:13.245  6733  6803 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 18:49:13.245  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 18:49:13.246  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 18:49:13.246  6733  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 18:49:13.246  6733  6803 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 18:49:13.246  6733  6803 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 18:49:13.246  6733  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:49:13.246  6733  6803 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 18:49:13.246  6733  6803 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 18:49:13.246  6733  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:49:13.246  6733  6803 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 18:49:13.246  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 18:49:13.250  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 18:49:13.251  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 18:49:13.251  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 18:49:13.252  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 18:49:13.252  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 18:49:13.252  6733  6803 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 18:49:13.252  6733  6803 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 18:49:13.252  6733  6803 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 18:49:13.254  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.254  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.254  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.254  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.254  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.254  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.254  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 18:49:13.255  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.255  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.255  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.255  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.255  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.255  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.255  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.255  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.257  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.257  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.258  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.258  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.258  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.258  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.258  6733  6803 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 18:49:13.258  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.258  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.259  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.260  6733  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-31 18:49:13.262  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.262  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.262  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.262  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.262  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.262  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.262  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.263  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.263  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.263  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.263  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.263  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.263  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.264  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.264  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.264  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.264  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.264  6733  6803 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 18:49:13.265  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.265  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.265  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.266  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.266  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.266  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.266  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.266  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.266  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.266  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.266  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.266  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.266  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.266  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.267  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.267  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.267  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.267  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.267  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.267  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
,08-31 18:49:13.269  6733  6803 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 18:49:13.269  6733  6803 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 18:49:13.269  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 18:49:13.269  6733  6803 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 18:49:13.269  6733  6803 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 18:49:13.269  6733  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 18:49:13.269  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 18:49:13.269  6733  6803 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 18:49:13.269  6733  6803 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 18:49:13.269  6733  6803 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 18:49:13.269  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 18:49:13.269  6733  6803 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 18:49:13.269  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.269  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.269  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.270  6733  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-31 18:49:13.270  6733  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-31 18:49:13.270  6733  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
08-31 18:49:13.273  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.273  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.273  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.273  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.273  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.273  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.273  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.273  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.273  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.273  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.273  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.274  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.274  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.274  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.274  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.274  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.274  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.274  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.274  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.274  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.274  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.275  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.275  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.275  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.275  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.275  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.275  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.275  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.275  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.275  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.275  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.275  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.275  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.275  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.275  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.276  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.276  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.276  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.276  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.276  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.276  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.276  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.276  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.276  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.276  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.276  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.277  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.277  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.278  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.278  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.278  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.278  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.279  6733  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 18:49:13.279  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.283  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 18:49:13.283  6733  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 18:49:13.283  6733  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 18:49:13.294  6733  6733 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 18:49:13.294  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 18:49:13.294  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 18:49:13.294  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.295  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 18:49:13.295  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 18:49:13.295  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 18:49:13.295  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.295  6733  6803 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 18:49:13.295  6733  6733 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 18:49:13.295  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.295  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.295  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 18:49:13.295  6733  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 18:49:13.295  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 18:49:13.296  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 18:49:13.296  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:13.296  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:13.296  6733  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 18:49:13.296  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.296  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.297  6733  6803 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:49:13.301  6733  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:49:13.301  6733  6733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 18:49:13.301  6733  6733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 18:49:13.301  6733  6815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 18:49:13.302  6733  6815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 18:49:13.303  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.303  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.303  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.303  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.304  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.304  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.304  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.304  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.304  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.304  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.304  6733  6733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 18:49:13.304  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.304  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.305  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.305  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.305  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.305  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.305  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.305  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.305  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.306  6733  6803 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 18:49:13.313  6733  6803 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 18:49:13.313  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 18:49:13.313  6733  6803 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 18:49:13.314  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.314  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.314  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.315  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.315  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.315  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.315  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.315  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.316  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.316  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.316  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.316  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.316  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.316  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.318  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.318  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.318  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.318  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.319  1035  2068 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 18:49:13.319  1035  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:13.321  1035  2115 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:13.322  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.322  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.322  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.323  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.323  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.323  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.324  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31 18:49:13.324  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.324  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.324  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.324  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.324  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.324  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.324  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.329  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.329  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.329  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.329  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.330  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:13.330  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:13.330  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:13.330  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:13.330  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.330  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.330  6733  6803 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f05f0c4 not in the list
08-31, 18:49:13.330  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.330  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.330  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:13.330  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.330  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.330  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:13.330  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:13.330  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:13.330  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:13.330  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:13.330  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bad not in the list
08-31 18:49:13.331  6733  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 18:49:13.331  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 18:49:13.332  6733  6803 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-31 18:49:13.332  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 18:49:13.332  6733  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 18:49:13.332  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 18:49:13.333  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-31 18:49:13.333  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 18:49:13.334  6733  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 18:49:13.334  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 18:49:13.334  6733  6803 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1,
08-31 18:49:13.334  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 18:49:13.334  6733  6803 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 18:49:13.334  6733  6803 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-31 18:49:13.334  6733  6803 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 18:49:13.334  6733  6803 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 18:49:13.335  6733  6803 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-31 18:49:13.335  6733  6803 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 18:49:13.335  6733  6803 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 18:49:13.335  6733  6803 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing,
,08-31 18:49:13.336  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:13.336  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ae0483a added. We now have 2 listener(s)
08-31 18:49:13.336  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:13.340  6733  6813 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-31 18:49:13.341  6733  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-31 18:49:13.342  6733  6803 D BluetoothAdapter: enable(): BT is already enabled..!
08-31 18:49:13.342  1035  2068 D WifiServiceImplEx: setWifiEnabled: true pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 18:49:13.343  1035  2068 D WifiService: setWifiEnabled: true pid=6733, uid=10118
08-31 18:49:13.343  1035  2068 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 18:49:13.344  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:13.344  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e5c9ceb added. We now have 3 listener(s)
08-31 18:49:13.344  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:13.346  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:13.346  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e009a48 added. We now have 4 listener(s)
08-31 18:49:13.347  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:13.348  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:13.348  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3d0e1 added. We now have 5 listener(s)
08-31 18:49:13.348  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:13.349  1035  2068 D WifiServiceImplEx: setWifiEnabled: false pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 18:49:13.349  1035  2068 D WifiService: setWifiEnabled: false pid=6733, uid=10118
08-31 18:49:13.349  1035  2068 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 18:49:13.361  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 18:49:13.361  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 18:49:13.362  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 18:49:13.362  1035  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:13.362  1035  1763 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@e8badc3 mBinding = false
08-31 18:49:13.362  1035  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-31 18:49:13.363  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 18:49:13.364  1035  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 18:49:13.364  1035  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 18:49:13.365  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
,08-31 18:49:13.365  1035  1541 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 18:49:13.365  1035  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 18:49:13.365  1035  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 18:49:13.367  1035  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 18:49:13.367  1035  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 18:49:13.371  1035  1097 D BluetoothManagerService: Message: 2
08-31 18:49:13.372  1035  1097 D BluetoothManagerService: Sending off request.
08-31 18:49:13.372  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 18:49:13.372  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 18:49:13.372  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 18:49:13.372  1035  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 18:49:13.372  3893  4024 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 18:49:13.372  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 18:49:13.372  1035  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.372  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.373  2686  2686 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 18:49:13.373  3893  3973 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 18:49:13.373  3893  3973 D BluetoothAdapterProperties: Setting state to 13
08-31 18:49:13.373  3893  3973 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 18:49:13.373  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 18:49:13.373  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 18:49:13.373  3893  3973 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 18:49:13.373  3893  3973 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 18:49:13.373  1035  1541 D WifiNative-wlan0: SET ps 1: returned true
08-31 18:49:13.374   309   892 D CommandListener: Clearing all IP addresses on wlan0
,08-31 18:49:13.376  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:13.376  1035  2802 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.378  3893  3976 D BluetoothAdapterProperties: Scan Mode:20
08-31 18:49:13.378  3893  3973 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 18:49:13.379  3893  3973 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 18:49:13.380  1035  1097 D BluetoothManagerService: Message: 60
08-31 18:49:13.380  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 18:49:13.380  1035  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 18:49:13.380  3893  4208 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 18:49:13.380  3893  4208 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:13.380  3893  4208 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 18:49:13.380  3893  4208 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 18:49:13.380  3893  4208 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 18:49:13.380  3893  4208 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 18:49:13.380  3893  4208 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 18:49:13.380  3893  4208 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 18:49:13.381  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 18:49:13.381  3893  4212 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:13.382  3893  4249 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:13.382  3893  4250 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:13.382  3893  4252 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:13.383  3893  4082 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 18:49:13.384  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 18:49:13.385  3893  4082 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 18:49:13.390  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for m,ultiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.390  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:13.390  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.390  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.390  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:13.390  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:13.390  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.390  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:13.390  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:49:13.392  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.392  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.392  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:13.394  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.396  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.404  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.404  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:13.404  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.404  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.404  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:13.404  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:13.404  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.404  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:13.404  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:49:13.405  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.405  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:13.407  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:13.413  1035  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 18:49:13.413  1035  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-31 18:49:13.416  1035  1584 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-31 18:49:13.425  1035  1092 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6831 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 18:49:13.425  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-9ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.425  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-9ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.425  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 18:49:13.425  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.425  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-31 18:49:13.428  1035  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:13.429  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:13.429  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-31 18:49:13.429  1035  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:13.429  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:13.430  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:13.430  1035  1541 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 18:49:13.430  1035  1540 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.430  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.430  1035  1540 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@888c823
08-31 18:49:13.431  1035  1540 D LGWifiP2pService: P2pDisablingState
08-31 18:49:13.431  1035  1540 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.431  1035  1540 D LGWifiP2pService: p2p socket connection lost
08-31 18:49:13.431  1035  1540 D LGWifiP2pService: P2pDisabledState
08-31 18:49:13.433  1976  1976 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:13.434  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 18:49:13.436  3893  3893 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:13.436  3893  3893 D BluetoothMapService: STATE_TURNING_OFF
08-31 18:49:13.436  3893  3893 V BluetoothMapService: Handler(): got msg=4
08-31 18:49:13.436  3893  3893 D BluetoothMapService: MAP Service closeService in
08-31 18:49:13.436  3893  3893 D BluetoothMapMasInstance: MAP Service shutdown
08-31 18:49:13.436  3893  3893 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 18:49:13.436  3893  3893 V BluetoothMapService: MAP Service closeService out
08-31 18:49:13.436  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.436  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:13.436  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.436  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.436  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:13.436  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:13.436  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:13.436  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:13.436  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:13.437  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.437  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:13.437  3893  3893 V BtOppService: Receiver DISABLED_ACTION 
08-31 18:49:13.437  3893  3893 I BtOppRfcommListener: stopping Accept Thread
08-31 18:49:13.438  3893  3893 V BtOppRfcommListener: close mBtServerSocket
08-31 18:49:13.438  3893  3893 V BtOppRfcommListener: waiting for thread to terminate
08-31 18:49:13.438  3893  4249 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 18:49:13.438  3893  3893 V BtOppRfcommListener: done waiting for thread to terminate
08-31 18:49:13.440  6733  6,733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.440  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:13.440  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.440  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.440  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:13.440  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:13.440  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:13.440  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:13.440  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:13.440  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.440  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:13.441  1035  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 18:49:13.442  1035  1540 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.442  1035  1540 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.442  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 18:49:13.442  2686  2686 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 18:49:13.443  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 18:49:13.443  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 1
,08-31 18:49:13.443  1035  1541 D WifiNative-wlan0: SET ps 1: returned true
08-31 18:49:13.458   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-31 18:49:13.458  1035  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 18:49:13.458  1035  1547 D DSQN    : disableDataServiceNotify
08-31 18:49:13.459  1035  1547 D DSQN    : stop dsqn bin
08-31 18:49:13.460   309  6852 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-31 18:49:13.460  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-31 18:49:13.461  1035  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 18:49:13.466  1035  1092 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 18:49:13.467  3893  3893 V BtOppService: onDestroy
08-31 18:49:13.467  1035  1541 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 18:49:13.468  1035  1541 D WifiNative-p2p0: TERMINATE: returned true
08-31 18:49:13.468  1035  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 18:49:13.468  1035  1541 E WifiStateMachine: useWiFiOffloading() : false
08-31 18:49:13.468  1035  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 18:49:13.468  1035  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 18:49:13.469  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:13.469  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:13.469  1035  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:13.469  1035  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 18:49:13.469  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.469  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.469  1035  2801 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 18:49:13.470  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 18:49:13.470  1035  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 18:49:13.470  1035  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-31 18:49:13.470  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 18:49:13.471  1035  1035 D WifiHS20: hidePasspointNotification off =false
,08-31 18:49:13.472  1976  1976 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 18:49:13.474  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:13.474  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:13.474  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 18:49:13.474  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-31 18:49:13.474  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:13.474  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:13.474  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 18:49:13.475  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 18:49:13.475  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-31 18:49:13.475  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-31 18:49:13.475  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 18:49:13.475  1976  1976 D WfdsService: WifiP2pState is changed : false
08-31 18:49:13.475  1035  1560 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.475  1035  1559 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.475  1976  2322 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 18:49:13.475  1976  2322 D WfdsService: Set the WFDS Monitor: false
08-31 18:49:13.477  3893  3893 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-31 18:49:13.477  1035  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:13.477  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 18:49:13.477  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:13.477  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:13.477  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 18:49:13.477  1976  2322 D WfdsMonitor: WFDS Monitor is stopped
08-31 18:49:13.477  1976  2322 D WfdsService: STATE : WfdsDisabledState - enter
08-31 18:49:13.478  1976  2324 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 18:49:13.478  1976  2741 D CtrlSupplicant: Received on exit socket, terminate
08-31 18:49:13.478  1976  2741 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 18:49:13.478  1976  2741 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 18:49:13.478  1976  2741 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 18:49:13.479  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 18:49:13.479  1035  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 18:49:13.480  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 18:49:13.480  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:13.480  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 18:49:13.481  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 18:49:13.481  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 18:49:13,.481  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 18:49:13.481  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 18:49:13.482  1035  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:13.483  1035  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 18:49:13.483  1035  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:13.485  1976  2322 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 18:49:13.485  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.485  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:13.485  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.485  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.485  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:13.485  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:13.485  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:13.485  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:13.485  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:13.485  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.485  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:13.486  1035  1547 D NetworkManagementService: Removing idletimer
08-31 18:49:13.487  1035  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:13.487  1035  1547 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 18:49:13.488  1035  1541 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:13.488  1035  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:13.488  1881  1881 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:13.488  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 18:49:13.488  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.488  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:13.488  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.488  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.488  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:13.488  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:13.488  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:13.488  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:13.488  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: ,true
08-31 18:49:13.489  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.489  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:13.490  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:13.490  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:13.490  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:13.492  1035  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 18:49:13.493  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 18:49:13.493  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 18:49:13.493  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 18:49:13.493  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-31 18:49:13.509  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:13.509  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 18:49:13.510  6853  6853 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 18:49:13.510  6853  6853 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-31 18:49:13.511  6853  6853 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 18:49:13.511  6853  6853 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-31 18:49:13.512  6853  6853 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 18:49:13.512  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:13.512  6853  6853 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 18:49:13.513  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 18:49:13.513  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:13.514  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:13.514  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 18:49:13.526  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 18:49:13.526  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:13.527  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 18:49:13.542  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 18:49:13.543  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:13.543  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:13.553  2686  2686 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 18:49:13.553  2686  2686 I wpa_supplicant: monitor socket send errors count : 1
08-31 18:49:13.553  2686  2686 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1976-2\x00 that cannot receive messages
,08-31 18:49:13.554  1035  2736 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 18:49:13.555  1035  2736 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 18:49:13.567  6831  6831 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-31 18:49:13.568  6831  6831 W LG Account v2.2: No ProfileInfo entries
08-31 18:49:13.568  6831  6831 I LG Account v2.2: isEnabled: false
08-31 18:49:13.568  6831  6831 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-31 18:49:13.568  6831  6831 I Feature : [Lifetracker]Country: EU
08-31 18:49:13.568  6831  6831 I Feature : [Lifetracker]Operator: OPEN
08-31 18:49:13.568  6831  6831 I Feature : [Lifetracker]Ranking support: false
08-31 18:49:13.568  6831  6831 I Feature : [Lifetracker]Comfort support: false
08-31 18:49:13.568  6831  6831 I Feature : [Lifetracker]Accessory: true
08-31 18:49:13.568  6831  6831 I Feature : [Lifetracker]Health device: true
08-31 18:49:13.568  6831  6831 I Feature : [Lifetracker]Extra Pedometer: false
08-31 18:49:13.569  6831  6831 I Feature : [Lifetracker]Blood glucose device: false
08-31 18:49:13.569  6831  6831 I Feature : [Lifetracker]Device Number: 3
08-31 18:49:13.574  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:13.581  1035  2802 D DhcpStateMachine: StoppedState
,08-31 18:49:13.581  1035  2802 D DhcpStateMachine: StoppedState{ when=-137ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:13.594  2686  2686 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 18:49:13.595  2686  2686 W wpa_supplicant: USIM:  scard_deinit function
,08-31 18:49:13.595  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 18:49:13.595  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 18:49:13.595  1035  2736 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 18:49:13.595  1035  2736 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 18:49:13.596  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:13.596  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:13.596  1035  1097 D Tethering: InitialState.processMessage what=4
08-31 18:49:13.597  1035  1541 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=193411
08-31 18:49:13.597  1035  1541 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=193411
08-31 18:49:13.598  1035  1541 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=193412  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 18:49:13.598  1035  1541 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=193412  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 18:49:13.605  1035  1740 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6873 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 18:49:13.607  1035  1740 I ActivityManager: Killing 6233:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-31 18:49:13.615  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 18:49:13.644  2686  2686 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 18:49:13.644  1035  2736 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-31 18:49:13.644  1035  2736 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 18:49:13.644  1035  2736 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 18:49:13.645  1035  1541 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-31 18:49:13.653  1035  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 18:49:13.658  1035  1050 W libprocessgroup: failed to open /acct/uid_10014/pid_6233/cgroup.procs: No such file or directory
,08-31 18:49:13.665  1035  1097 D BluetoothManagerService: Message: 20
08-31 18:49:13.666  1035  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b1d00ca:true
08-31 18:49:13.666  3893  3893 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 18:49:13.666  3893  3893 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-31 18:49:13.666  3893  3893 V BluetoothPbapReceiver: ***********state = 13
08-31 18:49:13.668  3893  3893 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 18:49:13.670  3893  3893 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:13.670  3893  3893 V BluetoothPbapService: state: 13
08-31 18:49:13.670  3893  3893 V BluetoothPbapService: Pbap Service closeService in
08-31 18:49:13.673  2244  2244 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 18:49:13.673  3893  3893 V BluetoothPbapService: successfully stopped pbap service
08-31 18:49:13.673  3893  3893 V BluetoothPbapService: Pbap Service closeService out
08-31 18:49:13.674  3893  3893 V BluetoothPbapService: Pbap Service onDestroy
08-31 18:49:13.674  3893  3893 V BluetoothPbapService: Pbap Service closeService in
08-31 18:49:13.674  3893  3893 V BluetoothPbapService: Pbap Service closeService out
08-31 18:49:13.674  3893  3893 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 18:49:13.685  1035  1097 D BluetoothManagerService: Message: 30
,08-31 18:49:13.692  1035  1097 D BluetoothManagerService: Message: 30
08-31 18:49:13.695  6853  6853 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 18:49:13.696  6853  6853 D BluetoothMap: Create BluetoothMap proxy object
08-31 18:49:13.697  1035  1097 D BluetoothManagerService: Message: 30
08-31 18:49:13.702  1035  1097 D BluetoothManagerService: Message: 30
,08-31 18:49:13.704  6853  6853 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 18:49:13.705  6853  6853 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-31 18:49:13.719  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 18:49:13.721  6853  6853 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-31 18:49:13.722  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 18:49:13.723  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:13.725  1035  1995 I ActivityManager: Killing 6310:com.android.defcontainer/u0a4 (adj 15): empty #17
08-31 18:49:13.726  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-31 18:49:13.758  1035  2004 W libprocessgroup: failed to open /acct/uid_10004/pid_6310/cgroup.procs: No such file or directory
,08-31 18:49:13.761  1035  1541 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 18:49:13.761  1035  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 18:49:13.761  1035  1541 E WifiStateMachine: useWiFiOffloading() : false
08-31 18:49:13.761  1035  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 18:49:13.763  1976  1976 D WfdsService: Supplicant Connection state is changed : false
08-31 18:49:13.763  1976  2322 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 18:49:13.763  1976  2322 D WfdsService: Set the WFDS Monitor: false
08-31 18:49:13.763  1976  2322 D WfdsMonitor: WFDS Monitor is stopped
08-31 18:49:13.764  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:13.764  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 18:49:13.764  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 18:49:13.765  1035  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 18:49:13.765  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:13.765  1035  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 18:49:13.767  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.767  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:13.767  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.767  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.767  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:13.767  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:13.767  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:13.767  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:13.767  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:13.769  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:13.769  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:13.769  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:13.769  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:13.769  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:13.769  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:13.769  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:13.769  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:13.769  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:13.772  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-31 18:49:13.785  6853  6853 D BluetoothInputDevice: Proxy object connected
08-31 18:49:13.786  6853  6853 D HidProfile: Bluetooth service connected
,08-31 18:49:13.787  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 18:49:13.788  6853  6853 D PanProfile: Bluetooth service connected
08-31 18:49:13.789  6853  6853 D BluetoothMap: Proxy object connected
08-31 18:49:13.790  6853  6853 D MapProfile: Bluetooth service connected
08-31 18:49:13.790  6853  6853 D BluetoothMap: getConnectedDevices()
08-31 18:49:13.790  6853  6853 D BluetoothMap: Bluetooth is Not enabled
08-31 18:49:13.802  6733  6733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 18:49:13.803  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 18:49:13.844  6853  6853 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:13.844  6853  6853 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 18:49:13.855  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:13.856  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 18:49:13.858  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 18:49:13.864  6853  6853 D BluetoothPermissionRequest: onReceive
08-31 18:49:13.868  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 18:49:13.875  1035  1740 I ActivityManager: Killing 6460:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-31 18:49:13.881  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 18:49:13.965  1035  1541 E WifiStateMachine:  InitialState CMD_ON_QUIT 0 0
,08-31 18:49:13.967  1035  1541 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-31 18:49:13.968  3893  3893 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 18:49:13.968  3893  3893 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-31 18:49:13.968  1035  1541 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:13.969  1035  1762 W libprocessgroup: failed to open /acct/uid_10008/pid_6460/cgroup.procs: No such file or directory
08-31 18:49:13.970  1035  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:13.970  3893  3893 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 18:49:13.980  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=595780445, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
08-31 18:49:13.982  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{36ef54d2 type 2 when 193742 com.google.android.gms} when 193742
08-31 18:49:14.103  1035  1993 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6904 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-31 18:49:14.104  3893  3893 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:14.104  3893  3893 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 18:49:14.107  3893  3893 V BluetoothFtpService: Ftp Service onStartCommand
08-31 18:49:14.107  3893  3893 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 18:49:14.108  3893  3893 V BluetoothFtpService: Ftp Service closeService
08-31 18:49:14.108  3893  3893 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 18:49:14.111  3893  3893 V BluetoothFtpService: successfully stopped ftp service
08-31 18:49:14.111  3893  3893 V BluetoothFtpService: Ftp Service onDestroy
08-31 18:49:14.111  3893  3893 V BluetoothFtpService: Ftp Service closeService
08-31 18:49:14.116   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 476us total 23.527ms
08-31 18:49:14.125  3893  3893 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 18:49:14.125  3893  3893 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 18:49:14.125  3893  3893 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 18:49:14.125  3893  3893 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:14.125  3893  3893 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 18:49:14.125  3893  3893 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-31 18:49:14.127  3893  3893 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:14.127  3893  3893 V BluetoothSapService: state: 13
08-31 18:49:14.127  3893  3893 V BluetoothSapService: Stopping SAP server process
08-31 18:49:14.128  3893  3893 V BluetoothSapService: Sap Service closeSapService in
08-31 18:49:14.128  3893  3893 V BluetoothSapService: Close listen Socket : 
08-31 18:49:14.129  3893  3893 V BluetoothSapService: Close rfcomm Socket : 
08-31 18:49:14.129  3893  3893 V BluetoothSapService: Close sapd  Socket : 
08-31 18:49:14.131  3893  3893 V BluetoothSapService: Sap Service closeSapService out
08-31 18:49:14.131  3893  3893 V BluetoothSapService: Sap Service onDestroy
08-31 18:49:14.131  3893  3893 V BluetoothSapService: Sap Service closeSapService in
08-31 18:49:14.131  3893  3893 V BluetoothSapService: Close listen Socket : 
08-31 18:49:14.131  3893  3893 V BluetoothSapService: Close rfcomm Socket : 
08-31 18:49:14.131  3893  3893 V BluetoothSapService: Close sapd  Socket : 
08-31 18:49:14.132  3893  3893 V BluetoothSapService: Sap Service closeSapService out
08-31 18:49:14.140   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 23.145ms
,08-31 18:49:14.163   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 20.732ms
,08-31 18:49:14.208  1035  1993 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6925 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 18:49:14.235  6904  6904 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 18:49:14.257  6904  6904 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-31 18:49:14.284  6925  6925 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 18:49:14.292  6904  6904 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-31 18:49:14.292  6904  6904 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 18:49:14.293  6904  6904 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 18:49:14.293  6904  6904 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 18:49:14.293  6904  6904 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 18:49:14.295  6904  6904 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-31 18:49:14.299  6904  6904 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 18:49:14.300  1035  2091 I ActivityManager: Killing 6042:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-31 18:49:14.390  3893  3976 D bt_hci_bdroid: cleanup
,08-31 18:49:14.390  3893  4084 I bt_lpm  : LPM is already off!!!
08-31 18:49:14.391  3893  4201 I bt_userial_mct: exiting userial_read_thread
08-31 18:49:14.391  3893  4201 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 18:49:14.391  3893  4082 W bt-btif : ag scb idx 1 not allocated
,08-31 18:49:14.391  3893  4082 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 18:49:14.391  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:14.391  3893  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:49:14.391  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:14.391  3893  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:49:14.391  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:14.391  3893  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 18:49:14.391  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:14.391  3893  3976 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 18:49:14.391  3893  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 18:49:14.392  3893  4084 I bt_vendor: hw_epilog_process
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:14.392  3893  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 18:49:14.392  3893  4082 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 18:49:14.393  3893  3976 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 18:49:14.393  3893  3976 D bt_userial_mct: userial_close
08-31 18:49:14.393  3893  3976 E bt_userial_mct: pthread_join() FAILED result:3
08-31 18:49:14.393  3893  3976 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 18:49:14.399  1035  1050 W libprocessgroup: failed to open /acct/uid_10011/pid_6042/cgroup.procs: No such file or directory
08-31 18:49:14.427  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 18:49:14.445  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 18:49:14.462  2666  2666 D [Concierge]Service: onStartCommand(). Type : 9
,08-31 18:49:14.475  6904  6904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 18:49:14.478  6904  6904 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-31 18:49:14.481  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 18:49:14.483  6904  6904 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-31 18:49:14.488  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 18:49:14.488  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 18:49:14.488  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:14.497  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:14.506  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:14.512  3893  3976 D bt_hci_bdroid: set_power 0
08-31 18:49:14.512  3893  3976 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 18:49:14.512  3893  3976 I bt_vendor: bluetooth satus is on
08-31 18:49:14.512  3893  3976 I bt_vendor: bt-vendor : resetting BT status
08-31 18:49:14.512  3893  3976 I bt_vendor: Starting hciattach daemon
08-31 18:49:14.512  3893  3976 I bt_vendor: try to set false
08-31 18:49:14.513  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 18:49:14.513  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:14.513  3893  3976 I bt_vendor: Starting hciattach daemon
,08-31 18:49:14.513  3893  3976 I bt_vendor: try to set false
08-31 18:49:14.514  3893  3976 I bt_vendor: cleanup
08-31 18:49:14.514  3893  4082 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 18:49:14.515  3893  3976 I GKI_LINUX: GKI_exit_task 0 done
08-31 18:49:14.515  3893  3976 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-31 18:49:14.516  6904  6904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 18:49:14.516  3893  3973 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 18:49:14.519  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:14.520  3893  3893 D HeadsetService: Received stop request...Stopping profile...
08-31 18:49:14.524  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 18:49:14.524  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 18:49:14.524  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:14.524  3893  3893 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 18:49:14.524  3893  3893 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 18:49:14.524  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22273132
08-31 18:49:14.524  3893  4008 D HeadsetStateMachine: Exit Disconnected: -1
08-31 18:49:14.525  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-31 18:49:14.525  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 18:49:14.528  1881  1881 D BluetoothHeadset: Proxy object disconnected
08-31 18:49:14.528  1881  1881 D BluetoothHeadset: Proxy object disconnected
08-31 18:49:14.529  3893  3893 D A2dpService: Received stop request...Stopping profile...
08-31 18:49:14.529  1881  1881 D BluetoothHeadset: Proxy object disconnected
08-31 18:49:14.529  3893  4045 D A2dpStateMachine: Exit Disconnected: -1
08-31 18:49:14.529  3893  3893 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-31 18:49:14.533  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 18:49:14.535  3893  3973 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 18:49:14.535  3893  3893 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 18:49:14.535  3893  3893 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 18:49:14.535  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22273132
08-31 18:49:14.536  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-31 18:49:14.536  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 18:49:14.537  3893  3893 D HidService: Received stop request...Stopping profile...
08-31 18:49:14.537  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22273132
08-31 18:49:14.539  3893  3893 D HeadsetStateMachine: Unbinding service...
08-31 18:49:14.540  3893  3893 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 18:49:14.540  3893  3893 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 18:49:14.540  3893  3893 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 18:49:14.540  3893  3893 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 18:49:14.540  3893  3893 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 18:49:14.540  3893  3893 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 18:49:14.540  3893  3893 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 18:49:14.541  3893  3893 D HealthService: Received stop request...Stopping profile...
08-31 18:49:14.541  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22273132
08-31 18:49:14.542  3893  3893 D PanService: Received stop request...Stopping profile...
08-31 18:49:14.542  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22273132
08-31 18:49:14.543  3893  3893 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 18:49:14.544  3893  3893 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 18:49:14.544  3893  3893 D BtGatt.GattService: stop()
08-31 18:49:14.544  3893  3893 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 18:49:14.545  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22273132
,08-31 18:49:14.546  3893  3893 D BluetoothMapService: Received stop request...Stopping profile...
08-31 18:49:14.546  3893  3893 D BluetoothMapService: stop()
08-31 18:49:14.546  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:14.547  3893  3893 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 18:49:14.547  6853  6853 D BluetoothInputDevice: Proxy object disconnected
08-31 18:49:14.547  3893  3893 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 18:49:14.547  6853  6853 D HidProfile: Bluetooth service disconnected
08-31 18:49:14.547  6853  6853 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 18:49:14.547  6853  6853 D PanProfile: Bluetooth service disconnected
08-31 18:49:14.549  3893  3893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22273132
08-31 18:49:14.550  3893  3893 I BluetoothA2dpServiceJni: cleanupNative
08-31 18:49:14.551  3893  4046 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-31 18:49:14.552  3893  3893 I GKI_LINUX: GKI_exit_task 2 done
08-31 18:49:14.552  3893  3893 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 18:49:14.552  3893  3893 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 18:49:14.552  3893  3893 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 18:49:14.553  3893  3893 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 18:49:14.553  3893  3893 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 18:49:14.553  3893  3893 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 18:49:14.553  3893  3893 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 18:49:14.553  3893  3893 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 18:49:14.554  3893  3893 V BluetoothMapService: Handler(): got msg=4
08-31 18:49:14.555  3893  3893 D BluetoothMapService: MAP Service closeService in
08-31 18:49:14.555  3893  3893 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 18:49:14.555  3893  3893 V BluetoothMapService: MAP Service closeService out
08-31 18:49:14.555  3893  3973 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 18:49:14.555  3893  3973 D BluetoothAdapterProperties: Setting state to 10
08-31 18:49:14.555  3893  3973 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 18:49:14.555  3893  3893 D BluetoothMapService: cleanup()
08-31 18:49:14.555  3893  3893 D BluetoothMapService: MAP Service closeService in
,08-31 18:49:14.555  3893  3893 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 18:49:14.555  3893  3893 V BluetoothMapService: MAP Service closeService out
08-31 18:49:14.556  3893  3973 I BluetoothAdapterState: Entering OffState
08-31 18:49:14.556  1035  1097 D BluetoothManagerService: Message: 60
08-31 18:49:14.556  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 18:49:14.556  1035  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-31 18:49:14.556  1881  1897 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:49:14.556  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:14.557  6853  6869 D BluetoothPan: onBluetoothStateChange on: false
,08-31 18:49:14.557  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:14.557  6853  6853 D BluetoothMap: Proxy object disconnected
08-31 18:49:14.557  6853  6868 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 18:49:14.557  6853  6853 D MapProfile: Bluetooth service disconnected
08-31 18:49:14.558  1035  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 18:49:14.558  6904  6904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 18:49:14.558  6853  6869 D BluetoothMap: onBluetoothStateChange: up=false
08-31 18:49:14.617  1035  1051 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6950 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-31 18:49:14.619  6853  6868 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 18:49:14.620  1035  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 18:49:14.621  1881  2449 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:49:14.622  1881  1896 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:49:14.623  1035  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 18:49:14.623  1035  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 18:49:14.628  1035  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 18:49:14.628  1035  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 18:49:14.628  1035  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@e8badc3 mBinding = false
08-31 18:49:14.629  1035  1097 D BluetoothManagerService: Sending unbind request.
08-31 18:49:14.631  1035  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-31 18:49:14.635  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:14.636  6853  6853 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 18:49:14.636  1976  1976 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:14.636  1976  2198 D LGBluetoothAPIService: Message: 2
08-31 18:49:14.636  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 18:49:14.637  1976  2198 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2955024d mBinding = false
08-31 18:49:14.637  1976  2198 D LGBluetoothAPIService: Sending unbind request.
08-31 18:49:14.637  6853  6853 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 18:49:14.637  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:14.638  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 18:49:14.644  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 18:49:14.648  1605  1605 D BluetoothAdapter: 330926252: getState() :  mService = null. Returning STATE_OFF
08-31 18:49:14.648  1605  1605 D BluetoothAdapter: 330926252: getState() :  mService = null. Returning STATE_OFF
08-31 18:49:14.650  3893  3976 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 18:49:14.650  3893  3893 I GKI_LINUX: GKI_exit_task 1 done
08-31 18:49:14.650  3893  3893 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 18:49:14.650  3893  3893 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 18:49:14.650  3893  3893 I art     : --- WEIRD: removing null entry 246
08-31 18:49:14.650  3893  3893 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-31 18:49:14.651  3893  3893 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 18:49:14.651  3893  3893 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 18:49:14.652  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-31 18:49:14.654  3893  3893 I art     : System.exit called, status: 0
08-31 18:49:14.654  3893  3893 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 18:49:14.674   313   313 V AudioFlinger: 3893 died, releasing its sessions
08-31 18:49:14.674   313   313 V AudioFlinger:  pid 1881 @ 0
08-31 18:49:14.674   313   313 V AudioFlinger:  pid 3452 @ 1
08-31 18:49:14.674   313   313 V AudioFlinger:  pid 3452 @ 2
,08-31 18:49:14.675  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 18:49:14.702  1035  1762 I ActivityManager: Process com.android.bluetooth (pid 3893) has died
08-31 18:49:14.703  1035  1762 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-31 18:49:14.716  2244  2244 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 18:49:14.732  6853  6853 D BluetoothPermissionRequest: onReceive
,08-31 18:49:14.736  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 18:49:14.736  6853  6853 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-31 18:49:14.740  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 18:49:14.784  1035  2091 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6969 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-31 18:49:14.795  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:14.800  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 18:49:14.808  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:14.827  6950  6987 W FormManager: Network not available. Please check & try again.
,08-31 18:49:14.833  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 18:49:14.833  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 18:49:14.833  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 18:49:14.834  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-31 18:49:14.834  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 18:49:14.838  6950  6989 V FormManager: Network unavailable.
08-31 18:49:14.850  6950  6989 V FormManager: Network unavailable.
,08-31 18:49:14.854  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-31 18:49:14.854  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 18:49:14.855  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 18:49:14.855  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 18:49:14.855  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 18:49:14.856  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 18:49:14.860  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 18:49:14.861  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 18:49:14.863  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:14.867  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 18:49:14.867  1035  1050 I ActivityManager: Killing 6063:com.android.contacts/u0a19 (adj 15): empty #17
08-31 18:49:14.868  6969  6969 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 18:49:14.868  6969  6969 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 18:49:14.869  6969  6969 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 18:49:14.869  6969  6969 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 18:49:14.886  6969  6969 D BluetoothAdapterApp: Loading JNI Library
,08-31 18:49:14.919  6969  6969 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2a90d90b Instance Count = 1
,08-31 18:49:14.929  1035  1051 W libprocessgroup: failed to open /acct/uid_10019/pid_6063/cgroup.procs: No such file or directory
08-31 18:49:14.932  6969  6969 D BluetoothAdapterApp: onCreate
08-31 18:49:14.939  4328  6996 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 18:49:14.940  6873  6873 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 18:49:14.940  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 18:49:14.940  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 18:49:14.945  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 18:49:14.950  4328  6997 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 18:49:14.950  4328  6997 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 18:49:14.957  6950  6999 W FormManager: Network not available. Please check & try again.
08-31 18:49:14.959  6950  7000 V FormManager: Network unavailable.
08-31 18:49:14.960  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:14.960  6969  6969 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 18:49:14.961  6969  6969 D ProfileConfigQcom: Adding HeadsetService
08-31 18:49:14.962  6969  6969 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 18:49:14.962  6969  6969 D ProfileConfigQcom: Adding A2dpService
08-31 18:49:14.963  6969  6969 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 18:49:14.963  6969  6969 D ProfileConfigQcom: Adding HidService
08-31 18:49:14.964  6969  6969 D ProfileConfigQcom: [BTUI] HealthService is supported
08-31 18:49:14.965  6969  6969 D ProfileConfigQcom: Adding HealthService
08-31 18:49:14.965  6969  6969 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-31 18:49:14.967  6969  6969 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 18:49:14.968  6969  6969 D ProfileConfigQcom: Adding PanService
08-31 18:49:14.969  6969  6969 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 18:49:14.969  6969  6969 D ProfileConfigQcom: Adding GattService
08-31 18:49:14.970  6969  6969 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 18:49:14.970  6969  6969 D ProfileConfigQcom: Adding BluetoothMapService
08-31 18:49:14.971  6969  6969 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 18:49:14.972  6950  7000 V FormManager: Network unavailable.
08-31 18:49:14.975  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=595780445 [*alarm*], flags=0x0
08-31 18:49:14.975  6969  6969 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-31 18:49:14.980   309  7004 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 18:49:14.980  1035  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 18:49:14.982  6904  6904 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 18:49:14.984  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-31 18:49:14.984  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-31 18:49:14.985  6904  6904 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-31 18:49:14.986  6969  6969 V LGMDMManagerInternal: Create singleton instance
08-31 18:49:15.022  6904  6904 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 18:49:15.023  6904  6904 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 18:49:15.031  6904  6904 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-31 18:49:15.033  6904  6904 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-31 18:49:15.033  6904  6904 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-31 18:49:15.033  6904  6904 V SoundPool: doLoad: loading sample sampleID=1
08-31 18:49:15.034  6904  6904 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-31 18:49:15.038  6631  6631 D UEI.SmartControl: QS Service created
08-31 18:49:15.038  6904  6904 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-31 18:49:15.039  6904  7008 V SoundPool: Start decode
,08-31 18:49:15.040  6904  7008 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-31 18:49:15.042  6904  6904 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 18:49:15.043  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 18:49:15.043   313   313 V MediaPlayerService: decode(23, 10857164, 17813)
08-31 18:49:15.043   313   313 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-31 18:49:15.043   313   313 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-31 18:49:15.044   313   313 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-31 18:49:15.044   313   313 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-31 18:49:15.044   313   313 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-31 18:49:15.044   313   313 V MediaPlayerService: player type = 3
08-31 18:49:15.044   313   313 V AwesomePlayer: AwesomePlayer create()
08-31 18:49:15.045   313   313 V AwesomePlayer: reset_l() 
08-31 18:49:15.046   313   313 V AwesomePlayer: cancelPlayerEvents
08-31 18:49:15.046   313   313 V AwesomePlayer: setAudioSink() 
08-31 18:49:15.046   313   313 V AwesomePlayer: reset_l() 
08-31 18:49:15.046   313   313 V AudioCache: notify(0xb0409500, 8, 0, 0)
08-31 18:49:15.046   313   313 V AudioCache: ignored
08-31 18:49:15.046   313   313 V AwesomePlayer: cancelPlayerEvents
08-31 18:49:15.046   313   313 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-31 18:49:15.046   313   313 V AwesomePlayer: setDataSource_l dataSource
08-31 18:49:15.046   313   313 V LGParserOSAL: SniffLGParser start
08-31 18:49:15.046   313   313 V LGParserOSAL: MainType:5, SubType=0
08-31 18:49:15.047   313   313 V LGParserOSAL: #### check Mime : application/ogg
08-31 18:49:15.047   313   313 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-31 18:49:15.047   313   313 E MediaExtractor: Use LGExtractor :application/ogg 
08-31 18:49:15.054  6904  6904 V LGMDMManager: Create singleton instance
,08-31 18:49:15.070  6631  6631 I UEI.SmartControl: Service initServices...
08-31 18:49:15.070  6631  6631 D UEI.SmartControl: QS start get config
08-31 18:49:15.079  6969  6969 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-31 18:49:15.083  6969  6969 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 18:49:15.084  6969  6969 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 18:49:15.084  6969  6969 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 18:49:15.086  6969  6969 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:15.086  6969  6969 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 18:49:15.094  6925  6925 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 18:49:15.103   313   313 V LGParserOSAL: supported mime: application/ogg
08-31 18:49:15.103   313   313 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-31 18:49:15.103   313   313 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-31 18:49:15.103   313   313 V AwesomePlayer: mBitrate = -1 bits/sec
08-31 18:49:15.103   313   313 V AwesomePlayer: AudioTrack Setting
08-31 18:49:15.103   313   313 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-31 18:49:15.103   313   313 V AwesomePlayer: setAudioSource() 
08-31 18:49:15.103   313   313 V MediaPlayerService: prepare
08-31 18:49:15.103   313   313 V AwesomePlayer: prepareAsync_l() 
08-31 18:49:15.103   313   313 V MediaPlayerService: wait for prepare
08-31 18:49:15.103   313  7010 V AwesomePlayer: onPrepareAsyncEvent() 
08-31 18:49:15.103   313  7010 V AwesomePlayer: initAudioDecoder() 
08-31 18:49:15.103   313  7010 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 18:49:15.103   313  7010 V AudioSystem: isOffloadSupported()
08-31 18:49:15.103   313  7010 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 18:49:15.103   313  7010 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 18:49:15.103   313  7010 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 18:49:15.103   313  7010 V AwesomePlayer: getUseOffload() = 0 
08-31 18:49:15.103   313  7010 V OMXCodec: OMXCodec::Create
08-31 18:49:15.103   313  7010 V OMXCodec: findMatchingCodecs()
08-31 18:49:15.103   313  7010 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-31 18:49:15.103   313  7010 V OMXCodec: matchingCodecs.size()=1
08-31 18:49:15.103   313  7010 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-31 18:49:15.105   313  7010 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-31 18:49:15.105   313  7010 V LGCodecAdapter: LG Codec Adapter start
08-31 18:49:15.105   313  7010 V OMXCodec: OMXCodec Createtor
08-31 18:49:15.105   313  7010 V OMXCodec: setComponentRole
08-31 18:49:15.105   313  7010 V OMXCodec: configureCodec protected=0
08-31 18:49:15.105   313  7010 V LGCodecAdapter: called getLGCodecSpecificData
08-31 18:49:15.105   313  7010 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-31 18:49:15.105   313  7010 V LGCodecOSAL: Called LGconfigureCodecMETA
08-31 18:49:15.105   313  7010 V LGCodecOSAL: Called LGconfigureCodecMSG
08-31 18:49:15.105   313  7010 V LGCodecOSAL: Not support LGCodec
08-31 18:49:15.105   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 18:49:15.105   313  7010 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-31 18:49:15.105   313  7010 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-31 18:49:15.105   313  7010 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-31 18:49:15.105   313  7010 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-31 18:49:15.105   313  7010 V AudioSystem: isOffloadSupported()
08-31 18:49:15.105   313  7010 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-31 18:49:15.105   313  7010 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-31 18:49:15.105   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-31 18:49:15.105   313  7010 V OMXCodec: init()
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-31 18:49:15.106   313  7010 V OMXCodec: allocateBuffers
08-31 18:49:15.106   313  7010 V OMXCodec: allocateBuffersOnPort portIndex=0
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
,08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-31 18:49:15.106   313  7010 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-31 18:49:15.106   313  7010 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-31 18:49:15.106   313  7010 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 18:49:15.106   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 18:49:15.106   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 18:49:15.107   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-31 18:49:15.107   313  7010 V OMXCodec: init() mAsyncCompletion wait!!! 
08-31 18:49:15.107   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-31 18:49:15.107   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-31 18:49:15.107   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-31 18:49:15.107   313  7010 V OMXCodec: init() mAsyncCompletion wait free! 
08-31 18:49:15.107   313  7010 V AwesomePlayer: finishAsyncPrepare_l() 
08-31 18:49:15.107   313  7010 V AudioCache: notify(0xb0409500, 5, 0, 0)
08-31 18:49:15.107   313  7010 V AudioCache: ignored
08-31 18:49:15.107   313  7010 V AudioCache: notify(0xb0409500, 1, 0, 0)
08-31 18:49:15.107   313  7010 V AudioCache: prepared
08-31 18:49:15.107   313   313 V AudioCache: wait - success
08-31 18:49:15.107   313   313 V MediaPlayerService: start
08-31 18:49:15.107   313   313 V AwesomePlayer: play_l() 
08-31 18:49:15.107   313   313 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-31 18:49:15.107   313   313 V AwesomePlayer: createAudioPlayer_l
08-31 18:49:15.107   313   313 V AwesomePlayer: seekAudioIfNecessary_l() 
08-31 18:49:15.107   313   313 V AwesomePlayer: startAudioPlayer_l() 
08-31 18:49:15.107   313   313 D AudioPlayer: start of Playback, useOffload 0
08-31 18:49:15.107   313   313 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 18:49:15.107   313   313 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer ,3041885648
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-31 18:49:15.114   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-31 18:49:15.115   313  7012 V OMXCodec: allocateBuffersOnPort portIndex=1
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-31 18:49:15.115   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-31 18:49:15.117   313   313 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-31 18:49:15.117   313   313 V AudioCache: notify(0xb0409500, 6, 0, 0)
08-31 18:49:15.117   313   313 V AudioCache: ignored
08-31 18:49:15.117   313   313 V MediaPlayerService: wait for playback complete
08-31 18:49:15.117   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.117   313  7013 V AudioCache: memcpy(0xaf004000, 0xb16a2000, 4096)
08-31 18:49:15.118   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.118   313  7013 V AudioCache: memcpy(0xaf005000, 0xb16a2000, 4096)
08-31 18:49:15.118   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.118   313  7013 V AudioCache: memcpy(0xaf006000, 0xb16a2000, 4096)
,08-31 18:49:15.121  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 18:49:15.122  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-31 18:49:15.123   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.123   313  7013 V AudioCache: memcpy(0xaf007000, 0xb16a2000, 4096)
08-31 18:49:15.124   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.124   313  7013 V AudioCache: memcpy(0xaf008000, 0xb16a2000, 4096)
08-31 18:49:15.124   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.124   313  7013 V AudioCache: memcpy(0xaf009000, 0xb16a2000, 4096)
08-31 18:49:15.125   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.125   313  7013 V AudioCache: memcpy(0xaf00a000, 0xb16a2000, 4096)
08-31 18:49:15.125  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:859
08-31 18:49:15.126   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.126   313  7013 V AudioCache: memcpy(0xaf00b000, 0xb16a2000, 4096)
08-31 18:49:15.126   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.126   313  7013 V AudioCache: memcpy(0xaf00c000, 0xb16a2000, 4096)
08-31 18:49:15.127   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.127   313  7013 V AudioCache: memcpy(0xaf00d000, 0xb16a2000, 4096)
08-31 18:49:15.127   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.127   313  7013 V AudioCache: memcpy(0xaf00e000, 0xb16a2000, 4096)
08-31 18:49:15.128   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.128   313  7013 V AudioCache: memcpy(0xaf00f000, 0xb16a2000, 4096)
08-31 18:49:15.128   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.128   313  7013 V AudioCache: memcpy(0xaf010000, 0xb16a2000, 4096)
08-31 18:49:15.129   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.129   313  7013 V AudioCache: memcpy(0xaf011000, 0xb16a2000, 4096)
08-31 18:49:15.130   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.130   313  7013 V AudioCache: memcpy(0xaf012000, 0xb16a2000, 4096)
08-31 18:49:15.130   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.130   313  7013 V AudioCache: memcpy(0xaf013000, 0xb16a2000, 4096)
,08-31 18:49:15.130   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.130   313  7013 V AudioCache: memcpy(0xaf014000, 0xb16a2000, 4096)
08-31 18:49:15.131   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.131   313  7013 V AudioCache: memcpy(0xaf015000, 0xb16a2000, 4096)
08-31 18:49:15.132   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.132   313  7013 V AudioCache: memcpy(0xaf016000, 0xb16a2000, 4096)
08-31 18:49:15.132   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.132   313  7013 V AudioCache: memcpy(0xaf017000, 0xb16a2000, 4096)
08-31 18:49:15.133   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.133   313  7013 V AudioCache: memcpy(0xaf018000, 0xb16a2000, 4096)
08-31 18:49:15.133   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.133   313  7013 V AudioCache: memcpy(0xaf019000, 0xb16a2000, 4096)
08-31 18:49:15.134   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.134   313  7013 V AudioCache: memcpy(0xaf01a000, 0xb16a2000, 4096)
08-31 18:49:15.134   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.134   313  7013 V AudioCache: memcpy(0xaf01b000, 0xb16a2000, 4096)
08-31 18:49:15.135   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.135   313  7013 V AudioCache: memcpy(0xaf01c000, 0xb16a2000, 4096)
08-31 18:49:15.135   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.135   313  7013 V AudioCache: memcpy(0xaf01d000, 0xb16a2000, 4096)
08-31 18:49:15.136   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.136   313  7013 V AudioCache: memcpy(0xaf01e000, 0xb16a2000, 4096)
08-31 18:49:15.137   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.137   313  7013 V AudioCache: memcpy(0xaf01f000, 0xb16a2000, 4096)
08-31 18:49:15.137   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.137   313  7013 V AudioCache: memcpy(0xaf020000, 0xb16a2000, 4096)
08-31 18:49:15.138   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.138   313  7013 V AudioCache: memcpy(0xaf021000, 0xb16a2000, 4096)
,08-31 18:49:15.138   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.138   313  7013 V AudioCache: memcpy(0xaf022000, 0xb16a2000, 4096)
08-31 18:49:15.139   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.139   313  7013 V AudioCache: memcpy(0xaf023000, 0xb16a2000, 4096)
08-31 18:49:15.139   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.139   313  7013 V AudioCache: memcpy(0xaf024000, 0xb16a2000, 4096)
08-31 18:49:15.140   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.140   313  7013 V AudioCache: memcpy(0xaf025000, 0xb16a2000, 4096)
08-31 18:49:15.140   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.141   313  7013 V AudioCache: memcpy(0xaf026000, 0xb16a2000, 4096)
08-31 18:49:15.141   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.141   313  7013 V AudioCache: memcpy(0xaf027000, 0xb16a2000, 4096)
08-31 18:49:15.142   313  7013 V AudioCache: write(0xb16a2000, 4096)
,08-31 18:49:15.142   313  7013 V AudioCache: memcpy(0xaf028000, 0xb16a2000, 4096)
,08-31 18:49:15.143   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.143   313  7013 V AudioCache: memcpy(0xaf029000, 0xb16a2000, 4096)
08-31 18:49:15.143   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.143   313  7013 V AudioCache: memcpy(0xaf02a000, 0xb16a2000, 4096)
08-31 18:49:15.144   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.144   313  7013 V AudioCache: memcpy(0xaf02b000, 0xb16a2000, 4096)
08-31 18:49:15.144   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.144   313  7013 V AudioCache: memcpy(0xaf02c000, 0xb16a2000, 4096)
08-31 18:49:15.145   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.145   313  7013 V AudioCache: memcpy(0xaf02d000, 0xb16a2000, 4096)
08-31 18:49:15.145   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.145   313  7013 V AudioCache: memcpy(0xaf02e000, 0xb16a2000, 4096)
08-31 18:49:15.146   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.146   313  7013 V AudioCache: memcpy(0xaf02f000, 0xb16a2000, 4096)
08-31 18:49:15.146   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.146   313  7013 V AudioCache: memcpy(0xaf030000, 0xb16a2000, 4096)
08-31 18:49:15.147   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.147   313  7013 V AudioCache: memcpy(0xaf031000, 0xb16a2000, 4096)
08-31 18:49:15.147   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.147   313  7013 V AudioCache: memcpy(0xaf032000, 0xb16a2000, 4096)
08-31 18:49:15.148   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.148   313  7013 V AudioCache: memcpy(0xaf033000, 0xb16a2000, 4096)
08-31 18:49:15.148   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.148   313  7013 V AudioCache: memcpy(0xaf034000, 0xb16a2000, 4096)
08-31 18:49:15.148   313  7013 V AudioCache: write(0xb16a2000, 4096)
08-31 18:49:15.149   313  7013 V AudioCache: memcpy(0xaf035000, 0xb16a2000, 4096)
08-31 18:49:15.149   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-31 18:49:15.149   313  7013 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-31 18:49:15.149   313  7013 V AwesomePlayer: postAudioEOS() 
08-31 18:49:15.149   313  7013 V AudioCache: write(0xb16a2000, 280)
08-31 18:49:15.149   313  7013 V AudioCache: memcpy(0xaf036000, 0xb16a2000, 280)
08-31 18:49:15.151   313  7010 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-31 18:49:15.151   313  7010 V AwesomePlayer: onStreamDone
08-31 18:49:15.151   313  7010 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-31 18:49:15.151   313  7010 V AudioCache: notify(0xb0409500, 2, 0, 0)
08-31 18:49:15.151   313  7010 V AudioCache: playback complete
08-31 18:49:15.151   313  7010 V AwesomePlayer: pause_l() 
08-31 18:49:15.151   313  7010 V AudioCache: notify(0xb0409500, 7, 0, 0)
08-31 18:49:15.151   313  7010 V AudioCache: ignored
,08-31 18:49:15.151   313  7010 V AwesomePlayer: cancelPlayerEvents
08-31 18:49:15.151   313  7010 D AudioPlayer: Pause Playback at 1068125
08-31 18:49:15.151   313   313 V AudioCache: wait - success
08-31 18:49:15.151   313   313 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-31 18:49:15.152   313   313 V AwesomePlayer: reset_l() 
08-31 18:49:15.152   313   313 V AudioCache: notify(0xb0409500, 8, 0, 0)
08-31 18:49:15.152   313   313 V AudioCache: ignored
08-31 18:49:15.152   313   313 V AwesomePlayer: cancelPlayerEvents
08-31 18:49:15.152   313   313 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-31 18:49:15.152   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-31 18:49:15.152   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-31 18:49:15.152   313   313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-31 18:49:15.152   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 1
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-31 18:49:15.152   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-31 18:49:15.153   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 18:49:15.153   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-31 18:49:15.153   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-31 18:49:15.153   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-31 18:49:15.153   313  7012 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-31 18:49:15.153   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-31 18:49:15.153   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-31 18:49:15.153   313   313 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-31 18:49:15.153   313   313 V OMXCodec: [OMX.google.vorbis.decoder] setState mStat,e=1 , newState=0
08-31 18:49:15.154   313   313 D AudioPlayer: AudioPlayer releasing audio source
08-31 18:49:15.154   313   313 D AudioPlayer: AudioPlayer done releasing audio source
08-31 18:49:15.154   313   313 V AwesomePlayer: reset_l() 
08-31 18:49:15.154   313   313 V AwesomePlayer: cancelPlayerEvents
08-31 18:49:15.154   313   313 V AwesomePlayer: ~AwesomePlayer call
08-31 18:49:15.154   313   313 V AwesomePlayer: reset_l() 
08-31 18:49:15.154   313   313 V AwesomePlayer: cancelPlayerEvents
08-31 18:49:15.154  6904  7008 V SoundPool: close(31)
08-31 18:49:15.154  6904  7008 V SoundPool: pointer = 0x9fe9c000, size = 205080, sampleRate = 48000, numChannels = 2
,08-31 18:49:15.343  6631  6631 I UEI.SmartControl: Supports setup maps: true
,08-31 18:49:15.346  6631  6631 D UEI.SmartControl: QS start statue = true Error code = 0
,08-31 18:49:15.346  6631  6631 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 18:49:15.346  6631  6631 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 18:49:15.346  6631  6631 I UEI.SmartControl: ### init IR Blaster...
08-31 18:49:15.350  6631  6631 D serial_port: Configuring serial port
08-31 18:49:15.350  6631  6631 E UEI.SmartControl: UEIBLaster setting for 616
08-31 18:49:15.350  6631  6631 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 18:49:15.350  6631  6631 I UEI.SmartControl: configuring settings for MAXQ616
08-31 18:49:15.350  6631  6631 I UEI.SmartControl: Get version...
08-31 18:49:15.369  6631  7014 D UEI.SmartControl: serial port data available: 21
,08-31 18:49:15.395  6631  6631 D UEI.SmartControl: MAXQ616 A2-X4 software.,
08-31 18:49:15.395  6631  6631 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 18:49:15.395  6631  6631 I UEI.SmartControl: QS saving settings...
08-31 18:49:15.401  6631  6631 D UEI.SmartControl: IR Blaster version: 25672567
,08-31 18:49:15.421  6631  7014 D UEI.SmartControl: serial port data available: 4,
,08-31 18:49:15.451  6631  7020 I UEI.SmartControl: Device manager: loading config....,
,08-31 18:49:15.453  6631  7020 D UEI.SmartControl: ----------- loading internal config...,
08-31 18:49:15.454  6631  6631 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 18:49:15.456  6631  6631 E UEI.SmartControl: Services init done
08-31 18:49:15.456  6631  6631 D UEI.SmartControl: QS Service init finished
08-31 18:49:15.457  6631  6631 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 18:49:15.457  6631  6631 D UEI.SmartControl: QS Service version code: 201091
08-31 18:49:15.458  6631  6631 D UEI.SmartControl: Service requested: Control
,08-31 18:49:15.463  6631  6631 D UEI.SmartControl: Request IControl service: devices are loaded...
08-31 18:49:15.464  6631  7020 E UEI.SmartControl: Loading SETTINGS...
,08-31 18:49:15.467  6904  6904 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 18:49:15.467  6631  6631 D UEI.SmartControl: Internal service binding...
08-31 18:49:15.469  6631  6647 I UEI.SmartControl: ------ IControl API: 11
08-31 18:49:15.469  6631  6647 D UEI.SmartControl: File observer start...
08-31 18:49:15.470  6631  6647 E UEI.SmartControl: IR Port is disabled: false
08-31 18:49:15.470  6631  6647 D UEI.SmartControl: Starting file observer...
08-31 18:49:15.471  6631  6647 I UEI.SmartControl: Registering callback...
08-31 18:49:15.472  6631  6646 I UEI.SmartControl: ------ IControl API: 19
08-31 18:49:15.474  6631  6646 I UEI.SmartControl: Registering Services Ready callback...
08-31 18:49:15.478  6631  7020 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-31 18:49:15.491  6631  7019 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 18:49:15.491  6631  7019 D UEI.SmartControl: -----service ready thread exits
,08-31 18:49:15.492  6904  6919 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-31 18:49:15.493  6904  7006 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-31 18:49:15.493  6904  7006 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-31 18:49:15.494  6904  6904 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-31 18:49:15.495  6904  6904 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-31 18:49:15.496  6631  6647 I UEI.SmartControl: ------ IControl API: 8
08-31 18:49:15.499  6904  6904 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-31 18:49:15.500  6904  6904 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
,08-31 18:49:15.501  6904  6904 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-31 18:49:15.502  6904  6904 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-31 18:49:15.504  6904  6904 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-31 18:49:15.505  6904  6904 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-31 18:49:15.509  6904  6904 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-31 18:49:15.514  6904  6904 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-31 18:49:15.516  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-31 18:49:15.518  6904  6904 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 18:49:15.520  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-31 18:49:15.523  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-31 18:49:15.526  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-31 18:49:15.528  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,08-31 18:49:15.531  6904  6904 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472662155529]
08-31 18:49:15.535  6904  6904 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-31 18:49:15.538  1035  2091 I ActivityManager: Killing 6091:com.android.gallery3d/u0a27 (adj 15): empty #17
08-31 18:49:15.565  6904  7022 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-31 18:49:15.634  1035  2091 I ActivityManager: Killing 6523:com.lge.email/u0a23 (adj 15): empty #18
,08-31 18:49:15.716  1035  1996 W libprocessgroup: failed to open /acct/uid_10023/pid_6523/cgroup.procs: No such file or directory
,08-31 18:49:15.722  6904  6904 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-31 18:49:15.722  1035  1762 W libprocessgroup: failed to open /acct/uid_10027/pid_6091/cgroup.procs: No such file or directory
08-31 18:49:15.725  6904  6904 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-31 18:49:15.726  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-31 18:49:15.726  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-31 18:49:15.726  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-31 18:49:15.727  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-31 18:49:15.727  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-31 18:49:15.737  6904  6904 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-31 18:49:16.014  1035  1386 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3a4a05d0 type 2 when 195814 com.google.android.gms} when 195814
,08-31 18:49:16.399  1035  2004 D WifiServiceImplEx: setWifiEnabled: true pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 18:49:16.401  1035  2004 D WifiService: setWifiEnabled: true pid=6733, uid=10118
08-31 18:49:16.401  1035  2004 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 18:49:16.436  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 18:49:16.437  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 18:49:16.437  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-31 18:49:16.440  1035  1541 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 18:49:16.440  1035  1541 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 18:49:16.442  1035  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-31 18:49:16.442  1035  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 18:49:16.443  1035  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 18:49:16.443  1035  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 18:49:16.443  1035  1541 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 18:49:16.443  1035  1541 E WifiHW  : unknown target_country: EU , set to default
08-31 18:49:16.443  1035  1541 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-31 18:49:16.443  1035  1541 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-31 18:49:16.443  1035  1541 I WifiUtil: gEnableBmps=1
08-31 18:49:16.480  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:49:16.498  1035  1097 D Tethering: MasterInitialState.processMessage what=3
,08-31 18:49:16.519  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:16.526  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:16.528  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:16.531  1035  1097 D Tethering: MasterInitialState.processMessage what=3
,08-31 18:49:16.545  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:16.548  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:16.548  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:16.550  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 18:49:16.559  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 18:49:16.566  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 18:49:16.567  6419  6872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 18:49:16.598  2244  2244 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:49:16.673  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:49:16.676  1035  1995 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7031 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-31 18:49:16.678  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:16.678  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 18:49:16.751  7031  7031 I AppUp4:AppBoxCP: onCreate
08-31 18:49:16.752  7031  7031 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-31 18:49:16.761  7031  7031 I AppUp4:DB:  setFingerPrint start
08-31 18:49:16.762  7031  7031 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-31 18:49:16.769  7031  7031 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-31 18:49:16.769  7031  7031 I AppUp4:DB:  SDK version = 21
08-31 18:49:16.769  7031  7031 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-31 18:49:16.771  7031  7031 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-31 18:49:16.773  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 18:49:16.773  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:16.775  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 18:49:16.776  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 18:49:16.785  7031  7031 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 18:49:16.834  7031  7031 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:16.834  7031  7031 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 18:49:16.842  7031  7031 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3938f53d
08-31 18:49:16.843  7031  7031 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 18:49:16.843  7031  7031 D AppUp4:CustFacade: isPhone : true
08-31 18:49:16.844  7031  7031 D AppUp4:CustModeStarterReceiver: begin check event
08-31 18:49:16.844  7031  7031 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-31 18:49:16.844  7031  7031 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-31 18:49:16.845  7031  7064 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-31 18:49:16.846  7031  7064 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-31 18:49:16.846  7031  7064 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-31 18:49:16.849  1035  1993 I ActivityManager: Killing 6150:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-31 18:49:16.908  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:16.909  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 18:49:16.910  1035  1584 W libprocessgroup: failed to open /acct/uid_10080/pid_6150/cgroup.procs: No such file or directory
08-31 18:49:16.911  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 18:49:16.918  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:16.927  4328  7066 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 18:49:16.935  4328  7067 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:16.936  4328  7067 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 18:49:16.995  1035  2091 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7077 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 18:49:17.084  7077  7077 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 18:49:17.085  7077  7077 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 18:49:17.086  7077  7077 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 18:49:17.087  7077  7077 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 18:49:17.170  1035  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 18:49:17.170  1035  1097 D Tethering: InitialState.processMessage what=4
,08-31 18:49:17.172  1035  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 18:49:17.180   309   892 D SoftapController: Softap fwReload - Ok
08-31 18:49:17.182  1035  1541 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (730ms)
,08-31 18:49:17.186   309   892 D CommandListener: Setting iface cfg
08-31 18:49:17.186   309   892 D CommandListener: Trying to bring down wlan0
08-31 18:49:17.186   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-31 18:49:17.188  1035  1541 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-31 18:49:17.190  1035  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 18:49:17.190  1035  1541 E WifiStateMachine: useWiFiOffloading() : false
08-31 18:49:17.190  1035  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 18:49:17.189  7097  7097 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:17.189  7097  7097 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:17.194  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 18:49:17.195  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:17.199  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:17.202  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 18:49:17.203  1035  1541 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-31 18:49:17.203  1035  1541 D WifiMonitor: connecting to supplicant
08-31 18:49:17.203  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:17.211  7077  7077 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-31 18:49:17.213  7097  7097 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 18:49:17.227  7077  7077 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-31 18:49:17.235  7097  7097 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 18:49:17.235  7097  7097 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-31 18:49:17.268  7077  7077 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 18:49:17.301  7097  7097 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 18:49:17.324  7077  7077 D LgDataFeature: LgDataFeature() Constructor: none
,08-31 18:49:17.324  7077  7077 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 18:49:17.370  7097  7097 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 18:49:17.377  7097  7097 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 18:49:17.378  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 18:49:17.378  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 18:49:17.379  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 18:49:17.379  1035  1541 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 18:49:17.380  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:17.381  1035  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:17.381  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:17.381  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-31 18:49:17.382  1035  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:17.382  1035  1541 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 18:49:17.382  1035  1541 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 18:49:17.383  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 18:49:17.383  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 18:49:17.383  1035  7106 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 18:49:17.383  1035  7106 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 18:49:17.383  1035  7106 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-31 18:49:17.383  1035  7106 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 18:49:17.383  1035  1541 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 18:49:17.384  1035  1541 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 18:49:17.384  1035  1541 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-31 18:49:17.387  1035  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 18:49:17.387  1035  1541 E WifiStateMachine: useWiFiOffloading() : false
08-31 18:49:17.387  1035  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 18:49:17.388  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 18:49:17.388  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:17.388  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:17.388  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:17.388  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 18:49:17.389  1035  1541 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 18:49:17.390  1035  1541 D WifiNative-wlan0: SET update_config 1: returned true
08-31 18:49:17.392  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 18:49:17.392  1976  1976 D WfdService: Waiting for WifiP2p enabling
08-31 18:49:17.393  1035  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 18:49:17.393  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:17.394  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:17.394  1035  1541 D WifiConfigStore: Loading config and enabling all networks 
08-31 18:49:17.394  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:17.394  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:17.394  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:17.394  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:17.394  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:17.394  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:17.394  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:17.394  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:17.395  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:17.395  1035  1541 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 18:49:17.395  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:17.396  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:17.396  1035  1541 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 18:49:17.396  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:17.396  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:17.396  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:17.396  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:17.396  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:17.396  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:17.396  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:17.396  6733  6733 V io.jxcore.node.ConnectivityMonitor: ,    - active network type is Wi-Fi: false
08-31 18:49:17.396  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:17.396  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:17.407  1035  1541 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-31 18:49:17.422  1035  1541 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-31 18:49:17.423  1035  1541 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 18:49:17.424  1035  1541 D WifiStateMachine: enableVerboseLogging : level 2
08-31 18:49:17.425  1035  1541 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 18:49:17.425  1035  1541 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-31 18:49:17.425  1035  1541 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 18:49:17.425  1035  1541 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 18:49:17.425  1035  1541 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 18:49:17.426  1035  1541 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 18:49:17.426  1035  1541 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 18:49:17.426  1035  1541 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 18:49:17.426  1035  1541 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-31 18:49:17.427  1035  1541 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 18:49:17.427  1035  1541 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 18:49:17.427  1035  1541 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 18:49:17.427  1035  1541 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 18:49:17.427  1035  1541 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 18:49:17.428  1035  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 18:49:17.428  1035  1541 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 18:49:17.428  1035  1541 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 18:49:17.428  1035  1541 D WifiNative-HAL: Setting external_sim to 1
08-31 18:49:17.428  1035  1541 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 18:49:17.428  1976  1976 D WfdsService: Supplicant Connection state is changed : true
08-31 18:49:17.429  1976  2322 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 18:49:17.429  1976  2322 D WfdsService: Set the WFDS Monitor: true
08-31 18:49:17.429  1976  2322 D WfdsMonitor: WfdsMonitorThread create
08-31 18:49:17.429  1976  2322 D WfdsMonitor: WFDS Monitor is created and started
08-31 18:49:17.429  1035  1541 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 18:49:17.429  1976  2322 D WfdsService: WiFi: Supplicant connection re-established
08-31 18:49:17.429  1035  1541 I WifiNative-HAL: startHal
08-31 18:49:17.429  1035  1541 D wifi    : setting scan oui 0xaf7679a0
08-31 18:49:17.430  1035  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 18:49:17.430  1035  1541 I WifiNative-HAL: startHal
08-31 18:49:17.430  1035  1541 D wifi    : setting scan oui 0xaf7679a0
08-31 18:49:17.430  1976  7108 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 18:49:17.430  1035  1541 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 18:49:17.430  1976  7108 E CtrlSupplicant: Succeed to open control connection
08-31 18:49:17.430  1035  1541 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 18:49:17.430  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 18:49:17.430  1976  7108 E CtrlSupplicant: Succeed to open monitor connection
08-31 18:49:17.431  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 18:49:17.431  1976  7108 D WfdsMonitor: Supplicant connection established
08-31 18:49:17.431  1976  2322 D WfdsService: Connected to the supplicant for wfds
08-31 18:49:17.431  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 18:49:17.431  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 18:49:17.431  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 18:49:17.432  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 18:49:17.432  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 18:49:17.432  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 18:49:17.432  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 18:49:17.432  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 18:49:17.432  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 18:49:17.433  10,35  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 18:49:17.433  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 18:49:17.433  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 18:49:17.433  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 18:49:17.433  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 18:49:17.433  7097  7097 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 18:49:17.433  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 18:49:17.433  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 18:49:17.434  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 18:49:17.434  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 18:49:17.435  1035  1541 E WifiNative: : [197,248,795 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 18:49:17.435  1035  1541 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 18:49:17.437  1035  1541 D WifiNative-wlan0: RECONNECT: returned true
08-31 18:49:17.437  1035  1541 D WifiNative-wlan0: doString: [STATUS]
08-31 18:49:17.438  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 18:49:17.438  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 18:49:17.438  1035  1541 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 18:49:17.438  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 18:49:17.438  1035  1541 D WifiNative-wlan0: SET ps 1: returned true
08-31 18:49:17.439  1035  1540 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.439  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 18:49:17.439  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-31 18:49:17.439  1035  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.439  1035  1559 I WifiNative-HAL: startHal
08-31 18:49:17.440  1035  1559 D wifi    : getting scan capabilities on interface[1] = 0xaf7679a0
08-31 18:49:17.440  1035  1559 D wifi    : failed to get capabilities : -3
08-31 18:49:17.440  1035  1559 E WifiScanningService: could not get scan capabilities
08-31 18:49:17.440  1035  1560 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.440  1035  1541 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 18:49:17.440   309   892 D CommandListener: Setting iface cfg
08-31 18:49:17.440   309   892 D CommandListener: Trying to bring up p2p0
08-31 18:49:17.441  1035  1540 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 18:49:17.441  1035  1540 D LGWifiP2pService: P2pEnablingState
08-31 18:49:17.441  1035  1541 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 18:49:17.441  1035  1540 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.441  1035  1540 D LGWifiP2pService: P2p socket connection successful
08-31 18:49:17.441  1035  1540 D LGWifiP2pService: P2pEnabledState
08-31 18:49:17.441  1035  1541 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 18:49:17.441  1035  1540 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 18:49:17.441  1035  1541 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 18:49:17.442  1035  1541 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 18:49:17.442  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 18:49:17.442  1976  1976 D WfdsSer,vice: WifiP2pState is changed : true
08-31 18:49:17.442  1976  2322 D WfdsService: Receive the WFDS_ENABLE Method
08-31 18:49:17.442  1976  2322 D WfdsService: Set the WFDS Monitor: true
08-31 18:49:17.442  1035  1541 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 18:49:17.442  1976  2322 D WfdsService: Connected to the supplicant for wfds
08-31 18:49:17.443  1976  2322 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 18:49:17.443  7097  7097 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 18:49:17.443  1976  2322 D WfdsService: selectPreferredScanChannel [36]
08-31 18:49:17.443  1976  2322 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 18:49:17.443  1035  1541 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 18:49:17.443  1035  1541 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 18:49:17.443  7097  7097 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 18:49:17.444  1035  1541 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 18:49:17.444  1035  1541 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 18:49:17.445  1035  1541 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 18:49:17.445  1035  1541 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 18:49:17.445  7097  7097 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 18:49:17.446  1035  1541 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 18:49:17.446  1035  1541 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 18:49:17.446  1035  1541 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-31 18:49:17.446  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 18:49:17.447  1035  1540 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 18:49:17.448  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 18:49:17.449  7097  7097 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:17.449  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 18:49:17.449  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:17.449  1035  7106 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:17.449  7097  7097 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 18:49:17.449  1035  7106 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:17.449  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.450  1035  1541 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 18:49:17.450  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.450  1035  1540 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 18:49:17.451  1035  7106 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:17.451  1035  7106 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.451  1035  1540 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 18:49:17.451  1976  1976 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 18:49:17.451  1035  7106 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.451  1035  7106 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.451  1035  7106 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:17.451  1035  7106 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.451  1035  7106 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.451  1035  7106 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.451  1976  7108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:17.451  1976  7108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:17.451  1976  1976 D WfdsService: isConnected: false
08-31 18:49:17.451  1035  1540 D WifiNative-p2p0: SET device_name G3: returned true
08-31 18:49:17.451  1035  1540 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 18:49:17.451  1035  1540 D LGWifiP2pService: before postfix = G3
08-31 18:49:17.451  1035  1540 D WifiServerServiceExt: postfix byte check : 2
08-31 18:49:17.451  1035  1540 D LGWifiP2pService: after postfix = G3
08-31 18:49:17.451  1035  1540 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 18:49:17.452  1035  1540 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 18:49:17.452  1035  1540 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 18:49:17.452  1035  1541 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-31 18:49:17.453  1035  1541 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 18:49:17.453  1035  1540 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 18:49:17.453  1035  1540 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 18:49:17.453  1035  1541 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 18:49:17.453  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 18:49:17.453  1035  1540 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 18:49:17.454  1035  1540 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 18:49:17.454  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 18:49:17.454  7097  7097 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 18:49:17.454  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 18:49:17.454  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 18:49:17.454  1035  7106 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 18:49:17.454  1035  7106 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 18:49:17.455  1035  1541 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 18:49:17.455  1035  1541 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 18:49:17.455  1035  1540 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 18:49:17.455  1035  1540 D WifiNative-HAL: p2pGetDeviceAddress
08-31 18:49:17.455  1035  1541 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 18:49:17.455  1035  1541 D WifiNative-wlan0: doBoolean: SCAN
08-31 18:49:17.456  1035  1540 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-31 18:49:17.456  1035  1541 D WifiNative-wlan0: SCAN: returned false
08-31 18:49:17.456  1035  1540 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-31 18:49:17.456  1035  1540 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 18:49:17.456  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=197271  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 18:49:17.456  1035  1540 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 18:49:17.457  1035  1540 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 18:49:17.457  1035  1540 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 18:49:17.457  1035  1540 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 18:49:17.457  1035  1540 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 18:49:17.457  1976  1976 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 18:49:17.457  1035  1540 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 18:49:17.457  1976  1976 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 18:49:17.458  1976  1976 D WfdsService: Update P2p Interface State: 3
08-31 18:49:17.460  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:17.460  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:17.461  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=197275  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 18:49:17.461  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:17.461  1035  1541 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:17.462  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:17.462  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:17.462  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 18:49:17.462  1035  1541 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:17.464  1035  1541 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:17.464  1035  1541 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:17.464  1035  1541 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:17.465  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:17.465  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 18:49:17.474  1035  1540 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 18:49:17.475  1035  1540 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 18:49:17.475  1035  1540 D LGWifiP2pService: InactiveState
08-31 18:49:17.475  1035  1540 D LGWifiP2pService: InactiveState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.475  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.475  1035  1540 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 18:49:17.475  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 18:49:17.476  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:17.476  1976  7108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 18:49:17.476  1035  7106 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 18:49:17.476  1035  7106 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:17.476  1035  7106 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:17.476  1035  7106 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:17.477  7097  7097 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 18:49:17.477  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.477  1976  7108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:17.477  1035  7106 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:17.477  1035  7106 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.477  1035  7106 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.477  1035  7106 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 18:49:17.478  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.478  1976  7108 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:17.478  1035  7106 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:17.478  1035  7106 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.478  1035  7106 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.478  1035  7106 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:17.478  1035  1540 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-31 18:49:17.479  1035  1540 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.479  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.479  1035  1540 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.479  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.479  1035  1540 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.479  1035  1540 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.479  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.479  1035  1540 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.480  1035  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.480  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.480  1035  1540 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.480  1035  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.480  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.480  1035  1540 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:17.480  1035  1035 E WifiServerServiceExt: No p2p device connected
08-31 18:49:17.482  1976  2322 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 18:49:17.495  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 18:49:17.518  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 18:49:17.518  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:17.519  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 18:49:17.519  7077  7077 I HubEmail: JNI_OnLoad()
08-31 18:49:17.519  7077  7077 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 18:49:17.519  7077  7077 I HubEmail: registerNatives()
08-31 18:49:17.519  7077  7077 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 18:49:17.519  7077  7077 I HubEmail: registerNativeMethods()
08-31 18:49:17.519  7077  7077 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-31 18:49:17.520  7077  7077 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-31 18:49:17.566  1035  1782 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7115 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-31 18:49:17.573  6950  7112 W FormManager: Network not available. Please check & try again.
08-31 18:49:17.575  7077  7114 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:17.582  6950  7113 V FormManager: Network unavailable.
,08-31 18:49:17.586  6950  7113 V FormManager: Network unavailable.
08-31 18:49:17.590  1035  1051 I ActivityManager: Killing 6558:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-31 18:49:17.633  1035  2091 W libprocessgroup: failed to open /acct/uid_10061/pid_6558/cgroup.procs: No such file or directory
,08-31 18:49:17.714  7115  7115 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:17.714  7115  7115 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 18:49:17.718  7115  7115 D PhoneMonitor: Register our PhoneStateListener
08-31 18:49:17.745  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-31 18:49:17.750  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 18:49:17.776  7115  7115 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-31 18:49:17.778  7115  7115 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-31 18:49:17.780  7115  7115 D TelephonyAutoProfiling: [parse] Load xml
08-31 18:49:17.788  7115  7115 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-31 18:49:17.788  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-31 18:49:17.788  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-31 18:49:17.788  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,08-31 18:49:17.788  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-31 18:49:17.788  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-31 18:49:17.788  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-31 18:49:17.788  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-31 18:49:17.789  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-31 18:49:17.789  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-31 18:49:17.789  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-31 18:49:17.789  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-31 18:49:17.789  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-31 18:49:17.789  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-31 18:49:17.789  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-31 18:49:17.789  7115  7115 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-31 18:49:17.789  7115  7115 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-31 18:49:17.803  7115  7115 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-31 18:49:17.816  1035  1993 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7134 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 18:49:17.817  1035  1993 I ActivityManager: Killing 6179:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-31 18:49:17.864  1035  2115 W libprocessgroup: failed to open /acct/uid_10097/pid_6179/cgroup.procs: No such file or directory
,08-31 18:49:18.016  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 18:49:18.016  1035  7106 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 18:49:18.016  7097  7097 E wpa_supplicant: USIM:  scard_init function
08-31 18:49:18.016  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 18:49:18.016  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-31 18:49:18.016  1035  7106 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 18:49:18.017  7097  7097 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 18:49:18.018  1035  1541 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 18:49:18.018  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 18:49:18.018  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-31 18:49:18.019  1035  1541 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 18:49:18.020  1035  1541 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 18:49:18.021  1035  1541 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 18:49:18.022  1035  1541 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-31 18:49:18.051  1035  1051 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7152 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-31 18:49:18.052  1035  1051 I ActivityManager: Killing 6597:com.lge.eula/1000 (adj 15): empty #17
,08-31 18:49:18.095  1035  2091 W libprocessgroup: failed to open /acct/uid_1000/pid_6597/cgroup.procs: No such file or directory
08-31 18:49:18.097  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=197911  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 18:49:18.111  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.111  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:18.112  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 18:49:18.112  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.112  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 18:49:18.113  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.117  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=197931  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 18:49:18.117  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.117  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.117  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 18:49:18.118  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:18.118  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 18:49:18.135  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.135  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 18:49:18.138  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.141  7097  7097 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 18:49:18.141  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 18:49:18.141  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 18:49:18.142  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 18:49:18.142  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 18:49:18.142  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:18.142  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:18.143  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=197958  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 18:49:18.144  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=197958  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 18:49:18.144  1035  1541 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197959
08-31 18:49:18.145  1035  1541 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197959
08-31 18:49:18.145  1035  1541 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197959
08-31 18:49:18.145  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197960
08-31 18:49:18.145  1035  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 18:49:18.151  1035  1541 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=197965
08-31 18:49:18.151  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=197965  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 18:49:18.151  7097  7097 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 18:49:18.152  7097  7097 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 18:49:18.152  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:18.153  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:18.153  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 18:49:18.154  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 18:49:18.154  1035  7106 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 18:49:18.154  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 18:49:18.154  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 18:49:18.154  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.154  1035  7106 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 18:49:18.154  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.154  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 18:49:18.154  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:18.154  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:18.158  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.158  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.158  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 18:49:18.159  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=197973  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 18:49:18.159  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.160  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:18.160  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:18.160  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-31 18:49:18.161  1035  1541 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:18.161  1035  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:18.162  1035  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:18.162  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:18.164  1035  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:18.164  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=197978  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 18:49:18.164  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=197979  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 18:49:18.165  1035  1541 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=197979
08-31 18:49:18.165  1035  1541 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=197979
08-31 18:49:18.165  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.165  1035  1541 D WifiNative-wlan0: doString: [STATUS]
08-31 18:49:18.166  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:18.166  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:18.166  1035  1541 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 18:49:18.167  1035  1541 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 18:49:18.168  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.168  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:18.169  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.216  1035  1050 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7169 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 18:49:18.217  1035  1050 I ActivityManager: Killing 6614:com.lge.bnr/1000 (adj 15): empty #17
,08-31 18:49:18.325  1035  1541 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 18:49:18.325  1035  1993 W libprocessgroup: failed to open /acct/uid_1000/pid_6614/cgroup.procs: No such file or directory
08-31 18:49:18.325  1035  1541 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-31 18:49:18.349  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.349  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 18:49:18.349  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 18:49:18.349  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.349  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:18.356  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.359  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.359  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.359  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 18:49:18.371  1035  1541 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 18:49:18.372  1035  1547 D ConnectivityService: Got NetworkAgent Messenger
08-31 18:49:18.372  1035  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 18:49:18.372  1035  1547 D ConnectivityService: NetworkAgent connected
08-31 18:49:18.372  1035  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 18:49:18.372  1035  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-31 18:49:18.373  1035  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 18:49:18.373  1035  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 18:49:18.381  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.381  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:18.383  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.386  1035  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 18:49:18.386  1035  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 18:49:18.386  1035  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 18:49:18.387  1035  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 18:49:18.387  1035  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 18:49:18.393  7169  7169 I art     : Almond Protected OAT
08-31 18:49:18.408  1035  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-31 18:49:18.412   309   892 D CommandListener: Setting iface cfg
08-31 18:49:18.415  1035  1541 E WifiStateMachine: Start Dhcp Watchdog 2
08-31 18:49:18.415  1035  7187 D DhcpStateMachine: StoppedState
08-31 18:49:18.415  1035  7187 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.415  1035  7187 D DhcpStateMachine: WaitBeforeStartState
08-31 18:49:18.415  1035  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=198229  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:18.416  1035  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=198230  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:18.416  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=198230  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:18.417  1035  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=198231  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:18.418  1035  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=198232  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:18.418  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=198232  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:18.419  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:152002] from screen [on:0 period:-511624109] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 18:49:18.420  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-511624108] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 18:49:18.420  1035  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 18:49:18.425  1035  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-31 18:49:18.425  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:18.425  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 18:49:18.426  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.426  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.426  1035  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.427  1035  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.427  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.427  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.428  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.428  1035  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 18:49:18.428  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=155,0,0
08-31 18:49:18.428  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=155,0,0
08-31 18:49:18.429  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 18:49:18.429  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 18:49:18.429  1035  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 18:49:18.429  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 18:49:18.430  1035  1541 D WifiNative-wlan0: SET ps 0: returned true
08-31 18:49:18.430  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 18:49:18.430  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 18:49:18.430  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 18:49:18.430  1035  1541 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 18:49:18.430  1035  1541 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 18:49:18.430  1035  1541 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 18:49:18.431   309   892 D CommandListener: Setting iface cfg
08-31 18:49:18.431   309   892 D CommandListener: Trying to bring up wlan0
08-31 18:49:18.432  1035  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.432  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.432  1035  1540 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.432  1035  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c39c38e target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.432  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c39c38e target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.432  1035  7187 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.432  1035  7187 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 18:49:18.434  1035  1541 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 18:49:18.434  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:18.435  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 18:49:18.435  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:18.435  10,35  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 18:49:18.436  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.437  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.437  1035  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.437  1035  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.438  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.438  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:18.439  1035  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 18:49:18.439  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 18:49:18.439  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-31 18:49:18.439  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 18:49:18.439  1035  1540 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.439  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.440  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 18:49:18.440  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 18:49:18.440  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 18:49:18.440  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 18:49:18.440  1035  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 18:49:18.440  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 1
,08-31 18:49:18.450  7169  7169 D WeatherApplication: removeAccount
08-31 18:49:18.451  7169  7169 D WeatherApplication: Account.length = 0
08-31 18:49:18.451  7169  7169 E WeatherApplication: OPERATOR:OPEN
,08-31 18:49:18.456  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:18
08-31 18:49:18.458  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 18:49:18.458  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
08-31 18:49:18.459  1035  1541 D WifiNative-wlan0: SET ps 1: returned true
08-31 18:49:18.459  1035  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-31 18:49:18.460  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 18:49:18.460  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 18:49:18.460  1035  1541 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 18:49:18.460  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 18:49:18.460  1035  1547 D ConnectivityService: ignoring duplicate network state non-change
08-31 18:49:18.463  7169  7169 D WeatherAncestor: connectivity changed - connection : true
,08-31 18:49:18.464  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-31 18:49:18.466  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.466  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:18.467  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.467  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.468  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 18:49:18.468  1035  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 18:49:18.469  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.470  1035  1547 D ConnectivityService: Adding iface wlan0 to network 101
08-31 18:49:18.470  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.471  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.471  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 18:49:18.475  1035  1541 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 18:49:18.476  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.476  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:18.477  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.477  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 18:49:18.480  1976  1976 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 18:49:18.481  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.482  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.482  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 18:49:18.483  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 18:49:18.486  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 18:49:18.486  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 18:49:18.486  7169  7169 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-31 18:49:18.496  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.496  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:18.496  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 18:49:18.497  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.497  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 18:49:18.497  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.503  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:18.505  1035  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 18:49:18.505  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 18:49:18.505  1035  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-31 18:49:18.506  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.506  1035  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 18:49:18.506  1035  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-31 18:49:18.507  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 18:49:18.507   309   892 E Netd    : netlink response contains error (File exists)
08-31 18:49:18.507  1035  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-31 18:49:18.507  1035  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 18:49:18.507  1035  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 18:49:18.508  1035  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 18:49:18.508  1035  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-31 18:49:18.508  1035  1547 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-31 18:49:18.508  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-31 18:49:18.508  1035  1541 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-31 18:49:18.512  1035  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 18:49:18.512  1035  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 18:49:18.512  1035  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-31 18:49:18.513  1035  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 18:49:18.513  1035  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:18.513  1035  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:18.513  1035  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 18:49:18.513  1035  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.513  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.513  1035  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 18:49:18.513  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 18:49:18.513  1035  1547 D ConnectivityService: currentScore = 0, newScore = 20
08-31 18:49:18.513  1035  1547 D ConnectivityService:    accepting network in place of null
08-31 18:49:18.513  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:18.513  1035  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.513  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 18:49:18.513  1881  1881 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.514  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 18:49:18.514  1035  1541 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.514  1035  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:18.515  1035  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 18:49:18.515  1035  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 18:49:18.515  1035  1547 D ConnectivityService: sendStickyBroadcast: ,action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 18:49:18.516  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 18:49:18.517  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 18:49:18.517  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 18:49:18.517  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 18:49:18.517   309  7192 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 18:49:18.518  1035  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:18.518  1035  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 18:49:18.518  1035  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-31 18:49:18.519  1035  1547 D ConnectivityService: validation of new default Network = false
08-31 18:49:18.519  1035  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 18:49:18.519  1035  1547 D DSQN    : enableDataServiceNotify 
08-31 18:49:18.519  1035  1547 D DSQN    : start dsqn bin
,08-31 18:49:18.538  1035  1539 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-31 18:49:18.543  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 18:49:18.543  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:18
08-31 18:49:18.545  1035  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 18:49:18.545  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.545  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:18.545  1035  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:18.546  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 18:49:18.539  7194  7194 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:18.539  7194  7194 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:18.565  7194  7194 E DSQN    : DSQN ssw
,08-31 18:49:18.575  1035  2068 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7198 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 18:49:18.576  1035  2068 I ActivityManager: Killing 2204:com.lge.music/u0a34 (adj 15): empty #17
08-31 18:49:18.586   313  1383 V AudioFlinger: 2204 died, releasing its sessions
08-31 18:49:18.586   313  1383 V AudioFlinger:  pid 1881 @ 0
08-31 18:49:18.587   313  1383 V AudioFlinger:  pid 3452 @ 1
08-31 18:49:18.587   313  1383 V AudioFlinger:  pid 3452 @ 2
,08-31 18:49:18.590   309  7192 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-31 18:49:18.603  1846  7193 I CheckinService: active receiver: enabled
08-31 18:49:18.603  1035  1782 W libprocessgroup: failed to open /acct/uid_10034/pid_2204/cgroup.procs: No such file or directory
,08-31 18:49:18.613  1846  7193 I CheckinService: Preparing to send checkin request
08-31 18:49:18.613  1846  7193 I EventLogService: Accumulating logs since 1472662019227
,08-31 18:49:18.620  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 18:49:18.620  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.621  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.626   309  7192 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-31 18:49:18.634  1035  7187 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 18:49:18.635  1035  7187 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 18:49:18.635  1035  7187 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-31 18:49:18.629  7216  7216 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:18.629  7216  7216 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:18.644  7216  7216 I dhcpcd  : version 5.5.6 starting
08-31 18:49:18.645  7216  7216 E dhcpcd  : get_duid: m
08-31 18:49:18.645  7216  7216 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 18:49:18.645  7216  7216 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-31 18:49:18.652  1846  7193 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-31 18:49:18.655   309   891 D LGDataListener: argv[0]=dsqncommand
08-31 18:49:18.655   309   891 D LGDataListener: argv[1]=wlan0
08-31 18:49:18.655   309   891 D LGDataListener: argv[2]=1
08-31 18:49:18.655   309   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 18:49:18.656  1035  1095 D DSQN    : DSQM DsqnNotification wlan0  1
08-31 18:49:18.656  1035  1095 D DSQN    : start to monitor internet connection
,08-31 18:49:18.684  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 16:49:18 GMT], X-Android-Received-Millis=[1472662158684], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472662158655]}
08-31 18:49:18.684  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 18:49:18.684  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 18:49:18.684  1035  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-31 18:49:18.684  1035  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-31 18:49:18.684  1035  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:18.684  1035  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:18.684  1035  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-31 18:49:18.684  1035  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-31 18:49:18.684  1035  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-31 18:49:18.684  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.684  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:18.685  1035  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:18.685  1035  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.685  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 18:49:18.685  1881  1881 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.685  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 18:49:18.685  1035  1541 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:18.685  1035  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:18.686  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 18:49:18.687   278   397 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 18:49:18.687   278   397 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 18:49:18.687   278   397 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 18:49:18.688  7198  7224 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 18:49:18.693   278   397 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 18:49:18.693   278   397 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 18:49:18.693   278   397 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 18:49:18.694  7198  7224 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-31 18:49:18.699  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 18:49:18.700  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.700  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:18.701  7216  7216 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 18:49:18.701   278   397 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 18:49:18.701  7216  7216 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 18:49:18.701   278   397 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-31 18:49:18.701   278   397 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 18:49:18.701  7216  7216 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 18:49:18.701  7216  7216 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 18:49:18.701  7216  7216 D dhcpcd  : wlan0: sending REQUEST (xid 0x5d9fa0f5), next in 3.13 seconds
08-31 18:49:18.701  7198  7229 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-31 18:49:18.703   278   397 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-31 18:49:18.703   278   397 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-31 18:49:18.703   278   397 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 18:49:18.704  7198  7229 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-31 18:49:18.742  7216  7216 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-31 18:49:18.746  1035  2068 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7232 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-31 18:49:18.757   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 213us total 10.254ms
08-31 18:49:18.767   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.708ms
,08-31 18:49:18.772  7216  7216 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 18:49:18.772  7216  7216 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 18:49:18.772  7216  7216 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 18:49:18.773  7216  7216 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 18:49:18.773  7216  7216 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 18:49:18.773  7216  7216 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 18:49:18.773  7216  7216 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 18:49:18.773  7216  7216 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 18:49:18.776   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 8.889ms
,08-31 18:49:18.822  7232  7232 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 18:49:18.823  7232  7232 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 18:49:18.850  7232  7232 I MultiDex: VM with version 2.1.0 has multidex support
,08-31 18:49:18.850  7232  7232 I MultiDex: install
,08-31 18:49:18.850  7232  7232 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-31 18:49:18.859  7232  7232 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-31 18:49:18.870  7198  7198 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-31 18:49:18.878  7198  7198 I LibraryLoader: Loading: webviewchromium
08-31 18:49:18.882  7198  7198 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8704-8707)
08-31 18:49:18.882  7198  7198 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 18:49:18.886  7198  7198 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {376cc05c}
08-31 18:49:18.886  7198  7198 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 18:49:18.887  7198  7198 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 18:49:18.894  7198  7198 I BrowserStartupController: Initializing chromium process, renderers=0
,08-31 18:49:18.895  7198  7198 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 18:49:18.906  7198  7198 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-31 18:49:18.906  7198  7198 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-31 18:49:18.906  7198  7198 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-31 18:49:18.909   313  1384 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10093
,08-31 18:49:18.911  7198  7288 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 18:49:18.919  7198  7198 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 18:49:18.919  7198  7198 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 18:49:18.919  7198  7198 I Adreno-EGL: Build Date: 12/12/14 금
08-31 18:49:18.919  7198  7198 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 18:49:18.919  7198  7198 I Adreno-EGL: Remote Branch: 
08-31 18:49:18.919  7198  7198 I Adreno-EGL: Local Patches: 
08-31 18:49:18.919  7198  7198 I Adreno-EGL: Reconstruct Branch: 
,08-31 18:49:19.038  1035  7187 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-31 18:49:19.039  1035  7187 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 18:49:19.039  1035  7187 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 18:49:19.039  1035  7187 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 18:49:19.039  1035  7187 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 18:49:19.039  1035  7187 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 18:49:19.039  1035  7187 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 18:49:19.039  1035  7187 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 18:49:19.040  1035  7187 D DhcpStateMachine: RunningState
08-31 18:49:19.109  7232  7258 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:19.109  7232  7258 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 18:49:19.111  1035  1782 I art     : Explicit concurrent mark sweep GC freed 105814(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.546ms total 112.602ms
08-31 18:49:19.133  7198  7198 I NSApplication: Starting up...
,08-31 18:49:19.155  7300  7300 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 18:49:19.189  1035  1051 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7308 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 18:49:19.190  1035  1051 I ActivityManager: Killing 6112:com.android.vending/u0a44 (adj 15): empty #17
08-31 18:49:19.210  7300  7300 I dex2oat : dex2oat took 55.291ms (threads: 4)
,08-31 18:49:19.225  7232  7258 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 18:49:19.225  7232  7258 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 18:49:19.225  7232  7258 I Adreno-EGL: Build Date: 12/12/14 금
08-31 18:49:19.225  7232  7258 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 18:49:19.225  7232  7258 I Adreno-EGL: Remote Branch: 
08-31 18:49:19.225  7232  7258 I Adreno-EGL: Local Patches: 
08-31 18:49:19.225  7232  7258 I Adreno-EGL: Reconstruct Branch: 
,08-31 18:49:19.304  1035  1782 W libprocessgroup: failed to open /acct/uid_10044/pid_6112/cgroup.procs: No such file or directory
,08-31 18:49:19.312  7232  7258 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 18:49:19.312  7232  7258 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 18:49:19.312  7232  7258 I Adreno-EGL: Build Date: 12/12/14 금
08-31 18:49:19.312  7232  7258 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 18:49:19.312  7232  7258 I Adreno-EGL: Remote Branch: 
08-31 18:49:19.312  7232  7258 I Adreno-EGL: Local Patches: 
08-31 18:49:19.312  7232  7258 I Adreno-EGL: Reconstruct Branch: 
08-31 18:49:19.345  7308  7308 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 18:49:19.444  1035  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-31 18:49:19.445  1035  1051 D WifiService: setWifiEnabled: false pid=6733, uid=10118
08-31 18:49:19.445  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 18:49:19.450  7232  7258 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-31 18:49:19.450  7232  7258 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-31 18:49:19.450  7232  7258 I Adreno-EGL: Build Date: 12/12/14 금
08-31 18:49:19.450  7232  7258 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-31 18:49:19.450  7232  7258 I Adreno-EGL: Remote Branch: 
08-31 18:49:19.450  7232  7258 I Adreno-EGL: Local Patches: 
08-31 18:49:19.450  7232  7258 I Adreno-EGL: Reconstruct Branch: 
08-31 18:49:19.464  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 18:49:19.468  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 18:49:19.468  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 18:49:19.470  1035  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 18:49:19.470  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-31 18:49:19.470  1035  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-31 18:49:19.470  1035  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-31 18:49:19.471  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-31 18:49:19.471  1035  1541 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 18:49:19.471  1035  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 18:49:19.471  1035  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 18:49:19.472  1035  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 18:49:19.472  1035  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 18:49:19.480  1035  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 18:49:19.480  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 18:49:19.480  1035  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.480  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.481  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-31 18:49:19.483  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 18:49:19.483  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 18:49:19.483  1035  1541 D WifiNative-wlan0: SET ps 1: returned true
08-31 18:49:19.484  1035  7187 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.489   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-31 18:49:19.509  1035  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-31 18:49:19.509  1035  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-31 18:49:19.512  1976  1976 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-31 18:49:19.514  1035  1035 D WifiHS20: hidePasspointNotification off =false
,08-31 18:49:19.514  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:19.514  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:19.514  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 18:49:19.515  1035  1035 D WifiHS20: hidePasspointNotification off =false
08-31 18:49:19.516  1035  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:19.516  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:19.517  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:19.517  1035  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:19.518  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:19.518  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:19.518  1035  1541 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 18:49:19.519  1035  1540 D LGWifiP2pService: InactiveState{ when=-9ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.519  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.519  1035  1540 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@888c823
08-31 18:49:19.521  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:19.521  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 18:49:19.523  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:19.523  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:19.523  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:19.525  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:19.525  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:19.526  1035  1540 D LGWifiP2pService: P2pDisablingState
08-31 18:49:19.526  1035  1540 D LGWifiP2pService: P2pDisablingState{ when=-7ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.526  1035  1540 D LGWifiP2pService: p2p socket connection lost
08-31 18:49:19.526  1035  1540 D LGWifiP2pService: P2pDisabledState
08-31 18:49:19.526  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:19.527  1035  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-31 18:49:19.527  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 18:49:19.528  7097  7097 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 18:49:19.528  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 18:49:19.528  1035  1035 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 18:49:19.528  1035  1035 D RttService: SCAN_AVAILABLE : 1
08-31 18:49:19.528  1035  1559 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.528  1035  1560 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.528  1035  1540 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.528  1035  1540 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.529  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 18:49:19.529  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 18:49:19.530  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 18:49:19.530  1976  1976 D WfdsService: WifiP2pState is changed : false
08-31 18:49:19.531  1976  2322 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-31 18:49:19.531  1976  2322 D WfdsService: Set the WFDS Monitor: false
08-31 18:49:19.531  1976  2322 D WfdsMonitor: WFDS Monitor is stopped
08-31 18:49:19.531  1035  1541 D WifiNative-wlan0: SET ps 1: returned true
08-31 18:49:19.531  1976  2322 D WfdsService: STATE : WfdsDisabledState - enter
08-31 18:49:19.531  1976  7108 D CtrlSupplicant: Received on exit socket, terminate
08-31 18:49:19.531  1976  7108 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-31 18:49:19.531  1976  7108 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-31 18:49:19.531  1976  7108 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-31 18:49:19.532  1976  2324 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-31 18:49:19.532  1976  2322 W WfdsService: DefaultState - msg [9445378] is not handled
08-31 18:49:19.548   309   892 D CommandListener: Clearing all IP addresses on wlan0
08-31 18:49:19.548  1035  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-31 18:49:19.548  1035  1547 D DSQN    : disableDataServiceNotify
08-31 18:49:19.548 , 1035  1547 D DSQN    : stop dsqn bin
08-31 18:49:19.549  1035  1541 D WifiNative-p2p0: doBoolean: TERMINATE
08-31 18:49:19.549  1035  1541 D WifiNative-p2p0: TERMINATE: returned true
08-31 18:49:19.549  1035  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 18:49:19.549  1035  1541 E WifiStateMachine: useWiFiOffloading() : false
08-31 18:49:19.549  1035  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 18:49:19.549  1035  1035 D WifiHS20: hidePasspointNotification off =false
,08-31 18:49:19.551  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 18:49:19.551  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:19.552  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:19.553  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 18:49:19.553  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:19.553  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-31 18:49:19.554  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-31 18:49:19.554  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:19.554  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-31 18:49:19.554  1035  1035 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-31 18:49:19.554  1035  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-31 18:49:19.554  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:19.554  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:19.555  1035  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:19.555  1035  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-31 18:49:19.555  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.555  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.555  1035  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-31 18:49:19.555  1035  7186 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 18:49:19.555  1035  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-31 18:49:19.555  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 18:49:19.555  1035  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:19.555  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 18:49:19.556  1035  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:19.556  1035  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:19.556  1035  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:19.556  1035  1547 D NetworkManagementService: Removing idletimer
08-31 18:49:19.556  1035  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:19.556  1035  1547 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 18:49:19.556  1035  1547 D ConnectivityService: Ne,tTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-31 18:49:19.556  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 18:49:19.557  1881  1881 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:19.557  1035  1541 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:19.557  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:19.557  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:19.557  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:19.557  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:19.557  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:19.557  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:19.557  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:19.557  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:19.557  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:19.557  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 18:49:19.557  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:19.557  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:19.557  1035  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:19.557  1035  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 18:49:19.559  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:19.559  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:19.559  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:19.559  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:19.559  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:19.559  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:19.559  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:19.559  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:19.559  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:19.559  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:19.559  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetoo,th: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:19.559  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 18:49:19.559  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 18:49:19.559  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 18:49:19.559  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 18:49:19.560  1035  1539 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-31 18:49:19.560  1035  1035 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-31 18:49:19.560  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 18:49:19.560  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 18:49:19.561  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 18:49:19.572  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:19.589  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 18:49:19.589  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 18:49:19.590  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:19.603  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 18:49:19.603  6419  6872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 18:49:19.612  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 18:49:19.613  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:19.613  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:19.615  2244  2244 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:49:19.623  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 18:49:19.624  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:19.624  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 18:49:19.624  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 18:49:19.625  7031  7031 I AppUp4:CustModeStarterReceiver: onReceive
08-31 18:49:19.627  7031  7031 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3938f53d
08-31 18:49:19.627  7031  7031 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-31 18:49:19.627  7031  7031 D AppUp4:CustFacade: isPhone : true
08-31 18:49:19.627  7031  7031 D AppUp4:CustModeStarterReceiver: begin check event
08-31 18:49:19.627  7031  7031 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 18:49:19.629  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:19.629  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 18:49:19.630  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:19.631  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:19.635  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 18:49:19.636  4328  7339 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 18:49:19.644  4328  7341 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:19.644  4328  7341 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 18:49:19.647  7077  7342 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:19.651  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 18:49:19.651  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:19.651  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 18:49:19.653  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 18:49:19.654  7097  7097 I wpa_supplicant: monitor socket send errors count : 1
08-31 18:49:19.654  7097  7097 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1976-4\x00 that cannot receive messages
08-31 18:49:19.654  1035  7106 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-31 18:49:19.655  1035  7106 D WifiMonitor: Dropping event because (p2p0) is stopped
08-31 18:49:19.655  6950  7345 W FormManager: Network not available. Please check & try again.
08-31 18:49:19.655  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 18:49:19.656  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 18:49:19.656  6950  7346 V FormManager: Network unavailable.
,08-31 18:49:19.664  6950  7346 V FormManager: Network unavailable.
08-31 18:49:19.666  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:19
08-31 18:49:19.669  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 18:49:19.669  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
08-31 18:49:19.669  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 18:49:19.669  7169  7169 D WeatherAncestor: connectivity changed - connection : true
08-31 18:49:19.669  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a595e83
08-31 18:49:19.670  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 18:49:19.670  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 18:49:19.670  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 18:49:19.670  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-31 18:49:19.672  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:19
,08-31 18:49:19.675  7097  7097 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 18:49:19.675  7097  7097 W wpa_supplicant: USIM:  scard_deinit function
08-31 18:49:19.675  1035  1097 D Tethering: InitialState.processMessage what=4
08-31 18:49:19.676  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-31 18:49:19.676  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 18:49:19.676  1035  7106 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-31 18:49:19.676  1035  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 18:49:19.676  1035  7106 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-31 18:49:19.676  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:19.676  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:19.677  1035  1541 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=199491
08-31 18:49:19.677  1035  1541 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=199491
08-31 18:49:19.677  1035  1541 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:19.678  1035  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:19.678  1035  1541 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=199492  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 18:49:19.678  1035  1541 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=199492  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-31 18:49:19.690  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 18:49:19.690  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 18:49:19.690  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 18:49:19.690  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 18:49:19.690  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-31 18:49:19.691  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 18:49:19.691  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 18:49:19.691  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 18:49:19.691  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 18:49:19.691  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 18:49:19.692  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 18:49:19.695  1035  7187 D DhcpStateMachine: StoppedState
08-31 18:49:19.695  1035  7187 D DhcpStateMachine: StoppedState{ when=-163ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:19.697  1035  1541 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-31 18:49:19.697  1035  1541 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-31 18:49:19.698  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:19.700  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-31 18:49:19.707  6950  7352 V FormManager: Network unavailable.
,08-31 18:49:19.714  6950  7351 W FormManager: Network not available. Please check & try again.
08-31 18:49:19.715  6950  7352 V FormManager: Network unavailable.
08-31 18:49:19.716  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:19.737  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 18:49:19.741  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 18:49:19.742  6950  7354 W FormManager: Network not available. Please check & try again.
08-31 18:49:19.746  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:19.749  6950  7355 V FormManager: Network unavailable.
,08-31 18:49:19.752  6950  7355 V FormManager: Network unavailable.
08-31 18:49:19.755  7097  7097 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 18:49:19.756   309  7357 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-31 18:49:19.757  1035  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-31 18:49:19.757  1035  7106 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-31 18:49:19.757  1035  7106 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-31 18:49:19.757  1035  7106 D WifiMonitor: Disconnecting from the supplicant, no more events
08-31 18:49:19.757  1846  7193 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-31 18:49:19.758  1035  1541 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-31 18:49:19.759  1035  1541 D WifiOffDelayIfNotUsed: stopMonitoring
08-31 18:49:19.759  1035  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 18:49:19.759  1035  1541 E WifiStateMachine: useWiFiOffloading() : false
08-31 18:49:19.759  1035  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 18:49:19.760  1976  1976 D WfdsService: Supplicant Connection state is changed : false
08-31 18:49:19.760  1976  2322 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-31 18:49:19.760  1976  2322 D WfdsService: Set the WFDS Monitor: false
08-31 18:49:19.760  1976  2322 D WfdsMonitor: WFDS Monitor is stopped
08-31 18:49:19.761  2478  2478 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:19.761  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-31 18:49:19.761  1035  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-31 18:49:19.761  1035  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-31 18:49:19.761  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-31 18:49:19.762  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:19.766  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:19.766  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:19.766  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:19.766  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:19.766  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:19.766  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:19.766  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:19.766  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:19.766  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:19.767  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:19.767  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 18:49:19.767  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 18:49:19.768  1846  7193 I CheckinService: active receiver: disabled
08-31 18:49:19.769  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:19.775  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.,startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:19.779  4328  7358 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 18:49:19.781  4328  7359 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 18:49:19.781  4328  7359 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 18:49:19.818  1035  1996 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7360 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 18:49:19.903  7360  7360 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 18:49:19.903  7360  7360 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 18:49:19.914  7360  7360 V [BNRBootReceiver]: Boot Receiver Return
08-31 18:49:19.915  7360  7360 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 18:49:19.918  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 18:49:19.932  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:19.944  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:19.957  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:19.958  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 18:49:19.960  6904  6904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 18:49:19.968  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-31 18:49:19.976  6853  6853 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 18:49:19.985  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.004  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.017  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.030  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:20.031  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.034  6904  6904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 18:49:20.041  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.056  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.063  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.070  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 18:49:20.070  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.071  6904  6904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:20.075  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.082  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.089  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.096  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:20.097  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.097  6904  6904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 18:49:20.101  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.109  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.117  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.129  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:20.130  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.130  6904  6904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 18:49:20.136  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.142  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.151  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.158  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 18:49:20.159  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.161  6904  6904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:20.167  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.180  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.189  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.198  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 18:49:20.198  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.200  6904  6904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:20.213  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 18:49:20.234  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.245  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.259  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:20.260  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 18:49:20.265  6904  6904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:20.273  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.289  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.299  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.312  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:20.312  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 18:49:20.314  6904  6904 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 18:49:20.322  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.327  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 18:49:20.339  1035  1546 D WifiService: New client listening to asynchronous messages
08-31 18:49:20.340  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 18:49:20.346  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.354  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 18:49:20.366  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:20.367  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.368  6904  6904 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 18:49:20.369  6904  6904 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-31 18:49:20.370  6904  6904 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-31 18:49:20.379  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.383  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 18:49:20.387  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:20.391  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.400  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.411  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:20.411  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 18:49:20.413  6904  6904 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 18:49:20.414  6904  6904 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 18:49:20.414  6904  6904 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 18:49:20.417  1035  2091 I ActivityManager: Killing 6831:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-31 18:49:20.452  6631  7021 D UEI.SmartControl: Internal timer expired: 2
08-31 18:49:20.452  6631  7021 D UEI.SmartControl: unbind internal service
,08-31 18:49:20.465  1035  1993 W libprocessgroup: failed to open /acct/uid_10037/pid_6831/cgroup.procs: No such file or directory
,08-31 18:49:20.472  2244  2244 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-31 18:49:20.489  2244  2244 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-31 18:49:20.490  2244  2244 D c       : Getting all permits...
08-31 18:49:20.490  2244  2244 D a       : Opening database...
08-31 18:49:20.500  2244  2244 D a       : Opening database auth.proximity.permit_store...
08-31 18:49:20.503  2244  2244 D a       : Closing database...
,08-31 18:49:20.523  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 18:49:20.534  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 18:49:20.534  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 18:49:20.534  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:20.542  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 18:49:20.543  6631  7018 D serial_port: close(fd = 24)
,08-31 18:49:20.549  6631  7018 I UEI.SmartControl: Serial port is closed.
,08-31 18:49:20.558  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.576  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 18:49:20.577  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.581  6904  6904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 18:49:20.589  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:20.596  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-31 18:49:20.596  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 18:49:20.596  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 18:49:20.604  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.610  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 18:49:20.618  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:20.619  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.622  6904  6904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 18:49:20.628  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 18:49:20.631  6873  6873 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-31 18:49:20.631  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-31 18:49:20.631  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:20.640  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:20.649  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.662  6904  6904 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-31 18:49:20.663  6904  6904 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:20.666  6904  6904 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 18:49:20.682  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 18:49:20.687  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 18:49:20.698  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 18:49:20.714  6950  7385 W FormManager: Network not available. Please check & try again.
,08-31 18:49:20.724  6950  7386 V FormManager: Network unavailable.
08-31 18:49:20.729  6950  7386 V FormManager: Network unavailable.
,08-31 18:49:20.737  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 18:49:20.737  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 18:49:20.739  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:20.744  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 18:49:20.750  4328  7387 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 18:49:20.755  4328  7388 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 18:49:20.755  4328  7388 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 18:49:20.759  6873  6873 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-31 18:49:20.759  6873  6873 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-31 18:49:20.759  6873  6873 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:20.766  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 18:49:20.768  6950  7390 W FormManager: Network not available. Please check & try again.
,08-31 18:49:20.771  6950  7391 V FormManager: Network unavailable.
,08-31 18:49:20.773  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:20.774  6950  7391 V FormManager: Network unavailable.
08-31 18:49:20.790  2244  2244 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-31 18:49:21.428  1035  1541 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-511621100] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 18:49:21.430  1035  1541 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-511621098] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-31 18:49:21.520  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:49:21.536  1035  1097 D Tethering: MasterInitialState.processMessage what=3
08-31 18:49:21.543  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:21.546  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:21.549  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:21.553  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 18:49:21.554  6419  6872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 18:49:21.567  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-31 18:49:21.585  2244  2244 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-31 18:49:21.604  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 18:49:21.604  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:21.604  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 18:49:21.604  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-31 18:49:21.609  7031  7031 I AppUp4:CustModeStarterReceiver: onReceive
08-31 18:49:21.613  7031  7031 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3938f53d
08-31 18:49:21.613  7031  7031 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 18:49:21.613  7031  7031 D AppUp4:CustFacade: isPhone : true
08-31 18:49:21.614  7031  7031 D AppUp4:CustModeStarterReceiver: begin check event
08-31 18:49:21.614  7031  7031 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 18:49:21.618  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:21.619  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 18:49:21.620  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-31 18:49:21.626  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:21.634  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-31 18:49:21.656  4328  7400 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 18:49:21.664  7077  7399 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:21.672  4328  7401 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:21.672  4328  7401 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 18:49:21.683  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:21.694  6950  7402 W FormManager: Network not available. Please check & try again.
08-31 18:49:21.698  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 18:49:21.698  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:21.698  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = true
08-31 18:49:21.698  3452  3452 D PhoneState: setPdpRejectCasuse : false
,08-31 18:49:21.705  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 18:49:21.705  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 18:49:21.713  6950  7403 V FormManager: Network unavailable.
,08-31 18:49:21.727  6950  7403 V FormManager: Network unavailable.
08-31 18:49:21.727  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:21
,08-31 18:49:21.728  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-31 18:49:21.728  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
08-31 18:49:21.729  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 18:49:21.729  7169  7169 D WeatherAncestor: connectivity changed - connection : true
08-31 18:49:21.729  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a595e83
08-31 18:49:21.730  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 18:49:21.730  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-31 18:49:21.730  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0,
08-31 18:49:21.730  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-31 18:49:21.730  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:21
08-31 18:49:22.472  1035  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,08-31 18:49:22.487  1035  1763 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-31 18:49:22.511  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 18:49:22.511  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 18:49:22.511  1035  1035 D Ulp_jni : JNI:system_update. Event-4
,08-31 18:49:22.515  1035  1097 D BluetoothManagerService: Message: 1
08-31 18:49:22.515  1035  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-31 18:49:22.546  1035  1097 D BluetoothManagerService: Message: 20
08-31 18:49:22.546  1035  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@138e2b6f:true
08-31 18:49:22.547  6969  6969 D BluetoothAdapterState: make
08-31 18:49:22.552  6969  6969 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 18:49:22.552  6969  6969 I bluedroid-qcom: init
,08-31 18:49:22.556  6969  7432 I BluetoothAdapterState: Entering OffState
08-31 18:49:22.557  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.561  1035  1097 D Tethering: MasterInitialState.processMessage what=3
08-31 18:49:22.565  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:22.568  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:22.573  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.573  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.576  6969  6969 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 18:49:22.576  6969  6969 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 18:49:22.576  6969  6969 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 18:49:22.576  6969  6969 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 18:49:22.576  6969  6969 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 18:49:22.578  6969  6969 I bluedroid-qcom: get_profile_interface socket
08-31 18:49:22.578  6969  6969 I bluedroid-qcom: get_profile_interface map_client
,08-31 18:49:22.583  6969  7436 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 18:49:22.579  7435  7435 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:22.579  7435  7435 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:22.595  1035  1097 D Tethering: MasterInitialState.processMessage what=3
,08-31 18:49:22.604  7435  7435 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 18:49:22.604  7435  7435 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 18:49:22.604  7435  7435 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 18:49:22.606  7435  7435 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 18:49:22.610  6969  7436 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 18:49:22.614  7435  7435 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 18:49:22.614  7435  7435 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-31 18:49:22.617  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:22.619  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:22.621  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-31 18:49:22.621  1035  1097 D BluetoothManagerService: Message: 40
08-31 18:49:22.621  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 18:49:22.623  6969  6986 I bluedroid-qcom: config_hci_snoop_log
,08-31 18:49:22.627  1035  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 18:49:22.627  1035  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 18:49:22.632  6969  7432 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 18:49:22.632  6969  7436 D BluetoothAdapterProperties: Name is: G3
08-31 18:49:22.633  6969  7432 D BluetoothAdapterProperties: Setting state to 11
08-31 18:49:22.633  6969  7432 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 18:49:22.634  1035  1097 D BluetoothManagerService: Message: 60
08-31 18:49:22.634  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 18:49:22.634  1035  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 18:49:22.635  6969  7432 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 18:49:22.638  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 18:49:22.638  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 18:49:22.647  6969  7432 D BluetoothBondStateMachine: make
08-31 18:49:22.649  6969  7432 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:22.649  6969  7432 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 18:49:22.650  6969  7432 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:22.650  6969  7432 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 18:49:22.650  6969  7432 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-31 18:49:22.653  6969  7437 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 18:49:22.654  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-31 18:49:22.663  6419  6872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-31 18:49:22.667  1976  1976 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:22.668  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 18:49:22.686  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:22.687  6969  7432 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:22.688  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 18:49:22.692  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 18:49:22.694  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:22.707  6969  6969 D HeadsetService: Received start request. Starting profile...
08-31 18:49:22.708  6969  7432 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:22.708  6969  6969 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 18:49:22.708  6969  6969 D LGBluetoothHfpAdapter: Version 1.6
08-31 18:49:22.710  1035  1091 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.711  6969  6969 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 18:49:22.712  6969  6969 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 18:49:22.712  6969  6969 D HeadsetStateMachine: make
,08-31 18:49:22.717  6969  7432 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:22.718  5796  5796 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-31 18:49:22.719  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:22.721  1035  1091 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:22.725  6969  7432 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 18:49:22.732  6969  7432 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:22.739  6969  7432 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 18:49:22.744  2244  2244 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.744  6969  6969 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:22.744  6969  6969 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 18:49:22.747  6969  7432 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:22.752  6969  6969 D HeadsetStateMachine: max_hf_connections = 1
08-31 18:49:22.752  6969  6969 I bluedroid-qcom: get_profile_interface handsfree
,08-31 18:49:22.754  6969  6969 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 18:49:22.755   313  1384 V AudioPolicyService: registerClient() client 0xb57f6420, uid 1002
08-31 18:49:22.755   313   313 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 18:49:22.755   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 18:49:22.755   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 18:49:22.756  6969  6969 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 18:49:22.756   313  1383 V AudioFlinger: registerClient() client 0xb5581b08, pid 6969
08-31 18:49:22.756   313  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:22.756   313  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:22.756  1605  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:22.756  1605  1624 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:22.757  3452  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:22.757  3452  3468 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:22.757  1035  1584 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:22.757  1035  1584 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:22.757  1881  1896 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:22.757  1881  1896 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:22.757  6969  6986 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:22.757  6969  6986 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 18:49:22.757   313  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:22.757   313  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:22.757  1605  3510 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:22.757  1605  3510 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:22.758  3452  3467 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:22.758  3452  3467 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:22.758  1035  1995 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:22.758  1035  1995 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:22.758  1881  1897 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:22.758  1881  1897 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:22.758  6969  6986 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:22.758  6969  6986 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 18:49:22.758  6969  6969 V ToneGenerator: Create Track: 0xb4928080
08-31 18:49:22.758  6969  6969 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 18:49:22.758  6969  6969 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 18:49:22.759   313  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 18:49:22.759   313  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 18:49:22.759   313  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 18:49:22.759   313  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 18:49:22.759   313   313 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 18:49:22.759   313  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 18:49:22.759   313  1383 V AudioPolicyManager: ,getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 18:49:22.759   313  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 18:49:22.760   313  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 18:49:22.760  6969  6969 V AudioSystem: getLatency() output 2, latency 50
08-31 18:49:22.760  6969  6969 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 18:49:22.760  6969  6969 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 18:49:22.761   313  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 18:49:22.761   313  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 18:49:22.761   313  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 18:49:22.761   313  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 18:49:22.761   313  1384 V AudioFlinger: createTrack() lSessionId: 22
08-31 18:49:22.762  6969  6969 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 18:49:22.762   313   313 V AudioFlinger: acquiring 22 from 6969, for 6969
08-31 18:49:22.762   313   313 V AudioFlinger:  added new entry for 22
08-31 18:49:22.762  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 18:49:22.762  6969  6969 V ToneGenerator: ToneGenerator INIT OK, time: 202590
08-31 18:49:22.762  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:22.762  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.763  6969  7456 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 18:49:22.763  6969  7456 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 18:49:22.763  6969  7456 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 18:49:22.763  6969  7456 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 18:49:22.764  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 18:49:22.764  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 18:49:22.766   313  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6969
08-31 18:49:22.766  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:22.767  6969  6969 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 18:49:22.768  6969  6969 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:22.768  6969  6969 V BluetoothPbapReceiver: ***********state = 11
08-31 18:49:22.768  6969  7432 V LGMDMManager: Create singleton instance
08-31 18:49:22.768  7031  7031 I AppUp4:CustModeStarterReceiver: onReceive
08-31 18:49:22.769   313  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 18:49:22.769   313  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 18:49:22.769   313  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 18:49:22.769   313  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 18:49:22.769   313  1384 V voice   : voice_set_parameters: exit with code(0)
08-31 18:49:22.769   313  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 18:49:22.769   313  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-31 18:49:22.769   313  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 18:49:22.769   313  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 18:49:22.769   313  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 18:49:22.769   313  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 18:49:22.770  6969  7456 V ToneGenerator: ToneGenerator destructor
08-31 18:49:22.770  6969  7456 V ToneGenerator: stopTone
08-31 18:49:22.770  6969  7456 V ToneGenerator: Delete Track: 0xb4928080
08-31 18:49:22.771  6969  7456 V AudioTrack: ~AudioTrack, releasing session id from 6969 on behalf of 6969
08-31 18:49:22.771   313   313 V AudioFlinger: releasing 22 from 6969 for 6969
08-31 18:49:22.771   313   313 V AudioFlinger:  decremented refcount to 0
08-31 18:49:22.771   313   313 V AudioFlinger: purging stale effects
08-31 18:49:22.771   313   313 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 18:49:22.771   313   313 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 18:49:22.771   313  1259 V AudioPolicyService: AudioCommandThread() waking up
08-31 18:49:22.771   313  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 18:49:22.771   313  1259 V AudioPolicyManager: releaseOutput() 2
08-31 18:49:22.771   313  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 18:49:22.771   313   313 V AudioFlinger: PlaybackThread::Track destructor
08-31 18:49:22.771   313   313 V AudioFlinger: removeClient_l() pid 6969, calling pid 313
,08-31 18:49:22.773  6969  6969 D A2dpService: Received start request. Starting profile...
08-31 18:49:22.774  6969  6969 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 18:49:22.775  6969  6969 V Avrcp   : make
08-31 18:49:22.775  2244  2244 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 18:49:22.775  6969  6969 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 18:49:22.775  6969  6969 I bluedroid-qcom: get_profile_interface avrcp
08-31 18:49:22.776  6969  7432 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 18:49:22.782  7031  7031 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3938f53d
08-31 18:49:22.782  7031  7031 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 18:49:22.782  7031  7031 D AppUp4:CustFacade: isPhone : true
08-31 18:49:22.782  7031  7031 D AppUp4:CustModeStarterReceiver: begin check event
08-31 18:49:22.782  7031  7031 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-31 18:49:22.831  1035  2091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7459 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-31 18:49:22.844  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.845  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 18:49:22.847  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:22.853  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:22.859  6969  6969 V AudioManager: registerRemoteController: size of Media player list: 0
,08-31 18:49:22.863  6969  6969 E AudioManager: No RCC entry present to update
08-31 18:49:22.863  6969  6969 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 18:49:22.864  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 18:49:22.865  4328  7478 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-31 18:49:22.867  6969  6969 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 18:49:22.868  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 18:49:22.869  6969  6969 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-31 18:49:22.874  4328  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.874  4328  7479 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-31 18:49:22.879  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 18:49:22.968  7077  7482 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 18:49:22.980  6950  7484 V FormManager: Network unavailable.
,08-31 18:49:22.982  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 18:49:22.982  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:22.982  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 18:49:22.983  6950  7483 W FormManager: Network not available. Please check & try again.
08-31 18:49:22.985  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 18:49:22.986  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-31 18:49:22.994  6950  7484 V FormManager: Network unavailable.
,08-31 18:49:23.006  1035  1782 V SIM_STK : Menu title from STK is T-Mobile
08-31 18:49:23.006  1035  1782 V SIM_STK : Menu title from STK is T-Mobile
08-31 18:49:23.012  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:23
,08-31 18:49:23.016  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 18:49:23.016  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
08-31 18:49:23.016  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 18:49:23.017  7169  7169 D WeatherAncestor: connectivity changed - connection : true
08-31 18:49:23.017  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a595e83
08-31 18:49:23.017  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 18:49:23.017  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 18:49:23.017  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 18:49:23.017  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 18:49:23.018  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:23
08-31 18:49:23.032  6419  6419 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-31 18:49:23.033  6419  6872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-31 18:49:23.043  7459  7459 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-31 18:49:23.044  7459  7459 W LG Account v2.2: No ProfileInfo entries
08-31 18:49:23.044  7459  7459 I LG Account v2.2: isEnabled: false
08-31 18:49:23.044  7459  7459 I Feature : [Lifetracker]ver: 4.21.112(40211120)
,08-31 18:49:23.044  7459  7459 I Feature : [Lifetracker]Country: EU
08-31 18:49:23.044  7459  7459 I Feature : [Lifetracker]Operator: OPEN
08-31 18:49:23.044  7459  7459 I Feature : [Lifetracker]Ranking support: false
08-31 18:49:23.044  7459  7459 I Feature : [Lifetracker]Comfort support: false
08-31 18:49:23.045  7459  7459 I Feature : [Lifetracker]Accessory: true
08-31 18:49:23.045  7459  7459 I Feature : [Lifetracker]Health device: true
,08-31 18:49:23.045  7459  7459 I Feature : [Lifetracker]Extra Pedometer: false
08-31 18:49:23.045  7459  7459 I Feature : [Lifetracker]Blood glucose device: false
08-31 18:49:23.045  7459  7459 I Feature : [Lifetracker]Device Number: 3
08-31 18:49:23.051  2244  2244 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:23.055  6853  6853 D BluetoothPermissionRequest: onReceive
08-31 18:49:23.057  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 18:49:23.066  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-31 18:49:23.066  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:23.066  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-31 18:49:23.066  7031  7031 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-31 18:49:23.067  7031  7031 I AppUp4:CustModeStarterReceiver: onReceive
,08-31 18:49:23.070  7031  7031 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3938f53d
08-31 18:49:23.070  7031  7031 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 18:49:23.070  7031  7031 D AppUp4:CustFacade: isPhone : true
08-31 18:49:23.071  7031  7031 D AppUp4:CustModeStarterReceiver: begin check event
08-31 18:49:23.071  7031  7031 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-31 18:49:23.074  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:23.074  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-31 18:49:23.075  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:23.078  1035  2091 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 18:49:23.078  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:23.083  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 18:49:23.084  7077  7077 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-31 18:49:23.086  4328  7488 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 18:49:23.087  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 18:49:23.087  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 18:49:23.088  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 18:49:23.088  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 18:49:23.088  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 18:49:23.088  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 18:49:23.088  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 18:49:23.088  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 18:49:23.088  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 18:49:23.088  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 18:49:23.088  6969  6969 I BluetoothA2dpServiceJni: classInitNative
08-31 18:49:23.088  6969  6969 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 18:49:23.088  6969  6969 D A2dpStateMachine: make
08-31 18:49:23.089  6969  6969 I bluedroid-qcom: get_profile_interface a2dp
08-31 18:49:23.090  6969  7491 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 18:49:23.090  4328  7489 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:23.090  4328  7489 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 18:49:23.091  6969  6969 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 18:49:23.091  6969  6969 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 18:49:23.092  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.092  6969  7490 D A2dpStateMachine: Enter Disconnected: -2
08-31 18:49:23.093  6969  6969 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 18:49:23.094  6969  6969 D HidService: Received start request. Starting profile...
08-31 18:49:23.094  6969  6969 I bluedroid-qcom: get_profile_interface hidhost
08-31 18:49:23.094  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.094  6969  6969 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 18:49:23.095  6969  6969 D HealthService: Received start request. Starting profile...
08-31 18:49:23.097  6969  6969 I bluedroid-qcom: get_profile_interface health
08-31 18:49:23.097  6969  6969 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 18:49:23.097  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.097  6969  6969 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 18:49:23.099  6969  6969 D PanService: Received start request. Starting profile...
08-31 18:49:23.099  6969  6969 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 18:49:23.099  6969  6969 I bluedroid-qcom: get_profile_interface pan
,08-31 18:49:23.103  7077  7496 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:23.104  6969  6969 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-31 18:49:23.104  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.106  6969  6969 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 18:49:23.108  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-31 18:49:23.108  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:23.109  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = false
08-31 18:49:23.111  7115  7115 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-31 18:49:23.112  7115  7115 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-31 18:49:23.112  6969  6969 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 18:49:23.113  6969  6969 D BtGatt.GattService: Received start request. Starting profile...
08-31 18:49:23.113  6950  7499 W FormManager: Network not available. Please check & try again.
08-31 18:49:23.113  6969  6969 D BtGatt.GattService: start()
08-31 18:49:23.113  6969  6969 I bluedroid-qcom: get_profile_interface gatt
08-31 18:49:23.113  6969  6969 D BtGatt.AdvertiseManager: advertise manager created
08-31 18:49:23.122  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.122  6969  6969 D HeadsetStateMachine: Proxy object connected
08-31 18:49:23.123  6969  6969 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 18:49:23.123  6969  6969 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-31 18:49:23.124  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.124  6969  6969 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 18:49:23.125  6950  7500 V FormManager: Network unavailable.
08-31 18:49:23.125  6969  6969 V BluetoothMapService: BluetoothMapBinder()
08-31 18:49:23.126  7169  7169 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:23
,08-31 18:49:23.126  6969  6969 D BluetoothMapService: Received start request. Starting profile...
08-31 18:49:23.126  6969  6969 D BluetoothMapService: start()
08-31 18:49:23.128  7169  7169 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-31 18:49:23.128  7169  7169 D Weather.Utils: 2 : All the weather widget is gone.
08-31 18:49:23.128  7169  7169 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-31 18:49:23.128  7169  7169 D WeatherAncestor: connectivity changed - connection : true
08-31 18:49:23.128  7169  7169 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3a595e83
08-31 18:49:23.129  6969  6969 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-31 18:49:23.129  6969  6969 D BluetoothMapEmailAppObserver: createReceiver()
08-31 18:49:23.129  6950  7500 V FormManager: Network unavailable.
08-31 18:49:23.130  6969  6969 D BluetoothMapEmailAppObserver: initObservers()
08-31 18:49:23.130  6969  6969 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 18:49:23.132  7169  7169 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-31 18:49:23.132  7169  7169 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-31 18:49:23.132  7169  7169 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-31 18:49:23.132  7169  7169 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-31 18:49:23.133  7169  7169 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:49:23
08-31 18:49:23.137  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.138  6969  7456 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-31 18:49:23.140  6969  6969 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 18:49:23.140  6969  7456 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 18:49:23.141  6969  7456 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 18:49:23.142  6969  6969 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 18:49:23.144  6969  6969 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 18:49:23.146  6969  6969 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 18:49:23.146  6969  6969 V PanService: [BTUI] SIM Extra State :ABSENT
08-31 18:49:23.148  6969  6969 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 18:49:23.150  6969  6969 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-31 18:49:23.150  6969  6969 V BluetoothMapService: Handler(): got msg=1
08-31 18:49:23.151  6969  7432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 18:49:23.151  6969  7432 I bluedroid-qcom: enable
08-31 18:49:23.151  6969  7432 I bt_hci_bdroid: init
,08-31 18:49:23.152  6969  6969 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.153  6969  7503 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 18:49:23.153  6969  7432 I bt_vendor: bt-vendor : init
08-31 18:49:23.153  6969  7432 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 18:49:23.153  6969  7432 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 18:49:23.153  6969  7432 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 18:49:23.153  6969  7432 D bt_userial_mct: userial_init
08-31 18:49:23.153  6969  6969 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 18:49:23.154  6969  6969 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 18:49:23.154  6969  6969 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 18:49:23.154  6969  7503 I bt-btu  : btu_task pending for preload complete event
08-31 18:49:23.154  6969  6969 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.154  6969  7432 D bt_hci_bdroid: set_power 1
08-31 18:49:23.154  6969  7432 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 18:49:23.154  6969  7432 I bt_vendor: Starting hciattach daemon
08-31 18:49:23.154  6969  6969 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 18:49:23.154  6969  7432 I bt_vendor: try to set true
08-31 18:49:23.149  7506  7506 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:23.149  7506  7506 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:23.173  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 18:49:23.252  7513  7513 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 18:49:23.266  7514  7514 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 18:49:23.317  7516  7516 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 18:49:23.343  7517  7517 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 18:49:23.368  7518  7518 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 18:49:23.389  7519  7519 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 18:49:23.422  7524  7524 I libmdmdetect: ESOC framework not supported
,08-31 18:49:23.423  7524  7524 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 18:49:23.431  7524  7524 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 18:49:23.431  7524  7524 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 18:49:23.431  7524  7524 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 18:49:23.431  7524  7524 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 18:49:23.431  7524  7524 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 18:49:23.431  7524  7524 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 18:49:23.431  7524  7524 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 18:49:23.474  7524  7525 E QC-QMI  : qmi_client [7524] 14: failed to locate client data
,08-31 18:49:23.478   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 18:49:23.478   474   474 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-31 18:49:23.525  7526  7526 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 18:49:23.552  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 18:49:23.606  6969  7432 I bt_vendor: bluetooth satus is on
08-31 18:49:23.606  6969  7432 D bt_hci_bdroid: preload
08-31 18:49:23.606  6969  7505 D bt_userial_mct: userial_open(port:0)
08-31 18:49:23.607  6969  7505 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 18:49:23.612  6969  7505 I bt_vendor: Done intiailizing UART
08-31 18:49:23.616  6969  7505 I bt_vendor: Done intiailizing UART
08-31 18:49:23.616  6969  7505 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 18:49:23.619  6969  7505 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 18:49:23.620  6969  7529 D bt_userial_mct: Entering userial_read_thread()
08-31 18:49:23.620  6969  7503 I bt-btu  : btu_task received preload complete event
08-31 18:49:23.621  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 18:49:23.622  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-31 18:49:23.631  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-31 18:49:23.640  6969  7503 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 18:49:23.640  6969  7503 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 18:49:23.640  6969  7503 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 18:49:23.640  6969  7503 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 18:49:23.640  6969  7503 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 18:49:23.640  6969  7503 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_BTM
,08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 18:49:23.641  6969  7503 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 18:49:23.694  6969  7503 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 18:49:23.694  6969  7503 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a8061 
08-31 18:49:23.694  6969  7503 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a8061 
,08-31 18:49:23.715  7198  7227 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-31 18:49:23.722  6969  7436 E bt-btif : Calling BTA_HhEnable
08-31 18:49:23.722  6969  7436 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 18:49:23.722  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 18:49:23.722  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 18:49:23.722  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 18:49:23.722  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 18:49:23.722  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 18:49:23.722  6969  7436 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 18:49:23.723  6969  7436 D BluetoothAdapterProperties: Name is: G3
08-31 18:49:23.724  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 18:49:23.724  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
,08-31 18:49:23.725  6969  7436 D BluetoothAdapterProperties: Scan Mode:20
08-31 18:49:23.725  6969  7436 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 18:49:23.725  6969  7436 D bt_hci_bdroid: postload
08-31 18:49:23.725  6969  7505 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 18:49:23.726  6969  7503 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 18:49:23.726  6969  7436 D bte_conf: Device ID record 1 : primary
08-31 18:49:23.726  6969  7436 D bte_conf:   vendorId            = 00c4
08-31 18:49:23.726  6969  7436 D bte_conf:   vendorIdSource      = 0001
08-31 18:49:23.726  6969  7436 D bte_conf:   product             = 13a1
08-31 18:49:23.726  6969  7436 D bte_conf:   version             = 1000
08-31 18:49:23.726  6969  7436 D bte_conf:   clientExecutableURL = 
08-31 18:49:23.726  6969  7436 D bte_conf:   serviceDescription  = 
08-31 18:49:23.726  6969  7436 D bte_conf:   documentationURL    = 
,08-31 18:49:23.726  6969  7436 D bte_conf: bte_load_did_conf no section named DID2.
08-31 18:49:23.729  6969  7503 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:23.729  6969  7503 W bt-smp  : Plain text(LSB ~ MSB) = ff bb 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:23.729  6969  7503 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 a7 39 35 28 8d c5 5c 83 18 a1 ae f7 48 fd 9d 
,08-31 18:49:23.730  6969  7503 W bt-btm  : Stopping oneshot timer
08-31 18:49:23.730  6969  7505 D bt_hci_bdroid: Used up Tx Cmd credits
,08-31 18:49:23.734  6969  7505 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 18:49:23.734  6969  7505 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 18:49:23.719  7533  7533 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:23.719  7533  7533 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:23.737  6969  7432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 18:49:23.737  6969  7432 D BluetoothAdapterProperties: ScanMode =  20
08-31 18:49:23.737  6969  7432 D BluetoothAdapterProperties: State =  11
08-31 18:49:23.737  6969  7432 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 18:49:23.737  6969  7432 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 18:49:23.737  6969  7432 D BluetoothAdapterProperties: Setting state to 12
08-31 18:49:23.737  6969  7432 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 18:49:23.738  6969  7436 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 18:49:23.738  6969  7436 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 18:49:23.739  6969  7505 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 18:49:23.741  6969  7432 I BluetoothAdapterState: Entering On State
08-31 18:49:23.742  6969  7529 E bt_mct  : hci lib postload completed
08-31 18:49:23.743  1035  1097 D BluetoothManagerService: Message: 60
08-31 18:49:23.743  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 18:49:23.744  1035  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-31 18:49:23.745  6969  7432 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 18:49:23.749  1881  2449 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:49:23.749  6969  7432 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 18:49:23.749  6969  7432 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 18:49:23.751  6969  7432 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 18:49:23.754  6969  7436 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 18:49:23.754  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:23.754  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:23.754  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:23.754  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:23.754  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:23.754  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:23.754  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:23.754  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:23.754  6969  7436 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-31 18:49:23.756  6853  6869 D BluetoothPan: onBluetoothStateChange on: true
08-31 18:49:23.756  6853  6869 D BluetoothPan: onBluetoothStateChange call bindService
08-31 18:49:23.757  1881  1881 D BluetoothHeadset: Proxy object connected
,08-31 18:49:23.758  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:23.764  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:23.764  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:23.764  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:23.764  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:23.764  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:23.764  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:23.764  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:23.764  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:23.766  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:23.766  6853  6869 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 18:49:23.768  6969  7503 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:23.768  6969  7503 W bt-smp  : Plain text(LSB ~ MSB) = 6d e7 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:23.768  6969  7503 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 9a f3 69 6b 0e 43 28 9d 43 c9 99 b3 af dc 56 
08-31 18:49:23.768  6969  7503 W bt-btm  : Stopping oneshot timer
08-31 18:49:23.769  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 18:49:23.769  6853  6853 D PanProfile: Bluetooth service connected
08-31 18:49:23.772  1035  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 18:49:23.774  6853  6869 D BluetoothMap: onBluetoothStateChange: up=true
08-31 18:49:23.775  1035  1035 D BluetoothA2dp: Proxy object connected
08-31 18:49:23.777  6853  7303 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 18:49:23.779  1035  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:49:23.779  1035  1035 D BluetoothHeadset: Proxy object connected
08-31 18:49:23.780  6853  6853 D BluetoothInputDevice: Proxy object connected
08-31 18:49:23.780  6853  6853 D HidProfile: Bluetooth service connected
08-31 18:49:23.780  1881  1897 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:49:23.782  6969  7503 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:23.783  6969  7503 W bt-smp  : Plain text(LSB ~ MSB) = 2c f8 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:23.783  6969  7503 W bt-smp  : Encrypted text(LSB ~ MSB) = 6e 02 24 eb 53 04 6d 56 b8 fa a5 4d 00 38 64 a5 
08-31 18:49:23.783  6969  7503 W bt-btm  : Stopping oneshot timer
,08-31 18:49:23.785  1881  1881 D BluetoothHeadset: Proxy object connected
08-31 18:49:23.786  1881  1896 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:49:23.788  1881  1881 D BluetoothHeadset: Proxy object connected
08-31 18:49:23.789  6853  6853 D BluetoothMap: Proxy object connected
08-31 18:49:23.789  6853  6853 D MapProfile: Bluetooth service connected
08-31 18:49:23.789  6853  6853 D BluetoothMap: getConnectedDevices()
08-31 18:49:23.790  6969  7450 V BluetoothMapService: getConnectedDevices()
08-31 18:49:23.791  1035  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 18:49:23.791  1035  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 18:49:23.792  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 18:49:23.792  6969  7432 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-31 18:49:23.793  1035  1097 D BluetoothManagerService: Message: 40
08-31 18:49:23.793  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 18:49:23.794  6969  7503 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:23.794  6969  7503 W bt-smp  : Plain text(LSB ~ MSB) = e9 c0 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:23.794  6969  7503 W bt-smp  : Encrypted text(LSB ~ MSB) = ff 35 2d 99 ff 25 e0 58 fd 89 16 fe ae f4 ad 9a 
08-31 18:49:23.795  6969  7503 W bt-btm  : Stopping oneshot timer
08-31 18:49:23.797  1976  1976 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.797  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 18:49:23.799  6733  6733 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-31 18:49:23.800  7538  7538 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 18:49:23.802  1976  2198 D LGBluetoothAPIService: Message: 1
08-31 18:49:23.803  1976  2198 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 18:49:23.806  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:23.809  6969  6969 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.809  6969  6969 D BluetoothMapService: STATE_ON
08-31 18:49:23.809  6969  6969 V BluetoothMapService: Handler(): got msg=1
08-31 18:49:23.810  6969  6969 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 18:49:23.810  1976  2198 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-31 18:49:23.812  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:23.815  6969  7503 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:23.815  6969  7503 W bt-smp  : Plain text(LSB ~ MSB) = 2b fc 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:23.815  6969  7503 W bt-smp  : Encrypted text(LSB ~ MSB) = 9a ff 06 4e 5b fa f2 68 6a d1 35 69 a1 96 e7 00 
08-31 18:49:23.815  6969  7503 W bt-btm  : Stopping oneshot timer
08-31 18:49:23.815  6853  6853 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 18:49:23.819  1035  1097 D BluetoothManagerService: Message: 30
08-31 18:49:23.821  6853  6853 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 18:49:23.823  6969  7539 D BluetoothMapMasInstance: MAS initSocket()
,08-31 18:49:23.824  6969  7539 D BluetoothMapMasInstance:   masId = 00
08-31 18:49:23.824  6969  7539 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 18:49:23.824  6969  7539 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 18:49:23.824  6969  7539 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 18:49:23.825  1035  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 18:49:23.828  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.828  6969  7539 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:23.828  6969  6969 V BluetoothPbapService: Pbap Service onCreate
08-31 18:49:23.828  6969  6969 V BluetoothPbapService: Starting PBAP service
08-31 18:49:23.829  6969  6969 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 18:49:23.830  6969  7539 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 18:49:23.830  6969  7539 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 18:49:23.830  6969  7539 D BluetoothMapMasInstance: Accepting socket connection...
08-31 18:49:23.830  6969  7436 D BluetoothAdapterProperties: Scan Mode:21
08-31 18:49:23.831  6969  7436 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 18:49:23.832  6969  6969 V BluetoothPbapService: Pbap Service onBind
08-31 18:49:23.833  1035  1097 D BluetoothManagerService: Message: 30
08-31 18:49:23.836  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:23.838  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:23.843  6969  6969 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.844  6969  6969 V BluetoothPbapService: state: 12
08-31 18:49:23.845  6969  6969 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 18:49:23.845  6969  6969 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 18:49:23.847  6969  6969 V BluetoothPbapService: Handler(): got msg=1
08-31 18:49:23.847  1976  1976 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 18:49:23.847  6969  6969 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 18:49:23.847  1976  2198 D LGBluetoothAPIService: Message: 100
08-31 18:49:23.847  1976  2198 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 18:49:23.848  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 18:49:23.848  6969  7545 V BluetoothPbapService: Pbap Service initSocket
08-31 18:49:23.849  1035  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:23.850  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 18:49:23.852  6969  7545 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:23.854  6969  7545 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 18:49:23.854  6969  7545 V BluetoothPbapService: Succeed to create listening socket 
08-31 18:49:23.854  6969  7545 V BluetoothPbapService: Accepting socket connection...
08-31 18:49:23.856  6969  6969 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 18:49:23.856  6969  6969 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.856  6969  6969 V BluetoothPbapReceiver: ***********state = 12
08-31 18:49:23.857  6853  6853 D BluetoothA2dp: Proxy object connected
08-31 18:49:23.858  6853  6853 D A2dpProfile: Bluetooth service connected
08-31 18:49:23.859  2244  2244 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 18:49:23.860  2244  2244 D c       : Getting all permits...
08-31 18:49:23.860  2244  2244 D a       : Opening database...
08-31 18:49:23.864  2244  2244 D a       : Opening database auth.proximity.permit_store...
,08-31 18:49:23.864  6853  6853 D BluetoothPbap: Proxy object connected
08-31 18:49:23.865  6853  6853 D PbapServerProfile: Bluetooth service connected
08-31 18:49:23.865  2244  2244 D a       : Closing database...
08-31 18:49:23.865  6853  6853 D BluetoothHeadset: Proxy object connected
08-31 18:49:23.866  6853  6853 D HeadsetProfile: Bluetooth service connected
08-31 18:49:23.876  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-31 18:49:23.882  6853  6853 D BluetoothPermissionRequest: onReceive
,08-31 18:49:23.886  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 18:49:23.889  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 18:49:23.892  6969  6969 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-31 18:49:23.895  6969  6969 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-31 18:49:23.907  6969  6969 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 18:49:23.933  6969  6969 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 18:49:23.933  6969  6969 V BtOppService: onCreate
,08-31 18:49:23.938  6969  6969 V BluetoothOppNotification: send message
08-31 18:49:23.941  6969  6969 V BtOppService: Starting RfcommListener
08-31 18:49:23.953  6969  6969 D BluetoothOppPreference: Dumping Names:  
08-31 18:49:23.953  6969  6969 D BluetoothOppPreference: {}
,08-31 18:49:23.953  6969  6969 D BluetoothOppPreference: Dumping Channels:  
,08-31 18:49:23.953  6969  6969 D BluetoothOppPreference: {}
08-31 18:49:23.954  6969  6969 V BtOppService: onStartCommand
08-31 18:49:23.959  6969  6969 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.959  6969  6969 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-31 18:49:23.959  6969  7553 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 18:49:23.963  6969  7550 V BtOppService: Deleted complete outbound shares, number =  0
08-31 18:49:23.964  6969  6969 V BluetoothOppNotification: new notify threadi!
08-31 18:49:23.965  6969  6969 V BluetoothOppNotification: send delay message
08-31 18:49:23.966  6969  7550 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 18:49:23.966  6969  6969 V BtOppService: start RfcommListener
08-31 18:49:23.968  6969  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 18:49:23.968  6969  7550 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 18:49:23.970  6969  6969 V BtOppService: RfcommListener started
08-31 18:49:23.971  6969  7550 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15879cbc on behalf of 
,08-31 18:49:23.973  6969  7553 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 18:49:23.976  6969  7555 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 18:49:23.977  1035  2068 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:23.977  6969  7553 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31e73445 on behalf of 
08-31 18:49:23.978  6969  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23bc779a on behalf of 
08-31 18:49:23.979  6969  7555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:23.980  6969  7555 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-31 18:49:23.981  6969  7555 V BtOppRfcommListener: Started RFCOMM listener....
08-31 18:49:23.981  6969  7555 I BtOppRfcommListener: Accept thread started.
08-31 18:49:23.981  6969  7555 V BtOppRfcommListener: Accepting connection...
08-31 18:49:23.981  6969  7554 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 18:49:23.982  6969  7553 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 18:49:23.983  6969  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-31 18:49:23.986  6969  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ecc08cb on behalf of 
08-31 18:49:23.988  6969  7554 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 18:49:23.989  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:23.989  6969  6969 V BluetoothFtpService: Ftp Service onCreate
08-31 18:49:23.989  6969  6969 I BluetoothFtpService: Ftp Service onCreate
08-31 18:49:23.990  6969  6969 V BluetoothFtpService: Ftp Service onStartCommand
08-31 18:49:23.990  6969  6969 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.990  6969  6969 V BluetoothFtpService: Starting Listening on sockets
08-31 18:49:23.990  6969  6969 V BtOppService: ContentObserver received notification
08-31 18:49:23.991  6969  6969 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 18:49:23.991  6969  6969 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 18:49:23.991  6969  6969 V BluetoothSapReceiver: SapReceiver onReceive 
,08-31 18:49:23.991  6969  6969 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:23.991  6969  6969 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 18:49:23.991  6969  6969 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 18:49:23.992  6969  7554 V BluetoothOppNotification: outbound notification was removed.
08-31 18:49:23.992  6969  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 18:49:23.993  6969  7556 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 18:49:23.993  6969  7556 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-31 18:49:23.994  6969  6969 V BtOppService: ContentObserver received notification
08-31 18:49:23.994  6969  6969 V BluetoothFtpService: Handler(): got msg=1
08-31 18:49:23.994  6969  6969 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 18:49:23.994  6969  6969 V BluetoothFtpService: Ftp Service initSocket
08-31 18:49:23.998  6969  7556 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@394bcfc1 on behalf of 
08-31 18:49:23.998  6969  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2eda7366 on behalf of 
08-31 18:49:23.999  6969  7554 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 18:49:23.999  1035  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:24.000  6969  7556 V BluetoothOppNotification: update too frequent, put in queue
08-31 18:49:24.001  6969  6969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 18:49:24.002  6969  6969 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-31 18:49:24.003  6969  6969 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 18:49:24.003  6969  7556 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 18:49:24.003  6969  7556 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 18:49:24.004  6969  7554 V BluetoothOppNotification: inbound notification was removed.
08-31 18:49:24.005  6969  7556 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@291066a7 on behalf of 
08-31 18:49:24.005  6969  7554 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 18:49:24.007  6969  7554 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@76cc754 on behalf of 
08-31 18:49:24.008  6969  7556 V BluetoothOppNotification: update too frequent, put in queue
08-31 18:49:24.009  6969  7556 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 18:49:24.011  6969  7557 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-31 18:49:24.024  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:24.024  6969  6969 V BluetoothSapService: Sap Service onCreate
,08-31 18:49:24.028  6969  6969 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 18:49:24.028  6969  6969 V BluetoothSapService: state: 12
08-31 18:49:24.029  6969  6969 V BluetoothSapService: Starting SAP server process
08-31 18:49:24.032  6969  6969 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 18:49:24.019  7558  7558 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:24.019  7558  7558 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:24.034  6969  7559 V BluetoothSapService: Sap Service initRfcommSocket
08-31 18:49:24.034  1035  1740 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:24.035  6969  7559 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:24.037  6969  7559 V BluetoothSapService: Succeed to create listening socket 
08-31 18:49:24.037  6969  7559 V BluetoothSapService: Accepting socket connection...
,08-31 18:49:24.047  7558  7558 V BT_SAP  : Event pipe created
,08-31 18:49:24.047  7558  7558 V BT_SAP  : create_server_socket qcom.sap.server
08-31 18:49:24.047  7558  7558 V BT_SAP  : created socket fd 6
08-31 18:49:24.527  1035  1540 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:24.527  1035  1540 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 18:49:24.554  1035  1541 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 18:49:24.555  1035  1541 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-31 18:49:24.625  1035  2091 I ActivityManager: Killing 7360:com.lge.bnr/1000 (adj 15): empty #17
,08-31 18:49:24.664  1035  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_7360/cgroup.procs: No such file or directory
,08-31 18:49:24.755  1035  1993 I ActivityManager: Killing 6631:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-31 18:49:24.786  6904  6904 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-31 18:49:24.787  6904  6904 W System.err: android.os.DeadObjectException
08-31 18:49:24.787  6904  6904 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 18:49:24.787  6904  6904 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 18:49:24.787  6904  6904 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-31 18:49:24.787  6904  6904 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-31 18:49:24.787  6904  6904 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 18:49:24.787  6904  6904 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 18:49:24.787  6904  6904 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 18:49:24.787  6904  6904 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 18:49:24.788  6904  6904 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 18:49:24.788  6904  6904 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 18:49:24.788  6904  6904 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:49:24.788  6904  6904 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 18:49:24.788  6904  6904 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 18:49:24.788  6904  6904 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 18:49:24.788  6904  6904 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-31 18:49:24.788  6904  6904 W System.err: android.os.DeadObjectException
08-31 18:49:24.788  6904  6904 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 18:49:24.788  6904  6904 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 18:49:24.789  6904  6904 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-31 18:49:24.789  6904  6904 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-31 18:49:24.789  6904  6904 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-31 18:49:24.789  6904  6904 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-31 18:49:24.789  6904  6904 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 18:49:24.789  6904  6904 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-31 18:49:24.796  6904  6904 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 18:49:24.796  6904  6904 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 18:49:24.796  6904  6904 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:49:24.796  6904  6904 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 18:49:24.796  6904  6904 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 18:49:24.796  6904  6904 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 18:49:24.796  6904  6904 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-31 18:49:24.797  6904  6904 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-31 18:49:24.824  1035  1763 W libprocessgroup: failed to open /acct/uid_1000/pid_6631/cgroup.procs: No such file or directory
08-31 18:49:24.824  1035  1763 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-31 18:49:24.840  6904  6904 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-31 18:49:24.840  6904  6904 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-31 18:49:24.890  1035  1051 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7569 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 18:49:24.890  6904  6904 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-31 18:49:24.966  6969  6969 V BluetoothOppNotification: new notify threadi!
08-31 18:49:24.966  6969  6969 V BluetoothOppNotification: send delay message
,08-31 18:49:24.970  6969  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 18:49:24.996  6969  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f7904c0 on behalf of 
08-31 18:49:24.998  6969  7586 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-31 18:49:25.006  6969  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 18:49:25.007  6969  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2279b5f9 on behalf of 
08-31 18:49:25.008  6969  7586 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 18:49:25.009  6969  7586 V BluetoothOppNotification: outbound notification was removed.
08-31 18:49:25.009  6969  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 18:49:25.009  6969  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ada893e on behalf of 
08-31 18:49:25.010  6969  7586 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 18:49:25.011  6969  7586 V BluetoothOppNotification: inbound notification was removed.
08-31 18:49:25.011  6969  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 18:49:25.012  6969  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8d1839f on behalf of 
08-31 18:49:25.084  1035  1740 I art     : Explicit concurrent mark sweep GC freed 92975(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.517ms total 139.658ms
,08-31 18:49:25.117  7569  7569 D UEI.SmartControl: Quickset Services start...
,08-31 18:49:25.118  7569  7569 I UEI.SmartControl: Manufacture = LGE
,08-31 18:49:25.119  7569  7569 D UEI.SmartControl: Id = LGNevo
08-31 18:49:25.119  7569  7569 D UEI.SmartControl: File observer start...
08-31 18:49:25.120  7569  7569 E UEI.SmartControl: IR Port is disabled: false
,08-31 18:49:25.120  7569  7569 D UEI.SmartControl: Starting file observer...
08-31 18:49:25.121  7569  7569 D UEI.SmartControl: Extracting JNI libs...
08-31 18:49:25.121  7569  7569 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-31 18:49:25.185  7569  7569 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-31 18:49:25.185  7569  7569 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-31 18:49:25.185  7569  7569 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-31 18:49:25.210  7569  7569 I UEI.SmartControl: --- Selecting new region: 6
08-31 18:49:25.211  7569  7569 I UEI.SmartControl: Model = LG-D855
08-31 18:49:25.213  7569  7569 D UEI.SmartControl: QS Service created
,08-31 18:49:25.242  7569  7569 I UEI.SmartControl: Service initServices...
,08-31 18:49:25.248  7569  7569 D UEI.SmartControl: QS start get config
,08-31 18:49:25.318  7569  7569 D UEI.SmartControl: Loading JNI Libs...
,08-31 18:49:25.537  1035  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 18:49:25.537  1035  1763 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3495e546 mBinding = false
,08-31 18:49:25.555  1035  1097 D BluetoothManagerService: Message: 2
08-31 18:49:25.556  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 18:49:25.556  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 18:49:25.556  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 18:49:25.557  1035  1097 D BluetoothManagerService: Sending off request.
08-31 18:49:25.558  6969  6988 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-31 18:49:25.558  6969  7432 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-31 18:49:25.558  6969  7432 D BluetoothAdapterProperties: Setting state to 13
08-31 18:49:25.558  6969  7432 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 18:49:25.559  6969  7432 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 18:49:25.559  6969  7432 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 18:49:25.560  6969  7436 D BluetoothAdapterProperties: Scan Mode:20
08-31 18:49:25.560  6969  7432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 18:49:25.561  6969  7555 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:25.561  6969  7432 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 18:49:25.561  6969  7557 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:25.563  6969  7559 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:25.563  6969  7545 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:25.563  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-31 18:49:25.563  6969  7503 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-31 18:49:25.564  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-31 18:49:25.564  6969  7503 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 18:49:25.566  6969  7539 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-31 18:49:25.566  6969  7539 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 18:49:25.566  6969  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-31 18:49:25.566  6969  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-31 18:49:25.566  6969  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-31 18:49:25.566  6969  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-31 18:49:25.566  6969  7539 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-31 18:49:25.566  6969  7539 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-31 18:49:25.568  1035  1097 D BluetoothManagerService: Message: 60
08-31 18:49:25.569  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-31 18:49:25.569  1035  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-31 18:49:25.572  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:25.572  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:25.572  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:25.572  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:25.572  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:25.572  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:25.572  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:25.572  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:25.572  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:49:25.573  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:25.573  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:25.573  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 18:49:25.574  1976  1976 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:25.576  6969  6969 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:25.576  6969  6969 D BluetoothMapService: STATE_TURNING_OFF
08-31 18:49:25.576  6969  6969 V BtOppService: Receiver DISABLED_ACTION 
08-31 18:49:25.576  6969  6969 V BluetoothMapService: Handler(): got msg=4
08-31 18:49:25.576  6969  6969 D BluetoothMapService: MAP Service closeService in
08-31 18:49:25.576  6969  6969 D BluetoothMapMasInstance: MAP Service shutdown
08-31 18:49:25.576  6969  6969 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 18:49:25.576  6969  6969 V BluetoothMapService: MAP Service closeService out
08-31 18:49:25.577  6969  6969 I BtOppRfcommListener: stopping Accept Thread
08-31 18:49:25.577  6969  6969 V BtOppRfcommListener: close mBtServerSocket
08-31 18:49:25.577  6969  6969 V BtOppRfcommListener: waiting for thread to terminate
08-31 18:49:25.577  6969  7555 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 18:49:25.578  6969  6969 V BtOppRfcommListener: done waiting for thread to terminate
08-31 18:49:25.582  6969  6969 V BtOppService: onDestroy
08-31 18:49:25.583  6969  6969 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-31 18:49:25.585  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:25.585  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:25.585  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:25.585  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:25.585  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:25.585  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 18:49:25.585  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:25.585  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:25.585  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:25.586  6733  6733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 18:49:25.586  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:25.586  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-31 18:49:25.587  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:25.588  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:25.588  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 18:49:25.592  6969  6969 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 18:49:25.592  6969  6969 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:25.592  6969  6969 V BluetoothPbapReceiver: ***********state = 13
08-31 18:49:25.593  6969  6969 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-31 18:49:25.596  6969  6969 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:25.596  6969  6969 V BluetoothPbapService: state: 13
08-31 18:49:25.596  6969  6969 V BluetoothPbapService: Pbap Service closeService in
,08-31 18:49:25.605  2244  2244 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 18:49:25.607  6969  6969 V BluetoothPbapService: successfully stopped pbap service
08-31 18:49:25.607  6969  6969 V BluetoothPbapService: Pbap Service closeService out
08-31 18:49:25.607  6969  6969 V BluetoothPbapService: Pbap Service onDestroy
08-31 18:49:25.607  6969  6969 V BluetoothPbapService: Pbap Service closeService in
08-31 18:49:25.607  6969  6969 V BluetoothPbapService: Pbap Service closeService out
08-31 18:49:25.607  6969  6969 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-31 18:49:25.608  6853  6853 D DockEventReceiver: finishStartingService: stopping service
08-31 18:49:25.608  6853  6853 D BluetoothPbap: Proxy object disconnected
08-31 18:49:25.608  6853  6853 D PbapServerProfile: Bluetooth service disconnected
08-31 18:49:25.620  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-31 18:49:25.625  6853  6853 D BluetoothPermissionRequest: onReceive
08-31 18:49:25.625  6853  6853 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-31 18:49:25.630  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 18:49:25.634  6969  6969 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-31 18:49:25.634  6969  6969 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-31 18:49:25.636  6969  6969 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-31 18:49:25.639  6969  6969 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:25.639  6969  6969 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 18:49:25.640  6969  6969 V BluetoothFtpService: Ftp Service onStartCommand
08-31 18:49:25.640  6969  6969 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:25.640  6969  6969 V BluetoothFtpService: Ftp Service closeService
08-31 18:49:25.641  6969  6969 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-31 18:49:25.641  6969  6969 V BluetoothFtpService: successfully stopped ftp service
08-31 18:49:25.642  6969  6969 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 18:49:25.642  6969  6969 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 18:49:25.642  6969  6969 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 18:49:25.642  6969  6969 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:25.642  6969  6969 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-31 18:49:25.642  6969  6969 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 18:49:25.650  6969  6969 V BluetoothFtpService: Ftp Service onDestroy
08-31 18:49:25.650  6969  6969 V BluetoothFtpService: Ftp Service closeService
,08-31 18:49:25.660  6969  6969 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:25.660  6969  6969 V BluetoothSapService: state: 13
08-31 18:49:25.660  6969  6969 V BluetoothSapService: Stopping SAP server process
08-31 18:49:25.662  6969  6969 V BluetoothSapService: Sap Service closeSapService in
08-31 18:49:25.663  6969  6969 V BluetoothSapService: Close listen Socket : 
08-31 18:49:25.663  6969  6969 V BluetoothSapService: Close rfcomm Socket : 
,08-31 18:49:25.663  6969  6969 V BluetoothSapService: Close sapd  Socket : 
,08-31 18:49:25.667  6969  6969 V BluetoothSapService: Sap Service closeSapService out
08-31 18:49:25.667  6969  6969 V BluetoothSapService: Sap Service onDestroy
08-31 18:49:25.668  6969  6969 V BluetoothSapService: Sap Service closeSapService in
08-31 18:49:25.668  6969  6969 V BluetoothSapService: Close listen Socket : 
08-31 18:49:25.668  6969  6969 V BluetoothSapService: Close rfcomm Socket : 
08-31 18:49:25.668  6969  6969 V BluetoothSapService: Close sapd  Socket : 
08-31 18:49:25.670  6969  6969 V BluetoothSapService: Sap Service closeSapService out
08-31 18:49:25.692  7569  7569 I UEI.SmartControl: Supports setup maps: true
,08-31 18:49:25.694  7569  7569 D UEI.SmartControl: QS start statue = true Error code = 0
08-31 18:49:25.695  7569  7569 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-31 18:49:25.695  7569  7569 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-31 18:49:25.695  7569  7569 I UEI.SmartControl: ### init IR Blaster...
08-31 18:49:25.699  7569  7569 D serial_port: Configuring serial port
08-31 18:49:25.702  7569  7569 E UEI.SmartControl: UEIBLaster setting for 616
08-31 18:49:25.702  7569  7569 I UEI.SmartControl: Setting serial record hearder size = 2
08-31 18:49:25.702  7569  7569 I UEI.SmartControl: configuring settings for MAXQ616
08-31 18:49:25.702  7569  7569 I UEI.SmartControl: Get version...
08-31 18:49:25.718  7569  7615 D UEI.SmartControl: serial port data available: 21
,08-31 18:49:25.746  7569  7569 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-31 18:49:25.746  7569  7569 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-31 18:49:25.747  7569  7569 I UEI.SmartControl: QS saving settings...
08-31 18:49:25.749  7569  7569 D UEI.SmartControl: IR Blaster version: 25672567
08-31 18:49:25.766  7569  7615 D UEI.SmartControl: serial port data available: 4
,08-31 18:49:25.803  7569  7619 I UEI.SmartControl: Device manager: loading config....
08-31 18:49:25.804  7569  7619 D UEI.SmartControl: ----------- loading internal config...
,08-31 18:49:25.806  7569  7569 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-31 18:49:25.809  7569  7569 E UEI.SmartControl: Services init done
08-31 18:49:25.809  7569  7569 D UEI.SmartControl: QS Service init finished
08-31 18:49:25.810  7569  7569 D UEI.SmartControl: QS Service version name: 2.1.91
08-31 18:49:25.811  7569  7569 D UEI.SmartControl: QS Service version code: 201091
08-31 18:49:25.812  7569  7569 D UEI.SmartControl: Service requested: Control
08-31 18:49:25.820  7569  7619 E UEI.SmartControl: Loading SETTINGS...
,08-31 18:49:25.823  7569  7569 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-31 18:49:25.828  6904  6904 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-31 18:49:25.829  1035  1993 I ActivityManager: Killing 6904:com.lge.qremote/u0a112 (adj 15): empty #17
08-31 18:49:25.830  7569  7584 I UEI.SmartControl: ------ IControl API: 11
08-31 18:49:25.833  7569  7584 I UEI.SmartControl: Registering callback...
,08-31 18:49:25.838  7569  7619 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-31 18:49:25.860  7569  7618 I UEI.SmartControl: Notify AllClients services are ready: 0
08-31 18:49:25.861  7569  7618 D UEI.SmartControl: -----service ready thread exits
,08-31 18:49:25.893  1035  1763 W libprocessgroup: failed to open /acct/uid_10112/pid_6904/cgroup.procs: No such file or directory
,08-31 18:49:25.895  7569  7569 D UEI.SmartControl: Internal service binding...
,08-31 18:49:26.469  6969  7436 D bt_hci_bdroid: cleanup
,08-31 18:49:26.477  6969  7505 I bt_lpm  : LPM is already off!!!
08-31 18:49:26.478  6969  7529 I bt_userial_mct: exiting userial_read_thread
08-31 18:49:26.478  6969  7529 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 18:49:26.481  6969  7503 W bt-btif : ag scb idx 1 not allocated
08-31 18:49:26.481  6969  7503 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 18:49:26.481  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:26.481  6969  7503 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:49:26.481  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:26.481  6969  7503 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:49:26.481  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:26.481  6969  7503 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 18:49:26.481  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:26.481  6969  7503 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-31 18:49:26.482  6969  7503 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 18:49:26.485  6969  7436 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 18:49:26.487  6969  7505 I bt_vendor: hw_epilog_process
,08-31 18:49:26.490  6969  7436 D bt_hci_bdroid: cleanup Finalizing cleanup
08-31 18:49:26.491  6969  7436 D bt_userial_mct: userial_close
08-31 18:49:26.491  6969  7436 E bt_userial_mct: pthread_join() FAILED result:3
08-31 18:49:26.491  6969  7436 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-31 18:49:26.491  6969  7503 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-31 18:49:26.493  6969  7436 D bt_hci_bdroid: set_power 0
08-31 18:49:26.493  6969  7436 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 18:49:26.493  6969  7436 I bt_vendor: bluetooth satus is on
08-31 18:49:26.493  6969  7436 I bt_vendor: bt-vendor : resetting BT status
08-31 18:49:26.493  6969  7436 I bt_vendor: Starting hciattach daemon
08-31 18:49:26.493  6969  7436 I bt_vendor: try to set false
08-31 18:49:26.495  6969  7436 I bt_vendor: Starting hciattach daemon
08-31 18:49:26.495  6969  7436 I bt_vendor: try to set false
08-31 18:49:26.497  6969  7436 I bt_vendor: cleanup
08-31 18:49:26.497  6969  7503 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-31 18:49:26.499  6969  7436 I GKI_LINUX: GKI_exit_task 0 done
08-31 18:49:26.499  6969  7436 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-31 18:49:26.503  6969  7432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 18:49:26.510  6969  6969 D HeadsetService: Received stop request...Stopping profile...
,08-31 18:49:26.514  6969  7432 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 18:49:26.515  6969  6969 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 18:49:26.515  6969  6969 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 18:49:26.515  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:26.516  6969  7456 D HeadsetStateMachine: Exit Disconnected: -1
08-31 18:49:26.518  1881  1881 D BluetoothHeadset: Proxy object disconnected
08-31 18:49:26.518  1881  1881 D BluetoothHeadset: Proxy object disconnected
08-31 18:49:26.520  1035  1035 D BluetoothHeadset: Proxy object disconnected
08-31 18:49:26.520  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 18:49:26.521  6969  6969 D A2dpService: Received stop request...Stopping profile...
08-31 18:49:26.521  6969  7490 D A2dpStateMachine: Exit Disconnected: -1
08-31 18:49:26.523  6969  6969 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-31 18:49:26.527  6969  6969 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-31 18:49:26.527  6969  6969 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 18:49:26.527  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:26.528  1881  1881 D BluetoothHeadset: Proxy object disconnected
08-31 18:49:26.529  1035  1035 D BluetoothA2dp: Proxy object disconnected
08-31 18:49:26.529  1035  1035 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 18:49:26.530  6969  6969 D HidService: Received stop request...Stopping profile...
08-31 18:49:26.530  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:26.532  6969  6969 D HealthService: Received stop request...Stopping profile...
08-31 18:49:26.532  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:26.534  6969  6969 D PanService: Received stop request...Stopping profile...
08-31 18:49:26.534  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:26.536  6969  6969 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 18:49:26.539  6969  6969 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 18:49:26.539  6969  6969 D BtGatt.GattService: stop()
08-31 18:49:26.539  6969  6969 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 18:49:26.541  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:26.544  6969  6969 D BluetoothMapService: Received stop request...Stopping profile...
08-31 18:49:26.544  6969  6969 D BluetoothMapService: stop()
08-31 18:49:26.545  6969  6969 D BluetoothMapEmailAppObserver: deinitObservers()
08-31 18:49:26.545  6969  6969 D BluetoothMapEmailAppObserver: removeReceiver()
08-31 18:49:26.546  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a595e83
08-31 18:49:26.548  6969  6969 D HeadsetStateMachine: Unbinding service...
,08-31 18:49:26.551  6969  6969 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 18:49:26.551  6969  6969 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 18:49:26.551  6969  6969 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 18:49:26.551  6969  6969 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 18:49:26.551  6969  6969 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 18:49:26.551  6969  6969 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 18:49:26.551  6969  6969 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-31 18:49:26.552  6969  6969 I BluetoothA2dpServiceJni: cleanupNative
08-31 18:49:26.552  6969  7491 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 18:49:26.553  6969  6969 I GKI_LINUX: GKI_exit_task 2 done
08-31 18:49:26.553  6969  6969 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 18:49:26.553  6969  6969 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 18:49:26.553  6969  6969 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 18:49:26.553  6969  6969 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 18:49:26.554  6969  6969 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 18:49:26.554  6969  6969 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 18:49:26.554  6969  6969 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 18:49:26.554  6969  6969 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 18:49:26.556  6969  6969 V BluetoothMapService: Handler(): got msg=4
08-31 18:49:26.556  6969  6969 D BluetoothMapService: MAP Service closeService in
08-31 18:49:26.556  6969  6969 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 18:49:26.556  6969  6969 V BluetoothMapService: MAP Service closeService out
08-31 18:49:26.557  6969  7432 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-31 18:49:26.557  6969  7432 D BluetoothAdapterProperties: Setting state to 10
08-31 18:49:26.557  6969  7432 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 18:49:26.559  6969  6969 D BluetoothMapService: cleanup()
08-31 18:49:26.559  6969  6969 D BluetoothMapService: MAP Service closeService in
08-31 18:49:26.559  6969  6969 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-31 18:49:26.559  6969  6969 V BluetoothMapService: MAP Service closeService out
08-31 18:49:26.560  1035  1097 D BluetoothManagerService: Message: 60
08-31 18:49:26.560  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-31 18:49:26.560  1035  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-31 18:49:26.564  6969  7432 I BluetoothAdapterState: Entering OffState
08-31 18:49:26.564  1881  1897 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:49:26.565  6853  6868 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 18:49:26.565  6853  6868 D BluetoothPan: onBluetoothStateChange on: false
08-31 18:49:26.566  6853  6868 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 18:49:26.569  6853  6868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:49:26.570  1035  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 18:49:26.571  6853  6868 D BluetoothMap: onBluetoothStateChange: up=false
08-31 18:49:26.571  6853  6868 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 18:49:26.572  1035  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 18:49:26.574  1881  2449 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:49:26.574  1881  1896 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 18:49:26.575  1035  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-31 18:49:26.576  1035  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-31 18:49:26.577  1035  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-31 18:49:26.577  1035  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-31 18:49:26.577  1035  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3495e546 mBinding = false
08-31 18:49:26.578  1035  1097 D BluetoothManagerService: Sending unbind request.
08-31 18:49:26.583  6969  7436 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 18:49:26.585  6969  6969 I GKI_LINUX: GKI_exit_task 1 done
08-31 18:49:26.585  6969  6969 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 18:49:26.586  6969  6969 I BluetoothServiceJni: cleanupNative: return from cleanup
08-31 18:49:26.586  6969  6969 I art     : --- WEIRD: removing null entry 248
08-31 18:49:26.586  6969  6969 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-31 18:49:26.586  6969  6969 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-31 18:49:26.587  6969  6969 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-31 18:49:26.589  1035  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-31 18:49:26.590  6969  6969 I art     : System.exit called, status: 0
08-31 18:49:26.591  6969  6969 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 18:49:26.609   313   313 V AudioFlinger: 6969 died, releasing its sessions
08-31 18:49:26.610   313   313 V AudioFlinger:  pid 1881 @ 0
08-31 18:49:26.610   313   313 V AudioFlinger:  pid 3452 @ 1
08-31 18:49:26.610   313   313 V AudioFlinger:  pid 3452 @ 2
,08-31 18:49:26.614  1976  1976 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-31 18:49:26.614  1976  2198 D LGBluetoothAPIService: Message: 101
,08-31 18:49:26.614  1976  2198 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-31 18:49:26.615  1976  2198 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-31 18:49:26.615  1976  2198 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-31 18:49:26.616  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-31 18:49:26.618  1035  2004 I ActivityManager: Process com.android.bluetooth (pid 6969) has died
08-31 18:49:26.618  1035  2004 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-31 18:49:26.618  1035  2004 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-31 18:49:26.637  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 18:49:26.637  1976  1976 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:26.637  1976  2198 D LGBluetoothAPIService: Message: 2
08-31 18:49:26.638  1976  2198 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-31 18:49:26.640  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:26.640  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:26.642  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-31 18:49:26.642  6853  6853 D LGBluetoothEventManager: [BTUI] clear device connection state
08-31 18:49:26.646  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-31 18:49:26.649  1605  1605 D BluetoothAdapter: 330926252: getState() :  mService = null. Returning STATE_OFF
08-31 18:49:26.649  1605  1605 D BluetoothAdapter: 330926252: getState() :  mService = null. Returning STATE_OFF
08-31 18:49:26.683  1035  1995 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7650 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-31 18:49:26.684  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-31 18:49:26.729  7650  7650 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 18:49:26.730  7650  7650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 18:49:26.730  7650  7650 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-31 18:49:26.731  7650  7650 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 18:49:26.747  7650  7650 D BluetoothAdapterApp: Loading JNI Library
,08-31 18:49:26.781  7650  7650 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2a90d90b Instance Count = 1
,08-31 18:49:26.787  7650  7650 D BluetoothAdapterApp: onCreate
08-31 18:49:26.811  7650  7650 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-31 18:49:26.811  7650  7650 D ProfileConfigQcom: Adding HeadsetService
08-31 18:49:26.812  7650  7650 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-31 18:49:26.812  7650  7650 D ProfileConfigQcom: Adding A2dpService
08-31 18:49:26.812  7650  7650 D ProfileConfigQcom: [BTUI] HidService is supported
08-31 18:49:26.812  7650  7650 D ProfileConfigQcom: Adding HidService
08-31 18:49:26.813  7650  7650 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-31 18:49:26.813  7650  7650 D ProfileConfigQcom: Adding HealthService
08-31 18:49:26.813  7650  7650 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-31 18:49:26.814  7650  7650 D ProfileConfigQcom: [BTUI] PanService is supported
08-31 18:49:26.814  7650  7650 D ProfileConfigQcom: Adding PanService
08-31 18:49:26.814  7650  7650 D ProfileConfigQcom: [BTUI] GattService is supported
08-31 18:49:26.814  7650  7650 D ProfileConfigQcom: Adding GattService
08-31 18:49:26.815  7650  7650 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-31 18:49:26.815  7650  7650 D ProfileConfigQcom: Adding BluetoothMapService
08-31 18:49:26.815  7650  7650 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-31 18:49:26.816  7650  7650 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 18:49:26.817  7650  7650 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:26.817  7650  7650 V BluetoothPbapReceiver: ***********state = 10
08-31 18:49:26.819  7650  7650 V LGMDMManagerInternal: Create singleton instance
08-31 18:49:26.884  2244  2244 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 18:49:26.910  6853  6853 D BluetoothPermissionRequest: onReceive
08-31 18:49:26.912  6853  6853 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-31 18:49:26.916  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-31 18:49:26.916  6853  6853 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter,
08-31 18:49:26.917  7650  7650 D LGBluetoothAPIServer: [BTUI] onCreate()
08-31 18:49:26.917  7650  7650 D LGBluetoothAPIServer: [BTUI] onBind()
08-31 18:49:26.919  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 18:49:26.920  1976  1976 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-31 18:49:26.920  1976  2198 D LGBluetoothAPIService: Message: 100
08-31 18:49:26.920  1976  2198 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-31 18:49:26.929  7650  7650 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-31 18:49:26.934  7650  7650 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:26.938  7650  7650 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 18:49:26.938  7650  7650 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 18:49:26.938  7650  7650 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 18:49:26.940  7650  7650 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:26.940  7650  7650 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-31 18:49:26.943  6925  6925 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-31 18:49:28.561  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 18:49:28.561  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:49:28.711  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-31 18:49:28.747  1035  1455 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 18:49:28.808  1035  1035 D administrator: Handling package changes for user 0
,08-31 18:49:28.822  1035  1092 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7686 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-31 18:49:28.828  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-31 18:49:28.830  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-31 18:49:28.833  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 18:49:28.859  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 18:49:28.888  7686  7686 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 18:49:28.934  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-31 18:49:28.934  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-31 18:49:28.969  7686  7686 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:28.969  7686  7686 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 18:49:28.973  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 18:49:28.978  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 18:49:28.985  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-31 18:49:28.986  2478  2478 V GmsNetworkLocationProvi: DISABLE
,08-31 18:49:29.008  1035  1091 D LocationProviderProxy: applying state to connected service
08-31 18:49:29.008  2478  2478 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-31 18:49:29.094  7686  7722 I Babel   : MmsConfig: mnc/mcc: 0/0
08-31 18:49:29.094  7686  7722 I Babel   : MmsConfig.loadMmsSettings
08-31 18:49:29.111  7686  7722 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 18:49:29.112  7686  7722 I Babel   : MmsConfig.loadFromDatabase
,08-31 18:49:29.138  7686  7686 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:29.141  7686  7722 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-31 18:49:29.141  7686  7722 I Babel   : MmsConfig.loadFromResources
08-31 18:49:29.143  7686  7722 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-31 18:49:29.143  7686  7722 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-31 18:49:29.149  7686  7721 W AudioCapabilities: Unsupported mime audio/evrc
08-31 18:49:29.150  7686  7721 W AudioCapabilities: Unsupported mime audio/qcelp
08-31 18:49:29.152  7686  7721 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 18:49:29.166  1846  7725 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-31 18:49:29.167  1846  7725 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-31 18:49:29.171  7031  7031 I AppUp4:CustModeStarterReceiver: onReceive
08-31 18:49:29.176  7031  7031 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3938f53d
08-31 18:49:29.176  7031  7031 D AppUp4:CustFacade: isCustomizationCompleted : false
08-31 18:49:29.176  7031  7031 D AppUp4:CustFacade: isPhone : true
08-31 18:49:29.176  7031  7031 D AppUp4:CustModeStarterReceiver: begin check event
08-31 18:49:29.176  7031  7031 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-31 18:49:29.181  1846  4818 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-31 18:49:29.182  7686  7721 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-31 18:49:29.198  7686  7721 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 18:49:29.203  7686  7721 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 18:49:29.219  7686  7721 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-31 18:49:29.221  7686  7721 W VideoCapabilities: Unsupported mime video/divx
08-31 18:49:29.224  1035  1993 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7727 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-31 18:49:29.226  7686  7721 W VideoCapabilities: Unsupported mime video/divx311
,08-31 18:49:29.228  1035  2091 I ActivityManager: Killing 6873:com.lge.sync/1000 (adj 15): empty #17
08-31 18:49:29.241  1035  1546 D WifiService: Client connection lost with reason: 4
,08-31 18:49:29.243  7686  7721 W VideoCapabilities: Unsupported mime video/divx4
,08-31 18:49:29.249  7686  7721 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-31 18:49:29.262  7686  7721 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 18:49:29.265  7686  7721 W AudioCapabilities: Unsupported mime audio/eac3
08-31 18:49:29.265  7686  7721 W AudioCapabilities: Unsupported mime audio/ac3
08-31 18:49:29.266  7686  7721 W AudioCapabilities: Unsupported mime audio/g726
08-31 18:49:29.267  7686  7721 W AudioCapabilities: Unsupported mime audio/wma-voice
08-31 18:49:29.267  7686  7721 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-31 18:49:29.268  7686  7721 W AudioCapabilities: Unsupported mime audio/adpcm
08-31 18:49:29.270  7686  7721 W VideoCapabilities: Unsupported mime video/theora
08-31 18:49:29.271  7686  7721 W VideoCapabilities: Unsupported mime video/mjpg
,08-31 18:49:29.383  1035  2068 W libprocessgroup: failed to open /acct/uid_1000/pid_6873/cgroup.procs: No such file or directory
,08-31 18:49:29.399  7727  7727 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 18:49:29.399  7727  7727 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 18:49:29.399  7727  7727 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 18:49:29.401  7727  7727 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-31 18:49:29.401  7727  7727 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 18:49:29.470  7727  7727 I SystemConfig: BUILD Country: EU
08-31 18:49:29.470  7727  7727 I SystemConfig: BUILD Operator: OPEN
,08-31 18:49:29.509  1035  1584 I ActivityManager: Killing 7077:com.lge.email/u0a23 (adj 15): empty #17
,08-31 18:49:29.589  1035  2068 W libprocessgroup: failed to open /acct/uid_10023/pid_7077/cgroup.procs: No such file or directory
,08-31 18:49:29.677  1035  1584 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7749 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-31 18:49:29.684  7727  7747 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
,08-31 18:49:29.685  7727  7747 I SystemConfig: existFile = false
08-31 18:49:29.685  7727  7747 I SystemConfig: canReadFile = false
08-31 18:49:29.685  7727  7747 I SystemConfig: systemFeature RCS result false
08-31 18:49:29.685  7727  7747 D SystemConfig: refreshRcsSupport() :false
,08-31 18:49:29.768  7749  7749 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 18:49:29.768  7749  7749 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 18:49:29.768  7749  7749 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-31 18:49:29.769  7749  7749 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 18:49:29.881  7749  7749 I AppConfig: Total System Memory = 2995761152
,08-31 18:49:29.892  7749  7749 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-31 18:49:29.970  1035  2004 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7771 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 18:49:29.973  1035  2004 I ActivityManager: Killing 6950:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-31 18:49:30.075  1035  2096 W libprocessgroup: failed to open /acct/uid_10026/pid_6950/cgroup.procs: No such file or directory
,08-31 18:49:30.298  7771  7771 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 18:49:30.424  7771  7771 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:30.424  7771  7771 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 18:49:30.476  7771  7771 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-31 18:49:30.496  7771  7771 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 18:49:30.499  7771  7771 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 18:49:30.529  7771  7771 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 18:49:30.529  7771  7771 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-31 18:49:30.548  1035  1051 I ActivityManager: Killing 6419:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-31 18:49:30.588  1035  1050 W libprocessgroup: failed to open /acct/uid_1000/pid_6419/cgroup.procs: No such file or directory
,08-31 18:49:30.590  4666  7811 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-31 18:49:30.592  2857  2873 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-31 18:49:30.594  2857  2873 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1e2f3051 on behalf of 7771
08-31 18:49:30.642  1035  1051 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7812 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-31 18:49:30.687  7771  7771 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-31 18:49:30.714  7771  7771 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-31 18:49:30.757  7812  7812 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-31 18:49:30.778  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-31 18:49:30.778  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-31 18:49:30.778  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-31 18:49:30.778  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-31 18:49:30.778  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-31 18:49:30.778  7812  7812 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-31 18:49:30.795  1035  1584 I ActivityManager: Killing 7115:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-31 18:49:30.803  7569  7620 D UEI.SmartControl: Internal timer expired: 1
,08-31 18:49:30.803  7569  7620 D UEI.SmartControl: unbind internal service
08-31 18:49:30.826  7569  7569 D UEI.SmartControl: Service.onUnbind: IControl
,08-31 18:49:30.827  1035  1051 W libprocessgroup: failed to open /acct/uid_10046/pid_7115/cgroup.procs: No such file or directory
08-31 18:49:30.828  7569  7569 D UEI.SmartControl: Service.onDestroy
08-31 18:49:30.828  7569  7569 D UEI.SmartControl: Lock is in USE false
08-31 18:49:30.828  7569  7569 D UEI.SmartControl: unbind internal service
08-31 18:49:30.828  7569  7569 D serial_port: close(fd = 25)
08-31 18:49:30.831  7569  7569 I UEI.SmartControl: Serial port is closed.
08-31 18:49:30.831  7569  7569 I UEI.SmartControl: Serial port is closed.
08-31 18:49:30.831  7569  7569 D UEI.SmartControl: Blaster closed
08-31 18:49:30.832  7569  7569 D UEI.SmartControl: Shut down QS...
08-31 18:49:30.832  7569  7569 D UEI.SmartControl: Stopping QS lib
08-31 18:49:30.832  7569  7569 D UEI.SmartControl: QS lib stop result = true
08-31 18:49:30.832  7569  7569 D UEI.SmartControl: Stopped QS lib
08-31 18:49:30.832  7569  7569 D UEI.SmartControl: Stopped file observer...
08-31 18:49:30.832  7569  7569 D UEI.SmartControl: QS shutdown complete
08-31 18:49:30.971  1035  1763 V SIM_STK : Menu title from STK is T-Mobile
,08-31 18:49:30.997  4666  7811 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 406 ms] updated apps [took 406 ms] 
,08-31 18:49:31.576  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 18:49:31.577  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13e61cc7 added. We now have 6 listener(s)
08-31 18:49:31.577  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 18:49:31.586  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:31.586  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ea912f4 added. We now have 7 listener(s)
08-31 18:49:31.586  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:31.587  6733  6803 I System.out: IsBluetoothEnabled
08-31 18:49:31.588  1035  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:31.588  1035  1782 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-31 18:49:31.588  1035  1097 D BluetoothManagerService: Message: 2
08-31 18:49:31.591  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:31.592  1035  2115 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:31.592  1035  2115 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-31 18:49:31.608  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-31 18:49:31.608  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-31 18:49:31.609  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 18:49:31.609  1035  1097 D BluetoothManagerService: Message: 1
08-31 18:49:31.609  1035  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-31 18:49:31.634  1035  1097 D BluetoothManagerService: Message: 20
08-31 18:49:31.634  1035  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@354afa87:true
,08-31 18:49:31.638  7650  7650 D BluetoothAdapterState: make
08-31 18:49:31.643  7650  7650 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-31 18:49:31.643  7650  7650 I bluedroid-qcom: init
08-31 18:49:31.644  7650  7857 I BluetoothAdapterState: Entering OffState
08-31 18:49:31.645  7650  7650 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 18:49:31.645  7650  7650 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 18:49:31.645  7650  7650 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 18:49:31.645  7650  7650 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 18:49:31.645  7650  7650 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-31 18:49:31.647  7650  7650 I bluedroid-qcom: get_profile_interface socket
08-31 18:49:31.647  7650  7650 I bluedroid-qcom: get_profile_interface map_client
,08-31 18:49:31.651  7650  7861 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-31 18:49:31.649  7860  7860 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:31.656  7650  7861 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-31 18:49:31.649  7860  7860 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:31.665  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-31 18:49:31.668  1035  1097 D BluetoothManagerService: Message: 40
08-31 18:49:31.668  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-31 18:49:31.671  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-31 18:49:31.671  7860  7860 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-31 18:49:31.671  7860  7860 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-31 18:49:31.672  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 18:49:31.672  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 18:49:31.673  7650  7666 I bluedroid-qcom: config_hci_snoop_log
08-31 18:49:31.674  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-31 18:49:31.675  1035  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-31 18:49:31.675  1035  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 18:49:31.680  7860  7860 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-31 18:49:31.681  7860  7860 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-31 18:49:31.687  7650  7857 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-31 18:49:31.688  7650  7861 D BluetoothAdapterProperties: Name is: G3
08-31 18:49:31.688  7650  7857 D BluetoothAdapterProperties: Setting state to 11
08-31 18:49:31.689  7650  7857 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 18:49:31.689  1035  1097 D BluetoothManagerService: Message: 60
08-31 18:49:31.689  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-31 18:49:31.689  1035  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-31 18:49:31.691  7650  7857 I LGBluetoothServiceJni: classInitNative: succeeds
08-31 18:49:31.696  1976  1976 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 18:49:31.698  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 18:49:31.702  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:31.705  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-31 18:49:31.710  7650  7650 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 18:49:31.710  7650  7650 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:31.710  7650  7650 V BluetoothPbapReceiver: ***********state = 11
,08-31 18:49:31.716  2244  2244 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 18:49:31.740  6853  6853 D BluetoothPermissionRequest: onReceive
,08-31 18:49:31.747  7650  7857 D BluetoothBondStateMachine: make
08-31 18:49:31.748  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-31 18:49:31.751  7650  7857 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:31.752  7650  7857 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-31 18:49:31.752  7650  7857 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:31.752  7650  7857 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-31 18:49:31.753  7650  7857 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-31 18:49:31.754  7650  7876 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 18:49:31.757  7650  7650 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:31.758  7650  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:31.759  7650  7650 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 18:49:31.759  7650  7650 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 18:49:31.759  7650  7650 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 18:49:31.759  7650  7650 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:31.759  7650  7650 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-31 18:49:31.766  7650  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:31.768  7650  7650 D HeadsetService: Received start request. Starting profile...
08-31 18:49:31.768  7650  7650 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 18:49:31.768  7650  7650 D LGBluetoothHfpAdapter: Version 1.6
,08-31 18:49:31.771  7650  7650 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 18:49:31.772  7650  7857 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 18:49:31.773  7650  7650 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-31 18:49:31.773  7650  7650 D HeadsetStateMachine: make
08-31 18:49:31.777  7650  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:31.782  7650  7857 E BluetoothAdapterService: File transfer profiles supported!!
,08-31 18:49:31.789  7650  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:31.793  7650  7857 E BluetoothAdapterService: File transfer profiles supported!!
08-31 18:49:31.801  7650  7650 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:31.801  7650  7650 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-31 18:49:31.805  7650  7650 D HeadsetStateMachine: max_hf_connections = 1
08-31 18:49:31.805  7650  7650 I bluedroid-qcom: get_profile_interface handsfree
08-31 18:49:31.807  7650  7650 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-31 18:49:31.807   313  7458 V AudioPolicyService: registerClient() client 0xb558ad20, uid 1002
08-31 18:49:31.808   313   313 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-31 18:49:31.808   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 18:49:31.808   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 18:49:31.808  7650  7650 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-31 18:49:31.808   313  1383 V AudioFlinger: registerClient() client 0xb55819e8, pid 7650
08-31 18:49:31.808   313  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:31.808   313  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:31.809   313  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:31.809   313  1378 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:31.809  1035  1740 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:31.809  1035  1740 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:31.809  7650  7666 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:31.809  1035  1740 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:31.809  1035  1740 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:31.809  7650  7857 V LGMDMManager: Create singleton instance
08-31 18:49:31.810  3452  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:31.810  3452  3468 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:31.810  1605  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:31.810  1605  1624 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:31.810  3452  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:31.810  3452  3468 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:31.810  1605  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:31.810  1605  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:31.810  1881  2449 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-31 18:49:31.810  1881  2449 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-31 18:49:31.810  1881  2449 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:31.810  1881  2449 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-31 18:49:31.810  7650  7666 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-31 18:49:31.810  7650  7666 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-31 18:49:31.810  7650  7666 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-31 18:49:31.810  7650  7650 V ToneGenerator: Create Track: 0xb4928a80
08-31 18:49:31.810  7650  7650 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-31 18:49:31.810  7650  7650 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-31 18:49:31.810   313  7458 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 18:49:31.810   313  7458 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-31 18:49:31.810   313  7458 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 18:49:31.810   313  7458 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 18:4,9:31.811   313   313 I AudioFlinger: isAudioPlaybackHookOn() false
08-31 18:49:31.811   313  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-31 18:49:31.811   313  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-31 18:49:31.811   313  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-31 18:49:31.811   313  1383 V AudioPolicyManagerEx: getOutput() returns output 2
08-31 18:49:31.811  7650  7857 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 18:49:31.811  7650  7650 V AudioSystem: getLatency() output 2, latency 50
08-31 18:49:31.811  7650  7650 V AudioSystem: getFrameCount() output 2, frameCount 960
08-31 18:49:31.811  7650  7650 V AudioTrack: createTrack_l() output 2 afLatency 50
08-31 18:49:31.812   313  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 18:49:31.812   313  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 18:49:31.812   313  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-31 18:49:31.812   313  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-31 18:49:31.812   313  1384 V AudioFlinger: createTrack() lSessionId: 23
08-31 18:49:31.813  7650  7650 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-31 18:49:31.813   313  7458 V AudioFlinger: acquiring 23 from 7650, for 7650
08-31 18:49:31.813   313  7458 V AudioFlinger:  added new entry for 23
08-31 18:49:31.813  7650  7650 V ToneGenerator: ToneGenerator INIT OK, time: 211640
08-31 18:49:31.813  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:31.814  7650  7879 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-31 18:49:31.814  7650  7879 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-31 18:49:31.814  7650  7879 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-31 18:49:31.815  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:31.815  7650  7879 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-31 18:49:31.815   313   313 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7650
08-31 18:49:31.815   313   313 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-31 18:49:31.815   313   313 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-31 18:49:31.815   313   313 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-31 18:49:31.815   313   313 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-31 18:49:31.815   313   313 V voice   : voice_set_parameters: exit with code(0)
08-31 18:49:31.815   313   313 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-31 18:49:31.815   313   313 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
,08-31 18:49:31.816   313   313 V msm8974_platform: platform_set_parameters: exit with code(0)
08-31 18:49:31.816   313   313 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-31 18:49:31.816   313   313 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-31 18:49:31.816   313   313 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-31 18:49:31.816  7650  7879 V ToneGenerator: ToneGenerator destructor
08-31 18:49:31.816  7650  7879 V ToneGenerator: stopTone
08-31 18:49:31.816  7650  7879 V ToneGenerator: Delete Track: 0xb4928a80
08-31 18:49:31.816   313  1383 V AudioPolicyService: AudioCommandThread() adding release output 2
08-31 18:49:31.816   313  1383 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-31 18:49:31.816   313  1259 V AudioPolicyService: AudioCommandThread() waking up
,08-31 18:49:31.816   313  1259 V AudioPolicyService: AudioCommandThread() processing release output 2
08-31 18:49:31.816   313  1259 V AudioPolicyManager: releaseOutput() 2
08-31 18:49:31.816   313  1259 V AudioPolicyService: AudioCommandThread() going to sleep
08-31 18:49:31.816   313  1383 V AudioFlinger: PlaybackThread::Track destructor
08-31 18:49:31.816   313  1383 V AudioFlinger: removeClient_l() pid 7650, calling pid 313
08-31 18:49:31.817  7650  7879 V AudioTrack: ~AudioTrack, releasing session id from 7650 on behalf of 7650
08-31 18:49:31.817   313   313 V AudioFlinger: releasing 23 from 7650 for 7650
08-31 18:49:31.817   313   313 V AudioFlinger:  decremented refcount to 0
08-31 18:49:31.817   313   313 V AudioFlinger: purging stale effects
,08-31 18:49:31.818  7650  7650 D A2dpService: Received start request. Starting profile...
,08-31 18:49:31.818  7650  7650 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 18:49:31.819  1035  1996 W Process : Unable to open /proc/7880/status
08-31 18:49:31.819  7650  7650 V Avrcp   : make
08-31 18:49:31.820  7650  7650 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-31 18:49:31.820  7650  7650 I bluedroid-qcom: get_profile_interface avrcp
08-31 18:49:31.829  7650  7650 V AudioManager: registerRemoteController: size of Media player list: 0
,08-31 18:49:31.831  7650  7650 E AudioManager: No RCC entry present to update
,08-31 18:49:31.831  7650  7650 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 18:49:31.839  7650  7650 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-31 18:49:31.841  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-31 18:49:31.841  7650  7650 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-31 18:49:31.845  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-31 18:49:31.954  1035  1993 V SIM_STK : Menu title from STK is T-Mobile
,08-31 18:49:31.954  1035  1993 V SIM_STK : Menu title from STK is T-Mobile
,08-31 18:49:32.024  1035  1996 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-31 18:49:32.032  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 18:49:32.036  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 18:49:32.037  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 18:49:32.038  7650  7650 I BluetoothA2dpServiceJni: classInitNative
08-31 18:49:32.038  7650  7650 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 18:49:32.038  7650  7650 D A2dpStateMachine: make
08-31 18:49:32.041  7650  7650 I bluedroid-qcom: get_profile_interface a2dp
,08-31 18:49:32.041  7650  7886 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-31 18:49:32.045  7650  7650 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-31 18:49:32.046  7650  7650 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-31 18:49:32.046  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:32.047  7650  7885 D A2dpStateMachine: Enter Disconnected: -2
08-31 18:49:32.047  7650  7650 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 18:49:32.049  7650  7650 D HidService: Received start request. Starting profile...
08-31 18:49:32.049  7650  7650 I bluedroid-qcom: get_profile_interface hidhost
08-31 18:49:32.049  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:32.050  7650  7650 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 18:49:32.051  7650  7650 D HealthService: Received start request. Starting profile...
08-31 18:49:32.054  7650  7650 I bluedroid-qcom: get_profile_interface health
08-31 18:49:32.055  7650  7650 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-31 18:49:32.055  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:32.056  7650  7650 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 18:49:32.058  7650  7650 D PanService: Received start request. Starting profile...
08-31 18:49:32.058  7650  7650 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 18:49:32.058  7650  7650 I bluedroid-qcom: get_profile_interface pan
08-31 18:49:32.074  7650  7650 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-31 18:49:32.074  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:32.078  7650  7650 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-31 18:49:32.087  7650  7650 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 18:49:32.087  7650  7650 D BtGatt.GattService: Received start request. Starting profile...
08-31 18:49:32.087  7650  7650 D BtGatt.GattService: start()
08-31 18:49:32.087  7650  7650 I bluedroid-qcom: get_profile_interface gatt
08-31 18:49:32.088  7650  7650 D BtGatt.AdvertiseManager: advertise manager created
08-31 18:49:32.096  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:32.097  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:32.097  7650  7650 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-31 18:49:32.098  7650  7650 V BluetoothMapService: BluetoothMapBinder()
,08-31 18:49:32.099  7650  7650 D BluetoothMapService: Received start request. Starting profile...
08-31 18:49:32.099  7650  7650 D BluetoothMapService: start()
08-31 18:49:32.103  7650  7650 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-31 18:49:32.103  7650  7650 D BluetoothMapEmailAppObserver: createReceiver()
08-31 18:49:32.104  7650  7650 D BluetoothMapEmailAppObserver: initObservers()
08-31 18:49:32.105  7650  7650 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-31 18:49:32.114  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:32.115  7650  7650 D HeadsetStateMachine: Proxy object connected
08-31 18:49:32.116  7650  7650 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-31 18:49:32.116  7650  7650 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-31 18:49:32.119  7650  7879 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-31 18:49:32.120  7650  7879 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 18:49:32.121  7650  7879 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-31 18:49:32.124  7650  7650 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 18:49:32.128  7650  7650 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 18:49:32.143  7650  7650 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-31 18:49:32.156  7650  7650 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 18:49:32.157  7650  7650 V PanService: [BTUI] SIM Extra State :ABSENT
,08-31 18:49:32.164  7650  7650 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-31 18:49:32.168  7650  7650 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-31 18:49:32.168  7650  7650 V BluetoothMapService: Handler(): got msg=1
08-31 18:49:32.170  7650  7857 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-31 18:49:32.171  7650  7857 I bluedroid-qcom: enable
08-31 18:49:32.171  7650  7857 I bt_hci_bdroid: init
08-31 18:49:32.174  7650  7857 I bt_vendor: bt-vendor : init
08-31 18:49:32.174  7650  7857 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 18:49:32.174  7650  7857 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 18:49:32.174  7650  7857 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-31 18:49:32.174  7650  7857 D bt_userial_mct: userial_init
08-31 18:49:32.182  7650  7857 D bt_hci_bdroid: set_power 1
,08-31 18:49:32.182  7650  7857 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-31 18:49:32.182  7650  7857 I bt_vendor: Starting hciattach daemon
08-31 18:49:32.183  7650  7857 I bt_vendor: try to set true
08-31 18:49:32.186  7650  7899 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-31 18:49:32.186  7650  7899 I bt-btu  : btu_task pending for preload complete event
08-31 18:49:32.179  7902  7902 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:32.179  7902  7902 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 18:49:32.214  7903  7903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 18:49:32.300  7918  7918 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-31 18:49:32.312  7920  7920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-31 18:49:32.350  7923  7923 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 18:49:32.365  7924  7924 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 18:49:32.391  7925  7925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 18:49:32.415  7926  7926 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-31 18:49:32.439  7928  7928 I libmdmdetect: ESOC framework not supported
08-31 18:49:32.440  7928  7928 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-31 18:49:32.449  7928  7928 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-31 18:49:32.449  7928  7928 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-31 18:49:32.449  7928  7928 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-31 18:49:32.450  7928  7928 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-31 18:49:32.450  7928  7928 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-31 18:49:32.450  7928  7928 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-31 18:49:32.450  7928  7928 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-31 18:49:32.488  7928  7930 E QC-QMI  : qmi_client [7928] 15: failed to locate client data
08-31 18:49:32.490   474   474 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-31 18:49:32.490   474   474 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-31 18:49:32.571  7934  7934 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-31 18:49:32.586  7938  7938 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 18:49:32.637  7650  7857 I bt_vendor: bluetooth satus is on
08-31 18:49:32.637  7650  7857 D bt_hci_bdroid: preload
08-31 18:49:32.638  7650  7901 D bt_userial_mct: userial_open(port:0)
08-31 18:49:32.638  7650  7901 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 18:49:32.644  7650  7901 I bt_vendor: Done intiailizing UART
08-31 18:49:32.648  7650  7901 I bt_vendor: Done intiailizing UART
08-31 18:49:32.648  7650  7901 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 18:49:32.649  7650  7901 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 18:49:32.649  7650  7899 I bt-btu  : btu_task received preload complete event
08-31 18:49:32.651  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-31 18:49:32.651  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-31 18:49:32.655  7650  7940 D bt_userial_mct: Entering userial_read_thread()
,08-31 18:49:32.660  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-31 18:49:32.677  7650  7899 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 18:49:32.677  7650  7899 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 18:49:32.678  7650  7899 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 18:49:32.749  7650  7899 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-31 18:49:32.749  7650  7899 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01a8061 
08-31 18:49:32.749  7650  7899 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01a8061 
,08-31 18:49:32.767  7650  7861 E bt-btif : Calling BTA_HhEnable
08-31 18:49:32.767  7650  7861 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-31 18:49:32.768  7650  7861 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-31 18:49:32.772  1035  1035 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-31 18:49:32.772  7650  7861 D BluetoothAdapterProperties: Name is: G3
08-31 18:49:32.774  7650  7861 D BluetoothAdapterProperties: Scan Mode:20
08-31 18:49:32.774  7650  7861 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 18:49:32.774  7650  7861 D bt_hci_bdroid: postload
08-31 18:49:32.776  7650  7861 D bte_conf: Device ID record 1 : primary
08-31 18:49:32.776  7650  7861 D bte_conf:   vendorId            = 00c4
08-31 18:49:32.776  7650  7861 D bte_conf:   vendorIdSource      = 0001
08-31 18:49:32.776  7650  7861 D bte_conf:   product             = 13a1
08-31 18:49:32.776  7650  7861 D bte_conf:   version             = 1000
08-31 18:49:32.776  7650  7861 D bte_conf:   clientExecutableURL = 
08-31 18:49:32.776  7650  7861 D bte_conf:   serviceDescription  = 
08-31 18:49:32.776  7650  7861 D bte_conf:   documentationURL    = 
08-31 18:49:32.777  7650  7901 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 18:49:32.777  7650  7861 D bte_conf: bte_load_did_conf no section named DID2.
08-31 18:49:32.780  7650  7901 D bt_hci_bdroid: Used up Tx Cmd credits
08-31 18:49:32.784  7650  7857 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 18:49:32.785  7650  7857 D BluetoothAdapterProperties: ScanMode =  20
,08-31 18:49:32.788  7650  7857 D BluetoothAdapterProperties: State =  11
08-31 18:49:32.788  7650  7857 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-31 18:49:32.779  7945  7945 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:32.779  7945  7945 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:32.790  7650  7857 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-31 18:49:32.790  7650  7857 D BluetoothAdapterProperties: Setting state to 12
08-31 18:49:32.791  7650  7857 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 18:49:32.791  7650  7861 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 18:49:32.798  1035  1097 D BluetoothManagerService: Message: 60
08-31 18:49:32.798  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-31 18:49:32.798  1035  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-31 18:49:32.801  7650  7857 I BluetoothAdapterState: Entering On State
08-31 18:49:32.808  7650  7940 E bt_mct  : hci lib postload completed
08-31 18:49:32.814  1881  1897 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:49:32.820  7650  7857 D LGBluetoothServiceAdapter: [BTUI] OnState
08-31 18:49:32.820  7650  7857 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-31 18:49:32.820  7650  7857 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-31 18:49:32.824  7650  7857 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-31 18:49:32.838  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:32.838  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:32.838  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:32.838  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:32.838  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:32.838  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:32.838  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:32.838  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:49:32.844  7650  7861 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 18:49:32.845  7650  7861 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-31 18:49:32.848  1035  1035 D BluetoothManagerService: Stored Bluetooth name: G3
08-31 18:49:32.849  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:32.852  7650  7857 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-31 18:49:32.863  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-31 18:49:32.863  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-31 18:49:32.863  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-31 18:49:32.863  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-31 18:49:32.863  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-31 18:49:32.863  7650  7899 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-31 18:49:32.864  7650  7861 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 18:49:32.870  1881  1881 D BluetoothHeadset: Proxy object connected
,08-31 18:49:32.893  6853  6868 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 18:49:32.908  7650  7899 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:32.909  7650  7899 W bt-smp  : Plain text(LSB ~ MSB) = 4d 40 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:32.909  7650  7899 W bt-smp  : Encrypted text(LSB ~ MSB) = fe 50 e3 05 00 ad 6a fe 1d 10 43 62 ab f3 97 65 
08-31 18:49:32.909  7650  7899 W bt-btm  : Stopping oneshot timer
,08-31 18:49:32.913  7950  7950 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-31 18:49:32.925  6853  6869 D BluetoothPan: onBluetoothStateChange on: true
08-31 18:49:32.925  6853  6869 D BluetoothPan: onBluetoothStateChange call bindService
,08-31 18:49:32.926  7650  7899 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:32.926  7650  7899 W bt-smp  : Plain text(LSB ~ MSB) = b1 31 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:32.926  7650  7899 W bt-smp  : Encrypted text(LSB ~ MSB) = 79 b1 c8 e6 f9 69 3b a1 d2 5c 00 07 9b 9a 69 14 
08-31 18:49:32.926  7650  7899 W bt-btm  : Stopping oneshot timer
08-31 18:49:32.927  6853  6853 D BluetoothA2dp: Proxy object connected
08-31 18:49:32.927  6853  6853 D A2dpProfile: Bluetooth service connected
08-31 18:49:32.931  6853  6868 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 18:49:32.932  6853  6853 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 18:49:32.932  6853  6853 D PanProfile: Bluetooth service connected
08-31 18:49:32.937  6853  6853 D BluetoothInputDevice: Proxy object connected
08-31 18:49:32.937  6853  6853 D HidProfile: Bluetooth service connected
08-31 18:49:32.937  6853  6869 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:49:32.939  7650  7899 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:32.939  7650  7899 W bt-smp  : Plain text(LSB ~ MSB) = 33 35 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:32.939  7650  7899 W bt-smp  : Encrypted text(LSB ~ MSB) = 5f 39 d0 cd 5d f1 51 8b 82 02 fe f2 bc 45 49 ee 
08-31 18:49:32.939  7650  7899 W bt-btm  : Stopping oneshot timer
08-31 18:49:32.943  6853  6853 D BluetoothHeadset: Proxy object connected
08-31 18:49:32.943  6853  6853 D HeadsetProfile: Bluetooth service connected
08-31 18:49:32.943  1035  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 18:49:32.944  1035  1035 D BluetoothA2dp: Proxy object connected
08-31 18:49:32.944  6853  7303 D BluetoothMap: onBluetoothStateChange: up=true
08-31 18:49:32.947  6853  6868 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 18:49:32.947  6853  6853 D BluetoothMap: Proxy object connected
08-31 18:49:32.947  6853  6853 D MapProfile: Bluetooth service connected
08-31 18:49:32.947  6853  6853 D BluetoothMap: getConnectedDevices()
08-31 18:49:32.949  7650  7666 V BluetoothMapService: getConnectedDevices()
08-31 18:49:32.949  1035  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:49:32.950  1881  1896 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 18:49:32.950  7650  7899 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-31 18:49:32.951  7650  7899 W bt-smp  : Plain text(LSB ~ MSB) = 95 fa 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:32.951  7650  7899 W bt-smp  : Encrypted text(LSB ~ MSB) = af 41 f3 1b db 47 2d d0 25 fc 16 ed b2 da 3a 4a 
08-31 18:49:32.951  7650  7899 W bt-btm  : Stopping oneshot timer
08-31 18:49:32.951  1035  1035 D BluetoothHeadset: Proxy object connected
08-31 18:49:32.955  1881  1881 D BluetoothHeadset: Proxy object connected
08-31 18:49:32.955  1881  1897 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 18:49:32.957  1881  1881 D BluetoothHeadset: Proxy object connected
08-31 18:49:32.959  1035  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-31 18:49:32.959  1035  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-31 18:49:32.959  1035  1035 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-31 18:49:32.960  7650  7899 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-31 18:49:32.960  7650  7899 W bt-smp  : Plain text(LSB ~ MSB) = 0a 94 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-31 18:49:32.960  7650  7899 W bt-smp  : Encrypted text(LSB ~ MSB) = be 5d 65 9f 8d 97 b0 3c 5e ab e6 73 68 20 f6 e1 
08-31 18:49:32.961  7650  7899 W bt-btm  : Stopping oneshot timer
08-31 18:49:32.963  1976  1976 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:32.964  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-31 18:49:32.965  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:32.965  1976  2198 D LGBluetoothAPIService: Message: 1
08-31 18:49:32.965  1976  2198 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-31 18:49:32.966  1976  2198 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-31 18:49:32.966  1976  2198 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-31 18:49:32.968  1035  1097 D BluetoothManagerService: Message: 40
08-31 18:49:32.968  1035  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-31 18:49:32.974  7650  7650 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-31 18:49:32.975  7650  7650 D BluetoothMapService: STATE_ON
,08-31 18:49:32.979  6853  6853 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-31 18:49:32.981  6853  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-31 18:49:32.991  6853  6853 D DockEventReceiver: finishStartingService: stopping service
,08-31 18:49:32.993  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:32.993  7650  7650 V BluetoothPbapService: Pbap Service onCreate
08-31 18:49:32.993  7650  7650 V BluetoothPbapService: Starting PBAP service
08-31 18:49:32.995  7650  7650 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-31 18:49:32.996  7650  7650 V BluetoothPbapService: Pbap Service onBind
08-31 18:49:32.997  7650  7650 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:32.997  6853  6853 D BluetoothPbap: Proxy object connected
08-31 18:49:32.997  6853  6853 D PbapServerProfile: Bluetooth service connected
08-31 18:49:32.997  7650  7650 V BluetoothPbapService: state: 12
08-31 18:49:32.997  7650  7650 V BluetoothMapService: Handler(): got msg=1
08-31 18:49:32.998  7650  7650 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-31 18:49:32.998  7650  7650 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-31 18:49:32.998  7650  7650 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:32.998  7650  7650 V BluetoothPbapReceiver: ***********state = 12
08-31 18:49:32.999  7650  7970 D BluetoothMapMasInstance: MAS initSocket()
08-31 18:49:33.000  7650  7650 V BluetoothPbapService: Handler(): got msg=1
08-31 18:49:33.001  2244  2244 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 18:49:33.002  7650  7970 D BluetoothMapMasInstance:   masId = 00
08-31 18:49:33.002  7650  7970 D BluetoothMapMasInstance:   msgTypes = 0e
08-31 18:49:33.002  7650  7970 D BluetoothMapMasInstance:   masName = SMS/MMS
08-31 18:49:33.002  7650  7970 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-31 18:49:33.002  2244  2244 D c       : Getting all permits...
08-31 18:49:33.002  2244  2244 D a       : Opening database...
08-31 18:49:33.002  7650  7650 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-31 18:49:33.003  1035  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 18:49:33.005  7650  7970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:33.006  7650  7971 V BluetoothPbapService: Pbap Service initSocket
08-31 18:49:33.006  2244  2244 D a       : Opening database auth.proximity.permit_store...
08-31 18:49:33.006  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:33.007  2244  2244 D a       : Closing database...
08-31 18:49:33.008  7650  7970 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-31 18:49:33.008  7650  7970 V BluetoothMapMasInstance: Succeed to create listening socket 
08-31 18:49:33.008  7650  7970 D BluetoothMapMasInstance: Accepting socket connection...
08-31 18:49:33.011  7650  7861 D BluetoothAdapterProperties: Scan Mode:21
08-31 18:49:33.011  7650  7861 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-31 18:49:33.012  7650  7971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:33.014  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:33.015  7650  7971 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-31 18:49:33.016  7650  7971 V BluetoothPbapService: Succeed to create listening socket 
08-31 18:49:33.016  7650  7971 V BluetoothPbapService: Accepting socket connection...
,08-31 18:49:33.023  6853  6853 D BluetoothPermissionRequest: onReceive
08-31 18:49:33.025  6853  6853 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-31 18:49:33.027  6853  6853 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-31 18:49:33.030  7650  7650 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-31 18:49:33.032  7650  7650 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-31 18:49:33.038  7650  7650 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-31 18:49:33.059  7650  7650 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-31 18:49:33.059  7650  7650 V BtOppService: onCreate
,08-31 18:49:33.064  7650  7650 V BluetoothOppNotification: send message
08-31 18:49:33.070  7650  7650 V BtOppService: Starting RfcommListener
08-31 18:49:33.081  7650  7650 D BluetoothOppPreference: Dumping Names:  
08-31 18:49:33.081  7650  7650 D BluetoothOppPreference: {}
08-31 18:49:33.081  7650  7650 D BluetoothOppPreference: Dumping Channels:  
08-31 18:49:33.081  7650  7650 D BluetoothOppPreference: {}
,08-31 18:49:33.082  7650  7650 V BtOppService: onStartCommand
08-31 18:49:33.086  7650  7978 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 18:49:33.090  7650  7650 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:33.090  7650  7650 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-31 18:49:33.095  7650  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 18:49:33.097  7650  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15879cbc on behalf of 
,08-31 18:49:33.097  7650  7975 V BtOppService: Deleted complete outbound shares, number =  0
08-31 18:49:33.100  7650  7650 V BluetoothOppNotification: new notify threadi!
08-31 18:49:33.100  7650  7975 V BtOppService: Deleted complete inbound failed shares, number = 0
08-31 18:49:33.101  7650  7975 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-31 18:49:33.102  7650  7650 V BluetoothOppNotification: send delay message
08-31 18:49:33.102  7650  7978 V BluetoothOppNotification: update too frequent, put in queue
08-31 18:49:33.103  7650  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31e73445 on behalf of 
08-31 18:49:33.104  7650  7650 V BtOppService: start RfcommListener
08-31 18:49:33.107  7650  7978 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 18:49:33.107  7650  7978 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 18:49:33.109  7650  7978 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23bc779a on behalf of 
,08-31 18:49:33.109  7650  7650 V BtOppService: RfcommListener started
08-31 18:49:33.111  7650  7980 V BtOppRfcommListener: Starting RFCOMM listener....
08-31 18:49:33.111  1035  2115 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:33.112  7650  7980 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:33.113  7650  7979 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 18:49:33.113  7650  7980 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-31 18:49:33.113  7650  7980 V BtOppRfcommListener: Started RFCOMM listener....
08-31 18:49:33.113  7650  7980 I BtOppRfcommListener: Accept thread started.
08-31 18:49:33.114  7650  7980 V BtOppRfcommListener: Accepting connection...
08-31 18:49:33.117  7650  7978 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 18:49:33.126  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
,08-31 18:49:33.126  7650  7650 V BluetoothFtpService: Ftp Service onCreate
08-31 18:49:33.126  7650  7650 I BluetoothFtpService: Ftp Service onCreate
08-31 18:49:33.126  7650  7650 V BluetoothFtpService: Ftp Service onStartCommand
08-31 18:49:33.126  7650  7650 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:33.127  7650  7650 V BluetoothFtpService: Starting Listening on sockets
08-31 18:49:33.127  7650  7650 V BtOppService: ContentObserver received notification
08-31 18:49:33.127  7650  7650 V BtOppService: ContentObserver received notification
08-31 18:49:33.127  7650  7650 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-31 18:49:33.127  7650  7650 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-31 18:49:33.127  7650  7650 V BluetoothSapReceiver: SapReceiver onReceive 
08-31 18:49:33.128  7650  7650 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:33.128  7650  7650 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-31 18:49:33.128  7650  7650 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-31 18:49:33.128  7650  7981 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-31 18:49:33.128  7650  7981 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-31 18:49:33.247  1035  1763 I art     : Explicit concurrent mark sweep GC freed 27484(1350KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.300ms total 128.368ms
,08-31 18:49:33.248  7650  7979 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3f8fc8a8 on behalf of 
08-31 18:49:33.248  7650  7979 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 18:49:33.250  7650  7979 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-31 18:49:33.250  7650  7981 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@394bcfc1 on behalf of 
08-31 18:49:33.251  7650  7979 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2eda7366 on behalf of 
08-31 18:49:33.252  7650  7981 V BluetoothOppNotification: update too frequent, put in queue
08-31 18:49:33.253  7650  7650 V BluetoothFtpService: Handler(): got msg=1
08-31 18:49:33.254  7650  7650 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-31 18:49:33.255  7650  7650 V BluetoothFtpService: Ftp Service initSocket
08-31 18:49:33.255  7650  7981 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-31 18:49:33.257  7650  7979 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 18:49:33.264  7650  7979 V BluetoothOppNotification: outbound notification was removed.
08-31 18:49:33.264  7650  7979 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 18:49:33.266  7650  7979 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@291066a7 on behalf of 
,08-31 18:49:33.270  7650  7979 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 18:49:33.272  1035  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:33.273  7650  7979 V BluetoothOppNotification: inbound notification was removed.
08-31 18:49:33.274  7650  7979 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 18:49:33.275  7650  7650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:33.276  7650  7979 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@76cc754 on behalf of 
08-31 18:49:33.276  7650  7650 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-31 18:49:33.276  7650  7650 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-31 18:49:33.281  7650  7982 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-31 18:49:33.314  7650  7650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f2b5800
08-31 18:49:33.314  7650  7650 V BluetoothSapService: Sap Service onCreate
,08-31 18:49:33.316  7650  7650 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-31 18:49:33.316  7650  7650 V BluetoothSapService: state: 12
08-31 18:49:33.316  7650  7650 V BluetoothSapService: Starting SAP server process
08-31 18:49:33.318  7650  7650 V BluetoothSapService: SAP Service startRfcommListenerThread
08-31 18:49:33.309  7983  7983 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 18:49:33.309  7983  7983 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:33.320  7650  7984 V BluetoothSapService: Sap Service initRfcommSocket
08-31 18:49:33.320  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:33.321  7650  7984 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 18:49:33.322  7650  7984 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-31 18:49:33.322  7650  7984 V BluetoothSapService: Succeed to create listening socket 
08-31 18:49:33.322  7650  7984 V BluetoothSapService: Accepting socket connection...
08-31 18:49:33.346  7983  7983 V BT_SAP  : Event pipe created
08-31 18:49:33.346  7983  7983 V BT_SAP  : create_server_socket qcom.sap.server
08-31 18:49:33.346  7983  7983 V BT_SAP  : created socket fd 6
,08-31 18:49:33.644  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:33.644  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:33.644  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:33.644  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 18:49:33.644  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:33.644  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:33.644  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:33.644  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:49:33.649  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:33.651  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:33.651  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e7b9a1d added. We now have 8 listener(s)
08-31 18:49:33.651  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:33.654  1035  1051 D WifiServiceImplEx: setWifiEnabled: false pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 18:49:33.655  1035  1051 D WifiService: setWifiEnabled: false pid=6733, uid=10118
08-31 18:49:33.655  1035  1051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 18:49:33.659  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 18:49:33.664  1035  1763 D WifiServiceImplEx: setWifiEnabled: true pid=6733, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-31 18:49:33.665  1035  1763 D WifiService: setWifiEnabled: true pid=6733, uid=10118
08-31 18:49:33.665  1035  1763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 18:49:33.682  1035  1035 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-31 18:49:33.683  1035  1035 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-31 18:49:33.683  1035  1035 D Ulp_jni : JNI:system_update. Event-4
08-31 18:49:33.684  1035  1541 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-31 18:49:33.684  1035  1541 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-31 18:49:33.687  1035  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-31 18:49:33.687  1035  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 18:49:33.687  1035  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1035] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-31 18:49:33.687  1035  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-31 18:49:33.687  1035  1541 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-31 18:49:33.687  1035  1541 E WifiHW  : unknown target_country: EU , set to default
08-31 18:49:33.687  1035  1541 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-31 18:49:33.687  1035  1541 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
,08-31 18:49:33.687  1035  1541 I WifiUtil: gEnableBmps=1
,08-31 18:49:34.105  7650  7650 V BluetoothOppNotification: new notify threadi!,
08-31 18:49:34.106  7650  7650 V BluetoothOppNotification: send delay message
,08-31 18:49:34.126  7650  8003 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-31 18:49:34.128  7650  8003 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f7904c0 on behalf of 
08-31 18:49:34.129  7650  8003 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-31 18:49:34.130  7650  8003 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-31 18:49:34.133  7650  8003 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2279b5f9 on behalf of 
08-31 18:49:34.134  7650  8003 V BluetoothOppNotification: outbound: succ-0  fail-0
08-31 18:49:34.136  7650  8003 V BluetoothOppNotification: outbound notification was removed.
08-31 18:49:34.136  7650  8003 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-31 18:49:34.137  7650  8003 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ada893e on behalf of 
08-31 18:49:34.138  7650  8003 V BluetoothOppNotification: inbound: succ-0  fail-0
08-31 18:49:34.140  7650  8003 V BluetoothOppNotification: inbound notification was removed.
08-31 18:49:34.140  7650  8003 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-31 18:49:34.142  7650  8003 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8d1839f on behalf of 
08-31 18:49:34.249   309   892 D SoftapController: Softap fwReload - Ok
,08-31 18:49:34.265  1035  1541 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (573ms)
,08-31 18:49:34.289   309   892 D CommandListener: Setting iface cfg
08-31 18:49:34.289   309   892 D CommandListener: Trying to bring down wlan0
,08-31 18:49:34.333   309   892 D CommandListener: Clearing all IP addresses on wlan0
,08-31 18:49:34.362  1035  1541 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-31 18:49:34.369  1035  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 18:49:34.369  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 18:49:34.369  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 18:49:34.369  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 18:49:34.370  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 18:49:34.370  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 18:49:34.371  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 18:49:34.371  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 18:49:34.371  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 18:49:34.371  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 18:49:34.371  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 18:49:34.371  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 18:49:34.371  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 18:49:34.369  8017  8017 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:34.369  8017  8017 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 18:49:34.398  8017  8017 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 18:49:34.422  8017  8017 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 18:49:34.422  8017  8017 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-31 18:49:34.424  1035  1097 D Tethering: InitialState.processMessage what=4
08-31 18:49:34.425  1035  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 18:49:34.426  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-31 18:49:34.426  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 18:49:34.426  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 18:49:34.426  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 18:49:34.427  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 18:49:34.427  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 18:49:34.427  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-31 18:49:34.427  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 18:49:34.427  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 18:49:34.427  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 18:49:34.427  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-31 18:49:34.466  1035  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 18:49:34.466  1035  1541 E WifiStateMachine: useWiFiOffloading() : false
08-31 18:49:34.466  1035  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-31 18:49:34.467  1035  1541 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 18:49:34.467  1035  1541 D WifiMonitor: connecting to supplicant
08-31 18:49:34.470  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-31 18:49:34.470  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:34.475  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:34.478  8017  8017 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 18:49:34.514  8017  8017 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-31 18:49:34.519  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-31 18:49:34.519  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-31 18:49:34.519  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-31 18:49:34.520  1035  1541 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-31 18:49:34.520  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:34.520  1035  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:34.521  1035  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:34.521  1035  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:34.521  1035  1541 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-31 18:49:34.521  1035  1541 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-31 18:49:34.522  1035  1541 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-31 18:49:34.522  1035  1541 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-31 18:49:34.522  1035  1541 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-31 18:49:34.522  1035  1092 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8022 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-31 18:49:34.523  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-31 18:49:34.523  1035  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-31 18:49:34.523  1035  1541 E WifiStateMachine: useWiFiOffloading() : false
08-31 18:49:34.523  1035  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-31 18:49:34.524  1035  1541 D WifiNative-wlan0: doBoolean: SET update_config 1
08-31 18:49:34.525  1035  1541 D WifiNative-wlan0: SET update_config 1: returned true
08-31 18:49:34.525  1035  1541 D WifiConfigStore: Loading config and enabling all networks 
08-31 18:49:34.525  1035  1541 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-31 18:49:34.525  1035  1541 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-31 18:49:34.529   335   335 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 308us total 14.387ms
08-31 18:49:34.529  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:34.529  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:34.529  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:34.529  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:34.529  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-31 18:49:34.530  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:34.530  1976  1976 D WfdService: Waiting for WifiP2p enabling
08-31 18:49:34.532  1035  1035 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-31 18:49:34.532  1035  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-31 18:49:34.535  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:34.535  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:34.535  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:34.535  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:34.535  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:34.535  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:34.535  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:34.535  6733  6733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 18:49:34.536  6733  6733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:34.538  1035  1541 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-31 18:49:34.543  8017  8017 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-31 18:49:34.544  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 18:49:34.544  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 18:49:34.544  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-31 18:49:34.544  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-31 18:49:34.544  1035  8028 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-31 18:49:34.544  1035  8028 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-31 18:49:34.546  1035  1541 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-31 18:49:34.546  1035  1541 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 18:49:34.547  1035  1541 D WifiStateMachine: enableVerboseLogging : level 2
08-31 18:49:34.547  1035  1541 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-31 18:49:34.547  1035  1541 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-31 18:49:34.547  1035  1541 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-31 18:49:34.548  1035  1541 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-31 18:49:34.548  1035  1541 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-31 18:49:34.548  1035  1541 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-31 18:49:34.548  1035  1541 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-31 18:49:34.548  1035  1541 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-31 18:49:34.548  1035  1541 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-31 18:49:34.549  1035  1541 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-31 18:49:34.549  1035  1541 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-31 18:49:34.549  1035  1541 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-31 18:49:34.549  1035  1541 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-31 18:49:34.552  1035  1541 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-31 18:49:34.554  1976  1976 D WfdsService: Supplicant Connection state is changed : true
08-31 18:49:34.554  1976  2322 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-31 18:49:34.554  1976  2322 D WfdsService: Set the WFDS Monitor: true
08-31 18:49:34.554  1976  2322 D WfdsMonitor: WfdsMonitorThread create
08-31 18:49:34.554  1976  2322 D WfdsMonitor: WFDS Monitor is created and started
08-31 18:49:34.554  1976  2322 D WfdsService: WiFi: Supplicant connection re-established
08-31 18:49:34.554   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 513us total 24.428ms
08-31 18:49:34.554  1035  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 18:49:34.554  1035  1541 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-31 18:49:34.554  1976  8042 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-31 18:49:34.555  1035  1541 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-31 18:49:34.555  1035  1541 D WifiNative-HAL: Setting external_sim to 1
08-31 18:49:34.555  1035  1541 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-31 18:49:34.555  1976  8042 E CtrlSupplicant: Succeed to open control connection
08-31 18:49:34.555  1035  1541 D WifiNative-wlan0: SET external_sim 1: returned true
08-31 18:49:34.555  1976  8042 E CtrlSupplicant: Succeed to open monitor connection
08-31 18:49:34.555  1035  1541 I WifiNative-HAL: startHal
08-31 18:49:34.555  1035  1541 D wifi    : setting scan oui 0xaf7679a0
08-31 18:49:34.555  1976  8042 D WfdsMonitor: Supplicant connection established
08-31 18:49:34.555  1976  2322 D WfdsService: Connected to the supplicant for wfds
08-31 18:49:34.555  1035  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 18:49:34.555  1035  1541 I WifiNative-HAL: startHal
08-31 18:49:34.555  1035  1541 D wifi    : setting scan oui 0xaf7679a0
08-31 18:49:34.556  1035  1541 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-31 18:49:34.556  1035  1541 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-31 18:49:34.556  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-31 18:49:34.556  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-31 18:49:34.556  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-31 18:49:34.556  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 18:49:34.556  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 18:49:34.557  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 18:49:34.557  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-31 18:49:34.557  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-31 18:49:34.557  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-31 18:49:34.557  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 18:49:34.557  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 18:49:34.557  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 18:49:34.557  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-31 18:49:34.557  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-31 18:49:34.557  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-31 18:49:34.557  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-31 18:49:34.557 , 8017  8017 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-31 18:49:34.558  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-31 18:49:34.558  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-31 18:49:34.558  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-31 18:49:34.558  1035  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-31 18:49:34.558  7686  7686 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:34.559  1035  1541 E WifiNative: : [214,372,683 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-31 18:49:34.559  1035  1541 D WifiNative-wlan0: doBoolean: RECONNECT
08-31 18:49:34.559  1035  1541 D WifiNative-wlan0: RECONNECT: returned true
08-31 18:49:34.559  1035  1541 D WifiNative-wlan0: doString: [STATUS]
08-31 18:49:34.560  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-31 18:49:34.560  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-31 18:49:34.561  1035  1541 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-31 18:49:34.561  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 18:49:34.561  1035  1541 D WifiNative-wlan0: SET ps 1: returned true
08-31 18:49:34.561  1035  1540 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 18:49:34.563   309   892 D CommandListener: Setting iface cfg
08-31 18:49:34.563   309   892 D CommandListener: Trying to bring up p2p0
08-31 18:49:34.563  1035  1540 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 18:49:34.563  1035  1540 D LGWifiP2pService: P2pEnablingState
08-31 18:49:34.563  1035  1540 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.563  1035  1540 D LGWifiP2pService: P2p socket connection successful
08-31 18:49:34.563  1035  1540 D LGWifiP2pService: P2pEnabledState
08-31 18:49:34.564  1035  1540 D LGWifiP2pService: sending p2p connection changed broadcast
08-31 18:49:34.565  1976  1976 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-31 18:49:34.565  1976  1976 D WfdsService: WifiP2pState is changed : true
08-31 18:49:34.565  1976  2322 D WfdsService: Receive the WFDS_ENABLE Method
08-31 18:49:34.565  1976  2322 D WfdsService: Set the WFDS Monitor: true
08-31 18:49:34.565  1976  2322 D WfdsService: Connected to the supplicant for wfds
08-31 18:49:34.565  1976  2322 D WfdsJNI : doCommand: WFDS_SET TRUE
08-31 18:49:34.566  8017  8017 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-31 18:49:34.566  1976  2322 D WfdsService: selectPreferredScanChannel [36]
08-31 18:49:34.566  1976  2322 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-31 18:49:34.566  1976  1976 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-31 18:49:34.565  1035  1540 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-31 18:49:34.566  1035  1541 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-31 18:49:34.566  1976  1976 D WfdsService: isConnected: false
08-31 18:49:34.567  1035  1541 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-31 18:49:34.567  1035  1540 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-31 18:49:34.567  1035  1540 D WifiNative-p2p0: doBoolean: SET device_name G3
08-31 18:49:34.567  1035  1541 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-31 18:49:34.567  1035  1541 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-31 18:49:34.567  1035  1540 D WifiNative-p2p0: SET device_name G3: returned true
08-31 18:49:34.567  1035  1540 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-31 18:49:34.567  1035  1540 D LGWifiP2pService: before postfix = G3
08-31 18:49:34.567  1035  1540 D WifiServerServiceExt: postfix byte check : 2
08-31 18:49:34.567  1035  1540 D LGWifiP2pService: after postfix = G3
08-31 18:49:34.567  1035  1540 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-31 18:49:34.567  1035  1541 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-31 18:49:34.567  1035  1541 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-31 18:49:34.567  1035  1540 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-31 18:49:34.568  1035  1540 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-31 18:49:34.568  1035  1541 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-31 18:49:34.568  1035  1541 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-31 18:49:34.568  8017  8017 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-31 18:49:34.568  1035  1540 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-31 18:49:34.568  1035  1540 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-31 18:49:34.568  1035  1540 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-31 18:49:34.568  1035  1540 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-31 18:49:34.568  1035  1540 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-31 18:49:34.568  1035  1540 D WifiNative-HAL: p2pGetDeviceAddress
08-31 18:49:34.568  1035  1540 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-31 18:49:34.569  1035  1035 D WifiScanningService: ,SCAN_AVAILABLE : 3
08-31 18:49:34.569  1035  1035 D RttService: SCAN_AVAILABLE : 3
08-31 18:49:34.569  1035  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.569  1035  1559 I WifiNative-HAL: startHal
08-31 18:49:34.569  1035  1560 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.569  1035  1559 D wifi    : getting scan capabilities on interface[1] = 0xaf7679a0
08-31 18:49:34.569  1035  1559 D wifi    : failed to get capabilities : -3
08-31 18:49:34.569  1035  1559 E WifiScanningService: could not get scan capabilities
08-31 18:49:34.569  1035  1540 D LGWifiP2pService: DeviceAddress: 
08-31 18:49:34.569  1035  1541 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-31 18:49:34.569  1035  1540 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-31 18:49:34.570  1035  1540 D WifiNative-p2p0: P2P_FLUSH: returned true
08-31 18:49:34.570  1035  1540 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-31 18:49:34.570  1035  1540 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-31 18:49:34.570  1035  1540 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-31 18:49:34.570  1035  1540 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-31 18:49:34.570  1035  1540 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-31 18:49:34.572  1976  1976 I WfdStateTracker: handleP2pThisDeviceChanged
08-31 18:49:34.572  1035  1541 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-31 18:49:34.572  1976  1976 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-31 18:49:34.572  1035  1541 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-31 18:49:34.572  1035  1541 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-31 18:49:34.573  1976  1976 D WfdsService: Update P2p Interface State: 3
08-31 18:49:34.573   335   335 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 18.130ms
,08-31 18:49:34.578  8017  8017 E wpa_supplicant: disconnect_rssi_lvl: -100
08-31 18:49:34.578  1035  1540 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-31 18:49:34.579  1035  1540 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-31 18:49:34.579  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=214393  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 18:49:34.579  1035  1540 D LGWifiP2pService: InactiveState
08-31 18:49:34.579  1035  1540 D LGWifiP2pService: InactiveState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.579  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.579  1035  1540 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-31 18:49:34.579  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 18:49:34.580  8017  8017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:34.580  1035  8028 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 18:49:34.580  1035  8028 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:34.580  1035  8028 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:34.580  1035  8028 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:34.580  8017  8017 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 18:49:34.580  8017  8017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.580  1035  8028 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:34.580  1035  8028 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.580  1035  8028 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.580  1035  8028 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.581  8017  8017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.581  1035  8028 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:34.581  1035  8028 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.581  1035  8028 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.581  1035  8028 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.581  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:34.581  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:34.581  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 18:49:34.581  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:34.581  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:34.581  1035  1540 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,08-31 18:49:34.582  1035  1540 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1976  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1976  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1976  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1540 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.582  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=214397  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 18:49:34.583  1976  2322 W WfdsService: DefaultState - msg [9441285] is not handled
08-31 18:49:34.583  1035  1541 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 18:49:34.583  1035  1035 E WifiServerServiceExt: No p2p device connected
08-31 18:49:34.583  1035  1541 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 18:49:34.584  1035  1541 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-31 18:49:34.584  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-31 18:49:34.584  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:34.584  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-31 18:49:34.585  8017  8017 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:34.585  8017  8017 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-31 18:49:34.586  8017  8017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.586  8017  8017 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.587  1976  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:34.587  1976  8042 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-31 18:49:34.587  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-31 18:49:34.587  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:34.587  1035  8028 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:34.587  1035  8028 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-31 18:49:34.587  1035  8028 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:34.587  1035  8028 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.588  1035  8028 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.588  1035  8028 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-31 18:49:34.588  1035  8028 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-31 18:49:34.588  1035  8028 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.588  1035  8028 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.588  1035  8028 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-31 18:49:34.588  1035  1541 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-31 18:49:34.589  1035  1541 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,08-31 18:49:34.589  1035  1541 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-31 18:49:34.589  1035  1541 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-31 18:49:34.589  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-31 18:49:34.589  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-31 18:49:34.589  8017  8017 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 18:49:34.590  1035  1540 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.590  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:34.591  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-31 18:49:34.591  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 18:49:34.591  1035  8028 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 18:49:34.591  1035  8028 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-31 18:49:34.591  1035  1541 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-31 18:49:34.591  1035  1541 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-31 18:49:34.592  1035  1541 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-31 18:49:34.592  1035  1541 D WifiNative-wlan0: doBoolean: SCAN
08-31 18:49:34.592  1035  1541 D WifiNative-wlan0: SCAN: returned false
08-31 18:49:34.593  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=214407  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 18:49:34.593  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=214408  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-31 18:49:34.594  1035  1541 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:34.594  1035  1541 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:34.594  1035  1541 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:34.595  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 18:49:34.595  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:34.595  1035  1541 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:34.595  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-31 18:49:34.595  1035  1541 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-31 18:49:34.596  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:34.596  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 18:49:34.596  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:34.596  1035  1035 D WifiServerServiceExt: setSupplicantStateSCANNING
08-31 18:49:34.603  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:34.603  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:34.604  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 18:49:34.635  1035  1763 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8047 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-31 18:49:34.639  8022  8045 W FormManager: Network not available. Please check & try again.
08-31 18:49:34.642  8022  8046 V FormManager: Network unavailable.
08-31 18:49:34.644  8022  8046 V FormManager: Network unavailable.
08-31 18:49:34.655  1035  1050 I ActivityManager: Killing 7134:com.android.chrome/u0a57 (adj 15): empty #17
,08-31 18:49:34.686  1035  2091 W libprocessgroup: failed to open /acct/uid_10057/pid_7134/cgroup.procs: No such file or directory
08-31 18:49:34.697  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 18:49:34.697  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:34.697  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:34.697  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:34.697  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:34.697  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 18:49:34.697  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 18:49:34.697  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 18:49:34.698  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 18:49:34.701  6733  6803 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-31 18:49:34.702  6733  6803 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 18:49:34.703  6733  6803 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2996bd7 Bundle[{}]
08-31 18:49:34.704  6733  6803 I io.jxcore.node.LifeCycleMonitor: start: OK
08-31 18:49:34.704  6733  6803 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 18:49:34.704  6733  6803 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-31 18:49:34.705  6733  6803 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 18:49:34.705  6733  6803 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 18:49:34.705  6733  6803 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 18:49:34.709  6733  6803 I System.out: Running OutgoingSocketThread
,08-31 18:49:34.711  6733  8065 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
08-31 18:49:34.712  6733  8065 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 59004
08-31 18:49:34.712  6733  8065 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-31 18:49:34.726  8047  8047 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 18:49:34.728  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 18:49:34.733  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:34.735  1035  1740 I ActivityManager: Killing 7152:com.lge.drmservice/u0a62 (adj 15): empty #17
08-31 18:49:34.784  1035  2116 W libprocessgroup: failed to open /acct/uid_10062/pid_7152/cgroup.procs: No such file or directory
,08-31 18:49:34.803  8047  8047 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-31 18:49:34.806  8022  8069 W FormManager: Network not available. Please check & try again.
,08-31 18:49:34.808  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-31 18:49:34.814  8022  8070 V FormManager: Network unavailable.
,08-31 18:49:34.819  8022  8070 V FormManager: Network unavailable.
08-31 18:49:34.820  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:34.843  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 18:49:34.844  4328  4328 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-31 18:49:34.849  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:34.854  4328  4328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-31 18:49:34.867  4328  8074 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-31 18:49:34.874  4328  8075 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-31 18:49:34.875  4328  8075 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-31 18:49:34.926  1035  1995 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8076 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-31 18:49:35.053  8076  8076 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 18:49:35.054  8076  8076 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-31 18:49:35.064  8076  8076 V [BNRBootReceiver]: Boot Receiver Return
08-31 18:49:35.065  8076  8076 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-31 18:49:35.137  1035  1740 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8094 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-31 18:49:35.140  1035  1740 I ActivityManager: Killing 7169:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-31 18:49:35.175  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-31 18:49:35.175  1035  8028 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-31 18:49:35.175  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-31 18:49:35.175  8017  8017 E wpa_supplicant: USIM:  scard_init function
08-31 18:49:35.175  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-31 18:49:35.175  1035  8028 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-31 18:49:35.176  8017  8017 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-31 18:49:35.176  1035  1541 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 18:49:35.176  1035  1541 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,08-31 18:49:35.177  1035  1541 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 18:49:35.177  1035  1541 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-31 18:49:35.177  1035  1541 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-31 18:49:35.179  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-31 18:49:35.179  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-31 18:49:35.193  1035  2096 W libprocessgroup: failed to open /acct/uid_10085/pid_7169/cgroup.procs: No such file or directory
,08-31 18:49:35.197  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=215011  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-31 18:49:35.201  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=215016  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-31 18:49:35.203  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.203  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.204  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 18:49:35.204  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:35.204  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-31 18:49:35.205  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.205  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:35.209  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 18:49:35.238  8094  8094 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 18:49:35.261  8094  8094 D PluginManager: init()
,08-31 18:49:35.290  8017  8017 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-31 18:49:35.290  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-31 18:49:35.290  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-31 18:49:35.290  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-31 18:49:35.290  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-31 18:49:35.290  1035  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 18:49:35.290  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-31 18:49:35.291  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=215105  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 18:49:35.292  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=215106  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-31 18:49:35.293  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:35.296  1035  1541 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215110
08-31 18:49:35.296  1035  1541 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215110
08-31 18:49:35.297  1035  1541 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215111
08-31 18:49:35.297  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215112
08-31 18:49:35.298  1035  1541 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215112
08-31 18:49:35.299  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:35.299  1035  1035 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-31 18:49:35.299  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=215113  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 18:49:35.301  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:35.301  8017  8017 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 18:49:35.301  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:35.301  8017  8017 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 18:49:35.301  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-31 18:49:35.301  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 18:49:35.301  1035  8028 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 18:49:35.301  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-31 18:49:35.302  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 18:49:35.302  1035  8028 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-31 18:49:35.302  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:35.302  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-31 18:49:35.306  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.306  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:35.307  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=215121  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-31 18:49:35.307  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 18:49:35.307  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.307  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.307  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-31 18:49:35.310  1035  1541 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:35.311  1035  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:35.311  1035  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:35.312  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:35.312  1035  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-31 18:49:35.313  1035  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=215127  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 18:49:35.313  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=215128  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-31 18:49:35.314  1035  1541 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=215128
08-31 18:49:35.314  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.314  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.314  1035  1541 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=215128
08-31 18:49:35.314  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-31 18:49:35.315  1035  1541 D WifiNative-wlan0: doString: [STATUS]
08-31 18:49:35.315  1035  8028 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-31 18:49:35.315  1035  8028 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-31 18:49:35.316  1035  1541 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-31 18:49:35.317  1035  1541 I WifiServiceExtension: setVHTCapabilityType  : false
08-31 18:49:35.325  1035  1541 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-31 18:49:35.325  1035  1541 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-31 18:49:35.331  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.331  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-31 18:49:35.332  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.333  1035  1541 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-31 18:49:35.334  1035  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 18:49:35.334  1035  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 18:49:35.334  1035  1547 D ConnectivityService: Got NetworkAgent Messenger
08-31 18:49:35.334  1035  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-31 18:49:35.334  1035  1547 D ConnectivityService: NetworkAgent connected
08-31 18:49:35.334  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.334  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.334  1035  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 18:49:35.334  1035  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 18:49:35.334  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 18:49:35.335  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.335  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.335  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-31 18:49:35.336  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.336  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:35.337  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.338  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.338  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:35.339  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.340  1035  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 18:49:35.340  1035  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 18:49:35.340  1035  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-31 18:49:35.340  1035  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-31 18:49:35.340  1035  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-31 18:49:35.343  1035  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-31 18:49:35.344   309   892 D CommandListener: Setting iface cfg
,08-31 18:49:35.347  1035  1541 E WifiStateMachine: Start Dhcp Watchdog 3
08-31 18:49:35.347  1035  8117 D DhcpStateMachine: StoppedState
08-31 18:49:35.347  1035  8117 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:35.347  1035  8117 D DhcpStateMachine: WaitBeforeStartState
08-31 18:49:35.348  1035  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=215162  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:35.348  1035  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=215162  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:35.348  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=215162  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:35.349  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:35.349  1035  1035 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-31 18:49:35.350  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:35.350  1035  1035 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-31 18:49:35.351  1035  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=215165  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:35.351  1035  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=215165  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:35.352  1035  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=215166  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-31 18:49:35.353  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13922] from screen [on:0 period:-511607175] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 18:49:35.355  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-511607174] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-31 18:49:35.355  1035  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-31 18:49:35.358  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-31 18:49:35.358  1035  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-31 18:49:35.358  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:35.358  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:35.359  1035  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:35.359  1035  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:35.359  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:35.359  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-31 18:49:35.360  1035  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 18:49:35.360  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=163,0,0
08-31 18:49:35.360  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=163,0,0
08-31 18:49:35.360  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-31 18:49:35.360  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-31 18:49:35.361  1035  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-31 18:49:35.361  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 0
08-31 18:49:35.361  1035  1541 D WifiNative-wlan0: SET ps 0: returned true
08-31 18:49:35.361  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-31 18:49:35.361  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-31 18:49:35.361  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-31 18:49:35.361  1035  1540 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e4af89c target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:35.361  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e4af89c target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:35.362  1035  1541 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-31 18:49:35.362  1035  1541 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 18:49:35.362  1035  8117 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:35.362  1035  8117 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-31 18:49:35.362  1035  1541 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 18:49:35.362   309   892 D CommandListener: Setting iface cfg
08-31 18:49:35.362   309   892 D CommandListener: Trying to bring up wlan0
08-31 18:49:35.363  1035  1541 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-31 18:49:35.364  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-31 18:49:35.364  1035  1035 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-31 18:49:35.364  1035  1035 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-31 18:49:35.364  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-31 18:49:35.364  1035  1540 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:35.364  1035  1540 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:35.364  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-31 18:49:35.365  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-31 18:49:35.365  1035  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-31 18:4,9:35.365  1035  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-31 18:49:35.365  8017  8017 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-31 18:49:35.365  1035  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-31 18:49:35.365  1035  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-31 18:49:35.386  1035  1541 D WifiNative-wlan0: SET ps 1: returned true
,08-31 18:49:35.387  1035  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 18:49:35.387  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:35.387  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 18:49:35.388  1035  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:35.388  1035  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:35.388  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:35.388  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:35.389  1035  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-31 18:49:35.389  1035  1541 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 18:49:35.390  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-31 18:49:35.390  1035  1541 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 18:49:35.390  1035  1547 D ConnectivityService: ignoring duplicate network state non-change
08-31 18:49:35.392  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.392  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:35.393  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.393  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.393  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 18:49:35.394  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.395  1035  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 18:49:35.395  1035  1547 D ConnectivityService: Adding iface wlan0 to network 102
08-31 18:49:35.400  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.400  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.400  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-31 18:49:35.402  1035  1541 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 18:49:35.407  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-31 18:49:35.410  1976  1976 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-31 18:49:35.413  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.413  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.413  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 18:49:35.415  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.415  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-31 18:49:35.415  1035  1035 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-31 18:49:35.423  1035  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 18:49:35.424  1035  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-31 18:49:35.425  1035  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-31 18:49:35.426   309   892 E Netd    : netlink response contains error (File exists)
08-31 18:49:35.426  1035  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-31 18:49:35.427  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.427  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.427  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 18:49:35.427  1035  1035 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-31 18:49:35.427  1035  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-31 18:49:35.427  1035  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-31 18:49:35.427  1035  1547 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-31 18:49:35.428  1035  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 18:49:35.428  1035  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-31 18:49:35.428  1035  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-31 18:49:35.429  1035  8116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:35.429  1035  8116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-31 18:49:35.429  1035  8116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 18:49:35.429  1035  8116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-31 18:49:35.430  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.430  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 18:49:35.430  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.431  1035  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 18:49:35.432  1035  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:35.432  1035  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:35.432  1035  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 18:49:35.432   309  8122 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-31 18:49:35.433  1035  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:35.435  1035  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-31 18:49:35.435  1035  1547 D ConnectivityService: currentScore = 0, newScore = 20
08-31 18:49:35.435  1035  1547 D ConnectivityService:    accepting network in place of null
08-31 18:49:35.435  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false,, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 18:49:35.435  1035  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:35.435  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-31 18:49:35.435  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.436  1881  1881 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:35.436  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 18:49:35.436  1035  1541 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:35.437  1035  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:35.439  1035  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 18:49:35.439  1035  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-31 18:49:35.439  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 18:49:35.440  1035  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-31 18:49:35.440  1035  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-31 18:49:35.440  1035  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-31 18:49:35.442  1035  1547 D ConnectivityService: validation of new default Network = false
08-31 18:49:35.442  1035  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-31 18:49:35.443  1035  1547 D DSQN    : enableDataServiceNotify 
08-31 18:49:35.443  1035  1547 D DSQN    : start dsqn bin
08-31 18:49:35.446  1035  1035 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-31 18:49:35.446  1035  1035 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-31 18:49:35.446  1035  1035 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-31 18:49:35.446  1035  1035 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-31 18:49:35.448  1035  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 18:49:35.448  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:35.448  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:35.448  1035  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:35.449  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 18:49:35.439  8123  8123 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:35.439  8123  8123 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 18:49:35.466  8123  8123 E DSQN    : DSQN ssw
,08-31 18:49:35.473  1035  1539 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-31 18:49:35.483   309  8122 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-31 18:49:35.485  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-31 18:49:35.486  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.487  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.523   309  8122 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-31 18:49:35.560   309   891 D LGDataListener: argv[0]=dsqncommand
08-31 18:49:35.560   309   891 D LGDataListener: argv[1]=wlan0
08-31 18:49:35.560   309   891 D LGDataListener: argv[2]=1
08-31 18:49:35.560   309   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-31 18:49:35.562  1035  1095 D DSQN    : DSQM DsqnNotification wlan0  1
,08-31 18:49:35.562  1035  1095 D DSQN    : start to monitor internet connection
08-31 18:49:35.566  1035  8117 D DhcpStateMachine: DHCPV4 request on wlan0
08-31 18:49:35.568  1035  8117 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-31 18:49:35.568  1035  8117 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-31 18:49:35.569  8129  8129 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-31 18:49:35.569  8129  8129 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-31 18:49:35.593  8129  8129 I dhcpcd  : version 5.5.6 starting
,08-31 18:49:35.596  8129  8129 E dhcpcd  : get_duid: m
,08-31 18:49:35.596  8129  8129 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-31 18:49:35.596  8129  8129 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-31 18:49:35.603  1035  8116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 16:49:35 GMT], X-Android-Received-Millis=[1472662175596], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472662175560]}
08-31 18:49:35.603  1035  8116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-31 18:49:35.603  1035  8116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-31 18:49:35.603  1035  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-31 18:49:35.603  1035  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-31 18:49:35.603  1035  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:35.604  1035  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:35.604  1035  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-31 18:49:35.604  1035  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-31 18:49:35.604  1035  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-31 18:49:35.605  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 18:49:35.605  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:35.605  1035  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:35.606  1035  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:35.606  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 18:49:35.607  1881  1881 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:35.607  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-31 18:49:35.608  1035  1541 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:35.608  1035  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 18:49:35.608  1035  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 18:49:35.630  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-31 18:49:35.631  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.632  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-31 18:49:35.664  8129  8129 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-31 18:49:35.664  8129  8129 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-31 18:49:35.664  8129  8129 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 18:49:35.664  8129  8129 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-31 18:49:35.664  8129  8129 D dhcpcd  : wlan0: sending REQUEST (xid 0xe52d3052), next in 3.39 seconds
08-31 18:49:35.712  6733  6803 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
08-31 18:49:35.712  6733  6803 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
,08-31 18:49:35.730  6733  6803 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
,08-31 18:49:35.734  6733  6803 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 18:49:35.734  6733  6803 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
08-31 18:49:35.742  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.742  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@303a492 added. We now have 2 listener(s)
08-31 18:49:35.743  1035  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.745  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.746  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.746  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.746  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.746  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9dbe63 added. We now have 9 listener(s)
08-31 18:49:35.746  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.746  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 18:49:35.747  8129  8129 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-31 18:49:35.749  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:35.752  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:35.752  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:35.752  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:35.752  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:35.752  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:35.752  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.752  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:35.752  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:35.754  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.754  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:35.755  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.755  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10bcbb19 added. We now have 3 listener(s)
08-31 18:49:35.755  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.756  1035  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.757  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.759  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.759  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.762  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.762  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.762  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fb377de added. We now have 10 listener(s)
08-31 18:49:35.763  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.763  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:35.763  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:35.763  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:35.763  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.763  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.763  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bl,uetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:35.763  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.763  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@303a492 removed from the list
08-31 18:49:35.763  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.763  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9dbe63 removed from the list
08-31 18:49:35.763  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:35.763  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.764  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.764  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 18:49:35.764  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 18:49:35.764  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 18:49:35.764  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.764  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f9dbe63 not in the list
08-31 18:49:35.764  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.765  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.765  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.765  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.765  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.766  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fb377de removed from the list
08-31 18:49:35.766  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.766  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.766  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.766  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.766  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10bcbb19 removed from the list
08-31 18:49:35.767  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.767  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11a3ddbf added. We now have 2 listener(s)
08-31 18:49:35.768  1035  2068 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.768  8094  8094 W ExternalStrings: load override strings
08-31 18:49:35.768  8094  8094 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:49:35.768  8094  8094 ,W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 18:49:35.768  8094  8094 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 18:49:35.770  8094  8094 D StatusProvider: onCreate
08-31 18:49:35.770  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.770  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.770  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.770  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.771  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@310fcc8c added. We now have 9 listener(s)
08-31 18:49:35.771  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.771  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:49:35.775  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 18:49:35.779  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:35.779  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:35.779  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:35.779  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:35.779  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:35.779  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.779  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:35.779  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:35.781  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.781  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:35.783  8129  8129 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-31 18:49:35.783  8129  8129 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-31 18:49:35.783  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.783  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfb33ea added. We now have 3 listener(s)
08-31 18:49:35.783  8129  8129 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-31 18:49:35.783  8129  8129 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-31 18:49:35.783  8129  8129 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-31 18:49:35.783  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.783  8129  8129 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-31 18:49:35.784  8129  8129 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-31 18:49:35.784  8129  8129 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-31 18:49:35.784  1035  1993 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.785  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.787  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.787  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.787  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.787  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.788  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11c296db added. We now have 10 listener(s)
08-31 18:49:35.788  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.788  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:49:35.788  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: S,tart operation: Should affect listening to advertisements only
08-31 18:49:35.788  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:49:35.788  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:35.788  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 18:49:35.790  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 18:49:35.791  1035  1762 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.794  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 18:49:35.795  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 18:49:35.796  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 18:49:35.797  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:35.798  6733  6803 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 18:49:35.798  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:35.798  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:35.800  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:35.800  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:35.800  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:35.801  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.801  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.801  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:35.801  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.801  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11a3ddbf removed from the list
08-31 18:49:35.801  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.801  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@310fcc8c removed from the list
08-31 18:49:35.801  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:35.801  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.802  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.802  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.803  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.803  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.803  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.803  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@310fcc8c not in the list
08-31 18:49:35.803  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.803  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.804  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.804  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:35.804  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:35.804  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.804  6733  6803 I org.thal,iproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.804  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11c296db removed from the list
08-31 18:49:35.804  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.804  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.804  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.804  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.804  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfb33ea removed from the list
08-31 18:49:35.805  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.805  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@550a4b6 added. We now have 2 listener(s)
08-31 18:49:35.805  1035  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.807  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.807  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.807  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.807  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.807  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3049c5b7 added. We now have 9 listener(s)
08-31 18:49:35.807  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.808  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 18:49:35.810  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:35.812  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:35.812  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:35.812  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:35.812  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:35.812  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:35.812  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.812  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:35.812  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:35.814  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.814  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:35.815  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.817  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.817  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.817  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edc448d added. We now have 3 listener(s)
08-31 18:49:35.817  1035  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.819  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.819  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.819  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.819  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.819  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ba5642 added. We now have 10 listener(s)
08-31 18:49:35.819  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.819  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:49:35.820  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:49:35.820  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 18:49:35.820  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:49:35.820  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:35.820  6733  6803, I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 18:49:35.823  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 18:49:35.823  1035  2068 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 18:49:35.826  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 18:49:35.826  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 18:49:35.827  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:49:35.827  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:35.828  6733  6803 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 18:49:35.829  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:35.829  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:35.829  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:35.829  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.829  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.829  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:35.829  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.829  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@550a4b6 removed from the list
08-31 18:49:35.829  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.829  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3049c5b7 removed from the list
08-31 18:49:35.829  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:35.829  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.830  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.830  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.830  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.830  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.830  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.830  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3049c5b7 not in the list
08-31 18:49:35.830  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.830  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.831  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.831  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:35.831  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:35.831  6733  6803 I ,org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.831  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.831  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ba5642 removed from the list
08-31 18:49:35.831  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.831  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.831  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.832  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.832  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edc448d removed from the list
08-31 18:49:35.832  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 18:49:35.832  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a559c89 added. We now have 2 listener(s)
08-31 18:49:35.833  1035  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-31 18:49:35.834  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.835  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.835  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.835  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.835  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171b948e added. We now have 9 listener(s)
08-31 18:49:35.835  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.835  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:49:35.836  8094  8094 V Signer  : override build config not found
08-31 18:49:35.836  8094  8094 D Signer  : value of property debug is false
08-31 18:49:35.839  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:35.841  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:35.841  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:35.841  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:35.841  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:35.841  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:35.841  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.841  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:35.841  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 18:49:35.842  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.843  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:35.843  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.843  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36570bc added. We now have 3 listener(s)
08-31 18:49:35.843  1035  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.844  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.845  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.846  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.847  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.847  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.847  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettin,gs: load: Already loaded
08-31 18:49:35.847  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f27845 added. We now have 10 listener(s)
08-31 18:49:35.847  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.847  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:49:35.847  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 18:49:35.847  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 18:49:35.847  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:35.847  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 18:49:35.852  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 18:49:35.852  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.855  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 18:49:35.856  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 18:49:35.857  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 18:49:35.860  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 18:49:35.862  6733  6803 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 18:49:35.863  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:35.863  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:35.863  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:35.864  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.864  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.864  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:35.864  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.864  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a559c89 removed from the list
08-31 18:49:35.864  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.864  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171b948e removed from the list
08-31 18:49:35.864  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:35.864  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.864  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.864  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.865  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.865  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.865  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.865  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171b948e not in the list
08-31 18:49:35.865  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.865  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.865  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.866  6733  6803 D BluetoothLeScanner: could not find callback wrapper
08-31 18:49:35.866  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 18:49:35.866  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.866  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.866  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f27845 removed from the list
08-31 18:49:35.866  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.866  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-3,1 18:49:35.866  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.866  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.866  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36570bc removed from the list
08-31 18:49:35.866  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.866  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f76dca8 added. We now have 2 listener(s)
08-31 18:49:35.867  1035  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.868  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.868  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.868  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.868  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.868  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec753c1 added. We now have 9 listener(s)
08-31 18:49:35.868  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.869  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 18:49:35.870  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 18:49:35.872  6733  6803 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 18:49:35.872  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 18:49:35.872  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-31 18:49:35.872  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 18:49:35.872  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 18:49:35.872  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.872  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 18:49:35.872  6733  6803 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 18:49:35.878  6733  6803 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 18:49:35.878  6733  6803 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 18:49:35.878  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 18:49:35.878  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e218aa7 added. We now have 3 listener(s)
08-31 18:49:35.878  1035  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-31 18:49:35.878  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-31 18:49:35.879  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-31 18:49:35.879  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-31 18:49:35.879  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-31 18:49:35.880  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-31 18:49:35.880  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-31 18:49:35.880  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-31 18:49:35.880  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-31 18:49:35.880  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-31 18:49:35.880  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-31 18:49:35.880  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 18:49:35.880  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.880  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 18:49:35.880  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-31 18:49:35.880  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 18:49:35.881  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30b11b54 added. We now have 10 listener(s)
08-31 18:49:35.881  6733  6803 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 18:49:35.881  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-31 18:49:35.881  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-31 18:49:35.881  6733  6803 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 18:49:35.881  8094  8094 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-31 18:49:35.881  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:35.881  6733  6803 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 18:49:35.881  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.881  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listene,r does not exist in the list - probably already removed
08-31 18:49:35.881  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 18:49:35.881  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.881  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f76dca8 removed from the list
08-31 18:49:35.881  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.881  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec753c1 removed from the list
08-31 18:49:35.882  6733  6733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 18:49:35.883  6733  6803 D io.jxcore.node.ConnectivityMonitor: stop
08-31 18:49:35.883  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.883  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.883  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.884  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.884  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.885  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.885  6733  6803 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec753c1 not in the list
08-31 18:49:35.885  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.885  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.885  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 18:49:35.885  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 18:49:35.885  6733  6803 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 18:49:35.885  6733  6803 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30b11b54 removed from the list
08-31 18:49:35.885  6733  6803 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 18:49:35.885  6733  6803 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 18:49:35.885  6733  6803 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 18:49:35.885  6733  6803 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 18:49:35.886  6733  6803 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e218aa7 removed from the list
08-31 18:49:35.886  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 18:49:35.886  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 18:49:35.886  6733  6803 V io.jxcore.node.StartStopO,peration: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 18:49:35.887  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 18:49:35.887  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 18:49:35.887  6733  6803 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 18:49:35.892  8094  8094 V LGMDMManager: Create singleton instance
08-31 18:49:35.895  6733  8153 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: My test thread name)
08-31 18:49:35.896  6733  8153 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: My test thread name)
08-31 18:49:35.896  6733  8153 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 18:49:35.903  6733  8155 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: My test thread name)
08-31 18:49:35.904  6733  8155 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: My test thread name)
08-31 18:49:35.904  6733  8155 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-31 18:49:35.905  6733  6803 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 18:49:35.905  6733  6803 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 18:49:35.905  6733  6803 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 18:49:35.905  6733  6803 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 18:49:35.905  6733  6803 D com.test.thalitest.ThaliTestRunner: Total duration: 22900 ms
08-31 18:49:35.907  6733  6803 I jxcore-log: *Native tests were executed*
08-31 18:49:35.907  6733  6803 I jxcore-log: 
08-31 18:49:35.907  6733  6803 I jxcore-log: Total number of executed tests:  80
08-31 18:49:35.907  6733  6803 I jxcore-log: 
08-31 18:49:35.907  6733  6803 I jxcore-log: Number of passed tests:  80
08-31 18:49:35.907  6733  6803 I jxcore-log: 
08-31 18:49:35.907  6733  6803 I jxcore-log: Number of failed tests:  0
08-31 18:49:35.907  6733  6803 I jxcore-log: 
08-31 18:49:35.907  6733  6803 I jxcore-log: Number of ignored tests:  0
08-31 18:49:35.907  6733  6803 I jxcore-log: 
08-31 18:49:35.908  6733  6803 I jxcore-log: Total duration:  22900
08-31 18:49:35.908  6733  6803 I jxcore-log: 
08-31 18:49:35.908  6733  6803 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 18:49:35.908  6733  6803 I jxcore-log: 
08-31 18:49:35.910  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.910  6733  6803 I jxcore-log: 
08-31 18:49:35.912  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.912  6733  6803 I jxcore-log: 
08-31 18:49:35.913  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.913  6733  6803 I jxcore-log: 
08-31 18:49:35.914  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.914  6733  6803 I jxcore-log: 
08-31 18:49:35.915  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.915  6733  6803 I jxcore-log: 
08-31 18:49:35.916  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.916  6733  6803 I jxcore-log: 
,08-31 18:49:35.916  6733  6733 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 18:49:35.918  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.918  6733  6803 I jxcore-log: 
08-31 18:49:35.919  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 18:49:35.919  6733  6803 I jxcore-log: 
08-31 18:49:35.920  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 18:49:35.920  6733  6803 I jxcore-log: 
08-31 18:49:35.921  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.921  6733  6803 I jxcore-log: 
08-31 18:49:35.921  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.921  6733  6803 I jxcore-log: 
08-31 18:49:35.922  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 18:49:35.922  6733  6803 I jxcore-log: 
08-31 18:49:35.923  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 18:49:35.923  6733  6803 I jxcore-log: 
08-31 18:49:35.923  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 18:49:35.923  6733  6803 I jxcore-log: 
08-31 18:49:35.924  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.924  6733  6803 I jxcore-log: 
08-31 18:49:35.924  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.924  6733  6803 I jxcore-log: 
08-31 18:49:35.925  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.925  6733  6803 I jxcore-log: 
08-31 18:49:35.925  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.925  6733  6803 I jxcore-log: 
08-31 18:49:35.926  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.926  6733  6803 I jxcore-log: 
08-31 18:49:35.926  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.926  6733  6803 I jxcore-log: 
08-31 18:49:35.927  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.927  6733  6803 I jxcore-log: 
08-31 18:49:35.927  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 18:49:35.927  6733  6803 I jxcore-log: 
08-31 18:49:35.928  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 18:49:35.928  6733  6803 I jxcore-log: 
08-31 18:49:35.928  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 18:49:35.928  6733  6803 I jxcore-log: 
08-31 18:49:35.928  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.928  6733  6803 I jxcore-log: 
08-31 18:49:35.929  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.929  6733  6803 I jxcore-log: 
08-31 18:49:35.929  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.929  6733  6803 I jxcore-log: 
08-31 18:49:35.930  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.930  6733  6803 I jxcore-log: 
08-31 18:49:35.930  6733  6803 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 18:49:35.930  6733  6803 I jxcore-log: 
08-31 18:49:35.946  8094  8094 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-31 18:49:35.973  1035  8117 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-31 18:49:35.975  1035  8117 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-31 18:49:35.975  1035  8117 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-31 18:49:35.976  1035  8117 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-31 18:49:35.976  1035  8117 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-31 18:49:35.976  1035  8117 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-31 18:49:35.976  1035  8117 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-31 18:49:35.976  1035  8117 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-31 18:49:35.977  1035  8117 D DhcpStateMachine: RunningState
08-31 18:49:36.003  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:36.004  8094  8160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 18:49:36.019  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:36.029  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:36.094  1035  2096 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8165 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-31 18:49:36.095  1035  2096 I ActivityManager: Killing 7198:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-31 18:49:36.158  8094  8159 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 18:49:36.198  8161  8161 D AndroidRuntime: 
08-31 18:49:36.198  8161  8161 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 18:49:36.201  8161  8161 D AndroidRuntime: CheckJNI is OFF
,08-31 18:49:36.329  8161  8161 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 18:49:36.334  1035  2116 W libprocessgroup: failed to open /acct/uid_10093/pid_7198/cgroup.procs: No such file or directory
,08-31 18:49:36.351  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-31 18:49:36.352  1035  1092 I ActivityManager: Killing 6733:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-31 18:49:36.415  1035  1050 I WindowState: WIN DEATH: Window{10dfa7e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 18:49:36.415  1035  1546 D WifiService: Client connection lost with reason: 4
,08-31 18:49:36.423  1035  1050 D InputDispatcher: Window went away: Window{10dfa7e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 18:49:36.443  1035  1541 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:36.444  1035  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:36.444  1035  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:36.444  1035  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:36.445  1035  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-31 18:49:36.445  1035  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-31 18:49:36.446  1035  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
,08-31 18:49:36.446  1035  1547 D ConnectivityService: identical MTU - not setting
,08-31 18:49:36.446  1035  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-31 18:49:36.446  1035  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-31 18:49:36.446  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 18:49:36.446  1035  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:36.446  1035  1547 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-31 18:49:36.447  1605  1813 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 18:49:36.455  8165  8165 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 18:49:36.572  1035  1092 I ActivityManager:   Force finishing activity ActivityRecord{cecba75 u0 com.test.thalitest/.MainActivity t6}
,08-31 18:49:36.633   331   345 E GBMv2   : DFP En is all cleared set to be enabled
,08-31 18:49:36.636  1035  2091 W ActivityManager: Spurious death for ProcessRecord{2b9bf7c9 6733:com.test.thalitest/u0a118}, curProc for 6733: null
08-31 18:49:36.637  1035  1103 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-31 18:49:36.638  1035  1103 I ActivityManager:   Force finishing activity ActivityRecord{cecba75 u0 com.test.thalitest/.MainActivity t6 f}
08-31 18:49:36.639  1035  1103 W ActivityManager: Duplicate finish request for ActivityRecord{cecba75 u0 com.test.thalitest/.MainActivity t6 f}
,08-31 18:49:36.661  2097  2097 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-31 18:49:36.662  1976  1991 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-31 18:49:36.663  2097  2097 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-31 18:49:36.665  1976  1991 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2d685450 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 18:49:36.666  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-31 18:49:36.666  1976  3994 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-31 18:49:36.666  1976  3994 D SplitWindowPolicy: topRunningActivity=ActivityInfo{24fc7649 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-31 18:49:36.666  2097  2200 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
,08-31 18:49:36.671  8165  8165 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-31 18:49:36.672  1938  1938 D ActionManagerService: notifyUserLog: 1000003
08-31 18:49:36.673  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-31 18:49:36.674  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-31 18:49:36.677  3831  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-31 18:49:36.681  1035  1455 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 18:49:36.695  2052  2052 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-31 18:49:36.700  7650  7650 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-31 18:49:36.700  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-31 18:49:36.701  3831  3831 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-31 18:49:36.704  2097  2097 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-31 18:49:36.746  1035  1051 V SIM_STK : Menu title from STK is T-Mobile
,08-31 18:49:36.770  2478  2615 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 18:49:36.773  4527  4527 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 18:49:36.774  4527  4527 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-31 18:49:36.774  4527  4527 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-31 18:49:36.774  4527  4527 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-31 18:49:36.774  4527  4527 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 18:49:36.774  4527  4527 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 18:49:36.774  4527  4527 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-31 18:49:36.774  4527  4527 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-31 18:49:36.774  4527  4527 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 18:49:36.774  4527  4527 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 18:49:36.774  4527  4527 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-31 18:49:36.774  4527  4527 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-31 18:49:36.783  2097  2097 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-31 18:49:36.784  1035  1035 D administrator: Handling package changes for user 0
08-31 18:49:36.789  4666  4666 I art     : Explicit concurrent mark sweep GC freed 8254(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 605us total 141.319ms
08-31 18:49:36.826  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-31 18:49:36.828  2097  2097 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-31 18:49:36.830  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-31 18:49:36.831  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 18:49:36.831  8094  8159 D LgDataFeature: LgDataFeature() Constructor: none
08-31 18:49:36.831  8094  8159 D LgDataFeature: LgDataFeature() Constructor Done, null
08-31 18:49:36.832  1605  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 18:49:36.832  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.833  1938  1938 D ActionManagerService: notifyUserLog: 1000004
08-31 18:49:36.834  3831  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , create_time: 1430832262123
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , expire_time: 0
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , display: false
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , animation: false }
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , create_time: 1430832262287
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , expire_time: 0
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , display: false
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , animation: false }
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , create_time: 1472216588858
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , expire_time: 0
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , display: false
08-31 18:49:36.834  2097  2097 I GBoardWebViewUtils: , animation: false }
,08-31 18:49:36.840  1898  1898 D SplitUIManager: split_name #11 / not available #0
08-31 18:49:36.841  1898  1898 D SplitUIService: removed split : 
08-31 18:49:36.842  1605  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 18:49:36.842  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.846  1605  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 18:49:36.847  1605  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 18:49:36.847  1605  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-31 18:49:36.848  1605  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 18:49:36.862  2097  2097 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-31 18:49:36.867  1898  1898 D SplitUIManager: split_name #11 / not available #0
,08-31 18:49:36.867  1898  1898 I SplitUIService: split app #11
08-31 18:49:36.870  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-31 18:49:36.870  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-31 18:49:36.872  1605  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 18:49:36.872  1605  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 18:49:36.873  1605  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 18:49:36.873  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.876  1605  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-31 18:49:36.876  1605  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-31 18:49:36.877  1035  2115 V SIM_STK : Menu title from STK is T-Mobile
08-31 18:49:36.877  1035  2115 V SIM_STK : Menu title from STK is T-Mobile
,08-31 18:49:36.904  8165  8165 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-31 18:49:36.905  8165  8165 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-31 18:49:36.905  8165  8165 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-31 18:49:36.905  8165  8165 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-31 18:49:36.905  8165  8165 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-31 18:49:36.906  8165  8165 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-31 18:49:36.922  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 18:49:36.923  1605  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 18:49:36.923  1605  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-31 18:49:36.923  1605  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 18:49:36.924  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.924  2097  2097 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-31 18:49:36.930  1605  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 18:49:36.930  1605  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 18:49:36.931  1605  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-31 18:49:36.931  1605  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 18:49:36.931  1605  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 18:49:36.931  1605  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 18:49:36.932  8165  8165 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-31 18:49:36.947  2097  8211 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-31 18:49:36.947  1605  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 18:49:36.947  1605  1649 D KeyguardModel: createShortcutInfo...
,08-31 18:49:36.953  1035  2096 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-31 18:49:36.954  7650  7650 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-31 18:49:36.955  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-31 18:49:36.955  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 18:49:36.958  1605  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-31 18:49:36.958  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.960  1605  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-31 18:49:36.960  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.961  1605  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 18:49:36.961  1605  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-31 18:49:36.962  1605  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-31 18:49:36.962  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.967  1605  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 18:49:36.967  1605  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-31 18:49:36.968  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-31 18:49:36.968  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 18:49:36.968  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 18:49:36.969  1035  1579 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-31 18:49:36.973  1605  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-31 18:49:36.973  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.974  1605  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 18:49:36.974  1605  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-31 18:49:36.974  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:36.976  1605  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-31 18:49:36.976  1605  1649 D KeyguardModel: createShortcutInfo...
08-31 18:49:36.977  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-31 18:49:36.977  1035  1782 V SIM_STK : Menu title from STK is T-Mobile
08-31 18:49:36.980  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-31 18:49:36.980  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-31 18:49:36.981  1035  1103 I art     : Explicit concurrent mark sweep GC freed 78845(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 8.465ms total 309.046ms
08-31 18:49:36.983  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:36.993  8165  8165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-31 18:49:36.995  8165  8165 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-31 18:49:36.997  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:36.999  8094  8160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 18:49:37.002  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 18:49:37.004  8165  8165 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-31 18:49:37.012  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.017  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.018  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:37.020  8165  8165 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-31 18:49:37.023  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-31 18:49:37.025  6853  6853 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-31 18:49:37.027  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:37.027  8094  8160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 18:49:37.032  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:37.039  8094  8159 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-31 18:49:37.041  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.048  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.049  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 18:49:37.050  8165  8165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:37.050  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-31 18:49:37.054  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 18:49:37.055  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-31 18:49:37.056  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-31 18:49:37.057  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-31 18:49:37.059  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-31 18:49:37.059  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-31 18:49:37.059  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-31 18:49:37.059  6853  6853 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-31 18:49:37.060  6853  6853 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-31 18:49:37.063  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-31 18:49:37.063  6853  6853 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-31 18:49:37.063  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-31 18:49:37.063  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-31 18:49:37.063  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-31 18:49:37.063  6853  6853 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-31 18:49:37.063  6853  6853 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-31 18:49:37.063  6853  6853 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-31 18:49:37.065  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:37.065  8094  8160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 18:49:37.070  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 18:49:37.073  1035  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e78a9e0 u0 com.lge.launcher2/.Launcher t5} time:216901
08-31 18:49:37.074  8094  8159 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-31 18:49:37.075  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-31 18:49:37.075  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 18:49:37.076  2097  2286 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-31 18:49:37.076  2097  2286 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-31 18:49:37.083  8094  8159 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-31 18:49:37.084  8094  8159 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 18:49:37.084  8094  8159 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-31 18:49:37.088  8094  8159 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-31 18:49:37.090  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-31 18:49:37.090  8094  8159 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-31 18:49:37.090  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 18:49:37.090  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 18:49:37.093  8094  8159 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-31 18:49:37.099  2097  2097 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-31 18:49:37.100  2666  2666 D [Concierge]Service: onStartCommand(). Type : 8
08-31 18:49:37.100  2666  2666 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-31 18:49:37.101  2666  2666 D [Concierge]Service: Update widget ID : 11
08-31 18:49:37.103  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.103  2097  2097 D [Concierge]WidgetView: change position of spinner
,08-31 18:49:37.106  2666  2666 D [Concierge]Service: onStartCommand(). Type : 0
08-31 18:49:37.107  2097  2097 I [Concierge]WidgetView: initWebView(). Time : 1472662177106
08-31 18:49:37.107  8094  8159 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-31 18:49:37.111  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.111  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:37.111  8165  8165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:37.113  8094  8160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 18:49:37.113  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:37.117  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:37.121  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.124  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.125  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:37.125  8165  8165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:37.127  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:37.128  8094  8160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-31 18:49:37.131  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 18:49:37.133  2097  2097 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 782426972
08-31 18:49:37.134  2097  2097 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-31 18:49:37.134  2097  2097 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 18:49:37.136  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.137  2097  2097 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@29b83068
08-31 18:49:37.137  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-31 18:49:37.139  2097  2097 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-31 18:49:37.139  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 18:49:37.141  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.142  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:37.142  8165  8165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:37.144  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:37.144  8094  8160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 18:49:37.145  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-31 18:49:37.145  2097  2097 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-31 18:49:37.145  2097  2097 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 18:49:37.156  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:37.156  2097  2097 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472661989026, New one : 1472662177106
08-31 18:49:37.156  2097  2097 D [Concierge]WidgetView: Unregister all receivers
08-31 18:49:37.156  2097  2097 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-31 18:49:37.157  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 18:49:37.158  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-31 18:49:37.159  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-31 18:49:37.160  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-31 18:49:37.161  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-31 18:49:37.162  8161  8161 D AndroidRuntime: Shutting down VM
08-31 18:49:37.164  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-31 18:49:37.165  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 18:49:37.165  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-31 18:49:37.170  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.177  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.178  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:37.178  8165  8165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-31 18:49:37.184  8094  8160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-31 18:49:37.188  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 18:49:37.202  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:37.212  2097  2097 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-31 18:49:37.219  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 18:49:37.221  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-31 18:49:37.225  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.225  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:37.226  2097  2097 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-31 18:49:37.226  2097  2097 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-31 18:49:37.227  2097  2097 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-31 18:49:37.228  8165  8165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:37.230  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-31 18:49:37.233  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-31 18:49:37.244  2097  2097 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-31 18:49:37.248  2097  2097 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1db2496d time:217076
08-31 18:49:37.251  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:37.265  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.269  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.269  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-31 18:49:37.270  8165  8165 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-31 18:49:37.271  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:37.274  8047  8047 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-31 18:49:37.277  8047  8047 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:37.278  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-31 18:49:37.281  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.295  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.296  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 18:49:37.297  8165  8165 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 18:49:37.298  8165  8165 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 18:49:37.298  8165  8165 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 18:49:37.302  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:37.306  8047  8047 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-31 18:49:37.307  8047  8047 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-31 18:49:37.309  6853  6853 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-31 18:49:37.314  6853  6853 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-31 18:49:37.319  8165  8165 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-31 18:49:37.319  8165  8165 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-31 18:49:37.320  8165  8165 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-31 18:49:37.321  8165  8165 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-31 18:49:37.322  8165  8165 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-31 18:49:37.326  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-31 18:49:37.331  8094  8094 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-31 18:49:37.340  1846  1846 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-31 18:49:37.349  2244  2244 I ConfigService: onCreate
08-31 18:49:37.350  2244  2244 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-31 18:49:37.351  1846  1846 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-31 18:49:37.356  2244  2244 I ConfigService: onBind returning update interface
08-31 18:49:37.356  2244  2244 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-31 18:49:37.356  2244  2244 I ConfigService: onBind returning config service
08-31 18:49:37.373  2244  2244 I ConfigService: onDestroy
,08-31 18:49:37.374  2097  2097 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-31 18:49:37.377  1846  8227 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-31 18:49:37.406  7031  7031 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-31 18:49:37.416  2097  2885 I GBoardtInterface: onReloaded()
08-31 18:49:37.417  2097  2097 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-31 18:49:37.431  1035  1103 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8231 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 18:49:37.434  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 18:49:37.445  3831  4510 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-31 18:49:37.453  5976  8248 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-31 18:49:37.457  1846  8251 I PeopleContactsSync: CP2 sync disabled
,08-31 18:49:37.459  2157  8252 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 18:49:37.490  1035  1782 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8255 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-31 18:49:37.492  1938  1938 D ActionManagerService: notifyUserLog: 1000001
08-31 18:49:37.500  1938  1938 D ActionManagerService: notifyUserLog: 1000001
08-31 18:49:37.500  3831  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-31 18:49:37.500  3831  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 18:49:37.502  3831  4514 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-31 18:49:37.502  3831  4514 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-31 18:49:37.502  1846  4818 I Icing   : doRemovePackageData com.test.thalitest
08-31 18:49:37.502  3831  4514 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-31 18:49:37.502  3831  4514 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-31 18:49:37.503  3831  3846 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-31 18:49:37.508  2097  2097 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-31 18:49:37.508  2097  2097 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-31 18:49:37.510  2097  2097 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-31 18:49:37.510  2097  2097 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-31 18:49:37.514  2097  2097 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-31 18:49:37.515  2097  2097 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-31 18:49:37.534  1035  2068 I ActivityManager: Killing 7232:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-31 18:49:37.551  8255  8255 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 18:49:37.552  8255  8255 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-31 18:49:37.552  8255  8255 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-31 18:49:37.553  8255  8255 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-31 18:49:37.624  1035  2091 W libprocessgroup: failed to open /acct/uid_10005/pid_7232/cgroup.procs: No such file or directory
,08-31 18:49:37.627  1846  8245 W GmsApplication: Using Auth Proxy for data requests.
08-31 18:49:37.628  8255  8255 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-31 18:49:37.630  1846  8245 W GmsApplication: Using Auth Proxy for data requests.
,08-31 18:49:37.636  1846  8245 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-31 18:49:37.636  1846  8245 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: Runtime exception while performing operation
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:135)
08-31 18:49:37.636  1846  8245 E ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at com.google.android.gms.common.d.a.delete(SourceFile:258)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:135)
08-31 18:49:37.637  1846  8245 F ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: Can't write: system_app_wtf
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 18:49:37.643  1035  8274 E DropBoxManagerService: 	... 5 more
08-31 18:49:37.644  8255  8255 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-31 18:49:37.654  2244  2364 I art     : Explicit concurrent mark sweep GC freed 6292(376KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 613us total 16.620ms
,08-31 18:49:37.668  8255  8255 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 18:49:37.680  1846  8229 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-31 18:49:37.681  1846  8229 E DriveAsyncService: disk I/O error (code 3850)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:438)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1384)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.al.a(SourceFile:15)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:135)
08-31 18:49:37.681  1846  8229 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
