#### Test 81492074ffbc155_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 17:45:00.053  1613  1613 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 17:45:00.054  1613  1613 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 17:45:00.054  1613  1613 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 17:45:00.054  1613  1613 I [SystemUI]Clock: called onTimeUpdated()
,08-16 17:45:00.069  1613  1613 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 17:45:00.069  1613  1613 I [SystemUI]DateView: called onTimeUpdated()
08-16 17:45:00.072  1613  1613 I [SystemUI]DateView: called onTimeUpdated()
08-16 17:45:00.073  1613  1613 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 17:45:00.379  6798  6798 D AndroidRuntime: 
08-16 17:45:00.379  6798  6798 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 17:45:00.384  6798  6798 D AndroidRuntime: CheckJNI is OFF
08-16 17:45:00.594  6798  6798 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 17:45:00.604  1044  1897 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 17:45:00.619  1951  1966 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 17:45:00.625  1044  1897 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 17:45:00.627  1044  1897 D ActivityManager: setTaskToReturnTo : TaskRecord{2abbc597 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 17:45:00.627  1044  1897 D ActivityManager: setTaskToReturnTo : TaskRecord{2abbc597 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 17:45:00.630  1044  1897 D WindowStateEx: AppWindowTokenEx init.. 
08-16 17:45:00.631   327   348 E GBMv2   : DFP En is all cleared set to be enabled
08-16 17:45:00.661  1044  1897 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6813 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:45:00.663  6798  6798 D AndroidRuntime: Shutting down VM
08-16 17:45:00.718  1951  2756 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 17:45:00.718  1951  2756 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1ba281d5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 17:45:00.719  1951  1967 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 17:45:00.719  1951  1967 D SplitWindowPolicy: topRunningActivity=ActivityInfo{77e5dea co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 17:45:00.765  6813  6813 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-16 17:45:00.828  6813  6813 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-16 17:45:00.834  6813  6813 I LibraryLoader: Loading: webviewchromium
08-16 17:45:00.836  6813  6813 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8735-8738)
08-16 17:45:00.836  6813  6813 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:45:00.853  6813  6813 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2be7af4b}
08-16 17:45:00.854  6813  6813 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:45:00.855  6813  6813 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:45:00.863  6813  6813 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 17:45:00.864  6813  6813 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:45:00.887  6813  6813 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-16 17:45:00.888  6813  6813 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 17:45:00.889  6813  6813 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 17:45:00.890   311  2160 V AudioPolicyService: registerClient() client 0xb101fe20, uid 10118
08-16 17:45:00.895  1044  1106 D BluetoothManagerService: Message: 20
08-16 17:45:00.896  1044  1106 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25ac9d69:true
08-16 17:45:00.916  6813  6813 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 17:45:00.916  6813  6813 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 17:45:00.916  6813  6813 I Adreno-EGL: Build Date: 12/12/14 금
08-16 17:45:00.916  6813  6813 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 17:45:00.916  6813  6813 I Adreno-EGL: Remote Branch: 
08-16 17:45:00.916  6813  6813 I Adreno-EGL: Local Patches: 
08-16 17:45:00.916  6813  6813 I Adreno-EGL: Reconstruct Branch: 
,08-16 17:45:01.012  6813  6858 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 17:45:01.014  6813  6813 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 17:45:01.036  6813  6813 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:45:01.042  6813  6813 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 17:45:01.045  6813  6813 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 17:45:01.048  6813  6813 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 17:45:01.048  6813  6813 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-16 17:45:01.062  6813  6813 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 17:45:01.068  6813  6813 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:45:01.068  6813  6813 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:45:01.122  6813  6873 D OpenGLRenderer: Render dirty regions requested: true
08-16 17:45:01.122  6813  6873 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 17:45:01.128  6813  6873 D OpenGLRenderer: Enabling debug mode 0
,08-16 17:45:01.145  6813  6813 D Atlas   : Validating map...
,08-16 17:45:01.149  1044  1584 D SplitWindow: check instance of lgWin Window{222ad09b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 17:45:01.198  6813  6871 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:01.198  6813  6871 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:01.299  1044  1107 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +582ms (total +666ms)
08-16 17:45:01.299  6813  6813 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d0e5a96 time:189202
08-16 17:45:01.301  1044  1107 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11f15384 u0 com.test.thalitest/.MainActivity t6} time:189203
08-16 17:45:01.431  6813  6813 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 17:45:01.431  6813  6813 I chromium: 
,08-16 17:45:01.474  6813  6813 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 17:45:01.648  6813  6889 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435032064
,08-16 17:45:01.665  6813  6889 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 17:45:01.665  6813  6889 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:45:01.665  6813  6889 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:45:01.665  6813  6889 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:45:01.665  6813  6889 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 17:45:01.666  6813  6889 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@164a3b7a added. We now have 1 listener(s)
08-16 17:45:01.672  1044  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:01.675  6813  6889 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 17:45:01.680  6813  6889 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:01.683  6813  6889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:01.684  6813  6889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 17:45:01.700  6813  6889 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37bfcd21 added. We now have 1 listener(s)
,08-16 17:45:01.700  6813  6889 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:01.705  1044  1506 D WifiService: New client listening to asynchronous messages
08-16 17:45:01.710  6813  6889 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:45:01.710  6813  6889 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 17:45:01.710  6813  6889 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 17:45:01.710  6813  6889 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 17:45:01.711  6813  6889 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 17:45:01.715  6813  6889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:01.716  1044  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:01.717  6813  6889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-16 17:45:01.730  6813  6889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 17:45:01.731  6813  6889 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:01.731  6813  6889 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:01.731  6813  6889 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:01.731  6813  6889 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:01.731  6813  6889 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:01.731  6813  6889 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:01.731  6813  6889 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:01.731  6813  6889 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:01.731  6813  6889 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 17:45:01.731  6813  6889 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:45:01.734  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:01.736  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:01.738  6813  6889 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 17:45:01.773  6813  6871 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 17:45:01.773  6813  6871 I chromium: 
,08-16 17:45:01.835  6813  6813 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:45:01.912  1044  1388 D PowerManagerServiceEx: acquireWakeLockInternal: lock=971599754, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,08-16 17:45:01.947   327   350 E GBMv2   : DFP En is all cleared set to be enabled
08-16 17:45:01.947   327   350 E GBMv2   : Set value is all cleared set the max
08-16 17:45:01.947   327   350 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 17:45:01.980  1044  1102 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6893 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-16 17:45:02.014  2600  2600 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 17:45:02.114  6893  6893 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-16 17:45:02.119  6893  6893 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1e2b393c
08-16 17:45:02.120  1044  2005 I ActivityManager: Killing 6018:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-16 17:45:02.120  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=971599754 [*alarm*], flags=0x0
08-16 17:45:02.282  1044  1932 W libprocessgroup: failed to open /acct/uid_10014/pid_6018/cgroup.procs: No such file or directory
,08-16 17:45:02.677  6813  6892 W jxcore-log: Initializing JXcore engine
,08-16 17:45:02.677  6813  6892 W jxcore-log: JXcore engine is ready
08-16 17:45:02.747  6892  6892 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10245]" dev="sockfs" ino=10245 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 17:45:02.747  6892  6892 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-16 17:45:02.747  6892  6892 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10068]" dev="sockfs" ino=10068 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 17:45:02.747  6892  6892 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 17:45:02.747  6892  6892 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33347]" dev="sockfs" ino=33347 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 17:45:02.786  6813  6892 W jxcore-log: Starting JXcore engine
,08-16 17:45:02.913  6813  6892 W jxcore-log: Platform android
08-16 17:45:02.913  6813  6892 W jxcore-log: 
,08-16 17:45:02.913  6813  6892 W jxcore-log: Process ARCH arm
08-16 17:45:02.913  6813  6892 W jxcore-log: 
,08-16 17:45:03.105  6813  6892 I jxcore-log: JXcore Cordova bridge is ready!
08-16 17:45:03.105  6813  6892 I jxcore-log: 
08-16 17:45:03.106  6813  6892 W jxcore-log: JXcore engine is started
,08-16 17:45:03.118  6813  6889 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 17:45:03.124  6813  6813 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:45:21.892  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 17:45:21.892  6813  6892 I jxcore-log: 
,08-16 17:45:21.900  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 17:45:21.900  6813  6892 I jxcore-log: 
08-16 17:45:21.905  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:21.905  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:21.905  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:21.905  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:21.905  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:21.905  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:21.905  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:21.905  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:21.908  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:45:21.914  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:45:21.914  6813  6892 I jxcore-log: 
08-16 17:45:21.917  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:45:21.917  6813  6892 I jxcore-log: 
08-16 17:45:22.555  6813  6892 D ExecuteNativeTests: Running unit tests
,08-16 17:45:22.694  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:22.694  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be added. We now have 2 listener(s)
,08-16 17:45:22.697  1044  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:22.700  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:22.700  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:22.700  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:22.700  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:22.700  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f added. We now have 2 listener(s)
08-16 17:45:22.700  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:22.701  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:45:22.857  1044  1933 I art     : Explicit concurrent mark sweep GC freed 26274(1242KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.853ms total 141.812ms
,08-16 17:45:22.861  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:22.865  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:22.865  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:22.865  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:22.865  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:22.865  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:22.865  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:22.865  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:22.865  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:22.866  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:22.866  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:22.868  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:22.870  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:22.875  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:45:22.877  6813  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:45:22.878  6813  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:45:22.881  6813  6892 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 17:45:22.884  6813  6892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:45:22.884  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:45:22.884  6813  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:45:22.884  6813  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:45:22.885  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:22.886  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:22.897  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:45:22.900  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:22.900  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:22.900  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:22.901  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:22.901  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be removed from the list
08-16 17:45:22.901  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:22.901  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f removed from the list
08-16 17:45:22.901  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:22.901  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:22.902  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:22.902  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:22.903  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:22.903  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:22.903  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:22.903  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:22.905  6813  6892 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 17:45:22.906  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:22.906  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:22.906  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:22.906  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:22.906  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:22.906  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:22.906  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:22.906  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:22.906  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:22.906  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:22.906  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:22.907  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:22.907  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:22.907  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:22.911  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:22.911  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:22.911  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:22.911  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
,08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:45:22.928  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:45:22.929  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:45:22.929  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:22.929  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:22.929  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:22.933  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:22.933  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:22.933  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:22.933  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:22.933  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:22.933  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list,
08-16 17:45:22.933  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:22.933  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:22.934  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:22.934  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:22.934  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:45:22.941  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:22.941  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:22.941  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:22.941  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:22.942  6813  6892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:45:22.945  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:22.948  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:22.948  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:22.948  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:22.948  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:22.948  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:22.948  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:22.948  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:22.948  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:45:22.952  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:22.952  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:22.954  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:22.955  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:22.956  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:45:22.956  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:45:22.956  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:45:22.956  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:22.956  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:45:22.961  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:45:22.963  1044  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:22.970  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:45:22.976  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:45:22.985  6813  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 17:45:22.987  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:45:22.991  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:45:22.995  6813  6892 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:45:22.995  6813  6892 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:45:23.001  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.001  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.001  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.002  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.002  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.002  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:23.002  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.002  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.002  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.002  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.002  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.002  6813  6892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:45:23.005  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:23.009  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:23.009  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:23.009  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.009  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:23.009  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:23.009  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:23.009  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:23.009  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:23.010  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:23.010  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:23.011  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:45:23.011  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:45:23.011  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:45:23.011  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:23.011  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:45:23.013  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:23.015  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:23.018  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:45:23.019  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:23.021  6813  6892 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:45:23.021  6813  6892 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:45:23.023  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.023  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.023  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.023  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.023  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.023  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:23.024  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.024  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.024  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.024  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.024  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.024  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.024  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.025  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.025  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.027  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.028  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.028  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.028  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.028  6813  6892 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:45:23.031  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:23.034  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:23.034  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:23.034  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.034  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:23.034  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:23.034  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:23.034  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:23.034  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:23.036  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:23.036  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:23.036  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:45:23.036  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:45:23.036  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:45:23.036  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:23.036  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:45:23.039  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:23.041  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:23.046  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:45:23.046  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:23.048  6813  6892 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:45:23.048  6813  6892 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:45:23.048  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.048  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.048  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.049  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.049  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.049  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.049  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.049  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.049  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:23.049  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.049  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.049  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.049  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.050  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.050  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.050  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.051  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.051  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.051  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.052  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:45:23.052  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.052  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.052  6813  6892 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 17:45:23.053  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.053  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:45:23.053  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:45:23.057  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.057  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.057  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.058  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.058  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.058  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.058  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.058  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.058  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.058  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.058  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.060  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.060  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.061  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.061  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.061  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.061  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.063  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:45:23.063  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.063  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.063  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.064  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:45:23.064  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.064  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.064  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.064  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:45:23.064  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.064  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.064  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:45:23.064  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.064  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.064  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:45:23.068  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.068  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.070  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.070  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.070  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.070  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.071  6813  6892 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 17:45:23.072  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.072  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.072  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.072  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.072  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.072  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.072  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.073  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.073  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.073  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.073  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.073  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.073  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.073  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.075  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.075  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:45:23.076  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.077  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.077  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.077  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.079  6813  6892 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 17:45:23.079  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.079  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.079  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.079  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.079  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.079  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.079  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.079  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.079  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.080  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.080  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.080  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.080  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.080  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.081  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.081  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.082  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.082  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.082  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.082  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.083  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:45:23.086  6813  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:45:23.086  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:45:23.086  6813  6892 ,V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:45:23.086  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:45:23.086  6813  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:45:23.086  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.087  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.087  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.087  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.087  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.087  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.087  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.087  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.087  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.087  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.087  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.088  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.088  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.088  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.090  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.090  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.092  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.092  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.092  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.092  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.094  6813  6892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:45:23.095  6813  6892 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:45:23.095  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:45:23.104  6813  6892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:45:23.105  6813  6892 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:45:23.105  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:45:23.105  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:45:23.106  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:45:23.106  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:45:23.106  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:45:23.106  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:45:23.106  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:45:23.106  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:45:23.106  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:45:23.106  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:45:23.107  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:45:23.107  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:45:23.107  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:45:23.107  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:45:23.109  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:45:23.110  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:45:23.110  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:45:23.110  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:45:23.110  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:45:23.110  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:45:23.110  6813  6892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:45:23.110  6813  6892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:45:23.110  6813  6892 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:45:23.110  6813  6892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:45:23.110  6813  6892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:45:23.111  6813  6892 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 17:45:23.111  6813  6892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:45:23.111  6813  6892 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:45:23.111  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:45:23.113  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 17:45:23.114  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:45:23.115  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:45:23.115  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 17:45:23.116  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:45:23.116  6813  6892 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:45:23.116  6813  6892 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:45:23.116  6813  6892 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 17:45:23.117  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.117  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.117  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.117  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.117  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.117  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.118  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 17:45:23.118  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.118  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.118  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.118  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.118  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.118  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.118  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.118  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.119  6813  6958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-16 17:45:23.120  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.120  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.121  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.121  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.121  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.121  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.122  6813  6959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-16 17:45:23.122  6813  6892 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:45:23.122  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.123  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.123  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.123  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.124  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.124  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.124  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.124  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.124  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.124  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.124  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.124  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.124  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.124  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.126  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.126  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.127  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.127  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.127  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.127  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.128  6813  6892 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:45:23.129  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.129  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.129  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.130  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.130  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.130  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.130  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.130  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.130  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.130  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.130  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.130  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.130  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.130  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.132  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.132  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.133  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.133  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.133  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.133  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.134  6813  6892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:45:23.135  6813  6892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 17:45:23.135  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:45:23.136  6813  6892 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:45:23.136  6813  6892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:45:23.136  6813  6892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:45:23.136  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:45:23.138  6813  6892 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:45:23.138  6813  6892 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:45:23.138  6813  6892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:45:23.138  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:45:23.138  6813  6892 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:45:23.139  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.139  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.139  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.141  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.141  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.141  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.141  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.141  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.141  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.141  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.141  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.141  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.141  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.141  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.143  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.143  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.143  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.143  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.143  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.143  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.144  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.144  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.144  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.144  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.144  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.144  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.144  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.144  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.144  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.145  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.145  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.145  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.145  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.145  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.145  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.145  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.145  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.145  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.145  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.145  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.145  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.145  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.145  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.146  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.146  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.146  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.146  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.146  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.146  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.151  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.151  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.157  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.157  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.157  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.157  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.159  6813  6892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 17:45:23.160  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:23.160  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 17:45:23.161  6813  6892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 17:45:23.161  6813  6892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:45:23.162  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:45:23.162  6813  6813 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 17:45:23.162  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:45:23.163  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.163  1044  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:23.163  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:45:23.163  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:45:23.163  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:45:23.163  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.163  6813  6892 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:45:23.163  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.163  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.164  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:45:23.164  6813  6892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:45:23.164  6813  6813 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:45:23.164  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:45:23.164  6813  6960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:23.164  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:45:23.165  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:23.165  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:23.165  6813  6892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:45:23.165  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.165  3931  3952 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 17:45:23.165  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.166  6813  6892 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:45:23.167  6813  6960 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 17:45:23.167  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.167  6813  6813 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:45:23.167  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.167  6813  6813 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:45:23.167  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.167  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.167  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.167  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.167  6813  6813 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:45:23.167  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.167  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.167  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.167  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.167  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.167  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.167  6813  6960 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:45:23.167  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.167  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.168  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.168  6813  6960 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:45:23.168  6813  6813 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:45:23.168  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.168  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.168  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.168  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.170  6813  6892 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 17:45:23.170  6813  6892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:45:23.170  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:45:23.170  6813  6892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:45:23.170  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.170  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.170  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.171  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.171  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.171  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.171  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.171  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.171  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.171  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.171  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.171  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.171  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.171  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.172  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.172  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.172  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.172  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.174  1044  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:23.176  1044  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:23.179  1044  1968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:23.180  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.180  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.180  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.180  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.180  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.180  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.180  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.180  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.180  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.180  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.180  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.180  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.180  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.181  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.182  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.182  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.182  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.182  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.183  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:23.183  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:23.183  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:23.183  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:23.183  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.184  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.184  6813  6892 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d38c4be not in the list
08-16 17:45:23.184  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.184  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.184  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:23.184  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.184  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.184  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:23.184  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:23.185  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:23.185  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:23.185  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:23.186  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.th,aliproject.p2p.btconnectorlib.DiscoveryManager@3611d91f not in the list
08-16 17:45:23.188  6813  6892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:45:23.188  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:45:23.189  6813  6892 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 17:45:23.189  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:45:23.189  6813  6892 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 17:45:23.189  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:45:23.191  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:45:23.191  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 17:45:23.193  6813  6892 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 17:45:23.193  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:45:23.193  6813  6892 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 17:45:23.193  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:45:23.193  6813  6892 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:45:23.193  6813  6892 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 17:45:23.194  6813  6892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:45:23.194  6813  6892 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 17:45:23.195  6813  6892 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:45:23.195  6813  6892 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 17:45:23.196  6813  6892 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:45:23.196  6813  6892 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 17:45:23.197  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:23.197  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13418504 added. We now have 2 listener(s)
08-16 17:45:23.198  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:23.199  6813  6892 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 17:45:23.204  1044  2042 D WifiServiceImplEx: setWifiEnabled: true pid=6813, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 17:45:23.205  1044  2042 D WifiService: setWifiEnabled: true pid=6813, uid=10118
08-16 17:45:23.205  1044  2042 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 17:45:23.206  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:23.206  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e850aed added. We now have 3 listener(s)
08-16 17:45:23.206  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:23.212  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:23.212  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18480d22 added. We now have 4 listener(s)
08-16 17:45:23.212  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:23.214  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:23.214  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14fa23b3 added. We now have 5 listener(s)
08-16 17:45:23.214  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:23.217  1044  1933 D WifiServiceImplEx: setWifiEnabled: false pid=6813, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 17:45:23.217  1044  1933 D WifiService: setWifiEnabled: false pid=6813, uid=10118
08-16 17:45:23.217  1044  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:45:23.231  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 17:45:23.232  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:45:23.232  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 17:45:23.233  1044  1449 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:23.234  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:23.234  1044  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:23.234  1044  1449 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:23.234  1044  2023 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ef0580a mBinding = false
08-16 17:45:23.234  1044  1449 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0,
08-16 17:45:23.235  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:23.235  1044  1449 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 17:45:23.235  1044  1449 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:45:23.235  1044  1449 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 17:45:23.236  1044  1449 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 17:45:23.236  1044  1449 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 17:45:23.245  1044  1449 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-16 17:45:23.245  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.245  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.246  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 17:45:23.246  2742  2742 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 17:45:23.248  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 17:45:23.248  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:45:23.250  1044  1106 D BluetoothManagerService: Message: 2
08-16 17:45:23.251  1044  1106 D BluetoothManagerService: Sending off request.
08-16 17:45:23.251  6813  6958 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 17:45:23.251  6813  6958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:23.251  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 17:45:23.251  3931  4078 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 17:45:23.252  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:45:23.252  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 17:45:23.252  3931  3952 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:23.252  3931  4129 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
08-16 17:45:23.254  3931  4011 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 17:45:23.254  3931  4011 D BluetoothAdapterProperties: Setting state to 13
08-16 17:45:23.254  3931  4011 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:45:23.254  3931  4011 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:45:23.255  3931  4011 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 17:45:23.255  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:23.257  3931  4019 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:45:23.258  3931  4011 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 17:45:23.258  3931  4236 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:23.258  3931  4011 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:45:23.261  3931  4285 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:23.261  3931  4288 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:23.261  3931  4290 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:23.262  3931  4234 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 17:45:23.262  3931  4234 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:23.262  3931  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 17:45:23.262  3931  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 17:45:23.262  3931  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 17:45:23.262  3931  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 17:45:23.262  3931  4234 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 17:45:23.262  3931  4234 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 17:45:23.262  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
,08-16 17:45:23.262  3931  4129 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 17:45:23.263  1044  1449 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:45:23.263   307   904 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 17:45:23.264  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 17:45:23.264  3931  4129 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 17:45:23.268  1044  2870 D DhcpStateMachine: RunningState{ when=-5ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.269  1044  1106 D BluetoothManagerService: Message: 60
08-16 17:45:23.269  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 17:45:23.269  1044  1106 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 17:45:23.271  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.271  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:23.271  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:23.271  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.271  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:23.271  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:23.271  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:23.271  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:23.271  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:23.272  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.272  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:23.272  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:23.274  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:23.276  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:23.279  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.279  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:23.279  6813  6813 V io.jxcore.node.ConnectivityMonitor:    , - is Wi-Fi Direct supported: true
08-16 17:45:23.279  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.279  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:23.279  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:23.279  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:23.279  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:23.279  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:23.279  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.279  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:23.281  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:23.283  6813  6958 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
08-16 17:45:23.305  1044  1102 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6964 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 17:45:23.310  1044  1526 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 17:45:23.310  1044  1526 D ConnectivityService: ignoring duplicate network state non-change
08-16 17:45:23.310  1044  1526 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-16 17:45:23.316  3931  3931 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:23.316  3931  3931 D BluetoothMapService: STATE_TURNING_OFF
08-16 17:45:23.316  3931  3931 V BluetoothMapService: Handler(): got msg=4
08-16 17:45:23.317  3931  3931 D BluetoothMapService: MAP Service closeService in
08-16 17:45:23.317  3931  3931 D BluetoothMapMasInstance: MAP Service shutdown
08-16 17:45:23.317  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 17:45:23.317  3931  3931 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 17:45:23.317  3931  3931 V BluetoothMapService: MAP Service closeService out
,08-16 17:45:23.317  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:23.317  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:23.317  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 17:45:23.319  1044  1044 D WifiHS20: hidePasspointNotification off =false
,08-16 17:45:23.320  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:23.320  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:23.320  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:45:23.322  3931  3931 V BtOppService: Receiver DISABLED_ACTION 
08-16 17:45:23.322  3931  3931 I BtOppRfcommListener: stopping Accept Thread
08-16 17:45:23.322  3931  3931 V BtOppRfcommListener: close mBtServerSocket
08-16 17:45:23.322  3931  3931 V BtOppRfcommListener: waiting for thread to terminate
08-16 17:45:23.323  3931  4285 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 17:45:23.323  3931  3931 V BtOppRfcommListener: done waiting for thread to terminate
08-16 17:45:23.324  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:23.324  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:23.325  1951  1951 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 17:45:23.325  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:23.328  1044  1792 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-16 17:45:23.329  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.329  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.329  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 17:45:23.329  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.329  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 17:45:23.335  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 17:45:23.343  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.343  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:23.343  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:23.343  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.343  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:23.343  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:23.343  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:23.343  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:23.343  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:23.344  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.344  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:23.346  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.346  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:23.346  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:23.346  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.346  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:23.346  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:23.346  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:23.346  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:23.346  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:23.347  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.347  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:23.349  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:23.349  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:23.350  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:23.351  1613  1613 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 17:45:23.383  1044  1102 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6989 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 17:45:23.383  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.383  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.384  1044  1400 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f88d8e1
08-16 17:45:23.384  1044  1449 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:23.384  1044  1400 D LGWifiP2pService: P2pDisablingState
08-16 17:45:23.384  3931  3931 V BtOppService: onDestroy
08-16 17:45:23.384  1044  1400 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.385  1044  1400 D LGWifiP2pService: p2p socket connection lost
,08-16 17:45:23.385  1044  1400 D LGWifiP2pService: P2pDisabledState
08-16 17:45:23.386  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:23.386  1044  1449 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:23.386  1044  1449 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:45:23.387  1044  1449 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 17:45:23.387  1044  1400 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.387  1044  1400 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.387  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 17:45:23.388  2742  2742 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 17:45:23.388  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 17:45:23.388  3931  3931 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 17:45:23.389   307  7001 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 17:45:23.389  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:45:23.390  1044  1044 D RttService: SCAN_AVAILABLE : 1
08-16 17:45:23.390  1044  1565 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.390  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 17:45:23.390  1044  1526 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 17:45:23.390  1044  1526 D DSQN    : disableDataServiceNotify
08-16 17:45:23.390  1044  1104 D DSQN    : Dns fail occured do internet check.
08-16 17:45:23.390  1044  1566 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.390  1044  1044 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-16 17:45:23.391  1044  1044 D DSQN    : try Internet connection check
08-16 17:45:23.391  1044  1526 D DSQN    : stop dsqn bin
08-16 17:45:23.391  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 17:45:23.391  1951  1951 D WfdsService: WifiP2pState is changed : false
08-16 17:45:23.391  1951  2315 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 17:45:23.391  1951  2315 D WfdsService: Set the WFDS Monitor: false
08-16 17:45:23.392  1951  2315 D WfdsMonitor: WFDS Monitor is stopped
08-16 17:45:23.392  1951  2315 D WfdsService: STATE : WfdsDisabledState - enter
08-16 17:45:23.392  1951  2778 D CtrlSupplicant: Received on exit socket, terminate
08-16 17:45:23.392  1951  2778 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 17:45:23.392  1951  2778 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 17:45:23.392  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:45:23.392  1951  2778 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 17:45:23.392  1951  2319 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 17:45:23.392  1044  1449 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:45:23.393   307   904 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:45:23.393  1951  2315 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 17:45:23.398   307  7004 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 17:45:23.399  1044  7003 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
,08-16 17:45:23.399  1044  1104 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 17:45:23.400  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 17:45:23.401  1044  7002 D DSQN    : ThreadInternetCheck internet check NOK 
08-16 17:45:23.401  1044  7002 D DSQN    : L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
,08-16 17:45:23.401  1044  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
08-16 17:45:23.401  1044  1526 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 17:45:23.401  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:23.401  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:23.401  1044  1526 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:23.402  1044  1526 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 17:45:23.400  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:23.402  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:23.402  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:45:23.402  1044  1526 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 17:45:23.402  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.402  1044  1526 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 17:45:23.402  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:23.402  1044  2868 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 17:45:23.403  1613  2080 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 17:45:23.403  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:45:23.403  1044  1449 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 17:45:23.404  1044  1044 D WifiDataContinuityService: L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
08-16 17:45:23.404  1044  1449 D WifiNative-p2p0: TERMINATE: returned true
08-16 17:45:23.404  1044  1449 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:45:23.404  1044  1449 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:45:23.404  1044  1449 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:45:23.405  1044  1526 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:23.405  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:45:23.407  1044  1399 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16, 17:45:23.408  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 17:45:23.411  1044  1526 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:23.411  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:45:23.411  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:23.411  1044  1526 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:23.412  1044  1526 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:23.412  1044  1526 D NetworkManagementService: Removing idletimer
08-16 17:45:23.412  1862  1862 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:23.412  1044  1399 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 17:45:23.412  1044  1526 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:23.413  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 17:45:23.414  1044  1449 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:23.414  1044  1449 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:23.414  1951  1967 D WifiServiceExtension: isInternetCheckAvailable return false
08-16 17:45:23.415  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 17:45:23.415  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 17:45:23.415  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:23.415  1044  1044 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 17:45:23.415  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 17:45:23.415  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 17:45:23.416  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 17:45:23.416  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 17:45:23.416  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 17:45:23.416  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 17:45:23.416  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 17:45:23.416  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.416  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:23.416  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:23.416  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.416  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:23.416  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:23.416  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:23.416  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:23.416  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:23.416  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:23.417  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.417  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:23.419  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.419  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 1,7:45:23.419  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:23.419  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.419  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:23.419  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:23.419  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:23.419  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:23.419  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:23.419  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.419  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:45:23.449  1613  1613 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 17:45:23.450  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:23.450  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:23.450  6989  6989 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:45:23.450  6989  6989 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 17:45:23.450  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:23.451  6989  6989 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 17:45:23.451  6989  6989 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 17:45:23.452  6989  6989 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 17:45:23.452  6989  6989 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 17:45:23.463  1613  1613 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 17:45:23.464  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:23.465  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:23.488  2742  2742 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 17:45:23.488  2742  2742 I wpa_supplicant: monitor socket send errors count : 1
08-16 17:45:23.488  2742  2742 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1951-2\x00 that cannot receive messages
08-16 17:45:23.488  1044  2870 D DhcpStateMachine: StoppedState
08-16 17:45:23.488  1044  2870 D DhcpStateMachine: StoppedState{ when=-96ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:45:23.489  1044  2776 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 17:45:23.489  1044  2776 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 17:45:23.489  1044  1449 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 17:45:23.489  1044  1449 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-16 17:45:23.490  6964  6964 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 17:45:23.490  6964  6964 W LG Account v2.2: No ProfileInfo entries
08-16 17:45:23.490  6964  6964 I LG Account v2.2: isEnabled: false
08-16 17:45:23.490  6964  6964 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 17:45:23.490  6964  6964 I Feature : [Lifetracker]Country: EU
08-16 17:45:23.490  6964  6964 I Feature : [Lifetracker]Operator: OPEN
08-16 17:45:23.490  6964  6964 I Feature : [Lifetracker]Ranking support: false
08-16 17:45:23.490  6964  6964 I Feature : [Lifetracker]Comfort support: false
08-16 17:45:23.490  6964  6964 I Feature : [Lifetracker]Accessory: true
08-16 17:45:23.490  6964  6964 I Feature : [Lifetracker]Health device: true
08-16 17:45:23.490  6964  6964 I Feature : [Lifetracker]Extra Pedometer: false
08-16 17:45:23.491  6964  6964 I Feature : [Lifetracker]Blood glucose device: false
08-16 17:45:23.491  6964  6964 I Feature : [Lifetracker]Device Number: 3
08-16 17:45:23.496  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:23.531  1044  2023 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7016 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 17:45:23.532  1044  2023 I ActivityManager: Killing 6390:com.android.defcontainer/u0a4 (adj 15): empty #17
08-16 17:45:23.533  6989  6989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 17:45:23.569  1044  1933 W libprocessgroup: failed to open /acct/uid_10004/pid_6390/cgroup.procs: No such file or directory
,08-16 17:45:23.573  1044  1106 D BluetoothManagerService: Message: 20
08-16 17:45:23.574  1044  1106 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dfc592d:true
08-16 17:45:23.576  3931  3931 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-16 17:45:23.576  3931  3931 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:45:23.576  3931  3931 V BluetoothPbapReceiver: ***********state = 13
08-16 17:45:23.578  3931  3931 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 17:45:23.579  3931  3931 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:23.579  3931  3931 V BluetoothPbapService: state: 13
08-16 17:45:23.579  3931  3931 V BluetoothPbapService: Pbap Service closeService in
08-16 17:45:23.580  3931  3931 V BluetoothPbapService: successfully stopped pbap service
08-16 17:45:23.580  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:45:23.580  3931  3931 V BluetoothPbapService: Pbap Service closeService out
08-16 17:45:23.580  3931  3931 V BluetoothPbapService: Pbap Service onDestroy
08-16 17:45:23.580  3931  3931 V BluetoothPbapService: Pbap Service closeService in
08-16 17:45:23.580  3931  3931 V BluetoothPbapService: Pbap Service closeService out
08-16 17:45:23.580  3931  3931 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-16 17:45:23.584  1044  1106 D BluetoothManagerService: Message: 30
08-16 17:45:23.587  1044  1106 D BluetoothManagerService: Message: 30
08-16 17:45:23.588  2742  2742 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:45:23.589  2742  2742 W wpa_supplicant: USIM:  scard_deinit function
08-16 17:45:23.589  1044  1106 D Tethering: InitialState.processMessage what=4
08-16 17:45:23.589  1044  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 17:45:23.589  1044  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:45:23.589  1044  2776 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:45:23.590  1044  2776 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 17:45:23.590  1044  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:23.590  1044  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:23.590  1044  1449 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=211480
08-16 17:45:23.591  1044  1449 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=211480
08-16 17:45:23.591  1044  1449 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=211481  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 17:45:23.591  1044  1106 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:45:23.592  1044  1449 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=211481  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-16 17:45:23.592  6989  6989 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 17:45:23.593  1044  1449 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:23.593  6989  6989 D BluetoothMap: Create BluetoothMap proxy object
08-16 17:45:23.593  1044  1449 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:23.593  1044  1106 D BluetoothManagerService: Message: 30
08-16 17:45:23.599  1044  1106 D BluetoothManagerService: Message: 30
08-16 17:45:23.600  6989  6989 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 17:45:23.601  6989  6989 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-16 17:45:23.610  6989  6989 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-16 17:45:23.613  6989  6989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-16 17:45:23.621  6989  6989 D DockEventReceiver: finishStartingService: stopping service
08-16 17:45:23.622  6989  6989 D BluetoothInputDevice: Proxy object connected
,08-16 17:45:23.622  6989  6989 D HidProfile: Bluetooth service connected
08-16 17:45:23.628  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 17:45:23.628  6989  6989 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:45:23.629  6989  6989 D PanProfile: Bluetooth service connected
08-16 17:45:23.629  6989  6989 D BluetoothMap: Proxy object connected
08-16 17:45:23.629  6989  6989 D MapProfile: Bluetooth service connected
08-16 17:45:23.630  6989  6989 D BluetoothMap: getConnectedDevices()
08-16 17:45:23.630  6989  6989 D BluetoothMap: Bluetooth is Not enabled
08-16 17:45:23.630  6989  6989 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 17:45:23.631  6989  6989 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 17:45:23.633  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-16 17:45:23.633  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 17:45:23.636  1044  1629 I ActivityManager: Killing 6540:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-16 17:45:23.644  6989  6989 D BluetoothPermissionRequest: onReceive
08-16 17:45:23.647  6989  6989 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 17:45:23.668  6813  6813 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:45:23.668  2742  2742 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 17:45:23.670  1044  2776 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 17:45:23.670  1044  2776 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 17:45:23.670  1044  2776 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 17:45:23.671  1044  1449 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 17:45:23.673  1044  2005 W libprocessgroup: failed to open /acct/uid_10008/pid_6540/cgroup.procs: No such file or directory
08-16 17:45:23.681  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:23.722  6989  6989 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:23.722  6989  6989 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:23.733  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:23.736  1044  1897 I ActivityManager: Killing 6142:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-16 17:45:23.740  6989  6989 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 17:45:23.792  3931  3931 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-16 17:45:23.792  3931  3931 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 17:45:23.794  3931  3931 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 17:45:23.796  1044  2023 W libprocessgroup: failed to open /acct/uid_10011/pid_6142/cgroup.procs: No such file or directory
08-16 17:45:23.804  1044  1449 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 17:45:23.804  1044  1449 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:45:23.804  1044  1449 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:45:23.804  1044  1449 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:45:23.806  1951  1951 D WfdsService: Supplicant Connection state is changed : false
08-16 17:45:23.806  1951  2315 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 17:45:23.806  1951  2315 D WfdsService: Set the WFDS Monitor: false
08-16 17:45:23.807  1951  2315 D WfdsMonitor: WFDS Monitor is stopped
,08-16 17:45:23.820  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:23.820  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-16 17:45:23.824  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 17:45:23.826  1044  1479 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 17:45:23.826  1044  1479 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 17:45:23.828  2488  2488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:23.829  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:23.829  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:23.829  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:23.829  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:23.829  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:23.829  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:23.829  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:23.829  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:23.829  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:23.835  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:23.895  1044  1897 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7045 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 17:45:23.898  3931  3931 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:23.898  3931  3931 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 17:45:23.901  3931  3931 V BluetoothFtpService: Ftp Service onStartCommand
08-16 17:45:23.901  3931  3931 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:23.902  3931  3931 V BluetoothFtpService: Ftp Service closeService
08-16 17:45:23.902  3931  3931 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 17:45:23.905  3931  3931 V BluetoothFtpService: successfully stopped ftp service
08-16 17:45:23.905  3931  3931 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 17:45:23.906  3931  3931 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:45:23.906  3931  3931 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:45:23.906  3931  3931 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:23.906  3931  3931 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 17:45:23.906  3931  3931 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 17:45:23.908  3931  3931 V BluetoothFtpService: Ftp Service onDestroy
08-16 17:45:23.908  3931  3931 V BluetoothFtpService: Ftp Service closeService
,08-16 17:45:23.971  1044  1987 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7062 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 17:45:23.980  3931  3931 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:23.980  3931  3931 V BluetoothSapService: state: 13
08-16 17:45:23.980  3931  3931 V BluetoothSapService: Stopping SAP server process
08-16 17:45:23.983  3931  3931 V BluetoothSapService: Sap Service closeSapService in
08-16 17:45:23.983  3931  3931 V BluetoothSapService: Close listen Socket : 
,08-16 17:45:23.984  3931  3931 V BluetoothSapService: Close rfcomm Socket : 
08-16 17:45:23.985  3931  3931 V BluetoothSapService: Close sapd  Socket : 
08-16 17:45:23.986  3931  3931 V BluetoothSapService: Sap Service closeSapService out
08-16 17:45:23.986  3931  3931 V BluetoothSapService: Sap Service onDestroy
08-16 17:45:23.986  3931  3931 V BluetoothSapService: Sap Service closeSapService in
08-16 17:45:23.986  3931  3931 V BluetoothSapService: Close listen Socket : 
08-16 17:45:23.986  3931  3931 V BluetoothSapService: Close rfcomm Socket : 
08-16 17:45:23.986  3931  3931 V BluetoothSapService: Close sapd  Socket : 
08-16 17:45:23.987  3931  3931 V BluetoothSapService: Sap Service closeSapService out
08-16 17:45:23.994   359   359 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 487us total 23.672ms
08-16 17:45:24.006  7045  7045 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 17:45:24.015   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 20.054ms
,08-16 17:45:24.031  7045  7045 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-16 17:45:24.033   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 18.304ms
08-16 17:45:24.036  7062  7062 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 17:45:24.050  1044  1584 I ActivityManager: Killing 6164:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 17:45:24.063  7045  7045 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-16 17:45:24.063  7045  7045 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 17:45:24.063  7045  7045 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-16 17:45:24.064  7045  7045 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 17:45:24.064  7045  7045 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 17:45:24.065  7045  7045 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 17:45:24.070  7045  7045 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 17:45:24.079  1044  2042 W libprocessgroup: failed to open /acct/uid_10019/pid_6164/cgroup.procs: No such file or directory
,08-16 17:45:24.085  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:24.087  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:24.103  7045  7045 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 17:45:24.106  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:24.107  7045  7045 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-16 17:45:24.113  7045  7045 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 17:45:24.115  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 17:45:24.116  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:45:24.116  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:24.126  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:24.136  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:24.146  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 17:45:24.147  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:24.148  7045  7045 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 17:45:24.152  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:24.154  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 17:45:24.154  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:45:24.155  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:24.159  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:24.169  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 17:45:24.178  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:24.179  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:24.181  7045  7045 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 17:45:24.247  1044  1059 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7082 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 17:45:24.267  3931  4019 D bt_hci_bdroid: cleanup
,08-16 17:45:24.267  3931  4133 I bt_lpm  : LPM is already off!!!
08-16 17:45:24.267  3931  4224 I bt_userial_mct: exiting userial_read_thread
08-16 17:45:24.267  3931  4224 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 17:45:24.267  3931  4129 W bt-btif : ag scb idx 1 not allocated
08-16 17:45:24.267  3931  4129 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 17:45:24.267  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:24.268  3931  4129 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:45:24.268  3931  4129 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 17:45:24.268  3931  4019 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 17:45:24.268  3931  4133 I bt_vendor: hw_epilog_process
08-16 17:45:24.269  3931  4019 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 17:45:24.269  3931  4019 D bt_userial_mct: userial_close
08-16 17:45:24.269  3931  4019 E bt_userial_mct: pthread_join() FAILED result:3
08-16 17:45:24.269  3931  4019 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 17:45:24.328  3931  4019 D bt_hci_bdroid: set_power 0
08-16 17:45:24.328  3931  4019 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 17:45:24.328  3931  4019 I bt_vendor: bluetooth satus is on
08-16 17:45:24.328  3931  4019 I bt_vendor: bt-vendor : resetting BT status
08-16 17:45:24.328  3931  4019 I bt_vendor: Starting hciattach daemon
08-16 17:45:24.328  3931  4019 I bt_vendor: try to set false
08-16 17:45:24.329  3931  4019 I bt_vendor: Starting hciattach daemon
08-16 17:45:24.329  3931  4019 I bt_vendor: try to set false
,08-16 17:45:24.330  3931  4019 I bt_vendor: cleanup
08-16 17:45:24.331  3931  4129 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 17:45:24.331  3931  4019 I GKI_LINUX: GKI_exit_task 0 done
08-16 17:45:24.331  3931  4019 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 17:45:24.333  3931  4011 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 17:45:24.335  3931  3931 D HeadsetService: Received stop request...Stopping profile...
08-16 17:45:24.336  3931  3931 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 17:45:24.336  3931  3931 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:45:24.336  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2810ad28
08-16 17:45:24.336  3931  4067 D HeadsetStateMachine: Exit Disconnected: -1
08-16 17:45:24.338  1044  1044 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:24.338  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 17:45:24.338  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:24.338  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:24.340  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:24.341  3931  3931 D A2dpService: Received stop request...Stopping profile...
08-16 17:45:24.342  3931  4108 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:45:24.345  3931  3931 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-16 17:45:24.348  3931  4011 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 17:45:24.348  3931  3931 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 17:45:24.348  3931  3931 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:45:24.349  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2810ad28
08-16 17:45:24.349  1044  1044 D BluetoothA2dp: Proxy object disconnected
08-16 17:45:24.350  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 17:45:24.351  3931  3931 D HeadsetStateMachine: Unbinding service...
08-16 17:45:24.353  3931  3931 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 17:45:24.353  3931  3931 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 17:45:24.353  3931  3931 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 17:45:24.353  3931  3931 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 17:45:24.353  3931  3931 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:45:24.353  3931  3931 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:45:24.353  3931  3931 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 17:45:24.354  3931  3931 D HidService: Received stop request...Stopping profile...
08-16 17:45:24.354  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2810ad28
08-16 17:45:24.355  6989  6989 D BluetoothInputDevice: Proxy object disconnected
08-16 17:45:24.355  3931  3931 D HealthService: Received stop request...Stopping profile...
08-16 17:45:24.355  6989  6989 D HidProfile: Bluetooth service disconnected
08-16 17:45:24.355  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2810ad28
08-16 17:45:24.356  3931  3931 D PanService: Received stop request...Stopping profile...
08-16 17:45:24.356  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2810ad28
08-16 17:45:24.357  6989  6989 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:45:24.357  6989  6989 D PanProfile: Bluetooth service disconnected
08-16 17:45:24.357  3931  3931 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:45:24.358  3931  3931 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:45:24.358  3931  3931 D BtGatt.GattService: stop()
08-16 17:45:24.358  3931  3931 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:45:24.362  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2810ad28
08-16 17:45:24.363  3931  3931 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:45:24.363  3931  3931 D BluetoothMapService: stop()
08-16 17:45:24.366  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 17:45:24.368  3931  3931 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 17:45:24.368  3931  3931 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 17:45:24.371  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:45:24.374  3931  3931 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2810ad28
08-16 17:45:24.375  3931  3931 I BluetoothA2dpServiceJni: cleanupNative
,08-16 17:45:24.375  3931  4109 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 17:45:24.376  3931  3931 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:45:24.376  3931  3931 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 17:45:24.376  3931  3931 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:45:24.376  3931  3931 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:45:24.377  3931  3931 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:45:24.377  3931  3931 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:45:24.377  3931  3931 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:45:24.377  3931  3931 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:45:24.377  3931  3931 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:45:24.378  3931  3931 V BluetoothMapService: Handler(): got msg=4
08-16 17:45:24.378  3931  3931 D BluetoothMapService: MAP Service closeService in
08-16 17:45:24.378  3931  3931 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 17:45:24.378  3931  3931 V BluetoothMapService: MAP Service closeService out
08-16 17:45:24.379  3931  3931 D BluetoothMapService: cleanup()
08-16 17:45:24.379  3931  3931 D BluetoothMapService: MAP Service closeService in
08-16 17:45:24.379  3931  3931 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 17:45:24.379  3931  3931 V BluetoothMapService: MAP Service closeService out
08-16 17:45:24.379  3931  4011 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:45:24.379  3931  4011 D BluetoothAdapterProperties: Setting state to 10
08-16 17:45:24.379  3931  4011 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:45:24.380  1044  1106 D BluetoothManagerService: Message: 60
08-16 17:45:24.380  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 17:45:24.380  1044  1106 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 17:45:24.380  1044  1106 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:24.380  3931  4011 I BluetoothAdapterState: Entering OffState
08-16 17:45:24.380  1862  1877 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:24.380  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:24.380  6989  7011 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:45:24.386  6989  6989 D BluetoothMap: Proxy object disconnected
08-16 17:45:24.386  6989  6989 D MapProfile: Bluetooth service disconnected
,08-16 17:45:24.388  6989  7102 D BluetoothPan: onBluetoothStateChange on: false
,08-16 17:45:24.389  1044  1106 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:45:24.391  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:24.391  6989  7012 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:45:24.392  6989  7011 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:45:24.393  1862  2466 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:24.395  1044  1106 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 17:45:24.395  1044  1106 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 17:45:24.397  1044  1106 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,08-16 17:45:24.398  1044  1106 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 17:45:24.398  1044  1106 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ef0580a mBinding = false
08-16 17:45:24.399  1044  1106 D BluetoothManagerService: Sending unbind request.
,08-16 17:45:24.402  1044  1106 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 17:45:24.404  1044  1044 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-16 17:45:24.405  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:24.406  1951  2134 D LGBluetoothAPIService: Message: 2
08-16 17:45:24.406  1613  1613 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 17:45:24.406  1951  2134 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3e6778db mBinding = false
08-16 17:45:24.406  1951  2134 D LGBluetoothAPIService: Sending unbind request.
08-16 17:45:24.410  6989  6989 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 17:45:24.411  1613  1613 D BluetoothAdapter: 373615427: getState() :  mService = null. Returning STATE_OFF
08-16 17:45:24.411  1613  1613 D BluetoothAdapter: 373615427: getState() :  mService = null. Returning STATE_OFF
08-16 17:45:24.413  6989  6989 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 17:45:24.413  6989  6989 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 17:45:24.415  3931  4019 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 17:45:24.416  3931  3931 I GKI_LINUX: GKI_exit_task 1 done
08-16 17:45:24.416  3931  3931 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 17:45:24.416  3931  3931 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 17:45:24.416  3931  3931 I art     : --- WEIRD: removing null entry 246
08-16 17:45:24.416  3931  3931 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 17:45:24.416  3931  3931 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 17:45:24.418  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:24.418  7082  7103 W FormManager: Network not available. Please check & try again.
08-16 17:45:24.419  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:24.419  6989  6989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 17:45:24.422  3931  3931 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-16 17:45:24.426  3931  3931 I art     : System.exit called, status: 0
08-16 17:45:24.426  3931  3931 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 17:45:24.432  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 17:45:24.432  7082  7104 V FormManager: Network unavailable.
08-16 17:45:24.433  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 17:45:24.433  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 17:45:24.433  6989  6989 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 17:45:24.434  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 17:45:24.435  7082  7104 V FormManager: Network unavailable.
08-16 17:45:24.445   311  1406 V AudioFlinger: 3931 died, releasing its sessions
08-16 17:45:24.445   311  1406 V AudioFlinger:  pid 1862 @ 0
08-16 17:45:24.445   311  1406 V AudioFlinger:  pid 3504 @ 1
08-16 17:45:24.445   311  1406 V AudioFlinger:  pid 3504 @ 2
,08-16 17:45:24.454  6989  6989 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 17:45:24.454  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 17:45:24.454  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 17:45:24.454  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 17:45:24.454  6989  6989 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 17:45:24.454  6989  6989 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 17:45:24.517  1044  1629 I ActivityManager: Process com.android.bluetooth (pid 3931) has died
08-16 17:45:24.518  1044  1629 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 17:45:24.537  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 17:45:24.538  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 17:45:24.544  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:45:24.544  6989  6989 D DockEventReceiver: finishStartingService: stopping service
08-16 17:45:24.545  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:24.548  6989  6989 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 17:45:24.558  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 17:45:24.573  4340  7109 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 17:45:24.576  4340  7110 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 17:45:24.577  4340  7110 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 17:45:24.600  7016  7016 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 17:45:24.601  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:45:24.601  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:24.604  6989  6989 D BluetoothPermissionRequest: onReceive
,08-16 17:45:24.608  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:45:24.622  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 17:45:24.622  7082  7112 W FormManager: Network not available. Please check & try again.
08-16 17:45:24.623  6989  6989 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 17:45:24.624  6989  6989 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 17:45:24.630  7082  7113 V FormManager: Network unavailable.
,08-16 17:45:24.634  6989  6989 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 17:45:24.719  1044  1896 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7117 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 17:45:24.733  7082  7113 V FormManager: Network unavailable.
,08-16 17:45:24.745  1044  1897 I ActivityManager: Killing 6588:com.lge.email/u0a23 (adj 15): empty #17
,08-16 17:45:24.790  1044  1969 W libprocessgroup: failed to open /acct/uid_10023/pid_6588/cgroup.procs: No such file or directory
,08-16 17:45:24.801  1044  1388 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39de2fd3 type 2 when 212669 com.google.android.gms} when 212669
08-16 17:45:24.813  7045  7045 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 17:45:24.815  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 17:45:24.816  7045  7045 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 17:45:24.832  7117  7117 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 17:45:24.833  7117  7117 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 17:45:24.834  7117  7117 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 17:45:24.836  7117  7117 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 17:45:24.860  7117  7117 D BluetoothAdapterApp: Loading JNI Library
,08-16 17:45:24.862  7045  7045 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:24.862  7045  7045 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 17:45:24.871  7045  7045 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 17:45:24.875  7045  7045 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 17:45:24.875  7045  7045 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-16 17:45:24.875  7045  7045 V SoundPool: doLoad: loading sample sampleID=1
08-16 17:45:24.876  7045  7136 V SoundPool: Start decode
08-16 17:45:24.876  7045  7136 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-16 17:45:24.876   311   311 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 17:45:24.877   311   311 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 17:45:24.877   311   311 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 17:45:24.877   311   311 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 17:45:24.877   311   311 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 17:45:24.877   311   311 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 17:45:24.877   311   311 V MediaPlayerService: player type = 3
08-16 17:45:24.877   311   311 V AwesomePlayer: AwesomePlayer create()
08-16 17:45:24.877  7045  7045 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 17:45:24.877   311   311 V AwesomePlayer: reset_l() 
08-16 17:45:24.877   311   311 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:24.877   311   311 V AwesomePlayer: setAudioSink() 
08-16 17:45:24.877   311   311 V AwesomePlayer: reset_l() 
08-16 17:45:24.877   311   311 V AudioCache: notify(0xb5474b40, 8, 0, 0)
08-16 17:45:24.877   311   311 V AudioCache: ignored
08-16 17:45:24.877   311   311 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:24.877   311   311 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 17:45:24.878   311   311 V AwesomePlayer: setDataSource_l dataSource
08-16 17:45:24.878   311   311 V LGParserOSAL: SniffLGParser start
08-16 17:45:24.878   311   311 V LGParserOSAL: MainType:5, SubType=0
08-16 17:45:24.878   311   311 V LGParserOSAL: #### check Mime : application/ogg
08-16 17:45:24.878   311   311 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 17:45:24.878   311   311 E MediaExtractor: Use LGExtractor :application/ogg 
,08-16 17:45:24.893  7045  7045 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 17:45:24.894  6729  6729 D UEI.SmartControl: QS Service created
08-16 17:45:24.896  7045  7045 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 17:45:24.897  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 17:45:24.903  7117  7117 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15121309 Instance Count = 1
08-16 17:45:24.910  7117  7117 D BluetoothAdapterApp: onCreate
08-16 17:45:24.911  7045  7045 V LGMDMManager: Create singleton instance
,08-16 17:45:24.923   311   311 V LGParserOSAL: supported mime: application/ogg
08-16 17:45:24.923   311   311 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 17:45:24.923   311   311 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-16 17:45:24.923   311   311 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 17:45:24.923   311   311 V AwesomePlayer: AudioTrack Setting
08-16 17:45:24.923   311   311 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 17:45:24.923   311   311 V AwesomePlayer: setAudioSource() 
08-16 17:45:24.923   311   311 V MediaPlayerService: prepare
08-16 17:45:24.923   311   311 V AwesomePlayer: prepareAsync_l() 
08-16 17:45:24.923   311   311 V MediaPlayerService: wait for prepare
08-16 17:45:24.924   311  7137 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 17:45:24.924   311  7137 V AwesomePlayer: initAudioDecoder() 
08-16 17:45:24.924   311  7137 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 17:45:24.924   311  7137 V AudioSystem: isOffloadSupported()
08-16 17:45:24.924   311  7137 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 17:45:24.924   311  7137 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 17:45:24.924   311  7137 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 17:45:24.924   311  7137 V AwesomePlayer: getUseOffload() = 0 
08-16 17:45:24.924   311  7137 V OMXCodec: OMXCodec::Create
08-16 17:45:24.924   311  7137 V OMXCodec: findMatchingCodecs()
08-16 17:45:24.924   311  7137 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 17:45:24.924   311  7137 V OMXCodec: matchingCodecs.size()=1
08-16 17:45:24.924   311  7137 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 17:45:24.926   311  7137 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 17:45:24.926   311  7137 V LGCodecAdapter: LG Codec Adapter start
08-16 17:45:24.926   311  7137 V OMXCodec: OMXCodec Createtor
08-16 17:45:24.926   311  7137 V OMXCodec: setComponentRole
08-16 17:45:24.926   311  7137 V OMXCodec: configureCodec protected=0
08-16 17:45:24.926   311  7137 V LGCodecAdapter: called getLGCodecSpecificData
08-16 17:45:24.926   311  7137 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 17:45:24.926   311  7137 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 17:45:24.926   311  7137 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 17:45:24.926   311  7137 V LGCodecOSAL: Not support LGCodec
08-16 17:45:24.926   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 17:45:24.926   311  7137 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 17:45:24.926   311  7137 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 17:45:24.926   311  7137 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 17:45:24.926   311  7137 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 17:45:24.926   311  7137 V AudioSystem: isOffloadSupported()
08-16 17:45:24.926   311  7137 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 17:45:24.926   311  7137 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 17:45:24.926   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 17:45:24.926   311  7137 V OMXCodec: init()
08-16 17:45:24.926   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-16 17:45:24.926   311  7137 V OMXCodec: allocateBuffers
08-16 17:45:24.926   311  7137 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 17:45:24.926   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on, input port
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-16 17:45:24.927   311  7137 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-16 17:45:24.927   311  7137 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57f9100 on output port
08-16 17:45:24.927   311  7137 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 17:45:24.927   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 17:45:24.927   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 17:45:24.927   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 17:45:24.927   311  7137 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 17:45:24.927   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 17:45:24.927   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 17:45:24.928   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 17:45:24.928   311  7137 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 17:45:24.928   311  7137 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 17:45:24.928   311  7137 V AudioCache: notify(0xb5474b40, 5, 0, 0)
08-16 17:45:24.928   311  7137 V AudioCache: ignored
08-16 17:45:24.928   311  7137 V AudioCache: notify(0xb5474b40, 1, 0, 0)
08-16 17:45:24.928   311  7137 V AudioCache: prepared
08-16 17:45:24.928   311   311 V AudioCache: wait - success
08-16 17:45:24.928   311   311 V MediaPlayerService: start
08-16 17:45:24.928   311   311 V AwesomePlayer: play_l() 
08-16 17:45:24.928   311   311 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
,08-16 17:45:24.928   311   311 V AwesomePlayer: createAudioPlayer_l
08-16 17:45:24.928   311   311 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 17:45:24.928   311   311 V AwesomePlayer: startAudioPlayer_l() 
08-16 17:45:24.928   311   311 D AudioPlayer: start of Playback, useOffload 0
08-16 17:45:24.928   311   311 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 17:45:24.928   311   311 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 17:45:24.931   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 17:45:24.931   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 17:45:24.931   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 17:45:24.931   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 17:45:24.931   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1),
08-16 17:45:24.931   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 17:45:24.931   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-16 17:45:24.931   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
,08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3045036288
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 17:45:24.932   311  7139 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-16 17:45:24.932  7117  7117 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on output port
08-16 17:45:24.932  7117  7117 D ProfileConfigQcom: Adding HeadsetService
,08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 17:45:24.932   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 17:45:24.933  7117  7117 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 17:45:24.933  7117  7117 D ProfileConfigQcom: Adding A2dpService
08-16 17:45:24.933  7117  7117 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 17:45:24.933  7117  7117 D ProfileConfigQcom: Adding HidService
,08-16 17:45:24.933  7117  7117 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 17:45:24.934  7117  7117 D ProfileConfigQcom: Adding HealthService
08-16 17:45:24.934  7117  7117 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 17:45:24.934   311   311 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 17:45:24.934  7117  7117 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 17:45:24.935  7117  7117 D ProfileConfigQcom: Adding PanService
08-16 17:45:24.935   311   311 V AudioCache: notify(0xb5474b40, 6, 0, 0)
08-16 17:45:24.935   311   311 V AudioCache: ignored
,08-16 17:45:24.935  7117  7117 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 17:45:24.935   311   311 V MediaPlayerService: wait for playback complete
08-16 17:45:24.935  7117  7117 D ProfileConfigQcom: Adding GattService
08-16 17:45:24.935  7117  7117 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 17:45:24.935  7117  7117 D ProfileConfigQcom: Adding BluetoothMapService
08-16 17:45:24.936  7117  7117 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 17:45:24.937  7117  7117 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-16 17:45:24.942   311  7141 V AudioCache: write(0xb1788000, 4096)
,08-16 17:45:24.942   311  7141 V AudioCache: memcpy(0xaf006000, 0xb1788000, 4096)
08-16 17:45:24.945  6989  6989 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 17:45:24.945  7117  7117 V LGMDMManagerInternal: Create singleton instance
08-16 17:45:24.945  6729  6729 I UEI.SmartControl: Service initServices...
08-16 17:45:24.945  6729  6729 D UEI.SmartControl: QS start get config
08-16 17:45:24.947   311  7141 V AudioCache: write(0xb1788000, 4096)
,08-16 17:45:24.948   311  7141 V AudioCache: memcpy(0xaf007000, 0xb1788000, 4096)
,08-16 17:45:24.948   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.948   311  7141 V AudioCache: memcpy(0xaf008000, 0xb1788000, 4096)
08-16 17:45:24.958   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.958   311  7141 V AudioCache: memcpy(0xaf009000, 0xb1788000, 4096)
08-16 17:45:24.959   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.959   311  7141 V AudioCache: memcpy(0xaf00a000, 0xb1788000, 4096)
08-16 17:45:24.960   311  7141 V AudioCache: write(0xb1788000, 4096)
,08-16 17:45:24.960   311  7141 V AudioCache: memcpy(0xaf00b000, 0xb1788000, 4096)
08-16 17:45:24.961   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.961   311  7141 V AudioCache: memcpy(0xaf00c000, 0xb1788000, 4096)
,08-16 17:45:24.962   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.962   311  7141 V AudioCache: memcpy(0xaf00d000, 0xb1788000, 4096)
08-16 17:45:24.963   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.963   311  7141 V AudioCache: memcpy(0xaf00e000, 0xb1788000, 4096)
08-16 17:45:24.964   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.964   311  7141 V AudioCache: memcpy(0xaf00f000, 0xb1788000, 4096)
08-16 17:45:24.965   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.965   311  7141 V AudioCache: memcpy(0xaf010000, 0xb1788000, 4096)
08-16 17:45:24.966   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.966   311  7141 V AudioCache: memcpy(0xaf011000, 0xb1788000, 4096)
08-16 17:45:24.966   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.966   311  7141 V AudioCache: memcpy(0xaf012000, 0xb1788000, 4096)
08-16 17:45:24.967   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.967   311  7141 V AudioCache: memcpy(0xaf013000, 0xb1788000, 4096)
08-16 17:45:24.968   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.968   311  7141 V AudioCache: memcpy(0xaf014000, 0xb1788000, 4096)
08-16 17:45:24.968   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.968   311  7141 V AudioCache: memcpy(0xaf015000, 0xb1788000, 4096)
08-16 17:45:24.969   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.969   311  7141 V AudioCache: memcpy(0xaf016000, 0xb1788000, 4096)
08-16 17:45:24.969   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.969   311  7141 V AudioCache: memcpy(0xaf017000, 0xb1788000, 4096)
08-16 17:45:24.970   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.970   311  7141 V AudioCache: memcpy(0xaf018000, 0xb1788000, 4096)
08-16 17:45:24.971   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.971   311  7141 V AudioCache: memcpy(0xaf019000, 0xb1788000, 4096)
08-16 17:45:24.971   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.971   311  7141 V AudioCache: memcpy(0xaf01a000, 0xb1788000, 4096)
08-16 17:45:24.972   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.972   311  7141 V AudioCache: memcpy(0xaf01b000, 0xb1788000, 4096)
08-16 17:45:24.973   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.973   311  7141 V AudioCache: memcpy(0xaf01c000, 0xb1788000, 4096)
08-16 17:45:24.973   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.973   311  7141 V AudioCache: memcpy(0xaf01d000, 0xb1788000, 4096)
08-16 17:45:24.974   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.974   311  7141 V AudioCache: memcpy(0xaf01e000, 0xb1788000, 4096)
,08-16 17:45:24.975   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.975   311  7141 V AudioCache: memcpy(0xaf01f000, 0xb1788000, 4096)
08-16 17:45:24.976   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.976   311  7141 V AudioCache: memcpy(0xaf020000, 0xb1788000, 4096)
08-16 17:45:24.977   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.977   311  7141 V AudioCache: memcpy(0xaf021000, 0xb1788000, 4096)
08-16 17:45:24.978   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.978   311  7141 V AudioCache: memcpy(0xaf022000, 0xb1788000, 4096)
08-16 17:45:24.979   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.979   311  7141 V AudioCache: memcpy(0xaf023000, 0xb1788000, 4096)
08-16 17:45:24.979   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.979   311  7141 V AudioCache: memcpy(0xaf024000, 0xb1788000, 4096)
08-16 17:45:24.980   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.980   311  7141 V AudioCache: memcpy(0xaf025000, 0xb1788000, 4096)
08-16 17:45:24.981   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.981   311  7141 V AudioCache: memcpy(0xaf026000, 0xb1788000, 4096)
08-16 17:45:24.982   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.982   311  7141 V AudioCache: memcpy(0xaf027000, 0xb1788000, 4096)
08-16 17:45:24.982   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.982   311  7141 V AudioCache: memcpy(0xaf028000, 0xb1788000, 4096)
08-16 17:45:24.983   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.983   311  7141 V AudioCache: memcpy(0xaf029000, 0xb1788000, 4096)
08-16 17:45:24.984   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.984   311  7141 V AudioCache: memcpy(0xaf02a000, 0xb1788000, 4096)
08-16 17:45:24.984   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.984   311  7141 V AudioCache: memcpy(0xaf02b000, 0xb1788000, 4096)
,08-16 17:45:24.985   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.985   311  7141 V AudioCache: memcpy(0xaf02c000, 0xb1788000, 4096)
08-16 17:45:24.986   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.986   311  7141 V AudioCache: memcpy(0xaf02d000, 0xb1788000, 4096)
08-16 17:45:24.987   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.987   311  7141 V AudioCache: memcpy(0xaf02e000, 0xb1788000, 4096)
08-16 17:45:24.988   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.988   311  7141 V AudioCache: memcpy(0xaf02f000, 0xb1788000, 4096)
08-16 17:45:24.989   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.989   311  7141 V AudioCache: memcpy(0xaf030000, 0xb1788000, 4096)
08-16 17:45:24.989   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.989   311  7141 V AudioCache: memcpy(0xaf031000, 0xb1788000, 4096)
08-16 17:45:24.990   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.990   311  7141 V AudioCache: memcpy(0xaf032000, 0xb1788000, 4096)
08-16 17:45:24.991   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.991   311  7141 V AudioCache: memcpy(0xaf033000, 0xb1788000, 4096)
08-16 17:45:24.991   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.991   311  7141 V AudioCache: memcpy(0xaf034000, 0xb1788000, 4096)
08-16 17:45:24.992   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.992   311  7141 V AudioCache: memcpy(0xaf035000, 0xb1788000, 4096)
08-16 17:45:24.992   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.992   311  7141 V AudioCache: memcpy(0xaf036000, 0xb1788000, 4096)
08-16 17:45:24.993   311  7141 V AudioCache: write(0xb1788000, 4096)
08-16 17:45:24.993   311  7141 V AudioCache: memcpy(0xaf037000, 0xb1788000, 4096)
08-16 17:45:24.993   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 17:45:24.993   311  7141 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 17:45:24.993   311  7141 V AwesomePlayer: postAudioEOS() 
08-16 17:45:24.993   311  7141 V AudioCache: write(0xb1788000, 280)
08-16 17:45:24.993   311  7141 V AudioCache: memcpy(0xaf038000, 0xb1788000, 280)
08-16 17:45:24.997   311  7137 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 17:45:24.997   311  7137 V AwesomePlayer: onStreamDone
08-16 17:45:24.997   311  7137 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 17:45:24.997   311  7137 V AudioCache: notify(0xb5474b40, 2, 0, 0)
08-16 17:45:24.997   311  7137 V AudioCache: playback complete
08-16 17:45:24.997   311  7137 V AwesomePlayer: pause_l() 
08-16 17:45:24.997   311   311 V AudioCache: wait - success
08-16 17:45:24.997   311  7137 V AudioCache: notify(0xb5474b40, 7, 0, 0)
08-16 17:45:24.997   311   311 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 17:45:24.997   311  7137 V AudioCache: ignored
08-16 17:45:24.997   311  7137 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:24.997   311  7137 D AudioPlayer: Pause Playback at 1068125
08-16 17:45:24.998   311   311 V AwesomePlayer: reset_l() 
08-16 17:45:24.998   311   311 V AudioCache: notify(0xb5474b40, 8, 0, 0)
08-16 17:45:24.998   311   311 V AudioCache: ignored
08-16 17:45:24.998   311   311 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:24.998   311   311 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 17:45:24.998   311   311 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 17:45:24.998   311   311 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 17:45:24.998   311   311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 17:45:24.998   311   311 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 17:45:24.999   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 17:45:24.999   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 17:45:24.999   311  71,39 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 17:45:24.999   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-16 17:45:24.999   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 17:45:24.999   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-16 17:45:24.999   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
,08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 1
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-16 17:45:25.000   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:25.001   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 17:45:25.001   311   311 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 17:45:25.001   311   311 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 17:45:25.001   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 17:45:25.001   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 17:45:25.001   311  7139 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 17:45:25.001   311   311 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 17:45:25.001   311   311 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 17:45:25.001   311   311 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 17:45:25.002   311   311 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 17:45:25.002   311   311 D AudioPlayer: AudioPlayer releasing audio source
08-16 17:45:25.002   311   311 D AudioPlayer: AudioPlayer done releasing audio source
08-16 17:45:25.002   311   311 V AwesomePlayer: reset_l() 
08-16 17:45:25.003   311   311 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:25.003   311   311 V AwesomePlayer: ~AwesomePlayer call
08-16 17:45:25.003   311   311 V AwesomePlayer: reset_l() 
08-16 17:45:25.003   311   311 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:25.004  7045  7136 V SoundPool: close(32)
08-16 17:45:25.004  7045  7136 V SoundPool: pointer = 0xa002d000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 17:45:25.022  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 17:45:25.023  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-16 17:45:25.026  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4188
08-16 17:45:25.032   307  7148 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 17:45:25.032  1044  1104 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-16 17:45:25.052  7117  7117 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:45:25.055  7117  7117 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 17:45:25.055  7117  7117 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:45:25.055  7117  7117 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:45:25.056  7117  7117 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:25.056  7117  7117 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 17:45:25.063  7062  7062 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 17:45:25.254  6729  6729 I UEI.SmartControl: Supports setup maps: true
,08-16 17:45:25.258  6729  6729 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 17:45:25.258  6729  6729 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-16 17:45:25.258  6729  6729 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 17:45:25.258  6729  6729 I UEI.SmartControl: ### init IR Blaster...
08-16 17:45:25.261  6729  6729 D serial_port: Configuring serial port
08-16 17:45:25.261  6729  6729 E UEI.SmartControl: UEIBLaster setting for 616
08-16 17:45:25.261  6729  6729 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 17:45:25.261  6729  6729 I UEI.SmartControl: configuring settings for MAXQ616
08-16 17:45:25.261  6729  6729 I UEI.SmartControl: Get version...
08-16 17:45:25.280  6729  7150 D UEI.SmartControl: serial port data available: 21
,08-16 17:45:25.309  6729  6729 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 17:45:25.309  6729  6729 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-16 17:45:25.309  6729  6729 I UEI.SmartControl: QS saving settings...
08-16 17:45:25.311  6729  6729 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 17:45:25.329  6729  7150 D UEI.SmartControl: serial port data available: 4
,08-16 17:45:25.358  6729  7156 I UEI.SmartControl: Device manager: loading config....
,08-16 17:45:25.359  6729  7156 D UEI.SmartControl: ----------- loading internal config...
08-16 17:45:25.361  6729  6729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 17:45:25.371  6729  6729 E UEI.SmartControl: Services init done
08-16 17:45:25.371  6729  6729 D UEI.SmartControl: QS Service init finished
08-16 17:45:25.373  6729  7156 E UEI.SmartControl: Loading SETTINGS...
,08-16 17:45:25.374  6729  6729 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 17:45:25.374  6729  6729 D UEI.SmartControl: QS Service version code: 201091
08-16 17:45:25.375  6729  6729 D UEI.SmartControl: Service requested: Control
08-16 17:45:25.379  7045  7045 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 17:45:25.381  6729  6745 I UEI.SmartControl: ------ IControl API: 11
08-16 17:45:25.381  6729  6745 D UEI.SmartControl: File observer start...
08-16 17:45:25.381  6729  6729 D UEI.SmartControl: Internal service binding...
08-16 17:45:25.382  6729  6745 E UEI.SmartControl: IR Port is disabled: false
08-16 17:45:25.382  6729  6745 D UEI.SmartControl: Starting file observer...
08-16 17:45:25.383  6729  6745 I UEI.SmartControl: Registering callback...
08-16 17:45:25.384  6729  6744 I UEI.SmartControl: ------ IControl API: 19
08-16 17:45:25.386  6729  7156 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 17:45:25.386  6729  6744 I UEI.SmartControl: Registering Services Ready callback...
,08-16 17:45:25.397  6729  7155 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 17:45:25.398  7045  7060 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 17:45:25.398  6729  7155 D UEI.SmartControl: -----service ready thread exits
08-16 17:45:25.399  7045  7134 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 17:45:25.399  7045  7134 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 17:45:25.399  7045  7045 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 17:45:25.400  7045  7045 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-16 17:45:25.400  6729  6745 I UEI.SmartControl: ------ IControl API: 8
08-16 17:45:25.402  7045  7045 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 17:45:25.403  7045  7045 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 17:45:25.403  7045  7045 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 17:45:25.404  7045  7045 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 17:45:25.405  7045  7045 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 17:45:25.406  7045  7045 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 17:45:25.407  7045  7045 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 17:45:25.410  7045  7045 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 17:45:25.412  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-16 17:45:25.413  7045  7045 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 17:45:25.413  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-16 17:45:25.415  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 17:45:25.416  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 17:45:25.416  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 17:45:25.418  7045  7045 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471362325417]
08-16 17:45:25.420  7045  7045 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 17:45:25.423  1044  1969 I ActivityManager: Killing 6265:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-16 17:45:25.446  7045  7161 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 17:45:25.467  1044  1969 I ActivityManager: Killing 6189:com.android.gallery3d/u0a27 (adj 15): empty #18
,08-16 17:45:25.496  1044  2005 W libprocessgroup: failed to open /acct/uid_10080/pid_6265/cgroup.procs: No such file or directory
,08-16 17:45:25.502  1044  1059 W libprocessgroup: failed to open /acct/uid_10027/pid_6189/cgroup.procs: No such file or directory
08-16 17:45:25.509  7045  7045 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-16 17:45:25.510  7045  7045 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 17:45:25.511  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 17:45:25.511  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 17:45:25.512  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 17:45:25.512  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 17:45:25.513  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 17:45:25.525  7045  7045 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 17:45:26.286  1044  1968 D WifiServiceImplEx: setWifiEnabled: true pid=6813, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 17:45:26.294  1044  1968 D WifiService: setWifiEnabled: true pid=6813, uid=10118
08-16 17:45:26.294  1044  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:45:26.316  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 17:45:26.317  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:45:26.317  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 17:45:26.318  1044  1449 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 17:45:26.318  1044  1449 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 17:45:26.321  1044  1449 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 17:45:26.321  1044  1449 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 17:45:26.321  1044  1449 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 17:45:26.321  1044  1449 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-16 17:45:26.321  1044  1449 I WifiUtil: Intf0MacAddress=C49A027FFB5D,
08-16 17:45:26.321  1044  1449 E WifiHW  : unknown target_country: EU , set to default
,08-16 17:45:26.321  1044  1449 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-16 17:45:26.321  1044  1449 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
,08-16 17:45:26.322  1044  1449 I WifiUtil: gEnableBmps=1
,08-16 17:45:26.408  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:26.442  1044  1106 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:45:26.447  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:26.455  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:26.461  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:26.464  1044  1106 D Tethering: MasterInitialState.processMessage what=3
08-16 17:45:26.478  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:26.481  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:26.482  1044  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:26.484  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 17:45:26.487  6505  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 17:45:26.489  5870  5870 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 17:45:26.501  5870  5870 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 17:45:26.530  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:26.586  1044  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:26.594  1044  1059 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7166 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-16 17:45:26.601  1044  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:26.601  1044  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:45:26.699  7166  7166 I AppUp4:AppBoxCP: onCreate
08-16 17:45:26.700  7166  7166 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 17:45:26.713  7166  7166 I AppUp4:DB:  setFingerPrint start
08-16 17:45:26.713  7166  7166 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 17:45:26.722  7166  7166 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 17:45:26.722  7166  7166 I AppUp4:DB:  SDK version = 21
08-16 17:45:26.722  7166  7166 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-16 17:45:26.724  7166  7166 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-16 17:45:26.726  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-16 17:45:26.726  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:26.731  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 17:45:26.732  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 17:45:26.741  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 17:45:26.795  7166  7166 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:26.796  7166  7166 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:26.806  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2be7af4b
08-16 17:45:26.806  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 17:45:26.806  7166  7166 D AppUp4:CustFacade: isPhone : true
08-16 17:45:26.807  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-16 17:45:26.807  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 17:45:26.808  7166  7166 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-16 17:45:26.810  7166  7200 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 17:45:26.810  7166  7200 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 17:45:26.810  7166  7200 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 17:45:26.819  1044  2005 I ActivityManager: Killing 6291:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-16 17:45:26.899  1044  1059 W libprocessgroup: failed to open /acct/uid_10097/pid_6291/cgroup.procs: No such file or directory
,08-16 17:45:26.900  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:26.901  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 17:45:26.909  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:26.911  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:26.918  4340  7212 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 17:45:26.924  4340  7213 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:26.925  4340  7213 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 17:45:26.973  1044  1629 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7214 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 17:45:27.020  1044  1106 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:45:27.023   307   904 D SoftapController: Softap fwReload - Ok
,08-16 17:45:27.025  1044  1449 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (697ms)
08-16 17:45:27.031   307   904 D CommandListener: Setting iface cfg
08-16 17:45:27.032   307   904 D CommandListener: Trying to bring down wlan0
08-16 17:45:27.038  1044  1106 D Tethering: InitialState.processMessage what=4
08-16 17:45:27.038   307   904 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:45:27.041  1044  1449 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 17:45:27.041  1044  1106 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:45:27.043  1044  1449 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:45:27.043  1044  1449 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:45:27.043  1044  1449 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:45:27.047  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:27.049  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 17:45:27.037  7232  7232 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:27.037  7232  7232 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:27.055  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-16 17:45:27.058  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:27.059  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:27.059  1044  1449 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 17:45:27.059  1044  1449 D WifiMonitor: connecting to supplicant
,08-16 17:45:27.079  7232  7232 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 17:45:27.092  7214  7214 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:45:27.092  7214  7214 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 17:45:27.094  7214  7214 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 17:45:27.094  7214  7214 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 17:45:27.115  7232  7232 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 17:45:27.115  7232  7232 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 17:45:27.192  7214  7214 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 17:45:27.207  7214  7214 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 17:45:27.213  7232  7232 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 17:45:27.250  7214  7214 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 17:45:27.266  7232  7232 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 17:45:27.285  7232  7232 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-16 17:45:27.286  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 17:45:27.287  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
,08-16 17:45:27.288  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 17:45:27.288  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 17:45:27.288  1044  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 17:45:27.288  1044  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 17:45:27.289  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 17:45:27.290  1044  1449 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 17:45:27.290  7214  7214 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:27.290  7214  7214 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 17:45:27.291  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:27.292  1044  1449 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:27.293  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:27.295  1044  1449 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:27.296  1044  1449 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,08-16 17:45:27.296  1044  1449 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 17:45:27.297  1044  1449 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 17:45:27.297  1044  1449 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 17:45:27.297  1044  1449 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 17:45:27.298  1044  1449 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:45:27.298  1044  1449 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:45:27.298  1044  1449 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:45:27.298  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.298  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.299  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.299  1044  1449 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 17:45:27.299  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.299  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:45:27.300  1044  1449 D WifiNative-wlan0: SET update_config 1: returned true
08-16 17:45:27.300  1044  1449 D WifiConfigStore: Loading config and enabling all networks 
08-16 17:45:27.301  1044  1449 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 17:45:27.301  1044  1449 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 17:45:27.302  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:27.303  1951  1951 D WfdService: Waiting for WifiP2p enabling
08-16 17:45:27.304  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 17:45:27.304  1044  1479 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 17:45:27.305  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:27.305  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:27.305  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:27.305  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:27.305  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:27.305  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:27.305  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:27.305  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:27.305  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:27.305  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:27.305  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:27.308  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:27.308  6813  6813 V io.jxcore.node.Connectiv,ityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:27.308  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:27.308  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:27.308  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:27.308  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:27.308  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:27.308  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:27.308  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:27.308  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:27.308  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:27.308  1044  1449 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 17:45:27.317  1044  1449 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 17:45:27.318  1044  1449 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:45:27.318  1044  1449 D WifiStateMachine: enableVerboseLogging : level 2
08-16 17:45:27.318  1044  1449 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 17:45:27.319  1044  1449 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 17:45:27.319  1044  1449 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 17:45:27.320  1044  1449 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 17:45:27.320  1044  1449 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-16 17:45:27.320  1044  1449 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 17:45:27.320  1044  1449 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 17:45:27.321  1044  1449 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 17:45:27.321  1044  1449 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 17:45:27.321  1044  1449 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 17:45:27.321  1044  1449 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 17:45:27.322  1044  1449 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 17:45:27.322  1044  1449 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 17:45:27.322  1044  1449 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 17:45:27.323  1044  1449 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:45:27.323  1044  1449 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 17:45:27.324  1044  1449 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 17:45:27.324  1044  1449 D WifiNative-HAL: Setting external_sim to 1
08-16 17:45:27.324  1044  1449 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 17:45:27.324  1044  1449 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 17:45:27.324  1044  1449 I WifiNative-HAL: startHal
08-16 17:45:27.324  1044  1449 D wifi    : setting scan oui 0xaf669e00
08-16 17:45:27.325  1044  1449 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:45:27.325  1044  1449 I WifiNative-HAL: startHal
08-16 17:45:27.325  1044  1449 D wifi    : setting scan oui 0xaf669e00
08-16 17:45:27.325  1044  1449 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 17:45:27.325  1951  1951 D WfdsService: Supplicant Connection state is changed : true
08-16 17:45:27.326  1044  1449 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 17:45:27.326  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 17:45:27.326  1951  2315 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 17:45:27.326  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 17:45:27.326  1951  2315 D WfdsService: Set the WFDS Monitor: true
08-16 17:45:27.326  1951  2315 D WfdsMonitor: WfdsMonitorThread create
08-16 17:45:27.327  1951  2315 D WfdsMonitor: WFDS Monitor is created and started
08-16 17:45:27.327  1951  2315 D WfdsService: WiFi: Supplicant connection re-established
08-16 17:45:27.327  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 17:45:27.327  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 17:45:27.327  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 17:45:27.328  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 17:45:27.328  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 17:45:27.328  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 17:45:27.328  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 17:45:27.328  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 17:45:27.328  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 17:45:27.328  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-16 17:45:27.328  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 17:45:27.329  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 17:45:27.329  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 17:45:27.329  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 17:45:27.329  7232  7232 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
,08-16 17:45:27.329  1951  7242 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 17:45:27.330  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 17:45:27.330  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 17:45:27.330  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 17:45:27.330  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-16 17:45:27.330  1951  7242 E CtrlSupplicant: Succeed to open control connection
08-16 17:45:27.331  1951  7242 E CtrlSupplicant: Succeed to open monitor connection
08-16 17:45:27.331  1044  1449 E WifiNative: : [215,220,350 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 17:45:27.331  1044  1449 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 17:45:27.332  1044  1449 D WifiNative-wlan0: RECONNECT: returned true
08-16 17:45:27.332  1044  1449 D WifiNative-wlan0: doString: [STATUS]
08-16 17:45:27.332  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,08-16 17:45:27.332  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 17:45:27.333  1044  1449 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 17:45:27.333  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 1
,08-16 17:45:27.333  1044  1449 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:45:27.334  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 17:45:27.334  1044  1044 D RttService: SCAN_AVAILABLE : 3
08-16 17:45:27.334  1044  1565 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.334  1044  1565 I WifiNative-HAL: startHal
08-16 17:45:27.334  1044  1565 D wifi    : getting scan capabilities on interface[1] = 0xaf669e00
08-16 17:45:27.334  1044  1565 D wifi    : failed to get capabilities : -3
08-16 17:45:27.334  1044  1565 E WifiScanningService: could not get scan capabilities
08-16 17:45:27.335  1044  1566 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.335  1044  1449 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 17:45:27.335  1044  1449 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 17:45:27.335  1044  1400 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.335  1044  1449 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 17:45:27.336  1044  1449 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 17:45:27.336  1044  1449 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 17:45:27.337  1044  1449 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 17:45:27.337  1044  1449 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 17:45:27.337  1044  1449 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 17:45:27.337  1951  7242 D WfdsMonitor: Supplicant connection established
08-16 17:45:27.339   307   904 D CommandListener: Setting iface cfg
08-16 17:45:27.339   307   904 D CommandListener: Trying to bring up p2p0
08-16 17:45:27.340  1044  1400 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 17:45:27.340  1044  1400 D LGWifiP2pService: P2pEnablingState
08-16 17:45:27.340  1044  1400 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.340  7232  7232 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 17:45:27.340  1044  1400 D LGWifiP2pService: P2p socket connection successful
08-16 17:45:27.340  1044  1400 D LGWifiP2pService: P2pEnabledState
08-16 17:45:27.340  1044  1449 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 17:45:27.341  1044  1449 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 17:45:27.341  1044  1449 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 17:45:27.341  1044  1449 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 17:45:27.341  7232  7232 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 17:45:27.342  1044  1449 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 17:45:27.342  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 17:45:27.342  1044  1449 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 17:45:27.342  1044  1400 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 17:45:27.343  1044  1449 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 17:45:27.343  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 17:45:27.343  1951  1951 D WfdsService: WifiP2pState is changed : true
08-16 17:45:27.343  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 17:45:27.344  7232  7232 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:27.344  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 17:45:27.344  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:27.344  1044  7240 E WifiMonitor: handleEvent, 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:27.344  1044  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:27.344  7232  7232 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 17:45:27.344  7232  7232 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.345  1044  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:27.345  1044  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.345  1044  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.345  1044  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.345  7232  7232 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.346  1044  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:27.346  1044  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.346  1044  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.346  1044  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.347  1044  1449 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 17:45:27.347  1044  1449 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 17:45:27.348  1044  1449 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 17:45:27.348  1044  1449 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 17:45:27.348  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 17:45:27.348  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 17:45:27.348  7232  7232 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 17:45:27.348  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 17:45:27.348  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 17:45:27.348  1044  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN,
,08-16 17:45:27.348  1044  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 17:45:27.350  1044  1449 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 17:45:27.350  1044  1449 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-16 17:45:27.350  1044  1449 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 17:45:27.350  1044  1449 D WifiNative-wlan0: doBoolean: SCAN
,08-16 17:45:27.351  1044  1449 D WifiNative-wlan0: SCAN: returned false
,08-16 17:45:27.352  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=215241  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 17:45:27.352  1951  2315 D WfdsService: Connected to the supplicant for wfds
08-16 17:45:27.352  1951  2315 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 17:45:27.353  7232  7232 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 17:45:27.353  1951  2315 D WfdsService: selectPreferredScanChannel [36]
08-16 17:45:27.354  1951  2315 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 17:45:27.354  1951  2315 D WfdsService: DefaultState - WFDS_ENABLE(DISABLE)
08-16 17:45:27.354  1044  1400 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 17:45:27.355  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=215244  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 17:45:27.355  1951  7242 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:27.355  1044  1449 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:27.355  1951  7242 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:27.356  1044  1449 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:27.356  1044  1400 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,08-16 17:45:27.356  1044  1449 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:27.356  1044  1400 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 17:45:27.356  1044  1449 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:27.357  1044  1449 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:27.357  1044  1400 D WifiNative-p2p0: SET device_name G3: returned true
08-16 17:45:27.357  1044  1400 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 17:45:27.357  1044  1400 D LGWifiP2pService: before postfix = G3
08-16 17:45:27.357  1044  1400 D WifiServerServiceExt: postfix byte check : 2
08-16 17:45:27.357  1044  1400 D LGWifiP2pService: after postfix = G3
08-16 17:45:27.357  1044  1400 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 17:45:27.358  1044  1400 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 17:45:27.358  1044  1400 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 17:45:27.359  1044  1400 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 17:45:27.359  1044  1400 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 17:45:27.359  1044  1400 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 17:45:27.359  1044  1400 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 17:45:27.359  1951  1951 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 17:45:27.360  1044  1400 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 17:45:27.360  1044  1400 D WifiNative-HAL: p2pGetDeviceAddress
08-16 17:45:27.360  1951  1951 D WfdsService: isConnected: false
08-16 17:45:27.360  1044  1400 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 17:45:27.363  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:27.363  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:27.363  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.363  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.363  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 17:45:27.364  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-16 17:45:27.364  1044  1044 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 17:45:27.365  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:27.365  1044  1400 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 17:45:27.366  1044  1400 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 17:45:27.366  1044  1400 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 17:45:27.366  1044  1400 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 17:45:27.366  1044  1400 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 17:45:27.366  1044  1400 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 17:45:27.367  1044  1400 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 17:45:27.367  1044  1400 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 17:45:27.369  1951  1951 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 17:45:27.369  1951  1951 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 17:45:27.370  1951  1951 D WfdsService: Update P2p Interface State: 3
08-16 17:45:27.376  1044  1400 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 17:45:27.376  1044  1400 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 17:45:27.376  1044  1400 D LGWifiP2pService: InactiveState
08-16 17:45:27.376  1044  1400 D LGWifiP2pService: InactiveState{ when=-29ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.376  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-29ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.376  1044  1400 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-16 17:45:27.377  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 17:45:27.377  7232  7232 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:27.377  1044  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 17:45:27.377  1044  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:27.378  1044  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:27.378  1044  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:27.378  7232  7232 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 17:45:27.378  7232  7232 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.378  7232  7232 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.378  1044  1400 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1951  7242 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1951  7242 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1951  7242 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:27.379  1044  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:27.379  1044  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.379  1044  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1044  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1044  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:27.379  1044  7240 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1044  7240 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.379  1044  7240 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.379  1044  1400 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.380,  1044  1400 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.380  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.380  1951  2315 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 17:45:27.380  1044  1400 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:27.380  1044  1044 E WifiServerServiceExt: No p2p device connected
,08-16 17:45:27.449  7214  7214 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 17:45:27.482  7214  7214 I HubEmail: JNI_OnLoad()
08-16 17:45:27.482  7214  7214 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 17:45:27.482  7214  7214 I HubEmail: registerNatives()
08-16 17:45:27.482  7214  7214 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 17:45:27.482  7214  7214 I HubEmail: registerNativeMethods()
08-16 17:45:27.482  7214  7214 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-16 17:45:27.483  7214  7214 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 17:45:27.497  3504  3504 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 17:45:27.497  3504  3504 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:27.498  3504  3504 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 17:45:27.503  7214  7246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:27.544  1044  1896 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7250 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 17:45:27.548  7082  7248 W FormManager: Network not available. Please check & try again.
08-16 17:45:27.554  7082  7249 V FormManager: Network unavailable.
08-16 17:45:27.559  7082  7249 V FormManager: Network unavailable.
,08-16 17:45:27.570  1044  1629 I ActivityManager: Killing 6627:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-16 17:45:27.610  1044  2042 W libprocessgroup: failed to open /acct/uid_10061/pid_6627/cgroup.procs: No such file or directory
,08-16 17:45:27.682  7250  7250 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:27.682  7250  7250 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 17:45:27.686  7250  7250 D PhoneMonitor: Register our PhoneStateListener
,08-16 17:45:27.710  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 17:45:27.715  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 17:45:27.729  7250  7250 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 17:45:27.730  7250  7250 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 17:45:27.731  7250  7250 D TelephonyAutoProfiling: [parse] Load xml
08-16 17:45:27.733  7250  7250 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 17:45:27.733  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 17:45:27.734  7250  7250 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 17:45:27.734  7250  7250 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 17:45:27.742  7250  7250 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-16 17:45:27.790  1044  1060 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7269 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:45:27.792  1044  1060 I ActivityManager: Killing 6687:com.lge.eula/1000 (adj 15): empty #17
,08-16 17:45:27.848  1044  1968 W libprocessgroup: failed to open /acct/uid_1000/pid_6687/cgroup.procs: No such file or directory
,08-16 17:45:27.950  7232  7232 E wpa_supplicant: USIM:  scard_init function
,08-16 17:45:27.950  7232  7232 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 17:45:27.953  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 17:45:27.953  1044  7240 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 17:45:27.954  1044  1449 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 17:45:27.955  1044  1449 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 17:45:27.955  1044  1449 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 17:45:27.955  1044  1449 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 17:45:27.956  1044  1449 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 17:45:27.956  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 17:45:27.956  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-16 17:45:27.956  1044  7240 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 17:45:27.957  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 17:45:27.957  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 17:45:27.962  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=215852  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 17:45:27.966  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.966  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.966  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 17:45:27.967  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:27.967  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:27.969  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:27.975  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=215865  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 17:45:27.976  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.976  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:27.976  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 17:45:27.977  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:27.978  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-16 17:45:27.994  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:27.994  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:27.996  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 17:45:28.060  7232  7232 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 17:45:28.062  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 17:45:28.063  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 17:45:28.063  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 17:45:28.063  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 17:45:28.063  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:28.063  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:28.064  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=215954  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 17:45:28.065  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=215954  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 17:45:28.066  1044  1449 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215955
08-16 17:45:28.066  1044  1449 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215956
08-16 17:45:28.067  1044  1449 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215956
08-16 17:45:28.067  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215956
08-16 17:45:28.068  1044  1449 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=215957
08-16 17:45:28.068  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=215958  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 17:45:28.078  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:28.078  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:28.078  7232  7232 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:45:28.078  7232  7232 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 17:45:28.078  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-16 17:45:28.081  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:45:28.082  1044  7240 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:45:28.082  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 17:45:28.082  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 17:45:28.082  1044  7240 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 17:45:28.082  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:28.082  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:28.088  1044  1060 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7290 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-16 17:45:28.090  1044  1060 I ActivityManager: Killing 6704:com.lge.bnr/1000 (adj 15): empty #17
,08-16 17:45:28.194  1044  2005 W libprocessgroup: failed to open /acct/uid_1000/pid_6704/cgroup.procs: No such file or directory
,08-16 17:45:28.195  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=216084  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 17:45:28.215  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:28.216  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 17:45:28.219  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.226  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.226  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.226  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 17:45:28.231  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.231  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.231  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-16 17:45:28.232  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=216122  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 17:45:28.234  1044  1106 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:45:28.234  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:28.234  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 17:45:28.236  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=216125  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 17:45:28.238  1044  1449 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216127
08-16 17:45:28.238  1044  1449 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=216128
08-16 17:45:28.239  1044  1449 D WifiNative-wlan0: doString: [STATUS]
08-16 17:45:28.240  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:28.240  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:28.241  1044  1449 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 17:45:28.243  1044  1449 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 17:45:28.244  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:28.244  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 17:45:28.246  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.250  1044  1449 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 17:45:28.250  1044  1449 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 17:45:28.254  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.254  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.254  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 17:45:28.265  1044  1449 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 17:45:28.265  1044  1449 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:45:28.265  1044  1449 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 17:45:28.265  1044  1526 D ConnectivityService: Got NetworkAgent Messenger
08-16 17:45:28.265  1044  1526 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 17:45:28.265  1044  1526 D ConnectivityService: NetworkAgent connected
,08-16 17:45:28.268  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:28.268  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:28.268  1044  1449 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 17:45:28.268  1044  1449 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 17:45:28.270  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.293  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:28.293  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 17:45:28.295  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.296  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.296  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.297  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 17:45:28.311  1044  1449 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 17:45:28.311  1044  1449 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:45:28.311  1044  1449 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 17:45:28.312  1044  1449 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 17:45:28.312  1044  1449 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 17:45:28.321  1044  1449 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 17:45:28.324   307   904 D CommandListener: Setting iface cfg
08-16 17:45:28.346  1044  1933 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7313 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:45:28.348  1044  1933 I ActivityManager: Killing 2144:com.lge.music/u0a34 (adj 15): empty #17
,08-16 17:45:28.379   311  1406 V AudioFlinger: 2144 died, releasing its sessions
08-16 17:45:28.379   311  1406 V AudioFlinger:  pid 1862 @ 0
08-16 17:45:28.379   311  1406 V AudioFlinger:  pid 3504 @ 1
08-16 17:45:28.379   311  1406 V AudioFlinger:  pid 3504 @ 2
,08-16 17:45:28.385  1044  1400 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:45:28.385  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.385  1044  1400 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:45:28.546  1044  2042 W libprocessgroup: failed to open /acct/uid_10034/pid_2144/cgroup.procs: No such file or directory
,08-16 17:45:28.556  1044  7312 D DhcpStateMachine: StoppedState
,08-16 17:45:28.556  1044  1449 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 17:45:28.556  1044  7312 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.557  1044  7312 D DhcpStateMachine: WaitBeforeStartState
08-16 17:45:28.559  1044  1449 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216448  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:28.561  1044  1449 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216450  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:28.562  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=216452  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:28.565  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:28.565  1044  1044 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 17:45:28.565  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:28.567  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,08-16 17:45:28.568  1044  1449 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-16 17:45:28.569  1044  1449 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:28.569  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:28.570  1044  1449 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:28.571  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:28.571  1044  1449 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=216460  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:28.571  1044  1044 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 17:45:28.571  1044  1449 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=216461  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:28.572  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=216461  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:28.573  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:170185] from screen [on:0 period:-1811453955] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 17:45:28.577  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1811453951] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 17:45:28.577  1044  1449 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 17:45:28.582  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.583  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.583  1044  1526 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 17:45:28.583  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.584  1044  1449 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.584  1044  1449 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.585  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.585  1044  1449 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.586  1044  1526 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 17:45:28.586  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 17:45:28.587  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 17:45:28.587  1044  1449 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 17:45:28.588  1044  1449 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 17:45:28.588  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 17:45:28.589  1044  1449 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 17:45:28.589  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-16 17:45:28.590  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=145,0,0
08-16 17:45:28.590  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 17:45:28.591  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 17:45:28.591  1044  1449 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 17:45:28.591  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 0
,08-16 17:45:28.592  1044  1449 D WifiNative-wlan0: SET ps 0: returned true
08-16 17:45:28.592  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
,08-16 17:45:28.593  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 17:45:28.593  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 17:45:28.594  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a1c360b target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.594  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a1c360b target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.594  1044  7312 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.594  1044  7312 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 17:45:28.595  1044  1449 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 17:45:28.595  1044  1449 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 17:45:28.595  1044  1449 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 17:45:28.596   307   904 D CommandListener: Setting iface cfg
08-16 17:45:28.597   307   904 D CommandListener: Trying to bring up wlan0
08-16 17:45:28.599  1044  1449 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 17:45:28.601  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:28.601  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 17:45:28.602  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:28.602  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 17:45:28.602  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.603  7313  7313 I art     : Almond Protected OAT
08-16 17:45:28.603  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.603  1044  1449 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.604  1044  1449 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.605  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.605  1044  1449 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:28.606  1044  1526 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 17:45:28.606  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 17:45:28.607  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 17:45:28.607  1044  1400 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.607  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.608  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 17:45:28.608  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 17:45:28.609  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 17:45:28.609  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 17:45:28.609  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-16 17:45:28.610  1044  1449 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-16 17:45:28.610  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:45:28.625  1044  1449 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:45:28.626  1044  1526 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 17:45:28.626  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-16 17:45:28.627  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 17:45:28.627  1044  1449 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 17:45:28.627  1044  1526 D ConnectivityService: ignoring duplicate network state non-change
08-16 17:45:28.631  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.631  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.631  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 17:45:28.632  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:28.632  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:28.632  1044  1526 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 17:45:28.633  1044  1526 D ConnectivityService: Adding iface wlan0 to network 101
08-16 17:45:28.633  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.638  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:28.638  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.638  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 17:45:28.640  1044  1449 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 17:45:28.642  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 17:45:28.646  1951  1951 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 17:45:28.648  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.648  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.648  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 17:45:28.648  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 17:45:28.653  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:28.654  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:28.655  1044  1526 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 17:45:28.656  1044  1526 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 17:45:28.656  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.656  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:28.656  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-16 17:45:28.657  1044  1526 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 17:45:28.657   307   904 E Netd    : netlink response contains error (File exists)
08-16 17:45:28.658  1044  1526 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 17:45:28.659  1044  1526 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 17:45:28.659  1044  1526 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 17:45:28.659  1044  1526 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 17:45:28.659  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.660  1044  1526 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 17:45:28.660  1044  1526 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 17:45:28.660  1044  1526 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 17:45:28.661  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.661  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 17:45:28.661  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:28.661  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:28.661  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 17:45:28.661  1613  1613 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 17:45:28.661  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.664  1044  1526 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 17:45:28.664  1044  1526 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:28.664  1044  1526 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:28.664  1044  1526 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 17:45:28.664  1044  1526 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.664  1044  1526 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 17:45:28.664  1044  1526 D ConnectivityService: currentScore = 0, newScore = 20
08-16 17:45:28.664  1044  1526 D ConnectivityService:    accepting network in place of null
08-16 17:45:28.664  1044  1526 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.665  1044  1449 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.665   307  7336 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 17:45:28.665  1044  1449 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:28.666  1862  1862 D TelephonyNetworkFactory-1: new score 20, for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.666  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 17:45:28.666  1044  1526 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 17:45:28.666  1044  1526 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 17:45:28.666  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:45:28.667  1044  1526 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:28.668  1044  1044 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,08-16 17:45:28.668  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 17:45:28.668  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 17:45:28.668  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 17:45:28.671  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:28.671  1613  1613 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 17:45:28.671  1044  1526 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 17:45:28.672  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.672  1044  1526 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 17:45:28.673  1044  1526 D ConnectivityService: validation of new default Network = false
08-16 17:45:28.673  1044  1526 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 17:45:28.673  1044  1526 D DSQN    : enableDataServiceNotify 
08-16 17:45:28.673  1044  1526 D DSQN    : start dsqn bin
08-16 17:45:28.676  7313  7313 D WeatherApplication: removeAccount
08-16 17:45:28.677  7313  7313 D WeatherApplication: Account.length = 0
08-16 17:45:28.677  7313  7313 E WeatherApplication: OPERATOR:OPEN
08-16 17:45:28.681  1044  1526 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 17:45:28.681  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.681  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:28.681  1044  1526 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:28.667  7337  7337 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 17:45:28.667  7337  7337 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:28.684  7313  7313 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:28
08-16 17:45:28.684  1613  2080 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:45:28.687  7313  7313 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 17:45:28.688  7313  7313 D Weather.Utils: 2 : All the weather widget is gone.
08-16 17:45:28.690  7313  7313 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 17:45:28.691  1044  1399 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 17:45:28.694  7337  7337 E DSQN    : DSQN ssw
08-16 17:45:28.695  7313  7313 D WeatherAncestor: connectivity changed - connection : true
,08-16 17:45:28.696  7313  7313 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 17:45:28.704  7313  7313 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 17:45:28.704  7313  7313 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 17:45:28.705  7313  7313 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-16 17:45:28.710  1827  7339 I CheckinService: active receiver: enabled
08-16 17:45:28.718  1827  7339 I CheckinService: Preparing to send checkin request
08-16 17:45:28.718  1827  7339 I EventLogService: Accumulating logs since 1471362173720
08-16 17:45:28.719   307  7336 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 17:45:28.722  1613  1613 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 17:45:28.723  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.724  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.726  7313  7313 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 17:45:28.726  7313  7313 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:28
08-16 17:45:28.750   307  7336 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 17:45:28.767  1044  2023 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7344 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:45:28.768  1044  2023 I ActivityManager: Killing 6211:com.android.vending/u0a44 (adj 15): empty #17
,08-16 17:45:28.779   307   903 D LGDataListener: argv[0]=dsqncommand
08-16 17:45:28.779   307   903 D LGDataListener: argv[1]=wlan0
,08-16 17:45:28.779   307   903 D LGDataListener: argv[2]=1
08-16 17:45:28.779   307   903 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 17:45:28.779  1044  1104 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 17:45:28.779  1044  1104 D DSQN    : start to monitor internet connection
08-16 17:45:28.798  1044  7312 D DhcpStateMachine: DHCPV4 request on wlan0
,08-16 17:45:28.798  1044  7312 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-16 17:45:28.798  1044  7312 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 17:45:28.787  7363  7363 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:28.787  7363  7363 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:28.806  7363  7363 I dhcpcd  : version 5.5.6 starting
08-16 17:45:28.807  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:45:28 GMT], X-Android-Received-Millis=[1471362328807], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471362328779]}
08-16 17:45:28.808  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 17:45:28.808  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 17:45:28.808  1044  1526 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 17:45:28.808  1044  1526 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 17:45:28.808  7363  7363 E dhcpcd  : get_duid: m
08-16 17:45:28.808  7363  7363 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 17:45:28.808  7363  7363 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 17:45:28.808  1044  1526 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:28.808  1044  1526 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:28.808  1044  1526 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 17:45:28.808  1044  1526 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 17:45:28.809  1044  1526 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 17:45:28.809  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.809  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:28.809  1044  1526 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:28.810  1044  1526 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.810  1044  1449 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.810  1044  1449 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:28.810  1827  7339 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-16 17:45:28.810  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 17:45:28.810  1044  1968 W libprocessgroup: failed to open /acct/uid_10044/pid_6211/cgroup.procs: No such file or directory
08-16 17:45:28.810  1613  2080 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:45:28.811  1862  1862 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:28.811  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Trans,ports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-16 17:45:28.836  1613  1613 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 17:45:28.838  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:28.839  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 17:45:28.866  7363  7363 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 17:45:28.866  7363  7363 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 17:45:28.866  7363  7363 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-16 17:45:28.866  7363  7363 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 17:45:28.866  7363  7363 D dhcpcd  : wlan0: sending REQUEST (xid 0xd57aa9cc), next in 3.21 seconds
,08-16 17:45:28.906  7363  7363 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 17:45:28.909   278   387 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-16 17:45:28.909   278   387 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 17:45:28.909   278   387 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 17:45:28.910  7344  7371 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 17:45:28.911   278   387 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 17:45:28.911   278   387 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 17:45:28.911   278   387 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 17:45:28.912  7344  7371 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 17:45:28.916   278   387 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 17:45:28.916   278   387 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 17:45:28.916   278   387 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 17:45:28.917  7344  7375 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 17:45:28.919   278   387 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 17:45:28.919   278   387 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 17:45:28.919   278   387 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:45:28.920  7344  7375 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 17:45:28.924  7363  7363 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 17:45:28.925  7363  7363 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 17:45:28.925  7363  7363 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 17:45:28.925  7363  7363 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 17:45:28.925  7363  7363 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 17:45:28.926  7363  7363 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 17:45:28.926  7363  7363 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 17:45:28.926  7363  7363 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 17:45:28.954  1044  1932 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7378 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 17:45:29.017  7378  7378 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 17:45:29.017  7378  7378 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 17:45:29.049  7378  7378 I MultiDex: VM with version 2.1.0 has multidex support
08-16 17:45:29.050  7378  7378 I MultiDex: install
08-16 17:45:29.050  7378  7378 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 17:45:29.059  7378  7378 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-16 17:45:29.181  1044  1584 I art     : Explicit concurrent mark sweep GC freed 104794(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.468ms total 101.454ms
,08-16 17:45:29.200  1044  7312 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 17:45:29.201  1044  7312 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 17:45:29.201  1044  7312 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 17:45:29.201  1044  7312 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 17:45:29.201  1044  7312 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 17:45:29.201  1044  7312 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 17:45:29.201  1044  7312 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 17:45:29.201  1044  7312 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 17:45:29.202  1044  7312 D DhcpStateMachine: RunningState
08-16 17:45:29.303  7344  7344 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 17:45:29.320  1044  1060 D WifiServiceImplEx: setWifiEnabled: false pid=6813, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 17:45:29.320  1044  1060 D WifiService: setWifiEnabled: false pid=6813, uid=10118
08-16 17:45:29.320  1044  1060 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 17:45:29.321  7344  7344 I LibraryLoader: Loading: webviewchromium
,08-16 17:45:29.323  7344  7344 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7223-7226)
08-16 17:45:29.324  7344  7344 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:45:29.328  7344  7344 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26cd8a22}
08-16 17:45:29.329  7344  7344 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:45:29.329  7344  7344 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:45:29.333  1044  1449 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:29.333  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:29.334  1044  1449 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:29.334  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 17:45:29.334  1044  1449 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:29.334  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:45:29.334  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 17:45:29.335  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 17:45:29.335  1044  1449 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 17:45:29.335  1044  1449 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:45:29.335  1044  1449 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 17:45:29.336  7344  7344 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 17:45:29.336  1044  1449 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 17:45:29.336  1044  1449 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 17:45:29.337  7344  7344 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:45:29.348  7344  7344 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 17:45:29.348  1044  1449 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 17:45:29.348  7344  7344 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 17:45:29.348  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 17:45:29.349  7344  7344 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 17:45:29.349  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-16 17:45:29.349  1044  1400 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.350  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.350  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 17:45:29.350  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:45:29.353  1044  1449 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:45:29.353   311  2159 V AudioPolicyService: registerClient() client 0xb558a5a0, uid 10093
08-16 17:45:29.353  1044  7312 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.354   307   904 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:45:29.354  7344  7434 W AudioManagerAndroid: Requires BLUETOOTH permission
08-16 17:45:29.371  7344  7344 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 17:45:29.371  7344  7344 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 17:45:29.371  7344  7344 I Adreno-EGL: Build Date: 12/12/14 금
08-16 17:45:29.371  7344  7344 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 17:45:29.371  7344  7344 I Adreno-EGL: Remote Branch: 
08-16 17:45:29.371  7344  7344 I Adreno-EGL: Local Patches: 
08-16 17:45:29.371  7344  7344 I Adreno-EGL: Reconstruct Branch: 
,08-16 17:45:29.373  1044  1449 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:29.373  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:29.373  1044  1449 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:29.374  1044  1449 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:29.374  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:29.374  1044  1449 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 17:45:29.375  1044  1526 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 17:45:29.375  1044  1526 D ConnectivityService: ignoring duplicate network state non-change
08-16 17:45:29.375  1044  1526 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-16 17:45:29.377  1044  1400 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.377  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.378  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 17:45:29.378  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:29.378  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:29.378  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:45:29.378  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 17:45:29.379  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:29.379  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:29.380  1951  1951 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 17:45:29.380  1044  1400 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2f88d8e1
08-16 17:45:29.380  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:29.381  1044  1400 D LGWifiP2pService: P2pDisablingState
08-16 17:45:29.381  1044  1400 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.381  1044  1400 D LGWifiP2pService: p2p socket connection lost
08-16 17:45:29.381  1044  1400 D LGWifiP2pService: P2pDisabledState
08-16 17:45:29.381  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:29.381  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:29.381  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:45:29.381  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:45:29.381  1044  1044 D RttService: SCAN_AVAILABLE : 1
08-16 17:45:29.382  1044  1565 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.382  1044  1566 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.382  1044  1449 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:45:29.382  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 17:45:29.382  1951  1951 D WfdsService: WifiP2pState is changed : false
08-16 17:45:29.382  1044  1449 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 17:45:29.382  1951  2315 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 17:45:29.382  1951  2315 D WfdsService: Set the WFDS Monitor: false
08-16 17:45:29.383  1044  1400 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.383  1044  1400 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.383  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 17:45:29.383  7232  7232 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 17:45:29.383  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 17:45:29.383  1951  2315 D WfdsMonitor: WFDS Monitor is stopped
08-16 17:45:29.383  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:45:29.383  1951  2315 D WfdsService: STATE : WfdsDisabledState - enter
08-16 17:45:29.383  1951  7242 D CtrlSupplicant: Received on exit socket, terminate
08-16 17:45:29.384  1951  7242 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 17:45:29.384  1951  7242 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 17:45:29.384  1044  1449 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:45:29.384  1951  7242 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 17:45:29.385  1951  2315 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 17:45:29.385  1951  2319 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
,08-16 17:45:29.389  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:29.389  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:29.395  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:29.405   307   904 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:45:29.405  1044  1526 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 17:45:29.405  1044  1526 D DSQN    : disableDataServiceNotify
08-16 17:45:29.405  1044  1526 D DSQN    : stop dsqn bin
08-16 17:45:29.407  1044  1449 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 17:45:29.408  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 17:45:29.408  1044  1449 D WifiNative-p2p0: TERMINATE: returned true
08-16 17:45:29.409  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:29.409  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:29.409  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:45:29.409  1044  1526 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 17:45:29.409  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:29.409  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:29.409  1044  1526 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:29.409  1044  1526 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 17:45:29.409  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.409  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:29.409  1044  7307 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 17:45:29.410  1044  1526 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 17:45:29.410  1044  1526 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 17:45:29.410  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:45:29.410  1044  1526 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:29.410  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:45:29.410  1044  1526 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:29.410  1044  1526 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:29.410  1044  1526 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:29.410  1044  1526 D NetworkManagementService: Removing idletimer
08-16 17:45:29.410  1044  1526 W Settings: Setting airplan,e_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:29.411  1613  2080 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 17:45:29.411  1862  1862 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:29.411  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 17:45:29.411  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 17:45:29.411  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 17:45:29.411  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 17:45:29.411  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 17:45:29.412  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 17:45:29.412  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 17:45:29.412  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 17:45:29.412  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 17:45:29.412  1044  1399 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 17:45:29.412  1044  1399 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 17:45:29.412  1044  1449 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:45:29.412  1044  1449 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:45:29.412  1044  1449 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:45:29.413  1044  1449 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:29.413  1044  1449 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:29.414  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 17:45:29.414  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 17:45:29.414  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:29.414  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:29.414  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:29.414  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:29.414  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:29.414  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:29.414  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:29.414  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:29.414  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:29.414  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:29.414  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager:, Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:29.415  1044  1044 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 17:45:29.415  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:29.415  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:29.415  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:29.415  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:29.415  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:29.415  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:29.415  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:29.415  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:29.415  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:29.415  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:29.415  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:29.415  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:29.422  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:45:29.423  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:29.424  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 17:45:29.447  1613  1613 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 17:45:29.447  7446  7446 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-16 17:45:29.448  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:29.448  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:29.451  7344  7344 I NSApplication: Starting up...
,08-16 17:45:29.464  1613  1613 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 17:45:29.465  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:29.466  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:29.466  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 17:45:29.478  7232  7232 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 17:45:29.478  7232  7232 I wpa_supplicant: monitor socket send errors count : 1
08-16 17:45:29.478  7232  7232 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1951-4\x00 that cannot receive messages
,08-16 17:45:29.479  1044  7240 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 17:45:29.479  1044  7240 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 17:45:29.483  7446  7446 I dex2oat : dex2oat took 35.745ms (threads: 4)
08-16 17:45:29.491  7378  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 17:45:29.491  7378  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 17:45:29.491  7378  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-16 17:45:29.491  7378  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 17:45:29.491  7378  7397 I Adreno-EGL: Remote Branch: 
08-16 17:45:29.491  7378  7397 I Adreno-EGL: Local Patches: 
08-16 17:45:29.491  7378  7397 I Adreno-EGL: Reconstruct Branch: 
,08-16 17:45:29.495  1044  1629 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7457 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:45:29.496  1044  1629 I ActivityManager: Killing 6893:com.lge.clock/u0a10 (adj 15): empty #17
08-16 17:45:29.499  7232  7232 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:45:29.500  7232  7232 W wpa_supplicant: USIM:  scard_deinit function
08-16 17:45:29.500  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 17:45:29.500  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:45:29.500  1044  7240 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:45:29.500  1044  7240 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 17:45:29.500  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:29.500  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:29.501  1044  1449 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=217390
08-16 17:45:29.501  1044  1449 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=217390
08-16 17:45:29.501  1044  1106 D Tethering: InitialState.processMessage what=4
08-16 17:45:29.501  1044  1449 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=217391  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 17:45:29.501  1044  1449 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=217391  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 17:45:29.510   359   359 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 212us total 14.741ms
,08-16 17:45:29.519   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 9.180ms
08-16 17:45:29.529   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 9.021ms
,08-16 17:45:29.557  1044  7312 D DhcpStateMachine: StoppedState
08-16 17:45:29.557  1044  7312 D DhcpStateMachine: StoppedState{ when=-174ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:45:29.571  1044  1106 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:45:29.571  1044  1792 W libprocessgroup: failed to open /acct/uid_10010/pid_6893/cgroup.procs: No such file or directory
,08-16 17:45:29.591  1044  1449 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 17:45:29.592  1044  1449 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 17:45:29.593  1044  1449 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:29.595  1044  1449 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 17:45:29.615  7457  7457 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:45:29.630  7232  7232 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 17:45:29.631  1044  7240 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 17:45:29.631  1044  7240 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 17:45:29.631  1044  7240 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 17:45:29.632  1044  1449 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-16 17:45:29.682  1044  1526 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 17:45:29.734  1044  1449 D WifiOffDelayIfNotUsed: stopMonitoring
,08-16 17:45:29.734  1044  1449 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:45:29.734  1044  1449 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:45:29.734  1044  1449 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:45:29.734  1951  1951 D WfdsService: Supplicant Connection state is changed : false
08-16 17:45:29.735  1951  2315 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 17:45:29.735  1951  2315 D WfdsService: Set the WFDS Monitor: false
08-16 17:45:29.735  1951  2315 D WfdsMonitor: WFDS Monitor is stopped
08-16 17:45:29.736  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 17:45:29.737  1044  1479 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 17:45:29.737  1044  1479 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 17:45:29.737  2488  2488 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:29.738  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:29.738  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:29.740  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:29.742  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 17:45:29.846  7378  7397 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:29.846  7378  7397 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:29.903  7378  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 17:45:29.903  7378  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 17:45:29.903  7378  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-16 17:45:29.903  7378  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 17:45:29.903  7378  7397 I Adreno-EGL: Remote Branch: 
08-16 17:45:29.903  7378  7397 I Adreno-EGL: Local Patches: 
08-16 17:45:29.903  7378  7397 I Adreno-EGL: Reconstruct Branch: 
,08-16 17:45:29.916  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 17:45:29.919  6505  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 17:45:29.941  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:29.952  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 17:45:29.952  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:29.954  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-16 17:45:29.954  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 17:45:29.957  7378  7397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 17:45:29.957  7378  7397 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 17:45:29.957  7378  7397 I Adreno-EGL: Build Date: 12/12/14 금
08-16 17:45:29.957  7378  7397 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 17:45:29.957  7378  7397 I Adreno-EGL: Remote Branch: 
08-16 17:45:29.957  7378  7397 I Adreno-EGL: Local Patches: 
08-16 17:45:29.957  7378  7397 I Adreno-EGL: Reconstruct Branch: 
08-16 17:45:29.958  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
08-16 17:45:29.962  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2be7af4b
08-16 17:45:29.962  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 17:45:29.962  7166  7166 D AppUp4:CustFacade: isPhone : true
08-16 17:45:29.963  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-16 17:45:29.963  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 17:45:29.967  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:29.967  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 17:45:29.969  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 17:45:29.971  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:29.980  7214  7214 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 17:45:29.983  4340  7486 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 17:45:29.985  4340  7487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:29.988  4340  7487 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 17:45:30.004  7214  7489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:30.010  3504  3504 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 17:45:30.011  3504  3504 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:30.011  3504  3504 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 17:45:30.014  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 17:45:30.014  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 17:45:30.015  7082  7491 W FormManager: Network not available. Please check & try again.
08-16 17:45:30.019  7082  7492 V FormManager: Network unavailable.
,08-16 17:45:30.026  7313  7313 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:30
08-16 17:45:30.028  7082  7492 V FormManager: Network unavailable.
08-16 17:45:30.030  7313  7313 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 17:45:30.030  7313  7313 D Weather.Utils: 2 : All the weather widget is gone.
08-16 17:45:30.030  7313  7313 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 17:45:30.030  7313  7313 D WeatherAncestor: connectivity changed - connection : true
08-16 17:45:30.030  7313  7313 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38cc1a41
08-16 17:45:30.031  7313  7313 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 17:45:30.031  7313  7313 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 17:45:30.031  7313  7313 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 17:45:30.031  7313  7313 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 17:45:30.031  7313  7313 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:30
,08-16 17:45:30.046   307  7495 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 17:45:30.047  1044  1104 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 17:45:30.047  1827  7339 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-16 17:45:30.055  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 17:45:30.055  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-16 17:45:30.055  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 17:45:30.055  6989  6989 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 17:45:30.055  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 17:45:30.056  1827  7339 I CheckinService: active receiver: disabled
08-16 17:45:30.057  6989  6989 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 17:45:30.057  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 17:45:30.057  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 17:45:30.057  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 17:45:30.058  6989  6989 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 17:45:30.058  6989  6989 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 17:45:30.068  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 17:45:30.071  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 17:45:30.075  7082  7497 W FormManager: Network not available. Please check & try again.
,08-16 17:45:30.076  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.080  7082  7498 V FormManager: Network unavailable.
08-16 17:45:30.082  7082  7498 V FormManager: Network unavailable.
08-16 17:45:30.091  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:30.095  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:45:30.098  7082  7500 W FormManager: Network not available. Please check & try again.
08-16 17:45:30.099  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.099  7082  7501 V FormManager: Network unavailable.
08-16 17:45:30.103  7082  7501 V FormManager: Network unavailable.
,08-16 17:45:30.112  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 17:45:30.112  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 17:45:30.114  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:30.115  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 17:45:30.120  4340  7502 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 17:45:30.121  4340  7503 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 17:45:30.121  4340  7503 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 17:45:30.173  1044  1059 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7504 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 17:45:30.326  7504  7504 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 17:45:30.326  7504  7504 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 17:45:30.340  7504  7504 V [BNRBootReceiver]: Boot Receiver Return
,08-16 17:45:30.342  7504  7504 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 17:45:30.346  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:30.357  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.360  6729  7157 D UEI.SmartControl: Internal timer expired: 2
,08-16 17:45:30.360  6729  7157 D UEI.SmartControl: unbind internal service
08-16 17:45:30.363  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.382  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.383  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:30.385  7045  7045 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 17:45:30.392  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 17:45:30.401  6989  6989 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 17:45:30.409  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 17:45:30.427  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.435  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.447  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 17:45:30.449  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:30.452  7045  7045 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 17:45:30.458  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:30.467  6729  7154 D serial_port: close(fd = 24)
,08-16 17:45:30.471  6729  7154 I UEI.SmartControl: Serial port is closed.
08-16 17:45:30.473  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 17:45:30.479  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.491  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.492  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:30.494  7045  7045 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 17:45:30.502  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:30.515  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.526  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 17:45:30.540  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.541  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:30.542  7045  7045 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 17:45:30.552  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:30.565  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.574  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.584  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.585  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:30.585  7045  7045 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 17:45:30.591  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:30.607  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.614  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.626  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.626  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:30.627  7045  7045 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 17:45:30.632  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 17:45:30.647  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.657  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 17:45:30.669  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.669  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:30.670  7045  7045 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 17:45:30.685  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 17:45:30.709  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.723  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.738  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.738  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:30.744  7045  7045 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 17:45:30.751  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:30.761  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.769  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.778  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.778  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:30.779  7045  7045 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 17:45:30.785  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:30.790  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 17:45:30.799  1044  1506 D WifiService: New client listening to asynchronous messages
,08-16 17:45:30.800  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:30.803  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 17:45:30.809  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.817  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.818  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:30.819  7045  7045 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 17:45:30.819  7045  7045 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 17:45:30.820  7045  7045 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-16 17:45:30.825  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:30.829  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 17:45:30.831  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 17:45:30.835  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:30.842  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:30.849  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:30.850  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:30.851  7045  7045 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 17:45:30.852  7045  7045 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 17:45:30.852  7045  7045 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 17:45:30.855  1044  1792 I ActivityManager: Killing 6964:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 17:45:30.973  1044  1896 W libprocessgroup: failed to open /acct/uid_10037/pid_6964/cgroup.procs: No such file or directory
,08-16 17:45:30.981  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 17:45:31.010  2214  2214 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 17:45:31.011  2214  2214 D c       : Getting all permits...
,08-16 17:45:31.011  2214  2214 D a       : Opening database...
08-16 17:45:31.020  2214  2214 D a       : Opening database auth.proximity.permit_store...
08-16 17:45:31.021  2214  2214 D a       : Closing database...
08-16 17:45:31.038  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 17:45:31.046  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 17:45:31.046  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:45:31.046  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 17:45:31.051  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:31.061  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:31.069  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 17:45:31.069  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:31.071  7045  7045 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 17:45:31.075  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 17:45:31.081  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 17:45:31.081  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:45:31.082  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:31.092  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:31.103  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:31.114  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 17:45:31.114  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:31.118  7045  7045 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 17:45:31.122  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:31.131  7016  7016 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 17:45:31.131  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:45:31.131  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:31.143  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:31.154  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:31.165  7045  7045 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:31.165  7045  7045 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:31.169  7045  7045 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 17:45:31.187  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:31.196  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 17:45:31.197  7082  7529 W FormManager: Network not available. Please check & try again.
08-16 17:45:31.200  7082  7530 V FormManager: Network unavailable.
,08-16 17:45:31.202  7082  7530 V FormManager: Network unavailable.
08-16 17:45:31.208  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:31.227  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 17:45:31.228  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 17:45:31.230  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 17:45:31.232  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:31.241  4340  7531 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 17:45:31.244  7016  7016 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-16 17:45:31.244  7016  7016 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 17:45:31.244  7016  7016 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 17:45:31.245  4340  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 17:45:31.245  4340  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 17:45:31.254  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:45:31.265  7082  7534 W FormManager: Network not available. Please check & try again.
08-16 17:45:31.265  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 17:45:31.278  7082  7535 V FormManager: Network unavailable.
,08-16 17:45:31.283  7082  7535 V FormManager: Network unavailable.
08-16 17:45:31.284  2214  2214 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-16 17:45:31.585  1044  1449 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1811450943] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 17:45:31.587  1044  1449 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1811450941] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 17:45:31.667  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:31.680  1044  1106 D Tethering: MasterInitialState.processMessage what=3
08-16 17:45:31.693  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:31.698  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:31.702  1044  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:31.704  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 17:45:31.706  6505  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 17:45:31.720  5870  5870 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 17:45:31.737  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:31.773  1044  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:45:31.783  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 17:45:31.783  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:31.783  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 17:45:31.783  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 17:45:31.786  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 17:45:31.792  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2be7af4b
08-16 17:45:31.792  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 17:45:31.792  7166  7166 D AppUp4:CustFacade: isPhone : true
08-16 17:45:31.794  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-16 17:45:31.794  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 17:45:31.799  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:31.799  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 17:45:31.803  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:31.806  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:31.814  7214  7214 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 17:45:31.834  3504  3504 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 17:45:31.834  3504  3504 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:31.834  3504  3504 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 17:45:31.834  3504  3504 D PhoneState: setPdpRejectCasuse : false
,08-16 17:45:31.840  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 17:45:31.840  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 17:45:31.868  7313  7313 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:31
,08-16 17:45:31.871  7313  7313 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 17:45:31.871  7313  7313 D Weather.Utils: 2 : All the weather widget is gone.
08-16 17:45:31.872  4340  7552 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 17:45:31.873  7313  7313 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 17:45:31.873  7313  7313 D WeatherAncestor: connectivity changed - connection : true
08-16 17:45:31.873  7313  7313 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38cc1a41
08-16 17:45:31.875  7313  7313 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 17:45:31.875  7313  7313 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 17:45:31.875  7313  7313 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 17:45:31.875  7313  7313 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 17:45:31.875  7313  7313 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:31
08-16 17:45:31.887  4340  7557 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:31.888  7214  7553 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:31.892  4340  7557 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 17:45:31.896  7082  7558 W FormManager: Network not available. Please check & try again.
08-16 17:45:31.902  7082  7559 V FormManager: Network unavailable.
,08-16 17:45:31.914  7082  7559 V FormManager: Network unavailable.
,08-16 17:45:32.334  1044  2042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 17:45:32.335  1044  2042 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 17:45:32.360  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 17:45:32.360  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:45:32.360  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 17:45:32.361  1044  1106 D BluetoothManagerService: Message: 1
08-16 17:45:32.361  1044  1106 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 17:45:32.388  1044  1106 D BluetoothManagerService: Message: 20
08-16 17:45:32.388  1044  1106 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cfd61a8:true
,08-16 17:45:32.393  7117  7117 D BluetoothAdapterState: make
08-16 17:45:32.398  7117  7117 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 17:45:32.398  7117  7117 I bluedroid-qcom: init
08-16 17:45:32.400  7117  7575 I BluetoothAdapterState: Entering OffState
08-16 17:45:32.400  7117  7117 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 17:45:32.400  7117  7117 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 17:45:32.400  7117  7117 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:45:32.401  7117  7117 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 17:45:32.401  7117  7117 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 17:45:32.404  7117  7117 I bluedroid-qcom: get_profile_interface socket
08-16 17:45:32.404  7117  7117 I bluedroid-qcom: get_profile_interface map_client
,08-16 17:45:32.408  7117  7579 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 17:45:32.410  7117  7579 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 17:45:32.397  7578  7578 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:32.397  7578  7578 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:32.418  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:32.421  1044  1106 D Tethering: MasterInitialState.processMessage what=3
08-16 17:45:32.422  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.422  1044  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.427  7578  7578 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 17:45:32.427  7578  7578 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 17:45:32.427  7578  7578 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 17:45:32.436  7578  7578 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 17:45:32.440  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:32.445  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:32.457  1044  1106 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:45:32.468  7578  7578 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 17:45:32.468  7578  7578 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 17:45:32.470  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:32.473  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:32.477  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 17:45:32.477  1044  1106 D BluetoothManagerService: Message: 40
08-16 17:45:32.477  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 17:45:32.478  7117  7132 I bluedroid-qcom: config_hci_snoop_log
08-16 17:45:32.479  1044  1106 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 17:45:32.479  1044  1106 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 17:45:32.483  7117  7579 D BluetoothAdapterProperties: Name is: G3
,08-16 17:45:32.488  7117  7575 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 17:45:32.488  7117  7575 D BluetoothAdapterProperties: Setting state to 11
08-16 17:45:32.488  7117  7575 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:45:32.490  7117  7575 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 17:45:32.493  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 17:45:32.493  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 17:45:32.494  1044  1106 D BluetoothManagerService: Message: 60
08-16 17:45:32.494  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 17:45:32.494  1044  1106 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 17:45:32.495  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:45:32.500  1613  1613 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 17:45:32.503  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:32.505  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:32.508  6989  6989 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 17:45:32.513  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 17:45:32.515  6505  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 17:45:32.518  7117  7575 D BluetoothBondStateMachine: make
08-16 17:45:32.525  7117  7575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.525  7117  7575 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 17:45:32.525  7117  7575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.525  7117  7575 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 17:45:32.526  7117  7575 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-16 17:45:32.529  7117  7580 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 17:45:32.538  7117  7575 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:32.556  7117  7117 D HeadsetService: Received start request. Starting profile...
08-16 17:45:32.557  7117  7117 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 17:45:32.557  7117  7117 D LGBluetoothHfpAdapter: Version 1.6
,08-16 17:45:32.571  5870  5870 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 17:45:32.572  7117  7117 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 17:45:32.575  7117  7117 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 17:45:32.576  7117  7117 D HeadsetStateMachine: make
08-16 17:45:32.584  5870  5870 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 17:45:32.585  1044  1101 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.586  1044  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:32.586  1044  1101 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:45:32.601  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:32.617  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 17:45:32.617  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:32.617  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 17:45:32.617  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 17:45:32.624  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
08-16 17:45:32.625  7117  7117 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:32.626  7117  7117 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 17:45:32.630  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2be7af4b
08-16 17:45:32.631  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 17:45:32.631  7166  7166 D AppUp4:CustFacade: isPhone : true
08-16 17:45:32.631  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-16 17:45:32.631  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 17:45:32.632  7117  7117 D HeadsetStateMachine: max_hf_connections = 1
08-16 17:45:32.633  7117  7117 I bluedroid-qcom: get_profile_interface handsfree
08-16 17:45:32.633  7117  7575 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:32.635  7117  7117 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 17:45:32.636   311   311 V AudioPolicyService: registerClient() client 0xb0410520, uid 1002
08-16 17:45:32.636   311  1406 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 17:45:32.636   311  1406 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 17:45:32.636   311  1406 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 17:45:32.636  7117  7117 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-16 17:45:32.637   311  2159 V AudioFlinger: registerClient() client 0xb101dd48, pid 7117
08-16 17:45:32.637   311  1402 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:32.637   311  1402 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:32.638   311  1401 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:32.638   311  1401 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:32.638  1044  1987 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:32.638  1044  1987 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:32.638  1044  1987 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:32.639  1044  1987 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:32.639  7117  7133 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:32.639  7117  7133 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 17:45:32.639  7117  7117 V ToneGenerator: Create Track: 0xb4928080
08-16 17:45:32.639  7117  7117 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 17:45:32.639  7117  7117 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 17:45:32.640   311  1407 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 17:45:32.640   311  1407 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 17:45:32.640   311  1407 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 17:45:32.640   311  1407 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 17:45:32.640  7117  7117 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 17:45:32.640  7117  7133 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:32.640  1613  1633 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:32.640  7117  7133 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,08-16 17:45:32.640  1613  1633 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:32.640  1613  1633 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:32.640  1613  1633 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:32.641  1862  2713 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:32.641  1862  2713 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:32.641  1862  2713 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:32.641  1862  2713 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:32.641   311  1406 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 17:45:32.641  3504  3519 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:32.641  3504  3519 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:32.641   311  2160 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 17:45:32.641   311  2160 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 17:45:32.641   311  2160 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 17:45:32.641   311  2160 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 17:45:32.643  3504  3519 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:32.643  3504  3519 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:32.644  7117  7117 V AudioSystem: getLatency() output 2, latency 50
08-16 17:45:32.644  7117  7117 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 17:45:32.644  7117  7117 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 17:45:32.644   311  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 17:45:32.644   311  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 17:45:32.644   311  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 17:45:32.644   311  2159 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 17:45:32.644   311  2159 V AudioFlinger: createTrack() lSessionId: 22
08-16 17:45:32.644  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.644  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 17:45:32.645  7117  7117 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 17:45:32.646   311  2159 V AudioFlinger: acquiring 22 from 7117, for 7117
08-16 17:45:32.646   311  2159 V AudioFlinger:  added new entry for 22
08-16 17:45:32.646  7117  7117 V ToneGenerator: ToneGenerator INIT OK, time: 220549
08-16 17:45:32.646  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.648  7117  7589 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 17:45:32.648  7117  7589 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 17:45:32.648  7117  7589 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 17:45:32.648  7117  7589 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 17:45:32.649  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:32.650  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.650   311  1407 V AudioFlinger: setParameters(): i,o 0, keyvalue bt_samplerate=8000, calling pid 7117
08-16 17:45:32.650  7117  7117 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 17:45:32.651   311  1407 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 17:45:32.651   311  1407 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 17:45:32.651   311  1407 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 17:45:32.651   311  1407 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 17:45:32.651   311  1407 V voice   : voice_set_parameters: exit with code(0)
08-16 17:45:32.651   311  1407 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 17:45:32.651   311  1407 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 17:45:32.651   311  1407 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 17:45:32.651   311  1407 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 17:45:32.651   311  1407 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 17:45:32.651   311  1407 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 17:45:32.652  7117  7589 V ToneGenerator: ToneGenerator destructor
08-16 17:45:32.652  7117  7589 V ToneGenerator: stopTone
08-16 17:45:32.652  7117  7589 V ToneGenerator: Delete Track: 0xb4928080
08-16 17:45:32.652  7117  7589 V AudioTrack: ~AudioTrack, releasing session id from 7117 on behalf of 7117
08-16 17:45:32.653   311  2160 V AudioFlinger: releasing 22 from 7117 for 7117
08-16 17:45:32.653   311  2160 V AudioFlinger:  decremented refcount to 0
08-16 17:45:32.653   311  2160 V AudioFlinger: purging stale effects
08-16 17:45:32.654  1044  1897 W Process : Unable to open /proc/7598/status
08-16 17:45:32.655   311  2160 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 17:45:32.655   311  2160 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 17:45:32.655   311  2160 V AudioFlinger: PlaybackThread::Track destructor
08-16 17:45:32.655   311  1228 V AudioPolicyService: AudioCommandThread() waking up
08-16 17:45:32.655   311  2160 V AudioFlinger: removeClient_l() pid 7117, calling pid 311
08-16 17:45:32.655   311  1228 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 17:45:32.655   311  1228 V AudioPolicyManager: releaseOutput() 2
08-16 17:45:32.655   311  1228 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 17:45:32.656  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:32.656  7117  7117 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:32.657  7117  7117 V BluetoothPbapReceiver: ***********state = 11
08-16 17:45:32.658  7117  7117 D HeadsetStateMachine: Proxy object connected
08-16 17:45:32.659  7117  7117 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 17:45:32.659  7117  7117 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 17:45:32.659  7117  7575 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:32.662  7117  7117 D A2dpService: Received start request. Starting profile...
08-16 17:45:32.663  7117  7117 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 17:45:32.663  4340  7600 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 17:45:32.664  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:45:32.664  7117  7117 V Avrcp   : make
08-16 17:45:32.665  7117  7117 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 17:45:32.665  7117  7117 I bluedroid-qcom: get_profile_interface avrcp
08-16 17:45:32.668  4340  7601 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.668  4340  7601 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 17:45:32.668  7117  7575 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:32.674  7117  7117 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 17:45:32.675  7117  7575 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 17:45:32.678  7117  7117 E AudioManager: No RCC entry present to update
08-16 17:45:32.678  7117  7117 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 17:45:32.683  7117  7117 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 17:45:32.684  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 17:45:32.684  7117  7117 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 17:45:32.726  1044  1969 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7604 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 17:45:32.741  7117  7575 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 17:45:32.743  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 17:45:32.748  7214  7214 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 17:45:32.756  7117  7575 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 17:45:32.831  7117  7575 V LGMDMManager: Create singleton instance
,08-16 17:45:32.833  3504  3504 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 17:45:32.833  3504  3504 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.833  3504  3504 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 17:45:32.838  7117  7575 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 17:45:32.838  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 17:45:32.839  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 17:45:32.852  7082  7624 W FormManager: Network not available. Please check & try again.
,08-16 17:45:32.855  7214  7626 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:32.855  7313  7313 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:32
08-16 17:45:32.860  7082  7625 V FormManager: Network unavailable.
08-16 17:45:32.862  1044  2005 V SIM_STK : Menu title from STK is T-Mobile
08-16 17:45:32.862  1044  2005 V SIM_STK : Menu title from STK is T-Mobile
08-16 17:45:32.863  7313  7313 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 17:45:32.863  7313  7313 D Weather.Utils: 2 : All the weather widget is gone.
08-16 17:45:32.863  7082  7625 V FormManager: Network unavailable.
08-16 17:45:32.867  7313  7313 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-16 17:45:32.867  7313  7313 D WeatherAncestor: connectivity changed - connection : true
08-16 17:45:32.869  7313  7313 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38cc1a41
08-16 17:45:32.870  7313  7313 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 17:45:32.870  7313  7313 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 17:45:32.870  7313  7313 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 17:45:32.870  7313  7313 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 17:45:32.870  7313  7313 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:32
08-16 17:45:32.892  7604  7604 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 17:45:32.893  7604  7604 W LG Account v2.2: No ProfileInfo entries
,08-16 17:45:32.894  7604  7604 I LG Account v2.2: isEnabled: false
08-16 17:45:32.894  6505  6505 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Country: EU
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Operator: OPEN
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Ranking support: false
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Comfort support: false
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Accessory: true
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Health device: true
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Extra Pedometer: false
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Blood glucose device: false
08-16 17:45:32.895  7604  7604 I Feature : [Lifetracker]Device Number: 3
08-16 17:45:32.896  6505  7015 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 17:45:32.914  1044  1792 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 17:45:32.916  6989  6989 D BluetoothPermissionRequest: onReceive
08-16 17:45:32.919  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 17:45:32.919  2214  2214 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.921  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 17:45:32.922  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 17:45:32.922  7117  7117 I BluetoothA2dpServiceJni: classInitNative
08-16 17:45:32.923  7117  7117 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:45:32.923  7117  7117 D A2dpStateMachine: make
08-16 17:45:32.924  7117  7117 I bluedroid-qcom: get_profile_interface a2dp
08-16 17:45:32.924  7117  7630 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 17:45:32.924  6989  6989 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 17:45:32.926  7117  7117 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:45:32.926  7117  7117 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 17:45:32.927  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.928  7117  7629 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:45:32.930  7117  7117 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:32.931  7117  7589 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 17:45:32.931  7117  7589 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:45:32.931  7117  7117 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 17:45:32.931  7117  7589 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 17:45:32.933  7117  7117 D HidService: Received start request. Starting profile...
08-16 17:45:32.933  7117  7117 I bluedroid-qcom: get_profile_interface hidhost
08-16 17:45:32.933  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
,08-16 17:45:32.933  7117  7117 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 17:45:32.934  7117  7117 D HealthService: Received start request. Starting profile...
08-16 17:45:32.935  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 17:45:32.935  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.935  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 17:45:32.935  7166  7166 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 17:45:32.936  7117  7117 I bluedroid-qcom: get_profile_interface health
08-16 17:45:32.936  7117  7117 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 17:45:32.936  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
,08-16 17:45:32.936  7117  7117 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 17:45:32.936  7166  7166 I AppUp4:CustModeStarterReceiver: onReceive
08-16 17:45:32.938  7117  7117 D PanService: Received start request. Starting profile...
08-16 17:45:32.938  7117  7117 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:45:32.938  7117  7117 I bluedroid-qcom: get_profile_interface pan
08-16 17:45:32.940  7166  7166 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2be7af4b
08-16 17:45:32.940  7166  7166 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 17:45:32.940  7166  7166 D AppUp4:CustFacade: isPhone : true
08-16 17:45:32.940  7166  7166 D AppUp4:CustModeStarterReceiver: begin check event
08-16 17:45:32.940  7166  7166 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-16 17:45:32.943  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.943  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 17:45:32.943  7117  7117 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 17:45:32.943  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.944  7117  7117 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 17:45:32.945  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:32.946  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:32.947  7117  7117 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:45:32.948  7117  7117 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:45:32.948  7117  7117 D BtGatt.GattService: start()
08-16 17:45:32.948  7117  7117 I bluedroid-qcom: get_profile_interface gatt
08-16 17:45:32.948  7117  7117 D BtGatt.AdvertiseManager: advertise manager created
08-16 17:45:32.952  4340  7636 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 17:45:32.954  7214  7214 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 17:45:32.956  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.956  4340  7637 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:32.956  4340  7637 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 17:45:32.956  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.957  7117  7117 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 17:45:32.957  7117  7117 V BluetoothMapService: BluetoothMapBinder()
08-16 17:45:32.958  7117  7117 D BluetoothMapService: Received start request. Starting profile...
08-16 17:45:32.958  7117  7117 D BluetoothMapService: start()
08-16 17:45:32.963  7117  7117 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 17:45:32.963  7117  7117 D BluetoothMapEmailAppObserver: createReceiver()
08-16 17:45:32.964  7117  7117 D BluetoothMapEmailAppObserver: initObservers()
08-16 17:45:32.964  7117  7117 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-16 17:45:32.977  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:32.980  3504  3504 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 17:45:32.980  3504  3504 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:45:32.980  3504  3504 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 17:45:32.980  7082  7640 W FormManager: Network not available. Please check & try again.
08-16 17:45:32.980  7117  7117 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:32.983  7250  7250 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 17:45:32.983  7250  7250 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 17:45:32.984  7117  7117 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:32.988  7117  7117 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:32.988  7117  7117 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 17:45:32.990  7214  7643 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:32.991  7082  7641 V FormManager: Network unavailable.
08-16 17:45:32.991  7117  7117 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:32.997  7117  7117 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 17:45:32.997  7117  7117 V BluetoothMapService: Handler(): got msg=1
08-16 17:45:32.998  7117  7575 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 17:45:32.998  7117  7575 I bluedroid-qcom: enable
08-16 17:45:32.998  7313  7313 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:32
08-16 17:45:32.998  7117  7575 I bt_hci_bdroid: init
,08-16 17:45:32.999  7117  7575 I bt_vendor: bt-vendor : init
08-16 17:45:32.999  7117  7575 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 17:45:32.999  7117  7575 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 17:45:32.999  7117  7575 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 17:45:32.999  7117  7575 D bt_userial_mct: userial_init
08-16 17:45:33.000  7117  7644 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 17:45:33.000  7117  7575 D bt_hci_bdroid: set_power 1
08-16 17:45:33.000  7117  7575 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 17:45:33.000  7117  7575 I bt_vendor: Starting hciattach daemon
08-16 17:45:33.000  7117  7575 I bt_vendor: try to set true
08-16 17:45:33.000  7117  7117 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:33.000  7117  7644 I bt-btu  : btu_task pending for preload complete event
08-16 17:45:33.001  7082  7641 V FormManager: Network unavailable.
08-16 17:45:33.001  7313  7313 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 17:45:33.002  7313  7313 D Weather.Utils: 2 : All the weather widget is gone.
08-16 17:45:33.002  7313  7313 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 17:45:33.002  7313  7313 D WeatherAncestor: connectivity changed - connection : true
08-16 17:45:33.002  7313  7313 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@38cc1a41
08-16 17:45:33.002  7117  7117 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 17:45:33.002  7117  7117 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:45:33.002  7117  7117 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:45:33.002  7117  7117 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:33.002  7117  7117 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 17:45:32.987  7647  7647 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:32.987  7647  7647 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 17:45:33.010  7313  7313 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 17:45:33.010  7313  7313 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 17:45:33.010  7313  7313 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 17:45:33.010  7313  7313 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 17:45:33.010  7313  7313 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:45:33
08-16 17:45:33.019  7648  7648 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 17:45:33.093  7654  7654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 17:45:33.120  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 17:45:33.172  7657  7657 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 17:45:33.194  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 17:45:33.215  7659  7659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 17:45:33.231  7660  7660 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 17:45:33.274  7662  7662 I libmdmdetect: ESOC framework not supported
08-16 17:45:33.275  7662  7662 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 17:45:33.283  7662  7662 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-16 17:45:33.283  7662  7662 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 17:45:33.283  7662  7662 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 17:45:33.283  7662  7662 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 17:45:33.283  7662  7662 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 17:45:33.283  7662  7662 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 17:45:33.283  7662  7662 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 17:45:33.324  7662  7666 E QC-QMI  : qmi_client [7662] 14: failed to locate client data
08-16 17:45:33.326   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 17:45:33.327   475   475 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 17:45:33.358  7670  7670 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 17:45:33.381  7671  7671 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 17:45:33.405  7117  7575 I bt_vendor: bluetooth satus is on
08-16 17:45:33.405  7117  7575 D bt_hci_bdroid: preload
08-16 17:45:33.406  7117  7646 D bt_userial_mct: userial_open(port:0)
08-16 17:45:33.406  7117  7646 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 17:45:33.410  7117  7646 I bt_vendor: Done intiailizing UART
,08-16 17:45:33.411  7117  7646 I bt_vendor: Done intiailizing UART
08-16 17:45:33.411  7117  7646 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 17:45:33.411  7117  7646 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 17:45:33.411  7117  7673 D bt_userial_mct: Entering userial_read_thread()
08-16 17:45:33.412  7117  7644 I bt-btu  : btu_task received preload complete event
08-16 17:45:33.412  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 17:45:33.412  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 17:45:33.415  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:45:33.418  7117  7644 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 17:45:33.522  7117  7644 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-16 17:45:33.522  7117  7644 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa023b061 ,
08-16 17:45:33.522  7117  7644 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa023b061 
,08-16 17:45:33.558  7117  7579 E bt-btif : Calling BTA_HhEnable
08-16 17:45:33.558  7117  7579 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040,
,08-16 17:45:33.566  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 17:45:33.566  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 17:45:33.566  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 17:45:33.566  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 17:45:33.566  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 17:45:33.567  7117  7579 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 17:45:33.568  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 17:45:33.569  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 17:45:33.569  7117  7579 D BluetoothAdapterProperties: Name is: G3
08-16 17:45:33.570  7117  7579 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:45:33.571  7117  7579 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:45:33.571  7117  7579 D bt_hci_bdroid: postload
08-16 17:45:33.571  7117  7646 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 17:45:33.575  7117  7646 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 17:45:33.576  7117  7644 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 17:45:33.576  7117  7579 D bte_conf: Device ID record 1 : primary
08-16 17:45:33.576  7117  7579 D bte_conf:   vendorId            = 00c4
08-16 17:45:33.576  7117  7579 D bte_conf:   vendorIdSource      = 0001
08-16 17:45:33.576  7117  7579 D bte_conf:   product             = 13a1
08-16 17:45:33.577  7117  7579 D bte_conf:   version             = 1000
08-16 17:45:33.577  7117  7579 D bte_conf:   clientExecutableURL = 
08-16 17:45:33.577  7117  7579 D bte_conf:   serviceDescription  = 
08-16 17:45:33.577  7117  7579 D bte_conf:   documentationURL    = 
08-16 17:45:33.577  7117  7579 D bte_conf: bte_load_did_conf no section named DID2.
08-16 17:45:33.578  7117  7646 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 17:45:33.581  7117  7575 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 17:45:33.581  7117  7575 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:45:33.581  7117  7575 D BluetoothAdapterProperties: State =  11
08-16 17:45:33.581  7117  7575 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 17:45:33.581  7117  7575 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 17:45:33.581  7117  7575 D BluetoothAdapterProperties: Setting state to 12
08-16 17:45:33.581  7117  7575 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 17:45:33.582  7117  7579 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 17:45:33.582  7117  7579 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:45:33.567  7678  7678 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 17:45:33.577  7678  7678 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:33.597  7117  7575 I BluetoothAdapterState: Entering On State
08-16 17:45:33.598  7117  7644 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:33.598  7117  7644 W bt-smp  : Plain text(LSB ~ MSB) = 95 e9 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:33.598  7117  7644 W bt-smp  : Encrypted text(LSB ~ MSB) = 58 7f 42 1f f3 b9 6e 7f aa 6f 1c 8c fa e9 c9 25 
,08-16 17:45:33.600  7117  7646 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 17:45:33.601  7117  7644 W bt-btm  : Stopping oneshot timer
08-16 17:45:33.601  7117  7673 E bt_mct  : hci lib postload completed
08-16 17:45:33.601  1044  1106 D BluetoothManagerService: Message: 60
08-16 17:45:33.601  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 17:45:33.601  1044  1106 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 17:45:33.601  1044  1106 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:45:33.619  7117  7575 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 17:45:33.628  7117  7575 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 17:45:33.628  7117  7575 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 17:45:33.632  7117  7575 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 17:45:33.636  7117  7579 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:45:33.636  7117  7579 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 17:45:33.640  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:33.640  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:33.640  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:33.640  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:33.640  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:33.640  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:33.640  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:33.640  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:33.646  1862  1878 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:45:33.648  7117  7575 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 17:45:33.654  7117  7644 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:33.654  7117  7644 W bt-smp  : Plain text(LSB ~ MSB) = b4 0c 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:33.654  7117  7644 W bt-smp  : Encrypted text(LSB ~ MSB) = 87 9c 20 c9 d4 00 87 49 22 ac 60 b3 c6 1a 74 62 
08-16 17:45:33.655  7117  7644 W bt-btm  : Stopping oneshot timer
08-16 17:45:33.656  1044  1044 D BluetoothHeadset: Proxy object connected
08-16 17:45:33.657  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:33.668  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:33.668  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:33.668  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:33.668  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:33.668  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:33.668  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:33.668  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:33.668  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:45:33.671  7117  7644 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:33.671  7117  7644 W bt-smp  : Plain text(LSB ~ MSB) = 5d b6 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:33.671  7117  7644 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 8a 77 81 34 fa 75 1b 9a 4a a2 63 c7 ac fb 22 
08-16 17:45:33.671  7117  7644 W bt-btm  : Stopping oneshot timer
08-16 17:45:33.677  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:33.693  7117  7644 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:33.693  7117  7644 W bt-smp  : Plain text(LSB ~ MSB) = 65 09 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:33.693  7117  7644 W bt-smp  : Encrypted text(LSB ~ MSB) = 78 30 3c 1f 40 d1 b9 fe 49 c7 4a 1f 72 dd 8a 9e 
,08-16 17:45:33.695  7117  7644 W bt-btm  : Stopping oneshot timer
08-16 17:45:33.697  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 17:45:33.721  7117  7644 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:33.721  7117  7644 W bt-smp  : Plain text(LSB ~ MSB) = e4 ee 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:33.721  7117  7644 W bt-smp  : Encrypted text(LSB ~ MSB) = 65 f1 05 6b ed e9 37 c1 7e ba f8 3e 3b d4 eb 88 
08-16 17:45:33.721  7117  7644 W bt-btm  : Stopping oneshot timer
,08-16 17:45:33.725  6989  7011 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:45:33.733  6989  7102 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:45:33.733  6989  7102 D BluetoothPan: onBluetoothStateChange call bindService
08-16 17:45:33.735  7693  7693 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 17:45:33.739  1044  1106 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:45:33.740  1862  2713 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:45:33.742  6989  6989 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:45:33.742  6989  6989 D PanProfile: Bluetooth service connected
08-16 17:45:33.742  1862  1862 D BluetoothHeadset: Proxy object connected
,08-16 17:45:33.743  1044  1044 D BluetoothA2dp: Proxy object connected
08-16 17:45:33.743  6989  7011 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:45:33.747  6989  7102 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:45:33.758  1862  2466 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:45:33.757  6989  6989 D BluetoothInputDevice: Proxy object connected
08-16 17:45:33.761  6989  6989 D HidProfile: Bluetooth service connected
08-16 17:45:33.762  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 17:45:33.764  1044  1106 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 17:45:33.765  1044  1106 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 17:45:33.765  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 17:45:33.765  1044  1106 D BluetoothManagerService: Message: 40
08-16 17:45:33.765  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 17:45:33.765  6989  6989 D BluetoothMap: Proxy object connected
08-16 17:45:33.765  6989  6989 D MapProfile: Bluetooth service connected
08-16 17:45:33.765  6989  6989 D BluetoothMap: getConnectedDevices()
08-16 17:45:33.767  7117  7681 V BluetoothMapService: getConnectedDevices()
,08-16 17:45:33.786  1044  1102 W ProcessCpuTracker: Skipping unknown process pid 7678
,08-16 17:45:33.787  1044  1102 W ProcessCpuTracker: Skipping unknown process pid 7682
,08-16 17:45:33.788  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:45:33.789  1951  2134 D LGBluetoothAPIService: Message: 1
08-16 17:45:33.789  1951  2134 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 17:45:33.790  1613  1613 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 17:45:33.794  6813  6813 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 17:45:33.800  6989  6989 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 17:45:33.802  1044  1106 D BluetoothManagerService: Message: 30
08-16 17:45:33.803  7117  7117 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:45:33.803  7117  7117 D BluetoothMapService: STATE_ON
08-16 17:45:33.805  7117  7117 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 17:45:33.805  7117  7117 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 17:45:33.805  1951  2134 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 17:45:33.805  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:33.806  1951  1951 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 17:45:33.807  1951  2134 D LGBluetoothAPIService: Message: 100
08-16 17:45:33.807  1951  2134 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 17:45:33.807  6989  6989 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 17:45:33.807  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:33.810  1044  1106 D BluetoothManagerService: Message: 30
08-16 17:45:33.814  6989  6989 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-16 17:45:33.816  6989  6989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 17:45:33.821  6989  6989 D BluetoothA2dp: Proxy object connected
08-16 17:45:33.821  6989  6989 D A2dpProfile: Bluetooth service connected
08-16 17:45:33.823  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:33.823  7117  7117 V BluetoothPbapService: Pbap Service onCreate
08-16 17:45:33.823  6989  6989 D BluetoothHeadset: Proxy object connected
08-16 17:45:33.823  7117  7117 V BluetoothPbapService: Starting PBAP service
08-16 17:45:33.824  7117  7117 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 17:45:33.824  7117  7117 V BluetoothMapService: Handler(): got msg=1
08-16 17:45:33.825  7117  7117 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 17:45:33.825  7117  7117 V BluetoothPbapService: Pbap Service onBind
08-16 17:45:33.826  7117  7702 D BluetoothMapMasInstance: MAS initSocket()
08-16 17:45:33.826  7117  7117 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:33.826  7117  7117 V BluetoothPbapService: state: 12
08-16 17:45:33.827  7117  7117 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 17:45:33.827  7117  7117 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:33.827  7117  7117 V BluetoothPbapReceiver: ***********state = 12
,08-16 17:45:33.828  7117  7702 D BluetoothMapMasInstance:   masId = 00
08-16 17:45:33.828  7117  7702 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 17:45:33.828  7117  7702 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 17:45:33.828  7117  7702 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 17:45:33.828  7117  7117 V BluetoothPbapService: Handler(): got msg=1
08-16 17:45:33.829  7117  7117 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-16 17:45:33.830  6989  6989 D HeadsetProfile: Bluetooth service connected
08-16 17:45:33.830  7117  7703 V BluetoothPbapService: Pbap Service initSocket
08-16 17:45:33.830  1044  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:33.831  1044  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:33.831  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:45:33.832  2214  2214 D c       : Getting all permits...
08-16 17:45:33.832  2214  2214 D a       : Opening database...
08-16 17:45:33.832  7117  7702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:33.832  7117  7703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:33.834  7117  7703 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 17:45:33.834  7117  7702 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 17:45:33.834  7117  7703 V BluetoothPbapService: Succeed to create listening socket 
08-16 17:45:33.834  7117  7702 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 17:45:33.834  7117  7703 V BluetoothPbapService: Accepting socket connection...
08-16 17:45:33.834  7117  7702 D BluetoothMapMasInstance: Accepting socket connection...
08-16 17:45:33.834  7117  7579 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:45:33.835  7117  7579 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 17:45:33.836  2214  2214 D a       : Opening database auth.proximity.permit_store...
08-16 17:45:33.836  2214  2214 D a       : Closing database...
08-16 17:45:33.839  7117  7579 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:45:33.839  7117  7579 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 17:45:33.839  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:33.840  6989  6989 D DockEventReceiver: finishStartingService: stopping service
08-16 17:45:33.841  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:33.843  6989  6989 D BluetoothPbap: Proxy object connected
,08-16 17:45:33.844  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:33.845  6989  6989 D PbapServerProfile: Bluetooth service connected
08-16 17:45:33.845  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:33.859  6989  6989 D BluetoothPermissionRequest: onReceive
,08-16 17:45:33.862  6989  6989 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 17:45:33.863  6989  6989 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 17:45:33.866  7117  7117 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 17:45:33.867  7117  7117 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 17:45:33.871  7117  7117 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 17:45:33.888  7117  7117 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 17:45:33.888  7117  7117 V BtOppService: onCreate
,08-16 17:45:33.892  7117  7117 V BluetoothOppNotification: send message
08-16 17:45:33.895  7117  7117 V BtOppService: Starting RfcommListener
08-16 17:45:33.899  7117  7117 D BluetoothOppPreference: Dumping Names:  
08-16 17:45:33.899  7117  7117 D BluetoothOppPreference: {}
08-16 17:45:33.899  7117  7117 D BluetoothOppPreference: Dumping Channels:  
08-16 17:45:33.899  7117  7117 D BluetoothOppPreference: {}
08-16 17:45:33.902  7117  7117 V BtOppService: onStartCommand
,08-16 17:45:33.903  7117  7711 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 17:45:33.906  7117  7708 V BtOppService: Deleted complete outbound shares, number =  0
08-16 17:45:33.907  7117  7711 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 17:45:33.907  7117  7117 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:33.907  7117  7117 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 17:45:33.908  7117  7708 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 17:45:33.908  7117  7708 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 17:45:33.911  7117  7708 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8a4c182 on behalf of 
08-16 17:45:33.912  7117  7117 V BluetoothOppNotification: new notify threadi!
08-16 17:45:33.913  7117  7117 V BluetoothOppNotification: send delay message
08-16 17:45:33.913  7117  7711 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@da83093 on behalf of 
,08-16 17:45:33.913  7117  7117 V BtOppService: start RfcommListener
08-16 17:45:33.914  7117  7711 V BluetoothOppNotification: update too frequent, put in queue
08-16 17:45:33.915  7117  7713 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 17:45:33.915  7117  7711 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 17:45:33.915  7117  7711 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 17:45:33.916  7344  7373 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-16 17:45:33.916  7117  7711 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@341ba8d0 on behalf of 
08-16 17:45:33.917  7117  7713 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e1670c9 on behalf of 
08-16 17:45:33.917  7117  7713 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 17:45:33.918  7117  7711 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 17:45:33.918  7117  7713 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 17:45:33.920  7117  7713 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a6173ce on behalf of 
,08-16 17:45:33.920  7117  7117 V BtOppService: RfcommListener started
,08-16 17:45:33.920  7117  7117 V BtOppService: ContentObserver received notification
,08-16 17:45:33.921  7117  7715 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 17:45:33.921  7117  7117 V BtOppService: ContentObserver received notification
08-16 17:45:33.922  1044  1932 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:33.924  7117  7716 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 17:45:33.924  7117  7716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 17:45:33.924  7117  7713 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 17:45:33.926  7117  7713 V BluetoothOppNotification: outbound notification was removed.
08-16 17:45:33.926  7117  7713 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 17:45:33.926  7117  7716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c1b42ef on behalf of 
08-16 17:45:33.927  7117  7716 V BluetoothOppNotification: update too frequent, put in queue
08-16 17:45:33.928  7117  7715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:33.934  7117  7715 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 17:45:33.935  7117  7715 V BtOppRfcommListener: Started RFCOMM listener....
08-16 17:45:33.935  7117  7715 I BtOppRfcommListener: Accept thread started.
08-16 17:45:33.935  7117  7715 V BtOppRfcommListener: Accepting connection...
,08-16 17:45:33.946  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:33.947  7117  7117 V BluetoothFtpService: Ftp Service onCreate
08-16 17:45:33.947  7117  7117 I BluetoothFtpService: Ftp Service onCreate
,08-16 17:45:33.947  7117  7117 V BluetoothFtpService: Ftp Service onStartCommand
08-16 17:45:33.948  7117  7117 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:33.948  7117  7117 V BluetoothFtpService: Starting Listening on sockets
08-16 17:45:33.948  7117  7117 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 17:45:33.948  7117  7117 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:45:33.948  7117  7117 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:45:33.948  7117  7117 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:33.948  7117  7117 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 17:45:33.948  7117  7117 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 17:45:34.042  1044  2042 I art     : Explicit concurrent mark sweep GC freed 92514(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.028ms total 114.743ms
08-16 17:45:34.042  7117  7716 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-16 17:45:34.043  7117  7117 V BluetoothFtpService: Handler(): got msg=1
,08-16 17:45:34.045  7117  7117 V BluetoothFtpService: Ftp Service startRfcommSocketListener
,08-16 17:45:34.045  7117  7117 V BluetoothFtpService: Ftp Service initSocket
08-16 17:45:34.046  1044  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:34.048  7117  7117 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:34.049  7117  7713 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a8c5085 on behalf of 
08-16 17:45:34.051  7117  7713 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 17:45:34.051  7117  7117 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-16 17:45:34.051  7117  7117 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 17:45:34.054  7117  7717 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 17:45:34.055  7117  7713 V BluetoothOppNotification: inbound notification was removed.
08-16 17:45:34.055  7117  7713 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 17:45:34.056  7117  7713 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a24feda on behalf of 
,08-16 17:45:34.076  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:34.076  7117  7117 V BluetoothSapService: Sap Service onCreate
08-16 17:45:34.077  7117  7117 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:34.077  7117  7117 V BluetoothSapService: state: 12
08-16 17:45:34.078  7117  7117 V BluetoothSapService: Starting SAP server process
,08-16 17:45:34.081  7117  7117 V BluetoothSapService: SAP Service startRfcommListenerThread
,08-16 17:45:34.067  7718  7718 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 17:45:34.067  7718  7718 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:34.084  7117  7719 V BluetoothSapService: Sap Service initRfcommSocket
,08-16 17:45:34.085  1044  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:34.087  7718  7718 V BT_SAP  : Event pipe created
08-16 17:45:34.087  7718  7718 V BT_SAP  : create_server_socket qcom.sap.server
,08-16 17:45:34.087  7718  7718 V BT_SAP  : created socket fd 6
,08-16 17:45:34.087  7117  7719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:34.088  7117  7719 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
,08-16 17:45:34.088  7117  7719 V BluetoothSapService: Succeed to create listening socket 
08-16 17:45:34.088  7117  7719 V BluetoothSapService: Accepting socket connection...
08-16 17:45:34.386  1044  1400 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:34.387  1044  1400 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:45:34.414  1044  1449 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 17:45:34.415  1044  1449 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-16 17:45:34.914  7117  7117 V BluetoothOppNotification: new notify threadi!
,08-16 17:45:34.914  7117  7117 V BluetoothOppNotification: send delay message
,08-16 17:45:34.934  7117  7729 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 17:45:34.938  1044  1969 I ActivityManager: Killing 7504:com.lge.bnr/1000 (adj 15): empty #17
08-16 17:45:34.954  7117  7729 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12642ea6 on behalf of 
08-16 17:45:34.955  7117  7729 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-16 17:45:34.960  7117  7729 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 17:45:34.961  7117  7729 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1542a0e7 on behalf of 
08-16 17:45:34.962  7117  7729 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 17:45:34.964  7117  7729 V BluetoothOppNotification: outbound notification was removed.
08-16 17:45:34.964  7117  7729 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 17:45:34.965  7117  7729 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@340f1494 on behalf of 
08-16 17:45:34.965  7117  7729 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 17:45:34.968  7117  7729 V BluetoothOppNotification: inbound notification was removed.
08-16 17:45:34.968  7117  7729 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-16 17:45:34.971  7117  7729 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1290b3d on behalf of 
08-16 17:45:34.975  1044  2042 W libprocessgroup: failed to open /acct/uid_1000/pid_7504/cgroup.procs: No such file or directory
08-16 17:45:35.049  1044  1060 I ActivityManager: Killing 6729:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-16 17:45:35.071  7045  7045 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 17:45:35.071  7045  7045 W System.err: android.os.DeadObjectException
08-16 17:45:35.071  7045  7045 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 17:45:35.072  7045  7045 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 17:45:35.072  7045  7045 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 17:45:35.072  7045  7045 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 17:45:35.072  7045  7045 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 17:45:35.072  7045  7045 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 17:45:35.072  7045  7045 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:45:35.072  7045  7045 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:45:35.072  7045  7045 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 17:45:35.072  7045  7045 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 17:45:35.072  7045  7045 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:45:35.072  7045  7045 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:45:35.072  7045  7045 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 17:45:35.072  7045  7045 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 17:45:35.072  7045  7045 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 17:45:35.073  7045  7045 W System.err: android.os.DeadObjectException
08-16 17:45:35.073  7045  7045 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 17:45:35.073  7045  7045 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 17:45:35.073  7045  7045 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 17:45:35.073  7045  7045 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 17:45:35.073  7045  7045 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 17:45:35.073  7045  7045 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 17:45:35.073  7045  7045 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:45:35.073  7045  7045 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:45:35.073  7045  7045 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 17:45:35.073  7045  7045 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 17:45:35.073  7045  7045 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:45:35.073  7045  7045 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:45:35.073  7045  7045 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 17:45:35.073  7045  7045 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 17:45:35.074  7045  7045 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 17:45:35.074  7045  7045 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-16 17:45:35.108  1044  1896 W libprocessgroup: failed to open /acct/uid_1000/pid_6729/cgroup.procs: No such file or directory
08-16 17:45:35.109  1044  1896 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 17:45:35.116  7045  7045 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 17:45:35.116  7045  7045 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 17:45:35.167  1044  2005 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7730 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 17:45:35.219  7045  7045 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 17:45:35.263  7730  7730 D UEI.SmartControl: Quickset Services start...
,08-16 17:45:35.266  7730  7730 I UEI.SmartControl: Manufacture = LGE
08-16 17:45:35.266  7730  7730 D UEI.SmartControl: Id = LGNevo
08-16 17:45:35.268  7730  7730 D UEI.SmartControl: File observer start...
08-16 17:45:35.268  7730  7730 E UEI.SmartControl: IR Port is disabled: false
08-16 17:45:35.269  7730  7730 D UEI.SmartControl: Starting file observer...
08-16 17:45:35.269  7730  7730 D UEI.SmartControl: Extracting JNI libs...
08-16 17:45:35.269  7730  7730 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 17:45:35.357  7730  7730 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 17:45:35.357  7730  7730 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 17:45:35.357  7730  7730 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 17:45:35.380  1044  2042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 17:45:35.380  1044  2042 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@f6526e3 mBinding = false
,08-16 17:45:35.387  7730  7730 I UEI.SmartControl: --- Selecting new region: 6
08-16 17:45:35.389  7730  7730 I UEI.SmartControl: Model = LG-D855
08-16 17:45:35.390  7730  7730 D UEI.SmartControl: QS Service created
08-16 17:45:35.402  7730  7730 I UEI.SmartControl: Service initServices...
,08-16 17:45:35.406  7730  7730 D UEI.SmartControl: QS start get config
,08-16 17:45:35.410  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 17:45:35.410  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:45:35.410  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 17:45:35.411  1044  1106 D BluetoothManagerService: Message: 2
08-16 17:45:35.412  1044  1106 D BluetoothManagerService: Sending off request.
08-16 17:45:35.413  7117  7132 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 17:45:35.414  7117  7575 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 17:45:35.414  7117  7575 D BluetoothAdapterProperties: Setting state to 13
08-16 17:45:35.414  7117  7575 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:45:35.414  7117  7575 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 17:45:35.414  7117  7575 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 17:45:35.416  7117  7579 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:45:35.416  7117  7575 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 17:45:35.417  7117  7575 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:45:35.417  7117  7703 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:35.417  7117  7719 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:35.417  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 17:45:35.419  7117  7715 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:35.420  7117  7717 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:35.420  7117  7644 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 17:45:35.423  7117  7702 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 17:45:35.423  7117  7702 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:45:35.423  7117  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 17:45:35.423  7117  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 17:45:35.423  7117  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 17:45:35.423  7117  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 17:45:35.423  7117  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 17:45:35.423  7117  7702 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:35.428  7117  7644 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:45:35.429  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 17:45:35.429  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 17:45:35.429  7117  7644 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 17:45:35.434  1044  1106 D BluetoothManagerService: Message: 60
08-16 17:45:35.434  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 17:45:35.435  1044  1106 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-16 17:45:35.437  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.444  7730  7730 D UEI.SmartControl: Loading JNI Libs...
08-16 17:45:35.444  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:35.445  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:35.445  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:35.445  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:35.445  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:35.445  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:35.445  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:35.445  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:35.445  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:35.445  7117  7117 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.445  7117  7117 D BluetoothMapService: STATE_TURNING_OFF
08-16 17:45:35.445  6989  6989 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 17:45:35.445  7117  7117 V BluetoothMapService: Handler(): got msg=4
08-16 17:45:35.445  7117  7117 D BluetoothMapService: MAP Service closeService in
08-16 17:45:35.446  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:35.446  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:35.446  1613  1613 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 17:45:35.448  6989  6989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 17:45:35.448  7117  7117 D BluetoothMapMasInstance: MAP Service shutdown
,08-16 17:45:35.448  7117  7117 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 17:45:35.448  7117  7117 V BluetoothMapService: MAP Service closeService out
08-16 17:45:35.448  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:35.448  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:35.448  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:35.448  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:35.448  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:35.448  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:45:35.448  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:35.448  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:35.448  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:35.449  7117  7117 V BtOppService: Receiver DISABLED_ACTION 
08-16 17:45:35.449  7117  7117 I BtOppRfcommListener: stopping Accept Thread
08-16 17:45:35.449  7117  7117 V BtOppRfcommListener: close mBtServerSocket
08-16 17:45:35.449  6813  6813 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:45:35.449  7117  7117 V BtOppRfcommListener: waiting for thread to terminate
08-16 17:45:35.449  7117  7715 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 17:45:35.450  7117  7117 V BtOppRfcommListener: done waiting for thread to terminate
08-16 17:45:35.450  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:35.451  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:35.452  7117  7117 V BtOppService: onDestroy
08-16 17:45:35.454  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:35.455  6989  6989 D DockEventReceiver: finishStartingService: stopping service
08-16 17:45:35.455  7117  7117 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 17:45:35.455  7117  7117 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 17:45:35.455  7117  7117 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.456  7117  7117 V BluetoothPbapReceiver: ***********state = 13
08-16 17:45:35.457  7117  7117 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 17:45:35.459  7117  7117 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.459  7117  7117 V BluetoothPbapService: state: 13
08-16 17:45:35.459  7117  7117 V BluetoothPbapService: Pbap Service closeService in
08-16 17:45:35.460  7117  7117 V BluetoothPbapService: successfully stopped pbap service
08-16 17:45:35.460  7117  7117 V BluetoothPbapService: Pbap Service closeService out
08-16 17:45:35.460  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:45:35.461  7117  7117 V BluetoothPbapService: Pbap Service onDestroy
08-16 17:45:35.461  7117  7117 V BluetoothPbapService: Pbap Service closeService in
08-16 17:45:35.461  7117  7117 V BluetoothPbapService: Pbap Service closeService out
08-16 17:45:35.461  7117  7117 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-16 17:45:35.462  6989  6989 D BluetoothPbap: Proxy object disconnected
08-16 17:45:35.462  6989  6989 D PbapServerProfile: Bluetooth service disconnected
08-16 17:45:35.467  6989  6989 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 17:45:35.469  6989  6989 D BluetoothPermissionRequest: onReceive
08-16 17:45:35.469  6989  6989 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-16 17:45:35.473  6989  6989 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 17:45:35.474  7117  7117 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 17:45:35.475  7117  7117 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-16 17:45:35.475  7117  7117 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 17:45:35.478  7117  7117 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.478  7117  7117 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 17:45:35.478  7117  7117 V BluetoothFtpService: Ftp Service onStartCommand
08-16 17:45:35.478  7117  7117 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.479  7117  7117 V BluetoothFtpService: Ftp Service closeService
08-16 17:45:35.479  7117  7117 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 17:45:35.480  7117  7117 V BluetoothFtpService: successfully stopped ftp service
08-16 17:45:35.480  7117  7117 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 17:45:35.480  7117  7117 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:45:35.480  7117  7117 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:45:35.480  7117  7117 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.480  7117  7117 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 17:45:35.480  7117  7117 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 17:45:35.482  7117  7117 V BluetoothFtpService: Ftp Service onDestroy
08-16 17:45:35.482  7117  7117 V BluetoothFtpService: Ftp Service closeService
08-16 17:45:35.482  7117  7117 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.482  7117  7117 V BluetoothSapService: state: 13
08-16 17:45:35.483  7117  7117 V BluetoothSapService: Stopping SAP server process
08-16 17:45:35.483  7117  7117 V BluetoothSapService: Sap Service closeSapService in
08-16 17:45:35.483  7117  7117 V BluetoothSapService: Close listen Socket : 
08-16 17:45:35.484  7117  7117 V BluetoothSapService: Close rfcomm Socket : 
08-16 17:45:35.484  7117  7117 V BluetoothSapService: Close sapd  Socket : 
08-16 17:45:35.487  7117  7117 V BluetoothSapService: Sap Service closeSapService out
08-16 17:45:35.487  7117  7117 V BluetoothSapService: Sap Service onDestroy
08-16 17:45:35.487  7117  7117 V BluetoothSapService: Sap Service closeSapService in
08-16 17:45:35.487  7117  7117 V BluetoothSapService: Close listen Socket : 
08-16 17:45:35.487  7117  7117 V BluetoothSapService: Close rfcomm Socket : 
08-16 17:45:35.487  7117  7117 V BluetoothSapService: Close sapd  Socket : 
,08-16 17:45:35.490  7117  7117 V BluetoothSapService: Sap Service closeSapService out
08-16 17:45:35.522  7117  7644 W bt-btif : ag scb idx 1 not allocated
08-16 17:45:35.522  7117  7579 D bt_hci_bdroid: cleanup
08-16 17:45:35.522  7117  7644 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 17:45:35.522  7117  7646 I bt_lpm  : LPM is already off!!!
08-16 17:45:35.522  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:35.522  7117  7644 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:35.523  7117  7673 I bt_userial_mct: exiting userial_read_thread
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:45:35.523  7117  7673 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 17:45:35.523  7117  7644 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:45:35.523  7117  7644 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 17:45:35.523  7117  7579 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 17:45:35.523  7117  7646 I bt_vendor: hw_epilog_process
08-16 17:45:35.523  7117  7579 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 17:45:35.523  7117  7579 D bt_userial_mct: userial_close
08-16 17:45:35.523  7117  7579 E bt_userial_mct: pthread_join() FAILED result:3
08-16 17:45:35.523  7117  7579 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 17:45:35.708  7117  7579 D bt_hci_bdroid: set_power 0
08-16 17:45:35.708  7117  7579 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 17:45:35.708  7117  7579 I bt_vendor: bluetooth satus is on
08-16 17:45:35.708  7117  7579 I bt_vendor: bt-vendor : resetting BT status
08-16 17:45:35.708  7117  7579 I bt_vendor: Starting hciattach daemon
08-16 17:45:35.708  7117  7579 I bt_vendor: try to set false
,08-16 17:45:35.712  7117  7579 I bt_vendor: Starting hciattach daemon
08-16 17:45:35.712  7117  7579 I bt_vendor: try to set false
08-16 17:45:35.714  7117  7579 I bt_vendor: cleanup
08-16 17:45:35.715  7117  7644 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 17:45:35.715  7117  7579 I GKI_LINUX: GKI_exit_task 0 done
08-16 17:45:35.715  7117  7579 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 17:45:35.716  7117  7575 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 17:45:35.720  7117  7117 D HeadsetService: Received stop request...Stopping profile...
08-16 17:45:35.722  7117  7117 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 17:45:35.722  7117  7117 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:45:35.722  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:35.722  7117  7589 D HeadsetStateMachine: Exit Disconnected: -1
08-16 17:45:35.724  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:35.724  1044  1044 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:35.725  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 17:45:35.727  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:35.728  7117  7117 D A2dpService: Received stop request...Stopping profile...
08-16 17:45:35.728  7117  7575 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 17:45:35.728  7117  7629 D A2dpStateMachine: Exit Disconnected: -1
08-16 17:45:35.729  6989  6989 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:35.729  1862  1862 D BluetoothHeadset: Proxy object disconnected
08-16 17:45:35.729  6989  6989 D HeadsetProfile: Bluetooth service disconnected
08-16 17:45:35.730  7117  7117 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-16 17:45:35.731  7117  7117 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 17:45:35.731  7117  7117 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:45:35.732  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:35.733  1044  1044 D BluetoothA2dp: Proxy object disconnected
08-16 17:45:35.733  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 17:45:35.734  6989  6989 D BluetoothA2dp: Proxy object disconnected
08-16 17:45:35.734  6989  6989 D A2dpProfile: Bluetooth service disconnected
08-16 17:45:35.735  7117  7117 D HidService: Received stop request...Stopping profile...
08-16 17:45:35.735  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:35.738  6989  6989 D BluetoothInputDevice: Proxy object disconnected
08-16 17:45:35.738  6989  6989 D HidProfile: Bluetooth service disconnected
,08-16 17:45:35.739  7117  7117 D HealthService: Received stop request...Stopping profile...
08-16 17:45:35.739  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:35.742  7117  7117 D PanService: Received stop request...Stopping profile...
08-16 17:45:35.742  7730  7730 I UEI.SmartControl: Supports setup maps: true
08-16 17:45:35.742  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:35.744  6989  6989 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:45:35.744  6989  6989 D PanProfile: Bluetooth service disconnected
08-16 17:45:35.744  7117  7117 D HeadsetStateMachine: Unbinding service...
08-16 17:45:35.745  7117  7117 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 17:45:35.745  7117  7117 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 17:45:35.745  7117  7117 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 17:45:35.745  7117  7117 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 17:45:35.745  7117  7117 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:45:35.745  7117  7117 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:45:35.745  7117  7117 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 17:45:35.746  7117  7117 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:45:35.746  7117  7117 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:45:35.746  7117  7117 D BtGatt.GattService: stop()
08-16 17:45:35.746  7117  7117 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 17:45:35.746  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:35.747  7117  7117 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 17:45:35.747  7117  7117 D BluetoothMapService: stop()
08-16 17:45:35.748  7117  7117 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 17:45:35.748  7117  7117 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 17:45:35.748  7730  7730 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 17:45:35.748  7117  7117 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:35.748  7730  7730 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 17:45:35.748  7730  7730 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 17:45:35.749  7730  7730 I UEI.SmartControl: ### init IR Blaster...
08-16 17:45:35.749  7117  7117 I BluetoothA2dpServiceJni: cleanupNative
08-16 17:45:35.749  7117  7630 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 17:45:35.750  7117  7117 I GKI_LINUX: GKI_exit_task 2 done
,08-16 17:45:35.750  7117  7117 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 17:45:35.750  7117  7117 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-16 17:45:35.750  7117  7117 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:45:35.750  7117  7117 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:45:35.751  7117  7117 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:45:35.751  7117  7117 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:45:35.751  7117  7117 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:45:35.751  7117  7117 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:45:35.752  6989  6989 D BluetoothMap: Proxy object disconnected
08-16 17:45:35.752  7117  7117 V BluetoothMapService: Handler(): got msg=4
08-16 17:45:35.752  7117  7117 D BluetoothMapService: MAP Service closeService in
08-16 17:45:35.752  6989  6989 D MapProfile: Bluetooth service disconnected
08-16 17:45:35.752  7117  7117 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 17:45:35.752  7117  7117 V BluetoothMapService: MAP Service closeService out
08-16 17:45:35.752  7117  7575 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:45:35.752  7117  7117 D BluetoothMapService: cleanup()
08-16 17:45:35.752  7117  7575 D BluetoothAdapterProperties: Setting state to 10
08-16 17:45:35.752  7117  7117 D BluetoothMapService: MAP Service closeService in
08-16 17:45:35.752  7117  7575 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:45:35.752  7117  7117 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 17:45:35.752  7117  7117 V BluetoothMapService: MAP Service closeService out
08-16 17:45:35.753  1044  1106 D BluetoothManagerService: Message: 60
08-16 17:45:35.753  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 17:45:35.753  1044  1106 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 17:45:35.753  1044  1106 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:35.753  7117  7575 I BluetoothAdapterState: Entering OffState
08-16 17:45:35.754  1862  1877 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:35.754  6989  7102 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:45:35.755  6989  7012 D BluetoothPan: onBluetoothStateChange on: false
08-16 17:45:35.755  1044  1106 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:45:35.755  6989  7011 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:35.756  1862  2713 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:35.756  6989  7102 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:45:35.756  6989  7012 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:45:35.757  6989  7011 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:45:35.757  1862  2466 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:45:35.758  1044  1106 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 17:45:35.758  1044  1106 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 17:45:35.759  7730  7730 D serial_port: Configuring serial port
08-16 17:45:35.759  1044  1106 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 17:45:35.759  1044  1106 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 17:45:35.759  1044  1106 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@f6526e3 mBinding = false
08-16 17:45:35.760  1044  1106 D BluetoothManagerService: Sending unbind request.
08-16 17:45:35.761  1044  1106 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 17:45:35.762  7117  7579 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 17:45:35.762  7117  7117 I GKI_LINUX: GKI_exit_task 1 done
08-16 17:45:35.762  7117  7117 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 1,7:45:35.763  7117  7117 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 17:45:35.763  7117  7117 I art     : --- WEIRD: removing null entry 248
08-16 17:45:35.763  7117  7117 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 17:45:35.763  7117  7117 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-16 17:45:35.765  7730  7730 E UEI.SmartControl: UEIBLaster setting for 616
08-16 17:45:35.765  7730  7730 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 17:45:35.765  1613  1613 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 17:45:35.765  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:35.765  7730  7730 I UEI.SmartControl: configuring settings for MAXQ616
08-16 17:45:35.765  1951  2134 D LGBluetoothAPIService: Message: 2
08-16 17:45:35.766  7730  7730 I UEI.SmartControl: Get version...
08-16 17:45:35.766  1951  2134 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2d435f78 mBinding = false
08-16 17:45:35.766  1951  2134 D LGBluetoothAPIService: Sending unbind request.
08-16 17:45:35.769  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:35.770  1613  1613 D BluetoothAdapter: 373615427: getState() :  mService = null. Returning STATE_OFF
08-16 17:45:35.770  1613  1613 D BluetoothAdapter: 373615427: getState() :  mService = null. Returning STATE_OFF
08-16 17:45:35.770  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:35.770  6989  6989 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 17:45:35.770  6989  6989 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 17:45:35.776  7117  7117 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-16 17:45:35.779  6989  6989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 17:45:35.781  7117  7117 I art     : System.exit called, status: 0
08-16 17:45:35.781  7117  7117 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 17:45:35.782  6989  6989 D DockEventReceiver: finishStartingService: stopping service
08-16 17:45:35.787  7730  7769 D UEI.SmartControl: serial port data available: 21
08-16 17:45:35.803   311  1407 V AudioFlinger: 7117 died, releasing its sessions
08-16 17:45:35.803   311  1407 V AudioFlinger:  pid 1862 @ 0
08-16 17:45:35.803   311  1407 V AudioFlinger:  pid 3504 @ 1
08-16 17:45:35.803   311  1407 V AudioFlinger:  pid 3504 @ 2
08-16 17:45:35.803  6989  6989 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-16 17:45:35.815  7730  7730 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 17:45:35.815  7730  7730 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 17:45:35.815  7730  7730 I UEI.SmartControl: QS saving settings...
08-16 17:45:35.816  7730  7730 D UEI.SmartControl: IR Blaster version: 25672567
08-16 17:45:35.817  1044  2023 I ActivityManager: Process com.android.bluetooth (pid 7117) has died
08-16 17:45:35.817  1044  2023 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-16 17:45:35.822  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:45:35.834  7730  7769 D UEI.SmartControl: serial port data available: 4
,08-16 17:45:35.836  6989  6989 D BluetoothPermissionRequest: onReceive
08-16 17:45:35.839  6989  6989 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 17:45:35.839  6989  6989 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 17:45:35.843  6989  6989 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 17:45:35.873  7730  7774 I UEI.SmartControl: Device manager: loading config....
,08-16 17:45:35.875  7730  7774 D UEI.SmartControl: ----------- loading internal config...
08-16 17:45:35.879  7730  7730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 17:45:35.895  7730  7774 E UEI.SmartControl: Loading SETTINGS...
,08-16 17:45:35.906  7730  7774 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 17:45:35.922  1044  1987 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7776 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-16 17:45:35.923  7730  7730 E UEI.SmartControl: Services init done
,08-16 17:45:35.923  7730  7730 D UEI.SmartControl: QS Service init finished
08-16 17:45:35.925  7730  7730 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 17:45:35.925  7730  7730 D UEI.SmartControl: QS Service version code: 201091
08-16 17:45:35.928  7730  7730 D UEI.SmartControl: Service requested: Control
08-16 17:45:35.929  7730  7773 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 17:45:35.929  7730  7773 D UEI.SmartControl: -----service ready thread exits
08-16 17:45:35.930  1044  1933 I ActivityManager: Killing 7045:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 17:45:35.999  1044  1896 W libprocessgroup: failed to open /acct/uid_10112/pid_7045/cgroup.procs: No such file or directory
08-16 17:45:35.999  7730  7730 D UEI.SmartControl: Internal service binding...
,08-16 17:45:36.031  7776  7776 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 17:45:36.032  7776  7776 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 17:45:36.032  7776  7776 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 17:45:36.035  7776  7776 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 17:45:36.061  1044  1388 V AlarmManager: ELAPSED_WAKEUP set : Alarm{4fe8f5b type 2 when 223949 android} when 223949
,08-16 17:45:36.073  7776  7776 D BluetoothAdapterApp: Loading JNI Library
08-16 17:45:36.111  7776  7776 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15121309 Instance Count = 1
,08-16 17:45:36.145  1044  1102 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7793 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 17:45:36.146  7776  7776 D BluetoothAdapterApp: onCreate
,08-16 17:45:36.171  7776  7776 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-16 17:45:36.171  7776  7776 D ProfileConfigQcom: Adding HeadsetService
08-16 17:45:36.172  7776  7776 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 17:45:36.172  7776  7776 D ProfileConfigQcom: Adding A2dpService
08-16 17:45:36.173  7776  7776 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 17:45:36.174  7776  7776 D ProfileConfigQcom: Adding HidService
08-16 17:45:36.175  7776  7776 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 17:45:36.175  7776  7776 D ProfileConfigQcom: Adding HealthService
08-16 17:45:36.176  7776  7776 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 17:45:36.177  7776  7776 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 17:45:36.177  7776  7776 D ProfileConfigQcom: Adding PanService
08-16 17:45:36.178  7776  7776 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 17:45:36.179  7776  7776 D ProfileConfigQcom: Adding GattService
08-16 17:45:36.179  7776  7776 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 17:45:36.180  7776  7776 D ProfileConfigQcom: Adding BluetoothMapService
08-16 17:45:36.180  7776  7776 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 17:45:36.184  7776  7776 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 17:45:36.190  6989  6989 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 17:45:36.193  7776  7776 V LGMDMManagerInternal: Create singleton instance
08-16 17:45:36.207  7793  7793 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 17:45:36.223  7793  7793 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 17:45:36.245  7793  7793 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 17:45:36.245  7793  7793 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 17:45:36.245  7793  7793 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 17:45:36.246  7793  7793 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-16 17:45:36.246  7793  7793 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 17:45:36.247  7793  7793 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-16 17:45:36.251  7793  7793 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 17:45:36.255  7793  7793 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 17:45:36.256  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4188
08-16 17:45:36.257  7793  7793 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 17:45:36.259  7793  7793 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 17:45:36.259  7793  7793 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 17:45:36.260  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 17:45:36.260  7793  7793 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-16 17:45:36.272  7776  7776 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:45:36.275  7776  7776 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-16 17:45:36.276  7776  7776 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:45:36.276  7776  7776 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:45:36.277  7776  7776 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:36.277  7776  7776 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 17:45:36.279  7062  7062 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 17:45:36.280  1044  1932 I ActivityManager: Killing 7016:com.lge.sync/1000 (adj 15): empty #17
08-16 17:45:36.282  7793  7793 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:36.282  7793  7793 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 17:45:36.288  7793  7793 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 17:45:36.289  7793  7793 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 17:45:36.289  7793  7793 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 17:45:36.289  7793  7793 V SoundPool: doLoad: loading sample sampleID=1
08-16 17:45:36.290  7793  7814 V SoundPool: Start decode
08-16 17:45:36.290  7793  7814 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 17:45:36.290   311  1406 V MediaPlayerService: decode(23, 10857164, 17813)
08-16 17:45:36.290   311  1406 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 17:45:36.290   311  1406 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 17:45:36.290   311  1406 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 17:45:36.290   311  1406 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 17:45:36.290   311  1406 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 17:45:36.290   311  1406 V MediaPlayerService: player type = 3
08-16 17:45:36.290   311  1406 V AwesomePlayer: AwesomePlayer create()
08-16 17:45:36.290   311  1406 V AwesomePlayer: reset_l() 
08-16 17:45:36.290   311  1406 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:36.290   311  1406 V AwesomePlayer: setAudioSink() 
08-16 17:45:36.290   311  1406 V AwesomePlayer: reset_l() 
08-16 17:45:36.290   311  1406 V AudioCache: notify(0xb54745c0, 8, 0, 0)
08-16 17:45:36.290   311  1406 V AudioCache: ignored
08-16 17:45:36.290   311  1406 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:36.290  7793  7793 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 17:45:36.290   311  1406 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 17:45:36.290   311  1406 V AwesomePlayer: setDataSource_l dataSource
08-16 17:45:36.290   311  1406 V LGParserOSAL: SniffLGParser start
08-16 17:45:36.291   311  1406 V LGParserOSAL: MainType:5, SubType=0
08-16 17:45:36.291   311  1406 V LGParserOSAL: #### check Mime : application/ogg
08-16 17:45:36.291   311  1406 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 17:45:36.291   311  1406 E MediaExtractor: Use LGExtractor :application/ogg 
,08-16 17:45:36.301  1044  1506 D WifiService: Client connection lost with reason: 4
08-16 17:45:36.320   311  1406 V LGParserOSAL: supported mime: application/ogg
08-16 17:45:36.321   311  1406 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 17:45:36.321   311  1406 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 17:45:36.321   311  1406 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 17:45:36.321   311  1406 V AwesomePlayer: AudioTrack Setting
08-16 17:45:36.321   311  1406 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 17:45:36.321   311  1406 V AwesomePlayer: setAudioSource() 
08-16 17:45:36.321   311  1406 V MediaPlayerService: prepare
08-16 17:45:36.321   311  1406 V AwesomePlayer: prepareAsync_l() 
08-16 17:45:36.321   311  1406 V MediaPlayerService: wait for prepare
08-16 17:45:36.321   311  7815 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 17:45:36.321   311  7815 V AwesomePlayer: initAudioDecoder() 
08-16 17:45:36.321   311  7815 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 17:45:36.321   311  7815 V AudioSystem: isOffloadSupported()
08-16 17:45:36.321   311  7815 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 17:45:36.321   311  7815 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 17:45:36.321   311  7815 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 17:45:36.321   311  7815 V AwesomePlayer: getUseOffload() = 0 
08-16 17:45:36.321   311  7815 V OMXCodec: OMXCodec::Create
08-16 17:45:36.321   311  7815 V OMXCodec: findMatchingCodecs()
,08-16 17:45:36.321   311  7815 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000,
08-16 17:45:36.322   311  7815 V OMXCodec: matchingCodecs.size()=1
08-16 17:45:36.322   311  7815 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 17:45:36.324   311  7815 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 17:45:36.324   311  7815 V LGCodecAdapter: LG Codec Adapter start
08-16 17:45:36.324   311  7815 V OMXCodec: OMXCodec Createtor
08-16 17:45:36.324   311  7815 V OMXCodec: setComponentRole
08-16 17:45:36.324   311  7815 V OMXCodec: configureCodec protected=0
08-16 17:45:36.324   311  7815 V LGCodecAdapter: called getLGCodecSpecificData
08-16 17:45:36.324   311  7815 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 17:45:36.324   311  7815 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 17:45:36.324   311  7815 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 17:45:36.324   311  7815 V LGCodecOSAL: Not support LGCodec
08-16 17:45:36.324   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 17:45:36.325   311  7815 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 17:45:36.325   311  7815 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 17:45:36.325   311  7815 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 17:45:36.325   311  7815 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 17:45:36.325   311  7815 V AudioSystem: isOffloadSupported()
08-16 17:45:36.325   311  7815 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 17:45:36.325   311  7815 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 17:45:36.325   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 17:45:36.325   311  7815 V OMXCodec: init()
08-16 17:45:36.325   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
,08-16 17:45:36.325   311  7815 V OMXCodec: allocateBuffers
08-16 17:45:36.325   311  7815 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 17:45:36.325   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 17:45:36.326   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76a0 on input port
08-16 17:45:36.326   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-16 17:45:36.326   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-16 17:45:36.326   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-16 17:45:36.326   311  7815 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 17:45:36.326   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 17:45:36.327   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
,08-16 17:45:36.327   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-16 17:45:36.327   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 17:45:36.327   311  7815 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-16 17:45:36.327   311  7815 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 17:45:36.327   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 17:45:36.327   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 17:45:36.327   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 17:45:36.328   311  7815 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 17:45:36.328   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 17:45:36.328   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 17:45:36.328   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,08-16 17:45:36.328   311  7815 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 17:45:36.328   311  7815 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 17:45:36.328   311  7815 V AudioCache: notify(0xb54745c0, 5, 0, 0)
08-16 17:45:36.328   311  7815 V AudioCache: ignored
08-16 17:45:36.328   311  7815 V AudioCache: notify(0xb54745c0, 1, 0, 0)
08-16 17:45:36.328   311  7815 V AudioCache: prepared
08-16 17:45:36.328   311  1406 V AudioCache: wait - success
08-16 17:45:36.328   311  1406 V MediaPlayerService: start
08-16 17:45:36.328   311  1406 V AwesomePlayer: play_l() 
08-16 17:45:36.328   311  1406 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
,08-16 17:45:36.328   311  1406 V AwesomePlayer: createAudioPlayer_l
08-16 17:45:36.328   311  1406 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 17:45:36.328   311  1406 V AwesomePlayer: startAudioPlayer_l() 
08-16 17:45:36.328   311  1406 D AudioPlayer: start of Playback, useOffload 0
08-16 17:45:36.328   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 17:45:36.328   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 17:45:36.336   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 17:45:36.336   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 17:45:36.336   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 17:45:36.336   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-16 17:45:36.337   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 17:45:36.337   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 17:45:36.338   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884608
08-16 17:45:36.338   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:36.338   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-16 17:45:36.338   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:36.338   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-16 17:45:36.338   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:36.338   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-16 17:45:36.338   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-16 17:45:36.339   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 17:45:36.339   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 17:45:36.339   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 17:45:36.339   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 17:45:36.339   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 17:45:36.339   311  7817 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 17:45:36.339   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 17:45:36.339   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 17:45:36.340   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
,08-16 17:45:36.340   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
08-16 17:45:36.340   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-16 17:45:36.340   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 17:45:36.340   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 17:45:36.341   311  1406 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 17:45:36.341   311  1406 V AudioCache: notify(0xb54745c0, 6, 0, 0)
08-16 17:45:36.341   311  1406 V AudioCache: ignored
08-16 17:45:36.342   311  1406 V MediaPlayerService: wait for playback complete
,08-16 17:45:36.343   311  7818 V AudioCache: write(0xb16e2000, 4096),
08-16 17:45:36.343   311  7818 V AudioCache: memcpy(0xaf006000, 0xb16e2000, 4096)
08-16 17:45:36.348   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.348   311  7818 V AudioCache: memcpy(0xaf007000, 0xb16e2000, 4096)
08-16 17:45:36.349   311  7818 V AudioCache: write(0xb16e2000, 4096)
,08-16 17:45:36.349   311  7818 V AudioCache: memcpy(0xaf008000, 0xb16e2000, 4096)
08-16 17:45:36.350   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.350   311  7818 V AudioCache: memcpy(0xaf009000, 0xb16e2000, 4096)
08-16 17:45:36.351   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.351   311  7818 V AudioCache: memcpy(0xaf00a000, 0xb16e2000, 4096)
08-16 17:45:36.351   311  7818 V AudioCache: write(0xb16e2000, 4096)
,08-16 17:45:36.351   311  7818 V AudioCache: memcpy(0xaf00b000, 0xb16e2000, 4096)
08-16 17:45:36.352   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.352   311  7818 V AudioCache: memcpy(0xaf00c000, 0xb16e2000, 4096)
08-16 17:45:36.353   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.353   311  7818 V AudioCache: memcpy(0xaf00d000, 0xb16e2000, 4096)
08-16 17:45:36.354   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.354   311  7818 V AudioCache: memcpy(0xaf00e000, 0xb16e2000, 4096)
,08-16 17:45:36.354   311  7818 V AudioCache: write(0xb16e2000, 4096)
,08-16 17:45:36.354   311  7818 V AudioCache: memcpy(0xaf00f000, 0xb16e2000, 4096)
08-16 17:45:36.355   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.355   311  7818 V AudioCache: memcpy(0xaf010000, 0xb16e2000, 4096)
08-16 17:45:36.356   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.356   311  7818 V AudioCache: memcpy(0xaf011000, 0xb16e2000, 4096)
08-16 17:45:36.357   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.357   311  7818 V AudioCache: memcpy(0xaf012000, 0xb16e2000, 4096)
08-16 17:45:36.357   311  7818 V AudioCache: write(0xb16e2000, 4096)
,08-16 17:45:36.357   311  7818 V AudioCache: memcpy(0xaf013000, 0xb16e2000, 4096)
08-16 17:45:36.358   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.358   311  7818 V AudioCache: memcpy(0xaf014000, 0xb16e2000, 4096)
08-16 17:45:36.359   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.359   311  7818 V AudioCache: memcpy(0xaf015000, 0xb16e2000, 4096)
08-16 17:45:36.359   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.359   311  7818 V AudioCache: memcpy(0xaf016000, 0xb16e2000, 4096)
,08-16 17:45:36.360   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.360   311  7818 V AudioCache: memcpy(0xaf017000, 0xb16e2000, 4096)
08-16 17:45:36.361   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.361   311  7818 V AudioCache: memcpy(0xaf018000, 0xb16e2000, 4096)
08-16 17:45:36.361   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.361   311  7818 V AudioCache: memcpy(0xaf019000, 0xb16e2000, 4096)
08-16 17:45:36.362   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.362   311  7818 V AudioCache: memcpy(0xaf01a000, 0xb16e2000, 4096)
08-16 17:45:36.363   311  7818 V AudioCache: write(0xb16e2000, 4096)
,08-16 17:45:36.363   311  7818 V AudioCache: memcpy(0xaf01b000, 0xb16e2000, 4096)
08-16 17:45:36.364   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.364   311  7818 V AudioCache: memcpy(0xaf01c000, 0xb16e2000, 4096)
08-16 17:45:36.364   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.364   311  7818 V AudioCache: memcpy(0xaf01d000, 0xb16e2000, 4096)
08-16 17:45:36.365   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.365   311  7818 V AudioCache: memcpy(0xaf01e000, 0xb16e2000, 4096)
08-16 17:45:36.366   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.366   311  7818 V AudioCache: memcpy(0xaf01f000, 0xb16e2000, 4096)
,08-16 17:45:36.367   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.367   311  7818 V AudioCache: memcpy(0xaf020000, 0xb16e2000, 4096)
08-16 17:45:36.367   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.367   311  7818 V AudioCache: memcpy(0xaf021000, 0xb16e2000, 4096)
08-16 17:45:36.368   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.368   311  7818 V AudioCache: memcpy(0xaf022000, 0xb16e2000, 4096)
08-16 17:45:36.369   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.369   311  7818 V AudioCache: memcpy(0xaf023000, 0xb16e2000, 4096)
08-16 17:45:36.370   311  7818 V AudioCache: write(0xb16e2000, 4096)
,08-16 17:45:36.370   311  7818 V AudioCache: memcpy(0xaf024000, 0xb16e2000, 4096)
,08-16 17:45:36.370   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.370   311  7818 V AudioCache: memcpy(0xaf025000, 0xb16e2000, 4096)
08-16 17:45:36.371   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.371   311  7818 V AudioCache: memcpy(0xaf026000, 0xb16e2000, 4096)
08-16 17:45:36.372   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.372   311  7818 V AudioCache: memcpy(0xaf027000, 0xb16e2000, 4096)
08-16 17:45:36.372   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.372   311  7818 V AudioCache: memcpy(0xaf028000, 0xb16e2000, 4096)
08-16 17:45:36.373   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.373   311  7818 V AudioCache: memcpy(0xaf029000, 0xb16e2000, 4096)
08-16 17:45:36.374   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.374   311  7818 V AudioCache: memcpy(0xaf02a000, 0xb16e2000, 4096)
08-16 17:45:36.374   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.375   311  7818 V AudioCache: memcpy(0xaf02b000, 0xb16e2000, 4096)
08-16 17:45:36.375   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.375   311  7818 V AudioCache: memcpy(0xaf02c000, 0xb16e2000, 4096)
08-16 17:45:36.376   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.376   311  7818 V AudioCache: memcpy(0xaf02d000, 0xb16e2000, 4096)
08-16 17:45:36.377   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.377   311  7818 V AudioCache: memcpy(0xaf02e000, 0xb16e2000, 4096)
08-16 17:45:36.377   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.377   311  7818 V AudioCache: memcpy(0xaf02f000, 0xb16e2000, 4096)
08-16 17:45:36.378   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.378   311  7818 V AudioCache: memcpy(0xaf030000, 0xb16e2000, 4096)
08-16 17:45:36.379   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.379   311  7818 V AudioCache: memcpy(0xaf031000, 0xb16e2000, 4096)
08-16 17:45:36.379   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.379   311  7818 V AudioCache: memcpy(0xaf032000, 0xb16e2000, 4096)
08-16 17:45:36.380   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.380   311  7818 V AudioCache: memcpy(0xaf033000, 0xb16e2000, 4096)
08-16 17:45:36.381   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.381   311  7818 V AudioCache: memcpy(0xaf034000, 0xb16e2000, 4096)
08-16 17:45:36.381   311  7818 V AudioCache: write(0xb16e2000, 4096)
,08-16 17:45:36.381   311  7818 V AudioCache: memcpy(0xaf035000, 0xb16e2000, 4096)
,08-16 17:45:36.382   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.382   311  7818 V AudioCache: memcpy(0xaf036000, 0xb16e2000, 4096)
08-16 17:45:36.382   311  7818 V AudioCache: write(0xb16e2000, 4096)
08-16 17:45:36.382   311  7818 V AudioCache: memcpy(0xaf037000, 0xb16e2000, 4096)
08-16 17:45:36.382   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 17:45:36.382  1044  1792 W libprocessgroup: failed to open /acct/uid_1000/pid_7016/cgroup.procs: No such file or directory
08-16 17:45:36.382   311  7818 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 17:45:36.382   311  7818 V AwesomePlayer: postAudioEOS() 
08-16 17:45:36.382   311  7818 V AudioCache: write(0xb16e2000, 280)
08-16 17:45:36.382   311  7818 V AudioCache: memcpy(0xaf038000, 0xb16e2000, 280)
08-16 17:45:36.384   311  7815 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 17:45:36.384   311  7815 V AwesomePlayer: onStreamDone
08-16 17:45:36.384   311  7815 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 17:45:36.384   311  7815 V AudioCache: notify(0xb54745c0, 2, 0, 0)
08-16 17:45:36.384   311  7815 V AudioCache: playback complete
08-16 17:45:36.384   311  7815 V AwesomePlayer: pause_l() 
08-16 17:45:36.384   311  7815 V AudioCache: notify(0xb54745c0, 7, 0, 0)
08-16 17:45:36.384   311  7815 V AudioCache: ignored
08-16 17:45:36.384   311  7815 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:36.384   311  1406 V AudioCache: wait - success
08-16 17:45:36.384   311  1406 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 17:45:36.384   311  7815 D AudioPlayer: Pause Playback at 1068125
08-16 17:45:36.385   311  1406 V AwesomePlayer: reset_l() 
08-16 17:45:36.385   311  1406 V AudioCache: notify(0xb54745c0, 8, 0, 0)
08-16 17:45:36.385   311  1406 V AudioCache: ignored
08-16 17:45:36.385   311  1406 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:36.385   311  1406 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 17:45:36.385   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 17:45:36.385   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 17:45:36.385   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 17:45:36.385   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 17:45:36.385   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 17:45:36.385   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 17:45:36.385   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 17:45:36.385   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-16 17:45:36.385   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 17:45:36.385   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76a0 on port 0
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
08-16 17:45:36.386   311  7817 V OMXCodec: [OM,X.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 17:45:36.386  7793  7793 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 17:45:36.386   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 17:45:36.386   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 17:45:36.386   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 17:45:36.387   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 17:45:36.387   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 17:45:36.387   311  7817 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 17:45:36.387   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 17:45:36.387   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 17:45:36.387   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 17:45:36.388   311  1406 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 17:45:36.388   311  1406 D AudioPlayer: AudioPlayer releasing audio source
08-16 17:45:36.388   311  1406 D AudioPlayer: AudioPlayer done releasing audio source
08-16 17:45:36.388   311  1406 V AwesomePlayer: reset_l() 
08-16 17:45:36.388   311  1406 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:36.388   311  1406 V AwesomePlayer: ~AwesomePlayer call
08-16 17:45:36.389   311  1406 V AwesomePlayer: reset_l() 
08-16 17:45:36.389   311  1406 V AwesomePlayer: cancelPlayerEvents
08-16 17:45:36.389  7793  7814 V SoundPool: close(31)
08-16 17:45:36.389  7793  7814 V SoundPool: pointer = 0xa002d000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 17:45:36.390  7793  7793 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 17:45:36.391  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 17:45:36.406  7793  7793 V LGMDMManager: Create singleton instance
,08-16 17:45:36.470  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-16 17:45:36.472  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 17:45:36.476  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4236
08-16 17:45:36.481  7793  7793 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 17:45:36.483  7730  7746 I UEI.SmartControl: ------ IControl API: 11
,08-16 17:45:36.485  7730  7746 I UEI.SmartControl: Registering callback...
08-16 17:45:36.487  7730  7745 I UEI.SmartControl: ------ IControl API: 19
08-16 17:45:36.489  7730  7745 I UEI.SmartControl: Registering Services Ready callback...
08-16 17:45:36.489  7730  7745 I UEI.SmartControl: Notify client services are ready...
08-16 17:45:36.490  7793  7809 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 17:45:36.490  7793  7812 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 17:45:36.490  7793  7812 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 17:45:36.491  7793  7793 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 17:45:36.491  7793  7793 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 17:45:36.491  7730  7746 I UEI.SmartControl: ------ IControl API: 8
08-16 17:45:36.493  7793  7793 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 17:45:36.493  7793  7793 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 17:45:36.494  7793  7793 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 17:45:36.494  7793  7793 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 17:45:36.495  7793  7793 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 17:45:36.495  7793  7793 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-16 17:45:36.498  7793  7793 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 17:45:36.502  7793  7793 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 17:45:36.502  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 17:45:36.503  7793  7793 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 17:45:36.503  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 17:45:36.504  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 17:45:36.505  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 17:45:36.506  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 17:45:36.507  7793  7793 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471362336506]
,08-16 17:45:36.510  7793  7793 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 17:45:36.511  1044  1629 I ActivityManager: Killing 7166:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-16 17:45:36.545  7793  7819 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 17:45:36.566  1044  1987 W libprocessgroup: failed to open /acct/uid_10011/pid_7166/cgroup.procs: No such file or directory
,08-16 17:45:36.573  7793  7793 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-16 17:45:36.574  7793  7793 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 17:45:36.575  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 17:45:36.576  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 17:45:36.577  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 17:45:36.578  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 17:45:36.579  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-16 17:45:36.600  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 17:45:38.412  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:45:38.412  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:45:38.756  1044  1390 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 17:45:38.780  1613  1613 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 17:45:38.838  2043  2043 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 17:45:38.878  1044  1102 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7829 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 17:45:38.903  1613  1613 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 17:45:38.908  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 17:45:38.908  1613  1613 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-16 17:45:38.956  1044  1044 D administrator: Handling package changes for user 0
08-16 17:45:38.992  7829  7829 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 17:45:39.093  7829  7829 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:39.093  7829  7829 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:39.097  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-16 17:45:39.097  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 17:45:39.148  1044  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:45:39.155  1044  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 17:45:39.171  2043  2043 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 17:45:39.171  2488  2488 V GmsNetworkLocationProvi: DISABLE
,08-16 17:45:39.202  1044  1101 D LocationProviderProxy: applying state to connected service
,08-16 17:45:39.204  2488  2488 E GCoreFlp: Bound FusedProviderService with LocationManager
08-16 17:45:39.230  7829  7875 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 17:45:39.231  7829  7875 I Babel   : MmsConfig.loadMmsSettings
,08-16 17:45:39.236  7829  7875 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 17:45:39.236  7829  7875 I Babel   : MmsConfig.loadFromDatabase
,08-16 17:45:39.268  7829  7875 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 17:45:39.268  7829  7875 I Babel   : MmsConfig.loadFromResources
08-16 17:45:39.271  7829  7875 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 17:45:39.272  7829  7875 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 17:45:39.279  7829  7873 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:45:39.282  7829  7873 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 17:45:39.284  7829  7873 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 17:45:39.293  7829  7829 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:39.296  7829  7873 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 17:45:39.297  7829  7873 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 17:45:39.298  7829  7873 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:45:39.313  7829  7873 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 17:45:39.315  7829  7873 W VideoCapabilities: Unsupported mime video/divx
08-16 17:45:39.318  7829  7873 W VideoCapabilities: Unsupported mime video/divx311
08-16 17:45:39.320  7829  7873 W VideoCapabilities: Unsupported mime video/divx4
08-16 17:45:39.344  1827  7876 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 17:45:39.344  1827  7876 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 17:45:39.344  7829  7873 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 17:45:39.380  7829  7873 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 17:45:39.381  1044  1584 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7880 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-16 17:45:39.389  1044  1584 I ActivityManager: Killing 7214:com.lge.email/u0a23 (adj 15): empty #17
,08-16 17:45:39.398  1827  4832 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 17:45:39.406  7829  7873 W AudioCapabilities: Unsupported mime audio/eac3
08-16 17:45:39.409  7829  7873 W AudioCapabilities: Unsupported mime audio/ac3
,08-16 17:45:39.409  7829  7873 W AudioCapabilities: Unsupported mime audio/g726
08-16 17:45:39.411  7829  7873 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 17:45:39.412  7829  7873 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 17:45:39.413  7829  7873 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 17:45:39.416  7829  7873 W VideoCapabilities: Unsupported mime video/theora
08-16 17:45:39.418  7829  7873 W VideoCapabilities: Unsupported mime video/mjpg
,08-16 17:45:39.479  1044  1987 W libprocessgroup: failed to open /acct/uid_10023/pid_7214/cgroup.procs: No such file or directory
08-16 17:45:39.519  7880  7880 I AppUp4:AppBoxCP: onCreate
08-16 17:45:39.520  7880  7880 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 17:45:39.531  7880  7880 I AppUp4:DB:  setFingerPrint start
08-16 17:45:39.532  7880  7880 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-16 17:45:39.539  7880  7880 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 17:45:39.539  7880  7880 I AppUp4:DB:  SDK version = 21
08-16 17:45:39.539  7880  7880 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-16 17:45:39.541  7880  7880 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 17:45:39.548  7880  7880 I AppUp4:CustModeStarterReceiver: onReceive
08-16 17:45:39.579  7880  7880 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:39.579  7880  7880 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:39.590  7880  7880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1e2b393c
08-16 17:45:39.590  7880  7880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 17:45:39.590  7880  7880 D AppUp4:CustFacade: isPhone : true
08-16 17:45:39.594  7880  7880 D AppUp4:CustModeStarterReceiver: begin check event
08-16 17:45:39.594  7880  7880 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-16 17:45:39.665  1044  1060 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7900 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-16 17:45:39.666  1044  1060 I ActivityManager: Killing 7082:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 17:45:39.739  1044  1897 W libprocessgroup: failed to open /acct/uid_10026/pid_7082/cgroup.procs: No such file or directory
,08-16 17:45:39.784  7900  7900 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:45:39.784  7900  7900 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 17:45:39.785  7900  7900 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 17:45:39.786  7900  7900 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 17:45:39.786  7900  7900 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-16 17:45:39.865  7900  7900 I SystemConfig: BUILD Country: EU
08-16 17:45:39.865  7900  7900 I SystemConfig: BUILD Operator: OPEN
,08-16 17:45:39.911  1044  1933 I ActivityManager: Killing 6505:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 17:45:40.035  1044  1896 W libprocessgroup: failed to open /acct/uid_1000/pid_6505/cgroup.procs: No such file or directory
,08-16 17:45:40.120  1044  1933 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7928 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 17:45:40.166  7900  7917 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 17:45:40.166  7900  7917 I SystemConfig: existFile = false
08-16 17:45:40.166  7900  7917 I SystemConfig: canReadFile = false
08-16 17:45:40.166  7900  7917 I SystemConfig: systemFeature RCS result false
08-16 17:45:40.167  7900  7917 D SystemConfig: refreshRcsSupport() :false
,08-16 17:45:40.201  7928  7928 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:45:40.202  7928  7928 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 17:45:40.202  7928  7928 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 17:45:40.202  7928  7928 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 17:45:40.332  7928  7928 I AppConfig: Total System Memory = 2995761152
,08-16 17:45:40.340  7928  7928 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-16 17:45:40.440  1044  2005 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7963 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:45:40.442  1044  2005 I ActivityManager: Killing 7250:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-16 17:45:40.491  1044  1060 W libprocessgroup: failed to open /acct/uid_10046/pid_7250/cgroup.procs: No such file or directory
,08-16 17:45:40.712  7963  7963 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 17:45:40.802  7963  7963 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:40.802  7963  7963 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:40.855  7963  7963 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 17:45:40.873  7730  7775 D UEI.SmartControl: Internal timer expired: 1
,08-16 17:45:40.873  7730  7775 D UEI.SmartControl: unbind internal service
08-16 17:45:40.876  7963  7963 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 17:45:40.877  7963  7963 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 17:45:40.892  7963  7963 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 17:45:40.893  7963  7963 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 17:45:40.910  1044  2042 I ActivityManager: Killing 7269:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 17:45:40.950  1044  1792 W libprocessgroup: failed to open /acct/uid_10057/pid_7269/cgroup.procs: No such file or directory
,08-16 17:45:40.954  3566  7331 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 17:45:40.957  3566  7331 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@226d5bff on behalf of 7963
08-16 17:45:40.959  7730  7772 D serial_port: close(fd = 25)
08-16 17:45:40.962  4680  8008 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-16 17:45:40.965  7730  7772 I UEI.SmartControl: Serial port is closed.
08-16 17:45:41.000  1044  1932 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8009 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 17:45:41.030   359   359 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 448us total 26.502ms
,08-16 17:45:41.053   359   359 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 21.809ms
08-16 17:45:41.074   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 406us total 19.664ms
,08-16 17:45:41.083  7963  7963 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-16 17:45:41.106  7963  7963 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 17:45:41.132  8009  8009 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 17:45:41.157  8009  8009 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 17:45:41.157  8009  8009 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 17:45:41.157  8009  8009 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 17:45:41.157  8009  8009 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 17:45:41.157  8009  8009 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 17:45:41.157  8009  8009 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-16 17:45:41.177  1044  1969 I ActivityManager: Killing 7290:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-16 17:45:41.222  1044  1968 W libprocessgroup: failed to open /acct/uid_10062/pid_7290/cgroup.procs: No such file or directory
,08-16 17:45:41.415  1044  2005 V SIM_STK : Menu title from STK is T-Mobile
,08-16 17:45:41.427  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:41.427  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@253468e9 added. We now have 6 listener(s)
08-16 17:45:41.427  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:41.431  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:41.431  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c7dd96e added. We now have 7 listener(s)
08-16 17:45:41.431  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:45:41.435  6813  6892 I System.out: IsBluetoothEnabled
08-16 17:45:41.438  1044  2042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:41.438  1044  2042 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-16 17:45:41.438  1044  1106 D BluetoothManagerService: Message: 2
08-16 17:45:41.441  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:41.441  1044  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:41.442  1044  2023 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 17:45:41.458  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 17:45:41.458  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:45:41.458  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 17:45:41.459  1044  1106 D BluetoothManagerService: Message: 1
08-16 17:45:41.459  1044  1106 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-16 17:45:41.466  4680  8008 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 503 ms] updated apps [took 503 ms] 
,08-16 17:45:41.484  1044  1106 D BluetoothManagerService: Message: 20
08-16 17:45:41.484  1044  1106 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3612fdb7:true
,08-16 17:45:41.485  7776  7776 D BluetoothAdapterState: make
,08-16 17:45:41.487  7793  7793 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 17:45:41.492  7776  7776 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 17:45:41.492  7776  7776 I bluedroid-qcom: init
08-16 17:45:41.493  7776  7776 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 17:45:41.494  7776  7776 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 17:45:41.494  7776  7776 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:45:41.494  7776  7776 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 17:45:41.494  7776  7776 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 17:45:41.492  7776  8048 I BluetoothAdapterState: Entering OffState
08-16 17:45:41.496  7793  7793 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4236
08-16 17:45:41.496  7776  7776 I bluedroid-qcom: get_profile_interface socket
08-16 17:45:41.496  7776  7776 I bluedroid-qcom: get_profile_interface map_client
08-16 17:45:41.477  8051  8051 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:41.477  8051  8051 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:41.501  7776  8052 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 17:45:41.503  7776  8052 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 17:45:41.504  8051  8051 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 17:45:41.504  8051  8051 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 17:45:41.504  8051  8051 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 17:45:41.507  7776  8052 D BluetoothAdapterProperties: Name is: G3
08-16 17:45:41.507  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-16 17:45:41.507  1044  1106 D BluetoothManagerService: Message: 40
08-16 17:45:41.507  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 17:45:41.507  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 17:45:41.508  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 17:45:41.508  8051  8051 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 17:45:41.508  7776  7791 I bluedroid-qcom: config_hci_snoop_log
08-16 17:45:41.510  1044  1106 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 17:45:41.510  1044  1106 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 17:45:41.515  7776  8048 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-16 17:45:41.516  7776  8048 D BluetoothAdapterProperties: Setting state to 11
08-16 17:45:41.516  7776  8048 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:45:41.517  1044  1106 D BluetoothManagerService: Message: 60
08-16 17:45:41.517  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 17:45:41.517  1044  1106 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 17:45:41.518  7776  8048 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 17:45:41.519  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:41.519  1613  1613 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 17:45:41.522  6989  6989 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 17:45:41.522  8051  8051 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 17:45:41.522  8051  8051 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 17:45:41.524  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:41.530  7776  7776 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-16 17:45:41.531  7776  7776 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:41.531  7776  7776 V BluetoothPbapReceiver: ***********state = 11
08-16 17:45:41.535  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:45:41.536  7776  8048 D BluetoothBondStateMachine: make
08-16 17:45:41.539  7776  8048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:41.540  7776  8048 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 17:45:41.540  7776  8048 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:41.540  7776  8048 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 17:45:41.540  7776  8048 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 17:45:41.542  7776  8053 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:45:41.546  7776  8048 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:41.547  6989  6989 D BluetoothPermissionRequest: onReceive
08-16 17:45:41.553  7776  8048 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:41.554  7776  7776 D HeadsetService: Received start request. Starting profile...
,08-16 17:45:41.555  7776  7776 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 17:45:41.555  7776  7776 D LGBluetoothHfpAdapter: Version 1.6
08-16 17:45:41.560  6989  6989 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 17:45:41.565  7776  8048 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:41.569  7776  7776 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 17:45:41.570  7776  7776 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 17:45:41.571  7776  8048 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:41.571  7776  7776 D HeadsetStateMachine: make
08-16 17:45:41.576  7776  8048 E BluetoothAdapterService: File transfer profiles supported!!
08-16 17:45:41.582  7776  8048 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 17:45:41.588  7776  8048 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 17:45:41.607  7776  8048 V LGMDMManager: Create singleton instance
,08-16 17:45:41.617  7776  8048 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 17:45:41.618  7776  7776 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:41.618  7776  7776 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 17:45:41.624  7776  7776 D HeadsetStateMachine: max_hf_connections = 1
08-16 17:45:41.624  7776  7776 I bluedroid-qcom: get_profile_interface handsfree
08-16 17:45:41.627  7776  7776 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 17:45:41.627   311   311 V AudioPolicyService: registerClient() client 0xb558a600, uid 1002
08-16 17:45:41.628   311  1407 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 17:45:41.628   311  1407 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 17:45:41.628   311  1407 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 17:45:41.628  7776  7776 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 17:45:41.628   311  1406 V AudioFlinger: registerClient() client 0xb1433f88, pid 7776
08-16 17:45:41.629   311  1401 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:41.629   311  1401 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:41.629  3504  3520 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:41.629  3504  3520 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:41.629  7776  7791 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:41.629  7776  7791 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
,08-16 17:45:41.629  7776  7776 V ToneGenerator: Create Track: 0xb4928080
08-16 17:45:41.629  7776  7776 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 17:45:41.630  7776  7776 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 17:45:41.630  1044  1059 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:41.630  1044  1059 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:41.630   311  1406 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 17:45:41.630   311  1406 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 17:45:41.630   311  1406 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 17:45:41.630  1613  1630 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:41.630   311  1406 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 17:45:41.630  1613  1630 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:41.631   311  1402 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:41.631   311  1402 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:41.631  7776  7792 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:41.631  7776  7792 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 17:45:41.631  3504  3519 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:41.631  3504  3519 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:41.631  1613  1630 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:41.631  1613  1630 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:41.631  1044  1584 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:41.632  1044  1584 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:41.632  1862  1878 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 17:45:41.632  1862  1878 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 17:45:41.632  1862  1878 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 17:45:41.632  1862  1878 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 17:45:41.632   311  2160 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 17:45:41.633   311  1407 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 17:45:41.633   311  1407 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 17:45:41.633   311  1407 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 17:45:41.633   311  1407 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 17:45:41.633  7776  7776 V AudioSystem: getLatency() output 2, latency 50
08-16 17:45:41.633  7776  7776 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 17:45:41.633  7776  7776 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 17:45:41.634   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 17:45:41.634   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 17:45:41.634   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 17:45:41.634   311   311 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 17:45:41.634   311   311 V AudioFlinger: createTrack() lSessionId: 23
08-16 17:45:41.635  7776  7776 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 17:45:41.636   311   311 V AudioFlinger: acquiring 23 from 7776, for 7776
08-16 17:45:41.636   311   311 V AudioFlinger:  added new entry for 23
08-16 17:45:41.636  7776  7776 V Tone,Generator: ToneGenerator INIT OK, time: 229538
08-16 17:45:41.636  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:41.637  7776  8059 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 17:45:41.637  7776  8059 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 17:45:41.637  7776  8059 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 17:45:41.637  7776  8059 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 17:45:41.637   311  2159 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7776
08-16 17:45:41.638   311  2159 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 17:45:41.638   311  2159 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 17:45:41.638   311  2159 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 17:45:41.638   311  2159 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 17:45:41.638   311  2159 V voice   : voice_set_parameters: exit with code(0)
08-16 17:45:41.638   311  2159 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 17:45:41.638   311  2159 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 17:45:41.638   311  2159 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 17:45:41.638   311  2159 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 17:45:41.638   311  2159 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 17:45:41.638   311  2159 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 17:45:41.638  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:41.639  7776  8059 V ToneGenerator: ToneGenerator destructor
08-16 17:45:41.639  7776  8059 V ToneGenerator: stopTone
08-16 17:45:41.639  7776  8059 V ToneGenerator: Delete Track: 0xb4928080
08-16 17:45:41.640   311  1406 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 17:45:41.640   311  1406 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 17:45:41.640   311  1228 V AudioPolicyService: AudioCommandThread() waking up
08-16 17:45:41.640   311  1228 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 17:45:41.640   311  1228 V AudioPolicyManager: releaseOutput() 2
08-16 17:45:41.640   311  1228 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 17:45:41.640   311  1406 V AudioFlinger: PlaybackThread::Track destructor
08-16 17:45:41.641   311  1406 V AudioFlinger: removeClient_l() pid 7776, calling pid 311
08-16 17:45:41.641  7776  8059 V AudioTrack: ~AudioTrack, releasing session id from 7776 on behalf of 7776
08-16 17:45:41.641   311   311 V AudioFlinger: releasing 23 from 7776 for 7776
08-16 17:45:41.641   311   311 V AudioFlinger:  decremented refcount to 0
08-16 17:45:41.641   311   311 V AudioFlinger: purging stale effects
08-16 17:45:41.641  7776  7776 D A2dpService: Received start request. Starting profile...
08-16 17:45:41.642  7776  7776 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 17:45:41.644  7776  7776 V Avrcp   : make
08-16 17:45:41.644  7776  7776 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 17:45:41.644  7776  7776 I bluedroid-qcom: get_profile_interface avrcp
,08-16 17:45:41.658  7776  7776 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 17:45:41.660  7776  7776 E AudioManager: No RCC entry present to update
08-16 17:45:41.660  7776  7776 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 17:45:41.664  7776  7776 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 17:45:41.665  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 17:45:41.665  7776  7776 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-16 17:45:41.671  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 17:45:41.806  1044  1897 V SIM_STK : Menu title from STK is T-Mobile
08-16 17:45:41.806  1044  1897 V SIM_STK : Menu title from STK is T-Mobile
,08-16 17:45:41.950  1044  1059 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 17:45:41.962  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-16 17:45:41.968  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 17:45:41.969  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-16 17:45:41.969  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 17:45:41.969  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 17:45:41.970  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 17:45:41.970  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 17:45:41.970  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 17:45:41.970  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 17:45:41.970  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 17:45:41.970  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-16 17:45:41.973  7776  7776 I BluetoothA2dpServiceJni: classInitNative
,08-16 17:45:41.974  7776  7776 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:45:41.974  7776  7776 D A2dpStateMachine: make
08-16 17:45:41.977  7776  7776 I bluedroid-qcom: get_profile_interface a2dp
08-16 17:45:41.977  7776  8071 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 17:45:41.980  7776  7776 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:45:41.980  7776  7776 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 17:45:41.981  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:41.982  7776  8070 D A2dpStateMachine: Enter Disconnected: -2
08-16 17:45:41.984  7776  7776 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:45:41.987  7776  7776 D HidService: Received start request. Starting profile...
,08-16 17:45:41.987  7776  7776 I bluedroid-qcom: get_profile_interface hidhost
08-16 17:45:41.987  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
,08-16 17:45:41.989  7776  7776 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:45:41.991  7776  7776 D HealthService: Received start request. Starting profile...
,08-16 17:45:41.993  7776  7776 I bluedroid-qcom: get_profile_interface health
08-16 17:45:41.993  7776  7776 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 17:45:41.994  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:41.995  7776  7776 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 17:45:41.997  7776  7776 D PanService: Received start request. Starting profile...
08-16 17:45:41.997  7776  7776 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:45:41.997  7776  7776 I bluedroid-qcom: get_profile_interface pan
08-16 17:45:42.006  7776  7776 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 17:45:42.006  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:42.008  7776  7776 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-16 17:45:42.017  7776  7776 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:45:42.017  7776  7776 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:45:42.018  7776  7776 D BtGatt.GattService: start()
08-16 17:45:42.018  7776  7776 I bluedroid-qcom: get_profile_interface gatt
08-16 17:45:42.018  7776  7776 D BtGatt.AdvertiseManager: advertise manager created
08-16 17:45:42.037  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
,08-16 17:45:42.046  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:42.047  7776  7776 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 17:45:42.050  7776  7776 V BluetoothMapService: BluetoothMapBinder()
08-16 17:45:42.051  7776  7776 D BluetoothMapService: Received start request. Starting profile...
08-16 17:45:42.051  7776  7776 D BluetoothMapService: start()
,08-16 17:45:42.212  1044  1968 I art     : Explicit concurrent mark sweep GC freed 27603(1343KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.210ms total 157.380ms
,08-16 17:45:42.216  7776  7776 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 17:45:42.216  7776  7776 D BluetoothMapEmailAppObserver: createReceiver()
08-16 17:45:42.218  7776  7776 D BluetoothMapEmailAppObserver: initObservers()
08-16 17:45:42.218  7776  7776 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 17:45:42.243  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:42.244  7776  7776 D HeadsetStateMachine: Proxy object connected
08-16 17:45:42.246  7776  7776 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 17:45:42.246  7776  7776 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-16 17:45:42.249  7776  8059 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 17:45:42.250  7776  8059 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:45:42.250  7776  8059 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 17:45:42.255  7776  7776 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:42.259  7776  7776 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 17:45:42.261  7776  7776 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:42.269  7776  7776 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:42.273  7776  7776 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:42.274  7776  7776 V PanService: [BTUI] SIM Extra State :ABSENT
,08-16 17:45:42.278  7776  7776 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 17:45:42.282  7776  7776 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 17:45:42.282  7776  7776 V BluetoothMapService: Handler(): got msg=1
08-16 17:45:42.283  7776  7776 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 17:45:42.283  7776  8048 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 17:45:42.284  7776  7776 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:45:42.284  7776  7776 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:45:42.284  7776  8048 I bluedroid-qcom: enable
08-16 17:45:42.284  7776  7776 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:42.284  7776  7776 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 17:45:42.285  7776  8048 I bt_hci_bdroid: init
08-16 17:45:42.285  7776  8083 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 17:45:42.285  7776  8083 I bt-btu  : btu_task pending for preload complete event
08-16 17:45:42.286  7776  8048 I bt_vendor: bt-vendor : init
08-16 17:45:42.287  7776  8048 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 17:45:42.287  7776  8048 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 17:45:42.287  7776  8048 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
,08-16 17:45:42.277  8086  8086 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:42.277  8086  8086 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:42.287  7776  8048 D bt_userial_mct: userial_init
08-16 17:45:42.287  7776  8048 D bt_hci_bdroid: set_power 1
08-16 17:45:42.287  7776  8048 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 17:45:42.287  7776  8048 I bt_vendor: Starting hciattach daemon
08-16 17:45:42.287  7776  8048 I bt_vendor: try to set true
08-16 17:45:42.322  8087  8087 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 17:45:42.441  8093  8093 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 17:45:42.466  8094  8094 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 17:45:42.492  8096  8096 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 17:45:42.504  8097  8097 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 17:45:42.517  8098  8098 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 17:45:42.534  8099  8099 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 17:45:42.560  8104  8104 I libmdmdetect: ESOC framework not supported
08-16 17:45:42.562  8104  8104 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 17:45:42.571  8104  8104 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 17:45:42.571  8104  8104 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 17:45:42.571  8104  8104 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 17:45:42.571  8104  8104 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 17:45:42.571  8104  8104 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 17:45:42.571  8104  8104 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 17:45:42.572  8104  8104 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 17:45:42.618  8104  8105 E QC-QMI  : qmi_client [8104] 15: failed to locate client data
08-16 17:45:42.619   475   475 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 17:45:42.619   475   475 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 17:45:42.673  8109  8109 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 17:45:42.689  8110  8110 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 17:45:42.705  7776  8048 I bt_vendor: bluetooth satus is on
08-16 17:45:42.705  7776  8048 D bt_hci_bdroid: preload
,08-16 17:45:42.708  7776  8085 D bt_userial_mct: userial_open(port:0)
08-16 17:45:42.708  7776  8085 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 17:45:42.711  7776  8085 I bt_vendor: Done intiailizing UART
08-16 17:45:42.712  7776  8085 I bt_vendor: Done intiailizing UART
08-16 17:45:42.712  7776  8085 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 17:45:42.713  7776  8085 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 17:45:42.713  7776  8083 I bt-btu  : btu_task received preload complete event
08-16 17:45:42.713  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 17:45:42.713  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 17:45:42.715  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 17:45:42.718  7776  8112 D bt_userial_mct: Entering userial_read_thread()
,08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:45:42.722  7776  8083 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 17:45:42.778  7776  8083 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 17:45:42.778  7776  8083 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa023b061 
08-16 17:45:42.778  7776  8083 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa023b061 
,08-16 17:45:42.812  7776  8052 E bt-btif : Calling BTA_HhEnable
08-16 17:45:42.812  7776  8052 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 17:45:42.813  7776  8052 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 17:45:42.819  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 17:45:42.819  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 17:45:42.819  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 17:45:42.819  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 17:45:42.819  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 17:45:42.822  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 17:45:42.823  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 17:45:42.823  7776  8052 D BluetoothAdapterProperties: Name is: G3
08-16 17:45:42.826  7776  8052 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:45:42.826  7776  8052 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:45:42.827  7776  8052 D bt_hci_bdroid: postload
08-16 17:45:42.829  7776  8085 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 17:45:42.832  7776  8085 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 17:45:42.832  7776  8083 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 17:45:42.833  7776  8052 D bte_conf: Device ID record 1 : primary
08-16 17:45:42.833  7776  8052 D bte_conf:   vendorId            = 00c4
08-16 17:45:42.833  7776  8052 D bte_conf:   vendorIdSource      = 0001
08-16 17:45:42.833  7776  8052 D bte_conf:   product             = 13a1
08-16 17:45:42.833  7776  8052 D bte_conf:   version             = 1000
08-16 17:45:42.833  7776  8052 D bte_conf:   clientExecutableURL = 
08-16 17:45:42.833  7776  8052 D bte_conf:   serviceDescription  = 
08-16 17:45:42.833  7776  8052 D bte_conf:   documentationURL    = 
08-16 17:45:42.833  7776  8052 D bte_conf: bte_load_did_conf no section named DID2.
08-16 17:45:42.837  7776  8085 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 17:45:42.838  7776  8048 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 17:45:42.838  7776  8048 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:45:42.838  7776  8048 D BluetoothAdapterProperties: State =  11
08-16 17:45:42.838  7776  8048 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 17:45:42.839  7776  8048 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 17:45:42.839  7776  8048 D BluetoothAdapterProperties: Setting state to 12
08-16 17:45:42.839  7776  8048 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 17:45:42.839  7776  8052 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 17:45:42.840  7776  8052 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:45:42.827  8114  8114 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 17:45:42.827  8114  8114 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:42.855  1044  1106 D BluetoothManagerService: Message: 60
08-16 17:45:42.855  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 17:45:42.855  1044  1106 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 17:45:42.855  1044  1106 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:45:42.857  7776  8085 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 17:45:42.859  7776  8112 E bt_mct  : hci lib postload completed
08-16 17:45:42.862  7776  8048 I BluetoothAdapterState: Entering On State
08-16 17:45:42.864  1862  1877 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:45:42.868  7776  8048 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 17:45:42.868  7776  8048 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 17:45:42.868  7776  8048 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 17:45:42.871  7776  8048 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-16 17:45:42.874  7776  8083 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:42.874  7776  8083 W bt-smp  : Plain text(LSB ~ MSB) = a5 22 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:42.876  7776  8083 W bt-smp  : Encrypted text(LSB ~ MSB) = 85 71 5f 63 f9 05 a8 69 a4 b1 20 a6 b3 c1 c8 3c 
08-16 17:45:42.876  7776  8083 W bt-btm  : Stopping oneshot timer
08-16 17:45:42.901  7776  8052 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:45:42.901  7776  8052 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 17:45:42.904  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:42.904  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:42.904  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:42.904  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:42.904  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:42.904  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:42.904  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:42.904  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:42.904  7776  8083 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:42.904  7776  8083 W bt-smp  : Plain text(LSB ~ MSB) = 57 ee 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:42.904  7776  8083 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 8c e5 fb 13 c7 d0 b1 8e 0b 35 f0 76 d6 e7 79 
08-16 17:45:42.905  7776  8083 W bt-btm  : Stopping oneshot timer
08-16 17:45:42.912  7776  8048 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 17:45:42.913  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:45:42.916  1044  1044 D BluetoothHeadset: Proxy object connected
08-16 17:45:42.920  7776  8083 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:42.920  7776  8083 W bt-smp  : Plain text(LSB ~ MSB) = 22 73 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:42.920  7776  8083 W bt-smp  : Encrypted text(LSB ~ MSB) = d7 db 34 ff 35 8c 3c 11 0d 9b 31 98 54 b6 ac fc 
08-16 17:45:42.920  7776  8083 W bt-btm  : Stopping oneshot timer
08-16 17:45:42.938  1862  1862 D BluetoothHeadset: Proxy object connected
,08-16 17:45:42.941  6989  7102 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:45:42.943  6989  7012 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:45:42.943  6989  7012 D BluetoothPan: onBluetoothStateChange call bindService
08-16 17:45:42.948  7776  8083 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:42.948  7776  8083 W bt-smp  : Plain text(LSB ~ MSB) = 35 58 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:42.948  7776  8083 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d a4 a2 1a c0 48 f8 3f db d1 eb 85 48 42 3d e9 
08-16 17:45:42.948  7776  8083 W bt-btm  : Stopping oneshot timer
08-16 17:45:42.970  8120  8120 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-16 17:45:42.976  7776  8083 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 17:45:42.976  7776  8083 W bt-smp  : Plain text(LSB ~ MSB) = d2 e2 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 17:45:42.976  7776  8083 W bt-smp  : Encrypted text(LSB ~ MSB) = d5 72 d8 6f b0 c4 ec a0 32 bb 19 09 a7 6b c1 a9 
08-16 17:45:42.976  7776  8083 W bt-btm  : Stopping oneshot timer
08-16 17:45:42.976  1044  1106 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:45:42.979  1044  1044 D BluetoothA2dp: Proxy object connected
08-16 17:45:42.981  6989  7012 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:45:42.983  6989  6989 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:45:42.983  6989  6989 D PanProfile: Bluetooth service connected
08-16 17:45:42.986  1862  2466 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:45:42.998  1862  1862 D BluetoothHeadset: Proxy object connected,
08-16 17:45:43.003  6989  7011 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:45:43.004  6989  6989 D BluetoothHeadset: Proxy object connected
,08-16 17:45:43.004  6989  6989 D HeadsetProfile: Bluetooth service connected
08-16 17:45:43.008  6989  7012 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:45:43.009  6989  6989 D BluetoothA2dp: Proxy object connected
08-16 17:45:43.009  6989  6989 D A2dpProfile: Bluetooth service connected
08-16 17:45:43.011  6989  7102 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:45:43.012  6989  6989 D BluetoothInputDevice: Proxy object connected
08-16 17:45:43.012  6989  6989 D HidProfile: Bluetooth service connected
08-16 17:45:43.016  1862  2713 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:45:43.019  6989  6989 D BluetoothMap: Proxy object connected
08-16 17:45:43.019  6989  6989 D MapProfile: Bluetooth service connected
08-16 17:45:43.019  6989  6989 D BluetoothMap: getConnectedDevices()
08-16 17:45:43.020  1862  1862 D BluetoothHeadset: Proxy object connected
08-16 17:45:43.021  7776  7791 V BluetoothMapService: getConnectedDevices()
08-16 17:45:43.021  1044  1106 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 17:45:43.021  1044  1106 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 17:45:43.023  1951  1951 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:43.023  1951  2134 D LGBluetoothAPIService: Message: 1
08-16 17:45:43.023  1613  1613 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 17:45:43.023  1951  2134 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 17:45:43.031  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:45:43.036  1951  2134 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 17:45:43.037  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 17:45:43.037  1044  1106 D BluetoothManagerService: Message: 40
08-16 17:45:43.037  1044  1106 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 17:45:43.039  6989  6989 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 17:45:43.041  7776  7776 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:43.041  6989  6989 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 17:45:43.041  7776  7776 D BluetoothMapService: STATE_ON
08-16 17:45:43.044  7776  7776 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 17:45:43.045  7776  7776 D LGBluetoothAPIServer: [BTUI] onBind()
,08-16 17:45:43.049  1951  1951 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 17:45:43.050  1951  2134 D LGBluetoothAPIService: Message: 100
08-16 17:45:43.050  1951  2134 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 17:45:43.053  6989  6989 D DockEventReceiver: finishStartingService: stopping service
08-16 17:45:43.066  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:43.067  7776  7776 V BluetoothPbapService: Pbap Service onCreate
08-16 17:45:43.067  7776  7776 V BluetoothPbapService: Starting PBAP service
,08-16 17:45:43.068  7776  7776 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 17:45:43.068  7776  7776 V BluetoothMapService: Handler(): got msg=1
08-16 17:45:43.069  7776  7776 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 17:45:43.069  7776  7776 V BluetoothPbapService: Pbap Service onBind
08-16 17:45:43.070  7776  7776 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:43.070  6989  6989 D BluetoothPbap: Proxy object connected
08-16 17:45:43.070  6989  6989 D PbapServerProfile: Bluetooth service connected
08-16 17:45:43.071  7776  7776 V BluetoothPbapService: state: 12
08-16 17:45:43.071  7776  7776 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 17:45:43.071  7776  7776 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:43.071  7776  7776 V BluetoothPbapReceiver: ***********state = 12
08-16 17:45:43.072  7776  8140 D BluetoothMapMasInstance: MAS initSocket()
08-16 17:45:43.073  7776  7776 V BluetoothPbapService: Handler(): got msg=1
08-16 17:45:43.073  7776  8140 D BluetoothMapMasInstance:   masId = 00
08-16 17:45:43.073  7776  8140 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 17:45:43.073  7776  8140 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 17:45:43.073  7776  8140 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 17:45:43.074  7776  7776 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 17:45:43.074  2214  2214 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:45:43.075  2214  2214 D c       : Getting all permits...
08-16 17:45:43.075  2214  2214 D a       : Opening database...
08-16 17:45:43.075  1044  2005 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:43.076  7776  8141 V BluetoothPbapService: Pbap Service initSocket
08-16 17:45:43.076  1044  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:43.076  7776  8140 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:43.078  7776  8141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:43.078  7776  8052 D BluetoothAdapterProperties: Scan Mode:21
,08-16 17:45:43.079  7776  8052 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 17:45:43.080  7776  8141 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-16 17:45:43.080  7776  8141 V BluetoothPbapService: Succeed to create listening socket 
08-16 17:45:43.080  7776  8141 V BluetoothPbapService: Accepting socket connection...
08-16 17:45:43.080  7776  8140 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=75
08-16 17:45:43.080  7776  8140 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 17:45:43.081  7776  8140 D BluetoothMapMasInstance: Accepting socket connection...
08-16 17:45:43.082  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:43.084  2214  2214 D a       : Opening database auth.proximity.permit_store...
08-16 17:45:43.085  2214  2214 D a       : Closing database...
08-16 17:45:43.097  6989  6989 D BluetoothPermissionRequest: onReceive
,08-16 17:45:43.099  6989  6989 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 17:45:43.101  6989  6989 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 17:45:43.104  7776  7776 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 17:45:43.105  7776  7776 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 17:45:43.112  7776  7776 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 17:45:43.132  7776  7776 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 17:45:43.132  7776  7776 V BtOppService: onCreate
,08-16 17:45:43.137  7776  7776 V BluetoothOppNotification: send message
08-16 17:45:43.141  7776  7776 V BtOppService: Starting RfcommListener
08-16 17:45:43.146  7776  7776 W art     : No such thread id for suspend: 30
,08-16 17:45:43.146  7776  7776 D BluetoothOppPreference: Dumping Names:  
08-16 17:45:43.146  7776  7776 D BluetoothOppPreference: {}
08-16 17:45:43.146  7776  7776 D BluetoothOppPreference: Dumping Channels:  
08-16 17:45:43.146  7776  7776 D BluetoothOppPreference: {}
08-16 17:45:43.147  7776  7776 V BtOppService: onStartCommand
08-16 17:45:43.151  7776  7776 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:43.151  7776  7776 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 17:45:43.154  7776  8147 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 17:45:43.155  7776  7776 V BluetoothOppNotification: new notify threadi!
08-16 17:45:43.155  7776  7776 V BluetoothOppNotification: send delay message
08-16 17:45:43.156  7776  7776 V BtOppService: start RfcommListener
08-16 17:45:43.158  7776  8144 V BtOppService: Deleted complete outbound shares, number =  0
,08-16 17:45:43.159  7776  7776 V BtOppService: RfcommListener started
08-16 17:45:43.161  7776  8144 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 17:45:43.162  7776  8144 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 17:45:43.162  7776  8147 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 17:45:43.163  7776  8148 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 17:45:43.164  7776  8144 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8a4c182 on behalf of 
08-16 17:45:43.165  7776  8147 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@da83093 on behalf of 
08-16 17:45:43.166  7776  8149 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 17:45:43.166  1044  1792 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:43.167  7776  8149 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:43.168  7776  8149 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=73
08-16 17:45:43.168  7776  8149 V BtOppRfcommListener: Started RFCOMM listener....
08-16 17:45:43.168  7776  8149 I BtOppRfcommListener: Accept thread started.
08-16 17:45:43.169  7776  8149 V BtOppRfcommListener: Accepting connection...
08-16 17:45:43.170  7776  8148 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@341ba8d0 on behalf of 
08-16 17:45:43.171  7776  8148 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 17:45:43.172  7776  8147 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 17:45:43.173  7776  8148 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-16 17:45:43.176  7776  8148 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e1670c9 on behalf of 
08-16 17:45:43.177  7776  8148 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 17:45:43.179  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
08-16 17:45:43.179  7776  7776 V BluetoothFtpService: Ftp Service onCreate
08-16 17:45:43.179  7776  7776 I BluetoothFtpService: Ftp Service onCreate
08-16 17:45:43.179  7776  8148 V BluetoothOppNotification: outbound notification was removed.
08-16 17:45:43.179  7776  7776 V BluetoothFtpService: Ftp Service onStartCommand
08-16 17:45:43.179  7776  7776 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:43.179  7776  8148 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 17:45:43.179  7776  7776 V BluetoothFtpService: Starting Listening on sockets
08-16 17:45:43.180  7776  7776 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 17:45:43.180  7776  7776 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 17:45:43.180  7776  7776 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 17:45:43.180  7776  7776 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:43.180  7776  7776 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 17:45:43.180  7776  7776 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 17:45:43.182  7776  7776 V BtOppService: ContentObserver received notification
08-16 17:45:43.183  7776  7776 V BtOppService: ContentObserver received notification
08-16 17:45:43.183  7776  7776 V BluetoothFtpService: Handler(): got msg=1
08-16 17:45:43.183  7776  7776 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 17:45:43.183  7776  7776 V BluetoothFtpService: Ftp Service initSocket
08-16 17:45:43.185  7776  8148 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c1b42ef on behalf of 
08-16 17:45:43.186  7776  8148 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 17:45:43.188  7776  8150 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 17:45:43.188  7776  8148 V BluetoothOppNotification: inbound notification was removed.
08-16 17:45:43.188  7776  8150 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 17:45:43.188  7776  8148 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 17:45:43.190  1044  1933 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:43.191  7776  7776 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:43.191  7776  8150 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19da81fc on behalf of 
08-16 17:45:43.192  7776  8150 V BluetoothOppNotification: update too frequent, put in queue
08-16 17:45:43.193  7776  7776 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-16 17:45:43.193  7776  8148 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a8c5085 on behalf of 
08-16 17:45:43.193  7776  7776 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 17:45:43.195  7776  8152 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-16 17:45:43.196  7776  8150 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 17:45:43.214  7776  7776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38cc1a41
,08-16 17:45:43.214  7776  7776 V BluetoothSapService: Sap Service onCreate
,08-16 17:45:43.217  7776  7776 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:45:43.217  7776  7776 V BluetoothSapService: state: 12
08-16 17:45:43.218  7776  7776 V BluetoothSapService: Starting SAP server process
08-16 17:45:43.219  7776  7776 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 17:45:43.222  7776  8154 V BluetoothSapService: Sap Service initRfcommSocket
08-16 17:45:43.207  8153  8153 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:43.207  8153  8153 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:43.223  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:43.223  7776  8154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:45:43.225  7776  8154 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-16 17:45:43.225  7776  8154 V BluetoothSapService: Succeed to create listening socket 
08-16 17:45:43.225  7776  8154 V BluetoothSapService: Accepting socket connection...
08-16 17:45:43.238  8153  8153 V BT_SAP  : Event pipe created
08-16 17:45:43.239  8153  8153 V BT_SAP  : create_server_socket qcom.sap.server
08-16 17:45:43.239  8153  8153 V BT_SAP  : created socket fd 6
,08-16 17:45:43.470  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:43.470  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:43.470  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:43.470  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:45:43.470  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:43.470  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:43.470  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:43.470  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:45:43.473  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:43.476  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:43.476  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12e9480f added. We now have 8 listener(s)
08-16 17:45:43.476  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:43.480  1044  2023 D WifiServiceImplEx: setWifiEnabled: false pid=6813, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 17:45:43.480  1044  2023 D WifiService: setWifiEnabled: false pid=6813, uid=10118
08-16 17:45:43.480  1044  2023 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 17:45:43.487  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:43.489  1044  2042 D WifiServiceImplEx: setWifiEnabled: true pid=6813, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 17:45:43.490  1044  2042 D WifiService: setWifiEnabled: true pid=6813, uid=10118
08-16 17:45:43.491  1044  2042 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:45:43.521  1044  1449 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-16 17:45:43.521  1044  1449 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 17:45:43.522  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 17:45:43.522  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 17:45:43.523  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 17:45:43.530  1044  1449 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 17:45:43.530  1044  1449 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 17:45:43.531  1044  1449 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 17:45:43.531  1044  1449 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 17:45:43.531  1044  1449 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 17:45:43.531  1044  1449 E WifiHW  : unknown target_country: EU , set to default
08-16 17:45:43.531  1044  1449 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 17:45:43.531  1044  1449 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 17:45:43.531  1044  1449 I WifiUtil: gEnableBmps=1
,08-16 17:45:44.119  1044  1106 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-16 17:45:44.119  1044  1106 D Tethering: InitialState.processMessage what=4
08-16 17:45:44.120  1044  1106 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 17:45:44.124   307   904 D SoftapController: Softap fwReload - Ok
08-16 17:45:44.146  1044  1449 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (605ms)
,08-16 17:45:44.156   307   904 D CommandListener: Setting iface cfg
08-16 17:45:44.157   307   904 D CommandListener: Trying to bring down wlan0
08-16 17:45:44.160   307   904 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:45:44.165  1044  1449 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 17:45:44.168  7776  7776 V BluetoothOppNotification: new notify threadi!
,08-16 17:45:44.168  7776  7776 V BluetoothOppNotification: send delay message
,08-16 17:45:44.172  1044  1449 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:45:44.172  1044  1449 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:45:44.172  1044  1449 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:45:44.174  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 17:45:44.174  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 17:45:44.174  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 17:45:44.174  6989  6989 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-16 17:45:44.157  8179  8179 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:44.157  8179  8179 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 17:45:44.198  8179  8179 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 17:45:44.201  7776  8180 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-16 17:45:44.209  1044  1449 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 17:45:44.210  1044  1449 D WifiMonitor: connecting to supplicant
08-16 17:45:44.217  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 17:45:44.221  6989  6989 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 17:45:44.221  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 17:45:44.221  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 17:45:44.221  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 17:45:44.221  6989  6989 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 17:45:44.222  6989  6989 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 17:45:44.225  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 17:45:44.227  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:44.229  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 17:45:44.231  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:44.234  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 17:45:44.234  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 17:45:44.234  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 17:45:44.234  6989  6989 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 17:45:44.235  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 17:45:44.235  8179  8179 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 17:45:44.236  6989  6989 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 17:45:44.236  8179  8179 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 17:45:44.236  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 17:45:44.236  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 17:45:44.236  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 17:45:44.236  6989  6989 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 17:45:44.236  6989  6989 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 17:45:44.239  7776  8180 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ec67001 on behalf of 
08-16 17:45:44.241  7776  8180 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 17:45:44.242  7776  8180 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 17:45:44.243  7776  8180 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12642ea6 on behalf of 
08-16 17:45:44.244  7776  8180 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 17:45:44.246  7776  8180 V BluetoothOppNotification: outbound notification was removed.
08-16 17:45:44.246  7776  8180 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 17:45:44.248  7776  8180 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1542a0e7 on behalf of 
08-16 17:45:44.249  7776  8180 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-16 17:45:44.254  7776  8180 V BluetoothOppNotification: inbound notification was removed.
08-16 17:45:44.254  7776  8180 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 17:45:44.255  7776  8180 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@340f1494 on behalf of 
08-16 17:45:44.287  1044  1059 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8192 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-16 17:45:44.316  8179  8179 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:45:44.362  8179  8179 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 17:45:44.368  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 17:45:44.368  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 17:45:44.369  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 17:45:44.369  1044  1449 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 17:45:44.370  1044  1449 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-16 17:45:44.370  1044  1449 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:44.370  1044  1449 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 17:45:44.371  1044  1449 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 17:45:44.371  1044  1449 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 17:45:44.371  1044  1449 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 17:45:44.371  1044  1449 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 17:45:44.380  8179  8179 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 17:45:44.381  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 17:45:44.381  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 17:45:44.381  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 17:45:44.381  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 17:45:44.381  1044  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 17:45:44.381  1044  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-16 17:45:44.416  1044  1629 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8216 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 17:45:44.419  1044  1449 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 17:45:44.419  1044  1449 E WifiStateMachine: useWiFiOffloading() : false
08-16 17:45:44.419  1044  1449 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 17:45:44.419  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.419  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.419  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.419  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.419  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 17:45:44.420  1044  1449 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 17:45:44.421  1044  1449 D WifiNative-wlan0: SET update_config 1: returned true
08-16 17:45:44.421  1044  1449 D WifiConfigStore: Loading config and enabling all networks 
08-16 17:45:44.421  1044  1449 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 17:45:44.421  1951  1951 D WfdService: Waiting for WifiP2p enabling
08-16 17:45:44.422  1044  1449 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 17:45:44.422  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:44.425  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 17:45:44.426  1044  1479 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 17:45:44.429  8192  8214 W FormManager: Network not available. Please check & try again.
,08-16 17:45:44.432  1044  1449 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 17:45:44.432  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:44.432  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:44.432  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:44.432  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:44.432  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:44.432  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:44.432  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:44.432  6813  6813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:44.434  6813  6813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:44.439  1044  1449 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 17:45:44.439  1044  1449 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:45:44.439  1044  1449 D WifiStateMachine: enableVerboseLogging : level 2
08-16 17:45:44.439  1044  1449 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 17:45:44.440  1044  1449 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 17:45:44.440  1044  1449 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 17:45:44.440  1044  1449 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 17:45:44.440  1044  1449 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 17:45:44.440  1044  1449 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 17:45:44.440  1044  1449 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 17:45:44.441  1044  1449 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 17:45:44.442  1044  1449 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-16 17:45:44.443  1044  1449 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 17:45:44.443  1044  1449 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 17:45:44.443  1044  1449 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 17:45:44.443  1044  1449 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 17:45:44.444  1044  1449 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 17:45:44.444  8192  8215 V FormManager: Network unavailable.
08-16 17:45:44.444  1044  1449 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:45:44.444  1044  1449 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
,08-16 17:45:44.445  1951  1951 D WfdsService: Supplicant Connection state is changed : true
08-16 17:45:44.445  1951  2315 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 17:45:44.445  1951  2315 D WfdsService: Set the WFDS Monitor: true
08-16 17:45:44.445  1951  2315 D WfdsMonitor: WfdsMonitorThread create
08-16 17:45:44.445  1951  2315 D WfdsMonitor: WFDS Monitor is created and started
08-16 17:45:44.445  1951  2315 D WfdsService: WiFi: Supplicant connection re-established
08-16 17:45:44.445  1044  1449 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 17:45:44.445  1044  1449 D WifiNative-HAL: Setting external_sim to 1
08-16 17:45:44.445  1044  1449 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 17:45:44.446  1044  1449 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 17:45:44.446  1044  1449 I WifiNative-HAL: startHal
08-16 17:45:44.446  1044  1449 D wifi    : setting scan oui 0xaf669e00
08-16 17:45:44.446  7829  7829 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.446  1044  1449 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:45:44.446  1044  1449 I WifiNative-HAL: startHal
08-16 17:45:44.446  1044  1449 D wifi    : setting scan oui 0xaf669e00
08-16 17:45:44.446  1044  1449 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 17:45:44.446  1951  8228 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 17:45:44.447  1951  8228 E CtrlSupplicant: Succeed to open control connection
08-16 17:45:44.447  1044  1449 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 17:45:44.447  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 17:45:44.447  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 17:45:44.447  1951  8228 E CtrlSupplicant: Succeed to open monitor connection
08-16 17:45:44.447  1951  8228 D WfdsMonitor: Supplicant connection established
08-16 17:45:44.447  8192  8215 V FormManager: Network unavailable.
08-16 17:45:44.448  1951  2315 D WfdsService: Connected to the supplicant for wfds
08-16 17:45:44.448  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 17:45:44.448  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 17:45:44.448  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 17:45:44.448  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 17:45:44.448  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 17:45:44.449  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 17:45:44.449  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 17:45:44.449  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 17:45:44.449  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 17:45:44.449  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 17:45:44.449  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 17:45:44.449  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 17:45:44.450  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 17:45:44.450  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 17:45:44.450  8179  8179 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 17:45:44.450  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 17:45:44.450  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 17:45:44.450  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 17:45:44.450  1044  1449 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 17:45:44.452  1044  1449 E WifiNative: : [232,340,599 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 17:45:44.,452  1044  1449 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 17:45:44.453  1044  1449 D WifiNative-wlan0: RECONNECT: returned true
08-16 17:45:44.453  1044  1449 D WifiNative-wlan0: doString: [STATUS]
08-16 17:45:44.453  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 17:45:44.453  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 17:45:44.453  1044  1449 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-16 17:45:44.454  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:45:44.454  1044  1449 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:45:44.454  1044  1400 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.456   307   904 D CommandListener: Setting iface cfg
08-16 17:45:44.456   307   904 D CommandListener: Trying to bring up p2p0
08-16 17:45:44.457  1044  1400 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 17:45:44.457  1044  1400 D LGWifiP2pService: P2pEnablingState
08-16 17:45:44.457  1044  1400 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.457  1044  1400 D LGWifiP2pService: P2p socket connection successful
08-16 17:45:44.457  1044  1400 D LGWifiP2pService: P2pEnabledState
08-16 17:45:44.457  1044  1400 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 17:45:44.459  1044  1400 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 17:45:44.459  1951  1951 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 17:45:44.459  1951  1951 D WfdsService: WifiP2pState is changed : true
08-16 17:45:44.459  1951  2315 D WfdsService: Receive the WFDS_ENABLE Method
08-16 17:45:44.459  1951  2315 D WfdsService: Set the WFDS Monitor: true
08-16 17:45:44.459  1951  2315 D WfdsService: Connected to the supplicant for wfds
08-16 17:45:44.459  1951  2315 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 17:45:44.459  8179  8179 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 17:45:44.459  1951  2315 D WfdsService: selectPreferredScanChannel [36]
08-16 17:45:44.459  1951  2315 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 17:45:44.459  1044  1400 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 17:45:44.460  1044  1400 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 17:45:44.460  1044  1400 D WifiNative-p2p0: SET device_name G3: returned true
08-16 17:45:44.460  1044  1400 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 17:45:44.460  1044  1400 D LGWifiP2pService: before postfix = G3
08-16 17:45:44.460  1044  1400 D WifiServerServiceExt: postfix byte check : 2
08-16 17:45:44.460  1044  1400 D LGWifiP2pService: after postfix = G3
08-16 17:45:44.460  1044  1400 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 17:45:44.460  1044  1400 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 17:45:44.460  1044  1400 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 17:45:44.461  1044  1400 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 17:45:44.461  1044  1400 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 17:45:44.461  1044  1400 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 17:45:44.461  1044  1400 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 17:45:44.461  1044  1400 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 17:45:44.461  1044  1400 D WifiNative-HAL: p2pGetDeviceAddress
08-16 17:45:44.461  1044  1400 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 17:45:44.461  1951  1951 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 17:45:44.462  1044  1400 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 17:45:44.462  1044  1400 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 17:45:44.462  1044  1400 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 17:45:44.462  1044  1400 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 17:45:44.462  1951  1951 D WfdsService: isConnected: false
08-16 17:45:44.462  1044  1400 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 17:45:44.462  1044  1400 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 17:45:44.462  1044  1449 E WifiStateMachine:  DisconnectedState CMD_SET,_OPERATIONAL_MODE 1 0
08-16 17:45:44.462  1044  1400 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 17:45:44.462  1044  1400 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 17:45:44.463  1044  1449 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 17:45:44.463  1044  1449 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 17:45:44.463  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 17:45:44.463  1044  1044 D RttService: SCAN_AVAILABLE : 3
08-16 17:45:44.463  1044  1449 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 17:45:44.464  1044  1566 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.464  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=232353  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 17:45:44.464  1044  1565 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.464  1044  1565 I WifiNative-HAL: startHal
08-16 17:45:44.465  1951  1951 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 17:45:44.465  1951  1951 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 17:45:44.465  1951  1951 D WfdsService: Update P2p Interface State: 3
,08-16 17:45:44.468  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:44.468  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:44.471  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.471  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.471  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 17:45:44.471  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:44.471  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=232361  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 17:45:44.476  1044  1449 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 17:45:44.476  1044  1449 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 17:45:44.476  1044  1449 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 17:45:44.476  1044  1449 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 17:45:44.476  1044  1400 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-16 17:45:44.477  8179  8179 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 17:45:44.477  1044  1400 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 17:45:44.477  1044  1565 D wifi    : getting scan capabilities on interface[1] = 0xaf669e00
08-16 17:45:44.477  1044  1565 D wifi    : failed to get capabilities : -3
08-16 17:45:44.477  1044  1565 E WifiScanningService: could not get scan capabilities
08-16 17:45:44.477  1044  1400 D LGWifiP2pService: InactiveState
08-16 17:45:44.477  1044  1400 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.477  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.477  1044  1400 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 17:45:44.478  1044  1449 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 17:45:44.478  1044  1449 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 17:45:44.478  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 17:45:44.479  1044  1449 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 17:45:44.479  1044  1449 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 17:45:44.479  8179  8179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 17:45:44.479  1951  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 17:45:44.479  8179  8179 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 17:45:44.479  8179  8179 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 17:45:44.479  8179  8179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.480  8179  8179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.480  1044  8213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 17:45:44.480  1044  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:44.481  1044  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:44.481  1044  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:44.481  1044  8213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:44.481  1044  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.481  1044  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.481  1044  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.481  1044  8213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:44.481  1044  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.481  1044  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.481  1044  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.481  1044  1400 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 17:45:44.481  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.481  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.481  1044  1400 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.481  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.481  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.481  1044  1400 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.482  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.482  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.482  1044  1400 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.482  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:45:44.482  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.482  1044  1400 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.482  1951  2315 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 17:45:44.482  1044  1044 E WifiServerServiceExt: No p2p device connected
08-16 17:45:44.483  1044  1449 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 17:45:44.483  1044  1449 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 17:45:44.484  1044  1449 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 17:45:44.484  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 17:45:44.484  1951  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:44.484  1951  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 17:45:44.484  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 17:45:44.485  8179  8179 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:44.485  8179  8179 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 17:45:44.485  8179  8179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 17:45:44.485  1044  1449 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 17:45:44.486  8179  8179 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.486  1044  1449 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 17:45:44.486  1951  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:44.486  1951  8228 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:44.486  1044  1449 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 17:45:44.486  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 17:45:44.486  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:44.486  1044  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:44.486  1044  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 17:45:44.486  1044  8213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 17:45:44.487  1044  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.487  1044  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.487  1044  1449 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 17:45:44.487  1044  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.487  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 17:45:44.487  1044  8213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-16 17:45:44.487  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 17:45:44.487  8179  8179 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 17:45:44.487  1044  8213 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.487  1044  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.488  1044  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 17:45:44.488  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 17:45:44.488  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 17:45:44.488  1044  8213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 17:45:44.488  1044  8213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 17:45:44.488  1044  1449 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 17:45:44.488  1044  1449 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-16 17:45:44.488  1044  1400 D LGWifiP2pService: InactiveState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.488  1044  1449 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 17:45:44.488  1044  1449 D WifiNative-wlan0: doBoolean: SCAN
08-16 17:45:44.488  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:44.489  1044  1449 D WifiNative-wlan0: SCAN: returned false
08-16 17:45:44.490  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=232379  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 17:45:44.491  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=232381  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 17:45:44.492  1044  1449 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:44.492  1044  1449 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:44.492  1044  1449 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:44.493  1044  1449 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:44.493  1044  1449 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 17:45:44.494  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:44.494  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:44.495  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.495  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:44.495  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 17:45:44.496  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:44.498  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:44.498  1044  1044 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-16 17:45:44.523  8216  8216 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:44.526  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 17:45:44.528  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:45:44.528  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:44.528  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:44.528  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:44.528  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:44.528  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:45:44.528  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:45:44.528  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:45:44.530  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:45:44.531  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:44.533  1044  2042 I ActivityManager: Killing 7313:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-16 17:45:44.534  6813  6892 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 17:45:44.535  6813  6892 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 17:45:44.536  6813  6892 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@109cfb35 Bundle[{}]
,08-16 17:45:44.537  6813  6892 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 17:45:44.538  6813  6892 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 17:45:44.538  6813  6892 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 17:45:44.539  6813  6892 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 17:45:44.539  6813  6892 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 17:45:44.540  6813  6892 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-16 17:45:44.545  6813  6892 I System.out: Running OutgoingSocketThread
08-16 17:45:44.546  6813  8237 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
08-16 17:45:44.547  6813  8237 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38473
08-16 17:45:44.547  6813  8237 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 17:45:44.563  1044  1933 W libprocessgroup: failed to open /acct/uid_10085/pid_7313/cgroup.procs: No such file or directory
,08-16 17:45:44.575  8216  8216 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:44.579  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 17:45:44.583  8192  8239 W FormManager: Network not available. Please check & try again.
08-16 17:45:44.583  8192  8240 V FormManager: Network unavailable.
08-16 17:45:44.585  8192  8240 V FormManager: Network unavailable.
08-16 17:45:44.585  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:44.596  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-16 17:45:44.596  4340  4340 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 17:45:44.598  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:44.599  4340  4340 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 17:45:44.604  4340  8241 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 17:45:44.606  4340  8242 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 17:45:44.606  4340  8242 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 17:45:44.658  1044  1584 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8243 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 17:45:44.777  8243  8243 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:45:44.777  8243  8243 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-16 17:45:44.790  8243  8243 V [BNRBootReceiver]: Boot Receiver Return
08-16 17:45:44.791  8243  8243 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 17:45:44.847  1044  1897 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8264 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 17:45:44.853  1044  1897 I ActivityManager: Killing 7344:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-16 17:45:44.964  1044  1059 W libprocessgroup: failed to open /acct/uid_10093/pid_7344/cgroup.procs: No such file or directory
,08-16 17:45:44.977  8179  8179 E wpa_supplicant: USIM:  scard_init function
08-16 17:45:44.978  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-16 17:45:44.978  1044  8213 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 17:45:44.978  8179  8179 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 17:45:44.978  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 17:45:44.978  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-16 17:45:44.979  1044  8213 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 17:45:44.982  1044  1449 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 17:45:44.986  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 17:45:44.986  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 17:45:44.988  1044  1449 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,08-16 17:45:44.989  1044  1449 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 17:45:44.990  1044  1449 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-16 17:45:44.990  1044  1449 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 17:45:45.003  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=232892  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 17:45:45.004  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=232894  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 17:45:45.009  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.009  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:45.010  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.010  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.010  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 17:45:45.010  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:45.011  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-16 17:45:45.011  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.015  8264  8264 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 17:45:45.039  8264  8264 D PluginManager: init()
,08-16 17:45:45.097  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 17:45:45.097  8179  8179 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 17:45:45.097  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 17:45:45.098  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 17:45:45.098  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 17:45:45.098  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:45.098  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 17:45:45.099  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=232988  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 17:45:45.099  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=232989  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 17:45:45.100  1044  1449 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=232990
08-16 17:45:45.100  1044  1449 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=232990
08-16 17:45:45.101  1044  1449 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=232990
08-16 17:45:45.101  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=232991
08-16 17:45:45.102  1044  1449 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=232991
08-16 17:45:45.103  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:45.103  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 17:45:45.105  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=232995  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 17:45:45.111  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.111  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:45.111  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 17:45:45.112  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.112  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 17:45:45.114  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.118  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:45.118  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:45.118  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=233007  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 17:45:45.119  1044  1449 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=233008  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 17:45:45.119  8179  8179 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:45:45.120  8179  8179 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 17:45:45.123  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.123  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.123  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 17:45:45.123  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 17:45:45.123  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:45:45.123  1044  8213 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:45:45.123  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 17:45:45.123  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 17:45:45.123  1044  8213 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 17:45:45.123  1044  1106 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:45:45.124  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:45.124  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:45.127  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=233009  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-16 17:45:45.128  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:45.128  1044  1044 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 17:45:45.130  1044  1449 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=233019
08-16 17:45:45.130  1044  1449 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=233020
08-16 17:45:45.131  1044  1449 D WifiNative-wlan0: doString: [STATUS]
08-16 17:45:45.133  1044  1449 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 17:45:45.133  1044  8213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 17:45:45.133  1044  8213 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 17:45:45.134  1044  1449 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 17:45:45.139  1044  1449 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-16 17:45:45.139  1044  1449 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 17:45:45.140  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.141  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 17:45:45.144  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.148  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.148  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.148  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 17:45:45.148  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.148  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.148  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 17:45:45.154  1044  1449 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 17:45:45.154  1044  1526 D ConnectivityService: Got NetworkAgent Messenger
08-16 17:45:45.154  1044  1449 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:45:45.154  1044  1449 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 17:45:45.154  1044  1526 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 17:45:45.154  1044  1526 D ConnectivityService: NetworkAgent connected
08-16 17:45:45.155  1044  1449 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 17:45:45.155  1044  1449 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 17:45:45.161  1044  1449 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 17:45:45.161  1044  1449 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:45:45.161  1044  1449 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 17:45:45.165  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.166  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 17:45:45.167  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.168  1044  1449 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 17:45:45.168  1044  1449 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 17:45:45.169  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.169  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:45.170  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.173  1044  1449 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 17:45:45.176   307   904 D CommandListener: Setting iface cfg
08-16 17:45:45.178  1044  1449 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 17:45:45.178  1044  8286 D DhcpStateMachine: StoppedState
08-16 17:45:45.179  1044  8286 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:45.179  1044  8286 D DhcpStateMachine: WaitBeforeStartState
,08-16 17:45:45.179  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:45.179  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:45.180  1044  1449 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:45.180  1044  1449 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:45.180  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:45.181  1044  1449 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 17:45:45.181  1044  1449 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=233071  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:45.182  1044  1449 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=233071  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:45.182  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=233072  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:45.184  1044  1449 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=233073  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:45.184  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:45.184  1044  1044 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 17:45:45.184  1044  1449 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=233074  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:45.185  1044  1449 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=233074  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 17:45:45.186  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13592] from screen [on:0 period:-1811437342] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 17:45:45.187  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1811437341] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 17:45:45.187  1044  1449 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 17:45:45.191  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.192  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.193  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.193  1044  1449 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.193  1044  1449 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.194  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 17:45:45.194  1044  1449 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.195  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-16 17:45:45.195  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=154,0,0
08-16 17:45:45.195  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 17:45:45.196  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 17:45:45.196  1044  1449 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 17:45:45.196  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 17:45:45.196  1044  1449 D WifiNative-wlan0: SET ps 0: returned true
08-16 17:45:45.196  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 17:45:45.197  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 17:45:45.197  1044  1526 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 17:45:45.197  1044  1526 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 17:45:45.197  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 17:45:45.197  1044  1449 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 17:45:45.197  1044  1449 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 17:45:45.197  1044  1400 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f690e5b target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:45.197  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f690e5b target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:45.198  1044  1449 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 17:45:45.198  1044  8286 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:45.198  1044  8286 D DhcpStateMachine: DHCP Start wake lock is acquired.
,08-16 17:45:45.198   307   904 D CommandListener: Setting iface cfg
08-16 17:45:45.199   307   904 D CommandListener: Trying to bring up wlan0
08-16 17:45:45.200  1044  1449 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 17:45:45.201  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:45.201  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 17:45:45.202  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 17:45:45.202  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 17:45:45.202  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.202  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.203  1044  1449 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.203  1044  1449 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.203  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.204  1044  1449 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 17:45:45.204  1044  1526 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 17:45:45.205  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 17:45:45.205  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 17:45:45.205  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 17:45:45.205  1044  1400 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:45.205  1044  1400 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:45.205  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 17:45:45.206  1044  1449 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 17:45:45.206  1044  1449 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 17:45:45.206  8179  8179 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 17:45:45.206  1044  1449 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 17:45:45.206  1044  1449 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 17:45:45.223  1044  1449 D WifiNative-wlan0: SET ps 1: returned true
08-16 17:45:45.223  1044  1526 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 17:45:45.224  1044  1449 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 17:45:45.224  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 17:45:45.224  1044  1449 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 17:45:45.225  1044  1526 D ConnectivityService: ignoring duplicate network state non-change
08-16 17:45:45.227  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.227  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 17:45:45.228  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.229  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.229  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.229  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 17:45:45.230  1044  1526 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 17:45:45.231  1044  1526 D ConnectivityService: Adding iface wlan0 to network 102
08-16 17:45:45.233  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.233  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.233  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 17:45:45.234  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 17:45:45.236  1951  1951 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 17:45:45.237  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.238  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:45:45.238  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 17:45:45.238  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 17:45:45.242  1044  1449 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 17:45:45.243  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.243  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:45:45.243  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 17:45:45.249  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.249  1613  1613 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 17:45:45.250  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.252  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.252  1613  1613 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 17:45:45.252  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.254  1613  1613 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:45:45.254  1613  1613 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 17:45:45.254  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.255  1044  1526 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 17:45:45.255  1044  1526 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 17:45:45.256  1044  1526 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-16 17:45:45.257   307   904 E Netd    : netlink response contains error (File exists)
08-16 17:45:45.257  1044  1526 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 17:45:45.258  1044  1526 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 17:45:45.258  1044  1526 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 17:45:45.258  1044  1526 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 17:45:45.259  1044  1526 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 17:45:45.259  1044  1526 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 17:45:45.259  1044  1526 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 17:45:45.260  1044  8281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:45.260  1044  8281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 17:45:45.260  1044  8281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:45:45.260  1044  8281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 17:45:45.262  1044  1526 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 17:45:45.262  1044  1526 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:45.262  1044  1526 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:45.262  1044  1526 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 17:45:45.262   307  8293 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 17:45:45.262  1044  1526 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.262  1044  1526 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 17:45:45.262  1044  1526 D ConnectivityService: currentScore = 0, newScore = 20
08-16 17:45:45.262  1044  1526 D ConnectivityService:    accepting network in place of null
08-16 17:45:45.262  1044  1526 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.262  1044  1449 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.262  1044  1449 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:45.263  1862  1862 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.263  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 17:45:45.264  1044  1526 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 17:45:45.264  1044  1526 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 17:45:45.264  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:45:45.268  1044  1044 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 17:45,:45.268  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 17:45:45.268  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 17:45:45.268  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 17:45:45.270  1044  1526 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:45:45.270  1044  1526 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 17:45:45.270  1044  1526 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 17:45:45.271  1044  1526 D ConnectivityService: validation of new default Network = false
08-16 17:45:45.271  1044  1526 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 17:45:45.271  1044  1526 D DSQN    : enableDataServiceNotify 
08-16 17:45:45.271  1044  1526 D DSQN    : start dsqn bin
,08-16 17:45:45.278  1044  1526 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 17:45:45.278  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.278  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:45.267  8294  8294 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:45.267  8294  8294 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:45.278  1044  1526 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:45.279  1613  2080 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:45:45.286  1044  1399 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-16 17:45:45.295  1613  1613 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 17:45:45.295  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.296  8294  8294 E DSQN    : DSQN ssw
08-16 17:45:45.296  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.319   307  8293 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-16 17:45:45.350   307  8293 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 17:45:45.384   307   903 D LGDataListener: argv[0]=dsqncommand
,08-16 17:45:45.384   307   903 D LGDataListener: argv[1]=wlan0
08-16 17:45:45.384   307   903 D LGDataListener: argv[2]=1
08-16 17:45:45.384   307   903 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 17:45:45.385  1044  1104 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 17:45:45.385  1044  1104 D DSQN    : start to monitor internet connection
,08-16 17:45:45.400  1044  8286 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 17:45:45.402  1044  8286 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 17:45:45.402  1044  8286 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-16 17:45:45.397  8300  8300 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 17:45:45.397  8300  8300 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 17:45:45.413  8300  8300 I dhcpcd  : version 5.5.6 starting
08-16 17:45:45.415  8300  8300 E dhcpcd  : get_duid: m
08-16 17:45:45.415  8300  8300 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 17:45:45.415  8300  8300 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 17:45:45.418  1044  8281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:45:45 GMT], X-Android-Received-Millis=[1471362345417], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471362345383]}
08-16 17:45:45.418  1044  8281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 17:45:45.418  1044  8281 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-16 17:45:45.419  1044  1526 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 17:45:45.420  1044  1526 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 17:45:45.420  1044  1526 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:45.420  1044  1526 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:45.420  1044  1526 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 17:45:45.420  1044  1526 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 17:45:45.421  1044  1526 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 17:45:45.421  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.421  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:45.422  1044  1526 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:45.424  1044  1526 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.424  1613  2080 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:45:45.425  1044  1449 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.425  1044  1449 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:45:45.427  1862  1862 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:45.428  1862  1862 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 17:45:45.428  1044  1526 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 17:45:45.461  1613  1613 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-16 17:45:45.464  8300  8300 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 17:45:45.464  8300  8300 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 17:45:45.464  8300  8300 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 17:45:45.464  8300  8300 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 17:45:45.464  8300  8300 D dhcpcd  : wlan0: sending REQUEST (xid 0xa910e167), next in 3.82 seconds
08-16 17:45:45.465  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.468  1613  1613 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 17:45:45.546  8300  8300 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-16 17:45:45.548  6813  6892 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
08-16 17:45:45.548  6813  6892 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
,08-16 17:45:45.557  6813  6892 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862),
08-16 17:45:45.560  6813  6892 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 17:45:45.560  6813  6892 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
,08-16 17:45:45.568  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:45:45.568  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be2709c added. We now have 2 listener(s)
08-16 17:45:45.568  1044  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.571  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17",
08-16 17:45:45.571  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.571  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:45:45.571  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.571  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2261aaa5 added. We now have 9 listener(s)
08-16 17:45:45.571  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-16 17:45:45.571  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:45:45.573  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:45:45.577  8264  8264 W ExternalStrings: load override strings,
08-16 17:45:45.577  8264  8264 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 17:45:45.577  8264  8264 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 17:45:45.577  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:45.577  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:45.577  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:45.577  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:45.577  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:45.577  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:45.577  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:45.577  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:45.579  8264  8264 D StatusProvider: onCreate
08-16 17:45:45.580  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:45.580  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:45.580  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.580  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34fc562b added. We now have 3 listener(s)
08-16 17:45:45.581  1044  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.583  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.584  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.587  8300  8300 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 17:45:45.587  8300  8300 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 17:45:45.588  8300  8300 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 17:45:45.588  8300  8300 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 17:45:45.589  8300  8300 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 17:45:45.589  8300  8300 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 17:45:45.590  8300  8300 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-16 17:45:45.590  8300  8300 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 17:45:45.587  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:45.591  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.591  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.591  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.592  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f3fa88 added. We now have 10 listener(s)
08-16 17:45:45.592  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.592  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:45.592  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:45.592  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:45.592  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.592  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.593  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:45.593  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.593  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be2709c removed from the list
08-16 17:45:45.593  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.593  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2261aaa5 removed from the list
08-16 17:45:45.593  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:45.593  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.594  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:45:45.594  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.595  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.595  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.595  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.595  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2261aaa5 not in the list
08-16 17:45:45.595  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.595  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.596  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.596  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.596  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.596  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f3fa88 removed from the list
08-16 17:45:45.596  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.596  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.596  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.596  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.596  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34fc562b removed from the list
08-16 17:45:45.597  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.597  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38674c21 added. We now have 2 listener(s)
08-16 17:45:45.597  1044  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 17:45:45.600  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:45.600  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.602  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.602  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.602  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb3a846 added. We now have 9 listener(s)
08-16 17:45:45.602  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.603  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:45:45.605  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:45.609  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:45.609  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:45.609  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:45.609  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:45.609  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:45.609  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:45.609  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:45.609  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:45:45.610  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:45:45.610  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:45.610  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.611  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10123734 added. We now have 3 listener(s)
08-16 17:45:45.611  1044  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.615  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:45.615  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.615  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.615  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.615  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acb895d added. We now have 10 listener(s)
08-16 17:45:45.615  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.615  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:45:45.615  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:45:45.615  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:45:45.615  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:45.615  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:45:45.616  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.617  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.619  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:45:45.619  1044  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.623  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:45:45.624  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:45:45.626  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:45:45.626  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:45.628  6813  6892 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:45:45.628  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:45.628  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:45.631  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:45.631  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:45.631  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:45.631  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.631  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.631  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:45.632  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.632  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38674c21 removed from the list
08-16 17:45:45.632  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.632  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb3a846 removed from the list
08-16 17:45:45.632  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:45.632  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.632  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.632  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.633  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.633  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.633  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.633  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb3a846 not in the list
08-16 17:45:45.633  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.633  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.634  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.635  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:45.635  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stop,ped
08-16 17:45:45.635  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.635  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.635  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@acb895d removed from the list
08-16 17:45:45.635  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.635  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.635  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.635  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.635  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10123734 removed from the list
08-16 17:45:45.636  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.636  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@143592a0 added. We now have 2 listener(s)
08-16 17:45:45.636  1044  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 17:45:45.639  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:45.639  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.639  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.639  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.639  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@353c5e59 added. We now have 9 listener(s)
08-16 17:45:45.639  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.640  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:45:45.644  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:45.646  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:45.646  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:45.646  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:45.646  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:45.646  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:45.646  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:45.646  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:45.646  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:45.648  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:45.648  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:45:45.650  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.652  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.652  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b252ff added. We now have 3 listener(s)
08-16 17:45:45.653  8264  8264 V Signer  : override build config not found
08-16 17:45:45.653  8264  8264 D Signer  : value of property debug is false
08-16 17:45:45.653  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.653  1044  2023 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.655  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:45.656  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.656  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.656  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.656  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@317138cc added. We now have 10 listener(s)
08-16 17:45:45.656  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.656  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:45:45.657  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:45:45.657  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:45:45.657  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:45:45.657  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:45.657  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:45:45.659  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:45:45.659  1044  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 17:45:45.663  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:45:45.664  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:45:45.665  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:45:45.666  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:45.667  6813  6892 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:45:45.667  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:45.668  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:45.668  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:45.668  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.668  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.668  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:45.668  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.668  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@143592a0 removed from the list
08-16 17:45:45.668  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.668  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@353c5e59 removed from the list
08-16 17:45:45.668  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:45.668  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.669  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.669  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.670  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.670  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.670  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.670  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@353c5e59 not in the list
08-16 17:45:45.670  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.670  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.671  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:45:45.671  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:45.671  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:45.671  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.671  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.671  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@317138cc removed from the list
08-16 17:45:45.671  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.671  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.672  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.672  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.672  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b252ff removed from the list
08-16 17:45:45.672  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.672  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d63201b added. We now have 2 listener(s)
08-16 17:45:45.673  1044  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.676  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:45.676  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.676  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.676  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.676  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6df15b8 added. We now have 9 listener(s)
08-16 17:45:45.676  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.677  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 17:45:45.677  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 17:45:45.678  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 17:45:45.678  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 17:45:45.678  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 17:45:45.678  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 17:45:45.678  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 17:45:45.678  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 17:45:45.678  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 17:45:45.679  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 17:45:45.679  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPic,tureTransfer'.
08-16 17:45:45.679  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 17:45:45.679  8264  8264 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 17:45:45.679  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:45:45.682  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:45:45.686  8264  8264 V LGMDMManager: Create singleton instance
08-16 17:45:45.690  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:45.690  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:45.690  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:45.690  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:45.690  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:45.690  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:45.690  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:45.690  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:45.691  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:45:45.691  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:45.691  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.691  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dcaef6 added. We now have 3 listener(s)
08-16 17:45:45.692  1044  1584 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.693  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.695  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.696  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 17:45:45.696  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.696  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.696  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.696  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3189a2f7 added. We now have 10 listener(s)
08-16 17:45:45.696  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.696  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:45:45.697  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:45:45.697  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:45:45.697  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:45.697  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:45:45.700  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:45:45.703  1044  1629 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.708  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:45:45.709  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:45:45.710  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:45:45.710  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:45.712  6813  6892 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 17:45:45.713  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:45.714  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:45.714  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:45.714  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.714  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.714  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:45.714  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.714  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d63201b removed from the list
08-16 17:45:45.714  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.714  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6df15b8 removed from the list
08-16 17:45:45.714  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:45.714  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.714  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.714  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.716  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.716  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.716  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.716  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6df15b8 not in the list
08-16 17:45:45.716  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.716  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.717  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.718  6813  6892 D BluetoothLeScanner: could not find callback wrapper
08-16 17:45:45.718  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:45:45.718  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.718  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.718  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3189a2f7 removed from the list
08-16, 17:45:45.718  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.718  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.718  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.718  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.718  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dcaef6 removed from the list
08-16 17:45:45.719  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.719  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139cc482 added. We now have 2 listener(s)
08-16 17:45:45.719  1044  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.721  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 17:45:45.721  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.722  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.722  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.722  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2b7793 added. We now have 9 listener(s)
08-16 17:45:45.722  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.722  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:45:45.723  8264  8264 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-16 17:45:45.725  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:45:45.728  6813  6892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:45:45.728  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:45:45.728  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:45:45.728  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:45:45.728  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:45:45.728  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:45.728  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:45:45.728  6813  6892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:45:45.730  6813  6892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:45:45.730  6813  6892 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:45:45.732  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.732  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:45:45.732  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18a48fc9 added. We now have 3 listener(s)
08-16 17:45:45.732  1044  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 17:45:45.734  6813  6813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:45:45.736  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 17:45:45.736  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:45:45.736  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:45:45.736  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:45:45.736  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2056a6ce added. We now have 10 listener(s)
08-16 17:45:45.736  6813  6892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:45:45.737  6813  6892 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:45:45.738  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:45.738  6813  6892 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:45:45.738  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.738  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.738  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:45:45.738  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.738  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139cc482 removed from the list
08-16 17:45:45.738  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.738  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2b7793 removed from the list
08-16 17:45:45.738  6813  6892 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:45:45.739  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.739  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.739  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.740  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.740  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.740  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:45:45.740  6813  6892 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2b7793 not in the list
08-16 17:45:45.740  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.740  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.741  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:45:45.741  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:45:45.741  6813  6892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08,-16 17:45:45.741  6813  6892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2056a6ce removed from the list
08-16 17:45:45.741  6813  6892 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:45:45.741  6813  6892 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:45:45.741  6813  6892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:45:45.741  6813  6892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:45:45.741  6813  6892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18a48fc9 removed from the list
08-16 17:45:45.742  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 17:45:45.742  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 17:45:45.742  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 17:45:45.743  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:45:45.743  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 17:45:45.743  6813  6892 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:45:45.754  6813  8328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: My test thread name)
08-16 17:45:45.754  6813  8328 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: My test thread name)
08-16 17:45:45.754  6813  8328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:45:45.762  6813  8329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: My test thread name)
08-16 17:45:45.762  6813  8329 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 872, thread name: My test thread name)
08-16 17:45:45.762  6813  8329 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 17:45:45.764  6813  6892 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 17:45:45.764  6813  6892 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 17:45:45.764  6813  6892 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 17:45:45.764  6813  6892 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 17:45:45.764  6813  6892 D com.test.thalitest.ThaliTestRunner: Total duration: 23074 ms
08-16 17:45:45.765  6813  6892 I jxcore-log: Total number of executed tests:  80
08-16 17:45:45.765  6813  6892 I jxcore-log: 
08-16 17:45:45.765  6813  6892 I jxcore-log: Number of passed tests:  80
08-16 17:45:45.765  6813  6892 I jxcore-log: 
08-16 17:45:45.765  6813  6892 I jxcore-log: Number of failed tests:  0
08-16 17:45:45.765  6813  6892 I jxcore-log: 
08-16 17:45:45.766  6813  6892 I jxcore-log: Number of ignored tests:  0
08-16 17:45:45.766  6813  6892 I jxcore-log: 
08-16 17:45:45.766  6813  6892 I jxcore-log: Total duration:  23074
08-16 17:45:45.766  6813  6892 I jxcore-log: 
08-16 17:45:45.766  6813  6892 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 17:45:45.766  6813  6892 I jxcore-log: 
08-16 17:45:45.769  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.769  6813  6892 I jxcore-log: 
,08-16 17:45:45.772  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.772  6813  6892 I jxcore-log: 
08-16 17:45:45.774  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.774  6813  6892 I jxcore-log: 
08-16 17:45:45.775  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.775  6813  6892 I jxcore-log: 
08-16 17:45:45.776  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.776  6813  6892 I jxcore-log: 
08-16 17:45:45.777  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.777  6813  6892 I jxcore-log: 
08-16 17:45:45.778  6813  6813 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 17:45:45.778  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:45.780  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.780  6813  6892 I jxcore-log: 
08-16 17:45:45.782  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:45:45.782  6813  6892 I jxcore-log: 
08-16 17:45:45.783  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:45:45.783  6813  6892 I jxcore-log: 
08-16 17:45:45.783  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:45.783  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.783  6813  6892 I jxcore-log: 
,08-16 17:45:45.784  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.784  6813  6892 I jxcore-log: 
,08-16 17:45:45.786  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:45:45.786  6813  6892 I jxcore-log: 
08-16 17:45:45.787  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:45:45.787  6813  6892 I jxcore-log: 
08-16 17:45:45.788  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:45:45.788  6813  6892 I jxcore-log: 
08-16 17:45:45.789  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.789  6813  6892 I jxcore-log: 
08-16 17:45:45.790  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 17:45:45.790  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.790  6813  6892 I jxcore-log: 
08-16 17:45:45.791  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.791  6813  6892 I jxcore-log: 
,08-16 17:45:45.792  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.792  6813  6892 I jxcore-log: 
08-16 17:45:45.793  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.793  6813  6892 I jxcore-log: 
08-16 17:45:45.793  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.793  6813  6892 I jxcore-log: 
08-16 17:45:45.794  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:45.794  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.794  6813  6892 I jxcore-log: 
08-16 17:45:45.795  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:45:45.795  6813  6892 I jxcore-log: 
08-16 17:45:45.796  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:45:45.796  6813  6892 I jxcore-log: 
08-16 17:45:45.797  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:45:45.797  6813  6892 I jxcore-log: 
08-16 17:45:45.798  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.798  6813  6892 I jxcore-log: 
08-16 17:45:45.799  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.799  6813  6892 I jxcore-log: 
08-16 17:45:45.800  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.800  6813  6892 I jxcore-log: 
08-16 17:45:45.801  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:45.801  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.801  6813  6892 I jxcore-log: 
08-16 17:45:45.802  6813  6892 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:45:45.802  6813  6892 I jxcore-log: 
08-16 17:45:45.803  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:45.807  1044  8286 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-16 17:45:45.808  1044  8286 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 17:45:45.808  1044  8286 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 17:45:45.808  1044  8286 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 17:45:45.808  1044  8286 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 17:45:45.808  1044  8286 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 17:45:45.808  1044  8286 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 17:45:45.808  1044  8286 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 17:45:45.809  1044  8286 D DhcpStateMachine: RunningState
,08-16 17:45:45.811  7793  7793 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 17:45:45.814  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:45.814  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:45.820  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:45.825  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:45.829  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:45.829  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:45.830  7793  7793 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 17:45:45.832  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-16 17:45:45.834  6989  6989 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 17:45:45.836  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:45.837  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:45.840  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 17:45:45.845  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:45.850  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:45.850  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:45.850  7793  7793 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 17:45:45.854  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 17:45:45.854  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:45.859  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:45.865  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:45.870  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:45.870  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:45.870  7793  7793 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 17:45:45.965  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:45.965  8264  8330 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 17:45:45.968  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:45.985  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:45.990  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:45.995  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:45.995  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:45.996  7793  7793 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 17:45:45.999  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 17:45:45.999  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 17:45:45.999  6989  6989 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 17:45:45.999  6989  6989 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 17:45:45.999  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 17:45:46.000  6989  6989 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 17:45:46.001  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 17:45:46.001  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 17:45:46.001  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 17:45:46.001  6989  6989 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 17:45:46.001  6989  6989 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 17:45:46.001  6989  6989 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 17:45:46.004  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:46.004  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:46.010  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:46.014  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:46.019  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:46.019  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:46.019  7793  7793 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 17:45:46.022  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:46.022  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 17:45:46.027  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 17:45:46.031  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:46.036  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:46.036  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:46.037  7793  7793 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 17:45:46.047  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:46.049  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 17:45:46.059  8336  8336 D AndroidRuntime: 
08-16 17:45:46.059  8336  8336 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 17:45:46.061  8336  8336 D AndroidRuntime: CheckJNI is OFF
08-16 17:45:46.065  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:46.074  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:46.080  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:46.081  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:46.086  7793  7793 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 17:45:46.089  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:46.090  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:46.095  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:46.105  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 17:45:46.112  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:46.112  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:46.113  7793  7793 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 17:45:46.116  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:46.116  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 17:45:46.123  8216  8216 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 17:45:46.128  8216  8216 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 17:45:46.131  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 17:45:46.137  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:46.143  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:46.143  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 17:45:46.145  7793  7793 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 17:45:46.146  7793  7793 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 17:45:46.146  7793  7793 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 17:45:46.151  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 17:45:46.151  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:46.155  8216  8216 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 17:45:46.156  8216  8216 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 17:45:46.160  6989  6989 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 17:45:46.165  8336  8336 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 17:45:46.173  6989  6989 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 17:45:46.176  1044  1102 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 17:45:46.176  1044  1102 I ActivityManager: Killing 6813:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-16 17:45:46.193  8264  8330 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:46.193  8264  8330 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:46.231  1044  2023 I WindowState: WIN DEATH: Window{222ad09b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 17:45:46.231  1044  1506 D WifiService: Client connection lost with reason: 4
,08-16 17:45:46.238  1044  2023 D InputDispatcher: Window went away: Window{222ad09b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 17:45:46.320  8264  8330 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-16 17:45:46.398  1044  1102 I ActivityManager:   Force finishing activity ActivityRecord{11f15384 u0 com.test.thalitest/.MainActivity t6}
,08-16 17:45:46.442   327   348 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 17:45:46.446  1044  1584 W ActivityManager: Spurious death for ProcessRecord{3a94d63b 6813:com.test.thalitest/u0a118}, curProc for 6813: null
,08-16 17:45:46.447  1044  1118 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-16 17:45:46.450  1044  1118 I ActivityManager: Killing 7378:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-16 17:45:46.507  1044  1118 I ActivityManager:   Force finishing activity ActivityRecord{11f15384 u0 com.test.thalitest/.MainActivity t6 f}
08-16 17:45:46.507  1044  1118 W ActivityManager: Duplicate finish request for ActivityRecord{11f15384 u0 com.test.thalitest/.MainActivity t6 f}
,08-16 17:45:46.534  1613  1613 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-16 17:45:46.538  2006  2006 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 17:45:46.539  3872  3872 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 17:45:46.545  7776  7776 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 17:45:46.545  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 17:45:46.552  2488  2653 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:45:46.555  2043  2043 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 17:45:46.557  2043  2043 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-16 17:45:46.558  1044  1932 W libprocessgroup: failed to open /acct/uid_10005/pid_7378/cgroup.procs: No such file or directory
08-16 17:45:46.559  1951  1967 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 17:45:46.560  1951  1967 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3f5ac7b7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 17:45:46.563  1951  2756 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 17:45:46.563  1951  2756 D SplitWindowPolicy: topRunningActivity=ActivityInfo{110afb24 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 17:45:46.565  7793  7793 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 17:45:46.566  7793  7793 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 17:45:46.567  7793  7793 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 17:45:46.572  1044  1390 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 17:45:46.581  7793  7793 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 17:45:46.581  7793  7793 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 17:45:46.591  4680  4680 I art     : Explicit concurrent mark sweep GC freed 8243(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 601us total 60.547ms
,08-16 17:45:46.613  1044  1101 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-16 17:45:46.616  4557  4557 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 17:45:46.616  4557  4557 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 17:45:46.616  4557  4557 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 17:45:46.617  4557  4557 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 17:45:46.617  4557  4557 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:45:46.617  4557  4557 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:45:46.617  4557  4557 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 17:45:46.617  4557  4557 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 17:45:46.617  4557  4557 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:45:46.617  4557  4557 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:45:46.617  4557  4557 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 17:45:46.617  4557  4557 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 17:45:46.622  1044  1044 D administrator: Handling package changes for user 0
08-16 17:45:46.656  2043  2043 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 17:45:46.657  2043  2133 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-16 17:45:46.658  1613  1613 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-16 17:45:46.671  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.672  8264  8330 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-16 17:45:46.674  2043  2043 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 17:45:46.675  1915  1915 D ActionManagerService: notifyUserLog: 1000003
08-16 17:45:46.676  2043  2043 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 17:45:46.678  1613  1674 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 17:45:46.678  1613  1674 D KeyguardModel: createShortcutInfo...
08-16 17:45:46.681  3872  4547 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 17:45:46.685  1613  1613 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 17:45:46.685  1613  1613 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 17:45:46.685  1613  1674 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 17:45:46.685  1613  1674 D KeyguardModel: createShortcutInfo...
,08-16 17:45:46.691  1044  1584 V SIM_STK : Menu title from STK is T-Mobile
08-16 17:45:46.692  1613  1674 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 17:45:46.692  1613  1674 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:45:46.693  1613  1674 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 17:45:46.694  1613  1674 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 17:45:46.696  1044  1987 V SIM_STK : Menu title from STK is T-Mobile
08-16 17:45:46.696  1044  1987 V SIM_STK : Menu title from STK is T-Mobile
08-16 17:45:46.702  1613  1674 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 17:45:46.702  1613  1674 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 17:45:46.703  8264  8330 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 17:45:46.706  8264  8330 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 17:45:46.717  2043  2043 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 17:45:46.718  2043  2043 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-16 17:45:46.719  1613  1674 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 17:45:46.719  1613  1674 D KeyguardModel: createShortcutInfo...
08-16 17:45:46.721  8264  8330 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 17:45:46.721  2043  2043 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-16 17:45:46.722  8264  8330 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 17:45:46.722  8264  8330 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-16 17:45:46.722  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.724  3872  4543 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 17:45:46.726  1915  1915 D ActionManagerService: notifyUserLog: 1000004
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , expire_time: 0
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , display: false
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , animation: false }
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , expire_time: 0
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , display: false
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , animation: false }
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , expire_time: 0
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , display: false
08-16 17:45:46.726  2043  2043 I GBoardWebViewUtils: , animation: false }
08-16 17:45:46.728  8264  8330 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 17:45:46.731  3872  4547 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 17:45:46.735  1613  1674 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' do,es not exist or contains no resources.
08-16 17:45:46.735  1613  1674 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 17:45:46.741  1879  1879 D SplitUIManager: split_name #11 / not available #0
08-16 17:45:46.741  1879  1879 D SplitUIService: removed split : 
08-16 17:45:46.747  8264  8330 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-16 17:45:46.747  1613  1674 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 17:45:46.747  1613  1674 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 17:45:46.748  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.749  1613  1674 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 17:45:46.749  1613  1674 D KeyguardModel: createShortcutInfo...
,08-16 17:45:46.754  1613  1674 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:45:46.754  1613  1674 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 17:45:46.754  1613  1674 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 17:45:46.754  1613  1674 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 17:45:46.755  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.756  1613  1674 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 17:45:46.756  1613  1674 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 17:45:46.757  2043  8369 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-16 17:45:46.763  1613  1674 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 17:45:46.763  1613  1674 D KeyguardModel: createShortcutInfo...
,08-16 17:45:46.764  1044  2005 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 17:45:46.765  2043  2043 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 17:45:46.765  7776  7776 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 17:45:46.766  2043  2043 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 17:45:46.767  1879  1879 D SplitUIManager: split_name #11 / not available #0
08-16 17:45:46.767  1879  1879 I SplitUIService: split app #11
08-16 17:45:46.768  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.769  1613  1613 D KeyguardModel: handleShortcutListChanged...
08-16 17:45:46.769  1613  1613 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 17:45:46.774  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.776  1613  1674 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 17:45:46.776  1613  1674 D KeyguardModel: createShortcutInfo...
08-16 17:45:46.778  1613  1674 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 17:45:46.778  1613  1674 D KeyguardModel: createShortcutInfo...
08-16 17:45:46.779  1613  1674 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 17:45:46.779  1613  1674 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 17:45:46.780  1613  1674 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 17:45:46.780  1613  1674 D KeyguardModel: createShortcutInfo...
08-16 17:45:46.781  1613  1674 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 17:45:46.781  1613  1674 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 17:45:46.782  1613  1674 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 17:45:46.782  1613  1674 D KeyguardModel: createShortcutInfo...
08-16 17:45:46.786  1613  1674 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 17:45:46.787  1613  1674 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 17:45:46.788  1613  1674 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 17:45:46.788  1613  1674 D KeyguardModel: createShortcutInfo...
,08-16 17:45:46.794  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.799  1044  1896 V SIM_STK : Menu title from STK is T-Mobile
08-16 17:45:46.810  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.813  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.815  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 17:45:46.816  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 17:45:46.820  8264  8264 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 17:45:46.820  8264  8331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 17:45:46.822  1827  1827 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 17:45:46.823  1613  1613 D KeyguardModel: handleShortcutListChanged...
08-16 17:45:46.823  1613  1613 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 17:45:46.824  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 17:45:46.824  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 17:45:46.825  1044  1044 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 17:45:46.826  1044  1588 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 17:45:46.828  2214  2214 I ConfigService: onCreate
08-16 17:45:46.829  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-16 17:45:46.833  2214  2214 I ConfigService: onBind returning update interface
08-16 17:45:46.834  2214  2214 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 17:45:46.834  2214  2214 I ConfigService: onBind returning config service
08-16 17:45:46.834  1827  1827 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 17:45:46.850  1827  1827 I ConfigFetchService: service connected
,08-16 17:45:46.857  2043  2043 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-16 17:45:46.859  2214  2214 I ConfigService: onDestroy
08-16 17:45:46.862  1827  8375 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-16 17:45:46.889  6074  8379 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-16 17:45:46.901  2043  2057 I art     : Background partial concurrent mark sweep GC freed 7104(324KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 22.179ms total 53.813ms
,08-16 17:45:46.916  1827  8382 I PeopleContactsSync: CP2 sync disabled
,08-16 17:45:46.921  1827  4832 I Icing   : doRemovePackageData com.test.thalitest
08-16 17:45:46.922  2043  2043 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-16 17:45:46.926  7880  7880 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-16 17:45:46.927  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 17:45:46.928  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 17:45:46.929   321   428 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 17:45:46.929  3188  8385 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 17:45:46.930  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 17:45:46.931  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 17:45:46.932  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 17:45:46.948  1827  8381 W GmsApplication: Using Auth Proxy for data requests.
,08-16 17:45:46.952  2043  2043 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 17:45:46.952  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 17:45:46.954  2043  2179 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 17:45:46.954  2043  2179 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 17:45:46.957  1044  1107 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{242c9c45 u0 com.lge.launcher2/.Launcher t5} time:234860
08-16 17:45:46.964  2349  8388 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 17:45:46.967  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 17:45:46.968  2043  2043 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 17:45:46.968  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 17:45:46.987  1044  1060 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8390 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 17:45:46.994  1827  8381 W GmsApplication: Using Auth Proxy for data requests.
08-16 17:45:46.997  2043  2043 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 17:45:47.000  2600  2600 D [Concierge]Service: onStartCommand(). Type : 8
08-16 17:45:47.000  2600  2600 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 17:45:47.002  2043  2043 D [Concierge]WidgetView: change position of spinner
,08-16 17:45:47.004  2043  2043 I [Concierge]WidgetView: initWebView(). Time : 1471362347004
08-16 17:45:47.006  1044  1118 I art     : Explicit concurrent mark sweep GC freed 86543(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 2.703ms total 304.672ms
08-16 17:45:47.006  2600  2600 D [Concierge]Service: Update widget ID : 11
08-16 17:45:47.006  2600  2600 D [Concierge]Service: onStartCommand(). Type : 0
08-16 17:45:47.024  2043  2043 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 500904974
08-16 17:45:47.024  2043  2043 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 17:45:47.024  2043  2043 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 17:45:47.027  2043  2043 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1bc2c98e
08-16 17:45:47.027  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 17:45:47.030  2214  2240 I art     : Explicit concurrent mark sweep GC freed 7266(417KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 3.450ms total 32.050ms
,08-16 17:45:47.041  8336  8336 D AndroidRuntime: Shutting down VM
,08-16 17:45:47.052  2043  2043 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 17:45:47.052  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 17:45:47.060  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,08-16 17:45:47.062  2043  2043 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 17:45:47.075  1044  1118 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8408 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-16 17:45:47.076  2043  2043 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471362139671, New one : 1471362347004
08-16 17:45:47.076  2043  2043 D [Concierge]WidgetView: Unregister all receivers
08-16 17:45:47.076  2043  2043 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 17:45:47.077  8390  8390 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:45:47.077  8390  8390 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 17:45:47.078  2043  2043 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 17:45:47.078  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 17:45:47.078  8390  8390 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 17:45:47.078  8390  8390 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 17:45:47.080  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 17:45:47.081  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 17:45:47.082  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 17:45:47.084  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 17:45:47.085  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 17:45:47.086  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 17:45:47.087  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 17:45:47.118  1044  1449 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 17:45:47.118  1044  1449 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 17:45:47.119  1044  1449 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 17:45:47.119  1044  1449 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 17:45:47.119  1044  1449 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 17:45:47.119  1044  1449 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 17:45:47.120  1044  1526 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 17:45:47.120  1044  1526 D ConnectivityService: identical MTU - not setting
08-16 17:45:47.120  1044  1526 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 17:45:47.120  1044  1526 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 17:45:47.120  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:45:47.120  1044  1526 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:47.120  1044  1526 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 17:45:47.121  1613  2080 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 17:45:47.137  1044  1101 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:45:47.137  2043  2043 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 17:45:47.145  1044  1101 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 17:45:47.145  2043  2043 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 17:45:47.145  2043  2043 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 17:45:47.147  2043  2043 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 17:45:47.148  1044  1968 I ActivityManager: Killing 7829:com.google.android.talk/u0a72 (adj 15): empty #17
08-16 17:45:47.166  2043  2043 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f9de0fb time:235069
,08-16 17:45:47.229  1044  1933 W libprocessgroup: failed to open /acct/uid_10072/pid_7829/cgroup.procs: No such file or directory
,08-16 17:45:47.231  2043  2043 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 17:45:47.232  8390  8390 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-16 17:45:47.240  8390  8390 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 17:45:47.263  8390  8390 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 17:45:47.283  8390  8390 D LgDataFeature: LgDataFeature() Constructor: none
08-16 17:45:47.283  8390  8390 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 17:45:47.317  2043  2043 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 17:45:47.332  8390  8390 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-16 17:45:47.338  7928  7928 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
,08-16 17:45:47.339  1044  2042 I ActivityManager: Killing 7963:com.android.vending/u0a44 (adj 15): empty #17
08-16 17:45:47.355  2043  2876 I GBoardtInterface: onReloaded()
,08-16 17:45:47.357  2043  2043 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 17:45:47.368  2006  2006 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 17:45:47.368  2006  2006 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-16 17:45:47.368  1044  1792 W libprocessgroup: failed to open /acct/uid_10044/pid_7963/cgroup.procs: No such file or directory
08-16 17:45:47.371  2006  2006 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 17:45:47.371  3872  3888 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 17:45:47.375  3872  4543 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: Failed to open database '/data/data/com.wsandroid.suite.lge/databases/CLOUDREPUTATIONDB'.
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.i.a(Unknown Source)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ad.a(Unknown Source)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.ab.j(Unknown Source)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.b(Unknown Source)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.k.a(Unknown Source)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at com.mcafee.cloudscan.mc20.CloudScanReceiver.onReceive(Unknown Source)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java,:372)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 17:45:47.375  8264  8264 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 17:45:47.378  8264  8264 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 17:45:47.382  7604  7604 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-16 17:45:47.383  1915  1915 D ActionManagerService: notifyUserLog: 1000001
,08-16 17:45:47.384  6989  6989 D PackageIntentReceiver: Not supported Hotkey customization function 
08-16 17:45:47.385  3872  4547 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 17:45:47.385  3872  4547 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 17:45:47.387  1915  1915 D ActionManagerService: notifyUserLog: 1000001
08-16 17:45:47.388  3872  4547 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 17:45:47.388  3872  4547 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 17:45:47.388  3872  4547 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 17:45:47.388  3872  4547 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 17:45:47.389  3872  3888 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 17:45:47.390  2043  2043 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 17:45:47.391  2043  2043 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 17:45:47.391  6989  6989 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-16 17:45:47.391  6989  6989 D HideNavigationAppsReceiver: replacing : false
08-16 17:45:47.392  2043  2043 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 17:45:47.392  2043  2043 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 17:45:47.393  6989  6989 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-16 17:45:47.394  2043  2043 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 17:45:47.394  2043  2043 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay

```
