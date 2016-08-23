#### Test 821470463bd5c99_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 08:45:00.100  1583  1583 I [SystemUI]Clock: called onTimeUpdated()
08-23 08:45:00.111  1583  1583 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 08:45:00.111  1583  1583 I [SystemUI]DateView: called onTimeUpdated()
08-23 08:45:00.113  1583  1583 I [SystemUI]DateView: called onTimeUpdated()
08-23 08:45:00.115  1583  1583 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 08:45:01.012  6701  6701 D AndroidRuntime: 
08-23 08:45:01.012  6701  6701 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 08:45:01.027  6701  6701 D AndroidRuntime: CheckJNI is OFF
08-23 08:45:01.241  6701  6701 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 08:45:01.251  1030  2029 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 08:45:01.268  1921  2700 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 08:45:01.273  1030  2029 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 08:45:01.275  1030  2029 D ActivityManager: setTaskToReturnTo : TaskRecord{2310ae #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 08:45:01.275  1030  2029 D ActivityManager: setTaskToReturnTo : TaskRecord{2310ae #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 08:45:01.277  1030  2029 D WindowStateEx: AppWindowTokenEx init.. 
08-23 08:45:01.277   344   350 E GBMv2   : DFP En is all cleared set to be enabled
08-23 08:45:01.305  1030  2029 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6716 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 08:45:01.308  6701  6701 D AndroidRuntime: Shutting down VM
08-23 08:45:01.372  1921  1937 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 08:45:01.373  1921  1937 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1a0fb320 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 08:45:01.376  1921  1936 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 08:45:01.377  1921  1936 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c0334d9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 08:45:01.424  6716  6716 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 08:45:01.494  6716  6716 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 08:45:01.503  6716  6716 I LibraryLoader: Loading: webviewchromium
08-23 08:45:01.506  6716  6716 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6536-6540)
08-23 08:45:01.506  6716  6716 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 08:45:01.537  6716  6716 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9a205ce}
08-23 08:45:01.538  6716  6716 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 08:45:01.539  6716  6716 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 08:45:01.550  6716  6716 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 08:45:01.551  6716  6716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 08:45:01.566  6716  6716 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-23 08:45:01.567  6716  6716 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-23 08:45:01.569  6716  6716 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-23 08:45:01.572   313  1363 V AudioPolicyService: registerClient() client 0xb14b78a0, uid 10118
08-23 08:45:01.577  1030  1113 D BluetoothManagerService: Message: 20
08-23 08:45:01.577  1030  1113 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6d77c8:true
08-23 08:45:01.603  6716  6716 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 08:45:01.603  6716  6716 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 08:45:01.603  6716  6716 I Adreno-EGL: Build Date: 12/12/14 금
08-23 08:45:01.603  6716  6716 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 08:45:01.603  6716  6716 I Adreno-EGL: Remote Branch: 
08-23 08:45:01.603  6716  6716 I Adreno-EGL: Local Patches: 
08-23 08:45:01.603  6716  6716 I Adreno-EGL: Reconstruct Branch: 
,08-23 08:45:01.699  6716  6757 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-23 08:45:01.702  6716  6716 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-23 08:45:01.724  6716  6716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 08:45:01.730  6716  6716 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 08:45:01.734  6716  6716 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 08:45:01.738  6716  6716 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 08:45:01.738  6716  6716 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-23 08:45:01.754  6716  6716 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-23 08:45:01.761  6716  6716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 08:45:01.761  6716  6716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 08:45:01.806  6716  6772 D OpenGLRenderer: Render dirty regions requested: true
08-23 08:45:01.806  6716  6772 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 08:45:01.812  6716  6772 D OpenGLRenderer: Enabling debug mode 0
,08-23 08:45:01.823  6716  6716 D Atlas   : Validating map...
,08-23 08:45:01.828  1030  1676 D SplitWindow: check instance of lgWin Window{b03a7c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 08:45:01.867  6716  6770 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:01.867  6716  6770 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 08:45:01.972  1030  1357 D PowerManagerServiceEx: acquireWakeLockInternal: lock=524830195, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1030
,08-23 08:45:01.997  6716  6716 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3fd1ef5 time:167032
,08-23 08:45:02.018  1030  1105 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6779 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-23 08:45:02.028  1030  1114 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +659ms (total +749ms)
08-23 08:45:02.028  1030  1114 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12974e4f u0 com.test.thalitest/.MainActivity t6} time:167062
08-23 08:45:02.029   348   348 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 305us total 16.834ms
08-23 08:45:02.044   348   348 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 285us total 13.248ms
,08-23 08:45:02.055  2586  2586 D [Concierge]Service: onStartCommand(). Type : 9
08-23 08:45:02.059   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 329us total 12.800ms
,08-23 08:45:02.144  6779  6779 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-23 08:45:02.153  6779  6779 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1273ba93
,08-23 08:45:02.153  1030  1030 D PowerManagerServiceEx: releaseWakeLockInternal: lock=524830195 [*alarm*], flags=0x0
08-23 08:45:02.154  1030  1901 I ActivityManager: Killing 6194:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-23 08:45:02.169  6716  6716 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 08:45:02.227  6716  6770 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 08:45:02.227  6716  6770 I chromium: 
,08-23 08:45:02.258  1030  1676 W libprocessgroup: failed to open /acct/uid_10014/pid_6194/cgroup.procs: No such file or directory
,08-23 08:45:02.347  6716  6811 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435171328
,08-23 08:45:02.363  6716  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 08:45:02.363  6716  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 08:45:02.363  6716  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 08:45:02.363  6716  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 08:45:02.363  6716  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 08:45:02.363  6716  6811 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35bca1a9 added. We now have 1 listener(s)
08-23 08:45:02.370  6716  6716 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 08:45:02.370  6716  6716 I chromium: 
,08-23 08:45:02.376  1030  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:02.379  6716  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-23 08:45:02.380  6716  6811 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:02.382  6716  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 08:45:02.383  6716  6811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 08:45:02.392  6716  6811 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b9f905c added. We now have 1 listener(s)
08-23 08:45:02.393  6716  6811 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:02.399  1030  1522 D WifiService: New client listening to asynchronous messages
,08-23 08:45:02.403  6716  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 08:45:02.403  6716  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 08:45:02.405  6716  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 08:45:02.406  6716  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 08:45:02.406  6716  6811 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 08:45:02.410  6716  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:02.410  1030  1678 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:02.411  6716  6811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-23 08:45:02.424  6716  6811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 08:45:02.425  6716  6811 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:02.425  6716  6811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:02.425  6716  6811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:02.425  6716  6811 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:02.425  6716  6811 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:02.425  6716  6811 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:02.425  6716  6811 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:02.425  6716  6811 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:02.425  6716  6811 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 08:45:02.425  6716  6811 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 08:45:02.429  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:02.431  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:02.432  6716  6811 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 08:45:02.479  6716  6716 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 08:45:02.773   344   352 E GBMv2   : DFP En is all cleared set to be enabled
08-23 08:45:02.774   344   352 E GBMv2   : Set value is all cleared set the max
08-23 08:45:02.774   344   352 I GBMv2   : DFP Enabled. Ignore VFP set
08-23 08:45:03.165  6716  6818 W jxcore-log: Initializing JXcore engine
08-23 08:45:03.166  6716  6818 W jxcore-log: JXcore engine is ready
08-23 08:45:03.201  6818  6818 W Thread-787: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[8370]" dev="sockfs" ino=8370 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 08:45:03.201  6818  6818 W Thread-787: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 08:45:03.201  6818  6818 W Thread-787: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10156]" dev="sockfs" ino=10156 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 08:45:03.201  6818  6818 W Thread-787: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-23 08:45:03.201  6818  6818 W Thread-787: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[30374]" dev="sockfs" ino=30374 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-23 08:45:03.216  6716  6818 W jxcore-log: Starting JXcore engine
08-23 08:45:03.295  6716  6818 W jxcore-log: Platform android
08-23 08:45:03.295  6716  6818 W jxcore-log: 
08-23 08:45:03.295  6716  6818 W jxcore-log: Process ARCH arm
08-23 08:45:03.295  6716  6818 W jxcore-log: 
08-23 08:45:03.481  6716  6818 I jxcore-log: JXcore Cordova bridge is ready!
08-23 08:45:03.481  6716  6818 I jxcore-log: 
08-23 08:45:03.481  6716  6818 W jxcore-log: JXcore engine is started
08-23 08:45:03.493  6716  6811 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 08:45:03.496  6716  6716 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 08:45:12.888  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 08:45:12.888  6716  6818 I jxcore-log: 
,08-23 08:45:12.891  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 08:45:12.891  6716  6818 I jxcore-log: 
08-23 08:45:12.897  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:12.897  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:12.897  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:12.897  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:12.897  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:12.897  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:12.897  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:12.897  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:12.900  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:12.902  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 08:45:12.902  6716  6818 I jxcore-log: 
,08-23 08:45:12.904  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 08:45:12.904  6716  6818 I jxcore-log: 
,08-23 08:45:13.409  6716  6818 D ExecuteNativeTests: Running unit tests
,08-23 08:45:13.490  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 08:45:13.490  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 added. We now have 2 listener(s)
08-23 08:45:13.490  1030  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 08:45:13.498  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:13.498  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:13.498  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:13.498  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:13.498  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e added. We now have 2 listener(s)
08-23 08:45:13.498  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:13.498  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 08:45:13.501  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:13.506  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:13.506  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.506  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.506  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:13.506  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:13.506  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.506  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:13.506  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 08:45:13.509  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.509  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:13.512  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.513  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 08:45:13.514  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.516  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 08:45:13.516  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 08:45:13.522  6716  6818 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-23 08:45:13.524  6716  6818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 08:45:13.525  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 08:45:13.525  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 08:45:13.525  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 08:45:13.527  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.530  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.531  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.532  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.532  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.532  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:13.533  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:13.533  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 removed from the list
08-23 08:45:13.533  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.533  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e removed from the list
08-23 08:45:13.533  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.533  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:45:13.535  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.535  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.537  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.537  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.537  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.537  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.538  6716  6818 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-23 08:45:13.538  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.538  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.538  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.539  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.539  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.539  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.539  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.539  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.539  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.539  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.539  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.539  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.539  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.539  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.539  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.539  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.539  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.539  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 08:45:13.543  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 08:45:13.544  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.544  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.544  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.544  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.544  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.544  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.544  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.544  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.544  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.544  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.544  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.544  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.544  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.544  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.546  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.546  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.546  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.546  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.548  6716  6818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 08:45:13.551  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:13.554  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:13.554  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.554  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.554  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:13.554  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:13.554  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.554  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:13.554  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:13.555  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.555  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:13.556  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.557  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:45:13.557  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:45:13.557  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:45:13.557  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:13.557  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 08:45:13.558  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.562  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 08:45:13.562  1030  1555 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:13.571  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 08:45:13.579  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 08:45:13.581  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 08:45:13.583  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 08:45:13.583  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:13.585  6716  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 08:45:13.585  6716  6818 I io.jxcore.node.ConnectionHelper: start: OK
08-23 08:45:13.589  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.589  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.589  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.590  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.590  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.590  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:13.590  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.590  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.590  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.590  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.590  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.590  6716  6818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 08:45:13.591  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:45:13.593  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:13.593  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.593  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.593  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:13.593  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:13.593  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.593  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:13.593  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:13.595  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.595  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:13.596  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.597  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.597  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:45:13.597  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:45:13.597  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:45:13.597  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:13.597  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 08:45:13.600  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 08:45:13.600  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:13.601  6716  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 08:45:13.601  6716  6818 I io.jxcore.node.ConnectionHelper: start: OK
08-23 08:45:13.603  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.603  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.603  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.603  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.603  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.603  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:13.603  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.603  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.603  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryMana,gerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.603  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.603  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.603  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.603  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:45:13.604  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.604  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.606  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.606  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.606  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.606  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.606  6716  6818 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 08:45:13.607  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:13.610  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:13.610  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.610  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.610  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:13.610  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:13.610  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.610  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:13.610  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:13.610  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.611  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:13.612  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.613  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.613  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:45:13.613  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:45:13.613  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:45:13.613  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:13.613  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 08:45:13.615  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 08:45:13.616  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 08:45:13.617  6716  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 08:45:13.617  6716  6818 I io.jxcore.node.ConnectionHelper: start: OK
08-23 08:45:13.617  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.617  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.617  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.618  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.618  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.618  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.618  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.618  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.618  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:13.619  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.619  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.619  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.619  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.619  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.619  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.619  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.620  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.620  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.620  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.620  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.620  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.620  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.621  6716  6818 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-23 08:45:13.621  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.621  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.621  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, s,kipping...
08-23 08:45:13.621  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.621  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.621  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.621  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.621  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.621  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.621  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.621  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.621  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.621  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.621  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.622  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.622  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.622  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.622  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.622  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.622  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.623  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 08:45:13.623  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.623  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.623  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.624  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.624  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.624  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.624  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.624  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.624  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.624  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.624  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.624  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.624  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.624  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.625  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.625  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.625  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.625  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.625  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.625  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.626  6716  6818 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-23 08:45:13.626  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.626  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.626  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.626  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.626  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.626  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.626  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.626  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.626  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.626  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.626  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.626  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.626  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.626  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.628  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.628  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.628  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.628  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.628  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.628  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.629  6716  6818 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-23 08:45:13.629  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.629  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.629  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.629  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.629  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.629  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.629  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.629  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.629  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.629  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.629  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.629  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.629  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.629  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.630  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.630  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.631  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.631  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.631  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.631  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.631  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 08:45:13.632  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 08:45:13.632  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 08:45:13.632  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 08:45:13.632  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 08:45:13.632  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-23 08:45:13.632  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.633  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.633  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.633  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.633  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.633  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.633  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.633  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.633  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.633  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.633  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.633  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.633  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.633  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.638  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.638  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.640  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.640  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.640  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.640  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.641  6716  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-23 08:45:13.641  6716  6818 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 08:45:13.641  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 08:45:13.644  6716  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:45:13.644  6716  6818 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 08:45:13.644  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 08:45:13.645  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 08:45:13.645  6716  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 08:45:13.645  6716  6818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 08:45:13.646  6716  6818 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 08:45:13.646  6716  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:45:13.646  6716  6818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 08:45:13.646  6716  6818 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 08:45:13.646  6716  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:45:13.646  6716  6818 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 08:45:13.646  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-23 08:45:13.648  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-23 08:45:13.648  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 08:45:13.648  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-23 08:45:13.649  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 08:45:13.649  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 08:45:13.649  6716  6818 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 08:45:13.649  6716  6818 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 08:45:13.649  6716  6818 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 08:45:13.650  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.650  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.650  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.650  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.650  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.650  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.650  6716  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 851)
08-23 08:45:13.651  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-23 08:45:13.652  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.652  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.652  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.652  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.652  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.652  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.652  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.652  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.653  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.653  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.653  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.653  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.653  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.653  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.654  6716  6818 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-23 08:45:13.654  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.654  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.654  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.657  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.657  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.657  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.657  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.657  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.657  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.657  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.657  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.657  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.657  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.657  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.658  6716  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 851
08-23 08:45:13.658  6716  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 851)
08-23 08:45:13.658  6716  6823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 851)
08-23 08:45:13.665  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.666  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.667  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.667  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.667  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.667  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.667  6716  6818 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-23 08:45:13.668  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.668  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.668  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.668  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.668  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.668  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.668  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.668  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.668  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.668  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.668  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.668  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.668  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.668  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.669  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.669  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.670  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.670  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.670  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.670  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.670  6716  6818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 08:45:13.670  6716  6818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 08:45:13.670  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 08:45:13.670  6716  6818 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 08:45:13.671  6716  6818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 08:45:13.671  6716  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 08:45:13.671  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 08:45:13.671  6716  6818 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 08:45:13.671  6716  6818 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 08:45:13.671  6716  6818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 08:45:13.671  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 08:45:13.671  6716  6818 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 08:45:13.671  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.671  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.671  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.671  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.671  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.671  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.671  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.671  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.671  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.671  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.671  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.671  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.672  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.672  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.672  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.672  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.673  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.673  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.673  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.673  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.673  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.673  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.673  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.673  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.673  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.673  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.673  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.673  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.673  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.673  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.673  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.673  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.673  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.673  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.673  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.673  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.673  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.673  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.674  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.674  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.674  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.674  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.674  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.674  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.674  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.674  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.674  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.674  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.674  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.675  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.675  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.675  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.675  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.675  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.675  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.677  6716  6818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 08:45:13.677  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:13.679  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-23 08:45:13.679  6716  6818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 08:45:13.679  6716  6818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 08:45:13.684  6716  6716 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 08:45:13.684  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 08:45:13.685  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 08:45:13.686  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.686  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 08:45:13.686  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 08:45:13.686  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 08:45:13.686  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.686  6716  6818 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 08:45:13.687  6716  6716 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 08:45:13.687  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.687  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.687  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 08:45:13.687  6716  6818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 08:45:13.687  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 08:45:13.687  1030  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:13.688  6716  6824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:13.689  4286  4303 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-23 08:45:13.690  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 08:45:13.690  6716  6824 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-23 08:45:13.690  6716  6824 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 08:45:13.690  6716  6824 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 08:45:13.691  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:13.691  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:13.691  6716  6818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 08:45:13.691  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.691  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.692  6716  6818 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 08:45:13.692  6716  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:45:13.692  6716  6716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 08:45:13.692  6716  6716 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 08:45:13.692  6716  6716 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 08:45:13.693  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.693  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.693  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.693  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.693  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.693  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.693  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.693  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.693  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.693  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.693  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.693  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.693  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.693  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.693  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.694  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.694  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.694  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.694  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.695  6716  6818 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-23 08:45:13.695  6716  6818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 08:45:13.695  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 08:45:13.696  6716  6818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 08:45:13.696  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.696  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.696  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.697  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.697  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.697  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.697  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.697  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.697  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.697  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.697  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.697  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.697  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.697  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:45:13.697  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.697  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.697  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.698  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.698  1030  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:13.699  1030  1676 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:13.700  1030  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:13.701  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.701  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.701  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.702  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.702  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.702  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.702  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.702  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.702  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.702  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.702  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.702  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.702  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.702  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.702  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.702  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.702  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.702  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.704  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:13.704  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:13.704  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:13.704  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:13.704  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.704  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.704  6716  6818 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32fe3c39 not in the list
08-23 08:45:13.704  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.704  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.704  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:13.704  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.704  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.704  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:13.704  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:13.705  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:13.705  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:13.705  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:13.705  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39af327e not in the list
08-23 08:45:13.706  6716  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-23 08:45:13.706  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 08:45:13.706  6716  6818 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 08:45:13.706  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 08:45:13.706  6716  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 08:45:13.706  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 08:45:13.707  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 08:45:13.707  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-23 08:45:13.708  6716  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-23 08:45:13.708  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 08:45:13.708  6716  6818 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 08:45:13.708  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 08:45:13.708  6716  6818 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 08:45:13.708  6716  6818 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-23 08:45:13.709  6716  6818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-23 08:45:13.709  6716  6818 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-23 08:45:13.709  6716  6818 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-23 08:45:13.709  6716  6818 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-23 08:45:13.709  6716  6818 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 08:45:13.709  6716  6818 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-23 08:45:13.710  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:13.710  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12419fd7 added. We now have 2 listener(s)
08-23 08:45:13.710  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:13.711  6716  6818 D BluetoothAdapter: enable(): BT is already enabled..!
08-23 08:45:13.713  1030  1892 D WifiServiceImplEx: setWifiEnabled: true pid=6716, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 08:45:13.713  1030  1892 D WifiService: setWifiEnabled: true pid=6716, uid=10118
08-23 08:45:13.713  1030  1892 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 08:45:13.714  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:13.714  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3beec0c4 added. We now have 3 listener(s)
08-23 08:45:13.714  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:13.719  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:13.719  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1efbfbad added. We now have 4 listener(s)
08-23 08:45:13.720  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:13.721  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:13.721  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc70ee2 added. We now have 5 listener(s)
08-23 08:45:13.721  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:13.722  1030  1892 D WifiServiceImplEx: setWifiEnabled: false pid=6716, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 08:45:13.722  1030  1892 D WifiService: setWifiEnabled: false pid=6716, uid=10118
08-23 08:45:13.722  1030  1892 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 08:45:13.733  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 08:45:13.733  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 08:45:13.733  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-23 08:45:13.734  1030  1678 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:13.734  1030  1678 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@380274ed mBinding = false
08-23 08:45:13.734  1030  1517 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:13.734  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:13.735  1030  1517 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:13.735  1030  1517 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:13.736  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:13.736  1030  1517 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 08:45:13.736  1030  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 08:45:13.736  1030  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 08:45:13.738  1030  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 08:45:13.738  1030  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 08:45:13.745  1030  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 08:45:13.745  1030  1515 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.745  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.745  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 08:45:13.746  2661  2661 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 08:45:13.746  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 08:45:13.746  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 08:45:13.747  1030  1517 D WifiNative-wlan0: SET ps 1: returned true
,08-23 08:45:13.747  1030  2784 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.751   308   888 D CommandListener: Clearing all IP addresses on wlan0
08-23 08:45:13.762  6716  6822 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-23 08:45:13.763  6716  6822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 851)
08-23 08:45:13.768  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 08:45:13.769  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 08:45:13.769  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-23 08:45:13.769  1030  1113 D BluetoothManagerService: Message: 2
08-23 08:45:13.771  1030  1113 D BluetoothManagerService: Sending off request.
08-23 08:45:13.771  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:13.772  4286  4303 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-23 08:45:13.773  4286  4354 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-23 08:45:13.773  4286  4354 D BluetoothAdapterProperties: Setting state to 13
08-23 08:45:13.773  4286  4354 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 08:45:13.774  4286  4354 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 08:45:13.774  4286  4354 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-23 08:45:13.776  4286  4357 D BluetoothAdapterProperties: Scan Mode:20
08-23 08:45:13.776  4286  4354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 08:45:13.777  4286  4354 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 08:45:13.778  4286  4634 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-23 08:45:13.778  4286  4634 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:13.778  4286  4634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-23 08:45:13.778  4286  4634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-23 08:45:13.778  4286  4634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-23 08:45:13.778  4286  4634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-23 08:45:13.778  4286  4634 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-23 08:45:13.778  4286  4634 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-23 08:45:13.779  4286  4692 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:13.779  4286  4642 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:13.779  4286  4670 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:13.779  4286  4690 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:13.781  1030  1113 D BluetoothManagerService: Message: 60
08-23 08:45:13.781  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-23 08:45:13.781  1030  1113 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-23 08:45:13.783  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-23 08:45:13.784  4286  4463 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-23 08:45:13.786  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-23 08:45:13.786  4286  4463 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 08:45:13.788  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.788  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:13.788  6716  6818 V io.jxcore.node.ConnectivityMonit,or:     - is Wi-Fi Direct supported: true
08-23 08:45:13.788  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.788  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:13.788  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:13.788  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.788  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:13.788  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:13.788  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.788  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.789  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:13.789  1030  1920 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-23 08:45:13.789  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 08:45:13.789  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.789  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-23 08:45:13.789  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.790  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-23 08:45:13.791  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.792  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.794  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.794  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:13.794  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.794  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.794  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:13.794  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:13.794  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.794  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:13.794  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:13.794  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.794  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:13.795  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:13.797   308  6840 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-23 08:45:13.798  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-23 08:45:13.799  1030  1111 D DSQN    : Dns fail occured do internet check.
08-23 08:45:13.799  1030  1030 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-23 08:45:13.799  1030  1030 D DSQN    : try Internet connection check
08-23 08:45:13.799  1030  1523 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 08:45:13.799  1030  1523 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-23 08:45:13.802   308  6843 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-23 08:45:13.803  1030  1111 D DSQN    : Dns timeout INTERNET_CHECK already in progress ignore!
08-23 08:45:13.803  1030  6842 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-23 08:45:13.803  1030  6841 D DSQN    : ThreadInternetCheck internet check NOK 
08-23 08:45:13.803  1030  6841 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
08-23 08:45:13.803  1030  6841 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.ac,cess$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-23 08:45:13.828  1030  1105 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6846 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-23 08:45:13.830  1030  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.831  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.831  1030  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.832  1030  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.832  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.832  1030  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.833  1030  1517 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 08:45:13.833  1030  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.834  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.834  1030  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:13.835  1030  1515 D LGWifiP2pService: InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.836  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.836  1030  1515 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@864871c
08-23 08:45:13.836  1921  1921 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:13.837  1583  1583 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 08:45:13.839  4286  4286 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:13.839  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 08:45:13.839  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:13.839  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.839  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.839  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:13.839  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:13.839  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:13.839  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:13.839  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:13.839  4286  4286 D BluetoothMapService: STATE_TURNING_OFF
08-23 08:45:13.840  4286  4286 V BluetoothMapService: Handler(): got msg=4
08-23 08:45:13.840  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.840  4286  4286 D BluetoothMapService: MAP Service closeService in
08-23 08:45:13.840  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:13.840  4286  4286 D BluetoothMapMasInstance: MAP Service shutdown
08-23 08:45:13.840  4286  4286 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 08:45:13.840  4286  4286 V BluetoothMapService: MAP Service closeService out
08-23 08:45:13.841  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.842  4286  4286 V BtOppService: Receiver DISABLED_ACTION 
08-23 08:45:13.842  4286  4286 I BtOppRfcommListener: stopping Accept Thread
08-23 08:45:13.842  4286  4286 V BtOppRfcommListener: close mBtServerSocket
08-23 08:45:13.842  4286  4286 V BtOppRfcommListener: waiting for thread to terminate
08-23 08:45:13.843  4286  4670 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 08:45:13.843  1030  1523 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-23 08:45:13.843  1030  1523 D DSQN    : disableDataServiceNotify
08-23 08:45:13.843  4286  4286 V BtOppRfcommListener: done waiting for thread to terminate
08-23 08:45:13.843  1030  1523 D DSQN    : stop dsqn bin
08-23 08:45:13.843  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:13.843  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.843  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.843  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:13.843  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:13.843  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:13.843  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:13.843  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:13.844  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.844  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:13.858  1030  1523 D ConnectivityService: notifyType L,OST for NetworkAgentInfo [WIFI () - 100]
,08-23 08:45:13.858  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:13.858  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:13.858  1030  1523 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:13.858  1030  1523 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-23 08:45:13.859  1030  1523 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-23 08:45:13.859  1030  1523 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-23 08:45:13.859  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 08:45:13.859  1583  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-23 08:45:13.859  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.859  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.860  1030  2782 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-23 08:45:13.883  1030  1105 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6865 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 08:45:13.884  1030  1523 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:13.884  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 08:45:13.884  1030  1523 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:13.884  1030  1523 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:13.884  1030  1523 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:13.885  1030  1515 D LGWifiP2pService: P2pDisablingState
08-23 08:45:13.885  1030  1515 D LGWifiP2pService: P2pDisablingState{ when=-49ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.885  1030  1515 D LGWifiP2pService: p2p socket connection lost
08-23 08:45:13.885  1030  1515 D LGWifiP2pService: P2pDisabledState
08-23 08:45:13.885  1030  1523 D NetworkManagementService: Removing idletimer
08-23 08:45:13.885  4286  4286 V BtOppService: onDestroy
08-23 08:45:13.886  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-23 08:45:13.886  1030  1523 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:13.886  1030  1523 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 08:45:13.887  1832  1832 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:13.887  1921  1921 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-23 08:45:13.887  1030  1517 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:13.887  1832  1832 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 08:45:13.887  1030  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:13.888  1030  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-23 08:45:13.888  1030  1515 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.888  1030  1515 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.888  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 08:45:13.889  2661  2661 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 08:45:13.889  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 08:45:13.889  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 08:45:13.889  1030  1517 D WifiNative-wlan0: SET ps 1: returned true
08-23 08:45:13.889   308   888 D CommandListener: Clearing all IP addresses on wlan0
08-23 08:45:13.891  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:13.891  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:13.891  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 08:45:13.891  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-23 08:45:13.891  1030  1030 W Settings: Setting stay_on_while_pl,ugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:13.891  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:13.891  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 08:45:13.891  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 08:45:13.892  1030  1030 D RttService: SCAN_AVAILABLE : 1
08-23 08:45:13.892  1030  1030 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-23 08:45:13.892  1030  1537 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.893  1030  1536 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.893  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 08:45:13.893  1921  1921 D WfdsService: WifiP2pState is changed : false
08-23 08:45:13.893  1921  2257 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-23 08:45:13.893  1921  2257 D WfdsService: Set the WFDS Monitor: false
08-23 08:45:13.894  1921  2257 D WfdsMonitor: WFDS Monitor is stopped
08-23 08:45:13.894  1921  2257 D WfdsService: STATE : WfdsDisabledState - enter
08-23 08:45:13.894  1921  2708 D CtrlSupplicant: Received on exit socket, terminate
08-23 08:45:13.894  1921  2708 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-23 08:45:13.894  1921  2708 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-23 08:45:13.894  1921  2708 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-23 08:45:13.895  1921  2259 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-23 08:45:13.895  1921  2257 W WfdsService: DefaultState - msg [9445378] is not handled
,08-23 08:45:13.896  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:13.896  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:13.897  1921  2700 D WifiServiceExtension: isInternetCheckAvailable return false
08-23 08:45:13.898  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:13.901  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:13.901  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:13.901  1030  1514 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 08:45:13.901  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 08:45:13.901  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 08:45:13.902  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 08:45:13.902  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 08:45:13.902  1030  1514 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 08:45:13.903  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:13.903  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 08:45:13.903  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 08:45:13.903  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 08:45:13.903  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 08:45:13.907  1030  1517 D WifiNative-p2p0: doBoolean: TERMINATE
08-23 08:45:13.908  4286  4286 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-23 08:45:13.909  1030  1517 D WifiNative-p2p0: TERMINATE: returned true
08-23 08:45:13.909  1030  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 08:45:13.909  1030  1517 E WifiStateMachine: useWiFiOffloading() : false
08-23 08:45:13.909  1030  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-23 08:45:13.911  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-23 08:45:13.916  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:13.916  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:13.917  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 08:45:13.919  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-23 08:45:13.922  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-23 08:45:13.923  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:13.923  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-23 08:45:13.924  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.924  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:13.924  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.924  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.924  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:13.924  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:13.924  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:13.924  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:13.924  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:13.925  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.925  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:13.927  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.927  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:13.927  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:13.927  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:13.927  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:13.927  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:13.927  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:13.927  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:13.927  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:13.928  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:13.928  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:45:13.945  6865  6865 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:45:13.946  6865  6865 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-23 08:45:13.946  6865  6865 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 08:45:13.947  6865  6865 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-23 08:45:13.948  6865  6865 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 08:45:13.948  6865  6865 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 08:45:13.950  1583  1583 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 08:45:13.951  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:13.951  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:13.957  1030  2784 D DhcpStateMachine: StoppedState
08-23 08:45:13.958  1030  2784 D DhcpStateMachine: StoppedState{ when=-69ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:13.959  1030  1517 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-23 08:45:13.959  1030  1517 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-23 08:45:13.966  1583  1583 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 08:45:13.967  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:13.968  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:13.968  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 08:45:13.968  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:13.969  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 08:45:13.991  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 08:45:13.996  2661  2661 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-23 08:45:13.996  2661  2661 I wpa_supplicant: monitor socket send errors count : 1
08-23 08:45:13.996  2661  2661 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1921-2\x00 that cannot receive messages
08-23 08:45:13.997  1030  2699 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-23 08:45:13.997  1030  2699 D WifiMonitor: Dropping event because (p2p0) is stopped
08-23 08:45:14.004  6846  6846 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 08:45:14.004  6846  6846 W LG Account v2.2: No ProfileInfo entries
08-23 08:45:14.004  6846  6846 I LG Account v2.2: isEnabled: false
08-23 08:45:14.004  6846  6846 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 08:45:14.004  6846  6846 I Feature : [Lifetracker]Country: EU
08-23 08:45:14.004  6846  6846 I Feature : [Lifetracker]Operator: OPEN
08-23 08:45:14.004  6846  6846 I Feature : [Lifetracker]Ranking support: false
08-23 08:45:14.005  6846  6846 I Feature : [Lifetracker]Comfort support: false
08-23 08:45:14.005  6846  6846 I Feature : [Lifetracker]Accessory: true
08-23 08:45:14.005  6846  6846 I Feature : [Lifetracker]Health device: true
08-23 08:45:14.005  6846  6846 I Feature : [Lifetracker]Extra Pedometer: false
08-23 08:45:14.005  6846  6846 I Feature : [Lifetracker]Blood glucose device: false
08-23 08:45:14.005  6846  6846 I Feature : [Lifetracker]Device Number: 3
,08-23 08:45:14.018  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:14.037  2661  2661 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 08:45:14.037  1030  2699 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-23 08:45:14.037  1030  2699 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 08:45:14.037  1030  2699 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 08:45:14.037  1030  2699 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
,08-23 08:45:14.037  2661  2661 W wpa_supplicant: USIM:  scard_deinit function
08-23 08:45:14.037  1030  1517 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179058
08-23 08:45:14.038  1030  1517 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=179058
08-23 08:45:14.038  1030  2699 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-23 08:45:14.038  1030  2699 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:14.038  1030  1517 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179059  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 08:45:14.039  1030  1517 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=179059  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 08:45:14.043  1030  1113 D Tethering: InitialState.processMessage what=4
08-23 08:45:14.051  6865  6865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-23 08:45:14.059  1030  1555 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6886 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 08:45:14.060  1030  1555 I ActivityManager: Killing 6260:com.android.defcontainer/u0a4 (adj 15): empty #17
08-23 08:45:14.098  1030  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 08:45:14.098  1030  1956 W libprocessgroup: failed to open /acct/uid_10004/pid_6260/cgroup.procs: No such file or directory
,08-23 08:45:14.102  1030  1113 D BluetoothManagerService: Message: 20
08-23 08:45:14.103  1030  1113 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16b3829c:true
08-23 08:45:14.103  1030  1517 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:14.103  1030  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:14.106  4286  4286 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 08:45:14.106  4286  4286 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:14.106  4286  4286 V BluetoothPbapReceiver: ***********state = 13
08-23 08:45:14.107  4286  4286 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-23 08:45:14.108  4286  4286 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:14.108  4286  4286 V BluetoothPbapService: state: 13
08-23 08:45:14.108  4286  4286 V BluetoothPbapService: Pbap Service closeService in
08-23 08:45:14.109  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 08:45:14.110  4286  4286 V BluetoothPbapService: successfully stopped pbap service
08-23 08:45:14.110  4286  4286 V BluetoothPbapService: Pbap Service closeService out
08-23 08:45:14.110  4286  4286 V BluetoothPbapService: Pbap Service onDestroy
08-23 08:45:14.110  4286  4286 V BluetoothPbapService: Pbap Service closeService in
08-23 08:45:14.110  4286  4286 V BluetoothPbapService: Pbap Service closeService out
08-23 08:45:14.111  4286  4286 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-23 08:45:14.124  1030  1113 D BluetoothManagerService: Message: 30
08-23 08:45:14.126  2661  2661 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-23 08:45:14.126  1030  2699 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-23 08:45:14.127  1030  2699 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-23 08:45:14.127  1030  2699 D WifiMonitor: Disconnecting from the supplicant, no more events
08-23 08:45:14.128  1030  1517 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-23 08:45:14.135  1030  1113 D BluetoothManagerService: Message: 30
08-23 08:45:14.138  6865  6865 D LocalBluetoothProfileManager: Adding local MAP profile
08-23 08:45:14.139  6865  6865 D BluetoothMap: Create BluetoothMap proxy object
08-23 08:45:14.141  1030  1113 D BluetoothManagerService: Message: 30
,08-23 08:45:14.146  1030  1113 D BluetoothManagerService: Message: 30
08-23 08:45:14.148  6865  6865 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-23 08:45:14.149  6865  6865 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-23 08:45:14.159  6886  6886 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-23 08:45:14.164  6865  6865 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-23 08:45:14.167  6865  6865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-23 08:45:14.167  6886  6886 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 08:45:14.168  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:14.174  1030  1956 I ActivityManager: Killing 6408:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-23 08:45:14.193  6716  6716 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 08:45:14.208  1030  1052 W libprocessgroup: failed to open /acct/uid_10008/pid_6408/cgroup.procs: No such file or directory
,08-23 08:45:14.208  6865  6865 D DockEventReceiver: finishStartingService: stopping service
08-23 08:45:14.227  6865  6865 D BluetoothInputDevice: Proxy object connected
,08-23 08:45:14.228  6865  6865 D HidProfile: Bluetooth service connected
,08-23 08:45:14.230  6865  6865 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 08:45:14.232  6865  6865 D PanProfile: Bluetooth service connected
08-23 08:45:14.234  1030  1517 D WifiOffDelayIfNotUsed: stopMonitoring
08-23 08:45:14.234  1030  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 08:45:14.234  1030  1517 E WifiStateMachine: useWiFiOffloading() : false
08-23 08:45:14.234  1030  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 08:45:14.234  1921  1921 D WfdsService: Supplicant Connection state is changed : false
08-23 08:45:14.234  1921  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-23 08:45:14.234  1921  2257 D WfdsService: Set the WFDS Monitor: false
08-23 08:45:14.234  1921  2257 D WfdsMonitor: WFDS Monitor is stopped
08-23 08:45:14.236  6865  6865 D BluetoothMap: Proxy object connected
08-23 08:45:14.236  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 08:45:14.239  2488  2488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:14.239  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:14.239  6865  6865 D MapProfile: Bluetooth service connected
08-23 08:45:14.240  6865  6865 D BluetoothMap: getConnectedDevices()
,08-23 08:45:14.242  6865  6865 D BluetoothMap: Bluetooth is Not enabled
08-23 08:45:14.243  6865  6865 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-23 08:45:14.244  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:14.246  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-23 08:45:14.247  1030  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-23 08:45:14.247  1030  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-23 08:45:14.248  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:14.257  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:14.295  6865  6865 D LgDataFeature: LgDataFeature() Constructor: none
,08-23 08:45:14.295  6865  6865 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:14.304  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:14.306  6865  6865 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-23 08:45:14.312  6865  6865 D BluetoothPermissionRequest: onReceive
08-23 08:45:14.316  6865  6865 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-23 08:45:14.323  1030  1974 I ActivityManager: Killing 5971:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-23 08:45:14.328  6865  6865 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 08:45:14.369  4286  4286 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-23 08:45:14.370  4286  4286 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-23 08:45:14.371  4286  4286 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-23 08:45:14.373  1030  1901 W libprocessgroup: failed to open /acct/uid_10011/pid_5971/cgroup.procs: No such file or directory
08-23 08:45:14.471  1030  1974 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6917 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-23 08:45:14.472  4286  4286 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:14.472  4286  4286 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 08:45:14.473  4286  4286 V BluetoothFtpService: Ftp Service onStartCommand
08-23 08:45:14.473  4286  4286 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:14.474  4286  4286 V BluetoothFtpService: Ftp Service closeService
08-23 08:45:14.474  4286  4286 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-23 08:45:14.477  4286  4286 V BluetoothFtpService: successfully stopped ftp service
08-23 08:45:14.477  4286  4286 V BluetoothFtpService: Ftp Service onDestroy
08-23 08:45:14.477  4286  4286 V BluetoothFtpService: Ftp Service closeService
08-23 08:45:14.481  4286  4286 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 08:45:14.481  4286  4286 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 08:45:14.481  4286  4286 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 08:45:14.481  4286  4286 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:14.481  4286  4286 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-23 08:45:14.481  4286  4286 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-23 08:45:14.484  4286  4286 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:14.484  4286  4286 V BluetoothSapService: state: 13
08-23 08:45:14.484  4286  4286 V BluetoothSapService: Stopping SAP server process
08-23 08:45:14.485  4286  4286 V BluetoothSapService: Sap Service closeSapService in
08-23 08:45:14.485  4286  4286 V BluetoothSapService: Close listen Socket : 
08-23 08:45:14.485  4286  4286 V BluetoothSapService: Close rfcomm Socket : 
08-23 08:45:14.485  4286  4286 V BluetoothSapService: Close sapd  Socket : 
08-23 08:45:14.534  1030  1974 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6934 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 08:45:14.536  4286  4286 V BluetoothSapService: Sap Service closeSapService out
08-23 08:45:14.536  4286  4286 V BluetoothSapService: Sap Service onDestroy
08-23 08:45:14.536  4286  4286 V BluetoothSapService: Sap Service closeSapService in
08-23 08:45:14.536  4286  4286 V BluetoothSapService: Close listen Socket : 
08-23 08:45:14.536  4286  4286 V BluetoothSapService: Close rfcomm Socket : 
08-23 08:45:14.536  4286  4286 V BluetoothSapService: Close sapd  Socket : 
08-23 08:45:14.536  4286  4286 V BluetoothSapService: Sap Service closeSapService out
,08-23 08:45:14.578  6917  6917 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 08:45:14.603  6917  6917 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-23 08:45:14.613  6934  6934 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 08:45:14.629  1030  1974 I ActivityManager: Killing 5994:com.android.contacts/u0a19 (adj 15): empty #17
,08-23 08:45:14.639  6917  6917 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-23 08:45:14.640  6917  6917 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-23 08:45:14.640  6917  6917 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-23 08:45:14.640  6917  6917 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-23 08:45:14.641  6917  6917 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-23 08:45:14.643  6917  6917 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-23 08:45:14.648  6917  6917 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-23 08:45:14.661  1030  1956 W libprocessgroup: failed to open /acct/uid_10019/pid_5994/cgroup.procs: No such file or directory
,08-23 08:45:14.669  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 08:45:14.672  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:14.689  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-23 08:45:14.693  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:14.698  6886  6886 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 08:45:14.698  6886  6886 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 08:45:14.698  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:14.699  6917  6917 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-23 08:45:14.701  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:14.707  6917  6917 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-23 08:45:14.714  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:14.724  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:14.725  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 08:45:14.728  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 08:45:14.732  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:14.738  6886  6886 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 08:45:14.738  6886  6886 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 08:45:14.738  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 08:45:14.744  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:14.757  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:14.771  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:14.772  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:14.775  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-23 08:45:14.790  4286  4357 D bt_hci_bdroid: cleanup
,08-23 08:45:14.790  4286  4463 W bt-btif : ag scb idx 1 not allocated
08-23 08:45:14.790  4286  4463 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 08:45:14.790  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:14.790  4286  4463 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:45:14.790  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:14.790  4286  4463 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:14.791  4286  4463 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-23 08:45:14.791  4286  4463 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 08:45:14.791  4286  4475 I bt_lpm  : LPM is already off!!!
08-23 08:45:14.792  4286  4628 I bt_userial_mct: exiting userial_read_thread
08-23 08:45:14.792  4286  4628 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 08:45:14.792  4286  4357 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-23 08:45:14.792  4286  4475 I bt_vendor: hw_epilog_process
08-23 08:45:14.793  4286  4357 D bt_hci_bdroid: cleanup Finalizing cleanup
08-23 08:45:14.793  4286  4357 D bt_userial_mct: userial_close
08-23 08:45:14.793  4286  4357 E bt_userial_mct: pthread_join() FAILED result:3
08-23 08:45:14.793  4286  4357 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-23 08:45:14.879  1030  1938 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6964 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-23 08:45:14.885  4286  4357 D bt_hci_bdroid: set_power 0
08-23 08:45:14.885  4286  4357 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 08:45:14.886  4286  4357 I bt_vendor: bluetooth satus is on
08-23 08:45:14.886  4286  4357 I bt_vendor: bt-vendor : resetting BT status
08-23 08:45:14.886  4286  4357 I bt_vendor: Starting hciattach daemon
08-23 08:45:14.886  4286  4357 I bt_vendor: try to set false
08-23 08:45:14.886  4286  4357 I bt_vendor: Starting hciattach daemon
08-23 08:45:14.886  4286  4357 I bt_vendor: try to set false
08-23 08:45:14.887  4286  4357 I bt_vendor: cleanup
08-23 08:45:14.888  4286  4463 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-23 08:45:14.890  4286  4357 I GKI_LINUX: GKI_exit_task 0 done
08-23 08:45:14.890  4286  4357 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-23 08:45:14.891  4286  4354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-23 08:45:14.896  4286  4286 D HeadsetService: Received stop request...Stopping profile...
08-23 08:45:14.897  4286  4286 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 08:45:14.897  4286  4286 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 08:45:14.898  4286  4286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3156cef
08-23 08:45:14.898  4286  4407 D HeadsetStateMachine: Exit Disconnected: -1
08-23 08:45:14.899  1832  1832 D BluetoothHeadset: Proxy object disconnected
08-23 08:45:14.900  1832  1832 D BluetoothHeadset: Proxy object disconnected
08-23 08:45:14.900  1030  1030 D BluetoothHeadset: Proxy object disconnected
08-23 08:45:14.900  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-23 08:45:14.901  1832  1832 D BluetoothHeadset: Proxy object disconnected
08-23 08:45:14.903  4286  4286 D A2dpService: Received stop request...Stopping profile...
08-23 08:45:14.903  4286  4354 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 08:45:14.904  4286  4443 D A2dpStateMachine: Exit Disconnected: -1
08-23 08:45:14.905  4286  4286 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-23 08:45:14.908  4286  4286 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-23 08:45:14.908  4286  4286 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 08:45:14.908  4286  4286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3156cef
08-23 08:45:14.910  1030  1030 D BluetoothA2dp: Proxy object disconnected
08-23 08:45:14.910  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 08:45:14.911  4286  4286 D HidService: Received stop request...Stopping profile...
,08-23 08:45:14.911  4286  4286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3156cef
08-23 08:45:14.912  6865  6865 D BluetoothInputDevice: Proxy object disconnected
08-23 08:45:14.913  4286  4286 D HealthService: Received stop request...Stopping profile...
08-23 08:45:14.913  4286  4286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3156cef
08-23 08:45:14.913  6865  6865 D HidProfile: Bluetooth service disconnected
08-23 08:45:14.916  4286  4286 D PanService: Received stop request...Stopping profile...
08-23 08:45:14.916  4286  4286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3156cef
08-23 08:45:14.918  4286  4286 D HeadsetStateMachine: Unbinding service...
08-23 08:45:14.919  6865  6865 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 08:45:14.919  6865  6865 D PanProfile: Bluetooth service disconnected
08-23 08:45:14.919  4286  4286 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,08-23 08:45:14.919  4286  4286 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 08:45:14.919  4286  4286 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 08:45:14.919  4286  4286 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 08:45:14.919  4286  4286 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-23 08:45:14.919  4286  4286 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 08:45:14.919  4286  4286 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 08:45:14.919  4286  4286 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 08:45:14.920  4286  4286 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 08:45:14.920  4286  4286 D BtGatt.GattService: stop()
08-23 08:45:14.920  4286  4286 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 08:45:14.921  4286  4286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3156cef
08-23 08:45:14.922  4286  4286 D BluetoothMapService: Received stop request...Stopping profile...
08-23 08:45:14.922  4286  4286 D BluetoothMapService: stop()
08-23 08:45:14.923  4286  4286 D BluetoothMapEmailAppObserver: deinitObservers()
08-23 08:45:14.923  4286  4286 D BluetoothMapEmailAppObserver: removeReceiver()
08-23 08:45:14.924  4286  4286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3156cef
08-23 08:45:14.925  4286  4286 I BluetoothA2dpServiceJni: cleanupNative
08-23 08:45:14.925  4286  4444 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 08:45:14.926  6865  6865 D BluetoothMap: Proxy object disconnected
08-23 08:45:14.926  4286  4286 I GKI_LINUX: GKI_exit_task 2 done
08-23 08:45:14.926  4286  4286 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 08:45:14.926  6865  6865 D MapProfile: Bluetooth service disconnected
08-23 08:45:14.926  4286  4286 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 08:45:14.926  4286  4286 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 08:45:14.926  4286  4286 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 08:45:14.927  4286  4286 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 08:45:14.927  4286  4286 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 08:45:14.927  4286  4286 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 08:45:14.927  4286  4286 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 08:45:14.928  4286  4286 V BluetoothMapService: Handler(): got msg=4
08-23 08:45:14.928  4286  4286 D BluetoothMapService: MAP Service closeService in
08-23 08:45:14.929  4286  4286 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 08:45:14.929  4286  4286 V BluetoothMapService: MAP Service closeService out
08-23 08:45:14.929  4286  4354 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-23 08:45:14.929  4286  4354 D BluetoothAdapterProperties: Setting state to 10
08-23 08:45:14.929  4286  4354 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-23 08:45:14.929  1030  1113 D BluetoothManagerService: Message: 60
08-23 08:45:14.929  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,08-23 08:45:14.930  1030  1113 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-23 08:45:14.930  4286  4286 D BluetoothMapService: cleanup()
08-23 08:45:14.930  4286  4286 D BluetoothMapService: MAP Service closeService in
08-23 08:45:14.930  4286  4286 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 08:45:14.930  4286  4286 V BluetoothMapService: MAP Service closeService out
08-23 08:45:14.931  4286  4354 I BluetoothAdapterState: Entering OffState
,08-23 08:45:14.931  1832  1847 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 08:45:14.932  6865  6881 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 08:45:14.932  1832  1848 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 08:45:14.933  6865  6880 D BluetoothMap: onBluetoothStateChange: up=false
08-23 08:45:14.935  1030  1113 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 08:45:14.935  1832  2688 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 08:45:14.936  1030  1113 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 08:45:14.936  6865  6881 D BluetoothPan: onBluetoothStateChange on: false
08-23 08:45:14.937  6865  6880 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 08:45:14.938  1030  1113 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-23 08:45:14.938  1030  1113 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-23 08:45:14.941  1030  1113 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-23 08:45:14.941  1030  1113 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-23 08:45:14.941  1030  1113 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@380274ed mBinding = false
08-23 08:45:14.942  1030  1113 D BluetoothManagerService: Sending unbind request.
08-23 08:45:14.944  1030  1113 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-23 08:45:14.950  1921  1921 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:14.953  1921  2059 D LGBluetoothAPIService: Message: 2
,08-23 08:45:14.953  1921  2059 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@104dce9e mBinding = false
08-23 08:45:14.953  1921  2059 D LGBluetoothAPIService: Sending unbind request.
,08-23 08:45:14.953  6865  6865 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 08:45:14.954  1583  1583 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 08:45:14.954  6865  6865 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-23 08:45:14.954  6865  6865 D LGBluetoothEventManager: [BTUI] clear device connection state
08-23 08:45:14.956  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:14.957  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:14.958  4286  4357 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-23 08:45:14.959  4286  4286 I GKI_LINUX: GKI_exit_task 1 done
08-23 08:45:14.959  4286  4286 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-23 08:45:14.959  4286  4286 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 08:45:14.959  4286  4286 I art     : --- WEIRD: removing null entry 246
08-23 08:45:14.960  4286  4286 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-23 08:45:14.960  4286  4286 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-23 08:45:14.962  4286  4286 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-23 08:45:14.963  6865  6865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 08:45:14.965  1583  1583 D BluetoothAdapter: 974704999: getState() :  mService = null. Returning STATE_OFF
08-23 08:45:14.965  1583  1583 D BluetoothAdapter: 974704999: getState() :  mService = null. Returning STATE_OFF
08-23 08:45:14.969  4286  4286 I art     : System.exit called, status: 0
,08-23 08:45:14.970  4286  4286 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 08:45:14.972  6865  6865 D DockEventReceiver: finishStartingService: stopping service
08-23 08:45:14.997   313   313 V AudioFlinger: 4286 died, releasing its sessions
,08-23 08:45:14.997   313   313 V AudioFlinger:  pid 1832 @ 0
08-23 08:45:14.997   313   313 V AudioFlinger:  pid 3282 @ 1
08-23 08:45:14.997   313   313 V AudioFlinger:  pid 3282 @ 2
08-23 08:45:14.997  6865  6865 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-23 08:45:15.015  1030  1053 I ActivityManager: Process com.android.bluetooth (pid 4286) has died
08-23 08:45:15.016  1030  1053 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-23 08:45:15.022  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 08:45:15.026  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:15.033  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:45:15.041  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:15.045  6865  6865 D BluetoothPermissionRequest: onReceive
,08-23 08:45:15.050  6865  6865 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 08:45:15.051  6865  6865 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-23 08:45:15.053  6865  6865 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 08:45:15.053  6964  6991 W FormManager: Network not available. Please check & try again.
08-23 08:45:15.105  1030  1762 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6994 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-23 08:45:15.123  6964  6992 V FormManager: Network unavailable.
,08-23 08:45:15.127  6964  6992 V FormManager: Network unavailable.
08-23 08:45:15.130  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 08:45:15.130  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 08:45:15.130  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 08:45:15.130  6865  6865 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 08:45:15.131  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 08:45:15.144  6865  6865 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 08:45:15.144  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 08:45:15.144  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 08:45:15.144  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 08:45:15.145  6865  6865 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 08:45:15.146  6865  6865 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-23 08:45:15.150  1030  2011 I ActivityManager: Killing 6456:com.lge.email/u0a23 (adj 15): empty #17
08-23 08:45:15.189  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-23 08:45:15.189  1030  1974 W libprocessgroup: failed to open /acct/uid_10023/pid_6456/cgroup.procs: No such file or directory
08-23 08:45:15.193  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 08:45:15.195  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 08:45:15.203  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 08:45:15.224  6994  6994 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-23 08:45:15.224  6886  6886 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-23 08:45:15.224  6886  6886 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 08:45:15.224  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:15.224  6994  6994 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 08:45:15.224  6994  6994 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-23 08:45:15.227  6994  6994 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 08:45:15.227  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:45:15.228  4769  7012 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 08:45:15.237  4769  7013 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 08:45:15.237  4769  7013 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-23 08:45:15.248  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:15.248  6994  6994 D BluetoothAdapterApp: Loading JNI Library
08-23 08:45:15.249  6964  7016 W FormManager: Network not available. Please check & try again.
08-23 08:45:15.254  6964  7017 V FormManager: Network unavailable.
,08-23 08:45:15.261  6964  7017 V FormManager: Network unavailable.
,08-23 08:45:15.271  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-23 08:45:15.273  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-23 08:45:15.274  6917  6917 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-23 08:45:15.291  6994  6994 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@12cfec64 Instance Count = 1
,08-23 08:45:15.296  6994  6994 D BluetoothAdapterApp: onCreate
,08-23 08:45:15.319  6994  6994 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-23 08:45:15.319  6994  6994 D ProfileConfigQcom: Adding HeadsetService
08-23 08:45:15.320  6994  6994 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-23 08:45:15.320  6994  6994 D ProfileConfigQcom: Adding A2dpService
08-23 08:45:15.320  6994  6994 D ProfileConfigQcom: [BTUI] HidService is supported
08-23 08:45:15.320  6994  6994 D ProfileConfigQcom: Adding HidService
08-23 08:45:15.321  6994  6994 D ProfileConfigQcom: [BTUI] HealthService is supported
08-23 08:45:15.321  6994  6994 D ProfileConfigQcom: Adding HealthService
08-23 08:45:15.321  6994  6994 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-23 08:45:15.322  6994  6994 D ProfileConfigQcom: [BTUI] PanService is supported
08-23 08:45:15.322  6994  6994 D ProfileConfigQcom: Adding PanService
08-23 08:45:15.322  6994  6994 D ProfileConfigQcom: [BTUI] GattService is supported
08-23 08:45:15.323  6994  6994 D ProfileConfigQcom: Adding GattService
08-23 08:45:15.323  6994  6994 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-23 08:45:15.323  6994  6994 D ProfileConfigQcom: Adding BluetoothMapService
08-23 08:45:15.323  6994  6994 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-23 08:45:15.324  6917  6917 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:15.325  6917  6917 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:15.325  6994  6994 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-23 08:45:15.332  6865  6865 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-23 08:45:15.335  6994  6994 V LGMDMManagerInternal: Create singleton instance
08-23 08:45:15.337  6917  6917 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-23 08:45:15.343  6917  6917 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-23 08:45:15.343  6917  6917 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-23 08:45:15.343  6917  6917 V SoundPool: doLoad: loading sample sampleID=1
08-23 08:45:15.344  6917  6917 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-23 08:45:15.346  6917  7021 V SoundPool: Start decode
08-23 08:45:15.346  6917  7021 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-23 08:45:15.348   313  1364 V MediaPlayerService: decode(22, 10857164, 17813)
08-23 08:45:15.348   313  1364 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,08-23 08:45:15.348   313  1364 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-23 08:45:15.348   313  1364 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-23 08:45:15.348   313  1364 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-23 08:45:15.348   313  1364 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-23 08:45:15.348   313  1364 V MediaPlayerService: player type = 3
08-23 08:45:15.349   313  1364 V AwesomePlayer: AwesomePlayer create()
08-23 08:45:15.349   313  1364 V AwesomePlayer: reset_l() 
08-23 08:45:15.349   313  1364 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:15.350   313  1364 V AwesomePlayer: setAudioSink() 
08-23 08:45:15.350   313  1364 V AwesomePlayer: reset_l() 
08-23 08:45:15.350   313  1364 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-23 08:45:15.350   313  1364 V AudioCache: ignored
08-23 08:45:15.350   313  1364 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:15.350  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-23 08:45:15.350   313  1364 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-23 08:45:15.350   313  1364 V AwesomePlayer: setDataSource_l dataSource
08-23 08:45:15.350   313  1364 V LGParserOSAL: SniffLGParser start
08-23 08:45:15.350   313  1364 V LGParserOSAL: MainType:5, SubType=0
08-23 08:45:15.350   313  1364 V LGParserOSAL: #### check Mime : application/ogg
08-23 08:45:15.351   313  1364 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-23 08:45:15.351   313  1364 E MediaExtractor: Use LGExtractor :application/ogg 
08-23 08:45:15.351  6627  6627 D UEI.SmartControl: QS Service created
,08-23 08:45:15.359  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 08:45:15.360  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-23 08:45:15.374  6627  6627 I UEI.SmartControl: Service initServices...
08-23 08:45:15.377  6627  6627 D UEI.SmartControl: QS start get config
08-23 08:45:15.388  6917  6917 V LGMDMManager: Create singleton instance
,08-23 08:45:15.424   313  1364 V LGParserOSAL: supported mime: application/ogg
08-23 08:45:15.424   313  1364 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-23 08:45:15.424   313  1364 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-23 08:45:15.424   313  1364 V AwesomePlayer: mBitrate = -1 bits/sec
08-23 08:45:15.424   313  1364 V AwesomePlayer: AudioTrack Setting
,08-23 08:45:15.424   313  1364 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-23 08:45:15.424   313  1364 V AwesomePlayer: setAudioSource() 
,08-23 08:45:15.424   313  1364 V MediaPlayerService: prepare
,08-23 08:45:15.424   313  1364 V AwesomePlayer: prepareAsync_l() 
08-23 08:45:15.424   313  1364 V MediaPlayerService: wait for prepare
08-23 08:45:15.424   313  7022 V AwesomePlayer: onPrepareAsyncEvent() 
08-23 08:45:15.425   313  7022 V AwesomePlayer: initAudioDecoder() 
08-23 08:45:15.425   313  7022 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 08:45:15.425   313  7022 V AudioSystem: isOffloadSupported()
08-23 08:45:15.425   313  7022 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 08:45:15.425   313  7022 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 08:45:15.425   313  7022 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 08:45:15.427  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:15.427   313  7022 V AwesomePlayer: getUseOffload() = 0 
08-23 08:45:15.427   313  7022 V OMXCodec: OMXCodec::Create
08-23 08:45:15.427   313  7022 V OMXCodec: findMatchingCodecs()
08-23 08:45:15.428   313  7022 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-23 08:45:15.428   313  7022 V OMXCodec: matchingCodecs.size()=1
08-23 08:45:15.428   313  7022 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-23 08:45:15.430  6994  6994 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 08:45:15.430   313  7022 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-23 08:45:15.430   313  7022 V LGCodecAdapter: LG Codec Adapter start
08-23 08:45:15.430   313  7022 V OMXCodec: OMXCodec Createtor
08-23 08:45:15.430   313  7022 V OMXCodec: setComponentRole
08-23 08:45:15.430   313  7022 V OMXCodec: configureCodec protected=0
08-23 08:45:15.430   313  7022 V LGCodecAdapter: called getLGCodecSpecificData
08-23 08:45:15.430   313  7022 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-23 08:45:15.431   313  7022 V LGCodecOSAL: Called LGconfigureCodecMETA
08-23 08:45:15.431   313  7022 V LGCodecOSAL: Called LGconfigureCodecMSG
08-23 08:45:15.431   313  7022 V LGCodecOSAL: Not support LGCodec
08-23 08:45:15.431   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 08:45:15.431   313  7022 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-23 08:45:15.431   313  7022 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-23 08:45:15.431   313  7022 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-23 08:45:15.431   313  7022 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 08:45:15.431  6994  6994 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 08:45:15.431   313  7022 V AudioSystem: isOffloadSupported()
08-23 08:45:15.431   313  7022 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 08:45:15.431   313  7022 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 08:45:15.431   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-23 08:45:15.431   313  7022 V OMXCodec: init()
08-23 08:45:15.431   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-23 08:45:15.431   313  7022 V OMXCodec: allocateBuffers
08-23 08:45:15.431   313  7022 V OMXCodec: allocateBuffersOnPort portIndex=0
08-23 08:45:15.431  6994  6994 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 08:45:15.431   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocating ,4 buffers of size 8192 on input port
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on input port
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
08-23 08:45:15.432   313  7022 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on output port
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on output port
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on output port
08-23 08:45:15.432   313  7022 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b88d0 on output port
08-23 08:45:15.432   313  7022 V OMXCodec: init() mAsyncCompletion wait!!! 
08-23 08:45:15.432  6994  6994 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:15.433  6994  6994 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-23 08:45:15.434   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 08:45:15.434   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 08:45:15.434   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-23 08:45:15.434   313  7022 V OMXCodec: init() mAsyncCompletion wait!!! 
08-23 08:45:15.435   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-23 08:45:15.435   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-23 08:45:15.435   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-23 08:45:15.435   313  7022 V OMXCodec: init() mAsyncCompletion wait free! 
08-23 08:45:15.435   313  7022 V AwesomePlayer: finishAsyncPrepare_l() 
08-23 08:45:15.435   313  7022 V AudioCache: notify(0xb5474a80, 5, 0, 0)
08-23 08:45:15.435   313  7022 V AudioCache: ignored
08-23 08:45:15.435   313  7022 V AudioCache: notify(0xb5474a80, 1, 0, 0)
08-23 08:45:15.435   313  7022 V AudioCache: prepared
08-23 08:45:15.435   313  1364 V AudioCache: wait - success
08-23 08:45:15.435   313  1364 V MediaPlayerService: start
08-23 08:45:15.435   313  1364 V AwesomePlayer: play_l() 
08-23 08:45:15.435   313  1364 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-23 08:45:15.435   313  1364 V AwesomePlayer: createAudioPlayer_l
08-23 08:45:15.435   313  1364 V AwesomePlayer: seekAudioIfNecessary_l() 
08-23 08:45:15.435   313  1364 V AwesomePlayer: startAudioPlayer_l() 
08-23 08:45:15.435   313  1364 D AudioPlayer: start of Playback, useOffload 0
,08-23 08:45:15.435   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 08:45:15.435   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 08:45:15.437   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-23 08:45:15.437   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-23 08:45:15.437   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-23 08:45:15.437   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-23 08:45:15.437   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-23 08:45:15.437   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975424
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974515696
,08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974515776
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517456
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
,08-23 08:45:15.438   313  7024 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on output port
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on output port
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on output port
08-23 08:45:15.438   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8d30 on output port
08-23 08:45:15.439   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-23 08:45:15.439   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-23 08:45:15.440   313  1364 V AudioCache: open(48000, 2, 0x0, 1, 4)
,08-23 08:45:15.440   313  1364 V AudioCache: notify(0xb5474a80, 6, 0, 0)
08-23 08:45:15.440   313  1364 V AudioCache: ignored
08-23 08:45:15.440   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.440   313  7026 V AudioCache: memcpy(0xaf0f9000, 0xb57d5000, 4096)
08-23 08:45:15.441   313  1364 V MediaPlayerService: wait for playback complete
08-23 08:45:15.442  6934  6934 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-23 08:45:15.444   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.444   313  7026 V AudioCache: memcpy(0xaf0fa000, 0xb57d5000, 4096)
08-23 08:45:15.444   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.444   313  7026 V AudioCache: memcpy(0xaf0fb000, 0xb57d5000, 4096)
,08-23 08:45:15.444   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.444   313  7026 V AudioCache: memcpy(0xaf0fc000, 0xb57d5000, 4096)
08-23 08:45:15.446   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.446   313  7026 V AudioCache: memcpy(0xaf0fd000, 0xb57d5000, 4096)
08-23 08:45:15.446   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.446   313  7026 V AudioCache: memcpy(0xaf0fe000, 0xb57d5000, 4096)
08-23 08:45:15.446   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.446   313  7026 V AudioCache: memcpy(0xaf0ff000, 0xb57d5000, 4096)
08-23 08:45:15.446   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.446   313  7026 V AudioCache: memcpy(0xaf100000, 0xb57d5000, 4096)
,08-23 08:45:15.448   313  7026 V AudioCache: write(0xb57d5000, 4096),
08-23 08:45:15.448   313  7026 V AudioCache: memcpy(0xaf101000, 0xb57d5000, 4096)
08-23 08:45:15.448   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.448   313  7026 V AudioCache: memcpy(0xaf102000, 0xb57d5000, 4096)
08-23 08:45:15.448   313  7026 V AudioCache: write(0xb57d5000, 4096)
,08-23 08:45:15.448   313  7026 V AudioCache: memcpy(0xaf103000, 0xb57d5000, 4096)
08-23 08:45:15.448   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.448   313  7026 V AudioCache: memcpy(0xaf104000, 0xb57d5000, 4096)
08-23 08:45:15.450   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.450   313  7026 V AudioCache: memcpy(0xaf105000, 0xb57d5000, 4096)
08-23 08:45:15.450   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.450   313  7026 V AudioCache: memcpy(0xaf106000, 0xb57d5000, 4096)
08-23 08:45:15.450   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.450   313  7026 V AudioCache: memcpy(0xaf107000, 0xb57d5000, 4096)
08-23 08:45:15.450   313  7026 V AudioCache: write(0xb57d5000, 4096)
,08-23 08:45:15.450   313  7026 V AudioCache: memcpy(0xaf108000, 0xb57d5000, 4096)
08-23 08:45:15.452   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.452   313  7026 V AudioCache: memcpy(0xaf109000, 0xb57d5000, 4096)
08-23 08:45:15.452   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.452   313  7026 V AudioCache: memcpy(0xaf10a000, 0xb57d5000, 4096)
08-23 08:45:15.452   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.452   313  7026 V AudioCache: memcpy(0xaf10b000, 0xb57d5000, 4096)
08-23 08:45:15.452   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.452   313  7026 V AudioCache: memcpy(0xaf10c000, 0xb57d5000, 4096)
08-23 08:45:15.454   313  7026 V AudioCache: write(0xb57d5000, 4096)
,08-23 08:45:15.454   313  7026 V AudioCache: memcpy(0xaf10d000, 0xb57d5000, 4096)
08-23 08:45:15.454   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.454   313  7026 V AudioCache: memcpy(0xaf10e000, 0xb57d5000, 4096)
08-23 08:45:15.454   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.454   313  7026 V AudioCache: memcpy(0xaf10f000, 0xb57d5000, 4096)
08-23 08:45:15.455   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.455   313  7026 V AudioCache: memcpy(0xaf110000, 0xb57d5000, 4096)
08-23 08:45:15.455   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.455   313  7026 V AudioCache: memcpy(0xaf111000, 0xb57d5000, 4096)
08-23 08:45:15.455   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.455   313  7026 V AudioCache: memcpy(0xaf112000, 0xb57d5000, 4096)
08-23 08:45:15.456   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.456   313  7026 V AudioCache: memcpy(0xaf113000, 0xb57d5000, 4096)
08-23 08:45:15.457   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.457   313  7026 V AudioCache: memcpy(0xaf114000, 0xb57d5000, 4096)
08-23 08:45:15.458   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.458   313  7026 V AudioCache: memcpy(0xaf115000, 0xb57d5000, 4096)
08-23 08:45:15.459   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.459   313  7026 V AudioCache: memcpy(0xaf116000, 0xb57d5000, 4096)
08-23 08:45:15.459   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.459   313  7026 V AudioCache: memcpy(0xaf117000, 0xb57d5000, 4096)
08-23 08:45:15.460   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.460   313  7026 V AudioCache: memcpy(0xaf118000, 0xb57d5000, 4096)
08-23 08:45:15.460   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.460   313  7026 V AudioCache: memcpy(0xaf119000, 0xb57d5000, 4096)
08-23 08:45:15.461   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.461   313  7026 V AudioCache: memcpy(0xaf11a000, 0xb57d5000, 4096)
08-23 08:45:15.462   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.462   313  7026 V AudioCache: memcpy(0xaf11b000, 0xb57d5000, 4096)
08-23 08:45:15.462   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.462   313  7026 V AudioCache: memcpy(0xaf11c000, 0xb57d5000, 4096)
08-23 08:45:15.463   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.463   313  7026 V AudioCache: memcpy(0xaf11d000, 0xb57d5000, 4096)
08-23 08:45:15.463   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.463   313  7026 V AudioCache: memcpy(0xaf11e000, 0xb57d5000, 4096)
08-23 08:45:15.464   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.464   313  7026 V AudioCache: memcpy(0xaf11f000, 0xb57d5000, 4096)
08-23 08:45:15.464   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.464   313  7026 V AudioCache: memcpy(0xaf120000, 0xb57d5000, 4096)
08-23 08:45:15.465   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.465   313  7026 V AudioCache: memcpy(0xaf121000, 0xb57d5000, 4096)
08-23 08:45:15.465   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.465   313  7026 V AudioCache: memcpy(0xaf122000, 0xb57d5000, 4096)
08-23 08:45:15.466   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.466   313  7026 V AudioCache: memcpy(0xaf123000, 0xb57d5000, 4096)
08-23 08:45:15.466   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.466   313  7026 V AudioCache: memcpy(0xaf124000, 0xb57d5000, 4096)
08-23 08:45:15.467   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.467   313  7026 V AudioCache: memcpy(0xaf125000, 0xb57d5000, 4096)
08-23 08:45:15.468   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.468   313  7026 V AudioCache: memcpy(0xaf126000, 0xb57d5000, 4096)
08-23 08:45:15.468  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-23 08:45:15.468   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.468   313  7026 V AudioCache: memcpy(0xaf127000, 0xb57d5000, 4096)
08-23 08:45:15.469  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-23 08:45:15.471  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9886
,08-23 08:45:15.473   313  7026 V AudioCache: write(0xb57d5000, 4096)
,08-23 08:45:15.473   313  7026 V AudioCache: memcpy(0xaf128000, 0xb57d5000, 4096)
08-23 08:45:15.473   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.473   313  7026 V AudioCache: memcpy(0xaf129000, 0xb57d5000, 4096)
08-23 08:45:15.473   313  7026 V AudioCache: write(0xb57d5000, 4096)
08-23 08:45:15.473   313  7026 V AudioCache: memcpy(0xaf12a000, 0xb57d5000, 4096)
08-23 08:45:15.473   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-23 08:45:15.473   313  7026 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-23 08:45:15.473   313  7026 V AwesomePlayer: postAudioEOS() 
08-23 08:45:15.474   313  7026 V AudioCache: write(0xb57d5000, 280)
08-23 08:45:15.474   313  7026 V AudioCache: memcpy(0xaf12b000, 0xb57d5000, 280)
08-23 08:45:15.475   313  7022 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-23 08:45:15.475   313  7022 V AwesomePlayer: onStreamDone
08-23 08:45:15.475   313  7022 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
,08-23 08:45:15.475   313  7022 V AudioCache: notify(0xb5474a80, 2, 0, 0)
08-23 08:45:15.475   313  7022 V AudioCache: playback complete
,08-23 08:45:15.475   313  7022 V AwesomePlayer: pause_l() 
,08-23 08:45:15.475   313  7022 V AudioCache: notify(0xb5474a80, 7, 0, 0)
,08-23 08:45:15.475   313  1364 V AudioCache: wait - success
08-23 08:45:15.475   313  1364 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,08-23 08:45:15.475   313  7022 V AudioCache: ignored
,08-23 08:45:15.475   313  7022 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:15.475   313  7022 D AudioPlayer: Pause Playback at 1068125
08-23 08:45:15.476   313  1364 V AwesomePlayer: reset_l() 
,08-23 08:45:15.476   313  1364 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-23 08:45:15.476   313  1364 V AudioCache: ignored,
,08-23 08:45:15.476   313  1364 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:15.476   313  1364 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
,08-23 08:45:15.476   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
,08-23 08:45:15.476   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-23 08:45:15.476   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
,08-23 08:45:15.476   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
,08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
,08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
,08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
,08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 0
08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
,08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8d30 on port 1
,08-23 08:45:15.476   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 1
,08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b81f0 on port 1
,08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 1
,08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
,08-23 08:45:15.477   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-23 08:45:15.477   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
,08-23 08:45:15.477   313  7024 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-23 08:45:15.477   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,08-23 08:45:15.477   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-23 08:45:15.477   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-23 08:45:15.478   313  1364 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-23 08:45:15.478   313  1364 D AudioPlayer: AudioPlayer releasing audio source
08-23 08:45:15.478   313  1364 D AudioPlayer: AudioPlayer done releasing audio source
,08-23 08:45:15.478   313  1364 V AwesomePlayer: reset_l() 
08-23 08:45:15.478   313  1364 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:15.478   313  1364 V AwesomePlayer: ~AwesomePlayer call
08-23 08:45:15.478   313  1364 V AwesomePlayer: reset_l() 
,08-23 08:45:15.478   313  1364 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:15.479  6917  7021 V SoundPool: close(31)
08-23 08:45:15.479  6917  7021 V SoundPool: pointer = 0xa0032000, size = 205080, sampleRate = 48000, numChannels = 2
08-23 08:45:15.827  6627  6627 I UEI.SmartControl: Supports setup maps: true
,08-23 08:45:15.835  6627  6627 D UEI.SmartControl: QS start statue = true Error code = 0
,08-23 08:45:15.835  6627  6627 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-23 08:45:15.835  6627  6627 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-23 08:45:15.835  6627  6627 I UEI.SmartControl: ### init IR Blaster...
08-23 08:45:15.840  6627  6627 D serial_port: Configuring serial port
08-23 08:45:15.840  6627  6627 E UEI.SmartControl: UEIBLaster setting for 616
08-23 08:45:15.840  6627  6627 I UEI.SmartControl: Setting serial record hearder size = 2
08-23 08:45:15.841  6627  6627 I UEI.SmartControl: configuring settings for MAXQ616
,08-23 08:45:15.841  6627  6627 I UEI.SmartControl: Get version...
08-23 08:45:15.859  6627  7033 D UEI.SmartControl: serial port data available: 21
,08-23 08:45:15.885  6627  6627 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-23 08:45:15.885  6627  6627 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-23 08:45:15.886  6627  6627 I UEI.SmartControl: QS saving settings...
08-23 08:45:15.887  6627  6627 D UEI.SmartControl: IR Blaster version: 25672567
,08-23 08:45:15.904  6627  7033 D UEI.SmartControl: serial port data available: 4
,08-23 08:45:15.936  6627  7036 I UEI.SmartControl: Device manager: loading config....
,08-23 08:45:15.937  6627  7036 D UEI.SmartControl: ----------- loading internal config...
08-23 08:45:15.938  6627  6627 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-23 08:45:15.942  6627  6627 E UEI.SmartControl: Services init done
08-23 08:45:15.942  6627  6627 D UEI.SmartControl: QS Service init finished
,08-23 08:45:15.962  6627  7036 E UEI.SmartControl: Loading SETTINGS...
08-23 08:45:15.966  6627  6627 D UEI.SmartControl: QS Service version name: 2.1.91
08-23 08:45:15.966  6627  6627 D UEI.SmartControl: QS Service version code: 201091
,08-23 08:45:15.968  6627  6627 D UEI.SmartControl: Service requested: Control
08-23 08:45:15.970  6627  6627 D UEI.SmartControl: Internal service binding...
08-23 08:45:15.971  6917  6917 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-23 08:45:15.972  6627  6643 I UEI.SmartControl: ------ IControl API: 11
08-23 08:45:15.972  6627  6643 D UEI.SmartControl: File observer start...
08-23 08:45:15.973  6627  6643 E UEI.SmartControl: IR Port is disabled: false
08-23 08:45:15.973  6627  6643 D UEI.SmartControl: Starting file observer...
08-23 08:45:15.974  6627  6643 I UEI.SmartControl: Registering callback...
08-23 08:45:15.977  6627  7036 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-23 08:45:15.982  6627  6642 I UEI.SmartControl: ------ IControl API: 19
08-23 08:45:15.983  6627  6642 I UEI.SmartControl: Registering Services Ready callback...
08-23 08:45:16.002  6627  7035 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-23 08:45:16.005  6917  6933 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-23 08:45:16.005  6917  7019 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-23 08:45:16.006  6917  7019 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-23 08:45:16.006  6917  6917 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-23 08:45:16.007  6917  6917 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-23 08:45:16.007  6627  6643 I UEI.SmartControl: ------ IControl API: 8
08-23 08:45:16.008  6627  7035 D UEI.SmartControl: -----service ready thread exits
08-23 08:45:16.009  6917  6917 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-23 08:45:16.010  6917  6917 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-23 08:45:16.010  6917  6917 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-23 08:45:16.010  6917  6917 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-23 08:45:16.011  6917  6917 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-23 08:45:16.012  6917  6917 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-23 08:45:16.015  6917  6917 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-23 08:45:16.021  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-23 08:45:16.023  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-23 08:45:16.023  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 08:45:16.024  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-23 08:45:16.025  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-23 08:45:16.026  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-23 08:45:16.027  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-23 08:45:16.028  6917  6917 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471934716028]
08-23 08:45:16.033  6917  6917 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-23 08:45:16.039  1030  1956 I ActivityManager: Killing 6497:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-23 08:45:16.080  6917  7041 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-23 08:45:16.084  1030  1956 I ActivityManager: Killing 6019:com.android.gallery3d/u0a27 (adj 15): empty #18
08-23 08:45:16.116  1030  1555 W libprocessgroup: failed to open /acct/uid_10061/pid_6497/cgroup.procs: No such file or directory
,08-23 08:45:16.123  1030  1053 W libprocessgroup: failed to open /acct/uid_10027/pid_6019/cgroup.procs: No such file or directory
08-23 08:45:16.128  6917  6917 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-23 08:45:16.129  6917  6917 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 08:45:16.129  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-23 08:45:16.130  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-23 08:45:16.130  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-23 08:45:16.130  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-23 08:45:16.131  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-23 08:45:16.142  6917  6917 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-23 08:45:16.797  1030  1762 D WifiServiceImplEx: setWifiEnabled: true pid=6716, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 08:45:16.798  1030  1762 D WifiService: setWifiEnabled: true pid=6716, uid=10118
08-23 08:45:16.798  1030  1762 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 08:45:16.828  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-23 08:45:16.828  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 08:45:16.828  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-23 08:45:16.830  1030  1517 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-23 08:45:16.830  1030  1517 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-23 08:45:16.832  1030  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-23 08:45:16.833  1030  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 08:45:16.833  1030  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-23 08:45:16.833  1030  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 08:45:16.833  1030  1517 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-23 08:45:16.833  1030  1517 E WifiHW  : unknown target_country: EU , set to default
08-23 08:45:16.833  1030  1517 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-23 08:45:16.833  1030  1517 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-23 08:45:16.833  1030  1517 I WifiUtil: gEnableBmps=1
08-23 08:45:16.886  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:16.902  1030  1113 D Tethering: MasterInitialState.processMessage what=3
08-23 08:45:16.906  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:45:16.914  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:16.917  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:16.919  1030  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:16.924  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-23 08:45:16.927  6370  6884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-23 08:45:16.935  1030  1113 D Tethering: MasterInitialState.processMessage what=3
,08-23 08:45:16.941  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:16.942  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:16.955  5732  5732 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-23 08:45:16.974  5732  5732 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-23 08:45:16.991  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:17.054  1030  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:17.067   348   348 I art     : Background concurrent mark sweep GC freed 788(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 15.392ms total 48.381ms
,08-23 08:45:17.086  1030  1974 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7056 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-23 08:45:17.091  1030  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:17.091  1030  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 08:45:17.177  7056  7056 I AppUp4:AppBoxCP: onCreate
,08-23 08:45:17.179  7056  7056 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-23 08:45:17.195  7056  7056 I AppUp4:DB:  setFingerPrint start
08-23 08:45:17.195  7056  7056 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-23 08:45:17.204  7056  7056 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-23 08:45:17.204  7056  7056 I AppUp4:DB:  SDK version = 21
08-23 08:45:17.204  7056  7056 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-23 08:45:17.206  7056  7056 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-23 08:45:17.207  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 08:45:17.207  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:17.210  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 08:45:17.210  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 08:45:17.219  7056  7056 I AppUp4:CustModeStarterReceiver: onReceive
,08-23 08:45:17.265  7056  7056 D LgDataFeature: LgDataFeature() Constructor: none,
,08-23 08:45:17.266  7056  7056 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 08:45:17.275  7056  7056 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9a205ce
,08-23 08:45:17.275  7056  7056 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-23 08:45:17.275  7056  7056 D AppUp4:CustFacade: isPhone : true
08-23 08:45:17.276  7056  7056 D AppUp4:CustModeStarterReceiver: begin check event
08-23 08:45:17.276  7056  7056 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-23 08:45:17.277  7056  7056 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-23 08:45:17.277  7056  7075 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-23 08:45:17.278  7056  7075 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,08-23 08:45:17.278  7056  7075 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-23 08:45:17.284  1030  1555 I ActivityManager: Killing 6535:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-23 08:45:17.371  1030  1678 W libprocessgroup: failed to open /acct/uid_10080/pid_6535/cgroup.procs: No such file or directory
,08-23 08:45:17.376  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:17.377  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 08:45:17.384  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:17.389  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 08:45:17.398  4769  7090 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:17.398  4769  7090 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 08:45:17.399  4769  7089 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 08:45:17.502  1030  2006 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7094 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-23 08:45:17.503  1030  1113 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-23 08:45:17.507   308   888 D SoftapController: Softap fwReload - Ok
08-23 08:45:17.511  1030  1517 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (673ms)
08-23 08:45:17.513   308   888 D CommandListener: Setting iface cfg
08-23 08:45:17.513   308   888 D CommandListener: Trying to bring down wlan0
08-23 08:45:17.520   308   888 D CommandListener: Clearing all IP addresses on wlan0
08-23 08:45:17.524  1030  1517 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-23 08:45:17.521  7101  7101 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:17.521  7101  7101 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:17.530  1030  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 08:45:17.530  1030  1517 E WifiStateMachine: useWiFiOffloading() : false
08-23 08:45:17.530  1030  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 08:45:17.532  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-23 08:45:17.535  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:17.536  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-23 08:45:17.537  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:17.539  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:17.540  1030  1517 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-23 08:45:17.540  1030  1517 D WifiMonitor: connecting to supplicant
08-23 08:45:17.573  7101  7101 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-23 08:45:17.612  7101  7101 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 08:45:17.612  7101  7101 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-23 08:45:17.613  7094  7094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:45:17.613  7094  7094 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 08:45:17.615  1030  1113 D Tethering: InitialState.processMessage what=4
08-23 08:45:17.616  1030  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 08:45:17.617  7094  7094 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 08:45:17.617  7094  7094 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-23 08:45:17.670  7101  7101 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 08:45:17.715  7094  7094 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-23 08:45:17.730  7094  7094 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-23 08:45:17.766  7094  7094 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-23 08:45:17.776  7101  7101 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-23 08:45:17.788  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-23 08:45:17.788  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-23 08:45:17.789  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-23 08:45:17.789  7101  7101 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-23 08:45:17.789  7101  7101 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-23 08:45:17.790  1030  1517 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-23 08:45:17.791  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-23 08:45:17.792  1030  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-23 08:45:17.792  7094  7094 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:17.793  1030  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-23 08:45:17.793  7094  7094 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:17.793  1030  7126 D WifiMonitor: Dropping event because (p2p0) is stopped
08-23 08:45:17.793  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-23 08:45:17.793  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-23 08:45:17.793  1030  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-23 08:45:17.793  1030  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-23 08:45:17.794  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:17.795  1030  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:17.797  1030  1517 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-23 08:45:17.798  1030  1517 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-23 08:45:17.798  1030  1517 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-23 08:45:17.799  1030  1517 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-23 08:45:17.799  1030  1517 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-23 08:45:17.800  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:17.800  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:17.800  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:17.800  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:17.800  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 08:45:17.800  1030  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 08:45:17.800  1030  1517 E WifiStateMachine: useWiFiOffloading() : false
08-23 08:45:17.800  1030  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 08:45:17.801  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:17.802  1921  1921 D WfdService: Waiting for WifiP2p enabling
08-23 08:45:17.804  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-23 08:45:17.805  1030  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-23 08:45:17.806  1030  1517 D WifiNative-wlan0: doBoolean: SET update_config 1
08-23 08:45:17.807  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:17.807  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:17.807  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:17.807  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:17.807  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:17.807  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:17.807  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:17.807  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:17.807  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:,45:17.807  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:17.807  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:45:17.808  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:17.808  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:17.808  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:17.808  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:17.808  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:17.808  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:17.808  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:17.808  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:17.808  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:17.808  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:17.808  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:17.807  1030  1517 D WifiNative-wlan0: SET update_config 1: returned true
08-23 08:45:17.808  1030  1517 D WifiConfigStore: Loading config and enabling all networks 
08-23 08:45:17.808  1030  1517 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-23 08:45:17.808  1030  1517 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-23 08:45:17.812  1030  1517 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-23 08:45:17.817  1030  1517 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-23 08:45:17.817  1030  1517 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-23 08:45:17.818  1030  1517 D WifiStateMachine: enableVerboseLogging : level 2
08-23 08:45:17.818  1030  1517 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-23 08:45:17.818  1030  1517 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-23 08:45:17.818  1030  1517 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-23 08:45:17.818  1030  1517 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-23 08:45:17.818  1030  1517 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-23 08:45:17.819  1030  1517 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-23 08:45:17.819  1030  1517 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-23 08:45:17.819  1030  1517 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-23 08:45:17.819  1030  1517 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-23 08:45:17.819  1030  1517 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-23 08:45:17.819  1030  1517 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-23 08:45:17.819  1030  1517 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-23 08:45:17.819  1030  1517 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-23 08:45:17.820  1030  1517 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-23 08:45:17.821  1921  1921 D WfdsService: Supplicant Connection state is changed : true
,08-23 08:45:17.821  1921  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-23 08:45:17.821  1921  2257 D WfdsService: Set the WFDS Monitor: true
08-23 08:45:17.821  1921  2257 D WfdsMonitor: WfdsMonitorThread create
08-23 08:45:17.821  1921  2257 D WfdsMonitor: WFDS Monitor is created and started
08-23 08:45:17.821  1921  2257 D WfdsService: WiFi: Supplicant connection re-established
08-23 08:45:17.821  1030  1517 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 08:45:17.821  1030  1517 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-23 08:45:17.822  1030  1517 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-23 08:45:17.822  1030  1517 D WifiNative-HAL: Setting external_sim to 1
,08-23 08:45:17.822  1030  1517 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-23 08:45:17.822  1921  7128 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-23 08:45:17.822  1030  1517 D WifiNative-wlan0: SET external_sim 1: returned true
08-23 08:45:17.822  1030  1517 I WifiNative-HAL: startHal
08-23 08:45:17.822  1030  1517 D wifi    : setting scan oui 0xaf69b5c0
08-23 08:45:17.822  1030  1517 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 08:45:17.822  1030  1517 I WifiNative-HAL: startHal
08-23 08:45:17.822  1030  1517 D wifi    : setting scan oui 0xaf69b5c0
08-23 08:45:17.822  1921  7128 E CtrlSupplicant: Succeed to open control connection
,08-23 08:45:17.822  1030  1517 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-23 08:45:17.823  1921  7128 E CtrlSupplicant: Succeed to open monitor connection
08-23 08:45:17.823  1921  7128 D WfdsMonitor: Supplicant connection established
08-23 08:45:17.823  1921  2257 D WfdsService: Connected to the supplicant for wfds
08-23 08:45:17.823  1030  1517 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-23 08:45:17.823  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-23 08:45:17.823  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-23 08:45:17.823  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-23 08:45:17.823  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 08:45:17.824  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-23 08:45:17.824  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 08:45:17.824  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-23 08:45:17.824  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-23 08:45:17.824  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-23 08:45:17.824  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 08:45:17.824  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 08:45:17.824  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 08:45:17.824  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 08:45:17.824  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-23 08:45:17.825  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 08:45:17.825  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-23 08:45:17.825  7101  7101 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-23 08:45:17.825  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-23 08:45:17.825  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 08:45:17.825  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 08:45:17.825  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 08:45:17.826  1030  1517 E WifiNative: : [182,846,571 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-23 08:45:17.826  1030  1517 D WifiNative-wlan0: doBoolean: RECONNECT
,08-23 08:45:17.826  1030  1517 D WifiNative-wlan0: RECONNECT: returned true
08-23 08:45:17.826  1030  1517 D WifiNative-wlan0: doString: [STATUS]
08-23 08:45:17.827  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-23 08:45:17.827  1030  1517 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 08:45:17.827  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-23 08:45:17.827  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 08:45:17.827  1030  1517 D WifiNative-wlan0: SET ps 1: returned true
08-23 08:45:17.827  1030  1515 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.828   308   888 D CommandListener: Setting iface cfg
,08-23 08:45:17.828   308   888 D CommandListener: Trying to bring up p2p0
08-23 08:45:17.828  1030  1515 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 08:45:17.828  1030  1515 D LGWifiP2pService: P2pEnablingState
08-23 08:45:17.828  1030  1515 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.828  1030  1515 D LGWifiP2pService: P2p socket connection successful
08-23 08:45:17.828  1030  1515 D LGWifiP2pService: P2pEnabledState
08-23 08:45:17.829  1030  1515 D LGWifiP2pService: sending p2p connection changed broadcast
08-23 08:45:17.831  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 08:45:17.831  1030  1536 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 08:45:17.831  1030  1536 I WifiNative-HAL: startHal
08-23 08:45:17.831  1030  1536 D wifi    : getting scan capabilities on interface[1] = 0xaf69b5c0
08-23 08:45:17.831  1030  1536 D wifi    : failed to get capabilities : -3
08-23 08:45:17.831  1030  1536 E WifiScanningService: could not get scan capabilities
08-23 08:45:17.832  1030  1030 D RttService: SCAN_AVAILABLE : 3
08-23 08:45:17.832  1030  1537 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.832  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
,08-23 08:45:17.833  1921  1921 D WfdsService: WifiP2pState is changed : true
08-23 08:45:17.833  1921  1921 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-23 08:45:17.833  1921  1921 D WfdsService: isConnected: false
08-23 08:45:17.833  1921  2257 D WfdsService: Receive the WFDS_ENABLE Method
08-23 08:45:17.834  1921  2257 D WfdsService: Set the WFDS Monitor: true
08-23 08:45:17.834  1921  2257 D WfdsService: Connected to the supplicant for wfds
08-23 08:45:17.834  1921  2257 D WfdsJNI : doCommand: WFDS_SET TRUE
08-23 08:45:17.834  7101  7101 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-23 08:45:17.834  1030  1515 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-23 08:45:17.834  1921  2257 D WfdsService: selectPreferredScanChannel [36]
08-23 08:45:17.834  1921  2257 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-23 08:45:17.835  1030  1515 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-23 08:45:17.836  1030  1515 D WifiNative-p2p0: doBoolean: SET device_name G3
08-23 08:45:17.836  1030  1515 D WifiNative-p2p0: SET device_name G3: returned true
08-23 08:45:17.836  1030  1515 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-23 08:45:17.836  1030  1515 D LGWifiP2pService: before postfix = G3
08-23 08:45:17.836  1030  1515 D WifiServerServiceExt: postfix byte check : 2
08-23 08:45:17.836  1030  1515 D LGWifiP2pService: after postfix = G3
08-23 08:45:17.836  1030  1515 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-23 08:45:17.837  1030  1515 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-23 08:45:17.837  1030  1515 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-23 08:45:17.838  1030  1515 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-23 08:45:17.839  1030  1515 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-23 08:45:17.839  1030  1517 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-23 08:45:17.839  1030  1515 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-23 08:45:17.839  1030  1515 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-23 08:45:17.839  1030  1517 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-23 08:45:17.840  1030  1515 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-23 08:45:17.840  1030  1515 D WifiNative-HAL: p2pGetDeviceAddress
08-23 08:45:17.840  1030  1517 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-23 08:45:17.840  1030  1515 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-23 08:45:17.840  1030  1517 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-23 08:45:17.840  1030  1515 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-23 08:45:17.840  1030  1515 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-23 08:45:17.840  1030  1517 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-23 08:45:17.841  1030  1517 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-23 08:45:17.841  1030  1515 D WifiNative-p2p0: P2P_FLUSH: returned true
08-23 08:45:17.841  1030  1515 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-23 08:45:17.841  1030  1517 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-23 08:45:17.841  1030  1515 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-23 08:45:17.841  1030  1517 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-23 08:45:17.841  1030  1515 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-23 08:45:17.841  7101  7101 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-23 08:45:17.842  1921  1921 I WfdStateTracker: handleP2pThisDeviceChanged
08-23 08:45:17.842  1921  1921 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-23 08:45:17.842  1921  1921 D WfdsService: Update P2p Interface State: 3
08-23 08:45:17.842  1030  1517 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-23 08:45:17.842  1030  1515 D ,WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-23 08:45:17.842  1030  1517 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-23 08:45:17.842  1030  1515 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-23 08:45:17.843  1030  1517 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-23 08:45:17.843  1030  1517 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-23 08:45:17.854  7101  7101 E wpa_supplicant: disconnect_rssi_lvl: -100
08-23 08:45:17.854  1030  1517 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz,
08-23 08:45:17.855  1030  1517 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-23 08:45:17.855  1030  1515 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-23 08:45:17.855  1030  1515 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-23 08:45:17.855  1030  1517 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-23 08:45:17.855  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-23 08:45:17.855  1030  1515 D LGWifiP2pService: InactiveState
,08-23 08:45:17.855  1030  1515 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.855  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.855  1030  1515 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-23 08:45:17.856  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 08:45:17.857  7101  7101 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:17.857  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 08:45:17.857  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:17.857  1030  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:17.857  1030  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:17.857  7101  7101 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 08:45:17.858  7101  7101 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.858  1921  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:17.858  1030  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:17.858  1030  7126 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.858  1030  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.858  1030  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.858  1030  1517 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-23 08:45:17.858  7101  7101 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.858  1030  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:17.858  1030  7126 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.858  1030  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.858  1030  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.859  1921  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:17.859  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 08:45:17.860  7101  7101 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:17.860  1030  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 08:45:17.860  1030  7126 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:17.860  1030  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:17.860  1030  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:17.860  1030  1517 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-23 08:45:17.860  7101  7101 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 08:45:17.860  7101  7101 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.860  1030  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:17.860  1030  1515 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-23 08:45:17.860  1030  7126 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.861  1030  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGD,OM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.861  1030  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.861  1030  1515 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.861  1030  1517 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-23 08:45:17.861  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.861  1030  1515 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.861  1030  1515 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.861  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.861  7101  7101 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.861  1030  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:17.861  1030  1515 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.861  1030  7126 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.861  1030  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.861  1030  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:17.861  1921  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 08:45:17.861  1921  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:17.861  1921  7128 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:17.862  1030  1517 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-23 08:45:17.862  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-23 08:45:17.862  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-23 08:45:17.862  7101  7101 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 08:45:17.863  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-23 08:45:17.863  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 08:45:17.863  1030  7126 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 08:45:17.863  1030  7126 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 08:45:17.863  1030  1517 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-23 08:45:17.863  1030  1517 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-23 08:45:17.863  1030  1517 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-23 08:45:17.863  1030  1517 D WifiNative-wlan0: doBoolean: SCAN
08-23 08:45:17.863  1030  1515 D LGWifiP2pService: InactiveState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.863  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-23 08:45:17.863  1030  1517 D WifiNative-wlan0: SCAN: returned false
08-23 08:45:17.864  1030  1515 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.864  1921  2257 W WfdsService: DefaultState - msg [9441285] is not handled
08-23 08:45:17.864  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.864  1030  1515 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.864  1030  1515 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.864  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.864  1030  1515 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:17.864  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=182884  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 08:45:17.864  1030  1030 E WifiServerServiceExt: No p2p device connected
08-23 08:45:17.865  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=182885  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 08:45:17.866  1030  1517 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:17.866  1030  1517 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:17.867  1030  1517 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:17.867  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 08:45:17.867  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:17.867  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:17.867  1030  1517 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:17.867  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:17.867  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 08:45:17.867  1030  1517 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:17.868  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:17.869  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:17.869  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-23 08:45:17.891  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69),
,08-23 08:45:17.912  6964  7132 W FormManager: Network not available. Please check & try again.
08-23 08:45:17.912  3282  3282 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 08:45:17.912  3282  3282 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:17.913  6964  7133 V FormManager: Network unavailable.
08-23 08:45:17.913  3282  3282 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-23 08:45:17.921  7094  7094 I HubEmail: JNI_OnLoad()
08-23 08:45:17.921  7094  7094 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 08:45:17.921  7094  7094 I HubEmail: registerNatives()
08-23 08:45:17.921  7094  7094 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 08:45:17.921  7094  7094 I HubEmail: registerNativeMethods()
08-23 08:45:17.921  7094  7094 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-23 08:45:17.922  7094  7094 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-23 08:45:17.945  1030  1938 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7136 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-23 08:45:17.949  6964  7133 V FormManager: Network unavailable.
08-23 08:45:17.955  7094  7135 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:17.956  1030  1901 I ActivityManager: Killing 6589:com.lge.eula/1000 (adj 15): empty #17
08-23 08:45:17.999  1030  2006 W libprocessgroup: failed to open /acct/uid_1000/pid_6589/cgroup.procs: No such file or directory
,08-23 08:45:18.083  7136  7136 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:18.084  7136  7136 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:18.087  7136  7136 D PhoneMonitor: Register our PhoneStateListener
,08-23 08:45:18.113  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-23 08:45:18.115  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 08:45:18.131  7136  7136 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-23 08:45:18.133  7136  7136 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-23 08:45:18.136  7136  7136 D TelephonyAutoProfiling: [parse] Load xml
,08-23 08:45:18.139  7136  7136 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
,08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
,08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
,08-23 08:45:18.139  7136  7136 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-23 08:45:18.139  7136  7136 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-23 08:45:18.146  7136  7136 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-23 08:45:18.168  1030  2011 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7155 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:45:18.169  1030  2011 I ActivityManager: Killing 6560:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-23 08:45:18.190   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 380us total 18.205ms
,08-23 08:45:18.206   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 293us total 14.741ms
,08-23 08:45:18.229   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 623us total 20.588ms
,08-23 08:45:18.246  1030  1357 V AlarmManager: RTC_WAKEUP set : Alarm{203f1619 type 0 when 1471934718029 android} when 1471934718029
,08-23 08:45:18.250  1030  1052 W libprocessgroup: failed to open /acct/uid_10097/pid_6560/cgroup.procs: No such file or directory
08-23 08:45:18.254  1030  1357 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23ee36de type 2 when 183176 com.google.android.gms} when 183176
08-23 08:45:18.423  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-23 08:45:18.423  1030  7126 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-23 08:45:18.424  7101  7101 E wpa_supplicant: USIM:  scard_init function
08-23 08:45:18.424  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-23 08:45:18.424  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-23 08:45:18.424  1030  7126 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-23 08:45:18.425  7101  7101 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-23 08:45:18.426  1030  1517 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-23 08:45:18.426  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-23 08:45:18.426  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-23 08:45:18.428  1030  1517 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-23 08:45:18.429  1030  1517 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-23 08:45:18.430  1030  1517 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-23 08:45:18.430  1030  1517 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-23 08:45:18.458  1030  2011 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7173 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-23 08:45:18.459  1030  2011 I ActivityManager: Killing 5573:com.lge.bnr/1000 (adj 15): empty #17
,08-23 08:45:18.498  1030  1892 W libprocessgroup: failed to open /acct/uid_1000/pid_5573/cgroup.procs: No such file or directory
08-23 08:45:18.499  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=183519  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-23 08:45:18.509  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.509  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:18.511  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.512  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.512  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.512  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 08:45:18.514  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=183534  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-23 08:45:18.520  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.521  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.521  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-23 08:45:18.521  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:18.521  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-23 08:45:18.531  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.531  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-23 08:45:18.533  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.542  7101  7101 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-23 08:45:18.543  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-23 08:45:18.543  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-23 08:45:18.544  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-23 08:45:18.544  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-23 08:45:18.544  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 08:45:18.544  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-23 08:45:18.548  1030  1113 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 08:45:18.548  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=183569  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 08:45:18.549  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=183569  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 08:45:18.549  1030  1517 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183570
08-23 08:45:18.550  1030  1517 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183570
08-23 08:45:18.550  1030  1517 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183571
08-23 08:45:18.551  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183571
08-23 08:45:18.551  1030  1517 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=183572
08-23 08:45:18.552  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=183572  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 08:45:18.553  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 08:45:18.553  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:18.554  7101  7101 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 08:45:18.554  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-23 08:45:18.554  7101  7101 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 08:45:18.554  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 08:45:18.554  1030  7126 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 08:45:18.554  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-23 08:45:18.554  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 08:45:18.554  1030  7126 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 08:45:18.554  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 08:45:18.554  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:18.557  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.557  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.557  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-23 08:45:18.557  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.557  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:18.558  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 08:45:18.562  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.562  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.562  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-23 08:45:18.563  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=183584  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 08:45:18.564  1030  1517 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:18.564  1030  1517 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:18.565  1030  1517 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:18.565  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:18.566  1030  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:18.567  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:18.567  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-23 08:45:18.567  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=183588  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 08:45:18.568  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=183588  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 08:45:18.569  1030  1517 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=183589
08-23 08:45:18.569  1030  1517 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=183590
08-23 08:45:18.569  1030  1517 D WifiNative-wlan0: doString: [STATUS]
08-23 08:45:18.570  1030  1517 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 08:45:18.570  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 08:45:18.570  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:18.572  1030  1517 I WifiServiceExtension: setVHTCapabilityType  : false
,08-23 08:45:18.577  1030  1517 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-23 08:45:18.577  1030  1517 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-23 08:45:18.580  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.580  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.580  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 08:45:18.580  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-23 08:45:18.580  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:18.581  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.583  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.583  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.583  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.583  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:18.583  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 08:45:18.584  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.588  1030  1517 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-23 08:45:18.588  1030  1523 D ConnectivityService: Got NetworkAgent Messenger
08-23 08:45:18.588  1030  1523 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-23 08:45:18.588  1030  1523 D ConnectivityService: NetworkAgent connected
08-23 08:45:18.588  1030  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 08:45:18.588  1030  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 08:45:18.589  1030  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 08:45:18.589  1030  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 08:45:18.593  1030  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 08:45:18.593  1030  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 08:45:18.593  1030  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 08:45:18.594  1030  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 08:45:18.594  1030  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 08:45:18.597  1030  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-23 08:45:18.598   308   888 D CommandListener: Setting iface cfg
,08-23 08:45:18.602  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.602  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:18.603  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.630  1030  1974 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7192 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:45:18.631  1030  1974 I ActivityManager: Killing 2110:com.lge.music/u0a34 (adj 15): empty #17
,08-23 08:45:18.652   313   313 V AudioFlinger: 2110 died, releasing its sessions
08-23 08:45:18.652   313   313 V AudioFlinger:  pid 1832 @ 0
08-23 08:45:18.652   313   313 V AudioFlinger:  pid 3282 @ 1
08-23 08:45:18.652   313   313 V AudioFlinger:  pid 3282 @ 2
,08-23 08:45:18.667  1030  1678 W libprocessgroup: failed to open /acct/uid_10034/pid_2110/cgroup.procs: No such file or directory
,08-23 08:45:18.676  1030  1517 E WifiStateMachine: Start Dhcp Watchdog 2
08-23 08:45:18.677  1030  7191 D DhcpStateMachine: StoppedState
08-23 08:45:18.677  1030  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=183698  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:18.677  1030  7191 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.677  1030  7191 D DhcpStateMachine: WaitBeforeStartState
08-23 08:45:18.678  1030  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=183698  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:18.678  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=183699  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-23 08:45:18.679  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:18.679  1030  1030 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-23 08:45:18.680  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:18.680  1030  1030 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-23 08:45:18.681  1030  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183701  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:18.682  1030  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183702  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:18.682  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=183703  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:18.691  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:137593] from screen [on:0 period:-1239063837] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-23 08:45:18.692  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1239063836] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-23 08:45:18.692  1030  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-23 08:45:18.698  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.699  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.699  1030  1523 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-23 08:45:18.700  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.701  1030  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.701  1030  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.702  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.703  1030  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.703  1030  1523 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-23 08:45:18.704  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=155,0,0
08-23 08:45:18.704  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=155,0,0
08-23 08:45:18.704  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-23 08:45:18.705  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-23 08:45:18.706  1030  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-23 08:45:18.706  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 0
08-23 08:45:18.706  1030  1517 D WifiNative-wlan0: SET ps 0: returned true
08-23 08:45:18.707  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-23 08:45:18.707  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-23 08:45:18.707  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-23 08:45:18.707  1030  1517 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-23 08:45:18.707  1030  1517 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 08:45:18.707  1030  1515 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2495cd43 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.707  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2495cd43 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.708  1030  1517 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 08:45:18.708  1030  7191 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.708  1030  7191 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-23 08:45:18.709   308   888 D CommandListener: Setting iface cfg
08-23 08:45:18.709   308   888 D CommandListener: Trying to bring up wlan0
,08-23 08:45:18.711  1030  1517 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-23 08:45:18.713  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:18.714  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 08:45:18.716  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.716  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.716  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:18.716  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 08:45:18.717  1030  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.717  1030  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.717  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.718  1030  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:18.718  1030  1523 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-23 08:45:18.719  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-23 08:45:18.719  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-23 08:45:18.719  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 08:45:18.719  1030  1515 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.719  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.720  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 08:45:18.720  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 08:45:18.720  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-23 08:45:18.721  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-23 08:45:18.721  1030  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-23 08:45:18.721  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 1
,08-23 08:45:18.739  1030  1517 D WifiNative-wlan0: SET ps 1: returned true
,08-23 08:45:18.740  1030  1523 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-23 08:45:18.742  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 08:45:18.743  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 08:45:18.743  1030  1517 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-23 08:45:18.744  1030  1523 D ConnectivityService: ignoring duplicate network state non-change
08-23 08:45:18.749  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.749  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:18.750  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.750  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.750  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 08:45:18.751  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.756  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.756  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.756  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 08:45:18.756  1030  1523 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-23 08:45:18.757  1030  1523 D ConnectivityService: Adding iface wlan0 to network 101
,08-23 08:45:18.761  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-23 08:45:18.761  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.761  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.761  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 08:45:18.764  1921  1921 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-23 08:45:18.765  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-23 08:45:18.772  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.772  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:18.772  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 08:45:18.773  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.773  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:18.774  1030  1517 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-23 08:45:18.776  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.778  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.778  1583  1583 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 08:45:18.779  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.781  1030  1523 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 08:45:18.781  1030  1523 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-23 08:45:18.782  1030  1523 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-23 08:45:18.783   308   888 E Netd    : netlink response contains error (File exists)
08-23 08:45:18.783  1030  1523 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-23 08:45:18.783  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:18.783  1583  1583 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 08:45:18.783  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.784  1030  1523 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-23 08:45:18.784  1030  1523 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-23 08:45:18.784  1030  1523 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-23 08:45:18.785  1030  1523 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-23 08:45:18.785  1030  1523 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-23 08:45:18.785  1030  1523 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-23 08:45:18.786  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.786  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-23 08:45:18.786  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.786  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-23 08:45:18.788  1030  1523 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-23 08:45:18.788  1030  1523 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:18.788  1030  1523 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:18.788  1030  1523 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 08:45:18.788  1030  1523 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.788   308  7212 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-23 08:45:18.788  1030  1523 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-23 08:45:18.788  1030  1523 D ConnectivityService: currentScore = 0, newScore = 20
08-23 08:45:18.788  1030  1523 D ConnectivityService:    accepting network in place of null
08-23 08:45:18.789  1030  1523 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.789  1030  1517 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.789  1030  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:18.790  1832  1832 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.791  1832  1832 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 08:45:18.791  1030  1523 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-23 08:45:18.791  1030  1523 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-23 08:45:18.791  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 08:45:18.792  1030  1523 D ConnectivityService: sendStickyBroadcastDelayed:, delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:18.792  1030  1523 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-23 08:45:18.792  1030  1523 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-23 08:45:18.794  1030  1523 D ConnectivityService: validation of new default Network = false
08-23 08:45:18.794  1030  1523 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-23 08:45:18.794  1030  1523 D DSQN    : enableDataServiceNotify 
08-23 08:45:18.794  1030  1523 D DSQN    : start dsqn bin
08-23 08:45:18.811  7213  7213 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:18.822  1030  1523 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-23 08:45:18.822  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.811  7213  7213 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:18.822  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:18.823  1030  1105 W ProcessCpuTracker: Skipping unknown process pid 7210
08-23 08:45:18.823  1030  1523 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-23 08:45:18.826  1583  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 08:45:18.833  1030  1030 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-23 08:45:18.833  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 08:45:18.834  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 08:45:18.834  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 08:45:18.837  7213  7213 E DSQN    : DSQN ssw
08-23 08:45:18.838  1030  1514 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-23 08:45:18.843  1030  1938 I art     : Explicit concurrent mark sweep GC freed 97106(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.786ms total 160.894ms
,08-23 08:45:18.844   308  7212 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-23 08:45:18.861  1583  1583 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-23 08:45:18.861  7192  7192 I art     : Almond Protected OAT
08-23 08:45:18.861  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.862  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:18.864  1796  7217 I CheckinService: active receiver: enabled
08-23 08:45:18.874  1796  7217 I CheckinService: Preparing to send checkin request
,08-23 08:45:18.874  1796  7217 I EventLogService: Accumulating logs since 1471934577808
08-23 08:45:18.877   308  7212 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-23 08:45:18.885  1030  1515 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.885  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.885  1030  1515 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:18.891  7192  7192 D WeatherApplication: removeAccount
08-23 08:45:18.891  7192  7192 D WeatherApplication: Account.length = 0
,08-23 08:45:18.892  7192  7192 E WeatherApplication: OPERATOR:OPEN
08-23 08:45:18.895  7192  7192 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:18
08-23 08:45:18.897  7192  7192 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 08:45:18.898  7192  7192 D Weather.Utils: 2 : All the weather widget is gone.
08-23 08:45:18.899  7192  7192 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 08:45:18.900   308   887 D LGDataListener: argv[0]=dsqncommand
08-23 08:45:18.900   308   887 D LGDataListener: argv[1]=wlan0
08-23 08:45:18.900   308   887 D LGDataListener: argv[2]=1
08-23 08:45:18.900   308   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-23 08:45:18.900  1030  1111 D DSQN    : DSQM DsqnNotification wlan0  1
08-23 08:45:18.900  1030  1111 D DSQN    : start to monitor internet connection
08-23 08:45:18.902  7192  7192 D WeatherAncestor: connectivity changed - connection : true
08-23 08:45:18.902  7192  7192 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-23 08:45:18.909  7192  7192 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 08:45:18.909  1030  7191 D DhcpStateMachine: DHCPV4 request on wlan0
08-23 08:45:18.910  1030  1517 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 08:45:18.910  1030  7191 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-23 08:45:18.910  1030  7191 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-23 08:45:18.910  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 08:45:18.910  1030  1517 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 08:45:18.910  1030  1517 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 08:45:18.911  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 08:45:18.901  7222  7222 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:18.901  7222  7222 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:18.911  1030  1517 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-23 08:45:18.911  7192  7192 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 08:45:18.911  7192  7192 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-23 08:45:18.914  1796  7217 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-23 08:45:18.916  7222  7222 I dhcpcd  : version 5.5.6 starting
08-23 08:45:18.917  7222  7222 E dhcpcd  : get_duid: m
08-23 08:45:18.917  7222  7222 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-23 08:45:18.917  7222  7222 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-23 08:45:18.924  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 06:45:18 GMT], X-Android-Received-Millis=[1471934718924], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471934718899]}
08-23 08:45:18.924  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-23 08:45:18.924  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-23 08:45:18.924  1030  1523 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-23 08:45:18.924  1030  1523 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-23 08:45:18.924  1030  1523 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:18.925  1030  1523 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:18.925  1030  1523 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 08:45:18.925  1030  1523 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-23 08:45:18.925  1030  1523 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-23 08:45:18.925  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.925  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:18.925  1030  1523 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:18.926  1030  1523 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.926  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-23 08:45:18.927  1030  1517 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.927  1030  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:18.927  1583  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 08:45:18.927  1832  1832 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:18.927  1832  1832 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-23 08:45:18.952  7192  7192 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 08:45:18.952  7192  7192 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:18
,08-23 08:45:18.964  7222  7222 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 08:45:18.964  7222  7222 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 08:45:18.964  7222  7222 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 08:45:18.964  7222  7222 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-23 08:45:18.964  7222  7222 D dhcpcd  : wlan0: sending REQUEST (xid 0x496290a1), next in 3.59 seconds
08-23 08:45:18.984  1030  2011 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7229 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 08:45:18.985  1030  2011 I ActivityManager: Killing 6038:com.android.vending/u0a44 (adj 15): empty #17
08-23 08:45:18.985  7222  7222 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-23 08:45:19.015  7222  7222 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-23 08:45:19.015  7222  7222 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-23 08:45:19.015  7222  7222 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-23 08:45:19.016  7222  7222 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-23 08:45:19.016  7222  7222 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 08:45:19.016  7222  7222 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 08:45:19.016  7222  7222 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 08:45:19.016  7222  7222 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-23 08:45:19.029  1030  1901 W libprocessgroup: failed to open /acct/uid_10044/pid_6038/cgroup.procs: No such file or directory
,08-23 08:45:19.034  1583  1583 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 08:45:19.034  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:19.035  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:19.104  1030  1052 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7253 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-23 08:45:19.137   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-23 08:45:19.137   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-23 08:45:19.137   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 08:45:19.141  7229  7266 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-23 08:45:19.143   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 08:45:19.143   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-23 08:45:19.143   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 08:45:19.144  7229  7266 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-23 08:45:19.157   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 08:45:19.157   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-23 08:45:19.157   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 08:45:19.160  7229  7280 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-23 08:45:19.165   278   426 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-23 08:45:19.165   278   426 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-23 08:45:19.166   278   426 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 08:45:19.167  7229  7280 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-23 08:45:19.182  7253  7253 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 08:45:19.182  7253  7253 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 08:45:19.211  7253  7253 I MultiDex: VM with version 2.1.0 has multidex support
08-23 08:45:19.212  7253  7253 I MultiDex: install
08-23 08:45:19.212  7253  7253 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 08:45:19.226  7253  7253 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-23 08:45:19.311  1030  7191 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-23 08:45:19.312  1030  7191 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-23 08:45:19.312  1030  7191 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 08:45:19.312  1030  7191 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-23 08:45:19.313  1030  7191 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-23 08:45:19.313  1030  7191 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 08:45:19.313  1030  7191 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-23 08:45:19.313  1030  7191 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-23 08:45:19.313  1030  7191 D DhcpStateMachine: RunningState
,08-23 08:45:19.371  7229  7229 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 08:45:19.387  7229  7229 I LibraryLoader: Loading: webviewchromium
08-23 08:45:19.391  7229  7229 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4421-4425)
08-23 08:45:19.391  7229  7229 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 08:45:19.401  7229  7229 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c4db571}
08-23 08:45:19.406  7229  7229 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 08:45:19.407  7229  7229 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 08:45:19.431  7229  7229 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 08:45:19.433  7229  7229 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 08:45:19.447  7229  7229 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-23 08:45:19.448  7229  7229 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-23 08:45:19.448  7229  7229 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-23 08:45:19.449   313  1363 V AudioPolicyService: registerClient() client 0xb14b7e40, uid 10093
08-23 08:45:19.450  7229  7311 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-23 08:45:19.464  7229  7229 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 08:45:19.464  7229  7229 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 08:45:19.464  7229  7229 I Adreno-EGL: Build Date: 12/12/14 금
08-23 08:45:19.464  7229  7229 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 08:45:19.464  7229  7229 I Adreno-EGL: Remote Branch: 
08-23 08:45:19.464  7229  7229 I Adreno-EGL: Local Patches: 
08-23 08:45:19.464  7229  7229 I Adreno-EGL: Reconstruct Branch: 
,08-23 08:45:19.553  7229  7229 I NSApplication: Starting up...
,08-23 08:45:19.560  7322  7322 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-23 08:45:19.626  1030  1974 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7332 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-23 08:45:19.627  1030  1974 I ActivityManager: Killing 6779:com.lge.clock/u0a10 (adj 15): empty #17
,08-23 08:45:19.659  7322  7322 I dex2oat : dex2oat took 99.227ms (threads: 4)
,08-23 08:45:19.675  7253  7275 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 08:45:19.675  7253  7275 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 08:45:19.675  7253  7275 I Adreno-EGL: Build Date: 12/12/14 금
08-23 08:45:19.675  7253  7275 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 08:45:19.675  7253  7275 I Adreno-EGL: Remote Branch: 
08-23 08:45:19.675  7253  7275 I Adreno-EGL: Local Patches: 
08-23 08:45:19.675  7253  7275 I Adreno-EGL: Reconstruct Branch: 
,08-23 08:45:19.688  1030  1901 W libprocessgroup: failed to open /acct/uid_10010/pid_6779/cgroup.procs: No such file or directory
08-23 08:45:19.719  7332  7332 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 08:45:19.807  7253  7275 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 08:45:19.807  7253  7275 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 08:45:19.807  7253  7275 I Adreno-EGL: Build Date: 12/12/14 금
08-23 08:45:19.807  7253  7275 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 08:45:19.807  7253  7275 I Adreno-EGL: Remote Branch: 
08-23 08:45:19.807  7253  7275 I Adreno-EGL: Local Patches: 
08-23 08:45:19.807  7253  7275 I Adreno-EGL: Reconstruct Branch: 
,08-23 08:45:19.824  1030  1523 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-23 08:45:19.832  1030  1974 D WifiServiceImplEx: setWifiEnabled: false pid=6716, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 08:45:19.832  1030  1974 D WifiService: setWifiEnabled: false pid=6716, uid=10118
08-23 08:45:19.832  1030  1974 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 08:45:19.850  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 08:45:19.850  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 08:45:19.850  1030  1030 D Ulp_jni : JNI:system_update. Event-4
,08-23 08:45:19.853  1030  1517 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:19.853  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:19.853  1030  1517 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:19.854  1030  1517 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:19.854  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-23 08:45:19.854  1030  1517 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 08:45:19.854  1030  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 08:45:19.855  1030  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 08:45:19.855  1030  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 08:45:19.855  1030  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 08:45:19.871  1030  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 08:45:19.871  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 08:45:19.871  1030  1515 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.872  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.872  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-23 08:45:19.880  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 08:45:19.880  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 08:45:19.880  1030  1517 D WifiNative-wlan0: SET ps 1: returned true
08-23 08:45:19.881  1030  7191 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.886   308   888 D CommandListener: Clearing all IP addresses on wlan0
,08-23 08:45:19.890  1030  1523 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 08:45:19.890  1030  1523 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-23 08:45:19.896  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-23 08:45:19.896  1921  1921 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-23 08:45:19.897  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:19.897  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:19.897  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:19.897  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:19.897  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 08:45:19.898  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:19.900  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-23 08:45:19.902  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:19.902  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:19.902  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 08:45:19.903  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 1
08-23 08:45:19.903  1030  1536 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.904  1030  1030 D RttService: SCAN_AVAILABLE : 1
08-23 08:45:19.904  1030  1537 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.904  1030  1515 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.904  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.904  1030  1515 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@864871c
08-23 08:45:19.905  1030  1515 D LGWifiP2pService: P2pDisablingState
08-23 08:45:19.905  1030  1515 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.905  1030  1515 D LGWifiP2pService: p2p socket connection lost
08-23 08:45:19.905  1030  1515 D LGWifiP2pService: P2pDisabledState
,08-23 08:45:19.908  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 08:45:19.908  1921  1921 D WfdsService: WifiP2pState is changed : false
08-23 08:45:19.908  1921  2257 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-23 08:45:19.908  1921  2257 D WfdsService: Set the WFDS Monitor: false
08-23 08:45:19.909  1921  2257 D WfdsMonitor: WFDS Monitor is stopped
08-23 08:45:19.909  1921  2257 D WfdsService: STATE : WfdsDisabledState - enter
08-23 08:45:19.909  1921  7128 D CtrlSupplicant: Received on exit socket, terminate
08-23 08:45:19.909  1921  7128 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-23 08:45:19.909  1921  7128 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-23 08:45:19.909  1921  7128 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-23 08:45:19.910  1921  2259 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-23 08:45:19.910  1921  2257 W WfdsService: DefaultState - msg [9445378] is not handled
08-23 08:45:19.910  1030  1517 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 08:45:19.911  1030  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-23 08:45:19.911  1030  1515 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.911  1030  1515 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.911  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 08:45:19.912  7101  7101 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 08:45:19.914  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-23 08:45:19.914  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 08:45:19.914  1030  1517 D WifiNative-wlan0: SET ps 1: returned true
08-23 08:45:19.936  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:19.936  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-23 08:45:19.937  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:19.959   308   888 D CommandListener: Clearing all IP addresses on wlan0
08-23 08:45:19.959  1030  1523 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-23 08:45:19.959  1030  1523 D DSQN    : disableDataServiceNotify
08-23 08:45:19.959  1030  1523 D DSQN    : stop dsqn bin
,08-23 08:45:19.960  1030  1517 D WifiNative-p2p0: doBoolean: TERMINATE
08-23 08:45:19.961  1030  1517 D WifiNative-p2p0: TERMINATE: returned true
08-23 08:45:19.961  1030  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 08:45:19.961  1030  1517 E WifiStateMachine: useWiFiOffloading() : false
08-23 08:45:19.961  1030  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 08:45:19.961  1030  1030 D WifiHS20: hidePasspointNotification off =false
08-23 08:45:19.963  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:19.963  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:19.963  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 08:45:19.964  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-23 08:45:19.964  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-23 08:45:19.964  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:19.965  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:19.967  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-23 08:45:19.967  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:19.968  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:19.968  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:19.968  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:19.968  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:19.968  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:19.968  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:19.968  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:19.968  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:19.968  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:19.968  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:19.968  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:19.968  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:19.968  1030  1030 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-23 08:45:19.969  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:19.969  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:19.969  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:19.969  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:19.969  6716  6716 V io.jxcore.node.C,onnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:19.969  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:19.969  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:19.969  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:19.969  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:19.969  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:19.969  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:19.974  1030  1523 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-23 08:45:19.974  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:19.974  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:19.975  1030  1523 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:19.975  1030  1523 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-23 08:45:19.975  1583  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-23 08:45:19.975  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.975  1030  1523 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-23 08:45:19.975  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:19.975  1030  7190 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-23 08:45:19.975  1030  1523 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-23 08:45:19.975  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 08:45:19.976  1030  1523 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:19.976  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-23 08:45:19.978  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 08:45:19.978  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 08:45:19.978  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 08:45:19.978  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 08:45:19.978  1030  1514 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 08:45:19.981  1030  1523 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:19.982  1030  1523 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:19.982  1030  1523 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:19.982  1030  1523 D NetworkManagementService: Removing idletimer
08-23 08:45:19.982  1030  1523 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:19.982  1030  1523 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 08:45:19.982  1030  1517 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:19.982  1030  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:19.983  1832  1832 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:19.983  1832  1832 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 08:45:19.984  1030  1514 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-23 08:45:19.984  1030  1030 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-23 08:45:19.985  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 08:45:19.985  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 08:45:19.985  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-23 08:45:20.003  1583  1583 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 08:45:20.004  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:20.005  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 08:45:20.028  1583  1583 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-23 08:45:20.029  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:20.029  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:20.048  7101  7101 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-23 08:45:20.048  7101  7101 I wpa_supplicant: monitor socket send errors count : 1
08-23 08:45:20.048  7101  7101 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1921-4\x00 that cannot receive messages
,08-23 08:45:20.051  1030  7126 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-23 08:45:20.051  1030  7126 D WifiMonitor: Dropping event because (p2p0) is stopped
08-23 08:45:20.053  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-23 08:45:20.055  6370  6884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-23 08:45:20.065  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:20.074  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 08:45:20.074  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:20.074  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 08:45:20.074  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 08:45:20.076  7056  7056 I AppUp4:CustModeStarterReceiver: onReceive
08-23 08:45:20.078  7056  7056 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9a205ce
08-23 08:45:20.078  7056  7056 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 08:45:20.078  7056  7056 D AppUp4:CustFacade: isPhone : true
08-23 08:45:20.079  7056  7056 D AppUp4:CustModeStarterReceiver: begin check event
08-23 08:45:20.079  7056  7056 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-23 08:45:20.082  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:20.082  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 08:45:20.084  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 08:45:20.087  7101  7101 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 08:45:20.088  7101  7101 W wpa_supplicant: USIM:  scard_deinit function
08-23 08:45:20.088  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-23 08:45:20.088  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 08:45:20.089  1030  7126 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 08:45:20.089  1030  7126 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-23 08:45:20.089  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 08:45:20.089  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:20.090  1030  1517 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185110
08-23 08:45:20.090  1030  1517 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=185110
08-23 08:45:20.090  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:20.090  1030  1517 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=185111  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 08:45:20.090  1030  1113 D Tethering: InitialState.processMessage what=4
08-23 08:45:20.091  1030  1517 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=185111  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-23 08:45:20.093  1030  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 08:45:20.094  1030  1517 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:20.094  1030  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:20.096  1030  7191 D DhcpStateMachine: StoppedState
08-23 08:45:20.096  1030  7191 D DhcpStateMachine: StoppedState{ when=-181ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 08:45:20.098  1030  1517 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-23 08:45:20.098  1030  1517 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-23 08:45:20.099  4769  7372 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 08:45:20.103  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-23 08:45:20.105  4769  7374 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:20.105  4769  7374 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 08:45:20.122  7253  7275 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 08:45:20.122  7253  7275 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 08:45:20.122  7253  7275 I Adreno-EGL: Build Date: 12/12/14 금
08-23 08:45:20.122  7253  7275 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 08:45:20.122  7253  7275 I Adreno-EGL: Remote Branch: 
08-23 08:45:20.122  7253  7275 I Adreno-EGL: Local Patches: 
08-23 08:45:20.122  7253  7275 I Adreno-EGL: Reconstruct Branch: 
,08-23 08:45:20.126  7094  7375 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:20.129  6964  7377 W FormManager: Network not available. Please check & try again.
08-23 08:45:20.134  3282  3282 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 08:45:20.134  3282  3282 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:20.134  3282  3282 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 08:45:20.137  6964  7378 V FormManager: Network unavailable.
08-23 08:45:20.138  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 08:45:20.138  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 08:45:20.142  6964  7378 V FormManager: Network unavailable.
08-23 08:45:20.146  7192  7192 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:20
08-23 08:45:20.149  7192  7192 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 08:45:20.149  7192  7192 D Weather.Utils: 2 : All the weather widget is gone.
08-23 08:45:20.149  7192  7192 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 08:45:20.149  7192  7192 D WeatherAncestor: connectivity changed - connection : true
08-23 08:45:20.149  7192  7192 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@72a63fc
,08-23 08:45:20.150  7192  7192 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-23 08:45:20.150  7192  7192 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 08:45:20.150  7192  7192 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 08:45:20.150  7192  7192 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 08:45:20.150  7192  7192 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:20
08-23 08:45:20.175  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 08:45:20.176  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 08:45:20.176  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 08:45:20.176  6865  6865 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 08:45:20.178  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-23 08:45:20.178  6865  6865 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 08:45:20.178  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 08:45:20.178  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 08:45:20.178  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 08:45:20.178  6865  6865 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 08:45:20.178  6865  6865 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 08:45:20.183  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:20.185  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-23 08:45:20.193  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.194  6964  7381 W FormManager: Network not available. Please check & try again.
08-23 08:45:20.198  7253  7275 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:20.198  7253  7275 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:20.205  6964  7382 V FormManager: Network unavailable.
08-23 08:45:20.206  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 08:45:20.208  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 08:45:20.210  6964  7382 V FormManager: Network unavailable.
08-23 08:45:20.213  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.216  7101  7101 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-23 08:45:20.217  1030  7126 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-23 08:45:20.218  1030  7126 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-23 08:45:20.218  1030  7126 D WifiMonitor: Disconnecting from the supplicant, no more events
08-23 08:45:20.218  1030  1517 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-23 08:45:20.222  6964  7383 W FormManager: Network not available. Please check & try again.
08-23 08:45:20.224  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 08:45:20.224  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 08:45:20.224  6964  7384 V FormManager: Network unavailable.
08-23 08:45:20.225  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:20.226  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:20.226  6964  7384 V FormManager: Network unavailable.
08-23 08:45:20.229  4769  7385 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 08:45:20.231  4769  7386 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 08:45:20.231  4769  7386 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-23 08:45:20.265  1030  2006 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7387 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-23 08:45:20.320  1921  1921 D WfdsService: Supplicant Connection state is changed : false
,08-23 08:45:20.320  1030  1517 D WifiOffDelayIfNotUsed: stopMonitoring
08-23 08:45:20.320  1030  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 08:45:20.320  1030  1517 E WifiStateMachine: useWiFiOffloading() : false
08-23 08:45:20.320  1030  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 08:45:20.320  1921  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-23 08:45:20.320  1921  2257 D WfdsService: Set the WFDS Monitor: false
08-23 08:45:20.320  1921  2257 D WfdsMonitor: WFDS Monitor is stopped
08-23 08:45:20.322  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:20.323  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-23 08:45:20.323  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-23 08:45:20.323  2488  2488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:20.323  1030  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-23 08:45:20.323  1030  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-23 08:45:20.324  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:20.324  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:20.324  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:20.352  7387  7387 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-23 08:45:20.352  7387  7387 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-23 08:45:20.357  7387  7387 V [BNRBootReceiver]: Boot Receiver Return
08-23 08:45:20.358  7387  7387 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 08:45:20.360  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:20.365  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.372  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:20.383  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.383  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:20.385  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 08:45:20.386  1030  1920 I ActivityManager: Killing 6846:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-23 08:45:20.393   308  7406 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-23 08:45:20.393  1030  1111 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-23 08:45:20.393  1796  7217 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-23 08:45:20.415  1030  1555 W libprocessgroup: failed to open /acct/uid_10037/pid_6846/cgroup.procs: No such file or directory
,08-23 08:45:20.419   308  7408 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-23 08:45:20.419  1030  1111 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-23 08:45:20.421  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-23 08:45:20.429  6865  6865 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-23 08:45:20.433  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:20.434  1796  7217 I CheckinService: active receiver: disabled
,08-23 08:45:20.458  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.465  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.471  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.472  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:20.473  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 08:45:20.476  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:20.481  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 08:45:20.487  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:20.492  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.493  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 08:45:20.493  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 08:45:20.496  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:20.504  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.511  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.520  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.520  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:20.521  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 08:45:20.524  1030  1517 E WifiStateMachine:  InitialState CMD_START_SCAN -2 -2 ic=1 proc(ms):139 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1825] from screen [on:0 period:-1239062004]
08-23 08:45:20.525  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:20.527  1030  1517 E WifiStateMachine:  DefaultState CMD_START_SCAN -2 -2 ic=1 proc(ms):140 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1239062001]
08-23 08:45:20.534  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.543  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.553  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.554  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:20.554  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 08:45:20.559  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:20.572  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.583  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.592  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.593  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 08:45:20.594  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 08:45:20.599  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:20.612  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.621  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.631  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.632  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 08:45:20.633  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 08:45:20.640  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:20.658  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.669  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:20.681  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 08:45:20.682  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:20.689  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 08:45:20.697  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:20.713  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.728  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.742  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.743  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:20.744  6917  6917 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 08:45:20.757  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:20.766  6886  6886 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-23 08:45:20.785  1030  1522 D WifiService: New client listening to asynchronous messages
,08-23 08:45:20.786  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:20.803  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.819  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:20.831  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 08:45:20.832  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:20.834  6917  6917 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-23 08:45:20.836  6917  6917 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 08:45:20.837  6917  6917 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 08:45:20.844  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:20.854  6886  6886 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-23 08:45:20.857  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:20.864  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.879  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:20.895  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.896  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:20.898  6917  6917 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-23 08:45:20.900  6917  6917 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 08:45:20.901  6917  6917 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 08:45:20.913  2154  2154 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-23 08:45:20.931  2154  2154 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-23 08:45:20.932  2154  2154 D c       : Getting all permits...
,08-23 08:45:20.932  2154  2154 D a       : Opening database...
08-23 08:45:20.937  6627  7037 D UEI.SmartControl: Internal timer expired: 2
08-23 08:45:20.937  6627  7037 D UEI.SmartControl: unbind internal service
08-23 08:45:20.943  2154  2154 D a       : Opening database auth.proximity.permit_store...
08-23 08:45:20.946  2154  2154 D a       : Closing database...
08-23 08:45:20.960  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:20.969  6886  6886 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-23 08:45:20.970  6886  6886 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 08:45:20.970  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:20.975  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:20.986  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:20.996  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:20.997  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 08:45:21.001  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 08:45:21.007  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:21.013  6886  6886 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 08:45:21.013  6886  6886 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 08:45:21.013  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 08:45:21.020  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:21.031  6627  7034 D serial_port: close(fd = 24)
,08-23 08:45:21.035  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:21.036  6627  7034 I UEI.SmartControl: Serial port is closed.
08-23 08:45:21.048  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 08:45:21.049  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:21.052  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 08:45:21.060  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:21.067  6886  6886 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-23 08:45:21.067  6886  6886 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-23 08:45:21.067  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 08:45:21.072  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:21.080  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:21.090  6917  6917 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:21.091  6917  6917 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:21.093  6917  6917 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-23 08:45:21.111  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 08:45:21.116  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 08:45:21.125  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:21.138  6964  7416 W FormManager: Network not available. Please check & try again.
,08-23 08:45:21.146  6964  7417 V FormManager: Network unavailable.
08-23 08:45:21.150  6964  7417 V FormManager: Network unavailable.
,08-23 08:45:21.155  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 08:45:21.159  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 08:45:21.161  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:21.163  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 08:45:21.172  6886  6886 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-23 08:45:21.172  6886  6886 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-23 08:45:21.172  6886  6886 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:21.176  4769  7418 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 08:45:21.180  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 08:45:21.184  6964  7420 W FormManager: Network not available. Please check & try again.
08-23 08:45:21.186  4769  7422 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 08:45:21.186  4769  7422 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 08:45:21.189  6964  7421 V FormManager: Network unavailable.
,08-23 08:45:21.193  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:21.195  6964  7421 V FormManager: Network unavailable.
08-23 08:45:21.212  2154  2154 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-23 08:45:21.700  1030  1517 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1173] from screen [on:0 period:-1239060828] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-23 08:45:21.703  1030  1517 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1239060826] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-23 08:45:21.793  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:21.810  1030  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:21.814  1030  1113 D Tethering: MasterInitialState.processMessage what=3
08-23 08:45:21.819  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:21.819  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:21.826  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-23 08:45:21.832  6370  6884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-23 08:45:21.834  5732  5732 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-23 08:45:21.872  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:21.902  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 08:45:21.902  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:21.902  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 08:45:21.902  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-23 08:45:21.909  7056  7056 I AppUp4:CustModeStarterReceiver: onReceive
08-23 08:45:21.913  7056  7056 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9a205ce
08-23 08:45:21.913  7056  7056 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 08:45:21.913  7056  7056 D AppUp4:CustFacade: isPhone : true
08-23 08:45:21.914  7056  7056 D AppUp4:CustModeStarterReceiver: begin check event
08-23 08:45:21.914  7056  7056 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-23 08:45:21.919  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:21.919  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 08:45:21.921  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-23 08:45:21.928  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:21.940  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-23 08:45:21.964  4769  7441 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 08:45:21.970  4769  7442 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:21.971  4769  7442 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 08:45:21.973  1030  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:21.985  7094  7445 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 08:45:21.990  3282  3282 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 08:45:21.990  3282  3282 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:21.990  3282  3282 I LgeMiscReceiver: networkInfo.isConnected() = true
08-23 08:45:21.990  3282  3282 D PhoneState: setPdpRejectCasuse : false
08-23 08:45:21.994  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 08:45:21.995  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 08:45:22.001  6964  7450 V FormManager: Network unavailable.
,08-23 08:45:22.005  6964  7449 W FormManager: Network not available. Please check & try again.
,08-23 08:45:22.006  6964  7450 V FormManager: Network unavailable.
08-23 08:45:22.010  7192  7192 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:22
08-23 08:45:22.011  7192  7192 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 08:45:22.011  7192  7192 D Weather.Utils: 2 : All the weather widget is gone.
08-23 08:45:22.011  7192  7192 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 08:45:22.012  7192  7192 D WeatherAncestor: connectivity changed - connection : true
08-23 08:45:22.012  7192  7192 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@72a63fc
08-23 08:45:22.012  7192  7192 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 08:45:22.012  7192  7192 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 08:45:22.013  7192  7192 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 08:45:22.013  7192  7192 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 08:45:22.013  7192  7192 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:22
08-23 08:45:22.852  1030  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:22.853  1030  1901 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-23 08:45:22.892  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 08:45:22.893  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 08:45:22.893  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-23 08:45:22.894  1030  1113 D BluetoothManagerService: Message: 1
08-23 08:45:22.894  1030  1113 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-23 08:45:22.920  1030  1113 D BluetoothManagerService: Message: 20
08-23 08:45:22.921  1030  1113 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10fbf503:true
,08-23 08:45:22.926  6994  6994 D BluetoothAdapterState: make
08-23 08:45:22.931  6994  6994 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-23 08:45:22.931  6994  6994 I bluedroid-qcom: init
08-23 08:45:22.933  6994  7462 I BluetoothAdapterState: Entering OffState
08-23 08:45:22.933  6994  6994 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 08:45:22.933  6994  6994 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 08:45:22.934  6994  6994 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 08:45:22.934  6994  6994 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 08:45:22.934  6994  6994 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-23 08:45:22.936  6994  6994 I bluedroid-qcom: get_profile_interface socket
08-23 08:45:22.936  6994  6994 I bluedroid-qcom: get_profile_interface map_client
,08-23 08:45:22.941  6994  7466 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-23 08:45:22.931  7465  7465 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:22.941  7465  7465 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:22.957  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-23 08:45:22.960  1030  1113 D BluetoothManagerService: Message: 40
08-23 08:45:22.960  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-23 08:45:22.961  6994  7009 I bluedroid-qcom: config_hci_snoop_log
08-23 08:45:22.962  1030  1113 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-23 08:45:22.963  1030  1113 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-23 08:45:22.965  7465  7465 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-23 08:45:22.965  7465  7465 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-23 08:45:22.965  7465  7465 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-23 08:45:22.970  6994  7462 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-23 08:45:22.974  6994  7466 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-23 08:45:22.974  7465  7465 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-23 08:45:22.977  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:22.979  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 08:45:22.979  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 08:45:22.981  1030  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:22.982  7465  7465 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-23 08:45:22.982  7465  7465 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-23 08:45:22.992  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:22.994  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:23.004  1030  1113 D Tethering: MasterInitialState.processMessage what=3
08-23 08:45:23.004  1030  1113 D Tethering: MasterInitialState.processMessage what=3
,08-23 08:45:23.012  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-23 08:45:23.016  6370  6884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-23 08:45:23.018  6994  7466 D BluetoothAdapterProperties: Name is: G3
,08-23 08:45:23.022  6994  7462 D BluetoothAdapterProperties: Setting state to 11
08-23 08:45:23.022  6994  7462 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 08:45:23.025  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:23.026  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:23.027  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:23.028  5732  5732 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-23 08:45:23.030  1030  1113 D BluetoothManagerService: Message: 60
08-23 08:45:23.030  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-23 08:45:23.030  1030  1113 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-23 08:45:23.031  6994  7462 I LGBluetoothServiceJni: classInitNative: succeeds
,08-23 08:45:23.048  1921  1921 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:45:23.052  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:23.051  1583  1583 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 08:45:23.055  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:23.057  6865  6865 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-23 08:45:23.063  6994  7462 D BluetoothBondStateMachine: make
,08-23 08:45:23.075  6994  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.075  6994  7462 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-23 08:45:23.075  6994  7462 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.075  6994  7462 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-23 08:45:23.077  6994  6994 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 08:45:23.078  6994  6994 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:23.078  6994  6994 V BluetoothPbapReceiver: ***********state = 11
,08-23 08:45:23.085  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 08:45:23.087  6994  7467 I BluetoothBondStateMachine: StableState(): Entering Off State
08-23 08:45:23.087  6994  7462 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-23 08:45:23.120  6994  7462 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 08:45:23.148  1030  1555 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7479 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-23 08:45:23.157  6994  6994 D HeadsetService: Received start request. Starting profile...
08-23 08:45:23.157  6994  6994 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 08:45:23.158  6994  6994 D LGBluetoothHfpAdapter: Version 1.6
08-23 08:45:23.161  6994  6994 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 08:45:23.162  6994  6994 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 08:45:23.163  6994  6994 D HeadsetStateMachine: make
08-23 08:45:23.165  1030  1103 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.166  1030  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:23.166  1030  1103 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:23.170  5732  5732 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-23 08:45:23.173  6994  7462 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:23.182  6994  7462 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 08:45:23.195  6994  7462 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:23.198  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.208  6994  7462 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 08:45:23.211  6994  6994 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:23.211  6994  6994 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:23.212  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 08:45:23.212  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.212  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 08:45:23.212  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 08:45:23.215  6994  7462 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:23.217  7056  7056 I AppUp4:CustModeStarterReceiver: onReceive
08-23 08:45:23.217  6994  6994 D HeadsetStateMachine: max_hf_connections = 1
08-23 08:45:23.217  6994  6994 I bluedroid-qcom: get_profile_interface handsfree
08-23 08:45:23.220  6994  6994 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-23 08:45:23.220  6994  7462 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:23.220   313   313 V AudioPolicyService: registerClient() client 0xb14b7ac0, uid 1002
,08-23 08:45:23.220  7056  7056 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9a205ce
,08-23 08:45:23.220  7056  7056 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 08:45:23.220  7056  7056 D AppUp4:CustFacade: isPhone : true
08-23 08:45:23.221  7056  7056 D AppUp4:CustModeStarterReceiver: begin check event
08-23 08:45:23.221  7056  7056 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-23 08:45:23.221   313  1363 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-23 08:45:23.221   313  1363 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 08:45:23.221   313  1363 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 08:45:23.221  6994  6994 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-23 08:45:23.222   313  1530 V AudioFlinger: registerClient() client 0xb1003478, pid 6994
08-23 08:45:23.222   313  1358 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:23.222   313  1358 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:23.223  1583  2250 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:23.223  1583  2250 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-23 08:45:23.223  6994  7010 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:23.223  1030  2006 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:23.223  1030  2006 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:23.223   313  1359 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:23.223   313  1359 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:23.223  3282  3297 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:23.223  3282  3297 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:23.224  1030  1920 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:23.224  1030  1920 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:23.224  6994  7010 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-23 08:45:23.224  6994  7010 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:23.224  6994  6994 V ToneGenerator: Create Track: 0xb4928a80
08-23 08:45:23.224  6994  7010 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-23 08:45:23.224  6994  6994 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-23 08:45:23.224  6994  6994 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-23 08:45:23.224  1583  2131 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:23.224  1583  2131 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:23.224   313   313 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 08:45:23.224   313   313 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-23 08:45:23.224   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 08:45:23.224   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 08:45:23.224   313  1364 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 08:45:23.224  3282  3298 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:23.225  3282  3298 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:23.225   313   313 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 08:45:23.225   313   313 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-23 08:45:23.225   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 08:45:23.225   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 08:45:23.225  6994  6994 V AudioSystem: getLatency() output 2, latency 50
08-23 08:45:23.225  6994  6994 V AudioSystem: getFrameCount() output 2, frameCount 960
08-23 08:45:23.225  6994  6994 V AudioTrack: createTrack_l() output 2 afLatency 50
08-23 08:45:23.225  1832  1847 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:23.225  1832  1847 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:23.225  1832  1847 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:23.225  1832  1847 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:23.226   313  1363 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 08:45:23.226   313  1363 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 08:45:23.226   313  1363 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 08:45:23.226   313  1363 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 08:45:23.226   313  1363 V AudioFlinger: createTrack() lSessionId: 22
08-23 08:45:23.228  4769  4769 D LGDMClient: [DmDev,iceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.228  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-23 08:45:23.229  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:23.232  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:23.233  6994  6994 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-23 08:45:23.234   313  1364 V AudioFlinger: acquiring 22 from 6994, for 6994
08-23 08:45:23.234   313  1364 V AudioFlinger:  added new entry for 22
08-23 08:45:23.234  6994  6994 V ToneGenerator: ToneGenerator INIT OK, time: 188269
08-23 08:45:23.234  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.235  6994  7492 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-23 08:45:23.235  6994  7492 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 08:45:23.235  6994  7492 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 08:45:23.235  6994  7492 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-23 08:45:23.236   313   313 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6994
08-23 08:45:23.236   313   313 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-23 08:45:23.236   313   313 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-23 08:45:23.236   313   313 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-23 08:45:23.236   313   313 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-23 08:45:23.236   313   313 V voice   : voice_set_parameters: exit with code(0)
08-23 08:45:23.236   313   313 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-23 08:45:23.236   313   313 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-23 08:45:23.236   313   313 V msm8974_platform: platform_set_parameters: exit with code(0)
08-23 08:45:23.236   313   313 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-23 08:45:23.236   313   313 V audio_hw_primary: adev_set_parameters: exit with code(0)
,08-23 08:45:23.236   313   313 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-23 08:45:23.236  6994  7492 V ToneGenerator: ToneGenerator destructor
08-23 08:45:23.236  6994  7492 V ToneGenerator: stopTone
08-23 08:45:23.236  6994  7492 V ToneGenerator: Delete Track: 0xb4928a80
08-23 08:45:23.237   313  1530 V AudioPolicyService: AudioCommandThread() adding release output 2
08-23 08:45:23.237   313  1530 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-23 08:45:23.237   313  1265 V AudioPolicyService: AudioCommandThread() waking up
08-23 08:45:23.237   313  1265 V AudioPolicyService: AudioCommandThread() processing release output 2
08-23 08:45:23.237   313  1265 V AudioPolicyManager: releaseOutput() 2
08-23 08:45:23.237   313  1265 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 08:45:23.237   313  1530 V AudioFlinger: PlaybackThread::Track destructor
08-23 08:45:23.237  6994  7492 V AudioTrack: ~AudioTrack, releasing session id from 6994 on behalf of 6994
08-23 08:45:23.237   313  1530 V AudioFlinger: removeClient_l() pid 6994, calling pid 313
,08-23 08:45:23.238   313  1364 V AudioFlinger: releasing 22 from 6994 for 6994
08-23 08:45:23.238   313  1364 V AudioFlinger:  decremented refcount to 0
08-23 08:45:23.238   313  1364 V AudioFlinger: purging stale effects
,08-23 08:45:23.245  6994  7462 V LGMDMManager: Create singleton instance
08-23 08:45:23.246  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.248  6994  6994 D A2dpService: Received start request. Starting profile...
,08-23 08:45:23.248  6994  6994 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 08:45:23.249  6994  6994 V Avrcp   : make
08-23 08:45:23.250  6994  6994 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-23 08:45:23.250  6994  6994 I bluedroid-qcom: get_profile_interface avrcp
08-23 08:45:23.251  6994  7462 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 08:45:23.254  4769  7505 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 08:45:23.258  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-23 08:45:23.265  6994  6994 V AudioManager: registerRemoteController: size of Media player list: 0
08-23 08:45:23.267  6994  6994 E AudioManager: No RCC entry present to update
08-23 08:45:23.267  6994  6994 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-23 08:45:23.270  6994  6994 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-23 08:45:23.271  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-23 08:45:23.271  6994  6994 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-23 08:45:23.276  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-23 08:45:23.286  4769  7506 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.286  4769  7506 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 08:45:23.333  7094  7509 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 08:45:23.337  3282  3282 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 08:45:23.337  3282  3282 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.337  3282  3282 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 08:45:23.340  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 08:45:23.340  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 08:45:23.349  7192  7192 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:23
,08-23 08:45:23.351  6964  7511 W FormManager: Network not available. Please check & try again.
08-23 08:45:23.353  6964  7513 V FormManager: Network unavailable.
08-23 08:45:23.354  7192  7192 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 08:45:23.354  7192  7192 D Weather.Utils: 2 : All the weather widget is gone.
08-23 08:45:23.356  7192  7192 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 08:45:23.356  7192  7192 D WeatherAncestor: connectivity changed - connection : true
08-23 08:45:23.356  7192  7192 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@72a63fc
08-23 08:45:23.356  6964  7513 V FormManager: Network unavailable.
08-23 08:45:23.357  7479  7479 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 08:45:23.358  7479  7479 W LG Account v2.2: No ProfileInfo entries
08-23 08:45:23.358  7479  7479 I LG Account v2.2: isEnabled: false
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Country: EU
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Operator: OPEN
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Ranking support: false
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Comfort support: false
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Accessory: true
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Health device: true
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Extra Pedometer: false
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Blood glucose device: false
08-23 08:45:23.358  7479  7479 I Feature : [Lifetracker]Device Number: 3
08-23 08:45:23.359  7192  7192 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 08:45:23.359  7192  7192 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 08:45:23.359  7192  7192 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 08:45:23.359  7192  7192 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 08:45:23.360  7192  7192 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:23
08-23 08:45:23.370  6865  6865 D BluetoothPermissionRequest: onReceive
08-23 08:45:23.370  1030  1919 V SIM_STK : Menu title from STK is T-Mobile
08-23 08:45:23.370  1030  1919 V SIM_STK : Menu title from STK is T-Mobile
,08-23 08:45:23.375  6865  6865 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 08:45:23.385  6370  6370 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-23 08:45:23.386  6370  6884 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-23 08:45:23.400  2154  2154 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-23 08:45:23.407  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-23 08:45:23.407  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.407  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-23 08:45:23.407  7056  7056 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-23 08:45:23.408  7056  7056 I AppUp4:CustModeStarterReceiver: onReceive
08-23 08:45:23.411  7056  7056 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9a205ce
08-23 08:45:23.411  7056  7056 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 08:45:23.411  7056  7056 D AppUp4:CustFacade: isPhone : true
08-23 08:45:23.411  7056  7056 D AppUp4:CustModeStarterReceiver: begin check event
08-23 08:45:23.411  7056  7056 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-23 08:45:23.414  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.415  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-23 08:45:23.416  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:23.417  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:23.420  4769  7516 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-23 08:45:23.420  1030  1919 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-23 08:45:23.423  7094  7094 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-23 08:45:23.425  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-23 08:45:23.426  4769  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.426  4769  7517 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-23 08:45:23.428  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 08:45:23.428  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 08:45:23.428  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 08:45:23.428  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 08:45:23.429  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 08:45:23.429  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 08:45:23.429  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 08:45:23.429  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 08:45:23.429  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 08:45:23.429  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 08:45:23.429  6994  6994 I BluetoothA2dpServiceJni: classInitNative
08-23 08:45:23.429  6994  6994 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 08:45:23.429  6994  6994 D A2dpStateMachine: make
08-23 08:45:23.430  6994  6994 I bluedroid-qcom: get_profile_interface a2dp
08-23 08:45:23.432  6994  7519 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 08:45:23.433  6994  6994 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-23 08:45:23.433  6994  6994 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-23 08:45:23.434  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.434  6994  7518 D A2dpStateMachine: Enter Disconnected: -2
08-23 08:45:23.435  6994  6994 I BluetoothHidServiceJni: classInitNative: succeeds
08-23 08:45:23.436  6994  6994 D HidService: Received start request. Starting profile...
,08-23 08:45:23.436  6994  6994 I bluedroid-qcom: get_profile_interface hidhost
08-23 08:45:23.436  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.436  6994  6994 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 08:45:23.437  6994  6994 D HealthService: Received start request. Starting profile...
08-23 08:45:23.439  6994  6994 I bluedroid-qcom: get_profile_interface health
08-23 08:45:23.439  6994  6994 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-23 08:45:23.439  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.439  7094  7521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:23.439  6994  6994 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 08:45:23.441  6994  6994 D PanService: Received start request. Starting profile...
08-23 08:45:23.441  6994  6994 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 08:45:23.441  6994  6994 I bluedroid-qcom: get_profile_interface pan
08-23 08:45:23.445  3282  3282 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-23 08:45:23.445  3282  3282 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:23.445  3282  3282 I LgeMiscReceiver: networkInfo.isConnected() = false
08-23 08:45:23.447  6994  6994 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-23 08:45:23.447  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.447  6994  6994 D HeadsetStateMachine: Proxy object connected
08-23 08:45:23.447  6994  6994 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-23 08:45:23.448  6994  6994 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-23 08:45:23.450  6994  6994 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-23 08:45:23.453  7136  7136 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-23 08:45:23.453  7136  7136 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-23 08:45:23.454  6994  6994 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 08:45:23.454  6964  7525 W FormManager: Network not available. Please check & try again.
08-23 08:45:23.454  6994  6994 D BtGatt.GattService: Received start request. Starting profile...
08-23 08:45:23.454  6994  6994 D BtGatt.GattService: start()
08-23 08:45:23.454  6994  6994 I bluedroid-qcom: get_profile_interface gatt
08-23 08:45:23.455  6994  6994 D BtGatt.AdvertiseManager: advertise manager created
08-23 08:45:23.460  6964  7526 V FormManager: Network unavailable.
,08-23 08:45:23.462  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.463  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:23.463  6994  6994 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-23 08:45:23.464  6994  6994 V BluetoothMapService: BluetoothMapBinder()
08-23 08:45:23.464  6994  6994 D BluetoothMapService: Received start request. Starting profile...
08-23 08:45:23.464  6994  6994 D BluetoothMapService: start()
08-23 08:45:23.464  7192  7192 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:23
08-23 08:45:23.465  6964  7526 V FormManager: Network unavailable.
08-23 08:45:23.465  7192  7192 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 08:45:23.465  7192  7192 D Weather.Utils: 2 : All the weather widget is gone.
08-23 08:45:23.466  7192  7192 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 08:45:23.466  7192  7192 D WeatherAncestor: connectivity changed - connection : true
08-23 08:45:23.466  7192  7192 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@72a63fc
08-23 08:45:23.466  7192  7192 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-23 08:45:23.466  7192  7192 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-23 08:45:23.466  7192  7192 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-23 08:45:23.466  7192  7192 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-23 08:45:23.466  7192  7192 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:45:23
08-23 08:45:23.467  6994  6994 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-23 08:45:23.467  6994  6994 D BluetoothMapEmailAppObserver: createReceiver()
08-23 08:45:23.469  6994  6994 D BluetoothMapEmailAppObserver: initObservers()
08-23 08:45:23.469  6994  6994 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-23 08:45:23.475  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
,08-23 08:45:23.478  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:23.478  6994  7492 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 08:45:23.478  6994  7492 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 08:45:23.479  6994  7492 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-23 08:45:23.480  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:23.482  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:23.484  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:23.486  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:23.486  6994  6994 V PanService: [BTUI] SIM Extra State :ABSENT
08-23 08:45:23.488  6994  6994 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-23 08:45:23.488  6994  6994 V BluetoothMapService: Handler(): got msg=1
,08-23 08:45:23.489  6994  7462 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-23 08:45:23.489  6994  7462 I bluedroid-qcom: enable
08-23 08:45:23.489  6994  7462 I bt_hci_bdroid: init
08-23 08:45:23.490  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:23.490  6994  7462 I bt_vendor: bt-vendor : init
08-23 08:45:23.490  6994  7462 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 08:45:23.490  6994  7462 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 08:45:23.490  6994  7462 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-23 08:45:23.490  6994  7462 D bt_userial_mct: userial_init
08-23 08:45:23.490  6994  7531 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-23 08:45:23.491  6994  7462 D bt_hci_bdroid: set_power 1
08-23 08:45:23.491  6994  7462 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 08:45:23.491  6994  7462 I bt_vendor: Starting hciattach daemon
08-23 08:45:23.491  6994  7462 I bt_vendor: try to set true
08-23 08:45:23.491  6994  6994 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 08:45:23.491  6994  6994 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 08:45:23.491  6994  6994 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 08:45:23.491  6994  6994 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:23.491  6994  6994 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-23 08:45:23.491  6994  7531 I bt-btu  : btu_task pending for preload complete event
08-23 08:45:23.481  7534  7534 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:23.481  7534  7534 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:23.507  7535  7535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-23 08:45:23.551  7541  7541 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-23 08:45:23.559  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-23 08:45:23.593  7544  7544 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 08:45:23.615  7545  7545 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-23 08:45:23.625  7546  7546 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 08:45:23.636  7547  7547 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-23 08:45:23.652  7549  7549 I libmdmdetect: ESOC framework not supported
08-23 08:45:23.653  7549  7549 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-23 08:45:23.660  7549  7549 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-23 08:45:23.660  7549  7549 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-23 08:45:23.660  7549  7549 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-23 08:45:23.660  7549  7549 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-23 08:45:23.660  7549  7549 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-23 08:45:23.660  7549  7549 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-23 08:45:23.660  7549  7549 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-23 08:45:23.693  7549  7550 E QC-QMI  : qmi_client [7549] 14: failed to locate client data
08-23 08:45:23.694   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-23 08:45:23.694   469   469 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-23 08:45:23.737  7553  7553 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-23 08:45:23.755  7555  7555 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 08:45:23.792  6994  7462 I bt_vendor: bluetooth satus is on
08-23 08:45:23.793  6994  7462 D bt_hci_bdroid: preload
,08-23 08:45:23.793  6994  7533 D bt_userial_mct: userial_open(port:0)
,08-23 08:45:23.793  6994  7533 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-23 08:45:23.796  6994  7533 I bt_vendor: Done intiailizing UART
08-23 08:45:23.797  6994  7533 I bt_vendor: Done intiailizing UART
08-23 08:45:23.797  6994  7533 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-23 08:45:23.797  6994  7533 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-23 08:45:23.797  6994  7531 I bt-btu  : btu_task received preload complete event
08-23 08:45:23.798  6994  7557 D bt_userial_mct: Entering userial_read_thread()
08-23 08:45:23.798  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-23 08:45:23.798  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-23 08:45:23.803  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 08:45:23.810  6994  7531 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 08:45:23.811  6994  7531 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 08:45:23.811  6994  7531 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 08:45:23.892  6994  7531 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-23 08:45:23.892  6994  7531 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0240061 
08-23 08:45:23.892  6994  7531 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0240061 
,08-23 08:45:23.929  6994  7466 E bt-btif : Calling BTA_HhEnable
08-23 08:45:23.929  6994  7466 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-23 08:45:23.929  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-23 08:45:23.929  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-23 08:45:23.930  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-23 08:45:23.930  6994  7466 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-23 08:45:23.930  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-23 08:45:23.930  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-23 08:45:23.932  6994  7466 D BluetoothAdapterProperties: Name is: G3
,08-23 08:45:23.935  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-23 08:45:23.936  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 08:45:23.939  6994  7466 D BluetoothAdapterProperties: Scan Mode:20
08-23 08:45:23.940  6994  7466 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 08:45:23.940  6994  7466 D bt_hci_bdroid: postload
08-23 08:45:23.940  6994  7533 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:23.942  6994  7531 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-23 08:45:23.942  6994  7466 D bte_conf: Device ID record 1 : primary
08-23 08:45:23.942  6994  7466 D bte_conf:   vendorId            = 00c4
08-23 08:45:23.942  6994  7466 D bte_conf:   vendorIdSource      = 0001
08-23 08:45:23.942  6994  7466 D bte_conf:   product             = 13a1
08-23 08:45:23.942  6994  7466 D bte_conf:   version             = 1000
08-23 08:45:23.942  6994  7466 D bte_conf:   clientExecutableURL = 
08-23 08:45:23.942  6994  7466 D bte_conf:   serviceDescription  = 
08-23 08:45:23.943  6994  7466 D bte_conf:   documentationURL    = 
08-23 08:45:23.943  6994  7466 D bte_conf: bte_load_did_conf no section named DID2.
08-23 08:45:23.946  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:23.950  6994  7531 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:23.950  6994  7466 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 08:45:23.950  6994  7531 W bt-smp  : Plain text(LSB ~ MSB) = 12 48 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:23.950  6994  7531 W bt-smp  : Encrypted text(LSB ~ MSB) = 4a 21 0b 99 21 f9 d2 ae 80 99 56 df 6c 5d 45 53 
08-23 08:45:23.950  6994  7531 W bt-btm  : Stopping oneshot timer
,08-23 08:45:23.952  6994  7462 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-23 08:45:23.952  6994  7462 D BluetoothAdapterProperties: ScanMode =  20
08-23 08:45:23.952  6994  7462 D BluetoothAdapterProperties: State =  11
08-23 08:45:23.952  6994  7462 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-23 08:45:23.954  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:23.941  7559  7559 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:23.956  6994  7533 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:23.957  6994  7462 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-23 08:45:23.951  7559  7559 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:23.957  6994  7462 D BluetoothAdapterProperties: Setting state to 12
08-23 08:45:23.958  6994  7462 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 08:45:23.960  1030  1113 D BluetoothManagerService: Message: 60
08-23 08:45:23.960  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-23 08:45:23.960  1030  1113 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-23 08:45:23.960  6994  7533 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:23.960  6994  7533 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:23.961  6994  7462 I BluetoothAdapterState: Entering On State
08-23 08:45:23.962  6994  7466 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 08:45:23.964  6994  7462 D LGBluetoothServiceAdapter: [BTUI] OnState
08-23 08:45:23.964  6994  7462 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-23 08:45:23.964  6994  7462 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-23 08:45:23.967  6994  7533 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:23.967  6994  7557 E bt_mct  : hci lib postload completed
08-23 08:45:23.968  6994  7462 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-23 08:45:23.970  1832  1848 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 08:45:23.975  6865  6881 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 08:45:23.977  6994  7466 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 08:45:23.978  6994  7466 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-23 08:45:23.978  1832  1832 D BluetoothHeadset: Proxy object connected
08-23 08:45:23.978  1832  1847 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 08:45:23.981  1832  1832 D BluetoothHeadset: Proxy object connected
,08-23 08:45:23.983  6865  6880 D BluetoothMap: onBluetoothStateChange: up=true
08-23 08:45:23.987  1030  1113 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 08:45:23.987  6865  6865 D BluetoothMap: Proxy object connected
08-23 08:45:23.987  6865  6865 D MapProfile: Bluetooth service connected
08-23 08:45:23.987  6865  6865 D BluetoothMap: getConnectedDevices()
08-23 08:45:23.987  6994  7531 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:23.987  6994  7531 W bt-smp  : Plain text(LSB ~ MSB) = d3 9a 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:23.987  6994  7531 W bt-smp  : Encrypted text(LSB ~ MSB) = dd 65 72 63 35 4e c0 04 25 f7 76 ac 84 de 05 8e 
08-23 08:45:23.987  6994  7531 W bt-btm  : Stopping oneshot timer
08-23 08:45:23.989  1832  1848 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 08:45:23.989  6994  7010 V BluetoothMapService: getConnectedDevices()
08-23 08:45:23.990  1030  1030 D BluetoothA2dp: Proxy object connected
,08-23 08:45:24.007  6994  7531 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-23 08:45:24.007  6994  7531 W bt-smp  : Plain text(LSB ~ MSB) = 2a a7 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:24.008  6994  7531 W bt-smp  : Encrypted text(LSB ~ MSB) = fa 7d 47 47 a6 a7 8a ee 4c 1c 70 53 8b f3 0c a3 
08-23 08:45:24.008  6994  7531 W bt-btm  : Stopping oneshot timer
08-23 08:45:24.011  6994  7462 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-23 08:45:24.020  6994  7531 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:24.020  6994  7531 W bt-smp  : Plain text(LSB ~ MSB) = 35 2b 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:24.020  6994  7531 W bt-smp  : Encrypted text(LSB ~ MSB) = 21 f5 2d e2 c2 2f 1b 1c 2a 23 c7 65 2d dc d9 f7 
08-23 08:45:24.020  6994  7531 W bt-btm  : Stopping oneshot timer
,08-23 08:45:24.033  6994  7531 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:24.033  6994  7531 W bt-smp  : Plain text(LSB ~ MSB) = 37 0c 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:24.033  6994  7531 W bt-smp  : Encrypted text(LSB ~ MSB) = 46 b9 1e ee a3 d8 7c c5 92 d2 21 af 25 4f 39 8d 
08-23 08:45:24.033  6994  7531 W bt-btm  : Stopping oneshot timer
,08-23 08:45:24.035  7566  7566 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-23 08:45:24.139  1030  1113 I art     : Explicit concurrent mark sweep GC freed 113226(5MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.738ms total 146.814ms
08-23 08:45:24.139  1832  1832 D BluetoothHeadset: Proxy object connected
08-23 08:45:24.140  1030  1113 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 08:45:24.140  6865  6881 D BluetoothPan: onBluetoothStateChange on: true
08-23 08:45:24.140  6865  6881 D BluetoothPan: onBluetoothStateChange call bindService
08-23 08:45:24.141  1030  1030 D BluetoothHeadset: Proxy object connected
,08-23 08:45:24.144  6865  6880 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 08:45:24.146  6865  6865 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 08:45:24.146  6865  6865 D PanProfile: Bluetooth service connected
08-23 08:45:24.148  1030  1113 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-23 08:45:24.148  1030  1113 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-23 08:45:24.155  6716  6716 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-23 08:45:24.156  1921  1921 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:24.157  1921  2059 D LGBluetoothAPIService: Message: 1
08-23 08:45:24.157  1921  2059 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-23 08:45:24.158  1583  1583 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 08:45:24.166  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:24.166  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:24.166  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:24.166  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:24.166  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:24.166  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:24.166  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:24.166  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:24.169  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-23 08:45:24.169  1030  1113 D BluetoothManagerService: Message: 40
08-23 08:45:24.169  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-23 08:45:24.172  6865  6865 D BluetoothInputDevice: Proxy object connected
08-23 08:45:24.172  6865  6865 D HidProfile: Bluetooth service connected
08-23 08:45:24.172  1921  2059 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-23 08:45:24.173  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:24.174  6994  6994 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:24.174  6994  6994 D BluetoothMapService: STATE_ON
08-23 08:45:24.176  6994  6994 D LGBluetoothAPIServer: [BTUI] onCreate()
08-23 08:45:24.176  6994  6994 D LGBluetoothAPIServer: [BTUI] onBind()
08-23 08:45:24.177  6994  6994 V BluetoothMapService: Handler(): got msg=1
08-23 08:45:24.177  1921  1921 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-23 08:45:24.178  1921  2059 D LGBluetoothAPIService: Message: 100
08-23 08:45:24.178  1921  2059 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-23 08:45:24.178  6994  6994 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-23 08:45:24.180  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:24.180  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:24.180  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:24.180  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:24.180  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:24.180  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:24.180  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:24.180  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:24.181  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:45:24.181  6865  6865 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 08:45:24.182  6994  7569 D BluetoothMapMasInstance: MAS initSocket()
08-23 08:45:24.182  6994  7569 D BluetoothMapMasInstance:   masId = 00
08-23 08:45:24.182  6994  7569 D BluetoothMapMasInstance:   msgTypes = 0e
08-23 08:45:24.182  6994  7569 D BluetoothMapMasInstance:   masName = SMS/MMS
08-23 08:45:24.182  6994  7569 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-23 08:45:24.186  1030  1555 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:24.186  1030  1113 D BluetoothManagerService: Message: 30
08-23 08:45:24.187  6994  7569 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:24.188  6865  6865 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-23 08:45:24.188  6994  7569 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-23 08:45:24.189  6994  7466 D BluetoothAdapterProperties: Scan Mode:21
08-23 08:45:24.189  6994  7569 V BluetoothMapMasInstance: Succeed to create listening socket 
08-23 08:45:24.189  6994  7466 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-23 08:45:24.189  6994  7569 D BluetoothMapMasInstance: Accepting socket connection...
08-23 08:45:24.190  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:24.191  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:24.192  7229  7277 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-23 08:45:24.193  1030  1113 D BluetoothManagerService: Message: 30
,08-23 08:45:24.197  6865  6865 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-23 08:45:24.199  6865  6865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 08:45:24.200  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:24.200  6994  6994 V BluetoothPbapService: Pbap Service onCreate
08-23 08:45:24.201  6994  6994 V BluetoothPbapService: Starting PBAP service
08-23 08:45:24.201  6865  6865 D BluetoothA2dp: Proxy object connected
08-23 08:45:24.201  6865  6865 D A2dpProfile: Bluetooth service connected
08-23 08:45:24.202  6994  6994 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-23 08:45:24.202  6994  6994 V BluetoothPbapService: Pbap Service onBind
08-23 08:45:24.203  6994  6994 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:24.203  6994  6994 V BluetoothPbapService: state: 12
08-23 08:45:24.203  6994  6994 V BluetoothPbapService: Handler(): got msg=1
08-23 08:45:24.204  6994  6994 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-23 08:45:24.204  6865  6865 D BluetoothHeadset: Proxy object connected
08-23 08:45:24.204  6994  6994 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 08:45:24.204  6994  6994 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:24.204  6994  6994 V BluetoothPbapReceiver: ***********state = 12
08-23 08:45:24.205  6865  6865 D HeadsetProfile: Bluetooth service connected
08-23 08:45:24.205  6994  7571 V BluetoothPbapService: Pbap Service initSocket
08-23 08:45:24.205  1030  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:24.207  6994  7571 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 08:45:24.211  6994  7571 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-23 08:45:24.211  6994  7571 V BluetoothPbapService: Succeed to create listening socket 
08-23 08:45:24.211  6994  7571 V BluetoothPbapService: Accepting socket connection...
08-23 08:45:24.211  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 08:45:24.211  2154  2154 D c       : Getting all permits...
08-23 08:45:24.211  2154  2154 D a       : Opening database...
08-23 08:45:24.214  6865  6865 D DockEventReceiver: finishStartingService: stopping service
08-23 08:45:24.214  2154  2154 D a       : Opening database auth.proximity.permit_store...
08-23 08:45:24.215  6865  6865 D BluetoothPbap: Proxy object connected
08-23 08:45:24.215  2154  2154 D a       : Closing database...
08-23 08:45:24.216  6865  6865 D PbapServerProfile: Bluetooth service connected
08-23 08:45:24.226  6865  6865 D BluetoothPermissionRequest: onReceive
08-23 08:45:24.228  6865  6865 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-23 08:45:24.231  6865  6865 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 08:45:24.235  6994  6994 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-23 08:45:24.236  6994  6994 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-23 08:45:24.244  6994  6994 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-23 08:45:24.272  6994  6994 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 08:45:24.272  6994  6994 V BtOppService: onCreate
,08-23 08:45:24.277  6994  6994 V BluetoothOppNotification: send message
08-23 08:45:24.280  6994  6994 V BtOppService: Starting RfcommListener
08-23 08:45:24.284  6994  6994 D BluetoothOppPreference: Dumping Names:  
08-23 08:45:24.284  6994  6994 D BluetoothOppPreference: {}
08-23 08:45:24.284  6994  6994 D BluetoothOppPreference: Dumping Channels:  
08-23 08:45:24.284  6994  6994 D BluetoothOppPreference: {}
,08-23 08:45:24.285  6994  6994 V BtOppService: onStartCommand
08-23 08:45:24.290  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:24.290  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 08:45:24.292  6994  7580 V BtOppService: Deleted complete outbound shares, number =  0
08-23 08:45:24.292  6994  7583 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 08:45:24.293  6994  7583 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 08:45:24.294  6994  7580 V BtOppService: Deleted complete inbound failed shares, number = 0
08-23 08:45:24.295  6994  7580 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-23 08:45:24.295  6994  6994 V BluetoothOppNotification: new notify threadi!
08-23 08:45:24.296  6994  6994 V BluetoothOppNotification: send delay message
08-23 08:45:24.297  6994  7580 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ecec051 on behalf of 
08-23 08:45:24.297  6994  7583 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c46c0b6 on behalf of 
,08-23 08:45:24.297  6994  6994 V BtOppService: start RfcommListener
08-23 08:45:24.299  6994  7584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 08:45:24.303  6994  6994 V BtOppService: RfcommListener started
08-23 08:45:24.303  6994  6994 V BtOppService: ContentObserver received notification
08-23 08:45:24.305  6994  7585 V BtOppRfcommListener: Starting RFCOMM listener....
08-23 08:45:24.305  6994  7584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b9bb1b7 on behalf of 
08-23 08:45:24.305  1030  1920 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:24.306  6994  7583 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 08:45:24.306  6994  7583 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 08:45:24.306  6994  7584 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 08:45:24.308  6994  7584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 08:45:24.308  6994  7585 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:24.310  6994  7585 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-23 08:45:24.310  6994  7585 V BtOppRfcommListener: Started RFCOMM listener....
08-23 08:45:24.310  6994  7585 I BtOppRfcommListener: Accept thread started.
08-23 08:45:24.310  6994  7585 V BtOppRfcommListener: Accepting connection...
08-23 08:45:24.310  6994  7583 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bfa9d24 on behalf of 
08-23 08:45:24.311  6994  7583 V BluetoothOppNotification: update too frequent, put in queue
,08-23 08:45:24.312  6994  7584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@236e108d on behalf of 
08-23 08:45:24.313  6994  7584 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 08:45:24.313  6994  7583 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 08:45:24.315  6994  7584 V BluetoothOppNotification: outbound notification was removed.
08-23 08:45:24.315  6994  7584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 08:45:24.316  6994  7584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38f63242 on behalf of 
08-23 08:45:24.317  6994  7584 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 08:45:24.319  6994  7584 V BluetoothOppNotification: inbound notification was removed.
08-23 08:45:24.319  6994  7584 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 08:45:24.321  6994  7584 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@252fb253 on behalf of 
08-23 08:45:24.329  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:24.330  6994  6994 V BluetoothFtpService: Ftp Service onCreate
,08-23 08:45:24.330  6994  6994 I BluetoothFtpService: Ftp Service onCreate
,08-23 08:45:24.330  6994  6994 V BluetoothFtpService: Ftp Service onStartCommand
08-23 08:45:24.330  6994  6994 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:24.330  6994  6994 V BluetoothFtpService: Starting Listening on sockets
08-23 08:45:24.330  6994  6994 V BtOppService: ContentObserver received notification
08-23 08:45:24.331  6994  6994 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 08:45:24.331  6994  6994 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 08:45:24.331  6994  6994 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 08:45:24.331  6994  6994 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:24.331  6994  6994 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-23 08:45:24.331  6994  6994 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-23 08:45:24.332  6994  7586 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 08:45:24.332  6994  7586 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 08:45:24.334  6994  6994 V BluetoothFtpService: Handler(): got msg=1
08-23 08:45:24.334  6994  7586 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4382889 on behalf of 
08-23 08:45:24.334  6994  6994 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-23 08:45:24.335  6994  6994 V BluetoothFtpService: Ftp Service initSocket
08-23 08:45:24.335  6994  7586 V BluetoothOppNotification: update too frequent, put in queue
08-23 08:45:24.336  6994  7586 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 08:45:24.339  1030  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:24.340  6994  6994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:24.341  6994  6994 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-23 08:45:24.341  6994  6994 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-23 08:45:24.343  6994  7587 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-23 08:45:24.362  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:24.362  6994  6994 V BluetoothSapService: Sap Service onCreate
,08-23 08:45:24.366  6994  6994 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:24.366  6994  6994 V BluetoothSapService: state: 12
08-23 08:45:24.367  6994  6994 V BluetoothSapService: Starting SAP server process
08-23 08:45:24.371  6994  6994 V BluetoothSapService: SAP Service startRfcommListenerThread
08-23 08:45:24.361  7589  7589 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:24.361  7589  7589 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:24.374  6994  7590 V BluetoothSapService: Sap Service initRfcommSocket
08-23 08:45:24.376  1030  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:24.378  6994  7590 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 08:45:24.380  6994  7590 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
,08-23 08:45:24.380  6994  7590 V BluetoothSapService: Succeed to create listening socket 
,08-23 08:45:24.380  6994  7590 V BluetoothSapService: Accepting socket connection...
08-23 08:45:24.385  7589  7589 V BT_SAP  : Event pipe created
,08-23 08:45:24.385  7589  7589 V BT_SAP  : create_server_socket qcom.sap.server
08-23 08:45:24.385  7589  7589 V BT_SAP  : created socket fd 6
08-23 08:45:24.910  1030  1515 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-23 08:45:24.911  1030  1515 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
,08-23 08:45:24.965  1030  1517 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-23 08:45:24.967  1030  1517 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-23 08:45:25.067  1030  2011 I ActivityManager: Killing 7387:com.lge.bnr/1000 (adj 15): empty #17
,08-23 08:45:25.107  1030  1920 W libprocessgroup: failed to open /acct/uid_1000/pid_7387/cgroup.procs: No such file or directory
,08-23 08:45:25.298  6994  6994 V BluetoothOppNotification: new notify threadi!
,08-23 08:45:25.298  6994  6994 V BluetoothOppNotification: send delay message
,08-23 08:45:25.311  6994  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-23 08:45:25.313  6994  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b71c445 on behalf of 
08-23 08:45:25.315  6994  7600 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 08:45:25.320  6994  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-23 08:45:25.326  6994  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b9bc79a on behalf of 
08-23 08:45:25.327  6994  7600 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 08:45:25.330  6994  7600 V BluetoothOppNotification: outbound notification was removed.
08-23 08:45:25.330  6994  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 08:45:25.331  6994  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@334118cb on behalf of 
08-23 08:45:25.332  6994  7600 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 08:45:25.334  6994  7600 V BluetoothOppNotification: inbound notification was removed.
08-23 08:45:25.334  6994  7600 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 08:45:25.335  6994  7600 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@204798a8 on behalf of 
,08-23 08:45:25.397  1030  2006 I ActivityManager: Killing 6627:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-23 08:45:25.424  6917  6917 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-23 08:45:25.424  6917  6917 W System.err: android.os.DeadObjectException
08-23 08:45:25.425  6917  6917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 08:45:25.425  6917  6917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 08:45:25.425  6917  6917 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-23 08:45:25.425  6917  6917 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-23 08:45:25.425  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-23 08:45:25.425  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-23 08:45:25.425  6917  6917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 08:45:25.425  6917  6917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-23 08:45:25.429  6917  6917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 08:45:25.429  6917  6917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 08:45:25.430  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:45:25.430  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:45:25.430  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 08:45:25.430  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 08:45:25.430  6917  6917 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-23 08:45:25.431  6917  6917 W System.err: android.os.DeadObjectException
08-23 08:45:25.431  6917  6917 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 08:45:25.431  6917  6917 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 08:45:25.431  6917  6917 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-23 08:45:25.431  6917  6917 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-23 08:45:25.431  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-23 08:45:25.431  6917  6917 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-23 08:45:25.431  6917  6917 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 08:45:25.431  6917  6917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 08:45:25.431  6917  6917 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 08:45:25.431  6917  6917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 08:45:25.431  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:45:25.431  6917  6917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:45:25.431  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 08:45:25.431  6917  6917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 08:45:25.431  6917  6917 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-23 08:45:25.432  6917  6917 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-23 08:45:25.460  1030  2011 W libprocessgroup: failed to open /acct/uid_1000/pid_6627/cgroup.procs: No such file or directory
08-23 08:45:25.461  1030  2011 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-23 08:45:25.470  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-23 08:45:25.470  6917  6917 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-23 08:45:25.512  1030  1901 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7601 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 08:45:25.513  6917  6917 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-23 08:45:25.603  7601  7601 D UEI.SmartControl: Quickset Services start...
08-23 08:45:25.605  7601  7601 I UEI.SmartControl: Manufacture = LGE
08-23 08:45:25.605  7601  7601 D UEI.SmartControl: Id = LGNevo
,08-23 08:45:25.609  7601  7601 D UEI.SmartControl: File observer start...
08-23 08:45:25.610  7601  7601 E UEI.SmartControl: IR Port is disabled: false
08-23 08:45:25.610  7601  7601 D UEI.SmartControl: Starting file observer...
08-23 08:45:25.611  7601  7601 D UEI.SmartControl: Extracting JNI libs...
08-23 08:45:25.611  7601  7601 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-23 08:45:25.721  7601  7601 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-23 08:45:25.721  7601  7601 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-23 08:45:25.722  7601  7601 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-23 08:45:25.763  7601  7601 I UEI.SmartControl: --- Selecting new region: 6
,08-23 08:45:25.766  7601  7601 I UEI.SmartControl: Model = LG-D855
08-23 08:45:25.768  7601  7601 D UEI.SmartControl: QS Service created
08-23 08:45:25.786  7601  7601 I UEI.SmartControl: Service initServices...
,08-23 08:45:25.791  7601  7601 D UEI.SmartControl: QS start get config
08-23 08:45:25.857  7601  7601 D UEI.SmartControl: Loading JNI Libs...
,08-23 08:45:25.908  1030  1678 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:25.908  1030  1678 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1d68172a mBinding = false
,08-23 08:45:25.930  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 08:45:25.931  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 08:45:25.931  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-23 08:45:25.932  1030  1113 D BluetoothManagerService: Message: 2
08-23 08:45:25.934  1030  1113 D BluetoothManagerService: Sending off request.
08-23 08:45:25.935  6994  7567 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-23 08:45:25.936  6994  7462 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-23 08:45:25.936  6994  7462 D BluetoothAdapterProperties: Setting state to 13
08-23 08:45:25.936  6994  7462 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 08:45:25.947  6994  7462 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 08:45:25.947  6994  7462 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-23 08:45:25.951  6994  7466 D BluetoothAdapterProperties: Scan Mode:20
08-23 08:45:25.952  6994  7462 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-23 08:45:25.954  6994  7462 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-23 08:45:25.957  6994  7569 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-23 08:45:25.957  6994  7569 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:25.957  6994  7569 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-23 08:45:25.957  6994  7569 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-23 08:45:25.957  6994  7569 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-23 08:45:25.957  6994  7569 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-23 08:45:25.957  6994  7569 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-23 08:45:25.957  6994  7569 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-23 08:45:25.958  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-23 08:45:25.960  6994  7585 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:25.960  6994  7531 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-23 08:45:25.961  6994  7590 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:25.961  6994  7587 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:25.962  6994  7571 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 08:45:25.963  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-23 08:45:25.964  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-23 08:45:25.964  6994  7531 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 08:45:25.967  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:25.967  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:25.967  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:25.967  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:25.967  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:25.967  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:25.967  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:25.967  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:25.967  6716  6716 V io.,jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:45:25.969  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:25.969  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:25.971  1030  1113 D BluetoothManagerService: Message: 60
08-23 08:45:25.971  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-23 08:45:25.971  1030  1113 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-23 08:45:25.973  1921  1921 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:25.974  6865  6865 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-23 08:45:25.974  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:25.975  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:25.975  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:25.975  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:25.975  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:25.975  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 08:45:25.975  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:25.975  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:25.975  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:25.975  1583  1583 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 08:45:25.975  6716  6716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 08:45:25.975  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:25.975  6994  6994 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:25.975  6994  6994 D BluetoothMapService: STATE_TURNING_OFF
08-23 08:45:25.976  6994  6994 V BtOppService: Receiver DISABLED_ACTION 
08-23 08:45:25.976  6994  6994 V BluetoothMapService: Handler(): got msg=4
08-23 08:45:25.976  6994  6994 D BluetoothMapService: MAP Service closeService in
08-23 08:45:25.976  6994  6994 D BluetoothMapMasInstance: MAP Service shutdown
08-23 08:45:25.976  6994  6994 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 08:45:25.976  6994  6994 V BluetoothMapService: MAP Service closeService out
08-23 08:45:25.976  6994  6994 I BtOppRfcommListener: stopping Accept Thread
08-23 08:45:25.976  6994  6994 V BtOppRfcommListener: close mBtServerSocket
08-23 08:45:25.976  6994  6994 V BtOppRfcommListener: waiting for thread to terminate
08-23 08:45:25.977  6994  7585 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 08:45:25.977  6994  6994 V BtOppRfcommListener: done waiting for thread to terminate
08-23 08:45:25.979  6865  6865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-23 08:45:25.982  6994  6994 V BtOppService: onDestroy
08-23 08:45:25.983  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:25.984  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:25.985  6994  6994 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-23 08:45:25.988  6865  6865 D DockEventReceiver: finishStartingService: stopping service
08-23 08:45:25.988  6994  6994 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 08:45:25.988  6994  6994 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:25.988  6994  6994 V BluetoothPbapReceiver: ***********state = 13
08-23 08:45:25.990  6994  6994 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-23 08:45:25.990  6994  6994 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:25.990  6994  6994 V BluetoothPbapService: state: 13
08-23 08:45:25.991  6994  6994 V BluetoothPbapService: Pbap Service closeService in
,08-23 08:45:25.993  6994  6994 V BluetoothPbapService: successfully stopped pbap service
08-23 08:45:25.993  6994  6994 V BluetoothPbapService: Pbap Service closeService out
08-23 08:45:25.993  6994  6994 V BluetoothPbapService: Pbap Service onDestroy
08-23 08:45:25.994  6994  6994 V BluetoothPbapService: Pbap Service closeService in
08-23 08:45:25.994  6994  6994 V BluetoothPbapService: Pbap Service closeService out
08-23 08:45:25.994  6994  6994 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-23 08:45:25.994  6865  6865 D BluetoothPbap: Proxy object disconnected
08-23 08:45:25.994  6865  6865 D PbapServerProfile: Bluetooth service disconnected
08-23 08:45:26.004  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 08:45:26.014  6865  6865 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-23 08:45:26.020  6865  6865 D BluetoothPermissionRequest: onReceive
08-23 08:45:26.020  6865  6865 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-23 08:45:26.024  6865  6865 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 08:45:26.026  6994  6994 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-23 08:45:26.026  6994  6994 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-23 08:45:26.027  6994  6994 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-23 08:45:26.030  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:26.031  6994  6994 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 08:45:26.033  6994  6994 V BluetoothFtpService: Ftp Service onStartCommand
08-23 08:45:26.033  6994  6994 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:26.033  6994  6994 V BluetoothFtpService: Ftp Service closeService
08-23 08:45:26.033  6994  6994 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-23 08:45:26.034  6994  6994 V BluetoothFtpService: successfully stopped ftp service
08-23 08:45:26.035  6994  6994 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 08:45:26.035  6994  6994 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 08:45:26.035  6994  6994 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 08:45:26.035  6994  6994 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:26.035  6994  6994 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-23 08:45:26.035  6994  6994 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-23 08:45:26.037  6994  6994 V BluetoothFtpService: Ftp Service onDestroy
08-23 08:45:26.037  6994  6994 V BluetoothFtpService: Ftp Service closeService
08-23 08:45:26.037  6994  6994 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:26.037  6994  6994 V BluetoothSapService: state: 13
08-23 08:45:26.037  6994  6994 V BluetoothSapService: Stopping SAP server process
08-23 08:45:26.038  6994  6994 V BluetoothSapService: Sap Service closeSapService in
08-23 08:45:26.038  6994  6994 V BluetoothSapService: Close listen Socket : 
08-23 08:45:26.039  6994  6994 V BluetoothSapService: Close rfcomm Socket : 
08-23 08:45:26.039  6994  6994 V BluetoothSapService: Close sapd  Socket : 
08-23 08:45:26.039  6994  6994 V BluetoothSapService: Sap Service closeSapService out
08-23 08:45:26.039  6994  6994 V BluetoothSapService: Sap Service onDestroy
08-23 08:45:26.039  6994  6994 V BluetoothSapService: Sap Service closeSapService in
08-23 08:45:26.039  6994  6994 V BluetoothSapService: Close listen Socket : 
08-23 08:45:26.039  6994  6994 V BluetoothSapService: Close rfcomm Socket : 
08-23 08:45:26.039  6994  6994 V BluetoothSapService: Close sapd  Socket : 
08-23 08:45:26.043  6994  6994 V BluetoothSapService: Sap Service closeSapService out
,08-23 08:45:26.161  7601  7601 I UEI.SmartControl: Supports setup maps: true
,08-23 08:45:26.169  7601  7601 D UEI.SmartControl: QS start statue = true Error code = 0
08-23 08:45:26.170  7601  7601 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-23 08:45:26.170  7601  7601 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-23 08:45:26.170  7601  7601 I UEI.SmartControl: ### init IR Blaster...
08-23 08:45:26.179  7601  7601 D serial_port: Configuring serial port
,08-23 08:45:26.188  7601  7601 E UEI.SmartControl: UEIBLaster setting for 616
,08-23 08:45:26.188  7601  7601 I UEI.SmartControl: Setting serial record hearder size = 2
08-23 08:45:26.189  7601  7601 I UEI.SmartControl: configuring settings for MAXQ616
08-23 08:45:26.189  7601  7601 I UEI.SmartControl: Get version...
08-23 08:45:26.206  7601  7646 D UEI.SmartControl: serial port data available: 21
,08-23 08:45:26.236  7601  7601 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-23 08:45:26.236  7601  7601 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-23 08:45:26.237  7601  7601 I UEI.SmartControl: QS saving settings...
08-23 08:45:26.240  7601  7601 D UEI.SmartControl: IR Blaster version: 25672567
,08-23 08:45:26.257  7601  7646 D UEI.SmartControl: serial port data available: 4
,08-23 08:45:26.299  7601  7650 I UEI.SmartControl: Device manager: loading config....
08-23 08:45:26.300  7601  7650 D UEI.SmartControl: ----------- loading internal config...
,08-23 08:45:26.301  7601  7601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-23 08:45:26.312  7601  7601 E UEI.SmartControl: Services init done
08-23 08:45:26.312  7601  7601 D UEI.SmartControl: QS Service init finished
08-23 08:45:26.317  7601  7601 D UEI.SmartControl: QS Service version name: 2.1.91
08-23 08:45:26.318  7601  7601 D UEI.SmartControl: QS Service version code: 201091
08-23 08:45:26.321  7601  7601 D UEI.SmartControl: Service requested: Control
,08-23 08:45:26.331  7601  7650 E UEI.SmartControl: Loading SETTINGS...
,08-23 08:45:26.332  7601  7601 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-23 08:45:26.338  6917  6917 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-23 08:45:26.340  7601  7617 I UEI.SmartControl: ------ IControl API: 11
08-23 08:45:26.344  1030  1052 I ActivityManager: Killing 6917:com.lge.qremote/u0a112 (adj 15): empty #17
08-23 08:45:26.344  7601  7617 I UEI.SmartControl: Registering callback...
08-23 08:45:26.353  7601  7650 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-23 08:45:26.374  7601  7649 I UEI.SmartControl: Notify AllClients services are ready: 0
08-23 08:45:26.374  7601  7649 D UEI.SmartControl: -----service ready thread exits
,08-23 08:45:26.407  7601  7601 D UEI.SmartControl: Internal service binding...
08-23 08:45:26.407  1030  1974 W libprocessgroup: failed to open /acct/uid_10112/pid_6917/cgroup.procs: No such file or directory
,08-23 08:45:26.872  6994  7466 D bt_hci_bdroid: cleanup
,08-23 08:45:26.881  6994  7557 I bt_userial_mct: exiting userial_read_thread
08-23 08:45:26.882  6994  7533 I bt_lpm  : LPM is already off!!!
08-23 08:45:26.883  6994  7531 W bt-btif : ag scb idx 1 not allocated
08-23 08:45:26.885  6994  7531 E bt-btif : BTA AG is already disabled, ignoring ...
08-23 08:45:26.887  6994  7557 D bt_userial_mct: Leaving userial_evt_read_thread()
08-23 08:45:26.888  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:26.888  6994  7531 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:45:26.888  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:26.888  6994  7531 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:45:26.888  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:26.888  6994  7531 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 08:45:26.888  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:26.888  6994  7531 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:45:26.889  6994  7466 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-23 08:45:26.889  6994  7533 I bt_vendor: hw_epilog_process
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-23 08:45:26.889  6994  7531 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-23 08:45:26.890  6994  7531 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-23 08:45:26.890  6994  7466 D bt_hci_bdroid: cleanup Finalizing cleanup
08-23 08:45:26.890  6994  7466 D bt_userial_mct: userial_close
08-23 08:45:26.890  6994  7466 E bt_userial_mct: pthread_join() FAILED result:3
08-23 08:45:26.890  6994  7466 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-23 08:45:26.898  6994  7466 D bt_hci_bdroid: set_power 0
08-23 08:45:26.898  6994  7466 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-23 08:45:26.898  6994  7466 I bt_vendor: bluetooth satus is on
08-23 08:45:26.898  6994  7466 I bt_vendor: bt-vendor : resetting BT status
08-23 08:45:26.898  6994  7466 I bt_vendor: Starting hciattach daemon
08-23 08:45:26.898  6994  7466 I bt_vendor: try to set false
,08-23 08:45:26.904  6994  7466 I bt_vendor: Starting hciattach daemon
08-23 08:45:26.904  6994  7466 I bt_vendor: try to set false
08-23 08:45:26.906  6994  7466 I bt_vendor: cleanup
08-23 08:45:26.906  6994  7531 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-23 08:45:26.907  6994  7466 I GKI_LINUX: GKI_exit_task 0 done
08-23 08:45:26.907  6994  7466 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-23 08:45:26.909  6994  7462 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-23 08:45:26.916  6994  6994 D HeadsetService: Received stop request...Stopping profile...
,08-23 08:45:26.920  6994  6994 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 08:45:26.920  6994  6994 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 08:45:26.921  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:26.921  6994  7492 D HeadsetStateMachine: Exit Disconnected: -1
08-23 08:45:26.924  1030  1030 D BluetoothHeadset: Proxy object disconnected
08-23 08:45:26.924  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-23 08:45:26.927  6994  7462 D BluetoothAdapterState: Stopping profile services that were post enabled
08-23 08:45:26.927  6994  6994 D A2dpService: Received stop request...Stopping profile...
08-23 08:45:26.928  6994  7518 D A2dpStateMachine: Exit Disconnected: -1
08-23 08:45:26.930  1832  1832 D BluetoothHeadset: Proxy object disconnected
08-23 08:45:26.930  1832  1832 D BluetoothHeadset: Proxy object disconnected
08-23 08:45:26.930  1832  1832 D BluetoothHeadset: Proxy object disconnected
,08-23 08:45:26.933  6994  6994 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-23 08:45:26.934  6994  6994 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-23 08:45:26.934  6994  6994 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 08:45:26.934  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:26.936  1030  1030 D BluetoothA2dp: Proxy object disconnected
08-23 08:45:26.936  1030  1030 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-23 08:45:26.937  6994  6994 D HidService: Received stop request...Stopping profile...
08-23 08:45:26.937  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:26.939  6994  6994 D HealthService: Received stop request...Stopping profile...
08-23 08:45:26.939  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:26.943  6994  6994 D PanService: Received stop request...Stopping profile...
,08-23 08:45:26.946  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:26.947  6994  6994 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 08:45:26.948  6994  6994 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 08:45:26.948  6994  6994 D BtGatt.GattService: stop()
08-23 08:45:26.948  6994  6994 D BtGatt.AdvertiseManager: advertise clients cleared
08-23 08:45:26.949  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:26.950  6994  6994 D HeadsetStateMachine: Unbinding service...
08-23 08:45:26.951  6994  6994 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 08:45:26.951  6994  6994 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 08:45:26.951  6994  6994 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 08:45:26.951  6994  6994 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 08:45:26.951  6994  6994 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 08:45:26.951  6994  6994 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 08:45:26.951  6994  6994 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-23 08:45:26.954  6994  6994 D BluetoothMapService: Received stop request...Stopping profile...
08-23 08:45:26.954  6994  6994 D BluetoothMapService: stop()
08-23 08:45:26.954  6994  6994 D BluetoothMapEmailAppObserver: deinitObservers()
08-23 08:45:26.955  6994  6994 D BluetoothMapEmailAppObserver: removeReceiver()
,08-23 08:45:26.958  6994  6994 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@72a63fc
08-23 08:45:26.959  6994  6994 I BluetoothA2dpServiceJni: cleanupNative
08-23 08:45:26.959  6994  7519 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-23 08:45:26.960  6994  6994 I GKI_LINUX: GKI_exit_task 2 done
08-23 08:45:26.960  6994  6994 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-23 08:45:26.960  6994  6994 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 08:45:26.960  6994  6994 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 08:45:26.960  6994  6994 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 08:45:26.961  6994  6994 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 08:45:26.961  6994  6994 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 08:45:26.961  6994  6994 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 08:45:26.961  6994  6994 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 08:45:26.964  6994  6994 V BluetoothMapService: Handler(): got msg=4
08-23 08:45:26.964  6994  6994 D BluetoothMapService: MAP Service closeService in
08-23 08:45:26.964  6994  6994 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 08:45:26.964  6994  6994 V BluetoothMapService: MAP Service closeService out
08-23 08:45:26.966  6994  7462 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-23 08:45:26.966  6994  7462 D BluetoothAdapterProperties: Setting state to 10
08-23 08:45:26.966  6994  7462 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-23 08:45:26.970  6994  6994 D BluetoothMapService: cleanup()
08-23 08:45:26.970  6994  6994 D BluetoothMapService: MAP Service closeService in
08-23 08:45:26.970  6994  6994 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-23 08:45:26.970  6994  6994 V BluetoothMapService: MAP Service closeService out
08-23 08:45:26.971  1030  1113 D BluetoothManagerService: Message: 60
08-23 08:45:26.972  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-23 08:45:26.972  1030  1113 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-23 08:45:26.973  6994  7462 I BluetoothAdapterState: Entering OffState
08-23 08:45:26.973  6865  7561 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 08:45:26.974  1832  1847 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 08:45:26.975  6865  7561 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 08:45:26.976  1832  1848 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 08:45:26.976  6865  7561 D BluetoothMap: onBluetoothStateChange: up=false
08-23 08:45:26.978  6865  7561 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 08:45:26.980  1030  1113 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 08:45:26.981  1832  2610 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 08:45:26.981  1030  1113 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 08:45:26.982  6865  7561 D BluetoothPan: onBluetoothStateChange on: false
08-23 08:45:26.982  6865  7561 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 08:45:26.983  1030  1113 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-23 08:45:26.983  1030  1113 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-23 08:45:26.985  1030  1113 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-23 08:45:26.985  1030  1113 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-23 08:45:26.985  1030  1113 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1d68172a mBinding = false
08-23 08:45:26.986  1030  1113 D BluetoothManagerService: Sending unbind request.
08-23 08:45:26.990  6994  7466 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-23 08:45:26.993  6994  6994 I GKI_LINUX: GKI_exit_task 1 done
08-23 08:45:26.993  6994  6994 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-23 08:45:26.994  6994  6994 I BluetoothServiceJni: cleanupNative: return from cleanup
08-23 08:45:26.994  6994  6994 I art     : --- WEIRD: removing null entry 248
08-23 08:45:26.994  6994  6994 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-23 08:45:26.994  6994  6994 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-23 08:45:26.995  6994  6994 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-23 08:45:26.997  1030  1113 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-23 08:45:26.999  6994  6994 I art     : System.exit called, status: 0
08-23 08:45:26.999  6994  6994 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-23 08:45:27.018   313  1363 V AudioFlinger: 6994 died, releasing its sessions
08-23 08:45:27.018   313  1363 V AudioFlinger:  pid 1832 @ 0
08-23 08:45:27.018   313  1363 V AudioFlinger:  pid 3282 @ 1
08-23 08:45:27.018   313  1363 V AudioFlinger:  pid 3282 @ 2
,08-23 08:45:27.022  1921  1921 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-23 08:45:27.022  1921  2059 D LGBluetoothAPIService: Message: 101
08-23 08:45:27.023  1921  2059 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-23 08:45:27.023  1921  2059 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-23 08:45:27.023  1921  2059 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-23 08:45:27.030  6865  6865 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-23 08:45:27.055  1030  1052 I ActivityManager: Process com.android.bluetooth (pid 6994) has died
08-23 08:45:27.056  1030  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-23 08:45:27.056  1030  1052 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-23 08:45:27.065  1921  1921 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:27.065  1921  2059 D LGBluetoothAPIService: Message: 2
08-23 08:45:27.065  1921  2059 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-23 08:45:27.066  1583  1583 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 08:45:27.066  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:27.068  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:27.070  6865  6865 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-23 08:45:27.070  6865  6865 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-23 08:45:27.071  1583  1583 D BluetoothAdapter: 974704999: getState() :  mService = null. Returning STATE_OFF
08-23 08:45:27.071  1583  1583 D BluetoothAdapter: 974704999: getState() :  mService = null. Returning STATE_OFF
08-23 08:45:27.076  6865  6865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 08:45:27.124  1030  1555 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7682 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-23 08:45:27.126  6865  6865 D DockEventReceiver: finishStartingService: stopping service
,08-23 08:45:27.181  7682  7682 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-23 08:45:27.182  7682  7682 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 08:45:27.182  7682  7682 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-23 08:45:27.183  7682  7682 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 08:45:27.202  7682  7682 D BluetoothAdapterApp: Loading JNI Library
,08-23 08:45:27.238  7682  7682 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@12cfec64 Instance Count = 1
,08-23 08:45:27.245  7682  7682 D BluetoothAdapterApp: onCreate
,08-23 08:45:27.272  7682  7682 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-23 08:45:27.272  7682  7682 D ProfileConfigQcom: Adding HeadsetService
,08-23 08:45:27.272  7682  7682 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-23 08:45:27.272  7682  7682 D ProfileConfigQcom: Adding A2dpService
08-23 08:45:27.273  7682  7682 D ProfileConfigQcom: [BTUI] HidService is supported
08-23 08:45:27.273  7682  7682 D ProfileConfigQcom: Adding HidService
08-23 08:45:27.273  7682  7682 D ProfileConfigQcom: [BTUI] HealthService is supported
08-23 08:45:27.273  7682  7682 D ProfileConfigQcom: Adding HealthService
08-23 08:45:27.274  7682  7682 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-23 08:45:27.275  7682  7682 D ProfileConfigQcom: [BTUI] PanService is supported
08-23 08:45:27.275  7682  7682 D ProfileConfigQcom: Adding PanService
,08-23 08:45:27.275  7682  7682 D ProfileConfigQcom: [BTUI] GattService is supported
08-23 08:45:27.276  7682  7682 D ProfileConfigQcom: Adding GattService
08-23 08:45:27.276  7682  7682 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-23 08:45:27.276  7682  7682 D ProfileConfigQcom: Adding BluetoothMapService
08-23 08:45:27.277  7682  7682 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-23 08:45:27.278  7682  7682 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 08:45:27.279  7682  7682 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:45:27.280  7682  7682 V BluetoothPbapReceiver: ***********state = 10
08-23 08:45:27.282  7682  7682 V LGMDMManagerInternal: Create singleton instance
08-23 08:45:27.378  6865  6865 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-23 08:45:27.385  7682  7682 D LGBluetoothAPIServer: [BTUI] onCreate()
08-23 08:45:27.386  7682  7682 D LGBluetoothAPIServer: [BTUI] onBind()
08-23 08:45:27.388  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 08:45:27.392  1921  1921 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-23 08:45:27.394  1921  2059 D LGBluetoothAPIService: Message: 100
08-23 08:45:27.394  1921  2059 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-23 08:45:27.407  6865  6865 D BluetoothPermissionRequest: onReceive
,08-23 08:45:27.411  6865  6865 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 08:45:27.411  6865  6865 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-23 08:45:27.415  6865  6865 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 08:45:27.420  7682  7682 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-23 08:45:27.428  7682  7682 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:27.433  7682  7682 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 08:45:27.433  7682  7682 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 08:45:27.433  7682  7682 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 08:45:27.435  7682  7682 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:45:27.435  7682  7682 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-23 08:45:27.442  6934  6934 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-23 08:45:28.940  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:28.940  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:45:28.948  1030  1407 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 08:45:28.959  1583  1583 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-23 08:45:29.054  1030  1105 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7710 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-23 08:45:29.061  1583  1583 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-23 08:45:29.062  1583  1583 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-23 08:45:29.073  1030  1030 D administrator: Handling package changes for user 0
,08-23 08:45:29.095  2012  2012 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-23 08:45:29.166  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 08:45:29.166  7710  7710 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-23 08:45:29.223  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-23 08:45:29.223  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-23 08:45:29.257  7710  7710 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:29.258  7710  7710 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 08:45:29.307  1030  1103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 08:45:29.313  1030  1103 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-23 08:45:29.320  2012  2012 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-23 08:45:29.321  2488  2488 V GmsNetworkLocationProvi: DISABLE
08-23 08:45:29.344  1030  1103 D LocationProviderProxy: applying state to connected service
08-23 08:45:29.344  2488  2488 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-23 08:45:29.357  7710  7754 I Babel   : MmsConfig: mnc/mcc: 0/0
08-23 08:45:29.357  7710  7754 I Babel   : MmsConfig.loadMmsSettings
,08-23 08:45:29.361  7710  7754 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-23 08:45:29.361  7710  7754 I Babel   : MmsConfig.loadFromDatabase
,08-23 08:45:29.378  7710  7754 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-23 08:45:29.378  7710  7754 I Babel   : MmsConfig.loadFromResources
08-23 08:45:29.380  7710  7754 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-23 08:45:29.381  7710  7754 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-23 08:45:29.388  7710  7710 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 08:45:29.393  7710  7753 W AudioCapabilities: Unsupported mime audio/evrc
08-23 08:45:29.394  7710  7753 W AudioCapabilities: Unsupported mime audio/qcelp
08-23 08:45:29.399  7710  7753 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-23 08:45:29.405  7710  7753 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-23 08:45:29.406  7710  7753 W AudioCapabilities: Unsupported mime audio/qcelp
08-23 08:45:29.407  7710  7753 W AudioCapabilities: Unsupported mime audio/evrc
08-23 08:45:29.422  1796  7757 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-23 08:45:29.422  1796  7757 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-23 08:45:29.427  7056  7056 I AppUp4:CustModeStarterReceiver: onReceive
08-23 08:45:29.430  7710  7753 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-23 08:45:29.431  1796  5183 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-23 08:45:29.431  7056  7056 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@9a205ce
08-23 08:45:29.431  7056  7056 D AppUp4:CustFacade: isCustomizationCompleted : false
08-23 08:45:29.431  7056  7056 D AppUp4:CustFacade: isPhone : true
,08-23 08:45:29.432  7056  7056 D AppUp4:CustModeStarterReceiver: begin check event
08-23 08:45:29.432  7056  7056 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-23 08:45:29.436  7710  7753 W VideoCapabilities: Unsupported mime video/divx
08-23 08:45:29.437  7710  7753 W VideoCapabilities: Unsupported mime video/divx311
08-23 08:45:29.439  7710  7753 W VideoCapabilities: Unsupported mime video/divx4
08-23 08:45:29.445  7710  7753 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-23 08:45:29.468  7710  7753 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-23 08:45:29.477  7710  7753 W AudioCapabilities: Unsupported mime audio/eac3
,08-23 08:45:29.479  7710  7753 W AudioCapabilities: Unsupported mime audio/ac3
08-23 08:45:29.485  1030  2029 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7761 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-23 08:45:29.496   348   348 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 300us total 13.791ms
,08-23 08:45:29.498  1030  1919 I ActivityManager: Killing 6886:com.lge.sync/1000 (adj 15): empty #17
08-23 08:45:29.506  7710  7753 W AudioCapabilities: Unsupported mime audio/g726
08-23 08:45:29.509   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 12.911ms
08-23 08:45:29.512  1030  1522 D WifiService: Client connection lost with reason: 4
08-23 08:45:29.512  7710  7753 W AudioCapabilities: Unsupported mime audio/wma-voice
,08-23 08:45:29.513  7710  7753 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-23 08:45:29.514  7710  7753 W AudioCapabilities: Unsupported mime audio/adpcm
08-23 08:45:29.517  7710  7753 W VideoCapabilities: Unsupported mime video/theora
08-23 08:45:29.519  7710  7753 W VideoCapabilities: Unsupported mime video/mjpg
08-23 08:45:29.522   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 258us total 11.814ms
,08-23 08:45:29.576  1030  1938 W libprocessgroup: failed to open /acct/uid_1000/pid_6886/cgroup.procs: No such file or directory
,08-23 08:45:29.616  7761  7761 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 08:45:29.617  7761  7761 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 08:45:29.617  7761  7761 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 08:45:29.619  7761  7761 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-23 08:45:29.619  7761  7761 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 08:45:29.681  7761  7761 I SystemConfig: BUILD Country: EU
08-23 08:45:29.682  7761  7761 I SystemConfig: BUILD Operator: OPEN
,08-23 08:45:29.719  1030  1762 I ActivityManager: Killing 7094:com.lge.email/u0a23 (adj 15): empty #17
,08-23 08:45:29.808  1030  1920 W libprocessgroup: failed to open /acct/uid_10023/pid_7094/cgroup.procs: No such file or directory
,08-23 08:45:29.819  7761  7779 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-23 08:45:29.820  7761  7779 I SystemConfig: existFile = false
08-23 08:45:29.820  7761  7779 I SystemConfig: canReadFile = false
08-23 08:45:29.820  7761  7779 I SystemConfig: systemFeature RCS result false
08-23 08:45:29.820  7761  7779 D SystemConfig: refreshRcsSupport() :false
,08-23 08:45:29.870  1030  1555 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7781 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-23 08:45:29.944  7781  7781 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 08:45:29.944  7781  7781 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 08:45:29.945  7781  7781 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 08:45:29.945  7781  7781 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 08:45:29.990  1030  1523 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-23 08:45:30.034  7781  7781 I AppConfig: Total System Memory = 2995761152
,08-23 08:45:30.042  7781  7781 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-23 08:45:30.147  1030  1974 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7800 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 08:45:30.151  1030  1974 I ActivityManager: Killing 6964:com.lge.formmanager/u0a26 (adj 15): empty #17
08-23 08:45:30.199  1030  1901 W libprocessgroup: failed to open /acct/uid_10026/pid_6964/cgroup.procs: No such file or directory
,08-23 08:45:30.394  7800  7800 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-23 08:45:30.500  7800  7800 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:30.500  7800  7800 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 08:45:30.557  7800  7800 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-23 08:45:30.582  7800  7800 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 08:45:30.583  7800  7800 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 08:45:30.600  7800  7800 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 08:45:30.600  7800  7800 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-23 08:45:30.620  1030  2029 I ActivityManager: Killing 6370:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-23 08:45:30.650  1030  1762 W libprocessgroup: failed to open /acct/uid_1000/pid_6370/cgroup.procs: No such file or directory
,08-23 08:45:30.653  2863  2882 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-23 08:45:30.654  2863  2882 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e508092 on behalf of 7800
08-23 08:45:30.662  5031  7840 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-23 08:45:30.731  1030  1920 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7841 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-23 08:45:30.753  7800  7800 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-23 08:45:30.785  7800  7800 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-23 08:45:30.843  7841  7841 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-23 08:45:30.869  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-23 08:45:30.869  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-23 08:45:30.869  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-23 08:45:30.869  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-23 08:45:30.869  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-23 08:45:30.869  7841  7841 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-23 08:45:30.889  1030  1938 I ActivityManager: Killing 7136:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-23 08:45:30.920  1030  2029 W libprocessgroup: failed to open /acct/uid_10046/pid_7136/cgroup.procs: No such file or directory
,08-23 08:45:31.084  1030  2029 V SIM_STK : Menu title from STK is T-Mobile
,08-23 08:45:31.125  5031  7840 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 463 ms] updated apps [took 463 ms] 
,08-23 08:45:31.298  7601  7651 D UEI.SmartControl: Internal timer expired: 1
,08-23 08:45:31.299  7601  7651 D UEI.SmartControl: unbind internal service
,08-23 08:45:31.317  7601  7601 D UEI.SmartControl: Service.onUnbind: IControl
,08-23 08:45:31.320  7601  7601 D UEI.SmartControl: Service.onDestroy
08-23 08:45:31.320  7601  7601 D UEI.SmartControl: Lock is in USE false
08-23 08:45:31.320  7601  7601 D UEI.SmartControl: unbind internal service
08-23 08:45:31.321  7601  7601 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1dcb0da
08-23 08:45:31.321  7601  7601 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-23 08:45:31.321  7601  7601 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-23 08:45:31.321  7601  7601 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-23 08:45:31.321  7601  7601 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-23 08:45:31.321  7601  7601 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-23 08:45:31.321  7601  7601 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-23 08:45:31.321  7601  7601 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-23 08:45:31.321  7601  7601 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-23 08:45:31.321  7601  7601 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:45:31.321  7601  7601 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 08:45:31.321  7601  7601 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 08:45:31.322  7601  7601 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:45:31.322  7601  7601 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:45:31.322  7601  7601 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 08:45:31.322  7601  7601 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 08:45:31.322  7601  7601 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@1dcb0da
08-23 08:45:31.324  7601  7601 D serial_port: close(fd = 25)
08-23 08:45:31.328  7601  7601 I UEI.SmartControl: Serial port is closed.
08-23 08:45:31.328  7601  7601 I UEI.SmartControl: Serial port is closed.
08-23 08:45:31.328  7601  7601 D UEI.SmartControl: Blaster closed
08-23 08:45:31.328  7601  7601 D UEI.SmartControl: Shut down QS...
08-23 08:45:31.328  7601  7601 D UEI.SmartControl: Stopping QS lib
08-23 08:45:31.328  7601  7601 D UEI.SmartControl: QS lib stop result = true
08-23 08:45:31.328  7601  7601 D UEI.SmartControl: Stopped QS lib
08-23 08:45:31.329  7601  7601 D UEI.SmartControl: Stopped file observer...
08-23 08:45:31.329  7601  7601 D UEI.SmartControl: QS shutdown complete
,08-23 08:45:32.064  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 08:45:32.064  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f792530 added. We now have 6 listener(s)
08-23 08:45:32.064  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:45:32.078  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:32.078  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2309a5a9 added. We now have 7 listener(s)
08-23 08:45:32.078  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:32.079  6716  6818 I System.out: IsBluetoothEnabled
08-23 08:45:32.081  1030  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:32.081  1030  1053 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-23 08:45:32.081  1030  1113 D BluetoothManagerService: Message: 2
08-23 08:45:32.084  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:45:32.087  1030  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:32.087  1030  1938 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-23 08:45:32.105  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-23 08:45:32.106  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 08:45:32.106  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-23 08:45:32.107  1030  1113 D BluetoothManagerService: Message: 1
08-23 08:45:32.107  1030  1113 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-23 08:45:32.132  1030  1113 D BluetoothManagerService: Message: 20
08-23 08:45:32.132  1030  1113 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@906189b:true
,08-23 08:45:32.136  7682  7682 D BluetoothAdapterState: make
08-23 08:45:32.141  7682  7682 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-23 08:45:32.142  7682  7682 I bluedroid-qcom: init
08-23 08:45:32.143  7682  7871 I BluetoothAdapterState: Entering OffState
08-23 08:45:32.143  7682  7682 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 08:45:32.143  7682  7682 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 08:45:32.144  7682  7682 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 08:45:32.144  7682  7682 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 08:45:32.144  7682  7682 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-23 08:45:32.145  7682  7682 I bluedroid-qcom: get_profile_interface socket
08-23 08:45:32.146  7682  7682 I bluedroid-qcom: get_profile_interface map_client
,08-23 08:45:32.150  7682  7875 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-23 08:45:32.141  7874  7874 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:32.141  7874  7874 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:32.164  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-23 08:45:32.167  1030  1113 D BluetoothManagerService: Message: 40
08-23 08:45:32.167  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-23 08:45:32.168  7682  7697 I bluedroid-qcom: config_hci_snoop_log
08-23 08:45:32.170  7682  7875 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-23 08:45:32.171  1030  1113 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-23 08:45:32.171  1030  1113 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-23 08:45:32.172  7874  7874 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-23 08:45:32.172  7874  7874 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-23 08:45:32.172  7874  7874 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-23 08:45:32.175  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 08:45:32.175  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 08:45:32.175  7874  7874 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-23 08:45:32.180  7682  7875 D BluetoothAdapterProperties: Name is: G3
08-23 08:45:32.185  7874  7874 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-23 08:45:32.185  7874  7874 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-23 08:45:32.188  7682  7871 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-23 08:45:32.188  7682  7871 D BluetoothAdapterProperties: Setting state to 11
08-23 08:45:32.188  7682  7871 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-23 08:45:32.189  7682  7871 I LGBluetoothServiceJni: classInitNative: succeeds
,08-23 08:45:32.196  1030  1113 D BluetoothManagerService: Message: 60
08-23 08:45:32.196  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-23 08:45:32.196  1030  1113 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-23 08:45:32.200  1921  1921 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:32.201  1583  1583 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-23 08:45:32.204  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:45:32.208  6865  6865 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-23 08:45:32.214  7682  7682 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 08:45:32.214  7682  7682 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:32.215  7682  7682 V BluetoothPbapReceiver: ***********state = 11
08-23 08:45:32.225  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 08:45:32.234  7682  7871 D BluetoothBondStateMachine: make
08-23 08:45:32.238  7682  7871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:32.238  7682  7871 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-23 08:45:32.238  7682  7871 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:32.239  7682  7890 I BluetoothBondStateMachine: StableState(): Entering Off State
08-23 08:45:32.239  7682  7871 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-23 08:45:32.239  7682  7871 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-23 08:45:32.243  7682  7871 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:32.250  6865  6865 D BluetoothPermissionRequest: onReceive
08-23 08:45:32.251  7682  7682 D HeadsetService: Received start request. Starting profile...
08-23 08:45:32.252  7682  7682 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 08:45:32.252  7682  7682 D LGBluetoothHfpAdapter: Version 1.6
,08-23 08:45:32.252  7682  7871 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:32.255  7682  7682 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 08:45:32.256  6865  6865 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 08:45:32.257  7682  7682 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 08:45:32.257  7682  7682 D HeadsetStateMachine: make
08-23 08:45:32.264  7682  7871 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:32.270  7682  7871 E BluetoothAdapterService: File transfer profiles supported!!
,08-23 08:45:32.275  7682  7871 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:32.281  7682  7871 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:32.286  7682  7871 E BluetoothAdapterService: File transfer profiles supported!!
08-23 08:45:32.296  7682  7682 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:32.296  7682  7682 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 08:45:32.304  7682  7871 V LGMDMManager: Create singleton instance
08-23 08:45:32.305  7682  7871 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-23 08:45:32.391  1030  1052 I art     : Explicit concurrent mark sweep GC freed 27424(1301KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.457ms total 89.759ms
,08-23 08:45:32.391  7682  7682 D HeadsetStateMachine: max_hf_connections = 1
08-23 08:45:32.391  7682  7682 I bluedroid-qcom: get_profile_interface handsfree
08-23 08:45:32.393  7682  7682 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-23 08:45:32.394   313  1364 V AudioPolicyService: registerClient() client 0xb14277a0, uid 1002
08-23 08:45:32.395   313  1364 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-23 08:45:32.395   313  1364 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 08:45:32.395   313  1364 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 08:45:32.396  7682  7682 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-23 08:45:32.396   313   313 V AudioFlinger: registerClient() client 0xb5581ef8, pid 7682
08-23 08:45:32.397   313  1358 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:32.397   313  1358 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:32.397  1583  2250 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:32.397   313  1359 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:32.397  1583  2250 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:32.397   313  1359 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:32.397  1030  1974 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:32.397  1030  1974 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:32.397  1030  1974 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:32.397  1030  1974 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:32.397  1832  2688 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:32.397  1832  2688 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:32.398  1832  2688 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:32.398  1832  2688 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:32.398  7682  7697 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:32.398  7682  7697 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-23 08:45:32.398  3282  3297 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-23 08:45:32.398  3282  3297 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-23 08:45:32.399  7682  7682 V ToneGenerator: Create Track: 0xb4928a80
08-23 08:45:32.399  7682  7682 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-23 08:45:32.399  7682  7682 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-23 08:45:32.399  7682  7697 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:32.399  7682  7697 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-23 08:45:32.399   313  1530 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 08:45:32.399   313  1530 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-23 08:45:32.399   313  1530 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 08:45:32.399  3282  3297 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-23 08:45:32.399   313  1530 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 08:45:32.399  3282  3297 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:32.399   313  1363 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 08:45:32.400   313   313 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-23 08:45:32.399  1583  1602 V AudioSystem: ioConfigChanged() event 0, ioHan,dle 4
08-23 08:45:32.400   313   313 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-23 08:45:32.400   313   313 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-23 08:45:32.400   313   313 V AudioPolicyManagerEx: getOutput() returns output 2
08-23 08:45:32.400  1583  1602 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-23 08:45:32.400  7682  7682 V AudioSystem: getLatency() output 2, latency 50
08-23 08:45:32.400  7682  7682 V AudioSystem: getFrameCount() output 2, frameCount 960
08-23 08:45:32.400  7682  7682 V AudioTrack: createTrack_l() output 2 afLatency 50
08-23 08:45:32.400   313  1530 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 08:45:32.400   313  1530 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 08:45:32.400   313  1530 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-23 08:45:32.400   313  1530 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-23 08:45:32.400   313  1530 V AudioFlinger: createTrack() lSessionId: 23
08-23 08:45:32.401  7682  7682 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-23 08:45:32.401   313  1530 V AudioFlinger: acquiring 23 from 7682, for 7682
08-23 08:45:32.401   313  1530 V AudioFlinger:  added new entry for 23
08-23 08:45:32.401  7682  7682 V ToneGenerator: ToneGenerator INIT OK, time: 197435
08-23 08:45:32.401  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:32.404  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
,08-23 08:45:32.407  7682  7682 D A2dpService: Received start request. Starting profile...
08-23 08:45:32.408  7682  7682 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 08:45:32.409  7682  7682 V Avrcp   : make
08-23 08:45:32.409  7682  7682 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-23 08:45:32.409  7682  7682 I bluedroid-qcom: get_profile_interface avrcp
08-23 08:45:32.409  7682  7894 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-23 08:45:32.409  7682  7894 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-23 08:45:32.412  7682  7894 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-23 08:45:32.412  7682  7894 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-23 08:45:32.412   313  1363 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7682
08-23 08:45:32.413   313  1363 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-23 08:45:32.413   313  1363 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-23 08:45:32.413   313  1363 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-23 08:45:32.413   313  1363 V compress_voip: voice_extn_compress_voip_set_parameters: exit
,08-23 08:45:32.413   313  1363 V voice   : voice_set_parameters: exit with code(0)
08-23 08:45:32.413   313  1363 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-23 08:45:32.413   313  1363 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-23 08:45:32.413   313  1363 V msm8974_platform: platform_set_parameters: exit with code(0)
08-23 08:45:32.413   313  1363 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-23 08:45:32.413   313  1363 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-23 08:45:32.413   313  1363 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-23 08:45:32.413  7682  7894 V ToneGenerator: ToneGenerator destructor
08-23 08:45:32.413  7682  7894 V ToneGenerator: stopTone
08-23 08:45:32.413  7682  7894 V ToneGenerator: Delete Track: 0xb4928a80
08-23 08:45:32.414   313   313 V AudioPolicyService: AudioCommandThread() adding release output 2
08-23 08:45:32.414   313   313 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-23 08:45:32.414   313   313 V AudioFlinger: PlaybackThread::Track destructor
08-23 08:45:32.414   313  1265 V AudioPolicyService: AudioCommandThread() waking up
08-23 08:45:32.414  7682  7894 V AudioTrack: ~AudioTrack, releasing session id from 7682 on behalf of 7682
08-23 08:45:32.414   313   313 V AudioFlinger: removeClient_l() pid 7682, calling pid 313
08-23 08:45:32.414   313  1265 V AudioPolicyService: AudioCommandThread() processing release output 2
08-23 08:45:32.414   313  1265 V AudioPolicyManager: releaseOutput() 2
08-23 08:45:32.414   313  1265 V AudioPolicyService: AudioCommandThread() going to sleep
08-23 08:45:32.414   313  1364 V AudioFlinger: releasing 23 from 7682 for 7682
08-23 08:45:32.414   313  1364 V AudioFlinger:  decremented refcount to 0
08-23 08:45:32.414   313  1364 V AudioFlinger: purging stale effects
08-23 08:45:32.418  7682  7682 V AudioManager: registerRemoteController: size of Media player list: 0
,08-23 08:45:32.420  7682  7682 E AudioManager: No RCC entry present to update
08-23 08:45:32.420  7682  7682 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 08:45:32.422  7682  7682 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-23 08:45:32.423  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-23 08:45:32.423  7682  7682 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-23 08:45:32.426  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-23 08:45:32.569  1030  1762 V SIM_STK : Menu title from STK is T-Mobile
08-23 08:45:32.569  1030  1762 V SIM_STK : Menu title from STK is T-Mobile
,08-23 08:45:32.694  1030  2029 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-23 08:45:32.704  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 08:45:32.709  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 08:45:32.709  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 08:45:32.710  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 08:45:32.710  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 08:45:32.710  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 08:45:32.710  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 08:45:32.710  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 08:45:32.710  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 08:45:32.710  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 08:45:32.710  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 08:45:32.710  7682  7682 I BluetoothA2dpServiceJni: classInitNative
08-23 08:45:32.710  7682  7682 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 08:45:32.710  7682  7682 D A2dpStateMachine: make
08-23 08:45:32.714  7682  7682 I bluedroid-qcom: get_profile_interface a2dp
,08-23 08:45:32.714  7682  7902 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-23 08:45:32.719  7682  7682 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-23 08:45:32.719  7682  7682 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-23 08:45:32.722  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:32.723  7682  7901 D A2dpStateMachine: Enter Disconnected: -2
08-23 08:45:32.725  7682  7682 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 08:45:32.730  7682  7682 D HidService: Received start request. Starting profile...
08-23 08:45:32.730  7682  7682 I bluedroid-qcom: get_profile_interface hidhost
08-23 08:45:32.730  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:32.732  7682  7682 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 08:45:32.736  7682  7682 D HealthService: Received start request. Starting profile...
,08-23 08:45:32.740  7682  7682 I bluedroid-qcom: get_profile_interface health
08-23 08:45:32.741  7682  7682 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-23 08:45:32.741  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:32.742  7682  7682 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 08:45:32.744  7682  7682 D PanService: Received start request. Starting profile...
08-23 08:45:32.744  7682  7682 D BluetoothPanServiceJni: initializeNative(L110): pan
08-23 08:45:32.744  7682  7682 I bluedroid-qcom: get_profile_interface pan
08-23 08:45:32.750  7682  7682 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-23 08:45:32.750  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
,08-23 08:45:32.751  7682  7682 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-23 08:45:32.755  7682  7682 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 08:45:32.755  7682  7682 D BtGatt.GattService: Received start request. Starting profile...
08-23 08:45:32.755  7682  7682 D BtGatt.GattService: start()
08-23 08:45:32.755  7682  7682 I bluedroid-qcom: get_profile_interface gatt
08-23 08:45:32.756  7682  7682 D BtGatt.AdvertiseManager: advertise manager created
08-23 08:45:32.765  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
,08-23 08:45:32.768  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:32.768  7682  7682 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-23 08:45:32.769  7682  7682 V BluetoothMapService: BluetoothMapBinder()
08-23 08:45:32.770  7682  7682 D BluetoothMapService: Received start request. Starting profile...
08-23 08:45:32.770  7682  7682 D BluetoothMapService: start()
08-23 08:45:32.774  7682  7682 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-23 08:45:32.774  7682  7682 D BluetoothMapEmailAppObserver: createReceiver()
08-23 08:45:32.775  7682  7682 D BluetoothMapEmailAppObserver: initObservers()
08-23 08:45:32.775  7682  7682 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-23 08:45:32.784  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
,08-23 08:45:32.785  7682  7682 D HeadsetStateMachine: Proxy object connected
08-23 08:45:32.786  7682  7682 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-23 08:45:32.786  7682  7682 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-23 08:45:32.790  7682  7682 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:32.792  7682  7894 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 08:45:32.793  7682  7894 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 08:45:32.793  7682  7894 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-23 08:45:32.794  7682  7682 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:32.796  7682  7682 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:32.803  7682  7682 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-23 08:45:32.809  7682  7682 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:32.809  7682  7682 V PanService: [BTUI] SIM Extra State :ABSENT
08-23 08:45:32.813  7682  7682 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-23 08:45:32.816  7682  7682 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-23 08:45:32.816  7682  7682 V BluetoothMapService: Handler(): got msg=1
08-23 08:45:32.818  7682  7871 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,08-23 08:45:32.818  7682  7871 I bluedroid-qcom: enable
,08-23 08:45:32.818  7682  7682 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 08:45:32.818  7682  7682 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 08:45:32.818  7682  7682 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 08:45:32.818  7682  7871 I bt_hci_bdroid: init
08-23 08:45:32.819  7682  7682 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:32.819  7682  7682 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-23 08:45:32.823  7682  7871 I bt_vendor: bt-vendor : init
08-23 08:45:32.823  7682  7871 I bt_vendor: bt-vendor : get_bt_soc_type
08-23 08:45:32.823  7682  7871 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-23 08:45:32.823  7682  7871 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-23 08:45:32.823  7682  7871 D bt_userial_mct: userial_init
08-23 08:45:32.823  7682  7909 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-23 08:45:32.823  7682  7909 I bt-btu  : btu_task pending for preload complete event
08-23 08:45:32.825  7682  7871 D bt_hci_bdroid: set_power 1
08-23 08:45:32.825  7682  7871 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-23 08:45:32.825  7682  7871 I bt_vendor: Starting hciattach daemon
08-23 08:45:32.825  7682  7871 I bt_vendor: try to set true
08-23 08:45:32.821  7912  7912 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:32.821  7912  7912 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 08:45:32.866  7913  7913 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-23 08:45:32.967  7919  7919 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-23 08:45:32.986  7920  7920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 08:45:33.020  7922  7922 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 08:45:33.038  7923  7923 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-23 08:45:33.053  7924  7924 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-23 08:45:33.066  7925  7925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-23 08:45:33.100  7927  7927 I libmdmdetect: ESOC framework not supported
08-23 08:45:33.102  7927  7927 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-23 08:45:33.111  7927  7927 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-23 08:45:33.111  7927  7927 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-23 08:45:33.111  7927  7927 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-23 08:45:33.111  7927  7927 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-23 08:45:33.111  7927  7927 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-23 08:45:33.111  7927  7927 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-23 08:45:33.111  7927  7927 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-23 08:45:33.151  7927  7928 E QC-QMI  : qmi_client [7927] 15: failed to locate client data
08-23 08:45:33.152   469   469 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-23 08:45:33.152   469   469 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-23 08:45:33.210  7935  7935 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-23 08:45:33.225  7936  7936 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-23 08:45:33.278  7682  7871 I bt_vendor: bluetooth satus is on
,08-23 08:45:33.278  7682  7871 D bt_hci_bdroid: preload
,08-23 08:45:33.278  7682  7911 D bt_userial_mct: userial_open(port:0)
08-23 08:45:33.278  7682  7911 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-23 08:45:33.290  7682  7911 I bt_vendor: Done intiailizing UART
08-23 08:45:33.291  7682  7911 I bt_vendor: Done intiailizing UART
08-23 08:45:33.292  7682  7911 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-23 08:45:33.292  7682  7911 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-23 08:45:33.292  7682  7909 I bt-btu  : btu_task received preload complete event
08-23 08:45:33.292  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-23 08:45:33.293  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-23 08:45:33.295  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-23 08:45:33.298  7682  7938 D bt_userial_mct: Entering userial_read_thread()
,08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-23 08:45:33.303  7682  7909 I         : BTE_InitTraceLevels -- TRC_GAP
,08-23 08:45:33.304  7682  7909 I         : BTE_InitTraceLevels -- TRC_PAN,
08-23 08:45:33.304  7682  7909 I         : BTE_InitTraceLevels -- TRC_SDP,
08-23 08:45:33.304  7682  7909 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 08:45:33.304  7682  7909 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 08:45:33.304  7682  7909 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-23 08:45:33.304  7682  7909 I         : BTE_InitTraceLevels -- TRC_BTIF,
,08-23 08:45:33.407  7682  7909 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-23 08:45:33.407  7682  7909 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0240061 
08-23 08:45:33.407  7682  7909 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0240061 
,08-23 08:45:33.440  7682  7875 E bt-btif : Calling BTA_HhEnable
08-23 08:45:33.440  7682  7875 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-23 08:45:33.441  7682  7875 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-23 08:45:33.443  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-23 08:45:33.443  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-23 08:45:33.443  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-23 08:45:33.445  1030  1030 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-23 08:45:33.445  1030  1030 D BluetoothManagerService: Stored Bluetooth name: G3
08-23 08:45:33.445  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-23 08:45:33.446  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-23 08:45:33.446  7682  7875 D BluetoothAdapterProperties: Name is: G3
08-23 08:45:33.447  7682  7875 D BluetoothAdapterProperties: Scan Mode:20
08-23 08:45:33.447  7682  7875 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 08:45:33.448  7682  7875 D bt_hci_bdroid: postload
08-23 08:45:33.448  7682  7911 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:33.449  7682  7875 D bte_conf: Device ID record 1 : primary
08-23 08:45:33.449  7682  7875 D bte_conf:   vendorId            = 00c4
08-23 08:45:33.449  7682  7875 D bte_conf:   vendorIdSource      = 0001
08-23 08:45:33.449  7682  7875 D bte_conf:   product             = 13a1
08-23 08:45:33.449  7682  7875 D bte_conf:   version             = 1000
08-23 08:45:33.449  7682  7875 D bte_conf:   clientExecutableURL = 
08-23 08:45:33.449  7682  7875 D bte_conf:   serviceDescription  = 
08-23 08:45:33.449  7682  7875 D bte_conf:   documentationURL    = 
08-23 08:45:33.449  7682  7875 D bte_conf: bte_load_did_conf no section named DID2.
08-23 08:45:33.450  7682  7909 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-23 08:45:33.450  7682  7911 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:33.450  7682  7911 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:33.451  7682  7911 D bt_hci_bdroid: Used up Tx Cmd credits
08-23 08:45:33.454  7682  7938 E bt_mct  : hci lib postload completed
,08-23 08:45:33.459  7682  7871 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-23 08:45:33.459  7682  7871 D BluetoothAdapterProperties: ScanMode =  20
08-23 08:45:33.459  7682  7871 D BluetoothAdapterProperties: State =  11
08-23 08:45:33.459  7682  7871 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-23 08:45:33.460  7682  7871 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-23 08:45:33.460  7682  7871 D BluetoothAdapterProperties: Setting state to 12
08-23 08:45:33.460  7682  7871 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 08:45:33.460  7682  7875 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-23 08:45:33.461  7682  7875 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-23 08:45:33.451  7940  7940 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:33.451  7940  7940 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:33.469  1030  1113 D BluetoothManagerService: Message: 60
08-23 08:45:33.469  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-23 08:45:33.469  1030  1113 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-23 08:45:33.473  7682  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:33.473  7682  7909 W bt-smp  : Plain text(LSB ~ MSB) = 86 27 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:33.473  7682  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = cf 76 bc 04 8f cb cb 46 23 39 d2 6e 9e fa 13 4c 
08-23 08:45:33.473  7682  7909 W bt-btm  : Stopping oneshot timer
08-23 08:45:33.503  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:33.503  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:33.503  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:33.503  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:33.503  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:33.503  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:33.503  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:33.503  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:45:33.507  7682  7871 I BluetoothAdapterState: Entering On State
08-23 08:45:33.508  6865  6881 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 08:45:33.509  7682  7875 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 08:45:33.509  7682  7875 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-23 08:45:33.511  7682  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:33.511  7682  7909 W bt-smp  : Plain text(LSB ~ MSB) = 21 01 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:33.511  7682  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = 67 08 4e 4d 2a a2 d5 c8 cb 48 9f 5c 8d 8d 69 2d 
08-23 08:45:33.511  7682  7909 W bt-btm  : Stopping oneshot timer
08-23 08:45:33.515  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:33.526  7682  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:33.526  7682  7909 W bt-smp  : Plain text(LSB ~ MSB) = a5 be 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:33.526  7682  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = e4 69 f2 c8 4e 69 e5 45 53 9f c1 07 8e 73 49 15 
,08-23 08:45:33.528  7682  7909 W bt-btm  : Stopping oneshot timer
08-23 08:45:33.533  7682  7871 D LGBluetoothServiceAdapter: [BTUI] OnState
08-23 08:45:33.533  7682  7871 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-23 08:45:33.533  7682  7871 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-23 08:45:33.534  7682  7871 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-23 08:45:33.542  1832  1847 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 08:45:33.550  7682  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:33.550  7682  7909 W bt-smp  : Plain text(LSB ~ MSB) = 3e 6c 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:33.550  7682  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 fc 90 f7 66 e2 01 29 a2 f0 99 d9 60 a2 54 c6 
08-23 08:45:33.550  7682  7909 W bt-btm  : Stopping oneshot timer
08-23 08:45:33.552  1832  1832 D BluetoothHeadset: Proxy object connected
08-23 08:45:33.553  6865  7561 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 08:45:33.564  7682  7871 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-23 08:45:33.581  6865  6865 D BluetoothA2dp: Proxy object connected
08-23 08:45:33.582  6865  6865 D A2dpProfile: Bluetooth service connected
,08-23 08:45:33.586  1832  2610 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 08:45:33.592  1832  1832 D BluetoothHeadset: Proxy object connected
08-23 08:45:33.593  6865  6880 D BluetoothMap: onBluetoothStateChange: up=true
08-23 08:45:33.596  6865  6865 D BluetoothMap: Proxy object connected
08-23 08:45:33.596  6865  6865 D MapProfile: Bluetooth service connected
08-23 08:45:33.596  6865  6865 D BluetoothMap: getConnectedDevices()
08-23 08:45:33.597  7682  7697 V BluetoothMapService: getConnectedDevices()
08-23 08:45:33.598  6865  6881 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 08:45:33.601  7682  7909 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-23 08:45:33.601  7682  7909 W bt-smp  : Plain text(LSB ~ MSB) = fe 65 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-23 08:45:33.601  7682  7909 W bt-smp  : Encrypted text(LSB ~ MSB) = c0 9a e4 09 63 81 5c f5 cf 26 ee cd 8b ca 6e 03 
08-23 08:45:33.601  7682  7909 W bt-btm  : Stopping oneshot timer
08-23 08:45:33.603  1030  1113 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 08:45:33.603  6865  6865 D BluetoothHeadset: Proxy object connected
08-23 08:45:33.603  6865  6865 D HeadsetProfile: Bluetooth service connected
08-23 08:45:33.603  1030  1030 D BluetoothA2dp: Proxy object connected
08-23 08:45:33.604  1832  1848 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 08:45:33.604  7959  7959 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-23 08:45:33.607  1030  1113 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 08:45:33.607  1832  1832 D BluetoothHeadset: Proxy object connected
08-23 08:45:33.607  1030  1030 D BluetoothHeadset: Proxy object connected
08-23 08:45:33.608  6865  7561 D BluetoothPan: onBluetoothStateChange on: true
08-23 08:45:33.608  6865  7561 D BluetoothPan: onBluetoothStateChange call bindService
08-23 08:45:33.610  6865  6880 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 08:45:33.612  6865  6865 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 08:45:33.612  6865  6865 D PanProfile: Bluetooth service connected
,08-23 08:45:33.615  1030  1030 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-23 08:45:33.616  6865  6865 D BluetoothInputDevice: Proxy object connected
08-23 08:45:33.616  1030  1113 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-23 08:45:33.616  6865  6865 D HidProfile: Bluetooth service connected
08-23 08:45:33.616  1030  1113 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-23 08:45:33.617  1030  1113 D BluetoothManagerService: Message: 40
08-23 08:45:33.617  1030  1113 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-23 08:45:33.620  1921  1921 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:33.620  1583  1583 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-23 08:45:33.621  1921  2059 D LGBluetoothAPIService: Message: 1
08-23 08:45:33.621  1921  2059 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-23 08:45:33.621  1921  2059 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-23 08:45:33.621  1921  2059 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-23 08:45:33.625  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:33.626  7682  7682 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:33.626  7682  7682 D BluetoothMapService: STATE_ON
08-23 08:45:33.626  7682  7682 V BluetoothMapService: Handler(): got msg=1
,08-23 08:45:33.628  7682  7682 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-23 08:45:33.630  7682  7963 D BluetoothMapMasInstance: MAS initSocket()
08-23 08:45:33.631  7682  7963 D BluetoothMapMasInstance:   masId = 00
08-23 08:45:33.631  7682  7963 D BluetoothMapMasInstance:   msgTypes = 0e
08-23 08:45:33.631  7682  7963 D BluetoothMapMasInstance:   masName = SMS/MMS
08-23 08:45:33.631  7682  7963 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-23 08:45:33.632  1030  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:33.634  7682  7963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:33.636  7682  7963 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-23 08:45:33.636  7682  7875 D BluetoothAdapterProperties: Scan Mode:21
08-23 08:45:33.636  7682  7963 V BluetoothMapMasInstance: Succeed to create listening socket 
08-23 08:45:33.636  7682  7875 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-23 08:45:33.637  7682  7963 D BluetoothMapMasInstance: Accepting socket connection...
08-23 08:45:33.640  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 08:45:33.645  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:33.645  7682  7682 V BluetoothPbapService: Pbap Service onCreate
08-23 08:45:33.646  7682  7682 V BluetoothPbapService: Starting PBAP service
08-23 08:45:33.647  6865  6865 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-23 08:45:33.647  7682  7682 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-23 08:45:33.648  7682  7682 V BluetoothPbapService: Pbap Service onBind
08-23 08:45:33.648  7682  7682 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:33.649  7682  7682 V BluetoothPbapService: state: 12
08-23 08:45:33.649  7682  7682 V BluetoothPbapService: Handler(): got msg=1
08-23 08:45:33.648  6865  6865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-23 08:45:33.651  7682  7682 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-23 08:45:33.652  6865  6865 D BluetoothPbap: Proxy object connected
08-23 08:45:33.652  6865  6865 D PbapServerProfile: Bluetooth service connected
,08-23 08:45:33.653  7682  7964 V BluetoothPbapService: Pbap Service initSocket
08-23 08:45:33.654  7682  7682 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-23 08:45:33.654  1030  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:33.654  7682  7682 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:33.654  7682  7682 V BluetoothPbapReceiver: ***********state = 12
08-23 08:45:33.657  6865  6865 D DockEventReceiver: finishStartingService: stopping service
08-23 08:45:33.657  2154  2154 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 08:45:33.657  2154  2154 D c       : Getting all permits...
08-23 08:45:33.657  2154  2154 D a       : Opening database...
08-23 08:45:33.661  2154  2154 D a       : Opening database auth.proximity.permit_store...
08-23 08:45:33.661  7682  7964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:33.662  2154  2154 D a       : Closing database...
08-23 08:45:33.662  7682  7964 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-23 08:45:33.662  7682  7964 V BluetoothPbapService: Succeed to create listening socket 
08-23 08:45:33.662  7682  7964 V BluetoothPbapService: Accepting socket connection...
08-23 08:45:33.671  6865  6865 D BluetoothPermissionRequest: onReceive
,08-23 08:45:33.673  6865  6865 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-23 08:45:33.675  6865  6865 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-23 08:45:33.678  7682  7682 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-23 08:45:33.679  7682  7682 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-23 08:45:33.684  7682  7682 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-23 08:45:33.702  7682  7682 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-23 08:45:33.702  7682  7682 V BtOppService: onCreate
,08-23 08:45:33.706  7682  7682 V BluetoothOppNotification: send message
,08-23 08:45:33.711  7682  7682 V BtOppService: Starting RfcommListener
08-23 08:45:33.719  7682  7682 D BluetoothOppPreference: Dumping Names:  
08-23 08:45:33.719  7682  7682 D BluetoothOppPreference: {}
08-23 08:45:33.719  7682  7682 D BluetoothOppPreference: Dumping Channels:  
,08-23 08:45:33.719  7682  7682 D BluetoothOppPreference: {}
08-23 08:45:33.723  7682  7682 V BtOppService: onStartCommand
08-23 08:45:33.724  7682  7972 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 08:45:33.725  7682  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 08:45:33.725  7682  7969 V BtOppService: Deleted complete outbound shares, number =  0
08-23 08:45:33.727  7682  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ecec051 on behalf of 
08-23 08:45:33.727  7682  7969 V BtOppService: Deleted complete inbound failed shares, number = 0
08-23 08:45:33.727  7682  7969 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-23 08:45:33.728  7682  7972 V BluetoothOppNotification: update too frequent, put in queue
08-23 08:45:33.729  7682  7969 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c46c0b6 on behalf of 
08-23 08:45:33.729  7682  7682 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:33.730  7682  7682 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-23 08:45:33.731  7682  7972 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 08:45:33.732  7682  7972 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 08:45:33.733  7682  7682 V BluetoothOppNotification: new notify threadi!
,08-23 08:45:33.734  7682  7682 V BluetoothOppNotification: send delay message
08-23 08:45:33.735  7682  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 08:45:33.736  7682  7682 V BtOppService: start RfcommListener
08-23 08:45:33.736  7682  7972 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b9bb1b7 on behalf of 
08-23 08:45:33.738  7682  7972 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 08:45:33.738  7682  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@bfa9d24 on behalf of 
08-23 08:45:33.739  7682  7973 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-23 08:45:33.740  7682  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 08:45:33.742  7682  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@236e108d on behalf of 
08-23 08:45:33.743  7682  7973 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 08:45:33.744  7682  7682 V BtOppService: RfcommListener started
08-23 08:45:33.744  7682  7682 V BtOppService: ContentObserver received notification
,08-23 08:45:33.746  7682  7682 V BtOppService: ContentObserver received notification
,08-23 08:45:33.746  7682  7973 V BluetoothOppNotification: outbound notification was removed.
08-23 08:45:33.747  7682  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 08:45:33.747  7682  7976 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-23 08:45:33.747  7682  7976 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-23 08:45:33.748  7682  7975 V BtOppRfcommListener: Starting RFCOMM listener....
08-23 08:45:33.749  1030  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:33.749  7682  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38f63242 on behalf of 
,08-23 08:45:33.750  7682  7973 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 08:45:33.750  7682  7975 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:33.751  7682  7976 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@252fb253 on behalf of 
08-23 08:45:33.751  7682  7975 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-23 08:45:33.751  7682  7975 V BtOppRfcommListener: Started RFCOMM listener....
08-23 08:45:33.752  7682  7975 I BtOppRfcommListener: Accept thread started.
08-23 08:45:33.752  7682  7975 V BtOppRfcommListener: Accepting connection...
08-23 08:45:33.752  7682  7973 V BluetoothOppNotification: inbound notification was removed.
08-23 08:45:33.753  7682  7976 V BluetoothOppNotification: update too frequent, put in queue
08-23 08:45:33.753  7682  7973 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-23 08:45:33.754  7682  7976 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-23 08:45:33.755  7682  7973 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cd66790 on behalf of 
08-23 08:45:33.768  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:33.768  7682  7682 V BluetoothFtpService: Ftp Service onCreate
08-23 08:45:33.768  7682  7682 I BluetoothFtpService: Ftp Service onCreate
08-23 08:45:33.768  7682  7682 V BluetoothFtpService: Ftp Service onStartCommand
08-23 08:45:33.768  7682  7682 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:33.768  7682  7682 V BluetoothFtpService: Starting Listening on sockets
08-23 08:45:33.769  7682  7682 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-23 08:45:33.769  7682  7682 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-23 08:45:33.769  7682  7682 V BluetoothSapReceiver: SapReceiver onReceive 
08-23 08:45:33.769  7682  7682 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-23 08:45:33.769  7682  7682 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-23 08:45:33.769  7682  7682 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-23 08:45:33.771  7682  7682 V BluetoothFtpService: Handler(): got msg=1
08-23 08:45:33.772  7682  7682 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-23 08:45:33.772  7682  7682 V BluetoothFtpService: Ftp Service initSocket
08-23 08:45:33.777  1030  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:33.777  7682  7682 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:33.778  7682  7682 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-23 08:45:33.779  7682  7682 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-23 08:45:33.780  7682  7977 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-23 08:45:33.795  7682  7682 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@86b8a85
08-23 08:45:33.795  7682  7682 V BluetoothSapService: Sap Service onCreate
,08-23 08:45:33.798  7682  7682 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-23 08:45:33.798  7682  7682 V BluetoothSapService: state: 12
08-23 08:45:33.798  7682  7682 V BluetoothSapService: Starting SAP server process
08-23 08:45:33.791  7978  7978 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:33.799  7682  7682 V BluetoothSapService: SAP Service startRfcommListenerThread
08-23 08:45:33.791  7978  7978 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:33.801  7682  7979 V BluetoothSapService: Sap Service initRfcommSocket
08-23 08:45:33.802  1030  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:33.803  7682  7979 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 08:45:33.805  7682  7979 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-23 08:45:33.805  7682  7979 V BluetoothSapService: Succeed to create listening socket 
08-23 08:45:33.805  7682  7979 V BluetoothSapService: Accepting socket connection...
08-23 08:45:33.814  7978  7978 V BT_SAP  : Event pipe created
08-23 08:45:33.814  7978  7978 V BT_SAP  : create_server_socket qcom.sap.server
08-23 08:45:33.814  7978  7978 V BT_SAP  : created socket fd 6
,08-23 08:45:34.131  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:34.131  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:34.131  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:34.131  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 08:45:34.131  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:34.131  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:34.131  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:34.131  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 08:45:34.137  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 08:45:34.156  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:34.157  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@254b372e added. We now have 8 listener(s)
08-23 08:45:34.157  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:34.162  1030  2029 D WifiServiceImplEx: setWifiEnabled: false pid=6716, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-23 08:45:34.162  1030  2029 D WifiService: setWifiEnabled: false pid=6716, uid=10118
08-23 08:45:34.162  1030  2029 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 08:45:34.168  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:34.169  1030  1956 D WifiServiceImplEx: setWifiEnabled: true pid=6716, uid=10118, package= com.test.thalitest, App Lable : ThaliTest,
08-23 08:45:34.169  1030  1956 D WifiService: setWifiEnabled: true pid=6716, uid=10118
08-23 08:45:34.170  1030  1956 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 08:45:34.185  1030  1517 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-23 08:45:34.185  1030  1517 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-23 08:45:34.191  1030  1030 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-23 08:45:34.191  1030  1030 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-23 08:45:34.191  1030  1030 D Ulp_jni : JNI:system_update. Event-4
08-23 08:45:34.191  1030  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-23 08:45:34.192  1030  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-23 08:45:34.192  1030  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1030] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-23 08:45:34.192  1030  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-23 08:45:34.192  1030  1517 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-23 08:45:34.192  1030  1517 E WifiHW  : unknown target_country: EU , set to default
08-23 08:45:34.192  1030  1517 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-23 08:45:34.192  1030  1517 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-23 08:45:34.192  1030  1517 I WifiUtil: gEnableBmps=1
08-23 08:45:34.737  7682  7682 V BluetoothOppNotification: new notify threadi!
08-23 08:45:34.737  7682  7682 V BluetoothOppNotification: send delay message
,08-23 08:45:34.756  7682  7998 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-23 08:45:34.759  7682  7998 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@b71c445 on behalf of 
08-23 08:45:34.760  7682  7998 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-23 08:45:34.763  7682  7998 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-23 08:45:34.764  7682  7998 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1b9bc79a on behalf of 
08-23 08:45:34.764  7682  7998 V BluetoothOppNotification: outbound: succ-0  fail-0
08-23 08:45:34.766  7682  7998 V BluetoothOppNotification: outbound notification was removed.
08-23 08:45:34.766  7682  7998 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-23 08:45:34.767  7682  7998 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@334118cb on behalf of 
08-23 08:45:34.768  7682  7998 V BluetoothOppNotification: inbound: succ-0  fail-0
08-23 08:45:34.771  7682  7998 V BluetoothOppNotification: inbound notification was removed.
08-23 08:45:34.771  7682  7998 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-23 08:45:34.774  7682  7998 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@204798a8 on behalf of 
08-23 08:45:34.813   308   888 D SoftapController: Softap fwReload - Ok
,08-23 08:45:34.817  1030  1517 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (619ms)
08-23 08:45:34.843  1030  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 08:45:34.844  1030  1113 D Tethering: InitialState.processMessage what=4
,08-23 08:45:34.851   308   888 D CommandListener: Setting iface cfg
08-23 08:45:34.851   308   888 D CommandListener: Trying to bring down wlan0
08-23 08:45:34.866   308   888 D CommandListener: Clearing all IP addresses on wlan0
,08-23 08:45:34.869  1030  1113 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-23 08:45:34.876  1030  1517 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-23 08:45:34.881  8000  8000 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 08:45:34.881  8000  8000 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:34.902  1030  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 08:45:34.902  1030  1517 E WifiStateMachine: useWiFiOffloading() : false
08-23 08:45:34.902  1030  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 08:45:34.905  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-23 08:45:34.906  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 08:45:34.906  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 08:45:34.906  6865  6865 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 08:45:34.914  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:34.918  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-23 08:45:34.918  1030  1517 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-23 08:45:34.918  1030  1517 D WifiMonitor: connecting to supplicant
08-23 08:45:34.921  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-23 08:45:34.927  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:34.928  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 08:45:34.929  6865  6865 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 08:45:34.929  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 08:45:34.929  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 08:45:34.929  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 08:45:34.930  6865  6865 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 08:45:34.930  6865  6865 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 08:45:34.932  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 08:45:34.932  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 08:45:34.932  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 08:45:34.932  6865  6865 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 08:45:34.934  8000  8000 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-23 08:45:34.936  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-23 08:45:34.936  6865  6865 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 08:45:34.937  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-23 08:45:34.937  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 08:45:34.937  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 08:45:34.937  6865  6865 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 08:45:34.937  6865  6865 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 08:45:34.973  8000  8000 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-23 08:45:34.974  8000  8000 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-23 08:45:34.985  1030  1892 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8019 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-23 08:45:35.054  8000  8000 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-23 08:45:35.092  1030  1901 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8040 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 08:45:35.098  8019  8038 W FormManager: Network not available. Please check & try again.
08-23 08:45:35.106  8019  8039 V FormManager: Network unavailable.
,08-23 08:45:35.113  8019  8039 V FormManager: Network unavailable.
08-23 08:45:35.126  1030  1919 I ActivityManager: Killing 7155:com.android.chrome/u0a57 (adj 15): empty #17
,08-23 08:45:35.127  8000  8000 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-23 08:45:35.131  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-23 08:45:35.132  8000  8000 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-23 08:45:35.132  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-23 08:45:35.133  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-23 08:45:35.133  1030  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-23 08:45:35.133  1030  8058 D WifiMonitor: Dropping event because (p2p0) is stopped
08-23 08:45:35.133  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-23 08:45:35.133  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-23 08:45:35.133  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-23 08:45:35.133  1030  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-23 08:45:35.134  1030  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-23 08:45:35.134  1030  1517 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-23 08:45:35.134  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.134  1030  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.135  1030  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.135  1030  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.136  1030  1517 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-23 08:45:35.136  1030  1517 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-23 08:45:35.136  1030  1517 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-23 08:45:35.137  1030  1517 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-23 08:45:35.137  1030  1517 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-23 08:45:35.167  1030  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-23 08:45:35.167  1030  1517 E WifiStateMachine: useWiFiOffloading() : false
08-23 08:45:35.167  1030  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-23 08:45:35.167  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.167  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.167  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.167  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.167  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-23 08:45:35.167  1030  1517 D WifiNative-wlan0: doBoolean: SET update_config 1
08-23 08:45:35.168  1030  1762 W libprocessgroup: failed to open /acct/uid_10057/pid_7155/cgroup.procs: No such file or directory
,08-23 08:45:35.172  1921  1921 D WfdService: Waiting for WifiP2p enabling
08-23 08:45:35.172  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.174  1030  1517 D WifiNative-wlan0: SET update_config 1: returned true
08-23 08:45:35.174  1030  1517 D WifiConfigStore: Loading config and enabling all networks 
08-23 08:45:35.174  1030  1517 D WifiNative-wlan0: doString: [LIST_NETWORKS]
,08-23 08:45:35.174  1030  1517 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-23 08:45:35.179  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:35.179  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:35.179  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:35.179  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:35.179  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:35.179  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:35.179  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 08:45:35.179  6716  6716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:35.181  1030  1030 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-23 08:45:35.181  1030  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-23 08:45:35.184  1030  1517 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-23 08:45:35.185  6716  6716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:35.198  1030  1517 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-23 08:45:35.198  1030  1517 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-23 08:45:35.199  1030  1517 D WifiStateMachine: enableVerboseLogging : level 2
08-23 08:45:35.199  1030  1517 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-23 08:45:35.200  1030  1517 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-23 08:45:35.200  1030  1517 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-23 08:45:35.200  1030  1517 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-23 08:45:35.200  1030  1517 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-23 08:45:35.201  1030  1517 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-23 08:45:35.201  1030  1517 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-23 08:45:35.201  1030  1517 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-23 08:45:35.201  1030  1517 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-23 08:45:35.202  1030  1517 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-23 08:45:35.202  1030  1517 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-23 08:45:35.202  1030  1517 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-23 08:45:35.202  1030  1517 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-23 08:45:35.202  1030  1517 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-23 08:45:35.203  1030  1517 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 08:45:35.203  1030  1517 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-23 08:45:35.204  1030  1517 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-23 08:45:35.204  1030  1517 D WifiNative-HAL: Setting external_sim to 1
08-23 08:45:35.204  1030  1517 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-23 08:45:35.205  1030  1517 D WifiNative-wlan0: SET external_sim 1: returned true
08-23 08:45:35.205  1030  1517 I WifiNative-HAL: startHal
08-23 08:45:35.205  1921  1921 D WfdsService: Supplicant Connection state is changed : true
08-23 08:45:35.205  1030  1517 D wifi    : setting scan oui 0xaf69b5c0
08-23 08:45:35.205  1030  1517 D WifiStateMachine: Setting OUI to DA-A1-19
08-23 08:45:35.205  1030  1517 I WifiNative-HAL: startHal
08-23 08:45:35.205  1030  1517 D wifi    : setting scan oui 0xaf69b5c0
08-23 08:45:35.205  1921  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-23 08:45:35.207  1030  1517 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-23 08:45:35.207  7710  7710 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.208  1030  1517 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-23 08:45:35.208  1921  2257 D WfdsService: Set the WFDS Monitor: true
08-23 08:45:35.208  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-23 08:45:35.208  1921  2257 D WfdsMonitor: WfdsMonitorThread create
08-23 08:45:35.208  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-23 08:45:35.208  1921  2257 D WfdsMonitor: WFDS Monitor is created and started
08-23 08:45:35.208  1921  2257 D WfdsService: WiFi: Supplicant connection re-established
08-23 08:45:35.209  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-23 08:45:35.209  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 08:45:35.209  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 08:45:35.209  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 08:45:35.209  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:35.209  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:35.209  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:35.209  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:35.209  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 08:45:35.209  6716  6818 V io.jxcore.node.ConnectivityMo,nitor:     - is connected/connecting to active network: false
08-23 08:45:35.209  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 08:45:35.210  1921  8059 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-23 08:45:35.210  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 08:45:35.210  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-23 08:45:35.210  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-23 08:45:35.210  1921  8059 E CtrlSupplicant: Succeed to open control connection
08-23 08:45:35.210  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-23 08:45:35.210  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 08:45:35.210  1921  8059 E CtrlSupplicant: Succeed to open monitor connection
08-23 08:45:35.211  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 08:45:35.211  1921  8059 D WfdsMonitor: Supplicant connection established
08-23 08:45:35.211  1921  2257 D WfdsService: Connected to the supplicant for wfds
08-23 08:45:35.211  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 08:45:35.211  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-23 08:45:35.211  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-23 08:45:35.212  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-23 08:45:35.212  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-23 08:45:35.212  8000  8000 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-23 08:45:35.212  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-23 08:45:35.212  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-23 08:45:35.212  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-23 08:45:35.213  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-23 08:45:35.213  1030  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-23 08:45:35.214  1030  1517 E WifiNative: : [200,234,342 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-23 08:45:35.214  1030  1517 D WifiNative-wlan0: doBoolean: RECONNECT
,08-23 08:45:35.215  1030  1517 D WifiNative-wlan0: RECONNECT: returned true
08-23 08:45:35.215  1030  1517 D WifiNative-wlan0: doString: [STATUS]
08-23 08:45:35.215  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-23 08:45:35.216  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-23 08:45:35.216  1030  1517 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 08:45:35.216  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 08:45:35.217  1030  1517 D WifiNative-wlan0: SET ps 1: returned true
08-23 08:45:35.217  1030  1515 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.219   308   888 D CommandListener: Setting iface cfg
08-23 08:45:35.219   308   888 D CommandListener: Trying to bring up p2p0
08-23 08:45:35.219  1030  1515 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-23 08:45:35.219  1030  1030 D WifiScanningService: SCAN_AVAILABLE : 3
08-23 08:45:35.219  1030  1515 D LGWifiP2pService: P2pEnablingState
08-23 08:45:35.219  1030  1030 D RttService: SCAN_AVAILABLE : 3
08-23 08:45:35.219  1030  1515 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.219  1030  1515 D LGWifiP2pService: P2p socket connection successful
08-23 08:45:35.219  1030  1515 D LGWifiP2pService: P2pEnabledState
08-23 08:45:35.219  1030  1536 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.219  1030  1536 I WifiNative-HAL: startHal
08-23 08:45:35.220  1030  1536 D wifi    : getting scan capabilities on interface[1] = 0xaf69b5c0
08-23 08:45:35.220  1030  1536 D wifi    : failed to get capabilities : -3
08-23 08:45:35.220  1030  1536 E WifiScanningService: could not get scan capabilities
08-23 08:45:35.220  1030  1515 D LGWifiP2pService: sending p2p connection changed broadcast
08-23 08:45:35.220  1030  1537 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.220  1030  1515 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-23 08:45:35.221  1030  1515 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-23 08:45:35.221  1030  1515 D WifiNative-p2p0: doBoolean: SET device_name G3
08-23 08:45:35.221  1030  1515 D WifiNative-p2p0: SET device_name G3: returned true
08-23 08:45:35.221  1030  1515 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-23 08:45:35.221  1030  1515 D LGWifiP2pService: before postfix = G3
08-23 08:45:35.221  1030  1515 D WifiServerServiceExt: postfix byte check : 2
08-23 08:45:35.221  1030  1515 D LGWifiP2pService: after postfix = G3
08-23 08:45:35.221  1030  1515 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-23 08:45:35.222  1921  1921 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-23 08:45:35.222  1030  1515 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-23 08:45:35.222  1030  1515 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-23 08:45:35.222  1921  1921 D WfdsService: WifiP2pState is changed : true
08-23 08:45:35.222  1921  2257 D WfdsService: Receive the WFDS_ENABLE Method
08-23 08:45:35.223  1921  2257 D WfdsService: Set the WFDS Monitor: true
08-23 08:45:35.223  1921  2257 D WfdsService: Connected to the supplicant for wfds
08-23 08:45:35.223  1921  2257 D WfdsJNI : doCommand: WFDS_SET TRUE
08-23 08:45:35.223  8000  8000 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-23 08:45:35.223  1921  2257 D WfdsService: selectPreferredScanChannel [36]
08-23 08:45:35.223  1921  2257 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-23 08:45,:35.223  1030  1515 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-23 08:45:35.223  1030  1515 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-23 08:45:35.224  1921  1921 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-23 08:45:35.224  1921  1921 D WfdsService: isConnected: false
08-23 08:45:35.225  1030  1515 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-23 08:45:35.225  1030  1515 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-23 08:45:35.227  1030  1515 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-23 08:45:35.227  1030  1515 D WifiNative-HAL: p2pGetDeviceAddress
08-23 08:45:35.227  1030  1517 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-23 08:45:35.227  6716  6818 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-23 08:45:35.227  1030  1515 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-23 08:45:35.228  1030  1517 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-23 08:45:35.228  6716  6818 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-23 08:45:35.229  1030  1517 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-23 08:45:35.229  1030  1517 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-23 08:45:35.230  1921  1921 I WfdStateTracker: handleP2pThisDeviceChanged
08-23 08:45:35.230  1921  1921 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-23 08:45:35.230  1921  1921 D WfdsService: Update P2p Interface State: 3
08-23 08:45:35.230  1030  1515 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
,08-23 08:45:35.230  1030  1515 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-23 08:45:35.230  1030  1517 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-23 08:45:35.230  1030  1517 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-23 08:45:35.231  6716  6818 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6bd2800 Bundle[{}]
08-23 08:45:35.231  1030  1517 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-23 08:45:35.231  1030  1517 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-23 08:45:35.231  8000  8000 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-23 08:45:35.232  6716  6818 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 08:45:35.232  6716  6818 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 08:45:35.232  1030  1517 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-23 08:45:35.232  1030  1515 D WifiNative-p2p0: P2P_FLUSH: returned true
08-23 08:45:35.232  1030  1515 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-23 08:45:35.232  6716  6818 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-23 08:45:35.233  1030  1517 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-23 08:45:35.233  1030  1515 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-23 08:45:35.233  1030  1515 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-23 08:45:35.233  1030  1515 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-23 08:45:35.233  1030  1515 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-23 08:45:35.235  1030  1517 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-23 08:45:35.235  1030  1517 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-23 08:45:35.235  6716  6818 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 08:45:35.236  6716  6818 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 08:45:35.237  6716  6818 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-23 08:45:35.244  6716  6818 I System.out: Running OutgoingSocketThread
08-23 08:45:35.245  8000  8000 E wpa_supplicant: disconnect_rssi_lvl: -100
08-23 08:45:35.246  1030  1515 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-23 08:45:35.246  1030  1515 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-23 08:45:35.246  1030  1515 D LGWifiP2pService: InactiveState
08-23 08:45:35.246  1030  1515 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.246  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.246  1030  1515 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-23 08:45:35.247  1030  1517 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 08:45:35.247  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 08:45:35.247  1030  1517 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 08:45:35.248  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:35.248  1030  1517 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-23 08:45:35.248  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-23 08:45:35.248  8000  8000 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 08:45:35.248  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.249  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.250  6716  8060 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 881)
08-23 08:45:35.250  1921  8059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 08:45:35.251  1921  8059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:35.251  1921  8059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:35.251  1030  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 08:45:35.251  1030  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:35.251  1030  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:35.251  1030  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:35.251  1030  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:35.251  1030  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.251  1030  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.252  1030  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.252  1030  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:35.252  1030  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.252  1030  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.252  1030  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.252  6716  8060 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44593
08-23 08:45:35.252  1030  1515 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-23 08:45:35.252  6716  8060 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-23 08:45:35.253  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-23 08:45:35.253  8000  8000 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:35.254  1030  1515 D LGWifiP2pService: InactiveState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.254  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-23 08:45:35.254  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.254  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:35.254  1030  1515 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.254  1030  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE i,nit=USER type=COUNTRY alpha2=CZ
08-23 08:45:35.254  1030  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-23 08:45:35.254  1030  1515 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.254  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.254  8000  8000 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-23 08:45:35.254  1030  1515 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.254  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.255  8000  8000 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.255  1921  2257 W WfdsService: DefaultState - msg [9441285] is not handled
08-23 08:45:35.255  1030  1517 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-23 08:45:35.255  1030  1515 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.255  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.255  1030  1515 D LGWifiP2pService: DefaultState{ when=-9ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.255  1030  1517 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-23 08:45:35.255  1030  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:35.255  1030  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.255  1030  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.256  1030  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.256  1921  8059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:35.256  1921  8059 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:35.256  1030  1515 D LGWifiP2pService: InactiveState{ when=-10ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.256  1030  8058 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-23 08:45:35.256  1030  8058 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.256  1030  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.256  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.256  1030  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-23 08:45:35.256  1030  1515 D LGWifiP2pService: DefaultState{ when=-11ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.256  1030  1030 E WifiServerServiceExt: No p2p device connected
08-23 08:45:35.257  1030  1515 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.257  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.257  1030  1517 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
,08-23 08:45:35.257  1030  1517 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-23 08:45:35.257  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-23 08:45:35.257  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-23 08:45:35.258  8000  8000 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 08:45:35.258  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-23 08:45:35.258  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 08:45:35.258  1030  8058 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 08:45:35.258  1030  8058 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-23 08:45:35.258  1030  1517 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-23 08:45:35.258  1030  1517 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-23 08:45:35.259  1030  1517 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-23 08:45:35.259  1030  1517 D WifiNative-wlan0: doBoolean: SCAN
08-23 08:45:35.259  1030  1517 D WifiNative-wlan0: SCAN: returned false
,08-23 08:45:35.259  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=200280  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-23 08:45:35.261  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.261  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:35.262  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.262  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.262  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 08:45:35.262  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.264  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=200285  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-23 08:45:35.265  1030  1517 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:35.265  1030  1517 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:35.265  1030  1517 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:35.266  1030  1517 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:35.266  1030  1517 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-23 08:45:35.267  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:35.267  1030  1030 D WifiServerServiceExt: setSupplicantStateSCANNING
08-23 08:45:35.282  8040  8040 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 08:45:35.285  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 08:45:35.289  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:35.290  1030  1920 I ActivityManager: Killing 7173:com.lge.drmservice/u0a62 (adj 15): empty #17
08-23 08:45:35.329  1030  1676 W libprocessgroup: failed to open /acct/uid_10062/pid_7173/cgroup.procs: No such file or directory
,08-23 08:45:35.377  8040  8040 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-23 08:45:35.385  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-23 08:45:35.390  8019  8064 W FormManager: Network not available. Please check & try again.
08-23 08:45:35.395  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:35.402  8019  8065 V FormManager: Network unavailable.
08-23 08:45:35.406  8019  8065 V FormManager: Network unavailable.
08-23 08:45:35.424  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 08:45:35.425  4769  4769 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-23 08:45:35.429  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:35.435  4769  4769 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-23 08:45:35.441  4769  8066 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-23 08:45:35.447  4769  8067 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-23 08:45:35.448  4769  8067 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-23 08:45:35.525  1030  1956 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8068 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-23 08:45:35.645  8068  8068 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-23 08:45:35.646  8068  8068 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-23 08:45:35.658  8068  8068 V [BNRBootReceiver]: Boot Receiver Return
08-23 08:45:35.659  8068  8068 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-23 08:45:35.672  8000  8000 E wpa_supplicant: USIM:  scard_init function
08-23 08:45:35.673  8000  8000 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-23 08:45:35.676  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-23 08:45:35.676  1030  8058 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-23 08:45:35.676  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-23 08:45:35.676  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-23 08:45:35.676  1030  8058 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-23 08:45:35.677  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-23 08:45:35.677  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-23 08:45:35.679  1030  1517 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-23 08:45:35.680  1030  1517 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-23 08:45:35.681  1030  1517 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-23 08:45:35.682  1030  1517 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-23 08:45:35.685  1030  1517 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-23 08:45:35.738  1030  1555 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 08:45:35.741  1030  1555 I ActivityManager: Killing 7192:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-23 08:45:35.782  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=200802  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-23 08:45:35.783  1030  1974 W libprocessgroup: failed to open /acct/uid_10085/pid_7192/cgroup.procs: No such file or directory
,08-23 08:45:35.786  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=200807  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-23 08:45:35.792  8000  8000 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-23 08:45:35.797  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-23 08:45:35.797  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-23 08:45:35.797  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-23 08:45:35.797  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-23 08:45:35.798  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-23 08:45:35.798  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:35.799  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=200819  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 08:45:35.799  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=200820  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-23 08:45:35.801  8000  8000 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 08:45:35.801  8000  8000 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 08:45:35.801  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.801  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:35.802  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.802  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.802  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-23 08:45:35.802  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 08:45:35.802  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:35.802  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.803  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.803  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-23 08:45:35.803  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-23 08:45:35.803  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:35.803  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 08:45:35.803  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-23 08:45:35.803  1030  8058 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 08:45:35.803  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-23 08:45:35.803  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 08:45:35.803  1030  8058 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-23 08:45:35.803  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 08:45:35.803  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:35.806  1030  1113 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-23 08:45:35.806  1030  1517 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200827
08-23 08:45:35.807  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 08:45:35.809  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.809  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:35.811  1030  1517 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200831
08-23 08:45:35.811  1030  1517 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200832
08-23 08:45:35.812  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200832
08-23 08:45:35.812  1030  1517 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=200833
08-23 08:45:35.813  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.815  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=200835  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 08:45:35.817  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=200837  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-23 08:45:35.818  1030  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=200838  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-23 08:45:35.819  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=200839  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-23 08:45:35.819  1030  1517 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=200840
08-23 08:45:35.820  1030  1517 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=200841
08-23 08:45:35.821  1030  1517 D WifiNative-wlan0: doString: [STATUS]
08-23 08:45:35.822  1030  8058 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-23 08:45:35.822  1030  8058 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-23 08:45:35.823  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.823  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.823  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-23 08:45:35.823  1030  1517 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-23 08:45:35.825  1030  1517 I WifiServiceExtension: setVHTCapabilityType  : false
08-23 08:45:35.825  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.825  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.825  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-23 08:45:35.825  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:35.825  1030  1030 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-23 08:45:35.831  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.831  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:35.832  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.832  1030  1517 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-23 08:45:35.832  1030  1517 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-23 08:45:35.838  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.838  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.838  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 08:45:35.840  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.840  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.840  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-23 08:45:35.842  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.842  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:35.843  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.846  1030  1517 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-23 08:45:35.846  1030  1523 D ConnectivityService: Got NetworkAgent Messenger
08-23 08:45:35.846  1030  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 08:45:35.846  1030  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 08:45:35.846  1030  1523 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-23 08:45:35.846  1030  1523 D ConnectivityService: NetworkAgent connected
08-23 08:45:35.846  1030  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 08:45:35.846  1030  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 08:45:35.852  1030  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 08:45:35.852  1030  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 08:45:35.852  1030  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-23 08:45:35.853  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.853  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-23 08:45:35.855  1030  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-23 08:45:35.855  1030  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-23 08:45:35.856  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.858  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.858  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:35.859  8089  8089 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 08:45:35.859  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.860  1030  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-23 08:45:35.861   308   888 D CommandListener: Setting iface cfg
08-23 08:45:35.863  1030  1517 E WifiStateMachine: Start Dhcp Watchdog 3
08-23 08:45:35.863  1030  8111 D DhcpStateMachine: StoppedState
08-23 08:45:35.863  1030  8111 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.863  1030  8111 D DhcpStateMachine: WaitBeforeStartState
08-23 08:45:35.864  1030  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=200884  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:35.864  1030  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=200885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:35.865  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=200885  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:35.865  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,08-23 08:45:35.866  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.866  1030  1517 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.867  1030  1517 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.867  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.867  1030  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-23 08:45:35.868  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:35.868  1030  1030 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-23 08:45:35.869  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:35.869  1030  1030 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-23 08:45:35.870  1030  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=200890  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:35.870  1030  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=200891  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:35.871  1030  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=200891  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-23 08:45:35.872  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14168] from screen [on:0 period:-1239046656] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-23 08:45:35.873  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1239046655] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-23 08:45:35.873  1030  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-23 08:45:35.877  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.878  1030  1523 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-23 08:45:35.878  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:35.878  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:35.879  1030  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:35.879  1030  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:35.880  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:35.880  1030  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-23 08:45:35.880  1030  1523 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-23 08:45:35.881  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=165,0,0
08-23 08:45:35.881  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=165,0,0
08-23 08:45:35.881  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-23 08:45:35.882  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-23 08:45:35.883  1030  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-23 08:45:35.883  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 0
08-23 08:45:35.883  1030  1517 D WifiNative-wlan0: SET ps 0: returned true
08-23 08:45:35.883  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-23 08:45:35.883  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-23 08:45:35.884  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
,08-23 08:45:35.884  1030  1515 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@27e16aa0 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.884  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@27e16aa0 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.885  1030  8111 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.885  1030  8111 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-23 08:45:35.886  1030  1517 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-23 08:45:35.886  1030  1517 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 08:45:35.886  1030  1517 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 08:45:35.888   308   888 D CommandListener: Setting iface cfg
08-23 08:45:35.888   308   888 D CommandListener: Trying to bring up wlan0
08-23 08:45:35.889  1030  1517 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-23 08:45:35.890  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-23 08:45:35.891  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-23 08:45:35.891  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-23 08:45:35.891  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-23 08:45:35.891  1030  1030 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-23 08:45:35.891  1030  1030 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-23 08:45:35.892  1030  1515 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.892  1030  1515 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.892  1030  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-23 08:45:35.892  1030  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-23 08:45:35.893  8000  8000 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-23 08:45:35.893  1030  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-23 08:45:35.893  1030  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-23 08:45:35.900  8089  8089 D PluginManager: init()
,08-23 08:45:35.908  1030  1517 D WifiNative-wlan0: SET ps 1: returned true
08-23 08:45:35.909  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:35.910  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:35.910  1030  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:35.911  1030  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:35.911  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:35.912  1030  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:35.912  1030  1517 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 08:45:35.913  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-23 08:45:35.913  1030  1517 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-23 08:45:35.914  1030  1523 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-23 08:45:35.914  1030  1523 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-23 08:45:35.914  1030  1523 D ConnectivityService: ignoring duplicate network state non-change
08-23 08:45:35.919  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.919  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-23 08:45:35.920  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.920  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.921  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.921  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 08:45:35.924  1030  1523 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-23 08:45:35.924  1030  1523 D ConnectivityService: Adding iface wlan0 to network 102
08-23 08:45:35.929  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.930  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.930  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-23 08:45:35.932  1030  1517 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 08:45:35.934  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-23 08:45:35.937  1921  1921 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-23 08:45:35.941  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.941  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.941  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 08:45:35.942  1030  1030 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-23 08:45:35.948  1030  1523 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 08:45:35.949  1030  1523 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-23 08:45:35.950  1030  1523 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-23 08:45:35.951  1030  1030 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.951  1030  1030 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 08:45:35.951  1030  1030 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-23 08:45:35.951   308   888 E Netd    : netlink response contains error (File exists)
08-23 08:45:35.952  1030  1523 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-23 08:45:35.952  1030  1523 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-23 08:45:35.953  1030  1523 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-23 08:45:35.953  1030  1523 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-23 08:45:35.954  1030  1523 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-23 08:45:35.954  1030  1523 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-23 08:45:35.954  1030  1523 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-23 08:45:35.954  1030  1523 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-23 08:45:35.954  1030  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.954  1030  1523 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:35.954  1030  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-23 08:45:35.954  1030  1523 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:35.954  1030  1523 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-23 08:45:35.954  1030  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-23 08:45:35.954  1030  1523 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:35.954  1030  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-23 08:45:35.954  1030  1523 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-23 08:45:35.954  1030  1523 D ConnectivityService: currentScore = 0, newScore = 20
08-23 08:45:35.954  1030  1523 D ConnectivityService:    accepting network in place of null
08-23 08:45:35.954  1030  1523 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:35.955  1832  1832 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:35.955  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.955  1832  1832 D TelephonyNetworkFact,ory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 08:45:35.956  1583  1583 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-23 08:45:35.958  1030  1523 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-23 08:45:35.958  1030  1523 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-23 08:45:35.958  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-23 08:45:35.959  1030  1517 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 08:45:35.959  1030  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:35.959  1030  1523 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-23 08:45:35.959   308  8116 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-23 08:45:35.959  1030  1523 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-23 08:45:35.960  1030  1523 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-23 08:45:35.961  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:35.964  1030  1030 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-23 08:45:35.964  1030  1523 D ConnectivityService: validation of new default Network = false
,08-23 08:45:35.964  1030  1523 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-23 08:45:35.964  1030  1523 D DSQN    : enableDataServiceNotify 
08-23 08:45:35.964  1030  1523 D DSQN    : start dsqn bin
08-23 08:45:35.964  1030  1030 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-23 08:45:35.964  1030  1030 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-23 08:45:35.964  1030  1030 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-23 08:45:35.969  1030  1523 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-23 08:45:35.969  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:35.969  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:35.970  1030  1523 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:35.970  1583  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 08:45:35.961  8117  8117 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:35.961  8117  8117 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-23 08:45:35.971  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.975  1030  1514 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-23 08:45:35.981  8117  8117 E DSQN    : DSQN ssw
08-23 08:45:35.982  1583  1583 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 08:45:35.982  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 08:45:35.984  1583  1583 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-23 08:45:35.984  1583  1583 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-23 08:45:35.984  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-23 08:45:36.002  1583  1583 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-23 08:45:36.003  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:36.003  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:36.012   308  8116 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-23 08:45:36.043   308  8116 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-23 08:45:36.069   308   887 D LGDataListener: argv[0]=dsqncommand
,08-23 08:45:36.069   308   887 D LGDataListener: argv[1]=wlan0
,08-23 08:45:36.069   308   887 D LGDataListener: argv[2]=1
08-23 08:45:36.069   308   887 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-23 08:45:36.070  1030  1111 D DSQN    : DSQM DsqnNotification wlan0  1
,08-23 08:45:36.070  1030  1111 D DSQN    : start to monitor internet connection
08-23 08:45:36.087  1030  8111 D DhcpStateMachine: DHCPV4 request on wlan0
08-23 08:45:36.087  1030  8111 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-23 08:45:36.087  1030  8111 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-23 08:45:36.081  8124  8124 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:36.081  8124  8124 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-23 08:45:36.093  1030  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 06:45:36 GMT], X-Android-Received-Millis=[1471934736092], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471934736068]}
08-23 08:45:36.093  1030  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-23 08:45:36.093  1030  8106 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-23 08:45:36.093  1030  1523 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-23 08:45:36.093  1030  1523 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-23 08:45:36.094  1030  1523 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:36.094  1030  1523 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:36.094  1030  1523 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false,
,08-23 08:45:36.094  1030  1523 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-23 08:45:36.094  1030  1523 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-23 08:45:36.095  8124  8124 I dhcpcd  : version 5.5.6 starting
08-23 08:45:36.095  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:36.095  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:36.096  8124  8124 E dhcpcd  : get_duid: m
08-23 08:45:36.096  8124  8124 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-23 08:45:36.096  8124  8124 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-23 08:45:36.097  1030  1523 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:36.098  1030  1523 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:36.098  1583  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-23 08:45:36.099  1832  1832 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:36.100  1832  1832 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-23 08:45:36.100  1030  1523 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-23 08:45:36.102  1030  1517 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:36.102  1030  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-23 08:45:36.124  1583  1583 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-23 08:45:36.125  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:36.126  1583  1583 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-23 08:45:36.145  8124  8124 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 08:45:36.145  8124  8124 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 08:45:36.145  8124  8124 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 08:45:36.145  8124  8124 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-23 08:45:36.145  8124  8124 D dhcpcd  : wlan0: sending REQUEST (xid 0x84876d0), next in 3.58 seconds
,08-23 08:45:36.247  6716  6818 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 882)
,08-23 08:45:36.247  6716  6818 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 882)
,08-23 08:45:36.254  8124  8124 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-23 08:45:36.258  6716  6818 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 887)
,08-23 08:45:36.261  6716  6818 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-23 08:45:36.261  6716  6818 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 888)
,08-23 08:45:36.271  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 08:45:36.271  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@276ab2cf added. We now have 2 listener(s)
,08-23 08:45:36.272  1030  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.277  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.277  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.277  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.277  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 08:45:36.277  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2603645c added. We now have 9 listener(s)
08-23 08:45:36.277  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:45:36.277  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 08:45:36.281  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 08:45:36.287  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:36.287  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:36.287  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:36.287  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:36.287  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:36.287  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.287  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:36.287  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:36.287  8089  8089 W ExternalStrings: load override strings
08-23 08:45:36.287  8089  8089 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 08:45:36.287  8089  8089 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 08:45:36.289  8089  8089 D StatusProvider: onCreate
,08-23 08:45:36.290  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.290  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:36.291  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.291  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fd7983a added. We now have 3 listener(s)
08-23 08:45:36.292  1030  1676 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.292  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.295  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.300  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.301  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.301  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.301  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.301  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@609aceb added. We now have 10 listener(s)
08-23 08:45:36.301  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:36.301  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:36.301  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:36.301  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:36.301  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.301  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.302  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:36.302  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.302  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@276ab2cf removed from the list
08-23 08:45:36.302  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.302  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2603645c removed from the list
08-23 08:45:36.302  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:36.302  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.303  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.303  6716  6818 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.304  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.305  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.305  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.305  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2603645c not in the list
08-23 08:45:36.305  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.305  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:45:36.305  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.305  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.305  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.306  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@609aceb removed from the list
08-23 08:45:36.306  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.306  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.306  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.306  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.306  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fd7983a removed from the list
08-23 08:45:36.306  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.306  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d906a48 added. We now have 2 listener(s)
08-23 08:45:36.308  1030  2029 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.311  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.311  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.311  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.311  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.311  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@228f60e1 added. We now have 9 listener(s)
,08-23 08:45:36.311  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:36.312  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 08:45:36.315  8124  8124 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-23 08:45:36.315  8124  8124 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-23 08:45:36.316  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:36.317  8124  8124 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-23 08:45:36.317  8124  8124 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-23 08:45:36.318  8124  8124 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-23 08:45:36.318  8124  8124 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-23 08:45:36.318  8124  8124 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-23 08:45:36.318  8124  8124 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-23 08:45:36.322  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:36.322  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:36.322  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:36.322  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:36.322  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:36.322  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.322  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:36.322  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:36.324  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.324  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:36.325  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.325  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11542cc7 added. We now have 3 listener(s)
08-23 08:45:36.325  1030  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.327  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.328  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.328  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.328  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.328  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.328  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.328  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f65e2f4 added. We now have 10 listener(s)
08-23 08:45:36.329  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:36.329  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:45:36.329  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:45:36.329  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:45:36.329  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:36.329  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 08:45:36.332  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 08:45:36.332  1030  2006 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 for,egroundUser=0
,08-23 08:45:36.336  8089  8089 V Signer  : override build config not found
,08-23 08:45:36.337  8089  8089 D Signer  : value of property debug is false
08-23 08:45:36.337  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 08:45:36.338  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 08:45:36.339  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 08:45:36.340  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:36.341  6716  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 08:45:36.341  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:36.341  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:36.343  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:36.343  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:36.343  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:36.344  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.344  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.344  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:36.344  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.344  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d906a48 removed from the list
08-23 08:45:36.344  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.344  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@228f60e1 removed from the list
08-23 08:45:36.344  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:36.344  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.345  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.345  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.346  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.346  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.346  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 08:45:36.346  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@228f60e1 not in the list
08-23 08:45:36.346  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.346  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 08:45:36.355  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.356  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:36.356  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 08:45:36.356  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.356  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.356  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f65e2f4 removed from the list
08-23 08:45:36.356  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.356  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.356  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.356  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.356  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11542cc7 removed from the list
08-23 08:45:36.356  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.356  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddcce63 added. We now have 2 listener(s)
08-23 08:45:36.365  1030  1676 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.368  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.368  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.368  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.369  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-23 08:45:36.369  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-23 08:45:36.370  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.370  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31783a60 added. We now have 9 listener(s)
08-23 08:45:36.370  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:36.370  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-23 08:45:36.370  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 08:45:36.370  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-23 08:45:36.370  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-23 08:45:36.370  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-23 08:45:36.371  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-23 08:45:36.371  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-23 08:45:36.371  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-23 08:45:36.371  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-23 08:45:36.371  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-23 08:45:36.371  8089  8089 D LGMDMWrap,per: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-23 08:45:36.371  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-23 08:45:36.373  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:36.377  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:36.377  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:36.377  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:36.377  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:36.377  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:36.377  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.377  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:36.377  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:36.379  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.379  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:36.379  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.379  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2209c7de added. We now have 3 listener(s)
08-23 08:45:36.379  1030  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.380  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.383  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.385  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.385  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.385  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.385  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.386  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc3edbf added. We now have 10 listener(s)
08-23 08:45:36.386  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 08:45:36.386  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:45:36.386  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:45:36.386  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:45:36.386  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:45:36.386  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:36.386  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 08:45:36.391  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 08:45:36.391  1030  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.395  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 08:45:36.396  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 08:45:36.398  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-23 08:45:36.398  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:36.400  6716  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 08:45:36.400  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:36.400  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:36.400  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:36.405  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.405  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.405  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:36.405  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.405  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddcce63 removed from the list
08-23 08:45:36.405  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.405  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31783a60 removed from the list
08-23 08:45:36.405  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:36.405  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.406  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.406  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.406  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.406  8089  8089 V LGMDMManager: Create singleton instance
08-23 08:45:36.406  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.406  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.406  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31783a60 not in the list
08-23 08:45:36.406  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.406  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.407  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 08:45:36.407  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:36.407  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:36.407  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.407  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.407  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc3edbf removed from the list
08-23 08:45:36.407  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.408  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.408  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.408  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.408  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2209c7de removed from the list
08-23 08:45:36.408  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.408  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66683ea added. We now have 2 listener(s)
08-23 08:45:36.409  1030  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.411  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.411  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.411  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.411  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.411  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d3a6db added. We now have 9 listener(s)
08-23 08:45:36.411  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:36.411  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 08:45:36.413  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:36.416  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:36.416  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:36.416  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:36.416  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:36.416  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:36.416  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.416  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:36.416  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network t,ype is Wi-Fi: true
08-23 08:45:36.417  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.417  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:36.417  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.417  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fa14451 added. We now have 3 listener(s)
08-23 08:45:36.417  1030  1901 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.419  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.420  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.421  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.421  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.421  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.421  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.421  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220f4b6 added. We now have 10 listener(s)
08-23 08:45:36.421  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:36.421  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:45:36.421  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 08:45:36.421  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 08:45:36.421  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:36.421  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 08:45:36.423  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 08:45:36.423  1030  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 08:45:36.426  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-23 08:45:36.426  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 08:45:36.427  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 08:45:36.427  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:36.429  6716  6818 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-23 08:45:36.430  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:36.430  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:36.430  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:36.430  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.430  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.430  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:36.430  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.430  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66683ea removed from the list
08-23 08:45:36.430  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.430  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d3a6db removed from the list
08-23 08:45:36.430  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:36.430  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.431  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.431  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.431  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.431  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.431  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.431  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d3a6db not in the list
08-23 08:45:36.431  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.431  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.432  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.432  6716  6818 D BluetoothLeScanner: could not find callback wrapper
08-23 08:45:36.432  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 08:45:36.432  6716  6818 I ,org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.432  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.432  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@220f4b6 removed from the list
08-23 08:45:36.432  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.432  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.432  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.432  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.432  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fa14451 removed from the list
08-23 08:45:36.433  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.433  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18e4d48d added. We now have 2 listener(s)
08-23 08:45:36.433  1030  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.434  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.434  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.434  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.434  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.435  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43fa642 added. We now have 9 listener(s)
08-23 08:45:36.435  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:36.435  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 08:45:36.437  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 08:45:36.439  6716  6818 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 08:45:36.439  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 08:45:36.439  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 08:45:36.439  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 08:45:36.439  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 08:45:36.439  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 08:45:36.439  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 08:45:36.439  6716  6818 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 08:45:36.440  6716  6818 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 08:45:36.440  6716  6818 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 08:45:36.441  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.442  6716  6716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 08:45:36.441  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 08:45:36.442  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15befb90 added. We now have 3 listener(s)
08-23 08:45:36.442  1030  1555 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 08:45:36.444  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 08:45:36.444  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 08:45:36.444  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 08:45:36.444  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 08:45:36.444  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14572c89 added. We now have 10 listener(s)
08-23 08:45:36.444  6716  6818 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 08:45:36.444  6716  6818 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 08:45:36.444  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 08:45:36.444  6716  6818 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 08:45:36.445  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.445  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.445  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 08:45:36.445  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.445  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18e4d48d removed from the list
08-23 08:45:36.445  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.445  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43fa642 removed from the list
08-23 08:45:36.445  6716  6818 D io.jxcore.node.ConnectivityMonitor: stop
08-23 08:45:36.445  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.446  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.446  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.447  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.447  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.447  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.447  6716  6818 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43fa642 not in the list
,08-23 08:45:36.447  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.447  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.448  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 08:45:36.448  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 08:45:36.448  6716  6818 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 08:45:36.448  6716  6818 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14572c89 removed from the list
08-23 08:45:36.448  6716  6818 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 08:45:36.448  6716  6818 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 08:45:36.448  6716  6818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 08:45:36.448  6716  6818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 08:45:36.448  6716  6818 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15befb90 removed from the list
08-23 08:45:36.448  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-23 08:45:36.448  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-23 08:45:36.449  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 08:45:36.449  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 08:45:36.449  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 08:45:36.449  6716  6818 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 08:45:36.455  6716  8155 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 895, name: My test thread name)
08-23 08:45:36.455  6716  8155 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 895, thread name: My test thread name)
08-23 08:45:36.456  6716  8155 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 895, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 08:45:36.457  6716  8156 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 897, name: My test thread name)
08-23 08:45:36.457  6716  8156 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 897, thread name: My test thread name)
08-23 08:45:36.458  6716  8156 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 897, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 08:45:36.459  6716  6818 D com.test.thalitest.ThaliTestRunner,: Total number of executed tests: 80
08-23 08:45:36.459  6716  6818 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-23 08:45:36.459  6716  6818 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-23 08:45:36.459  6716  6818 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-23 08:45:36.459  6716  6818 D com.test.thalitest.ThaliTestRunner: Total duration: 22971 ms
08-23 08:45:36.460  6716  6818 I jxcore-log: Total number of executed tests:  80
08-23 08:45:36.460  6716  6818 I jxcore-log: 
08-23 08:45:36.460  6716  6818 I jxcore-log: Number of passed tests:  80
08-23 08:45:36.460  6716  6818 I jxcore-log: 
08-23 08:45:36.460  6716  6818 I jxcore-log: Number of failed tests:  0
08-23 08:45:36.460  6716  6818 I jxcore-log: 
08-23 08:45:36.460  6716  6818 I jxcore-log: Number of ignored tests:  0
08-23 08:45:36.460  6716  6818 I jxcore-log: 
08-23 08:45:36.460  6716  6818 I jxcore-log: Total duration:  22971
08-23 08:45:36.460  6716  6818 I jxcore-log: 
08-23 08:45:36.460  6716  6818 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 08:45:36.460  6716  6818 I jxcore-log: 
,08-23 08:45:36.465  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.465  6716  6818 I jxcore-log: 
08-23 08:45:36.468  6716  6716 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 08:45:36.468  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.468  6716  6818 I jxcore-log: 
08-23 08:45:36.470  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.470  6716  6818 I jxcore-log: 
08-23 08:45:36.471  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.471  6716  6818 I jxcore-log: 
08-23 08:45:36.472  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.472  6716  6818 I jxcore-log: 
08-23 08:45:36.473  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.473  6716  6818 I jxcore-log: 
,08-23 08:45:36.476  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.476  6716  6818 I jxcore-log: 
08-23 08:45:36.478  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 08:45:36.478  6716  6818 I jxcore-log: 
08-23 08:45:36.479  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 08:45:36.479  6716  6818 I jxcore-log: 
08-23 08:45:36.480  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.480  6716  6818 I jxcore-log: 
08-23 08:45:36.481  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.481  6716  6818 I jxcore-log: 
08-23 08:45:36.482  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 08:45:36.482  6716  6818 I jxcore-log: 
08-23 08:45:36.483  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 08:45:36.483  6716  6818 I jxcore-log: 
08-23 08:45:36.484  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 08:45:36.484  6716  6818 I jxcore-log: 
08-23 08:45:36.485  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.485  6716  6818 I jxcore-log: 
08-23 08:45:36.486  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.486  6716  6818 I jxcore-log: 
08-23 08:45:36.487  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.487  6716  6818 I jxcore-log: 
08-23 08:45:36.487  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.487  6716  6818 I jxcore-log: 
08-23 08:45:36.488  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.488  6716  6818 I jxcore-log: 
08-23 08:45:36.489  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.489  6716  6818 I jxcore-log: 
,08-23 08:45:36.490  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.490  6716  6818 I jxcore-log: 
08-23 08:45:36.490  1030  8111 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-23 08:45:36.490  8089  8089 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-23 08:45:36.490  1030  8111 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-23 08:45:36.491  1030  8111 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-23 08:45:36.491  1030  8111 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-23 08:45:36.491  1030  8111 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-23 08:45:36.491  1030  8111 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-23 08:45:36.491  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 08:45:36.491  6716  6818 I jxcore-log: 
08-23 08:45:36.491  1030  8111 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-23 08:45:36.491  1030  8111 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-23 08:45:36.491  1030  8111 D DhcpStateMachine: RunningState
08-23 08:45:36.492  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 08:45:36.492  6716  6818 I jxcore-log: 
08-23 08:45:36.494  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 08:45:36.494  6716  6818 I jxcore-log: 
08-23 08:45:36.494  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.494  6716  6818 I jxcore-log: 
08-23 08:45:36.496  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.496  6716  6818 I jxcore-log: 
08-23 08:45:36.498  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.498  6716  6818 I jxcore-log: 
08-23 08:45:36.499  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.499  6716  6818 I jxcore-log: 
08-23 08:45:36.500  6716  6818 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 08:45:36.500  6716  6818 I jxcore-log: 
08-23 08:45:36.550  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:36.553  8089  8165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 08:45:36.559  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:36.563  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:36.601  1030  1920 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8168 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-23 08:45:36.602  1030  1920 I ActivityManager: Killing 7229:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-23 08:45:36.697  8089  8162 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-23 08:45:36.779  8163  8163 D AndroidRuntime: 
08-23 08:45:36.779  8163  8163 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 08:45:36.784  8163  8163 D AndroidRuntime: CheckJNI is OFF
08-23 08:45:36.837  1030  1892 W libprocessgroup: failed to open /acct/uid_10093/pid_7229/cgroup.procs: No such file or directory
,08-23 08:45:36.914  8168  8168 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 08:45:36.940  8168  8168 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-23 08:45:36.969  8168  8168 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-23 08:45:36.969  8168  8168 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-23 08:45:36.969  8168  8168 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-23 08:45:36.971  8168  8168 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-23 08:45:36.971  8168  8168 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-23 08:45:36.973  8168  8168 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-23 08:45:36.973  8089  8162 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:36.973  8089  8162 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:36.978  8163  8163 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 08:45:36.987  8168  8168 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-23 08:45:36.989  1030  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-23 08:45:36.989  1030  1105 I ActivityManager: Killing 6716:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-23 08:45:36.999  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 08:45:37.005  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 08:45:37.043  1030  2006 I WindowState: WIN DEATH: Window{b03a7c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 08:45:37.044  1030  1522 D WifiService: Client connection lost with reason: 4
08-23 08:45:37.051  1030  2006 D InputDispatcher: Window went away: Window{b03a7c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 08:45:37.131  8089  8162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-23 08:45:37.261  1030  1105 I ActivityManager:   Force finishing activity ActivityRecord{12974e4f u0 com.test.thalitest/.MainActivity t6}
,08-23 08:45:37.300   344   350 E GBMv2   : DFP En is all cleared set to be enabled
08-23 08:45:37.301  1030  1956 W ActivityManager: Spurious death for ProcessRecord{316e652c 6716:com.test.thalitest/u0a118}, curProc for 6716: null
,08-23 08:45:37.305  8168  8168 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-23 08:45:37.306  1921  2700 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-23 08:45:37.307  1921  2700 D SplitWindowPolicy: topRunningActivity=ActivityInfo{34e94595 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 08:45:37.309  1921  1936 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-23 08:45:37.309  1921  1936 D SplitWindowPolicy: topRunningActivity=ActivityInfo{c436aa co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 08:45:37.318  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-23 08:45:37.321  8168  8168 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-23 08:45:37.321  1030  1119 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-23 08:45:37.326  8168  8168 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-23 08:45:37.330  6865  6865 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-23 08:45:37.356  2012  2012 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-23 08:45:37.357  8089  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-23 08:45:37.357  2012  2012 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-23 08:45:37.364  1583  1583 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-23 08:45:37.376  2488  2612 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 08:45:37.377  8089  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-23 08:45:37.381  1975  1975 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 08:45:37.381  8089  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-23 08:45:37.382  3778  3778 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-23 08:45:37.382  7682  7682 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-23 08:45:37.382  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-23 08:45:37.384  8089  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-23 08:45:37.410  1030  1407 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 08:45:37.414  5031  5031 I art     : Explicit concurrent mark sweep GC freed 8224(470KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 582us total 77.090ms
08-23 08:45:37.429  1030  1920 V SIM_STK : Menu title from STK is T-Mobile
,08-23 08:45:37.432  1030  1103 W InputMethodInfo: Duplicated subtype definition found: , voice
08-23 08:45:37.467  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:37.469  8089  8165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 08:45:37.471  4930  4930 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 08:45:37.471  4930  4930 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 08:45:37.471  4930  4930 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 08:45:37.471  4930  4930 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-23 08:45:37.471  4930  4930 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-23 08:45:37.472  4930  4930 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 08:45:37.472  4930  4930 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 08:45:37.472  4930  4930 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 08:45:37.472  4930  4930 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:45:37.472  4930  4930 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:45:37.472  4930  4930 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 08:45:37.472  4930  4930 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 08:45:37.474  8089  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-23 08:45:37.474  2012  2012 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-23 08:45:37.474  8089  8162 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-23 08:45:37.475  2012  2077 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-23 08:45:37.497  2012  2012 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-23 08:45:37.497  1883  1883 D ActionManagerService: notifyUserLog: 1000003
08-23 08:45:37.498  8089  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-23 08:45:37.498  3778  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-23 08:45:37.499  2012  2012 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 08:45:37.501  2012  2012 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-23 08:45:37.501  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 08:45:37.501  2012  2012 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-23 08:45:37.507  1583  1583 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-23 08:45:37.508  2012  2012 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-23 08:45:37.509  8089  8162 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-23 08:45:37.509  1883  1883 D ActionManagerService: notifyUserLog: 1000004
08-23 08:45:37.513  3778  3793 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , create_time: 1430832262123
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , expire_time: 0
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , display: false
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , animation: false }
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , create_time: 1430832262287
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , expire_time: 0
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , display: false
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , animation: false }
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , create_time: 1471602816196
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , expire_time: 0
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , display: false
08-23 08:45:37.515  2012  2012 I GBoardWebViewUtils: , animation: false }
08-23 08:45:37.516  3778  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-23 08:45:37.517  1583  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 08:45:37.517  1583  1643 D KeyguardModel: createShortcutInfo...
,08-23 08:45:37.520  2012  8227 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-23 08:45:37.527  1583  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 08:45:37.527  1583  1643 D KeyguardModel: createShortcutInfo...
08-23 08:45:37.530  1849  1849 D SplitUIManager: split_name #11 / not available #0
08-23 08:45:37.531  1849  1849 D SplitUIService: removed split : 
08-23 08:45:37.535  1583  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 08:45:37.535  1030  1678 V SIM_STK : Menu title from STK is T-Mobile
08-23 08:45:37.535  1030  1678 V SIM_STK : Menu title from STK is T-Mobile
,08-23 08:45:37.537  1583  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:45:37.537  1583  1643 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 08:45:37.538  1583  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 08:45:37.539  1583  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 08:45:37.539  1583  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 08:45:37.541  1583  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 08:45:37.541  1583  1643 D KeyguardModel: createShortcutInfo...
08-23 08:45:37.545  1583  1643 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 08:45:37.545  1583  1643 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 08:45:37.545  1583  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 08:45:37.546  1583  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 08:45:37.547  1583  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 08:45:37.547  1583  1643 D KeyguardModel: createShortcutInfo...
,08-23 08:45:37.549  1583  1583 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-23 08:45:37.549  1583  1583 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 08:45:37.560  2012  2012 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 08:45:37.561  2012  2012 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-23 08:45:37.567  1583  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:45:37.567  1583  1643 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 08:45:37.567  1583  1643 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 08:45:37.567  1583  1643 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 08:45:37.569  1583  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 08:45:37.569  1583  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 08:45:37.573  1583  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 08:45:37.573  1583  1643 D KeyguardModel: createShortcutInfo...
,08-23 08:45:37.575  1849  1849 D SplitUIManager: split_name #11 / not available #0
,08-23 08:45:37.575  1849  1849 I SplitUIService: split app #11
08-23 08:45:37.575  1583  1583 D KeyguardModel: handleShortcutListChanged...
08-23 08:45:37.575  1583  1583 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 08:45:37.577  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:37.581  1583  1643 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 08:45:37.581  1583  1643 D KeyguardModel: createShortcutInfo...
08-23 08:45:37.581  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.582  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.582  8168  8168 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-23 08:45:37.584  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:37.586  1583  1643 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 08:45:37.587  1583  1643 D KeyguardModel: createShortcutInfo...
08-23 08:45:37.587  1583  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 08:45:37.588  1583  1643 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 08:45:37.588  1583  1643 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 08:45:37.588  1583  1643 D KeyguardModel: createShortcutInfo...
08-23 08:45:37.589  1583  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 08:45:37.589  1583  1643 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 08:45:37.590  1583  1643 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 08:45:37.590  1583  1643 D KeyguardModel: createShortcutInfo...
08-23 08:45:37.590  1030  1030 D administrator: Handling package changes for user 0
08-23 08:45:37.593  1030  2011 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-23 08:45:37.593  1583  1643 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 08:45:37.593  1583  1643 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 08:45:37.593  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 08:45:37.593  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 08:45:37.594  7682  7682 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 08:45:37.594  1583  1643 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 08:45:37.594  1583  1643 D KeyguardModel: createShortcutInfo...
08-23 08:45:37.595  8089  8165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 08:45:37.600  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:37.608  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:37.609  1030  1555 V SIM_STK : Menu title from STK is T-Mobile
08-23 08:45:37.623  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.623  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.623  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 08:45:37.629  1583  1583 D KeyguardModel: handleShortcutListChanged...
08-23 08:45:37.629  1583  1583 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 08:45:37.634  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-23 08:45:37.634  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-23 08:45:37.634  6865  6865 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-23 08:45:37.635  6865  6865 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-23 08:45:37.642  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-23 08:45:37.650  6865  6865 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-23 08:45:37.650  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-23 08:45:37.650  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-23 08:45:37.650  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-23 08:45:37.651  6865  6865 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-23 08:45:37.651  6865  6865 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-23 08:45:37.651  6865  6865 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-23 08:45:37.653  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:37.653  8089  8165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 08:45:37.656  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:37.669  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:37.674  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.674  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.674  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 08:45:37.679  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:37.679  8089  8165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 08:45:37.684  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 08:45:37.685  1030  1030 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 08:45:37.685  1030  1030 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 08:45:37.685  1030  1030 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 08:45:37.686  1030  1558 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-23 08:45:37.693  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:37.696  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-23 08:45:37.696  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.696  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 08:45:37.698  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:37.699  8089  8165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 08:45:37.702  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 08:45:37.707  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:37.712  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.713  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.713  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 08:45:37.716  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:37.716  8089  8165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-23 08:45:37.724  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:37.727  2012  2012 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-23 08:45:37.730  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 08:45:37.731  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:37.732  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 08:45:37.733  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-23 08:45:37.734  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 08:45:37.735  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 08:45:37.737  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.737  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.737  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 08:45:37.748  1030  1114 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{293b644d u0 com.lge.launcher2/.Launcher t5} time:202783
08-23 08:45:37.750  2012  2012 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-23 08:45:37.751  2012  2012 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-23 08:45:37.751  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 08:45:37.751  2012  2153 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 08:45:37.755  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:37.755  2012  2153 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-23 08:45:37.771  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-23 08:45:37.772  2012  2012 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 08:45:37.772  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 08:45:37.776  1030  1517 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:37.776  1030  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:37.776  1030  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:37.777  1030  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:37.777  1030  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:37.777  1030  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-23 08:45:37.777  1030  1523 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-23 08:45:37.778  1030  1523 D ConnectivityService: identical MTU - not setting
08-23 08:45:37.778  1030  1523 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-23 08:45:37.778  1030  1523 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-23 08:45:37.778  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-23 08:45:37.778  1030  1523 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:37.778  1030  1523 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-23 08:45:37.778  1583  2057 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-23 08:45:37.782  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 08:45:37.782  2012  2012 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-23 08:45:37.783  2586  2586 D [Concierge]Service: onStartCommand(). Type : 8
08-23 08:45:37.783  2586  2586 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-23 08:45:37.784  2586  2586 D [Concierge]Service: Update widget ID : 11
,08-23 08:45:37.786  2012  2012 D [Concierge]WidgetView: change position of spinner
08-23 08:45:37.787  2586  2586 D [Concierge]Service: onStartCommand(). Type : 0
08-23 08:45:37.787  2012  2012 I [Concierge]WidgetView: initWebView(). Time : 1471934737787
08-23 08:45:37.788  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:37.792  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.792  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.797  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-23 08:45:37.798  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:37.803  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 08:45:37.807  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-23 08:45:37.812  1030  1103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 08:45:37.815  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.815  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.815  1030  1119 I art     : Explicit concurrent mark sweep GC freed 87609(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.786ms total 324.606ms
08-23 08:45:37.815  8168  8168 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-23 08:45:37.817  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:37.820  8040  8040 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-23 08:45:37.821  2012  2012 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 838356081
08-23 08:45:37.821  2012  2012 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-23 08:45:37.822  2012  2012 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 08:45:37.823  8040  8040 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:37.825  2012  2012 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3319194d
08-23 08:45:37.825  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-23 08:45:37.826  2012  2012 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 08:45:37.826  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 08:45:37.827  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-23 08:45:37.830  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:37.832  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 08:45:37.832  2012  2012 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-23 08:45:37.833  2012  2012 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 08:45:37.835  2012  2012 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471934562535, New one : 1471934737787
08-23 08:45:37.835  2012  2012 D [Concierge]WidgetView: Unregister all receivers
08-23 08:45:37.835  2012  2012 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 08:45:37.835  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 08:45:37.838  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-23 08:45:37.838  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.838  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-23 08:45:37.839  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-23 08:45:37.839  8168  8168 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-23 08:45:37.840  8168  8168 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 08:45:37.840  8168  8168 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 08:45:37.840  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-23 08:45:37.841  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-23 08:45:37.842  1030  1103 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-23 08:45:37.842  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-23 08:45:37.843  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-23 08:45:37.845  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 08:45:37.845  8040  8040 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-23 08:45:37.845  8040  8040 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-23 08:45:37.845  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 08:45:37.848  6865  6865 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-23 08:45:37.853  6865  6865 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-23 08:45:37.859  8168  8168 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-23 08:45:37.859  8168  8168 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-23 08:45:37.860  8168  8168 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-23 08:45:37.861  8168  8168 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-23 08:45:37.861  8168  8168 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-23 08:45:37.864  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-23 08:45:37.868  8168  8168 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-23 08:45:37.869  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-23 08:45:37.869  8168  8168 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-23 08:45:37.882  2012  2012 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 08:45:37.892  2012  2012 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-23 08:45:37.892  2012  2012 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-23 08:45:37.893  2012  2012 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-23 08:45:37.893  8168  8168 D LgDataFeature: LgDataFeature() Constructor: none
08-23 08:45:37.893  8168  8168 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:37.894  2012  2012 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 08:45:37.902  8168  8168 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-23 08:45:37.905  8168  8168 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-23 08:45:37.905  8168  8168 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-23 08:45:37.905  8168  8168 V SoundPool: doLoad: loading sample sampleID=1
08-23 08:45:37.906  8168  8240 V SoundPool: Start decode
08-23 08:45:37.906  8168  8240 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-23 08:45:37.906   313   313 V MediaPlayerService: decode(22, 10857164, 17813)
08-23 08:45:37.906   313   313 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-23 08:45:37.906   313   313 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-23 08:45:37.906   313   313 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-23 08:45:37.906   313   313 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-23 08:45:37.906   313   313 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-23 08:45:37.906   313   313 V MediaPlayerService: player type = 3
08-23 08:45:37.906   313   313 V AwesomePlayer: AwesomePlayer create()
08-23 08:45:37.906   313   313 V AwesomePlayer: reset_l() 
08-23 08:45:37.906   313   313 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:37.906   313   313 V AwesomePlayer: setAudioSink() 
08-23 08:45:37.906   313   313 V AwesomePlayer: reset_l() 
08-23 08:45:37.906   313   313 V AudioCache: notify(0xb5474cc0, 8, 0, 0)
08-23 08:45:37.906   313   313 V AudioCache: ignored
08-23 08:45:37.906   313   313 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:37.907   313   313 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-23 08:45:37.907  8168  8168 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-23 08:45:37.907   313   313 V AwesomePlayer: setDataSource_l dataSource
08-23 08:45:37.907   313   313 V LGParserOSAL: SniffLGParser start
08-23 08:45:37.907   313   313 V LGParserOSAL: MainType:5, SubType=0
08-23 08:45:37.907   313   313 V LGParserOSAL: #### check Mime : application/ogg
08-23 08:45:37.907   313   313 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-23 08:45:37.907   313   313 E MediaExtractor: Use LGExtractor :application/ogg 
08-23 08:45:37.909  7601  7601 D UEI.SmartControl: QS Service created
,08-23 08:45:37.917  2012  2012 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b98d93e time:202951
08-23 08:45:37.917  8168  8168 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-23 08:45:37.918  8168  8168 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-23 08:45:37.919  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-23 08:45:37.919  7601  7601 I UEI.SmartControl: Service initServices...
08-23 08:45:37.919  7601  7601 D UEI.SmartControl: QS start get config
08-23 08:45:37.928  8168  8168 V LGMDMManager: Create singleton instance
,08-23 08:45:37.930  8163  8163 D AndroidRuntime: Shutting down VM
08-23 08:45:37.931   313   313 V LGParserOSAL: supported mime: application/ogg
08-23 08:45:37.931   313   313 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-23 08:45:37.931   313   313 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-23 08:45:37.931   313   313 V AwesomePlayer: mBitrate = -1 bits/sec
08-23 08:45:37.931   313   313 V AwesomePlayer: AudioTrack Setting
08-23 08:45:37.931   313   313 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-23 08:45:37.931   313   313 V AwesomePlayer: setAudioSource() 
08-23 08:45:37.931   313   313 V MediaPlayerService: prepare
08-23 08:45:37.931   313   313 V AwesomePlayer: prepareAsync_l() 
08-23 08:45:37.931   313   313 V MediaPlayerService: wait for prepare
08-23 08:45:37.931   313  8241 V AwesomePlayer: onPrepareAsyncEvent() 
08-23 08:45:37.931   313  8241 V AwesomePlayer: initAudioDecoder() 
08-23 08:45:37.931   313  8241 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 08:45:37.931   313  8241 V AudioSystem: isOffloadSupported()
08-23 08:45:37.931   313  8241 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 08:45:37.931   313  8241 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 08:45:37.931   313  8241 I AudioFlinger: isAudioPlaybackHookOn() false
08-23 08:45:37.931   313  8241 V AwesomePlayer: getUseOffload() = 0 
08-23 08:45:37.931   313  8241 V OMXCodec: OMXCodec::Create
08-23 08:45:37.931   313  8241 V OMXCodec: findMatchingCodecs()
08-23 08:45:37.931   313  8241 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-23 08:45:37.931   313  8241 V OMXCodec: matchingCodecs.size()=1
08-23 08:45:37.931   313  8241 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-23 08:45:37.933   313  8241 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-23 08:45:37.933   313  8241 V LGCodecAdapter: LG Codec Adapter start
08-23 08:45:37.933   313  8241 V OMXCodec: OMXCodec Createtor
08-23 08:45:37.933   313  8241 V OMXCodec: setComponentRole
08-23 08:45:37.933   313  8241 V OMXCodec: configureCodec protected=0
08-23 08:45:37.933   313  8241 V LGCodecAdapter: called getLGCodecSpecificData
08-23 08:45:37.933   313  8241 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-23 08:45:37.933   313  8241 V LGCodecOSAL: Called LGconfigureCodecMETA
08-23 08:45:37.933   313  8241 V LGCodecOSAL: Called LGconfigureCodecMSG
08-23 08:45:37.933   313  8241 V LGCodecOSAL: Not support LGCodec
08-23 08:45:37.933   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 08:45:37.933   313  8241 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-23 08:45:37.933   313  8241 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-23 08:45:37.933   313  8241 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-23 08:45:37.933   313  8241 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-23 08:45:37.933   313  8241 V AudioSystem: isOffloadSupported()
08-23 08:45:37.933   313  8241 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-23 08:45:37.933   313  8241 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-23 08:45:37.933   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-23 08:45:37.934   313  8241 V OMXCodec: init()
08-23 0,8:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-23 08:45:37.934   313  8241 V OMXCodec: allocateBuffers
08-23 08:45:37.934   313  8241 V OMXCodec: allocateBuffersOnPort portIndex=0
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on input port
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434290 on input port
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434330 on input port
08-23 08:45:37.934   313  8241 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on output port
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on output port
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on output port
08-23 08:45:37.934   313  8241 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b89c0 on output port
08-23 08:45:37.934   313  8241 V OMXCodec: init() mAsyncCompletion wait!!! 
08-23 08:45:37.934   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 08:45:37.934   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 08:45:37.934   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-23 08:45:37.934   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-23 08:45:37.934   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-23 08:45:37.934   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-23 08:45:37.934   313  8241 V OMXCodec: init() mAsyncCompletion wait free! 
08-23 08:45:37.934   313  8241 V AwesomePlayer: finishAsyncPrepare_l() 
08-23 08:45:37.934   313  8241 V AudioCache: notify(0xb5474cc0, 5, 0, 0)
08-23 08:45:37.934   313  8241 V AudioCache: ignored
08-23 08:45:37.934   313  8241 V AudioCache: notify(0xb5474cc0, 1, 0, 0)
08-23 08:45:37.934   313  8241 V AudioCache: prepared
08-23 08:45:37.935   313   313 V AudioCache: wait - success
08-23 08:45:37.935   313   313 V MediaPlayerService: start
08-23 08:45:37.935   313   313 V AwesomePlayer: play_l() 
08-23 08:45:37.935   313   313 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-23 08:45:37.935   313   313 V AwesomePlayer: createAudioPlayer_l
08-23 08:45:37.935   313   313 V AwesomePlayer: seekAudioIfNecessary_l() 
08-23 08:45:37.935   313   313 V AwesomePlayer: startAudioPlayer_l() 
08-23 08:45:37.935   313   313 D AudioPlayer: start of Playback, useOffload 0
08-23 08:45:37.935   313   313 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 08:45:37.935   313   313 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975424
08-23 08:45:37.936   313  8243 V OMXCodec,: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974515696
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974515776
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974517696
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-23 08:45:37.936   313  8243 V OMXCodec: allocateBuffersOnPort portIndex=1
08-23 08:45:37.936   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-23 08:45:37.937   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b8240 on output port
08-23 08:45:37.937   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14b81f0 on output port
08-23 08:45:37.937   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on output port
08-23 08:45:37.937   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-23 08:45:37.937   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-23 08:45:37.937   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-23 08:45:37.937   313   313 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-23 08:45:37.938   313   313 V AudioCache: notify(0xb5474cc0, 6, 0, 0)
08-23 08:45:37.938   313   313 V AudioCache: ignored
08-23 08:45:37.938   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.938   313  8244 V AudioCache: memcpy(0xaf0f9000, 0xb57f4000, 4096)
08-23 08:45:37.939   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.939   313  8244 V AudioCache: memcpy(0xaf0fa000, 0xb57f4000, 4096)
08-23 08:45:37.939   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.939   313  8244 V AudioCache: memcpy(0xaf0fb000, 0xb57f4000, 4096)
08-23 08:45:37.940   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.940   313  8244 V AudioCache: memcpy(0xaf0fc000, 0xb57f4000, 4096)
08-23 08:45:37.940   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.940   313  8244 V AudioCache: memcpy(0xaf0fd000, 0xb57f4000, 4096)
08-23 08:45:37.940   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.940   313  8244 V AudioCache: memcpy(0xaf0fe000, 0xb57f4000, 4096)
08-23 08:45:37.940   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.940   313  8244 V AudioCache: memcpy(0xaf0ff000, 0xb57f4000, 4096)
08-23 08:45:37.941   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.941   313  8244 V AudioCache: memcpy(0xaf100000, 0xb57f4000, 4096)
08-23 08:45:37.941   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.941   313  8244 V AudioCache: memcpy(0xaf101000, 0xb57f4000, 4096)
08-23 08:45:37.941   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.941   313  8244 V AudioCache: memcpy(0xaf102000, 0xb57f4000, 4096)
08-23 08:45:37.941   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.941   313  8244 V AudioCache: memcpy(0xaf103000, 0xb57f4000, 4096)
08-23 08:45:37.942   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.942   313  8244 V AudioCache: memcpy(0xaf104000, 0xb57f4000, 4096)
08-23 08:45:37.942   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.942   313  8244 V AudioCache: memcpy(0xaf105000, 0xb57f4000, 4096)
08-23 08:45:37.942   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.942   313  8244 V AudioCache: memcpy(0xaf106000, 0xb57f4000, 4096)
08-23 08:45:37.942   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.942   313  8244 V AudioCache: memcpy(0xaf107000, 0xb57f4000, 4096)
08-23 08:45:37.943   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.943   313  8244 V AudioCache: memcpy(0xaf108000, 0xb57f4000, 4096)
08-23 08:45:37.943   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.943   313  8244 V AudioCache: memcpy(0xaf109000, 0xb57f4000, 4096)
08-23 08:45:37.943   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.943   313  8244 V AudioCache: memcpy(0xaf10a000, 0xb57f4000, 4096)
08-23 08:45:37.943   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.943   313  8244 V AudioCache: memcpy(0xaf10b000, 0xb57f4000, 4096)
08-23 08:45:37.944   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.944   313  8244 V AudioCache: memcpy(0xaf10c000, 0xb57f4000, 4096)
08-23 08:45:37.944   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.944   313  8244 V AudioCache: memcpy(0xaf10d000, 0xb57f4000, 4096)
08-23 08:45:37.945   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.945   313  8244 V AudioCache: memcpy(0xaf10e000, 0xb57f4000, 4096)
08-23 08:45:37.945   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.945   313  8244 V AudioCache: memcpy(0xaf10f000, 0xb57f4000, 4096)
08-23 08:45:37.945   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.945   313  8244 V AudioCache: memcpy(0xaf110000, 0xb57f4000, 4096)
08-23 08:45:37.946   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.946   313  8244 V AudioCache: memcpy(0xaf111000, 0xb57f4000, 4096)
08-23 08:45:37.946   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.946   313  8244 V AudioCache: memcpy(0xaf112000, 0xb57f4000, 4096)
08-23 08:45:37.946   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.946   313  8244 V AudioCache: memcpy(0xaf113000, 0xb57f4000, 4096)
08-23 08:45:37.947   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.947   313  8244 V AudioCache: memcpy(0xaf114000, 0xb57f4000, 4096)
08-23 08:45:37.947   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.947   313  8244 V AudioCache: memcpy(0xaf115000, 0xb57f4000, 4096)
08-23 08:45:37.948   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.948   313  8244 V AudioCache: memcpy(0xaf116000, 0xb57f4000, 4096)
08-23 08:45:37.948   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.948   313  8244 V AudioCache: memcpy(0xaf117000, 0xb57f4000, 4096)
08-23 08:45:37.948   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.948   313  8244 V AudioCache: memcpy(0xaf118000, 0xb57f4000, 4096)
08-23 08:45:37.949   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.949   313  8244 V AudioCache: memcpy(0xaf119000, 0xb57f4000, 4096)
08-23 08:45:37.949   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.949   313  8244 V AudioCache: memcpy(0xaf11a000, 0xb57f4000, 4096)
08-23 08:45:37.950   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.950   313  8244 V AudioCache: memcpy(0xaf11b000, 0xb57f4000, 4096)
08-23 08:45:37.950   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.950   313  8244 V AudioCache: memcpy(0xaf11c000, 0xb57f4000, 4096)
08-23 08:45:37.951   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.951   313  8244 V AudioCache: memcpy(0xaf11d000, 0xb57f4000, 4096)
08-23 08:45:37.951   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.951   313  8244 V AudioCache: memcpy(0xaf11e000, 0xb57f4000, 4096)
08-23 08:45:37.951   313   313 V MediaPlayerService: wait for playback complete
08-23 08:45:37.951   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.951   313  8244 V AudioCache: memcpy(0xaf11f000, 0xb57f4000, 4096)
08-23 08:45:37.952   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.952   313  8244 V AudioCache: memcpy(0xaf120000, 0xb57f4000, 4096)
08-23 08:45:37.952   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.952   313  8244 V AudioCache: memcpy(0xaf121000, 0xb57f4000, 4096)
08-23 08:45:37.952   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.952   313  8244 V AudioCache: memcpy(0xaf122000, 0xb57f4000, 4096)
08-23 08:45:37.953   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.953   313  8244 V AudioCache: memcpy(0xaf123000, 0xb57f4000, 4096)
08-23 08:45:37.953   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.953   313  8244 V AudioCache: memcpy(0xaf124000, 0xb57f4000, 4096)
08-23 08:45:37.953   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.953   313  8244 V AudioCache: memcpy(0xaf125000, 0xb57f4000, 4096)
08-23 08:45:37.954   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.954   313  8244 V AudioCache: memcpy(0xaf126000, 0xb57f4000, 4096)
08-23 08:45:37.954   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.954   313  8244 V AudioCache: memcpy(0xaf127000, 0xb57f4000, 4096)
08-23 08:45:37.954   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.954   313  8244 V AudioCache: memcpy(0xaf128000, 0xb57f4000, 4096)
08-23 08:45:37.955   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.955   313  8244 V AudioCache: memcpy(0xaf129000, 0xb57f4000, 4096)
08-23 08:45:37.955   313  8244 V AudioCache: write(0xb57f4000, 4096)
08-23 08:45:37.955   313  8244 V AudioCache: memcpy(0xaf12a000, 0xb57f4000, 4096)
08-23 08:45:37.955   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-23 08:45:37.955   313  8244 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-23 08:45:37.955   313  8244 V AwesomePlayer: postAudioEOS() 
08-23 08:45:37.955   313  8244 V AudioCache: write(0xb57f4000, 280)
08-23 08:45:37.955   313  8244 V AudioCache: memcpy(0xaf12b000, 0xb57f4000, 280)
08-23 08:45:37.957   313  8241 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-23 08:45:37.957   313  8241 V AwesomePlayer: onStreamDone
08-23 08:45:37.957   313  8241 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-23 08:45:37.957   313  8241 V AudioCache: notify(0xb5474cc0, 2, 0, 0)
08-23 08:45:37.957   313  8241 V AudioCache: playback complete
,08-23 08:45:37.957   313  8241 V AwesomePlayer: pause_l() 
08-23 08:45:37.957   313  8241 V AudioCache: notify(0xb5474cc0, 7, 0, 0)
08-23 08:45:37.957   313  8241 V AudioCache: ignored
08-23 08:45:37.957   313  8241 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:37.957   313  8241 D AudioPlayer: Pause Playback at 1068125
08-23 08:45:37.957   313   313 V AudioCache: wait - success
08-23 08:45:37.957   313   313 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-23 08:45:37.965   313   313 V AwesomePlayer: reset_l() 
08-23 08:45:37.965   313   313 V AudioCache: notify(0xb5474cc0, 8, 0, 0)
08-23 08:45:37.966   313   313 V AudioCache: ignored
08-23 08:45:37.966   313   313 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:37.966   313   313 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-23 08:45:37.966   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-23 08:45:37.966   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-23 08:45:37.966   313   313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-23 08:45:37.966   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434330 on port 0
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434290 on port 0
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 0
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 1
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b81f0 on port 1
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14b8240 on port 1
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-23 08:45:37.969   313  8243 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-23 08:45:37.969   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-23 08:45:37.969   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-23 08:45:37.969   313   313 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-23 08:45:37.970   313   313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-23 08:45:37.970   313   313 D AudioPlayer: AudioPlayer releasing audio source
08-23 08:45:37.970   313   313 D AudioPlayer: AudioPlayer done releasing audio source
08-23 08:45:37.970   313   313 V AwesomePlayer: reset_l() 
08-23 08:45:37.970   313   313 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:37.970   313   313 V AwesomePlayer: ~AwesomePlayer call
08-23 08:45:37.970   313   313 V AwesomePlayer: reset_l() 
08-23 08:45:37.970   313   313 V AwesomePlayer: cancelPlayerEvents
08-23 08:45:37.971  8168  8240 V SoundPool: close(31)
08-23 08:45:37.971  8168  8240 V SoundPool: pointer = 0xa0032000, size = 205080, sampleRate = 48000, numChannels = 2
08-23 08:45:37.977  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-23 08:45:37.978  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-23 08:45:37.994  1030  1119 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8245 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-23 08:45:37.997  8168  8168 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2898
08-23 08:45:37.999  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 08:45:38.001  1796  1796 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-23 08:45:38.006  2154  2154 I ConfigService: onCreate
,08-23 08:45:38.006  2154  2154 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-23 08:45:38.008  1796  1796 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 08:45:38.012  2154  2154 I ConfigService: onBind returning update interface
08-23 08:45:38.013  2154  2154 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 08:45:38.013  2154  2154 I ConfigService: onBind returning config service
08-23 08:45:38.024  2154  2154 I ConfigService: onDestroy
,08-23 08:45:38.029  1796  8263 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 08:45:38.054  5774  8269 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-23 08:45:38.073  1796  8271 I PeopleContactsSync: CP2 sync disabled
,08-23 08:45:38.076  1796  5183 I Icing   : doRemovePackageData com.test.thalitest
08-23 08:45:38.089  7056  7056 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-23 08:45:38.094  1796  8268 W GmsApplication: Using Auth Proxy for data requests.
08-23 08:45:38.106  1796  8268 W GmsApplication: Using Auth Proxy for data requests.
,08-23 08:45:38.112  2332  8273 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-23 08:45:38.128  2154  2179 I art     : Explicit concurrent mark sweep GC freed 6312(378KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 1.808ms total 27.267ms
,08-23 08:45:38.133  2012  2012 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-23 08:45:38.137  1030  1938 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8275 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-23 08:45:38.172  8275  8275 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 08:45:38.172  8275  8275 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 08:45:38.173  8275  8275 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 08:45:38.173  8275  8275 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 08:45:38.186  2012  2861 I GBoardtInterface: onReloaded()
,08-23 08:45:38.188  2012  2012 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-23 08:45:38.190  3778  3794 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 08:45:38.192  3778  3793 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 08:45:38.199  1883  1883 D ActionManagerService: notifyUserLog: 1000001
,08-23 08:45:38.201  3778  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 08:45:38.202  3778  4922 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 08:45:38.204  1883  1883 D ActionManagerService: notifyUserLog: 1000001
08-23 08:45:38.205  3778  4922 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 08:45:38.206  3778  4922 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 08:45:38.206  3778  4922 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-23 08:45:38.206  3778  4922 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-23 08:45:38.206  3778  3794 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 08:45:38.209  2012  2012 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-23 08:45:38.209  2012  2012 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-23 08:45:38.210  2012  2012 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-23 08:45:38.210  2012  2012 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 08:45:38.212  2012  2012 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-23 08:45:38.212  2012  2012 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-23 08:45:38.245  8275  8275 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-23 08:45:38.261  8275  8275 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-23 08:45:38.283  7601  7601 I UEI.SmartControl: Supports setup maps: true
08-23 08:45:38.285  7601  7601 D UEI.SmartControl: QS start statue = true Error code = 0
08-23 08:45:38.285  7601  7601 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-23 08:45:38.285  7601  7601 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-23 08:45:38.285  7601  7601 I UEI.SmartControl: ### init IR Blaster...
08-23 08:45:38.291  8275  8275 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 08:45:38.293  7601  7601 D serial_port: Configuring serial port
08-23 08:45:38.294  7601  7601 E UEI.SmartControl: UEIBLaster setting for 616
08-23 08:45:38.294  7601  7601 I UEI.SmartControl: Setting serial record hearder size = 2
08-23 08:45:38.294  7601  7601 I UEI.SmartControl: configuring settings for MAXQ616
08-23 08:45:38.294  7601  7601 I UEI.SmartControl: Get version...
08-23 08:45:38.311  8275  8275 D LgDataFeature: LgDataFeature() Constructor: none
,08-23 08:45:38.311  8275  8275 D LgDataFeature: LgDataFeature() Constructor Done, null
08-23 08:45:38.312  7601  8295 D UEI.SmartControl: serial port data available: 21
,08-23 08:45:38.338  7601  7601 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-23 08:45:38.338  7601  7601 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-23 08:45:38.338  7601  7601 I UEI.SmartControl: QS saving settings...
,08-23 08:45:38.340  7601  7601 W FileUtils: Failed to chmod(/data/data/com.uei.lg.quicksetsdk.maxq616/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-23 08:45:38.340  7601  7601 W System.err: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-23 08:45:38.341  7601  7601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 08:45:38.341  7601  7601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 08:45:38.341  7601  7601 W System.err: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-23 08:45:38.341  7601  7601 W System.err: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-23 08:45:38.341  7601  7601 W System.err: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-23 08:45:38.341  7601  7601 W System.err: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-23 08:45:38.341  7601  7601 W System.err: 	at com.uei.control.core.a.a(Unknown Source)
08-23 08:45:38.341  7601  7601 W System.err: 	at com.uei.control.core.a.<init>(Unknown Source)
08-23 08:45:38.341  7601  7601 W System.err: 	at com.uei.control.Service.a(Unknown Source)
08-23 08:45:38.341  7601  7601 W System.err: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 08:45:38.341  7601  7601 W System.err: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-23 08:45:38.341  7601  7601 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 08:45:38.341  7601  7601 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-23 08:45:38.341  7601  7601 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:45:38.341  7601  7601 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 08:45:38.341  7601  7601 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 08:45:38.341  7601  7601 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:45:38.341  7601  7601 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:45:38.341  7601  7601 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 08:45:38.341  7601  7601 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 08:45:38.341  7601  7601 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 08:45:38.341  7601  7601 W System.err: 	at libcore.io.Posix.open(Native Method)
08-23 08:45:38.341  7601  7601 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 08:45:38.341  7601  7601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 08:45:38.341  7601  7601 W System.err: 	... 19 more
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.core.a.a(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.core.a.<init>(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService,(ActivityThread.java:2738)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	... 19 more
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/files/Settings: open failed: EROFS (Read-only file system)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.core.QSApp.m(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.core.QSApp.b(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.core.a.a(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.core.a.<init>(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.Service.a(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.uei.control.Service.onCreate(Unknown Source)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.os.Looper.loop(Looper.java:135)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: Caused by: android.system.ErrnoExce,ption: open failed: EROFS (Read-only file system)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at libcore.io.Posix.open(Native Method)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 08:45:38.342  7601  7601 E UEI.SmartControl: 	... 19 more
08-23 08:45:38.342  7601  7601 D UEI.SmartControl: IR Blaster version: 25672567
08-23 08:45:38.358  7601  8295 D UEI.SmartControl: serial port data available: 4
08-23 08:45:38.382  8275  8275 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
