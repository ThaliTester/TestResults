#### Test 757892680c366d1_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
07-01 12:10:00.073  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
07-01 12:10:00.083  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:10:00.083  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:10:00.086  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:10:00.087  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:10:45.596  6870  6870 D AndroidRuntime: 
07-01 12:10:45.596  6870  6870 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 12:10:45.598  6870  6870 D AndroidRuntime: CheckJNI is OFF
07-01 12:10:45.762  6870  6870 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-01 12:10:45.770  1036  2031 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 12:10:45.793  1968  1984 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
07-01 12:10:45.798  1036  2031 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
07-01 12:10:45.799  1036  2031 D ActivityManager: setTaskToReturnTo : TaskRecord{11d90ff0 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-01 12:10:45.799  1036  2031 D ActivityManager: setTaskToReturnTo : TaskRecord{11d90ff0 #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-01 12:10:45.801  1036  2031 D WindowStateEx: AppWindowTokenEx init.. 
07-01 12:10:45.802   349   369 E GBMv2   : DFP En is all cleared set to be enabled
07-01 12:10:45.834  1036  2031 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6891 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 12:10:45.837  6870  6870 D AndroidRuntime: Shutting down VM
07-01 12:10:45.850   385   385 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 354us total 19.373ms
07-01 12:10:45.867   385   385 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 326us total 15.636ms
07-01 12:10:45.868  1036  1036 V ActivityManager: Display changed displayId=0
07-01 12:10:45.876  1881  1881 D DSDPConnection: Display #0 changed.
07-01 12:10:45.882   385   385 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 266us total 14.013ms
07-01 12:10:45.899  1968  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
07-01 12:10:45.899  1968  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f8e3fce co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-01 12:10:45.900  1968  2475 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
07-01 12:10:45.900  1968  2475 D SplitWindowPolicy: topRunningActivity=ActivityInfo{e561eef co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
07-01 12:10:45.931  2090  2090 D BubblePopupHelper: isShowingBubblePopup : false
07-01 12:10:45.943  6891  6891 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-01 12:10:46.004  6891  6891 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
07-01 12:10:46.010  6891  6891 I LibraryLoader: Loading: webviewchromium
07-01 12:10:46.012  6891  6891 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3344-3346)
07-01 12:10:46.012  6891  6891 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:10:46.029  6891  6891 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d24beb9}
07-01 12:10:46.030  6891  6891 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:10:46.030  6891  6891 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 12:10:46.037  6891  6891 I BrowserStartupController: Initializing chromium process, renderers=0
07-01 12:10:46.038  6891  6891 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:10:46.048  6891  6891 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-01 12:10:46.048  6891  6891 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=33 off=46780 len=2953
07-01 12:10:46.049  6891  6891 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:34 off:229536 len:643667
,07-01 12:10:46.058   322  4000 V AudioPolicyService: registerClient() client 0xb558a620, uid 10118
07-01 12:10:46.061  1036  1097 D BluetoothManagerService: Message: 20
07-01 12:10:46.062  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24ea2cfa:true
,07-01 12:10:46.066  6891  6891 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:10:46.066  6891  6891 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:10:46.066  6891  6891 I Adreno-EGL: Build Date: 12/12/14 금
07-01 12:10:46.066  6891  6891 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 12:10:46.066  6891  6891 I Adreno-EGL: Remote Branch: 
07-01 12:10:46.066  6891  6891 I Adreno-EGL: Local Patches: 
07-01 12:10:46.066  6891  6891 I Adreno-EGL: Reconstruct Branch: 
07-01 12:10:46.146  6891  6920 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,07-01 12:10:46.153  6891  6891 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-01 12:10:46.171  6891  6891 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:10:46.177  6891  6891 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 12:10:46.181  6891  6891 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-01 12:10:46.184  6891  6891 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-01 12:10:46.184  6891  6891 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,07-01 12:10:46.201  6891  6891 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-01 12:10:46.208  6891  6891 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:10:46.208  6891  6891 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:10:46.239  6891  6932 D OpenGLRenderer: Render dirty regions requested: true
07-01 12:10:46.239  6891  6932 I OpenGLRenderer: Initialized EGL, version 1.4
07-01 12:10:46.249  6891  6932 D OpenGLRenderer: Enabling debug mode 0
,07-01 12:10:46.267  6891  6891 D Atlas   : Validating map...
,07-01 12:10:46.272  1036  2076 D SplitWindow: check instance of lgWin Window{209b0fe4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-01 12:10:46.306  6891  6930 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:10:46.306  6891  6930 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 12:10:46.436  1036  1098 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +537ms (total +633ms)
,07-01 12:10:46.438  6891  6891 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@346dc8dc time:273772
07-01 12:10:46.440  1036  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3fe71969 u0 com.test.thalitest/.MainActivity t12} time:273774
07-01 12:10:46.586  6891  6891 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-01 12:10:46.727  6891  6943 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
07-01 12:10:46.750  6891  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 12:10:46.750  6891  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 12:10:46.750  6891  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 12:10:46.750  6891  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 12:10:46.750  6891  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 12:10:46.751  6891  6943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c2d76e0 added. We now have 1 listener(s)
07-01 12:10:46.756  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:10:46.766  6891  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
07-01 12:10:46.769  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
07-01 12:10:46.770  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 12:10:46.771  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 12:10:46.779  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11d5b43f added. We now have 1 listener(s)
07-01 12:10:46.780  6891  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:10:46.784  1036  1544 D WifiService: New client listening to asynchronous messages
07-01 12:10:46.787  6891  6943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-01 12:10:46.791  6891  6943 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-01 12:10:46.791  6891  6943 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
07-01 12:10:46.797  6891  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 12:10:46.798  1036  2330 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:10:46.799  6891  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
07-01 12:10:46.808  6891  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:10:46.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:46.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:46.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:46.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:10:46.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:46.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:10:46.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:10:46.808  6891  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 12:10:46.808  6891  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 12:10:46.813  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:10:46.814  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:10:46.815  6891  6943 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 12:10:46.850  6891  6930 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
07-01 12:10:46.850  6891  6930 I chromium: 
07-01 12:10:46.917  6891  6891 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-01 12:10:47.004  6891  6891 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-01 12:10:47.004  6891  6891 I chromium: 
,07-01 12:10:47.452  1036  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=332534726, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-01 12:10:47.456  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1c9bb05a type 2 when 257408 android} when 257408
07-01 12:10:47.510  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,07-01 12:10:47.530  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=332534726 [*alarm*], flags=0x0
,07-01 12:10:47.616   349   371 E GBMv2   : DFP En is all cleared set to be enabled
07-01 12:10:47.616   349   371 E GBMv2   : Set value is all cleared set the max
07-01 12:10:47.616   349   371 I GBMv2   : DFP Enabled. Ignore VFP set
,07-01 12:10:47.822  6891  6946 W jxcore-log: Initializing JXcore engine
07-01 12:10:47.823  6891  6946 W jxcore-log: JXcore engine is ready
,07-01 12:10:47.853  6946  6946 W Thread-792: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9907]" dev="sockfs" ino=9907 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,07-01 12:10:47.853  6946  6946 W Thread-792: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-01 12:10:47.853  6946  6946 W Thread-792: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10492]" dev="sockfs" ino=10492 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
07-01 12:10:47.853  6946  6946 W Thread-792: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
07-01 12:10:47.853  6946  6946 W Thread-792: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31610]" dev="sockfs" ino=31610 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
07-01 12:10:47.876  6891  6946 W jxcore-log: Starting JXcore engine
,07-01 12:10:47.953  6891  6946 W jxcore-log: Platform android
07-01 12:10:47.953  6891  6946 W jxcore-log: 
07-01 12:10:47.953  6891  6946 W jxcore-log: Process ARCH arm
07-01 12:10:47.953  6891  6946 W jxcore-log: 
,07-01 12:10:48.186  6891  6946 I jxcore-log: JXcore Cordova bridge is ready!
07-01 12:10:48.186  6891  6946 I jxcore-log: 
07-01 12:10:48.187  6891  6946 W jxcore-log: JXcore engine is started
,07-01 12:10:48.191  6891  6943 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-01 12:10:48.194  6891  6891 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 12:10:58.288  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-01 12:10:58.288  6891  6946 I jxcore-log: 
,07-01 12:10:58.291  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-01 12:10:58.291  6891  6946 I jxcore-log: 
,07-01 12:10:58.295  6891  6946 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:10:58.295  6891  6946 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:58.295  6891  6946 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:58.295  6891  6946 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:58.295  6891  6946 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:10:58.295  6891  6946 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:58.295  6891  6946 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:10:58.295  6891  6946 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:10:58.297  6891  6946 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:58.300  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-01 12:10:58.300  6891  6946 I jxcore-log: 
07-01 12:10:58.301  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-01 12:10:58.301  6891  6946 I jxcore-log: 
,07-01 12:10:58.622  6891  6946 I jxcore-log: Unit Test app is loaded
07-01 12:10:58.622  6891  6946 I jxcore-log: 
,07-01 12:10:58.634  6891  6891 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-01 12:10:58.640  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:10:58.640  6891  6946 I jxcore-log: 
,07-01 12:10:58.650  6891  6946 I jxcore-log: My device name is: LGE-LG-D855
07-01 12:10:58.650  6891  6946 I jxcore-log: 
07-01 12:10:58.680  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:10:58.680  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d61f0c9 added. We now have 2 listener(s)
07-01 12:10:58.680  6891  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:10:58.689  6891  6943 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:10:58.689  6891  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:10:58.689  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:10:58.689  6891  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:10:58.690  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d61f0c9 removed from the list
07-01 12:10:58.691  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:10:58.691  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e86f3ce added. We now have 2 listener(s)
07-01 12:10:58.691  6891  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:10:58.695  6891  6943 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:10:58.695  6891  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:10:58.695  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:10:58.695  6891  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:10:58.695  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e86f3ce removed from the list
07-01 12:10:58.696  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:10:58.696  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d12c2ef added. We now have 2 listener(s)
07-01 12:10:58.696  6891  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:10:58.699  1036  2330 D WifiServiceImplEx: setWifiEnabled: false pid=6891, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 12:10:58.699  1036  2330 D WifiService: setWifiEnabled: false pid=6891, uid=10118
07-01 12:10:58.699  1036  2330 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-01 12:10:58.720  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:10:58.720  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:10:58.720  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 12:10:58.721  1036  1539 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
07-01 12:10:58.721  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
07-01 12:10:58.721  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-01 12:10:58.722  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-01 12:10:58.722  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-01 12:10:58.722  1036  1539 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-01 12:10:58.722  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 12:10:58.722  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-01 12:10:58.723  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-01 12:10:58.723  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-01 12:10:58.724  1036  2093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:10:58.724  1036  2093 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1da1b28b mBinding = false
07-01 12:10:58.734  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-01 12:10:58.734  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-01 12:10:58.734  2720  2720 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,07-01 12:10:58.735  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.735  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-01 12:10:58.735  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.735  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 12:10:58.735  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
07-01 12:10:58.736   318   902 D CommandListener: Clearing all IP addresses on wlan0
07-01 12:10:58.738  1036  2846 D DhcpStateMachine: RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.746  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:10:58.746  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:10:58.746  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 12:10:58.746  1036  1097 D BluetoothManagerService: Message: 2
,07-01 12:10:58.756  1036  1097 D BluetoothManagerService: Sending off request.
07-01 12:10:58.757  6891  6943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 12:10:58.763  3883  4010 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,07-01 12:10:58.767  3883  3969 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-01 12:10:58.767  3883  3969 D BluetoothAdapterProperties: Setting state to 13
07-01 12:10:58.767  3883  3969 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 12:10:58.767  3883  3969 D BluetoothAdapterProperties: onBluetoothDisable()
07-01 12:10:58.767  3883  3969 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-01 12:10:58.772  3883  3974 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:10:58.772  3883  3969 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-01 12:10:58.773  3883  3969 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 12:10:58.774  3883  4186 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 12:10:58.774  3883  4213 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 12:10:58.774  3883  4218 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-01 12:10:58.775  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-01 12:10:58.775  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
07-01 12:10:58.775  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
07-01 12:10:58.776  3883  4221 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 12:10:58.777  3883  4185 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
07-01 12:10:58.777  3883  4185 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-01 12:10:58.777  3883  4185 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
07-01 12:10:58.777  3883  4185 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
07-01 12:10:58.777  3883  4185 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
07-01 12:10:58.777  3883  4185 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
07-01 12:10:58.777  3883  4185 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
07-01 12:10:58.777  3883  4185 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
07-01 12:10:58.778  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-01 12:10:58.778  3883  4063 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-01 12:10:58.778  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:10:58.778  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:10:58.778  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:10:58.778  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:10:58.778  3883  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:10:58.779  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:10:58.779  3883  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:10:58.779  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:10:58.779  3883  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:10:58.779  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-01 12:10:58.779  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-01 12:10:58.779  3883  4063 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:10:58.792  1036  1036 D WifiHS20: hidePasspointNotification off =false
,07-01 12:10:58.796  1968  1968 V WfdStateTracker: handleWifiStateChangedEvent: 0
07-01 12:10:58.797  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:58.797  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:10:58.799  1036  1537 D LGWifiP2pService: InactiveState{ when=-24ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.799  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-25ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.799  1036  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@80de634
07-01 12:10:58.801  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:10:58.803  1036  1097 D BluetoothManagerService: Message: 60
07-01 12:10:58.803  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-01 12:10:58.805  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:10:58.806  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:10:58.806  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,07-01 12:10:58.808  6891  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:10:58.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:58.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:58.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:58.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:10:58.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:58.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:10:58.808  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:10:58.810  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-01 12:10:58.811  1036  1576 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
07-01 12:10:58.811  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.811  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.811  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-01 12:10:58.811  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.811  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
07-01 12:10:58.814  6891  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:58.814  6891  6943 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 12:10:58.816  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:10:58.816  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:58.816  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:58.816  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:58.816  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:10:58.816  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:10:58.816  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:10:58.816  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:10:58.817  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:10:58.820  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:10:58.822  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:10:58.822  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:58.822  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:58.822  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:58.822  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:10:58.822  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:10:58.822  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:10:58.822  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:10:58.822  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:10:58.823  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:10:58.830  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:10:58.830  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:10:58.830  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:10:58.831  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 12:10:58.832  1036  1036 D RttService: SCAN_AVAILABLE : 1
07-01 12:10:58.832  1036  1557 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.832  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:10:58.833  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.833  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-01 12:10:58.833  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:10:58.834  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:10:58.834  1036  1539 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-01 12:10:58.837  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:58.837  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:10:58.837  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:10:58.838  1036  1537 D LGWifiP2pService: P2pDisablingState
07-01 12:10:58.838  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-39ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.838  1036  1537 D LGWifiP2pService: p2p socket connection lost
07-01 12:10:58.838  1036  1537 D LGWifiP2pService: P2pDisabledState
07-01 12:10:58.840  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-01 12:10:58.840  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-01 12:10:58.840  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.840  1036  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.840  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-01 12:10:58.841  1968  1968 D WfdsService: WifiP2pState is changed : false
07-01 12:10:58.841  1968  2319 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-01 12:10:58.841  1968  2319 D WfdsService: Set the WFDS Monitor: false
07-01 12:10:58.841  1968  1968 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:58.841  1968  2319 D WfdsMonitor: WFDS Monitor is stopped
07-01 12:10:58.841  1968  2755 D CtrlSupplicant: Received on exit socket, terminate
07-01 12:10:58.841  1968  2755 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-01 12:10:58.841  1968  2319 D WfdsService: STATE : WfdsDisabledState - enter
07-01 12:10:58.841  1968  2755 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-01 12:10:58.841  1968  2755 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-01 12:10:58.841  1968  2319 W WfdsService: DefaultState - msg [9445378] is not handled
07-01 12:10:58.842  2720  2720 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,07-01 12:10:58.844  3883  3883 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:10:58.844  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-01 12:10:58.844  3883  3883 D BluetoothMapService: STATE_TURNING_OFF
07-01 12:10:58.844  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 12:10:58.844  3883  3883 V BluetoothMapService: Handler(): got msg=4
07-01 12:10:58.844  3883  3883 D BluetoothMapService: MAP Service closeService in
07-01 12:10:58.844  3883  3883 D BluetoothMapMasInstance: MAP Service shutdown
07-01 12:10:58.844  3883  3883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:10:58.844  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
07-01 12:10:58.844  3883  3883 V BluetoothMapService: MAP Service closeService out
07-01 12:10:58.845  3883  3883 V BtOppService: Receiver DISABLED_ACTION 
07-01 12:10:58.845  3883  3883 I BtOppRfcommListener: stopping Accept Thread
07-01 12:10:58.845  1968  2320 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-01 12:10:58.845  3883  3883 V BtOppRfcommListener: close mBtServerSocket
07-01 12:10:58.845  3883  3883 V BtOppRfcommListener: waiting for thread to terminate
07-01 12:10:58.845  3883  4213 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-01 12:10:58.846  3883  3883 V BtOppRfcommListener: done waiting for thread to terminate
07-01 12:10:58.854   318   902 D CommandListener: Clearing all IP addresses on wlan0
07-01 12:10:58.855   318  6963 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-01 12:10:58.856  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,07-01 12:10:58.857  1036  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
07-01 12:10:58.857  1036  1545 D DSQN    : disableDataServiceNotify
07-01 12:10:58.857  1036  1545 D DSQN    : stop dsqn bin
07-01 12:10:58.858  1036  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-01 12:10:58.860  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 12:10:58.885  1036  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-01 12:10:58.885  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:58.885  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:10:58.885  1036  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:10:58.886  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
07-01 12:10:58.886  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.886  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:58.886  1036  2844 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-01 12:10:58.886  1036  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
07-01 12:10:58.887  1036  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-01 12:10:58.887  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 12:10:58.887  1603  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-01 12:10:58.889  1036  1093 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-01 12:10:58.896  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:10:58.896  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-01 12:10:58.898  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-01 12:10:58.899  3883  3883 V BtOppService: onDestroy
07-01 12:10:58.901  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-01 12:10:58.901  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-01 12:10:58.901  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-01 12:10:58.901  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-01 12:10:58.904  3883  3883 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
07-01 12:10:58.905  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:10:58.905  1036  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:58.905  1036  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:58.906  1036  1545 D NetworkManagementService: Removing idletimer
07-01 12:10:58.906  1036  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
07-01 12:10:58.906  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
07-01 12:10:58.906  1036  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:10:58.906  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-01 12:10:58.906  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-01 12:10:58.906  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-01 12:10:58.906  1881  1881 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:58.907  1036  1539 D WifiNative-p2p0: doBoolean: TERMINATE
07-01 12:10:58.907  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-01 12:10:58.907  1036  1539 D WifiNative-p2p0: TERMINATE: returned true
07-01 12:10:58.907  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 12:10:58.907  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
07-01 12:10:58.907  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 12:10:58.908  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-01 12:10:58.909  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:10:58.909  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:10:58.909  1036  1539 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:58.909  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:10:58.909  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-01 12:10:58.910  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-01 12:10:58.912  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-01 12:10:58.913  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 12:10:58.913  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
07-01 12:10:58.915  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:10:58.915  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:58.915  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:58.915  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:10:58.915  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:10:58.915  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:10:58.915  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:10:58.915  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:10:58.918  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:10:58.919  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:10:58.927  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:10:58.927  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:58.927  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:58.927  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:10:58.927  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:10:58.927  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:10:58.927  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:10:58.927  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:10:58.931  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:10:58.940  1036  1737 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6984 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-01 12:10:58.960  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-01 12:10:58.960  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:10:58.961  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:10:58.963  6966  6966 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:10:58.963  6966  6966 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-01 12:10:58.964  6966  6966 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:10:58.964  6966  6966 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
07-01 12:10:58.965  6966  6966 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 12:10:58.966  6966  6966 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-01 12:10:58.985  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-01 12:10:58.986  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:10:58.986  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:10:58.986  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 12:10:58.986  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:10:58.987  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 12:10:59.018  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,07-01 12:10:59.020  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:10:59.024  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:10:59.025  1036  1985 I ActivityManager: Killing 5994:com.lge.appbox.client/u0a11 (adj 15): empty #17
07-01 12:10:59.035  1036  2846 D DhcpStateMachine: StoppedState
,07-01 12:10:59.035  1036  2846 D DhcpStateMachine: StoppedState{ when=-191ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:59.045  2720  2720 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-01 12:10:59.046  2720  2720 I wpa_supplicant: monitor socket send errors count : 1
07-01 12:10:59.046  2720  2720 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1968-2\x00 that cannot receive messages
07-01 12:10:59.046  1036  2754 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-01 12:10:59.046  1036  2754 D WifiMonitor: Dropping event because (p2p0) is stopped
07-01 12:10:59.048  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:10:59.053  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-01 12:10:59.083  2720  2720 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-01 12:10:59.083  2720  2720 W wpa_supplicant: USIM:  scard_deinit function
07-01 12:10:59.083  1036  2754 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
07-01 12:10:59.083  1036  2754 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-01 12:10:59.083  1036  2754 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-01 12:10:59.084  1036  2754 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
07-01 12:10:59.084  1036  2754 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 12:10:59.084  1036  2754 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 12:10:59.084  1036  1539 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=286404
07-01 12:10:59.084  1036  1097 D Tethering: InitialState.processMessage what=4
07-01 12:10:59.084  1036  1539 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=286404
07-01 12:10:59.085  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286405  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-01 12:10:59.085  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286405  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
07-01 12:10:59.135  1036  1051 W libprocessgroup: failed to open /acct/uid_10011/pid_5994/cgroup.procs: No such file or directory
,07-01 12:10:59.142  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
07-01 12:10:59.142  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 12:10:59.143  1036  1539 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
07-01 12:10:59.146  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:10:59.146  3883  3883 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:10:59.146  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:10:59.146  3883  3883 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.146  3883  3883 V BluetoothPbapReceiver: ***********state = 13
07-01 12:10:59.150  3883  3883 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,07-01 12:10:59.153  3883  3883 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.153  3883  3883 V BluetoothPbapService: state: 13
07-01 12:10:59.153  3883  3883 V BluetoothPbapService: Pbap Service closeService in
07-01 12:10:59.157  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 12:10:59.159  2225  2225 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 12:10:59.160  3883  3883 V BluetoothPbapService: successfully stopped pbap service
07-01 12:10:59.160  3883  3883 V BluetoothPbapService: Pbap Service closeService out
07-01 12:10:59.160  3883  3883 V BluetoothPbapService: Pbap Service onDestroy
07-01 12:10:59.160  3883  3883 V BluetoothPbapService: Pbap Service closeService in
07-01 12:10:59.161  3883  3883 V BluetoothPbapService: Pbap Service closeService out
07-01 12:10:59.161  3883  3883 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-01 12:10:59.189  6966  6966 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 12:10:59.189  6966  6966 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 12:10:59.197  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:10:59.206  1036  1097 D BluetoothManagerService: Message: 20
,07-01 12:10:59.206  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f7ff0b2:true
07-01 12:10:59.217  1036  1097 D BluetoothManagerService: Message: 30
,07-01 12:10:59.221  1036  1097 D BluetoothManagerService: Message: 30
07-01 12:10:59.224  6966  6966 D LocalBluetoothProfileManager: Adding local MAP profile
07-01 12:10:59.226  6966  6966 D BluetoothMap: Create BluetoothMap proxy object
07-01 12:10:59.226  1036  1097 D BluetoothManagerService: Message: 30
07-01 12:10:59.231  1036  1097 D BluetoothManagerService: Message: 30
,07-01 12:10:59.233  6966  6966 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-01 12:10:59.234  6966  6966 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-01 12:10:59.246  2720  2720 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-01 12:10:59.246  1036  2754 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-01 12:10:59.246  1036  2754 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
07-01 12:10:59.247  1036  2754 D WifiMonitor: Disconnecting from the supplicant, no more events
,07-01 12:10:59.247  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
07-01 12:10:59.256  6966  6966 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
07-01 12:10:59.260  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,07-01 12:10:59.271  6966  6966 D DockEventReceiver: finishStartingService: stopping service
07-01 12:10:59.279  6966  6966 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-01 12:10:59.282  6966  6966 D BluetoothInputDevice: Proxy object connected
07-01 12:10:59.283  6966  6966 D HidProfile: Bluetooth service connected
07-01 12:10:59.284  6966  6966 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 12:10:59.286  6966  6966 D PanProfile: Bluetooth service connected
07-01 12:10:59.287  6966  6966 D BluetoothMap: Proxy object connected
07-01 12:10:59.287  6966  6966 D MapProfile: Bluetooth service connected
07-01 12:10:59.287  6966  6966 D BluetoothMap: getConnectedDevices()
07-01 12:10:59.288  6966  6966 D BluetoothMap: Bluetooth is Not enabled
07-01 12:10:59.288  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-01 12:10:59.289  6966  6966 D BluetoothPermissionRequest: onReceive
07-01 12:10:59.291  6966  6966 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-01 12:10:59.301  1036  2031 I ActivityManager: Killing 6017:com.android.contacts/u0a19 (adj 15): empty #17
07-01 12:10:59.303  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-01 12:10:59.399  3883  3883 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,07-01 12:10:59.399  1036  2332 W libprocessgroup: failed to open /acct/uid_10019/pid_6017/cgroup.procs: No such file or directory
,07-01 12:10:59.399  3883  3883 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,07-01 12:10:59.403  3883  3883 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-01 12:10:59.409  1036  1539 D WifiOffDelayIfNotUsed: stopMonitoring
07-01 12:10:59.409  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 12:10:59.409  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
07-01 12:10:59.409  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 12:10:59.414  1968  1968 D WfdsService: Supplicant Connection state is changed : false
07-01 12:10:59.414  1968  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,07-01 12:10:59.414  1968  2319 D WfdsService: Set the WFDS Monitor: false
07-01 12:10:59.414  1968  2319 D WfdsMonitor: WFDS Monitor is stopped
07-01 12:10:59.416  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-01 12:10:59.416  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:10:59.419  2498  2498 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:10:59.421  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-01 12:10:59.421  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-01 12:10:59.421  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-01 12:10:59.421  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:10:59.424  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:10:59.484  1036  2031 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7016 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
07-01 12:10:59.487  3883  3883 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.487  3883  3883 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,07-01 12:10:59.488  3883  3883 V BluetoothFtpService: Ftp Service onStartCommand
07-01 12:10:59.488  3883  3883 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.488  3883  3883 V BluetoothFtpService: Ftp Service closeService
,07-01 12:10:59.489  3883  3883 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
07-01 12:10:59.490  3883  3883 V BluetoothFtpService: successfully stopped ftp service
07-01 12:10:59.490  3883  3883 V BluetoothFtpService: Ftp Service onDestroy
07-01 12:10:59.490  3883  3883 V BluetoothFtpService: Ftp Service closeService
07-01 12:10:59.493  3883  3883 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:10:59.493  3883  3883 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 12:10:59.493  3883  3883 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 12:10:59.493  3883  3883 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.493  3883  3883 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-01 12:10:59.493  3883  3883 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-01 12:10:59.495  3883  3883 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.495  3883  3883 V BluetoothSapService: state: 13
07-01 12:10:59.495  3883  3883 V BluetoothSapService: Stopping SAP server process
07-01 12:10:59.496  3883  3883 V BluetoothSapService: Sap Service closeSapService in
07-01 12:10:59.496  3883  3883 V BluetoothSapService: Close listen Socket : 
07-01 12:10:59.496  3883  3883 V BluetoothSapService: Close rfcomm Socket : 
07-01 12:10:59.496  3883  3883 V BluetoothSapService: Close sapd  Socket : 
07-01 12:10:59.497  3883  3883 V BluetoothSapService: Sap Service closeSapService out
07-01 12:10:59.497  3883  3883 V BluetoothSapService: Sap Service onDestroy
07-01 12:10:59.497  3883  3883 V BluetoothSapService: Sap Service closeSapService in
07-01 12:10:59.497  3883  3883 V BluetoothSapService: Close listen Socket : 
07-01 12:10:59.497  3883  3883 V BluetoothSapService: Close rfcomm Socket : 
,07-01 12:10:59.497  3883  3883 V BluetoothSapService: Close sapd  Socket : 
07-01 12:10:59.498  3883  3883 V BluetoothSapService: Sap Service closeSapService out
07-01 12:10:59.544  1036  2031 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7037 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,07-01 12:10:59.563  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{332ebce5 type 2 when 286883 com.google.android.gms} when 286883,
,07-01 12:10:59.567  7016  7016 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-01 12:10:59.599  7037  7037 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:10:59.609  1036  1051 I ActivityManager: Killing 6473:com.lge.email/u0a23 (adj 15): empty #17
,07-01 12:10:59.777  1036  1576 W libprocessgroup: failed to open /acct/uid_10023/pid_6473/cgroup.procs: No such file or directory
,07-01 12:10:59.784  7016  7016 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
07-01 12:10:59.786  3883  3974 D bt_hci_bdroid: cleanup
07-01 12:10:59.786  3883  4063 W bt-btif : ag scb idx 1 not allocated
07-01 12:10:59.786  3883  4063 E bt-btif : BTA AG is already disabled, ignoring ...
07-01 12:10:59.786  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:10:59.786  3883  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:10:59.786  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:10:59.787  3883  4063 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:10:59.787  3883  4063 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:10:59.788  3883  4169 I bt_userial_mct: exiting userial_read_thread
07-01 12:10:59.788  3883  4169 D bt_userial_mct: Leaving userial_evt_read_thread()
07-01 12:10:59.788  3883  3974 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-01 12:10:59.788  3883  4066 I bt_lpm  : LPM is already off!!!
07-01 12:10:59.789  3883  4066 I bt_vendor: hw_epilog_process
07-01 12:10:59.789  3883  3974 D bt_hci_bdroid: cleanup Finalizing cleanup
07-01 12:10:59.789  3883  3974 D bt_userial_mct: userial_close
07-01 12:10:59.789  3883  3974 E bt_userial_mct: pthread_join() FAILED result:3
07-01 12:10:59.789  3883  3974 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-01 12:10:59.817  1036  2076 D WifiServiceImplEx: setWifiEnabled: true pid=6891, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,07-01 12:10:59.819  1036  2076 D WifiService: setWifiEnabled: true pid=6891, uid=10118
07-01 12:10:59.819  1036  2076 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-01 12:10:59.832  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:10:59.833  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:10:59.833  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-01 12:10:59.835  1036  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-01 12:10:59.835  1036  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-01 12:10:59.838  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-01 12:10:59.838  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-01 12:10:59.838  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-01 12:10:59.838  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-01 12:10:59.838  1036  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-01 12:10:59.838  1036  1539 E WifiHW  : unknown target_country: EU , set to default
07-01 12:10:59.838  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-01 12:10:59.838  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-01 12:10:59.838  1036  1539 I WifiUtil: gEnableBmps=1
07-01 12:10:59.854  7016  7016 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
07-01 12:10:59.854  7016  7016 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
07-01 12:10:59.855  7016  7016 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
07-01 12:10:59.856  7016  7016 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
07-01 12:10:59.856  7016  7016 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,07-01 12:10:59.860  7016  7016 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
07-01 12:10:59.870  7016  7016 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,07-01 12:10:59.882  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-01 12:10:59.888  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:10:59.905  7016  7016 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,07-01 12:10:59.907  7016  7016 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
07-01 12:10:59.908  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:10:59.911  7016  7016 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
07-01 12:10:59.911  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 12:10:59.911  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:10:59.911  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:10:59.914  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:10:59.920  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:10:59.925  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:10:59.925  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:10:59.926  7016  7016 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 12:10:59.929  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-01 12:10:59.935  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 12:10:59.935  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:10:59.935  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:10:59.938  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:10:59.943  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:10:59.948  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:10:59.949  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:10:59.950  7016  7016 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 12:10:59.957  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 12:10:59.959  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:10:59.965  3883  3974 D bt_hci_bdroid: set_power 0
07-01 12:10:59.965  3883  3974 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
07-01 12:10:59.965  3883  3974 I bt_vendor: bluetooth satus is on
07-01 12:10:59.965  3883  3974 I bt_vendor: bt-vendor : resetting BT status
07-01 12:10:59.965  3883  3974 I bt_vendor: Starting hciattach daemon
07-01 12:10:59.965  3883  3974 I bt_vendor: try to set false
07-01 12:10:59.966  3883  3974 I bt_vendor: Starting hciattach daemon
07-01 12:10:59.966  3883  3974 I bt_vendor: try to set false
07-01 12:10:59.967  3883  3974 I bt_vendor: cleanup
07-01 12:10:59.968  3883  4063 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-01 12:10:59.968  3883  3974 I GKI_LINUX: GKI_exit_task 0 done
07-01 12:10:59.968  3883  3974 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-01 12:10:59.969  3883  3969 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 12:10:59.971  3883  3883 D HeadsetService: Received stop request...Stopping profile...
07-01 12:10:59.972  3883  3883 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 12:10:59.973  3883  3883 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:10:59.973  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26d7c2fe
07-01 12:10:59.973  3883  3993 D HeadsetStateMachine: Exit Disconnected: -1
07-01 12:10:59.975  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-01 12:10:59.976  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 12:10:59.976  1881  1881 D BluetoothHeadset: Proxy object disconnected
07-01 12:10:59.976  1881  1881 D BluetoothHeadset: Proxy object disconnected
07-01 12:10:59.976  1881  1881 D BluetoothHeadset: Proxy object disconnected
07-01 12:10:59.978  3883  3883 D A2dpService: Received stop request...Stopping profile...
07-01 12:10:59.978  3883  4040 D A2dpStateMachine: Exit Disconnected: -1
,07-01 12:10:59.982  3883  3969 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 12:10:59.982  3883  3883 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
07-01 12:10:59.983  3883  3883 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-01 12:10:59.983  3883  3883 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:10:59.983  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26d7c2fe
07-01 12:10:59.984  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-01 12:10:59.984  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-01 12:10:59.986  3883  3883 D HidService: Received stop request...Stopping profile...
07-01 12:10:59.986  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26d7c2fe
07-01 12:10:59.988  3883  3883 D HealthService: Received stop request...Stopping profile...
07-01 12:10:59.988  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26d7c2fe
07-01 12:10:59.989  3883  3883 D HeadsetStateMachine: Unbinding service...
07-01 12:10:59.990  3883  3883 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:10:59.990  3883  3883 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:10:59.990  3883  3883 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:10:59.990  3883  3883 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:10:59.990  3883  3883 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 12:10:59.990  3883  3883 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:10:59.990  3883  3883 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 12:10:59.991  3883  3883 D PanService: Received stop request...Stopping profile...
07-01 12:10:59.991  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26d7c2fe
07-01 12:10:59.991  3883  3883 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-01 12:10:59.992  3883  3883 D BtGatt.GattService: Received stop request...Stopping profile...
07-01 12:10:59.992  3883  3883 D BtGatt.GattService: stop()
07-01 12:10:59.992  3883  3883 D BtGatt.AdvertiseManager: advertise clients cleared
07-01 12:10:59.993  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26d7c2fe
07-01 12:10:59.996  3883  3883 D BluetoothMapService: Received stop request...Stopping profile...
07-01 12:10:59.996  3883  3883 D BluetoothMapService: stop()
07-01 12:10:59.997  3883  3883 D BluetoothMapEmailAppObserver: deinitObservers()
07-01 12:10:59.997  3883  3883 D BluetoothMapEmailAppObserver: removeReceiver()
07-01 12:10:59.998  3883  3883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26d7c2fe
07-01 12:10:59.998  3883  3883 I BluetoothA2dpServiceJni: cleanupNative
07-01 12:10:59.998  3883  4043 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 12:10:59.999  3883  3883 I GKI_LINUX: GKI_exit_task 2 done
07-01 12:10:59.999  3883  3883 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-01 12:10:59.999  3883  3883 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 12:10:59.999  3883  3883 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 12:10:59.999  3883  3883 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 12:10:59.999  3883  3883 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:10:59.999  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:10:59.999  3883  3883 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:10:59.999  3883  3883 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 12:10:59.999  3883  3883 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-01 12:11:00.000  3883  3883 V BluetoothMapService: Handler(): got msg=4
07-01 12:11:00.000  3883  3883 D BluetoothMapService: MAP Service closeService in
07-01 12:11:00.000  3883  3883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:11:00.000  3883  3883 V BluetoothMapService: MAP Service closeService out
07-01 12:11:00.000  3883  3883 D BluetoothMapService: cleanup()
07-01 12:11:00.000  3883  3883 D BluetoothMapService: MAP Service closeService in
07-01 12:11:00.000  3883  3883 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:11:00.000  3883  3883 V BluetoothMapService: MAP Service closeService out
07-01 12:11:00.000  3883  3969 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-01 12:11:00.000  3883  3969 D BluetoothAdapterProperties: Setting state to 10
07-01 12:11:00.001  3883  3969 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 12:11:00.001  1036  1097 D BluetoothManagerService: Message: 60
07-01 12:11:00.001  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,07-01 12:11:00.001  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-01 12:11:00.001  3883  3969 I BluetoothAdapterState: Entering OffState
07-01 12:11:00.008  6966  6966 D BluetoothInputDevice: Proxy object disconnected
07-01 12:11:00.008  6966  6966 D HidProfile: Bluetooth service disconnected
07-01 12:11:00.009  1881  3996 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:11:00.009  6966  6966 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 12:11:00.009  6966  6966 D PanProfile: Bluetooth service disconnected
07-01 12:11:00.009  6966  6966 D BluetoothMap: Proxy object disconnected
07-01 12:11:00.009  6966  6966 D MapProfile: Bluetooth service disconnected
07-01 12:11:00.010  1881  3997 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:11:00.011  6966  6981 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-01 12:11:00.012  6966  6982 D BluetoothPan: onBluetoothStateChange on: false
07-01 12:11:00.012  6966  6981 D BluetoothMap: onBluetoothStateChange: up=false
07-01 12:11:00.013  6966  6982 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 12:11:00.013  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:11:00.014  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:11:00.014  1881  2562 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:11:00.015  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-01 12:11:00.015  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
07-01 12:11:00.016  6748  7066 V FormManager: Network unavailable.
07-01 12:11:00.018  1036  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-01 12:11:00.018  1036  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-01 12:11:00.018  1036  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1da1b28b mBinding = false
07-01 12:11:00.018  1036  1097 D BluetoothManagerService: Sending unbind request.
,07-01 12:11:00.021  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-01 12:11:00.022  1968  1968 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:00.022  1968  2179 D LGBluetoothAPIService: Message: 2
07-01 12:11:00.023  1968  2179 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@33f22dfc mBinding = false
07-01 12:11:00.023  1968  2179 D LGBluetoothAPIService: Sending unbind request.
07-01 12:11:00.023  2225  2225 I Coffee - BluetoothConnectionTracker: Bluetooth adapter off, revoking trust
07-01 12:11:00.025  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 12:11:00.026  3883  3974 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-01 12:11:00.027  3883  3883 I GKI_LINUX: GKI_exit_task 1 done
07-01 12:11:00.027  3883  3883 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-01 12:11:00.027  3883  3883 I BluetoothServiceJni: cleanupNative: return from cleanup
07-01 12:11:00.027  3883  3883 I art     : --- WEIRD: removing null entry 246
07-01 12:11:00.027  3883  3883 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
07-01 12:11:00.027  3883  3883 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-01 12:11:00.027  3883  3883 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-01 12:11:00.029  3883  3883 I art     : System.exit called, status: 0
07-01 12:11:00.029  3883  3883 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-01 12:11:00.029  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 12:11:00.030  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 12:11:00.030  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 12:11:00.030  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-01 12:11:00.031  1603  1603 D BluetoothAdapter: 739472408: getState() :  mService = null. Returning STATE_OFF
07-01 12:11:00.031  1603  1603 D BluetoothAdapter: 739472408: getState() :  mService = null. Returning STATE_OFF
07-01 12:11:00.033  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 12:11:00.043  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 12:11:00.043  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,07-01 12:11:00.045  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 12:11:00.045  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 12:11:00.045  6748  7066 V FormManager: Network unavailable.
07-01 12:11:00.045  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 12:11:00.045  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 12:11:00.046  6966  6966 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 12:11:00.047  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-01 12:11:00.047  6966  6966 D LGBluetoothEventManager: [BTUI] clear device connection state
07-01 12:11:00.048  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 12:11:00.049  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:11:00.049  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:11:00.049  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:11:00.049  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
07-01 12:11:00.026  6748  7065 W FormManager: Network not available. Please check & try again.
07-01 12:11:00.049  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:11:00.049  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:11:00.050  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:11:00.050  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:11:00.052   322  1390 V AudioFlinger: 3883 died, releasing its sessions
07-01 12:11:00.052   322  1390 V AudioFlinger:  pid 1881 @ 0
07-01 12:11:00.052   322  1390 V AudioFlinger:  pid 3424 @ 1
07-01 12:11:00.052   322  1390 V AudioFlinger:  pid 3424 @ 2
07-01 12:11:00.052   322  1390 V AudioFlinger:  pid 1036 @ 3
07-01 12:11:00.054  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:11:00.054  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,07-01 12:11:00.056  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:00.155  1036  1052 I ActivityManager: Process com.android.bluetooth (pid 3883) has died
,07-01 12:11:00.156  1036  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
07-01 12:11:00.163  6966  6966 D DockEventReceiver: finishStartingService: stopping service
07-01 12:11:00.165  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-01 12:11:00.172  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:00.173  2225  2225 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:00.179  4321  7075 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 12:11:00.185  4321  7076 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:11:00.185  4321  7076 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:11:00.203  6748  7078 W FormManager: Network not available. Please check & try again.
,07-01 12:11:00.209  6984  6984 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-01 12:11:00.210  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:11:00.210  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:11:00.211  6966  6966 D BluetoothPermissionRequest: onReceive
07-01 12:11:00.211  6748  7079 V FormManager: Network unavailable.
,07-01 12:11:00.214  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:00.220  6748  7079 V FormManager: Network unavailable.
07-01 12:11:00.221  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:00.222  6966  6966 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 12:11:00.223  6966  6966 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-01 12:11:00.224  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 12:11:00.264  1036  1052 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7080 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-01 12:11:00.288  7016  7016 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,07-01 12:11:00.288   318  7097 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
07-01 12:11:00.289  1036  1095 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-01 12:11:00.295  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-01 12:11:00.296  7016  7016 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,07-01 12:11:00.320  7080  7080 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-01 12:11:00.320  7080  7080 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:11:00.320  7080  7080 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-01 12:11:00.321  7080  7080 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-01 12:11:00.335  7080  7080 D BluetoothAdapterApp: Loading JNI Library
,07-01 12:11:00.340  7016  7016 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:00.340  7016  7016 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 12:11:00.347  7016  7016 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
07-01 12:11:00.352  7016  7016 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
07-01 12:11:00.352  7016  7016 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
07-01 12:11:00.352  7016  7016 V SoundPool: doLoad: loading sample sampleID=1
07-01 12:11:00.352  7016  7101 V SoundPool: Start decode
07-01 12:11:00.352  7016  7101 V MediaPlayer[Native]: decode(30, 10857164, 17813)
07-01 12:11:00.353   322  1390 V MediaPlayerService: decode(26, 10857164, 17813)
07-01 12:11:00.353   322  1390 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
07-01 12:11:00.353   322  1390 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
07-01 12:11:00.353   322  1390 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
07-01 12:11:00.353   322  1390 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
07-01 12:11:00.353   322  1390 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
07-01 12:11:00.353   322  1390 V MediaPlayerService: player type = 3
07-01 12:11:00.353   322  1390 V AwesomePlayer: AwesomePlayer create()
07-01 12:11:00.353   322  1390 V AwesomePlayer: reset_l() 
07-01 12:11:00.353   322  1390 V AwesomePlayer: cancelPlayerEvents
07-01 12:11:00.353   322  1390 V AwesomePlayer: setAudioSink() 
07-01 12:11:00.353  7016  7016 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
07-01 12:11:00.353   322  1390 V AwesomePlayer: reset_l() 
07-01 12:11:00.353   322  1390 V AudioCache: notify(0xb54745c0, 8, 0, 0)
07-01 12:11:00.353   322  1390 V AudioCache: ignored
07-01 12:11:00.353   322  1390 V AwesomePlayer: cancelPlayerEvents
07-01 12:11:00.353   322  1390 D Utils   : printFileName fd(28) -> /data/preload/LGQRemote/LGQRemote.apk
07-01 12:11:00.353   322  1390 V AwesomePlayer: setDataSource_l dataSource
07-01 12:11:00.353   322  1390 V LGParserOSAL: SniffLGParser start
07-01 12:11:00.353   322  1390 V LGParserOSAL: MainType:5, SubType=0
07-01 12:11:00.353   322  1390 V LGParserOSAL: #### check Mime : application/ogg
07-01 12:11:00.353   322  1390 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
07-01 12:11:00.353   322  1390 E MediaExtractor: Use LGExtractor :application/ogg 
07-01 12:11:00.357  6590  6590 D UEI.SmartControl: QS Service created
,07-01 12:11:00.369  6590  6590 I UEI.SmartControl: Service initServices...
07-01 12:11:00.369  6590  6590 D UEI.SmartControl: QS start get config
07-01 12:11:00.373  7016  7016 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
07-01 12:11:00.389   322  1390 V LGParserOSAL: supported mime: application/ogg
07-01 12:11:00.389   322  1390 V AwesomePlayer: setDataSource_l() extractor countTracks=1
07-01 12:11:00.389   322  1390 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
07-01 12:11:00.389   322  1390 V AwesomePlayer: mBitrate = -1 bits/sec
07-01 12:11:00.389   322  1390 V AwesomePlayer: AudioTrack Setting
07-01 12:11:00.389   322  1390 V AwesomePlayer: AudioTrack Setting channelCount = 2
07-01 12:11:00.389   322  1390 V AwesomePlayer: setAudioSource() 
07-01 12:11:00.389   322  1390 V MediaPlayerService: prepare
07-01 12:11:00.389   322  1390 V AwesomePlayer: prepareAsync_l() 
07-01 12:11:00.389   322  1390 V MediaPlayerService: wait for prepare
07-01 12:11:00.390   322  7102 V AwesomePlayer: onPrepareAsyncEvent() 
07-01 12:11:00.390   322  7102 V AwesomePlayer: initAudioDecoder() 
07-01 12:11:00.390   322  7102 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-01 12:11:00.390   322  7102 V AudioSystem: isOffloadSupported()
07-01 12:11:00.390   322  7102 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-01 12:11:00.390   322  7102 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-01 12:11:00.390   322  7102 I AudioFlinger: isAudioPlaybackHookOn() false
07-01 12:11:00.390   322  7102 V AwesomePlayer: getUseOffload() = 0 
07-01 12:11:00.390   322  7102 V OMXCodec: OMXCodec::Create
07-01 12:11:00.390   322  7102 V OMXCodec: findMatchingCodecs()
07-01 12:11:00.390   322  7102 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
07-01 12:11:00.390   322  7102 V OMXCodec: matchingCodecs.size()=1
07-01 12:11:00.390   322  7102 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,07-01 12:11:00.391   322  7102 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
07-01 12:11:00.391   322  7102 V LGCodecAdapter: LG Codec Adapter start
07-01 12:11:00.392   322  7102 V OMXCodec: OMXCodec Createtor
07-01 12:11:00.392   322  7102 V OMXCodec: setComponentRole
07-01 12:11:00.392   322  7102 V OMXCodec: configureCodec protected=0
07-01 12:11:00.392   322  7102 V LGCodecAdapter: called getLGCodecSpecificData
07-01 12:11:00.392   322  7102 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
07-01 12:11:00.392   322  7102 V LGCodecOSAL: Called LGconfigureCodecMETA
07-01 12:11:00.392   322  7102 V LGCodecOSAL: Called LGconfigureCodecMSG
07-01 12:11:00.392   322  7102 V LGCodecOSAL: Not support LGCodec
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
07-01 12:11:00.392   322  7102 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
07-01 12:11:00.392   322  7102 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
07-01 12:11:00.392   322  7102 I AwesomePlayer: Could not offload audio decode, try pcm offload
07-01 12:11:00.392   322  7102 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
07-01 12:11:00.392   322  7102 V AudioSystem: isOffloadSupported()
07-01 12:11:00.392   322  7102 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
07-01 12:11:00.392   322  7102 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
07-01 12:11:00.392   322  7102 V OMXCodec: init()
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
07-01 12:11:00.392   322  7102 V OMXCodec: allocateBuffers
07-01 12:11:00.392   322  7102 V OMXCodec: allocateBuffersOnPort portIndex=0
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on input port
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on input port
07-01 12:11:00.392   322  7102 V OMXCodec: allocateBuffersOnPort portIndex=1
07-01 12:11:00.392   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-01 12:11:00.393   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-01 12:11:00.393   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
07-01 12:11:00.393   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd80 on output port
07-01 12:11:00.393   322  7102 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
07-01 12:11:00.393   322  7102 V OMXCodec: init() mAsyncCompletion wait!!! 
07-01 12:11:00.393   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-01 12:11:00.394   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-01 12:11:00.394   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
07-01 12:11:00.394   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
,07-01 12:11:00.394   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
07-01 12:11:00.394   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
07-01 12:11:00.394   322  7102 V OMXCodec: init() mAsyncCompletion wait free! 
07-01 12:11:00.394   322  7102 V AwesomePlayer: finishAsyncPrepare_l() 
07-01 12:11:00.394   322  7102 V AudioCache: notify(0xb54745c0, 5, 0, 0)
07-01 12:11:00.394   322  7102 V AudioCache: ignored
07-01 12:11:00.394   322  7102 V AudioCache: notify(0xb54745c0, 1, 0, 0)
07-01 12:11:00.394   322  7102 V AudioCache: prepared
07-01 12:11:00.394   322  1390 V AudioCache: wait - success
07-01 12:11:00.394   322  1390 V MediaPlayerService: start
07-01 12:11:00.394   322  1390 V AwesomePlayer: play_l() 
07-01 12:11:00.394   322  1390 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
07-01 12:11:00.394   322  1390 V AwesomePlayer: createAudioPlayer_l
07-01 12:11:00.394   322  1390 V AwesomePlayer: seekAudioIfNecessary_l() 
07-01 12:11:00.394   322  1390 V AwesomePlayer: startAudioPlayer_l() 
07-01 12:11:00.394   322  1390 D AudioPlayer: start of Playback, useOffload 0
07-01 12:11:00.394   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-01 12:11:00.394   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
07-01 12:11:00.395   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
07-01 12:11:00.395   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
07-01 12:11:00.395   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
07-01 12:11:00.395   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
07-01 12:11:00.395   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
07-01 12:11:00.395   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049216
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975264
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
07-01 12:11:00.396   322  7104 V OMXCodec: allocateBuffersOnPort portIndex=1
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fd80 on output port
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on output port
07-01 12:11:00.396   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
07-01 12:11:00.397   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
07-01 12:11:00.397   322  1390 V AudioCache: open(48000, 2, 0x0, 1, 4)
07-01 12:11:00.398   322  1390 V AudioCache: notify(0xb54745c0, 6, 0, 0)
07-01 12:11:00.398   322  1390 V AudioCache: ignored
07-01 12:11:00.398   322  1390 V MediaPlayerService: wait for playback complete
07-01 12:11:00.398   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.398   322  7105 V AudioCache: memcpy(0xabf04000, 0xb57c9000, 4096)
07-01 12:11:00.399  7016  7016 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-01 12:11:00.399  7080  7080 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@28316567 Instance Count = 1
07-01 12:11:00.399   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.399   322  7105 V AudioCache: memcpy(0xabf05000, 0xb57c9000, 4096)
07-01 12:11:00.399   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.399   322  7105 V AudioCache: memcpy(0xabf06000, 0xb57c9000, 4096)
07-01 12:11:00.399  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-01 12:11:00.400   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.400   322  7105 V AudioCache: memcpy(0xabf07000, 0xb57c9000, 4096)
07-01 12:11:00.400   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.400   322  7105 V AudioCache: memcpy(0xabf08000, 0xb57c9000, 4096)
07-01 12:11:00.400   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.400   322  7105 V AudioCache: memcpy(0xabf09000, 0xb57c9000, 4096)
07-01 12:11:00.400   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.400   322  7105 V AudioCache: memcpy(0xabf0a000, 0xb57c9000, 4096)
07-01 12:11:00.401   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.401   322  7105 V AudioCache: memcpy(0xabf0b000, 0xb57c9000, 4096)
07-01 12:11:00.401   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.401   322  7105 V AudioCache: memcpy(0xabf0c000, 0xb57c9000, 4096)
07-01 12:11:00.401   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.401   322  7105 V AudioCache: memcpy(0xabf0d000, 0xb57c9000, 4096)
07-01 12:11:00.401   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.401   322  7105 V AudioCache: memcpy(0xabf0e000, 0xb57c9000, 4096)
07-01 12:11:00.402   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.402   322  7105 V AudioCache: memcpy(0xabf0f000, 0xb57c9000, 4096)
07-01 12:11:00.402   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.402   322  7105 V AudioCache: memcpy(0xabf10000, 0xb57c9000, 4096)
07-01 12:11:00.402   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.402   322  7105 V AudioCache: memcpy(0xabf11000, 0xb57c9000, 4096)
07-01 12:11:00.402   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.402   322  7105 V AudioCache,: memcpy(0xabf12000, 0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: memcpy(0xabf13000, 0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: memcpy(0xabf14000, 0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: memcpy(0xabf15000, 0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: memcpy(0xabf16000, 0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.403   322  7105 V AudioCache: memcpy(0xabf17000, 0xb57c9000, 4096)
07-01 12:11:00.404   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.404   322  7105 V AudioCache: memcpy(0xabf18000, 0xb57c9000, 4096)
07-01 12:11:00.404   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.404   322  7105 V AudioCache: memcpy(0xabf19000, 0xb57c9000, 4096)
07-01 12:11:00.405   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.405   322  7105 V AudioCache: memcpy(0xabf1a000, 0xb57c9000, 4096)
07-01 12:11:00.405   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.405   322  7105 V AudioCache: memcpy(0xabf1b000, 0xb57c9000, 4096)
07-01 12:11:00.405   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.405   322  7105 V AudioCache: memcpy(0xabf1c000, 0xb57c9000, 4096)
07-01 12:11:00.406   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.406   322  7105 V AudioCache: memcpy(0xabf1d000, 0xb57c9000, 4096)
07-01 12:11:00.406   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.406   322  7105 V AudioCache: memcpy(0xabf1e000, 0xb57c9000, 4096)
07-01 12:11:00.406   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.406   322  7105 V AudioCache: memcpy(0xabf1f000, 0xb57c9000, 4096)
07-01 12:11:00.407   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.407   322  7105 V AudioCache: memcpy(0xabf20000, 0xb57c9000, 4096)
07-01 12:11:00.407   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.407   322  7105 V AudioCache: memcpy(0xabf21000, 0xb57c9000, 4096)
07-01 12:11:00.407   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.407   322  7105 V AudioCache: memcpy(0xabf22000, 0xb57c9000, 4096)
07-01 12:11:00.407   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.407   322  7105 V AudioCache: memcpy(0xabf23000, 0xb57c9000, 4096)
07-01 12:11:00.408   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.408   322  7105 V AudioCache: memcpy(0xabf24000, 0xb57c9000, 4096)
07-01 12:11:00.408   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.408   322  7105 V AudioCache: memcpy(0xabf25000, 0xb57c9000, 4096)
07-01 12:11:00.408   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.408   322  7105 V AudioCache: memcpy(0xabf26000, 0xb57c9000, 4096)
07-01 12:11:00.409   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.409   322  7105 V AudioCache: memcpy(0xabf27000, 0xb57c9000, 4096)
07-01 12:11:00.409   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.409   322  7105 V AudioCache: memcpy(0xabf28000, 0xb57c9000, 4096)
07-01 12:11:00.409  7016  7016 V LGMDMManager: Create singleton instance
07-01 12:11:00.409   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.409   322  7105 V AudioCache: memcpy(0xabf29000, 0xb57c9000, 4096)
07-01 12:11:00.410   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.410   322  7105 V AudioCache: memcpy(0xabf2a000, 0xb57c9000, 4096)
07-01 12:11:00.410   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.410   322  7105 V AudioCache: memcpy(0xabf2b000, 0xb57c9000, 4096)
07-01 12:11:00.410   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.410   322  7105 V AudioCache: memcpy(0xabf2c000, 0xb57c9000, 4096)
07-01 12:11:00.411   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.411   322  7105 V AudioCache: memcpy(0xabf2d000, 0xb57c9000, 4096)
07-01 12:11:00.411   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.411   322  7105 V AudioCache: memcpy(0xabf2e000, 0xb57c9000, 4096)
07-01 12:11:00.411   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.411   322  7105 V AudioCache: memcpy(0xabf2f000, 0xb57c9000, 4096)
07-01 12:11:00.412   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.412   322  7105 V AudioCache: memcpy(0xabf30000, 0xb57c9000, 4096)
07-01 12:11:00.412  7080  7080 D BluetoothAdapterApp: onCreate
07-01 12:11:00.415   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.415   322  7105 V AudioCache: memcpy(0xabf31000, 0xb57c9000, 4096)
07-01 12:11:00.415   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.415   322  7105 V AudioCache: memcpy(0xabf32000, 0xb57c9000, 4096)
07-01 12:11:00.415   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.415   322  7105 V AudioCache: memcpy(0xabf33000, 0xb57c9000, 4096)
07-01 12:11:00.416   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.416   322  7105 V AudioCache: memcpy(0xabf34000, 0xb57c9000, 4096)
07-01 12:11:00.416   322  7105 V AudioCache: write(0xb57c9000, 4096)
07-01 12:11:00.416   322  7105 V AudioCache: memcpy(0xabf35000, 0xb57c9000, 4096)
07-01 12:11:00.416   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
07-01 12:11:00.416   322  7105 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
07-01 12:11:00.416   322  7105 V AwesomePlayer: postAudioEOS() 
07-01 12:11:00.416   322  7105 V AudioCache: write(0xb57c9000, 280)
07-01 12:11:00.416   322  7105 V AudioCache: memcpy(0xabf36000, 0xb57c9000, 280)
07-01 12:11:00.425   322  7102 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
07-01 12:11:00.425   322  7102 V AwesomePlayer: onStreamDone
07-01 12:11:00.425   322  7102 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
07-01 12:11:00.425   322  7102 V AudioCache: notify(0xb54745c0, 2, 0, 0)
07-01 12:11:00.425   322  7102 V AudioCache: playback complete
07-01 12:11:00.425   322  7102 V AwesomePlayer: pause_l() 
07-01 12:11:00.425   322  7102 V AudioCache: notify(0xb54745c0, 7, 0, 0)
07-01 12:11:00.425   322  7102 V AudioCache: ignored
07-01 12:11:00.425   322  1390 V AudioCache: wait - success
07-01 12:11:00.425   322  7102 V AwesomePlayer: cancelPlayerEvents
07-01 12:11:00.425   322  1390 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
07-01 12:11:00.431   322  7102 D AudioPlayer: Pause Playback at 1068125
07-01 12:11:00.432   322  1390 V AwesomePlayer: reset_l() 
07-01 12:11:00.432   322  1390 V AudioCache: notify(0xb54745c0, 8, 0, 0)
07-01 12:11:00.432   322  1390 V AudioCache: ignored
07-01 12:11:00.432   322  1390 V AwesomePlayer: cancelPlayerEvents
07-01 12:11:00.432   322  1390 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
07-01 12:11:00.432   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
07-01 12:11:00.432   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
07-01 12:11:00.432   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
07-01 12:11:00.432   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 0
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 0
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 1
07-01 12:11:00.432   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fba0 on port 1
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fd80 on port 1
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
07-01 12:11:00.433   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-01 12:11:00.433   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
07-01 12:11:00.433   322  7104 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
07-01 12:11:00.433   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
07-01 12:11:00.433   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
07-01 12:11:00.433   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
07-01 12:11:00.434   322  1390 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
07-01 12:11:00.434   322  1390 D AudioPlayer: AudioPlayer releasing audio source
07-01 12:11:00.434   322  1390 D AudioPlayer: AudioPlayer done releasing audio source
07-01 12:11:00.434   322  1390 V AwesomePlayer: reset_l() 
07-01 12:11:00.434   322  1390 V AwesomePlayer: cancelPlayerEvents
07-01 12:11:00.434   322  1390 V AwesomePlayer: ~AwesomePlayer call
07-01 12:11:00.435   322  1390 V AwesomePlayer: reset_l() 
07-01 12:11:00.435   322  1390 V AwesomePlayer: cancelPlayerEvents
07-01 12:11:00.435  7016  7101 V SoundPool: close(30)
07-01 12:11:00.435  7016  7101 V SoundPool: pointer = 0xa0045000, size = 205080, sampleRate = 48000, numChannels = 2
07-01 12:11:00.436  7080  7080 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-01 12:11:00.436  7080  7080 D ProfileConfigQcom: Adding HeadsetService
07-01 12:11:00.436  7080  7080 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-01 12:11:00.436  7080  7080 D ProfileConfigQcom: Adding A2dpService
07-01 12:11:00.436  7080  7080 D ProfileConfigQcom: [BTUI] HidService is supported
07-01 12:11:00.436  7080  7080 D ProfileConfigQcom: Adding HidService
07-01 12:11:00.436  7080  7080 D ProfileConfigQcom: [BTUI] HealthService is supported
07-01 12:11:00.437  7080  7080 D ProfileConfigQcom: Adding HealthService
07-01 12:11:00.437  7080  7080 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
07-01 12:11:00.437  7080  7080 D ProfileConfigQcom: [BTUI] PanService is supported
07-01 12:11:00.437  7080  7080 D ProfileConfigQcom: Adding PanService
07-01 12:11:00.437  7080  7080 D ProfileConfigQcom: [BTUI] GattService is supported
07-01 12:11:00.437  7080  7080 D ProfileConfigQcom: Adding GattService
07-01 12:11:00.438  7080  7080 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-01 12:11:00.438  7080  7080 D ProfileConfigQcom: Adding BluetoothMapService
07-01 12:11:00.438  7080  7080 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-01 12:11:00.439  7080  7080 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-01 12:11:00.447  7080  7080 V LGMDMManagerInternal: Create singleton instance
07-01 12:11:00.456  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-01 12:11:00.464  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-01 12:11:00.465  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,07-01 12:11:00.467  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5682
07-01 12:11:00.522  7080  7080 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:00.525  7080  7080 V BluetoothSapReceiver: [BTUI] checkServiceStart
,07-01 12:11:00.526  7080  7080 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 12:11:00.526  7080  7080 V BluetoothSapReceiver: SapReceiver onReceive 
,07-01 12:11:00.527  7080  7080 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:00.527  7080  7080 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-01 12:11:00.533  7037  7037 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-01 12:11:00.612  6590  6590 I UEI.SmartControl: Supports setup maps: true
07-01 12:11:00.614  6590  6590 D UEI.SmartControl: QS start statue = true Error code = 0
,07-01 12:11:00.614  6590  6590 I UEI.SmartControl: QS version = v2.7.10.1_RC1
07-01 12:11:00.614  6590  6590 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
07-01 12:11:00.614  6590  6590 I UEI.SmartControl: ### init IR Blaster...
07-01 12:11:00.618  6590  6590 D serial_port: Configuring serial port
07-01 12:11:00.618  6590  6590 E UEI.SmartControl: UEIBLaster setting for 616
07-01 12:11:00.618  6590  6590 I UEI.SmartControl: Setting serial record hearder size = 2
,07-01 12:11:00.618  6590  6590 I UEI.SmartControl: configuring settings for MAXQ616
07-01 12:11:00.618  6590  6590 I UEI.SmartControl: Get version...
,07-01 12:11:00.636  6590  7115 D UEI.SmartControl: serial port data available: 21
,07-01 12:11:00.663  6590  6590 D UEI.SmartControl: MAXQ616 A2-X4 software.
,07-01 12:11:00.663  6590  6590 I UEI.SmartControl: IR Blaster version: 256702256704300002
,07-01 12:11:00.663  6590  6590 I UEI.SmartControl: QS saving settings...
,07-01 12:11:00.666  1036  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-01 12:11:00.671   318   902 D SoftapController: Softap fwReload - Ok
07-01 12:11:00.671  1036  1539 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (830ms)
07-01 12:11:00.672   318   902 D CommandListener: Setting iface cfg
07-01 12:11:00.672   318   902 D CommandListener: Trying to bring down wlan0
07-01 12:11:00.673   318   902 D CommandListener: Clearing all IP addresses on wlan0
07-01 12:11:00.674  1036  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
07-01 12:11:00.675  1036  1097 D Tethering: InitialState.processMessage what=4
07-01 12:11:00.675  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 12:11:00.677  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 12:11:00.677  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
07-01 12:11:00.677  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 12:11:00.678  1036  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-01 12:11:00.678  1036  1539 D WifiMonitor: connecting to supplicant
07-01 12:11:00.673  7118  7118 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:00.679  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,07-01 12:11:00.679  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 12:11:00.679  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 12:11:00.679  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 12:11:00.680  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:00.681  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-01 12:11:00.683  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:00.683  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:00.684  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-01 12:11:00.673  7118  7118 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:00.687  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 12:11:00.690  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 12:11:00.690  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-01 12:11:00.690  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 12:11:00.690  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 12:11:00.690  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 12:11:00.690  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-01 12:11:00.691  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 12:11:00.692  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 12:11:00.692  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,07-01 12:11:00.692  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 12:11:00.692  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 12:11:00.693  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 12:11:00.693  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 12:11:00.693  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-01 12:11:00.693  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 12:11:00.693  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 12:11:00.693  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 12:11:00.694  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 12:11:00.696  7118  7118 I wpa_supplicant: Successfully initialized wpa_supplicant
07-01 12:11:00.701  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:11:00.711  6748  7120 W FormManager: Network not available. Please check & try again.
07-01 12:11:00.712  6748  7121 V FormManager: Network unavailable.
,07-01 12:11:00.712  7118  7118 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-01 12:11:00.712  7118  7118 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-01 12:11:00.714  6748  7121 V FormManager: Network unavailable.
07-01 12:11:00.715  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:00.715  6590  6590 D UEI.SmartControl: IR Blaster version: 25672567
07-01 12:11:00.720  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:00.731  6590  7115 D UEI.SmartControl: serial port data available: 4
,07-01 12:11:00.759  6590  6590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,07-01 12:11:00.759  6590  6590 E UEI.SmartControl: Services init done
07-01 12:11:00.759  6590  6590 D UEI.SmartControl: QS Service init finished
07-01 12:11:00.760  6590  6590 D UEI.SmartControl: QS Service version name: 2.1.91
07-01 12:11:00.760  6590  6590 D UEI.SmartControl: QS Service version code: 201091
07-01 12:11:00.760  6590  7123 I UEI.SmartControl: Device manager: loading config....
07-01 12:11:00.760  6590  6590 D UEI.SmartControl: Service requested: Control
07-01 12:11:00.761  6590  7123 D UEI.SmartControl: ----------- loading internal config...
07-01 12:11:00.763  6590  7123 E UEI.SmartControl: Loading SETTINGS...
07-01 12:11:00.765  6590  7123 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
07-01 12:11:00.766  6590  6590 D UEI.SmartControl: Request IControl service: devices are loaded...
07-01 12:11:00.767  7016  7016 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
07-01 12:11:00.768  6590  6605 I UEI.SmartControl: ------ IControl API: 11
07-01 12:11:00.768  6590  6605 D UEI.SmartControl: File observer start...
07-01 12:11:00.768  6590  6590 D UEI.SmartControl: Internal service binding...
07-01 12:11:00.768  6590  6605 E UEI.SmartControl: IR Port is disabled: false
07-01 12:11:00.768  6590  6605 D UEI.SmartControl: Starting file observer...
07-01 12:11:00.768  6590  6605 I UEI.SmartControl: Registering callback...
07-01 12:11:00.768  6590  6606 I UEI.SmartControl: ------ IControl API: 19
07-01 12:11:00.769  6590  6606 I UEI.SmartControl: Registering Services Ready callback...
07-01 12:11:00.779  6590  7122 I UEI.SmartControl: Notify AllClients services are ready: 0
07-01 12:11:00.779  6590  7122 D UEI.SmartControl: -----service ready thread exits
07-01 12:11:00.779  7016  7031 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
07-01 12:11:00.779  7016  7099 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
07-01 12:11:00.780  7016  7099 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
07-01 12:11:00.780  7016  7016 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
07-01 12:11:00.780  7016  7016 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,07-01 12:11:00.780  6590  6605 I UEI.SmartControl: ------ IControl API: 8
07-01 12:11:00.781  7016  7016 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
07-01 12:11:00.782  7016  7016 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
07-01 12:11:00.782  7016  7016 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
07-01 12:11:00.782  7016  7016 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
07-01 12:11:00.783  7016  7016 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
07-01 12:11:00.783  7016  7016 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
07-01 12:11:00.785  7016  7016 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
07-01 12:11:00.786  7016  7016 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
07-01 12:11:00.787  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
07-01 12:11:00.787  7016  7016 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-01 12:11:00.787  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
07-01 12:11:00.788  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
07-01 12:11:00.789  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
07-01 12:11:00.789  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
07-01 12:11:00.789  7016  7016 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1467367860789]
07-01 12:11:00.792  7016  7016 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,07-01 12:11:00.793  1036  1986 I ActivityManager: Killing 6307:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-01 12:11:00.793  7118  7118 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-01 12:11:00.811  7016  7125 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,07-01 12:11:00.885  1036  1986 I ActivityManager: Killing 6043:com.android.gallery3d/u0a27 (adj 15): empty #18
,07-01 12:11:00.913  7118  7118 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-01 12:11:00.921  7118  7118 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-01 12:11:00.921  7118  7118 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-01 12:11:00.923  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-01 12:11:00.923  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
07-01 12:11:00.923  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-01 12:11:00.923  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-01 12:11:00.924  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:00.924  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:00.924  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:00.924  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:00.924  1036  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-01 12:11:00.924  1036  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-01 12:11:00.925  1036  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-01 12:11:00.925  1036  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-01 12:11:00.925  1036  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-01 12:11:00.925  1036  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-01 12:11:00.926  1036  7126 D WifiMonitor: Dropping event because (p2p0) is stopped
07-01 12:11:00.926  1036  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-01 12:11:00.926  1036  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
07-01 12:11:00.926  1036  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-01 12:11:00.926  1036  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-01 12:11:01.012  1036  1052 W libprocessgroup: failed to open /acct/uid_10004/pid_6307/cgroup.procs: No such file or directory
,07-01 12:11:01.022  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 12:11:01.022  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
07-01 12:11:01.022  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 12:11:01.023  1036  1985 W libprocessgroup: failed to open /acct/uid_10027/pid_6043/cgroup.procs: No such file or directory
07-01 12:11:01.024  7016  7016 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
07-01 12:11:01.026  7016  7016 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
07-01 12:11:01.027  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
07-01 12:11:01.028  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,07-01 12:11:01.028  1036  1773 D WifiServiceImplEx: setWifiEnabled: false pid=6891, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 12:11:01.029  1036  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
07-01 12:11:01.029  1036  1773 D WifiService: setWifiEnabled: false pid=6891, uid=10118
07-01 12:11:01.029  1036  1773 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-01 12:11:01.029  1036  1539 D WifiNative-wlan0: SET update_config 1: returned true
07-01 12:11:01.030  1036  1539 D WifiConfigStore: Loading config and enabling all networks 
07-01 12:11:01.030  1036  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-01 12:11:01.030  1036  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-01 12:11:01.032  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:01.032  1968  1968 D WfdService: Waiting for WifiP2p enabling
07-01 12:11:01.033  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:01.033  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:01.033  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:01.033  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:11:01.034  1036  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
07-01 12:11:01.035  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:01.037  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
07-01 12:11:01.038  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
07-01 12:11:01.039  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
07-01 12:11:01.039  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:01.039  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:01.039  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:01.039  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:01.039  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:01.039  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:01.039  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:01.039  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:01.039  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:01.041  1036  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,07-01 12:11:01.042  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:01.042  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:01.042  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:01.042  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:01.042  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:01.042  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:01.042  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:01.042  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:01.042  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:01.045  1036  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-01 12:11:01.046  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-01 12:11:01.046  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-01 12:11:01.047  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:11:01.047  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:11:01.047  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 12:11:01.049  1036  1539 D WifiStateMachine: enableVerboseLogging : level 2
07-01 12:11:01.049  1036  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-01 12:11:01.049  1036  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-01 12:11:01.049  1036  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-01 12:11:01.049  1036  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-01 12:11:01.049  1036  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-01 12:11:01.050  1036  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-01 12:11:01.050  1036  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
07-01 12:11:01.050  1036  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-01 12:11:01.050  1036  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
07-01 12:11:01.051  1036  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-01 12:11:01.051  1036  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-01 12:11:01.051  1036  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-01 12:11:01.051  1036  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-01 12:11:01.051  1036  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-01 12:11:01.053  1968  1968 D WfdsService: Supplicant Connection state is changed : true
07-01 12:11:01.053  1968  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-01 12:11:01.053  1968  2319 D WfdsService: Set the WFDS Monitor: true
07-01 12:11:01.054  1968  2319 D WfdsMonitor: WfdsMonitorThread create
07-01 12:11:01.054  1968  2319 D WfdsMonitor: WFDS Monitor is created and started
07-01 12:11:01.054  1968  2319 D WfdsService: WiFi: Supplicant connection re-established
,07-01 12:11:01.056  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 12:11:01.056  1036  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-01 12:11:01.056  1968  7128 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-01 12:11:01.056  1036  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-01 12:11:01.056  1036  1539 D WifiNative-HAL: Setting external_sim to 1
07-01 12:11:01.056  1036  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-01 12:11:01.056  1968  7128 E CtrlSupplicant: Succeed to open control connection
,07-01 12:11:01.056  1036  1539 D WifiNative-wlan0: SET external_sim 1: returned true
07-01 12:11:01.057  1036  1539 I WifiNative-HAL: startHal
07-01 12:11:01.057  1036  1539 D wifi    : setting scan oui 0x95768960
07-01 12:11:01.057  1968  7128 E CtrlSupplicant: Succeed to open monitor connection
07-01 12:11:01.057  1968  7128 D WfdsMonitor: Supplicant connection established
07-01 12:11:01.057  1968  2319 D WfdsService: Connected to the supplicant for wfds
07-01 12:11:01.057  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 12:11:01.057  1036  1539 I WifiNative-HAL: startHal
07-01 12:11:01.057  1036  1539 D wifi    : setting scan oui 0x95768960
07-01 12:11:01.057  1036  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-01 12:11:01.058  1036  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-01 12:11:01.058  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-01 12:11:01.058  7118  7118 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-01 12:11:01.059  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-01 12:11:01.059  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-01 12:11:01.059  7118  7118 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-01 12:11:01.060  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-01 12:11:01.060  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-01 12:11:01.060  7118  7118 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-01 12:11:01.060  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-01 12:11:01.060  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-01 12:11:01.060  7118  7118 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-01 12:11:01.060  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-01 12:11:01.060  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-01 12:11:01.060  7118  7118 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-01 12:11:01.061  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-01 12:11:01.061  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-01 12:11:01.061  7118  7118 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
07-01 12:11:01.061  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-01 12:11:01.061  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-01 12:11:01.061  7118  7118 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-01 12:11:01.062  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-01 12:11:01.063  1036  1539 E WifiNative: : [288,382,286 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-01 12:11:01.063  1036  1539 D WifiNative-wlan0: doBoolean: RECONNECT
07-01 12:11:01.063  1036  1539 D WifiNative-wlan0: RECONNECT: returned true
07-01 12:11:01.063  1036  1539 D WifiNative-wlan0: doString: [STATUS]
07-01 12:11:01.063  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
07-01 12:11:01.064  1036  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-01 12:11:01.064  1036  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-01 12:11:01.064  1036  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-01 12:11:01.064  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 12:11:01.065  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
07-01 12:11:01.066  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.067   318   902 D CommandLis,tener: Setting iface cfg
07-01 12:11:01.067   318   902 D CommandListener: Trying to bring up p2p0
07-01 12:11:01.067  1036  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-01 12:11:01.067  1036  1537 D LGWifiP2pService: P2pEnablingState
07-01 12:11:01.067  1036  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.067  1036  1537 D LGWifiP2pService: P2p socket connection successful
07-01 12:11:01.067  1036  1537 D LGWifiP2pService: P2pEnabledState
,07-01 12:11:01.070  1036  1537 D LGWifiP2pService: sending p2p connection changed broadcast
07-01 12:11:01.070  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
07-01 12:11:01.071  1036  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-01 12:11:01.071  1036  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-01 12:11:01.071  1036  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-01 12:11:01.072  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 12:11:01.072  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-01 12:11:01.072  1036  1558 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.073  1036  1539 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
07-01 12:11:01.073  1036  1539 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
07-01 12:11:01.074  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-01 12:11:01.074  1036  1557 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.074  1036  1557 I WifiNative-HAL: startHal
07-01 12:11:01.074  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0x95768960
07-01 12:11:01.074  1036  1557 D wifi    : failed to get capabilities : -3
07-01 12:11:01.074  1036  1557 E WifiScanningService: could not get scan capabilities
07-01 12:11:01.074  1968  1968 D WfdsService: WifiP2pState is changed : true
07-01 12:11:01.074  1036  1539 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
07-01 12:11:01.074  1968  2319 D WfdsService: Receive the WFDS_ENABLE Method
07-01 12:11:01.074  1968  2319 D WfdsService: Set the WFDS Monitor: true
07-01 12:11:01.074  1968  2319 D WfdsService: Connected to the supplicant for wfds
07-01 12:11:01.074  1968  2319 D WfdsJNI : doCommand: WFDS_SET TRUE
07-01 12:11:01.074  1036  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-01 12:11:01.074  7118  7118 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-01 12:11:01.075  1968  2319 D WfdsService: selectPreferredScanChannel [36]
,07-01 12:11:01.075  1968  2319 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,07-01 12:11:01.076  1968  1968 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-01 12:11:01.076  1968  1968 D WfdsService: isConnected: false
07-01 12:11:01.076  1036  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-01 12:11:01.077  1036  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
07-01 12:11:01.077  1036  1537 D WifiNative-p2p0: SET device_name G3: returned true
07-01 12:11:01.077  1036  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-01 12:11:01.077  1036  1537 D LGWifiP2pService: before postfix = G3
07-01 12:11:01.077  1036  1537 D WifiServerServiceExt: postfix byte check : 2
07-01 12:11:01.077  1036  1537 D LGWifiP2pService: after postfix = G3
07-01 12:11:01.077  1036  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-01 12:11:01.077  1036  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-01 12:11:01.077  1036  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-01 12:11:01.078  1036  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-01 12:11:01.078  1036  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-01 12:11:01.078  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
07-01 12:11:01.078  1036  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-01 12:11:01.078  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-01 12:11:01.079  1036  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-01 12:11:01.079  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress
07-01 12:11:01.079  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:11:01.079  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-01 12:11:01.079  1036  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-01 12:11:01.079  1036  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-01 12:11:01.079  1036  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
07-01 12:11:01.079  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-01 12:11:01.080  1968  1968 I WfdStateTracker: handleP2pThisDeviceChanged
07-01 12:11:01.080  1968  1968 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-01 12:11:01.080  1968  1968 D WfdsService: Update P2p Interface State: 3
07-01 12:11:01.080  1036  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-01 12:11:01.080  1036  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-01 12:11:01.081  1036  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-01 12:11:01.081  1036  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-01 12:11:01.082  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:01.087  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 12:11:01.087  1036  1036 D RttService: SCAN_AVAILABLE : 1
07-01 12:11:01.088  1036  1557 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.088  1036  1558 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.090  1036  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-01 12:11:01.090  1036  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-01 12:11:01.091  1036  1537 D LGWifiP2pService: InactiveState
07-01 12:11:01.091  1036  1539 E WifiStateMachine:  WaitForP2pDisableState what:132106 1 0
07-01 12:11:01.091  1036  1537 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.091  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.091  1036  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-01 12:11:01.091  7118  7118 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-01 12:11:01.091  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:01.092  7118  7118 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:01.093  7118  7118 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-01 12:11:01.093  7118  7118 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:01.094  7118  7118 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:01.094  1968  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-01 12:11:01.095  1036  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-01 12:11:01.095  1968  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:01.095  1968  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:01.095  1036  7126 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:01.095  1036  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:01.095  1036  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:01.095  1036  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:01.095  1036  7126 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:01.095  1036  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:01.095  1036  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:01.095  1036  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:01.095  1036  7126 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:01.096  1036  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:01.096  1036  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:01.096  1036  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-01 12:11:01.096  1036  1537 D LGWifiP2pService: InactiveState{ when=-9ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.096  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.096  1036  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@80de634
07-01 12:11:01.096  1036  1537, D LGWifiP2pService: P2pDisablingState
07-01 12:11:01.096  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.097  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.097  1036  1539 E WifiStateMachine:  SupplicantStartedState what:132106 1 0
,07-01 12:11:01.097  1036  1539 E WifiStateMachine:  DefaultState what:132106 1 0
07-01 12:11:01.097  1036  1539 E WifiStateMachine: Error! unhandled message{ when=-51ms what=132106 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.098  1036  1539 E WifiStateMachine:  WaitForP2pDisableState what:132096 -100 0
07-01 12:11:01.098  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.098  1036  1537 D LGWifiP2pService: DefaultState{ when=-7ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.098  1036  1539 E WifiStateMachine:  SupplicantStartedState what:132096 -100 0
07-01 12:11:01.099  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.099  1036  1537 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.099  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.099  1036  1537 D LGWifiP2pService: DefaultState{ when=-8ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.099  1036  1537 D LGWifiP2pService: P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.099  1036  1537 D LGWifiP2pService: p2p socket connection lost
07-01 12:11:01.099  1036  1537 D LGWifiP2pService: P2pDisabledState
07-01 12:11:01.099  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-01 12:11:01.099  1968  1968 D WfdsService: WifiP2pState is changed : false
07-01 12:11:01.099  1968  2319 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
07-01 12:11:01.099  1968  2319 D WfdsService: Set the WFDS Monitor: false
07-01 12:11:01.099  1036  1036 E WifiServerServiceExt: No p2p device connected
07-01 12:11:01.100  1968  2319 D WfdsMonitor: WFDS Monitor is stopped
07-01 12:11:01.100  1968  2319 D WfdsService: STATE : WfdsDisabledState - enter
07-01 12:11:01.100  1968  7128 D CtrlSupplicant: Received on exit socket, terminate
07-01 12:11:01.100  1968  7128 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
07-01 12:11:01.100  1968  2319 W WfdsService: DefaultState - msg [9441285] is not handled
07-01 12:11:01.100  1968  2320 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
07-01 12:11:01.100  1968  7128 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
07-01 12:11:01.100  1968  7128 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
07-01 12:11:01.100  1968  2319 W WfdsService: DefaultState - msg [9445378] is not handled
07-01 12:11:01.100  1036  1539 E WifiStateMachine:  DefaultState what:132096 -100 0
07-01 12:11:01.101  1036  1539 E WifiStateMachine: Error! unhandled message{ when=-54ms what=132096 arg1=-100 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.102  6748  7130 W FormManager: Network not available. Please check & try again.
07-01 12:11:01.102  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 2 0 cz
07-01 12:11:01.102  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_FREQUENCY_BAND 0 0
07-01 12:11:01.103  1036  1539 E WifiStateMachine:  WaitForP2pDisableState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=288423  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 12:11:01.103  1036  1539 E WifiStateMachine:  WaitForP2pDisableState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 12:11:01.103  6748  7131 V FormManager: Network unavailable.
07-01 12:11:01.104  1036  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 12:11:01.105  1036  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1,000 0 0 st=UNKNOWN/IDLE
07-01 12:11:01.105  1036  1539 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
07-01 12:11:01.105   318   902 D CommandListener: Clearing all IP addresses on wlan0
07-01 12:11:01.106  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:11:01.106  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:11:01.107  1036  1539 D WifiNative-p2p0: doBoolean: TERMINATE
07-01 12:11:01.107  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-01 12:11:01.108  1036  1036 D WifiHS20: hidePasspointNotification off =false
07-01 12:11:01.108  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:01.109  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:01.109  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:11:01.110  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 12:11:01.110  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-01 12:11:01.111  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:01.111  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:01.113  1036  1539 D WifiNative-p2p0: TERMINATE: returned true
07-01 12:11:01.113  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 12:11:01.113  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
07-01 12:11:01.113  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 12:11:01.114  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 2 0 cz
07-01 12:11:01.115  1036  1539 E WifiStateMachine:  SupplicantStoppingState CMD_SET_FREQUENCY_BAND 0 0
07-01 12:11:01.115  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
07-01 12:11:01.115  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
07-01 12:11:01.116  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=288436  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 12:11:01.116  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:01.116  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:01.116  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:01.116  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:01.116  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:01.116  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:01.116  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:01.116  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:01.116  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:01.116  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=288436  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 12:11:01.117  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:01.117  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:01.117  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:01.117  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:01.117  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:01.117  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:01.117  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:01.117  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:01.117  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:01.117  6748  7131 V FormManager: Network unavailable.
07-01 12:11:01.117  6569  6569 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 12:11:01.118  6569  6569 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-01 12:11:01.120  4321  7132 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAg,entState()] : [672] : iAgentState=0, isUserType=0
,07-01 12:11:01.123  6569  6569 V [BNRBootReceiver]: Boot Receiver Return
07-01 12:11:01.124  4321  7134 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:11:01.125  4321  7134 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-01 12:11:01.125  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:01.129  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
07-01 12:11:01.129  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:11:01.129  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:11:01.130  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:01.132  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:11:01.137  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:01.142  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:01.142  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:01.143  7016  7016 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 12:11:01.151  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 12:11:01.152  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:01.157  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:01.165  6748  7136 W FormManager: Network not available. Please check & try again.
,07-01 12:11:01.176  6748  7137 V FormManager: Network unavailable.
07-01 12:11:01.177  6748  7137 V FormManager: Network unavailable.
,07-01 12:11:01.504  7118  7118 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-01 12:11:01.504  7118  7118 I wpa_supplicant: monitor socket send errors count : 1
07-01 12:11:01.504  7118  7118 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1968-4\x00 that cannot receive messages
,07-01 12:11:01.513  1036  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
07-01 12:11:01.513  1036  7126 D WifiMonitor: Dropping event because (p2p0) is stopped
07-01 12:11:01.513  1036  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
07-01 12:11:01.514  1036  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
07-01 12:11:01.515  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=288835  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
07-01 12:11:01.516  1036  1539 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=288836  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,07-01 12:11:01.608  7118  7118 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-01 12:11:01.615  1036  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
07-01 12:11:01.615  1036  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-TERMINATING 
07-01 12:11:01.615  1036  7126 D WifiMonitor: Disconnecting from the supplicant, no more events
,07-01 12:11:01.617  1036  1539 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 28 0
07-01 12:11:01.718  1036  1539 D WifiOffDelayIfNotUsed: stopMonitoring
07-01 12:11:01.719  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 12:11:01.719  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
07-01 12:11:01.719  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-01 12:11:01.727  1968  1968 D WfdsService: Supplicant Connection state is changed : false
07-01 12:11:01.727  1968  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
07-01 12:11:01.727  1968  2319 D WfdsService: Set the WFDS Monitor: false
07-01 12:11:01.727  1968  2319 D WfdsMonitor: WFDS Monitor is stopped
,07-01 12:11:01.736  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:01.737  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
07-01 12:11:01.741  2498  2498 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:01.744  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:01.745  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:01.746  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
07-01 12:11:01.746  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
07-01 12:11:01.746  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
07-01 12:11:01.747  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:11:01.748  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:11:01.750  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:01.753  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:01.757  1036  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=332534726, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
07-01 12:11:01.758  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1b12624b type 2 when 289075 com.google.android.gms} when 289075
,07-01 12:11:01.764  4321  7144 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 12:11:01.766  4321  7145 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:11:01.766  4321  7145 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:11:01.777  6984  6984 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
07-01 12:11:01.777  6984  6984 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-01 12:11:01.777  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-01 12:11:01.786  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:01.805  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:01.815  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,07-01 12:11:01.830  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=332534726 [*alarm*], flags=0x0
,07-01 12:11:01.835  6748  7147 W FormManager: Network not available. Please check & try again.
07-01 12:11:01.836  6748  7148 V FormManager: Network unavailable.
07-01 12:11:01.837  6748  7148 V FormManager: Network unavailable.
07-01 12:11:01.899  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:01.905  1036  1097 D Tethering: MasterInitialState.processMessage what=3
,07-01 12:11:01.906  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:01.903  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:01.907  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:01.909  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:01.913  1036  1097 D Tethering: MasterInitialState.processMessage what=3
07-01 12:11:01.913  5757  5757 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-01 12:11:01.913  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-01 12:11:01.921  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:01.921  6385  6983 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-01 12:11:01.922  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:01.927  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:01.928  5757  5757 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
07-01 12:11:01.928  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:01.928  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:01.935  1036  1539 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 2 0 cz
07-01 12:11:01.935  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 2 0 cz
07-01 12:11:01.936  1036  1539 E WifiStateMachine:  InitialState CMD_SET_FREQUENCY_BAND 0 0
07-01 12:11:01.936  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_FREQUENCY_BAND 0 0
07-01 12:11:01.948  2225  2225 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:02.020  1036  1950 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7161 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-01 12:11:02.047  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:11:02.047  1036  1576 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,07-01 12:11:02.056  1036  1097 D BluetoothManagerService: Message: 1
07-01 12:11:02.056  1036  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-01 12:11:02.057  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:11:02.058  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:11:02.058  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 12:11:02.072  1036  1097 D BluetoothManagerService: Message: 20
,07-01 12:11:02.072  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e6e9f72:true
07-01 12:11:02.073  7080  7080 D BluetoothAdapterState: make
,07-01 12:11:02.079  7080  7080 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
,07-01 12:11:02.079  7080  7080 I bluedroid-qcom: init
07-01 12:11:02.079  7080  7180 I BluetoothAdapterState: Entering OffState
07-01 12:11:02.081  7080  7080 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-01 12:11:02.081  7080  7080 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-01 12:11:02.081  7080  7080 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-01 12:11:02.081  7080  7080 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-01 12:11:02.081  7080  7080 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-01 12:11:02.083  7080  7080 I bluedroid-qcom: get_profile_interface socket
07-01 12:11:02.084  7080  7080 I bluedroid-qcom: get_profile_interface map_client
07-01 12:11:02.073  7183  7183 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:02.073  7183  7183 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-01 12:11:02.086  7080  7184 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-01 12:11:02.088  7080  7184 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-01 12:11:02.093  7183  7183 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-01 12:11:02.093  7183  7183 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-01 12:11:02.093  7183  7183 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-01 12:11:02.094  7183  7183 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-01 12:11:02.129  7183  7183 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-01 12:11:02.129  7183  7183 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,07-01 12:11:02.227  1036  1985 I art     : Explicit concurrent mark sweep GC freed 105186(5MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 43MB/65MB, paused 1.853ms total 149.200ms
,07-01 12:11:02.240  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-01 12:11:02.241  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-01 12:11:02.241  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-01 12:11:02.241  1036  1097 D BluetoothManagerService: Message: 40
07-01 12:11:02.241  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-01 12:11:02.242  7080  7184 D BluetoothAdapterProperties: Name is: G3
07-01 12:11:02.243  7080  7098 I bluedroid-qcom: config_hci_snoop_log
,07-01 12:11:02.245  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-01 12:11:02.246  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
07-01 12:11:02.253  7080  7180 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-01 12:11:02.254  7080  7180 D BluetoothAdapterProperties: Setting state to 11
07-01 12:11:02.254  7080  7180 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 12:11:02.255  1036  1097 D BluetoothManagerService: Message: 60
07-01 12:11:02.255  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-01 12:11:02.255  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,07-01 12:11:02.257  1968  1968 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:02.258  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-01 12:11:02.258  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 12:11:02.259  7080  7180 I LGBluetoothServiceJni: classInitNative: succeeds
07-01 12:11:02.264  7080  7080 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:11:02.266  7080  7080 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:02.266  7080  7080 V BluetoothPbapReceiver: ***********state = 11
07-01 12:11:02.269  2225  2225 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:02.272  7080  7180 D BluetoothBondStateMachine: make
07-01 12:11:02.273  7080  7180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.274  7080  7180 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-01 12:11:02.274  7080  7180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.274  7080  7180 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-01 12:11:02.274  7080  7180 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-01 12:11:02.274  7080  7185 I BluetoothBondStateMachine: StableState(): Entering Off State
07-01 12:11:02.279  6966  6966 D BluetoothPermissionRequest: onReceive
07-01 12:11:02.280  7080  7180 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:02.281  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 12:11:02.289  7080  7180 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:02.289  7080  7080 D HeadsetService: Received start request. Starting profile...
07-01 12:11:02.290  7080  7080 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 12:11:02.290  7080  7080 D LGBluetoothHfpAdapter: Version 1.6
07-01 12:11:02.293  7080  7080 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 12:11:02.294  7080  7080 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 12:11:02.295  7080  7080 D HeadsetStateMachine: make
,07-01 12:11:02.300  7080  7180 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:02.306  7080  7180 E BluetoothAdapterService: File transfer profiles supported!!
,07-01 12:11:02.311  7080  7180 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:02.315  7080  7180 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:02.319  7080  7180 E BluetoothAdapterService: File transfer profiles supported!!
,07-01 12:11:02.320  7161  7161 I AppUp4:AppBoxCP: onCreate
07-01 12:11:02.321  7161  7161 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-01 12:11:02.326  7161  7161 I AppUp4:DB:  setFingerPrint start
07-01 12:11:02.326  7161  7161 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-01 12:11:02.327  7080  7080 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:02.327  7080  7080 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 12:11:02.330  7080  7080 D HeadsetStateMachine: max_hf_connections = 1
07-01 12:11:02.330  7080  7080 I bluedroid-qcom: get_profile_interface handsfree
07-01 12:11:02.331  7161  7161 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-01 12:11:02.331  7161  7161 I AppUp4:DB:  SDK version = 21
07-01 12:11:02.331  7161  7161 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-01 12:11:02.332  7080  7080 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,07-01 12:11:02.332  7161  7161 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-01 12:11:02.332   322   322 V AudioPolicyService: registerClient() client 0xb558a220, uid 1002
07-01 12:11:02.332   322  1389 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-01 12:11:02.332   322  1389 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 12:11:02.332   322  1389 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 12:11:02.333  7080  7080 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-01 12:11:02.333  7161  7161 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-01 12:11:02.333  7161  7161 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:02.333   322  1390 V AudioFlinger: registerClient() client 0xb1433100, pid 7080
07-01 12:11:02.333   322  1384 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:02.333   322  1384 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:02.334   322  1385 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:02.334   322  1385 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:02.334  7161  7161 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-01 12:11:02.334  7161  7161 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-01 12:11:02.334  1036  1576 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:02.334  1036  1576 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:02.334  1036  1576 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:02.334  1036  1576 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:02.335  7080  7098 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:02.335  3424  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:02.335  3424  3440 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:02.335  3424  3440 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:02.335  3424  3440 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:02.335  1881  3992 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:02.335  1881  3992 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:02.335  1881  3992 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:02.335  1881  3992 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:02.335  1603  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:02.335  1603  1625 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:02.335  1603  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:02.335  1603  1625 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:02.335  7080  7080 V ToneGenerator: Create Track: 0xb4928080
07-01 12:11:02.335  7080  7098 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-01 12:11:02.335  7080  7080 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-01 12:11:02.335  7080  7098 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:02.335  7080  7080 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-01 12:11:02.335  7080  7098 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-01 12:11:02.335   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 12:11:02.335   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-0,1 12:11:02.336   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 12:11:02.336   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 12:11:02.337   322  1389 I AudioFlinger: isAudioPlaybackHookOn() false
07-01 12:11:02.337   322  1390 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 12:11:02.337   322  1390 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-01 12:11:02.337   322  1390 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 12:11:02.337   322  1390 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 12:11:02.337  7080  7080 V AudioSystem: getLatency() output 2, latency 50
07-01 12:11:02.337  7080  7080 V AudioSystem: getFrameCount() output 2, frameCount 960
07-01 12:11:02.337  7080  7080 V AudioTrack: createTrack_l() output 2 afLatency 50
07-01 12:11:02.338   322  4000 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-01 12:11:02.338   322  4000 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-01 12:11:02.338   322  4000 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-01 12:11:02.338   322  4000 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-01 12:11:02.338   322  4000 V AudioFlinger: createTrack() lSessionId: 26
07-01 12:11:02.339  7080  7080 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-01 12:11:02.339   322   322 V AudioFlinger: acquiring 26 from 7080, for 7080
07-01 12:11:02.339   322   322 V AudioFlinger:  added new entry for 26
07-01 12:11:02.339  7080  7080 V ToneGenerator: ToneGenerator INIT OK, time: 289674
07-01 12:11:02.339  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.340  7161  7161 I AppUp4:CustModeStarterReceiver: onReceive
07-01 12:11:02.340  7080  7186 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-01 12:11:02.340  7080  7186 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:11:02.340  7080  7186 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:11:02.340  7080  7186 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-01 12:11:02.340   322  1389 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7080
07-01 12:11:02.341   322  1389 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-01 12:11:02.341   322  1389 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-01 12:11:02.341   322  1389 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-01 12:11:02.341  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.341   322  1389 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-01 12:11:02.341   322  1389 V voice   : voice_set_parameters: exit with code(0)
07-01 12:11:02.341   322  1389 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-01 12:11:02.341   322  1389 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-01 12:11:02.341   322  1389 V msm8974_platform: platform_set_parameters: exit with code(0)
07-01 12:11:02.341   322  1389 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-01 12:11:02.341   322  1389 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-01 12:11:02.341   322  1389 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-01 12:11:02.342  7080  7186 V ToneGenerator: ToneGenerator destructor
07-01 12:11:02.342  7080  7186 V ToneGenerator: stopTone
07-01 12:11:02.342  7080  7186 V ToneGenerator: Delete Track: 0xb4928080
07-01 12:11:02.342  7080  7186 V AudioTrack: ~AudioTrack, releasing session i,d from 7080 on behalf of 7080
07-01 12:11:02.342   322  1390 V AudioFlinger: releasing 26 from 7080 for 7080
07-01 12:11:02.342   322  1390 V AudioFlinger:  decremented refcount to 0
07-01 12:11:02.342   322  1390 V AudioFlinger: purging stale effects
07-01 12:11:02.343  7080  7080 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:02.343   322  1390 V AudioPolicyService: AudioCommandThread() adding release output 2
07-01 12:11:02.343   322  1390 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-01 12:11:02.343   322  1261 V AudioPolicyService: AudioCommandThread() waking up
07-01 12:11:02.343   322  1261 V AudioPolicyService: AudioCommandThread() processing release output 2
07-01 12:11:02.343   322  1261 V AudioPolicyManager: releaseOutput() 2
07-01 12:11:02.343   322  1261 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 12:11:02.343   322  1390 V AudioFlinger: PlaybackThread::Track destructor
07-01 12:11:02.343   322  1390 V AudioFlinger: removeClient_l() pid 7080, calling pid 322
07-01 12:11:02.344  1036  1950 W Process : Unable to open /proc/7187/status
07-01 12:11:02.344  7080  7080 D A2dpService: Received start request. Starting profile...
07-01 12:11:02.344  7080  7080 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-01 12:11:02.345  7080  7180 V LGMDMManager: Create singleton instance
07-01 12:11:02.345  7080  7080 V Avrcp   : make
07-01 12:11:02.346  7080  7080 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-01 12:11:02.346  7080  7080 I bluedroid-qcom: get_profile_interface avrcp
07-01 12:11:02.349  7080  7180 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-01 12:11:02.351  7080  7080 V AudioManager: registerRemoteController: size of Media player list: 0
07-01 12:11:02.352  7080  7080 E AudioManager: No RCC entry present to update
07-01 12:11:02.352  7080  7080 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-01 12:11:02.354  7080  7080 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-01 12:11:02.355  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-01 12:11:02.355  7080  7080 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-01 12:11:02.358  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-01 12:11:02.366  7161  7161 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:02.366  7161  7161 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 12:11:02.387  7161  7161 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d24beb9
07-01 12:11:02.387  7161  7161 D AppUp4:CustFacade: isCustomizationCompleted : false
07-01 12:11:02.388  7161  7161 D AppUp4:CustFacade: isPhone : true
07-01 12:11:02.388  7161  7161 D AppUp4:CustModeStarterReceiver: begin check event
07-01 12:11:02.388  7161  7161 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-01 12:11:02.388  7161  7161 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-01 12:11:02.389  7161  7188 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-01 12:11:02.389  7161  7188 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-01 12:11:02.389  7161  7188 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-01 12:11:02.392  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:02.392  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:11:02.393  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:02.396  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-01 12:11:02.399  4321  7192 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 12:11:02.401  4321  7193 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:02.401  4321  7193 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:11:02.428  1036  1576 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7194 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-01 12:11:02.459  1036  1737 V SIM_STK : Menu title from STK is T-Mobile
07-01 12:11:02.459  1036  1737 V SIM_STK : Menu title from STK is T-Mobile
07-01 12:11:02.473  7194  7194 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 12:11:02.473  7194  7194 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:11:02.474  7194  7194 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 12:11:02.475  7194  7194 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-01 12:11:02.516  1036  1985 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-01 12:11:02.526  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-01 12:11:02.529  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 12:11:02.530  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-01 12:11:02.530  7080  7080 I BluetoothA2dpServiceJni: classInitNative
,07-01 12:11:02.530  7080  7080 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-01 12:11:02.531  7080  7080 D A2dpStateMachine: make
07-01 12:11:02.532  7080  7080 I bluedroid-qcom: get_profile_interface a2dp
07-01 12:11:02.532  7080  7212 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-01 12:11:02.534  7080  7080 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-01 12:11:02.534  7080  7080 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-01 12:11:02.535  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.535  7080  7211 D A2dpStateMachine: Enter Disconnected: -2
07-01 12:11:02.535  7080  7080 I BluetoothHidServiceJni: classInitNative: succeeds
07-01 12:11:02.537  7080  7080 D HidService: Received start request. Starting profile...
07-01 12:11:02.537  7080  7080 I bluedroid-qcom: get_profile_interface hidhost
07-01 12:11:02.537  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.537  7080  7080 I BluetoothHealthServiceJni: classInitNative: succeeds
07-01 12:11:02.539  7080  7080 D HealthService: Received start request. Starting profile...
07-01 12:11:02.542  7080  7080 I bluedroid-qcom: get_profile_interface health
07-01 12:11:02.542  7080  7080 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-01 12:11:02.542  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
,07-01 12:11:02.543  7080  7080 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-01 12:11:02.544  7080  7080 D PanService: Received start request. Starting profile...
07-01 12:11:02.544  7080  7080 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 12:11:02.544  7080  7080 I bluedroid-qcom: get_profile_interface pan
07-01 12:11:02.548  7080  7080 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-01 12:11:02.548  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.549  7080  7080 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-01 12:11:02.549  7194  7194 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
07-01 12:11:02.553  7080  7080 D BtGatt.DebugUtils: handleDebugAction() action=null
07-01 12:11:02.553  7080  7080 D BtGatt.GattService: Received start request. Starting profile...
07-01 12:11:02.553  7080  7080 D BtGatt.GattService: start()
07-01 12:11:02.553  7080  7080 I bluedroid-qcom: get_profile_interface gatt
07-01 12:11:02.553  7080  7080 D BtGatt.AdvertiseManager: advertise manager created
07-01 12:11:02.559  7194  7194 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
07-01 12:11:02.565  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
,07-01 12:11:02.569  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.570  7080  7080 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-01 12:11:02.573  7080  7080 V BluetoothMapService: BluetoothMapBinder()
07-01 12:11:02.574  7080  7080 D BluetoothMapService: Received start request. Starting profile...
07-01 12:11:02.574  7080  7080 D BluetoothMapService: start()
07-01 12:11:02.578  7080  7080 D BluetoothMapEmailSettingsLoader: Found 0 applications
,07-01 12:11:02.578  7080  7080 D BluetoothMapEmailAppObserver: createReceiver()
07-01 12:11:02.579  7080  7080 D BluetoothMapEmailAppObserver: initObservers()
07-01 12:11:02.579  7080  7080 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-01 12:11:02.581  7194  7194 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-01 12:11:02.588  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:02.588  7080  7080 D HeadsetStateMachine: Proxy object connected
07-01 12:11:02.589  7080  7080 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-01 12:11:02.589  7080  7080 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,07-01 12:11:02.590  7080  7186 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 12:11:02.591  7080  7186 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-01 12:11:02.591  7080  7186 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-01 12:11:02.593  7080  7080 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:02.593  7080  7080 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:11:02.593  7080  7080 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 12:11:02.593  7080  7080 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 12:11:02.593  7080  7080 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:02.593  7080  7080 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-01 12:11:02.596  7080  7080 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:02.599  7080  7080 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:02.601  7080  7080 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,07-01 12:11:02.601  7080  7080 V PanService: [BTUI] SIM Extra State :ABSENT
,07-01 12:11:02.604  7080  7080 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:02.605  7080  7080 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
07-01 12:11:02.605  7080  7080 V BluetoothMapService: Handler(): got msg=1
07-01 12:11:02.606  7080  7180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-01 12:11:02.606  7080  7180 I bluedroid-qcom: enable
07-01 12:11:02.606  7080  7220 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-01 12:11:02.606  7080  7220 I bt-btu  : btu_task pending for preload complete event
07-01 12:11:02.606  7080  7180 I bt_hci_bdroid: init
07-01 12:11:02.607  7080  7180 I bt_vendor: bt-vendor : init
07-01 12:11:02.607  7080  7180 I bt_vendor: bt-vendor : get_bt_soc_type
07-01 12:11:02.607  7080  7180 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-01 12:11:02.607  7080  7180 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-01 12:11:02.607  7080  7180 D bt_userial_mct: userial_init
07-01 12:11:02.607  7080  7180 D bt_hci_bdroid: set_power 1
07-01 12:11:02.607  7080  7180 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-01 12:11:02.607  7080  7180 I bt_vendor: Starting hciattach daemon
07-01 12:11:02.607  7080  7180 I bt_vendor: try to set true
07-01 12:11:02.608  7194  7194 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:02.609  7194  7194 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 12:11:02.603  7223  7223 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:02.603  7223  7223 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-01 12:11:02.625  7224  7224 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-01 12:11:02.682  7233  7233 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-01 12:11:02.688  7234  7234 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-01 12:11:02.702  7236  7236 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
07-01 12:11:02.703  7194  7194 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-01 12:11:02.713  7237  7237 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,07-01 12:11:02.722  7238  7238 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
07-01 12:11:02.731  7239  7239 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,07-01 12:11:02.743  3424  3424 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-01 12:11:02.743  3424  3424 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:02.743  3424  3424 I LgeMiscReceiver: networkInfo.isConnected() = false
07-01 12:11:02.749  7194  7194 I HubEmail: JNI_OnLoad()
07-01 12:11:02.749  7194  7194 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:11:02.749  7194  7194 I HubEmail: registerNatives()
07-01 12:11:02.749  7194  7194 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,07-01 12:11:02.749  7194  7194 I HubEmail: registerNativeMethods()
07-01 12:11:02.749  7194  7194 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:11:02.749  7194  7194 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-01 12:11:02.750  7241  7241 I libmdmdetect: ESOC framework not supported
07-01 12:11:02.751  7241  7241 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
07-01 12:11:02.758  7241  7241 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-01 12:11:02.758  7241  7241 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-01 12:11:02.758  7241  7241 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,07-01 12:11:02.758  7241  7241 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-01 12:11:02.758  7241  7241 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-01 12:11:02.758  7241  7241 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
,07-01 12:11:02.758  7241  7241 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-01 12:11:02.786  1036  1985 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7248 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,07-01 12:11:02.789  6748  7244 W FormManager: Network not available. Please check & try again.
07-01 12:11:02.792  7194  7246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:02.792  6748  7245 V FormManager: Network unavailable.
07-01 12:11:02.795  7241  7247 E QC-QMI  : qmi_client [7241] 14: failed to locate client data
07-01 12:11:02.796   451   451 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-01 12:11:02.796   451   451 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
07-01 12:11:02.805  6748  7245 V FormManager: Network unavailable.
,07-01 12:11:02.809  1036  1051 I ActivityManager: Killing 6104:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
07-01 12:11:02.929  7265  7265 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-01 12:11:02.947  1036  2076 W libprocessgroup: failed to open /acct/uid_10080/pid_6104/cgroup.procs: No such file or directory
,07-01 12:11:02.957  7266  7266 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,07-01 12:11:03.000  7248  7248 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:03.000  7248  7248 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 12:11:03.002  7248  7248 D PhoneMonitor: Register our PhoneStateListener
07-01 12:11:03.009  7080  7180 I bt_vendor: bluetooth satus is on
07-01 12:11:03.009  7080  7180 D bt_hci_bdroid: preload
07-01 12:11:03.009  7080  7222 D bt_userial_mct: userial_open(port:0)
07-01 12:11:03.009  7080  7222 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
07-01 12:11:03.012  7080  7222 I bt_vendor: Done intiailizing UART
,07-01 12:11:03.012  7080  7222 I bt_vendor: Done intiailizing UART
07-01 12:11:03.013  7080  7222 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-01 12:11:03.013  7080  7222 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-01 12:11:03.013  7080  7220 I bt-btu  : btu_task received preload complete event
07-01 12:11:03.013  7080  7269 D bt_userial_mct: Entering userial_read_thread()
07-01 12:11:03.013  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-01 12:11:03.013  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-01 12:11:03.014  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_HCI
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_AVDT
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_A2D
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_BNEP
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_BTM
,07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_GAP
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_PAN
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_SDP
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_GATT
,07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_SMP
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-01 12:11:03.017  7080  7220 I         : BTE_InitTraceLevels -- TRC_BTIF
07-01 12:11:03.017  7248  7248 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-01 12:11:03.020  7248  7248 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-01 12:11:03.036  7248  7248 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-01 12:11:03.037  7248  7248 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-01 12:11:03.038  7248  7248 D TelephonyAutoProfiling: [parse] Load xml
07-01 12:11:03.044  7248  7248 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-01 12:11:03.044  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
07-01 12:11:03.044  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
07-01 12:11:03.044  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
07-01 12:11:03.044  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
07-01 12:11:03.044  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
07-01 12:11:03.044  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
07-01 12:11:03.044  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
07-01 12:11:03.044  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
07-01 12:11:03.045  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
07-01 12:11:03.045  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
07-01 12:11:03.045  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
07-01 12:11:03.045  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
07-01 12:11:03.045  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
07-01 12:11:03.045  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
07-01 12:11:03.045  7248  7248 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
07-01 12:11:03.045  7248  7248 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,07-01 12:11:03.054  7248  7248 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-01 12:11:03.057  1036  2076 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7271 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:03.058  1036  2076 I ActivityManager: Killing 6516:com.google.android.apps.docs/u0a61 (adj 15): empty #17
07-01 12:11:03.071  7080  7220 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-01 12:11:03.071  7080  7220 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
,07-01 12:11:03.071  7080  7220 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
07-01 12:11:03.084  7080  7184 E bt-btif : Calling BTA_HhEnable
07-01 12:11:03.084  7080  7184 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-01 12:11:03.084  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-01 12:11:03.085  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-01 12:11:03.085  7080  7184 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
07-01 12:11:03.085  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,07-01 12:11:03.085  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-01 12:11:03.085  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,07-01 12:11:03.094  7080  7220 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,07-01 12:11:03.094  7080  7220 W bt-smp  : Plain text(LSB ~ MSB) = 9a 48 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
,07-01 12:11:03.094  7080  7220 W bt-smp  : Encrypted text(LSB ~ MSB) = f4 95 68 3d f5 f5 e6 6c ca 5e 7f ed cb 1b 63 87 
07-01 12:11:03.094  7080  7220 W bt-btm  : Stopping oneshot timer
07-01 12:11:03.197  1036  1737 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:11:03.197  1036  1737 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2e8008df mBinding = false
07-01 12:11:03.198  1036  2035 W libprocessgroup: failed to open /acct/uid_10061/pid_6516/cgroup.procs: No such file or directory
,07-01 12:11:03.206  7080  7184 D BluetoothAdapterProperties: Name is: G3
07-01 12:11:03.216  1036  1097 D BluetoothManagerService: Message: 2
,07-01 12:11:03.216  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:11:03.217  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:11:03.217  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 12:11:03.217  7080  7184 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:11:03.218  7080  7184 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 12:11:03.218  7080  7184 D bt_hci_bdroid: postload
07-01 12:11:03.218  7080  7184 D bte_conf: Device ID record 1 : primary
07-01 12:11:03.218  7080  7184 D bte_conf:   vendorId            = 00c4
07-01 12:11:03.218  7080  7184 D bte_conf:   vendorIdSource      = 0001
07-01 12:11:03.218  7080  7184 D bte_conf:   product             = 13a1
07-01 12:11:03.218  7080  7184 D bte_conf:   version             = 1000
07-01 12:11:03.218  7080  7184 D bte_conf:   clientExecutableURL = 
07-01 12:11:03.218  7080  7184 D bte_conf:   serviceDescription  = 
07-01 12:11:03.218  7080  7184 D bte_conf:   documentationURL    = 
07-01 12:11:03.218  7080  7184 D bte_conf: bte_load_did_conf no section named DID2.
07-01 12:11:03.218  7080  7222 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 12:11:03.218  7080  7222 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 12:11:03.218  7080  7220 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-01 12:11:03.219  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:03.220  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-01 12:11:03.220  7080  7180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 12:11:03.220  7080  7180 D BluetoothAdapterProperties: ScanMode =  20
07-01 12:11:03.220  7080  7180 D BluetoothAdapterProperties: State =  11
07-01 12:11:03.220  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-01 12:11:03.220  7080  7180 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-01 12:11:03.220  7080  7180 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-01 12:11:03.213  7290  7290 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:03.220  7080  7180 D BluetoothAdapterProperties: Setting state to 12
07-01 12:11:03.220  7080  7180 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-01 12:11:03.220  7080  7184 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-01 12:11:03.213  7290  7290 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:03.221  7080  7184 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 12:11:03.222  7080  7222 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 12:11:03.222  7080  7180 I BluetoothAdapterState: Entering On State
07-01 12:11:03.223  7080  7222 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 12:11:03.223  7080  7222 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 12:11:03.224  7080  7222 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 12:11:03.224  7080  7222 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 12:11:03.225  7080  7269 E bt_mct  : hci lib postload completed
07-01 12:11:03.226  7080  7180 D LGBluetoothServiceAdapter: [BTUI] OnState
07-01 12:11:03.226  7080  7180 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-01 12:11:03.226  7080  7180 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-01 12:11:03.226  7080  7180 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-01 12,:11:03.228  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:03.228  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:03.228  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:03.228  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:03.228  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:03.228  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:03.228  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:03.228  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:03.230  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:03.271  7295  7295 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,07-01 12:11:03.273  7080  7180 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-01 12:11:03.371  1036  1051 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7297 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-01 12:11:03.372  1036  1051 I ActivityManager: Killing 6135:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,07-01 12:11:03.390  7080  7184 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-01 12:11:03.390  7080  7184 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-01 12:11:03.496  1036  1773 W libprocessgroup: failed to open /acct/uid_10097/pid_6135/cgroup.procs: No such file or directory
,07-01 12:11:03.517  1036  1097 D BluetoothManagerService: Sending off request.
,07-01 12:11:03.518  7080  7098 D LGBluetoothServiceAdapter: [BTUI] Precleanup
07-01 12:11:03.519  7080  7180 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
07-01 12:11:03.519  7080  7180 D BluetoothAdapterProperties: Setting state to 13
07-01 12:11:03.519  7080  7180 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 12:11:03.519  7080  7180 D BluetoothAdapterProperties: onBluetoothDisable()
07-01 12:11:03.519  1036  1097 D BluetoothManagerService: Message: 60
07-01 12:11:03.519  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-01 12:11:03.519  7080  7180 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-01 12:11:03.519  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-01 12:11:03.519  1881  2562 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:11:03.521  7080  7184 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:11:03.521  7080  7180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-01 12:11:03.522  7080  7180 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 12:11:03.522  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
07-01 12:11:03.523  7080  7220 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
07-01 12:11:03.523  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
07-01 12:11:03.523  7080  7220 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:11:03.528  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:03.528  1881  3992 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:11:03.530  1881  1881 D BluetoothHeadset: Proxy object connected
07-01 12:11:03.531  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:03.531  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:03.531  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:03.531  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:03.531  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:03.531  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:03.531  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:03.531  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:03.533  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:03.535  1881  1881 D BluetoothHeadset: Proxy object connected
07-01 12:11:03.536  6966  6981 D BluetoothInputDevice: on,BluetoothStateChange: up=true
07-01 12:11:03.540  6966  6982 D BluetoothPan: onBluetoothStateChange on: true
07-01 12:11:03.541  6966  6982 D BluetoothPan: onBluetoothStateChange call bindService
07-01 12:11:03.545  6966  6966 D BluetoothInputDevice: Proxy object connected
07-01 12:11:03.545  6966  6966 D HidProfile: Bluetooth service connected
07-01 12:11:03.548  6966  7314 D BluetoothMap: onBluetoothStateChange: up=true
07-01 12:11:03.551  6966  6981 D BluetoothPbap: onBluetoothStateChange: up=true
07-01 12:11:03.552  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:11:03.553  1036  1036 D BluetoothHeadset: Proxy object connected
07-01 12:11:03.553  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 12:11:03.554  6966  6966 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 12:11:03.554  6966  6966 D PanProfile: Bluetooth service connected
07-01 12:11:03.555  1881  1896 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:11:03.556  1036  1036 D BluetoothA2dp: Proxy object connected
07-01 12:11:03.557  1881  1881 D BluetoothHeadset: Proxy object connected
07-01 12:11:03.558  1036  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-01 12:11:03.558  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-01 12:11:03.558  1036  1097 D BluetoothManagerService: Message: 60
07-01 12:11:03.558  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
07-01 12:11:03.558  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
07-01 12:11:03.559  6966  6966 D BluetoothMap: Proxy object connected
07-01 12:11:03.559  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 12:11:03.559  6966  6966 D MapProfile: Bluetooth service connected
07-01 12:11:03.559  6966  6966 D BluetoothMap: getConnectedDevices()
07-01 12:11:03.560  6966  6966 D BluetoothMap: Bluetooth is Not enabled
07-01 12:11:03.561  1968  1968 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.561  1968  2179 D LGBluetoothAPIService: Message: 1
07-01 12:11:03.561  1968  2179 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
07-01 12:11:03.562  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-01 12:11:03.562  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-01 12:11:03.563  1036  1097 D BluetoothManagerService: Message: 40
07-01 12:11:03.563  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-01 12:11:03.565  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 12:11:03.567  1968  1968 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.569  1968  2179 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-01 12:11:03.570  7080  7080 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.570  7080  7080 D BluetoothMapService: STATE_ON
07-01 12:11:03.571  7080  7080 D LGBluetoothAPIServer: [BTUI] onCreate()
07-01 12:11:03.572  7080  7080 D LGBluetoothAPIServer: [BTUI] onBind()
07-01 12:11:03.574  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
07-01 12:11:03.574  7080  7080 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.574  7080  7080 D BluetoothMapService: STATE_TURNING_OFF
07-01 12:11:03.574  1968  1968 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-01 12:11:03.574  1968  2179 D LGBluetoothAPIService: Message: 100
07-01 12:11:03.574  1968  2179 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-01 12:11:03.576  6966  6966 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:11:03.581  6699  6699 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:11:3
07-01 12:11:03.582  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 12:11:03.584  6699  6699 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-01 12:11:03.584  6699  6699 D Weather.Utils: 2 : All the weather widget is gone.
07-01 12:11:03.584  6699  6699 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-01 12:11:03.586  6699  6699 D WeatherAncestor: connectivity changed - connection : true
07-01 12:11:03.588  6699  6699 D WeatherService: 2 : isServiceAlived():false forecastCache:null
07-01 12:11:03.588  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:03.588  7080  7080 V BluetoothPbapService: Pbap Service onCreate
07-01 12:11:03.588  7080  7080 V BluetoothPbapService: Starting PBAP service
07-01 12:11:03.589  7080  7080 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-01 12:11:03.590  7080  7080 V BluetoothPbapService: Pbap Service onBind
07-01 12:11:03.590  6966  6966 D BluetoothPbap: Proxy object connected
07-01 12:11:03.590  7080  7080 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.590  7080  7080 V BluetoothPbapService: state: 13
07-01 12:11:03.591  7080  7080 V BluetoothPbapService: Pbap Service closeService in
07-01 12:11:03.591  6966  6966 D PbapServerProfile: Bluetooth service connected
07-01 12:11:03.592  7080  7080 V BluetoothPbapService: successfully stopped pbap service
07-01 12:11:03.592  7080  7080 V BluetoothPbapService: Pbap Service closeService out
07-01 12:11:03.592  7080  7080 V BluetoothMapService: Handler(): got msg=4
07-01 12:11:03.592  7080  7080 D BluetoothMapService: MAP Service closeService in
07-01 12:11:03.592  7080  7080 D BluetoothMapMasInstance: MAP Service shutdown
07-01 12:11:03.592  7080  7080 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:11:03.592  7080  7080 V BluetoothMapService: MAP Service closeService out
07-01 12:11:03.593  7080  7080 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:11:03.593  7080  7080 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.593  7080  7080 V BluetoothPbapReceiver: ***********state = 12
07-01 12:11:03.594  6966  6966 D BluetoothPbap: Proxy object disconnected
07-01 12:11:03.594  6966  6966 D PbapServerProfile: Bluetooth service disconnected
07-01 12:11:03.594  7080  7080 V BluetoothPbapService: Pbap Service onDestroy
07-01 12:11:03.594  7080  7080 V BluetoothPbapService: Pbap Service closeService in
07-01 12:11:03.594  7080  7080 V BluetoothPbapService: Pbap Service closeService out
07-01 12:11:03.594  7080  7080 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-01 12:11:03.595  2225  2225 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 12:11:03.596  2225  2225 D c       : Getting all permits...
07-01 12:11:03.596  2225  2225 D a       : Opening database...
07-01 12:11:03.597  6699  6699 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-01 12:11:03.597  6699  6699 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-01 12:11:03.597  6699  6699 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
07-01 12:11:03.599  2225  2225 D a       : Opening database auth.proximity.permit_store...
07-01 12:11:03.600  2225  2225 D a       : Closing database...
07-01 12:11:03.607  6966  6966 D BluetoothPermissionRequest: onReceive
07-01 12:11:03.608  6966  6966 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 12:11:03.609  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,07-01 12:11:03.612  7080  7080 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-01 12:11:03.613  7080  7080 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-01 12:11:03.614  6699  6699 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-01 12:11:03.614  6699  6699 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:11:3
07-01 12:11:03.624  7080  7080 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,07-01 12:11:03.634  7080  7080 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,07-01 12:11:03.634  7080  7080 V BtOppService: onCreate
07-01 12:11:03.637  7080  7080 V BluetoothOppNotification: send message
,07-01 12:11:03.644  1036  2332 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7321 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-01 12:11:03.644  7080  7320 V BtOppService: Deleted complete outbound shares, number =  0
07-01 12:11:03.645  7080  7320 V BtOppService: Deleted complete inbound failed shares, number = 0
07-01 12:11:03.646  7080  7320 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,07-01 12:11:03.647  7080  7320 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13ab1928 on behalf of 
07-01 12:11:03.655  1036  2332 I ActivityManager: Killing 6552:com.lge.eula/1000 (adj 15): empty #17
07-01 12:11:03.656   385   385 I art     : Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 13.821ms
,07-01 12:11:03.669   385   385 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 251us total 11.842ms
,07-01 12:11:03.681   385   385 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 223us total 11.050ms
,07-01 12:11:03.772  7080  7080 D BluetoothOppPreference: Dumping Names:  
07-01 12:11:03.772  7080  7080 D BluetoothOppPreference: {}
07-01 12:11:03.772  7080  7080 D BluetoothOppPreference: Dumping Channels:  
07-01 12:11:03.772  7080  7080 D BluetoothOppPreference: {}
07-01 12:11:03.772  7080  7080 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
07-01 12:11:03.773  7080  7080 V BtOppService: onStartCommand
07-01 12:11:03.777  7080  7080 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
07-01 12:11:03.777  1036  1737 W libprocessgroup: failed to open /acct/uid_1000/pid_6552/cgroup.procs: No such file or directory
07-01 12:11:03.778  7080  7080 V BluetoothOppNotification: previous thread is not finished yet
07-01 12:11:03.778  7080  7080 V BtOppService: ContentObserver received notification
07-01 12:11:03.778  7080  7080 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
07-01 12:11:03.778  7080  7080 V BtOppService: ContentObserver received notification
07-01 12:11:03.778  7080  7080 E BtOppService: [BTUI] updateFromProvider : mListenStarted is null
,07-01 12:11:03.786  7080  7080 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.786  7080  7080 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-01 12:11:03.803  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:03.804  7080  7080 V BluetoothFtpService: Ftp Service onCreate
07-01 12:11:03.804  7080  7080 I BluetoothFtpService: Ftp Service onCreate
07-01 12:11:03.804  7080  7080 V BluetoothFtpService: Ftp Service onStartCommand
07-01 12:11:03.804  7080  7080 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.804  7080  7080 V BluetoothFtpService: Starting Listening on sockets
07-01 12:11:03.804  7080  7080 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:11:03.804  7080  7080 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 12:11:03.804  7080  7080 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 12:11:03.804  7080  7080 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.804  7080  7080 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-01 12:11:03.805  7080  7080 V BluetoothSapReceiver: Calling SAP service start service with action = null
,07-01 12:11:03.807  7080  7080 V BluetoothFtpService: Handler(): got msg=1
07-01 12:11:03.809  7080  7080 V BluetoothFtpService: Ftp Service closeService
07-01 12:11:03.811  7080  7080 V BluetoothFtpService: successfully stopped ftp service
07-01 12:11:03.820  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 12:11:03.826  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:03.826  7080  7080 V BluetoothSapService: Sap Service onCreate
07-01 12:11:03.828  7080  7080 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.828  7080  7080 V BluetoothSapService: state: 12
07-01 12:11:03.828  7080  7080 V BluetoothSapService: Starting SAP server process
,07-01 12:11:03.830  7080  7080 V BluetoothFtpService: Ftp Service onDestroy
07-01 12:11:03.830  7080  7080 V BluetoothFtpService: Ftp Service closeService
07-01 12:11:03.830  7080  7080 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:11:03.830  7080  7080 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.830  7080  7080 V BluetoothPbapReceiver: ***********state = 13
07-01 12:11:03.823  7341  7341 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:03.823  7341  7341 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:03.832  7080  7080 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
07-01 12:11:03.834  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:03.834  7080  7080 V BluetoothPbapService: Pbap Service onCreate
07-01 12:11:03.834  7080  7080 V BluetoothPbapService: Starting PBAP service
07-01 12:11:03.835  7080  7080 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-01 12:11:03.835  7080  7080 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.835  7080  7080 V BluetoothPbapService: state: 13
07-01 12:11:03.835  7080  7080 V BluetoothPbapService: Pbap Service closeService in
07-01 12:11:03.836  2225  2225 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 12:11:03.838  7080  7080 V BluetoothPbapService: successfully stopped pbap service
07-01 12:11:03.838  7080  7080 V BluetoothPbapService: Pbap Service closeService out
07-01 12:11:03.838  7080  7080 V BluetoothPbapService: Pbap Service onDestroy
07-01 12:11:03.838  7080  7080 V BluetoothPbapService: Pbap Service closeService in
07-01 12:11:03.838  7080  7080 V BluetoothPbapService: Pbap Service closeService out
07-01 12:11:03.838  7080  7080 D LGBluetoothPbapAdapter: [BTUI] cleanup
07-01 12:11:03.840  7341  7341 V BT_SAP  : Event pipe created
07-01 12:11:03.840  7341  7341 V BT_SAP  : create_server_socket qcom.sap.server
07-01 12:11:03.840  7341  7341 V BT_SAP  : created socket fd 6
07-01 12:11:03.841  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:03.841  1036  1537 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 12:11:03.845  6966  6966 D DockEventReceiver: finishStartingService: stopping service
07-01 12:11:03.850  6966  6966 D LGBluetoothAuthorization: [BTUI] cancel All Notification
07-01 12:11:03.853  6966  6966 D BluetoothPermissionRequest: onReceive
07-01 12:11:03.853  6966  6966 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,07-01 12:11:03.857  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 12:11:03.860  7080  7080 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
07-01 12:11:03.860  7080  7080 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
07-01 12:11:03.860  7080  7080 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
07-01 12:11:03.863  7080  7080 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.863  7080  7080 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-01 12:11:03.865  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:03.865  7080  7080 V BluetoothFtpService: Ftp Service onCreate
07-01 12:11:03.865  7080  7080 I BluetoothFtpService: Ftp Service onCreate
,07-01 12:11:03.866  7080  7080 V BluetoothFtpService: Ftp Service onStartCommand
07-01 12:11:03.866  7080  7080 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.866  7080  7080 V BluetoothFtpService: Ftp Service closeService
07-01 12:11:03.867  7080  7080 V BluetoothFtpService: successfully stopped ftp service
07-01 12:11:03.867  7080  7080 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:11:03.867  7080  7080 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 12:11:03.867  7080  7080 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 12:11:03.868  7080  7080 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.868  7080  7080 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
07-01 12:11:03.868  7080  7080 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-01 12:11:03.868  7080  7080 V BluetoothFtpService: Ftp Service onDestroy
07-01 12:11:03.868  7080  7080 V BluetoothFtpService: Ftp Service closeService
07-01 12:11:03.871  7080  7080 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.871  7080  7080 V BluetoothSapService: state: 13
07-01 12:11:03.871  7080  7080 V BluetoothSapService: Stopping SAP server process
07-01 12:11:03.873  7080  7080 V BluetoothSapService: Sap Service closeSapService in
07-01 12:11:03.873  7080  7080 V BluetoothSapService: Close listen Socket : 
07-01 12:11:03.873  7080  7080 V BluetoothSapService: Close rfcomm Socket : 
07-01 12:11:03.873  7080  7080 V BluetoothSapService: Close sapd  Socket : 
07-01 12:11:03.874  7080  7080 V BluetoothSapService: Sap Service closeSapService out
07-01 12:11:03.874  7080  7080 V BluetoothSapService: Sap Service onDestroy
07-01 12:11:03.874  7080  7080 V BluetoothSapService: Sap Service closeSapService in
07-01 12:11:03.874  7080  7080 V BluetoothSapService: Close listen Socket : 
07-01 12:11:03.874  7080  7080 V BluetoothSapService: Close rfcomm Socket : 
07-01 12:11:03.874  7080  7080 V BluetoothSapService: Close sapd  Socket : 
07-01 12:11:03.875  7080  7080 V BluetoothSapService: Sap Service closeSapService out
07-01 12:11:03.889   278   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:11:03.889   278   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-01 12:11:03.889   278   343 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:11:03.889  7321  7343 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-01 12:11:03.891   278   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:11:03.891   278   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-01 12:11:03.891   278   343 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:11:03.891  7321  7343 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,07-01 12:11:03.899   278   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:11:03.899   278   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-01 12:11:03.899   278   343 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:11:03.900  7321  7346 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-01 12:11:03.901   278   343 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-01 12:11:03.901   278   343 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-01 12:11:03.901   278   343 W Vold    : Returning OperationFailed - no handler for errno 0
07-01 12:11:03.902  7321  7346 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
07-01 12:11:03.904  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-01 12:11:03.904  6891  6946 I jxcore-log: 
,07-01 12:11:03.910  1036  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
07-01 12:11:03.910  1036  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
07-01 12:11:04.050  7321  7321 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,07-01 12:11:04.063  7321  7321 I LibraryLoader: Loading: webviewchromium
,07-01 12:11:04.069  7321  7321 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 1396-1403)
,07-01 12:11:04.069  7321  7321 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:11:04.076  7321  7321 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {32efd0ba}
,07-01 12:11:04.078  7321  7321 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 12:11:04.078  7321  7321 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 12:11:04.090  7321  7321 I BrowserStartupController: Initializing chromium process, renderers=0
,07-01 12:11:04.092  7321  7321 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:11:04.108  7321  7321 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,07-01 12:11:04.110  7321  7321 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,07-01 12:11:04.110  7321  7321 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
07-01 12:11:04.115   322   322 V AudioPolicyService: registerClient() client 0xb04104c0, uid 10093
07-01 12:11:04.118  7321  7367 W AudioManagerAndroid: Requires BLUETOOTH permission
07-01 12:11:04.127  7321  7321 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:11:04.127  7321  7321 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:11:04.127  7321  7321 I Adreno-EGL: Build Date: 12/12/14 금
07-01 12:11:04.127  7321  7321 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 12:11:04.127  7321  7321 I Adreno-EGL: Remote Branch: 
07-01 12:11:04.127  7321  7321 I Adreno-EGL: Local Patches: 
07-01 12:11:04.127  7321  7321 I Adreno-EGL: Reconstruct Branch: 
,07-01 12:11:04.217  6891  6943 D io.jxcore.node.ConnectivityMonitor: stop
,07-01 12:11:04.217  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:11:04.233  7321  7321 I NSApplication: Starting up...
,07-01 12:11:04.309  1036  2332 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7380 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-01 12:11:04.310  1036  2332 I ActivityManager: Killing 6065:com.android.vending/u0a44 (adj 15): empty #17
,07-01 12:11:04.314  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-01 12:11:04.314  6891  6946 I jxcore-log: 
07-01 12:11:04.339  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-01 12:11:04.339  6891  6946 I jxcore-log: 
,07-01 12:11:04.344  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-01 12:11:04.344  6891  6946 I jxcore-log: 
07-01 12:11:04.360  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-01 12:11:04.360  6891  6946 I jxcore-log: 
,07-01 12:11:04.364  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-01 12:11:04.364  6891  6946 I jxcore-log: 
,07-01 12:11:04.507  1036  1949 W libprocessgroup: failed to open /acct/uid_10044/pid_6065/cgroup.procs: No such file or directory
07-01 12:11:04.528  7080  7220 W bt-btif : ag scb idx 1 not allocated
07-01 12:11:04.528  7080  7220 E bt-btif : BTA AG is already disabled, ignoring ...
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:11:04.528  7080  7184 D bt_hci_bdroid: cleanup
,07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
07-01 12:11:04.528  7080  7220 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:11:04.529  7080  7220 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
07-01 12:11:04.529  7080  7220 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:11:04.529  7080  7220 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
07-01 12:11:04.529  7080  7222 I bt_lpm  : LPM is already off!!!
07-01 12:11:04.529  7080  7269 I bt_userial_mct: exiting userial_read_thread
07-01 12:11:04.529  7080  7269 D bt_userial_mct: Leaving userial_evt_read_thread()
07-01 12:11:04.532  7080  7184 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
07-01 12:11:04.532  7080  7222 I bt_vendor: hw_epilog_process
07-01 12:11:04.533  7080  7184 D bt_hci_bdroid: cleanup Finalizing cleanup
07-01 12:11:04.533  7080  7184 D bt_userial_mct: userial_close
07-01 12:11:04.533  7080  7184 E bt_userial_mct: pthread_join() FAILED result:3
07-01 12:11:04.533  7080  7184 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
07-01 12:11:04.533  7380  7380 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:11:04.765  7080  7184 D bt_hci_bdroid: set_power 0
07-01 12:11:04.765  7080  7184 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,07-01 12:11:04.765  7080  7184 I bt_vendor: bluetooth satus is on
07-01 12:11:04.765  7080  7184 I bt_vendor: bt-vendor : resetting BT status
07-01 12:11:04.765  7080  7184 I bt_vendor: Starting hciattach daemon
07-01 12:11:04.765  7080  7184 I bt_vendor: try to set false
07-01 12:11:04.767  7080  7184 I bt_vendor: Starting hciattach daemon
07-01 12:11:04.767  7080  7184 I bt_vendor: try to set false
07-01 12:11:04.768  7080  7184 I bt_vendor: cleanup
07-01 12:11:04.769  7080  7220 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-01 12:11:04.770  7080  7184 I GKI_LINUX: GKI_exit_task 0 done
07-01 12:11:04.770  7080  7184 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-01 12:11:04.771  7080  7180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 12:11:04.775  7080  7080 D HeadsetService: Received stop request...Stopping profile...
07-01 12:11:04.776  7080  7080 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 12:11:04.776  7080  7080 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:11:04.776  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:04.776  7080  7186 D HeadsetStateMachine: Exit Disconnected: -1
07-01 12:11:04.777  1036  1036 D BluetoothHeadset: Proxy object disconnected
07-01 12:11:04.777  1881  1881 D BluetoothHeadset: Proxy object disconnected
07-01 12:11:04.777  1881  1881 D BluetoothHeadset: Proxy object disconnected
07-01 12:11:04.777  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 12:11:04.777  1881  1881 D BluetoothHeadset: Proxy object disconnected
07-01 12:11:04.778  7080  7080 D A2dpService: Received stop request...Stopping profile...
,07-01 12:11:04.780  7080  7211 D A2dpStateMachine: Exit Disconnected: -1
07-01 12:11:04.782  7080  7080 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,07-01 12:11:04.785  7080  7080 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
07-01 12:11:04.785  7080  7080 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:11:04.785  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:04.786  1036  1036 D BluetoothA2dp: Proxy object disconnected
07-01 12:11:04.786  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-01 12:11:04.787  7080  7180 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 12:11:04.788  7080  7080 V BluetoothOppNotification: previous thread is not finished yet
07-01 12:11:04.788  7080  7080 D HeadsetStateMachine: Unbinding service...
07-01 12:11:04.788  7080  7080 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:11:04.788  7080  7080 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:11:04.788  7080  7080 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:11:04.788  7080  7080 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:11:04.788  7080  7080 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 12:11:04.788  7080  7080 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:11:04.788  7080  7080 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
07-01 12:11:04.789  7080  7080 D HidService: Received stop request...Stopping profile...
07-01 12:11:04.789  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:04.791  7080  7080 D HealthService: Received stop request...Stopping profile...
07-01 12:11:04.791  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:04.793  7080  7080 D PanService: Received stop request...Stopping profile...
07-01 12:11:04.794  6966  6966 D BluetoothInputDevice: Proxy object disconnected
07-01 12:11:04.794  6966  6966 D HidProfile: Bluetooth service disconnected
,07-01 12:11:04.795  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
,07-01 12:11:04.796  6966  6966 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 12:11:04.796  6966  6966 D PanProfile: Bluetooth service disconnected
07-01 12:11:04.796  7080  7080 D BtGatt.DebugUtils: handleDebugAction() action=null
07-01 12:11:04.797  7080  7080 D BtGatt.GattService: Received stop request...Stopping profile...
07-01 12:11:04.797  7080  7080 D BtGatt.GattService: stop()
07-01 12:11:04.797  7080  7080 D BtGatt.AdvertiseManager: advertise clients cleared
07-01 12:11:04.799  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:04.799  7080  7080 I BluetoothA2dpServiceJni: cleanupNative
07-01 12:11:04.799  7080  7212 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 12:11:04.800  7080  7080 I GKI_LINUX: GKI_exit_task 2 done
07-01 12:11:04.800  7080  7080 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-01 12:11:04.800  7080  7080 D BluetoothMapService: Received stop request...Stopping profile...
07-01 12:11:04.800  7080  7080 D BluetoothMapService: stop()
07-01 12:11:04.801  7080  7080 D BluetoothMapEmailAppObserver: deinitObservers()
07-01 12:11:04.801  7080  7080 D BluetoothMapEmailAppObserver: removeReceiver()
07-01 12:11:04.801  7080  7080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:04.802  7080  7080 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 12:11:04.802  7080  7080 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 12:11:04.802  7080  7080 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 12:11:04.803  7080  7080 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:11:04.803  7080  7080 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:11:04.803  7080  7080 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 12:11:04.803  7080  7080 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-01 12:11:04.804  7080  7080 V BluetoothMapService: Handler(): got msg=4
07-01 12:11:04.804  7080  7080 D BluetoothMapService: MAP Service closeService in
07-01 12:11:04.804  7080  7080 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:11:04.804  7080  7080 V BluetoothMapService: MAP Service closeService out
07-01 12:11:04.804  7080  7180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
07-01 12:11:04.804  7080  7180 D BluetoothAdapterProperties: Setting state to 10
07-01 12:11:04.804  7080  7180 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 12:11:04.804  7080  7080 D BluetoothMapService: cleanup()
07-01 12:11:04.804  7080  7080 D BluetoothMapService: MAP Service closeService in
07-01 12:11:04.804  7080  7080 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
07-01 12:11:04.804  7080  7080 V BluetoothMapService: MAP Service closeService out
07-01 12:11:04.804  1036  1097 D BluetoothManagerService: Message: 60
07-01 12:11:04.804  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
07-01 12:11:04.804  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
07-01 12:11:04.804  7080  7180 I BluetoothAdapterState: Entering OffState
07-01 12:11:04.805  1881  1897 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:11:04.805  6966  6966 D BluetoothMap: Proxy object disconnected
07-01 12:11:04.805  6966  6966 D MapProfile: Bluetooth service disconnected
07-01 12:11:04.805  1881  3997 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:11:04.805  6966  7314 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-01 12:11:04.806  6966  6981 D BluetoothPan: onBluetoothStateChange on: false
07-01 12:11:04.806  6966  6982 D BluetoothMap: onBluetoothStateChange: up=false
,07-01 12:11:04.806  6966  7314 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 12:11:04.807  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:11:04.807  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:11:04.807  1881  3992 D BluetoothHeadset: onBluetoothStateChange: up=false
07-01 12:11:04.808  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
07-01 12:11:04.808  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-01 12:11:04.809  1036  1097 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
07-01 12:11:04.809  1036  1097 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
07-01 12:11:04.809  1036  1097 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2e8008df mBinding = false
07-01 12:11:04.810  1036  1097 D BluetoothManagerService: Sending unbind request.
07-01 12:11:04.811  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
07-01 12:11:04.812  7080  7184 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-01 12:11:04.813  7080  7080 I GKI_LINUX: GKI_exit_task 1 done
07-01 12:11:04.813  7080  7080 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-01 12:11:04.813  7080  7080 I BluetoothServiceJni: cleanupNative: return from cleanup
07-01 12:11:04.813  7080  7080 I art     : --- WEIRD: removing null entry 249
07-01 12:11:04.813  7080  7080 W art     : JNI WARNING: DeleteGlobalRef(0x2003e6) failed to find entry
07-01 12:11:04.813  7080  7080 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
07-01 12:11:04.814  1968  1968 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:04.814  1968  2179 D LGBluetoothAPIService: Message: 2
07-01 12:11:04.814  1968  2179 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@35088c85 mBinding = false
07-01 12:11:04.814  1968  2179 D LGBluetoothAPIService: Sending unbind request.
07-01 12:11:04.814  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 12:11:04.815  2225  2225 I Coffee - BluetoothConnectionTracker: Bluetooth adapter off, revoking trust
07-01 12:11:04.817  7080  7080 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
07-01 12:11:04.818  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
07-01 12:11:04.818  6966  6966 D LGBluetoothEventManager: [BTUI] clear device connection state
07-01 12:11:04.819  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 12:11:04.819  7080  7080 I art     : System.exit called, status: 0
07-01 12:11:04.819  7080  7080 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-01 12:11:04.820  1603  1603 D BluetoothAdapter: 739472408: getState() :  mService = null. Returning STATE_OFF
07-01 12:11:04.820  1603  1603 D BluetoothAdapter: 739472408: getState() :  mService = null. Returning STATE_OFF
,07-01 12:11:04.822  6966  6966 D DockEventReceiver: finishStartingService: stopping service
07-01 12:11:04.840   322  1390 V AudioFlinger: 7080 died, releasing its sessions
07-01 12:11:04.840   322  1390 V AudioFlinger:  pid 1881 @ 0
07-01 12:11:04.840   322  1390 V AudioFlinger:  pid 3424 @ 1
07-01 12:11:04.840   322  1390 V AudioFlinger:  pid 3424 @ 2
07-01 12:11:04.840   322  1390 V AudioFlinger:  pid 1036 @ 3
,07-01 12:11:04.840  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
07-01 12:11:04.905  1036  1950 I ActivityManager: Process com.android.bluetooth (pid 7080) has died
07-01 12:11:04.906  1036  1950 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
07-01 12:11:04.906  1036  1950 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.opp.BluetoothOppService in 13999ms
,07-01 12:11:04.913  2225  2225 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 12:11:04.913  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
07-01 12:11:04.917  6385  6983 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-01 12:11:04.957  6966  6966 D BluetoothPermissionRequest: onReceive
,07-01 12:11:04.960  2225  2225 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:04.962  6966  6966 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 12:11:04.962  6966  6966 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
07-01 12:11:04.970  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 12:11:05.050  1036  2031 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7411 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,07-01 12:11:05.059  7161  7161 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-01 12:11:05.059  7161  7161 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:05.059  7161  7161 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-01 12:11:05.059  7161  7161 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-01 12:11:05.063  7161  7161 I AppUp4:CustModeStarterReceiver: onReceive
,07-01 12:11:05.088  7161  7161 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d24beb9
07-01 12:11:05.088  7161  7161 D AppUp4:CustFacade: isCustomizationCompleted : false
07-01 12:11:05.088  7161  7161 D AppUp4:CustFacade: isPhone : true
,07-01 12:11:05.091  7161  7161 D AppUp4:CustModeStarterReceiver: begin check event
07-01 12:11:05.092  7161  7161 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
07-01 12:11:05.095  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:05.096  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:11:05.097  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,07-01 12:11:05.100  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:05.109  4321  7429 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 12:11:05.112  7194  7194 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
07-01 12:11:05.119  7411  7411 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-01 12:11:05.119  4321  7430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:05.120  4321  7430 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:11:05.120  7411  7411 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:11:05.120  7411  7411 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
07-01 12:11:05.121  7411  7411 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-01 12:11:05.134  7194  7431 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:11:05.142  7411  7411 D BluetoothAdapterApp: Loading JNI Library
07-01 12:11:05.144  3424  3424 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-01 12:11:05.144  3424  3424 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:05.144  3424  3424 I LgeMiscReceiver: networkInfo.isConnected() = false
07-01 12:11:05.151  7248  7248 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-01 12:11:05.151  7248  7248 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,07-01 12:11:05.158  6748  7434 W FormManager: Network not available. Please check & try again.
07-01 12:11:05.159  6748  7435 V FormManager: Network unavailable.
07-01 12:11:05.161  6748  7435 V FormManager: Network unavailable.
07-01 12:11:05.170  6699  6699 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:11:5
07-01 12:11:05.172  6699  6699 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-01 12:11:05.172  6699  6699 D Weather.Utils: 2 : All the weather widget is gone.
,07-01 12:11:05.173  6699  6699 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-01 12:11:05.173  6699  6699 D WeatherAncestor: connectivity changed - connection : true
07-01 12:11:05.173  6699  6699 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15bb9a5f
,07-01 12:11:05.176  7411  7411 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@28316567 Instance Count = 1
07-01 12:11:05.178  6699  6699 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-01 12:11:05.178  6699  6699 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-01 12:11:05.178  6699  6699 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-01 12:11:05.178  6699  6699 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-01 12:11:05.178  6699  6699 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:11:5
07-01 12:11:05.182  7411  7411 D BluetoothAdapterApp: onCreate
07-01 12:11:05.201  7411  7411 D ProfileConfigQcom: [BTUI] HeadsetService is supported
07-01 12:11:05.201  7411  7411 D ProfileConfigQcom: Adding HeadsetService
07-01 12:11:05.201  7411  7411 D ProfileConfigQcom: [BTUI] A2dpService is supported
07-01 12:11:05.201  7411  7411 D ProfileConfigQcom: Adding A2dpService
07-01 12:11:05.202  7411  7411 D ProfileConfigQcom: [BTUI] HidService is supported
07-01 12:11:05.202  7411  7411 D ProfileConfigQcom: Adding HidService
07-01 12:11:05.202  7411  7411 D ProfileConfigQcom: [BTUI] HealthService is supported
07-01 12:11:05.202  7411  7411 D ProfileConfigQcom: Adding HealthService
07-01 12:11:05.202  7411  7411 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,07-01 12:11:05.203  7411  7411 D ProfileConfigQcom: [BTUI] PanService is supported
07-01 12:11:05.203  7411  7411 D ProfileConfigQcom: Adding PanService
07-01 12:11:05.203  7411  7411 D ProfileConfigQcom: [BTUI] GattService is supported
07-01 12:11:05.204  7411  7411 D ProfileConfigQcom: Adding GattService
07-01 12:11:05.204  7411  7411 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
07-01 12:11:05.204  7411  7411 D ProfileConfigQcom: Adding BluetoothMapService
07-01 12:11:05.205  7411  7411 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
07-01 12:11:05.206  7411  7411 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-01 12:11:05.210  7411  7411 V LGMDMManagerInternal: Create singleton instance
07-01 12:11:05.212  6966  6966 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
07-01 12:11:05.218  6891  6943 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:05.218  6891  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:11:05.218  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:11:05.218  6891  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:11:05.218  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d12c2ef removed from the list
,07-01 12:11:05.219  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:11:05.219  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30fd085 added. We now have 2 listener(s)
07-01 12:11:05.219  6891  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:11:05.219  6891  6943 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:05.219  6891  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:11:05.219  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:11:05.219  6891  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:11:05.219  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30fd085 removed from the list
07-01 12:11:05.220  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:11:05.220  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b227eda added. We now have 2 listener(s)
07-01 12:11:05.220  6891  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:11:05.221  1036  2332 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:11:05.221  1036  2332 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
07-01 12:11:05.221  1036  1097 D BluetoothManagerService: Message: 2
07-01 12:11:05.226  6891  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:05.227  1036  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:11:05.227  1036  1776 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-01 12:11:05.230  1036  1949 I art     : Explicit concurrent mark sweep GC freed 28750(1389KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.260ms total 85.655ms
07-01 12:11:05.236  1036  1097 D BluetoothManagerService: Message: 1
07-01 12:11:05.236  1036  1097 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,07-01 12:11:05.237  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:11:05.237  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:11:05.237  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,07-01 12:11:05.300  7411  7411 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:05.313  1036  1097 D BluetoothManagerService: Message: 20
,07-01 12:11:05.314  1036  1097 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89602f0:true
,07-01 12:11:05.314  7411  7411 D BluetoothAdapterState: make
07-01 12:11:05.320  7411  7411 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
,07-01 12:11:05.320  7411  7411 I bluedroid-qcom: init
07-01 12:11:05.321  7411  7440 I BluetoothAdapterState: Entering OffState
07-01 12:11:05.321  7411  7411 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-01 12:11:05.322  7411  7411 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-01 12:11:05.322  7411  7411 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-01 12:11:05.322  7411  7411 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-01 12:11:05.322  7411  7411 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
07-01 12:11:05.322  7411  7411 I bluedroid-qcom: get_profile_interface socket
07-01 12:11:05.322  7411  7411 I bluedroid-qcom: get_profile_interface map_client
07-01 12:11:05.322  7411  7443 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-01 12:11:05.313  7444  7444 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:05.313  7444  7444 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:05.328  7444  7444 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
07-01 12:11:05.328  7444  7444 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
07-01 12:11:05.328  7444  7444 I LGFTMITEM: [GET_FTM][id=8], offset=16384
07-01 12:11:05.329  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-01 12:11:05.329  1036  1097 D BluetoothManagerService: Message: 40
07-01 12:11:05.329  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,07-01 12:11:05.331  7411  7428 I bluedroid-qcom: config_hci_snoop_log
07-01 12:11:05.333  7444  7444 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
07-01 12:11:05.334  7411  7411 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:11:05.334  1036  1097 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-01 12:11:05.334  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
07-01 12:11:05.334  7411  7411 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 12:11:05.334  7411  7411 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 12:11:05.335  7411  7411 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:05.336  7411  7411 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
07-01 12:11:05.337  7444  7444 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
07-01 12:11:05.337  7444  7444 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
07-01 12:11:05.340  7037  7037 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
07-01 12:11:05.341  7411  7443 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-01 12:11:05.349  7411  7440 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-01 12:11:05.350  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-01 12:11:05.351  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-01 12:11:05.351  7411  7443 D BluetoothAdapterProperties: Name is: G3
07-01 12:11:05.351  7411  7440 D BluetoothAdapterProperties: Setting state to 11
07-01 12:11:05.351  7411  7440 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 12:11:05.352  1036  1097 D BluetoothManagerService: Message: 60
07-01 12:11:05.352  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-01 12:11:05.352  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-01 12:11:05.352  7411  7440 I LGBluetoothServiceJni: classInitNative: succeeds
07-01 12:11:05.354  1968  1968 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:05.354  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,07-01 12:11:05.360  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
07-01 12:11:05.371  7411  7411 V BluetoothPbapReceiver: PbapReceiver onReceive 
,07-01 12:11:05.372  7411  7411 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:05.372  7411  7411 V BluetoothPbapReceiver: ***********state = 11
07-01 12:11:05.376  2225  2225 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 12:11:05.378  7411  7440 D BluetoothBondStateMachine: make
07-01 12:11:05.380  7411  7445 I BluetoothBondStateMachine: StableState(): Entering Off State
07-01 12:11:05.380  7411  7440 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.380  7411  7440 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
07-01 12:11:05.380  7411  7440 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.380  7411  7440 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
07-01 12:11:05.380  7411  7440 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
07-01 12:11:05.384  7411  7440 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:05.387  6966  6966 D BluetoothPermissionRequest: onReceive
,07-01 12:11:05.392  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 12:11:05.393  7411  7440 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:05.394  7411  7411 D HeadsetService: Received start request. Starting profile...
07-01 12:11:05.394  7411  7411 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 12:11:05.394  7411  7411 D LGBluetoothHfpAdapter: Version 1.6
07-01 12:11:05.397  7411  7411 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 12:11:05.398  7411  7411 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-01 12:11:05.398  7411  7440 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:05.399  7411  7411 D HeadsetStateMachine: make
,07-01 12:11:05.403  7411  7440 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:05.409  7411  7440 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:05.413  7411  7440 E BluetoothAdapterService: File transfer profiles supported!!
,07-01 12:11:05.417  7411  7440 E BluetoothAdapterService: File transfer profiles supported!!
07-01 12:11:05.421  7411  7411 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:05.421  7411  7411 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 12:11:05.424  7411  7411 D HeadsetStateMachine: max_hf_connections = 1
07-01 12:11:05.424  7411  7411 I bluedroid-qcom: get_profile_interface handsfree
07-01 12:11:05.425  7411  7411 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,07-01 12:11:05.426   322  1390 V AudioPolicyService: registerClient() client 0xb1027ba0, uid 1002
07-01 12:11:05.426   322  1390 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-01 12:11:05.426   322  1390 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 12:11:05.426   322  1390 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 12:11:05.426  7411  7411 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-01 12:11:05.426   322  4000 V AudioFlinger: registerClient() client 0xb1025c58, pid 7411
07-01 12:11:05.427   322  1384 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:05.427   322  1384 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:05.427  7411  7411 V ToneGenerator: Create Track: 0xb4928080
07-01 12:11:05.427  7411  7411 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-01 12:11:05.427  7411  7411 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
07-01 12:11:05.427   322  1385 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:05.427   322  1385 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:05.427  7411  7427 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:05.427  7411  7427 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-01 12:11:05.427  3424  3439 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:05.427  3424  3439 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:05.427  7411  7427 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:05.427  7411  7427 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-01 12:11:05.427   322  4000 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 12:11:05.427   322  4000 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
07-01 12:11:05.427  3424  3439 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:05.427   322  4000 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 12:11:05.427  3424  3439 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:05.427   322  4000 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 12:11:05.427  1881  3992 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:05.427  1881  3992 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:05.427   322  4000 I AudioFlinger: isAudioPlaybackHookOn() false
07-01 12:11:05.427  1881  3992 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:05.427  1881  3992 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:05.428   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-01 12:11:05.428   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-01 12:11:05.428   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-01 12:11:05.428   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
07-01 12:11:05.428  7411  7411 V AudioSystem: getLatency() output 2, latency 50
07-01 12:11:05.428  7411  7411 V AudioSystem: getFrameCount() output 2, frameCount 960
07-01 12:11:05.428  7411  7411 V AudioTrack: createTrack_l() output 2 afLatency 50
07-01 12:11:05.428  1603  1626 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:05.428  1603  1626 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:05.428  1603  1626 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:05.428  1603  1626 V AudioSystem: ioConfigChan,ged() opening already existing output! 4
07-01 12:11:05.428   322  4000 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-01 12:11:05.428   322  4000 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-01 12:11:05.428   322  4000 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
07-01 12:11:05.428   322  4000 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
07-01 12:11:05.428   322  4000 V AudioFlinger: createTrack() lSessionId: 27
07-01 12:11:05.428  1036  2093 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-01 12:11:05.428  1036  2093 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-01 12:11:05.428  1036  2093 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-01 12:11:05.428  1036  2093 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-01 12:11:05.429  7411  7411 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-01 12:11:05.429   322   322 V AudioFlinger: acquiring 27 from 7411, for 7411
07-01 12:11:05.430   322   322 V AudioFlinger:  added new entry for 27
07-01 12:11:05.430  7411  7411 V ToneGenerator: ToneGenerator INIT OK, time: 292765
07-01 12:11:05.430  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.431  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.432  7411  7446 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-01 12:11:05.432  7411  7446 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-01 12:11:05.432  7411  7411 D A2dpService: Received start request. Starting profile...
07-01 12:11:05.432  7411  7446 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-01 12:11:05.432  7411  7446 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-01 12:11:05.433   322  1389 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7411
07-01 12:11:05.433   322  1389 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-01 12:11:05.433   322  1389 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-01 12:11:05.433   322  1389 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-01 12:11:05.433   322  1389 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-01 12:11:05.433   322  1389 V voice   : voice_set_parameters: exit with code(0)
07-01 12:11:05.433  7411  7411 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-01 12:11:05.433   322  1389 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-01 12:11:05.433   322  1389 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-01 12:11:05.433   322  1389 V msm8974_platform: platform_set_parameters: exit with code(0)
07-01 12:11:05.433   322  1389 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
,07-01 12:11:05.433   322  1389 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-01 12:11:05.433   322  1389 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
07-01 12:11:05.433  7411  7446 V ToneGenerator: ToneGenerator destructor
07-01 12:11:05.433  7411  7446 V ToneGenerator: stopTone
07-01 12:11:05.433  7411  7446 V ToneGenerator: Delete Track: 0xb4928080
07-01 12:11:05.434  7411  7411 V Avrcp   : make
07-01 12:11:05.434   322  1390 V AudioPolicyService: AudioCommandThread() adding release output 2
07-01 12:11:05.434   322  1390 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-01 12:11:05.434   322  1261 V AudioPolicyService: AudioCommandThread() waking up
07-01 12:11:05.434   322  1261 V AudioPolicyService: AudioCommandThread() processing release output 2
,07-01 12:11:05.434   322  1261 V AudioPolicyManager: releaseOutput() 2
07-01 12:11:05.434   322  1261 V AudioPolicyService: AudioCommandThread() going to sleep
07-01 12:11:05.434   322  1390 V AudioFlinger: PlaybackThread::Track destructor
07-01 12:11:05.434   322  1390 V AudioFlinger: removeClient_l() pid 7411, calling pid 322
07-01 12:11:05.434  7411  7446 V AudioTrack: ~AudioTrack, releasing session id from 7411 on behalf of 7411
07-01 12:11:05.434  7411  7411 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-01 12:11:05.434  7411  7411 I bluedroid-qcom: get_profile_interface avrcp
07-01 12:11:05.434   322  1389 V AudioFlinger: releasing 27 from 7411 for 7411
07-01 12:11:05.434   322  1389 V AudioFlinger:  decremented refcount to 0
07-01 12:11:05.434   322  1389 V AudioFlinger: purging stale effects
07-01 12:11:05.437  1036  1776 W Process : Unable to open /proc/7447/status
07-01 12:11:05.438  7411  7440 V LGMDMManager: Create singleton instance
,07-01 12:11:05.440  7411  7440 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-01 12:11:05.443  7411  7411 V AudioManager: registerRemoteController: size of Media player list: 0
07-01 12:11:05.446  7411  7411 E AudioManager: No RCC entry present to update
07-01 12:11:05.446  7411  7411 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-01 12:11:05.448  7411  7411 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
07-01 12:11:05.448  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
07-01 12:11:05.448  7411  7411 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
07-01 12:11:05.451  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,07-01 12:11:05.594  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
07-01 12:11:05.594  1036  1052 V SIM_STK : Menu title from STK is T-Mobile
,07-01 12:11:05.668  1036  2093 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,07-01 12:11:05.676  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-01 12:11:05.680  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-01 12:11:05.680  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-01 12:11:05.680  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-01 12:11:05.680  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-01 12:11:05.680  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 12:11:05.680  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-01 12:11:05.680  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-01 12:11:05.680  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-01 12:11:05.681  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 12:11:05.681  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-01 12:11:05.681  7411  7411 I BluetoothA2dpServiceJni: classInitNative
07-01 12:11:05.681  7411  7411 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-01 12:11:05.681  7411  7411 D A2dpStateMachine: make
07-01 12:11:05.684  7411  7411 I bluedroid-qcom: get_profile_interface a2dp
07-01 12:11:05.684  7411  7451 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-01 12:11:05.695  7411  7411 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-01 12:11:05.695  7411  7411 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,07-01 12:11:05.698  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.699  7411  7411 I BluetoothHidServiceJni: classInitNative: succeeds
07-01 12:11:05.702  7411  7411 D HidService: Received start request. Starting profile...
07-01 12:11:05.702  7411  7411 I bluedroid-qcom: get_profile_interface hidhost
07-01 12:11:05.702  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.703  7411  7450 D A2dpStateMachine: Enter Disconnected: -2
07-01 12:11:05.703  7411  7411 I BluetoothHealthServiceJni: classInitNative: succeeds
07-01 12:11:05.707  7411  7411 D HealthService: Received start request. Starting profile...
07-01 12:11:05.711  7411  7411 I bluedroid-qcom: get_profile_interface health
07-01 12:11:05.711  7411  7411 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-01 12:11:05.711  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
,07-01 12:11:05.715  7411  7411 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-01 12:11:05.723  7411  7411 D PanService: Received start request. Starting profile...
07-01 12:11:05.723  7411  7411 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 12:11:05.723  7411  7411 I bluedroid-qcom: get_profile_interface pan
07-01 12:11:05.729  7411  7411 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-01 12:11:05.729  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.730  7411  7411 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-01 12:11:05.733  7411  7411 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-01 12:11:05.735  7411  7411 D BtGatt.GattService: Received start request. Starting profile...
,07-01 12:11:05.735  7411  7411 D BtGatt.GattService: start()
07-01 12:11:05.735  7411  7411 I bluedroid-qcom: get_profile_interface gatt
07-01 12:11:05.736  7411  7411 D BtGatt.AdvertiseManager: advertise manager created
07-01 12:11:05.743  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.744  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.744  7411  7411 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-01 12:11:05.744  7411  7411 V BluetoothMapService: BluetoothMapBinder()
07-01 12:11:05.745  7411  7411 D BluetoothMapService: Received start request. Starting profile...
07-01 12:11:05.745  7411  7411 D BluetoothMapService: start()
,07-01 12:11:05.747  7411  7411 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-01 12:11:05.747  7411  7411 D BluetoothMapEmailAppObserver: createReceiver()
07-01 12:11:05.748  7411  7411 D BluetoothMapEmailAppObserver: initObservers()
07-01 12:11:05.748  7411  7411 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
07-01 12:11:05.752  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:05.753  7411  7411 D HeadsetStateMachine: Proxy object connected
07-01 12:11:05.753  7411  7411 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-01 12:11:05.753  7411  7411 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
07-01 12:11:05.755  7411  7446 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 12:11:05.757  7411  7411 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:05.758  6590  7124 D UEI.SmartControl: Internal timer expired: 2
07-01 12:11:05.758  6590  7124 D UEI.SmartControl: unbind internal service
,07-01 12:11:05.759  7411  7446 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-01 12:11:05.759  7411  7411 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:05.759  7411  7446 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-01 12:11:05.761  7411  7411 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:05.764  7411  7411 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:05.766  7411  7411 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:05.766  7411  7411 V PanService: [BTUI] SIM Extra State :ABSENT
07-01 12:11:05.768  7411  7411 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
07-01 12:11:05.770  7411  7411 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,07-01 12:11:05.770  7411  7411 V BluetoothMapService: Handler(): got msg=1
07-01 12:11:05.771  7411  7411 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:11:05.771  7411  7411 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 12:11:05.771  7411  7411 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 12:11:05.771  7411  7411 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:05.771  7411  7411 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
07-01 12:11:05.771  7411  7440 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-01 12:11:05.772  7411  7440 I bluedroid-qcom: enable
07-01 12:11:05.772  7411  7440 I bt_hci_bdroid: init
07-01 12:11:05.773  7411  7440 I bt_vendor: bt-vendor : init
07-01 12:11:05.773  7411  7440 I bt_vendor: bt-vendor : get_bt_soc_type
07-01 12:11:05.773  7411  7440 E bt_vendor: get_bt_soc_type: Failed to get soc type
07-01 12:11:05.773  7411  7440 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
07-01 12:11:05.773  7411  7440 D bt_userial_mct: userial_init
07-01 12:11:05.772  7411  7461 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-01 12:11:05.774  7411  7461 I bt-btu  : btu_task pending for preload complete event
07-01 12:11:05.777  7411  7440 D bt_hci_bdroid: set_power 1
07-01 12:11:05.777  7411  7440 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
07-01 12:11:05.777  7411  7440 I bt_vendor: Starting hciattach daemon
07-01 12:11:05.777  7411  7440 I bt_vendor: try to set true
07-01 12:11:05.773  7464  7464 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:05.773  7464  7464 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:05.789  7465  7465 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,07-01 12:11:05.813  6590  7116 D serial_port: close(fd = 24)
,07-01 12:11:05.818  6590  7116 I UEI.SmartControl: Serial port is closed.
07-01 12:11:05.837  7471  7471 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,07-01 12:11:05.846  7472  7472 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-01 12:11:05.860  7474  7474 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-01 12:11:05.868  7475  7475 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
07-01 12:11:05.876  7476  7476 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,07-01 12:11:05.883  7477  7477 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
07-01 12:11:05.898  7479  7479 I libmdmdetect: ESOC framework not supported
,07-01 12:11:05.899  7479  7479 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
07-01 12:11:05.906  7479  7479 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
07-01 12:11:05.906  7479  7479 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
07-01 12:11:05.906  7479  7479 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
07-01 12:11:05.906  7479  7479 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
07-01 12:11:05.906  7479  7479 D bthci_qcomm_common: [BTUI]     LE: Class 2
07-01 12:11:05.906  7479  7479 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
07-01 12:11:05.906  7479  7479 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
07-01 12:11:05.940  7479  7480 E QC-QMI  : qmi_client [7479] 15: failed to locate client data
,07-01 12:11:05.940   451   451 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
07-01 12:11:05.940   451   451 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
07-01 12:11:06.057  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,07-01 12:11:06.068  7482  7482 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
07-01 12:11:06.083  7411  7440 I bt_vendor: bluetooth satus is on
07-01 12:11:06.083  7411  7440 D bt_hci_bdroid: preload
07-01 12:11:06.084  7411  7463 D bt_userial_mct: userial_open(port:0)
07-01 12:11:06.084  7411  7463 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,07-01 12:11:06.087  7411  7463 I bt_vendor: Done intiailizing UART
07-01 12:11:06.087  7411  7463 I bt_vendor: Done intiailizing UART
07-01 12:11:06.087  7411  7463 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
07-01 12:11:06.088  7411  7463 I bt_vendor: Bluetooth Firmware and transport layer are initialized
07-01 12:11:06.088  7411  7461 I bt-btu  : btu_task received preload complete event
07-01 12:11:06.088  7411  7484 D bt_userial_mct: Entering userial_read_thread()
07-01 12:11:06.088  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
07-01 12:11:06.088  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
07-01 12:11:06.092  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_HCI
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_AVDT
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_AVRC
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_A2D
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_BNEP
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_BTM
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_HID_HOST
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_GAP
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_PAN
07-01 12:11:06.097  7411  7461 I         : BTE_InitTraceLevels -- TRC_SDP
07-01 12:11:06.098  7411  7461 I         : BTE_InitTraceLevels -- TRC_GATT
07-01 12:11:06.098  7411  7461 I         : BTE_InitTraceLevels -- TRC_SMP
07-01 12:11:06.098  7411  7461 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-01 12:11:06.098  7411  7461 I         : BTE_InitTraceLevels -- TRC_BTIF
07-01 12:11:06.098  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:06.098  1036  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 12:11:06.116  1036  1539 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
07-01 12:11:06.117  1036  1539 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,07-01 12:11:06.183  7411  7461 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
07-01 12:11:06.183  7411  7461 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01ce061 
07-01 12:11:06.183  7411  7461 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01ce061 
,07-01 12:11:06.228  7411  7443 E bt-btif : Calling BTA_HhEnable
07-01 12:11:06.228  7411  7443 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
07-01 12:11:06.228  7411  7443 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,07-01 12:11:06.236  7411  7443 D BluetoothAdapterProperties: Name is: G3
07-01 12:11:06.237  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
07-01 12:11:06.237  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
07-01 12:11:06.240  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
07-01 12:11:06.240  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
07-01 12:11:06.240  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
07-01 12:11:06.240  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
07-01 12:11:06.240  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
07-01 12:11:06.241  7411  7443 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:11:06.241  7411  7443 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 12:11:06.241  7411  7443 D bt_hci_bdroid: postload
07-01 12:11:06.242  7411  7443 D bte_conf: Device ID record 1 : primary
07-01 12:11:06.242  7411  7443 D bte_conf:   vendorId            = 00c4
07-01 12:11:06.242  7411  7443 D bte_conf:   vendorIdSource      = 0001
07-01 12:11:06.242  7411  7443 D bte_conf:   product             = 13a1
07-01 12:11:06.242  7411  7443 D bte_conf:   version             = 1000
07-01 12:11:06.242  7411  7443 D bte_conf:   clientExecutableURL = 
07-01 12:11:06.242  7411  7443 D bte_conf:   serviceDescription  = 
07-01 12:11:06.242  7411  7443 D bte_conf:   documentationURL    = 
07-01 12:11:06.242  7411  7443 D bte_conf: bte_load_did_conf no section named DID2.
07-01 12:11:06.245  7411  7461 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
07-01 12:11:06.246  7411  7463 D bt_hci_bdroid: Used up Tx Cmd credits
,07-01 12:11:06.249  7411  7463 D bt_hci_bdroid: Used up Tx Cmd credits
07-01 12:11:06.243  7489  7489 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:06.243  7489  7489 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:06.253  7411  7440 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 12:11:06.253  7411  7440 D BluetoothAdapterProperties: ScanMode =  20
07-01 12:11:06.253  7411  7440 D BluetoothAdapterProperties: State =  11
07-01 12:11:06.254  7411  7440 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-01 12:11:06.254  7411  7440 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
07-01 12:11:06.254  7411  7440 D BluetoothAdapterProperties: Setting state to 12
07-01 12:11:06.254  7411  7440 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-01 12:11:06.255  7411  7443 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-01 12:11:06.256  7411  7443 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 12:11:06.260  7411  7463 D bt_hci_bdroid: Used up Tx Cmd credits
,07-01 12:11:06.264  1036  1097 D BluetoothManagerService: Message: 60
07-01 12:11:06.264  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-01 12:11:06.264  1036  1097 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
07-01 12:11:06.264  1881  3996 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:11:06.264  7411  7484 E bt_mct  : hci lib postload completed
07-01 12:11:06.265  7411  7440 I BluetoothAdapterState: Entering On State
07-01 12:11:06.268  7411  7440 D LGBluetoothServiceAdapter: [BTUI] OnState
07-01 12:11:06.268  7411  7440 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
07-01 12:11:06.268  7411  7440 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
07-01 12:11:06.268  7411  7440 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-01 12:11:06.270  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:06.270  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:06.270  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:06.270  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:06.270  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:06.270  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:06.270  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:06.270  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:06.272  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:06.274  7411  7461 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 12:11:06.274  7411  7461 W bt-smp  : Plain text(LSB ~ MSB) = 89 f0 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 12:11:06.274  7411  7461 W bt-smp  : Encrypted text(LSB ~ MSB) = a6 c5 65 94 23 e8 b7 ad 7f 8e 10 98 1a 7b 83 c2 
07-01 12:11:06.274  7411  7461 W bt-btm  : Stopping oneshot timer
,07-01 12:11:06.279  1881  1881 D BluetoothHeadset: Proxy object connected
07-01 12:11:06.279  1881  3992 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:11:06.280  7411  7443 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 12:11:06.280  7411  7443 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
07-01 12:11:06.281  1881  1881 D BluetoothHeadset: Proxy object connected
07-01 12:11:06.289  6891  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:06.289  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:06.289  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:06.289  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:06.289  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:06.289  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:06.289  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:06.289  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:06.290  6891  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:06.291  6891  6943 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:06.291  6891  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:11:06.291  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:11:06.291  6891  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:11:06.291  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b227eda removed from the list
07-01 12:11:06.292  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:11:06.292  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16f29f0b added. We now have 2 listener(s)
07-01 12:11:06.292  6891  6943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:11:06.295  7411  7461 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 12:11:06.295  7411  7461 W bt-smp  : Plain text(LSB ~ MSB) = c9 9b 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 12:11:06.295  7411  7461 W bt-smp  : Encrypted text(LSB ~ MSB) = 82 49 3f 50 af 00 61 f1 5f 8f 04 0c 71 ae f8 9d 
07-01 12:11:06.295  7411  7461 W bt-btm  : Stopping oneshot timer
07-01 12:11:06.295  6966  6982 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-01 12:11:06.301  1036  1773 D WifiServiceImplEx: setWifiEnabled: false pid=6891, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 12:11:06.301  1036  1773 D WifiService: setWifiEnabled: false pid=6891, uid=10118
07-01 12:11:06.301  1036  1773 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-01 12:11:06.305  6966  6982 D BluetoothPan: onBluetoothStateChange on: true
07-01 12:11:06.305  6966  6982 D BluetoothPan: onBluetoothStateChange call bindService
,07-01 12:11:06.309  6966  7314 D BluetoothMap: onBluetoothStateChange: up=true
07-01 12:11:06.311  7411  7461 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 12:11:06.311  7411  7461 W bt-smp  : Plain text(LSB ~ MSB) = 47 9a 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 12:11:06.311  7411  7461 W bt-smp  : Encrypted text(LSB ~ MSB) = 6d f5 00 be e5 21 d9 7c 6d 5e 22 0d 6a 9a fc f5 
07-01 12:11:06.311  7411  7461 W bt-btm  : Stopping oneshot timer
07-01 12:11:06.316  7411  7440 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
07-01 12:11:06.323  7495  7495 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
07-01 12:11:06.327  6966  6966 D BluetoothInputDevice: Proxy object connected
07-01 12:11:06.327  6966  6966 D HidProfile: Bluetooth service connected
,07-01 12:11:06.330  6966  6982 D BluetoothPbap: onBluetoothStateChange: up=true
07-01 12:11:06.333  1036  1097 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:11:06.333  6966  6966 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 12:11:06.333  6966  6966 D PanProfile: Bluetooth service connected
07-01 12:11:06.333  1036  1097 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 12:11:06.333  1036  1036 D BluetoothHeadset: Proxy object connected
07-01 12:11:06.335  7411  7461 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 12:11:06.335  1881  2562 D BluetoothHeadset: onBluetoothStateChange: up=true
07-01 12:11:06.335  7411  7461 W bt-smp  : Plain text(LSB ~ MSB) = 34 e1 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 12:11:06.335  7411  7461 W bt-smp  : Encrypted text(LSB ~ MSB) = 16 43 ba d3 24 69 e9 e3 60 05 f2 ff a5 c6 fd b2 
07-01 12:11:06.335  7411  7461 W bt-btm  : Stopping oneshot timer
07-01 12:11:06.336  6891  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:06.337  1036  1949 D WifiServiceImplEx: setWifiEnabled: true pid=6891, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
07-01 12:11:06.337  1881  1881 D BluetoothHeadset: Proxy object connected
07-01 12:11:06.337  1036  1036 D BluetoothA2dp: Proxy object connected
07-01 12:11:06.337  1036  1097 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-01 12:11:06.337  1036  1097 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-01 12:11:06.337  1036  1949 D WifiService: setWifiEnabled: true pid=6891, uid=10118
07-01 12:11:06.337  1036  1949 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-01 12:11:06.339  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
07-01 12:11:06.339  1968  1968 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:06.340  1968  2179 D LGBluetoothAPIService: Message: 1
07-01 12:11:06.340  1968  2179 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,07-01 12:11:06.346  6966  6966 D BluetoothMap: Proxy object connected
07-01 12:11:06.346  6966  6966 D MapProfile: Bluetooth service connected
07-01 12:11:06.346  6966  6966 D BluetoothMap: getConnectedDevices()
07-01 12:11:06.346  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-01 12:11:06.347  7411  7411 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:06.347  7411  7411 D BluetoothMapService: STATE_ON
07-01 12:11:06.347  1968  2179 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-01 12:11:06.348  7411  7461 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 12:11:06.348  7411  7461 W bt-smp  : Plain text(LSB ~ MSB) = b1 7b 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 12:11:06.348  7411  7461 W bt-smp  : Encrypted text(LSB ~ MSB) = 9e 84 c3 45 e4 b0 05 98 52 70 c9 e1 eb e6 90 12 
07-01 12:11:06.348  7411  7461 W bt-btm  : Stopping oneshot timer
07-01 12:11:06.348  7411  7411 D LGBluetoothAPIServer: [BTUI] onCreate()
07-01 12:11:06.348  7411  7411 D LGBluetoothAPIServer: [BTUI] onBind()
07-01 12:11:06.348  1036  1097 D BluetoothManagerService: Message: 40
07-01 12:11:06.348  1036  1097 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-01 12:11:06.349  1968  1968 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-01 12:11:06.349  1968  2179 D LGBluetoothAPIService: Message: 100
07-01 12:11:06.349  1968  2179 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-01 12:11:06.351  1036  1539 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
07-01 12:11:06.351  1036  1539 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-01 12:11:06.351  7411  7504 V BluetoothMapService: getConnectedDevices()
07-01 12:11:06.353  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:11:06.353  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-01 12:11:06.353  1036  1036 D Ulp_jni : JNI:system_update. Event-4
07-01 12:11:06.353  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
07-01 12:11:06.353  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-01 12:11:06.353  6966  6966 D LocalBluetoothProfileManager: Adding local A2DP profile
07-01 12:11:06.353  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
07-01 12:11:06.353  1036  1539 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
07-01 12:11:06.353  1036  1539 I WifiUtil: Intf0MacAddress=C49A027FFB5D
07-01 12:11:06.353  1036  1539 E WifiHW  : unknown target_country: EU , set to default
07-01 12:11:06.353  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
07-01 12:11:06.353  1036  1539 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
07-01 12:11:06.353  1036  1539 I WifiUtil: gEnableBmps=1
07-01 12:11:06.355  1036  1097 D BluetoothManagerService: Message: 30
,07-01 12:11:06.356  6966  6966 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-01 12:11:06.357  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:06.357  7411  7411 V BluetoothPbapService: Pbap Service onCreate
,07-01 12:11:06.357  7411  7411 V BluetoothPbapService: Starting PBAP service
07-01 12:11:06.358  7411  7411 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-01 12:11:06.358  7411  7411 V BluetoothPbapService: Pbap Service onBind
07-01 12:11:06.358  1036  1097 D BluetoothManagerService: Message: 30
07-01 12:11:06.360  7411  7411 V BluetoothMapService: Handler(): got msg=1
07-01 12:11:06.360  7411  7411 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-01 12:11:06.361  7411  7411 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:06.361  7411  7411 V BluetoothPbapService: state: 12
07-01 12:11:06.361  7411  7411 V BluetoothPbapService: Handler(): got msg=1
07-01 12:11:06.361  7411  7511 D BluetoothMapMasInstance: MAS initSocket()
07-01 12:11:06.362  7411  7511 D BluetoothMapMasInstance:   masId = 00
07-01 12:11:06.362  7411  7511 D BluetoothMapMasInstance:   msgTypes = 0e
07-01 12:11:06.362  7411  7511 D BluetoothMapMasInstance:   masName = SMS/MMS
07-01 12:11:06.362  7411  7511 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-01 12:11:06.363  7411  7411 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-01 12:11:06.364  1036  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:11:06.365  7411  7511 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 12:11:06.366  6966  6966 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
07-01 12:11:06.366  7411  7511 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
07-01 12:11:06.366  7411  7511 V BluetoothMapMasInstance: Succeed to create listening socket 
07-01 12:11:06.366  7411  7511 D BluetoothMapMasInstance: Accepting socket connection...
07-01 12:11:06.366  7411  7443 D BluetoothAdapterProperties: Scan Mode:21
07-01 12:11:06.366  7411  7443 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
07-01 12:11:06.367  7411  7512 V BluetoothPbapService: Pbap Service initSocket
07-01 12:11:06.368  1036  1737 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,07-01 12:11:06.369  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:06.369  6966  6966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
07-01 12:11:06.371  7411  7512 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 12:11:06.372  6966  6966 D BluetoothA2dp: Proxy object connected
07-01 12:11:06.372  6966  6966 D A2dpProfile: Bluetooth service connected
07-01 12:11:06.375  7411  7512 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
07-01 12:11:06.376  7411  7512 V BluetoothPbapService: Succeed to create listening socket 
07-01 12:11:06.376  7411  7512 V BluetoothPbapService: Accepting socket connection...
07-01 12:11:06.376  6966  6966 D BluetoothPbap: Proxy object connected
07-01 12:11:06.376  6966  6966 D PbapServerProfile: Bluetooth service connected
07-01 12:11:06.376  6966  6966 D BluetoothHeadset: Proxy object connected
07-01 12:11:06.376  6966  6966 D HeadsetProfile: Bluetooth service connected
07-01 12:11:06.377  7411  7411 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-01 12:11:06.377  7411  7411 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:06.377  7411  7411 V BluetoothPbapReceiver: ***********state = 12
07-01 12:11:06.380  2225  2225 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:06.380  2225  2225 D c       : Getting all permits...
07-01 12:11:06.380  2225  2225 D a       : Opening database...
07-01 12:11:06.383  6966  6966 D DockEventReceiver: finishStartingService: stopping service
07-01 12:11:06.384  2225  2225 D a       : Opening database auth.proximity.permit_store...
07-01 12:11:06.385  2225  2225 D a       : Closing database...
07-01 12:11:06.392  6966  6966 D BluetoothPermissionRequest: onReceive
,07-01 12:11:06.393  6966  6966 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-01 12:11:06.394  6966  6966 D LGBluetoothResetSettingReceiver: return without doing reset settings.
07-01 12:11:06.396  7411  7411 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
07-01 12:11:06.397  7411  7411 I LGBluetoothOppAdapter: [BTUI] startOppService()
07-01 12:11:06.401  7411  7411 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-01 12:11:06.411  7411  7411 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-01 12:11:06.411  7411  7411 V BtOppService: onCreate
,07-01 12:11:06.415  7411  7411 V BluetoothOppNotification: send message
07-01 12:11:06.418  7411  7411 V BtOppService: Starting RfcommListener
07-01 12:11:06.420  7411  7411 D BluetoothOppPreference: Dumping Names:  
07-01 12:11:06.420  7411  7411 D BluetoothOppPreference: {}
07-01 12:11:06.420  7411  7411 D BluetoothOppPreference: Dumping Channels:  
07-01 12:11:06.420  7411  7411 D BluetoothOppPreference: {}
07-01 12:11:06.421  7411  7411 V BtOppService: onStartCommand
07-01 12:11:06.422  7411  7521 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-01 12:11:06.424  7411  7411 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:06.424  7411  7411 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
07-01 12:11:06.427  7411  7411 V BluetoothOppNotification: new notify threadi!
07-01 12:11:06.428  7411  7411 V BluetoothOppNotification: send delay message
07-01 12:11:06.428  7411  7411 V BtOppService: start RfcommListener
07-01 12:11:06.430  7411  7411 V BtOppService: RfcommListener started
07-01 12:11:06.431  7411  7523 V BtOppRfcommListener: Starting RFCOMM listener....
07-01 12:11:06.431  1036  1776 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:11:06.432  7411  7523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 12:11:06.432  7411  7523 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
07-01 12:11:06.432  7411  7523 V BtOppRfcommListener: Started RFCOMM listener....
07-01 12:11:06.432  7411  7523 I BtOppRfcommListener: Accept thread started.
07-01 12:11:06.432  7411  7523 V BtOppRfcommListener: Accepting connection...
07-01 12:11:06.434  7411  7521 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-01 12:11:06.434  7411  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-01 12:11:06.435  7411  7518 V BtOppService: Deleted complete outbound shares, number =  0
07-01 12:11:06.436  7411  7518 V BtOppService: Deleted complete inbound failed shares, number = 0
,07-01 12:11:06.437  7411  7518 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-01 12:11:06.438  7411  7521 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e741641 on behalf of 
07-01 12:11:06.438  7411  7518 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d7b77e6 on behalf of 
07-01 12:11:06.439  7411  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13ab1928 on behalf of 
07-01 12:11:06.440  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
07-01 12:11:06.440  7411  7411 V BluetoothFtpService: Ftp Service onCreate
07-01 12:11:06.440  7411  7411 I BluetoothFtpService: Ftp Service onCreate
07-01 12:11:06.440  7411  7411 V BluetoothFtpService: Ftp Service onStartCommand
07-01 12:11:06.440  7411  7411 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:06.440  7411  7411 V BluetoothFtpService: Starting Listening on sockets
07-01 12:11:06.441  7411  7411 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-01 12:11:06.441  7411  7411 V BluetoothSapReceiver: [BTUI] region:EU country:EU
07-01 12:11:06.441  7411  7411 V BluetoothSapReceiver: SapReceiver onReceive 
07-01 12:11:06.441  7411  7411 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:06.441  7411  7411 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
07-01 12:11:06.441  7411  7411 V BluetoothSapReceiver: Calling SAP service start service with action = null
07-01 12:11:06.442  7411  7521 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-01 12:11:06.442  7411  7521 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-01 12:11:06.442  7411  7411 V BtOppService: ContentObserver received notification
07-01 12:11:06.442  7411  7411 V BtOppService: ContentObserver received notification
07-01 12:11:06.442  7411  7411 V BluetoothFtpService: Handler(): got msg=1
07-01 12:11:06.443  7411  7411 V BluetoothFtpService: Ftp Service startRfcommSocketListener
07-01 12:11:06.443  7411  7411 V BluetoothFtpService: Ftp Service initSocket
07-01 12:11:06.444  7411  7521 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d2c9fd4 on behalf of 
07-01 12:11:06.445  7411  7522 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-01 12:11:06.445  1036  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:11:06.445  7411  7521 V BluetoothOppNotification: update too frequent, put in queue
07-01 12:11:06.445  7411  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-01 12:11:06.445  7411  7411 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 12:11:06.446  7411  7521 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
07-01 12:11:06.446  7411  7411 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
07-01 12:11:06.446  7411  7521 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-01 12:11:06.446  7411  7411 V BluetoothFtpService: Succeed to create listening socket on channel 20
,07-01 12:11:06.446  7411  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26aad57d on behalf of 
07-01 12:11:06.447  7411  7522 V BluetoothOppNotification: outbound: succ-0  fail-0
07-01 12:11:06.448  7411  7522 V BluetoothOppNotification: outbound notification was removed.
07-01 12:11:06.448  7411  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-01 12:11:06.448  7411  7521 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f772c72 on behalf of 
07-01 12:11:06.448  7411  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@774d8c3 on behalf of 
07-01 12:11:06.448  7411  7521 V BluetoothOppNotification: update too frequent, put in queue
07-01 12:11:06.449  7411  7522 V BluetoothOppNotification: inbound: succ-0  fail-0
07-01 12:11:06.449  7411  7521 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
07-01 12:11:06.452  7411  7522 V BluetoothOppNotification: inbound notification was removed.
07-01 12:11:06.452  7411  7522 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-01 12:11:06.453  7411  7522 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@309de540 on behalf of 
07-01 12:11:06.455  7411  7524 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
07-01 12:11:06.462  7411  7411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15bb9a5f
,07-01 12:11:06.462  7411  7411 V BluetoothSapService: Sap Service onCreate
07-01 12:11:06.464  7411  7411 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:06.464  7411  7411 V BluetoothSapService: state: 12
07-01 12:11:06.464  7411  7411 V BluetoothSapService: Starting SAP server process
07-01 12:11:06.465  7411  7411 V BluetoothSapService: SAP Service startRfcommListenerThread
07-01 12:11:06.467  7411  7526 V BluetoothSapService: Sap Service initRfcommSocket
07-01 12:11:06.463  7525  7525 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:06.463  7525  7525 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:06.467  1036  2093 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-01 12:11:06.468  7411  7526 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 12:11:06.469  7411  7526 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
07-01 12:11:06.469  7411  7526 V BluetoothSapService: Succeed to create listening socket 
07-01 12:11:06.469  7411  7526 V BluetoothSapService: Accepting socket connection...
07-01 12:11:06.478  7525  7525 V BT_SAP  : Event pipe created
07-01 12:11:06.478  7525  7525 V BT_SAP  : create_server_socket qcom.sap.server
07-01 12:11:06.478  7525  7525 V BT_SAP  : created socket fd 6
,07-01 12:11:07.303  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 12:11:07.303  1036  1097 D Tethering: InitialState.processMessage what=4
07-01 12:11:07.303  1036  1097 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-01 12:11:07.311   318   902 D SoftapController: Softap fwReload - Ok
07-01 12:11:07.311  1036  1539 E NetdConnector: NDC Command {65 softap fwreload wlan0 STA} took too long (955ms)
07-01 12:11:07.313   318   902 D CommandListener: Setting iface cfg
07-01 12:11:07.313   318   902 D CommandListener: Trying to bring down wlan0
07-01 12:11:07.314   318   902 D CommandListener: Clearing all IP addresses on wlan0
07-01 12:11:07.318  1036  1539 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-01 12:11:07.326  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 12:11:07.326  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 12:11:07.323  7549  7549 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:07.323  7549  7549 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,07-01 12:11:07.326  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 12:11:07.347  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 12:11:07.328  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 12:11:07.328  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
07-01 12:11:07.328  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,07-01 12:11:07.362  1036  1539 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-01 12:11:07.362  1036  1539 D WifiMonitor: connecting to supplicant
07-01 12:11:07.363  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 12:11:07.363  7549  7549 I wpa_supplicant: Successfully initialized wpa_supplicant
07-01 12:11:07.375  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 12:11:07.375  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-01 12:11:07.375  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 12:11:07.375  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 12:11:07.375  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,07-01 12:11:07.381  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:07.381  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
07-01 12:11:07.384  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-01 12:11:07.384  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 12:11:07.386  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:07.386  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 12:11:07.386  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 12:11:07.386  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 12:11:07.386  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 12:11:07.387  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 12:11:07.387  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 12:11:07.387  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
07-01 12:11:07.387  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 12:11:07.387  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 12:11:07.387  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 12:11:07.387  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-01 12:11:07.396  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:11:07.397  7549  7549 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-01 12:11:07.397  7549  7549 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
07-01 12:11:07.402  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:07.410  6748  7560 W FormManager: Network not available. Please check & try again.
07-01 12:11:07.411  6748  7561 V FormManager: Network unavailable.
07-01 12:11:07.411  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:07.416  6748  7561 V FormManager: Network unavailable.
,07-01 12:11:07.429  7411  7411 V BluetoothOppNotification: new notify threadi!
07-01 12:11:07.429  7411  7411 V BluetoothOppNotification: send delay message
,07-01 12:11:07.435  7411  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-01 12:11:07.436  7411  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@51c156c on behalf of 
07-01 12:11:07.437  7411  7562 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-01 12:11:07.438  7411  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-01 12:11:07.439  7411  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39043735 on behalf of 
07-01 12:11:07.439  7411  7562 V BluetoothOppNotification: outbound: succ-0  fail-0
07-01 12:11:07.440  7411  7562 V BluetoothOppNotification: outbound notification was removed.
07-01 12:11:07.440  7411  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-01 12:11:07.441  7411  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@379bd7ca on behalf of 
07-01 12:11:07.442  7411  7562 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-01 12:11:07.448  7411  7562 V BluetoothOppNotification: inbound notification was removed.
07-01 12:11:07.448  7411  7562 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-01 12:11:07.449  7411  7562 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19569d3b on behalf of 
07-01 12:11:07.491  7549  7549 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 12:11:07.529  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-01 12:11:07.529  6891  6946 I jxcore-log: 
,07-01 12:11:07.540  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-01 12:11:07.540  6891  6946 I jxcore-log: 
,07-01 12:11:07.548  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-01 12:11:07.548  6891  6946 I jxcore-log: 
,07-01 12:11:07.574  7549  7549 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,07-01 12:11:07.587  7549  7549 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
07-01 12:11:07.588  7549  7549 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-01 12:11:07.591  1036  7565 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
07-01 12:11:07.591  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
07-01 12:11:07.591  1036  7565 D WifiMonitor: Dropping event because (p2p0) is stopped
07-01 12:11:07.591  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
07-01 12:11:07.591  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,07-01 12:11:07.591  1036  7565 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
07-01 12:11:07.591  1036  7565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
07-01 12:11:07.592  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,07-01 12:11:07.593  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
07-01 12:11:07.594  1036  1539 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
07-01 12:11:07.596  1036  1539 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:07.597  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:07.599  1036  1539 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
07-01 12:11:07.599  1036  1539 D WifiNative-wlan0: doString: [DRIVER MACADDR]
07-01 12:11:07.599  1036  1539 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
07-01 12:11:07.600  1036  1539 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
07-01 12:11:07.600  1036  1539 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-01 12:11:07.600  1036  1539 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
07-01 12:11:07.600  1036  1539 E WifiStateMachine: useWiFiOffloading() : false
07-01 12:11:07.600  1036  1539 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
07-01 12:11:07.601  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:07.601  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:07.601  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:07.601  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:07.601  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-01 12:11:07.601  1036  1539 D WifiNative-wlan0: doBoolean: SET update_config 1
07-01 12:11:07.602  1036  1539 D WifiNative-wlan0: SET update_config 1: returned true
07-01 12:11:07.602  1036  1539 D WifiConfigStore: Loading config and enabling all networks 
07-01 12:11:07.602  1036  1539 D WifiNative-wlan0: doString: [LIST_NETWORKS]
07-01 12:11:07.602  1036  1539 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
07-01 12:11:07.604  1968  1968 D WfdService: Waiting for WifiP2p enabling
07-01 12:11:07.605  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 12:11:07.611  1036  1539 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,07-01 12:11:07.618  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:07.618  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:07.618  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:07.618  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:07.618  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:07.618  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:07.618  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:07.618  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:07.620  1036  1539 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
07-01 12:11:07.620  1036  1539 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-01 12:11:07.621  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
07-01 12:11:07.621  1036  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-01 12:11:07.621  1036  1539 D WifiStateMachine: enableVerboseLogging : level 2
07-01 12:11:07.621  1036  1539 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
07-01 12:11:07.622  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:07.623  1036  1539 D WifiNative-wlan0: SET device_name g3_global_com: returned true
07-01 12:11:07.623  1036  1539 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
07-01 12:11:07.623  1036  1539 D WifiNative-wlan0: SET manufacturer LGE: returned true
07-01 12:11:07.623  1036  1539 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
07-01 12:11:07.624  1036  1539 D WifiNative-wlan0: SET model_name LG-D855: returned true
07-01 12:11:07.624  1036  1539 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
,07-01 12:11:07.624  1036  1539 D WifiNative-wlan0: SET model_number LG-D855: returned true
07-01 12:11:07.624  1036  1539 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,07-01 12:11:07.625  1036  1539 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
07-01 12:11:07.625  1036  1539 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
07-01 12:11:07.626  1036  1539 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
07-01 12:11:07.626  1036  1539 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
07-01 12:11:07.626  1036  1539 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
07-01 12:11:07.627  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 12:11:07.627  1036  1539 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
07-01 12:11:07.627  1036  1539 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
07-01 12:11:07.627  1036  1539 D WifiNative-HAL: Setting external_sim to 1
07-01 12:11:07.628  1036  1539 D WifiNative-wlan0: doBoolean: SET external_sim 1
07-01 12:11:07.628  1036  1539 D WifiNative-wlan0: SET external_sim 1: returned true
07-01 12:11:07.628  1036  1539 I WifiNative-HAL: startHal
07-01 12:11:07.628  1036  1539 D wifi    : setting scan oui 0x95768960
07-01 12:11:07.628  1036  1539 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 12:11:07.628  1036  1539 I WifiNative-HAL: startHal
07-01 12:11:07.629  1036  1539 D wifi    : setting scan oui 0x95768960
07-01 12:11:07.629  1968  1968 D WfdsService: Supplicant Connection state is changed : true
07-01 12:11:07.629  1968  2319 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-01 12:11:07.629  1036  1539 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
07-01 12:11:07.629  1968  2319 D WfdsService: Set the WFDS Monitor: true
07-01 12:11:07.629  1968  2319 D WfdsMonitor: WfdsMonitorThread create
07-01 12:11:07.629  1968  2319 D WfdsMonitor: WFDS Monitor is created and started
07-01 12:11:07.629  1968  2319 D WfdsService: WiFi: Supplicant connection re-established
07-01 12:11:07.630  1036  1539 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
07-01 12:11:07.630  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
07-01 12:11:07.630  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
07-01 12:11:07.630  1968  7566 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-01 12:11:07.630  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
07-01 12:11:07.630  1968  7566 E CtrlSupplicant: Succeed to open control connection
07-01 12:11:07.630  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-01 12:11:07.630  1968  7566 E CtrlSupplicant: Succeed to open monitor connection
07-01 12:11:07.631  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-01 12:11:07.631  1968  7566 D WfdsMonitor: Supplicant connection established
07-01 12:11:07.631  1968  2319 D WfdsService: Connected to the supplicant for wfds
07-01 12:11:07.631  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-01 12:11:07.631  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
07-01 12:11:07.631  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
07-01 12:11:07.632  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
07-01 12:11:07.632  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-01 12:11:07.632  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-01 12:11:07.632  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-01 12:11:07.632  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
07-01 12:11:07.632  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
07-01 12:11:07.633  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
07-01 12:11:07.633  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
07-01 12:11:07.633  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:11:07.633  7549  7549 I wpa_supplicant: android_multica,st_filter_startstop : multicast filter set
07-01 12:11:07.633  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
07-01 12:11:07.633  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
07-01 12:11:07.633  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
07-01 12:11:07.635  1036  1539 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
07-01 12:11:07.636  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:07.636  1036  1539 E WifiNative: : [294,955,714 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
07-01 12:11:07.637  1036  1539 D WifiNative-wlan0: doBoolean: RECONNECT
,07-01 12:11:07.637  1036  1539 D WifiNative-wlan0: RECONNECT: returned true
07-01 12:11:07.637  1036  1539 D WifiNative-wlan0: doString: [STATUS]
07-01 12:11:07.638  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
07-01 12:11:07.638  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
07-01 12:11:07.638  1036  1539 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-01 12:11:07.638  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 12:11:07.639  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
07-01 12:11:07.639  1036  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.641  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:07.641   318   902 D CommandListener: Setting iface cfg
07-01 12:11:07.641   318   902 D CommandListener: Trying to bring up p2p0
07-01 12:11:07.641  1036  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-01 12:11:07.641  1036  1537 D LGWifiP2pService: P2pEnablingState
07-01 12:11:07.642  1036  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.642  1036  1537 D LGWifiP2pService: P2p socket connection successful
07-01 12:11:07.642  1036  1537 D LGWifiP2pService: P2pEnabledState
07-01 12:11:07.643  1036  1537 D LGWifiP2pService: sending p2p connection changed broadcast
07-01 12:11:07.643  1036  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
07-01 12:11:07.644  1036  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
07-01 12:11:07.644  1036  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
07-01 12:11:07.644  1968  1968 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
07-01 12:11:07.644  1968  1968 D WfdsService: WifiP2pState is changed : true
07-01 12:11:07.644  1968  2319 D WfdsService: Receive the WFDS_ENABLE Method
07-01 12:11:07.644  1968  2319 D WfdsService: Set the WFDS Monitor: true
07-01 12:11:07.644  1968  2319 D WfdsService: Connected to the supplicant for wfds
07-01 12:11:07.644  1968  2319 D WfdsJNI : doCommand: WFDS_SET TRUE
07-01 12:11:07.644  7549  7549 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-01 12:11:07.644  1968  2319 D WfdsService: selectPreferredScanChannel [36]
07-01 12:11:07.644  1968  2319 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
07-01 12:11:07.645  1968  1968 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-01 12:11:07.645  1036  1537 D WifiNative-p2p0: SET device_name G3: returned true
07-01 12:11:07.645  1036  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-01 12:11:07.645  1036  1537 D LGWifiP2pService: before postfix = G3
07-01 12:11:07.645  1036  1537 D WifiServerServiceExt: postfix byte check : 2
07-01 12:11:07.645  1036  1537 D LGWifiP2pService: after postfix = G3
07-01 12:11:07.645  1036  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
07-01 12:11:07.645  1968  1968 D WfdsService: isConnected: false
07-01 12:11:07.646  1036  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
07-01 12:11:07.646  1036  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
07-01 12:11:07.647  1036  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
07-01 12:11:07.647  1036  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
07-01 12:11:07.647  1036  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
07-01 12:11:07.647  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
07-01 12:11:07.647  1036  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
07-01 12:,11:07.647  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress
07-01 12:11:07.647  1036  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
07-01 12:11:07.648  1036  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
07-01 12:11:07.648  1036  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
07-01 12:11:07.648  1036  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
07-01 12:11:07.648  1036  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
07-01 12:11:07.649  1036  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
07-01 12:11:07.649  1036  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
07-01 12:11:07.649  1036  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
07-01 12:11:07.649  1036  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
07-01 12:11:07.651  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,07-01 12:11:07.651  1036  1539 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
07-01 12:11:07.652  1036  1539 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
07-01 12:11:07.652  1036  1539 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
07-01 12:11:07.655  1036  1539 E WifiStateMachine:  DisconnectedState what:132106 1 0
07-01 12:11:07.655  1968  1968 I WfdStateTracker: handleP2pThisDeviceChanged
07-01 12:11:07.655  1968  1968 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-01 12:11:07.655  1968  1968 D WfdsService: Update P2p Interface State: 3
07-01 12:11:07.655  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 12:11:07.656  1036  1036 D RttService: SCAN_AVAILABLE : 3
07-01 12:11:07.657  1036  1558 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.657  1036  1557 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.657  1036  1557 I WifiNative-HAL: startHal
07-01 12:11:07.657  1036  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
07-01 12:11:07.657  1036  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-01 12:11:07.659  1036  1537 D LGWifiP2pService: InactiveState
07-01 12:11:07.660  1036  1537 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.660  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.660  1036  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
07-01 12:11:07.660  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-01 12:11:07.661  7549  7549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:07.661  1036  7565 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-01 12:11:07.661  1036  7565 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:07.661  1036  7565 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:07.661  1036  7565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:07.662  7549  7549 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,07-01 12:11:07.662  7549  7549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.662  1036  7565 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:07.662  1036  7565 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.662  1036  7565 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.662  1036  7565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.663  7549  7549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.663  1968  7566 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-01 12:11:07.663  1968  7566 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:07.664  1968  7566 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:07.664  1036  7565 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:07.664  1036  7565 E WifiMonitor: WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.664  1036  7565 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.664  1036  7565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.664  1036  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
07-01 12:11:07.664  1036  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.664  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.664  1036  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.665  1036  1557 D wifi    : getting scan capabilities on interface[1] = 0x95768960
07-01 12:11:07.665  1036  1557 D wifi    : failed to get capabilities : -3
07-01 12:11:07.665  1036  1557 E WifiScanningService: could not get scan capabilities
07-01 12:11:07.665  1036  1539 E WifiStateMachine:  ConnectModeState what:132106 1 0
07-01 12:11:07.665  1036  1539 E WifiStateMachine:  DriverStartedState what:132106 1 0
07-01 12:11:07.665  1036  1539 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
07-01 12:11:07.665  1036  1537 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.665  7549  7549 E wpa_supplicant: nWIFIDualbandAPConnection: 1
07-01 12:11:07.665  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.665  1036  1537 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.666  1036  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.666  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.666  1036  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.666  1968  2319 W WfdsService: DefaultState - msg [9441285] is not handled
07-01 12:11:07.666  1036  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.666  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.667  1036  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.,StateMachine$SmHandler }
07-01 12:11:07.667  1036  1036 E WifiServerServiceExt: No p2p device connected
07-01 12:11:07.667  1036  1539 E WifiStateMachine:  DisconnectedState what:132096 -100 0
07-01 12:11:07.668  1036  1539 E WifiStateMachine:  ConnectModeState what:132096 -100 0
07-01 12:11:07.668  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:11:07.668  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:11:07.668  1036  1539 E WifiStateMachine:  DriverStartedState what:132096 -100 0
07-01 12:11:07.668  1036  1539 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
07-01 12:11:07.668  7549  7549 E wpa_supplicant: disconnect_rssi_lvl: -100
07-01 12:11:07.669  6748  7568 W FormManager: Network not available. Please check & try again.
07-01 12:11:07.669  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
07-01 12:11:07.669  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
07-01 12:11:07.669  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:07.669  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
07-01 12:11:07.670  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
07-01 12:11:07.670  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
07-01 12:11:07.671  7549  7549 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:07.671  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:07.671  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
07-01 12:11:07.671  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:07.671  1036  7565 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:07.671  7549  7549 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
07-01 12:11:07.671  1036  7565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
07-01 12:11:07.671  7549  7549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.671  1036  7565 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:07.671  1036  7565 E WifiMonitor: WifiMonitor:p2p0 cnt=34 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.672  1036  7565 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.672  1036  7565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,07-01 12:11:07.672  1036  1539 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
07-01 12:11:07.672  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.672  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.672  7549  7549 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.672  1036  7565 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:07.672  1036  7565 E WifiMonitor: WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.672  1036  7565 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.672  1036  7565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
07-01 12:11:07.672  1036  1539 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
07-01 12:11:07.673  1968  7566 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,07-01 12:11:07.673  1968  7566 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
07-01 12:11:07.673  1036  1539 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
07-01 12:11:07.674  6569  6569 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 12:11:07.674  6569  6569 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
07-01 12:11:07.674  6569  6569 V [BNRBootReceiver]: Boot Receiver Return
,07-01 12:11:07.676  4321  7570 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 12:11:07.677  1036  1539 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
07-01 12:11:07.677  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
07-01 12:11:07.677  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
07-01 12:11:07.677  7549  7549 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-01 12:11:07.678  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
07-01 12:11:07.678  1036  1539 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
07-01 12:11:07.678  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-01 12:11:07.678  1036  1539 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
07-01 12:11:07.678  1036  7565 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-01 12:11:07.678  1036  7565 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-01 12:11:07.679  1036  1539 D WifiNative-wlan0: BSS_FLUSH 0: returned true
07-01 12:11:07.680  1036  1539 D WifiNative-wlan0: doBoolean: SCAN
07-01 12:11:07.680  1036  1539 D WifiNative-wlan0: SCAN: returned false
07-01 12:11:07.681  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=295000  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 12:11:07.682  4321  7571 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-01 12:11:07.682  4321  7571 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-01 12:11:07.682  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:07.682  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:07.683  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:07.683  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:07.683  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-01 12:11:07.683  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:07.683  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=295003  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
07-01 12:11:07.684  1036  1539 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 12:11:07.685  1036  1539 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 12:11:07.685  1036  1539 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 12:11:07.685  6748  7569 V FormManager: Network unavailable.
07-01 12:11:07.686  1036  1539 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 12:11:07.686  1036  1539 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
07-01 12:11:07.687  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 12:11:07.687  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
07-01 12:11:07.687  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-01 12:11:07.691  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 12:11:07.692  6748  7569 V FormManager: Network unavailable.
07-01 12:11:07.695  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:07.701  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-01 12:11:07.702  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:07.703  7016  7016 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 12:11:07.744  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-01 12:11:07.744  6891  6946 I jxcore-log: 
,07-01 12:11:07.768  6891  6943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:07.768  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:07.768  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:07.768  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:07.768  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:07.768  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:07.768  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:07.768  6891  6943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:07.771  6891  6943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:11:07.773  6891  6943 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:07.773  6891  6943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:11:07.773  6891  6943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-01 12:11:07.773  6891  6943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:11:07.773  6891  6943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16f29f0b removed from the list
07-01 12:11:07.781  6891  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-01 12:11:07.782  6891  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-01 12:11:07.782  6891  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-01 12:11:07.782  6891  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-01 12:11:07.783  6891  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-01 12:11:07.783  6891  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-01 12:11:07.787  6891  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-01 12:11:07.787  6891  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-01 12:11:07.789  6891  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-01 12:11:07.789  6891  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-01 12:11:07.789  6891  6943 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-01 12:11:07.789  6891  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-01 12:11:07.789  6891  6943 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,07-01 12:11:07.790  6891  6943 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-01 12:11:07.791  6891  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-01 12:11:07.791  6891  6943 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-01 12:11:07.792  6891  6943 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-01 12:11:07.792  6891  6943 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-01 12:11:07.792  6891  6943 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-01 12:11:07.792  6891  6943 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-01 12:11:07.795  6891  6943 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-01 12:11:07.796  6891  6943 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-01 12:11:07.801  6891  6943 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@387420f3 Bundle[{}]
07-01 12:11:07.802  6891  6943 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 12:11:07.802  6891  6943 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-01 12:11:07.803  6891  6943 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-01 12:11:07.803  6891  6943 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 12:11:07.804  6891  6943 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 12:11:07.805  6891  6943 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-01 12:11:07.818  6891  7572 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 815, name: My test thread name)
07-01 12:11:07.819  6891  7572 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 815, thread name: My test thread name)
,07-01 12:11:07.819  6891  7572 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 815, name: My test thread name)
07-01 12:11:07.824  6891  7573 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 817, name: My test thread name)
07-01 12:11:07.824  6891  7573 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 817, thread name: My test thread name)
07-01 12:11:07.824  6891  7573 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 817, name: My test thread name)
07-01 12:11:07.827  6891  6943 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 36
07-01 12:11:07.827  6891  6943 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 36
07-01 12:11:07.827  6891  6943 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-01 12:11:07.827  6891  6943 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-01 12:11:07.827  6891  6943 E com.test.thalitest.ThaliTestRunner: Total duration: 9148 ms
07-01 12:11:07.827  6891  6943 I System.out: Tests succeded_00
07-01 12:11:07.827  6891  6943 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 9192ms. Plugin should use CordovaInterface.getThreadPool().
07-01 12:11:07.855  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-01 12:11:07.855  6891  6946 I jxcore-log: 
,07-01 12:11:07.934  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-01 12:11:07.934  6891  6946 I jxcore-log: 
,07-01 12:11:07.952  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-01 12:11:07.952  6891  6946 I jxcore-log: 
,07-01 12:11:08.180  7549  7549 E wpa_supplicant: USIM:  scard_init function
,07-01 12:11:08.181  7549  7549 I wpa_supplicant: Trying to associate with SSID 'NG700'
,07-01 12:11:08.186  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
07-01 12:11:08.186  1036  7565 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
07-01 12:11:08.187  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
07-01 12:11:08.187  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPS-AP-AVAILABLE 
07-01 12:11:08.187  1036  7565 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
07-01 12:11:08.187  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
07-01 12:11:08.187  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
07-01 12:11:08.189  1036  1539 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,07-01 12:11:08.190  1036  1539 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
07-01 12:11:08.191  1036  1539 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
07-01 12:11:08.192  1036  1539 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
07-01 12:11:08.192  1036  1539 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
07-01 12:11:08.206  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=295526  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-01 12:11:08.209  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=295529  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,07-01 12:11:08.209  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
07-01 12:11:08.217  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.217  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:08.217  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.217  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.217  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-01 12:11:08.220  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.221  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.221  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.221  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-01 12:11:08.222  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 12:11:08.222  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,07-01 12:11:08.224  6966  6966 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-01 12:11:08.227  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.233  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.233  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:08.234  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.241  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:11:08.248  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.251  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.251  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.253  7016  7016 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
07-01 12:11:08.263  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,07-01 12:11:08.268  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 12:11:08.272  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-01 12:11:08.272  6891  6946 I jxcore-log: 
07-01 12:11:08.273  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.279  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-01 12:11:08.279  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
07-01 12:11:08.279  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.279  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.279  7016  7016 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-01 12:11:08.299  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-01 12:11:08.299  6891  6946 I jxcore-log: 
07-01 12:11:08.300  7549  7549 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-01 12:11:08.302  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
07-01 12:11:08.302  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
07-01 12:11:08.302  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
07-01 12:11:08.302  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: Associated with f4:f2:6d:22:99:3e
07-01 12:11:08.303  1036  1097 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-01 12:11:08.303  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=295623  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-01 12:11:08.303  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 12:11:08.304  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 12:11:08.304  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-01 12:11:08.304  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-01 12:11:08.304  6966  6966 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-01 12:11:08.304  6966  6966 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
07-01 12:11:08.305  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=295624  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
07-01 12:11:08.305  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-01 12:11:08.305  6891  6946 I jxcore-log: 
07-01 12:11:08.305  1036  1539 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 41 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=295625
07-01 12:11:08.305  1036  1539 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 41 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=295625
07-01 12:11:08.305  1036  1539 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 41 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=295625
07-01 12:11:08.306  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 41 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=295626
07-01 12:11:08.306  1036  1539 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 41 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=295626
07-01 12:11:08.306  1036  1539 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:08.306  1036  1539 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:08.307  1036  1539 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:08.307  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:08.307  1036  1539 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
07-01 12:11:08.307  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=295627  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-01 12:11:08.309  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.309  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:08.309  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 12:11:08.309  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 12:11:08.309  7549  7549 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07,-01 12:11:08.309  7549  7549 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-01 12:11:08.309  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.309  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
07-01 12:11:08.309  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-01 12:11:08.309  1036  7565 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-01 12:11:08.309  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
07-01 12:11:08.309  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-01 12:11:08.309  1036  7565 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-01 12:11:08.310  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.310  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.310  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-01 12:11:08.310  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 12:11:08.310  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 12:11:08.312  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-01 12:11:08.312  6891  6946 I jxcore-log: 
,07-01 12:11:08.315  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-01 12:11:08.316  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=295636  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
07-01 12:11:08.326  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.326  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:11:08.326  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-01 12:11:08.328  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 12:11:08.328  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
07-01 12:11:08.328  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.328  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:08.329  6966  6966 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-01 12:11:08.329  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
,07-01 12:11:08.329  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-01 12:11:08.329  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-01 12:11:08.329  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.329  6966  6966 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-01 12:11:08.329  6966  6966 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-01 12:11:08.329  1036  1539 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=295649  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-01 12:11:08.330  6966  6966 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
07-01 12:11:08.330  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=295650  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
07-01 12:11:08.331  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.331  1036  1539 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=295651
07-01 12:11:08.332  1036  1539 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=295652
07-01 12:11:08.332  1036  1539 D WifiNative-wlan0: doString: [STATUS]
07-01 12:11:08.333  1036  7565 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
07-01 12:11:08.333  1036  7565 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
07-01 12:11:08.333  1036  1539 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
07-01 12:11:08.334  1036  1539 I WifiServiceExtension: setVHTCapabilityType  : false
07-01 12:11:08.339  1036  1539 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-01 12:11:08.339  1036  1539 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
07-01 12:11:08.339  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:11:08.343  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.344  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-01 12:11:08.344  6891  6946 I jxcore-log: 
07-01 12:11:08.345  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.345  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.345  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-01 12:11:08.346  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.346  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.346  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-01 12:11:08.347  1036  1539 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-01 12:11:08.347  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 12:11:08.347  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-01 12:11:08.347  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-01 12:11:08.347  1036  1545 D ConnectivityService: Got NetworkAgent Messenger
07-01 12:11:08.347  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-01 12:11:08.347  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-01 12:11:08.347  1036  1545 D ConnectivityService: NetworkAgent connected
07-01 12:11:08.350  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.350  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:08.351  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
07-01 12:11:08.351  1036  1539 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 12:11:08.351  1036  1539 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
07-01 12:11:08.351  1036  1539 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
07-01 12:11:08.351  1036  1539 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
07-01 12:11:08.352  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.355  1036  1539 D WifiNative-wlan0: SAVE_CONFIG: returned true
,07-01 12:11:08.356   318   902 D CommandListener: Setting iface cfg
07-01 12:11:08.357  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.357  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.357  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:08.357  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.358  7016  7016 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 12:11:08.360  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.362  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.366  1036  7584 D DhcpStateMachine: StoppedState
07-01 12:11:08.366  1036  1539 E WifiStateMachine: Start Dhcp Watchdog 2
07-01 12:11:08.367  1036  7584 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:08.367  1036  7584 D DhcpStateMachine: WaitBeforeStartState
07-01 12:11:08.367  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=295687  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 12:11:08.367  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=295687  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 12:11:08.368  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=295688  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 12:11:08.369  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-01 12:11:08.369  6891  6946 I jxcore-log: 
07-01 12:11:08.371  1036  1539 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=295691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 12:11:08.371  1036  1539 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=295691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 12:11:08.371  1036  1539 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=295691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
07-01 12:11:08.372  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:104511] from screen [on:0 period:-1510946860] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:08.373  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1510946859] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:08.373  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:08.373  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-01 12:11:08.373  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-01 12:11:08.374  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 12:11:08.377  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.378  1036  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
07-01 12:11:08.378  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.378  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.378  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.379  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.379  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.379  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.379  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-01 12:11:08.380  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
07-01 12:11:08.380  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=136,0,0
07-01 12:11:08.380  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
07-01 12:11:08.380  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
07-01 12:11:08.380  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.380  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
07-01 12:11:08.380  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 0
07-01 12:11:08.381  1036  1539 D WifiNative-wlan0: SET ps 0: returned true
07-01 12:11:08.381  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
07-01 12:11:08.381  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
07-01 12:11:08.381  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
07-01 12:11:08.381  1036  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ca70817 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:08.382  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ca70817 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:08.382  1036  7584 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:08.382  1036  7584 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-01 12:11:08.382  1036  1539 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-01 12:11:08.382  1036  1539 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-01 12:11:08.383  1036  1539 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-01 12:11:08.383   318   902 D CommandListener: Setting iface cfg
07-01 12:11:08.384   318   902 D CommandListener: Trying to bring up wlan0
07-01 12:11:08.384  1036  1539 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-01 12:11:08.386  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.386  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.386  7016  7016 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-01 12:11:08.390  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,07-01 12:11:08.390  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-01 12:11:08.391  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.391  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.392  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.392  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.392  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.393  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.393  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
07-01 12:11:08.394  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-01 12:11:08.394  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-01 12:11:08.394  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
07-01 12:11:08.394  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
07-01 12:11:08.395  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
07-01 12:11:08.395  1036  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:08.395  1036  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:08.395  1036  1539 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
07-01 12:11:08.395  1036  1539 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
07-01 12:11:08.395  7549  7549 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
07-01 12:11:08.395  1036  1539 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
07-01 12:11:08.395  1036  1539 D WifiNative-wlan0: doBoolean: SET ps 1
07-01 12:11:08.398  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:11:08.407  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.411  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.411  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.412  7016  7016 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-01 12:11:08.414  1036  1539 D WifiNative-wlan0: SET ps 1: returned true
07-01 12:11:08.414  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
07-01 12:11:08.415  1036  1539 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-01 12:11:08.415  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
07-01 12:11:08.415  1036  1539 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-01 12:11:08.415  1036  1545 D ConnectivityService: ignoring duplicate network state non-change
07-01 12:11:08.418  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.420  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.420  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:08.421  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.421  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.421  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.421  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-01 12:11:08.423  1036  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-01 12:11:08.424  1036  1545 D ConnectivityService: Adding iface wlan0 to network 101
,07-01 12:11:08.426  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.426  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.426  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-01 12:11:08.432  1968  1968 V WfdStateTracker: handleWifiStateChangedEvent: 1
07-01 12:11:08.433  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-01 12:11:08.433  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.433  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.433  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-01 12:11:08.436  1036  1539 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-01 12:11:08.437  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-01 12:11:08.439  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.439  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 12:11:08.439  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:08.439  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-01 12:11:08.441  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.441  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-01 12:11:08.442  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.443  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.444  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-01 12:11:08.444  1036  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-01 12:11:08.444  1036  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-01 12:11:08.444  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.445  1036  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
07-01 12:11:08.445   318   902 E Netd    : netlink response contains error (File exists)
07-01 12:11:08.446  1036  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
07-01 12:11:08.447  1036  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-01 12:11:08.447  1036  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
07-01 12:11:08.447  1036  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
07-01 12:11:08.447  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:08.447  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-01 12:11:08.447  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 12:11:08.447  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-01 12:11:08.447  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-01 12:11:08.447  1036  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-01 12:11:08.447  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-01 12:11:08.447  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:11:08.448  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:08.448  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-01 12:11:08.448  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.448  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-01 12:11:08.448  1036  1545 D ConnectivityService: currentScore = 0, newScore = 20
07-01 12:11:08.448  1036  1545 D ConnectivityService:    accepting network in place of null
07-01 12:11:08.448  1036  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.448  1036  1539 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.448  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:11:08.448  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:08.448  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-01 12:11:08.448  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:08.448  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-01 12:11:08.450  1036  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-01 12:11:08.450  1036  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-01 12:11:08.450  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 12:11:08.451  1881  1881 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.451  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NO,T_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-01 12:11:08.451  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
07-01 12:11:08.452  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-01 12:11:08.452  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-01 12:11:08.452  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-01 12:11:08.454   318  7588 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
07-01 12:11:08.455  1036  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:08.455  1036  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-01 12:11:08.455  1036  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,07-01 12:11:08.456  1036  1545 D ConnectivityService: validation of new default Network = false
07-01 12:11:08.456  1036  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-01 12:11:08.456  1036  1545 D DSQN    : enableDataServiceNotify 
07-01 12:11:08.453  7589  7589 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:08.453  7589  7589 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:08.456  1036  1545 D DSQN    : start dsqn bin
07-01 12:11:08.457  1036  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-01 12:11:08.462  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-01 12:11:08.462  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.462  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:08.462  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:08.468  1603  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-01 12:11:08.481  7589  7589 E DSQN    : DSQN ssw
07-01 12:11:08.482  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.492  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,07-01 12:11:08.495  1842  7593 I CheckinService: active receiver: enabled
07-01 12:11:08.495  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.496  7016  7016 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 12:11:08.496  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-01 12:11:08.496  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.497  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.500  1842  7593 I CheckinService: Preparing to send checkin request
07-01 12:11:08.500  1842  7593 I EventLogService: Accumulating logs since 1467367629207
07-01 12:11:08.503  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.512  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:11:08.517  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,07-01 12:11:08.521  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-01 12:11:08.521  6891  6946 I jxcore-log: 
07-01 12:11:08.521  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.521   318  7588 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-01 12:11:08.522  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.524  7016  7016 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,07-01 12:11:08.527  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.528  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-01 12:11:08.528  6891  6946 I jxcore-log: 
07-01 12:11:08.534  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-01 12:11:08.537  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.541  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.542  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.542  7016  7016 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
07-01 12:11:08.544  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.545  1842  7593 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
07-01 12:11:08.547  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-01 12:11:08.550  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:11:08.553  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 12:11:08.558  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.559  6891  6946 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-01 12:11:08.559  6891  6946 I jxcore-log: 
,07-01 12:11:08.562  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.563  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.563  7016  7016 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-01 12:11:08.564  7016  7016 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-01 12:11:08.564  7016  7016 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-01 12:11:08.569  6891  6946 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
07-01 12:11:08.570   318  7588 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-01 12:11:08.571  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
07-01 12:11:08.571  6891  6946 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-01 12:11:08.571  6891  6946 I jxcore-log: 
,07-01 12:11:08.573  6984  6984 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-01 12:11:08.573  6984  6984 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-01 12:11:08.575  6966  6966 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-01 12:11:08.581  6966  6966 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-01 12:11:08.583  1036  7584 D DhcpStateMachine: DHCPV4 request on wlan0
07-01 12:11:08.583  1036  7584 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-01 12:11:08.583  1036  7584 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,07-01 12:11:08.583  7595  7595 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:08.583  7595  7595 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
07-01 12:11:08.587  7016  7016 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
07-01 12:11:08.587  7016  7016 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
07-01 12:11:08.588  7016  7016 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
07-01 12:11:08.589  7016  7016 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
07-01 12:11:08.589  7016  7016 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
07-01 12:11:08.592  7595  7595 I dhcpcd  : version 5.5.6 starting
07-01 12:11:08.593  7595  7595 E dhcpcd  : get_duid: m
07-01 12:11:08.593  7595  7595 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
07-01 12:11:08.593  7595  7595 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
07-01 12:11:08.604   318   901 D LGDataListener: argv[0]=dsqncommand
07-01 12:11:08.604   318   901 D LGDataListener: argv[1]=wlan0
07-01 12:11:08.604   318   901 D LGDataListener: argv[2]=1
07-01 12:11:08.604   318   901 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-01 12:11:08.604  1036  1095 D DSQN    : DSQM DsqnNotification wlan0  1
07-01 12:11:08.604  1036  1095 D DSQN    : start to monitor internet connection
,07-01 12:11:08.629  1036  2332 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7604 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,07-01 12:11:08.632  7595  7595 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-01 12:11:08.632  7595  7595 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-01 12:11:08.632  7595  7595 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-01 12:11:08.632  7595  7595 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
07-01 12:11:08.633  7595  7595 D dhcpcd  : wlan0: sending REQUEST (xid 0xae4d6dde), next in 4.49 seconds
07-01 12:11:08.642  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 01 Jul 2016 10:11:08 GMT], X-Android-Received-Millis=[1467367868641], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467367868603]}
,07-01 12:11:08.642  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-01 12:11:08.642  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-01 12:11:08.642  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-01 12:11:08.642  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-01 12:11:08.642  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:11:08.642  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:08.642  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-01 12:11:08.642  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-01 12:11:08.642  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-01 12:11:08.642  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.642  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:08.643  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:08.643  1036  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.643  1603  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-01 12:11:08.643  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-01 12:11:08.643  1036  1539 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.643  1036  1539 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:11:08.644  1881  1881 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:08.644  1881  1881 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
07-01 12:11:08.645  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:11:08.645  6891  6946 I jxcore-log: 
07-01 12:11:08.646  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:11:08.646  6891  6946 I jxcore-log: 
07-01 12:11:08.648  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:11:08.648  6891  6946 I jxcore-log: 
07-01 12:11:08.648  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:08.648  6891  6946 I jxcore-log: 
07-01 12:11:08.650  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:08.650  6891  6946 I jxcore-log: 
07-01 12:11:08.652  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnerg,y":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:11:08.652  6891  6946 I jxcore-log: 
07-01 12:11:08.653  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:11:08.653  6891  6946 I jxcore-log: 
07-01 12:11:08.654  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:08.654  6891  6946 I jxcore-log: 
07-01 12:11:08.654  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-01 12:11:08.654  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:08.654  6891  6946 I jxcore-log: 
07-01 12:11:08.654  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.655  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
07-01 12:11:08.655  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:11:08.655  6891  6946 I jxcore-log: 
,07-01 12:11:08.657  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:08.657  6891  6946 I jxcore-log: 
07-01 12:11:08.658  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:11:08.658  6891  6946 I jxcore-log: 
07-01 12:11:08.658  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:11:08.658  6891  6946 I jxcore-log: 
07-01 12:11:08.658  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-01 12:11:08.658  6891  6946 I jxcore-log: 
07-01 12:11:08.659  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-01 12:11:08.659  6891  6946 I jxcore-log: 
07-01 12:11:08.664  7595  7595 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
07-01 12:11:08.670  7604  7604 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-01 12:11:08.670  7604  7604 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 12:11:08.675  7595  7595 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
07-01 12:11:08.675  7595  7595 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
07-01 12:11:08.675  7595  7595 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
07-01 12:11:08.675  7595  7595 D dhcpcd  : wlan0: adding default route via 192.168.1.1
07-01 12:11:08.675  7595  7595 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
07-01 12:11:08.675  7595  7595 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
07-01 12:11:08.675  7595  7595 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
07-01 12:11:08.675  7595  7595 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
07-01 12:11:08.686  7604  7604 I MultiDex: VM with version 2.1.0 has multidex support
07-01 12:11:08.686  7604  7604 I MultiDex: install
07-01 12:11:08.686  7604  7604 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-01 12:11:08.693  7604  7604 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
07-01 12:11:08.696  2225  2225 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-01 12:11:08.703  2225  2225 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-01 12:11:08.704  2225  2225 D c       : Getting all permits...
07-01 12:11:08.704  2225  2225 D a       : Opening database...
07-01 12:11:08.715  2225  2225 D a       : Opening database auth.proximity.permit_store...
07-01 12:11:08.716  2225  2225 D a       : Closing database...
,07-01 12:11:08.907  1036  1545 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,07-01 12:11:08.921  7321  7345 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-01 12:11:08.986  1036  7584 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,07-01 12:11:08.989  1036  7584 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
07-01 12:11:08.990  1036  7584 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-01 12:11:08.990  1036  7584 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
07-01 12:11:08.990  1036  7584 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
07-01 12:11:08.990  1036  7584 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-01 12:11:08.990  1036  7584 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
07-01 12:11:08.990  1036  7584 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,07-01 12:11:08.992  1036  7584 D DhcpStateMachine: RunningState
07-01 12:11:09.156  7604  7619 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:09.156  7604  7619 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 12:11:09.308  7653  7653 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-01 12:11:09.361  7653  7653 I dex2oat : dex2oat took 52.722ms (threads: 4)
,07-01 12:11:09.380  7604  7619 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:11:09.380  7604  7619 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:11:09.380  7604  7619 I Adreno-EGL: Build Date: 12/12/14 금
07-01 12:11:09.380  7604  7619 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 12:11:09.380  7604  7619 I Adreno-EGL: Remote Branch: 
07-01 12:11:09.380  7604  7619 I Adreno-EGL: Local Patches: 
07-01 12:11:09.380  7604  7619 I Adreno-EGL: Reconstruct Branch: 
,07-01 12:11:09.535  7604  7619 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:11:09.535  7604  7619 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:11:09.535  7604  7619 I Adreno-EGL: Build Date: 12/12/14 금
07-01 12:11:09.535  7604  7619 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 12:11:09.535  7604  7619 I Adreno-EGL: Remote Branch: 
07-01 12:11:09.535  7604  7619 I Adreno-EGL: Local Patches: 
07-01 12:11:09.535  7604  7619 I Adreno-EGL: Reconstruct Branch: 
,07-01 12:11:09.615  7604  7619 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-01 12:11:09.615  7604  7619 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-01 12:11:09.615  7604  7619 I Adreno-EGL: Build Date: 12/12/14 금
07-01 12:11:09.615  7604  7619 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
07-01 12:11:09.615  7604  7619 I Adreno-EGL: Remote Branch: 
07-01 12:11:09.615  7604  7619 I Adreno-EGL: Local Patches: 
07-01 12:11:09.615  7604  7619 I Adreno-EGL: Reconstruct Branch: 
,07-01 12:11:09.770  1036  1539 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 12:11:09.771  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 12:11:09.772  1036  1539 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 12:11:09.773  1036  1539 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,07-01 12:11:09.778  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 12:11:09.779  1036  1539 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
07-01 12:11:09.779  1036  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
07-01 12:11:09.780  1036  1545 D ConnectivityService: identical MTU - not setting
07-01 12:11:09.781  1036  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-01 12:11:09.781  1036  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-01 12:11:09.781  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:09.781  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:09.782  1036  1545 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:09.783  1603  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-01 12:11:09.787   318  7661 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
07-01 12:11:09.787   318  7661 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
07-01 12:11:09.823   318  7661 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,07-01 12:11:09.852  1036  1052 I ActivityManager: Killing 7161:com.lge.appbox.client/u0a11 (adj 15): empty #17
,07-01 12:11:09.926  1036  2093 W libprocessgroup: failed to open /acct/uid_10011/pid_7161/cgroup.procs: No such file or directory
,07-01 12:11:10.029  1842  7593 I CheckinTask: Sending checkin request (7603 bytes)
,07-01 12:11:10.259  1842  7593 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-01 12:11:10.279  1842  7593 I CheckinService: active receiver: disabled
,07-01 12:11:10.300  2225  2225 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-01 12:11:10.319  2225  2225 I GCM     : GCM config loaded
,07-01 12:11:10.335   318  7667 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-01 12:11:10.337   318  7667 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
07-01 12:11:10.347  7248  7248 V SetupWizard: Connected to Gservices successfully
07-01 12:11:10.373   318  7667 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,07-01 12:11:10.665  2225  7670 D GCM     : Connected
,07-01 12:11:10.712  2225  7670 D GCM     : Message class com.google.e.a.a.q
,07-01 12:11:11.382  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=68.0, 0.0, 0.0  rx=107.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1510943850] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 12:11:11.395  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=68.0, 0.0, 0.0  rx=107.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510943837] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-01 12:11:11.395  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:11:11.409  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,07-01 12:11:11.435  1036  1540 V WifiInternetCheck: Single check msg out of sync, ignoring.
,07-01 12:11:11.455  1036  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:11.471  1036  1097 D Tethering: MasterInitialState.processMessage what=3
,07-01 12:11:11.477  1036  1092 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:11.509  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:11.509  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:11.509  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:11.509  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:11.509  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:11.509  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:11:11.509  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:11:11.509  6891  6891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 12:11:11.514  6891  6891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 12:11:11.519  6891  6946 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:11:11.519  6891  6946 I jxcore-log: 
07-01 12:11:11.522  6385  6385 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,07-01 12:11:11.527  6385  6983 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
07-01 12:11:11.539  5757  5757 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-01 12:11:11.561  2225  2225 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:11.620  1036  1986 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,07-01 12:11:11.626  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:11.627  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:11.627  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-01 12:11:11.627  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:11.627  1036  1092 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:11.627  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-01 12:11:11.640  1036  1051 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7684 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-01 12:11:11.672  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 01 Jul 2016 10:11:11 GMT], X-Android-Received-Millis=[1467367871672], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467367871631]}
07-01 12:11:11.672  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-01 12:11:11.672  1036  7583 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-01 12:11:11.673  1036  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
07-01 12:11:11.673  1036  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
07-01 12:11:11.673  1036  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:11:11.673  1036  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:11.673  1036  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-01 12:11:11.673  1036  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
07-01 12:11:11.673  1036  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
07-01 12:11:11.673  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:11.673  1036  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:11.673  1036  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:11.673  1603  1814 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-01 12:11:11.693  7684  7684 I AppUp4:AppBoxCP: onCreate
07-01 12:11:11.694  7684  7684 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-01 12:11:11.701  7684  7684 I AppUp4:DB:  setFingerPrint start
07-01 12:11:11.701  7684  7684 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
07-01 12:11:11.706  7684  7684 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
07-01 12:11:11.706  7684  7684 I AppUp4:DB:  SDK version = 21
07-01 12:11:11.706  7684  7684 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-01 12:11:11.708  7684  7684 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,07-01 12:11:11.708  7684  7684 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-01 12:11:11.709  7684  7684 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:11.710  7684  7684 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-01 12:11:11.710  7684  7684 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
07-01 12:11:11.714  7684  7684 I AppUp4:CustModeStarterReceiver: onReceive
07-01 12:11:11.736  7684  7684 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:11.736  7684  7684 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 12:11:11.741  7684  7684 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d24beb9
07-01 12:11:11.741  7684  7684 D AppUp4:CustFacade: isCustomizationCompleted : false
07-01 12:11:11.741  7684  7684 D AppUp4:CustFacade: isPhone : true
07-01 12:11:11.741  7684  7684 D AppUp4:CustModeStarterReceiver: begin check event
07-01 12:11:11.742  7684  7684 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-01 12:11:11.742  7684  7684 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
07-01 12:11:11.742  7684  7706 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-01 12:11:11.742  7684  7706 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-01 12:11:11.742  7684  7706 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-01 12:11:11.746  1036  1986 I ActivityManager: Killing 7194:com.lge.email/u0a23 (adj 15): empty #17
07-01 12:11:11.804  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:11.805  4321  4321 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-01 12:11:11.806  1036  1950 W libprocessgroup: failed to open /acct/uid_10023/pid_7194/cgroup.procs: No such file or directory
07-01 12:11:11.810  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:11.814  4321  4321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
07-01 12:11:11.822  3480  3480 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:11.827  4321  7709 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-01 12:11:11.828  3480  3480 V DownloadManager: DownloadService onCreate
07-01 12:11:11.830  3480  7710 I DownloadManager: in removeSpuriousFiles
07-01 12:11:11.831  3480  7710 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
07-01 12:11:11.833  3480  7710 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2c4b0f0d on behalf of 3480
07-01 12:11:11.834  4321  7709 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
07-01 12:11:11.834  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
07-01 12:11:11.834  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
07-01 12:11:11.834  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
07-01 12:11:11.834  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
07-01 12:11:11.834  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
07-01 12:11:11.835  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
07-01 12:11:11.835  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
07-01 12:11:11.835  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
07-01 12:11:11.835  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
07-01 12:11:11.835  3480  7710 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
07-01 12:11:11.837  3480  7710 I DownloadManager: in trimDatabase
07-01 12:11:11.838  3480  7710 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
07-01 12:11:11.839  3480  7710 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2b998ec2 on behalf of 3480
07-01 12:11:11.841  4321  7712 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:11.841  4321  7712 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,07-01 12:11:11.879  1036  2093 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7714 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-01 12:11:11.883  3480  3480 V DownloadManager: DownloadService onStartCommand
07-01 12:11:11.883  3480  7711 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
07-01 12:11:11.885  3480  7711 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@34268f09 on behalf of 3480
07-01 12:11:11.887  3480  7711 V DownloadManager: processing inserted download 1
07-01 12:11:11.887  4321  7709 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
07-01 12:11:11.888  3480  7711 V DownloadManager: processing inserted download 4
07-01 12:11:11.891  3480  7711 V DownloadManager: processing inserted download 7
07-01 12:11:11.893  4321  4321 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
07-01 12:11:11.893  3480  7711 V DownloadManager: processing inserted download 8
,07-01 12:11:11.895  3480  7711 V DownloadManager: processing inserted download 9
07-01 12:11:11.897  3480  7711 V DownloadManager: processing inserted download 10
07-01 12:11:11.897  4321  4321 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
07-01 12:11:11.897  4321  4321 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
07-01 12:11:11.898  3480  7711 V DownloadManager: processing inserted download 11
07-01 12:11:11.899  4321  4321 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
07-01 12:11:11.900  3480  7711 V DownloadManager: processing inserted download 12
07-01 12:11:11.904  4321  4321 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,07-01 12:11:11.905  3480  7711 V DownloadManager: processing inserted download 13
07-01 12:11:11.907  3480  7711 V DownloadManager: processing inserted download 14
07-01 12:11:11.910  3480  3480 V DownloadManager: DownloadService onDestroy
,07-01 12:11:11.946  7714  7714 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:11:11.947  7714  7714 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:11:11.948  7714  7714 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-01 12:11:11.948  7714  7714 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,07-01 12:11:12.013  7714  7714 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-01 12:11:12.022  7714  7714 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,07-01 12:11:12.095  7714  7714 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-01 12:11:12.133  7714  7714 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 12:11:12.133  7714  7714 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 12:11:12.262  7714  7714 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,07-01 12:11:12.314  3424  3424 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-01 12:11:12.314  3424  3424 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:12.314  3424  3424 I LgeMiscReceiver: networkInfo.isConnected() = true
07-01 12:11:12.314  3424  3424 D PhoneState: setPdpRejectCasuse : false
,07-01 12:11:12.332   318  7747 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-01 12:11:12.334   318  7747 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,07-01 12:11:12.396   318  7747 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,07-01 12:11:12.434  1036  2332 I art     : Explicit concurrent mark sweep GC freed 76502(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.763ms total 115.540ms
,07-01 12:11:12.443  6748  7744 V FormManager: There are no updated forms. The schedule will be deleted.
07-01 12:11:12.445  6748  7744 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
07-01 12:11:12.448  7714  7714 I HubEmail: JNI_OnLoad()
,07-01 12:11:12.453  7714  7714 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:11:12.453  7714  7714 I HubEmail: registerNatives()
07-01 12:11:12.453  7714  7714 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:11:12.453  7714  7714 I HubEmail: registerNativeMethods()
07-01 12:11:12.453  7714  7714 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-01 12:11:12.453  7714  7714 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
07-01 12:11:12.455  7248  7248 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
07-01 12:11:12.456  7248  7248 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-01 12:11:12.477  7714  7748 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:11:12.481  6699  6699 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:11:12
07-01 12:11:12.482  6699  6699 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
07-01 12:11:12.482  6699  6699 D Weather.Utils: 2 : All the weather widget is gone.
07-01 12:11:12.483  6699  6699 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-01 12:11:12.483  6699  6699 D WeatherAncestor: connectivity changed - connection : true
07-01 12:11:12.483  6699  6699 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15bb9a5f
07-01 12:11:12.484  6699  6699 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
07-01 12:11:12.484  6699  6699 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
07-01 12:11:12.484  6699  6699 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
07-01 12:11:12.484  6699  6699 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-01 12:11:12.484  6699  6699 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:11:12
07-01 12:11:12.495  1036  1985 I ActivityManager: Killing 6771:com.lge.lifetracker/u0a37 (adj 15): empty #17
,07-01 12:11:12.579  1036  1051 W libprocessgroup: failed to open /acct/uid_10037/pid_6771/cgroup.procs: No such file or directory
,07-01 12:11:12.660   318  7750 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-01 12:11:12.661   318  7750 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,07-01 12:11:12.700   318  7750 D libc-netbsd: res_queryN name = www.google.com succeed
,07-01 12:11:12.711   318  7752 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-01 12:11:12.711   318  7752 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
07-01 12:11:12.711   318  7752 D libc-netbsd: res_queryN name = clients3.google.com succeed
07-01 12:11:12.787  1036  1541 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,07-01 12:11:14.417  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=51.5, 0.0, 0.0  rx=68.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510940815] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 12:11:14.420  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=51.5, 0.0, 0.0  rx=68.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510940812] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-01 12:11:14.420  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:14.772  1036  2330 I ActivityManager: Killing 7037:com.lge.settings.easy/1000 (adj 15): empty #17
,07-01 12:11:14.816  1036  1949 W libprocessgroup: failed to open /acct/uid_1000/pid_7037/cgroup.procs: No such file or directory
,07-01 12:11:15.064  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1f7b7285 type 2 when 302372 com.google.android.gms} when 302372
,07-01 12:11:15.080  7016  7016 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
07-01 12:11:15.080  7016  7016 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5682
07-01 12:11:15.092   318  7757 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,07-01 12:11:15.094   318  7757 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
07-01 12:11:15.095   318  7757 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,07-01 12:11:15.393  2225  7758 D GCM     : Connected
,07-01 12:11:15.436  2225  7758 D GCM     : Message class com.google.e.a.a.q
,07-01 12:11:17.443  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=34.8, 0.0, 0.0  rx=40.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1510937789] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 12:11:17.456  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=34.8, 0.0, 0.0  rx=40.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510937776] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-01 12:11:17.457  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:11:18.566  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-01 12:11:18.591  1036  1383 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-01 12:11:18.594  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-01 12:11:18.679  1036  1093 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7759 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 12:11:18.691  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-01 12:11:18.695  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,07-01 12:11:18.741  1036  1036 D administrator: Handling package changes for user 0
,07-01 12:11:18.750  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:11:18.753  2090  2090 I [LGHome]LGMenuPagedAppsView: [LGMenuPagedAppsView.java:3983:updateApps()]updateApps updateList size = 1
,07-01 12:11:18.779  7759  7759 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 12:11:18.849  7759  7759 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:11:18.849  7759  7759 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 12:11:18.850  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
07-01 12:11:18.850  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-01 12:11:18.897  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 12:11:18.904  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-01 12:11:18.913  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,07-01 12:11:18.917  2498  2498 V GmsNetworkLocationProvi: DISABLE
,07-01 12:11:18.953  7759  7804 I Babel   : MmsConfig: mnc/mcc: 0/0
07-01 12:11:18.953  7759  7804 I Babel   : MmsConfig.loadMmsSettings
07-01 12:11:18.954  2498  2498 E GCoreFlp: Bound FusedProviderService with LocationManager
07-01 12:11:18.961  7759  7804 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
07-01 12:11:18.961  7759  7804 I Babel   : MmsConfig.loadFromDatabase
,07-01 12:11:18.986  7759  7804 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-01 12:11:18.986  7759  7804 I Babel   : MmsConfig.loadFromResources
07-01 12:11:18.987  7759  7759 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:18.987  7759  7804 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
07-01 12:11:18.988  7759  7804 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,07-01 12:11:19.007  1842  7806 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-01 12:11:19.007  1842  7806 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
07-01 12:11:19.009  7759  7802 W AudioCapabilities: Unsupported mime audio/evrc
,07-01 12:11:19.012  7759  7802 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 12:11:19.012  7684  7684 I AppUp4:CustModeStarterReceiver: onReceive
07-01 12:11:19.016  7684  7684 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2d24beb9
07-01 12:11:19.016  7684  7684 D AppUp4:CustFacade: isCustomizationCompleted : false
07-01 12:11:19.016  7684  7684 D AppUp4:CustFacade: isPhone : true
,07-01 12:11:19.016  7684  7684 D AppUp4:CustModeStarterReceiver: begin check event
07-01 12:11:19.016  7684  7684 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
07-01 12:11:19.018  7759  7802 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-01 12:11:19.020  1842  4786 I Icing   : updateResources: need to parse e{com.google.android.gms}
07-01 12:11:19.040  1036  1773 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7808 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-01 12:11:19.057  7759  7802 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-01 12:11:19.057  1036  2332 I ActivityManager: Killing 6569:com.lge.bnr/1000 (adj 15): empty #17
07-01 12:11:19.059  7759  7802 W AudioCapabilities: Unsupported mime audio/qcelp
07-01 12:11:19.060  7759  7802 W AudioCapabilities: Unsupported mime audio/evrc
07-01 12:11:19.071  7759  7802 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-01 12:11:19.072  7759  7802 W VideoCapabilities: Unsupported mime video/divx
,07-01 12:11:19.074  7759  7802 W VideoCapabilities: Unsupported mime video/divx311
07-01 12:11:19.075  7759  7802 W VideoCapabilities: Unsupported mime video/divx4
07-01 12:11:19.079  7759  7802 W VideoCapabilities: Unsupported mime video/mp4v-esdp
07-01 12:11:19.089  7759  7802 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-01 12:11:19.092  7759  7802 W AudioCapabilities: Unsupported mime audio/eac3
,07-01 12:11:19.093  7759  7802 W AudioCapabilities: Unsupported mime audio/ac3
07-01 12:11:19.094  7759  7802 W AudioCapabilities: Unsupported mime audio/g726
07-01 12:11:19.094  7759  7802 W AudioCapabilities: Unsupported mime audio/wma-voice
07-01 12:11:19.095  7759  7802 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-01 12:11:19.096  7759  7802 W AudioCapabilities: Unsupported mime audio/adpcm
07-01 12:11:19.097  7759  7802 W VideoCapabilities: Unsupported mime video/theora
07-01 12:11:19.098  7759  7802 W VideoCapabilities: Unsupported mime video/mjpg
,07-01 12:11:19.206  1036  2093 W libprocessgroup: failed to open /acct/uid_1000/pid_6569/cgroup.procs: No such file or directory
,07-01 12:11:19.213  1036  1092 D LocationProviderProxy: applying state to connected service
,07-01 12:11:19.238  7808  7808 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 12:11:19.239  7808  7808 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:11:19.239  7808  7808 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-01 12:11:19.240  7808  7808 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-01 12:11:19.241  7808  7808 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-01 12:11:19.314  7808  7808 I SystemConfig: BUILD Country: EU
07-01 12:11:19.314  7808  7808 I SystemConfig: BUILD Operator: OPEN
,07-01 12:11:19.357  1036  2035 I ActivityManager: Killing 6984:com.lge.sync/1000 (adj 15): empty #17
,07-01 12:11:19.531  1036  2035 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7833 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-01 12:11:19.538  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6984/cgroup.procs: No such file or directory
,07-01 12:11:19.540  7808  7828 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-01 12:11:19.540  7808  7828 I SystemConfig: existFile = false
07-01 12:11:19.540  7808  7828 I SystemConfig: canReadFile = false
07-01 12:11:19.540  7808  7828 I SystemConfig: systemFeature RCS result false
07-01 12:11:19.540  7808  7828 D SystemConfig: refreshRcsSupport() :false
,07-01 12:11:19.572  7833  7833 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 12:11:19.572  7833  7833 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 12:11:19.572  7833  7833 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-01 12:11:19.573  7833  7833 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-01 12:11:19.649  7833  7833 I AppConfig: Total System Memory = 2995761152
,07-01 12:11:19.657  7833  7833 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-01 12:11:19.719  1036  1986 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7852 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:19.722  1036  1986 I ActivityManager: Killing 6966:com.android.settings/1000 (adj 15): empty #17
07-01 12:11:19.765  1036  1773 W libprocessgroup: failed to open /acct/uid_1000/pid_6966/cgroup.procs: No such file or directory
,07-01 12:11:19.931  7852  7852 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-01 12:11:20.027  7852  7852 D LgDataFeature: LgDataFeature() Constructor: none
,07-01 12:11:20.027  7852  7852 D LgDataFeature: LgDataFeature() Constructor Done, null
,07-01 12:11:20.094  7852  7852 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,07-01 12:11:20.114  7852  7852 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-01 12:11:20.116  7852  7852 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-01 12:11:20.132  7852  7852 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
07-01 12:11:20.132  7852  7852 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,07-01 12:11:20.148  1036  1576 I ActivityManager: Killing 7714:com.lge.email/u0a23 (adj 15): empty #17
,07-01 12:11:20.178  1036  1985 W libprocessgroup: failed to open /acct/uid_10023/pid_7714/cgroup.procs: No such file or directory
,07-01 12:11:20.180  3480  3496 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
07-01 12:11:20.182  3480  3496 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3f6a2b2f on behalf of 7852
07-01 12:11:20.187  4597  7889 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
07-01 12:11:20.244  1036  2093 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7890 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:20.258  7852  7852 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-01 12:11:20.297  7852  7852 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
07-01 12:11:20.328  7890  7890 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-01 12:11:20.355  7890  7890 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,07-01 12:11:20.355  7890  7890 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-01 12:11:20.355  7890  7890 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-01 12:11:20.355  7890  7890 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-01 12:11:20.355  7890  7890 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
07-01 12:11:20.355  7890  7890 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,07-01 12:11:20.378  1036  1737 I ActivityManager: Killing 6748:com.lge.formmanager/u0a26 (adj 15): empty #17
,07-01 12:11:20.419  1036  1986 W libprocessgroup: failed to open /acct/uid_10026/pid_6748/cgroup.procs: No such file or directory
,07-01 12:11:20.474  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=21.9, 0.0, 0.0  rx=24.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1510934758] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 12:11:20.476  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=21.9, 0.0, 0.0  rx=24.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1510934756] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-01 12:11:20.476  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:11:20.610  1036  1949 V SIM_STK : Menu title from STK is T-Mobile
,07-01 12:11:20.637  4597  7889 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 450 ms] updated apps [took 450 ms] 
,07-01 12:11:23.486  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=12.4, 0.0, 0.0  rx=12.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510931747] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 12:11:23.489  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=12.4, 0.0, 0.0  rx=12.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510931743] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-01 12:11:23.489  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:26.516  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510928716] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-01 12:11:26.519  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=6.2, 0.0, 0.0  rx=6.2 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510928713] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-01 12:11:26.520  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:29.558  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3013] from screen [on:0 period:-1510925674] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:29.561  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=3.1, 0.0, 0.0  rx=3.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510925671] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:29.561  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:32.582  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510922650] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:32.593  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=2.1, 0.0, 0.0  rx=2.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510922639] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:32.593  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:11:35.617  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510919616] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:35.620  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510919613] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:35.620  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:38.647  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510916586] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:38.650  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510916582] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:38.650  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:41.676  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510913556] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:41.679  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510913553] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:41.679  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:44.706  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510910526] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-01 12:11:44.709  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510910523] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:44.709  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:47.252  1036  3533 I LocationManagerService: remove 64d597b
,07-01 12:11:47.261  1036  3533 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,07-01 12:11:47.261  1036  3533 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-01 12:11:47.263  1036  3533 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-01 12:11:47.266  1036  3533 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,07-01 12:11:47.267  1036  3533 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,07-01 12:11:47.737  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510907495] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:47.740  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510907492] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:47.740  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:48.368  1036  1539 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,07-01 12:11:48.369  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
07-01 12:11:48.370  1036  1539 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
07-01 12:11:48.371  1036  1539 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
07-01 12:11:48.373  1036  1539 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
07-01 12:11:48.374  1036  1539 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,07-01 12:11:50.767  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510904465] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:50.770  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510904462] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:50.770  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:53.796  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510901436] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:53.799  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510901433] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:53.799  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:56.825  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510898407] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:56.829  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510898404] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:11:56.829  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:11:59.852  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510895381] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:59.855  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510895378] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:11:59.862  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:12:00.002  1036  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=332534726, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-01 12:12:00.047  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:12:00.047  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:12:00.047  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:12:00.047  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:12:00.051  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:12:00.051  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:12:00.052  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:12:00.069  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:12:00.081  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,07-01 12:12:00.118  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=332534726 [*alarm*], flags=0x0
,07-01 12:12:02.882  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510892350] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:02.893  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510892340] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:02.893  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:12:05.913  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510889320] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:05.927  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510889307] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:05.928  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:12:08.947  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510886285] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:08.950  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510886282] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:08.950  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:11.973  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510883260] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:11.983  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510883249] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:11.983  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:12:15.003  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510880229] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:15.015  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510880217] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:15.016  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:12:18.036  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510877196] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:18.039  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510877193] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:18.039  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:21.067  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510874165] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:21.070  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510874162] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:21.070  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:24.100  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510871132] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:24.103  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510871129] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:24.103  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:27.131  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510868102] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:27.134  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510868099] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:27.134  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:30.156  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510865076] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:30.159  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510865073] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:30.159  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:33.186  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510862046] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:33.189  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510862043] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:33.189  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:36.212  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510859020] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:36.223  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510859009] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:36.223  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:12:39.246  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510855988] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:39.249  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.3 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510855984] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:39.249  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:42.273  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1510852959] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:42.274  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1510852958] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:42.274  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:45.292  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510849940] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:45.302  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1510849931] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:45.302  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:12:48.320  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510846912] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:48.323  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510846909] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:48.323  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:51.347  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510843885] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:51.350  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510843882] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:51.350  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:12:54.373  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510840859] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:54.384  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510840848] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:12:54.384  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:12:57.407  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510837826] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:57.410  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510837823] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:12:57.410  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:00.040  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:13:00.040  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:13:00.040  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:13:00.041  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:13:00.056  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:13:00.056  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:13:00.058  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:13:00.060  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:13:00.434  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510834798] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:00.449  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1510834784] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:00.449  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:13:03.477  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3009] from screen [on:0 period:-1510831756] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:03.487  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510831745] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:03.488  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:13:06.504  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510828729] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:06.516  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510828716] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:06.517  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:13:09.537  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510825695] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:09.540  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510825692] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:09.540  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:12.569  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510822663] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:12.572  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510822660] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:12.572  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:15.592  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510819640] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:15.603  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510819629] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:15.603  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:13:18.621  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2998] from screen [on:0 period:-1510816612] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:18.622  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1510816611] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:18.622  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:21.646  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3010] from screen [on:0 period:-1510813586] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:21.649  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510813583] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:21.649  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:24.671  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510810561] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:24.674  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510810558] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:24.674  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:27.700  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510807532] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:27.703  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510807529] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:27.703  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:30.727  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510804505] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:30.730  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510804502] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:30.730  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:33.753  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510801479] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:33.764  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510801468] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:33.765  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:13:36.787  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510798446] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:36.790  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510798442] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:36.790  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:39.816  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510795417] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:39.819  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510795414] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:39.819  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:42.846  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510792386] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:42.849  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510792383] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:42.849  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:45.876  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510789356] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:45.879  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510789353] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:45.880  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:48.905  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510786327] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:48.908  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510786324] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:48.908  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:51.931  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510783301] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:51.934  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510783298] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:51.934  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:54.956  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510780276] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:54.959  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510780273] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:13:54.959  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:13:57.984  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510777248] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:57.995  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510777237] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:13:57.995  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:14:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:14:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:14:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:14:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:14:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:14:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:14:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:14:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:14:01.015  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510774218] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:01.018  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510774214] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:01.018  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:04.043  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510771189] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:04.053  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510771179] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:04.054  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:14:07.076  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510768156] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:07.079  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510768153] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:07.079  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:10.107  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510765125] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:10.110  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510765122] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:10.110  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:13.138  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510762094] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:13.141  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510762091] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:13.141  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:16.165  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510759068] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:16.168  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510759064] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:16.169  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:19.198  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510756034] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:19.201  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510756031] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:19.201  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:21.828  1603  1603 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-01 12:14:21.828  1603  1603 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-01 12:14:21.844  1603  1603 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,07-01 12:14:21.848  1968  2142 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-01 12:14:21.848  1968  2142 D LEDHandler: Battery Level Remaining: 100%
07-01 12:14:21.848  1968  2142 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
07-01 12:14:21.849  1036  1544 D WifiController: battery changed pluggedType: 2
07-01 12:14:21.852  1603  1603 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-01 12:14:21.854  7411  7446 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-01 12:14:21.855  1603  1603 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-01 12:14:21.859  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:14:21.859  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:14:22.223  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510753009] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:22.233  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510752999] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:22.234  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:14:25.255  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510749978] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:25.258  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510749974] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:25.258  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:28.284  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510746948] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:28.296  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510746937] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:28.296  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:14:31.316  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510743916] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:31.319  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510743913] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:31.319  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:34.346  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510740886] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:34.349  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510740883] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:34.350  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:37.373  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510737859] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:37.383  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510737849] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:37.384  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:14:40.407  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510734825] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:40.410  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510734822] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:40.410  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:43.437  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510731795] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:43.440  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510731792] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:43.440  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:46.463  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510728769] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:46.473  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510728759] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:46.474  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:14:49.494  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510725738] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:49.509  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1510725724] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:49.511  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:52.534  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510722698] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:52.545  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510722687] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:52.548  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:14:55.567  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510719665] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:55.570  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510719662] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:55.570  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:14:58.599  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510716634] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:14:58.602  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510716631] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:14:58.602  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:00.092  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:15:00.092  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:15:00.092  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:15:00.093  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:15:00.109  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:15:00.112  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-01 12:15:00.119  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-01 12:15:00.123  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:15:01.423  1036  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=332534726, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-01 12:15:01.491  1036  1093 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7939 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-01 12:15:01.544   385   385 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 6.783ms total 38.525ms
,07-01 12:15:01.581   385   385 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 27.406ms
,07-01 12:15:01.590  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
07-01 12:15:01.611   385   385 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 27.563ms
,07-01 12:15:01.623  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510713609] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:01.624  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1510713608] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:01.624  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:01.661  7939  7939 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-01 12:15:01.665  7939  7939 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1bb37db2
07-01 12:15:01.665  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=332534726 [*alarm*], flags=0x0
07-01 12:15:01.666  1036  1773 I ActivityManager: Killing 6385:com.wsandroid.suite.lge/1000 (adj 15): empty #17
07-01 12:15:01.731  1036  1986 W libprocessgroup: failed to open /acct/uid_1000/pid_6385/cgroup.procs: No such file or directory
,07-01 12:15:04.641  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510710591] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:04.644  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510710588] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:04.644  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:07.672  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510707560] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:07.683  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510707549] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:07.683  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:15:10.706  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510704526] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:10.709  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510704523] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:10.709  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:13.735  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510701497] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:13.738  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510701494] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:13.738  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:16.761  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510698472] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:16.764  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=1.2, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510698468] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:16.764  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:19.789  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510695443] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:19.792  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.6, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510695440] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:19.792  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:22.812  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510692421] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:22.815  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=0.4 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510692418] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:22.821  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:15:25.842  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510689390] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:25.852  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.2, 0.0, 0.0  rx=0.2 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510689380] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:25.853  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:15:28.874  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510686358] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:28.889  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.1, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510686345] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:28.889  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:15:31.908  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510683324] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:31.911  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510683321] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:31.911  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:34.934  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510680298] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:34.945  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510680287] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:34.945  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:15:37.966  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510677266] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:37.969  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510677263] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:37.969  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:40.993  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510674239] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:41.003  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510674229] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:41.004  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:15:44.025  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510671208] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:44.029  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1510671203] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:44.029  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:47.057  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510668175] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:47.058  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1510668174] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:47.058  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:50.078  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510665154] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:50.081  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510665151] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:50.081  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:53.103  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510662129] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:53.113  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510662119] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:53.114  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:15:56.136  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510659096] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:56.139  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510659093] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:56.139  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:15:59.166  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510656068] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:15:59.169  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1510656063] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:15:59.169  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:00.065  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:16:00.065  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:16:00.065  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:16:00.066  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:16:00.080  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:16:00.080  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-01 12:16:00.082  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:16:00.084  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:16:02.197  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510653035] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:02.199  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1510653033] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:02.199  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:05.220  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510650012] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:05.223  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510650009] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:05.224  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:08.244  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510646988] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:08.255  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510646977] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:08.258  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:16:11.279  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510643953] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:11.282  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510643950] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:11.282  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:14.307  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510640926] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:14.310  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510640923] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:14.310  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:17.334  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510637899] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:17.347  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1510637885] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:17.348  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:16:20.367  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510634865] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:20.370  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510634862] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:20.370  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:23.398  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510631834] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:23.401  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510631831] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:23.402  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:26.422  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510628810] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:26.432  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1510628801] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:26.432  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:16:29.451  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510625781] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:29.455  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510625778] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:29.464  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:32.486  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510622746] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:32.489  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510622743] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:32.489  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:35.517  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510619715] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:35.520  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510619712] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:35.520  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:38.544  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510616688] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:38.555  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510616677] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:38.556  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:16:41.576  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510613657] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:41.579  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510613654] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:41.579  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:44.604  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510610628] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:44.615  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510610618] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:44.615  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:16:47.638  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510607594] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:47.641  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510607591] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:47.641  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:50.664  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510604569] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:50.675  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510604557] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:50.678  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:16:53.697  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510601536] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:53.700  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510601533] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:16:53.700  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:16:56.723  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510598510] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:56.733  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510598500] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:56.733  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:16:58.218  1036  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=332534726, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-01 12:16:58.289  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,07-01 12:16:58.317  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=332534726 [*alarm*], flags=0x0
,07-01 12:16:59.754  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510595479] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:59.764  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510595468] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:16:59.765  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:17:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:17:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:17:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:17:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:17:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:17:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:17:00.072  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:17:02.787  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510592445] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:02.790  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510592442] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:02.791  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:05.814  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510589418] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:05.827  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510589406] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:05.827  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:08.848  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510586384] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:08.851  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510586381] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:08.851  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:11.872  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510583360] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:11.883  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510583350] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:11.883  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:14.903  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510580329] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:14.916  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510580316] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:14.916  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:17.939  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510577293] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:17.942  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510577290] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:17.942  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:20.961  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510574272] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:20.964  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510574269] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:20.964  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:23.987  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510571246] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:23.990  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510571242] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:23.990  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:27.018  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510568214] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:27.021  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510568211] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:27.022  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:30.043  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510565189] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:30.054  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510565178] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:30.055  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:33.074  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510562158] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:33.087  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510562145] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:33.087  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:36.107  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510559126] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:36.110  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510559123] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:36.110  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:39.137  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510556096] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:39.140  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510556093] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:39.140  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:42.168  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510553064] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:42.171  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510553061] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:42.171  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:45.194  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510550038] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:45.204  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510550028] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:45.207  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:48.227  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510547006] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:48.230  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510547003] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:48.230  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:17:51.253  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510543979] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:51.264  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510543969] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:51.264  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:54.284  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510540948] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:54.298  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510540935] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:17:54.298  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:17:57.316  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510537916] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:57.319  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510537913] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:17:57.319  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:18:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:18:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:18:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:18:00.069  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:18:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:18:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:18:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:18:00.347  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510534885] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:00.350  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510534882] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:00.350  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:03.379  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510531854] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:03.382  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510531851] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:03.382  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:06.402  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510528830] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:06.413  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510528820] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:06.413  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:18:09.433  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510525799] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:09.446  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510525786] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:09.448  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:18:12.468  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510522764] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:12.471  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510522761] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:12.471  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:15.496  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510519736] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:15.499  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510519733] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:15.499  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:18.528  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510516704] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:18.531  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510516701] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:18.531  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:21.553  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510513679] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:21.564  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510513668] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:21.564  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:18:24.586  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510510648] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:24.589  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1510510643] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:24.589  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:27.617  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510507615] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:27.620  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510507612] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:27.620  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:30.647  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510504585] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:30.650  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510504582] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:30.650  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:33.673  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510501559] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:33.684  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510501548] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:33.684  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:18:36.707  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510498525] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:36.710  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510498522] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:36.710  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:39.737  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510495495] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:39.740  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510495492] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:39.740  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:42.764  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510492469] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:42.774  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510492458] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:42.774  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:18:45.794  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510489438] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:45.807  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510489426] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:45.809  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:18:48.828  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510486404] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:48.831  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510486401] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:48.831  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:51.851  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510483381] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:51.854  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510483378] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:51.855  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:18:54.884  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510480348] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:54.898  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510480336] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:18:54.899  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:18:57.920  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510477312] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:57.923  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510477309] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:18:57.923  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:00.055  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:19:00.056  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:19:00.056  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:19:00.056  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:19:00.070  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:19:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:19:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:19:00.074  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:19:00.950  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510474282] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:00.953  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510474279] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:00.953  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:03.978  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510471254] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:03.981  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510471251] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:03.981  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:07.007  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510468225] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:07.010  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510468222] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:07.010  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:10.037  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510465195] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:10.040  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510465192] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:10.041  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:13.066  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510462166] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:13.069  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510462163] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:13.069  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:16.096  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510459136] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:16.099  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510459133] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:16.099  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:19.124  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510456108] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:19.136  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510456097] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:19.136  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:19:22.157  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510453075] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:22.160  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510453072] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:22.160  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:25.185  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510450047] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:25.186  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1510450046] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:25.186  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:28.204  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510447028] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:28.214  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510447018] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:28.214  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:19:31.236  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510443996] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:31.239  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510443993] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:31.239  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:34.266  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510440967] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:34.269  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510440964] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:34.269  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:37.291  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510437941] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:37.295  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510437938] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:37.301  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:40.323  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510434909] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:40.336  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510434897] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:40.336  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:19:43.361  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510431871] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:43.364  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510431868] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:43.382  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:46.398  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510428834] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:46.402  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510428831] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:46.402  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:49.427  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510425805] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:49.430  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510425802] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:49.430  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:52.454  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510422779] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:52.464  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510422768] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:52.465  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:19:55.486  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510419746] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:55.489  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510419743] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:55.490  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:19:58.519  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510416714] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:19:58.522  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510416711] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:19:58.522  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:00.062  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:20:00.062  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:20:00.063  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:20:00.063  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:20:00.077  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:20:00.077  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:20:00.079  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:20:00.081  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:20:01.542  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510413690] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:01.556  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1510413676] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:01.556  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:20:04.577  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510410655] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:04.581  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510410652] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:04.581  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:07.604  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510407628] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:07.613  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1510407619] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:07.614  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:20:10.633  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510404599] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:10.646  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510404586] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:10.646  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:13.669  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510401564] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:13.672  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510401561] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:13.672  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:16.702  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510398530] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:16.713  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510398520] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:16.713  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:20:19.733  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510395499] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:19.746  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510395487] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:19.746  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:20:22.769  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510392463] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:22.772  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510392460] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:22.772  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:25.800  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510389432] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:25.803  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510389429] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:25.803  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:28.825  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510386408] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:28.828  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510386404] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:28.828  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:31.854  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510383379] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:31.864  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510383368] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:31.865  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:20:34.886  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510380346] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:34.889  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510380343] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:34.889  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:37.917  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510377315] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:37.920  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510377312] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:37.920  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:40.946  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510374286] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:40.949  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510374283] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:40.949  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:43.977  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510371255] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:43.981  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510371252] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:43.981  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:47.006  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510368227] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:47.009  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510368223] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:47.009  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:50.034  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510365198] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:50.045  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510365187] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:50.046  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:20:53.065  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510362167] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:53.069  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510362164] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:53.069  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:20:56.093  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510359139] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:56.105  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510359127] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:20:56.106  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:20:59.125  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510356107] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:59.128  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510356104] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:20:59.129  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:21:00.099  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:21:00.099  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:21:00.100  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:21:00.100  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:21:00.114  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:21:00.114  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:21:00.118  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-01 12:21:00.124  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:21:02.152  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510353081] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:02.167  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510353078] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:02.167  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:05.188  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510350044] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:05.191  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510350041] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:05.191  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:21:08.213  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510347019] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:08.223  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510347009] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:08.224  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:08.949  1036  1986 I ActivityManager: Killing 7248:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,07-01 12:21:09.017  1036  2093 W libprocessgroup: failed to open /acct/uid_10046/pid_7248/cgroup.procs: No such file or directory
,07-01 12:21:11.243  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510343989] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:11.254  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510343978] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:11.256  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:14.278  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510340954] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:14.282  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510340951] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:14.282  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:21:17.307  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510337925] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:17.310  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510337922] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:17.310  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:21:20.333  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510334899] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:20.344  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510334888] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:20.344  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:23.364  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510331869] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:23.376  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510331856] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:23.377  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:26.398  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510328834] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:26.401  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510328831] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:26.402  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:21:29.421  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510325811] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:29.424  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510325808] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:29.424  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:21:32.454  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510322778] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:32.463  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1510322769] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-01 12:21:32.463  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:35.484  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510319748] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:35.497  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510319735] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:35.497  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:38.514  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510316718] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:38.526  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510316706] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:38.526  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:41.546  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510313686] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:41.549  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510313683] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:41.549  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:21:44.573  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510310659] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:44.584  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510310648] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:44.584  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:47.604  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510307628] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:47.616  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510307617] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:47.616  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:50.635  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510304597] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:50.638  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510304594] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:50.639  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:21:53.662  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510301570] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:53.673  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510301560] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-01 12:21:53.673  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:56.693  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510298539] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:21:56.706  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:-1510298526] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
07-01 12:21:56.706  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:21:59.727  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510295505] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:59.730  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510295502] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:21:59.731  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:00.060  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:22:00.060  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:22:00.060  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:22:00.061  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:22:00.073  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:22:00.074  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:22:00.077  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-01 12:22:00.083  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:22:02.757  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510292475] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:02.760  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510292472] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:02.761  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:05.784  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510289449] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:05.795  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510289438] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:05.795  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:22:08.817  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510286415] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:08.820  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510286412] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:08.821  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:11.847  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510283385] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:11.851  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510283382] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:11.851  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:14.875  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510280358] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:14.878  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510280354] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:14.878  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:17.902  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510277331] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:17.910  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510277328] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:17.910  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:22:20.932  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510274301] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:20.943  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510274297] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:20.943  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:22:23.966  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510271267] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:23.969  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510271263] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:23.969  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:26.994  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510268238] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:27.005  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510268228] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:27.005  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:22:30.029  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510265203] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:30.032  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510265200] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:30.032  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:33.056  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510262176] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:33.059  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510262173] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:33.059  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:36.085  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510259148] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:36.088  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510259144] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:36.088  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:39.111  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510256121] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:39.114  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510256118] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:39.120  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:22:42.142  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510253091] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:42.152  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510253081] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:42.153  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:22:45.176  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510250056] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:45.180  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510250053] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:45.180  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:48.207  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510247025] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:48.210  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510247022] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:48.210  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:51.237  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510243995] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:51.240  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510243992] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:51.241  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:22:54.264  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510240968] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:54.274  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510240958] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:22:54.275  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:22:57.296  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510237937] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:57.299  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510237934] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:22:57.299  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:00.077  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:23:00.077  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:23:00.077  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:23:00.078  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:23:00.090  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:23:00.090  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:23:00.093  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:23:00.095  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:23:00.323  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510234910] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:00.334  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510234898] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:00.335  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:23:03.358  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510231874] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:03.361  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510231871] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:03.361  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:06.382  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1510228850] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:06.393  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510228840] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:06.393  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:23:09.414  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510225819] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:09.425  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510225807] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:09.425  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:23:12.446  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510222786] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:12.449  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510222783] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:12.449  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:15.473  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510219759] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,07-01 12:23:15.485  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510219747] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:15.486  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:23:18.506  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510216726] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:18.509  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510216723] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:18.509  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:21.537  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510213695] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:21.540  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510213692] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:21.540  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:24.569  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1510210664] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:24.572  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510210660] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:24.572  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:27.592  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510207640] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:27.603  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510207630] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:27.603  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:23:30.623  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510204609] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:30.635  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510204597] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:30.635  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:23:33.656  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510201577] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:33.659  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510201573] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:33.659  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:36.686  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510198546] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:36.689  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510198543] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:36.689  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:39.716  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1510195517] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:39.717  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1510195515] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:39.717  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:42.740  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3008] from screen [on:0 period:-1510192492] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:42.751  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510192481] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:42.752  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:23:45.769  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510189464] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:45.772  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510189460] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:45.772  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:48.799  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510186433] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:48.802  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510186430] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:48.802  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:51.827  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510183405] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:23:51.831  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510183402] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:51.831  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:54.855  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510180377] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:54.858  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510180374] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:54.858  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:23:57.881  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510177352] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:57.884  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510177348] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:23:57.884  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:00.101  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,07-01 12:24:00.101  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:24:00.101  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:24:00.102  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:24:00.116  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:24:00.116  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:24:00.122  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,07-01 12:24:00.130  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:24:00.911  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510174321] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:00.914  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510174318] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:00.914  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:03.942  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510171291] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:03.951  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510171288] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:03.951  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:24:06.970  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510168262] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:06.973  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510168259] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:06.974  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:09.998  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510165234] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:10.001  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510165231] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:10.002  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:13.027  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510162205] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:13.030  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510162202] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:13.030  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:16.057  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510159175] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:16.060  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510159172] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:16.060  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:19.088  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510156144] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:19.091  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510156141] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:19.091  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:22.117  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510153115] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:22.120  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510153112] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:22.120  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:25.143  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510150089] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:25.154  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510150079] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:25.154  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:24:28.176  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510147056] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:28.179  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510147053] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:28.179  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:31.204  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510144028] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:31.216  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510144017] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:31.216  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:24:34.237  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510140995] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:34.240  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510140992] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:34.240  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:37.267  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510137966] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:37.270  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510137963] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:37.270  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:40.293  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510134939] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:40.304  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510134929] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:40.304  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:24:43.324  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510131908] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:43.334  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510131898] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:43.335  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:24:46.356  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510128876] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:46.359  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510128873] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:46.359  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:49.382  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510125850] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:49.392  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1510125841] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:49.392  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:24:52.412  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510122820] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:52.423  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510122809] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:52.424  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:55.447  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510119785] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:55.450  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510119782] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:24:55.450  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:24:58.477  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510116755] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:58.481  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510116752] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:24:58.481  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:00.064  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:25:00.064  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:25:00.064  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:25:00.065  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:25:00.078  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:25:00.078  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:25:00.080  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:25:00.082  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:25:01.504  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510113728] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:01.516  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510113716] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:01.516  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:25:04.540  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510110693] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:04.543  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510110689] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:04.543  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:07.569  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510107663] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:07.572  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510107660] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:07.572  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:10.597  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510104635] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:10.601  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510104632] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:10.601  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:13.621  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510101611] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:13.624  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510101608] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:13.624  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:16.652  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510098581] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:16.655  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510098578] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:16.661  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:25:19.679  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510095554] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:19.682  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510095551] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:19.682  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:22.709  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510092523] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:22.712  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510092520] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:22.712  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:25.737  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510089495] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:25.741  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510089492] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:25.741  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:28.768  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510086464] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:28.771  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510086461] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:28.771  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:31.796  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510083436] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:31.799  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510083433] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:31.799  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:34.827  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510080405] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:34.830  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510080402] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:34.830  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:37.857  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510077375] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:37.861  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510077372] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:37.861  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:40.886  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510074347] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:40.889  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510074344] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:40.889  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:43.912  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510071320] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:43.922  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510071310] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:43.922  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:25:46.942  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510068291] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:46.952  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1510068287] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:46.953  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:25:49.974  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510065258] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:49.985  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510065247] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:49.985  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:25:53.007  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510062225] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:53.010  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510062222] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:53.011  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:56.038  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510059194] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:56.041  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510059191] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:56.042  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:25:59.063  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1510056170] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:25:59.072  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510056160] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:25:59.072  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:26:00.076  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:26:00.076  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:26:00.076  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:26:00.077  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:26:00.090  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:26:00.091  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:26:00.093  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:26:00.095  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:26:02.093  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510053139] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:02.104  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1510053128] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:02.104  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:26:05.124  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510050108] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:05.136  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510050096] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:05.137  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:26:06.106  1036  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=332534726, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-01 12:26:06.131  1036  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{207db902 type 2 when 1193421 com.android.bluetooth} when 1193421
,07-01 12:26:06.137  7411  7461 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
07-01 12:26:06.137  7411  7461 W bt-smp  : Plain text(LSB ~ MSB) = 57 af 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-01 12:26:06.137  7411  7461 W bt-smp  : Encrypted text(LSB ~ MSB) = cd b9 b6 cd 8a b0 84 8d ce 81 2e 6c be d9 97 a0 
07-01 12:26:06.137  7411  7461 W bt-btm  : Stopping oneshot timer
07-01 12:26:06.191  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,07-01 12:26:06.216  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=332534726 [*alarm*], flags=0x0
,07-01 12:26:08.158  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510047074] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:08.161  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510047071] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:08.161  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:11.181  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1510044051] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:11.182  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1510044050] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:11.182  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:14.200  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510041032] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:14.203  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510041029] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:14.204  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:17.231  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510038001] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:17.234  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510037998] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:17.234  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:20.261  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510034971] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:20.264  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510034968] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:20.272  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:23.294  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510031938] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:23.306  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1510031926] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:23.307  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:26:26.327  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510028905] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:26.330  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510028902] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:26.330  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:29.356  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510025877] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:29.359  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510025874] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:29.359  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:32.386  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510022846] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:32.389  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510022843] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:32.389  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:32.728  1036  1092 I UsageStatsService: User[0] Flushing usage stats to disk
,07-01 12:26:35.414  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510019818] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:35.425  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510019808] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:35.425  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:26:38.448  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510016784] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:38.451  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510016781] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:38.451  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:41.474  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510013758] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:41.485  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510013748] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:41.485  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:26:44.508  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510010725] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:44.511  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510010722] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:44.511  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:47.538  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1510007694] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:47.542  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510007691] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:47.542  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:50.566  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1510004666] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:50.569  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1510004663] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:50.569  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:53.594  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1510001638] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:53.605  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1510001628] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:53.605  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:26:56.627  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509998605] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:56.630  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509998602] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:56.630  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:26:59.658  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1509995574] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:26:59.661  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509995571] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:26:59.661  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:27:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:27:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:27:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:27:00.066  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:27:00.066  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:27:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:27:00.070  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:27:02.686  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509992548] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:02.689  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1509992543] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:02.689  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:05.717  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509989515] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:05.721  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509989512] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:05.721  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:08.748  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509986484] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:08.752  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509986481] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:08.752  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:11.777  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509983455] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:11.780  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509983452] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:11.780  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:14.803  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1509980430] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:14.812  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509980420] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:14.813  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:27:17.833  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509977399] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:17.844  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509977388] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:17.844  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:27:20.867  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509974366] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:20.869  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509974363] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:20.869  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:23.889  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509971344] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:23.892  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509971340] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:23.892  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:26.917  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1509968315] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:26.920  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509968312] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:26.920  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:29.944  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509965288] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:29.954  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509965278] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:29.954  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:27:32.976  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509962257] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:32.979  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509962254] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:32.979  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:36.003  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509959230] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:36.014  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509959219] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:36.014  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:27:39.035  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509956197] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:39.038  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509956194] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:39.039  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:42.069  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509953163] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:42.072  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509953160] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:42.072  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:45.094  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1509950138] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:45.104  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509950128] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:45.104  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:27:48.126  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509947106] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:48.129  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509947103] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:48.129  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:51.152  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509944081] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:51.161  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509944077] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:51.161  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:27:54.180  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509941052] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:54.184  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509941049] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:54.184  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:27:57.212  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509938021] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:27:57.221  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509938011] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:27:57.221  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:28:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:28:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:28:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:28:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:28:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:28:00.072  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:28:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:28:00.241  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509934991] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:00.244  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509934988] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:00.244  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:03.272  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1509931960] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:03.284  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509931949] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:03.284  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:06.303  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1509928929] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:06.314  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509928918] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:06.315  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:09.336  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509925896] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:09.339  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509925893] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:09.339  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:12.366  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509922867] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:12.369  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509922863] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:12.369  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:15.393  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509919839] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:15.403  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1509919830] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:15.403  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:18.424  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509916808] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:18.436  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509916797] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:18.436  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:21.457  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509913775] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:21.461  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509913772] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:21.461  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:24.487  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509910745] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:24.491  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509910742] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:24.491  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:27.517  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509907715] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:27.521  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509907712] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:27.521  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:30.548  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509904684] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:30.551  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509904681] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:30.552  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:33.574  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509901658] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:33.585  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509901647] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:33.585  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:36.609  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509898623] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:36.612  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509898620] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:36.612  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:39.634  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509895598] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:39.645  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509895587] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:39.646  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:42.665  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509892568] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:42.677  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1509892556] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:42.677  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:45.698  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509889535] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:45.701  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509889531] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:45.701  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:48.729  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509886503] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:48.741  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509886492] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:48.741  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:28:51.758  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509883474] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:51.762  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509883471] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:51.762  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:54.790  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509880442] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:54.793  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509880439] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:54.793  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:28:57.816  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509877416] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:28:57.819  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509877413] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:28:57.819  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:29:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:29:00.055  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,07-01 12:29:00.061  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
07-01 12:29:00.069  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:29:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:29:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:29:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:29:00.844  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509874388] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:00.857  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1509874376] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:00.857  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:29:03.877  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509871355] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:03.880  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509871352] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:03.880  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:06.909  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509868323] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:06.912  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509868320] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:06.912  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:09.936  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509865298] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:09.939  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:5] from screen [on:0 period:-1509865293] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:09.939  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:12.969  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509862263] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:12.972  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509862260] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:12.973  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:15.996  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509859237] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:15.999  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509859234] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:15.999  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:19.023  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509856210] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:19.033  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509856199] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:19.033  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:29:22.054  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509853178] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:22.066  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1509853166] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:22.066  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:29:25.088  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509850144] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:25.092  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509850141] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:25.092  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:28.118  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509847114] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:28.122  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509847111] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:28.122  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:31.146  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509844086] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:31.149  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509844083] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:31.149  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:34.176  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509841056] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:34.180  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509841053] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:34.180  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:37.206  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509838026] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:37.209  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509838023] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:37.209  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:40.234  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509834998] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:40.244  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1509834989] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:40.244  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:29:43.265  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509831967] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:43.268  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509831964] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:43.268  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:46.292  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509828940] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:46.302  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1509828931] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:46.302  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:29:49.322  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509825910] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:49.334  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509825899] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:49.334  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:29:52.355  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509822878] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:52.358  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509822874] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:52.358  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:29:55.381  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1509819851] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:55.384  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509819848] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:55.391  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:29:58.413  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509816819] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:29:58.424  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509816808] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:29:58.425  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:30:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:30:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:30:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:30:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:30:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:30:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:30:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:30:00.072  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:30:01.446  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509813786] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:01.449  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509813783] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:01.450  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:01.666  1036  1381 D PowerManagerServiceEx: acquireWakeLockInternal: lock=332534726, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,07-01 12:30:01.694  7939  7939 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,07-01 12:30:01.709  7939  7939 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1bb37db2
,07-01 12:30:01.758  2628  2628 D [Concierge]Service: onStartCommand(). Type : 9
,07-01 12:30:01.781  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=332534726 [*alarm*], flags=0x0
,07-01 12:30:04.476  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509810757] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:04.479  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509810754] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:04.479  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:07.506  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509807726] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:07.509  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509807723] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:07.509  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:10.537  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509804695] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:10.541  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509804692] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:10.541  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:13.567  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509801665] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:13.570  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509801662] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:13.570  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:16.598  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509798634] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:16.601  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509798631] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:16.601  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:19.627  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509795605] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:19.630  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509795602] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:19.631  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:22.658  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509792574] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:22.661  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509792571] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:22.662  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:25.680  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509789552] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:25.683  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509789549] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:25.684  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:28.711  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509786522] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:28.714  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509786518] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:28.714  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:31.738  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509783495] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:31.741  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509783492] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:31.741  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:34.766  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509780466] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:34.769  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509780463] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:34.769  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:37.797  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509777435] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:37.800  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509777432] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:37.800  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:40.828  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509774405] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:40.831  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509774402] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:40.831  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:43.856  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509771376] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:43.859  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509771373] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:43.859  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:46.887  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509768346] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:46.890  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509768343] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:46.890  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:49.919  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509765313] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:49.923  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509765310] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:49.923  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:52.948  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1509762284] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:52.951  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509762281] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:52.951  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:30:55.973  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1509759259] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:55.982  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:9] from screen [on:0 period:-1509759250] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:55.983  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:30:59.003  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509756229] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:30:59.014  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509756218] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:30:59.014  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:31:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:31:00.054  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:31:00.054  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:31:00.055  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:31:00.068  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:31:00.068  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:31:00.070  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:31:00.072  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:31:02.033  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1509753199] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:02.034  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1509753198] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:02.034  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:05.053  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509750179] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:05.064  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509750169] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:05.064  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:31:08.087  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509747145] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:08.090  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509747142] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:08.090  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:11.119  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509744113] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:11.122  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509744110] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:11.122  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:14.148  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509741084] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:14.151  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509741081] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:14.151  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:17.174  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509738058] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:17.185  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509738047] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:17.186  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:31:20.206  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509735026] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:20.209  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509735023] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:20.209  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:23.236  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509731996] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:23.239  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509731993] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:23.239  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:26.264  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509728969] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:26.273  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509728959] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:26.274  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:31:29.294  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509725938] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:29.306  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509725927] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:29.306  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:31:32.329  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509722904] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:32.332  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509722900] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:32.332  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:35.360  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509719873] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:35.363  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509719870] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:35.363  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:38.390  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509716843] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:38.393  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509716840] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:38.393  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:41.417  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509713815] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:41.420  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509713812] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:41.420  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:44.447  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509710785] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:44.450  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509710782] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:44.450  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:47.478  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509707754] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:47.490  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1509707742] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:47.490  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:31:50.508  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1509704724] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:50.511  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509704721] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:50.511  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:31:53.533  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509701699] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:53.544  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509701689] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:53.544  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:31:56.564  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1509698668] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:56.575  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509698658] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:56.575  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:31:59.594  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509695638] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:31:59.605  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509695627] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:31:59.606  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:32:00.052  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:32:00.052  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:32:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:32:00.053  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:32:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,07-01 12:32:00.065  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:32:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:32:00.069  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:32:02.629  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509692604] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:02.632  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509692600] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:02.632  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:05.657  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509689576] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:05.660  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509689572] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:05.660  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:08.689  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509686543] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:08.692  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509686540] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:08.692  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:11.718  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509683514] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:11.721  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509683511] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:11.721  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:14.747  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509680485] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:14.750  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509680482] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:14.751  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:17.778  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509677454] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:17.782  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509677451] gl rssi=-40 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:17.782  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:20.807  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509674425] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:20.810  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509674422] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:20.811  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:23.837  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509671395] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:23.840  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509671392] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:23.841  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:26.868  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509668364] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:26.871  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509668361] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:26.871  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:29.899  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509665333] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:29.902  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509665330] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:29.902  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:32.928  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509662304] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:32.931  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509662301] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:32.931  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:35.958  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509659274] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:35.961  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509659271] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:35.962  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:38.985  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509656247] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:38.988  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509656244] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:38.988  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:42.016  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509653217] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:42.019  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509653214] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:42.019  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:45.044  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509650188] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:32:45.055  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509650177] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:45.055  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:32:48.079  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509647154] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:48.082  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509647151] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:48.082  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:51.109  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509644123] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:51.112  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509644120] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:51.113  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:54.140  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509641092] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:54.143  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509641089] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:54.143  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:32:57.166  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509638066] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:57.169  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509638063] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:32:57.169  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:00.051  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:33:00.051  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:33:00.052  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:33:00.052  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:33:00.065  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:33:00.065  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:33:00.067  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:33:00.069  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:33:00.198  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509635035] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:00.201  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509635032] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:00.201  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:03.228  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509632004] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:03.231  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509632001] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:03.232  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:06.255  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509628978] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:06.266  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1509628966] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:06.266  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:09.287  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509625946] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:09.290  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509625942] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:09.290  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:12.313  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509622919] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:12.323  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509622909] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:12.323  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:15.344  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509619888] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:15.357  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1509619876] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:15.357  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:18.378  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509616855] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:18.381  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509616851] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:18.381  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:21.407  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509613826] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:21.410  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509613822] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:21.410  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:24.438  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1509610794] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:24.441  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509610791] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:24.441  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:27.462  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509607771] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:27.465  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509607768] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:27.471  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:30.491  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509604741] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:30.494  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509604738] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:30.495  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:33.522  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509601711] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:33.531  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509601707] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:33.532  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:36.551  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509598681] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:36.554  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509598678] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:36.554  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:39.581  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509595651] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:39.584  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509595648] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:39.584  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:42.613  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509592620] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:42.622  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509592610] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:42.623  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:45.644  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509589588] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:45.655  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509589577] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:45.656  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:48.680  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1509586552] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:48.683  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509586549] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:48.684  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:51.703  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509583529] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:51.714  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509583518] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:51.714  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:33:54.736  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509580496] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:54.739  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509580493] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:54.739  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:33:57.762  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509577470] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:33:57.772  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509577460] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:33:57.772  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:34:00.053  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-01 12:34:00.053  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
07-01 12:34:00.053  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
07-01 12:34:00.054  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,07-01 12:34:00.069  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
07-01 12:34:00.069  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:34:00.071  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
07-01 12:34:00.073  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:34:00.792  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509574440] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:34:00.803  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509574429] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:00.804  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:34:03.824  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509571409] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:34:03.835  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:12] from screen [on:0 period:-1509571397] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:03.836  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:34:06.859  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509568374] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:06.862  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1509568370] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:06.862  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:34:09.888  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509565344] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:09.891  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1509565341] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:09.891  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,07-01 12:34:12.914  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509562318] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,07-01 12:34:12.924  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1509562308] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:12.924  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:34:15.953  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1509559280] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,TIME-OUT KILL (timeout was 1400000ms),07-01 12:34:15.963  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509559269] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:15.964  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:34:18.984  1036  1539 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:-1509556248] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:18.995  1036  1539 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 6 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1509556237] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
07-01 12:34:18.995  1036  1539 D WifiNative-wlan0: doString: [SIGNAL_POLL]
07-01 12:34:19.987  8008  8008 D AndroidRuntime: 
07-01 12:34:19.987  8008  8008 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 12:34:19.993  8008  8008 D AndroidRuntime: CheckJNI is OFF
07-01 12:34:20.124  8008  8008 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-01 12:34:20.137  1036  1093 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
07-01 12:34:20.138  1036  1093 I ActivityManager: Killing 6891:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
07-01 12:34:20.215  1036  1544 D WifiService: Client connection lost with reason: 4
07-01 12:34:20.215  1036  1052 I WindowState: WIN DEATH: Window{209b0fe4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-01 12:34:20.222  1036  1052 D InputDispatcher: Window went away: Window{209b0fe4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-01 12:34:20.364  1036  1093 I ActivityManager:   Force finishing activity ActivityRecord{3fe71969 u0 com.test.thalitest/.MainActivity t12}
07-01 12:34:20.412   349   369 E GBMv2   : DFP En is all cleared set to be enabled
07-01 12:34:20.416  1036  1118 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
07-01 12:34:20.418  1036  1118 I ActivityManager:   Force finishing activity ActivityRecord{3fe71969 u0 com.test.thalitest/.MainActivity t12 f}
07-01 12:34:20.418  1036  1118 W ActivityManager: Duplicate finish request for ActivityRecord{3fe71969 u0 com.test.thalitest/.MainActivity t12 f}
07-01 12:34:20.448  1036  1773 W ActivityManager: Spurious death for ProcessRecord{3d729213 6891:com.test.thalitest/u0a118}, curProc for 6891: null
07-01 12:34:20.449  2090  2090 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
07-01 12:34:20.449  1968  1983 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
07-01 12:34:20.449  2090  2090 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
07-01 12:34:20.450  1968  1983 D SplitWindowPolicy: topRunningActivity=ActivityInfo{a322de8 co.....Launcher}, taskId=11, activityType=1, bIsSplit=false
07-01 12:34:20.457  1968  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
07-01 12:34:20.457  1968  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{aca6c01 co.....Launcher}, taskId=11, activityType=1, bIsSplit=false
07-01 12:34:20.465  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
07-01 12:34:20.466  2090  2181 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
07-01 12:34:20.471  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
07-01 12:34:20.475  1036  1383 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-01 12:34:20.487  3819  3819 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
07-01 12:34:20.487  2033  2033 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
07-01 12:34:20.491  2498  2612 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-01 12:34:20.494  7411  7411 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
07-01 12:34:20.494  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
07-01 12:34:20.530  4486  4486 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-01 12:34:20.531  4486  4486 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
07-01 12:34:20.531  4486  4486 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
07-01 12:34:20.531  4486  4486 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
07-01 12:34:20.531  4486  4486 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:34:20.531  4486  4486 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:34:20.531  4486  4486 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:34:20.531  4486  4486 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-01 12:34:20.531  4486  4486 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:34:20.531  4486  4486 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:34:20.531  4486  4486 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-01 12:34:20.531  4486  4486 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-01 12:34:20.569  4597  4597 I art     : Explicit concurrent mark sweep GC freed 8130(469KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 657us total 57.260ms
07-01 12:34:20.571  1036  2031 V SIM_STK : Menu title from STK is T-Mobile
07-01 12:34:20.586  1036  1093 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8046 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
07-01 12:34:20.588  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
07-01 12:34:20.591  1932  1932 D ActionManagerService: notifyUserLog: 1000003
07-01 12:34:20.592  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
07-01 12:34:20.592  2090  2090 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
07-01 12:34:20.592  3819  4480 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
07-01 12:34:20.593  2090  2090 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
07-01 12:34:20.594  2090  2090 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
07-01 12:34:20.601  1932  1932 D ActionManagerService: notifyUserLog: 1000004
07-01 12:34:20.602  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
07-01 12:34:20.602  1898  1898 D SplitUIManager: split_name #11 / not available #0
07-01 12:34:20.603  1898  1898 D SplitUIService: removed split : 
07-01 12:34:20.603  3819  4480 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
07-01 12:34:20.603  3819  3835 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-01 12:34:20.603  1603  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-01 12:34:20.603  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.606  1603  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-01 12:34:20.606  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , create_time: 1430832262123
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , expire_time: 0
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , display: false
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , animation: false }
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , create_time: 1430832262287
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , expire_time: 0
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , display: false
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , animation: false }
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1467198142274
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , create_time: 1467198143124
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , expire_time: 0
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1467198142274&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , display: false
07-01 12:34:20.608  2090  2090 I GBoardWebViewUtils: , animation: false }
07-01 12:34:20.612  1603  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-01 12:34:20.613  1603  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:34:20.613  1603  1653 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
07-01 12:34:20.614  1603  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-01 12:34:20.622  2090  8058 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
07-01 12:34:20.626  1603  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-01 12:34:20.626  1603  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-01 12:34:20.634  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-01 12:34:20.634  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
07-01 12:34:20.635  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
07-01 12:34:20.635  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
07-01 12:34:20.649  1603  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-01 12:34:20.649  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.657  1898  1898 D SplitUIManager: split_name #11 / not available #0
07-01 12:34:20.657  1898  1898 I SplitUIService: split app #11
07-01 12:34:20.663  1603  1653 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
07-01 12:34:20.663  1603  1653 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:34:20.669  1603  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-01 12:34:20.669  1603  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-01 12:34:20.671  1603  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-01 12:34:20.671  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.679  1603  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:34:20.679  1603  1653 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 12:34:20.680  1603  1653 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
07-01 12:34:20.680  1603  1653 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
07-01 12:34:20.680  1603  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-01 12:34:20.680  1603  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-01 12:34:20.681  1603  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-01 12:34:20.681  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.691  1603  1603 D KeyguardModel: handleShortcutListChanged...
07-01 12:34:20.691  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-01 12:34:20.694  1036  1949 V SIM_STK : Menu title from STK is T-Mobile
07-01 12:34:20.694  1036  1949 V SIM_STK : Menu title from STK is T-Mobile
07-01 12:34:20.697  1603  1653 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
07-01 12:34:20.697  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.717  1603  1653 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
07-01 12:34:20.717  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.718  1603  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-01 12:34:20.718  1603  1653 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
07-01 12:34:20.719  1603  1653 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
07-01 12:34:20.719  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.721  1603  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-01 12:34:20.721  1603  1653 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
07-01 12:34:20.722  1603  1653 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
07-01 12:34:20.722  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.723  1603  1653 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-01 12:34:20.723  1603  1653 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
07-01 12:34:20.725  1603  1653 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
07-01 12:34:20.725  1603  1653 D KeyguardModel: createShortcutInfo...
07-01 12:34:20.737  1603  1603 D KeyguardModel: handleShortcutListChanged...
07-01 12:34:20.737  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
07-01 12:34:20.742  1036  1036 I art     : Explicit concurrent mark sweep GC freed 388375(18MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 44MB/67MB, paused 1.911ms total 290.583ms
07-01 12:34:20.751   331   409 I ThermalEngine: Thermal-Server: Thermal received msg from  override
07-01 12:34:20.753  3195  8069 I Thermal-Lib: Thermal-Lib-Client: Client request sent
07-01 12:34:20.758  1036  1118 I art     : WaitForGcToComplete blocked for 286.616ms for cause Explicit
07-01 12:34:20.765  1036  1949 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
07-01 12:34:20.766  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
07-01 12:34:20.766  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
07-01 12:34:20.766  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
07-01 12:34:20.766  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
07-01 12:34:20.766  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
07-01 12:34:20.766  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 12:34:20.767  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
07-01 12:34:20.767  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
07-01 12:34:20.767  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
07-01 12:34:20.767  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
07-01 12:34:20.767  7411  7411 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
07-01 12:34:20.767  8046  8046 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-01 12:34:20.776  1036  1036 D administrator: Handling package changes for user 0
07-01 12:34:20.776  1036  2332 V SIM_STK : Menu title from STK is T-Mobile
07-01 12:34:20.779  8046  8046 D PluginManager: init()
07-01 12:34:20.816  2090  2090 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
07-01 12:34:20.818  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:34:20.820  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
07-01 12:34:20.821  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
07-01 12:34:20.822  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
07-01 12:34:20.823  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
07-01 12:34:20.837  2090  2090 D BubblePopupHelper: isShowingBubblePopup : false
07-01 12:34:20.839  2090  2090 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
07-01 12:34:20.840  1036  1098 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c29fa1d u0 com.lge.launcher2/.Launcher t11} time:1688174
07-01 12:34:20.842  2090  2090 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
07-01 12:34:20.842  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:34:20.861  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
07-01 12:34:20.862  2090  2090 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-01 12:34:20.862  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:34:20.862  2090  2839 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
07-01 12:34:20.863  2090  2839 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
07-01 12:34:20.869  2090  2090 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
07-01 12:34:20.870  2628  2628 D [Concierge]Service: onStartCommand(). Type : 8
07-01 12:34:20.870  2628  2628 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
07-01 12:34:20.871  2628  2628 D [Concierge]Service: Update widget ID : 11
07-01 12:34:20.872  2090  2090 D [Concierge]WidgetView: change position of spinner
07-01 12:34:20.874  2090  2090 I [Concierge]WidgetView: initWebView(). Time : 1467369260874
07-01 12:34:20.874  2628  2628 D [Concierge]Service: onStartCommand(). Type : 0
07-01 12:34:20.900  2090  2090 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 218350100
07-01 12:34:20.900  2090  2090 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
07-01 12:34:20.900  2090  2090 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-01 12:34:20.903  2090  2090 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3da5ea1a
07-01 12:34:20.903  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
07-01 12:34:20.904  2090  2090 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
07-01 12:34:20.904  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:34:20.909  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
07-01 12:34:20.909  2090  2090 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-01 12:34:20.921  2090  2090 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1467367729486, New one : 1467369260874
07-01 12:34:20.921  2090  2090 D [Concierge]WidgetView: Unregister all receivers
07-01 12:34:20.921  2090  2090 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
07-01 12:34:20.921  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:34:20.923  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
07-01 12:34:20.924  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
07-01 12:34:20.925  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
07-01 12:34:20.926  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
07-01 12:34:20.927  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
07-01 12:34:20.928  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:34:20.928  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:34:20.934  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
07-01 12:34:20.934  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-01 12:34:20.934  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-01 12:34:20.942  1036  1578 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
07-01 12:34:20.953  2090  2090 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
07-01 12:34:20.958  1036  1118 I art     : Explicit concurrent mark sweep GC freed 19809(1080KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 13.549ms total 189.319ms
07-01 12:34:20.960  2090  2090 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-01 12:34:20.961  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
07-01 12:34:20.961  2090  2090 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
07-01 12:34:20.963  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
07-01 12:34:20.977  2090  2090 I [LGHome]LGMenuPagedAppsView: [LGMenuPagedAppsView.java:3717:removeApps()]removeApps list size= 1
07-01 12:34:20.979  2090  2090 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@56445e9 time:1688314
07-01 12:34:21.020  8008  8008 D AndroidRuntime: Shutting down VM
07-01 12:34:21.037  1036  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:34:21.041  1036  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
07-01 12:34:21.042  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-01 12:34:21.089  8046  8046 W ExternalStrings: load override strings
07-01 12:34:21.089  8046  8046 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-01 12:34:21.089  8046  8046 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-01 12:34:21.090  8046  8046 D StatusProvider: onCreate
07-01 12:34:21.122  8046  8046 V Signer  : override build config not found
07-01 12:34:21.122  8046  8046 D Signer  : value of property debug is false
07-01 12:34:21.137  2090  2090 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
07-01 12:34:21.142  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
07-01 12:34:21.142  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
07-01 12:34:21.142  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
07-01 12:34:21.142  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
07-01 12:34:21.142  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
07-01 12:34:21.142  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
07-01 12:34:21.143  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
07-01 12:34:21.143  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
07-01 12:34:21.143  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
07-01 12:34:21.143  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
07-01 12:34:21.143  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
07-01 12:34:21.143  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
07-01 12:34:21.143  8046  8046 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
07-01 12:34:21.150  8046  8046 V LGMDMManager: Create singleton instance
07-01 12:34:21.172  2090  2924 I GBoardtInterface: onReloaded()
07-01 12:34:21.174  2090  2090 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
07-01 12:34:21.175  3819  3835 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-01 12:34:21.178  3819  3834 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-01 12:34:21.182  1932  1932 D ActionManagerService: notifyUserLog: 1000001
07-01 12:34:21.183  3819  4480 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-01 12:34:21.183  3819  4480 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-01 12:34:21.186  1932  1932 D ActionManagerService: notifyUserLog: 1000001
07-01 12:34:21.187  3819  4480 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
07-01 12:34:21.187  3819  4480 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
07-01 12:34:21.187  3819  4480 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
07-01 12:34:21.187  3819  4480 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
07-01 12:34:21.188  3819  3835 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
07-01 12:34:21.189  8046  8046 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
07-01 12:34:21.190  2090  2090 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
07-01 12:34:21.190  2090  2090 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
07-01 12:34:21.191  2090  2090 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
07-01 12:34:21.191  2090  2090 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
07-01 12:34:21.193  2090  2090 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1467198142274&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
07-01 12:34:21.193  2090  2090 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1467198142274&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
07-01 12:34:21.219  8046  8046 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
07-01 12:34:21.220  1842  1842 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-01 12:34:21.223  8046  8074 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
07-01 12:34:21.230  2225  2225 I ConfigService: onCreate
07-01 12:34:21.231  2225  2225 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-01 12:34:21.236  2225  2225 I ConfigService: onBind returning update interface
07-01 12:34:21.261  1036  1118 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8078 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-01 12:34:21.263  2225  2225 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-01 12:34:21.263  2225  2225 I ConfigService: onBind returning config service
07-01 12:34:21.263  1842  1842 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-01 12:34:21.303  1036  1986 I ActivityManager: Killing 7271:com.android.chrome/u0a57 (adj 15): empty #17
07-01 12:34:21.307  1842  1842 I ConfigFetchService: service connected
07-01 12:34:21.307  1842  1842 I ConfigClient: service connected
07-01 12:34:21.331  8046  8073 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.g.b.a(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.364  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.a.a(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.d.d(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.d.<init>(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.d.a(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.modes.adapt.a.a(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.h.<init>(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.f.<init>(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.f.a(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.380  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: Couldn't open lockedapplications for writing (will try read-only):
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.a.a(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.d.d(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.d.<init>(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.d.a(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.modes.adapt.a.a(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.h.<init>(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.f.<init>(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.f.a(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.381  8046  8073 E SQLiteOpenHelper: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.382  8046  8073 W SQLiteOpenHelper: Opened lockedapplications in read-only mode
07-01 12:34:21.386  1036  1949 W libprocessgroup: failed to open /acct/uid_10057/pid_7271/cgroup.procs: No such file or directory
07-01 12:34:21.390  2225  2225 I ConfigService: onDestroy
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.notificationtray.e.a(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.395  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.395  1842  8103 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-01 12:34:21.403  7684  7684 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.wavesecure.utils.y.v(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.403  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: Error inserting package=com.test.thalitest
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
07-01 12:34:21.403  7684  7684 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.wavesecure.utils.y.v(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.405  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.412  2184  2338 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQ,LiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.413  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.414  2184  8107 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: performBackgroundTask SQLiteDiskIOException during query
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:34:21.414  2184  2338 D ContactsProvider2ForLG: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.wavesecure.c2dm.a.d(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.wavesecure.c2dm.a.c(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.wavesecure.notification.g.a(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.418  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.423  2184  8107 E SQLiteLog: (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
07-01 12:34:21.424  2184  8107 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-01 12:34:21.424  2184  8107 E AndroidRuntime: Process: android.process.acore, PID: 2184
07-01 12:34:21.424  2184  8107 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:34:21.424  2184  8107 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:34:21.439  8046  8073 D LgDataFeature: LgDataFeature() Constructor: none
07-01 12:34:21.439  8046  8073 D LgDataFeature: LgDataFeature() Constructor Done, null
07-01 12:34:21.442  1036  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8110 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: Can't write: system_app_crash
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:34:21.451  1036  8120 E DropBoxManagerService: 	... 5 more
07-01 12:34:21.454  2184  8107 I Process : Sending signal. PID: 2184 SIG: 9
07-01 12:34:21.464  5928  8131 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.J(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.wavesecure.c2dm.a.d(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.wavesecure.c2dm.a.c(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.wavesecure.notification.g.a(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.465  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.r(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.wavesecure.notification.c.a(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.467  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.wavesecure.notification.r.a(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.471  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.wavesecure.notification.o.d(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.notificationtray.a.b.b(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.notificationtray.a.b.a(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.notificationtray.a.c.run(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.472  8046  8108 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.wavesecure.notification.q.a(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.474  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.479  2090  2924 I GBoardtInterface: exportHTML()
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.aq(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.c(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.485  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.486  4486  4527 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: Error inserting f004=13 f005=8110 f002=1467369261453 f003=com.lge.email f006=10023
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-01 12:34:21.487  4486  4527 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.c(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.487  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.b.a(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.m(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.a(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.a.b(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.e(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.c(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.wavesecure.core.WSComponent.a(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.c.b.b(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.framework.b.a(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.app.t.run(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.f.run(Unknown Source)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:34:21.488  8046  8073 E SQLiteDatabase: 	at com.mcafee.d.c.run(Unknown Source)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:34:21.490  8046  8073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableD
```
