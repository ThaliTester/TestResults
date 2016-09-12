#### Test 84265062d118465_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
09-12 18:15:00.107  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-12 18:15:00.107  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
09-12 18:15:00.108  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
09-12 18:15:00.108  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,09-12 18:15:00.121  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
09-12 18:15:00.121  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
09-12 18:15:00.124  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
09-12 18:15:00.125  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
09-12 18:15:00.413  6798  6798 D AndroidRuntime: 
09-12 18:15:00.413  6798  6798 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 18:15:00.416  6798  6798 D AndroidRuntime: CheckJNI is OFF
09-12 18:15:00.543  6798  6798 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 18:15:00.549  1033  1970 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 18:15:00.560  1967  1983 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
09-12 18:15:00.563  1033  1970 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
09-12 18:15:00.564  1033  1970 D ActivityManager: setTaskToReturnTo : TaskRecord{6ea1b2c #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-12 18:15:00.564  1033  1970 D ActivityManager: setTaskToReturnTo : TaskRecord{6ea1b2c #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-12 18:15:00.565  1033  1970 D WindowStateEx: AppWindowTokenEx init.. 
09-12 18:15:00.566   346   367 E GBMv2   : DFP En is all cleared set to be enabled
09-12 18:15:00.597  1033  1970 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6817 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 18:15:00.600  6798  6798 D AndroidRuntime: Shutting down VM
09-12 18:15:00.670  1967  1983 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
09-12 18:15:00.671  1967  1983 D SplitWindowPolicy: topRunningActivity=ActivityInfo{26cf67da co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-12 18:15:00.674  1967  2541 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
09-12 18:15:00.675  1967  2541 D SplitWindowPolicy: topRunningActivity=ActivityInfo{248fd40b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
09-12 18:15:00.720  6817  6817 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
09-12 18:15:00.788  6817  6817 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-12 18:15:00.795  6817  6817 I LibraryLoader: Loading: webviewchromium
09-12 18:15:00.798  6817  6817 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9344-9348)
09-12 18:15:00.798  6817  6817 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:15:00.822  6817  6817 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1dc9fc98}
,09-12 18:15:00.823  6817  6817 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:15:00.824  6817  6817 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 18:15:00.837  6817  6817 I BrowserStartupController: Initializing chromium process, renderers=0
,09-12 18:15:00.838  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 18:15:00.857   322   322 V AudioPolicyService: registerClient() client 0xb558a760, uid 10118
,09-12 18:15:00.858  6817  6817 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-12 18:15:00.859  6817  6817 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
09-12 18:15:00.860  6817  6817 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
09-12 18:15:00.865  1033  1095 D BluetoothManagerService: Message: 20
09-12 18:15:00.865  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28df7e56:true
09-12 18:15:00.894  6817  6817 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 18:15:00.894  6817  6817 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 18:15:00.894  6817  6817 I Adreno-EGL: Build Date: 12/12/14 금
09-12 18:15:00.894  6817  6817 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 18:15:00.894  6817  6817 I Adreno-EGL: Remote Branch: 
09-12 18:15:00.894  6817  6817 I Adreno-EGL: Local Patches: 
09-12 18:15:00.894  6817  6817 I Adreno-EGL: Reconstruct Branch: 
,09-12 18:15:00.979  6817  6854 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,09-12 18:15:00.984  6817  6817 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,09-12 18:15:01.016  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:15:01.022  6817  6817 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-12 18:15:01.026  6817  6817 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,09-12 18:15:01.030  6817  6817 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-12 18:15:01.030  6817  6817 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-12 18:15:01.047  6817  6817 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-12 18:15:01.055  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 18:15:01.055  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:15:01.091  6817  6866 D OpenGLRenderer: Render dirty regions requested: true
09-12 18:15:01.091  6817  6866 I OpenGLRenderer: Initialized EGL, version 1.4
09-12 18:15:01.096  6817  6866 D OpenGLRenderer: Enabling debug mode 0
09-12 18:15:01.105  6817  6817 D Atlas   : Validating map...
,09-12 18:15:01.110  1033  1970 D SplitWindow: check instance of lgWin Window{38c20d60 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 18:15:01.158  6817  6864 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 18:15:01.158  6817  6864 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 18:15:01.247  1033  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +578ms (total +680ms)
09-12 18:15:01.248  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35fd29f5 u0 com.test.thalitest/.MainActivity t6} time:189798
09-12 18:15:01.248  6817  6817 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d4ccc47 time:189799
09-12 18:15:01.388  6817  6817 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 18:15:01.533  6817  6879 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,09-12 18:15:01.549  6817  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 18:15:01.549  6817  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 18:15:01.549  6817  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 18:15:01.549  6817  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 18:15:01.549  6817  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 18:15:01.549  6817  6879 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25d22e5b added. We now have 1 listener(s)
09-12 18:15:01.555  1033  2089 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:01.558  6817  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
09-12 18:15:01.560  6817  6879 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,09-12 18:15:01.564  6817  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:01.565  6817  6879 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:01.570  1033  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=485939779, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 18:15:01.580  6817  6879 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2118c236 added. We now have 1 listener(s)
,09-12 18:15:01.581  6817  6879 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:01.589  1033  1541 D WifiService: New client listening to asynchronous messages
09-12 18:15:01.593  6817  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:15:01.594  6817  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 18:15:01.596  6817  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 18:15:01.596  6817  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 18:15:01.596  6817  6879 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-12 18:15:01.618  1033  1091 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6882 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-12 18:15:01.625  6817  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:01.625  1033  2112 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:01.626  6817  6879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
09-12 18:15:01.635  6817  6879 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-12 18:15:01.637  6817  6879 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:01.637  6817  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:01.637  6817  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:01.637  6817  6879 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:01.637  6817  6879 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:01.637  6817  6879 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:01.637  6817  6879 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:01.637  6817  6879 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:01.637  6817  6879 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 18:15:01.638  6817  6879 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:15:01.643  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:01.645  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:01.645  6817  6879 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 18:15:01.660  2619  2619 D [Concierge]Service: onStartCommand(). Type : 9
,09-12 18:15:01.717  6817  6864 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
09-12 18:15:01.717  6817  6864 I chromium: 
,09-12 18:15:01.749  6882  6882 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,09-12 18:15:01.753  6882  6882 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1aa7fe75
09-12 18:15:01.754  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=485939779 [*alarm*], flags=0x0
09-12 18:15:01.755  1033  1597 I ActivityManager: Killing 6078:com.android.providers.calendar/u0a14 (adj 15): empty #17
09-12 18:15:01.776  6817  6817 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 18:15:01.854  1033  1049 W libprocessgroup: failed to open /acct/uid_10014/pid_6078/cgroup.procs: No such file or directory
,09-12 18:15:01.867  6817  6817 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
09-12 18:15:01.867  6817  6817 I chromium: 
,09-12 18:15:02.327   346   369 E GBMv2   : DFP En is all cleared set to be enabled
09-12 18:15:02.327   346   369 E GBMv2   : Set value is all cleared set the max
09-12 18:15:02.327   346   369 I GBMv2   : DFP Enabled. Ignore VFP set
,09-12 18:15:02.538  6817  6899 W jxcore-log: Initializing JXcore engine
09-12 18:15:02.538  6817  6899 W jxcore-log: JXcore engine is ready
,09-12 18:15:02.564  6899  6899 W Thread-796: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10395]" dev="sockfs" ino=10395 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-12 18:15:02.564  6899  6899 W Thread-796: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3271 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,09-12 18:15:02.564  6899  6899 W Thread-796: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10566]" dev="sockfs" ino=10566 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
09-12 18:15:02.564  6899  6899 W Thread-796: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
09-12 18:15:02.564  6899  6899 W Thread-796: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33814]" dev="sockfs" ino=33814 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
09-12 18:15:02.592  6817  6899 W jxcore-log: Starting JXcore engine
,09-12 18:15:02.670  6817  6899 W jxcore-log: Platform android
09-12 18:15:02.670  6817  6899 W jxcore-log: 
09-12 18:15:02.670  6817  6899 W jxcore-log: Process ARCH arm
09-12 18:15:02.670  6817  6899 W jxcore-log: 
,09-12 18:15:02.867  6817  6899 I jxcore-log: JXcore Cordova bridge is ready!
09-12 18:15:02.867  6817  6899 I jxcore-log: 
09-12 18:15:02.867  6817  6899 W jxcore-log: JXcore engine is started
,09-12 18:15:02.883  6817  6879 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 18:15:02.887  6817  6817 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 18:15:12.429  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 18:15:12.429  6817  6899 I jxcore-log: 
,09-12 18:15:12.432  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 18:15:12.432  6817  6899 I jxcore-log: 
09-12 18:15:12.438  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:12.438  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:12.438  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:12.438  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:12.438  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:12.438  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:12.438  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:12.438  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:12.440  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:12.442  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 18:15:12.442  6817  6899 I jxcore-log: 
09-12 18:15:12.444  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 18:15:12.444  6817  6899 I jxcore-log: 
,09-12 18:15:12.946  6817  6899 D executeNativeTests: Running unit tests
,09-12 18:15:13.026  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:13.027  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b added. We now have 2 listener(s)
09-12 18:15:13.027  1033  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 18:15:13.028  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:13.028  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:13.029  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:13.029  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:13.029  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 added. We now have 2 listener(s)
09-12 18:15:13.029  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:13.029  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:15:13.032  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:13.037  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:13.037  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.037  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.037  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:13.037  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:13.037  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.037  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:13.037  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:13.039  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.039  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:15:13.043  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.044  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.046  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 18:15:13.049  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:15:13.049  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:15:13.053  6817  6899 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 18:15:13.054  6817  6899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:15:13.054  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:15:13.055  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:15:13.055  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:15:13.056  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.056  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.057  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.057  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.057  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.057  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:13.057  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:13.058  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b removed from the list
09-12 18:15:13.058  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.058  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 removed from the list
09-12 18:15:13.058  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.058  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.060  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.060  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.061  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.061  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.061  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.061  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.062  6817  6899 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 18:15:13.062  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:15:13.062  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.063  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.063  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.063  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.063  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.063  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.063  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.063  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.063  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.063  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.063  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.063  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.063  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.063  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.063  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.063  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.064  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.067  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 18:15:13.067  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 18:15:13.067  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:15:13.067  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 18:15:13.067  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:15:13.067  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:15:13.067  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:15:13.067  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:15:13.068  6817  6899 D io.jxcore.node,.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:15:13.068  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:15:13.068  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.068  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.068  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.069  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.069  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.069  6817  6899 D org.thaliproject.p2p.btconnectorlib.inte,rnal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.069  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.069  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.069  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.069  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.069  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.069  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.070  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.070  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:15:13.072  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.072  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.072  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.072  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.074  6817  6899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 18:15:13.076  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:13.078  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:13.078  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.078  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.078  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:13.078  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:13.078  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.078  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:13.078  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:15:13.079  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.079  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:13.080  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:15:13.081  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.081  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:15:13.081  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:15:13.081  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:13.081  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:15:13.084  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.086  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:15:13.087  1033  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:13.092  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:15:13.098  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:15:13.100  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-12 18:15:13.102  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:15:13.102  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:13.103  6817  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 18:15:13.104  6817  6899 I io.jxcore.node.ConnectionHelper: start: OK
09-12 18:15:13.107  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.107  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.107  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.108  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.108  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.108  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:13.108  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.108  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.108  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.108  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.108  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.108  6817  6899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 18:15:13.109  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:15:13.112  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:13.112  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.112  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.112  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:13.112  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:13.112  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.112  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:13.112  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:15:13.113  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.113  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:13.113  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:15:13.113  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:15:13.113  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:15:13.113  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:13.113  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:15:13.115  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.117  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.118  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:15:13.118  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:13.119  6817  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 18:15:13.119  6817  6899 I io.jxcore.node.ConnectionHelper: start: OK
09-12 18:15:13.120  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.120  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.120  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:15:13.121  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.121  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.121  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:13.121  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.121  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.121  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.121  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.121  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.122  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.122  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.122  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.122  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.123  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.123  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.123  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.123  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.124  6817  6899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 18:15:13.125  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:13.127  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:13.127  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.127  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.127  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:13.127  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:13.127  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.127  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:13.127  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:13.129  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.129  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:13.129  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:15:13.129  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:15:13.129  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start:, Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:15:13.129  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:13.129  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:15:13.131  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:13.133  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:15:13.134  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:13.134  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.135  6817  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 18:15:13.135  6817  6899 I io.jxcore.node.ConnectionHelper: start: OK
09-12 18:15:13.135  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.135  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.135  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.136  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.136  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.136  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.136  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.136  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.136  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:13.136  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.136  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.136  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.136  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.136  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.136  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.136  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.137  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.137  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.137  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.137  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.137  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.137  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.138  6817  6899 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 18:15:13.138  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connectio,ns
09-12 18:15:13.138  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.138  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.139  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.139  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.139  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.139  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.139  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.139  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.139  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.139  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.139  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.139  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.139  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.140  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.140  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.140  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.140  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.140  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.140  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.141  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 18:15:13.141  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.141  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.141  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.141  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.141  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.141  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.141  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.141  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.142  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.142  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.142  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.142  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.142  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.142  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.142  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.142  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.145  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.145  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.145  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.146  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.147  6817  6899 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 18:15:13.148  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.148  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.148  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.148  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.148  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.148  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.148  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.148  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.149  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.149  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.149  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.149  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.149  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.149  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.150  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.150  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.151  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.151  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.151  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.151  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.152  6817  6899 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 18:15:13.152  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.152  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.152  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.152  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.152  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.152  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.153  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.153  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.153  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.153  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.153  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.153  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.153  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.153  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.155  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.155  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.156  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.156  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.156  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.156  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.157  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 18:15:13.158  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:15:13.158  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:15:13.158  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:15:13.158  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 18:15:13.158  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:15:13.158  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.158  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.158  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.158  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.158  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.158  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.158  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.158  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.158  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.158  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.158  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.158  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.158  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.158  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.159  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.159  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.159  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.159  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.159  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.159  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.160  6817  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:15:13.161  6817  6899 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 18:15:13.161  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 18:15:13.164  6817  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:15:13.164  6817  6899 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 18:15:13.164  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:15:13.165  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:15:13.165  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:15:13.165  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:15:13.165  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:15:13.165  6817  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 18:15:13.165  6817  6899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:15:13.165  6817  6899 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 18:15:13.165  6817  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:15:13.165  6817  6899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:15:13.165  6817  6899 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 18:15:13.165  6817  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:15:13.165  6817  6899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:15:13.165  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 18:15:13.167  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 18:15:13.168  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 18:15:13.168  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 18:15:13.168  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 18:15:13.168  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 18:15:13.168  6817  6899 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 18:15:13.168  6817  6899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:15:13.168  6817  6899 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 18:15:13.169  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.169  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.169  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:15:13.171  6817  6917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 860)
09-12 18:15:13.173  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.173  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.173  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.173  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 18:15:13.173  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.173  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.173  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.173  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.173  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.173  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.173  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.173  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.175  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.175  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.175  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.175  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.175  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.175  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.176  6817  6899 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 18:15:13.176  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.176  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.176  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.176  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.176  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.176  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.176  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.176  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.177  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.177  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.177  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.177  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.177  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.177  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.178  6817  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 860
09-12 18:15:13.178  6817  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 860)
09-12 18:15:13.178  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.178  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.178  6817  6918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 860)
09-12 18:15:13.178  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.178  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.178  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.178  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.180  6817  6899 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 18:15:13.180  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.180  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.180  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.190  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.190  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.190  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.190  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.190  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.190  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.190  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.190  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.190  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.190  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.190  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.193  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.193  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.193  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.194  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.194  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.194  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.194  6817  6899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 18:15:13.195  6817  6899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 18:15:13.195  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:15:13.195  6817  6899 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 18:15:13.195  6817  6899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:15:13.195  6817  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 18:15:13.195  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:15:13.195  6817  6899 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 18:15:13.195  6817  6899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:15:13.195  6817  6899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 18:15:13.195  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:15:13.195  6817  6899 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 18:15:13.196  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.196  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.196  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.197  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.197  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.197  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.197  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.197  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.197  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.197  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.197  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.197  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.197  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.197  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.198  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.198  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.199  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.199  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.199  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.199  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.199  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.199  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.199  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.200  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.200  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.200  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.200  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.200  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.200  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.200  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.200  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.200  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.200  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.200  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.200  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.200  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.200  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.200  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.201  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.201  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.201  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.201  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.202  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.202  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.202  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.202  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.202  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.202  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.202  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.205  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.205  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.206  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.206  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.206  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.206  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.207  6817  6899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 18:15:13.208  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:13.209  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 18:15:13.209  6817  6899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 18:15:13.209  6817  6899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 18:15:13.209  6817  6817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 18:15:13.210  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 18:15:13.210  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:15:13.210  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.210  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 18:15:13.210  6817  6899 I org.thaliproject.p2p.btconnecto,rlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 18:15:13.210  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 18:15:13.210  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.210  6817  6899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 18:15:13.211  1033  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:13.212  6817  6919 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:15:13.213  6817  6817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 18:15:13.213  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.213  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.213  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:15:13.213  6817  6899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:15:13.213  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:15:13.213  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:15:13.214  4148  4255 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
09-12 18:15:13.214  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:13.214  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:13.214  6817  6899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:15:13.214  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.214  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.215  6817  6919 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 18:15:13.215  6817  6919 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 18:15:13.215  6817  6919 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 18:15:13.218  6817  6899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:15:13.218  6817  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:15:13.218  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.218  6817  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:15:13.218  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.218  6817  6817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 18:15:13.218  6817  6817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:15:13.218  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.218  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.218  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.218  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.219  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.219  6817  6899 E org.thali,project.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.219  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.219  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.219  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.219  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.219  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.219  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.219  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.219  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.219  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.219  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.219  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.220  6817  6899 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 18:15:13.220  6817  6899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:15:13.220  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:15:13.220  6817  6899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:15:13.221  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.221  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.221  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.221  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.221  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.221  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.221  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.221  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.221  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.221  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.221  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.221  6817  6899 D org.thali,project.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.221  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.221  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.223  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.223  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.223  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.223  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.224  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:13.225  1033  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:13.226  1033  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:13.227  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.227  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.227  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.227  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.227  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.227  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.227  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.227  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.228  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.228  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.228  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.228  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.228  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.228  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.229  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.229  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.229  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.229  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.231  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:13.231  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:13.231  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:13.232  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:13.232  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.232  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.232  6817  6899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f1c386b not in the list
09-12 18:15:13.232  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.232  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.232  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:13.232  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.232  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.232  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:13.232  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:13.233  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:13.233  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:13.233  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:13.233  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f6cfc8 not in the list
09-12 18:15:13.234  6817  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 18:15:13.234  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:15:13.235  6817  6899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 18:15:13.235  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:15:13.235  6817  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 18:15:13.235  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:15:13.239  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 18:15:13.239  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 18:15:13.242  6817  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 18:15:13.242  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:15:13.242  6817  6899 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 18:15:13.242  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:15:13.242  6817  6899 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 18:15:13.242  6817  6899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 18:15:13.243  6817  6899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 18:15:13.243  6817  6899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 18:15:13.243  6817  6899 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 18:15:13.243  6817  6899 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 18:15:13.243  6817  6899 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 18:15:13.243  6817  6899 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 18:15:13.244  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:13.244  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45ff299 added. We now have 2 listener(s)
09-12 18:15:13.244  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:13.246  6817  6917 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-12 18:15:13.249  6817  6917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 860)
09-12 18:15:13.249  6817  6899 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 18:15:13.251  1033  2020 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 18:15:13.251  1033  2020 D WifiService: setWifiEnabled: true pid=6817, uid=10118
09-12 18:15:13.252  1033  2020 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 18:15:13.258  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:13.258  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@141b195e added. We now have 3 listener(s)
09-12 18:15:13.258  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:15:13.262  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:13.262  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@df8a13f added. We now have 4 listener(s)
09-12 18:15:13.262  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:13.263  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:13.263  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29b80a0c added. We now have 5 listener(s)
09-12 18:15:13.263  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:13.265  1033  1597 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 18:15:13.265  1033  1597 D WifiService: setWifiEnabled: false pid=6817, uid=10118
09-12 18:15:13.265  1033  1597 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 18:15:13.275  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 18:15:13.275  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 18:15:13.275  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-12 18:15:13.276  1033  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:13.276  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:13.276  1033  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:13.276  1033  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:13.277  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:13.277  1033  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 18:15:13.277  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:15:13.277  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 18:15:13.277  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:13.277  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 18:15:13.277  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 18:15:13.277  1033  1049 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ab5f943 mBinding = false
09-12 18:15:13.282  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 18:15:13.283  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.283  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.283  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 18:15:13.283  2667  2667 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 18:15:13.283  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 18:15:13.283  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 18:15:13.283  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
09-12 18:15:13.283  1033  2847 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.284   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:15:13.286  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 18:15:13.286  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 18:15:13.287  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-12 18:15:13.287  1033  1095 D BluetoothManagerService: Message: 2
09-12 18:15:13.288  1033  1095 D BluetoothManagerService: Sending off request.
09-12 18:15:13.288  4148  4169 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-12 18:15:13.289  4148  4232 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-12 18:15:13.289  4148  4232 D BluetoothAdapterProperties: Setting state to 13
09-12 18:15:13.289  4148  4232 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 18:15:13.290  4148  4232 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 18:15:13.290  4148  4232 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-12 18:15:13.291  1033  1095 D BluetoothManagerService: Message: 60
09-12 18:15:13.291  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-12 18:15:13.291  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-12 18:15:13.293  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:13.294  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 18:15:13.299  4148  4148 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:13.299  4148  4148 D BluetoothMapService: STATE_TURNING_OFF
09-12 18:15:13.299  4148  4148 V BluetoothMapService: Handler(): got msg=4
09-12 18:15:13.299  4148  4148 D BluetoothMapService: MAP Service closeService in
09-12 18:15:13.300  4148  4148 D BluetoothMapMasInstance: MAP Service shutdown
09-12 18:15:13.300  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.300  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:13.300  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.300  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.300  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:13.300  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:13.300  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.300  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:13.300  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:13.300  4148  4521 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-12 18:15:13.300  4148  4521 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:13.300  4148  4521 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-12 18:15:13.300  4148  4521 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-12 18:15:13.300  4148  4521 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-12 18:15:13.300  4148  4521 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-12 18:15:13.300  4148  4521 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-12 18:15:13.300  4148  4521 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-12 18:15:13.301  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.301  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:13.301  4148  4148 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 18:15:13.301  4148  4148 V BluetoothMapService: MAP Service closeService out
09-12 18:15:13.302  4148  4148 V BtOppService: Receiver DISABLED_ACTION 
09-12 18:15:13.302  4148  4148 I BtOppRfcommListener: stopping Accept Thread
09-12 18:15:13.302  4148  4148 V BtOppRfcommListener: close mBtServerSocket
09-12 18:15:13.303  4148  4556 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:13.303  4148  4556 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 18:15:13.303  4148  4148 V BtOppRfcommListener: waiting for thread to terminate
09-12 18:15:13.304  4148  4148 V BtOppRfcommListener: done waiting for thread to terminate
,09-12 18:15:13.310  1033  1542 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 18:15:13.311  1033  1542 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
09-12 18:15:13.316  1033  1970 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,09-12 18:15:13.316  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.316  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.316  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 18:15:13.316  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.316  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,09-12 18:15:13.351  1033  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6931 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 18:15:13.351  4148  4236 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:15:13.351  4148  4232 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-12 18:15:13.352  4148  4232 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 18:15:13.353  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-12 18:15:13.353  4148  4340 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-12 18:15:13.354  4148  4525 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:13.354  1033  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.354  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.354  1033  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2bd332f6
09-12 18:15:13.355  1033  1535 D LGWifiP2pService: P2pDisablingState
09-12 18:15:13.355  1033  1535 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.355  1033  1535 D LGWifiP2pService: p2p socket connection lost
09-12 18:15:13.355  1033  1535 D LGWifiP2pService: P2pDisabledState
09-12 18:15:13.355   318  6942 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-12 18:15:13.356  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
09-12 18:15:13.356  1033  1542 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-12 18:15:13.356  1033  1542 D DSQN    : disableDataServiceNotify
09-12 18:15:13.356  1033  1542 D DSQN    : stop dsqn bin
09-12 18:15:13.356  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-12 18:15:13.357  4148  4564 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:13.357  4148  4560 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-12 18:15:13.358  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-12 18:15:13.358  4148  4340 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 18:15:13.358  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:13.359  4148  4148 V BtOppService: onDestroy
09-12 18:15:13.360  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-12 18:15:13.361  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.361  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:13.361  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported,: true
09-12 18:15:13.361  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.361  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:13.361  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:13.361  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:13.361  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:13.361  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:13.361  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.361  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:13.362  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.362  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:13.362  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.362  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.362  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:13.362  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:13.362  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:13.362  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:13.362  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:13.362  1967  1967 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-12 18:15:13.362  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.362  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:13.362  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:13.364  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:13.364  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:13.364  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:13.364  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:13.365  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:13.365  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:13.366  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:13.367  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:13.367  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:13.367  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 18:15:13.368  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-12 18:15:13.368  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:13.368  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:13.369  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:13.370  1033  1542 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 18:15:13.370  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:13.370  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:13.370  1033  1542 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:13.371  1033  1542 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-12 18:15:13.371  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.371  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.371  1033  2842 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 18:15:13.371  1603  1812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 18:15:13.372  1033  1542 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-12 18:15:13.372  1033  1542 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 18:15:13.372  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 18:15:13.372  1033  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 18:15:13.373  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:13.373  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:13.373  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDAT,E_LINKPROPERTIES 0 0
09-12 18:15:13.373  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-12 18:15:13.374  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:13.374  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:13.374  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 18:15:13.374  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 18:15:13.374  1033  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.375  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.375  1033  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.375  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 18:15:13.375  2667  2667 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 18:15:13.375  1033  1033 D RttService: SCAN_AVAILABLE : 1
09-12 18:15:13.375  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 18:15:13.375  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 18:15:13.375  1033  1555 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.375  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
09-12 18:15:13.375   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:15:13.378  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 18:15:13.378  1967  1967 D WfdsService: WifiP2pState is changed : false
09-12 18:15:13.378  1967  2347 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-12 18:15:13.378  1967  2347 D WfdsService: Set the WFDS Monitor: false
09-12 18:15:13.379  1967  2347 D WfdsMonitor: WFDS Monitor is stopped
09-12 18:15:13.379  1967  2347 D WfdsService: STATE : WfdsDisabledState - enter
,09-12 18:15:13.379  1967  2349 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-12 18:15:13.379  1967  2741 D CtrlSupplicant: Received on exit socket, terminate
09-12 18:15:13.379  1967  2741 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-12 18:15:13.379  1967  2741 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-12 18:15:13.379  1967  2741 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-12 18:15:13.379  1967  2347 W WfdsService: DefaultState - msg [9445378] is not handled
09-12 18:15:13.387  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:13.387  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:13.388  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:13.421  1033  1091 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6956 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-12 18:15:13.422  4148  4148 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-12 18:15:13.422  1033  1542 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:13.422  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 18:15:13.423  1033  1542 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:13.423  1033  1542 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:13.424  1033  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 18:15:13.424  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.424  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 18:15:13.424  1033  1536 D WifiNative-p2p0: doBoolean: TERMINATE
09-12 18:15:13.424  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 18:15:13.425  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 18:15:13.425  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 18:15:13.425  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 18:15:13.425  1033  1542 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:13.425  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-12 18:15:13.425  1033  1536 D WifiNative-p2p0: TERMINATE: returned true
09-12 18:15:13.425  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 18:15:13.425  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
09-12 18:15:13.425  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 18:15:13.425  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 18:15:13.425  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 18:15:13.425  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 18:15:13.425  1033  1542 D NetworkManagementService: Removing idletimer
09-12 18:15:13.426  1033  1542 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:13.426  1033  1542 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 18:15:13.426  1879  1879 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 18:15:13.427  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 18:15:13.427  1033  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 18:15:13.427  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:13.427  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:13.428  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 18:15:13.431  1033  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:13.431  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:13.432  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.432  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:13.432  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.432  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.432  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:13.432  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:13.432  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:13.432  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:13.432  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:13.432  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-12 18:15:13.433  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.433  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:13.435  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-12 18:15:13.436  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.436  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:13.436  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.436  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.436  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:13.436  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:13.436  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:13.436  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:13.436  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:13.437  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_AC,TION
09-12 18:15:13.437  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-12 18:15:13.437  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.437  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:13.439  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:13.439  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:13.439  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:13.439  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:13.439  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:13.439  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:13.439  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:13.439  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:13.439  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:15:13.452  6931  6931 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:15:13.452  6931  6931 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,09-12 18:15:13.453  6931  6931 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:13.453  6931  6931 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
09-12 18:15:13.454  6931  6931 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 18:15:13.455  6931  6931 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-12 18:15:13.465  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 18:15:13.466  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:13.467  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:13.480  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 18:15:13.480  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:13.481  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:13.481  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 18:15:13.481  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:13.482  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:13.500  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:13.506  1033  2847 D DhcpStateMachine: StoppedState
09-12 18:15:13.506  1033  2847 D DhcpStateMachine: StoppedState{ when=-131ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:13.507  1033  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-12 18:15:13.507  1033  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
09-12 18:15:13.524  6956  6956 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-12 18:15:13.524  6956  6956 W LG Account v2.2: No ProfileInfo entries
09-12 18:15:13.524  6956  6956 I LG Account v2.2: isEnabled: false
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]Country: EU
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]Operator: OPEN
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]Ranking support: false
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]Comfort support: false
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]Accessory: true
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]Health device: true
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]Extra Pedometer: false
09-12 18:15:13.524  6956  6956 I Feature : [Lifetracker]Blood glucose device: false
,09-12 18:15:13.525  6956  6956 I Feature : [Lifetracker]Device Number: 3
,09-12 18:15:13.532  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:13.551  2667  2667 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 18:15:13.551  2667  2667 I wpa_supplicant: monitor socket send errors count : 1
09-12 18:15:13.551  2667  2667 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1967-2\x00 that cannot receive messages
09-12 18:15:13.551  6931  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 18:15:13.552  1033  2735 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,09-12 18:15:13.552  1033  2735 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 18:15:13.579  1033  1573 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6977 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 18:15:13.581  1033  1573 I ActivityManager: Killing 6221:com.android.defcontainer/u0a4 (adj 15): empty #17
09-12 18:15:13.589  2667  2667 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 18:15:13.590  1033  2735 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-12 18:15:13.590  1033  2735 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 18:15:13.590  1033  2735 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 18:15:13.590  1033  2735 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-12 18:15:13.590  1033  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=202126
09-12 18:15:13.590  2667  2667 W wpa_supplicant: USIM:  scard_deinit function
09-12 18:15:13.590  1033  2735 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:13.590  1033  2735 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 18:15:13.590  1033  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=202126
09-12 18:15:13.591  1033  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=202127  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 18:15:13.592  1033  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=202127  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,09-12 18:15:13.621  2667  2667 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-12 18:15:13.621  1033  2735 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
09-12 18:15:13.621  1033  2735 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
,09-12 18:15:13.622  1033  2735 D WifiMonitor: Disconnecting from the supplicant, no more events
09-12 18:15:13.623  1033  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
09-12 18:15:13.633  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{136853b5 type 2 when 202115 com.google.android.gms} when 202115
,09-12 18:15:13.634  1033  1095 D Tethering: InitialState.processMessage what=4
09-12 18:15:13.643  1033  1763 W libprocessgroup: failed to open /acct/uid_10004/pid_6221/cgroup.procs: No such file or directory
09-12 18:15:13.649  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:15:13.649  1033  1095 D BluetoothManagerService: Message: 20
,09-12 18:15:13.649  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e8b4dbb:true
,09-12 18:15:13.652  4148  4148 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 18:15:13.652  4148  4148 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:13.652  4148  4148 V BluetoothPbapReceiver: ***********state = 13
09-12 18:15:13.653  4148  4148 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-12 18:15:13.655  4148  4148 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:13.655  4148  4148 V BluetoothPbapService: state: 13
09-12 18:15:13.655  4148  4148 V BluetoothPbapService: Pbap Service closeService in
09-12 18:15:13.658  1033  1095 D BluetoothManagerService: Message: 30
09-12 18:15:13.660  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:15:13.664  4148  4148 V BluetoothPbapService: successfully stopped pbap service
09-12 18:15:13.664  4148  4148 V BluetoothPbapService: Pbap Service closeService out
09-12 18:15:13.665  4148  4148 V BluetoothPbapService: Pbap Service onDestroy
09-12 18:15:13.665  4148  4148 V BluetoothPbapService: Pbap Service closeService in
09-12 18:15:13.665  4148  4148 V BluetoothPbapService: Pbap Service closeService out
,09-12 18:15:13.665  4148  4148 D LGBluetoothPbapAdapter: [BTUI] cleanup
,09-12 18:15:13.673  1033  1095 D BluetoothManagerService: Message: 30
09-12 18:15:13.678  6931  6931 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 18:15:13.679  6931  6931 D BluetoothMap: Create BluetoothMap proxy object
09-12 18:15:13.680  1033  1095 D BluetoothManagerService: Message: 30
09-12 18:15:13.684  1033  1095 D BluetoothManagerService: Message: 30
09-12 18:15:13.687  6931  6931 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-12 18:15:13.690  6931  6931 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,09-12 18:15:13.702  6977  6977 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,09-12 18:15:13.712  6977  6977 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 18:15:13.712  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:13.717  1033  2089 I ActivityManager: Killing 6394:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,09-12 18:15:13.719  6817  6817 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 18:15:13.743  1033  2020 W libprocessgroup: failed to open /acct/uid_10008/pid_6394/cgroup.procs: No such file or directory
09-12 18:15:13.743  1967  1967 D WfdsService: Supplicant Connection state is changed : false
,09-12 18:15:13.744  1967  2347 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-12 18:15:13.744  1967  2347 D WfdsService: Set the WFDS Monitor: false
09-12 18:15:13.744  1967  2347 D WfdsMonitor: WFDS Monitor is stopped
09-12 18:15:13.744  6931  6931 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
09-12 18:15:13.748  1033  1536 D WifiOffDelayIfNotUsed: stopMonitoring
09-12 18:15:13.748  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 18:15:13.748  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
09-12 18:15:13.748  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 18:15:13.749  6931  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
09-12 18:15:13.750  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 18:15:13.750  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:13.753  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-12 18:15:13.753  1033  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-12 18:15:13.754  1033  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-12 18:15:13.754  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:13.755  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:13.756  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:13.762  6931  6931 D DockEventReceiver: finishStartingService: stopping service
09-12 18:15:13.763  6931  6931 D BluetoothInputDevice: Proxy object connected
,09-12 18:15:13.764  6931  6931 D HidProfile: Bluetooth service connected
09-12 18:15:13.775  6931  6931 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:15:13.776  6931  6931 D PanProfile: Bluetooth service connected
09-12 18:15:13.776  6931  6931 D BluetoothMap: Proxy object connected
09-12 18:15:13.777  6931  6931 D MapProfile: Bluetooth service connected
09-12 18:15:13.777  6931  6931 D BluetoothMap: getConnectedDevices()
,09-12 18:15:13.778  6931  6931 D BluetoothMap: Bluetooth is Not enabled
09-12 18:15:13.790  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:13.830  6931  6931 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:13.831  6931  6931 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 18:15:13.841  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:13.841  6931  6931 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-12 18:15:13.843  6931  6931 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-12 18:15:13.850  6931  6931 D BluetoothPermissionRequest: onReceive
,09-12 18:15:13.855  6931  6931 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,09-12 18:15:13.868  6931  6931 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-12 18:15:13.870  1033  1763 I ActivityManager: Killing 6433:com.lge.appbox.client/u0a11 (adj 15): empty #17
,09-12 18:15:13.952  1033  1536 E WifiStateMachine:  InitialState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:13.953  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-12 18:15:13.978  1033  2112 W libprocessgroup: failed to open /acct/uid_10011/pid_6433/cgroup.procs: No such file or directory
,09-12 18:15:13.980  4148  4148 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-12 18:15:13.980  4148  4148 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-12 18:15:13.982  4148  4148 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-12 18:15:14.071  1033  2000 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7011 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,09-12 18:15:14.080  4148  4148 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:14.081  4148  4148 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 18:15:14.083  4148  4148 V BluetoothFtpService: Ftp Service onStartCommand
09-12 18:15:14.083  4148  4148 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:14.084  4148  4148 V BluetoothFtpService: Ftp Service closeService
09-12 18:15:14.084  4148  4148 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-12 18:15:14.086  4148  4148 V BluetoothFtpService: successfully stopped ftp service
09-12 18:15:14.087  4148  4148 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 18:15:14.087  4148  4148 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 18:15:14.087  4148  4148 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 18:15:14.088  4148  4148 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:14.088  4148  4148 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-12 18:15:14.088  4148  4148 V BluetoothSapReceiver: Calling SAP service start service with action = null
,09-12 18:15:14.091  4148  4148 V BluetoothFtpService: Ftp Service onDestroy
09-12 18:15:14.091  4148  4148 V BluetoothFtpService: Ftp Service closeService
09-12 18:15:14.132  1033  2112 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7028 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 18:15:14.137  4148  4148 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:14.137  4148  4148 V BluetoothSapService: state: 13
09-12 18:15:14.137  4148  4148 V BluetoothSapService: Stopping SAP server process
09-12 18:15:14.138  4148  4148 V BluetoothSapService: Sap Service closeSapService in
09-12 18:15:14.139  4148  4148 V BluetoothSapService: Close listen Socket : 
09-12 18:15:14.139  4148  4148 V BluetoothSapService: Close rfcomm Socket : 
09-12 18:15:14.139  4148  4148 V BluetoothSapService: Close sapd  Socket : 
09-12 18:15:14.142  4148  4148 V BluetoothSapService: Sap Service closeSapService out
09-12 18:15:14.143  4148  4148 V BluetoothSapService: Sap Service onDestroy
09-12 18:15:14.143  4148  4148 V BluetoothSapService: Sap Service closeSapService in
09-12 18:15:14.143  4148  4148 V BluetoothSapService: Close listen Socket : 
09-12 18:15:14.143  4148  4148 V BluetoothSapService: Close rfcomm Socket : 
09-12 18:15:14.143  4148  4148 V BluetoothSapService: Close sapd  Socket : 
,09-12 18:15:14.148  4148  4148 V BluetoothSapService: Sap Service closeSapService out
,09-12 18:15:14.195  7011  7011 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-12 18:15:14.205  7028  7028 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:14.220  1033  2020 I ActivityManager: Killing 6453:com.android.contacts/u0a19 (adj 15): empty #17
,09-12 18:15:14.254  1033  1763 W libprocessgroup: failed to open /acct/uid_10019/pid_6453/cgroup.procs: No such file or directory
,09-12 18:15:14.256  7011  7011 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-12 18:15:14.296  7011  7011 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
09-12 18:15:14.296  7011  7011 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-12 18:15:14.296  7011  7011 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-12 18:15:14.297  7011  7011 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-12 18:15:14.297  7011  7011 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-12 18:15:14.299  7011  7011 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,09-12 18:15:14.305  7011  7011 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-12 18:15:14.313  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:14.318  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:14.337  7011  7011 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 18:15:14.340  7011  7011 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
09-12 18:15:14.343  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:14.346  7011  7011 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-12 18:15:14.348  6977  6977 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 18:15:14.348  6977  6977 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 18:15:14.348  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:14.352  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:14.362  4148  4340 W bt-btif : ag scb idx 1 not allocated
09-12 18:15:14.362  4148  4340 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 18:15:14.362  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 18:15:14.362  4148  4340 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:15:14.362  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:14.362  4148  4236 D bt_hci_bdroid: cleanup
09-12 18:15:14.362  4148  4340 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 18:15:14.363  4148  4340 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:15:14.363  4148  4340 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 18:15:14.363  4148  4344 I bt_lpm  : LPM is already off!!!
09-12 18:15:14.363  4148  4499 I bt_userial_mct: exiting userial_read_thread
09-12 18:15:14.363  4148  4499 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 18:15:14.364  4148  4236 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 18:15:14.364  4148  4344 I bt_vendor: hw_epilog_process
09-12 18:15:14.365  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:14.365  4148  4236 D bt_hci_bdroid: cleanup Finalizing cleanup
09-12 18:15:14.365  4148  4236 D bt_userial_mct: userial_close
09-12 18:15:14.366  4148  4236 E bt_userial_mct: pthread_join() FAILED result:3
09-12 18:15:14.366  4148  4236 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 18:15:14.376  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:14.376  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:14.379  7011  7011 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 18:15:14.384  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:14.389  6977  6977 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 18:15:14.389  6977  6977 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 18:15:14.389  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:14.393  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:14.404  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:14.417  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:14.418  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:14.421  7011  7011 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 18:15:14.470  4148  4236 D bt_hci_bdroid: set_power 0
09-12 18:15:14.470  4148  4236 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 18:15:14.470  4148  4236 I bt_vendor: bluetooth satus is on
09-12 18:15:14.470  4148  4236 I bt_vendor: bt-vendor : resetting BT status
09-12 18:15:14.470  4148  4236 I bt_vendor: Starting hciattach daemon
09-12 18:15:14.470  4148  4236 I bt_vendor: try to set false
09-12 18:15:14.472  4148  4236 I bt_vendor: Starting hciattach daemon
09-12 18:15:14.472  4148  4236 I bt_vendor: try to set false
,09-12 18:15:14.474  4148  4236 I bt_vendor: cleanup
09-12 18:15:14.475  4148  4340 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-12 18:15:14.484  1033  1970 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7061 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
09-12 18:15:14.487  4148  4236 I GKI_LINUX: GKI_exit_task 0 done
09-12 18:15:14.487  4148  4236 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-12 18:15:14.488  4148  4232 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-12 18:15:14.493  4148  4148 D HeadsetService: Received stop request...Stopping profile...
,09-12 18:15:14.494  4148  4148 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 18:15:14.494  4148  4148 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:15:14.494  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f870cf1
09-12 18:15:14.494  4148  4258 D HeadsetStateMachine: Exit Disconnected: -1
09-12 18:15:14.495  1879  1879 D BluetoothHeadset: Proxy object disconnected
09-12 18:15:14.495  1033  1033 D BluetoothHeadset: Proxy object disconnected
09-12 18:15:14.495  1879  1879 D BluetoothHeadset: Proxy object disconnected
09-12 18:15:14.495  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 18:15:14.495  1879  1879 D BluetoothHeadset: Proxy object disconnected
09-12 18:15:14.497  4148  4148 D A2dpService: Received stop request...Stopping profile...
09-12 18:15:14.498  4148  4306 D A2dpStateMachine: Exit Disconnected: -1
09-12 18:15:14.499  4148  4148 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
09-12 18:15:14.500  4148  4232 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-12 18:15:14.501  4148  4148 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-12 18:15:14.501  4148  4148 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:15:14.501  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f870cf1
09-12 18:15:14.504  4148  4148 D HidService: Received stop request...Stopping profile...
09-12 18:15:14.504  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f870cf1
09-12 18:15:14.505  6931  6931 D BluetoothInputDevice: Proxy object disconnected
09-12 18:15:14.505  1033  1033 D BluetoothA2dp: Proxy object disconnected
09-12 18:15:14.505  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-12 18:15:14.505  6931  6931 D HidProfile: Bluetooth service disconnected
09-12 18:15:14.506  4148  4148 D HealthService: Received stop request...Stopping profile...
09-12 18:15:14.506  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f870cf1
09-12 18:15:14.507  4148  4148 D HeadsetStateMachine: Unbinding service...
09-12 18:15:14.508  4148  4148 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 18:15:14.508  4148  4148 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 18:15:14.508  4148  4148 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 18:15:14.508  4148  4148 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 18:15:14.508  4148  4148 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 18:15:14.508  4148  4148 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:15:14.508  4148  4148 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 18:15:14.509  4148  4148 D PanService: Received stop request...Stopping profile...
09-12 18:15:14.509  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f870cf1
09-12 18:15:14.510  4148  4148 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:15:14.510  4148  4148 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 18:15:14.510  4148  4148 D BtGatt.GattService: stop()
09-12 18:15:14.510  4148  4148 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 18:15:14.511  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f870cf1
09-12 18:15:14.511  6931  6931 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:15:14.511  6931  6931 D PanProfile: Bluetooth service disconnected
09-12 18:15:14.512  4148  4148 D BluetoothMapService: Received stop request...Stopping profile...
09-12 18:15:14.512  4148  4148 D BluetoothMapService: stop()
09-12 18:15:14.513  4148  4148 D BluetoothMapEmailAppObserver: deinitObservers()
09-12 18:15:14.513  4148  4148 D BluetoothMapEmailAppObserver: removeReceiver()
09-12 18:15:14.514  4148  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f870cf1
,09-12 18:15:14.515  4148  4148 I BluetoothA2dpServiceJni: cleanupNative
09-12 18:15:14.515  4148  4307 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 18:15:14.515  4148  4148 I GKI_LINUX: GKI_exit_task 2 done
09-12 18:15:14.515  4148  4148 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 18:15:14.516  4148  4148 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 18:15:14.516  4148  4148 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 18:15:14.516  4148  4148 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 18:15:14.516  4148  4148 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:15:14.516  4148  4148 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-12 18:15:14.517  4148  4148 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:15:14.517  4148  4148 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 18:15:14.517  6931  6931 D BluetoothMap: Proxy object disconnected
09-12 18:15:14.517  6931  6931 D MapProfile: Bluetooth service disconnected
09-12 18:15:14.518  4148  4148 V BluetoothMapService: Handler(): got msg=4
09-12 18:15:14.518  4148  4148 D BluetoothMapService: MAP Service closeService in
09-12 18:15:14.518  4148  4148 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 18:15:14.518  4148  4148 V BluetoothMapService: MAP Service closeService out
09-12 18:15:14.518  4148  4148 D BluetoothMapService: cleanup()
09-12 18:15:14.518  4148  4148 D BluetoothMapService: MAP Service closeService in
09-12 18:15:14.518  4148  4148 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 18:15:14.518  4148  4148 V BluetoothMapService: MAP Service closeService out
09-12 18:15:14.518  4148  4232 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-12 18:15:14.518  4148  4232 D BluetoothAdapterProperties: Setting state to 10
09-12 18:15:14.518  4148  4232 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 18:15:14.519  1033  1095 D BluetoothManagerService: Message: 60
09-12 18:15:14.519  4148  4232 I BluetoothAdapterState: Entering OffState
09-12 18:15:14.519  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-12 18:15:14.519  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
09-12 18:15:14.519  1879  2442 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:15:14.520  6931  6953 D BluetoothMap: onBluetoothStateChange: up=false
09-12 18:15:14.521  6931  6954 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 18:15:14.521  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:15:14.522  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:15:14.522  6931  6953 D BluetoothPan: onBluetoothStateChange on: false
09-12 18:15:14.522  6931  6954 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 18:15:14.523  1879  4264 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:15:14.523  1879  3208 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:15:14.524  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-12 18:15:14.525  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-12 18:15:14.527  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-12 18:15:14.527  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-12 18:15:14.527  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ab5f943 mBinding = false
09-12 18:15:14.528  1033  1095 D BluetoothManagerService: Sending unbind request.
,09-12 18:15:14.531  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
09-12 18:15:14.536  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 18:15:14.538  4148  4236 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-12 18:15:14.538  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:14.539  4148  4148 I GKI_LINUX: GKI_exit_task 1 done
09-12 18:15:14.539  4148  4148 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-12 18:15:14.539  4148  4148 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 18:15:14.539  4148  4148 I art     : --- WEIRD: removing null entry 246
09-12 18:15:14.539  4148  4148 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
,09-12 18:15:14.539  4148  4148 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-12 18:15:14.540  6931  6931 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 18:15:14.541  6931  6931 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-12 18:15:14.541  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:14.541  6931  6931 D LGBluetoothEventManager: [BTUI] clear device connection state
09-12 18:15:14.541  1967  2179 D LGBluetoothAPIService: Message: 2
09-12 18:15:14.541  1967  2179 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2f5ad2e8 mBinding = false
09-12 18:15:14.541  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:14.541  1967  2179 D LGBluetoothAPIService: Sending unbind request.
09-12 18:15:14.543  6931  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,09-12 18:15:14.546  4148  4148 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-12 18:15:14.548  4148  4148 I art     : System.exit called, status: 0
09-12 18:15:14.548  4148  4148 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-12 18:15:14.549  1603  1603 D BluetoothAdapter: 116975731: getState() :  mService = null. Returning STATE_OFF
09-12 18:15:14.549  1603  1603 D BluetoothAdapter: 116975731: getState() :  mService = null. Returning STATE_OFF
09-12 18:15:14.552  6931  6931 D DockEventReceiver: finishStartingService: stopping service
09-12 18:15:14.568   322  1383 V AudioFlinger: 4148 died, releasing its sessions
09-12 18:15:14.568   322  1383 V AudioFlinger:  pid 1879 @ 0
09-12 18:15:14.568   322  1383 V AudioFlinger:  pid 3329 @ 1
09-12 18:15:14.568   322  1383 V AudioFlinger:  pid 3329 @ 2
,09-12 18:15:14.569  6931  6931 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-12 18:15:14.590  1033  2036 I ActivityManager: Process com.android.bluetooth (pid 4148) has died
,09-12 18:15:14.590  1033  2036 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,09-12 18:15:14.595  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:15:14.602  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:14.610  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:15:14.618  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:14.622  6931  6931 D BluetoothPermissionRequest: onReceive
09-12 18:15:14.629  6931  6931 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 18:15:14.630  6931  6931 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,09-12 18:15:14.633  7061  7082 W FormManager: Network not available. Please check & try again.
09-12 18:15:14.636  6931  6931 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 18:15:14.694  1033  1764 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7084 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-12 18:15:14.712  7061  7083 V FormManager: Network unavailable.
,09-12 18:15:14.720  7061  7083 V FormManager: Network unavailable.
,09-12 18:15:14.723   318  7099 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
09-12 18:15:14.724  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,09-12 18:15:14.744  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 18:15:14.744  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 18:15:14.745  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 18:15:14.745  6931  6931 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 18:15:14.745  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 18:15:14.754  6931  6931 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 18:15:14.754  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 18:15:14.754  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 18:15:14.754  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 18:15:14.755  6931  6931 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 18:15:14.755  6931  6931 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,09-12 18:15:14.760  1033  1573 I ActivityManager: Killing 6478:com.lge.email/u0a23 (adj 15): empty #17
,09-12 18:15:14.774  7084  7084 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-12 18:15:14.774  7084  7084 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:14.775  7084  7084 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-12 18:15:14.775  7084  7084 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 18:15:14.791  7084  7084 D BluetoothAdapterApp: Loading JNI Library
,09-12 18:15:14.816  7084  7084 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e040ffe Instance Count = 1
,09-12 18:15:14.822  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 18:15:14.822  1033  2089 W libprocessgroup: failed to open /acct/uid_10023/pid_6478/cgroup.procs: No such file or directory
09-12 18:15:14.822  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:14.823  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:14.835  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 18:15:14.837  7084  7084 D BluetoothAdapterApp: onCreate
09-12 18:15:14.852  6977  6977 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-12 18:15:14.852  6977  6977 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 18:15:14.853  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 18:15:14.854  7084  7084 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-12 18:15:14.854  7084  7084 D ProfileConfigQcom: Adding HeadsetService
09-12 18:15:14.854  7084  7084 D ProfileConfigQcom: [BTUI] A2dpService is supported
09-12 18:15:14.854  7084  7084 D ProfileConfigQcom: Adding A2dpService
09-12 18:15:14.854  7084  7084 D ProfileConfigQcom: [BTUI] HidService is supported
09-12 18:15:14.854  7084  7084 D ProfileConfigQcom: Adding HidService
09-12 18:15:14.855  7084  7084 D ProfileConfigQcom: [BTUI] HealthService is supported
09-12 18:15:14.855  7084  7084 D ProfileConfigQcom: Adding HealthService
09-12 18:15:14.855  7084  7084 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-12 18:15:14.855  7084  7084 D ProfileConfigQcom: [BTUI] PanService is supported
09-12 18:15:14.856  7084  7084 D ProfileConfigQcom: Adding PanService
09-12 18:15:14.856  7084  7084 D ProfileConfigQcom: [BTUI] GattService is supported
09-12 18:15:14.856  7084  7084 D ProfileConfigQcom: Adding GattService
09-12 18:15:14.856  7084  7084 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-12 18:15:14.856  7084  7084 D ProfileConfigQcom: Adding BluetoothMapService
09-12 18:15:14.856  7084  7084 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-12 18:15:14.858  7084  7084 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-12 18:15:14.860  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 18:15:14.861  4615  7105 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 18:15:14.862  4615  7106 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 18:15:14.864  4615  7106 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 18:15:14.866  7084  7084 V LGMDMManagerInternal: Create singleton instance
,09-12 18:15:14.875  7061  7111 V FormManager: Network unavailable.
09-12 18:15:14.876  7061  7110 W FormManager: Network not available. Please check & try again.
09-12 18:15:14.876  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:14.878  6931  6931 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
09-12 18:15:14.884  7061  7111 V FormManager: Network unavailable.
,09-12 18:15:14.892  7011  7011 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-12 18:15:14.900  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,09-12 18:15:14.901  7011  7011 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-12 18:15:14.913  7084  7084 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:15:14.916  7084  7084 V BluetoothSapReceiver: [BTUI] checkServiceStart
,09-12 18:15:14.916  7084  7084 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 18:15:14.916  7084  7084 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 18:15:14.917  7084  7084 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:14.917  7084  7084 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-12 18:15:14.922  7028  7028 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-12 18:15:14.924  1033  1964 I ActivityManager: Killing 6502:com.android.gallery3d/u0a27 (adj 15): empty #17
09-12 18:15:14.937  7011  7011 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:14.937  7011  7011 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 18:15:14.943  7011  7011 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
09-12 18:15:14.944  7011  7011 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-12 18:15:14.944  7011  7011 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-12 18:15:14.944  7011  7011 V SoundPool: doLoad: loading sample sampleID=1
09-12 18:15:14.944  7011  7011 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-12 18:15:14.946  7011  7115 V SoundPool: Start decode
09-12 18:15:14.946  7011  7115 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-12 18:15:14.947   322  1383 V MediaPlayerService: decode(22, 10857164, 17813)
,09-12 18:15:14.947   322  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-12 18:15:14.947   322  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-12 18:15:14.947   322  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-12 18:15:14.947   322  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-12 18:15:14.947   322  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-12 18:15:14.947   322  1383 V MediaPlayerService: player type = 3
09-12 18:15:14.947   322  1383 V AwesomePlayer: AwesomePlayer create()
09-12 18:15:14.947   322  1383 V AwesomePlayer: reset_l() 
,09-12 18:15:14.947   322  1383 V AwesomePlayer: cancelPlayerEvents
,09-12 18:15:14.947   322  1383 V AwesomePlayer: setAudioSink() 
09-12 18:15:14.947   322  1383 V AwesomePlayer: reset_l() 
,09-12 18:15:14.947   322  1383 V AudioCache: notify(0xb5474700, 8, 0, 0)
09-12 18:15:14.947   322  1383 V AudioCache: ignored
09-12 18:15:14.947   322  1383 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:14.947   322  1383 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
,09-12 18:15:14.947   322  1383 V AwesomePlayer: setDataSource_l dataSource
09-12 18:15:14.947   322  1383 V LGParserOSAL: SniffLGParser start
09-12 18:15:14.947   322  1383 V LGParserOSAL: MainType:5, SubType=0
09-12 18:15:14.947   322  1383 V LGParserOSAL: #### check Mime : application/ogg
09-12 18:15:14.947   322  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-12 18:15:14.947   322  1383 E MediaExtractor: Use LGExtractor :application/ogg 
09-12 18:15:14.983   322  1383 V LGParserOSAL: supported mime: application/ogg
,09-12 18:15:14.983   322  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,09-12 18:15:14.984   322  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-12 18:15:14.984   322  1383 V AwesomePlayer: mBitrate = -1 bits/sec
09-12 18:15:14.984   322  1383 V AwesomePlayer: AudioTrack Setting
09-12 18:15:14.984   322  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-12 18:15:14.984   322  1383 V AwesomePlayer: setAudioSource() 
,09-12 18:15:14.984   322  1383 V MediaPlayerService: prepare
09-12 18:15:14.984   322  1383 V AwesomePlayer: prepareAsync_l() 
09-12 18:15:14.984   322  1383 V MediaPlayerService: wait for prepare
09-12 18:15:14.984   322  7116 V AwesomePlayer: onPrepareAsyncEvent() 
,09-12 18:15:14.984   322  7116 V AwesomePlayer: initAudioDecoder() 
09-12 18:15:14.984   322  7116 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-12 18:15:14.984   322  7116 V AudioSystem: isOffloadSupported()
09-12 18:15:14.984   322  7116 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,09-12 18:15:14.984   322  7116 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-12 18:15:14.984   322  7116 I AudioFlinger: isAudioPlaybackHookOn() false
09-12 18:15:14.984   322  7116 V AwesomePlayer: getUseOffload() = 0 
,09-12 18:15:14.984   322  7116 V OMXCodec: OMXCodec::Create
09-12 18:15:14.984   322  7116 V OMXCodec: findMatchingCodecs()
09-12 18:15:14.984   322  7116 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
,09-12 18:15:14.984   322  7116 V OMXCodec: matchingCodecs.size()=1
09-12 18:15:14.984   322  7116 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-12 18:15:14.985   322  7116 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-12 18:15:14.985   322  7116 V LGCodecAdapter: LG Codec Adapter start,
09-12 18:15:14.985   322  7116 V OMXCodec: OMXCodec Createtor
09-12 18:15:14.985   322  7116 V OMXCodec: setComponentRole
,09-12 18:15:14.986   322  7116 V OMXCodec: configureCodec protected=0
09-12 18:15:14.986   322  7116 V LGCodecAdapter: called getLGCodecSpecificData
09-12 18:15:14.986   322  7116 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-12 18:15:14.986   322  7116 V LGCodecOSAL: Called LGconfigureCodecMETA
09-12 18:15:14.986   322  7116 V LGCodecOSAL: Called LGconfigureCodecMSG
09-12 18:15:14.986   322  7116 V LGCodecOSAL: Not support LGCodec
09-12 18:15:14.986   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,09-12 18:15:14.986   322  7116 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-12 18:15:14.986   322  7116 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-12 18:15:14.986   322  7116 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-12 18:15:14.987   322  7116 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-12 18:15:14.987   322  7116 V AudioSystem: isOffloadSupported()
09-12 18:15:14.987   322  7116 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-12 18:15:14.987   322  7116 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-12 18:15:14.987   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
,09-12 18:15:14.987   322  7116 V OMXCodec: init()
09-12 18:15:14.987   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-12 18:15:14.987   322  7116 V OMXCodec: allocateBuffers
09-12 18:15:14.987   322  7116 V OMXCodec: allocateBuffersOnPort portIndex=0
09-12 18:15:14.987   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-12 18:15:14.988   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
09-12 18:15:14.988   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
09-12 18:15:14.988   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
,09-12 18:15:14.988   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
09-12 18:15:14.988   322  7116 V OMXCodec: allocateBuffersOnPort portIndex=1
09-12 18:15:14.988   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-12 18:15:14.989   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on output port
09-12 18:15:14.989   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-12 18:15:14.989   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-12 18:15:14.989   322  7116 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
09-12 18:15:14.989   322  7116 V OMXCodec: init() mAsyncCompletion wait!!! 
09-12 18:15:14.989   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-12 18:15:14.989   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-12 18:15:14.989   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
09-12 18:15:14.989   322  7116 V OMXCodec: init() mAsyncCompletion wait!!! 
09-12 18:15:14.989   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-12 18:15:14.989   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-12 18:15:14.989   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,09-12 18:15:14.989   322  7116 V OMXCodec: init() mAsyncCompletion wait free! 
09-12 18:15:14.989   322  7116 V AwesomePlayer: finishAsyncPrepare_l() ,
09-12 18:15:14.989   322  7116 V AudioCache: notify(0xb5474700, 5, 0, 0)
09-12 18:15:14.989   322  7116 V AudioCache: ignored
09-12 18:15:14.989   322  7116 V AudioCache: notify(0xb5474700, 1, 0, 0)
,09-12 18:15:14.989   322  7116 V AudioCache: prepared
09-12 18:15:14.989   322  1383 V AudioCache: wait - success
09-12 18:15:14.989   322  1383 V MediaPlayerService: start
09-12 18:15:14.989   322  1383 V AwesomePlayer: play_l() 
09-12 18:15:14.989   322  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-12 18:15:14.989   322  1383 V AwesomePlayer: createAudioPlayer_l
09-12 18:15:14.989   322  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
09-12 18:15:14.989   322  1383 V AwesomePlayer: startAudioPlayer_l() 
,09-12 18:15:14.989   322  1383 D AudioPlayer: start of Playback, useOffload 0
09-12 18:15:14.989   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-12 18:15:14.989   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-12 18:15:14.991  1033  1048 W libprocessgroup: failed to open /acct/uid_10027/pid_6502/cgroup.procs: No such file or directory
09-12 18:15:14.991   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-12 18:15:14.991   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
09-12 18:15:14.991   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,09-12 18:15:14.991   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-12 18:15:14.991   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048176
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,09-12 18:15:14.994   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
09-12 18:15:14.995   322  7118 V OMXCodec: allocateBuffersOnPort portIndex=1
09-12 18:15:14.995   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-12 18:15:14.995   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-12 18:15:14.995   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-12 18:15:14.995   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on output port
09-12 18:15:14.995   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on output port
09-12 18:15:14.995   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,09-12 18:15:14.995   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-12 18:15:14.996  7011  7011 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-12 18:15:14.996   322  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-12 18:15:14.997  7011  7011 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 18:15:14.997   322  1383 V AudioCache: notify(0xb5474700, 6, 0, 0)
09-12 18:15:14.997   322  1383 V AudioCache: ignored
09-12 18:15:14.997  6693  6693 D UEI.SmartControl: QS Service created
,09-12 18:15:14.997   322  1383 V MediaPlayerService: wait for playback complete
09-12 18:15:14.997  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-12 18:15:14.998   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:14.998   322  7119 V AudioCache: memcpy(0xaf006000, 0xb57be000, 4096)
09-12 18:15:14.999   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:14.999   322  7119 V AudioCache: memcpy(0xaf007000, 0xb57be000, 4096)
09-12 18:15:15.000   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.000   322  7119 V AudioCache: memcpy(0xaf008000, 0xb57be000, 4096)
,09-12 18:15:15.000   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.001   322  7119 V AudioCache: memcpy(0xaf009000, 0xb57be000, 4096)
09-12 18:15:15.001   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.001   322  7119 V AudioCache: memcpy(0xaf00a000, 0xb57be000, 4096)
09-12 18:15:15.002   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.002   322  7119 V AudioCache: memcpy(0xaf00b000, 0xb57be000, 4096)
09-12 18:15:15.002   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.002   322  7119 V AudioCache: memcpy(0xaf00c000, 0xb57be000, 4096)
,09-12 18:15:15.003   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.003   322  7119 V AudioCache: memcpy(0xaf00d000, 0xb57be000, 4096)
09-12 18:15:15.003   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.003   322  7119 V AudioCache: memcpy(0xaf00e000, 0xb57be000, 4096)
09-12 18:15:15.004   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.004   322  7119 V AudioCache: memcpy(0xaf00f000, 0xb57be000, 4096)
,09-12 18:15:15.004   322  7119 V AudioCache: write(0xb57be000, 4096)
,09-12 18:15:15.005   322  7119 V AudioCache: memcpy(0xaf010000, 0xb57be000, 4096)
09-12 18:15:15.005   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.005   322  7119 V AudioCache: memcpy(0xaf011000, 0xb57be000, 4096)
09-12 18:15:15.006   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.006   322  7119 V AudioCache: memcpy(0xaf012000, 0xb57be000, 4096)
09-12 18:15:15.006   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.006   322  7119 V AudioCache: memcpy(0xaf013000, 0xb57be000, 4096)
09-12 18:15:15.007   322  7119 V AudioCache: write(0xb57be000, 4096)
,09-12 18:15:15.007   322  7119 V AudioCache: memcpy(0xaf014000, 0xb57be000, 4096)
09-12 18:15:15.007   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.007   322  7119 V AudioCache: memcpy(0xaf015000, 0xb57be000, 4096)
09-12 18:15:15.008   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.008   322  7119 V AudioCache: memcpy(0xaf016000, 0xb57be000, 4096)
09-12 18:15:15.008   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.008   322  7119 V AudioCache: memcpy(0xaf017000, 0xb57be000, 4096)
09-12 18:15:15.009   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.009   322  7119 V AudioCache: memcpy(0xaf018000, 0xb57be000, 4096)
,09-12 18:15:15.010   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.010   322  7119 V AudioCache: memcpy(0xaf019000, 0xb57be000, 4096)
09-12 18:15:15.010   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.010   322  7119 V AudioCache: memcpy(0xaf01a000, 0xb57be000, 4096)
09-12 18:15:15.011   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.011   322  7119 V AudioCache: memcpy(0xaf01b000, 0xb57be000, 4096)
09-12 18:15:15.011   322  7119 V AudioCache: write(0xb57be000, 4096)
,09-12 18:15:15.011   322  7119 V AudioCache: memcpy(0xaf01c000, 0xb57be000, 4096)
09-12 18:15:15.012   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.012   322  7119 V AudioCache: memcpy(0xaf01d000, 0xb57be000, 4096)
09-12 18:15:15.012   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.012   322  7119 V AudioCache: memcpy(0xaf01e000, 0xb57be000, 4096)
09-12 18:15:15.013   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.013   322  7119 V AudioCache: memcpy(0xaf01f000, 0xb57be000, 4096)
09-12 18:15:15.013   322  7119 V AudioCache: write(0xb57be000, 4096)
,09-12 18:15:15.013   322  7119 V AudioCache: memcpy(0xaf020000, 0xb57be000, 4096)
09-12 18:15:15.014   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.014   322  7119 V AudioCache: memcpy(0xaf021000, 0xb57be000, 4096)
09-12 18:15:15.014   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.014   322  7119 V AudioCache: memcpy(0xaf022000, 0xb57be000, 4096)
09-12 18:15:15.015   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.015   322  7119 V AudioCache: memcpy(0xaf023000, 0xb57be000, 4096)
09-12 18:15:15.016  6693  6693 I UEI.SmartControl: Service initServices...
,09-12 18:15:15.016   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.016   322  7119 V AudioCache: memcpy(0xaf024000, 0xb57be000, 4096)
09-12 18:15:15.016  6693  6693 D UEI.SmartControl: QS start get config
09-12 18:15:15.016   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.016   322  7119 V AudioCache: memcpy(0xaf025000, 0xb57be000, 4096)
09-12 18:15:15.017   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.017   322  7119 V AudioCache: memcpy(0xaf026000, 0xb57be000, 4096)
09-12 18:15:15.017   322  7119 V AudioCache: write(0xb57be000, 4096)
,09-12 18:15:15.017   322  7119 V AudioCache: memcpy(0xaf027000, 0xb57be000, 4096)
,09-12 18:15:15.018   322  7119 V AudioCache: write(0xb57be000, 4096)
,09-12 18:15:15.018   322  7119 V AudioCache: memcpy(0xaf028000, 0xb57be000, 4096)
09-12 18:15:15.018   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.019   322  7119 V AudioCache: memcpy(0xaf029000, 0xb57be000, 4096)
09-12 18:15:15.019   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.019   322  7119 V AudioCache: memcpy(0xaf02a000, 0xb57be000, 4096)
09-12 18:15:15.020   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.020   322  7119 V AudioCache: memcpy(0xaf02b000, 0xb57be000, 4096)
09-12 18:15:15.020   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.020   322  7119 V AudioCache: memcpy(0xaf02c000, 0xb57be000, 4096)
09-12 18:15:15.020   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.020   322  7119 V AudioCache: memcpy(0xaf02d000, 0xb57be000, 4096)
09-12 18:15:15.020   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.020   322  7119 V AudioCache: memcpy(0xaf02e000, 0xb57be000, 4096)
,09-12 18:15:15.021   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.022   322  7119 V AudioCache: memcpy(0xaf02f000, 0xb57be000, 4096)
09-12 18:15:15.022   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.022   322  7119 V AudioCache: memcpy(0xaf030000, 0xb57be000, 4096)
09-12 18:15:15.022   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.022   322  7119 V AudioCache: memcpy(0xaf031000, 0xb57be000, 4096)
09-12 18:15:15.022   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.022   322  7119 V AudioCache: memcpy(0xaf032000, 0xb57be000, 4096)
09-12 18:15:15.023   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.023   322  7119 V AudioCache: memcpy(0xaf033000, 0xb57be000, 4096)
09-12 18:15:15.023   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.023   322  7119 V AudioCache: memcpy(0xaf034000, 0xb57be000, 4096)
,09-12 18:15:15.023   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.023   322  7119 V AudioCache: memcpy(0xaf035000, 0xb57be000, 4096)
09-12 18:15:15.024   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.024   322  7119 V AudioCache: memcpy(0xaf036000, 0xb57be000, 4096)
09-12 18:15:15.024   322  7119 V AudioCache: write(0xb57be000, 4096)
09-12 18:15:15.024   322  7119 V AudioCache: memcpy(0xaf037000, 0xb57be000, 4096)
09-12 18:15:15.024   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-12 18:15:15.024   322  7119 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-12 18:15:15.024   322  7119 V AwesomePlayer: postAudioEOS() 
09-12 18:15:15.024   322  7119 V AudioCache: write(0xb57be000, 280)
09-12 18:15:15.024   322  7119 V AudioCache: memcpy(0xaf038000, 0xb57be000, 280)
09-12 18:15:15.026   322  7116 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
,09-12 18:15:15.026   322  7116 V AwesomePlayer: onStreamDone
09-12 18:15:15.026   322  7116 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-12 18:15:15.026   322  7116 V AudioCache: notify(0xb5474700, 2, 0, 0)
09-12 18:15:15.026   322  7116 V AudioCache: playback complete
09-12 18:15:15.026   322  7116 V AwesomePlayer: pause_l() 
09-12 18:15:15.026   322  1383 V AudioCache: wait - success
09-12 18:15:15.026   322  7116 V AudioCache: notify(0xb5474700, 7, 0, 0)
09-12 18:15:15.026   322  7116 V AudioCache: ignored
09-12 18:15:15.026   322  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-12 18:15:15.026   322  7116 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:15.026   322  7116 D AudioPlayer: Pause Playback at 1068125
09-12 18:15:15.027   322  1383 V AwesomePlayer: reset_l() 
,09-12 18:15:15.027   322  1383 V AudioCache: notify(0xb5474700, 8, 0, 0)
09-12 18:15:15.027   322  1383 V AudioCache: ignored
09-12 18:15:15.027   322  1383 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:15.027   322  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-12 18:15:15.027   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-12 18:15:15.027   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-12 18:15:15.027   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-12 18:15:15.027   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
,09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 1
09-12 18:15:15.027   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-12 18:15:15.028   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 1
09-12 18:15:15.028   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
,09-12 18:15:15.028   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
09-12 18:15:15.028   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-12 18:15:15.028   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
09-12 18:15:15.028   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 18:15:15.028   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-12 18:15:15.028   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-12 18:15:15.028   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,09-12 18:15:15.030   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
,09-12 18:15:15.030   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-12 18:15:15.030   322  7118 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-12 18:15:15.030   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-12 18:15:15.030   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
09-12 18:15:15.031   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-12 18:15:15.032   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-12 18:15:15.032   322  1383 D AudioPlayer: AudioPlayer releasing audio source
09-12 18:15:15.032   322  1383 D AudioPlayer: AudioPlayer done releasing audio source
,09-12 18:15:15.032   322  1383 V AwesomePlayer: reset_l() 
09-12 18:15:15.032   322  1383 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:15.032   322  1383 V AwesomePlayer: ~AwesomePlayer call
09-12 18:15:15.032   322  1383 V AwesomePlayer: reset_l() 
09-12 18:15:15.032   322  1383 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:15.033  7011  7115 V SoundPool: close(31)
09-12 18:15:15.033  7011  7115 V SoundPool: pointer = 0x9fe5c000, size = 205080, sampleRate = 48000, numChannels = 2
09-12 18:15:15.042  7011  7011 V LGMDMManager: Create singleton instance
,09-12 18:15:15.106  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view,
,09-12 18:15:15.107  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-12 18:15:15.110  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3331
09-12 18:15:15.247  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3ef87d4d type 2 when 203783 com.google.android.gms} when 203783
,09-12 18:15:15.289  6693  6693 I UEI.SmartControl: Supports setup maps: true
,09-12 18:15:15.305  6693  6693 D UEI.SmartControl: QS start statue = true Error code = 0
,09-12 18:15:15.305  6693  6693 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-12 18:15:15.305  6693  6693 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,09-12 18:15:15.305  6693  6693 I UEI.SmartControl: ### init IR Blaster...
09-12 18:15:15.310  6693  6693 D serial_port: Configuring serial port
09-12 18:15:15.311  6693  6693 E UEI.SmartControl: UEIBLaster setting for 616
09-12 18:15:15.311  6693  6693 I UEI.SmartControl: Setting serial record hearder size = 2
09-12 18:15:15.311  6693  6693 I UEI.SmartControl: configuring settings for MAXQ616
09-12 18:15:15.311  6693  6693 I UEI.SmartControl: Get version...
09-12 18:15:15.327  6693  7124 D UEI.SmartControl: serial port data available: 21
,09-12 18:15:15.353  6693  6693 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-12 18:15:15.353  6693  6693 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-12 18:15:15.353  6693  6693 I UEI.SmartControl: QS saving settings...
09-12 18:15:15.355  6693  6693 D UEI.SmartControl: IR Blaster version: 25672567
,09-12 18:15:15.372  6693  7124 D UEI.SmartControl: serial port data available: 4
,09-12 18:15:15.401  6693  7130 I UEI.SmartControl: Device manager: loading config....
,09-12 18:15:15.403  6693  6693 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
09-12 18:15:15.404  6693  7130 D UEI.SmartControl: ----------- loading internal config...
,09-12 18:15:15.406  6693  6693 E UEI.SmartControl: Services init done
09-12 18:15:15.406  6693  6693 D UEI.SmartControl: QS Service init finished
09-12 18:15:15.407  6693  6693 D UEI.SmartControl: QS Service version name: 2.1.91
09-12 18:15:15.407  6693  6693 D UEI.SmartControl: QS Service version code: 201091
09-12 18:15:15.408  6693  6693 D UEI.SmartControl: Service requested: Control
09-12 18:15:15.410  6693  7130 E UEI.SmartControl: Loading SETTINGS...
09-12 18:15:15.414  6693  6693 D UEI.SmartControl: Request IControl service: devices are loaded...
09-12 18:15:15.417  7011  7011 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,09-12 18:15:15.420  6693  7130 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-12 18:15:15.421  6693  6693 D UEI.SmartControl: Internal service binding...
09-12 18:15:15.421  6693  6708 I UEI.SmartControl: ------ IControl API: 11
09-12 18:15:15.421  6693  6708 D UEI.SmartControl: File observer start...
09-12 18:15:15.422  6693  6708 E UEI.SmartControl: IR Port is disabled: false
09-12 18:15:15.422  6693  6708 D UEI.SmartControl: Starting file observer...
09-12 18:15:15.423  6693  6708 I UEI.SmartControl: Registering callback...
09-12 18:15:15.424  6693  6714 I UEI.SmartControl: ------ IControl API: 19
09-12 18:15:15.426  6693  6714 I UEI.SmartControl: Registering Services Ready callback...
09-12 18:15:15.440  6693  7129 I UEI.SmartControl: Notify AllClients services are ready: 0
,09-12 18:15:15.441  7011  7027 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
09-12 18:15:15.442  7011  7113 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-12 18:15:15.442  7011  7113 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-12 18:15:15.443  6693  7129 D UEI.SmartControl: -----service ready thread exits
09-12 18:15:15.444  7011  7011 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,09-12 18:15:15.444  7011  7011 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-12 18:15:15.445  6693  6708 I UEI.SmartControl: ------ IControl API: 8
09-12 18:15:15.447  7011  7011 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-12 18:15:15.447  7011  7011 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-12 18:15:15.447  7011  7011 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-12 18:15:15.448  7011  7011 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-12 18:15:15.449  7011  7011 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-12 18:15:15.450  7011  7011 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-12 18:15:15.453  7011  7011 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,09-12 18:15:15.458  7011  7011 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-12 18:15:15.460  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-12 18:15:15.462  7011  7011 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 18:15:15.462  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-12 18:15:15.464  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-12 18:15:15.466  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
09-12 18:15:15.467  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,09-12 18:15:15.470  7011  7011 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1473696915468]
09-12 18:15:15.477  7011  7011 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,09-12 18:15:15.481  1033  1573 I ActivityManager: Killing 6561:com.google.android.apps.docs/u0a61 (adj 15): empty #17
09-12 18:15:15.500  7011  7132 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,09-12 18:15:15.511  1033  2020 W libprocessgroup: failed to open /acct/uid_10061/pid_6561/cgroup.procs: No such file or directory
09-12 18:15:15.516  7011  7011 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,09-12 18:15:15.519  7011  7011 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 18:15:15.519  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
09-12 18:15:15.520  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
09-12 18:15:15.520  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
09-12 18:15:15.520  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
09-12 18:15:15.521  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
09-12 18:15:15.530  7011  7011 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,09-12 18:15:16.312  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{17524b50 type 2 when 204835 com.google.android.gms} when 204835
,09-12 18:15:16.368  1033  2036 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,09-12 18:15:16.369  1033  2036 D WifiService: setWifiEnabled: true pid=6817, uid=10118
09-12 18:15:16.377  1033  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 18:15:16.397  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 18:15:16.397  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 18:15:16.397  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,09-12 18:15:16.402  1033  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-12 18:15:16.402  1033  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-12 18:15:16.404  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-12 18:15:16.404  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 18:15:16.405  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-12 18:15:16.405  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 18:15:16.405  1033  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-12 18:15:16.405  1033  1536 E WifiHW  : unknown target_country: EU , set to default
09-12 18:15:16.405  1033  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-12 18:15:16.405  1033  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-12 18:15:16.405  1033  1536 I WifiUtil: gEnableBmps=1
09-12 18:15:16.425  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:16.432  1033  1095 D Tethering: MasterInitialState.processMessage what=3
09-12 18:15:16.440  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:16.443  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:16.445  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:16.450  1033  1095 D Tethering: MasterInitialState.processMessage what=3
09-12 18:15:16.452  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:16.462  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:16.463  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:16.465  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-12 18:15:16.469  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-12 18:15:16.472  6322  6976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,09-12 18:15:16.492  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-12 18:15:16.508  2222  2222 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:16.590  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:16.593  1033  2112 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7151 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-12 18:15:16.595  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:16.596  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 18:15:16.663  7151  7151 I AppUp4:AppBoxCP: onCreate
09-12 18:15:16.664  7151  7151 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,09-12 18:15:16.673  7151  7151 I AppUp4:DB:  setFingerPrint start
09-12 18:15:16.673  7151  7151 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
09-12 18:15:16.680  7151  7151 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
09-12 18:15:16.680  7151  7151 I AppUp4:DB:  SDK version = 21
09-12 18:15:16.680  7151  7151 I AppUp4:DB:  beforefinger == newfinger no write in DB
09-12 18:15:16.681  7151  7151 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,09-12 18:15:16.683  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 18:15:16.683  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:16.685  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 18:15:16.685  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 18:15:16.691  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
09-12 18:15:16.737  7151  7151 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:16.738  7151  7151 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 18:15:16.752  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1dc9fc98
09-12 18:15:16.752  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 18:15:16.752  7151  7151 D AppUp4:CustFacade: isPhone : true
09-12 18:15:16.753  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-12 18:15:16.753  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
09-12 18:15:16.753  7151  7151 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,09-12 18:15:16.754  7151  7172 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
09-12 18:15:16.755  7151  7172 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
09-12 18:15:16.755  7151  7172 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
09-12 18:15:16.758  1033  1970 I ActivityManager: Killing 6607:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
09-12 18:15:16.815  1033  1048 W libprocessgroup: failed to open /acct/uid_10080/pid_6607/cgroup.procs: No such file or directory
,09-12 18:15:16.819  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:16.820  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:16.822  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:16.825  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:16.834  4615  7174 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-12 18:15:16.841  4615  7175 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:16.841  4615  7175 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 18:15:16.894  1033  2112 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7179 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-12 18:15:16.926   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 482us total 33.524ms
,09-12 18:15:16.947   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 444us total 20.834ms
,09-12 18:15:16.969   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 454us total 21.139ms
,09-12 18:15:16.982  7179  7179 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:15:16.983  7179  7179 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:16.986  7179  7179 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 18:15:16.986  7179  7179 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 18:15:17.084  7179  7179 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-12 18:15:17.099  7179  7179 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-12 18:15:17.139  7179  7179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 18:15:17.221  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-12 18:15:17.224  1033  1095 D Tethering: InitialState.processMessage what=4
09-12 18:15:17.227  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:15:17.238   318   893 D SoftapController: Softap fwReload - Ok
,09-12 18:15:17.247  1033  1536 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (836ms)
,09-12 18:15:17.257   318   893 D CommandListener: Setting iface cfg
09-12 18:15:17.258   318   893 D CommandListener: Trying to bring down wlan0
09-12 18:15:17.260   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:15:17.262  1033  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-12 18:15:17.263  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 18:15:17.263  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
09-12 18:15:17.263  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 18:15:17.254  7204  7204 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:17.254  7204  7204 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:17.272  1033  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-12 18:15:17.272  1033  1536 D WifiMonitor: connecting to supplicant
09-12 18:15:17.273  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:17.274  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,09-12 18:15:17.277  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-12 18:15:17.283  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:17.286  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:17.304  1033  2036 I art     : Explicit concurrent mark sweep GC freed 66990(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 3.870ms total 161.518ms
,09-12 18:15:17.310  7204  7204 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 18:15:17.333  7179  7179 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:17.333  7179  7179 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 18:15:17.344  7204  7204 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:15:17.344  7204  7204 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
09-12 18:15:17.378  7204  7204 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:15:17.429  7204  7204 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,09-12 18:15:17.434  7179  7179 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-12 18:15:17.442  7204  7204 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-12 18:15:17.443  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-12 18:15:17.444  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-12 18:15:17.444  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-12 18:15:17.445  1033  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-12 18:15:17.445  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:17.446  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:17.446  1033  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-12 18:15:17.446  1033  7213 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 18:15:17.446  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:17.447  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:17.447  1033  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-12 18:15:17.447  1033  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-12 18:15:17.448  1033  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-12 18:15:17.448  1033  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-12 18:15:17.448  1033  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-12 18:15:17.453  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 18:15:17.453  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
09-12 18:15:17.453  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 18:15:17.454  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.454  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.454  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.454  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.454  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 18:15:17.454  1033  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
09-12 18:15:17.455  1033  1536 D WifiNative-wlan0: SET update_config 1: returned true
09-12 18:15:17.455  1033  1536 D WifiConfigStore: Loading config and enabling all networks 
09-12 18:15:17.455  1033  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-12 18:15:17.455  1033  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,09-12 18:15:17.458  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
09-12 18:15:17.458  1033  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-12 18:15:17.459  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:17.459  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:17.459  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:17.459  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:17.459  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:17.459  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:17.459  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:17.459  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:17.459  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:17.459  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:17.459  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:17.460  1967  1967 D WfdService: Waiting for WifiP2p enabling
09-12 18:15:17.461  7204  7204 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-12 18:15:17.461  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-12 18:15:17.461  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 18:15:17.461  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-12 18:15:17.461  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:17.461  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-12 18:15:17.461  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:17.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:17.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:17.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:17.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:17.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:17.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:17.461  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:17.461  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:17.461  1033  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-12 18:15:17.461  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:17.461  1033  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-12 18:15:17.462  1603  1603, D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:17.463  1033  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-12 18:15:17.469  3329  3329 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 18:15:17.469  3329  3329 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:17.470  3329  3329 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 18:15:17.472  1033  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,09-12 18:15:17.473  1033  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-12 18:15:17.511  1033  2057 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7218 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,09-12 18:15:17.515  1033  1536 D WifiStateMachine: enableVerboseLogging : level 2
,09-12 18:15:17.515  1033  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-12 18:15:17.516  1033  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-12 18:15:17.516  1033  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-12 18:15:17.517  1033  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-12 18:15:17.517  1033  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-12 18:15:17.517  1033  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-12 18:15:17.517  1033  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-12 18:15:17.518  7061  7216 W FormManager: Network not available. Please check & try again.
09-12 18:15:17.518  1033  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-12 18:15:17.518  1033  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-12 18:15:17.518  7061  7217 V FormManager: Network unavailable.
09-12 18:15:17.518  1033  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-12 18:15:17.518  1033  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-12 18:15:17.519  1033  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-12 18:15:17.519  1033  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-12 18:15:17.519  1033  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-12 18:15:17.520  7061  7217 V FormManager: Network unavailable.
09-12 18:15:17.521  1033  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 18:15:17.521  1033  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-12 18:15:17.521  1967  1967 D WfdsService: Supplicant Connection state is changed : true
09-12 18:15:17.521  1967  2347 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-12 18:15:17.521  1967  2347 D WfdsService: Set the WFDS Monitor: true
09-12 18:15:17.521  1967  2347 D WfdsMonitor: WfdsMonitorThread create
,09-12 18:15:17.521  1967  2347 D WfdsMonitor: WFDS Monitor is created and started
09-12 18:15:17.521  1967  2347 D WfdsService: WiFi: Supplicant connection re-established
09-12 18:15:17.521  1033  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-12 18:15:17.521  1033  1536 D WifiNative-HAL: Setting external_sim to 1
09-12 18:15:17.521  1033  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-12 18:15:17.522  1033  1536 D WifiNative-wlan0: SET external_sim 1: returned true
09-12 18:15:17.522  1033  1536 I WifiNative-HAL: startHal
09-12 18:15:17.522  1967  7227 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-12 18:15:17.522  1033  1536 D wifi    : setting scan oui 0xaf6251a0
09-12 18:15:17.522  1967  7227 E CtrlSupplicant: Succeed to open control connection
09-12 18:15:17.522  1033  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 18:15:17.523  1033  1536 I WifiNative-HAL: startHal
,09-12 18:15:17.523  1033  1536 D wifi    : setting scan oui 0xaf6251a0
09-12 18:15:17.523  1967  7227 E CtrlSupplicant: Succeed to open monitor connection
09-12 18:15:17.523  1033  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-12 18:15:17.523  1967  7227 D WfdsMonitor: Supplicant connection established
09-12 18:15:17.524  1967  2347 D WfdsService: Connected to the supplicant for wfds
09-12 18:15:17.526  1033  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-12 18:15:17.526  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-12 18:15:17.526  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-12 18:15:17.527  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-12 18:15:17.527  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 18:15:17.527  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 18:15:17.528  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 18:15:17.528  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-12 18:15:17.529  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-12 18:15:17.529  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-12 18:15:17.529  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 18:15:17.529  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 18:15:17.530  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 18:15:17.530  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 18:15:17.530  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 18:15:17.530  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 18:15:17.530  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-12 18:15:17.530  7204  7204 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-12 18:15:17.531  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-12 18:15:17.531  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 18:15:17.531  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 18:15:17.531  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 18:15:17.532  7179  7179 I HubEmail: JNI_OnLoad()
09-12 18:15:17.532  7179  7179 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 18:15:17.532  7179  7179 I HubEmail: registerNatives()
09-12 18:15:17.532  7179  7179 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 18:15:17.532  7179  7179 I HubEmail: registerNativeMethods()
09-12 18:15:17.532  7179  7179 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
09-12 18:15:17.532  1033  1536 E WifiNative: : [206,067,810 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-12 18:15:17.532  7179  7179 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
09-12 18:15:17.532  1033  1536 D WifiNative-wlan0: doBoolean: RECONNECT
09-12 18:15:17.533  1033  1536 D WifiNative-wlan0: RECONNECT: returned true
09-12 18:15:17.533  1033  1536 D WifiNative-wlan0: doString: [STATUS]
09-12 18:15:17.533  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-12 18:15:17.534  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 18:15:17.534  1033  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 18:15:17.534  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 18:15:17.534  1033  1536 D WifiNative-wla,n0: SET ps 1: returned true
09-12 18:15:17.534  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.535  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 18:15:17.535  1033  1033 D RttService: SCAN_AVAILABLE : 3
,09-12 18:15:17.535  1033  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.535  1033  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.535  1033  1554 I WifiNative-HAL: startHal
09-12 18:15:17.535  1033  1554 D wifi    : getting scan capabilities on interface[1] = 0xaf6251a0
09-12 18:15:17.535  1033  1554 D wifi    : failed to get capabilities : -3
09-12 18:15:17.535  1033  1554 E WifiScanningService: could not get scan capabilities
09-12 18:15:17.536  1033  1048 I ActivityManager: Killing 6658:com.lge.eula/1000 (adj 15): empty #17
09-12 18:15:17.536  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-12 18:15:17.537   318   893 D CommandListener: Setting iface cfg
09-12 18:15:17.537   318   893 D CommandListener: Trying to bring up p2p0
09-12 18:15:17.537  1033  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 18:15:17.537  1033  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-12 18:15:17.537  1033  1535 D LGWifiP2pService: P2pEnablingState
09-12 18:15:17.537  1033  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.537  1033  1535 D LGWifiP2pService: P2p socket connection successful
09-12 18:15:17.537  1033  1535 D LGWifiP2pService: P2pEnabledState
09-12 18:15:17.538  1033  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-12 18:15:17.538  1033  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-12 18:15:17.538  1033  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-12 18:15:17.539  1033  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-12 18:15:17.539  1033  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-12 18:15:17.539  1033  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-12 18:15:17.539  7204  7204 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-12 18:15:17.540  1033  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-12 18:15:17.541  1033  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-12 18:15:17.541  1033  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-12 18:15:17.541  1033  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-12 18:15:17.541  7204  7204 E wpa_supplicant: disconnect_rssi_lvl: -100
09-12 18:15:17.542  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=206078  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 18:15:17.632  1033  1535 D LGWifiP2pService: sending p2p connection changed broadcast
09-12 18:15:17.633  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,09-12 18:15:17.635  1967  1967 D WfdsService: WifiP2pState is changed : true
,09-12 18:15:17.635  1967  2347 D WfdsService: Receive the WFDS_ENABLE Method
09-12 18:15:17.635  1967  2347 D WfdsService: Set the WFDS Monitor: true
09-12 18:15:17.635  1967  2347 D WfdsService: Connected to the supplicant for wfds
,09-12 18:15:17.636  1967  2347 D WfdsJNI : doCommand: WFDS_SET TRUE
09-12 18:15:17.636  7204  7204 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-12 18:15:17.636  1967  2347 D WfdsService: selectPreferredScanChannel [36]
09-12 18:15:17.637  1967  2347 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-12 18:15:17.651  1033  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-12 18:15:17.653  1033  1964 W libprocessgroup: failed to open /acct/uid_1000/pid_6658/cgroup.procs: No such file or directory
09-12 18:15:17.654  1033  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-12 18:15:17.656  1033  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
,09-12 18:15:17.658  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=206194  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 18:15:17.659  1033  1535 D WifiNative-p2p0: SET device_name G3: returned true
09-12 18:15:17.659  1033  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-12 18:15:17.659  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 18:15:17.659  1033  1535 D LGWifiP2pService: before postfix = G3
09-12 18:15:17.659  1033  1535 D WifiServerServiceExt: postfix byte check : 2
09-12 18:15:17.659  1033  1535 D LGWifiP2pService: after postfix = G3
09-12 18:15:17.660  1033  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-12 18:15:17.660  1033  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 18:15:17.660  1033  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
09-12 18:15:17.660  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-12 18:15:17.661  1033  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-12 18:15:17.661  1033  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-12 18:15:17.662  1033  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-12 18:15:17.662  1033  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-12 18:15:17.664  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.664  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.664  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 18:15:17.665  1967  1967 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-12 18:15:17.665  1033  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-12 18:15:17.665  1033  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-12 18:15:17.665  1967  1967 D WfdsService: isConnected: false
09-12 18:15:17.666  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:17.667  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:17.667  1033  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-12 18:15:17.668  1033  1535 D WifiNative-HAL: p2pGetDeviceAddress
09-12 18:15:17.668  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:17.669  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 18:15:17.670  7204  7204 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-12 18:15:17.671  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 18:15:17.671  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:17.671  1033  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-12 18:15:17.671  1033  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:17.672  7179  7231 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.673  7204  7204 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 18:15:17.673  7204  7204 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.673  1033  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:17.673  1967  7227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:17.674  1033  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.674  1033  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.674  1033  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.674  1033  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
,09-12 18:15:17.675  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-12 18:15:17.675  7204  7204 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.676  1967  7227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:17.676  1033  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-12 18:15:17.677  1033  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-12 18:15:17.677  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-12 18:15:17.677  1033  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:17.677  1033  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.678  1033  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.678  1033  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.678  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-12 18:15:17.678  7204  7204 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 18:15:17.678  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-12 18:15:17.679  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 18:15:17.679  1033  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 18:15:17.679  1033  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 18:15:17.681  1033  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-12 18:15:17.681  1033  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-12 18:15:17.682  1033  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-12 18:15:17.682  1033  1536 D WifiNative-wlan0: doBoolean: SCAN
09-12 18:15:17.683  1033  1536 D WifiNative-wlan0: SCAN: returned false
,09-12 18:15:17.685  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=206221  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 18:15:17.686  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=206222  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 18:15:17.687  1033  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:17.688  1033  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-12 18:15:17.688  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.689  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:17.689  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 18:15:17.689  1033  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:17.690  1033  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:17.690  1033  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:17.690  1033  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:17.691  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:17.691  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
09-12 18:15:17.692  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:17.692  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:17.693  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:17.694  1033  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-12 18:15:17.694  1033  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-12 18:15:17.694  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:17.694  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
09-12 18:15:17.695  1033  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
09-12 18:15:17.695  1033  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-12 18:15:17.695  1967  1967 I WfdStateTracker: handleP2pThisDeviceChanged
09-12 18:15:17.695  1967  1967 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-12 18:15:17.695  1967  1967 D WfdsService: Update P2p Interface State: 3
09-12 18:15:17.695  1033  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-12 18:15:17.695  1033  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-12 18:15:17.696  1033  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-12 18:15:17.696  1033  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,09-12 18:15:17.714  1033  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-12 18:15:17.714  1033  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-12 18:15:17.714  1033  1535 D LGWifiP2pService: InactiveState
09-12 18:15:17.714  1033  1535 D LGWifiP2pService: InactiveState{ when=-40ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.714  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-40ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.714  1033  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-12 18:15:17.715  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 18:15:17.715  7204  7204 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:17.715  1033  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 18:15:17.715  1033  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:17.716  1033  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:17.716  1033  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,09-12 18:15:17.716  7204  7204 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
,09-12 18:15:17.716  7204  7204 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.716  1967  7227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 18:15:17.716  1967  7227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:17.716  7204  7204 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.716  1033  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-12 18:15:17.716  1033  1535 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.716  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1967  7227 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:17.717  1033  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:17.717  1033  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1033  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.717  1033  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1033  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1033  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.717  1033  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.717  1033  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.717  1033  1535 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.718  1967  2347 W WfdsService: DefaultState - msg [9441285] is not handled
09-12 18:15:17.718  1033  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.718  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.718  1033  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:17.718  1033  1033 E WifiServerServiceExt: No p2p device connected
09-12 18:15:17.733  7218  7218 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:17.734  7218  7218 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 18:15:17.736  7218  7218 D PhoneMonitor: Register our PhoneStateListener
,09-12 18:15:17.746  7218  7218 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,09-12 18:15:17.747  7218  7218 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 18:15:17.758  7218  7218 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
09-12 18:15:17.759  7218  7218 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,09-12 18:15:17.760  7218  7218 D TelephonyAutoProfiling: [parse] Load xml
09-12 18:15:17.763  7218  7218 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
09-12 18:15:17.763  7218  7218 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
09-12 18:15:17.763  7218  7218 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
09-12 18:15:17.768  7218  7218 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
09-12 18:15:17.824  1033  1597 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7240 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:15:17.829  1033  1597 I ActivityManager: Killing 5457:com.lge.bnr/1000 (adj 15): empty #17
09-12 18:15:17.880  1033  2057 W libprocessgroup: failed to open /acct/uid_1000/pid_5457/cgroup.procs: No such file or directory
,09-12 18:15:18.116  1033  1049 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7261 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,09-12 18:15:18.117  1033  1049 I ActivityManager: Killing 6629:com.google.android.apps.plus/u0a97 (adj 15): empty #17
09-12 18:15:18.144  7204  7204 E wpa_supplicant: USIM:  scard_init function
09-12 18:15:18.144  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-12 18:15:18.144  1033  7213 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-12 18:15:18.145  7204  7204 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-12 18:15:18.145  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-12 18:15:18.145  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
09-12 18:15:18.145  1033  7213 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-12 18:15:18.145  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-12 18:15:18.145  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
09-12 18:15:18.146  1033  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,09-12 18:15:18.147  1033  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 18:15:18.148  1033  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 18:15:18.150  1033  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 18:15:18.150  1033  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
09-12 18:15:18.201  1033  2000 W libprocessgroup: failed to open /acct/uid_10097/pid_6629/cgroup.procs: No such file or directory
,09-12 18:15:18.206  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206742  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 18:15:18.211  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=206747  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 18:15:18.213  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:15:18.215  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.215  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 18:15:18.215  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:18.215  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-12 18:15:18.216  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.216  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:18.219  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.258  7204  7204 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-12 18:15:18.258  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,09-12 18:15:18.258  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-12 18:15:18.262  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=206798  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 18:15:18.262  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=206798  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 18:15:18.265  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-12 18:15:18.265  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-12 18:15:18.266  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:18.266  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 18:15:18.268  7204  7204 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:15:18.268  7204  7204 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 18:15:18.269  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:18.269  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 18:15:18.269  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-12 18:15:18.269  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:15:18.269  1033  7213 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:15:18.269  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-12 18:15:18.269  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 18:15:18.269  1033  7213 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 18:15:18.269  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:18.269  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-12 18:15:18.292  1033  1597 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7278 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 18:15:18.300  1033  1597 I ActivityManager: Killing 2181:com.lge.music/u0a34 (adj 15): empty #17
,09-12 18:15:18.330   322  4265 V AudioFlinger: 2181 died, releasing its sessions
09-12 18:15:18.330   322  4265 V AudioFlinger:  pid 1879 @ 0
09-12 18:15:18.330   322  4265 V AudioFlinger:  pid 3329 @ 1
09-12 18:15:18.330   322  4265 V AudioFlinger:  pid 3329 @ 2
,09-12 18:15:18.356  1033  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.356  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:15:18.356  1033  1535 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.361  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 18:15:18.361  1033  1764 W libprocessgroup: failed to open /acct/uid_10034/pid_2181/cgroup.procs: No such file or directory
09-12 18:15:18.362  1033  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206898
09-12 18:15:18.362  1033  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206898
09-12 18:15:18.363  1033  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206899
09-12 18:15:18.363  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206900
09-12 18:15:18.364  1033  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=206900
09-12 18:15:18.365  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206901  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 18:15:18.379  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:18.379  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,09-12 18:15:18.382  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.382  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:18.385  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.385  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.385  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 18:15:18.386  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.386  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=206922  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 18:15:18.386  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=206922  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 18:15:18.387  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=206923  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 18:15:18.388  1033  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206924
09-12 18:15:18.388  1033  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=206924
09-12 18:15:18.389  1033  1536 D WifiNative-wlan0: doString: [STATUS]
09-12 18:15:18.390  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:18.390  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 18:15:18.390  1033  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 18:15:18.391  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.393  1033  1536 I WifiServiceExtension: setVHTCapabilityType  : false
09-12 18:15:18.394  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.394  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,09-12 18:15:18.407  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.407  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:18.408  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:18.411  7278  7278 I art     : Almond Protected OAT
09-12 18:15:18.463  7278  7278 D WeatherApplication: removeAccount
,09-12 18:15:18.464  7278  7278 D WeatherApplication: Account.length = 0
09-12 18:15:18.464  7278  7278 E WeatherApplication: OPERATOR:OPEN
09-12 18:15:18.470  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:18
09-12 18:15:18.481  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 18:15:18.481  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
,09-12 18:15:18.484  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 18:15:18.487  7278  7278 D WeatherAncestor: connectivity changed - connection : true
09-12 18:15:18.488  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:null
09-12 18:15:18.496  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-12 18:15:18.496  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 18:15:18.496  7278  7278 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
09-12 18:15:18.510  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 18:15:18.510  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:18
,09-12 18:15:18.579  1033  2000 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7302 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:15:18.581  1033  2000 I ActivityManager: Killing 6523:com.android.vending/u0a44 (adj 15): empty #17
09-12 18:15:18.716  1033  1764 W libprocessgroup: failed to open /acct/uid_10044/pid_6523/cgroup.procs: No such file or directory
,09-12 18:15:18.722  1033  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-12 18:15:18.722  1033  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
09-12 18:15:18.736  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.736  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:18.737  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:18.747  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.747  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.747  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,09-12 18:15:18.751  1033  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,09-12 18:15:18.751  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:15:18.751  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 18:15:18.752  1033  1542 D ConnectivityService: Got NetworkAgent Messenger
09-12 18:15:18.752  1033  1542 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-12 18:15:18.752  1033  1542 D ConnectivityService: NetworkAgent connected
09-12 18:15:18.753  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 18:15:18.753  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 18:15:18.762  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 18:15:18.762  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:15:18.762  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 18:15:18.762  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 18:15:18.762  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-12 18:15:18.766  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.766  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.766  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 18:15:18.766  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 18:15:18.768   318   893 D CommandListener: Setting iface cfg
09-12 18:15:18.770  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.770  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:18.771  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.772  1033  1536 E WifiStateMachine: Start Dhcp Watchdog 2
09-12 18:15:18.773  1033  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=207309  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:18.774  1033  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=207310  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:18.774  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=207310  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:18.775  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:18.775  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:18.776  1033  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:18.776  1033  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:18.777  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:18.777  1033  7326 D DhcpStateMachine: StoppedState
09-12 18:15:18.777  1033  7326 D DhcpStateMachine: StoppedState{ when=-6ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.778  1033  7326 D DhcpStateMachine: WaitBeforeStartState
09-12 18:15:18.778  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,09-12 18:15:18.779  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:18.779  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-12 18:15:18.781  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:18.781  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-12 18:15:18.782  1033  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=207318  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:18.783  1033  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=207319  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:18.783  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=207319  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:18.784  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 18:15:18.784  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 18:15:18.785  1033  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 18:15:18.785  1033  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 18:15:18.786  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 18:15:18.786  1033  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
09-12 18:15:18.787  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:160925] from screen [on:0 period:523136259] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 18:15:18.789  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:523136261] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 18:15:18.789  1033  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
09-12 18:15:18.795  1033  1542 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-12 18:15:18.795  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.796  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.796  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-12 18:15:18.797  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.797  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.797  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.798  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.798  1033  1542 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 18:15:18.799  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:18.799  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
09-12 18:15:18.799  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 18:15:18.799  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=119,0,0
09-12 18:15:18.802  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-12 18:15:18.803  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
09-12 18:15:18.803  1033  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-12 18:15:18.803  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 0
09-12 18:15:18.803  1033  1536 D WifiNative-wlan0: SET ps 0: returned true
09-12 18:15:18.803  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-12 18:15:18.804  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-12 18:15:18.804  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-12 18:15:18.804  1033  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-12 18:15:18.804  1033  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 18:15:18.804  1033  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 18:15:18.805  1033  1535 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@98ac50e target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.805  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@98ac50e target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.805  1033  7326 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.805  1033  7326 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-12 18:15:18.805   318   893 D CommandListener: Setting iface cfg
09-12 18:15:18.806   318   893 D CommandListener: Trying to bring up wlan0
09-12 18:15:18.808  1033  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-12 18:15:18.808  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.809  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.809  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:18.809  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 18:15:18.810  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.810  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,09-12 18:15:18.815  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.815  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:18.816  1033  1542 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 18:15:18.816  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-12 18:15:18.817  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-12 18:15:18.817  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.817  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.818  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 18:15:18.818  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 18:15:18.818  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 18:15:18.818  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-12 18:15:18.819  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-12 18:15:18.819  1033  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-12 18:15:18.819  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 18:15:18.835  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
09-12 18:15:18.836  1033  1542 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
09-12 18:15:18.836  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,09-12 18:15:18.837  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 18:15:18.837  1033  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 18:15:18.837  1033  1542 D ConnectivityService: ignoring duplicate network state non-change
09-12 18:15:18.840  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.840  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:18.842  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.842  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.842  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.842  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 18:15:18.845  1033  1542 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 18:15:18.847  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.847  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.847  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 18:15:18.848  1033  1542 D ConnectivityService: Adding iface wlan0 to network 101
09-12 18:15:18.849  1033  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 18:15:18.860  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 18:15:18.863  1967  1967 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-12 18:15:18.864  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.864  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:18.867  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.867  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.867  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 18:15:18.869  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 18:15:18.870  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.874  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.874  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 18:15:18.874  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.876  1033  1542 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 18:15:18.876  1033  1542 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-12 18:15:18.877  1033  1542 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 18:15:18.877  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:18.877  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:15:18.877  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 18:15:18.878   318   893 E Netd    : netlink response contains error (File exists)
09-12 18:15:18.878  1033  1542 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-12 18:15:18.879  1033  1542 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-12 18:15:18.880  1033  1542 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
09-12 18:15:18.880  1033  1542 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-12 18:15:18.881  1033  1542 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 18:15:18.881  1033  1542 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 18:15:18.881  1033  1542 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-12 18:15:18.881  1033  1542 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-12 18:15:18.881  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.881  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
,09-12 18:15:18.881  1033  1542 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:18.881  1033  1542 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:18.881  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:18.881  1033  1542 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 18:15:18.881  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 18:15:18.881  1033  1542 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:18.881  1033  1542 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-12 18:15:18.881  1033  1542 D ConnectivityService: currentScore = 0, newScore = 20
09-12 18:15:18.881  1033  1542 D ConnectivityService:    accepting network in place of null
09-12 18:15:18.881  1033  1542 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:18.882  1033  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:18.882  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:18.883  1879  1879 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:18.883  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 18:15:18.885  1033  1542 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 18:15:18.886  1033  1542 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 18:15:18.886  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 18:15:18.886  1033  1542 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:18.886  1033  1542 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-12 18:15:18.887  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-12 18:15:18.887  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 18:15:18.887  1033  1542 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: fal,se]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-12 18:15:18.889  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 18:15:18.889  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 18:15:18.889  1033  1542 D ConnectivityService: validation of new default Network = false
09-12 18:15:18.889  1033  1542 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-12 18:15:18.889  1033  1542 D DSQN    : enableDataServiceNotify 
09-12 18:15:18.889  1033  1542 D DSQN    : start dsqn bin
09-12 18:15:18.890   318  7341 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,09-12 18:15:18.884  7343  7343 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:18.884  7343  7343 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:18.898  1033  1542 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-12 18:15:18.898  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:18.898  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:18.899  1033  1542 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:18.900  1603  1812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 18:15:18.908  1033  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-12 18:15:18.912  7343  7343 E DSQN    : DSQN ssw
09-12 18:15:18.912  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:18.912  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 18:15:18.912  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.921  1840  7345 I CheckinService: active receiver: enabled
,09-12 18:15:18.929  1840  7345 I CheckinService: Preparing to send checkin request
09-12 18:15:18.929  1840  7345 I EventLogService: Accumulating logs since 1473696753678
09-12 18:15:18.934   278   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 18:15:18.935   278   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
09-12 18:15:18.935   278   340 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 18:15:18.935  7302  7349 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-12 18:15:18.936  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 18:15:18.937   278   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 18:15:18.937   278   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-12 18:15:18.937   278   340 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 18:15:18.937  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.938  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:18.940  7302  7349 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-12 18:15:18.945   318  7341 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
09-12 18:15:18.948   278   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 18:15:18.949   278   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,09-12 18:15:18.949   278   340 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 18:15:18.949  7302  7354 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,09-12 18:15:18.951   278   340 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
09-12 18:15:18.951   278   340 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
09-12 18:15:18.951   278   340 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 18:15:18.951  7302  7354 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
09-12 18:15:18.964  1840  7345 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,09-12 18:15:18.982   318  7341 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-12 18:15:19.006   318   892 D LGDataListener: argv[0]=dsqncommand
09-12 18:15:19.006   318   892 D LGDataListener: argv[1]=wlan0
09-12 18:15:19.006   318   892 D LGDataListener: argv[2]=1
09-12 18:15:19.006   318   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-12 18:15:19.007  1033  1093 D DSQN    : DSQM DsqnNotification wlan0  1
09-12 18:15:19.007  1033  1093 D DSQN    : start to monitor internet connection
,09-12 18:15:19.010  1033  7326 D DhcpStateMachine: DHCPV4 request on wlan0
09-12 18:15:19.010  1033  7326 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-12 18:15:19.010  1033  7326 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-12 18:15:19.004  7359  7359 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:19.004  7359  7359 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:19.017  7359  7359 I dhcpcd  : version 5.5.6 starting
09-12 18:15:19.018  7359  7359 E dhcpcd  : get_duid: m
09-12 18:15:19.018  7359  7359 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-12 18:15:19.018  7359  7359 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-12 18:15:19.035  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 16:15:19 GMT], X-Android-Received-Millis=[1473696919034], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473696919005]}
09-12 18:15:19.035  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 18:15:19.035  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-12 18:15:19.035  1033  1542 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
09-12 18:15:19.035  1033  1542 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
09-12 18:15:19.036  1033  1542 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:19.036  1033  1542 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:19.036  1033  1542 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 18:15:19.036  1033  1542 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
09-12 18:15:19.036  1033  1542 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
09-12 18:15:19.036  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.036  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:19.037  1033  1542 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:19.037  1033  1542 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.037  1603  1812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 18:15:19.037  1033  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.037  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:19.037  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 18:15:19.038  1879  1879 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.038  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 18:15:19.078  7359  7359 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 18:15:19.078  7359  7359 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 18:15:19.078  7359  7359 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 18:15:19.079  7359  7359 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-12 18:15:19.080  7359  7359 D dhcpcd  : wlan0: sending REQUEST (xid 0xbe99b046), next in 4.73 seconds
,09-12 18:15:19.094  1033  2089 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7377 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,09-12 18:15:19.108  7359  7359 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,09-12 18:15:19.133  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 18:15:19.134  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.135  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.140  7359  7359 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-12 18:15:19.140  7359  7359 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-12 18:15:19.140  7359  7359 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-12 18:15:19.140  7359  7359 D dhcpcd  : wlan0: adding default route via 192.168.1.1
09-12 18:15:19.140  7359  7359 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 18:15:19.141  7359  7359 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 18:15:19.141  7359  7359 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 18:15:19.141  7359  7359 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
09-12 18:15:19.179  7377  7377 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-12 18:15:19.179  7377  7377 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 18:15:19.210  7377  7377 I MultiDex: VM with version 2.1.0 has multidex support
,09-12 18:15:19.210  7377  7377 I MultiDex: install
09-12 18:15:19.211  7377  7377 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-12 18:15:19.219  7302  7302 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
09-12 18:15:19.220  7377  7377 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
09-12 18:15:19.226  7302  7302 I LibraryLoader: Loading: webviewchromium
09-12 18:15:19.229  7302  7302 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7776-7779)
09-12 18:15:19.229  7302  7302 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:15:19.233  7302  7302 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d7fe5e3}
09-12 18:15:19.234  7302  7302 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 18:15:19.235  7302  7302 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 18:15:19.242  7302  7302 I BrowserStartupController: Initializing chromium process, renderers=0
09-12 18:15:19.243  7302  7302 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 18:15:19.253   322  1384 V AudioPolicyService: registerClient() client 0xb1023c40, uid 10093
,09-12 18:15:19.254  7302  7414 W AudioManagerAndroid: Requires BLUETOOTH permission
09-12 18:15:19.257  7302  7302 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
09-12 18:15:19.257  7302  7302 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
09-12 18:15:19.258  7302  7302 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
09-12 18:15:19.264  7302  7302 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 18:15:19.264  7302  7302 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 18:15:19.264  7302  7302 I Adreno-EGL: Build Date: 12/12/14 금
09-12 18:15:19.264  7302  7302 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 18:15:19.264  7302  7302 I Adreno-EGL: Remote Branch: 
09-12 18:15:19.264  7302  7302 I Adreno-EGL: Local Patches: 
09-12 18:15:19.264  7302  7302 I Adreno-EGL: Reconstruct Branch: 
,09-12 18:15:19.313  7302  7302 I NSApplication: Starting up...
,09-12 18:15:19.356  1033  2057 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7434 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-12 18:15:19.358  1033  2057 I ActivityManager: Killing 6882:com.lge.clock/u0a10 (adj 15): empty #17
09-12 18:15:19.391  1033  1764 W libprocessgroup: failed to open /acct/uid_10010/pid_6882/cgroup.procs: No such file or directory
,09-12 18:15:19.403  1033  1764 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 18:15:19.403  1033  1764 D WifiService: setWifiEnabled: false pid=6817, uid=10118
,09-12 18:15:19.403  1033  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 18:15:19.411  7434  7434 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:15:19.412  1033  7326 D DhcpStateMachine: DHCPV4 succeeded on wlan0
09-12 18:15:19.412  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 18:15:19.412  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 18:15:19.412  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-12 18:15:19.413  1033  7326 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-12 18:15:19.413  1033  7326 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 18:15:19.413  1033  7326 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
09-12 18:15:19.413  1033  7326 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-12 18:15:19.413  1033  7326 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 18:15:19.413  1033  7326 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-12 18:15:19.413  1033  7326 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
09-12 18:15:19.413  1033  7326 D DhcpStateMachine: RunningState
09-12 18:15:19.414  1033  1536 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:19.414  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:19.414  1033  1536 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:19.415  1033  1536 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:19.415  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
09-12 18:15:19.415  1033  1536 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 18:15:19.415  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:15:19.415  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 18:15:19.416  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 18:15:19.416  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-12 18:15:19.423  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 18:15:19.423  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 18:15:19.423  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 18:15:19.423  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.423  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.424  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 18:15:19.424  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 18:15:19.424  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
09-12 18:15:19.424  1033  7326 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.424   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:15:19.450  1033  1542 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 18:15:19.450  1033  1542 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,09-12 18:15:19.461  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:19.461  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:19.461  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:19.462  1033  1536 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 18:15:19.462  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:19.462  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:19.463  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:19.465  1033  1535 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.465  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-12 18:15:19.465  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:19.466  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:19.466  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 18:15:19.467  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:19.467  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:19.468  1967  1967 V WfdStateTracker: handleWifiStateChangedEvent: 0
09-12 18:15:19.469  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.472  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.472  1033  1535 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2bd332f6
09-12 18:15:19.473  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-12 18:15:19.474  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:19.474  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:19.474  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 18:15:19.474  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 18:15:19.474  1033  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.474  1033  1033 D RttService: SCAN_AVAILABLE : 1
09-12 18:15:19.474  1033  1555 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.475  1033  1535 D LGWifiP2pService: P2pDisablingState
09-12 18:15:19.475  1033  1535 D LGWifiP2pService: P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.475  1033  1535 D LGWifiP2pService: p2p socket connection lost
09-12 18:15:19.475  1033  1535 D LGWifiP2pService: P2pDisabledState
,09-12 18:15:19.475  1033  1536 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
09-12 18:15:19.475  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
09-12 18:15:19.475  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.475  1033  1535 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.476  7204  7204 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
09-12 18:15:19.476  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 18:15:19.476  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 18:15:19.476  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
09-12 18:15:19.476  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 18:15:19.476  1967  1967 D WfdsService: WifiP2pState is changed : false
09-12 18:15:19.477  1967  2347 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
09-12 18:15:19.479  1967  2347 D WfdsService: Set the WFDS Monitor: false
09-12 18:15:19.480  1967  2347 D WfdsMonitor: WFDS Monitor is stopped
09-12 18:15:19.480  1967  2347 D WfdsService: STATE : WfdsDisabledState - enter
09-12 18:15:19.480  1967  7227 D CtrlSupplicant: Received on exit socket, terminate
09-12 18:15:19.480  1967  7227 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
09-12 18:15:19.481  1967  7227 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
09-12 18:15:19.481  1967  7227 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
09-12 18:15:19.481  1967  2349 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
09-12 18:15:19.481  1967  2347 W WfdsService: DefaultState - msg [9445378] is not handled
09-12 18:15:19.491   318   893 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:15:19.492  1033  1542 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-12 18:15:19.492  1033  1542 D DSQN    : disableDataServiceNotify
,09-12 18:15:19.492  1033  1542 D DSQN    : stop dsqn bin
09-12 18:15:19.493  1033  1536 D WifiNative-p2p0: doBoolean: TERMINATE
09-12 18:15:19.493  1033  1536 D WifiNative-p2p0: TERMINATE: returned true
09-12 18:15:19.493  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 18:15:19.493  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
09-12 18:15:19.493  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 18:15:19.494  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:19.494  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:19.496  1033  1033 D WifiHS20: hidePasspointNotification off =false
09-12 18:15:19.496  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:19.496  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:19.497  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 18:15:19.497  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
09-12 18:15:19.497  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:19.497  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-12 18:15:19.498  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.498  1033  1542 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-12 18:15:19.498  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.498  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:19.498  1033  1542 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:19.499  1603  1812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 18:15:19.499  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
09-12 18:15:19.500  1033  1542 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-12 18:15:19.500  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:19.500  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:19.500  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:19.500  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:19.500  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:19.500  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:19.500  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:19.500  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:19.500  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:19.500  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:19.500  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE,, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:19.500  1033  1542 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-12 18:15:19.500  1033  1542 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 18:15:19.501  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 18:15:19.501  1033  1542 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:19.501  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 18:15:19.501  1033  1542 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:19.501  1033  1542 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.501  1033  1542 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.501  1033  1536 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.501  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:19.502  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.502  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.502  1033  7325 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 18:15:19.502  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:19.502  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:19.502  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:19.502  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:19.502  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:19.502  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:19.502  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:19.502  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:19.502  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:19.502  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the chec,k when the Bluetooth is disabled - will return stored value
09-12 18:15:19.502  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:19.502  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 18:15:19.502  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:19.503  1033  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 18:15:19.503  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.504  1033  1534 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-12 18:15:19.504  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 18:15:19.504  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
09-12 18:15:19.504  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 18:15:19.504  1033  1542 D NetworkManagementService: Removing idletimer
09-12 18:15:19.504  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 18:15:19.504  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 18:15:19.504  1033  1542 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:19.504  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 18:15:19.504  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 18:15:19.504  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 18:15:19.504  1033  1542 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 18:15:19.505  1879  1879 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:19.505  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 18:15:19.505  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.510  7458  7458 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
09-12 18:15:19.542  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-12 18:15:19.542  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.543  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.546  7458  7458 I dex2oat : dex2oat took 35.522ms (threads: 4)
09-12 18:15:19.555  7377  7394 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 18:15:19.555  7377  7394 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 18:15:19.555  7377  7394 I Adreno-EGL: Build Date: 12/12/14 금
09-12 18:15:19.555  7377  7394 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 18:15:19.555  7377  7394 I Adreno-EGL: Remote Branch: 
09-12 18:15:19.555  7377  7394 I Adreno-EGL: Local Patches: 
09-12 18:15:19.555  7377  7394 I Adreno-EGL: Reconstruct Branch: 
09-12 18:15:19.555  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 18:15:19.556  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.556  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.600  7204  7204 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 18:15:19.600  7204  7204 I wpa_supplicant: monitor socket send errors count : 1
09-12 18:15:19.600  7204  7204 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1967-4\x00 that cannot receive messages
,09-12 18:15:19.602  1033  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
09-12 18:15:19.602  1033  7213 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 18:15:19.622  7204  7204 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 18:15:19.623  1033  1095 D Tethering: InitialState.processMessage what=4
09-12 18:15:19.624  7204  7204 W wpa_supplicant: USIM:  scard_deinit function
09-12 18:15:19.624  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:15:19.627  1033  1536 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,09-12 18:15:19.627  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:19.627  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
09-12 18:15:19.627  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 18:15:19.627  1033  7213 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 18:15:19.628  1033  7213 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
09-12 18:15:19.628  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:19.628  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 18:15:19.629  1033  1536 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=208165
09-12 18:15:19.631  1033  1536 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=208167
09-12 18:15:19.632  1033  1536 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=208168  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 18:15:19.633  1033  1536 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=208169  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
09-12 18:15:19.634  1033  7326 D DhcpStateMachine: StoppedState
09-12 18:15:19.634  1033  7326 D DhcpStateMachine: StoppedState{ when=-158ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:19.635  1033  1536 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
09-12 18:15:19.635  7377  7394 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:19.635  7377  7394 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 18:15:19.636  1033  1536 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,09-12 18:15:19.680  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-12 18:15:19.682  6322  6976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 18:15:19.704  2222  2222 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:19.717  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 18:15:19.717  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:19.718  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 18:15:19.718  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-12 18:15:19.720  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
09-12 18:15:19.730  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1dc9fc98
,09-12 18:15:19.730  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 18:15:19.730  7151  7151 D AppUp4:CustFacade: isPhone : true
,09-12 18:15:19.731  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-12 18:15:19.732  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 18:15:19.735  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:19.736  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:19.737  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:19.739  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:19.744  7179  7179 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-12 18:15:19.746  4615  7474 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 18:15:19.751  4615  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:19.752  4615  7475 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 18:15:19.752  7204  7204 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-12 18:15:19.755  7377  7394 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 18:15:19.755  7377  7394 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 18:15:19.755  7377  7394 I Adreno-EGL: Build Date: 12/12/14 금
09-12 18:15:19.755  7377  7394 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 18:15:19.755  7377  7394 I Adreno-EGL: Remote Branch: 
09-12 18:15:19.755  7377  7394 I Adreno-EGL: Local Patches: 
09-12 18:15:19.755  7377  7394 I Adreno-EGL: Reconstruct Branch: 
09-12 18:15:19.755  1033  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,09-12 18:15:19.756  1033  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
09-12 18:15:19.756  1033  7213 D WifiMonitor: Disconnecting from the supplicant, no more events
09-12 18:15:19.760  1033  1536 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
,09-12 18:15:19.782  3329  3329 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 18:15:19.783  7061  7479 W FormManager: Network not available. Please check & try again.
09-12 18:15:19.784  3329  3329 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:19.784  3329  3329 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 18:15:19.784  7179  7476 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:15:19.788  7218  7218 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 18:15:19.788  7218  7218 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 18:15:19.791  7061  7480 V FormManager: Network unavailable.
09-12 18:15:19.805  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:19
,09-12 18:15:19.807  7377  7394 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 18:15:19.807  7377  7394 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 18:15:19.807  7377  7394 I Adreno-EGL: Build Date: 12/12/14 금
09-12 18:15:19.807  7377  7394 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 18:15:19.807  7377  7394 I Adreno-EGL: Remote Branch: 
09-12 18:15:19.807  7377  7394 I Adreno-EGL: Local Patches: 
09-12 18:15:19.807  7377  7394 I Adreno-EGL: Reconstruct Branch: 
09-12 18:15:19.807  7061  7480 V FormManager: Network unavailable.
09-12 18:15:19.808  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 18:15:19.808  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
09-12 18:15:19.808  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 18:15:19.808  7278  7278 D WeatherAncestor: connectivity changed - connection : true
09-12 18:15:19.808  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15d820d6
09-12 18:15:19.809  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 18:15:19.809  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 18:15:19.809  7278  7278 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 18:15:19.809  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 18:15:19.809  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:19
09-12 18:15:19.831  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 18:15:19.831  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,09-12 18:15:19.831  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 18:15:19.831  6931  6931 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 18:15:19.831  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 18:15:19.832  6931  6931 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 18:15:19.832  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 18:15:19.832  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 18:15:19.832  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 18:15:19.832  6931  6931 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 18:15:19.832  6931  6931 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 18:15:19.840  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:19.842  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:15:19.848  7061  7483 W FormManager: Network not available. Please check & try again.
09-12 18:15:19.851  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:19.858  7061  7484 V FormManager: Network unavailable.
,09-12 18:15:19.862  1033  1536 D WifiOffDelayIfNotUsed: stopMonitoring
09-12 18:15:19.862  1967  1967 D WfdsService: Supplicant Connection state is changed : false
09-12 18:15:19.862  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 18:15:19.862  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
09-12 18:15:19.862  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 18:15:19.862  1967  2347 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
09-12 18:15:19.862  1967  2347 D WfdsService: Set the WFDS Monitor: false
09-12 18:15:19.862  1967  2347 D WfdsMonitor: WFDS Monitor is stopped
09-12 18:15:19.865  7061  7484 V FormManager: Network unavailable.
09-12 18:15:19.867  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
09-12 18:15:19.867  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:19.867  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
09-12 18:15:19.868  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:19.868  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:19.868  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:19.868  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:19.868  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:19.868  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:19.868  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:19.868  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:19.868  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:19.868  2508  2508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:19.869  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:19.869  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:19.869  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:19.869  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:19.869  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:19.869  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:19.869  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:19.869  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:19.869  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:19.869  1033  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
09-12 18:15:19.869  1033  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
09-12 18:15:19.870  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 18:15:19.873  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 18:15:19.876  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:19.884  7061  7485 W FormManager: Network not available. Please check & try again.
,09-12 18:15:19.884  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 18:15:19.885  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:19.886  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:19.890  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:19.890  7061  7486 V FormManager: Network unavailable.
09-12 18:15:19.893  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:19.895  4615  7487 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-12 18:15:19.897  7061  7486 V FormManager: Network unavailable.
09-12 18:15:19.899  1033  1542 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
09-12 18:15:19.900  4615  7488 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 18:15:19.900  4615  7488 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 18:15:19.900  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:19.922  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:19.930  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:19.931  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 18:15:19.932  7011  7011 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 18:15:19.985  1033  1048 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7489 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-12 18:15:20.011   318  7507 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,09-12 18:15:20.011  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
09-12 18:15:20.012  1840  7345 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-12 18:15:20.032  1840  7345 I CheckinService: active receiver: disabled
09-12 18:15:20.128  7489  7489 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 18:15:20.129  7489  7489 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-12 18:15:20.139  7489  7489 V [BNRBootReceiver]: Boot Receiver Return
09-12 18:15:20.139  7489  7489 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-12 18:15:20.147  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:20.156  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.169  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.183  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:20.184  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 18:15:20.187  7011  7011 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 18:15:20.191  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
09-12 18:15:20.195  6931  6931 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,09-12 18:15:20.202  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:20.212  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.220  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.228  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:20.229  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.231  7011  7011 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 18:15:20.238  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:20.255  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.265  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.276  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:20.277  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.278  7011  7011 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 18:15:20.284  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:20.297  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.307  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.319  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:20.320  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.321  7011  7011 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:20.328  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:20.346  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.357  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.365  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:20.366  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 18:15:20.367  7011  7011 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:20.374  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:20.386  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.396  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.402  6693  7131 D UEI.SmartControl: Internal timer expired: 2
09-12 18:15:20.402  6693  7131 D UEI.SmartControl: unbind internal service
,09-12 18:15:20.406  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:20.407  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.408  7011  7011 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:20.420  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:20.444  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.455  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.456  6693  7128 D serial_port: close(fd = 24)
,09-12 18:15:20.461  6693  7128 I UEI.SmartControl: Serial port is closed.
,09-12 18:15:20.469  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:20.470  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.479  7011  7011 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:20.488  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:20.510  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.520  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.541  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:20.541  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.543  7011  7011 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:20.552  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:20.560  6977  6977 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-12 18:15:20.574  1033  1541 D WifiService: New client listening to asynchronous messages
,09-12 18:15:20.575  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:20.580  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.586  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.595  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:20.595  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.597  7011  7011 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 18:15:20.599  7011  7011 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 18:15:20.599  7011  7011 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 18:15:20.607  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:20.612  6977  6977 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-12 18:15:20.616  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:20.619  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.627  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.635  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:20.635  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.636  7011  7011 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 18:15:20.637  7011  7011 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 18:15:20.638  7011  7011 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,09-12 18:15:20.642  1033  1964 I ActivityManager: Killing 6956:com.lge.lifetracker/u0a37 (adj 15): empty #17
09-12 18:15:20.672  1033  2112 W libprocessgroup: failed to open /acct/uid_10037/pid_6956/cgroup.procs: No such file or directory
,09-12 18:15:20.677  2222  2222 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-12 18:15:20.692  2222  2222 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-12 18:15:20.693  2222  2222 D c       : Getting all permits...
09-12 18:15:20.693  2222  2222 D a       : Opening database...
09-12 18:15:20.698  2222  2222 D a       : Opening database auth.proximity.permit_store...
09-12 18:15:20.699  2222  2222 D a       : Closing database...
09-12 18:15:20.711  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:20.718  6977  6977 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 18:15:20.718  6977  6977 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 18:15:20.718  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:20.722  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.729  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.737  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:20.738  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 18:15:20.740  7011  7011 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 18:15:20.744  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:20.747  6977  6977 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 18:15:20.747  6977  6977 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 18:15:20.747  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:20.753  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.761  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.769  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:20.771  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.773  7011  7011 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 18:15:20.777  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:20.781  6977  6977 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
09-12 18:15:20.781  6977  6977 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 18:15:20.782  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:20.786  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:20.794  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.799  7011  7011 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:20.800  7011  7011 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:20.802  7011  7011 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,09-12 18:15:20.810  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 18:15:20.815  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:15:20.824  7061  7519 W FormManager: Network not available. Please check & try again.
09-12 18:15:20.824  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.829  7061  7520 V FormManager: Network unavailable.
,09-12 18:15:20.840  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 18:15:20.841  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:20.843  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:20.845  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 18:15:20.847  7061  7520 V FormManager: Network unavailable.
09-12 18:15:20.852  6977  6977 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
09-12 18:15:20.852  6977  6977 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
09-12 18:15:20.852  6977  6977 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:20.856  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:15:20.862  4615  7521 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 18:15:20.864  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:20.868  4615  7524 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 18:15:20.868  4615  7524 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 18:15:20.878  7061  7522 W FormManager: Network not available. Please check & try again.
,09-12 18:15:20.881  7061  7523 V FormManager: Network unavailable.
09-12 18:15:20.885  7061  7523 V FormManager: Network unavailable.
09-12 18:15:20.886  2222  2222 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
09-12 18:15:21.798  1033  1536 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:523139270] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-12 18:15:21.808  1033  1536 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:523139280] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 18:15:21.891  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:21.902  1033  1095 D Tethering: MasterInitialState.processMessage what=3
09-12 18:15:21.909  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:21.912  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:21.916  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:21.918  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-12 18:15:21.920  6322  6976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 18:15:21.932  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-12 18:15:21.952  2222  2222 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:21.980  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 18:15:21.980  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:21.980  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 18:15:21.981  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,09-12 18:15:21.985  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
09-12 18:15:21.989  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1dc9fc98
09-12 18:15:21.989  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 18:15:21.989  7151  7151 D AppUp4:CustFacade: isPhone : true
09-12 18:15:21.990  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-12 18:15:21.990  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 18:15:21.995  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:21.995  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:21.996  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,09-12 18:15:22.002  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:22.012  4615  7528 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-12 18:15:22.023  4615  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.023  4615  7529 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 18:15:22.054  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 18:15:22.074  7179  7179 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,09-12 18:15:22.096  3329  3329 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 18:15:22.096  3329  3329 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.096  3329  3329 I LgeMiscReceiver: networkInfo.isConnected() = true
09-12 18:15:22.096  3329  3329 D PhoneState: setPdpRejectCasuse : false
,09-12 18:15:22.098  7179  7546 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:22.099  7061  7549 W FormManager: Network not available. Please check & try again.
09-12 18:15:22.102  7218  7218 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 18:15:22.102  7218  7218 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 18:15:22.105  7061  7550 V FormManager: Network unavailable.
09-12 18:15:22.116  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:22
,09-12 18:15:22.118  7061  7550 V FormManager: Network unavailable.
,09-12 18:15:22.118  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 18:15:22.118  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
,09-12 18:15:22.119  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 18:15:22.119  7278  7278 D WeatherAncestor: connectivity changed - connection : true
09-12 18:15:22.119  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15d820d6
09-12 18:15:22.120  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,09-12 18:15:22.120  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 18:15:22.120  7278  7278 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 18:15:22.120  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 18:15:22.120  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:22
,09-12 18:15:22.414  1033  1764 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:22.415  1033  1764 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-12 18:15:22.434  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-12 18:15:22.435  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,09-12 18:15:22.435  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-12 18:15:22.435  1033  1095 D BluetoothManagerService: Message: 1
09-12 18:15:22.435  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-12 18:15:22.458  1033  1095 D BluetoothManagerService: Message: 20
09-12 18:15:22.458  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8499cc9:true
09-12 18:15:22.459  7084  7084 D BluetoothAdapterState: make
,09-12 18:15:22.466  7084  7084 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-12 18:15:22.466  7084  7084 I bluedroid-qcom: init
09-12 18:15:22.467  7084  7559 I BluetoothAdapterState: Entering OffState
09-12 18:15:22.469  7084  7084 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 18:15:22.470  7084  7084 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 18:15:22.470  7084  7084 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 18:15:22.470  7084  7084 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 18:15:22.470  7084  7084 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-12 18:15:22.472  7084  7084 I bluedroid-qcom: get_profile_interface socket
09-12 18:15:22.472  7084  7084 I bluedroid-qcom: get_profile_interface map_client
09-12 18:15:22.464  7563  7563 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:22.464  7563  7563 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:22.476  7084  7562 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-12 18:15:22.483  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-12 18:15:22.483  1033  1095 D BluetoothManagerService: Message: 40
09-12 18:15:22.483  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-12 18:15:22.484  7084  7102 I bluedroid-qcom: config_hci_snoop_log
09-12 18:15:22.486  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-12 18:15:22.486  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-12 18:15:22.488  7084  7562 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-12 18:15:22.489  7563  7563 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-12 18:15:22.489  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 18:15:22.489  7563  7563 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-12 18:15:22.489  7563  7563 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-12 18:15:22.490  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-12 18:15:22.490  7084  7562 D BluetoothAdapterProperties: Name is: G3
09-12 18:15:22.492  7563  7563 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-12 18:15:22.497  7084  7559 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-12 18:15:22.498  7084  7559 D BluetoothAdapterProperties: Setting state to 11
09-12 18:15:22.498  7084  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 18:15:22.500  1033  1095 D BluetoothManagerService: Message: 60
09-12 18:15:22.500  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-12 18:15:22.500  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-12 18:15:22.500  7563  7563 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-12 18:15:22.500  7563  7563 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-12 18:15:22.502  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.502  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:22.504  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 18:15:22.505  6931  6931 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
09-12 18:15:22.506  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:22.508  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.510  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:22.511  7084  7559 I LGBluetoothServiceJni: classInitNative: succeeds
09-12 18:15:22.515  7084  7084 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 18:15:22.516  7084  7084 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:22.516  7084  7084 V BluetoothPbapReceiver: ***********state = 11
09-12 18:15:22.517  1033  1095 D Tethering: MasterInitialState.processMessage what=3
09-12 18:15:22.526  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:22.528  1033  1095 D Tethering: MasterInitialState.processMessage what=3
09-12 18:15:22.529  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:22.530  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:22.540  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,09-12 18:15:22.544  6322  6976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 18:15:22.546  7084  7559 D BluetoothBondStateMachine: make
09-12 18:15:22.547  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:22.547  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:15:22.549  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:22.552  7084  7565 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 18:15:22.552  7084  7559 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:22.552  7084  7559 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-12 18:15:22.553  7084  7559 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:22.553  7084  7559 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
09-12 18:15:22.553  7084  7559 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-12 18:15:22.561  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
09-12 18:15:22.571  7084  7559 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 18:15:22.612  1033  2057 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7576 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,09-12 18:15:22.619  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.619  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:22.620  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:22.620  5765  5765 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,09-12 18:15:22.621  7084  7084 D HeadsetService: Received start request. Starting profile...
09-12 18:15:22.622  7084  7084 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 18:15:22.622  7084  7084 D LGBluetoothHfpAdapter: Version 1.6
09-12 18:15:22.622  7084  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:22.625  7084  7084 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 18:15:22.626  7084  7084 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 18:15:22.627  7084  7084 D HeadsetStateMachine: make
,09-12 18:15:22.630  7084  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:22.640  7084  7559 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 18:15:22.650  7084  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:22.656  2222  2222 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.665  7084  7559 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 18:15:22.668  7084  7084 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:22.669  7084  7084 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 18:15:22.674  7084  7084 D HeadsetStateMachine: max_hf_connections = 1
09-12 18:15:22.674  7084  7084 I bluedroid-qcom: get_profile_interface handsfree
09-12 18:15:22.675  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 18:15:22.676  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.676  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 18:15:22.676  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 18:15:22.676  7084  7084 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-12 18:15:22.677   322  4265 V AudioPolicyService: registerClient() client 0xb558a420, uid 1002
09-12 18:15:22.677   322  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-12 18:15:22.677   322  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 18:15:22.677   322  1384 V AudioPolicyManagerEx: getOutput() returns output 2
,09-12 18:15:22.678  7084  7084 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-12 18:15:22.678   322   322 V AudioFlinger: registerClient() client 0xb5581988, pid 7084
09-12 18:15:22.678   322  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:22.678   322  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:22.678  1603  3416 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:22.678  1603  3416 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:22.678  7084  7103 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:22.678  3329  3345 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:22.679  3329  3345 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:22.679  1879  2442 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:22.679  1879  2442 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:22.679  1033  1764 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:22.679  1033  1764 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:22.679   322  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:22.679   322  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:22.679  7084  7084 V ToneGenerator: Create Track: 0xb4928080
09-12 18:15:22.679  7084  7084 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-12 18:15:22.679  7084  7084 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-12 18:15:22.679  3329  3344 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:22.679  3329  3344 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:22.680   322  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-12 18:15:22.680  1033  2112 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:22.680   322  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-12 18:15:22.680  1033  2112 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:22.680   322  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 18:15:22.680   322  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 18:15:22.680  1879  4264 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:22.680  7084  7084 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-12 18:15:22.680  1879  4264 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:22.680  7084  7103 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-12 18:15:22.680  1603  1939 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:22.680  1603  1939 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:22.682   322  1383 I AudioFlinger: isAudioPlaybackHookOn() false
09-12 18:15:22.682   322  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-12 18:15:22.682   322  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-12 18:15:22.682   322  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 18:15:22.682   322  1384 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 18:15:22.683  7084  7084 V AudioSystem: getLatency() output 2, latency 50
09-12 18:15:22.683  7084  7084 V AudioSystem: getFrameCount() output 2, frameCount 960
09-12 18:15:22.683  7084  7084 V AudioTrack: createTrack_l() output 2 afLatency 50
09-12 18:15:22.683   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-12 18:,15:22.683   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-12 18:15:22.683   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-12 18:15:22.683   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-12 18:15:22.683   322   322 V AudioFlinger: createTrack() lSessionId: 22
09-12 18:15:22.683  7084  7103 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:22.683  7084  7103 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-12 18:15:22.685  7084  7559 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:22.685  7084  7084 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-12 18:15:22.685   322  1383 V AudioFlinger: acquiring 22 from 7084, for 7084
09-12 18:15:22.685   322  1383 V AudioFlinger:  added new entry for 22
09-12 18:15:22.685  7084  7084 V ToneGenerator: ToneGenerator INIT OK, time: 211236
09-12 18:15:22.686  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:22.686  7084  7591 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-12 18:15:22.686  7084  7591 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 18:15:22.686  7084  7591 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 18:15:22.686  7084  7591 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-12 18:15:22.687   322  1384 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7084
09-12 18:15:22.687  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
,09-12 18:15:22.687   322  1384 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-12 18:15:22.687   322  1384 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-12 18:15:22.687   322  1384 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-12 18:15:22.687   322  1384 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-12 18:15:22.687   322  1384 V voice   : voice_set_parameters: exit with code(0)
09-12 18:15:22.687   322  1384 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-12 18:15:22.687   322  1384 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-12 18:15:22.687   322  1384 V msm8974_platform: platform_set_parameters: exit with code(0)
09-12 18:15:22.687   322  1384 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-12 18:15:22.687   322  1384 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-12 18:15:22.687   322  1384 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-12 18:15:22.687  7084  7591 V ToneGenerator: ToneGenerator destructor
09-12 18:15:22.687  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
09-12 18:15:22.687  7084  7591 V ToneGenerator: stopTone
09-12 18:15:22.687  7084  7591 V ToneGenerator: Delete Track: 0xb4928080
09-12 18:15:22.689  7084  7084 D A2dpService: Received start request. Starting profile...
09-12 18:15:22.689  7084  7084 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 18:15:22.691  7084  7084 V Avrcp   : make
09-12 18:15:22.691  7084  7084 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-12 18:15:22.691  7084  7084 I bluedroid-qcom: get_profile_interface avrcp
09-12 18:15:22.692  7084  7591 V AudioTrack: ~AudioTrack, releasing session id from 7084 on behalf of 7084
09-12 18:15:22.692   322  4265 V AudioPolicyService: AudioCommandThread() adding release output 2
09-12 18:15:22.692   322  4265 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-12 18:15:22.692   322  1383 V AudioFlinger: releasing 22 from 7084 for 7084
09-12 18:15:22.692   322  1383 V AudioFlinger:  decremented refcount to 0
09-12 18:15:22.692   322  1383 V AudioFlinger: purging stale effects
09-12 18:15:22.692   322  1258 V AudioPolicyService: AudioCommandThread() waking up
09-12 18:15:22.692   322  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
09-12 18:15:22.692   322  1258 V AudioPolicyManager: releaseOutput() 2
09-12 18:15:22.692   322  1258 V AudioPolicyService: AudioCommandThread() going to sleep
09-12 18:15:22.692   322  4265 V AudioFlinger: PlaybackThread::Track destructor
09-12 18:15:22.692   322  4265 V AudioFlinger: removeClient_l() pid 7084, calling pid 322
09-12 18:15:22.694  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1dc9fc98
09-12 18:15:22.694  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 18:15:22.694  7151  7151 D AppUp4:CustFacade: isPhone : true
09-12 18:15:22.696  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-12 18:15:22.697  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 18:15:22.794  1033  1964 I art     : Explicit concurrent mark sweep GC freed 130332(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.564ms total 106.642ms
,09-12 18:15:22.808  7576  7576 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
09-12 18:15:22.808  7084  7084 V AudioManager: registerRemoteController: size of Media player list: 0
,09-12 18:15:22.808  7576  7576 W LG Account v2.2: No ProfileInfo entries
09-12 18:15:22.809  7084  7084 E AudioManager: No RCC entry present to update
09-12 18:15:22.809  7576  7576 I LG Account v2.2: isEnabled: false
09-12 18:15:22.809  7084  7084 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 18:15:22.809  7576  7576 I Feature : [Lifetracker]ver: 4.21.112(40211120)
09-12 18:15:22.809  7576  7576 I Feature : [Lifetracker]Country: EU
09-12 18:15:22.810  7576  7576 I Feature : [Lifetracker]Operator: OPEN
09-12 18:15:22.811  7084  7084 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
09-12 18:15:22.811  7576  7576 I Feature : [Lifetracker]Ranking support: false
09-12 18:15:22.811  7576  7576 I Feature : [Lifetracker]Comfort support: false
09-12 18:15:22.811  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-12 18:15:22.811  7084  7084 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
09-12 18:15:22.811  7576  7576 I Feature : [Lifetracker]Accessory: true
09-12 18:15:22.812  7576  7576 I Feature : [Lifetracker]Health device: true
09-12 18:15:22.812  7576  7576 I Feature : [Lifetracker]Extra Pedometer: false
09-12 18:15:22.812  7576  7576 I Feature : [Lifetracker]Blood glucose device: false
09-12 18:15:22.812  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.812  7576  7576 I Feature : [Lifetracker]Device Number: 3
09-12 18:15:22.813  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:22.820  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:22.822  7084  7559 V LGMDMManager: Create singleton instance
,09-12 18:15:22.825  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-12 18:15:22.825  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:22.827  7084  7559 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 18:15:22.859  6931  6931 D BluetoothPermissionRequest: onReceive
09-12 18:15:22.861  4615  7601 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,09-12 18:15:22.865  4615  7602 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.865  4615  7602 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 18:15:22.869  7179  7179 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-12 18:15:22.873  6931  6931 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-12 18:15:22.898  7179  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:15:22.907  1033  2020 V SIM_STK : Menu title from STK is T-Mobile
09-12 18:15:22.907  1033  2020 V SIM_STK : Menu title from STK is T-Mobile
09-12 18:15:22.913  7061  7605 W FormManager: Network not available. Please check & try again.
,09-12 18:15:22.917  3329  3329 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 18:15:22.917  3329  3329 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.917  3329  3329 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 18:15:22.920  7218  7218 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 18:15:22.921  7218  7218 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 18:15:22.924  7061  7606 V FormManager: Network unavailable.
,09-12 18:15:22.926  7061  7606 V FormManager: Network unavailable.
09-12 18:15:22.945  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:22
,09-12 18:15:22.947  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,09-12 18:15:22.947  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
09-12 18:15:22.947  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 18:15:22.948  7278  7278 D WeatherAncestor: connectivity changed - connection : true
09-12 18:15:22.948  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15d820d6
09-12 18:15:22.948  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 18:15:22.949  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 18:15:22.949  7278  7278 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 18:15:22.949  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 18:15:22.949  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:22
09-12 18:15:22.959  1033  2020 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-12 18:15:22.964  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-12 18:15:22.967  6322  6322 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
09-12 18:15:22.967  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 18:15:22.968  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-12 18:15:22.968  7084  7084 I BluetoothA2dpServiceJni: classInitNative
09-12 18:15:22.968  7084  7084 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:15:22.968  7084  7084 D A2dpStateMachine: make
09-12 18:15:22.969  6322  6976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
09-12 18:15:22.970  7084  7084 I bluedroid-qcom: get_profile_interface a2dp
09-12 18:15:22.970  7084  7609 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 18:15:22.972  7084  7084 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:15:22.972  7084  7084 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,09-12 18:15:22.973  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:22.974  7084  7084 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 18:15:22.975  7084  7608 D A2dpStateMachine: Enter Disconnected: -2
09-12 18:15:22.976  7084  7084 D HidService: Received start request. Starting profile...
09-12 18:15:22.976  7084  7084 I bluedroid-qcom: get_profile_interface hidhost
09-12 18:15:22.976  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:22.977  7084  7084 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 18:15:22.978  7084  7084 D HealthService: Received start request. Starting profile...
09-12 18:15:22.980  7084  7084 I bluedroid-qcom: get_profile_interface health
09-12 18:15:22.980  7084  7084 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-12 18:15:22.980  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:22.980  7084  7084 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-12 18:15:22.981  7084  7084 D PanService: Received start request. Starting profile...
09-12 18:15:22.981  7084  7084 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 18:15:22.981  7084  7084 I bluedroid-qcom: get_profile_interface pan
09-12 18:15:22.985  7084  7084 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-12 18:15:22.985  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:22.985  2222  2222 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.986  7084  7084 D HeadsetStateMachine: Proxy object connected
09-12 18:15:22.986  7084  7084 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
09-12 18:15:22.986  7084  7084 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,09-12 18:15:22.987  7084  7084 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
09-12 18:15:22.991  7084  7084 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:15:22.991  7084  7084 D BtGatt.GattService: Received start request. Starting profile...
09-12 18:15:22.991  7084  7084 D BtGatt.GattService: start()
09-12 18:15:22.991  7084  7084 I bluedroid-qcom: get_profile_interface gatt
09-12 18:15:22.991  7084  7084 D BtGatt.AdvertiseManager: advertise manager created
09-12 18:15:22.996  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
09-12 18:15:22.996  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:22.996  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
09-12 18:15:22.997  7151  7151 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
09-12 18:15:22.998  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:22.998  7084  7591 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-12 18:15:22.999  7084  7591 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 18:15:22.999  7084  7591 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-12 18:15:23.000  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
,09-12 18:15:23.001  7084  7084 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 18:15:23.002  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:23.002  7084  7084 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-12 18:15:23.003  7084  7084 V BluetoothMapService: BluetoothMapBinder()
09-12 18:15:23.003  7084  7084 D BluetoothMapService: Received start request. Starting profile...
09-12 18:15:23.003  7084  7084 D BluetoothMapService: start()
09-12 18:15:23.006  7084  7084 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-12 18:15:23.007  7084  7084 D BluetoothMapEmailAppObserver: createReceiver()
09-12 18:15:23.008  7084  7084 D BluetoothMapEmailAppObserver: initObservers()
09-12 18:15:23.008  7084  7084 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-12 18:15:23.010  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1dc9fc98
09-12 18:15:23.010  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 18:15:23.010  7151  7151 D AppUp4:CustFacade: isPhone : true
09-12 18:15:23.010  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-12 18:15:23.010  7151  7151 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
09-12 18:15:23.012  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:15:23.013  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:23.015  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:23.017  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:23.019  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:23.023  4615  7616 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 18:15:23.023  7084  7084 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 18:15:23.023  4615  7617 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:23.024  4615  7617 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,09-12 18:15:23.025  7179  7179 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
09-12 18:15:23.027  7084  7084 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 18:15:23.030  7084  7084 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 18:15:23.031  7084  7084 V PanService: [BTUI] SIM Extra State :ABSENT
09-12 18:15:23.035  7084  7084 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-12 18:15:23.040  7084  7084 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-12 18:15:23.041  7084  7084 V BluetoothMapService: Handler(): got msg=1
09-12 18:15:23.041  7179  7618 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:23.043  7084  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-12 18:15:23.043  7084  7559 I bluedroid-qcom: enable
09-12 18:15:23.043  7084  7084 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.043  7084  7622 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-12 18:15:23.043  7084  7559 I bt_hci_bdroid: init
09-12 18:15:23.044  7084  7559 I bt_vendor: bt-vendor : init
09-12 18:15:23.044  7084  7559 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 18:15:23.044  7084  7559 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 18:15:23.044  7084  7559 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-12 18:15:23.044  7084  7559 D bt_userial_mct: userial_init
09-12 18:15:23.044  7084  7622 I bt-btu  : btu_task pending for preload complete event
09-12 18:15:23.045  7084  7084 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 18:15:23.045  7084  7084 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 18:15:23.045  7084  7084 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 18:15:23.046  7084  7084 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.046  7084  7084 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-12 18:15:23.046  7084  7559 D bt_hci_bdroid: set_power 1
09-12 18:15:23.047  7084  7559 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 18:15:23.047  7084  7559 I bt_vendor: Starting hciattach daemon
09-12 18:15:23.047  7084  7559 I bt_vendor: try to set true
09-12 18:15:23.047  3329  3329 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
09-12 18:15:23.047  3329  3329 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:23.048  3329  3329 I LgeMiscReceiver: networkInfo.isConnected() = false
09-12 18:15:23.034  7626  7626 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-12 18:15:23.034  7626  7626 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:23.057  7218  7218 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
09-12 18:15:23.058  7218  7218 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
09-12 18:15:23.059  7061  7620 W FormManager: Network not available. Please check & try again.
09-12 18:15:23.067  7627  7627 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-12 18:15:23.089  7061  7621 V FormManager: Network unavailable.
09-12 18:15:23.090  7278  7278 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:23
,09-12 18:15:23.091  7278  7278 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
09-12 18:15:23.091  7278  7278 D Weather.Utils: 2 : All the weather widget is gone.
09-12 18:15:23.092  7061  7621 V FormManager: Network unavailable.
09-12 18:15:23.092  7278  7278 D UpdateThreadPoolManager: 2 : This is isUpdating : false
09-12 18:15:23.092  7278  7278 D WeatherAncestor: connectivity changed - connection : true
09-12 18:15:23.092  7278  7278 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@15d820d6
09-12 18:15:23.093  7278  7278 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
09-12 18:15:23.093  7278  7278 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
09-12 18:15:23.093  7278  7278 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
09-12 18:15:23.093  7278  7278 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
09-12 18:15:23.093  7278  7278 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 18:15:23
09-12 18:15:23.129  7633  7633 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-12 18:15:23.143  7634  7634 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-12 18:15:23.175  7636  7636 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-12 18:15:23.201  7637  7637 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-12 18:15:23.215  7638  7638 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-12 18:15:23.241  7639  7639 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-12 18:15:23.282  7641  7641 I libmdmdetect: ESOC framework not supported
,09-12 18:15:23.283  7641  7641 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-12 18:15:23.292  7641  7641 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
09-12 18:15:23.292  7641  7641 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-12 18:15:23.292  7641  7641 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-12 18:15:23.292  7641  7641 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-12 18:15:23.293  7641  7641 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-12 18:15:23.293  7641  7641 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-12 18:15:23.293  7641  7641 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-12 18:15:23.336  7641  7642 E QC-QMI  : qmi_client [7641] 14: failed to locate client data
,09-12 18:15:23.340   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-12 18:15:23.340   475   475 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
09-12 18:15:23.389  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-12 18:15:23.405  7647  7647 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-12 18:15:23.440  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7626
09-12 18:15:23.440  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7643
,09-12 18:15:23.449  7084  7559 I bt_vendor: bluetooth satus is on
09-12 18:15:23.449  7084  7559 D bt_hci_bdroid: preload
09-12 18:15:23.449  7084  7625 D bt_userial_mct: userial_open(port:0)
09-12 18:15:23.450  7084  7625 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-12 18:15:23.453  7084  7625 I bt_vendor: Done intiailizing UART
,09-12 18:15:23.456  7084  7625 I bt_vendor: Done intiailizing UART
09-12 18:15:23.456  7084  7625 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-12 18:15:23.456  7084  7625 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-12 18:15:23.456  7084  7649 D bt_userial_mct: Entering userial_read_thread()
09-12 18:15:23.456  7084  7622 I bt-btu  : btu_task received preload complete event
09-12 18:15:23.457  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-12 18:15:23.457  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-12 18:15:23.461  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 18:15:23.467  7084  7622 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 18:15:23.468  7084  7622 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 18:15:23.468  7084  7622 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 18:15:23.468  7084  7622 I         : BTE_InitTraceLevels -- TRC_BTIF
09-12 18:15:23.565  7084  7622 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
09-12 18:15:23.565  7084  7622 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0172061 
09-12 18:15:23.565  7084  7622 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0172061 
,09-12 18:15:23.609  7084  7562 E bt-btif : Calling BTA_HhEnable
09-12 18:15:23.609  7084  7562 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-12 18:15:23.609  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-12 18:15:23.609  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-12 18:15:23.610  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-12 18:15:23.610  7084  7562 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-12 18:15:23.612  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,09-12 18:15:23.612  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-12 18:15:23.613  7084  7562 D BluetoothAdapterProperties: Name is: G3
09-12 18:15:23.616  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 18:15:23.617  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-12 18:15:23.618  7084  7562 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:15:23.619  7084  7562 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 18:15:23.619  7084  7562 D bt_hci_bdroid: postload
09-12 18:15:23.620  7084  7625 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:23.620  7084  7625 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:23.622  7084  7622 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-12 18:15:23.622  7084  7562 D bte_conf: Device ID record 1 : primary
09-12 18:15:23.622  7084  7562 D bte_conf:   vendorId            = 00c4
09-12 18:15:23.622  7084  7562 D bte_conf:   vendorIdSource      = 0001
09-12 18:15:23.622  7084  7562 D bte_conf:   product             = 13a1
09-12 18:15:23.622  7084  7562 D bte_conf:   version             = 1000
09-12 18:15:23.622  7084  7562 D bte_conf:   clientExecutableURL = 
09-12 18:15:23.622  7084  7562 D bte_conf:   serviceDescription  = 
09-12 18:15:23.622  7084  7562 D bte_conf:   documentationURL    = 
09-12 18:15:23.622  7084  7562 D bte_conf: bte_load_did_conf no section named DID2.
09-12 18:15:23.624  7084  7625 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:23.624  7084  7625 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:23.625  7084  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-12 18:15:23.625  7084  7559 D BluetoothAdapterProperties: ScanMode =  20
09-12 18:15:23.625  7084  7559 D BluetoothAdapterProperties: State =  11
09-12 18:15:23.625  7084  7559 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-12 18:15:23.625  7084  7559 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-12 18:15:23.625  7084  7559 D BluetoothAdapterProperties: Setting state to 12
09-12 18:15:23.625  7084  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 18:15:23.626  7084  7562 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 18:15:23.626  7084  7562 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 18:15:23.614  7651  7651 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:23.614  7651  7651 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:23.631  1033  1095 D BluetoothManagerService: Message: 60
09-12 18:15:23.631  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-12 18:15:23.631  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,09-12 18:15:23.632  7084  7559 I BluetoothAdapterState: Entering On State
09-12 18:15:23.633  7084  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:23.633  7084  7622 W bt-smp  : Plain text(LSB ~ MSB) = 8e e1 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:23.633  7084  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 96 47 a2 e8 be 97 cd 47 05 28 27 ed 8a cd 80 
09-12 18:15:23.633  7084  7622 W bt-btm  : Stopping oneshot timer
09-12 18:15:23.633  7084  7625 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:23.634  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:15:23.638  7084  7649 E bt_mct  : hci lib postload completed
09-12 18:15:23.642  7084  7559 D LGBluetoothServiceAdapter: [BTUI] OnState
09-12 18:15:23.642  7084  7559 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
,09-12 18:15:23.642  7084  7559 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
09-12 18:15:23.646  7084  7559 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-12 18:15:23.647  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:23.647  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:23.647  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:23.647  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:23.647  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:23.647  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:23.647  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:23.647  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:23.648  7084  7562 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 18:15:23.648  7084  7562 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-12 18:15:23.650  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:23.653  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:23.653  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:23.653  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:23.653  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:23.653  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:23.653  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:23.653  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:23.653  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:23.656  7084  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:23.656  7084  7622 W bt-smp  : Plain text(LSB ~ MSB) = 16 44 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:23.656  7084  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = 2d 99 ed e7 2f f4 bd 1f 72 f5 ba dd d9 de 87 6f 
09-12 18:15:23.657  7084  7622 W bt-btm  : Stopping oneshot timer
09-12 18:15:23.658  1879  1879 D BluetoothHeadset: Proxy object connected
09-12 18:15:23.658  6931  6954 D BluetoothMap: onBluetoothStateChange: up=true
09-12 18:15:23.659  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:15:23.663  6931  6953 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 18:15:23.663  6931  6931 D BluetoothMap: Proxy object connected
09-12 18:15:23.663  6931  6931 D MapProfile: Bluetooth service connected
09-12 18:15:23.663  6931  6931 D BluetoothMap: getConnectedDevices()
09-12 18:15:23.664  7084  7102 V BluetoothMapService: getConnectedDevices()
09-12 18:15:23.665  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:15:23.666  1033  1033 D BluetoothHeadset: Proxy object connected
09-12 18:15:23.666  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:15:23.669  1033  1033 D BluetoothA2dp: Proxy object connected
09-12 18:15:23.670  6931  6954 D BluetoothPan: onBluetoothStateChange on: true
09-12 18:15:23.670  6931  6954 D BluetoothPan: onBluetoothStateChange call bindService
09-12 18:15:23.671  7084  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:23.671  7084  7622 W bt-smp  : Plain text(LSB ~ MSB) = 52 75 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:23.671  7084  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = aa 0b 38 98 19 08 3a af 94 ca 03 fb f5 07 2b 1e 
09-12 18:15:23.671  7084  7622 W bt-btm  : Stopping oneshot timer
,09-12 18:15:23.675  6931  6931 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:15:23.675  6931  6931 D PanProfile: Bluetooth service connected
09-12 18:15:23.675  6931  6953 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 18:15:23.679  1879  4264 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:15:23.681  1879  1879 D BluetoothHeadset: Proxy object connected
09-12 18:15:23.681  6931  6931 D BluetoothInputDevice: Proxy object connected
09-12 18:15:23.681  6931  6931 D HidProfile: Bluetooth service connected
09-12 18:15:23.682  1879  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:15:23.682  7084  7559 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-12 18:15:23.684  7084  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:23.684  7084  7622 W bt-smp  : Plain text(LSB ~ MSB) = 04 9e 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:23.684  7084  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = df 85 99 f8 67 e4 39 00 04 b1 1b 00 fb 89 29 48 
09-12 18:15:23.684  7084  7622 W bt-btm  : Stopping oneshot timer
,09-12 18:15:23.686  1879  1879 D BluetoothHeadset: Proxy object connected
09-12 18:15:23.690  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-12 18:15:23.690  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-12 18:15:23.690  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-12 18:15:23.692  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.692  1967  2179 D LGBluetoothAPIService: Message: 1
09-12 18:15:23.692  1967  2179 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-12 18:15:23.693  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 18:15:23.695  6817  6817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,09-12 18:15:23.700  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:23.702  1033  1095 D BluetoothManagerService: Message: 40
09-12 18:15:23.702  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-12 18:15:23.704  7661  7661 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-12 18:15:23.706  1967  2179 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
09-12 18:15:23.708  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:23.709  7084  7622 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:23.709  7084  7622 W bt-smp  : Plain text(LSB ~ MSB) = bb ff 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:23.709  7084  7622 W bt-smp  : Encrypted text(LSB ~ MSB) = c5 75 2c ef 60 d0 7b 44 a6 1a cc b6 07 c6 58 b2 
09-12 18:15:23.709  7084  7622 W bt-btm  : Stopping oneshot timer
,09-12 18:15:23.711  7084  7084 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.711  7084  7084 D BluetoothMapService: STATE_ON
09-12 18:15:23.712  6931  6931 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 18:15:23.713  7084  7084 D LGBluetoothAPIServer: [BTUI] onCreate()
09-12 18:15:23.713  7084  7084 D LGBluetoothAPIServer: [BTUI] onBind()
09-12 18:15:23.714  1967  1967 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-12 18:15:23.714  1967  2179 D LGBluetoothAPIService: Message: 100
09-12 18:15:23.714  1967  2179 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-12 18:15:23.715  1033  1095 D BluetoothManagerService: Message: 30
09-12 18:15:23.720  6931  6931 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-12 18:15:23.723  1033  1095 D BluetoothManagerService: Message: 30
,09-12 18:15:23.728  6931  6931 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
09-12 18:15:23.730  6931  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 18:15:23.730  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:23.730  7084  7084 V BluetoothPbapService: Pbap Service onCreate
09-12 18:15:23.730  7084  7084 V BluetoothPbapService: Starting PBAP service
09-12 18:15:23.732  7084  7084 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-12 18:15:23.732  7084  7084 V BluetoothPbapService: Pbap Service onBind
09-12 18:15:23.736  7084  7084 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.736  7084  7084 V BluetoothPbapService: state: 12
,09-12 18:15:23.736  7084  7084 V BluetoothMapService: Handler(): got msg=1
09-12 18:15:23.737  6931  6931 D BluetoothA2dp: Proxy object connected
09-12 18:15:23.737  7084  7084 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-12 18:15:23.737  7084  7084 V BluetoothPbapService: Handler(): got msg=1
09-12 18:15:23.738  7084  7084 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-12 18:15:23.738  7084  7084 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 18:15:23.739  7084  7084 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.739  7084  7084 V BluetoothPbapReceiver: ***********state = 12
09-12 18:15:23.739  7084  7666 V BluetoothPbapService: Pbap Service initSocket
09-12 18:15:23.740  7084  7665 D BluetoothMapMasInstance: MAS initSocket()
09-12 18:15:23.740  6931  6931 D A2dpProfile: Bluetooth service connected
09-12 18:15:23.742  7084  7665 D BluetoothMapMasInstance:   masId = 00
09-12 18:15:23.742  7084  7665 D BluetoothMapMasInstance:   msgTypes = 0e
09-12 18:15:23.742  7084  7665 D BluetoothMapMasInstance:   masName = SMS/MMS
09-12 18:15:23.742  7084  7665 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
09-12 18:15:23.742  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:15:23.742  6931  6931 D BluetoothHeadset: Proxy object connected
09-12 18:15:23.743  2222  2222 D c       : Getting all permits...
09-12 18:15:23.743  2222  2222 D a       : Opening database...
09-12 18:15:23.743  1033  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:23.743  6931  6931 D HeadsetProfile: Bluetooth service connected
09-12 18:15:23.744  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:23.744  7084  7665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:23.745  7084  7666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:23.745  7084  7665 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-12 18:15:23.746  7084  7666 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-12 18:15:23.746  7084  7665 V BluetoothMapMasInstance: Succeed to create listening socket 
09-12 18:15:23.746  7084  7666 V BluetoothPbapService: Succeed to create listening socket 
09-12 18:15:23.746  7084  7665 D BluetoothMapMasInstance: Accepting socket connection...
09-12 18:15:23.746  7084  7666 V BluetoothPbapService: Accepting socket connection...
09-12 18:15:23.746  7084  7562 D BluetoothAdapterProperties: Scan Mode:21
09-12 18:15:23.746  2222  2222 D a       : Opening database auth.proximity.permit_store...
09-12 18:15:23.747  7084  7562 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-12 18:15:23.748  2222  2222 D a       : Closing database...
,09-12 18:15:23.752  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:23.754  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:23.760  6931  6931 D DockEventReceiver: finishStartingService: stopping service
09-12 18:15:23.761  6931  6931 D BluetoothPbap: Proxy object connected
09-12 18:15:23.761  6931  6931 D PbapServerProfile: Bluetooth service connected
,09-12 18:15:23.766  6931  6931 D BluetoothPermissionRequest: onReceive
09-12 18:15:23.768  6931  6931 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 18:15:23.770  6931  6931 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 18:15:23.773  7084  7084 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-12 18:15:23.775  7084  7084 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-12 18:15:23.781  7084  7084 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-12 18:15:23.801  7084  7084 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 18:15:23.802  7084  7084 V BtOppService: onCreate
,09-12 18:15:23.806  7084  7084 V BluetoothOppNotification: send message
09-12 18:15:23.808  7084  7084 V BtOppService: Starting RfcommListener
09-12 18:15:23.812  7084  7084 D BluetoothOppPreference: Dumping Names:  
09-12 18:15:23.812  7084  7084 D BluetoothOppPreference: {}
09-12 18:15:23.812  7084  7084 D BluetoothOppPreference: Dumping Channels:  
09-12 18:15:23.812  7084  7084 D BluetoothOppPreference: {}
09-12 18:15:23.813  7084  7084 V BtOppService: onStartCommand
09-12 18:15:23.814  7084  7673 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 18:15:23.817  7084  7673 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 18:15:23.818  7084  7084 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:15:23.818  7084  7084 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 18:15:23.819  7084  7670 V BtOppService: Deleted complete outbound shares, number =  0
09-12 18:15:23.819  7084  7673 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f5e11c3 on behalf of 
09-12 18:15:23.821  7084  7670 V BtOppService: Deleted complete inbound failed shares, number = 0
09-12 18:15:23.821  7084  7670 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-12 18:15:23.821  7084  7084 V BluetoothOppNotification: new notify threadi!
09-12 18:15:23.822  7084  7084 V BluetoothOppNotification: send delay message
09-12 18:15:23.822  7084  7670 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14492a40 on behalf of 
09-12 18:15:23.822  7084  7084 V BtOppService: start RfcommListener
09-12 18:15:23.824  7084  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-12 18:15:23.825  7084  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b86ad79 on behalf of 
09-12 18:15:23.825  7084  7673 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 18:15:23.825  7084  7673 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 18:15:23.825  7084  7674 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 18:15:23.825  7084  7084 V BtOppService: RfcommListener started
09-12 18:15:23.826  7084  7084 V BtOppService: ContentObserver received notification
09-12 18:15:23.826  7084  7675 V BtOppRfcommListener: Starting RFCOMM listener....
09-12 18:15:23.827  1033  2089 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:23.827  7084  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 18:15:23.828  7084  7673 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25c8eabe on behalf of 
09-12 18:15:23.829  7084  7675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:23.829  7084  7673 V BluetoothOppNotification: update too frequent, put in queue
09-12 18:15:23.829  7084  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b06071f on behalf of 
09-12 18:15:23.830  7084  7673 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 18:15:23.830  7084  7673 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 18:15:23.830  7084  7674 V BluetoothOppNotification: outbound: succ-0  fail-0
,09-12 18:15:23.831  7084  7675 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-12 18:15:23.831  7084  7675 V BtOppRfcommListener: Started RFCOMM listener....
09-12 18:15:23.831  7084  7675 I BtOppRfcommListener: Accept thread started.
09-12 18:15:23.831  7084  7675 V BtOppRfcommListener: Accepting connection...
09-12 18:15:23.833  7084  7673 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38b6aa6c on behalf of 
09-12 18:15:23.833  7084  7673 V BluetoothOppNotification: update too frequent, put in queue
09-12 18:15:23.834  7084  7674 V BluetoothOppNotification: outbound notification was removed.
09-12 18:15:23.834  7084  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 18:15:23.835  7084  7673 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 18:15:23.835  7084  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@93ba835 on behalf of 
09-12 18:15:23.836  7084  7674 V BluetoothOppNotification: inbound: succ-0  fail-0
09-12 18:15:23.837  7084  7674 V BluetoothOppNotification: inbound notification was removed.
09-12 18:15:23.837  7084  7674 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 18:15:23.838  7084  7674 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29a4f4ca on behalf of 
09-12 18:15:23.841  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:23.841  7084  7084 V BluetoothFtpService: Ftp Service onCreate
09-12 18:15:23.841  7084  7084 I BluetoothFtpService: Ftp Service onCreate
09-12 18:15:23.841  7084  7084 V BluetoothFtpService: Ftp Service onStartCommand
09-12 18:15:23.841  7084  7084 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.841  7084  7084 V BluetoothFtpService: Starting Listening on sockets
09-12 18:15:23.841  7084  7084 V BtOppService: ContentObserver received notification
09-12 18:15:23.842  7084  7084 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 18:15:23.842  7084  7084 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 18:15:23.842  7084  7084 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 18:15:23.842  7084  7084 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.842  7084  7084 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-12 18:15:23.842  7084  7084 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 18:15:23.843  7084  7676 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 18:15:23.843  7084  7676 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,09-12 18:15:23.847  7084  7676 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f9a0158 on behalf of 
09-12 18:15:23.847  7084  7084 V BluetoothFtpService: Handler(): got msg=1
09-12 18:15:23.848  7084  7676 V BluetoothOppNotification: update too frequent, put in queue
09-12 18:15:23.849  7084  7084 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-12 18:15:23.849  7084  7084 V BluetoothFtpService: Ftp Service initSocket
09-12 18:15:23.850  7084  7676 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 18:15:23.852  1033  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:23.853  7084  7084 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:23.854  7084  7084 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-12 18:15:23.854  7084  7084 V BluetoothFtpService: Succeed to create listening socket on channel 20
,09-12 18:15:23.855  7084  7677 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
09-12 18:15:23.864  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:23.865  7084  7084 V BluetoothSapService: Sap Service onCreate
09-12 18:15:23.866  7084  7084 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:23.866  7084  7084 V BluetoothSapService: state: 12
09-12 18:15:23.866  7084  7084 V BluetoothSapService: Starting SAP server process
,09-12 18:15:23.868  7084  7084 V BluetoothSapService: SAP Service startRfcommListenerThread
09-12 18:15:23.869  7084  7679 V BluetoothSapService: Sap Service initRfcommSocket
09-12 18:15:23.870  1033  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:23.854  7678  7678 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:23.854  7678  7678 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:23.871  7084  7679 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:15:23.872  7084  7679 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-12 18:15:23.872  7084  7679 V BluetoothSapService: Succeed to create listening socket 
09-12 18:15:23.872  7084  7679 V BluetoothSapService: Accepting socket connection...
09-12 18:15:23.878  7678  7678 V BT_SAP  : Event pipe created
09-12 18:15:23.879  7678  7678 V BT_SAP  : create_server_socket qcom.sap.server
09-12 18:15:23.879  7678  7678 V BT_SAP  : created socket fd 6
09-12 18:15:23.963  7302  7352 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-12 18:15:24.479  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:15:24.479  1033  1535 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:15:24.497  1033  1536 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,09-12 18:15:24.503  1033  1536 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
09-12 18:15:24.693  1033  1597 I ActivityManager: Killing 7489:com.lge.bnr/1000 (adj 15): empty #17
,09-12 18:15:24.725  1033  2089 W libprocessgroup: failed to open /acct/uid_1000/pid_7489/cgroup.procs: No such file or directory
,09-12 18:15:24.824  7084  7084 V BluetoothOppNotification: new notify threadi!
09-12 18:15:24.825  7084  7084 V BluetoothOppNotification: send delay message
,09-12 18:15:24.835  7084  7691 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-12 18:15:24.839  7084  7691 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e59db04 on behalf of 
,09-12 18:15:24.844  7084  7691 V BluetoothOppNotification: mUpdateCompleteNotification = true
,09-12 18:15:24.853  7084  7691 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 18:15:24.855  7084  7691 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@615a8ed on behalf of 
09-12 18:15:24.856  7084  7691 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 18:15:24.858  7084  7691 V BluetoothOppNotification: outbound notification was removed.
09-12 18:15:24.858  7084  7691 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 18:15:24.859  7084  7691 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4ff5322 on behalf of 
09-12 18:15:24.860  7084  7691 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-12 18:15:24.864  7084  7691 V BluetoothOppNotification: inbound notification was removed.
,09-12 18:15:24.864  7084  7691 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 18:15:24.866  7084  7691 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a56f1b3 on behalf of 
,09-12 18:15:24.996  1033  1597 I ActivityManager: Killing 6693:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,09-12 18:15:25.031  7011  7011 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
09-12 18:15:25.031  7011  7011 W System.err: android.os.DeadObjectException
09-12 18:15:25.032  7011  7011 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:15:25.032  7011  7011 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 18:15:25.032  7011  7011 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
09-12 18:15:25.032  7011  7011 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
09-12 18:15:25.032  7011  7011 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-12 18:15:25.032  7011  7011 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-12 18:15:25.032  7011  7011 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 18:15:25.032  7011  7011 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 18:15:25.032  7011  7011 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 18:15:25.032  7011  7011 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 18:15:25.032  7011  7011 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:15:25.032  7011  7011 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:15:25.032  7011  7011 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 18:15:25.032  7011  7011 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 18:15:25.033  7011  7011 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
09-12 18:15:25.033  7011  7011 W System.err: android.os.DeadObjectException
09-12 18:15:25.033  7011  7011 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:15:25.033  7011  7011 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 18:15:25.033  7011  7011 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
09-12 18:15:25.033  7011  7011 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
09-12 18:15:25.033  7011  7011 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
09-12 18:15:25.033  7011  7011 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
09-12 18:15:25.033  7011  7011 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 18:15:25.033  7011  7011 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 18:15:25.033  7011  7011 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 18:15:25.034  7011  7011 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 18:15:25.034  7011  7011 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:15:25.034  7011  7011 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:15:25.034  7011  7011 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 18:15:25.034  7011  7011 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 18:15:25.034  7011  7011 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
09-12 18:15:25.034  7011  7011 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,09-12 18:15:25.069  1033  2089 W libprocessgroup: failed to open /acct/uid_1000/pid_6693/cgroup.procs: No such file or directory
,09-12 18:15:25.069  1033  2089 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,09-12 18:15:25.089  7011  7011 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
,09-12 18:15:25.093  7011  7011 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-12 18:15:25.144  1033  2000 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7692 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 18:15:25.195  7011  7011 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-12 18:15:25.222  7692  7692 D UEI.SmartControl: Quickset Services start...
09-12 18:15:25.224  7692  7692 I UEI.SmartControl: Manufacture = LGE
09-12 18:15:25.224  7692  7692 D UEI.SmartControl: Id = LGNevo
,09-12 18:15:25.228  7692  7692 D UEI.SmartControl: File observer start...
09-12 18:15:25.229  7692  7692 E UEI.SmartControl: IR Port is disabled: false
09-12 18:15:25.229  7692  7692 D UEI.SmartControl: Starting file observer...
09-12 18:15:25.229  7692  7692 D UEI.SmartControl: Extracting JNI libs...
09-12 18:15:25.229  7692  7692 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
09-12 18:15:25.296  7692  7692 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
09-12 18:15:25.296  7692  7692 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
09-12 18:15:25.296  7692  7692 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,09-12 18:15:25.330  7692  7692 I UEI.SmartControl: --- Selecting new region: 6
,09-12 18:15:25.334  7692  7692 I UEI.SmartControl: Model = LG-D855
09-12 18:15:25.336  7692  7692 D UEI.SmartControl: QS Service created
09-12 18:15:25.348  7692  7692 I UEI.SmartControl: Service initServices...
,09-12 18:15:25.363  7692  7692 D UEI.SmartControl: QS start get config
,09-12 18:15:25.424  7692  7692 D UEI.SmartControl: Loading JNI Libs...
,09-12 18:15:25.439  1033  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 18:15:25.439  1033  2020 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@17936508 mBinding = false
09-12 18:15:25.453  1033  1095 D BluetoothManagerService: Message: 2
,09-12 18:15:25.457  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 18:15:25.458  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 18:15:25.458  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-12 18:15:25.458  1033  1095 D BluetoothManagerService: Sending off request.
09-12 18:15:25.459  7084  7564 D LGBluetoothServiceAdapter: [BTUI] Precleanup
09-12 18:15:25.460  7084  7559 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
09-12 18:15:25.460  7084  7559 D BluetoothAdapterProperties: Setting state to 13
09-12 18:15:25.460  7084  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 18:15:25.461  7084  7559 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 18:15:25.461  7084  7559 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-12 18:15:25.463  7084  7562 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:15:25.464  7084  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 18:15:25.465  7084  7559 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 18:15:25.465  7084  7665 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
09-12 18:15:25.465  7084  7665 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:25.465  7084  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
09-12 18:15:25.465  7084  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
09-12 18:15:25.465  7084  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
09-12 18:15:25.465  7084  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
09-12 18:15:25.465  7084  7665 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
09-12 18:15:25.465  7084  7665 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
09-12 18:15:25.465  1033  1095 D BluetoothManagerService: Message: 60
09-12 18:15:25.465  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
09-12 18:15:25.465  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
09-12 18:15:25.466  7084  7675 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:25.467  7084  7679 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 18:15:25.469  7084  7666 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:25.467  7084  7677 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:15:25.472  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
09-12 18:15:25.472  7084  7622 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
09-12 18:15:25.474  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
09-12 18:15:25.475  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
09-12 18:15:25.476  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:25.476  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:25.476  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:25.476  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:25.476  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:25.476  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:25.476  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:25.476  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:25.476  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:25.476  7084  7622 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 18:15:25.477  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:25.477  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:25.479  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:25.479  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:25.480  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:25.480  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:25.480  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:25.480  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:25.480  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:15:,25.480  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:25.480  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:25.480  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:25.480  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 18:15:25.480  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:15:25.480  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:25.484  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:25.485  7084  7084 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:25.485  7084  7084 D BluetoothMapService: STATE_TURNING_OFF
09-12 18:15:25.486  7084  7084 V BtOppService: Receiver DISABLED_ACTION 
09-12 18:15:25.486  7084  7084 V BluetoothMapService: Handler(): got msg=4
09-12 18:15:25.486  7084  7084 D BluetoothMapService: MAP Service closeService in
09-12 18:15:25.486  7084  7084 D BluetoothMapMasInstance: MAP Service shutdown
09-12 18:15:25.487  7084  7084 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 18:15:25.487  7084  7084 V BluetoothMapService: MAP Service closeService out
09-12 18:15:25.487  7084  7084 I BtOppRfcommListener: stopping Accept Thread
09-12 18:15:25.487  7084  7084 V BtOppRfcommListener: close mBtServerSocket
09-12 18:15:25.488  7084  7084 V BtOppRfcommListener: waiting for thread to terminate
09-12 18:15:25.488  7084  7675 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 18:15:25.489  7084  7084 V BtOppRfcommListener: done waiting for thread to terminate
09-12 18:15:25.489  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:25.491  6931  6931 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
09-12 18:15:25.491  7084  7084 V BtOppService: onDestroy
09-12 18:15:25.492  7084  7084 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
09-12 18:15:25.495  6931  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 18:15:25.504  7084  7084 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 18:15:25.504  7084  7084 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:25.504  7084  7084 V BluetoothPbapReceiver: ***********state = 13
09-12 18:15:25.507  7084  7084 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
09-12 18:15:25.508  7084  7084 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:25.508  7084  7084 V BluetoothPbapService: state: 13
09-12 18:15:25.508  7084  7084 V BluetoothPbapService: Pbap Service closeService in
09-12 18:15:25.512  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:15:25.513  7084  7084 V BluetoothPbapService: successfully stopped pbap service
09-12 18:15:25.513  7084  7084 V BluetoothPbapService: Pbap Service closeService out
09-12 18:15:25.514  7084  7084 V BluetoothPbapService: Pbap Service onDestroy
09-12 18:15:25.514  7084  7084 V BluetoothPbapService: Pbap Service closeService in
09-12 18:15:25.514  7084  7084 V BluetoothPbapService: Pbap Service closeService out
09-12 18:15:25.514  7084  7084 D LGBluetoothPbapAdapter: [BTUI] cleanup
09-12 18:15:25.515  6931  6931 D DockEventReceiver: finishStartingService: stopping service
09-12 18:15:25.516  6931  6931 D BluetoothPbap: Proxy object disconnected
09-12 18:15:25.516  6931  6931 D PbapServerProfile: Bluetooth service disconnected
,09-12 18:15:25.530  6931  6931 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-12 18:15:25.535  6931  6931 D BluetoothPermissionRequest: onReceive
09-12 18:15:25.535  6931  6931 D LGBluetoothAuthorization: [BTUI] cancel All Notification
09-12 18:15:25.540  6931  6931 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 18:15:25.543  7084  7084 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
09-12 18:15:25.543  7084  7084 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
09-12 18:15:25.544  7084  7084 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
09-12 18:15:25.547  7084  7084 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:25.548  7084  7084 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 18:15:25.549  7084  7084 V BluetoothFtpService: Ftp Service onStartCommand
09-12 18:15:25.549  7084  7084 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:25.549  7084  7084 V BluetoothFtpService: Ftp Service closeService
09-12 18:15:25.549  7084  7084 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
09-12 18:15:25.552  7084  7084 V BluetoothFtpService: successfully stopped ftp service
09-12 18:15:25.552  7084  7084 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 18:15:25.553  7084  7084 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 18:15:25.553  7084  7084 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 18:15:25.553  7084  7084 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:25.553  7084  7084 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
09-12 18:15:25.553  7084  7084 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 18:15:25.554  7084  7084 V BluetoothFtpService: Ftp Service onDestroy
09-12 18:15:25.554  7084  7084 V BluetoothFtpService: Ftp Service closeService
09-12 18:15:25.558  7084  7084 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:25.558  7084  7084 V BluetoothSapService: state: 13
09-12 18:15:25.558  7084  7084 V BluetoothSapService: Stopping SAP server process
,09-12 18:15:25.560  7084  7084 V BluetoothSapService: Sap Service closeSapService in
,09-12 18:15:25.560  7084  7084 V BluetoothSapService: Close listen Socket : 
09-12 18:15:25.560  7084  7084 V BluetoothSapService: Close rfcomm Socket : 
09-12 18:15:25.560  7084  7084 V BluetoothSapService: Close sapd  Socket : 
09-12 18:15:25.564  7084  7084 V BluetoothSapService: Sap Service closeSapService out
09-12 18:15:25.564  7084  7084 V BluetoothSapService: Sap Service onDestroy
09-12 18:15:25.564  7084  7084 V BluetoothSapService: Sap Service closeSapService in
09-12 18:15:25.564  7084  7084 V BluetoothSapService: Close listen Socket : 
09-12 18:15:25.564  7084  7084 V BluetoothSapService: Close rfcomm Socket : 
09-12 18:15:25.564  7084  7084 V BluetoothSapService: Close sapd  Socket : 
09-12 18:15:25.565  7084  7084 V BluetoothSapService: Sap Service closeSapService out
09-12 18:15:25.826  7692  7692 I UEI.SmartControl: Supports setup maps: true
09-12 18:15:25.830  7692  7692 D UEI.SmartControl: QS start statue = true Error code = 0
09-12 18:15:25.830  7692  7692 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-12 18:15:25.830  7692  7692 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-12 18:15:25.831  7692  7692 I UEI.SmartControl: ### init IR Blaster...
,09-12 18:15:25.837  7692  7692 D serial_port: Configuring serial port
,09-12 18:15:25.841  7692  7692 E UEI.SmartControl: UEIBLaster setting for 616
09-12 18:15:25.841  7692  7692 I UEI.SmartControl: Setting serial record hearder size = 2
09-12 18:15:25.841  7692  7692 I UEI.SmartControl: configuring settings for MAXQ616
09-12 18:15:25.841  7692  7692 I UEI.SmartControl: Get version...
09-12 18:15:25.861  7692  7724 D UEI.SmartControl: serial port data available: 21
,09-12 18:15:25.893  7692  7692 D UEI.SmartControl: MAXQ616 A2-X4 software.
,09-12 18:15:25.893  7692  7692 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-12 18:15:25.894  7692  7692 I UEI.SmartControl: QS saving settings...
09-12 18:15:25.896  7692  7692 D UEI.SmartControl: IR Blaster version: 25672567
,09-12 18:15:25.927  7692  7724 D UEI.SmartControl: serial port data available: 4
,09-12 18:15:25.962  7692  7692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-12 18:15:25.967  7692  7733 I UEI.SmartControl: Device manager: loading config....
09-12 18:15:25.967  7692  7733 D UEI.SmartControl: ----------- loading internal config...
09-12 18:15:25.972  7692  7692 E UEI.SmartControl: Services init done
09-12 18:15:25.972  7692  7692 D UEI.SmartControl: QS Service init finished
09-12 18:15:25.974  7692  7692 D UEI.SmartControl: QS Service version name: 2.1.91
09-12 18:15:25.974  7692  7692 D UEI.SmartControl: QS Service version code: 201091
09-12 18:15:25.975  7692  7692 D UEI.SmartControl: Service requested: Control
,09-12 18:15:25.985  7692  7733 E UEI.SmartControl: Loading SETTINGS...
09-12 18:15:25.986  7692  7692 D UEI.SmartControl: Request IControl service: devices are loaded...
09-12 18:15:25.989  1033  1049 I ActivityManager: Killing 7011:com.lge.qremote/u0a112 (adj 15): empty #17
,09-12 18:15:25.998  7692  7733 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
09-12 18:15:26.019  7692  7732 I UEI.SmartControl: Notify AllClients services are ready: 0
09-12 18:15:26.019  7692  7732 D UEI.SmartControl: -----service ready thread exits
,09-12 18:15:26.046  1033  2020 W libprocessgroup: failed to open /acct/uid_10112/pid_7011/cgroup.procs: No such file or directory
,09-12 18:15:26.053  7692  7692 D UEI.SmartControl: Internal service binding...
,09-12 18:15:26.474  7084  7625 I bt_lpm  : LPM is already off!!!
,09-12 18:15:26.481  7084  7622 W bt-btif : ag scb idx 1 not allocated
,09-12 18:15:26.481  7084  7622 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 18:15:26.473  7084  7562 D bt_hci_bdroid: cleanup
09-12 18:15:26.484  7084  7649 I bt_userial_mct: exiting userial_read_thread
09-12 18:15:26.484  7084  7649 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019,
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
09-12 18:15:26.485  7084  7622 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:15:26.486  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,09-12 18:15:26.486  7084  7622 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:15:26.486  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
09-12 18:15:26.486  7084  7622 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:15:26.486  7084  7622 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,09-12 18:15:26.486  7084  7622 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:15:26.486  7084  7622 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
09-12 18:15:26.488  7084  7562 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 18:15:26.492  7084  7625 I bt_vendor: hw_epilog_process
,09-12 18:15:26.504  7084  7562 D bt_hci_bdroid: cleanup Finalizing cleanup
09-12 18:15:26.504  7084  7562 D bt_userial_mct: userial_close
09-12 18:15:26.504  7084  7562 E bt_userial_mct: pthread_join() FAILED result:3
09-12 18:15:26.504  7084  7562 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-12 18:15:26.510  7084  7562 D bt_hci_bdroid: set_power 0
09-12 18:15:26.510  7084  7562 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 18:15:26.511  7084  7562 I bt_vendor: bluetooth satus is on
09-12 18:15:26.511  7084  7562 I bt_vendor: bt-vendor : resetting BT status
09-12 18:15:26.511  7084  7562 I bt_vendor: Starting hciattach daemon
09-12 18:15:26.511  7084  7562 I bt_vendor: try to set false
09-12 18:15:26.513  7084  7562 I bt_vendor: Starting hciattach daemon
09-12 18:15:26.513  7084  7562 I bt_vendor: try to set false
,09-12 18:15:26.516  7084  7562 I bt_vendor: cleanup
09-12 18:15:26.518  7084  7622 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-12 18:15:26.518  7084  7562 I GKI_LINUX: GKI_exit_task 0 done
09-12 18:15:26.518  7084  7562 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-12 18:15:26.520  7084  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-12 18:15:26.527  7084  7559 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-12 18:15:26.530  7084  7084 D HeadsetService: Received stop request...Stopping profile...
09-12 18:15:26.531  7084  7084 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 18:15:26.532  7084  7084 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:15:26.532  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:26.532  7084  7591 D HeadsetStateMachine: Exit Disconnected: -1
09-12 18:15:26.535  1033  1033 D BluetoothHeadset: Proxy object disconnected
09-12 18:15:26.535  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 18:15:26.536  1879  1879 D BluetoothHeadset: Proxy object disconnected
09-12 18:15:26.536  1879  1879 D BluetoothHeadset: Proxy object disconnected
09-12 18:15:26.536  1879  1879 D BluetoothHeadset: Proxy object disconnected
09-12 18:15:26.537  7084  7084 D A2dpService: Received stop request...Stopping profile...
09-12 18:15:26.538  7084  7608 D A2dpStateMachine: Exit Disconnected: -1
09-12 18:15:26.539  7084  7084 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,09-12 18:15:26.544  7084  7084 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
09-12 18:15:26.544  7084  7084 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:15:26.544  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:26.546  1033  1033 D BluetoothA2dp: Proxy object disconnected
09-12 18:15:26.547  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-12 18:15:26.548  7084  7084 D HidService: Received stop request...Stopping profile...
09-12 18:15:26.548  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:26.550  7084  7084 D HealthService: Received stop request...Stopping profile...
09-12 18:15:26.550  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:26.552  7084  7084 D PanService: Received stop request...Stopping profile...
,09-12 18:15:26.555  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:26.558  7084  7084 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:15:26.558  7084  7084 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 18:15:26.559  7084  7084 D BtGatt.GattService: stop()
09-12 18:15:26.559  7084  7084 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 18:15:26.560  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
09-12 18:15:26.561  7084  7084 D BluetoothMapService: Received stop request...Stopping profile...
09-12 18:15:26.561  7084  7084 D BluetoothMapService: stop()
09-12 18:15:26.563  7084  7084 D BluetoothMapEmailAppObserver: deinitObservers()
09-12 18:15:26.563  7084  7084 D BluetoothMapEmailAppObserver: removeReceiver()
09-12 18:15:26.564  7084  7084 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15d820d6
,09-12 18:15:26.567  7084  7084 V BluetoothMapService: Handler(): got msg=4
09-12 18:15:26.567  7084  7084 D BluetoothMapService: MAP Service closeService in
09-12 18:15:26.567  7084  7084 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 18:15:26.567  7084  7084 V BluetoothMapService: MAP Service closeService out
09-12 18:15:26.569  7084  7559 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
09-12 18:15:26.569  7084  7559 D BluetoothAdapterProperties: Setting state to 10
09-12 18:15:26.569  7084  7559 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 18:15:26.571  1033  1095 D BluetoothManagerService: Message: 60
09-12 18:15:26.571  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
09-12 18:15:26.571  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
09-12 18:15:26.572  7084  7559 I BluetoothAdapterState: Entering OffState
09-12 18:15:26.573  6931  7654 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:15:26.574  1879  3208 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:15:26.575  6931  7654 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:15:26.575  6931  7654 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 18:15:26.578  6931  7654 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 18:15:26.579  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:15:26.580  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:15:26.581  6931  7654 D BluetoothPan: onBluetoothStateChange on: false
09-12 18:15:26.582  7084  7084 D HeadsetStateMachine: Unbinding service...
09-12 18:15:26.583  7084  7084 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 18:15:26.583  7084  7084 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 18:15:26.583  7084  7084 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 18:15:26.583  7084  7084 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 18:15:26.583  7084  7084 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 18:15:26.583  7084  7084 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:15:26.583  7084  7084 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
09-12 18:15:26.584  6931  7654 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 18:15:26.585  1879  1894 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 18:15:26.586  7084  7084 I BluetoothA2dpServiceJni: cleanupNative
09-12 18:15:26.586  7084  7609 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 18:15:26.586  7084  7084 I GKI_LINUX: GKI_exit_task 2 done
09-12 18:15:26.586  7084  7084 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 18:15:26.588  1879  2442 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 18:15:26.592  7084  7084 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 18:15:26.592  7084  7084 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 18:15:26.593  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
09-12 18:15:26.593  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
09-12 18:15:26.594  7084  7084 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 18:15:26.594  7084  7084 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:15:26.594  7084  7084 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:15:26.597  7084  7084 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:15:26.597  7084  7084 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 18:15:26.598  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
09-12 18:15:26.599  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
09-12 18:15:26.599  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@17936508 mBinding = false
09-12 18:15:26.600  1033  1095 D BluetoothManagerService: Sending unbind request.
,09-12 18:15:26.602  7084  7084 D BluetoothMapService: cleanup()
09-12 18:15:26.602  7084  7084 D BluetoothMapService: MAP Service closeService in
09-12 18:15:26.602  7084  7084 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
09-12 18:15:26.602  7084  7084 V BluetoothMapService: MAP Service closeService out
09-12 18:15:26.607  7084  7562 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-12 18:15:26.609  7084  7084 I GKI_LINUX: GKI_exit_task 1 done
09-12 18:15:26.609  7084  7084 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-12 18:15:26.609  7084  7084 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 18:15:26.609  7084  7084 I art     : --- WEIRD: removing null entry 248
09-12 18:15:26.609  7084  7084 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
09-12 18:15:26.609  7084  7084 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
09-12 18:15:26.611  7084  7084 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
09-12 18:15:26.612  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,09-12 18:15:26.616  7084  7084 I art     : System.exit called, status: 0
09-12 18:15:26.616  7084  7084 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-12 18:15:26.635   322   322 V AudioFlinger: 7084 died, releasing its sessions
09-12 18:15:26.635   322   322 V AudioFlinger:  pid 1879 @ 0
09-12 18:15:26.635   322   322 V AudioFlinger:  pid 3329 @ 1
09-12 18:15:26.635   322   322 V AudioFlinger:  pid 3329 @ 2
,09-12 18:15:26.638  1967  1967 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
09-12 18:15:26.638  1967  2179 D LGBluetoothAPIService: Message: 101
09-12 18:15:26.639  1967  2179 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
09-12 18:15:26.639  1967  2179 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
09-12 18:15:26.639  1967  2179 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
09-12 18:15:26.640  6931  6931 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
09-12 18:15:26.650  1033  1049 I ActivityManager: Process com.android.bluetooth (pid 7084) has died
09-12 18:15:26.650  1033  1049 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
09-12 18:15:26.650  1033  1049 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,09-12 18:15:26.658  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:26.658  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 18:15:26.660  1967  2179 D LGBluetoothAPIService: Message: 2
09-12 18:15:26.660  1967  2179 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
09-12 18:15:26.661  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:26.661  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:26.662  6931  6931 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
09-12 18:15:26.662  6931  6931 D LGBluetoothEventManager: [BTUI] clear device connection state
,09-12 18:15:26.676  6931  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 18:15:26.681  1603  1603 D BluetoothAdapter: 116975731: getState() :  mService = null. Returning STATE_OFF
,09-12 18:15:26.681  1603  1603 D BluetoothAdapter: 116975731: getState() :  mService = null. Returning STATE_OFF
,09-12 18:15:26.760  1033  1964 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7755 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,09-12 18:15:26.764  6931  6931 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:15:26.779   350   350 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 458us total 20.640ms
,09-12 18:15:26.799   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 18.446ms
,09-12 18:15:26.806  7755  7755 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-12 18:15:26.807  7755  7755 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:26.808  7755  7755 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
09-12 18:15:26.809  7755  7755 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-12 18:15:26.816   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 357us total 16.339ms
,09-12 18:15:26.832  7755  7755 D BluetoothAdapterApp: Loading JNI Library
,09-12 18:15:26.868  7755  7755 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@e040ffe Instance Count = 1
,09-12 18:15:26.873  7755  7755 D BluetoothAdapterApp: onCreate
,09-12 18:15:26.897  7755  7755 D ProfileConfigQcom: [BTUI] HeadsetService is supported
09-12 18:15:26.898  7755  7755 D ProfileConfigQcom: Adding HeadsetService
09-12 18:15:26.898  7755  7755 D ProfileConfigQcom: [BTUI] A2dpService is supported
,09-12 18:15:26.898  7755  7755 D ProfileConfigQcom: Adding A2dpService
,09-12 18:15:26.898  7755  7755 D ProfileConfigQcom: [BTUI] HidService is supported
09-12 18:15:26.898  7755  7755 D ProfileConfigQcom: Adding HidService
09-12 18:15:26.899  7755  7755 D ProfileConfigQcom: [BTUI] HealthService is supported
,09-12 18:15:26.899  7755  7755 D ProfileConfigQcom: Adding HealthService
09-12 18:15:26.899  7755  7755 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
09-12 18:15:26.900  7755  7755 D ProfileConfigQcom: [BTUI] PanService is supported
,09-12 18:15:26.900  7755  7755 D ProfileConfigQcom: Adding PanService
,09-12 18:15:26.901  7755  7755 D ProfileConfigQcom: [BTUI] GattService is supported
,09-12 18:15:26.901  7755  7755 D ProfileConfigQcom: Adding GattService
,09-12 18:15:26.901  7755  7755 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
09-12 18:15:26.901  7755  7755 D ProfileConfigQcom: Adding BluetoothMapService
,09-12 18:15:26.901  7755  7755 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
09-12 18:15:26.902  7755  7755 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 18:15:26.903  7755  7755 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:15:26.904  7755  7755 V BluetoothPbapReceiver: ***********state = 10
09-12 18:15:26.905  7755  7755 V LGMDMManagerInternal: Create singleton instance
,09-12 18:15:27.015  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:15:27.020  6931  6931 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,09-12 18:15:27.027  7755  7755 D LGBluetoothAPIServer: [BTUI] onCreate()
09-12 18:15:27.027  7755  7755 D LGBluetoothAPIServer: [BTUI] onBind()
09-12 18:15:27.030  1967  1967 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
09-12 18:15:27.030  1967  2179 D LGBluetoothAPIService: Message: 100
09-12 18:15:27.030  1967  2179 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
09-12 18:15:27.040  6931  6931 D BluetoothPermissionRequest: onReceive
,09-12 18:15:27.045  6931  6931 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 18:15:27.045  6931  6931 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
09-12 18:15:27.049  6931  6931 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 18:15:27.056  7755  7755 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
09-12 18:15:27.061  7755  7755 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:15:27.065  7755  7755 V BluetoothSapReceiver: [BTUI] checkServiceStart,
,09-12 18:15:27.065  7755  7755 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 18:15:27.065  7755  7755 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 18:15:27.066  7755  7755 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:27.066  7755  7755 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
09-12 18:15:27.068  7028  7028 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
09-12 18:15:28.454  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:15:28.454  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-12 18:15:28.969  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,09-12 18:15:29.030  1033  1428 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 18:15:29.074  1033  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7783 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-12 18:15:29.080  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
09-12 18:15:29.081  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
09-12 18:15:29.107  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-12 18:15:29.124  1033  1033 D administrator: Handling package changes for user 0
,09-12 18:15:29.146  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-12 18:15:29.157  7783  7783 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 18:15:29.223  7783  7783 D LgDataFeature: LgDataFeature() Constructor: none
,09-12 18:15:29.223  7783  7783 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 18:15:29.259  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
09-12 18:15:29.260  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,09-12 18:15:29.300  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:15:29.306  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-12 18:15:29.313  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,09-12 18:15:29.316  2508  2508 V GmsNetworkLocationProvi: DISABLE
09-12 18:15:29.331  7783  7826 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-12 18:15:29.331  7783  7826 I Babel   : MmsConfig.loadMmsSettings
09-12 18:15:29.337  7783  7826 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-12 18:15:29.337  7783  7826 I Babel   : MmsConfig.loadFromDatabase
09-12 18:15:29.338  2508  2508 E GCoreFlp: Bound FusedProviderService with LocationManager
09-12 18:15:29.338  1033  1090 D LocationProviderProxy: applying state to connected service
,09-12 18:15:29.366  7783  7826 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-12 18:15:29.366  7783  7826 I Babel   : MmsConfig.loadFromResources
09-12 18:15:29.368  7783  7826 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
09-12 18:15:29.369  7783  7826 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
09-12 18:15:29.370  7783  7783 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:15:29.380  7783  7825 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 18:15:29.393  7783  7825 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 18:15:29.395  7783  7825 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-12 18:15:29.398  1840  7829 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-12 18:15:29.399  1840  7829 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
09-12 18:15:29.401  7151  7151 I AppUp4:CustModeStarterReceiver: onReceive
,09-12 18:15:29.408  7151  7151 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1dc9fc98
09-12 18:15:29.408  7151  7151 D AppUp4:CustFacade: isCustomizationCompleted : false
09-12 18:15:29.408  7151  7151 D AppUp4:CustFacade: isPhone : true
09-12 18:15:29.408  7151  7151 D AppUp4:CustModeStarterReceiver: begin check event
09-12 18:15:29.408  7151  7151 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
09-12 18:15:29.415  1840  5076 I Icing   : updateResources: need to parse e{com.google.android.gms}
09-12 18:15:29.422  7783  7825 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,09-12 18:15:29.433  7783  7825 W AudioCapabilities: Unsupported mime audio/qcelp
09-12 18:15:29.434  1033  1049 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7832 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
09-12 18:15:29.437  7783  7825 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 18:15:29.445  1033  1942 I ActivityManager: Killing 6977:com.lge.sync/1000 (adj 15): empty #17
09-12 18:15:29.456  1033  1541 D WifiService: Client connection lost with reason: 4
,09-12 18:15:29.462  7783  7825 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-12 18:15:29.464  7783  7825 W VideoCapabilities: Unsupported mime video/divx
09-12 18:15:29.466  7783  7825 W VideoCapabilities: Unsupported mime video/divx311
09-12 18:15:29.468  7783  7825 W VideoCapabilities: Unsupported mime video/divx4
,09-12 18:15:29.474  7783  7825 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-12 18:15:29.489  7783  7825 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 18:15:29.493  7783  7825 W AudioCapabilities: Unsupported mime audio/eac3
09-12 18:15:29.494  7783  7825 W AudioCapabilities: Unsupported mime audio/ac3
09-12 18:15:29.495  7783  7825 W AudioCapabilities: Unsupported mime audio/g726
09-12 18:15:29.496  7783  7825 W AudioCapabilities: Unsupported mime audio/wma-voice
09-12 18:15:29.496  7783  7825 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-12 18:15:29.497  7783  7825 W AudioCapabilities: Unsupported mime audio/adpcm
09-12 18:15:29.499  7783  7825 W VideoCapabilities: Unsupported mime video/theora
09-12 18:15:29.501  7783  7825 W VideoCapabilities: Unsupported mime video/mjpg
,09-12 18:15:29.504  1033  1048 W libprocessgroup: failed to open /acct/uid_1000/pid_6977/cgroup.procs: No such file or directory
09-12 18:15:29.524  7832  7832 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:15:29.525  7832  7832 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:29.525  7832  7832 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-12 18:15:29.526  7832  7832 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,09-12 18:15:29.526  7832  7832 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 18:15:29.583  7832  7832 I SystemConfig: BUILD Country: EU
09-12 18:15:29.583  7832  7832 I SystemConfig: BUILD Operator: OPEN
,09-12 18:15:29.624  1033  2036 I ActivityManager: Killing 7179:com.lge.email/u0a23 (adj 15): empty #17
,09-12 18:15:29.762  1033  2020 W libprocessgroup: failed to open /acct/uid_10023/pid_7179/cgroup.procs: No such file or directory
,09-12 18:15:29.779  7832  7852 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
09-12 18:15:29.779  7832  7852 I SystemConfig: existFile = false
09-12 18:15:29.780  7832  7852 I SystemConfig: canReadFile = false
09-12 18:15:29.780  7832  7852 I SystemConfig: systemFeature RCS result false
09-12 18:15:29.780  7832  7852 D SystemConfig: refreshRcsSupport() :false
,09-12 18:15:29.832  1033  2036 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7857 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,09-12 18:15:29.915  7857  7857 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:15:29.916  7857  7857 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 18:15:29.916  7857  7857 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-12 18:15:29.917  7857  7857 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 18:15:30.050  7857  7857 I AppConfig: Total System Memory = 2995761152
,09-12 18:15:30.063  7857  7857 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
09-12 18:15:30.154  1033  1763 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7876 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:15:30.156  1033  1763 I ActivityManager: Killing 7061:com.lge.formmanager/u0a26 (adj 15): empty #17
,09-12 18:15:30.231  1033  1970 W libprocessgroup: failed to open /acct/uid_10026/pid_7061/cgroup.procs: No such file or directory
,09-12 18:15:30.431  7876  7876 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-12 18:15:30.526  7876  7876 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:30.526  7876  7876 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 18:15:30.584  7876  7876 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-12 18:15:30.603  7876  7876 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-12 18:15:30.603  7876  7876 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-12 18:15:30.620  7876  7876 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-12 18:15:30.621  7876  7876 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-12 18:15:30.643  1033  2000 I ActivityManager: Killing 6322:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,09-12 18:15:30.704  1033  2057 W libprocessgroup: failed to open /acct/uid_1000/pid_6322/cgroup.procs: No such file or directory
,09-12 18:15:30.722  2849  2954 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,09-12 18:15:30.728  4892  7916 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-12 18:15:30.753  2849  2954 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@16523a3c on behalf of 7876
,09-12 18:15:30.773  1033  2020 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7918 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
09-12 18:15:30.808  7876  7876 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-12 18:15:30.826  7876  7876 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-12 18:15:30.840  7918  7918 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,09-12 18:15:30.944  1033  1964 I art     : Explicit concurrent mark sweep GC freed 42107(2013KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.666ms total 92.458ms
,09-12 18:15:30.951  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
09-12 18:15:30.951  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
09-12 18:15:30.951  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
09-12 18:15:30.951  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
09-12 18:15:30.951  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
09-12 18:15:30.952  7918  7918 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
09-12 18:15:30.961  7692  7734 D UEI.SmartControl: Internal timer expired: 1
,09-12 18:15:30.962  7692  7734 D UEI.SmartControl: unbind internal service
,09-12 18:15:30.965  7692  7692 D UEI.SmartControl: Service.onUnbind: IControl
09-12 18:15:30.965  7692  7692 D UEI.SmartControl: Service.onDestroy
09-12 18:15:30.965  7692  7692 D UEI.SmartControl: Lock is in USE false
09-12 18:15:30.965  7692  7692 D UEI.SmartControl: unbind internal service
09-12 18:15:30.966  7692  7692 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@ae4a44
09-12 18:15:30.966  7692  7692 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
09-12 18:15:30.966  7692  7692 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
09-12 18:15:30.966  7692  7692 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
09-12 18:15:30.966  7692  7692 W System.err: 	at com.uei.control.Service.c(Unknown Source)
09-12 18:15:30.966  7692  7692 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
09-12 18:15:30.966  7692  7692 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
09-12 18:15:30.966  7692  7692 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
09-12 18:15:30.966  7692  7692 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
09-12 18:15:30.966  7692  7692 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:15:30.966  7692  7692 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 18:15:30.966  7692  7692 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 18:15:30.966  7692  7692 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:15:30.966  7692  7692 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:15:30.967  7692  7692 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 18:15:30.967  7692  7692 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 18:15:30.967  7692  7692 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@ae4a44
09-12 18:15:30.967  7692  7692 D serial_port: close(fd = 25)
09-12 18:15:30.972  7692  7692 I UEI.SmartControl: Serial port is closed.
09-12 18:15:30.972  7692  7692 I UEI.SmartControl: Serial port is closed.
09-12 18:15:30.972  7692  7692 D UEI.SmartControl: Blaster closed
09-12 18:15:30.973  7692  7692 D UEI.SmartControl: Shut down QS...
09-12 18:15:30.973  7692  7692 D UEI.SmartControl: Stopping QS lib
09-12 18:15:30.973  7692  7692 D UEI.SmartControl: QS lib stop result = true
09-12 18:15:30.973  7692  7692 D UEI.SmartControl: Stopped QS lib
09-12 18:15:30.973  7692  7692 D UEI.SmartControl: Stopped file observer...
09-12 18:15:30.973  7692  7692 D UEI.SmartControl: QS shutdown complete
09-12 18:15:30.974  1033  1970 I ActivityManager: Killing 7218:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,09-12 18:15:30.985  1033  1763 V SIM_STK : Menu title from STK is T-Mobile
09-12 18:15:30.995  4892  7916 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 267 ms] updated apps [took 267 ms] 
,09-12 18:15:31.010  1033  2020 W libprocessgroup: failed to open /acct/uid_10046/pid_7218/cgroup.procs: No such file or directory
,09-12 18:15:31.477  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:15:31.477  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19fb6d6a added. We now have 6 listener(s)
09-12 18:15:31.477  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:15:31.491  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:31.491  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3560125b added. We now have 7 listener(s)
,09-12 18:15:31.491  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:31.492  6817  6899 I System.out: IsBluetoothEnabled
09-12 18:15:31.494  1033  2112 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:31.494  1033  2112 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
09-12 18:15:31.494  1033  1095 D BluetoothManagerService: Message: 2
,09-12 18:15:31.500  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:31.501  1033  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:31.501  1033  1964 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,09-12 18:15:31.517  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-12 18:15:31.518  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 18:15:31.518  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-12 18:15:31.519  1033  1095 D BluetoothManagerService: Message: 1
09-12 18:15:31.519  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
09-12 18:15:31.544  1033  1095 D BluetoothManagerService: Message: 20
09-12 18:15:31.544  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15bdd021:true
,09-12 18:15:31.548  7755  7755 D BluetoothAdapterState: make
09-12 18:15:31.553  7755  7755 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
09-12 18:15:31.553  7755  7755 I bluedroid-qcom: init
09-12 18:15:31.555  7755  7963 I BluetoothAdapterState: Entering OffState
09-12 18:15:31.555  7755  7755 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 18:15:31.555  7755  7755 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 18:15:31.555  7755  7755 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 18:15:31.555  7755  7755 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 18:15:31.555  7755  7755 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
09-12 18:15:31.557  7755  7755 I bluedroid-qcom: get_profile_interface socket
09-12 18:15:31.557  7755  7755 I bluedroid-qcom: get_profile_interface map_client
,09-12 18:15:31.561  7755  7967 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-12 18:15:31.554  7966  7966 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:31.554  7966  7966 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:31.572  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,09-12 18:15:31.574  1033  1095 D BluetoothManagerService: Message: 40
09-12 18:15:31.574  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
09-12 18:15:31.575  7755  7770 I bluedroid-qcom: config_hci_snoop_log
09-12 18:15:31.577  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
09-12 18:15:31.577  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
09-12 18:15:31.581  7966  7966 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
09-12 18:15:31.581  7966  7966 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
09-12 18:15:31.581  7966  7966 I LGFTMITEM: [GET_FTM][id=8], offset=16384
09-12 18:15:31.584  7966  7966 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,09-12 18:15:31.591  7966  7966 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
09-12 18:15:31.591  7966  7966 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
09-12 18:15:31.593  7755  7963 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
09-12 18:15:31.593  7755  7963 D BluetoothAdapterProperties: Setting state to 11
09-12 18:15:31.593  7755  7963 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 18:15:31.595  7755  7967 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
09-12 18:15:31.598  7755  7963 I LGBluetoothServiceJni: classInitNative: succeeds
,09-12 18:15:31.601  1033  1095 D BluetoothManagerService: Message: 60
09-12 18:15:31.601  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
09-12 18:15:31.602  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
09-12 18:15:31.606  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:31.606  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 18:15:31.612  6931  6931 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,09-12 18:15:31.616  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 18:15:31.616  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-12 18:15:31.616  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:31.622  7755  7755 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 18:15:31.622  7755  7755 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:31.622  7755  7755 V BluetoothPbapReceiver: ***********state = 11
09-12 18:15:31.627  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 18:15:31.640  7755  7967 D BluetoothAdapterProperties: Name is: G3
,09-12 18:15:31.647  6931  6931 D BluetoothPermissionRequest: onReceive
09-12 18:15:31.652  6931  6931 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,09-12 18:15:31.663  7755  7963 D BluetoothBondStateMachine: make
09-12 18:15:31.669  7755  7963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:31.669  7755  7963 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
09-12 18:15:31.669  7755  7963 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:31.669  7755  7963 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,09-12 18:15:31.670  7755  7981 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 18:15:31.672  7755  7755 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:31.673  7755  7963 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
09-12 18:15:31.674  7755  7755 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 18:15:31.674  7755  7755 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 18:15:31.674  7755  7755 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 18:15:31.674  7755  7755 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:31.674  7755  7755 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
09-12 18:15:31.678  7755  7963 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:31.685  7755  7755 D HeadsetService: Received start request. Starting profile...
,09-12 18:15:31.685  7755  7755 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 18:15:31.686  7755  7755 D LGBluetoothHfpAdapter: Version 1.6
09-12 18:15:31.689  7755  7755 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
09-12 18:15:31.690  7755  7755 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 18:15:31.690  7755  7755 D HeadsetStateMachine: make
09-12 18:15:31.692  7755  7963 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:31.697  7755  7963 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:31.701  7755  7963 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 18:15:31.706  7755  7963 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:31.712  7755  7963 E BluetoothAdapterService: File transfer profiles supported!!
09-12 18:15:31.717  7755  7963 E BluetoothAdapterService: File transfer profiles supported!!
,09-12 18:15:31.725  7755  7755 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:31.725  7755  7755 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 18:15:31.730  7755  7755 D HeadsetStateMachine: max_hf_connections = 1
,09-12 18:15:31.730  7755  7755 I bluedroid-qcom: get_profile_interface handsfree
09-12 18:15:31.731  7755  7963 V LGMDMManager: Create singleton instance
09-12 18:15:31.732  7755  7755 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
09-12 18:15:31.733   322  1383 V AudioPolicyService: registerClient() client 0xb1023f00, uid 1002
09-12 18:15:31.733   322  4265 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
09-12 18:15:31.733   322  4265 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 18:15:31.733   322  4265 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 18:15:31.733  7755  7755 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-12 18:15:31.733   322  1384 V AudioFlinger: registerClient() client 0xb5581628, pid 7755
09-12 18:15:31.734  7755  7963 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 18:15:31.734   322  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:31.734   322  1379 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:31.734  7755  7755 V ToneGenerator: Create Track: 0xb4928080
09-12 18:15:31.734  7755  7755 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
09-12 18:15:31.734  7755  7755 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
09-12 18:15:31.734  1033  2057 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:31.734  1033  2057 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:31.734   322  1383 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-12 18:15:31.734   322  1383 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
09-12 18:15:31.734   322  1378 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:31.734   322  1383 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 18:15:31.734   322  1378 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:31.734  7755  7770 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:31.734   322  1383 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 18:15:31.734  7755  7770 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
09-12 18:15:31.734  1033  1942 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:31.734  7755  7755 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
09-12 18:15:31.734  1033  1942 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:31.735  7755  7770 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:31.735  7755  7770 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
09-12 18:15:31.735   322  1383 I AudioFlinger: isAudioPlaybackHookOn() false
09-12 18:15:31.735  1603  1939 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:31.735  1603  1939 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:31.735  1603  1939 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:31.735  1603  1939 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:31.735  1879  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:31.735  1879  1894 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:31.735  1879  1894 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:31.735  1879  1894 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:31.735   322  4265 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
09-12 18:15:31.7,35   322  4265 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
09-12 18:15:31.735   322  4265 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
09-12 18:15:31.735   322  4265 V AudioPolicyManagerEx: getOutput() returns output 2
09-12 18:15:31.735  3329  3345 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
09-12 18:15:31.735  3329  3345 V AudioSystem: ioConfigChanged() opening already existing output! 4
09-12 18:15:31.735  3329  3345 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
09-12 18:15:31.735  3329  3345 V AudioSystem: ioConfigChanged() opening already existing output! 2
09-12 18:15:31.736  7755  7755 V AudioSystem: getLatency() output 2, latency 50
09-12 18:15:31.736  7755  7755 V AudioSystem: getFrameCount() output 2, frameCount 960
09-12 18:15:31.736  7755  7755 V AudioTrack: createTrack_l() output 2 afLatency 50
09-12 18:15:31.736   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-12 18:15:31.736   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-12 18:15:31.736   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
09-12 18:15:31.736   322   322 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
09-12 18:15:31.736   322   322 V AudioFlinger: createTrack() lSessionId: 23
09-12 18:15:31.737  7755  7755 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
09-12 18:15:31.737   322  1383 V AudioFlinger: acquiring 23 from 7755, for 7755
09-12 18:15:31.737   322  1383 V AudioFlinger:  added new entry for 23
09-12 18:15:31.737  7755  7755 V ToneGenerator: ToneGenerator INIT OK, time: 220287
09-12 18:15:31.737  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:31.738  7755  7987 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
09-12 18:15:31.738  7755  7987 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
09-12 18:15:31.738  7755  7987 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
09-12 18:15:31.738  7755  7987 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
09-12 18:15:31.739   322  4265 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7755
09-12 18:15:31.739   322  4265 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
09-12 18:15:31.739   322  4265 V voice   : voice_set_parameters: enter: bt_samplerate=8000
09-12 18:15:31.739   322  4265 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
09-12 18:15:31.739   322  4265 V compress_voip: voice_extn_compress_voip_set_parameters: exit
09-12 18:15:31.739   322  4265 V voice   : voice_set_parameters: exit with code(0)
09-12 18:15:31.739   322  4265 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
09-12 18:15:31.739   322  4265 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
09-12 18:15:31.739  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:31.739   322  4265 V msm8974_platform: platform_set_parameters: exit with code(0)
09-12 18:15:31.739   322  4265 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
09-12 18:15:31.739   322  4265 V audio_hw_primary: adev_set_parameters: exit with code(0)
09-12 18:15:31.739   322  4265 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
09-12 18:15:31.740  7755  7987 V ToneGenerator: ToneGenerator destructor
09-12 18:15:31.740  7755  7987 V ToneGenerator: stopTone
09-12 18:15:31.740  7755  7987 V ToneGenerator: Delete Track: 0xb4928080
09-12 18:15:31.741  7755  7755 D A2dpService: Received start request. Starting profile...
09-12 18:15:31.741  7755  7987 V AudioTrack: ~AudioTrack, releasing session i,d from 7755 on behalf of 7755
09-12 18:15:31.741   322   322 V AudioFlinger: releasing 23 from 7755 for 7755
09-12 18:15:31.741   322  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
09-12 18:15:31.741   322   322 V AudioFlinger:  decremented refcount to 0
09-12 18:15:31.741   322   322 V AudioFlinger: purging stale effects
09-12 18:15:31.741   322  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
09-12 18:15:31.742   322  1384 V AudioFlinger: PlaybackThread::Track destructor
09-12 18:15:31.742   322  1258 V AudioPolicyService: AudioCommandThread() waking up
09-12 18:15:31.742   322  1258 V AudioPolicyService: AudioCommandThread() processing release output 2
09-12 18:15:31.742   322  1384 V AudioFlinger: removeClient_l() pid 7755, calling pid 322
09-12 18:15:31.742   322  1258 V AudioPolicyManager: releaseOutput() 2
09-12 18:15:31.742   322  1258 V AudioPolicyService: AudioCommandThread() going to sleep
09-12 18:15:31.742  7755  7755 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 18:15:31.743  7755  7755 V Avrcp   : make
09-12 18:15:31.743  7755  7755 D Avrcp   : [BTUI] Use Native AVRCP : init jni
09-12 18:15:31.743  7755  7755 I bluedroid-qcom: get_profile_interface avrcp
09-12 18:15:31.752  7755  7755 V AudioManager: registerRemoteController: size of Media player list: 0
09-12 18:15:31.754  7755  7755 E AudioManager: No RCC entry present to update
09-12 18:15:31.754  7755  7755 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-12 18:15:31.758  7755  7755 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,09-12 18:15:31.759  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
09-12 18:15:31.759  7755  7755 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,09-12 18:15:31.763  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-12 18:15:31.868  1033  2000 V SIM_STK : Menu title from STK is T-Mobile
09-12 18:15:31.868  1033  2000 V SIM_STK : Menu title from STK is T-Mobile
,09-12 18:15:31.995  1033  1573 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,09-12 18:15:32.003  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-12 18:15:32.008  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 18:15:32.008  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 18:15:32.008  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 18:15:32.009  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 18:15:32.009  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 18:15:32.009  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 18:15:32.009  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 18:15:32.009  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 18:15:32.009  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 18:15:32.009  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,09-12 18:15:32.010  7755  7755 I BluetoothA2dpServiceJni: classInitNative
09-12 18:15:32.010  7755  7755 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:15:32.010  7755  7755 D A2dpStateMachine: make
09-12 18:15:32.017  7755  7755 I bluedroid-qcom: get_profile_interface a2dp
09-12 18:15:32.018  7755  7998 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 18:15:32.031  7755  7755 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:15:32.031  7755  7755 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,09-12 18:15:32.032  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:32.033  7755  7755 I BluetoothHidServiceJni: classInitNative: succeeds
09-12 18:15:32.035  7755  7997 D A2dpStateMachine: Enter Disconnected: -2
09-12 18:15:32.037  7755  7755 D HidService: Received start request. Starting profile...
09-12 18:15:32.037  7755  7755 I bluedroid-qcom: get_profile_interface hidhost
09-12 18:15:32.037  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:32.038  7755  7755 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 18:15:32.040  7755  7755 D HealthService: Received start request. Starting profile...
09-12 18:15:32.043  7755  7755 I bluedroid-qcom: get_profile_interface health
09-12 18:15:32.044  7755  7755 I LGBluetoothHealthServiceJni: classInitNative: succeeds
09-12 18:15:32.044  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:32.045  7755  7755 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 18:15:32.049  7755  7755 D PanService: Received start request. Starting profile...
09-12 18:15:32.050  7755  7755 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 18:15:32.050  7755  7755 I bluedroid-qcom: get_profile_interface pan
09-12 18:15:32.060  7755  7755 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
09-12 18:15:32.060  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
,09-12 18:15:32.061  7755  7755 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,09-12 18:15:32.069  7755  7755 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:15:32.069  7755  7755 D BtGatt.GattService: Received start request. Starting profile...
09-12 18:15:32.069  7755  7755 D BtGatt.GattService: start()
09-12 18:15:32.069  7755  7755 I bluedroid-qcom: get_profile_interface gatt
09-12 18:15:32.070  7755  7755 D BtGatt.AdvertiseManager: advertise manager created
09-12 18:15:32.084  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:32.087  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:32.087  7755  7755 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
09-12 18:15:32.089  7755  7755 V BluetoothMapService: BluetoothMapBinder()
,09-12 18:15:32.090  7755  7755 D BluetoothMapService: Received start request. Starting profile...
09-12 18:15:32.090  7755  7755 D BluetoothMapService: start()
09-12 18:15:32.094  7755  7755 D BluetoothMapEmailSettingsLoader: Found 0 applications
09-12 18:15:32.094  7755  7755 D BluetoothMapEmailAppObserver: createReceiver()
09-12 18:15:32.095  7755  7755 D BluetoothMapEmailAppObserver: initObservers()
09-12 18:15:32.095  7755  7755 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
09-12 18:15:32.105  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:32.105  7755  7755 D HeadsetStateMachine: Proxy object connected
,09-12 18:15:32.106  7755  7755 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,09-12 18:15:32.106  7755  7755 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
09-12 18:15:32.112  7755  7755 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 18:15:32.112  7755  7987 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-12 18:15:32.113  7755  7987 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 18:15:32.113  7755  7987 D HeadsetStateMachine: Disconnected process message: 11, size: 0
09-12 18:15:32.115  7755  7755 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 18:15:32.118  7755  7755 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,09-12 18:15:32.123  7755  7755 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 18:15:32.123  7755  7755 V PanService: [BTUI] SIM Extra State :ABSENT
09-12 18:15:32.127  7755  7755 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
09-12 18:15:32.129  7755  7755 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
09-12 18:15:32.130  7755  7755 V BluetoothMapService: Handler(): got msg=1
09-12 18:15:32.131  7755  7963 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
09-12 18:15:32.131  7755  7963 I bluedroid-qcom: enable
,09-12 18:15:32.131  7755  7963 I bt_hci_bdroid: init
09-12 18:15:32.133  7755  7963 I bt_vendor: bt-vendor : init
09-12 18:15:32.133  7755  7963 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 18:15:32.133  7755  7963 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 18:15:32.133  7755  7963 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
09-12 18:15:32.133  7755  7963 D bt_userial_mct: userial_init
09-12 18:15:32.134  7755  8005 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-12 18:15:32.134  7755  7963 D bt_hci_bdroid: set_power 1
09-12 18:15:32.134  7755  7963 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 18:15:32.134  7755  8005 I bt-btu  : btu_task pending for preload complete event
09-12 18:15:32.135  7755  7963 I bt_vendor: Starting hciattach daemon
09-12 18:15:32.135  7755  7963 I bt_vendor: try to set true
09-12 18:15:32.124  8008  8008 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:32.124  8008  8008 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:32.160  8009  8009 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-12 18:15:32.229  8015  8015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-12 18:15:32.241  8016  8016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
09-12 18:15:32.263  8018  8018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-12 18:15:32.274  8019  8019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-12 18:15:32.286  8020  8020 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-12 18:15:32.299  8021  8021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-12 18:15:32.337  8023  8023 I libmdmdetect: ESOC framework not supported
09-12 18:15:32.338  8023  8023 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-12 18:15:32.348  8023  8023 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,09-12 18:15:32.348  8023  8023 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
09-12 18:15:32.348  8023  8023 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
09-12 18:15:32.348  8023  8023 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
09-12 18:15:32.348  8023  8023 D bthci_qcomm_common: [BTUI]     LE: Class 2
09-12 18:15:32.348  8023  8023 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
09-12 18:15:32.348  8023  8023 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
09-12 18:15:32.391  8023  8024 E QC-QMI  : qmi_client [8023] 15: failed to locate client data
09-12 18:15:32.395   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
09-12 18:15:32.395   475   475 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,09-12 18:15:32.438  8025  8025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,09-12 18:15:32.452  8026  8026 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-12 18:15:32.486  7755  7963 I bt_vendor: bluetooth satus is on
09-12 18:15:32.486  7755  7963 D bt_hci_bdroid: preload
09-12 18:15:32.486  7755  8007 D bt_userial_mct: userial_open(port:0)
09-12 18:15:32.486  7755  8007 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-12 18:15:32.490  7755  8007 I bt_vendor: Done intiailizing UART
,09-12 18:15:32.491  7755  8007 I bt_vendor: Done intiailizing UART
09-12 18:15:32.491  7755  8007 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-12 18:15:32.491  7755  8007 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-12 18:15:32.492  7755  8005 I bt-btu  : btu_task received preload complete event
09-12 18:15:32.492  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
09-12 18:15:32.492  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
09-12 18:15:32.494  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
09-12 18:15:32.491  7755  8028 D bt_userial_mct: Entering userial_read_thread()
,09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_HCI,
,09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_HID_HOST
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-12 18:15:32.498  7755  8005 I         : BTE_InitTraceLevels -- TRC_BTIF,
,09-12 18:15:32.599  7755  8005 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
,09-12 18:15:32.599  7755  8005 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0172061 
,09-12 18:15:32.600  7755  8005 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0172061 
,09-12 18:15:32.645  7755  7967 E bt-btif : Calling BTA_HhEnable
09-12 18:15:32.645  7755  7967 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
09-12 18:15:32.645  7755  7967 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,09-12 18:15:32.648  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
09-12 18:15:32.650  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
09-12 18:15:32.650  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
09-12 18:15:32.650  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
09-12 18:15:32.650  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
09-12 18:15:32.650  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
09-12 18:15:32.650  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
09-12 18:15:32.651  7755  7967 D BluetoothAdapterProperties: Name is: G3
09-12 18:15:32.652  7755  7967 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:15:32.653  7755  7967 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 18:15:32.653  7755  7967 D bt_hci_bdroid: postload
09-12 18:15:32.653  7755  8007 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:32.654  7755  8007 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:32.655  7755  8005 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
09-12 18:15:32.655  7755  8007 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:32.655  7755  7967 D bte_conf: Device ID record 1 : primary
09-12 18:15:32.655  7755  7967 D bte_conf:   vendorId            = 00c4
09-12 18:15:32.655  7755  7967 D bte_conf:   vendorIdSource      = 0001
09-12 18:15:32.655  7755  7967 D bte_conf:   product             = 13a1
09-12 18:15:32.655  7755  7967 D bte_conf:   version             = 1000
09-12 18:15:32.655  7755  7967 D bte_conf:   clientExecutableURL = 
09-12 18:15:32.656  7755  7967 D bte_conf:   serviceDescription  = 
09-12 18:15:32.656  7755  7967 D bte_conf:   documentationURL    = 
09-12 18:15:32.656  7755  7967 D bte_conf: bte_load_did_conf no section named DID2.
09-12 18:15:32.654  8033  8033 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-12 18:15:32.666  7755  8005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:32.666  7755  8005 W bt-smp  : Plain text(LSB ~ MSB) = 9d 0a 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:32.666  7755  8005 W bt-smp  : Encrypted text(LSB ~ MSB) = e1 11 ec bc 06 ef 2d 80 c3 c1 c1 00 45 f3 b4 39 
09-12 18:15:32.666  7755  8007 D bt_hci_bdroid: Used up Tx Cmd credits
09-12 18:15:32.666  7755  8005 W bt-btm  : Stopping oneshot timer
09-12 18:15:32.667  7755  7963 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-12 18:15:32.667  7755  7963 D BluetoothAdapterProperties: ScanMode =  20
09-12 18:15:32.667  7755  7963 D BluetoothAdapterProperties: State =  11
09-12 18:15:32.667  7755  7963 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
09-12 18:15:32.667  7755  7963 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
09-12 18:15:32.667  7755  7963 D BluetoothAdapterProperties: Setting state to 12
09-12 18:15:32.668  7755  7963 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 18:15:32.668  7755  7967 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 18:15:32.668  7755  7967 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 18:15:32.654  8033  8033 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:32.679  1033  1095 D BluetoothManagerService: Message: 60
09-12 18:15:32.679  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
09-12 18:15:32.679  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,09-12 18:15:32.684  7755  8028 E bt_mct  : hci lib postload completed
09-12 18:15:32.705  7755  7963 I BluetoothAdapterState: Entering On State
,09-12 18:15:32.717  7755  7967 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 18:15:32.717  7755  7967 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
09-12 18:15:32.721  7755  8005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:32.721  7755  8005 W bt-smp  : Plain text(LSB ~ MSB) = bf b1 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:32.721  7755  8005 W bt-smp  : Encrypted text(LSB ~ MSB) = 6b c4 5b f8 29 00 8c 02 02 58 6a e2 e6 4f df e4 
,09-12 18:15:32.723  7755  8005 W bt-btm  : Stopping oneshot timer
09-12 18:15:32.727  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:32.727  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:32.727  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:32.727  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:32.727  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:32.727  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:32.727  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:32.727  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:32.734  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:15:32.739  7755  8005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:32.739  7755  8005 W bt-smp  : Plain text(LSB ~ MSB) = 4a da 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:32.739  7755  8005 W bt-smp  : Encrypted text(LSB ~ MSB) = ee cc e3 26 77 bc 76 42 39 10 3b f2 12 6b e2 40 
09-12 18:15:32.739  7755  8005 W bt-btm  : Stopping oneshot timer
09-12 18:15:32.751  7755  7963 D LGBluetoothServiceAdapter: [BTUI] OnState
09-12 18:15:32.751  7755  7963 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
09-12 18:15:32.751  7755  7963 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,09-12 18:15:32.754  7755  7963 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
09-12 18:15:32.755  6931  7654 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:15:32.755  7755  7963 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
09-12 18:15:32.761  7755  8005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:32.761  7755  8005 W bt-smp  : Plain text(LSB ~ MSB) = 21 f9 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:32.761  7755  8005 W bt-smp  : Encrypted text(LSB ~ MSB) = 41 2c 0d 11 7e f7 66 a7 80 b9 6b 90 ae 0a 28 53 
09-12 18:15:32.761  7755  8005 W bt-btm  : Stopping oneshot timer
09-12 18:15:32.773  1879  3208 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 18:15:32.783  1879  1879 D BluetoothHeadset: Proxy object connected
09-12 18:15:32.783  6931  6953 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 18:15:32.784  7755  8005 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
09-12 18:15:32.784  7755  8005 W bt-smp  : Plain text(LSB ~ MSB) = a2 68 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-12 18:15:32.784  7755  8005 W bt-smp  : Encrypted text(LSB ~ MSB) = 58 7b 25 18 48 1e 29 d1 08 3a 0c 6b b8 87 c6 39 
09-12 18:15:32.784  7755  8005 W bt-btm  : Stopping oneshot timer
09-12 18:15:32.788  6931  6954 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 18:15:32.791  8047  8047 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
09-12 18:15:32.791  6931  6931 D BluetoothHeadset: Proxy object connected
09-12 18:15:32.791  6931  6931 D HeadsetProfile: Bluetooth service connected
09-12 18:15:32.793  6931  6931 D BluetoothA2dp: Proxy object connected
09-12 18:15:32.793  6931  6931 D A2dpProfile: Bluetooth service connected
09-12 18:15:32.797  6931  6931 D BluetoothMap: Proxy object connected
09-12 18:15:32.797  6931  6931 D MapProfile: Bluetooth service connected
09-12 18:15:32.797  6931  6931 D BluetoothMap: getConnectedDevices()
09-12 18:15:32.797  6931  6953 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 18:15:32.798  7755  7770 V BluetoothMapService: getConnectedDevices()
09-12 18:15:32.800  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:15:32.801  1033  1033 D BluetoothHeadset: Proxy object connected
09-12 18:15:32.802  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:15:32.804  1033  1033 D BluetoothA2dp: Proxy object connected
09-12 18:15:32.804  6931  6954 D BluetoothPan: onBluetoothStateChange on: true
09-12 18:15:32.804  6931  6954 D BluetoothPan: onBluetoothStateChange call bindService
09-12 18:15:32.806  6931  7654 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 18:15:32.807  6931  6931 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:15:32.807  6931  6931 D PanProfile: Bluetooth service connected
09-12 18:15:32.808  1879  1895 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:15:32.809  1879  1879 D BluetoothHeadset: Proxy object connected
09-12 18:15:32.809  1879  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 18:15:32.811  1879  1879 D BluetoothHeadset: Proxy object connected
09-12 18:15:32.811  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
09-12 18:15:32.811  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
09-12 18:15:32.812  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
09-12 18:15:32.812  1033  1095 D BluetoothManagerService: Message: 40
09-12 18:15:32.812  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
09-12 18:15:32.813  6931  6931 D BluetoothInputDevice: Proxy object connected
09-12 18:15:32.813  6931  6931 D HidProfile: Bluetooth service connected
,09-12 18:15:32.816  1967  1967 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:32.817  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
09-12 18:15:32.817  1967  2179 D LGBluetoothAPIService: Message: 1
09-12 18:15:32.817  1967  2179 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
09-12 18:15:32.817  1967  2179 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
09-12 18:15:32.817  1967  2179 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-12 18:15:32.819  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:32.823  7755  7755 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:32.823  7755  7755 D BluetoothMapService: STATE_ON
09-12 18:15:32.829  6931  6931 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,09-12 18:15:32.832  6931  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
09-12 18:15:32.838  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
09-12 18:15:32.838  7755  7755 V BluetoothPbapService: Pbap Service onCreate
09-12 18:15:32.838  7755  7755 V BluetoothPbapService: Starting PBAP service
09-12 18:15:32.840  7755  7755 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
09-12 18:15:32.840  7755  7755 V BluetoothMapService: Handler(): got msg=1
09-12 18:15:32.840  7755  7755 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
09-12 18:15:32.841  7755  7755 V BluetoothPbapService: Pbap Service onBind
09-12 18:15:32.841  7755  8057 D BluetoothMapMasInstance: MAS initSocket()
09-12 18:15:32.841  7755  8057 D BluetoothMapMasInstance:   masId = 00
09-12 18:15:32.841  7755  8057 D BluetoothMapMasInstance:   msgTypes = 0e
09-12 18:15:32.841  7755  8057 D BluetoothMapMasInstance:   masName = SMS/MMS
09-12 18:15:32.841  7755  8057 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,09-12 18:15:32.842  7755  7755 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:32.842  7755  7755 V BluetoothPbapService: state: 12
09-12 18:15:32.842  7755  7755 V BluetoothPbapReceiver: PbapReceiver onReceive 
09-12 18:15:32.842  7755  7755 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:32.842  7755  7755 V BluetoothPbapReceiver: ***********state = 12
09-12 18:15:32.844  7755  7755 V BluetoothPbapService: Handler(): got msg=1
09-12 18:15:32.844  7755  7755 V BluetoothPbapService: Pbap Service startRfcommSocketListener
09-12 18:15:32.845  1033  2057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:32.845  2222  2222 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 18:15:32.845  2222  2222 D c       : Getting all permits...
09-12 18:15:32.845  2222  2222 D a       : Opening database...
09-12 18:15:32.846  7755  8058 V BluetoothPbapService: Pbap Service initSocket
09-12 18:15:32.848  2222  2222 D a       : Opening database auth.proximity.permit_store...
09-12 18:15:32.848  2222  2222 D a       : Closing database...
09-12 18:15:32.849  1033  2112 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:32.849  6931  6931 D DockEventReceiver: finishStartingService: stopping service
09-12 18:15:32.850  6931  6931 D BluetoothPbap: Proxy object connected
09-12 18:15:32.850  6931  6931 D PbapServerProfile: Bluetooth service connected
09-12 18:15:32.850  7755  8057 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:32.856  7755  8057 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
09-12 18:15:32.856  7755  8057 V BluetoothMapMasInstance: Succeed to create listening socket 
09-12 18:15:32.856  7755  8057 D BluetoothMapMasInstance: Accepting socket connection...
,09-12 18:15:32.856  7755  8058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:32.859  7755  7967 D BluetoothAdapterProperties: Scan Mode:21
09-12 18:15:32.859  7755  7967 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
09-12 18:15:32.867  7755  8058 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
09-12 18:15:32.867  7755  8058 V BluetoothPbapService: Succeed to create listening socket 
,09-12 18:15:32.867  7755  8058 V BluetoothPbapService: Accepting socket connection...
09-12 18:15:32.868  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:32.872  6931  6931 D BluetoothPermissionRequest: onReceive
09-12 18:15:32.874  6931  6931 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
09-12 18:15:32.876  6931  6931 D LGBluetoothResetSettingReceiver: return without doing reset settings.
09-12 18:15:32.879  7755  7755 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
09-12 18:15:32.880  7755  7755 I LGBluetoothOppAdapter: [BTUI] startOppService()
,09-12 18:15:32.885  7755  7755 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
09-12 18:15:32.902  7755  7755 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,09-12 18:15:32.902  7755  7755 V BtOppService: onCreate
09-12 18:15:32.907  7755  7755 V BluetoothOppNotification: send message
09-12 18:15:32.910  7755  7755 V BtOppService: Starting RfcommListener
09-12 18:15:32.919  7755  8063 V BtOppService: Deleted complete outbound shares, number =  0
09-12 18:15:32.919  7755  7755 D BluetoothOppPreference: Dumping Names:  
09-12 18:15:32.919  7755  7755 D BluetoothOppPreference: {}
09-12 18:15:32.919  7755  7755 D BluetoothOppPreference: Dumping Channels:  
09-12 18:15:32.919  7755  7755 D BluetoothOppPreference: {}
,09-12 18:15:32.920  7755  7755 V BtOppService: onStartCommand
09-12 18:15:32.921  7755  8066 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 18:15:32.922  7755  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 18:15:32.924  7755  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f5e11c3 on behalf of 
09-12 18:15:32.925  7755  8063 V BtOppService: Deleted complete inbound failed shares, number = 0
09-12 18:15:32.925  7755  8063 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
09-12 18:15:32.926  7755  8063 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14492a40 on behalf of 
09-12 18:15:32.927  7755  7755 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:32.927  7755  7755 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
09-12 18:15:32.929  7755  8066 V BluetoothOppNotification: update too frequent, put in queue
09-12 18:15:32.930  7755  8066 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 18:15:32.930  7755  8066 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 18:15:32.931  7755  7755 V BluetoothOppNotification: new notify threadi!
,09-12 18:15:32.931  7755  7755 V BluetoothOppNotification: send delay message
09-12 18:15:32.932  7755  7755 V BtOppService: start RfcommListener
09-12 18:15:32.933  7755  8067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
09-12 18:15:32.934  7755  8066 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b86ad79 on behalf of 
09-12 18:15:32.934  7755  8067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25c8eabe on behalf of 
09-12 18:15:32.935  7755  8067 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 18:15:32.937  7755  8066 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 18:15:32.937  7755  8067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 18:15:32.937  7755  7755 V BtOppService: RfcommListener started
09-12 18:15:32.937  7755  7755 V BtOppService: ContentObserver received notification
09-12 18:15:32.938  7755  8068 V BtOppRfcommListener: Starting RFCOMM listener....
09-12 18:15:32.938  7755  7755 V BtOppService: ContentObserver received notification
09-12 18:15:32.938  1033  2089 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:32.939  7755  8068 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:32.940  7755  8068 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
09-12 18:15:32.941  7755  8068 V BtOppRfcommListener: Started RFCOMM listener....
09-12 18:15:32.941  7755  8068 I BtOppRfcommListener: Accept thread started.
09-12 18:15:32.941  7755  8068 V BtOppRfcommListener: Accepting connection...
09-12 18:15:32.941  7755  8067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b06071f on behalf of 
09-12 18:15:32.941  7755  8069 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
09-12 18:15:32.942  7755  8069 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
09-12 18:15:32.942  7755  8067 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 18:15:32.944  7755  8067 V BluetoothOppNotification: outbound notification was removed.
09-12 18:15:32.944  7755  8067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 18:15:32.944  7755  8069 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38b6aa6c on behalf of 
09-12 18:15:32.945  7755  8067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@93ba835 on behalf of 
09-12 18:15:32.946  7755  8069 V BluetoothOppNotification: update too frequent, put in queue
09-12 18:15:32.946  7755  8067 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-12 18:15:32.947  7755  8069 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
09-12 18:15:32.950  7755  8067 V BluetoothOppNotification: inbound notification was removed.
09-12 18:15:32.951  7755  8067 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 18:15:32.952  7755  8067 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29a4f4ca on behalf of 
09-12 18:15:32.958  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
,09-12 18:15:32.958  7755  7755 V BluetoothFtpService: Ftp Service onCreate
09-12 18:15:32.958  7755  7755 I BluetoothFtpService: Ftp Service onCreate
09-12 18:15:32.959  7755  7755 V BluetoothFtpService: Ftp Service onStartCommand
09-12 18:15:32.959  7755  7755 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:32.959  7755  7755 V BluetoothFtpService: Starting Listening on sockets
09-12 18:15:32.959  7755  7755 V BluetoothSapReceiver: [BTUI] checkServiceStart
09-12 18:15:32.959  7755  7755 V BluetoothSapReceiver: [BTUI] region:EU country:EU
09-12 18:15:32.959  7755  7755 V BluetoothSapReceiver: SapReceiver onReceive 
09-12 18:15:32.960  7755  7755 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:32.960  7755  7755 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
09-12 18:15:32.960  7755  7755 V BluetoothSapReceiver: Calling SAP service start service with action = null
09-12 18:15:32.962  7755  7755 V BluetoothFtpService: Handler(): got msg=1
09-12 18:15:32.964  7755  7755 V BluetoothFtpService: Ftp Service startRfcommSocketListener
09-12 18:15:32.964  7755  7755 V BluetoothFtpService: Ftp Service initSocket
09-12 18:15:32.968  1033  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:32.969  7755  7755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:32.970  7755  7755 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
09-12 18:15:32.970  7755  7755 V BluetoothFtpService: Succeed to create listening socket on channel 20
09-12 18:15:32.972  7755  8070 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,09-12 18:15:32.987  7755  7755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@228b5f57
,09-12 18:15:32.988  7755  7755 V BluetoothSapService: Sap Service onCreate
09-12 18:15:32.990  7755  7755 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:15:32.990  7755  7755 V BluetoothSapService: state: 12
,09-12 18:15:32.990  7755  7755 V BluetoothSapService: Starting SAP server process
09-12 18:15:32.991  7755  7755 V BluetoothSapService: SAP Service startRfcommListenerThread
09-12 18:15:32.984  8071  8071 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:32.984  8071  8071 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:32.994  7755  8072 V BluetoothSapService: Sap Service initRfcommSocket
09-12 18:15:32.994  1033  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:32.995  7755  8072 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:15:32.997  7755  8072 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
09-12 18:15:32.997  7755  8072 V BluetoothSapService: Succeed to create listening socket 
09-12 18:15:32.997  7755  8072 V BluetoothSapService: Accepting socket connection...
09-12 18:15:33.006  8071  8071 V BT_SAP  : Event pipe created
09-12 18:15:33.006  8071  8071 V BT_SAP  : create_server_socket qcom.sap.server
09-12 18:15:33.006  8071  8071 V BT_SAP  : created socket fd 6
,09-12 18:15:33.545  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:33.545  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:33.545  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:33.545  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:15:33.545  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:33.545  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:33.545  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:33.545  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:15:33.561  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:33.564  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:15:33.564  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce1baf8 added. We now have 8 listener(s)
09-12 18:15:33.564  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:15:33.580  1033  2112 D WifiServiceImplEx: setWifiEnabled: false pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 18:15:33.581  1033  2112 D WifiService: setWifiEnabled: false pid=6817, uid=10118
09-12 18:15:33.581  1033  2112 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:15:33.588  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:33.589  1033  1942 D WifiServiceImplEx: setWifiEnabled: true pid=6817, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
09-12 18:15:33.590  1033  1942 D WifiService: setWifiEnabled: true pid=6817, uid=10118
09-12 18:15:33.590  1033  1942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 18:15:33.611  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,09-12 18:15:33.611  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
09-12 18:15:33.611  1033  1033 D Ulp_jni : JNI:system_update. Event-4
09-12 18:15:33.612  1033  1536 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
09-12 18:15:33.612  1033  1536 I LGFTMITEM: [GET_FTM][id=6], offset=12288
09-12 18:15:33.615  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
09-12 18:15:33.615  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 18:15:33.615  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
09-12 18:15:33.615  1033  1536 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
09-12 18:15:33.615  1033  1536 I WifiUtil: Intf0MacAddress=C49A027FFB5D
09-12 18:15:33.615  1033  1536 E WifiHW  : unknown target_country: EU , set to default
09-12 18:15:33.615  1033  1536 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
09-12 18:15:33.615  1033  1536 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
09-12 18:15:33.615  1033  1536 I WifiUtil: gEnableBmps=1
09-12 18:15:33.934  7755  7755 V BluetoothOppNotification: new notify threadi!
09-12 18:15:33.934  7755  7755 V BluetoothOppNotification: send delay message
,09-12 18:15:33.951  7755  8086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,09-12 18:15:33.954  7755  8086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3fdbbb17 on behalf of 
,09-12 18:15:33.962  7755  8086 V BluetoothOppNotification: mUpdateCompleteNotification = true
09-12 18:15:33.964  7755  8086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
09-12 18:15:33.965  7755  8086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e59db04 on behalf of 
09-12 18:15:33.966  7755  8086 V BluetoothOppNotification: outbound: succ-0  fail-0
09-12 18:15:33.967  7755  8086 V BluetoothOppNotification: outbound notification was removed.
09-12 18:15:33.968  7755  8086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
09-12 18:15:33.969  7755  8086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@615a8ed on behalf of 
09-12 18:15:33.969  7755  8086 V BluetoothOppNotification: inbound: succ-0  fail-0
,09-12 18:15:34.000  7755  8086 V BluetoothOppNotification: inbound notification was removed.
09-12 18:15:34.000  7755  8086 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
09-12 18:15:34.005  7755  8086 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4ff5322 on behalf of 
,09-12 18:15:34.181   318   893 D SoftapController: Softap fwReload - Ok
,09-12 18:15:34.224  1033  1536 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (605ms)
,09-12 18:15:34.240  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:15:34.240  1033  1095 D Tethering: InitialState.processMessage what=4
,09-12 18:15:34.251   318   893 D CommandListener: Setting iface cfg
09-12 18:15:34.251   318   893 D CommandListener: Trying to bring down wlan0
09-12 18:15:34.254   318   893 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:15:34.260  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:15:34.264  1033  1536 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
09-12 18:15:34.264  8094  8094 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-12 18:15:34.278  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 18:15:34.278  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
09-12 18:15:34.278  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 18:15:34.274  8094  8094 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:34.286  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:34.294  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
09-12 18:15:34.296  1033  1536 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-12 18:15:34.296  1033  1536 D WifiMonitor: connecting to supplicant
09-12 18:15:34.301  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 18:15:34.302  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 18:15:34.302  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 18:15:34.302  6931  6931 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,09-12 18:15:34.309  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
09-12 18:15:34.311  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 18:15:34.312  6931  6931 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 18:15:34.312  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 18:15:34.312  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 18:15:34.312  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 18:15:34.312  6931  6931 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 18:15:34.312  6931  6931 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 18:15:34.312  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:34.315  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 18:15:34.315  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 18:15:34.315  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 18:15:34.315  6931  6931 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 18:15:34.316  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,09-12 18:15:34.319  6931  6931 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 18:15:34.319  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
09-12 18:15:34.319  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 18:15:34.319  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 18:15:34.319  6931  6931 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 18:15:34.319  6931  6931 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 18:15:34.326  8094  8094 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 18:15:34.354  1033  1763 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8111 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,09-12 18:15:34.363  8094  8094 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 18:15:34.363  8094  8094 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,09-12 18:15:34.425  8094  8094 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:15:34.439  1033  2036 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8133 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
09-12 18:15:34.442  8111  8131 W FormManager: Network not available. Please check & try again.
09-12 18:15:34.447  8111  8132 V FormManager: Network unavailable.
09-12 18:15:34.448  8111  8132 V FormManager: Network unavailable.
09-12 18:15:34.460  1033  2036 I ActivityManager: Killing 7240:com.android.chrome/u0a57 (adj 15): empty #17
,09-12 18:15:34.470  8094  8094 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
09-12 18:15:34.472  8094  8094 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,09-12 18:15:34.473  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
09-12 18:15:34.473  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
09-12 18:15:34.474  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
09-12 18:15:34.474  1033  1536 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
09-12 18:15:34.474  1033  8152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
09-12 18:15:34.474  1033  8152 D WifiMonitor: Dropping event because (p2p0) is stopped
09-12 18:15:34.474  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:34.474  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:34.474  1033  1536 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:34.475  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:34.475  1033  1536 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
09-12 18:15:34.475  1033  1536 D WifiNative-wlan0: doString: [DRIVER MACADDR]
09-12 18:15:34.475  1033  1536 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
09-12 18:15:34.475  1033  1536 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
09-12 18:15:34.475  1033  1536 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
09-12 18:15:34.482  1033  2000 W libprocessgroup: failed to open /acct/uid_10057/pid_7240/cgroup.procs: No such file or directory
09-12 18:15:34.483  1033  1536 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
09-12 18:15:34.483  1033  1536 E WifiStateMachine: useWiFiOffloading() : false
09-12 18:15:34.483  1033  1536 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
09-12 18:15:34.484  1033  1536 D WifiNative-wlan0: doBoolean: SET update_config 1
09-12 18:15:34.484  1033  1536 D WifiNative-wlan0: SET update_config 1: returned true
09-12 18:15:34.484  1033  1536 D WifiConfigStore: Loading config and enabling all networks 
09-12 18:15:34.484  1033  1536 D WifiNative-wlan0: doString: [LIST_NETWORKS]
09-12 18:15:34.484  1033  1536 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
09-12 18:15:34.487  1033  1536 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
09-12 18:15:34.488  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.488  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.488  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.488  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.488  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-12 18:15:34.489  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,09-12 18:15:34.492  1033  1540 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
09-12 18:15:34.493  1967  1967 D WfdService: Waiting for WifiP2p enabling
09-12 18:15:34.493  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:34.496  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:34.496  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:34.496  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:34.496  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:34.496  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:34.496  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:34.496  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:34.496  6817  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:34.496  1033  1536 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
09-12 18:15:34.496  1033  1536 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-12 18:15:34.497  1033  1536 D WifiStateMachine: enableVerboseLogging : level 2
09-12 18:15:34.497  1033  1536 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
09-12 18:15:34.497  1033  1536 D WifiNative-wlan0: SET device_name g3_global_com: returned true
09-12 18:15:34.497  1033  1536 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
09-12 18:15:34.497  6817  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:34.497  1033  1536 D WifiNative-wlan0: SET manufacturer LGE: returned true
09-12 18:15:34.498  1033  1536 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
09-12 18:15:34.498  1033  1536 D WifiNative-wlan0: SET model_name LG-D855: returned true
09-12 18:15:34.498  1033  1536 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
09-12 18:15:34.498  1033  1536 D WifiNative-wlan0: SET model_number LG-D855: returned true
09-12 18:15:34.498  1033  1536 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
09-12 18:15:34.498  1033  1536 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
09-12 18:15:34.498  1033  1536 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
09-12 18:15:34.499  1033  1536 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
09-12 18:15:34.499  1033  1536 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
09-12 18:15:34.499  1033  1536 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
09-12 18:15:34.499  1033  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 18:15:34.499  1033  1536 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
09-12 18:15:34.499  1033  1536 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
09-12 18:15:34.499  1033  1536 D WifiNative-HAL: Setting external_sim to 1
09-12 18:15:34.500  1033  1536 D WifiNative-wlan0: doBoolean: SET external_sim 1
09-12 18:15:34.500  1033  1536 D WifiNative-wlan0: SET external_sim 1: returned true
09-12 18:15:34.500  1033  1536 I WifiNative-HAL: startHal
09-12 18:15:34.500  1967  1967 D WfdsService: Supplicant Connection state is changed : true
09-12 18:15:34.500  1033  1536 D wifi    : setting scan oui 0xaf6251a0
09-12 18:15:34.500  1967  2347 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
09-12 18:15:34.500  1967  2347 D WfdsService: Set the WFDS Monitor: true
09-12 18:15:34.500  1967  2347 D WfdsMonitor: WfdsMonitorThread create
09-12 18:15:34.500  1967  2347 D WfdsMonitor: WFDS Monitor is created and started
09-12 18:15:34.500  1967  2347 D WfdsService: WiFi: Supplicant connection re-established
09-12 18:15:34.500  8094  8094 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
09-12 18:15:34.500  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID,=00:00:00:00:00:00 SSID=]
09-12 18:15:34.501  1033  1536 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 18:15:34.501  1033  1536 I WifiNative-HAL: startHal
09-12 18:15:34.501  1033  1536 D wifi    : setting scan oui 0xaf6251a0
09-12 18:15:34.501  1033  1536 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
09-12 18:15:34.501  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 18:15:34.501  1033  1536 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
09-12 18:15:34.501  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
09-12 18:15:34.501  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
09-12 18:15:34.501  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
09-12 18:15:34.501  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
09-12 18:15:34.501  1033  8152 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
09-12 18:15:34.501  1033  8152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
09-12 18:15:34.501  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
09-12 18:15:34.501  7783  7783 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.502  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 18:15:34.502  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 18:15:34.502  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 18:15:34.502  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
09-12 18:15:34.503  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
09-12 18:15:34.503  1967  8153 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
09-12 18:15:34.504  1967  8153 E CtrlSupplicant: Succeed to open control connection
09-12 18:15:34.504  1967  8153 E CtrlSupplicant: Succeed to open monitor connection
09-12 18:15:34.504  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
09-12 18:15:34.504  1967  8153 D WfdsMonitor: Supplicant connection established
09-12 18:15:34.504  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 18:15:34.505  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 18:15:34.505  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 18:15:34.505  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
09-12 18:15:34.505  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
09-12 18:15:34.505  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
09-12 18:15:34.505  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
09-12 18:15:34.505  8094  8094 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
09-12 18:15:34.505  1967  2347 D WfdsService: Connected to the supplicant for wfds
09-12 18:15:34.505  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
09-12 18:15:34.505  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
09-12 18:15:34.506  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
09-12 18:15:34.506  1033  1536 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
09-12 18:15:34.506  1033  1536 E WifiNative: : [223,042,302 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
09-12 18:15:34.506  1033  1536 D WifiNative-wlan0: doBoolean: RECONNECT
09-12 18:15:34.507  1033  1536 D WifiNative-wlan0: RECONNECT: returned true
09-12 18:15:34.507  1033  1536 D WifiNative-wlan0: doString: [STATUS]
09-12 18:15:34.507  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
09-12 18:15:34.507  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
09-12 18:15:34.507  1033  1536 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 18:15:34.507  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 18:15:34.508  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
09-12 18:15:34.508  1033  1535 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.510  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 18:15:34.510  1033  1033 D RttService: SCAN_AVAILABLE : 3
09-12 18:15:34.511  1033  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.511  1033  1554 I WifiNative-HAL: startHal
09-12 18:15:34.511  1033  1554 D wifi    : getting scan capabilities on interface[1] = 0xaf6251a0
09-12 18:15:34.511  1033  1554 D wifi    : failed to get capabilities : -3
09-12 18:15:34.511  1033  1554 E WifiScanningService: could not get scan capabilities
09-12 18:15:34.511   318   893 D CommandListener: Setting iface cfg
09-12 18:15:34.511  1033  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.511   318   893 D CommandListener: Trying to bring up p2p0
09-12 18:15:34.511  1033  1535 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 18:15:34.511  1033  1535 D LGWifiP2pService: P2pEnablingState
09-12 18:15:34.511  1033  1535 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.511  1033  1535 D LGWifiP2pService: P2p socket connection successful
09-12 18:15:34.511  1033  1535 D LGWifiP2pService: P2pEnabledState
09-12 18:15:34.512  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
09-12 18:15:34.512  1033  1536 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
09-12 18:15:34.512  1033  1536 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
09-12 18:15:34.513  1033  1536 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
09-12 18:15:34.513  1033  1536 E WifiStateMachine:  DisconnectedState what:132106 1 0
09-12 18:15:34.513  1033  1536 E WifiStateMachine:  ConnectModeState what:132106 1 0
09-12 18:15:34.513  1967  1967 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
09-12 18:15:34.513  1967  1967 D WfdsService: WifiP2pState is changed : true
09-12 18:15:34.513  1967  2347 D WfdsService: Receive the WFDS_ENABLE Method
09-12 18:15:34.513  1967  2347 D WfdsService: Set the WFDS Monitor: true
09-12 18:15:34.513  1033  1536 E WifiStateMachine:  DriverStartedState what:132106 1 0
09-12 18:15:34.513  1967  2347 D WfdsService: Connected to the supplicant for wfds
09-12 18:15:34.513  1033  1536 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
09-12 18:15:34.513  1967  2347 D WfdsJNI : doCommand: WFDS_SET TRUE
09-12 18:15:34.514  8094  8094 E wpa_supplicant: nWIFIDualbandAPConnection: 1
09-12 18:15:34.514  8094  8094 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
09-12 18:15:34.514  1967  2347 D WfdsService: selectPreferredScanChannel [36]
09-12 18:15:34.514  1967  2347 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
09-12 18:15:34.514  1033  1535 D LGWifiP2pService: sending p2p connection changed broadcast
09-12 18:15:34.516  1033  1536 E WifiStateMachine:  DisconnectedState what:132096 -100 0
09-12 18:15:34.516  1033  1536 E WifiStateMachine:  ConnectModeState what:132096 -100 0
09-12 18:15:34.516  1033  1536 E WifiStateMachine:  DriverStartedState what:132096 -100 0
09-12 18:15:34.516  1033  1536 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
09-12 18:15:34.516  8094  8094 E wpa_supplicant: disconnect_rssi_lvl: -100
09-12 18:15:34.516  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=223052  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 18:15:34.517  1967  1967 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
09-12 18:15:34.517  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=223053  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 18:15:34.518  1967  1967 D WfdsService: isConnected: false
09-12 18:15:34.518  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 18:15:34.518  1033  1536 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 18:15:34.518  1033  1536 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
09-12 18:15:34.518  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
09-12 18:15:34.519  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 18:15:34.519  8094  8094 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:34.519  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 18:15:34.519  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:34.519  1033  8152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:34.519  1033  8152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:34.520  8094  8094 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 18:15:34.520  8094  8094 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.520  1033  8152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:34.520  1033  8152 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.520  1033  8152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.520  1033  8152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.520  8094  8094 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.521  1967  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:34.521  1967  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:34.521  1033  8152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:34.521  1033  8152 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.521  1033  8152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.521  1033  8152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.522  1033  1536 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
09-12 18:15:34.524  1033  1536 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
09-12 18:15:34.524  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:34.524  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:34.524  1033  1536 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
09-12 18:15:34.525  1033  1536 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
09-12 18:15:34.525  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
09-12 18:15:34.525  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:34.525  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
09-12 18:15:34.525  8094  8094 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 18:15:34.526  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
09-12 18:15:34.526  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 18:15:34.526  1033  8152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 18:15:34.527  1033  8152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
09-12 18:15:34.527  1033  1536 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
09-12 18:15:34.527  1033  1536 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
09-12 18:15:34.527  1033  1536 D WifiNative-wlan0: BSS_FLUSH 0: returned true
09-12 18:15:34.527  1033  1536 D WifiNative-wlan0: doBoolean: SCAN
09-12 18:15:34.528  1033  1536 D WifiNative-wlan0: SCAN: returned false
09-12 18:15:34.528  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=223064  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 18:15:34.529  1033  1535 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
09-12 18:15:34.529  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.529  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.529  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 18:15:34.529  1033  1535 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
09-12 18:15:34.529  1033  1535 D WifiNative-p2p0: doBoolean: SET device_name G3
09-12 18:15:34.530  1033  1535 D WifiNative-p2p0: SET device_name G3: returned true
09-12 18:15:34.530  1033  1535 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
09-12 18:15:34.530  1033  1535 D LGWifiP2pService: before postfix = G3
09-12 18:15:34.530  1033  1535 D WifiServerServiceExt: postfix byte check : 2
09-12 18:15:34.530  1033  1535 D LGWifiP2pService: after postfix = G3
09-12 18:15:34.530  1033  1535 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
09-12 18:15:34.531  1033  1535 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
09-12 18:15:34.531  1033  1535 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
09-12 18:15:34.531  1033  1535 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
09-12 18:15:34.531  1033  1535 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
09-12 18:15:34.531  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.532  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:34.532  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
09-12 18:15:34.532  1033  1535 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
09-12 18:15:34.532  1033  1535 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
09-12 18:15:34.532  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=223068  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
09-12 18:15:34.532  1033  1535 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
09-12 18:15:34.532  1033  1535 D WifiNative-HAL: p2pGetDeviceAddress
09-12 18:15:34.533  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:34.533  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
09-12 18:15:34.533  1033  1535 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
09-12 18:15:34.533  1033  1535 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
09-12 18:15:34.533  1033  1535 D WifiNative-p2p0: doBoolean: P2P_FLUSH
09-12 18:15:34.534  1033  1535 D WifiNative-p2p0: P2P_FLUSH: returned true
09-12 18:15:34.534  1033  1535 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
09-12 18:15:34.534  1967  1967 I WfdStateTracker: handleP2pThisDeviceChanged
09-12 18:15:34.534  1967  1967 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
09-12 18:15:34.534  1967  1967 D WfdsService: Update P2p Interface State: 3
09-12 18:15:34.534  1033  1535 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
09-12 18:15:34.534  1033  1536 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:34.534  1033  1535 D WifiNative-p2p0: doString: [LIST_NETWORKS]
09-12 18:15:34.534  1033  1536 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:34.534  1033  1535 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
09-12 18:15:34.534  1033  1535 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
09-12 18:15:34.534  1033  1536 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:34.535  8133  8133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:34.535  1033  1536 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:34.535  1033  1536 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
09-12 18:15:34.536  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 18:15:34.536  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:34.537  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-12 18:15:34.544  1033  1535 D WifiNative-p2p0: SAVE_CONFIG: returned true
09-12 18:15:34.544  1033  1535 D LGWifiP2pService: sending p2p persistent groups changed broadcast
09-12 18:15:34.544  1033  1535 D LGWifiP2pService: InactiveState
09-12 18:15:34.544  1033  1535 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.544  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.544  1033  1535 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
09-12 18:15:34.544  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
09-12 18:15:34.544  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:34.545  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:34.545  8094  8094 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:34.545  1033  8152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 18:15:34.545  1033  8152 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:34.545  1033  8152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:34.545  1033  8152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
09-12 18:15:34.545  1967  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
09-12 18:15:34.545  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:34.545  8094  8094 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
09-12 18:15:34.545  8094  8094 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.546  1033  1535 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
09-12 18:15:34.546  1033  1573 I ActivityManager: Killing 7261:com.lge.drmservice/u0a62 (adj 15): empty #17
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1967  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:34.546  1033  8152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:34.546  1033  8152 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  8152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  8152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.546  8094  8094 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1967  8153 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  8152 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
09-12 18:15:34.546  1033  8152 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  8152 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.546  1033  8152 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-12 18:15:34.546  1033  1535 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:34.547  1033  1033 E WifiServerServiceExt: No p2p device connected
09-12 18:15:34.547  1967  2347 W WfdsService: DefaultState - msg [9441285] is not handled
09-12 18:15:34.571  1033  1942 W libprocessgroup: failed to open /acct/uid_10062/pid_7261/cgroup.procs: No such file or directory
,09-12 18:15:34.594  8133  8133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 18:15:34.596  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
09-12 18:15:34.599  8111  8157 W FormManager: Network not available. Please check & try again.
09-12 18:15:34.604  8111  8158 V FormManager: Network unavailable.
09-12 18:15:34.605  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 18:15:34.613  8111  8158 V FormManager: Network unavailable.
,09-12 18:15:34.626  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,09-12 18:15:34.626  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:15:34.626  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:34.626  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:34.626  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:34.626  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:34.626  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:15:34.626  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:15:34.626  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:15:34.626  4615  4615 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
09-12 18:15:34.629  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:15:34.629  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:34.632  4615  4615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
09-12 18:15:34.637  4615  8159 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
09-12 18:15:34.637  6817  6899 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 18:15:34.639  6817  6899 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-12 18:15:34.642  6817  6899 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@18d52dba Bundle[{}]
09-12 18:15:34.643  6817  6899 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 18:15:34.643  6817  6899 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-12 18:15:34.644  6817  6899 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-12 18:15:34.646  6817  6899 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 18:15:34.647  6817  6899 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 18:15:34.647  4615  8160 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
09-12 18:15:34.648  4615  8160 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
09-12 18:15:34.648  6817  6899 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-12 18:15:34.656  6817  6899 I System.out: Running OutgoingSocketThread
09-12 18:15:34.657  6817  8161 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 890)
,09-12 18:15:34.659  6817  8161 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40865
09-12 18:15:34.659  6817  8161 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-12 18:15:34.683  1033  2112 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8162 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,09-12 18:15:34.798  8162  8162 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 18:15:34.798  8162  8162 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,09-12 18:15:34.809  8162  8162 V [BNRBootReceiver]: Boot Receiver Return
09-12 18:15:34.809  8162  8162 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
09-12 18:15:34.862  1033  2000 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8180 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,09-12 18:15:34.865  1033  2000 I ActivityManager: Killing 7278:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
09-12 18:15:34.924  1033  2020 W libprocessgroup: failed to open /acct/uid_10085/pid_7278/cgroup.procs: No such file or directory
,09-12 18:15:34.947  8180  8180 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,09-12 18:15:34.970  8180  8180 D PluginManager: init()
,09-12 18:15:35.147  8094  8094 E wpa_supplicant: USIM:  scard_init function
09-12 18:15:35.147  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
09-12 18:15:35.147  1033  8152 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
09-12 18:15:35.147  8094  8094 I wpa_supplicant: Trying to associate with SSID 'NG700'
09-12 18:15:35.148  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
09-12 18:15:35.148  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
09-12 18:15:35.148  1033  8152 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
09-12 18:15:35.148  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
09-12 18:15:35.148  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,09-12 18:15:35.158  1033  1536 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 18:15:35.159  1033  1536 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 18:15:35.161  1033  1536 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 18:15:35.161  1033  1536 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
09-12 18:15:35.161  1033  1536 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,09-12 18:15:35.181  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=223717  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 18:15:35.184  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.184  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.184  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 18:15:35.186  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.186  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-12 18:15:35.188  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.192  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=223728  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
09-12 18:15:35.194  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:35.194  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
09-12 18:15:35.274  8094  8094 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 18:15:35.278  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
09-12 18:15:35.279  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
09-12 18:15:35.279  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
09-12 18:15:35.279  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
09-12 18:15:35.279  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:35.279  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 18:15:35.281  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=223816  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 18:15:35.281  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=223817  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
09-12 18:15:35.281  1033  1536 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223818
09-12 18:15:35.282  1033  1536 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223818
09-12 18:15:35.282  1033  1536 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223818
09-12 18:15:35.284  8094  8094 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:15:35.284  8094  8094 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 18:15:35.285  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:35.285  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 18:15:35.285  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
09-12 18:15:35.285  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:15:35.285  1033  8152 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:15:35.285  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
09-12 18:15:35.285  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 18:15:35.286  1033  8152 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-12 18:15:35.289  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:35.289  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,09-12 18:15:35.295  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 18:15:35.296  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223832
09-12 18:15:35.296  1033  1536 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=223832
09-12 18:15:35.298  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=223834  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
09-12 18:15:35.300  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.300  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:35.300  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.300  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.300  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
09-12 18:15:35.301  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.304  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=223839  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,09-12 18:15:35.304  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.305  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.305  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
09-12 18:15:35.305  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:35.305  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
09-12 18:15:35.306  1033  1536 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=223842  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 18:15:35.307  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=223843  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
09-12 18:15:35.307  1033  1536 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223843
09-12 18:15:35.308  1033  1536 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=223844
09-12 18:15:35.308  1033  1536 D WifiNative-wlan0: doString: [STATUS]
09-12 18:15:35.309  1033  1536 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
09-12 18:15:35.310  1033  8152 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
09-12 18:15:35.310  1033  8152 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
09-12 18:15:35.310  1033  1536 I WifiServiceExtension: setVHTCapabilityType  : false
09-12 18:15:35.315  1033  1536 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
09-12 18:15:35.315  1033  1536 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,09-12 18:15:35.318  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.318  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.318  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 18:15:35.320  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.320  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.321  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
09-12 18:15:35.322  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.322  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:35.323  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.324  1033  1377 V AlarmManager: RTC_WAKEUP set : Alarm{35341454 type 0 when 1473696930012 com.google.android.gms} when 1473696930012
09-12 18:15:35.324  1033  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{12566ffd type 2 when 222694 android} when 222694
09-12 18:15:35.326  1033  1536 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
09-12 18:15:35.326  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:15:35.326  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 18:15:35.326  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.326  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:35.326  1033  1542 D ConnectivityService: Got NetworkAgent Messenger
09-12 18:15:35.326  1033  1542 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-12 18:15:35.326  1033  1542 D ConnectivityService: NetworkAgent connected
09-12 18:15:35.326  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 18:15:35.326  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
09-12 18:15:35.327  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:35.329  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.329  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:35.331  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.338  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 18:15:35.338  1033  1536 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 18:15:35.339  1033  1536 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
09-12 18:15:35.339  1033  1536 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
09-12 18:15:35.339  1033  1536 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,09-12 18:15:35.343  1033  1536 D WifiNative-wlan0: SAVE_CONFIG: returned true
09-12 18:15:35.345   318   893 D CommandListener: Setting iface cfg
09-12 18:15:35.347  1033  1536 E WifiStateMachine: Start Dhcp Watchdog 3
09-12 18:15:35.347  1033  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223883  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:35.348  1033  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223884  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:35.348  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=223884  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:35.349  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:35.349  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:35.349  1033  8210 D DhcpStateMachine: StoppedState
09-12 18:15:35.350  1033  8210 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:35.350  1033  1536 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:35.350  1033  8210 D DhcpStateMachine: WaitBeforeStartState
09-12 18:15:35.350  1033  1536 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:35.350  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:35.351  1033  1536 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
09-12 18:15:35.352  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:35.352  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
09-12 18:15:35.353  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:35.353  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
09-12 18:15:35.353  1033  1536 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=223889  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:35.353  1033  1536 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=223889  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:35.354  1033  1536 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=223890  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
09-12 18:15:35.355  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13546] from screen [on:0 period:523152827] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,09-12 18:15:35.356  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:523152828] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
09-12 18:15:35.356  1033  1536 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,09-12 18:15:35.360  1033  1542 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
09-12 18:15:35.360  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:35.360  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.360  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.361  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.361  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.362  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.362  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.362  1033  1542 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-12 18:15:35.370  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:35.370  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,09-12 18:15:35.374  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=127,0,0
09-12 18:15:35.375  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=127,0,0
09-12 18:15:35.375  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
09-12 18:15:35.375  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,09-12 18:15:35.376  1033  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
09-12 18:15:35.376  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 0
09-12 18:15:35.376  1033  1536 D WifiNative-wlan0: SET ps 0: returned true
09-12 18:15:35.376  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
09-12 18:15:35.377  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
09-12 18:15:35.377  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
09-12 18:15:35.377  1033  1535 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22a1561c target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:35.377  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@22a1561c target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:35.377  1033  8210 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:35.377  1033  8210 D DhcpStateMachine: DHCP Start wake lock is acquired.
09-12 18:15:35.378  1033  1536 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
09-12 18:15:35.378  1033  1536 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 18:15:35.378  1033  1536 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 18:15:35.379   318   893 D CommandListener: Setting iface cfg
09-12 18:15:35.380   318   893 D CommandListener: Trying to bring up wlan0
09-12 18:15:35.380  1033  1536 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
09-12 18:15:35.382  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-12 18:15:35.382  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
09-12 18:15:35.383  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.383  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.384  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.384  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.385  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.385  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
09-12 18:15:35.385  1033  1542 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-12 18:15:35.386  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
09-12 18:15:35.386  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
,09-12 18:15:35.388  1033  1535 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:35.388  1033  1535 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:35.388  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,09-12 18:15:35.388  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2,
09-12 18:15:35.389  1033  1536 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
09-12 18:15:35.389  1033  1536 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
09-12 18:15:35.389  8094  8094 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
09-12 18:15:35.390  1033  1536 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
09-12 18:15:35.390  1033  1536 D WifiNative-wlan0: doBoolean: SET ps 1
09-12 18:15:35.406  1033  1536 D WifiNative-wlan0: SET ps 1: returned true
09-12 18:15:35.407  1033  1542 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
09-12 18:15:35.408  1033  1536 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 18:15:35.409  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
09-12 18:15:35.409  1033  1536 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 18:15:35.410  1033  1542 D ConnectivityService: ignoring duplicate network state non-change
,09-12 18:15:35.416  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.416  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-12 18:15:35.419  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:35.421  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.421  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.421  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 18:15:35.423  1033  1542 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 18:15:35.423  1033  1542 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 18:15:35.439  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.439  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.440  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
09-12 18:15:35.442  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.442  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,09-12 18:15:35.444  1033  1542 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 18:15:35.444  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.445  1033  1542 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-12 18:15:35.446  1033  1536 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 18:15:35.446  1033  1542 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
09-12 18:15:35.447   318   893 E Netd    : netlink response contains error (File exists)
09-12 18:15:35.447  1033  1542 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-12 18:15:35.447  1033  1542 D ConnectivityService: addLocalRoutetoDefaultNetwork
09-12 18:15:35.447  1033  1542 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
09-12 18:15:35.447  1033  1542 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
09-12 18:15:35.451  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 18:15:35.455  1967  1967 V WfdStateTracker: handleWifiStateChangedEvent: 1
,09-12 18:15:35.461  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.461  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.462  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 18:15:35.464  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
09-12 18:15:35.464  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.465  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 18:15:35.465  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,09-12 18:15:35.471  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.471  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:15:35.471  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
09-12 18:15:35.472  1033  1542 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 18:15:35.472  1033  1542 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 18:15:35.472  1033  1542 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-12 18:15:35.472  1033  1542 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 18:15:35.472  1033  1542 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:35.472  1033  1542 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:35.472  1033  1542 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 18:15:35.472  1033  1542 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.472  1033  1542 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
09-12 18:15:35.472  1033  1542 D ConnectivityService: currentScore = 0, newScore = 20
09-12 18:15:35.472  1033  1542 D ConnectivityService:    accepting network in place of null
09-12 18:15:35.472  1033  1542 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.473  1033  8209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:35.473  1033  8209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
09-12 18:15:35.473  1033  8209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:15:35.473  1033  8209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
09-12 18:15:35.474  1033  1536 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.474  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:35.475  1879  1879 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.475  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
09-12 18:15:35.475   318  8219 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
09-12 18:15:35.475  1033  1542 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 ,wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 18:15:35.475  1033  1542 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-12 18:15:35.475  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 18:15:35.476  1033  1542 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-12 18:15:35.476  1033  1542 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
09-12 18:15:35.476  1033  1542 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
09-12 18:15:35.477  1033  1542 D ConnectivityService: validation of new default Network = false
09-12 18:15:35.477  1033  1542 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
09-12 18:15:35.477  1033  1542 D DSQN    : enableDataServiceNotify 
09-12 18:15:35.477  1033  1542 D DSQN    : start dsqn bin
09-12 18:15:35.481  1033  1542 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 18:15:35.481  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.481  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:35.482  1033  1542 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:35.482  1603  1812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 18:15:35.474  8220  8220 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:35.474  8220  8220 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,09-12 18:15:35.491  8220  8220 E DSQN    : DSQN ssw
09-12 18:15:35.495  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:15:35.495  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
09-12 18:15:35.496  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.496  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
09-12 18:15:35.497  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
09-12 18:15:35.497  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
09-12 18:15:35.497  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
09-12 18:15:35.499  1033  1534 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,09-12 18:15:35.503  8180  8180 W ExternalStrings: load override strings
09-12 18:15:35.503  8180  8180 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 18:15:35.503  8180  8180 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 18:15:35.504  8180  8180 D StatusProvider: onCreate
,09-12 18:15:35.514  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-12 18:15:35.515  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.516  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.526   318  8219 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,09-12 18:15:35.551  8180  8180 V Signer  : override build config not found
09-12 18:15:35.551  8180  8180 D Signer  : value of property debug is false
,09-12 18:15:35.559   318  8219 D libc-netbsd: res_queryN name = clients3.google.com succeed
09-12 18:15:35.579  1033  8210 D DhcpStateMachine: DHCPV4 request on wlan0
,09-12 18:15:35.574  8224  8224 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:35.574  8224  8224 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6801 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
09-12 18:15:35.580  1033  8210 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
09-12 18:15:35.580  1033  8210 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
09-12 18:15:35.582  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
09-12 18:15:35.582  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
09-12 18:15:35.582  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
09-12 18:15:35.582  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
09-12 18:15:35.583  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
09-12 18:15:35.583  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
09-12 18:15:35.583  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
09-12 18:15:35.583  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
09-12 18:15:35.583  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
09-12 18:15:35.583  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
09-12 18:15:35.584  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
09-12 18:15:35.584  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
09-12 18:15:35.584  8180  8180 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
09-12 18:15:35.587   318   892 D LGDataListener: argv[0]=dsqncommand
09-12 18:15:35.587   318   892 D LGDataListener: argv[1]=wlan0
09-12 18:15:35.587   318   892 D LGDataListener: argv[2]=1
09-12 18:15:35.587   318   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
09-12 18:15:35.589  1033  1093 D DSQN    : DSQM DsqnNotification wlan0  1
09-12 18:15:35.589  1033  1093 D DSQN    : start to monitor internet connection
09-12 18:15:35.603  8224  8224 I dhcpcd  : version 5.5.6 starting
09-12 18:15:35.605  8224  8224 E dhcpcd  : get_duid: m
09-12 18:15:35.605  8224  8224 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
09-12 18:15:35.605  8224  8224 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,09-12 18:15:35.611  8180  8180 V LGMDMManager: Create singleton instance
09-12 18:15:35.619  1033  8209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 16:15:35 GMT], X-Android-Received-Millis=[1473696935619], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473696935585]}
,09-12 18:15:35.619  1033  8209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 18:15:35.619  1033  8209 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,09-12 18:15:35.619  1033  1542 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
09-12 18:15:35.619  1033  1542 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
09-12 18:15:35.620  1033  1542 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 18:15:35.620  1033  1542 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:35.620  1033  1542 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
09-12 18:15:35.620  1033  1542 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
09-12 18:15:35.620  1033  1542 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
09-12 18:15:35.620  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.620  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:35.620  1033  1542 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:35.621  1033  1542 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.621  1033  1542 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 18:15:35.621  1603  1812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 18:15:35.622  1033  1536 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.622  1033  1536 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:15:35.622  1879  1879 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:35.623  1879  1879 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,09-12 18:15:35.647  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-12 18:15:35.649  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.650  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
09-12 18:15:35.658  6817  6899 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 891)
09-12 18:15:35.658  6817  6899 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 891)
09-12 18:15:35.663  6817  6899 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 896)
,09-12 18:15:35.665  6817  6899 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 18:15:35.665  6817  6899 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 897)
09-12 18:15:35.672  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:35.672  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e45bd1 added. We now have 2 listener(s)
09-12 18:15:35.673  1033  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.676  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:35.676  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:15:35.676  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:15:35.676  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:35.676  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27daf636 added. We now have 9 listener(s)
09-12 18:15:35.676  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:35.677  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:15:35.681  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:35.691  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:35.691  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:35.691  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:35.691  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:35.691  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:35.691  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:35.691  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:35.691  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:35.692  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:15:35.693  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:35.693  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:35.693  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ef38ea4 added. We now have 3 listener(s)
,09-12 18:15:35.693  1033  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.695  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:35.697  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:35.697  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:35.697  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:35.697  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:35.697  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a01e40d added. We now have 10 listener(s)
09-12 18:15:35.697  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:35.697  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:35.697  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:35.698  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:35.698  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:35.698  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:15:35.698  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:35.698  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:35.698  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e45bd1 removed from the list
09-12 18:15:35.698  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.698  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27daf636 removed from the list
09-12 18:15:35.698  8224  8224 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 18:15:35.698  8224  8224 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 18:15:35.698  8224  8224 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 18:15:35.698  8224  8224 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
09-12 18:15:35.699  8224  8224 D dhcpcd  : wlan0: sending REQUEST (xid 0x5a2ab56c), next in 4.34 seconds
09-12 18:15:35.700  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:35.700  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:35.700  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.701  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.701  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.702  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:35.702  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:35.702  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.702  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27daf636 not in the list
09-12 18:15:35.702  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.702  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.702  8180  8180 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
09-12 18:15:35.703  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:35.703  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:35.703  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.703  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a01e40d removed from the list
09-12 18:15:35.703  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:35.703  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.703  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.703  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:35.703  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thal,iproject.p2p.btconnectorlib.ConnectionManager@1ef38ea4 removed from the list
09-12 18:15:35.704  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:35.704  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15583fc2 added. We now have 2 listener(s)
09-12 18:15:35.704  1033  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.706  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:35.706  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:35.706  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:35.706  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:35.707  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0c71d3 added. We now have 9 listener(s)
09-12 18:15:35.707  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:35.707  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:15:35.710  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:35.715  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:35.715  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:35.715  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:35.715  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:35.715  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:35.715  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:35.715  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:35.715  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:35.716  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:35.716  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:35.717  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:35.717  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ef5b409 added. We now have 3 listener(s)
09-12 18:15:35.717  1033  2020 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.719  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:35.720  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:35.721  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:35.721  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:35.721  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:35.721  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:35.721  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@236e960e added. We now have 10 listener(s)
09-12 18:15:35.721  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:35.722  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:15:35.722  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:15:35.722  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:15:35.722  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:35.722  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:15:35.724  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:15:35.724  1033  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.728  8224  8224 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
09-12 18:15:35.728  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:15:35.729  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 18:15:35.730  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:15:35.731  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:35.732  6817  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 18:15:35.733  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:35.733  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 18:15:35.734  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:15:35.735  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:35.735  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:35.735  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:35.735  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:15:35.735  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:35.735  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:35.735  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15583fc2 removed from the list
09-12 18:15:35.735  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 18:15:35.735  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0c71d3 removed from the list
09-12 18:15:35.735  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:35.735  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.736  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:15:35.736  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.737  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:35.737  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:15:35.737  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.737  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0c71d3 not in the list
09-12 18:15:35.737  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.737  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:15:35.738  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:35.738  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:35.738  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:15:35.738  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:35.738  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.738  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@236e960e removed from the list
09-12 18:15:35.738  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:15:35.739  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.739  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.739  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 18:15:35.739  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ef5b409 removed from the list
09-12 18:15:35.739  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:35.739  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f3c87c5 added. We now have 2 listener(s)
09-12 18:15:35.740  1033  1763 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 18:15:35.742  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:35.742  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:35.742  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:15:35.742  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:35.742  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1582051a added. We now have 9 listener(s)
09-12 18:15:35.742  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:35.743  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
09-12 18:15:35.745  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:15:35.748  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,09-12 18:15:35.748  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:35.748  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:35.748  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:35.748  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:35.748  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:35.748  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:35.748  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:15:35.750  8224  8224 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
09-12 18:15:35.750  8224  8224 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
09-12 18:15:35.750  8224  8224 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
09-12 18:15:35.750  8224  8224 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,09-12 18:15:35.750  8224  8224 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
09-12 18:15:35.750  8224  8224 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
09-12 18:15:35.750  8224  8224 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
09-12 18:15:35.750  8224  8224 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,09-12 18:15:35.751  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:35.751  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:35.751  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:35.751  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb5d228 added. We now have 3 listener(s)
,09-12 18:15:35.752  1033  1964 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.753  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:35.755  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:15:35.757  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:35.757  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:35.757  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:15:35.757  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:35.757  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1562db41 added. We now have 10 listener(s)
09-12 18:15:35.757  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:15:35.757  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:15:35.757  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:35.758  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:15:35.758  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:15:35.758  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:15:35.758  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:15:35.758  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:15:35.762  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:15:35.763  1033  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.769  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:15:35.770  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 18:15:35.771  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:15:35.772  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:35.772  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 18:15:35.773  6817  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-12 18:15:35.773  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:35.773  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:35.773  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:35.773  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:35.773  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.773  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:35.773  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:35.773  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f3c87c5 removed from the list
09-12 18:15:35.773  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.773  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1582051a removed from the list
09-12 18:15:35.773  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:35.774  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:15:35.774  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.774  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.775  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:35.775  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:35.775  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.775  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1582051a not in the list
09-12 18:15:35.775  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.775  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.775  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:35.776  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:35.776  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:35.776  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:15:35.776  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.776  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1562db41 removed from the list
09-12 18:15:35.776  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:35.776  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.776  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.776  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:35.776  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb5d228 removed from the list
09-12 18:15:35.775  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:35.777  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:35.777  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2da9e8d4 added. We now have 2 listener(s)
,09-12 18:15:35.777  1033  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.779  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:35.779  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:35.779  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:35.780  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:35.780  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e40ea7d added. We now have 9 listener(s)
09-12 18:15:35.780  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:15:35.780  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:15:35.782  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:35.785  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:35.785  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:35.785  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:35.785  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:35.785  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:35.785  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:35.785  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:35.785  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:15:35.786  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:35.786  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:35.788  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:35.788  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:35.788  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a575c3 added. We now have 3 listener(s)
,09-12 18:15:35.788  1033  2057 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.790  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:35.793  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:35.793  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:35.793  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:35.793  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:35.793  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3626be40 added. We now have 10 listener(s)
09-12 18:15:35.794  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:35.794  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:15:35.794  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:15:35.794  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:15:35.794  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:35.794  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:15:35.796  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:15:35.796  1033  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:35.799  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:15:35.800  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:15:35.803  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:35.804  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:15:35.809  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:35.812  6817  6899 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-12 18:15:35.814  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:35.814  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:35.814  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:35.814  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:35.814  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:35.814  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:35.814  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:35.814  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2da9e8d4 removed from the list
09-12 18:15:35.814  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:35.814  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e40ea7d removed from the list
09-12 18:15:35.814  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:35.814  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:35.848  1033  1764 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8249 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
09-12 18:15:35.848  1033  1764 I ActivityManager: Killing 7302:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,09-12 18:15:35.895  8180  8236 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 18:15:35.984  1033  8210 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,09-12 18:15:35.987  1033  8210 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
09-12 18:15:35.987  1033  8210 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
09-12 18:15:35.988  1033  8210 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,09-12 18:15:35.988  1033  8210 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
09-12 18:15:35.988  1033  8210 V DhcpStateMachine: Current State is mWaitBeforeStartState.
09-12 18:15:35.988  1033  8210 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
09-12 18:15:35.988  1033  8210 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
,09-12 18:15:35.989  1033  8210 D DhcpStateMachine: RunningState
09-12 18:15:36.063  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:36.063  1033  2112 W libprocessgroup: failed to open /acct/uid_10093/pid_7302/cgroup.procs: No such file or directory
09-12 18:15:36.063  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:15:36.067  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:36.067  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:36.068  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:36.069  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e40ea7d not in the list
09-12 18:15:36.069  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:36.070  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:36.074  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:36.076  6817  6899 D BluetoothLeScanner: could not find callback wrapper
09-12 18:15:36.076  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:15:36.076  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:36.076  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:36.077  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3626be40 removed from the list
09-12 18:15:36.077  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:36.077  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:36.077  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:36.077  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:36.077  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a575c3 removed from the list
09-12 18:15:36.080  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:36.081  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95fab1f added. We now have 2 listener(s)
,09-12 18:15:36.093  1033  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-12 18:15:36.101  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:36.101  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:36.101  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:36.101  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:36.101  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd97e6c added. We now have 9 listener(s)
09-12 18:15:36.101  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:15:36.102  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:15:36.112  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:15:36.116  6817  6899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:15:36.116  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:15:36.116  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-12 18:15:36.116  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:15:36.116  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:15:36.116  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:36.116  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:15:36.116  6817  6899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:15:36.120  6817  6899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:15:36.120  6817  6899 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:15:36.120  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:15:36.120  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1775e8ca added. We now have 3 listener(s)
09-12 18:15:36.121  1033  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-12 18:15:36.124  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
09-12 18:15:36.124  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:15:36.124  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:15:36.124  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:15:36.124  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dda3b added. We now have 10 listener(s)
09-12 18:15:36.124  6817  6899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:15:36.124  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:36.126  6817  6899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:15:36.126  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:36.126  6817  6899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:15:36.126  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:36.126  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:36.126  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:15:36.126  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:36.126  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:15:36.127  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95fab1f removed from the list
09-12 18:15:36.127  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:36.127  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd97e6c removed from the list
09-12 18:15:36.127  6817  6899 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:15:36.127  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:36.127  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:36.127  6817  6899 D org.thali,project.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:36.128  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:36.128  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:36.128  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:36.128  6817  6899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd97e6c not in the list
09-12 18:15:36.128  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:15:36.128  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:36.129  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:15:36.129  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:15:36.129  6817  6899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:15:36.129  6817  6899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dda3b removed from the list
09-12 18:15:36.129  6817  6899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:15:36.129  6817  6899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:15:36.129  6817  6899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:15:36.129  6817  6899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:15:36.129  6817  6899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1775e8ca removed from the list
09-12 18:15:36.131  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 18:15:36.131  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 18:15:36.131  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 18:15:36.131  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:15:36.131  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 18:15:36.132  6817  6899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:15:36.133  8249  8249 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:36.143  6817  8281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 904, name: My test thread name)
09-12 18:15:36.144  6817  8281 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 904, thread name: My test thread name)
09-12 18:15:36.144  6817  8281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 904, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 18:15:36.147  6817  8282 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 906, name: My test thread name)
09-12 18:15:36.147  6817  8282 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 906, thread name: My test thread name)
09-12 18:15:36.147  6817  8282 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 906, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 18:15:36.149  6817  6899 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-12 18:15:36.149  6817  6899 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 18:15:36.150  6817  6899 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 18:15:36.150  6817  6899 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 18:15:36.150  6817  6899 D com.test.thalitest.ThaliTestRunner: Total duration: 23125 ms
09-12 18:15:36.151  6817  6899 I jxcore-log: *Native tests were executed*
09-12 18:15:36.151  6817  6899 I jxcore-log: 
09-12 18:15:36.151  6817  6899 I jxcore-log: Total number of executed tests:  80
09-12 18:15:36.151  6817  6899 I jxcore-log: 
09-12 18:15:36.151  6817  6899 I jxcore-log: Number of passed tests:  80
09-12 18:15:36.151  6817  6899 I jxcore-log: 
09-12 18:15:36.152  6817  6899 I jxcore-log: Number of failed tests:  0
09-12 18:15:36.152  6817  6899 I jxcore-log: 
09-12 18:15:36.152  6817  6899 I jxcore-log: Number of ignored tests:  0
09-12 18:15:36.152  6817  6899 I jxcore-log: 
09-12 18:15:36.153  6817  6899 I jxcore-log: Total duration:  23125
09-12 18:15:36.153  6817  6899 I jxcore-log: 
09-12 18:15:36.153  6817  6899 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 18:15:36.153  6817  6899 I jxcore-log: 
09-12 18:15:36.156  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.156  6817  6899 I jxcore-log: 
09-12 18:15:36.159  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.159  6817  6899 I jxcore-log: 
,09-12 18:15:36.161  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.161  6817  6899 I jxcore-log: 
09-12 18:15:36.162  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.162  6817  6899 I jxcore-log: 
09-12 18:15:36.163  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.163  6817  6899 I jxcore-log: 
09-12 18:15:36.165  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.165  6817  6899 I jxcore-log: 
09-12 18:15:36.168  8249  8249 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
09-12 18:15:36.168  6817  6817 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 18:15:36.169  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:15:36.169  6817  6899 I jxcore-log: 
09-12 18:15:36.171  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:15:36.171  6817  6899 I jxcore-log: 
09-12 18:15:36.172  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.172  6817  6899 I jxcore-log: 
,09-12 18:15:36.173  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.173  6817  6899 I jxcore-log: 
09-12 18:15:36.175  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:15:36.175  6817  6899 I jxcore-log: 
09-12 18:15:36.176  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:15:36.176  6817  6899 I jxcore-log: 
09-12 18:15:36.177  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:15:36.177  6817  6899 I jxcore-log: 
09-12 18:15:36.178  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.178  6817  6899 I jxcore-log: 
09-12 18:15:36.179  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.179  6817  6899 I jxcore-log: 
09-12 18:15:36.180  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.180  6817  6899 I jxcore-log: 
09-12 18:15:36.181  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.181  6817  6899 I jxcore-log: 
09-12 18:15:36.182  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.182  6817  6899 I jxcore-log: 
09-12 18:15:36.183  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.183  6817  6899 I jxcore-log: 
,09-12 18:15:36.184  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.184  6817  6899 I jxcore-log: 
09-12 18:15:36.185  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:15:36.185  6817  6899 I jxcore-log: 
09-12 18:15:36.186  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:15:36.186  6817  6899 I jxcore-log: 
09-12 18:15:36.187  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:15:36.187  6817  6899 I jxcore-log: 
09-12 18:15:36.188  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.188  6817  6899 I jxcore-log: 
09-12 18:15:36.188  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.188  6817  6899 I jxcore-log: 
09-12 18:15:36.189  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.189  6817  6899 I jxcore-log: 
09-12 18:15:36.190  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.190  6817  6899 I jxcore-log: 
09-12 18:15:36.191  6817  6899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:15:36.191  6817  6899 I jxcore-log: 
09-12 18:15:36.198  8249  8249 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,09-12 18:15:36.199  8249  8249 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
09-12 18:15:36.199  8249  8249 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
09-12 18:15:36.199  8249  8249 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
09-12 18:15:36.200  8249  8249 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
09-12 18:15:36.201  8249  8249 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
09-12 18:15:36.205  8249  8249 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
09-12 18:15:36.209  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:36.211  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.221  8249  8249 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 18:15:36.222  8249  8249 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,09-12 18:15:36.224  8249  8249 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
09-12 18:15:36.225  8180  8236 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:36.225  8180  8236 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 18:15:36.226  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.226  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:36.230  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:36.237  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:36.242  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:36.242  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.243  8249  8249 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
09-12 18:15:36.245  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,09-12 18:15:36.249  6931  6931 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
09-12 18:15:36.252  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.252  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:36.256  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:36.261  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:36.267  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:36.268  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.268  8249  8249 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 18:15:36.269  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
09-12 18:15:36.269  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
09-12 18:15:36.269  6931  6931 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
09-12 18:15:36.270  6931  6931 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
09-12 18:15:36.270  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
09-12 18:15:36.270  6931  6931 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
09-12 18:15:36.270  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
09-12 18:15:36.270  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
09-12 18:15:36.270  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
09-12 18:15:36.270  6931  6931 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
09-12 18:15:36.270  6931  6931 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
09-12 18:15:36.271  6931  6931 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
09-12 18:15:36.273  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.273  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:36.279  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:36.287  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:36.294  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:36.294  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.295  8249  8249 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 18:15:36.299  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.300  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:36.306  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:36.311  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:36.317  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:36.318  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.318  8249  8249 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:36.321  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.323  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-12 18:15:36.327  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 18:15:36.332  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 18:15:36.337  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:36.338  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.338  8249  8249 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,09-12 18:15:36.341  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.341  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:36.346  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,09-12 18:15:36.351  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:36.357  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:36.358  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.358  8249  8249 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:36.366  8286  8286 D AndroidRuntime: 
09-12 18:15:36.366  8286  8286 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-12 18:15:36.368  8286  8286 D AndroidRuntime: CheckJNI is OFF
09-12 18:15:36.370  8249  8249 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
09-12 18:15:36.370  8249  8249 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3331
09-12 18:15:36.378  8180  8236 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
09-12 18:15:36.382  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:36.382  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:36.385  1840  8291 I CheckinService: active receiver: enabled
,09-12 18:15:36.400  1840  8291 I CheckinService: Preparing to send checkin request
09-12 18:15:36.400  1840  8291 I EventLogService: Accumulating logs since 1473696918930
09-12 18:15:36.401  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 18:15:36.405  8180  8236 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
09-12 18:15:36.408  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:36.414  8180  8236 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
09-12 18:15:36.414  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:36.415  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.420  8180  8236 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-12 18:15:36.421  8180  8236 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
09-12 18:15:36.421  8249  8249 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:36.424  8180  8236 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
09-12 18:15:36.424  8180  8236 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
09-12 18:15:36.424  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.425  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:36.429  8180  8236 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,09-12 18:15:36.431  8180  8236 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,09-12 18:15:36.433  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 18:15:36.436  1840  8291 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
09-12 18:15:36.439  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
09-12 18:15:36.446  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:36.447  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,09-12 18:15:36.447  8249  8249 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
09-12 18:15:36.452  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.452  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
09-12 18:15:36.455  8133  8133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
09-12 18:15:36.459  8133  8133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,09-12 18:15:36.461  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 18:15:36.468  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 18:15:36.475  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,09-12 18:15:36.475  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.476  8249  8249 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 18:15:36.476  8249  8249 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 18:15:36.476  8249  8249 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 18:15:36.480  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:36.480  8180  8237 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,09-12 18:15:36.485  8133  8133 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,09-12 18:15:36.486  8133  8133 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
09-12 18:15:36.488  6931  6931 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
09-12 18:15:36.498  6931  6931 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,09-12 18:15:36.504  8249  8249 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
09-12 18:15:36.504  8249  8249 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
09-12 18:15:36.504  8249  8249 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
09-12 18:15:36.505  8249  8249 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
09-12 18:15:36.505  8249  8249 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
09-12 18:15:36.505  8286  8286 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-12 18:15:36.510  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,09-12 18:15:36.514  8249  8249 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
09-12 18:15:36.515  8249  8249 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
09-12 18:15:36.515  1033  1091 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
09-12 18:15:36.515  8249  8249 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
09-12 18:15:36.515  1033  1091 I ActivityManager: Killing 6817:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
09-12 18:15:36.534  8249  8249 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:36.534  8249  8249 D LgDataFeature: LgDataFeature() Constructor Done, null
,09-12 18:15:36.557  1033  2020 I WindowState: WIN DEATH: Window{38c20d60 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 18:15:36.557  1033  1541 D WifiService: Client connection lost with reason: 4
,09-12 18:15:36.564  1033  2020 D InputDispatcher: Window went away: Window{38c20d60 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 18:15:36.601  8249  8249 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,09-12 18:15:36.603  8249  8249 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
09-12 18:15:36.603  8249  8249 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
09-12 18:15:36.603  8249  8249 V SoundPool: doLoad: loading sample sampleID=1
09-12 18:15:36.603  8249  8309 V SoundPool: Start decode
09-12 18:15:36.603  8249  8309 V MediaPlayer[Native]: decode(31, 10857164, 17813)
09-12 18:15:36.604   322  1383 V MediaPlayerService: decode(22, 10857164, 17813)
09-12 18:15:36.604   322  1383 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
09-12 18:15:36.604   322  1383 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
09-12 18:15:36.604   322  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
09-12 18:15:36.604   322  1383 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
09-12 18:15:36.604   322  1383 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
09-12 18:15:36.604  8249  8249 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
09-12 18:15:36.604   322  1383 V MediaPlayerService: player type = 3
09-12 18:15:36.604   322  1383 V AwesomePlayer: AwesomePlayer create()
09-12 18:15:36.604   322  1383 V AwesomePlayer: reset_l() 
09-12 18:15:36.604   322  1383 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:36.604   322  1383 V AwesomePlayer: setAudioSink() 
09-12 18:15:36.604   322  1383 V AwesomePlayer: reset_l() 
09-12 18:15:36.604   322  1383 V AudioCache: notify(0xb5474d00, 8, 0, 0)
09-12 18:15:36.604   322  1383 V AudioCache: ignored
09-12 18:15:36.604   322  1383 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:36.604   322  1383 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
09-12 18:15:36.604   322  1383 V AwesomePlayer: setDataSource_l dataSource
09-12 18:15:36.604   322  1383 V LGParserOSAL: SniffLGParser start
09-12 18:15:36.604   322  1383 V LGParserOSAL: MainType:5, SubType=0
09-12 18:15:36.604   322  1383 V LGParserOSAL: #### check Mime : application/ogg
09-12 18:15:36.604   322  1383 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
09-12 18:15:36.604   322  1383 E MediaExtractor: Use LGExtractor :application/ogg 
09-12 18:15:36.634   322  1383 V LGParserOSAL: supported mime: application/ogg
09-12 18:15:36.634   322  1383 V AwesomePlayer: setDataSource_l() extractor countTracks=1
09-12 18:15:36.634   322  1383 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
09-12 18:15:36.634   322  1383 V AwesomePlayer: mBitrate = -1 bits/sec
09-12 18:15:36.634   322  1383 V AwesomePlayer: AudioTrack Setting
09-12 18:15:36.634   322  1383 V AwesomePlayer: AudioTrack Setting channelCount = 2
09-12 18:15:36.634   322  1383 V AwesomePlayer: setAudioSource() 
09-12 18:15:36.634   322  1383 V MediaPlayerService: prepare
09-12 18:15:36.634   322  1383 V AwesomePlayer: prepareAsync_l() 
09-12 18:15:36.634   322  1383 V MediaPlayerService: wait for prepare
09-12 18:15:36.635   322  8310 V AwesomePlayer: onPrepareAsyncEvent() 
09-12 18:15:36.635   322  8310 V AwesomePlayer: initAudioDecoder() 
09-12 18:15:36.635   322  8310 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-12 18:15:36.635   322  8310 V AudioSystem: isOffloadSupported()
09-12 18:15:36.635   322  8310 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-12 18:15:36.635   322  8310 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-12 18:15:36.635   322  8310 I AudioFlinger: isAudioPlaybackHookOn() false
09-12 18:15:36.635   322  8310 V AwesomePlayer: getUseOffload() = 0 
09-12 18:15:36.635   322  8310 V OMXCodec: OMXCodec::Create
09-12 18:15:36.635   322  8310 V OMXCodec: findMatchingCodecs()
09-12 18:15:36.635   322  8310 V OMXCodec: matching 'OMX.google.vorbis.decoder' quir,ks 0x00000000
09-12 18:15:36.635   322  8310 V OMXCodec: matchingCodecs.size()=1
09-12 18:15:36.635   322  8310 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
09-12 18:15:36.636   322  8310 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
09-12 18:15:36.636   322  8310 V LGCodecAdapter: LG Codec Adapter start
09-12 18:15:36.636   322  8310 V OMXCodec: OMXCodec Createtor
09-12 18:15:36.636   322  8310 V OMXCodec: setComponentRole
09-12 18:15:36.636   322  8310 V OMXCodec: configureCodec protected=0
09-12 18:15:36.636   322  8310 V LGCodecAdapter: called getLGCodecSpecificData
09-12 18:15:36.636   322  8310 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
09-12 18:15:36.636   322  8310 V LGCodecOSAL: Called LGconfigureCodecMETA
09-12 18:15:36.636   322  8310 V LGCodecOSAL: Called LGconfigureCodecMSG
09-12 18:15:36.636   322  8310 V LGCodecOSAL: Not support LGCodec
09-12 18:15:36.636   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
09-12 18:15:36.636   322  8310 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
09-12 18:15:36.636   322  8310 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
09-12 18:15:36.636   322  8310 I AwesomePlayer: Could not offload audio decode, try pcm offload
09-12 18:15:36.636   322  8310 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
09-12 18:15:36.636   322  8310 V AudioSystem: isOffloadSupported()
09-12 18:15:36.636   322  8310 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
09-12 18:15:36.636   322  8310 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
09-12 18:15:36.636   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
09-12 18:15:36.636   322  8310 V OMXCodec: init()
09-12 18:15:36.636   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
09-12 18:15:36.636   322  8310 V OMXCodec: allocateBuffers
09-12 18:15:36.636   322  8310 V OMXCodec: allocateBuffersOnPort portIndex=0
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
09-12 18:15:36.637   322  8310 V OMXCodec: allocateBuffersOnPort portIndex=1
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on output port
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-12 18:15:36.637   322  8310 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb00 on output port
09-12 18:15:36.637   322  8310 V OMXCodec: init() mAsyncCompletion wait!!! 
09-12 18:15:36.637   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-12 18:15:36.637   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-12 18:15:36.637   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
,09-12 18:15:36.637   322  8310 V OMXCodec: init() mAsyncCompletion wait!!! 
09-12 18:15:36.637   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
09-12 18:15:36.637   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
09-12 18:15:36.637   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
09-12 18:15:36.637   322  8310 V OMXCodec: init() mAsyncCompletion wait free! 
09-12 18:15:36.637   322  8310 V AwesomePlayer: finishAsyncPrepare_l() 
09-12 18:15:36.637   322  8310 V AudioCache: notify(0xb5474d00, 5, 0, 0)
,09-12 18:15:36.637   322  8310 V AudioCache: ignored
09-12 18:15:36.637   322  8310 V AudioCache: notify(0xb5474d00, 1, 0, 0)
09-12 18:15:36.637   322  8310 V AudioCache: prepared
09-12 18:15:36.637   322  1383 V AudioCache: wait - success
09-12 18:15:36.637   322  1383 V MediaPlayerService: start
,09-12 18:15:36.637   322  1383 V AwesomePlayer: play_l() 
09-12 18:15:36.637   322  1383 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
09-12 18:15:36.637   322  1383 V AwesomePlayer: createAudioPlayer_l
09-12 18:15:36.637   322  1383 V AwesomePlayer: seekAudioIfNecessary_l() 
09-12 18:15:36.637   322  1383 V AwesomePlayer: startAudioPlayer_l() 
,09-12 18:15:36.637   322  1383 D AudioPlayer: start of Playback, useOffload 0
09-12 18:15:36.637   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-12 18:15:36.637   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
09-12 18:15:36.642   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
09-12 18:15:36.642   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,09-12 18:15:36.642   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
09-12 18:15:36.642   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
09-12 18:15:36.642   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048176
,09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048576
09-12 18:15:36.643   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,09-12 18:15:36.644   322  8312 V OMXCodec: allocateBuffersOnPort portIndex=1
09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
09-12 18:15:36.644   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on output port
09-12 18:15:36.645   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on output port
09-12 18:15:36.645   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,09-12 18:15:36.645   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
09-12 18:15:36.647   322  1383 V AudioCache: open(48000, 2, 0x0, 1, 4)
09-12 18:15:36.648   322  1383 V AudioCache: notify(0xb5474d00, 6, 0, 0)
09-12 18:15:36.648   322  1383 V AudioCache: ignored
09-12 18:15:36.648   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.648   322  8313 V AudioCache: memcpy(0xaf006000, 0xb57cd000, 4096)
09-12 18:15:36.648   322  1383 V MediaPlayerService: wait for playback complete
,09-12 18:15:36.652   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.652   322  8313 V AudioCache: memcpy(0xaf007000, 0xb57cd000, 4096)
09-12 18:15:36.653   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.653   322  8313 V AudioCache: memcpy(0xaf008000, 0xb57cd000, 4096)
09-12 18:15:36.654   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.654   322  8313 V AudioCache: memcpy(0xaf009000, 0xb57cd000, 4096)
09-12 18:15:36.656   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.656   322  8313 V AudioCache: memcpy(0xaf00a000, 0xb57cd000, 4096)
09-12 18:15:36.657   322  8313 V AudioCache: write(0xb57cd000, 4096)
,09-12 18:15:36.657   322  8313 V AudioCache: memcpy(0xaf00b000, 0xb57cd000, 4096)
09-12 18:15:36.658   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.658   322  8313 V AudioCache: memcpy(0xaf00c000, 0xb57cd000, 4096)
09-12 18:15:36.660   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.660   322  8313 V AudioCache: memcpy(0xaf00d000, 0xb57cd000, 4096)
09-12 18:15:36.660   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.661   322  8313 V AudioCache: memcpy(0xaf00e000, 0xb57cd000, 4096)
09-12 18:15:36.661   322  8313 V AudioCache: write(0xb57cd000, 4096)
,09-12 18:15:36.661   322  8313 V AudioCache: memcpy(0xaf00f000, 0xb57cd000, 4096)
,09-12 18:15:36.662   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.662   322  8313 V AudioCache: memcpy(0xaf010000, 0xb57cd000, 4096)
09-12 18:15:36.663   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.663   322  8313 V AudioCache: memcpy(0xaf011000, 0xb57cd000, 4096)
09-12 18:15:36.664   322  8313 V AudioCache: write(0xb57cd000, 4096)
,09-12 18:15:36.664   322  8313 V AudioCache: memcpy(0xaf012000, 0xb57cd000, 4096)
09-12 18:15:36.664   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.664   322  8313 V AudioCache: memcpy(0xaf013000, 0xb57cd000, 4096)
09-12 18:15:36.665   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.665   322  8313 V AudioCache: memcpy(0xaf014000, 0xb57cd000, 4096)
,09-12 18:15:36.666   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.666   322  8313 V AudioCache: memcpy(0xaf015000, 0xb57cd000, 4096)
09-12 18:15:36.666   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.666   322  8313 V AudioCache: memcpy(0xaf016000, 0xb57cd000, 4096)
09-12 18:15:36.667   322  8313 V AudioCache: write(0xb57cd000, 4096)
,09-12 18:15:36.667   322  8313 V AudioCache: memcpy(0xaf017000, 0xb57cd000, 4096)
09-12 18:15:36.668   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.668   322  8313 V AudioCache: memcpy(0xaf018000, 0xb57cd000, 4096)
09-12 18:15:36.669   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.669   322  8313 V AudioCache: memcpy(0xaf019000, 0xb57cd000, 4096)
,09-12 18:15:36.669   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.669   322  8313 V AudioCache: memcpy(0xaf01a000, 0xb57cd000, 4096)
09-12 18:15:36.670   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.670   322  8313 V AudioCache: memcpy(0xaf01b000, 0xb57cd000, 4096)
09-12 18:15:36.671   322  8313 V AudioCache: write(0xb57cd000, 4096)
,09-12 18:15:36.671   322  8313 V AudioCache: memcpy(0xaf01c000, 0xb57cd000, 4096)
09-12 18:15:36.673   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.673   322  8313 V AudioCache: memcpy(0xaf01d000, 0xb57cd000, 4096)
09-12 18:15:36.676   322  8313 V AudioCache: write(0xb57cd000, 4096)
,09-12 18:15:36.676   322  8313 V AudioCache: memcpy(0xaf01e000, 0xb57cd000, 4096)
09-12 18:15:36.676   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.676   322  8313 V AudioCache: memcpy(0xaf01f000, 0xb57cd000, 4096)
,09-12 18:15:36.677   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.677   322  8313 V AudioCache: memcpy(0xaf020000, 0xb57cd000, 4096)
09-12 18:15:36.678   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.678   322  8313 V AudioCache: memcpy(0xaf021000, 0xb57cd000, 4096)
09-12 18:15:36.679   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.679   322  8313 V AudioCache: memcpy(0xaf022000, 0xb57cd000, 4096)
09-12 18:15:36.680   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.680   322  8313 V AudioCache: memcpy(0xaf023000, 0xb57cd000, 4096)
09-12 18:15:36.681   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.681   322  8313 V AudioCache: memcpy(0xaf024000, 0xb57cd000, 4096)
09-12 18:15:36.681   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.681   322  8313 V AudioCache: memcpy(0xaf025000, 0xb57cd000, 4096)
09-12 18:15:36.682   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.682   322  8313 V AudioCache: memcpy(0xaf026000, 0xb57cd000, 4096)
09-12 18:15:36.683   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.683   322  8313 V AudioCache: memcpy(0xaf027000, 0xb57cd000, 4096)
09-12 18:15:36.684   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.684   322  8313 V AudioCache: memcpy(0xaf028000, 0xb57cd000, 4096)
09-12 18:15:36.685   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.685   322  8313 V AudioCache: memcpy(0xaf029000, 0xb57cd000, 4096)
09-12 18:15:36.685   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.685   322  8313 V AudioCache: memcpy(0xaf02a000, 0xb57cd000, 4096)
09-12 18:15:36.686   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.686   322  8313 V AudioCache: memcpy(0xaf02b000, 0xb57cd000, 4096)
09-12 18:15:36.687   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.687   322  8313 V AudioCache: memcpy(0xaf02c000, 0xb57cd000, 4096)
,09-12 18:15:36.688   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.688   322  8313 V AudioCache: memcpy(0xaf02d000, 0xb57cd000, 4096)
09-12 18:15:36.688   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.688   322  8313 V AudioCache: memcpy(0xaf02e000, 0xb57cd000, 4096)
09-12 18:15:36.689   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.689   322  8313 V AudioCache: memcpy(0xaf02f000, 0xb57cd000, 4096)
09-12 18:15:36.690   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.690   322  8313 V AudioCache: memcpy(0xaf030000, 0xb57cd000, 4096)
09-12 18:15:36.690   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.690   322  8313 V AudioCache: memcpy(0xaf031000, 0xb57cd000, 4096)
09-12 18:15:36.691   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.691   322  8313 V AudioCache: memcpy(0xaf032000, 0xb57cd000, 4096)
09-12 18:15:36.695   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.696   322  8313 V AudioCache: memcpy(0xaf033000, 0xb57cd000, 4096)
09-12 18:15:36.700   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.700   322  8313 V AudioCache: memcpy(0xaf034000, 0xb57cd000, 4096)
09-12 18:15:36.701   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.701   322  8313 V AudioCache: memcpy(0xaf035000, 0xb57cd000, 4096)
09-12 18:15:36.702   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.702   322  8313 V AudioCache: memcpy(0xaf036000, 0xb57cd000, 4096)
,09-12 18:15:36.703   322  8313 V AudioCache: write(0xb57cd000, 4096)
09-12 18:15:36.703   322  8313 V AudioCache: memcpy(0xaf037000, 0xb57cd000, 4096)
09-12 18:15:36.704   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
09-12 18:15:36.704   322  8313 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
09-12 18:15:36.704   322  8313 V AwesomePlayer: postAudioEOS() 
09-12 18:15:36.704   322  8313 V AudioCache: write(0xb57cd000, 280)
09-12 18:15:36.705   322  8313 V AudioCache: memcpy(0xaf038000, 0xb57cd000, 280)
09-12 18:15:36.706   322  8310 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
09-12 18:15:36.706   322  8310 V AwesomePlayer: onStreamDone
09-12 18:15:36.706   322  8310 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
09-12 18:15:36.706   322  8310 V AudioCache: notify(0xb5474d00, 2, 0, 0)
09-12 18:15:36.706   322  8310 V AudioCache: playback complete
09-12 18:15:36.706   322  8310 V AwesomePlayer: pause_l() 
09-12 18:15:36.706   322  1383 V AudioCache: wait - success
09-12 18:15:36.706   322  8310 V AudioCache: notify(0xb5474d00, 7, 0, 0)
09-12 18:15:36.706   322  1383 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
09-12 18:15:36.706   322  8310 V AudioCache: ignored
09-12 18:15:36.706   322  8310 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:36.707   322  8310 D AudioPlayer: Pause Playback at 1068125
09-12 18:15:36.707   322  1383 V AwesomePlayer: reset_l() 
09-12 18:15:36.707   322  1383 V AudioCache: notify(0xb5474d00, 8, 0, 0)
09-12 18:15:36.707   322  1383 V AudioCache: ignored
09-12 18:15:36.707   322  1383 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:36.707   322  1383 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
09-12 18:15:36.707   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
09-12 18:15:36.707   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
09-12 18:15:36.707   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
09-12 18:15:36.707   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-12 18:15:36.708   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
09-12 18:15:36.708   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
09-12 18:15:36.708   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
09-12 18:15:36.708   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
09-12 18:15:36.708   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
09-12 18:15:36.709   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
09-12 18:15:36.709   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
09-12 18:15:36.709   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
09-12 18:15:36.709   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
,09-12 18:15:36.709   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
09-12 18:15:36.709   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
09-12 18:15:36.710   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
09-12 18:15:36.710   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 1
09-12 18:15:36.710   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
09-12 18:15:36.710   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 1
09-12 18:15:36.710   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
09-12 18:15:36.710   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
,09-12 18:15:36.711   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
09-12 18:15:36.711   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
09-12 18:15:36.711   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
09-12 18:15:36.712   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
09-12 18:15:36.712   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-12 18:15:36.712   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
09-12 18:15:36.712   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
09-12 18:15:36.712   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
09-12 18:15:36.712   322  8312 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
09-12 18:15:36.712   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
09-12 18:15:36.712   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,09-12 18:15:36.712   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
09-12 18:15:36.714   322  1383 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
09-12 18:15:36.714   322  1383 D AudioPlayer: AudioPlayer releasing audio source
09-12 18:15:36.714   322  1383 D AudioPlayer: AudioPlayer done releasing audio source
,09-12 18:15:36.715   322  1383 V AwesomePlayer: reset_l() 
09-12 18:15:36.715   322  1383 V AwesomePlayer: cancelPlayerEvents
,09-12 18:15:36.715   322  1383 V AwesomePlayer: ~AwesomePlayer call
09-12 18:15:36.715   322  1383 V AwesomePlayer: reset_l() 
09-12 18:15:36.715   322  1383 V AwesomePlayer: cancelPlayerEvents
09-12 18:15:36.715  8249  8309 V SoundPool: close(31)
09-12 18:15:36.715  8249  8309 V SoundPool: pointer = 0x9fe5c000, size = 205080, sampleRate = 48000, numChannels = 2
09-12 18:15:36.760  1033  1091 I ActivityManager:   Force finishing activity ActivityRecord{35fd29f5 u0 com.test.thalitest/.MainActivity t6}
,09-12 18:15:36.808   346   367 E GBMv2   : DFP En is all cleared set to be enabled
,09-12 18:15:36.813  1033  1964 W ActivityManager: Spurious death for ProcessRecord{3347e3b2 6817:com.test.thalitest/u0a118}, curProc for 6817: null
,09-12 18:15:36.814  1033  1101 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,09-12 18:15:36.820  1033  1101 I ActivityManager:   Force finishing activity ActivityRecord{35fd29f5 u0 com.test.thalitest/.MainActivity t6 f}
09-12 18:15:36.821  1033  1101 W ActivityManager: Duplicate finish request for ActivityRecord{35fd29f5 u0 com.test.thalitest/.MainActivity t6 f}
,09-12 18:15:36.856  7692  7692 D UEI.SmartControl: QS Service created
09-12 18:15:36.858  2090  2090 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,09-12 18:15:36.865  2090  2090 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
09-12 18:15:36.865  1967  2541 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
09-12 18:15:36.866  1967  2541 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1065a5e7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-12 18:15:36.869  1967  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
09-12 18:15:36.870  1967  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2b7e3594 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
09-12 18:15:36.871  8249  8249 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
09-12 18:15:36.871  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
09-12 18:15:36.873  2090  2171 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,09-12 18:15:36.888  1033  1428 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-12 18:15:36.892  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,09-12 18:15:36.892  8249  8249 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
09-12 18:15:36.893  8249  8249 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
09-12 18:15:36.894  3764  3764 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
09-12 18:15:36.896  2040  2040 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-12 18:15:36.897  2508  2670 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 18:15:36.901  7755  7755 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
09-12 18:15:36.901  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
09-12 18:15:36.907  7692  7692 I UEI.SmartControl: Service initServices...
09-12 18:15:36.907  7692  7692 D UEI.SmartControl: QS start get config
,09-12 18:15:36.952  8249  8249 V LGMDMManager: Create singleton instance
,09-12 18:15:36.957  4892  4892 I art     : Explicit concurrent mark sweep GC freed 8228(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 471us total 116.644ms
09-12 18:15:36.958  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
09-12 18:15:36.959  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-12 18:15:36.960  2090  2090 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-12 18:15:36.968  2090  2090 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,09-12 18:15:36.969  1930  1930 D ActionManagerService: notifyUserLog: 1000003
09-12 18:15:36.970  3764  4764 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
09-12 18:15:36.970  2090  2090 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
09-12 18:15:36.971  4765  4765 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-12 18:15:36.973  4765  4765 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-12 18:15:36.973  4765  4765 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-12 18:15:36.973  4765  4765 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
09-12 18:15:36.973  4765  4765 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 18:15:36.973  4765  4765 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 18:15:36.973  4765  4765 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-12 18:15:36.973  4765  4765 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
09-12 18:15:36.973  4765  4765 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:15:36.973  4765  4765 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:15:36.973  4765  4765 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
09-12 18:15:36.973  4765  4765 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
09-12 18:15:36.974  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
09-12 18:15:36.975  3764  3781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , create_time: 1430832262123
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , expire_time: 0
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , display: false
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , animation: false }
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , create_time: 1430832262287
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , expire_time: 0
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , display: false
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , animation: false }
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1473420112499
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , create_time: 1473420113195
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , expire_time: 0
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
09-12 18:15:36.977  2090  2090 I GBoardWebViewUt,ils: , display: false
09-12 18:15:36.977  2090  2090 I GBoardWebViewUtils: , animation: false }
09-12 18:15:36.983  2090  8316 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
09-12 18:15:36.985  1033  1942 V SIM_STK : Menu title from STK is T-Mobile
,09-12 18:15:36.995  1930  1930 D ActionManagerService: notifyUserLog: 1000004
09-12 18:15:36.996  3764  4764 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
09-12 18:15:37.020  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,09-12 18:15:37.020  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-12 18:15:37.023  1603  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-12 18:15:37.023  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.030  1603  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-12 18:15:37.030  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.034  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-12 18:15:37.034  2090  2090 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
09-12 18:15:37.036  1033  1090 W InputMethodInfo: Duplicated subtype definition found: , voice
09-12 18:15:37.038  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-12 18:15:37.039  1603  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:15:37.039  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
09-12 18:15:37.043  1033  1033 I art     : Explicit concurrent mark sweep GC freed 80918(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 3.112ms total 197ms
09-12 18:15:37.044  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 18:15:37.050  1033  1101 I art     : WaitForGcToComplete blocked for 146.118ms for cause Explicit
,09-12 18:15:37.065  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 18:15:37.065  1603  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,09-12 18:15:37.066  1603  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-12 18:15:37.067  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.068  8249  8249 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
09-12 18:15:37.070  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
09-12 18:15:37.071  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:37.080  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 18:15:37.080  1603  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-12 18:15:37.081  1603  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-12 18:15:37.081  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.083  1896  1896 D SplitUIManager: split_name #11 / not available #0
09-12 18:15:37.083  1896  1896 D SplitUIService: removed split : 
09-12 18:15:37.085  1603  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:15:37.085  1603  1650 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 18:15:37.085  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
09-12 18:15:37.085  1603  1650 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 18:15:37.086  8249  8249 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
09-12 18:15:37.091  1033  1536 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 18:15:37.091  1033  1536 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 18:15:37.091  1033  1536 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 18:15:37.092  1033  1536 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 18:15:37.092  8249  8249 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7795
09-12 18:15:37.092  1033  1536 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 18:15:37.092  1033  1536 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
09-12 18:15:37.093  1033  1542 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
09-12 18:15:37.093  1033  1542 D ConnectivityService: identical MTU - not setting
09-12 18:15:37.093  1033  1542 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
09-12 18:15:37.093  1033  1542 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 18:15:37.093  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:15:37.093  1033  1542 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
09-12 18:15:37.094  1033  1542 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-12 18:15:37.096  1603  1812 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-12 18:15:37.098  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 18:15:37.098  1603  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-12 18:15:37.100  1603  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-12 18:15:37.100  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.112  1033  1573 V SIM_STK : Menu title from STK is T-Mobile
09-12 18:15:37.112  1033  1573 V SIM_STK : Menu title from STK is T-Mobile
,09-12 18:15:37.115  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:37.118  1896  1896 D SplitUIManager: split_name #11 / not available #0
09-12 18:15:37.119  1896  1896 I SplitUIService: split app #11
09-12 18:15:37.125   334   429 I ThermalEngine: Thermal-Server: Thermal received msg from  override
09-12 18:15:37.125  3262  8321 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,09-12 18:15:37.141  1033  1033 D administrator: Handling package changes for user 0
09-12 18:15:37.153  1603  1603 D KeyguardModel: handleShortcutListChanged...
09-12 18:15:37.153  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,09-12 18:15:37.160  1603  1650 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-12 18:15:37.160  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.166  1033  2057 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
09-12 18:15:37.167  1603  1650 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-12 18:15:37.167  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
09-12 18:15:37.167  7755  7755 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
09-12 18:15:37.168  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 18:15:37.168  1603  1650 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-12 18:15:37.174  1603  1650 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-12 18:15:37.174  1603  1650 D KeyguardModel: createShortcutInfo...
,09-12 18:15:37.176  2090  2090 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
09-12 18:15:37.177  2090  2090 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
09-12 18:15:37.178  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:37.179  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 18:15:37.179  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 18:15:37.179  1603  1650 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-12 18:15:37.180  1603  1650 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-12 18:15:37.180  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.181  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
09-12 18:15:37.181  1603  1650 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-12 18:15:37.181  1033  1763 V SIM_STK : Menu title from STK is T-Mobile
09-12 18:15:37.181  1603  1650 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-12 18:15:37.182  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
09-12 18:15:37.183  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
09-12 18:15:37.184  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,09-12 18:15:37.202  2090  2090 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
09-12 18:15:37.202  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 18:15:37.206  2090  2276 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
09-12 18:15:37.206  2090  2276 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
09-12 18:15:37.207  1603  1650 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-12 18:15:37.207  1603  1650 D KeyguardModel: createShortcutInfo...
09-12 18:15:37.212  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14168eb7 u0 com.lge.launcher2/.Launcher t5} time:225762
09-12 18:15:37.217  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:37.218  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
09-12 18:15:37.219  2090  2090 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-12 18:15:37.220  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,09-12 18:15:37.222  1603  1603 D KeyguardModel: handleShortcutListChanged...
09-12 18:15:37.222  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
09-12 18:15:37.225  7377  7394 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 18:15:37.225  7377  7394 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 18:15:37.225  7377  7394 I Adreno-EGL: Build Date: 12/12/14 금
09-12 18:15:37.225  7377  7394 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 18:15:37.225  7377  7394 I Adreno-EGL: Remote Branch: 
09-12 18:15:37.225  7377  7394 I Adreno-EGL: Local Patches: 
09-12 18:15:37.225  7377  7394 I Adreno-EGL: Reconstruct Branch: 
09-12 18:15:37.228  2090  2090 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
09-12 18:15:37.229  2619  2619 D [Concierge]Service: onStartCommand(). Type : 8
09-12 18:15:37.230  2619  2619 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
09-12 18:15:37.230  2619  2619 D [Concierge]Service: Update widget ID : 11
09-12 18:15:37.231  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:37.232  2090  2090 D [Concierge]WidgetView: change position of spinner
09-12 18:15:37.232  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:37.233  2090  2090 I [Concierge]WidgetView: initWebView(). Time : 1473696937233
09-12 18:15:37.233  2619  2619 D [Concierge]Service: onStartCommand(). Type : 0
09-12 18:15:37.239  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:37.248  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:37.259  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:37.261  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,09-12 18:15:37.264  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
09-12 18:15:37.266  8180  8180 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-12 18:15:37.267  1840  1840 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-12 18:15:37.278  2222  2222 I ConfigService: onCreate
,09-12 18:15:37.278  2222  2222 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-12 18:15:37.280  2090  2090 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 619147871
09-12 18:15:37.281  2090  2090 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
09-12 18:15:37.281  2090  2090 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
09-12 18:15:37.283  2222  2222 I ConfigService: onBind returning update interface
09-12 18:15:37.283  2090  2090 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@184e79df
09-12 18:15:37.283  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
09-12 18:15:37.284  2090  2090 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
09-12 18:15:37.284  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 18:15:37.288  2222  2222 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-12 18:15:37.288  2222  2222 I ConfigService: onBind returning config service
09-12 18:15:37.289  1840  1840 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-12 18:15:37.290  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
09-12 18:15:37.290  2090  2090 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-12 18:15:37.291  2090  2090 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1473696739821, New one : 1473696937233
09-12 18:15:37.291  2090  2090 D [Concierge]WidgetView: Unregister all receivers
09-12 18:15:37.291  2090  2090 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
09-12 18:15:37.292  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 18:15:37.294  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,09-12 18:15:37.295  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
09-12 18:15:37.296  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
09-12 18:15:37.297  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
09-12 18:15:37.298  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
09-12 18:15:37.303  1840  1840 I ConfigFetchService: service connected
09-12 18:15:37.303  1840  1840 I ConfigClient: service connected
09-12 18:15:37.303  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 18:15:37.304  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 18:15:37.306  2222  2222 I ConfigService: onDestroy
,09-12 18:15:37.336  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-12 18:15:37.336  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-12 18:15:37.336  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 18:15:37.339  1033  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
09-12 18:15:37.342  1840  8325 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-12 18:15:37.347  2090  2090 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,09-12 18:15:37.355  2090  2090 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
09-12 18:15:37.355  2090  2090 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
09-12 18:15:37.357  2090  2090 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
09-12 18:15:37.358  2090  2090 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
09-12 18:15:37.378  2090  2090 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@23bc7088 time:225928
,09-12 18:15:37.386  6115  8331 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-12 18:15:37.401  1840  8332 I PeopleContactsSync: CP2 sync disabled
09-12 18:15:37.405  7151  7151 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-12 18:15:37.424  2222  2244 I art     : Explicit concurrent mark sweep GC freed 6454(385KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.296ms total 23.746ms
,09-12 18:15:37.427  1840  5076 I Icing   : doRemovePackageData com.test.thalitest
09-12 18:15:37.427  2285  8334 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 18:15:37.444  7377  7394 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 18:15:37.444  7377  7394 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 18:15:37.444  7377  7394 I Adreno-EGL: Build Date: 12/12/14 금
09-12 18:15:37.444  7377  7394 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 18:15:37.444  7377  7394 I Adreno-EGL: Remote Branch: 
09-12 18:15:37.444  7377  7394 I Adreno-EGL: Local Patches: 
09-12 18:15:37.444  7377  7394 I Adreno-EGL: Reconstruct Branch: 
,09-12 18:15:37.446  1033  1942 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8335 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-12 18:15:37.456   350   350 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 209us total 11.561ms
,09-12 18:15:37.466   350   350 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 215us total 10.058ms
09-12 18:15:37.477   350   350 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 10.200ms
,09-12 18:15:37.484  1033  1101 I art     : Explicit concurrent mark sweep GC freed 14075(885KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 23.959ms total 400.766ms
09-12 18:15:37.500  1840  8330 W GmsApplication: Using Auth Proxy for data requests.
,09-12 18:15:37.508  1840  8330 W GmsApplication: Using Auth Proxy for data requests.
09-12 18:15:37.521  7377  7394 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-12 18:15:37.521  7377  7394 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-12 18:15:37.521  7377  7394 I Adreno-EGL: Build Date: 12/12/14 금
09-12 18:15:37.521  7377  7394 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
09-12 18:15:37.521  7377  7394 I Adreno-EGL: Remote Branch: 
09-12 18:15:37.521  7377  7394 I Adreno-EGL: Local Patches: 
09-12 18:15:37.521  7377  7394 I Adreno-EGL: Reconstruct Branch: 
,09-12 18:15:37.528  2090  2090 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
09-12 18:15:37.530  8335  8335 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:15:37.530  8335  8335 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-12 18:15:37.531  8335  8335 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-12 18:15:37.532  8335  8335 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
09-12 18:15:37.571  2090  2875 I GBoardtInterface: onReloaded()
,09-12 18:15:37.574  2090  2090 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
09-12 18:15:37.575  3764  4760 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 18:15:37.579  3764  3781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 18:15:37.585  1930  1930 D ActionManagerService: notifyUserLog: 1000001
,09-12 18:15:37.586  3764  4764 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-12 18:15:37.586  3764  4764 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-12 18:15:37.588  1930  1930 D ActionManagerService: notifyUserLog: 1000001
09-12 18:15:37.590  3764  3781 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
09-12 18:15:37.592  3764  4764 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
09-12 18:15:37.592  3764  4764 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
09-12 18:15:37.592  3764  4764 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
09-12 18:15:37.592  3764  4764 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
09-12 18:15:37.593  2090  2090 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
09-12 18:15:37.593  2090  2090 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
09-12 18:15:37.595  2090  2090 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
09-12 18:15:37.595  2090  2090 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
09-12 18:15:37.595  7692  7692 I UEI.SmartControl: Supports setup maps: true
09-12 18:15:37.597  2090  2090 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
09-12 18:15:37.597  2090  2090 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1473420112499&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
09-12 18:15:37.598  7692  7692 D UEI.SmartControl: QS start statue = true Error code = 0
09-12 18:15:37.598  7692  7692 I UEI.SmartControl: QS version = v2.7.10.1_RC1
09-12 18:15:37.598  7692  7692 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
09-12 18:15:37.598  7692  7692 I UEI.SmartControl: ### init IR Blaster...
,09-12 18:15:37.605  7692  7692 D serial_port: Configuring serial port
09-12 18:15:37.605  7692  7692 E UEI.SmartControl: UEIBLaster setting for 616
09-12 18:15:37.605  7692  7692 I UEI.SmartControl: Setting serial record hearder size = 2
09-12 18:15:37.605  7692  7692 I UEI.SmartControl: configuring settings for MAXQ616
09-12 18:15:37.605  7692  7692 I UEI.SmartControl: Get version...
09-12 18:15:37.621  7692  8354 D UEI.SmartControl: serial port data available: 21
,09-12 18:15:37.634  8335  8335 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-12 18:15:37.638  8286  8286 D AndroidRuntime: Shutting down VM
09-12 18:15:37.646  8335  8335 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,09-12 18:15:37.647  7692  7692 D UEI.SmartControl: MAXQ616 A2-X4 software.
09-12 18:15:37.647  7692  7692 I UEI.SmartControl: IR Blaster version: 256702256704300002
09-12 18:15:37.647  7692  7692 I UEI.SmartControl: QS saving settings...
09-12 18:15:37.647  7692  7692 D UEI.SmartControl: IR Blaster version: 25672567
09-12 18:15:37.659  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:15:37.664  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-12 18:15:37.670  1033  1101 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8357 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-12 18:15:37.685  7692  8354 D UEI.SmartControl: serial port data available: 4
09-12 18:15:37.690  2090  2090 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-12 18:15:37.691  8335  8335 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 18:15:37.711  7692  7692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,09-12 18:15:37.712  7692  7692 E UEI.SmartControl: Services init done
09-12 18:15:37.712  7692  7692 D UEI.SmartControl: QS Service init finished
09-12 18:15:37.713  7692  7692 D UEI.SmartControl: QS Service version name: 2.1.91
09-12 18:15:37.713  7692  7692 D UEI.SmartControl: QS Service version code: 201091
09-12 18:15:37.713  7692  7692 D UEI.SmartControl: Service requested: Control
09-12 18:15:37.714  7692  7692 D UEI.SmartControl: Internal service binding...
09-12 18:15:37.714  8249  8249 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
09-12 18:15:37.714  8335  8335 D LgDataFeature: LgDataFeature() Constructor: none
09-12 18:15:37.714  8335  8335 D LgDataFeature: LgDataFeature() Constructor Done, null
09-12 18:15:37.714  7692  8376 I UEI.SmartControl: Device manager: loading config....
09-12 18:15:37.714  7692  8376 D UEI.SmartControl: ----------- loading internal config...
09-12 18:15:37.716  7692  7708 I UEI.SmartControl: ------ IControl API: 11
09-12 18:15:37.716  7692  7708 D UEI.SmartControl: File observer start...
09-12 18:15:37.716  7692  7708 E UEI.SmartControl: IR Port is disabled: false
09-12 18:15:37.716  7692  7708 D UEI.SmartControl: Starting file observer...
09-12 18:15:37.717  7692  7708 I UEI.SmartControl: Registering callback...
09-12 18:15:37.717  7692  7707 I UEI.SmartControl: ------ IControl API: 19
09-12 18:15:37.718  7692  7707 I UEI.SmartControl: Registering Services Ready callback...
09-12 18:15:37.720  7692  8376 E UEI.SmartControl: Loading SETTINGS...
09-12 18:15:37.723  7692  8376 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,09-12 18:15:37.729   318  8380 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
09-12 18:15:37.730   318  8380 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
09-12 18:15:37.734  7692  8375 I UEI.SmartControl: Notify AllClients services are ready: 0
09-12 18:15:37.734  7692  8375 D UEI.SmartControl: -----service ready thread exits
09-12 18:15:37.734  8249  8270 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,09-12 18:15:37.735  8249  8307 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
09-12 18:15:37.735  8249  8307 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
09-12 18:15:37.735  8249  8249 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
09-12 18:15:37.735  8249  8249 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
09-12 18:15:37.735  7692  7708 I UEI.SmartControl: ------ IControl API: 8
09-12 18:15:37.736  8249  8249 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
09-12 18:15:37.736  8249  8249 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
09-12 18:15:37.736  8249  8249 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
09-12 18:15:37.736  8249  8249 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
09-12 18:15:37.737  8249  8249 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
09-12 18:15:37.737  8249  8249 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
09-12 18:15:37.738  8249  8249 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
09-12 18:15:37.738  8249  8249 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
09-12 18:15:37.739  1033  1573 I ActivityManager: Killing 7783:com.google.android.talk/u0a72 (adj 15): empty #17
09-12 18:15:37.770   318  8380 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,09-12 18:15:37.790  1033  2020 W libprocessgroup: failed to open /acct/uid_10072/pid_7783/cgroup.procs: No such file or directory
,09-12 18:15:37.818  8335  8335 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-12 18:15:37.830  1033  1048 I ActivityManager: Killing 7876:com.android.vending/u0a44 (adj 15): empty #17
,09-12 18:15:37.851  1840  8291 I CheckinTask: Sending checkin request (8213 bytes)
,09-12 18:15:37.888  2090  2875 I GBoardtInterface: exportHTML()
,09-12 18:15:37.910  2040  2040 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
09-12 18:15:37.911  2040  2040 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
09-12 18:15:37.911  1033  1763 W libprocessgroup: failed to open /acct/uid_10044/pid_7876/cgroup.procs: No such file or directory
,09-12 18:15:37.912  2040  2040 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
09-12 18:15:37.923  2090  2875 I GBoardtInterface: exportHTML()
,09-12 18:15:37.932  8180  8180 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
09-12 18:15:37.936  7576  7576 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,09-12 18:15:37.938  6931  6931 D PackageIntentReceiver: Not supported Hotkey customization function 
09-12 18:15:37.945  6931  6931 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
09-12 18:15:37.945  6931  6931 D HideNavigationAppsReceiver: replacing : false
09-12 18:15:37.947  6931  6931 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
09-12 18:15:37.950  6931  6931 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
09-12 18:15:37.950  6931  6931 D ButtonCombinationReceiver: replacing : false
,09-12 18:15:37.952  2090  2875 I GBoardtInterface: exportHTML()
09-12 18:15:37.970  1033  2112 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8386 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:15:37.972  4765  4809 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: Error inserting f004=13 f005=8386 f002=1473696937972 f003=com.android.vending f006=10044
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
09-12 18:15:37.974  4765  4809 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
09-12 18:15:37.984  1840  3935 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak
,09-12 18:15:37.986  1840  3935 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/Checkin.xml to backup file /data/data/com.google.android.gms/shared_prefs/Checkin.xml.bak

```
