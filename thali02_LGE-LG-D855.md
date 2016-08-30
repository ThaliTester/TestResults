#### Test 797638307ede68b_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-30 15:30:00.105  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 15:30:00.105  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 15:30:00.105  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-30 15:30:00.106  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-30 15:30:00.120  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 15:30:00.121  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-30 15:30:00.124  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-30 15:30:00.125  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 15:30:00.402  6745  6745 D AndroidRuntime: 
08-30 15:30:00.402  6745  6745 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 15:30:00.408  6745  6745 D AndroidRuntime: CheckJNI is OFF
08-30 15:30:00.520  6745  6745 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 15:30:00.525  1036  1978 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 15:30:00.551  1942  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-30 15:30:00.555  1036  1978 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-30 15:30:00.556  1036  1978 D ActivityManager: setTaskToReturnTo : TaskRecord{36f6755e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 15:30:00.556  1036  1978 D ActivityManager: setTaskToReturnTo : TaskRecord{36f6755e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 15:30:00.557  1036  1978 D WindowStateEx: AppWindowTokenEx init.. 
08-30 15:30:00.558   343   350 E GBMv2   : DFP En is all cleared set to be enabled
08-30 15:30:00.588  1036  1978 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6765 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 15:30:00.590  6745  6745 D AndroidRuntime: Shutting down VM
08-30 15:30:00.631  1942  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-30 15:30:00.632  1942  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{a62ce7b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 15:30:00.632  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-30 15:30:00.633  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{351d9498 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-30 15:30:00.668  6765  6765 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 15:30:00.735  6765  6765 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-30 15:30:00.741  6765  6765 I LibraryLoader: Loading: webviewchromium
08-30 15:30:00.743  6765  6765 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7610-7613)
08-30 15:30:00.743  6765  6765 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:30:00.763  6765  6765 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {83a20e1}
08-30 15:30:00.766  6765  6765 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:30:00.767  6765  6765 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 15:30:00.781  6765  6765 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 15:30:00.782  6765  6765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 15:30:00.794  6765  6765 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 15:30:00.795  6765  6765 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-30 15:30:00.796  6765  6765 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-30 15:30:00.800   316  1403 V AudioPolicyService: registerClient() client 0xb0404400, uid 10118
08-30 15:30:00.805  1036  1118 D BluetoothManagerService: Message: 20
08-30 15:30:00.805  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@108236f8:true
08-30 15:30:00.821  6765  6765 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:30:00.821  6765  6765 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:30:00.821  6765  6765 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:30:00.821  6765  6765 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:30:00.821  6765  6765 I Adreno-EGL: Remote Branch: 
08-30 15:30:00.821  6765  6765 I Adreno-EGL: Local Patches: 
08-30 15:30:00.821  6765  6765 I Adreno-EGL: Reconstruct Branch: 
,08-30 15:30:00.914  6765  6800 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-30 15:30:00.916  6765  6765 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-30 15:30:00.932  6765  6765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:30:00.939  6765  6765 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 15:30:00.942  6765  6765 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 15:30:00.945  6765  6765 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 15:30:00.945  6765  6765 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-30 15:30:00.957  6765  6765 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 15:30:00.964  6765  6765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 15:30:00.964  6765  6765 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:30:01.002  6765  6813 D OpenGLRenderer: Render dirty regions requested: true
08-30 15:30:01.002  6765  6813 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 15:30:01.021  6765  6813 D OpenGLRenderer: Enabling debug mode 0
,08-30 15:30:01.031  6765  6765 D Atlas   : Validating map...
08-30 15:30:01.035  1036  1936 D SplitWindow: check instance of lgWin Window{2a5fb972 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 15:30:01.080  6765  6811 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:01.080  6765  6811 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:01.223  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +593ms (total +665ms)
08-30 15:30:01.224  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2366cd3f u0 com.test.thalitest/.MainActivity t6} time:188095
08-30 15:30:01.232  6765  6765 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@166bb124 time:188103
08-30 15:30:01.343  6765  6765 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-30 15:30:01.343  6765  6765 I chromium: 
,08-30 15:30:01.377  6765  6765 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 15:30:01.443  6765  6811 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-30 15:30:01.443  6765  6811 I chromium: 
,08-30 15:30:01.598  6765  6827 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435156352
,08-30 15:30:01.627  6765  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 15:30:01.627  6765  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 15:30:01.627  6765  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 15:30:01.627  6765  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 15:30:01.627  6765  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 15:30:01.627  6765  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fac6ca8 added. We now have 1 listener(s)
,08-30 15:30:01.634  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:01.637  6765  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-30 15:30:01.640  6765  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:01.641  6765  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:01.642  6765  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 15:30:01.650  6765  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c05aa7 added. We now have 1 listener(s)
08-30 15:30:01.650  6765  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:01.655  1036  1423 D WifiService: New client listening to asynchronous messages
08-30 15:30:01.664  6765  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:30:01.665  6765  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 15:30:01.666  6765  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 15:30:01.667  6765  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 15:30:01.667  6765  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 15:30:01.672  6765  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:01.673  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:01.674  6765  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-30 15:30:01.684  6765  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 15:30:01.684  6765  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:01.684  6765  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:01.684  6765  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:01.684  6765  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:01.684  6765  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:01.684  6765  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:01.684  6765  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:01.684  6765  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:01.684  6765  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 15:30:01.685  6765  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:01.686  6765  6827 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 15:30:01.687  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:01.688  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:01.714  1036  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=593603578, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1036
,08-30 15:30:01.734  6765  6765 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 15:30:01.762  1036  1111 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6832 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-30 15:30:01.800  2569  2569 D [Concierge]Service: onStartCommand(). Type : 9
,08-30 15:30:01.909  6832  6832 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-30 15:30:01.913  6832  6832 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@104f583a
08-30 15:30:01.913  1036  1036 D PowerManagerServiceEx: releaseWakeLockInternal: lock=593603578 [*alarm*], flags=0x0
08-30 15:30:01.914  1036  1781 I ActivityManager: Killing 6251:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-30 15:30:01.971   343   352 E GBMv2   : DFP En is all cleared set to be enabled
08-30 15:30:01.971   343   352 E GBMv2   : Set value is all cleared set the max
08-30 15:30:01.971   343   352 I GBMv2   : DFP Enabled. Ignore VFP set
,08-30 15:30:02.012  1036  1914 W libprocessgroup: failed to open /acct/uid_10014/pid_6251/cgroup.procs: No such file or directory
,08-30 15:30:02.663  6765  6830 W jxcore-log: Initializing JXcore engine
08-30 15:30:02.663  6765  6830 W jxcore-log: JXcore engine is ready
,08-30 15:30:02.692  6830  6830 W Thread-782: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8366]" dev="sockfs" ino=8366 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-30 15:30:02.692  6830  6830 W Thread-782: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-30 15:30:02.692  6830  6830 W Thread-782: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10371]" dev="sockfs" ino=10371 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-30 15:30:02.692  6830  6830 W Thread-782: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-30 15:30:02.692  6830  6830 W Thread-782: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34058]" dev="sockfs" ino=34058 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-30 15:30:02.714  6765  6830 W jxcore-log: Starting JXcore engine
,08-30 15:30:02.789  6765  6830 W jxcore-log: Platform android
08-30 15:30:02.789  6765  6830 W jxcore-log: 
08-30 15:30:02.789  6765  6830 W jxcore-log: Process ARCH arm
08-30 15:30:02.789  6765  6830 W jxcore-log: 
,08-30 15:30:02.975  6765  6830 I jxcore-log: JXcore Cordova bridge is ready!
08-30 15:30:02.975  6765  6830 I jxcore-log: 
08-30 15:30:02.975  6765  6830 W jxcore-log: JXcore engine is started
,08-30 15:30:02.986  6765  6827 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 15:30:02.993  6765  6765 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 15:30:12.560  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 15:30:12.560  6765  6830 I jxcore-log: 
,08-30 15:30:12.563  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 15:30:12.563  6765  6830 I jxcore-log: 
08-30 15:30:12.568  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:12.568  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:12.568  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:12.568  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:12.568  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:12.568  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:12.568  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:12.568  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:12.572  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 15:30:12.574  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 15:30:12.574  6765  6830 I jxcore-log: 
08-30 15:30:12.576  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 15:30:12.576  6765  6830 I jxcore-log: 
08-30 15:30:13.085  6765  6830 D executeNativeTests: Running unit tests
,08-30 15:30:13.167  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:13.167  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 added. We now have 2 listener(s)
08-30 15:30:13.168  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:13.170  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-30 15:30:13.170  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:13.170  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:13.170  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:13.170  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 added. We now have 2 listener(s)
08-30 15:30:13.170  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:13.172  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:30:13.179  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.183  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:13.183  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.183  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.183  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:13.183  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:13.183  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.183  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:13.183  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:30:13.185  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.185  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:13.188  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:30:13.188  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:30:13.188  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:30:13.190  6765  6830 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 15:30:13.191  6765  6830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 15:30:13.191  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:30:13.191  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:30:13.191  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:30:13.191  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.191  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.192  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.192  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.192  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.192  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.192  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:13.192  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:13.193  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 removed from the list
08-30 15:30:13.193  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.193  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 removed from the list
08-30 15:30:13.193  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.195  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.195  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:30:13.198  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.198  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.199  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.199  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.199  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.199  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.202  6765  6830 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 15:30:13.202  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.202  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.202  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.202  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.203  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.203  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.203  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.203  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.203  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.203  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.203  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.203  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.203  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.203  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.204  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.204  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.204  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.204  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:30:13.214  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:30:13.215  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Pee,r: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:30:13.216  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:30:13.216  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.216  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.216  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.216  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.216  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.216  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.216  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.216  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.216  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.216  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.216  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.216  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.216  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.216  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.217  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.217  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.217  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.217  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.218  6765  6830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:30:13.342  1036  1959 I art     : Explicit concurrent mark sweep GC freed 34904(1631KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.317ms total 122.990ms
08-30 15:30:13.345  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.347  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:13.347  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.347  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.347  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:13.347  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:13.347  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.347  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting t,o active network: true
08-30 15:30:13.347  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:30:13.351  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.352  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:13.353  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.353  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:30:13.354  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:30:13.355  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.355  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:30:13.355  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.355  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:30:13.371  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:30:13.371  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:30:13.378  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:30:13.384  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:30:13.386  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 15:30:13.388  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:30:13.389  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:13.390  6765  6830 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:30:13.390  6765  6830 I io.jxcore.node.ConnectionHelper: start: OK
08-30 15:30:13.392  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.392  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.393  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.393  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.393  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.393  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:13.393  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.393  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.393  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.393  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.393  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.393  6765  6830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:30:13.395  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.398  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:13.398  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.398  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.398  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:13.398  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:13.398  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.398  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:13.398  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:13.399  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.399  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:13.399  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 15:30:13.400  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:30:13.400  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:30:13.400  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.400  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:30:13.402  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.404  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.405  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:30:13.405  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:13.406  6765  6830 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:30:13.407  6765  6830 I io.jxcore.node.ConnectionHelper: start: OK
08-30 15:30:13.408  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.408  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.408  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.408  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.408  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.408  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:13.408  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.408  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.408  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.408  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.408  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.409  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.409  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.410  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.410  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:30:13.412  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.412  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.412  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.412  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.413  6765  6830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 15:30:13.414  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.417  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:13.417  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.417  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.417  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:13.417  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:13.417  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.417  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:13.417  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:13.418  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.418  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:13.419  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:30:13.419  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:30:13.419  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:30:13.419  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.419  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:30:13.421  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.423  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:13.427  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:30:13.427  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:13.433  6765  6830 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:30:13.434  6765  6830 I io.jxcore.node.ConnectionHelper: start: OK
08-30 15:30:13.434  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.434  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.434  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.435  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.435  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.435  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:30:13.437  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.437  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.437  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:13.437  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.437  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.437  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.437  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.437  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.438  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.438  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.439  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.439  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.440  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.440  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.440  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.440  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.441  6765  6830 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 15:30:13.441  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.441  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.441  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.441  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.441  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.441  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.442  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.442  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.442  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.442  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.442  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.442  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blueto,othManager: release: 1 listener(s) left
08-30 15:30:13.442  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.442  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.443  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.443  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.443  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.443  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.443  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.443  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.445  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:30:13.445  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.445  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.445  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.445  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.445  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.445  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.445  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.445  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.445  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.445  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.445  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.445  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.446  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.446  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:30:13.447  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.447  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 15:30:13.450  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.450  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.450  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.450  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.451  6765  6830 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 15:30:13.451  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.451  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.451  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.451  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.451  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.451  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.451  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.451  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.451  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.452  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.452  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.452  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.452  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.452  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.453  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.453  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.454  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.454  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.454  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.454  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.455  6765  6830 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 15:30:13.455  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.455  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.455  6765  6830 V io.jxcore.node.StartStopOperationHand,ler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.455  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.455  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.455  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.456  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.456  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.456  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.456  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.456  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.456  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.456  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.456  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.457  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.457  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.457  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.457  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.457  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.457  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.458  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:30:13.458  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:30:13.458  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:30:13.458  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:30:13.459  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 15:30:13.459  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 15:30:13.459  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.459  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.459  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.461  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.461  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.461  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.461  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.461  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.461  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.461  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.461  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.461  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.461  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.461  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.463  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.463  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.463  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.463  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.463  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.463  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.464  6765  6830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:30:13.465  6765  6830 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:30:13.465  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 15:30:13.468  6765  6830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:30:13.468  6765  6830 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 15:30:13.468  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 15:30:13.468  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 15:30:13.468  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 15:30:13.468  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 15:30:13.468  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 15:30:13.468  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 15:30:13.469  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 15:30:13.470  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 15:30:13.470  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 15:30:13.470  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 15:30:13.470  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 15:30:13.470  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 15:30:13.470  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 15:30:13.470  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 15:30:13.470  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 15:30:13.470  6765  6830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 15:30:13.470  6765  6830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:30:13.470  6765  6830 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 15:30:13.471  6765  6830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:30:13.471  6765  6830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:30:13.471  6765  6830 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 15:30:13.472  6765  6830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:30:13.472  6765  6830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 15:30:13.473  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 15:30:13.475  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 15:30:13.476  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 15:30:13.476  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 15:30:13.477  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 15:30:13.477  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 15:30:13.477  6765  6830 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 15:30:13.477  6765  6830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 15:30:13.478  6765  6830 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 15:30:13.478  6765  6872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 846)
08-30 15:30:13.479  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.479  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.479  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.480  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.480  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.480  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.480  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 15:30:13.483  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.483  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.483  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.483  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.483  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.483  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.483  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.483  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.485  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.485  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.486  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.486  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.486  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.486  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.488  6765  6830 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 15:30:13.488  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.488  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.488  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.488  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.488  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.488  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.488  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.488  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.488  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.488  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.488  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.489  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.489  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.489  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.490  6765  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 846
08-30 15:30:13.491  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.491  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.491  6765  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 846)
08-30 15:30:13.491  6765  6873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 846)
08-30 15:30:13.491  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.491  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.491  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.491  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.492  6765  6830 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 15:30:13.493  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.493  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.493  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.493  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.493  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.494  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.494  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.494  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.494  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.494  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.494  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.494  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.494  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 15:30:13.494  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.496  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.496  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.497  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.497  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.497  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.497  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.498  6765  6830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 15:30:13.498  6765  6830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 15:30:13.498  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:30:13.499  6765  6830 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 15:30:13.499  6765  6830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:30:13.501  6765  6830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 15:30:13.501  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:30:13.501  6765  6830 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 15:30:13.502  6765  6830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 15:30:13.502  6765  6830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 15:30:13.502  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 15:30:13.502  6765  6830 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 15:30:13.502  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.502  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.502  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.502  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.502  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.502  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.502  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.502  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.502  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.502  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.502  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.502  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.502  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.502  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.504  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.504  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.505  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.505  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.505  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.505  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.506  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.506  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.506  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.506  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.506  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.506  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.507  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.507  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.507  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.507  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.507  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.507  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.507  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.507  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.507  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.507  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.507  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.507  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.508  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.508  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.508  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.508  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.508  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.508  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.508  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.508  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.508  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.508  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.508  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.509  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.509  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.510  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.510  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.510  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.510  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.512  6765  6830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 15:30:13.512  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.513  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 15:30:13.514  6765  6830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 15:30:13.514  6765  6830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 15:30:13.515  6765  6765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 15:30:13.515  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 15:30:13.515  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 15:30:13.516  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.516  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 15:30:13.516  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 15:30:13.516  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 15:30:13.516  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.517  6765  6830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 15:30:13.517  6765  6765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 15:30:13.517  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.517  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.517  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 15:30:13.517  6765  6830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 15:30:13.518  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 15:30:13.519  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 15:30:13.519  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:13.519  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:13.520  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:13.520  6765  6830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 15:30:13.520  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.520  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.521  6765  6875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:13.521  6765  6830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:30:13.521  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.521  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:30:13.521  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.521  6765  6765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 15:30:13.522  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.522  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.522  6765  6765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 15:30:13.522  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.522  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.522  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.522  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.522  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.522  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.522  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.522  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.522  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.522  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.522  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.523  3905  4195 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=83
08-30 15:30:13.524  6765  6875 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 15:30:13.524  6765  6875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 15:30:13.525  6765  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 15:30:13.525  6765  6765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 15:30:13.527  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.527  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.527  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.527  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.528  6765  6830 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 15:30:13.528  6765  6830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 15:30:13.528  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 15:30:13.528  6765  6830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 15:30:13.529  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.529  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.529  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.529  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.529  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.529  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.529  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.529  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 1,5:30:13.530  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.530  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.530  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.530  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.530  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.530  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.531  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.531  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.531  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.531  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.533  1036  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:13.534  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:13.535  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:30:13.540  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.540  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.540  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.540  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.540  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.540  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.540  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.540  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.540  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.540  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.541  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.541  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.541  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.541  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.542  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.543  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.543  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.543  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.544  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:13.544  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:13.544  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:13.544  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:13.544  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.544  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.544  6765  6830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bdec978 not in the list
08-30 15:30:13.544  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.544  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManage,r@a0e8851 not in the list
08-30 15:30:13.545  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:13.545  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.545  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.545  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:13.545  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:13.546  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:13.546  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:13.546  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:13.546  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0e8851 not in the list
08-30 15:30:13.547  6765  6830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 15:30:13.547  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:30:13.548  6765  6830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 15:30:13.548  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 15:30:13.548  6765  6830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 15:30:13.548  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 15:30:13.550  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 15:30:13.550  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 15:30:13.551  6765  6830 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 15:30:13.551  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 15:30:13.551  6765  6830 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 15:30:13.551  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 15:30:13.552  6765  6830 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 15:30:13.552  6765  6830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 15:30:13.552  6765  6830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 15:30:13.553  6765  6830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-30 15:30:13.553  6765  6830 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 15:30:13.553  6765  6830 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 15:30:13.554  6765  6830 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 15:30:13.554  6765  6830 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 15:30:13.555  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:13.555  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a2e588e added. We now have 2 listener(s)
08-30 15:30:13.555  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:13.556  6765  6830 D BluetoothAdapter: enable(): BT is already enabled..!
08-30 15:30:13.557  1036  1978 D WifiServiceImplEx: setWifiEnabled: true pid=6765, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:30:13.558  1036  1978 D WifiService: setWifiEnabled: true pid=6765, uid=10118
08-30 15:30:13.558  1036  1978 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:30:13.559  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:13.559  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@208b28af added. We now have 3 listener(s)
08-30 15:30:13.559  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:13.563  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:13.563  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27ffd4bc added. We now have 4 listener(s)
08-30 15:30:13.563  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:30:13.565  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:13.565  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@270c45 added. We now have 5 listener(s)
08-30 15:30:13.565  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:13.568  1036  1978 D WifiServiceImplEx: setWifiEnabled: false pid=6765, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:30:13.568  1036  1978 D WifiService: setWifiEnabled: false pid=6765, uid=10118
08-30 15:30:13.568  1036  1978 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:30:13.587  6765  6872 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-30 15:30:13.587  6765  6872 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 846)
,08-30 15:30:13.590  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:30:13.591  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:30:13.591  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 15:30:13.592  1036  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:13.592  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:13.592  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:13.592  1036  1051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@a77f75d mBinding = false
08-30 15:30:13.592  1036  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:13.593  1036  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:13.593  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:13.593  1036  1392 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 15:30:13.594  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:30:13.594  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:30:13.594  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:30:13.594  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:30:13.606  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:30:13.606  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:30:13.607  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.607  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:30:13.607  2725  2725 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:30:13.607  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:30:13.607  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:30:13.608  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:30:13.608  1036  2860 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.608   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:30:13.616  1036  1118 D BluetoothManagerService: Message: 2
,08-30 15:30:13.621  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:30:13.622  1036  1118 D BluetoothManagerService: Sending off request.
08-30 15:30:13.622  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:30:13.622  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 15:30:13.622  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:13.623  3905  3925 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 15:30:13.624  3905  3990 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 15:30:13.624  3905  3990 D BluetoothAdapterProperties: Setting state to 13
08-30 15:30:13.624  3905  3990 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:30:13.625  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.625  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:13.625  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.625  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.625  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:13.625  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:13.625  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.625  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:13.625  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:13.625  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.625  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.625  3905  3990 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 15:30:13.625  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:13.625  3905  3990 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 15:30:13.630  3905  3993 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:30:13.630  3905  3990 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 15:30:13.631  3905  4249 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:13.631  3905  3990 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 15:30:13.632  3905  4198 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:13.633  3905  4196 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 15:30:13.633  3905  4196 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:13.633  3905  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 15:30:13.633  3905  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 15:30:13.633  3905  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 15:30:13.633  3905  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 15:30:13.633  3905  4196 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 15:30:13.633  3905  4196 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-30 15:30:13.633  3905  4244 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:13.634  3905  4246 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:13.634  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 15:30:13.634  3905  4074 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 15:30:13.635  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:13.635  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:13.635  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:13.636  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:13.636  3905  4074 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:30:13.636  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:13.636  3905  4074 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:30:13.636  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:13.636  3905  4074 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:30:13.636  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 15:30:13.636  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 15:30:13.636  3905  4074 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 15:30:13.637  1036  1442 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 15:30:13.638  1036  1442 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-30 15:30:13.639  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.639  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:13.639  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.639  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.639  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:13.639  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:13.639  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.639  6765  6765 V, io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:13.639  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:13.640  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.640  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:13.640  1036  1118 D BluetoothManagerService: Message: 60
08-30 15:30:13.640  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 15:30:13.640  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 15:30:13.644  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.644  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:13.644  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.644  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.644  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:13.644  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:13.644  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:13.644  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:13.644  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:30:13.648  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.648  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:13.651  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.651  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:13.651  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.651  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.651  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:13.651  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:13.651  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:13.651  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:13.651  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:13.652  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.652  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:13.655  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.661  1036  1914 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,08-30 15:30:13.670  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.670  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-8ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.670  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 15:30:13.670  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.670  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-30 15:30:13.682  1036  1111 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6888 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 15:30:13.686  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 15:30:13.687  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:13.687  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:13.687  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:30:13.691   311  6899 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 15:30:13.692  3905  3905 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:13.692  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-30 15:30:13.692  3905  3905 D BluetoothMapService: STATE_TURNING_OFF
08-30 15:30:13.692  3905  3905 V BluetoothMapService: Handler(): got msg=4
08-30 15:30:13.692  3905  3905 D BluetoothMapService: MAP Service closeService in
08-30 15:30:13.692  3905  3905 D BluetoothMapMasInstance: MAP Service shutdown
08-30 15:30:13.692  3905  3905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:30:13.692  3905  3905 V BluetoothMapService: MAP Service closeService out
08-30 15:30:13.692  3905  3905 V BtOppService: Receiver DISABLED_ACTION 
08-30 15:30:13.693  3905  3905 I BtOppRfcommListener: stopping Accept Thread
08-30 15:30:13.693  3905  3905 V BtOppRfcommListener: close mBtServerSocket
08-30 15:30:13.693  3905  3905 V BtOppRfcommListener: waiting for thread to terminate
08-30 15:30:13.693  3905  4244 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 15:30:13.693  1036  1442 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 15:30:13.693  1036  1442 D DSQN    : disableDataServiceNotify
08-30 15:30:13.693  1036  1442 D DSQN    : stop dsqn bin
08-30 15:30:13.693  3905  3905 V BtOppRfcommListener: done waiting for thread to terminate
08-30 15:30:13.694  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-30 15:30:13.694  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 15:30:13.694  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:13.694  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:13.695  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:13.695  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:13.696  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.698  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:13.698  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:30:13.699   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 350us total 17.999ms
08-30 15:30:13.704  1036  1442 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 15:30:13.704  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:13.704  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:13.705  1036  1442 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:13.705  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 15:30:13.705  1036  1442 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 15:30:13.706  1036  1442 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 15:30:13.706  1036  1442 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 15:30:13.706  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.706  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.706  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:30:13.706  1036  2859 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-30 15:30:13.715   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 270us total 14.854ms
08-30 15:30:13.727   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 271us total 12.506ms
,08-30 15:30:13.760  1036  1111 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6907 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:30:13.761  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 15:30:13.762  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:13.762  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:30:13.762  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:30:13.762  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:13.762  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:13.762  1036  1442 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:13.763  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:30:13.763  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:13.765  3905  3905 V BtOppService: onDestroy
08-30 15:30:13.766  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.766  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.767  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.767  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.768  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.768  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.769  1036  1392 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:30:13.769  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.769  1036  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.769  1036  1442 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:13.770  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.770  1036  1442 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:13.770  1036  1442 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:13.770  1036  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@21e94c67
08-30 15:30:13.770  1036  1442 D NetworkManagementService: Removing idletimer
08-30 15:30:13.770  1036  1442 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:13.771  1036  1442 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 15:30:13.771  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 15:30:13.771  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 15:30:13.771  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:13.772  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:30:13.772  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 15:30:13.772  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 15:30:13.772  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-30 15:30:13.772  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 15:30:13.772  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:30:13.772  1036  ,1389 D LGWifiP2pService: P2pDisablingState
08-30 15:30:13.772  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:30:13.772  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:30:13.772  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:30:13.773  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:30:13.773  1036  1389 D LGWifiP2pService: P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.773  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:30:13.773  1036  1389 D LGWifiP2pService: p2p socket connection lost
08-30 15:30:13.773  1036  1389 D LGWifiP2pService: P2pDisabledState
08-30 15:30:13.773  1036  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.773  1036  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:30:13.774  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.774  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:13.775  1036  1392 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:13.775  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:13.775  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 15:30:13.775  1942  1942 D WfdsService: WifiP2pState is changed : false
08-30 15:30:13.775  1942  2352 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 15:30:13.775  1942  2352 D WfdsService: Set the WFDS Monitor: false
08-30 15:30:13.775  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 15:30:13.775  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:30:13.775  2725  2725 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:30:13.776  3905  3905 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 15:30:13.776  1942  2352 D WfdsMonitor: WFDS Monitor is stopped
08-30 15:30:13.776  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:30:13.776  1942  2777 D CtrlSupplicant: Received on exit socket, terminate
08-30 15:30:13.776  1942  2777 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 15:30:13.776  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:30:13.776  1942  2777 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 15:30:13.776  1942  2352 D WfdsService: STATE : WfdsDisabledState - enter
08-30 15:30:13.776  1942  2777 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 15:30:13.776  1942  2352 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 15:30:13.777  1942  2356 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 15:30:13.777  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:30:13.777   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:30:13.778  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.778  1036  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.779  1036  1392 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 15:30:13.780  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 15:30:13.781  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:13.781  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:13.781  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:30:13.781  1036  1392 D WifiNative-p2p0: TERMINATE: returned true
08-30 15:30:13.781  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:30:13.781  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:30:13.781  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:30:13.784  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 15:30:13.784  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:13.784  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 15:30:13.785  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-30 15:30:13.786  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.786  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:13.786  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.786  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.786  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:13.786  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:13.786  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:13.786  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:13.786  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:13.788  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.788  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:13.790  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.790  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:13.790  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:13.790  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:13.790  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:13.790  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:13.790  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:13.790  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:13.790  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:30:13.791  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:13.791  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:30:13.814  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:30:13.814  1036  2860 D DhcpStateMachine: StoppedState
08-30 15:30:13.814  1036  2860 D DhcpStateMachine: StoppedState{ when=-37ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:13.814  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:13.815  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:13.816  1036  1392 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-30 15:30:13.816  1036  1392 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 15:30:13.823  6907  6907 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:30:13.823  6907  6907 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-30 15:30:13.824  6907  6907 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:30:13.824  6907  6907 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-30 15:30:13.825  6907  6907 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 15:30:13.825  6907  6907 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:30:13.829  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:30:13.830  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:13.830  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:13.830  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 15:30:13.830  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:13.831  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:13.844  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:13.850  6888  6888 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 15:30:13.850  6888  6888 W LG Account v2.2: No ProfileInfo entries
08-30 15:30:13.850  6888  6888 I LG Account v2.2: isEnabled: false
08-30 15:30:13.850  6888  6888 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 15:30:13.850  6888  6888 I Feature : [Lifetracker]Country: EU
08-30 15:30:13.850  6888  6888 I Feature : [Lifetracker]Operator: OPEN
08-30 15:30:13.850  6888  6888 I Feature : [Lifetracker]Ranking support: false
08-30 15:30:13.850  6888  6888 I Feature : [Lifetracker]Comfort support: false
08-30 15:30:13.850  6888  6888 I Feature : [Lifetracker]Accessory: true
08-30 15:30:13.850  6888  6888 I Feature : [Lifetracker]Health device: true
08-30 15:30:13.851  6888  6888 I Feature : [Lifetracker]Extra Pedometer: false
08-30 15:30:13.851  6888  6888 I Feature : [Lifetracker]Blood glucose device: false
08-30 15:30:13.851  6888  6888 I Feature : [Lifetracker]Device Number: 3
08-30 15:30:13.858  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:13.870  2725  2725 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 15:30:13.870  2725  2725 I wpa_supplicant: monitor socket send errors count : 1
08-30 15:30:13.870  2725  2725 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-2\x00 that cannot receive messages
08-30 15:30:13.879  1036  2773 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 15:30:13.879  1036  2773 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-30 15:30:13.887  1036  1051 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6927 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 15:30:13.888  1036  1051 I ActivityManager: Killing 6372:com.android.defcontainer/u0a4 (adj 15): empty #17
08-30 15:30:13.916  2725  2725 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:30:13.917  1036  2773 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 15:30:13.917  1036  2773 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:30:13.917  1036  2773 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:30:13.917  2725  2725 W wpa_supplicant: USIM:  scard_deinit function
,08-30 15:30:13.918  1036  1118 D Tethering: InitialState.processMessage what=4
08-30 15:30:13.918  1036  2773 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 15:30:13.918  1036  2773 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:13.918  1036  2773 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:13.918  1036  1392 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=200773
,08-30 15:30:13.919  1036  1392 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=200773
08-30 15:30:13.919  1036  1392 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=200773  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 15:30:13.919  1036  1392 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=200773  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 15:30:13.931  1036  2051 W libprocessgroup: failed to open /acct/uid_10004/pid_6372/cgroup.procs: No such file or directory
,08-30 15:30:13.934  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:30:13.940  1036  1392 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:13.940  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:13.982  6907  6907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 15:30:13.987  3905  3905 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:30:13.987  3905  3905 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:13.987  3905  3905 V BluetoothPbapReceiver: ***********state = 13
08-30 15:30:13.988  1036  1118 D BluetoothManagerService: Message: 20
08-30 15:30:13.988  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d795ecc:true
08-30 15:30:13.990  3905  3905 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 15:30:13.991  6927  6927 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:30:13.992  3905  3905 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:13.992  3905  3905 V BluetoothPbapService: state: 13
08-30 15:30:13.992  3905  3905 V BluetoothPbapService: Pbap Service closeService in
08-30 15:30:13.995  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:30:13.997  3905  3905 V BluetoothPbapService: successfully stopped pbap service
08-30 15:30:13.997  3905  3905 V BluetoothPbapService: Pbap Service closeService out
08-30 15:30:13.997  3905  3905 V BluetoothPbapService: Pbap Service onDestroy
08-30 15:30:13.997  3905  3905 V BluetoothPbapService: Pbap Service closeService in
08-30 15:30:13.997  3905  3905 V BluetoothPbapService: Pbap Service closeService out
08-30 15:30:13.997  3905  3905 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-30 15:30:13.998  1036  1118 D BluetoothManagerService: Message: 30
08-30 15:30:13.999  6927  6927 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:30:13.999  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:14.003  1036  1941 I ActivityManager: Killing 6504:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-30 15:30:14.010  2725  2725 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 15:30:14.011  1036  2773 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 15:30:14.011  1036  2773 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 15:30:14.011  1036  2773 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-30 15:30:14.013  1036  1392 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-30 15:30:14.023  6765  6765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 15:30:14.044  1036  1575 W libprocessgroup: failed to open /acct/uid_10008/pid_6504/cgroup.procs: No such file or directory
,08-30 15:30:14.049  1036  1118 D BluetoothManagerService: Message: 30
08-30 15:30:14.053  6907  6907 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 15:30:14.056  6907  6907 D BluetoothMap: Create BluetoothMap proxy object
08-30 15:30:14.056  1036  1118 D BluetoothManagerService: Message: 30
08-30 15:30:14.063  1036  1118 D BluetoothManagerService: Message: 30
,08-30 15:30:14.066  6907  6907 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 15:30:14.069  6907  6907 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-30 15:30:14.094  6907  6907 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-30 15:30:14.099  6907  6907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-30 15:30:14.117  1036  1392 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 15:30:14.118  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:30:14.118  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:30:14.118  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:30:14.118  6907  6907 D DockEventReceiver: finishStartingService: stopping service
08-30 15:30:14.118  1942  1942 D WfdsService: Supplicant Connection state is changed : false
08-30 15:30:14.118  1942  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 15:30:14.119  1942  2352 D WfdsService: Set the WFDS Monitor: false
08-30 15:30:14.119  1942  2352 D WfdsMonitor: WFDS Monitor is stopped
,08-30 15:30:14.126  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 15:30:14.130  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 15:30:14.130  2507  2507 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:14.131  1036  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 15:30:14.131  1036  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 15:30:14.132  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:14.134  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:14.138  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:14.160  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:14.196  6907  6907 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 15:30:14.196  6907  6907 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:30:14.207  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:14.207  6907  6907 D BluetoothInputDevice: Proxy object connected
08-30 15:30:14.208  6907  6907 D HidProfile: Bluetooth service connected
,08-30 15:30:14.210  6907  6907 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 15:30:14.211  6907  6907 D PanProfile: Bluetooth service connected
08-30 15:30:14.212  6907  6907 D BluetoothMap: Proxy object connected
,08-30 15:30:14.213  6907  6907 D MapProfile: Bluetooth service connected
,08-30 15:30:14.213  6907  6907 D BluetoothMap: getConnectedDevices()
08-30 15:30:14.214  6907  6907 D BluetoothMap: Bluetooth is Not enabled
08-30 15:30:14.214  6907  6907 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 15:30:14.216  6907  6907 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 15:30:14.220  6907  6907 D BluetoothPermissionRequest: onReceive
08-30 15:30:14.224  6907  6907 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 15:30:14.235  1036  1051 I ActivityManager: Killing 6026:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-30 15:30:14.237  6907  6907 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:30:14.282  1036  1781 W libprocessgroup: failed to open /acct/uid_10011/pid_6026/cgroup.procs: No such file or directory
,08-30 15:30:14.282  3905  3905 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 15:30:14.282  3905  3905 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 15:30:14.284  3905  3905 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 15:30:14.375  1036  1998 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6958 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-30 15:30:14.377  3905  3905 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:14.377  3905  3905 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 15:30:14.380  3905  3905 V BluetoothFtpService: Ftp Service onStartCommand
08-30 15:30:14.380  3905  3905 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:14.381  3905  3905 V BluetoothFtpService: Ftp Service closeService
08-30 15:30:14.381  3905  3905 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 15:30:14.385  3905  3905 V BluetoothFtpService: successfully stopped ftp service
08-30 15:30:14.386  3905  3905 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:30:14.386  3905  3905 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:30:14.386  3905  3905 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:30:14.386  3905  3905 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:14.386  3905  3905 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 15:30:14.387  3905  3905 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-30 15:30:14.389  3905  3905 V BluetoothFtpService: Ftp Service onDestroy
08-30 15:30:14.389  3905  3905 V BluetoothFtpService: Ftp Service closeService
,08-30 15:30:14.441  1036  1896 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6975 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 15:30:14.442  3905  3905 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:14.442  3905  3905 V BluetoothSapService: state: 13
08-30 15:30:14.442  3905  3905 V BluetoothSapService: Stopping SAP server process
08-30 15:30:14.444  3905  3905 V BluetoothSapService: Sap Service closeSapService in
08-30 15:30:14.444  3905  3905 V BluetoothSapService: Close listen Socket : 
08-30 15:30:14.444  3905  3905 V BluetoothSapService: Close rfcomm Socket : 
08-30 15:30:14.444  3905  3905 V BluetoothSapService: Close sapd  Socket : 
08-30 15:30:14.451  3905  3905 V BluetoothSapService: Sap Service closeSapService out
08-30 15:30:14.451  3905  3905 V BluetoothSapService: Sap Service onDestroy
08-30 15:30:14.451  3905  3905 V BluetoothSapService: Sap Service closeSapService in
08-30 15:30:14.451  3905  3905 V BluetoothSapService: Close listen Socket : 
08-30 15:30:14.451  3905  3905 V BluetoothSapService: Close rfcomm Socket : 
08-30 15:30:14.451  3905  3905 V BluetoothSapService: Close sapd  Socket : 
08-30 15:30:14.452  3905  3905 V BluetoothSapService: Sap Service closeSapService out
08-30 15:30:14.476  6958  6958 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 15:30:14.508  6958  6958 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-30 15:30:14.508  6975  6975 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 15:30:14.532  1036  1652 I ActivityManager: Killing 6051:com.android.contacts/u0a19 (adj 15): empty #17
,08-30 15:30:14.546  6958  6958 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-30 15:30:14.546  6958  6958 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-30 15:30:14.547  6958  6958 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-30 15:30:14.547  6958  6958 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-30 15:30:14.548  6958  6958 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-30 15:30:14.550  6958  6958 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-30 15:30:14.555  6958  6958 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-30 15:30:14.617  1036  2051 W libprocessgroup: failed to open /acct/uid_10019/pid_6051/cgroup.procs: No such file or directory
,08-30 15:30:14.641  3905  3993 D bt_hci_bdroid: cleanup
08-30 15:30:14.641  3905  4077 I bt_lpm  : LPM is already off!!!
08-30 15:30:14.642  3905  4176 I bt_userial_mct: exiting userial_read_thread
08-30 15:30:14.642  3905  4176 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-30 15:30:14.642  3905  4074 W bt-btif : ag scb idx 1 not allocated
,08-30 15:30:14.642  3905  4074 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:14.643  3905  4074 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:30:14.644  3905  4074 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:14.644  3905  4074 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:30:14.644  3905  4074 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 15:30:14.644  3905  3993 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 15:30:14.644  3905  4077 I bt_vendor: hw_epilog_process
08-30 15:30:14.645  3905  3993 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 15:30:14.645  3905  3993 D bt_userial_mct: userial_close
08-30 15:30:14.645  3905  3993 E bt_userial_mct: pthread_join() FAILED result:3
08-30 15:30:14.645  3905  3993 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 15:30:14.651  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:14.657  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:30:14.687  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 15:30:14.690  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:14.693  6958  6958 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-30 15:30:14.694  6927  6927 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:30:14.694  6927  6927 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:30:14.694  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:14.698  6958  6958 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-30 15:30:14.699  3905  3993 D bt_hci_bdroid: set_power 0
08-30 15:30:14.699  3905  3993 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 15:30:14.699  3905  3993 I bt_vendor: bluetooth satus is on
08-30 15:30:14.699  3905  3993 I bt_vendor: bt-vendor : resetting BT status
08-30 15:30:14.699  3905  3993 I bt_vendor: Starting hciattach daemon
08-30 15:30:14.700  3905  3993 I bt_vendor: try to set false
08-30 15:30:14.700  3905  3993 I bt_vendor: Starting hciattach daemon
08-30 15:30:14.700  3905  3993 I bt_vendor: try to set false
08-30 15:30:14.701  3905  3993 I bt_vendor: cleanup
08-30 15:30:14.702  3905  4074 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 15:30:14.702  3905  3993 I GKI_LINUX: GKI_exit_task 0 done
08-30 15:30:14.702  3905  3993 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 15:30:14.704  3905  3990 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 15:30:14.704  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:14.707  3905  3905 D HeadsetService: Received stop request...Stopping profile...
08-30 15:30:14.708  3905  3905 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 15:30:14.709  3905  4022 D HeadsetStateMachine: Exit Disconnected: -1
08-30 15:30:14.709  3905  3905 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:30:14.709  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5cabe06
08-30 15:30:14.710  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-30 15:30:14.710  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 15:30:14.711  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-30 15:30:14.711  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-30 15:30:14.712  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-30 15:30:14.713  3905  3905 D A2dpService: Received stop request...Stopping profile...
08-30 15:30:14.713  3905  4058 D A2dpStateMachine: Exit Disconnected: -1
08-30 15:30:14.714  3905  3905 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 15:30:14.715  3905  3990 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 15:30:14.717  3905  3905 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 15:30:14.717  3905  3905 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 15:30:14.717  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5cabe06
08-30 15:30:14.719  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-30 15:30:14.719  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 15:30:14.719  3905  3905 D HidService: Received stop request...Stopping profile...
08-30 15:30:14.720  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5cabe06
08-30 15:30:14.721  3905  3905 D HealthService: Received stop request...Stopping profile...
08-30 15:30:14.721  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5cabe06
08-30 15:30:14.722  3905  3905 D HeadsetStateMachine: Unbinding service...
08-30 15:30:14.723  3905  3905 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:30:14.723  3905  3905 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:30:14.723  3905  3905 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:30:14.723  3905  3905 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:30:14.723  3905  3905 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 15:30:14.723  3905  3905 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:30:14.723  3905  3905 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 15:30:14.724  3905  3905 D PanService: Received stop request...Stopping profile...
08-30 15:30:14.725  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5cabe06
08-30 15:30:14.726  3905  3905 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:30:14.727  3905  3905 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:30:14.727  3905  3905 D BtGatt.GattService: stop()
08-30 15:30:14.727  3905  3905 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 15:30:14.727  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:14.728  6907  6907 D BluetoothInputDevice: Proxy object disconnected
08-30 15:30:14.728  6907  6907 D HidProfile: Bluetooth service disconnected
08-30 15:30:14.728  6907  6907 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 15:30:14.728  6907  6907 D PanProfile: Bluetooth service disconnected
,08-30 15:30:14.731  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5cabe06
08-30 15:30:14.733  3905  3905 D BluetoothMapService: Received stop request...Stopping profile...
08-30 15:30:14.733  3905  3905 D BluetoothMapService: stop()
08-30 15:30:14.734  3905  3905 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 15:30:14.735  3905  3905 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 15:30:14.735  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5cabe06
08-30 15:30:14.736  3905  3905 I BluetoothA2dpServiceJni: cleanupNative
08-30 15:30:14.736  3905  4059 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 15:30:14.739  3905  3905 I GKI_LINUX: GKI_exit_task 2 done
08-30 15:30:14.739  3905  3905 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 15:30:14.740  3905  3905 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 15:30:14.740  3905  3905 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:30:14.740  3905  3905 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:30:14.740  3905  3905 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:30:14.740  3905  3905 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:30:14.740  3905  3905 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:30:14.740  3905  3905 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:30:14.741  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:30:14.741  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:14.743  3905  3905 V BluetoothMapService: Handler(): got msg=4
08-30 15:30:14.743  6907  6907 D BluetoothMap: Proxy object disconnected
08-30 15:30:14.743  3905  3905 D BluetoothMapService: MAP Service closeService in
08-30 15:30:14.743  6907  6907 D MapProfile: Bluetooth service disconnected
08-30 15:30:14.743  3905  3905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:30:14.743  3905  3905 V BluetoothMapService: MAP Service closeService out
08-30 15:30:14.744  3905  3990 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 15:30:14.744  3905  3990 D BluetoothAdapterProperties: Setting state to 10
08-30 15:30:14.744  3905  3990 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 15:30:14.744  3905  3905 D BluetoothMapService: cleanup()
08-30 15:30:14.744  3905  3905 D BluetoothMapService: MAP Service closeService in
08-30 15:30:14.745  3905  3905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:30:14.745  3905  3905 V BluetoothMapService: MAP Service closeService out
08-30 15:30:14.745  1036  1118 D BluetoothManagerService: Message: 60
08-30 15:30:14.745  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 15:30:14.745  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-30 15:30:14.745  6907  6922 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:30:14.746  3905  3990 I BluetoothAdapterState: Entering OffState
08-30 15:30:14.746  6907  6923 D BluetoothPan: onBluetoothStateChange on: false
08-30 15:30:14.747  6907  6922 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:30:14.747  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:30:14.748  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:30:14.748  1853  2613 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:30:14.748  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:30:14.749  1853  4023 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:30:14.753  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:14.753  1853  4020 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 15:30:14.757  6927  6927 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:30:14.757  6927  6927 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:30:14.757  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:14.758  6907  6923 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:30:14.761  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:14.763  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 15:30:14.763  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 15:30:14.765  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 15:30:14.765  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 15:30:14.765  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@a77f75d mBinding = false
08-30 15:30:14.766  1036  1118 D BluetoothManagerService: Sending unbind request.
,08-30 15:30:14.769  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 15:30:14.773  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:14.774  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:30:14.774  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:14.774  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:14.775  1942  2124 D LGBluetoothAPIService: Message: 2
08-30 15:30:14.775  1942  2124 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@266ec4f1 mBinding = false
08-30 15:30:14.776  1942  2124 D LGBluetoothAPIService: Sending unbind request.
08-30 15:30:14.780  3905  3993 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 15:30:14.781  3905  3905 I GKI_LINUX: GKI_exit_task 1 done
08-30 15:30:14.781  3905  3905 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 15:30:14.781  3905  3905 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 15:30:14.781  3905  3905 I art     : --- WEIRD: removing null entry 246
08-30 15:30:14.781  3905  3905 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-30 15:30:14.781  3905  3905 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 15:30:14.782  3905  3905 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-30 15:30:14.783  1602  1602 D BluetoothAdapter: 92743774: getState() :  mService = null. Returning STATE_OFF
08-30 15:30:14.783  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:14.783  1602  1602 D BluetoothAdapter: 92743774: getState() :  mService = null. Returning STATE_OFF
08-30 15:30:14.784  6907  6907 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 15:30:14.785  6907  6907 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 15:30:14.785  6907  6907 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 15:30:14.788  6907  6907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 15:30:14.791  3905  3905 I art     : System.exit called, status: 0
08-30 15:30:14.791  3905  3905 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 15:30:14.798  6907  6907 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:30:14.805  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:30:14.805  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:14.808  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:30:14.815   316  1402 V AudioFlinger: 3905 died, releasing its sessions
08-30 15:30:14.815   316  1402 V AudioFlinger:  pid 1853 @ 0
08-30 15:30:14.815   316  1402 V AudioFlinger:  pid 3456 @ 1
08-30 15:30:14.815   316  1402 V AudioFlinger:  pid 3456 @ 2
08-30 15:30:14.816  6907  6907 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-30 15:30:14.863  1036  1941 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7003 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 15:30:14.874  1036  1652 I ActivityManager: Process com.android.bluetooth (pid 3905) has died
08-30 15:30:14.875  1036  1652 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-30 15:30:14.883  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:30:14.899  6907  6907 D BluetoothPermissionRequest: onReceive
,08-30 15:30:14.904  6907  6907 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 15:30:14.905  6907  6907 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 15:30:14.910  6907  6907 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:30:14.974  1036  1978 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7021 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 15:30:15.031  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:30:15.034  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:30:15.044  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:30:15.061  7021  7021 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 15:30:15.061  7021  7021 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:30:15.062  7021  7021 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 15:30:15.062  7021  7021 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:30:15.069  7003  7041 W FormManager: Network not available. Please check & try again.
08-30 15:30:15.070  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:30:15.070  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:30:15.070  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:30:15.070  6907  6907 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:30:15.071  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 15:30:15.079  7003  7042 V FormManager: Network unavailable.
,08-30 15:30:15.082  7021  7021 D BluetoothAdapterApp: Loading JNI Library
08-30 15:30:15.083  6907  6907 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:30:15.083  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 15:30:15.083  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:30:15.084  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:30:15.084  6907  6907 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:30:15.084  6907  6907 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:30:15.084  7003  7042 V FormManager: Network unavailable.
08-30 15:30:15.088  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:30:15.088  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:30:15.090  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:15.092  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:30:15.099  4351  7045 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:30:15.103  4351  7046 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:30:15.103  4351  7046 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:30:15.106  6927  6927 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 15:30:15.106  6927  6927 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-30 15:30:15.106  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:15.111  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:30:15.114  7003  7048 W FormManager: Network not available. Please check & try again.
08-30 15:30:15.117  7003  7049 V FormManager: Network unavailable.
,08-30 15:30:15.120  7003  7049 V FormManager: Network unavailable.
08-30 15:30:15.121  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:15.121  7021  7021 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@349b72cf Instance Count = 1
08-30 15:30:15.127  7021  7021 D BluetoothAdapterApp: onCreate
08-30 15:30:15.129  1036  1941 I ActivityManager: Killing 6556:com.lge.email/u0a23 (adj 15): empty #17
,08-30 15:30:15.150  7021  7021 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-30 15:30:15.150  7021  7021 D ProfileConfigQcom: Adding HeadsetService
08-30 15:30:15.150  7021  7021 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 15:30:15.150  7021  7021 D ProfileConfigQcom: Adding A2dpService
08-30 15:30:15.150  7021  7021 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 15:30:15.151  7021  7021 D ProfileConfigQcom: Adding HidService
08-30 15:30:15.151  7021  7021 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 15:30:15.151  7021  7021 D ProfileConfigQcom: Adding HealthService
08-30 15:30:15.151  7021  7021 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 15:30:15.152  7021  7021 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 15:30:15.152  7021  7021 D ProfileConfigQcom: Adding PanService
08-30 15:30:15.152  7021  7021 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 15:30:15.153  7021  7021 D ProfileConfigQcom: Adding GattService
08-30 15:30:15.153  7021  7021 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 15:30:15.153  7021  7021 D ProfileConfigQcom: Adding BluetoothMapService
08-30 15:30:15.153  7021  7021 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 15:30:15.155  7021  7021 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 15:30:15.171  1036  1959 W libprocessgroup: failed to open /acct/uid_10023/pid_6556/cgroup.procs: No such file or directory
,08-30 15:30:15.174  6907  6907 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-30 15:30:15.181  7021  7021 V LGMDMManagerInternal: Create singleton instance
08-30 15:30:15.187  6958  6958 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-30 15:30:15.189  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 15:30:15.189  6958  6958 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-30 15:30:15.218  6958  6958 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:15.218  6958  6958 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:15.225  6958  6958 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-30 15:30:15.225  6958  6958 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-30 15:30:15.225  6958  6958 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-30 15:30:15.225  6958  6958 V SoundPool: doLoad: loading sample sampleID=1
08-30 15:30:15.226  6958  6958 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-30 15:30:15.231  6958  7053 V SoundPool: Start decode
08-30 15:30:15.231  6958  7053 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-30 15:30:15.233   316  1402 V MediaPlayerService: decode(23, 10857164, 17813)
08-30 15:30:15.233   316  1402 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-30 15:30:15.232  6659  6659 D UEI.SmartControl: QS Service created
08-30 15:30:15.234   316  1402 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-30 15:30:15.234   316  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-30 15:30:15.234   316  1402 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-30 15:30:15.234   316  1402 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-30 15:30:15.234   316  1402 V MediaPlayerService: player type = 3
08-30 15:30:15.234   316  1402 V AwesomePlayer: AwesomePlayer create()
08-30 15:30:15.234   316  1402 V AwesomePlayer: reset_l() 
08-30 15:30:15.234   316  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:30:15.234  6958  6958 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-30 15:30:15.234   316  1402 V AwesomePlayer: setAudioSink() 
08-30 15:30:15.234   316  1402 V AwesomePlayer: reset_l() 
08-30 15:30:15.234   316  1402 V AudioCache: notify(0xb1432240, 8, 0, 0)
08-30 15:30:15.234   316  1402 V AudioCache: ignored
08-30 15:30:15.234   316  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:30:15.235   316  1402 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-30 15:30:15.235   316  1402 V AwesomePlayer: setDataSource_l dataSource
08-30 15:30:15.235   316  1402 V LGParserOSAL: SniffLGParser start
08-30 15:30:15.235   316  1402 V LGParserOSAL: MainType:5, SubType=0
08-30 15:30:15.235   316  1402 V LGParserOSAL: #### check Mime : application/ogg
08-30 15:30:15.235   316  1402 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-30 15:30:15.235   316  1402 E MediaExtractor: Use LGExtractor :application/ogg 
08-30 15:30:15.242  6659  6659 I UEI.SmartControl: Service initServices...
08-30 15:30:15.242  6958  6958 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 15:30:15.242  6659  6659 D UEI.SmartControl: QS start get config
08-30 15:30:15.243  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-30 15:30:15.263   316  1402 V LGParserOSAL: supported mime: application/ogg
08-30 15:30:15.263   316  1402 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-30 15:30:15.263   316  1402 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-30 15:30:15.263   316  1402 V AwesomePlayer: mBitrate = -1 bits/sec
08-30 15:30:15.263   316  1402 V AwesomePlayer: AudioTrack Setting
08-30 15:30:15.263   316  1402 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-30 15:30:15.263   316  1402 V AwesomePlayer: setAudioSource() 
08-30 15:30:15.263   316  1402 V MediaPlayerService: prepare
08-30 15:30:15.263   316  1402 V AwesomePlayer: prepareAsync_l() 
08-30 15:30:15.263   316  1402 V MediaPlayerService: wait for prepare
,08-30 15:30:15.265   316  7054 V AwesomePlayer: onPrepareAsyncEvent() 
08-30 15:30:15.265   316  7054 V AwesomePlayer: initAudioDecoder() 
08-30 15:30:15.265   316  7054 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 15:30:15.265   316  7054 V AudioSystem: isOffloadSupported()
08-30 15:30:15.265   316  7054 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 15:30:15.265   316  7054 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 15:30:15.265   316  7054 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 15:30:15.265   316  7054 V AwesomePlayer: getUseOffload() = 0 
08-30 15:30:15.265   316  7054 V OMXCodec: OMXCodec::Create
08-30 15:30:15.265   316  7054 V OMXCodec: findMatchingCodecs()
08-30 15:30:15.265   316  7054 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-30 15:30:15.265   316  7054 V OMXCodec: matchingCodecs.size()=1
08-30 15:30:15.265   316  7054 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-30 15:30:15.266   316  7054 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-30 15:30:15.267   316  7054 V LGCodecAdapter: LG Codec Adapter start
08-30 15:30:15.267   316  7054 V OMXCodec: OMXCodec Createtor
08-30 15:30:15.267   316  7054 V OMXCodec: setComponentRole
08-30 15:30:15.267   316  7054 V OMXCodec: configureCodec protected=0
08-30 15:30:15.267   316  7054 V LGCodecAdapter: called getLGCodecSpecificData
08-30 15:30:15.267   316  7054 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-30 15:30:15.267   316  7054 V LGCodecOSAL: Called LGconfigureCodecMETA
08-30 15:30:15.267   316  7054 V LGCodecOSAL: Called LGconfigureCodecMSG
08-30 15:30:15.267   316  7054 V LGCodecOSAL: Not support LGCodec
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 15:30:15.267   316  7054 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-30 15:30:15.267   316  7054 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-30 15:30:15.267   316  7054 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-30 15:30:15.267   316  7054 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-30 15:30:15.267   316  7054 V AudioSystem: isOffloadSupported()
08-30 15:30:15.267   316  7054 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-30 15:30:15.267   316  7054 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-30 15:30:15.267   316  7054 V OMXCodec: init()
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-30 15:30:15.267   316  7054 V OMXCodec: allocateBuffers
08-30 15:30:15.267   316  7054 V OMXCodec: allocateBuffersOnPort portIndex=0
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410b00 on input port
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410b50 on input port
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410ba0 on input port
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410bf0 on input port
08-30 15:30:15.267   31,6  7054 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 15:30:15.267   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 15:30:15.267  6958  6958 V LGMDMManager: Create singleton instance
08-30 15:30:15.268   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410c40 on output port
08-30 15:30:15.268   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410dd0 on output port
08-30 15:30:15.268   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
08-30 15:30:15.268   316  7054 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb16a9150 on output port
08-30 15:30:15.268   316  7054 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 15:30:15.268   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 15:30:15.268   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 15:30:15.268   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-30 15:30:15.268   316  7054 V OMXCodec: init() mAsyncCompletion wait!!! 
08-30 15:30:15.268   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-30 15:30:15.268   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-30 15:30:15.268   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-30 15:30:15.268   316  7054 V OMXCodec: init() mAsyncCompletion wait free! 
08-30 15:30:15.268   316  7054 V AwesomePlayer: finishAsyncPrepare_l() 
08-30 15:30:15.268   316  7054 V AudioCache: notify(0xb1432240, 5, 0, 0)
08-30 15:30:15.268   316  7054 V AudioCache: ignored
08-30 15:30:15.268   316  7054 V AudioCache: notify(0xb1432240, 1, 0, 0)
08-30 15:30:15.268   316  7054 V AudioCache: prepared
08-30 15:30:15.268   316  1402 V AudioCache: wait - success
08-30 15:30:15.268   316  1402 V MediaPlayerService: start
08-30 15:30:15.268   316  1402 V AwesomePlayer: play_l() 
08-30 15:30:15.268   316  1402 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-30 15:30:15.268   316  1402 V AwesomePlayer: createAudioPlayer_l
08-30 15:30:15.268   316  1402 V AwesomePlayer: seekAudioIfNecessary_l() 
08-30 15:30:15.268   316  1402 V AwesomePlayer: startAudioPlayer_l() 
08-30 15:30:15.268   316  1402 D AudioPlayer: start of Playback, useOffload 0
08-30 15:30:15.269   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 15:30:15.269   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-30 15:30:15.270   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-30 15:30:15.270   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-30 15:30:15.270   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-30 15:30:15.270   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-30 15:30:15.270   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
,08-30 15:30:15.270   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 15:30:15.270   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957052992
08-30 15:30:15.270   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957053392
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975904
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2976551248
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-30 15:30:15.271   316  7056 V OMXCodec: allocateBuffersOnPort portIndex=1
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on output port
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410dd0 on output port
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb0410c40 on output port
,08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb16a92e0 on output port
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-30 15:30:15.271   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-30 15:30:15.272   316  1402 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-30 15:30:15.272   316  1402 V AudioCache: notify(0xb1432240, 6, 0, 0)
08-30 15:30:15.272   316  1402 V AudioCache: ignored
08-30 15:30:15.272   316  1402 V MediaPlayerService: wait for playback complete
,08-30 15:30:15.273   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.273   316  7057 V AudioCache: memcpy(0xac300000, 0xb57be000, 4096)
08-30 15:30:15.274   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.274   316  7057 V AudioCache: memcpy(0xac301000, 0xb57be000, 4096)
08-30 15:30:15.274   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.274   316  7057 V AudioCache: memcpy(0xac302000, 0xb57be000, 4096)
08-30 15:30:15.275   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.275   316  7057 V AudioCache: memcpy(0xac303000, 0xb57be000, 4096)
,08-30 15:30:15.275   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.275   316  7057 V AudioCache: memcpy(0xac304000, 0xb57be000, 4096)
08-30 15:30:15.276   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.276   316  7057 V AudioCache: memcpy(0xac305000, 0xb57be000, 4096)
08-30 15:30:15.276   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.276   316  7057 V AudioCache: memcpy(0xac306000, 0xb57be000, 4096)
08-30 15:30:15.276   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.276   316  7057 V AudioCache: memcpy(0xac307000, 0xb57be000, 4096)
,08-30 15:30:15.277   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.277   316  7057 V AudioCache: memcpy(0xac308000, 0xb57be000, 4096)
08-30 15:30:15.277   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.277   316  7057 V AudioCache: memcpy(0xac309000, 0xb57be000, 4096)
08-30 15:30:15.278   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.278   316  7057 V AudioCache: memcpy(0xac30a000, 0xb57be000, 4096)
08-30 15:30:15.278   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.278   316  7057 V AudioCache: memcpy(0xac30b000, 0xb57be000, 4096)
08-30 15:30:15.279   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.279   316  7057 V AudioCache: memcpy(0xac30c000, 0xb57be000, 4096)
08-30 15:30:15.279   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.279   316  7057 V AudioCache: memcpy(0xac30d000, 0xb57be000, 4096)
08-30 15:30:15.280  7021  7021 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:15.281   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.281   316  7057 V AudioCache: memcpy(0xac30e000, 0xb57be000, 4096)
08-30 15:30:15.282   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.282   316  7057 V AudioCache: memcpy(0xac30f000, 0xb57be000, 4096)
08-30 15:30:15.282   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.282   316  7057 V AudioCache: memcpy(0xac310000, 0xb57be000, 4096)
08-30 15:30:15.283   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.283   316  7057 V AudioCache: memcpy(0xac311000, 0xb57be000, 4096)
08-30 15:30:15.284   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.285   316  7057 V AudioCache: memcpy(0xac312000, 0xb57be000, 4096)
08-30 15:30:15.285  7021  7021 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:30:15.286  7021  7021 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:30:15.286  7021  7021 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:30:15.286   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.286   316  7057 V AudioCache: memcpy(0xac313000, 0xb57be000, 4096)
08-30 15:30:15.287   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.287   316  7057 V AudioCache: memcpy(0xac314000, 0xb57be000, 4096)
08-30 15:30:15.287  7021  7021 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:15.287  7021  7021 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-30 15:30:15.287   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.287   316  7057 V AudioCache: memcpy(0xac315000, 0xb57be000, 4096)
08-30 15:30:15.288   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.288   316  7057 V AudioCache: memcpy(0xac316000, 0xb57be000, 4096)
08-30 15:30:15.288   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.288   316  7057 V AudioCache: memcpy(0xac317000, 0xb57be000, 4096)
08-30 15:30:15.289   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.289   316  7057 V AudioCache: memcpy(0xac318000, 0xb57be000, 4096)
08-30 15:30:15.291   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.291   316  7057 V AudioCache: memcpy(0xac319000, 0xb57be000, 4096)
08-30 15:30:15.292   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.292   316  7057 V AudioCache: memcpy(0xac31a000, 0xb57be000, 4096)
08-30 15:30:15.292   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.293   316  7057 V AudioCache: memcpy(0xac31b000, 0xb57be000, 4096)
08-30 15:30:15.293   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.293   316  7057 V AudioCache: memcpy(0xac31c000, 0xb57be000, 4096)
08-30 15:30:15.294   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.294   316  7057 V AudioCache: memcpy(0xac31d000, 0xb57be000, 4096)
08-30 15:30:15.294   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.294   316  7057 V AudioCache: memcpy(0xac31e000, 0xb57be000, 4096)
08-30 15:30:15.295   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.295   316  7057 V AudioCache: memcpy(0xac31f000, 0xb57be000, 4096)
08-30 15:30:15.295   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.295   316  7057 V AudioCache: memcpy(0xac320000, 0xb57be000, 4096)
08-30 15:30:15.295   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.295   316  7057 V AudioCache: memcpy(0xac321000, 0xb57be000, 4096)
08-30 15:30:15.296   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.296   316  7057 V AudioCache: memcpy(0xac322000, 0xb57be000, 4096)
08-30 15:30:15.296   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.296   316  7057 V AudioCache: memcpy(0xac323000, 0xb57be000, 4096)
08-30 15:30:15.296  6975  6975 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-30 15:30:15.296   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.297   316  7057 V AudioCache: memcpy(0xac324000, 0xb57be000, 4096)
08-30 15:30:15.297   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.297   316  7057 V AudioCache: memcpy(0xac325000, 0xb57be000, 4096)
08-30 15:30:15.297   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.297   316  7057 V AudioCache: memcpy(0xac326000, 0xb57be000, 4096)
08-30 15:30:15.298   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.298   316  7057 V AudioCache: memcpy(0xac327000, 0xb57be000, 4096)
08-30 15:30:15.298   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.298   316  7057 V AudioCache: memcpy(0xac328000, 0xb57be000, 4096)
08-30 15:30:15.299   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.299   316  7057 V AudioCache: memcpy(0xac329000, 0xb57be000, 4096)
08-30 15:30:15.299   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.299   316  7057 V AudioCache: memcpy(0xac32a000, 0xb57be000, 4096)
08-30 15:30:15.300   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.300   316  7057 V AudioCache: memcpy(0xac32b000, 0xb57be000, 4096)
08-30 15:30:15.300   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.300   316  7057 V AudioCache: memcpy(0xac32c000, 0xb57be000, 4096)
08-30 15:30:15.300   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.300   316  7057 V AudioCache: memcpy(0xac32d000, 0xb57be000, 4096)
08-30 15:30:15.301   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.301   316  7057 V AudioCache: memcpy(0xac32e000, 0xb57be000, 4096)
08-30 15:30:15.301   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.301   316  7057 V AudioCache: memcpy(0xac32f000, 0xb57be000, 4096)
08-30 15:30:15.301   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.301   316  7057 V AudioCache: memcpy(0xac330000, 0xb57be000, 4096)
08-30 15:30:15.302   316  7057 V AudioCache: write(0xb57be000, 4096)
08-30 15:30:15.302   316  7057 V AudioCache: memcpy(0xac331000, 0xb57be000, 4096)
08-30 15:30:15.302   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-30 15:30:15.302   316  7057 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-30 15:30:15.302   316  7057 V AwesomePlayer: postAudioEOS() 
08-30 15:30:15.302   316  7057 V AudioCache: write(0xb57be000, 280)
08-30 15:30:15.302   316  7057 V AudioCache: memcpy(0xac332000, 0xb57be000, 280)
08-30 15:30:15.303   316  7054 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-30 15:30:15.303   316  7054 V AwesomePlayer: onStreamDone
08-30 15:30:15.303   316  7054 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-30 15:30:15.303   316  7054 V AudioCache: notify(0xb1432240, 2, 0, 0)
08-30 15:30:15.303   316  7054 V AudioCache: playback complete
08-30 15:30:15.304   316  7054 V AwesomePlayer: pause_l() 
08-30 15:30:15.304   316  7054 V AudioCache: notify(0xb1432240, 7, 0, 0)
08-30 15:30:15.304   316  7054 V AudioCache: ignored
08-30 15:30:15.304   316  7054 V AwesomePlayer: cancelPlayerEvents
08-30 15:30:15.304   316  1402 V AudioCache: wait - success
08-30 15:30:15.304   316  1402 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-30 15:30:15.304   316  7054 D AudioPlayer: Pause Playback at 1068125
08-30 15:30:15.304   316  1402 V AwesomePlayer: reset_l() 
08-30 15:30:15.304   316  1402 V AudioCache: notify(0xb1432240, 8, 0, 0)
08-30 15:30:15.304   316  1402 V AudioCache: ignored
08-30 15:30:15.304   316  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:30:15.304   316  1402 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-30 15:30:15.304   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-30 15:30:15.304   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-30 15:30:15.304   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-30 15:30:15.304   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 15:30:15.304   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-30 15:30:15.304   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-30 15:30:15.304   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-30 15:30:15.304   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0410bf0 on port 0
08-30 15:30:15.304   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0410ba0 on port 0
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0410b50 on port 0
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0410b00 on port 0
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb16a92e0 on port 1
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0410c40 on port 1
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb0410dd0 on port 1
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 1
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-30 15:30:15.305   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 15:30:15.305   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-30 15:30:15.305   316  7056 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-30 15:30:15.305   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-30 15:30:15.305   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-30 15:30:15.305   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
,08-30 15:30:15.307   316  1402 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-30 15:30:15.307   316  1402 D AudioPlayer: AudioPlayer releasing audio source
08-30 15:30:15.307   316  1402 D AudioPlayer: AudioPlayer done releasing audio source
08-30 15:30:15.307   316  1402 V AwesomePlayer: reset_l() 
08-30 15:30:15.307   316  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:30:15.307   316  1402 V AwesomePlayer: ~AwesomePlayer call
08-30 15:30:15.307   316  1402 V AwesomePlayer: reset_l() 
08-30 15:30:15.307   316  1402 V AwesomePlayer: cancelPlayerEvents
08-30 15:30:15.308  6958  7053 V SoundPool: close(31)
08-30 15:30:15.308  6958  7053 V SoundPool: pointer = 0xa0032000, size = 205080, sampleRate = 48000, numChannels = 2
08-30 15:30:15.340  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 15:30:15.340  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-30 15:30:15.342  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3012
,08-30 15:30:15.511  6659  6659 I UEI.SmartControl: Supports setup maps: true
,08-30 15:30:15.514  6659  6659 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 15:30:15.514  6659  6659 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 15:30:15.514  6659  6659 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-30 15:30:15.514  6659  6659 I UEI.SmartControl: ### init IR Blaster...
08-30 15:30:15.518  6659  6659 D serial_port: Configuring serial port
08-30 15:30:15.518  6659  6659 E UEI.SmartControl: UEIBLaster setting for 616
08-30 15:30:15.518  6659  6659 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 15:30:15.518  6659  6659 I UEI.SmartControl: configuring settings for MAXQ616
08-30 15:30:15.518  6659  6659 I UEI.SmartControl: Get version...
08-30 15:30:15.536  6659  7059 D UEI.SmartControl: serial port data available: 21
,08-30 15:30:15.563  6659  6659 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-30 15:30:15.563  6659  6659 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 15:30:15.563  6659  6659 I UEI.SmartControl: QS saving settings...
08-30 15:30:15.563  6659  6659 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 15:30:15.579  6659  7059 D UEI.SmartControl: serial port data available: 4
,08-30 15:30:15.607  6659  7065 I UEI.SmartControl: Device manager: loading config....
,08-30 15:30:15.614  6659  7065 D UEI.SmartControl: ----------- loading internal config...
,08-30 15:30:15.618  6659  6659 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-30 15:30:15.623  6659  6659 E UEI.SmartControl: Services init done
08-30 15:30:15.623  6659  6659 D UEI.SmartControl: QS Service init finished
08-30 15:30:15.625  6659  6659 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 15:30:15.625  6659  6659 D UEI.SmartControl: QS Service version code: 201091
08-30 15:30:15.625  6659  6659 D UEI.SmartControl: Service requested: Control
08-30 15:30:15.629  6659  7065 E UEI.SmartControl: Loading SETTINGS...
08-30 15:30:15.631  6659  6659 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 15:30:15.633  6958  6958 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 15:30:15.634  6659  6659 D UEI.SmartControl: Internal service binding...
,08-30 15:30:15.637  6659  6674 I UEI.SmartControl: ------ IControl API: 11
08-30 15:30:15.637  6659  6674 D UEI.SmartControl: File observer start...
08-30 15:30:15.638  6659  6674 E UEI.SmartControl: IR Port is disabled: false
08-30 15:30:15.638  6659  6674 D UEI.SmartControl: Starting file observer...
08-30 15:30:15.638  6659  6674 I UEI.SmartControl: Registering callback...
08-30 15:30:15.639  6659  6675 I UEI.SmartControl: ------ IControl API: 19
08-30 15:30:15.641  6659  7065 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 15:30:15.641  6659  6675 I UEI.SmartControl: Registering Services Ready callback...
08-30 15:30:15.646  6659  7064 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-30 15:30:15.650  6659  7064 D UEI.SmartControl: -----service ready thread exits
,08-30 15:30:15.650  6958  6973 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 15:30:15.650  6958  7051 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 15:30:15.650  6958  7051 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-30 15:30:15.651  6958  6958 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-30 15:30:15.651  6958  6958 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 15:30:15.652  6659  6674 I UEI.SmartControl: ------ IControl API: 8
08-30 15:30:15.653  6958  6958 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 15:30:15.653  6958  6958 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 15:30:15.654  6958  6958 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-30 15:30:15.654  6958  6958 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 15:30:15.655  6958  6958 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 15:30:15.656  6958  6958 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 15:30:15.657  6958  6958 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-30 15:30:15.661  6958  6958 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 15:30:15.663  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 15:30:15.664  6958  6958 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 15:30:15.664  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 15:30:15.666  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 15:30:15.667  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 15:30:15.667  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 15:30:15.668  6958  6958 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472563815668]
08-30 15:30:15.672  6958  6958 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-30 15:30:15.674  1036  2017 I ActivityManager: Killing 6590:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-30 15:30:15.703  6958  7070 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 15:30:15.710  1036  2017 I ActivityManager: Killing 6079:com.android.gallery3d/u0a27 (adj 15): empty #18
08-30 15:30:15.750  1036  1052 W libprocessgroup: failed to open /acct/uid_10061/pid_6590/cgroup.procs: No such file or directory
,08-30 15:30:15.761  1036  1781 W libprocessgroup: failed to open /acct/uid_10027/pid_6079/cgroup.procs: No such file or directory
08-30 15:30:15.762  6958  6958 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 15:30:15.764  6958  6958 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-30 15:30:15.766  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 15:30:15.767  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 15:30:15.767  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 15:30:15.768  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 15:30:15.769  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 15:30:15.781  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 15:30:16.631  1036  1652 D WifiServiceImplEx: setWifiEnabled: true pid=6765, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-30 15:30:16.632  1036  1652 D WifiService: setWifiEnabled: true pid=6765, uid=10118
,08-30 15:30:16.632  1036  1652 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:30:16.661  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:30:16.661  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:30:16.661  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-30 15:30:16.664  1036  1392 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 15:30:16.664  1036  1392 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 15:30:16.667  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 15:30:16.667  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 15:30:16.667  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 15:30:16.667  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 15:30:16.667  1036  1392 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 15:30:16.667  1036  1392 E WifiHW  : unknown target_country: EU , set to default
08-30 15:30:16.667  1036  1392 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 15:30:16.667  1036  1392 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 15:30:16.667  1036  1392 I WifiUtil: gEnableBmps=1
08-30 15:30:16.766  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:16.792  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:30:16.798  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:16.804  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:16.814  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:16.816  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:30:16.826  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:16.827  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:16.829  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:16.832  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:30:16.835  6455  6926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:30:16.846  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 15:30:16.860  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 15:30:16.881  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:16.911  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:16.956  1036  1960 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7087 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-30 15:30:16.965  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:16.965  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 15:30:17.027  7087  7087 I AppUp4:AppBoxCP: onCreate
08-30 15:30:17.028  7087  7087 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-30 15:30:17.038  7087  7087 I AppUp4:DB:  setFingerPrint start
08-30 15:30:17.039  7087  7087 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-30 15:30:17.047  7087  7087 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-30 15:30:17.047  7087  7087 I AppUp4:DB:  SDK version = 21
08-30 15:30:17.047  7087  7087 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 15:30:17.049  7087  7087 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-30 15:30:17.051  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:30:17.051  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:17.053  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:30:17.053  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 15:30:17.060  7087  7087 I AppUp4:CustModeStarterReceiver: onReceive
,08-30 15:30:17.099  7087  7087 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:17.099  7087  7087 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:17.108  7087  7087 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@83a20e1
08-30 15:30:17.108  7087  7087 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:30:17.108  7087  7087 D AppUp4:CustFacade: isPhone : true
08-30 15:30:17.109  7087  7087 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:30:17.110  7087  7087 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-30 15:30:17.110  7087  7087 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-30 15:30:17.111  7087  7109 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-30 15:30:17.111  7087  7109 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-30 15:30:17.111  7087  7109 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-30 15:30:17.114  1036  1575 I ActivityManager: Killing 6146:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-30 15:30:17.173  1036  1978 W libprocessgroup: failed to open /acct/uid_10080/pid_6146/cgroup.procs: No such file or directory
08-30 15:30:17.174  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:17.174  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:30:17.180  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:17.183  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:17.193  4351  7118 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 15:30:17.200  4351  7119 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:17.200  4351  7119 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:30:17.244  1036  1051 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7120 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 15:30:17.347  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 15:30:17.352  1036  1118 D Tethering: InitialState.processMessage what=4
08-30 15:30:17.356  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:30:17.358  7120  7120 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:30:17.359  7120  7120 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:30:17.359   311   880 D SoftapController: Softap fwReload - Ok
,08-30 15:30:17.362  1036  1392 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (690ms)
08-30 15:30:17.363   311   880 D CommandListener: Setting iface cfg
08-30 15:30:17.364   311   880 D CommandListener: Trying to bring down wlan0
,08-30 15:30:17.366   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:30:17.367  7120  7120 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 15:30:17.368  7120  7120 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 15:30:17.369  1036  1392 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 15:30:17.374  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:30:17.374  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:30:17.374  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:30:17.362  7141  7141 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:30:17.362  7141  7141 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:17.380  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-30 15:30:17.382  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:17.384  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 15:30:17.386  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:17.386  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:17.387  1036  1392 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 15:30:17.387  1036  1392 D WifiMonitor: connecting to supplicant
08-30 15:30:17.401  7141  7141 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 15:30:17.434  7141  7141 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 15:30:17.434  7141  7141 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-30 15:30:17.477  7120  7120 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 15:30:17.492  7120  7120 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-30 15:30:17.516  7141  7141 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 15:30:17.568  7120  7120 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 15:30:17.584  7141  7141 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 15:30:17.593  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 15:30:17.594  7141  7141 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 15:30:17.595  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 15:30:17.596  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 15:30:17.597  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 15:30:17.597  1036  7149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 15:30:17.597  1036  7149 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 15:30:17.597  1036  1392 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 15:30:17.598  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 15:30:17.598  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 15:30:17.598  1036  7149 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 15:30:17.598  1036  7149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 15:30:17.598  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:17.599  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:17.600  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:17.601  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 15:30:17.602  1036  1392 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 15:30:17.602  1036  1392 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 15:30:17.604  1036  1392 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 15:30:17.604  1036  1392 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 15:30:17.605  1036  1392 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 15:30:17.606  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:17.607  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:17.607  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:17.607  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:17.607  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:30:17.608  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:30:17.608  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:30:17.608  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:30:17.613  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:17.614  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 15:30:17.614  1036  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 15:30:17.615  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-30 15:30:17.617  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:17.617  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:17.617  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:17.617  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:17.617  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:17.617  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:17.617  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:17.617  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:17.617  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:17.617  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:17.617  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:17.620  7120  7120 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:17.620  7120  7120 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:30:17.620  1036  1392 D WifiNative-wlan0: doBoolean: SET update_config 1
08-30 15:30:17.621  1036  1392 D WifiNative-wlan0: SET update_config 1: returned true
08-30 15:30:17.621  1036  1392 D WifiConfigStore: Loading config and enabling all networks 
08-30 15:30:17.621  1036  1392 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 15:30:17.621  1036  1392 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 15:30:17.621  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:17.621  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:17.621  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:17.621  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:17.621  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:17.621  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:17.621  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:17.621  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:17.621  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:17.622  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:17.622  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:17.629  1036  1392 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-30 15:30:17.640  1036  1392 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 15:30:17.640  1036  1392 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 15:30:17.642  1036  1392 D WifiStateMachine: enableVerboseLogging : level 2
,08-30 15:30:17.642  1036  1392 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 15:30:17.642  1036  1392 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 15:30:17.642  1036  1392 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 15:30:17.643  1036  1392 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 15:30:17.643  1036  1392 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 15:30:17.644  1036  1392 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 15:30:17.644  1036  1392 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 15:30:17.644  1036  1392 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-30 15:30:17.644  1036  1392 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-30 15:30:17.644  1036  1392 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 15:30:17.644  1036  1392 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 15:30:17.645  1036  1392 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 15:30:17.645  1036  1392 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 15:30:17.646  1036  1392 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 15:30:17.647  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-30 15:30:17.647  1942  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 15:30:17.647  1942  2352 D WfdsService: Set the WFDS Monitor: true
08-30 15:30:17.647  1942  2352 D WfdsMonitor: WfdsMonitorThread create
08-30 15:30:17.647  1036  1392 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:30:17.647  1942  2352 D WfdsMonitor: WFDS Monitor is created and started
08-30 15:30:17.647  1942  2352 D WfdsService: WiFi: Supplicant connection re-established
08-30 15:30:17.647  1036  1392 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 15:30:17.648  1942  7151 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 15:30:17.648  1942  7151 E CtrlSupplicant: Succeed to open control connection
08-30 15:30:17.649  1036  1392 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 15:30:17.649  1942  7151 E CtrlSupplicant: Succeed to open monitor connection
08-30 15:30:17.649  1036  1392 D WifiNative-HAL: Setting external_sim to 1
08-30 15:30:17.649  1036  1392 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-30 15:30:17.649  1942  7151 D WfdsMonitor: Supplicant connection established
08-30 15:30:17.649  1942  2352 D WfdsService: Connected to the supplicant for wfds
08-30 15:30:17.650  1036  1392 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 15:30:17.650  1036  1392 I WifiNative-HAL: startHal
08-30 15:30:17.650  1036  1392 D wifi    : setting scan oui 0xaf4f1e00
08-30 15:30:17.651  1036  1392 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:30:17.651  1036  1392 I WifiNative-HAL: startHal
08-30 15:30:17.651  1036  1392 D wifi    : setting scan oui 0xaf4f1e00
08-30 15:30:17.651  1036  1392 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 15:30:17.653  1036  1392 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 15:30:17.653  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 15:30:17.653  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 15:30:17.654  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 15:30:17.654  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 15:30:17.654  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 15:30:17.655  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-30 15:30:17.655  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 15:30:17.655  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 15:30:17.656  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 15:30:17.656  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 15:30:17.656  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 15:30:17.657  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 15:30:17.657  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 15:30:17.657  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 15:30:17.658  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 15:30:17.658  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 15:30:17.658  7141  7141 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 15:30:17.659  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 15:30:17.659  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 15:30:17.659  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 15:30:17.660  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 15:30:17.662  1036  1392 E WifiNative: : [204,514,991 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 15:30:17.662  1036  1392 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 15:30:17.662  1036  1392 D WifiNative-wlan0: RECONNECT: returned true
08-30 15:30:17.662  1036  1392 D WifiNative-wlan0: doString: [STATUS]
08-30 15:30:17.663  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 15:30:17.663  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 15:30:17.663  1036  1392 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 15:30:17.664  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:30:17.664  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:30:17.664  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.665  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 15:30:17.665  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-30 15:30:17.665  1036  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.665  1036  1556 I WifiNative-HAL: startHal
08-30 15:30:17.665  1036  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf4f1e00
08-30 15:30:17.665  1036  1556 D wifi    : failed to get capabilities : -3
08-30 15:30:17.665  1036  1556 E WifiScanningService: could not get scan capabilities
08-30 15:30:17.665  1036  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.666   311   880 D CommandListener: Setting iface cfg
,08-30 15:30:17.666  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 15:30:17.666   311   880 D CommandListener: Trying to bring up p2p0
08-30 15:30:17.667  1036  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 15:30:17.667  1036  1389 D LGWifiP2pService: P2pEnablingState
08-30 15:30:17.667  1036  1389 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.667  1036  1389 D LGWifiP2pService: P2p socket connection successful
08-30 15:30:17.667  1036  1389 D LGWifiP2pService: P2pEnabledState
08-30 15:30:17.667  1036  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 15:30:17.667  1036  1392 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 15:30:17.667  1036  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 15:30:17.668  1036  1392 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 15:30:17.669  1036  1392 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 15:30:17.670  1036  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 15:30:17.670  1036  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 15:30:17.670  1036  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-30 15:30:17.670  1036  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 15:30:17.670  1036  1389 D LGWifiP2pService: before postfix = G3
08-30 15:30:17.670  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 15:30:17.670  1036  1389 D WifiServerServiceExt: postfix byte check : 2
08-30 15:30:17.670  1036  1389 D LGWifiP2pService: after postfix = G3
08-30 15:30:17.670  1942  1942 D WfdsService: WifiP2pState is changed : true
08-30 15:30:17.670  1036  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 15:30:17.671  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 15:30:17.671  1036  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 15:30:17.671  1036  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 15:30:17.671  1942  2352 D WfdsService: Receive the WFDS_ENABLE Method
08-30 15:30:17.671  1942  2352 D WfdsService: Set the WFDS Monitor: true
08-30 15:30:17.671  1942  2352 D WfdsService: Connected to the supplicant for wfds
08-30 15:30:17.671  1942  2352 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 15:30:17.671  1942  1942 D WfdsService: isConnected: false
08-30 15:30:17.671  7141  7141 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 15:30:17.671  1942  2352 D WfdsService: selectPreferredScanChannel [36]
08-30 15:30:17.671  1942  2352 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 15:30:17.671  1036  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 15:30:17.671  1036  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 15:30:17.672  1036  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 15:30:17.672  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 15:30:17.672  1036  1392 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 15:30:17.672  1036  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 15:30:17.672  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-30 15:30:17.672  1036  1392 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 15:30:17.672  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-30 15:30:17.673  1036  1392 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 15:30:17.673  1036  1392 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 15:30:17.673  7141  7141 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 15:30:17.673  1036  1392 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 15:30:17.6,74  1036  1392 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 15:30:17.674  1036  1392 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 15:30:17.674  1036  1392 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 15:30:17.675  7141  7141 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 15:30:17.675  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 15:30:17.675  1036  1392 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 15:30:17.676  1036  1392 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-30 15:30:17.676  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 15:30:17.676  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 15:30:17.677  7141  7141 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:17.677  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:30:17.677  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:17.677  1036  7149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:17.677  1036  7149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:17.678  7141  7141 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 15:30:17.678  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.678  1942  7151 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:17.678  1036  7149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:17.678  1036  7149 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.678  1036  7149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.678  1036  7149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.678  1036  1392 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 15:30:17.678  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.679  1942  7151 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:17.679  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:30:17.679  1036  7149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:17.679  1036  1392 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:30:17.680  1036  7149 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.680  1036  7149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.680  1036  7149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-30 15:30:17.681  1036  1392 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:30:17.681  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-30 15:30:17.681  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 15:30:17.682  7141  7141 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:30:17.683  1036  1392 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 15:30:17.683  1036  1392 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 15:30:17.683  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 15:30:17.683  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 15:30:17.684  1942  1942 D WfdsService: Update P2p Interface State: 3
08-30 15:30:17.684  1036  1392 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 15:30:17.684  1036  1392 D WifiNative-wlan0: doBoolean: SCAN
08-30 15:30:17.684  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 15:30:17.684  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:30:17.684  1036  7149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-30 15:30:17.684  1036  7149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:30:17.684  1036  1392 D WifiNative-wlan0: SCAN: returned false
08-30 15:30:17.685  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=204539  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:30:17.687  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=204541  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:30:17.687  1036  1392 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:17.688  1036  1392 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:17.688  1036  1392 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:17.688  1036  1389 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-30 15:30:17.688  1036  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-30 15:30:17.689  1036  1392 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:17.689  1036  1392 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:17.690  1036  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 15:30:17.690  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-30 15:30:17.690  1036  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 15:30:17.690  1036  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 15:30:17.690  1036  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 15:30:17.691  1036  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 15:30:17.691  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 15:30:17.691  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:17.692  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:17.697  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:17.697  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:17.697  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 15:30:17.699  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:17.699  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
08-30 15:30:17.701  1036  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 15:30:17.701  1036  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-30 15:30:17.701  1036  1389 D LGWifiP2pService: InactiveState
08-30 15:30:17.701  1036  1389 D LGWifiP2pService: InactiveState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.702  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-23ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.702  1036  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 15:30:17.702  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 15:30:17.703  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:17.703  1036  7149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:30:17.703  1036  7149 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:17.703  1036  7149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:17.703  1036  7149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:17.703  1942  7151 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:30:17.703  7141  7141 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 15:30:17.704  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.704  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.705  1942  7151 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-30 15:30:17.705  1942  7151 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-30 15:30:17.706  1036  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 15:30:17.706  1036  1389 D LGWifiP2pService: InactiveState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.706  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.706  1036  7149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:17.706  1036  1389 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.706  1036  7149 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.706  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.706  1036  7149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.706  1036  1389 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.706  1036  7149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.706  1036  7149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:17.706  1036  7149 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.706  1036  7149 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.706  1036  7149 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:17.706  1036  1389 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.706  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.706  1036  1389 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.707  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.707  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.707  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.707  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.707  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.707  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:17.707  1036  1036 E WifiServerServiceExt: No p2p device connected
08-30 15:30:17.707  1942  2352 W WfdsService: DefaultState - msg [9441285] is not handled
,08-30 15:30:17.777  7120  7120 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 15:30:17.832  3456  3456 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-30 15:30:17.832  3456  3456 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:17.833  3456  3456 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-30 15:30:17.833  7120  7120 I HubEmail: JNI_OnLoad()
08-30 15:30:17.833  7120  7120 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 15:30:17.834  7120  7120 I HubEmail: registerNatives()
08-30 15:30:17.834  7120  7120 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 15:30:17.834  7120  7120 I HubEmail: registerNativeMethods()
08-30 15:30:17.834  7120  7120 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-30 15:30:17.834  7120  7120 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-30 15:30:17.889  1036  1652 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7159 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-30 15:30:17.895  7120  7158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:17.896  7003  7155 W FormManager: Network not available. Please check & try again.
08-30 15:30:17.906  7003  7156 V FormManager: Network unavailable.
,08-30 15:30:17.912  7003  7156 V FormManager: Network unavailable.
08-30 15:30:17.923  1036  1936 I ActivityManager: Killing 6165:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-30 15:30:18.010  1036  1998 W libprocessgroup: failed to open /acct/uid_10097/pid_6165/cgroup.procs: No such file or directory
,08-30 15:30:18.119  7159  7159 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:18.119  7159  7159 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:18.123  7159  7159 D PhoneMonitor: Register our PhoneStateListener
08-30 15:30:18.144  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 15:30:18.147  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-30 15:30:18.180  7159  7159 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-30 15:30:18.187  7159  7159 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-30 15:30:18.189  7159  7159 D TelephonyAutoProfiling: [parse] Load xml
,08-30 15:30:18.191  1036  1998 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7179 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:30:18.192  1036  1998 I ActivityManager: Killing 6623:com.lge.eula/1000 (adj 15): empty #17
08-30 15:30:18.195  7159  7159 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-30 15:30:18.195  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-30 15:30:18.195  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-30 15:30:18.196  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-30 15:30:18.197  7159  7159 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-30 15:30:18.197  7159  7159 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-30 15:30:18.200  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 15:30:18.200  1036  7149 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 15:30:18.200  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 15:30:18.200  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-30 15:30:18.200  1036  7149 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 15:30:18.201  7141  7141 E wpa_supplicant: USIM:  scard_init function
08-30 15:30:18.201  1036  1392 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 15:30:18.201  7141  7141 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 15:30:18.201  1036  1392 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 15:30:18.202  1036  1392 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 15:30:18.202  1036  1392 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-30 15:30:18.202  1036  1392 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 15:30:18.203  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:0,0:00 SSID=]
08-30 15:30:18.203  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-30 15:30:18.207  7159  7159 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-30 15:30:18.252  1036  1781 W libprocessgroup: failed to open /acct/uid_1000/pid_6623/cgroup.procs: No such file or directory
,08-30 15:30:18.254  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=205108  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 15:30:18.259  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=205113  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 15:30:18.260  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.260  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.261  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 15:30:18.262  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.262  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:18.263  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.263  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.263  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 15:30:18.264  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:18.266  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.266  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:18.267  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:18.267  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 15:30:18.267  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.316  7141  7141 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 15:30:18.317  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 15:30:18.317  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 15:30:18.317  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 15:30:18.317  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 15:30:18.319  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:18.319  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:18.319  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=205173  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 15:30:18.321  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=205175  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 15:30:18.322  1036  1392 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205177
08-30 15:30:18.322  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 15:30:18.323  1036  1392 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205178
08-30 15:30:18.324  1036  1392 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205179
08-30 15:30:18.326  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205180
08-30 15:30:18.327  1036  1392 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=205181
08-30 15:30:18.328  7141  7141 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 15:30:18.328  7141  7141 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:30:18.328  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=205183  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 15:30:18.329  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:18.329  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:18.333  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-30 15:30:18.333  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:30:18.333  1036  7149 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:30:18.333  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 15:30:18.333  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:30:18.333  1036  7149 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:30:18.333  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:18.333  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:18.337  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.337  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:18.338  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.338  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.338  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.338  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 15:30:18.341  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=205195  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 15:30:18.342  1036  1392 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:18.343  1036  1392 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:18.343  1036  1392 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:18.344  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:18.344  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.344  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.344  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 15:30:18.344  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:18.344  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 15:30:18.345  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 15:30:18.346  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=205200  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 15:30:18.346  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=205201  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 15:30:18.347  1036  1392 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=205201
08-30 15:30:18.347  1036  1392 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=205202
08-30 15:30:18.348  1036  1392 D WifiNative-wlan0: doString: [STATUS]
08-30 15:30:18.348  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:18.349  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:18.349  1036  1392 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 15:30:18.351  1036  1392 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 15:30:18.356  1036  1392 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 15:30:18.356  1036  1392 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 15:30:18.357  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.357  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:18.358  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.360  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.360  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.360  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 15:30:18.362  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.362  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.362  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 15:30:18.367  1036  1392 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 15:30:18.367  1036  1442 D ConnectivityService: Got NetworkAgent Messenger
08-30 15:30:18.367  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:30:18.368  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:30:18.368  1036  1442 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 15:30:18.368  1036  1442 D ConnectivityService: NetworkAgent connected
08-30 15:30:18.368  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:30:18.368  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:30:18.373  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:30:18.373  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:30:18.373  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:30:18.373  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:30:18.374  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:30:18.377  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.377  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:18.377  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:30:18.378  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.379  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.379  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-30 15:30:18.379   311   880 D CommandListener: Setting iface cfg
08-30 15:30:18.380  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.383  1036  1392 E WifiStateMachine: Start Dhcp Watchdog 2
08-30 15:30:18.384  1036  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=205238  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:18.385  1036  7198 D DhcpStateMachine: StoppedState
08-30 15:30:18.385  1036  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=205239  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:18.385  1036  7198 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.385  1036  7198 D DhcpStateMachine: WaitBeforeStartState
08-30 15:30:18.385  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=205240  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:18.438  1036  1960 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7199 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-30 15:30:18.439  1036  1960 I ActivityManager: Killing 6640:com.lge.bnr/1000 (adj 15): empty #17
08-30 15:30:18.460   347   347 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.109ms
,08-30 15:30:18.478   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 362us total 17.005ms
,08-30 15:30:18.492   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 289us total 14.430ms
,08-30 15:30:18.500  1036  1781 W libprocessgroup: failed to open /acct/uid_1000/pid_6640/cgroup.procs: No such file or directory
08-30 15:30:18.501  1036  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=205355  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:18.501  1036  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=205356  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:18.502  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=205356  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:18.503  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:159488] from screen [on:0 period:-609964025] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-30 15:30:18.504  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-609964024] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-30 15:30:18.504  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 15:30:18.505  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:18.505  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 15:30:18.509  1036  1442 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-30 15:30:18.509  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.510  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.510  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.510  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.510  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.511  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.511  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.512  1036  1442 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 15:30:18.512  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=94,0,0
08-30 15:30:18.512  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=94,0,0
08-30 15:30:18.513  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
,08-30 15:30:18.513  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-30 15:30:18.513  1036  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 15:30:18.513  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 0
08-30 15:30:18.514  1036  1392 D WifiNative-wlan0: SET ps 0: returned true
08-30 15:30:18.514  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 15:30:18.514  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 15:30:18.514  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 15:30:18.514  1036  1392 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 15:30:18.514  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@74f7c6d target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.514  1036  1392 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 15:30:18.514  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@74f7c6d target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.514  1036  1392 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 15:30:18.515  1036  7198 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.515  1036  7198 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 15:30:18.515   311   880 D CommandListener: Setting iface cfg
08-30 15:30:18.515   311   880 D CommandListener: Trying to bring up wlan0
,08-30 15:30:18.518  1036  1392 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 15:30:18.518  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:18.518  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 15:30:18.519  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:18.519  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 15:30:18.519  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.520  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.520  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.521  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.521  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.521  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:18.522  1036  1442 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-30 15:30:18.522  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 15:30:18.522  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 15:30:18.522  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:30:18.523  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-30 15:30:18.523  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.523  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:30:18.523  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:30:18.523  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 15:30:18.524  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
,08-30 15:30:18.524  1036  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 15:30:18.524  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:30:18.539  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:30:18.540  1036  1442 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-30 15:30:18.540  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 15:30:18.541  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 15:30:18.541  1036  1392 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-30 15:30:18.541  1036  1442 D ConnectivityService: ignoring duplicate network state non-change
,08-30 15:30:18.547  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.547  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:18.550  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.550  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.550  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.550  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 15:30:18.551  1036  1442 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 15:30:18.552  1036  1442 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 15:30:18.565  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.565  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.566  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 15:30:18.570  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 15:30:18.570  1036  1392 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 15:30:18.573  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-30 15:30:18.573  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.573  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:18.575  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.575  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.575  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 15:30:18.575  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 15:30:18.576  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.580  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.580  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 15:30:18.580  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.581  1036  1442 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 15:30:18.581  1036  1442 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-30 15:30:18.582  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.582  1036  1442 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-30 15:30:18.582  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:18.582  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 15:30:18.583   311   880 E Netd    : netlink response contains error (File exists)
08-30 15:30:18.583  1036  1442 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 15:30:18.586  1036  1442 D ConnectivityService: addLocalRoutetoDefaultNetwork
,08-30 15:30:18.587  1036  1442 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-30 15:30:18.587  1036  1442 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-30 15:30:18.598  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:18.598  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 15:30:18.599  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:18.630  1036  1896 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7218 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:30:18.632  1036  1896 I ActivityManager: Killing 2128:com.lge.music/u0a34 (adj 15): empty #17
08-30 15:30:18.671   316  1782 V AudioFlinger: 2128 died, releasing its sessions
08-30 15:30:18.671   316  1782 V AudioFlinger:  pid 1853 @ 0
08-30 15:30:18.671   316  1782 V AudioFlinger:  pid 3456 @ 1
08-30 15:30:18.671   316  1782 V AudioFlinger:  pid 3456 @ 2
,08-30 15:30:18.687  1036  1442 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-30 15:30:18.687  1036  1442 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-30 15:30:18.687  1036  1442 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 15:30:18.687  1036  1442 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 15:30:18.687  1036  1442 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:18.687  1036  1442 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:18.687  1036  1442 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 15:30:18.687  1036  1442 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.687  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.687  1036  1442 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 15:30:18.687  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 15:30:18.687  1036  1442 D ConnectivityService: currentScore = 0, newScore = 20
08-30 15:30:18.687  1036  1442 D ConnectivityService:    accepting network in place of null
08-30 15:30:18.687  1036  1442 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.688  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.688  1036  1392 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.688  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:18.688  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 15:30:18.690  1036  1442 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 15:30:18.690  1036  1442 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 15:30:18.690  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:30:18.691  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.692  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:30:18.694  1036  1442 D ConnectivityService: sendStickyBroadcastDelayed,: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:18.694  1036  1442 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-30 15:30:18.694  1036  1442 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 15:30:18.695  1036  1936 W libprocessgroup: failed to open /acct/uid_10034/pid_2128/cgroup.procs: No such file or directory
08-30 15:30:18.697  1036  1442 D ConnectivityService: validation of new default Network = false
08-30 15:30:18.697  1036  1442 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 15:30:18.697  1036  1442 D DSQN    : enableDataServiceNotify 
08-30 15:30:18.697  1036  1442 D DSQN    : start dsqn bin
08-30 15:30:18.698   311  7236 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-30 15:30:18.698   311  7236 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-30 15:30:18.713  7218  7218 I art     : Almond Protected OAT
,08-30 15:30:18.733  1036  1442 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 15:30:18.733  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.733  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-30 15:30:18.734  1036  1442 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:18.734  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:30:18.734  1036  7198 D DhcpStateMachine: DHCPV4 request on wlan0
08-30 15:30:18.722  7237  7237 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:18.722  7237  7237 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:18.741  1036  7198 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-30 15:30:18.741  1036  7198 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-30 15:30:18.745  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 15:30:18.745  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:30:18.745  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:30:18.745  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:30:18.742  7239  7239 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:18.752  1036  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-30 15:30:18.753  7237  7237 E DSQN    : DSQN ssw
08-30 15:30:18.742  7239  7239 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:30:18.755   311  7236 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-30 15:30:18.760  7239  7239 I dhcpcd  : version 5.5.6 starting
08-30 15:30:18.762  7239  7239 E dhcpcd  : get_duid: m
08-30 15:30:18.762  7239  7239 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 15:30:18.762  7239  7239 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-30 15:30:18.771  7218  7218 D WeatherApplication: removeAccount
08-30 15:30:18.771  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 15:30:18.772  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.773  7218  7218 D WeatherApplication: Account.length = 0
08-30 15:30:18.773  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.773  7218  7218 E WeatherApplication: OPERATOR:OPEN
08-30 15:30:18.773  1036  1389 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.773  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.773  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:18.778  7218  7218 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:18
08-30 15:30:18.779   311   879 D LGDataListener: argv[0]=dsqncommand
08-30 15:30:18.779   311   879 D LGDataListener: argv[1]=wlan0
08-30 15:30:18.779   311   879 D LGDataListener: argv[2]=1
08-30 15:30:18.779   311   879 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 15:30:18.780  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 15:30:18.780  1036  1116 D DSQN    : start to monitor internet connection
08-30 15:30:18.781  1036  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:30:18.782  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:30:18.782  1036  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:30:18.783  1036  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:30:18.783  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-30 15:30:18.784  1036  1392 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-30 15:30:18.784  7218  7218 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-30 15:30:18.784  7218  7218 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:30:18.785  7218  7218 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:30:18.789  7218  7218 D WeatherAncestor: connectivity changed - connection : true
08-30 15:30:18.790  7218  7218 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-30 15:30:18.797  7218  7218 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:30:18.797  7218  7218 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:30:18.798  7218  7218 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-30 15:30:18.798  1817  7247 I CheckinService: active receiver: enabled
,08-30 15:30:18.806  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 13:30:18 GMT], X-Android-Received-Millis=[1472563818805], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472563818778]}
08-30 15:30:18.807  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 15:30:18.807  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-30 15:30:18.807  1036  1442 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-30 15:30:18.807  1036  1442 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-30 15:30:18.807  1036  1442 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:18.807  1036  1442 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:18.807  1036  1442 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 15:30:18.807  1036  1442 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-30 15:30:18.807  1036  1442 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-30 15:30:18.807  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.807  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:18.808  1036  1442 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:18.808  1036  1442 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.808  1036  1392 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.808  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 15:30:18.808  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:30:18.808  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:18.808  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:18.808  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:30:18.810  1817  7247 I CheckinService: Preparing to send checkin request
,08-30 15:30:18.810  1817  7247 I EventLogService: Accumulating logs since 1472563670369
08-30 15:30:18.814  7239  7239 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 15:30:18.815  7239  7239 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 15:30:18.815  7239  7239 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 15:30:18.815  7239  7239 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 15:30:18.815  7239  7239 D dhcpcd  : wlan0: sending REQUEST (xid 0x34704b4f), next in 4.85 seconds
08-30 15:30:18.824  7218  7218 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:30:18.824  7218  7218 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:18
,08-30 15:30:18.825  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:30:18.825  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.826  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:18.838  7239  7239 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 15:30:18.862  7239  7239 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 15:30:18.862  7239  7239 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 15:30:18.863  7239  7239 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 15:30:18.863  7239  7239 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 15:30:18.863  7239  7239 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 15:30:18.863  7239  7239 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 15:30:18.863  7239  7239 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 15:30:18.863  7239  7239 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-30 15:30:18.866  1036  1998 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7253 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:30:18.867  1036  1998 I ActivityManager: Killing 6101:com.android.vending/u0a44 (adj 15): empty #17
08-30 15:30:18.870  1817  7247 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-30 15:30:18.911  1036  1896 W libprocessgroup: failed to open /acct/uid_10044/pid_6101/cgroup.procs: No such file or directory
,08-30 15:30:19.005  1036  1914 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7283 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-30 15:30:19.031   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-30 15:30:19.031   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 15:30:19.031   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:30:19.032  7253  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 15:30:19.033   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 15:30:19.033   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 15:30:19.033   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:30:19.033  7253  7303 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 15:30:19.049  7283  7283 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 15:30:19.049  7283  7283 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 15:30:19.066  7283  7283 I MultiDex: VM with version 2.1.0 has multidex support
08-30 15:30:19.067  7283  7283 I MultiDex: install
08-30 15:30:19.067  7283  7283 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 15:30:19.068   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 15:30:19.068   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-30 15:30:19.068   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:30:19.068  7253  7309 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-30 15:30:19.070   278   414 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-30 15:30:19.070   278   414 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-30 15:30:19.070   278   414 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 15:30:19.071  7253  7309 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-30 15:30:19.073  7283  7283 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 15:30:19.144  1036  7198 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 15:30:19.145  1036  7198 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 15:30:19.145  1036  7198 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 15:30:19.145  1036  7198 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 15:30:19.145  1036  7198 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 15:30:19.145  1036  7198 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 15:30:19.145  1036  7198 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 15:30:19.145  1036  7198 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 15:30:19.146  1036  7198 D DhcpStateMachine: RunningState
08-30 15:30:19.236  7253  7253 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-30 15:30:19.244  7253  7253 I LibraryLoader: Loading: webviewchromium
08-30 15:30:19.247  7253  7253 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6113-6117)
08-30 15:30:19.247  7253  7253 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:30:19.255  7253  7253 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1f44bb90}
,08-30 15:30:19.259  7253  7253 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 15:30:19.260  7253  7253 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 15:30:19.291  7253  7253 I BrowserStartupController: Initializing chromium process, renderers=0
08-30 15:30:19.293  7253  7253 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 15:30:19.305   316  1403 V AudioPolicyService: registerClient() client 0xb04045e0, uid 10093
08-30 15:30:19.306  7253  7253 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-30 15:30:19.307  7253  7253 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-30 15:30:19.307  7253  7253 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-30 15:30:19.310  7253  7333 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 15:30:19.338  7253  7253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:30:19.338  7253  7253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:30:19.338  7253  7253 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:30:19.338  7253  7253 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:30:19.338  7253  7253 I Adreno-EGL: Remote Branch: 
08-30 15:30:19.338  7253  7253 I Adreno-EGL: Local Patches: 
08-30 15:30:19.338  7253  7253 I Adreno-EGL: Reconstruct Branch: 
,08-30 15:30:19.398  1036  1959 I art     : Explicit concurrent mark sweep GC freed 105776(5MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 1.655ms total 81.398ms
,08-30 15:30:19.407  7283  7301 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 15:30:19.407  7283  7301 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:19.417  7253  7253 I NSApplication: Starting up...
08-30 15:30:19.467  1036  2051 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7349 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 15:30:19.469  1036  1960 I ActivityManager: Killing 6832:com.lge.clock/u0a10 (adj 15): empty #17
08-30 15:30:19.564  7366  7366 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 15:30:19.575  1036  1998 W libprocessgroup: failed to open /acct/uid_10010/pid_6832/cgroup.procs: No such file or directory
,08-30 15:30:19.620  7366  7366 I dex2oat : dex2oat took 55.628ms (threads: 4)
,08-30 15:30:19.624  7349  7349 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:30:19.647  7283  7301 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:30:19.647  7283  7301 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:30:19.647  7283  7301 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:30:19.647  7283  7301 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:30:19.647  7283  7301 I Adreno-EGL: Remote Branch: 
08-30 15:30:19.647  7283  7301 I Adreno-EGL: Local Patches: 
08-30 15:30:19.647  7283  7301 I Adreno-EGL: Reconstruct Branch: 
,08-30 15:30:19.667  1036  1896 D WifiServiceImplEx: setWifiEnabled: false pid=6765, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:30:19.667  1036  1896 D WifiService: setWifiEnabled: false pid=6765, uid=10118
08-30 15:30:19.667  1036  1896 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:30:19.682  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:30:19.682  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:30:19.683  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-30 15:30:19.683  1036  1392 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:19.684  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:19.684  1036  1392 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-30 15:30:19.684  1036  1392 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:19.685  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-30 15:30:19.685  1036  1392 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 15:30:19.685  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:30:19.685  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:30:19.686  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:30:19.686  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:30:19.695  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:30:19.695  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:30:19.695  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.695  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.696  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:30:19.696  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:30:19.696  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 15:30:19.696  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:30:19.697  1036  7198 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:30:19.700   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:30:19.730  1036  1442 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 15:30:19.730  1036  1442 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-30 15:30:19.732  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 15:30:19.733  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:19.733  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:19.733  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:30:19.734  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:19.734  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:19.735  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:19.735  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-30 15:30:19.737  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 15:30:19.738  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:19.739  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:19.739  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-30 15:30:19.740  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 15:30:19.740  1036  1036 D RttService: SCAN_AVAILABLE : 1
08-30 15:30:19.740  1036  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.741  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.741  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.741  1036  1389 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@21e94c67
08-30 15:30:19.741  1036  1389 D LGWifiP2pService: P2pDisablingState
08-30 15:30:19.741  1036  1389 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.741  1036  1389 D LGWifiP2pService: p2p socket connection lost
08-30 15:30:19.741  1036  1389 D LGWifiP2pService: P2pDisabledState
08-30 15:30:19.744  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 15:30:19.744  1942  1942 D WfdsService: WifiP2pState is changed : false
08-30 15:30:19.744  1942  2352 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-30 15:30:19.744  1942  2352 D WfdsService: Set the WFDS Monitor: false
08-30 15:30:19.745  1036  1557 D RttService: EnabledState got{ when=-5ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.745  1942  2352 D WfdsMonitor: WFDS Monitor is stopped
08-30 15:30:19.745  1942  2352 D WfdsService: STATE : WfdsDisabledState - enter
08-30 15:30:19.745  1942  7151 D CtrlSupplicant: Received on exit socket, terminate
08-30 15:30:19.745  1942  7151 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-30 15:30:19.745  1942  2356 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-30 15:30:19.745  1942  7151 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-30 15:30:19.745  1942  7151 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-30 15:30:19.745  1942  2352 W WfdsService: DefaultState - msg [9445378] is not handled
08-30 15:30:19.746  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:19.746  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:19.746  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:19.746  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:19.747  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:19.749  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:19.749  1036  1392 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 15:30:19.749  1036  1392 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-30 15:30:19.750  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.750  1036  1389 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.750  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:30:19.750  7141  7141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:30:19.750  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:30:19.750  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:30:19.752  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
,08-30 15:30:19.756  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 15:30:19.756  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:19.757  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:19.774   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:30:19.775  1036  1442 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-30 15:30:19.775  1036  1442 D DSQN    : disableDataServiceNotify
08-30 15:30:19.775  1036  1442 D DSQN    : stop dsqn bin
,08-30 15:30:19.777  1036  1392 D WifiNative-p2p0: doBoolean: TERMINATE
08-30 15:30:19.777  1036  1036 D WifiHS20: hidePasspointNotification off =false
08-30 15:30:19.778  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:19.778  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:19.778  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:30:19.779  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-30 15:30:19.779  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:19.779  1036  1392 D WifiNative-p2p0: TERMINATE: returned true
08-30 15:30:19.779  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:30:19.779  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:30:19.779  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:30:19.780  1036  1442 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 15:30:19.780  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-30 15:30:19.780  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:19.780  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:19.781  1036  1442 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:19.781  1036  1442 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-30 15:30:19.781  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.781  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.781  1036  7197 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 15:30:19.781  1036  1442 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-30 15:30:19.781  1036  1442 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 15:30:19.781  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:30:19.781  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 15:30:19.782  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:19.782  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-30 15:30:19.783  1036  1442 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:19.783  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:19.783  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:19.783  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:19.783  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:19.783  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:19.783  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:19.783  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name:, null
08-30 15:30:19.783  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:19.783  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:19.783  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:19.783  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:30:19.783  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:19.784  1036  1442 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:19.784  1036  1442 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:19.784  1036  1442 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:19.784  1036  1442 D NetworkManagementService: Removing idletimer
08-30 15:30:19.784  1036  1442 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:19.784  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:19.784  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:30:19.784  1036  1392 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:19.785  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:19.785  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 15:30:19.785  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:19.785  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:19.785  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:19.785  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:19.785  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:19.785  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:19.785  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:19.785  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:19.785  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:19.785  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:19.785  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:19.785  1036  1442 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () -, 100] cleared because we found a replacement network
08-30 15:30:19.785  1036  1442 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 15:30:19.785  1036  1388 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-30 15:30:19.787  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 15:30:19.788  1036  1036 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-30 15:30:19.788  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:19.788  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:19.788  1036  1036 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-30 15:30:19.788  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:30:19.788  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:30:19.788  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:30:19.788  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:30:19.788  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:30:19.788  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:30:19.799  7283  7301 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:30:19.799  7283  7301 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:30:19.799  7283  7301 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:30:19.799  7283  7301 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:30:19.799  7283  7301 I Adreno-EGL: Remote Branch: 
08-30 15:30:19.799  7283  7301 I Adreno-EGL: Local Patches: 
08-30 15:30:19.799  7283  7301 I Adreno-EGL: Reconstruct Branch: 
08-30 15:30:19.813  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:30:19.814  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:19.815  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:19.826  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:30:19.827  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:19.827  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:19.866  7283  7301 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 15:30:19.866  7283  7301 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 15:30:19.866  7283  7301 I Adreno-EGL: Build Date: 12/12/14 금
08-30 15:30:19.866  7283  7301 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-30 15:30:19.866  7283  7301 I Adreno-EGL: Remote Branch: 
08-30 15:30:19.866  7283  7301 I Adreno-EGL: Local Patches: 
08-30 15:30:19.866  7283  7301 I Adreno-EGL: Reconstruct Branch: 
,08-30 15:30:19.880  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 15:30:19.880  7141  7141 I wpa_supplicant: monitor socket send errors count : 1
08-30 15:30:19.880  7141  7141 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1942-4\x00 that cannot receive messages
08-30 15:30:19.881  1036  7149 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-30 15:30:19.881  1036  7149 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 15:30:19.905  1036  7198 D DhcpStateMachine: StoppedState
08-30 15:30:19.905  1036  7198 D DhcpStateMachine: StoppedState{ when=-153ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:19.906  1036  1392 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-30 15:30:19.906  1036  1392 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-30 15:30:19.910  7141  7141 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:30:19.911  7141  7141 W wpa_supplicant: USIM:  scard_deinit function
08-30 15:30:19.911  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:30:19.912  1036  1118 D Tethering: InitialState.processMessage what=4
08-30 15:30:19.912  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-30 15:30:19.913  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:30:19.913  1036  7149 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 15:30:19.913  1036  7149 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-30 15:30:19.913  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:19.913  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:19.913  1036  1392 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=206767
,08-30 15:30:19.913  1036  1392 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=206768
08-30 15:30:19.914  1036  1392 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=206768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 15:30:19.914  1036  1392 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=206768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-30 15:30:19.915  6455  6926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:30:19.918  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 15:30:19.924  1036  1392 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:19.924  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:19.934  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:19.942  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:30:19.942  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:19.942  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:30:19.942  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 15:30:19.943  7087  7087 I AppUp4:CustModeStarterReceiver: onReceive
08-30 15:30:19.946  7087  7087 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@83a20e1
08-30 15:30:19.946  7087  7087 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:30:19.946  7087  7087 D AppUp4:CustFacade: isPhone : true
08-30 15:30:19.946  7087  7087 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:30:19.946  7087  7087 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 15:30:19.949  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:19.949  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 15:30:19.950  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:19.952  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:19.956  4351  7388 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:30:19.959  4351  7390 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:19.960  4351  7390 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:30:19.960  7120  7120 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 15:30:19.977  7120  7392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:30:19.980  3456  3456 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-30 15:30:19.981  3456  3456 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:19.981  3456  3456 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 15:30:19.984  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 15:30:19.984  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 15:30:19.995  7218  7218 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:19
,08-30 15:30:19.996  7218  7218 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:30:19.997  7218  7218 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:30:19.997  7218  7218 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:30:19.997  7218  7218 D WeatherAncestor: connectivity changed - connection : true
08-30 15:30:19.997  7218  7218 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3bdcecc7
08-30 15:30:19.998  7218  7218 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:30:19.998  7218  7218 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:30:19.998  7218  7218 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 15:30:19.998  7218  7218 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-30 15:30:19.998  7218  7218 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:19
08-30 15:30:20.012  7003  7395 W FormManager: Network not available. Please check & try again.
,08-30 15:30:20.016  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:30:20.016  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:30:20.016  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:30:20.016  6907  6907 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:30:20.017  7003  7396 V FormManager: Network unavailable.
08-30 15:30:20.017  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 15:30:20.018  6907  6907 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:30:20.018  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 15:30:20.018  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:30:20.018  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:30:20.018  6907  6907 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:30:20.018  6907  6907 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:30:20.023  7003  7396 V FormManager: Network unavailable.
,08-30 15:30:20.024  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:20.027  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:30:20.030  7003  7397 W FormManager: Network not available. Please check & try again.
08-30 15:30:20.031  7141  7141 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 15:30:20.034  1036  7149 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-30 15:30:20.034  1036  7149 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-30 15:30:20.034  1036  7149 D WifiMonitor: Disconnecting from the supplicant, no more events
08-30 15:30:20.034  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.034  1036  1392 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-30 15:30:20.043   311  7400 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 15:30:20.043  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-30 15:30:20.044  1817  7247 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-30 15:30:20.047  7003  7398 V FormManager: Network unavailable.
,08-30 15:30:20.049  7003  7398 V FormManager: Network unavailable.
08-30 15:30:20.051  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:20.054  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:30:20.060  1817  7247 I CheckinService: active receiver: disabled
08-30 15:30:20.063  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.070  7003  7401 W FormManager: Network not available. Please check & try again.
,08-30 15:30:20.073  7003  7402 V FormManager: Network unavailable.
08-30 15:30:20.075  7003  7402 V FormManager: Network unavailable.
08-30 15:30:20.080  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:30:20.080  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:30:20.081  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:20.083  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:30:20.086  4351  7403 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:30:20.088  4351  7404 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:30:20.088  4351  7404 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:30:20.120  1036  2017 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7405 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 15:30:20.138  1036  1392 D WifiOffDelayIfNotUsed: stopMonitoring
08-30 15:30:20.138  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:30:20.138  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:30:20.138  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-30 15:30:20.138  1942  1942 D WfdsService: Supplicant Connection state is changed : false
,08-30 15:30:20.138  1942  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-30 15:30:20.138  1942  2352 D WfdsService: Set the WFDS Monitor: false
08-30 15:30:20.138  1942  2352 D WfdsMonitor: WFDS Monitor is stopped
08-30 15:30:20.139  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:20.140  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-30 15:30:20.141  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-30 15:30:20.142  1036  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-30 15:30:20.142  1036  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-30 15:30:20.142  2507  2507 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:20.143  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:20.144  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:20.144  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:30:20.204  7405  7405 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 15:30:20.204  7405  7405 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 15:30:20.212  7405  7405 V [BNRBootReceiver]: Boot Receiver Return
08-30 15:30:20.212  7405  7405 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 15:30:20.219  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:20.234  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.241  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.249  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:20.249  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.251  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 15:30:20.254  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 15:30:20.256  6907  6907 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 15:30:20.260  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:20.272  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.280  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.288  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:20.289  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:30:20.290  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 15:30:20.294  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:20.298  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.313  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.326  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:30:20.327  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.328  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:20.335  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:20.356  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.369  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.377  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:20.378  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.379  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:20.383  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:20.392  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.405  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.415  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:20.416  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.417  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 15:30:20.420  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:20.434  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.444  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.453  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:30:20.454  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.455  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:20.459  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:20.472  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.483  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.491  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:20.492  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.493  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:20.501  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:20.517  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.526  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.536  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:20.536  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:30:20.545  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:20.552  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:20.568  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.583  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.595  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:30:20.595  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.598  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:20.606  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:20.607  6659  7066 D UEI.SmartControl: Internal timer expired: 2
08-30 15:30:20.607  6659  7066 D UEI.SmartControl: unbind internal service
,08-30 15:30:20.616  6927  6927 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-30 15:30:20.634  1036  1423 D WifiService: New client listening to asynchronous messages
,08-30 15:30:20.635  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:20.644  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.656  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.670  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:30:20.672  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.674  6958  6958 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 15:30:20.676  6958  6958 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 15:30:20.678  6958  6958 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 15:30:20.689  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:20.703  6927  6927 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 15:30:20.707  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:20.715  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.721  6659  7063 D serial_port: close(fd = 24)
08-30 15:30:20.725  6659  7063 I UEI.SmartControl: Serial port is closed.
08-30 15:30:20.727  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.742  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:30:20.743  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.745  6958  6958 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-30 15:30:20.747  6958  6958 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 15:30:20.748  6958  6958 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 15:30:20.751  1036  2033 I ActivityManager: Killing 6888:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-30 15:30:20.785  1036  1914 W libprocessgroup: failed to open /acct/uid_10037/pid_6888/cgroup.procs: No such file or directory
,08-30 15:30:20.793  2210  2210 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 15:30:20.818  2210  2210 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 15:30:20.819  2210  2210 D c       : Getting all permits...
,08-30 15:30:20.819  2210  2210 D a       : Opening database...
08-30 15:30:20.826  2210  2210 D a       : Opening database auth.proximity.permit_store...
08-30 15:30:20.828  2210  2210 D a       : Closing database...
08-30 15:30:20.850  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:20.859  6927  6927 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:30:20.859  6927  6927 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:30:20.859  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:20.869  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:20.881  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.893  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-30 15:30:20.894  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.898  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:30:20.906  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:20.916  6927  6927 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:30:20.917  6927  6927 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:30:20.917  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:30:20.924  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:30:20.931  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:20.945  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:20.945  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-30 15:30:20.948  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:30:20.952  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:20.959  6927  6927 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-30 15:30:20.959  6927  6927 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:30:20.960  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:30:20.964  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:30:20.971  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:30:20.981  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:20.981  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:20.983  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:30:20.993  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:30:21.001  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-30 15:30:21.010  7003  7431 W FormManager: Network not available. Please check & try again.
08-30 15:30:21.012  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:21.018  7003  7432 V FormManager: Network unavailable.
,08-30 15:30:21.028  7003  7432 V FormManager: Network unavailable.
08-30 15:30:21.032  2210  2210 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-30 15:30:21.053  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:30:21.054  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 15:30:21.056  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:30:21.058  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:21.071  6927  6927 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-30 15:30:21.071  6927  6927 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-30 15:30:21.071  6927  6927 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:21.071  4351  7433 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 15:30:21.077  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:30:21.082  4351  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:30:21.083  4351  7434 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-30 15:30:21.088  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:21.090  7003  7436 W FormManager: Network not available. Please check & try again.
08-30 15:30:21.097  7003  7437 V FormManager: Network unavailable.
08-30 15:30:21.100  7003  7437 V FormManager: Network unavailable.
08-30 15:30:21.512  1036  1392 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-609961016] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 15:30:21.514  1036  1392 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-609961014] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-30 15:30:21.696  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:21.709  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-30 15:30:21.718  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:21.722  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:21.726  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:21.728  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:30:21.730  6455  6926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:30:21.740  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 15:30:21.758  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:21.778  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:30:21.778  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:21.778  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:30:21.778  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-30 15:30:21.784  7087  7087 I AppUp4:CustModeStarterReceiver: onReceive
08-30 15:30:21.788  7087  7087 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@83a20e1
08-30 15:30:21.788  7087  7087 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:30:21.788  7087  7087 D AppUp4:CustFacade: isPhone : true
08-30 15:30:21.788  7087  7087 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:30:21.788  7087  7087 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 15:30:21.793  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:21.793  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:30:21.795  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:30:21.801  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:21.808  7120  7120 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 15:30:21.835  7120  7445 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:30:21.838  4351  7446 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:30:21.846  4351  7447 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:21.847  4351  7447 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:30:21.858  7003  7448 W FormManager: Network not available. Please check & try again.
,08-30 15:30:21.862  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:21.873  3456  3456 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 15:30:21.873  3456  3456 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:21.873  3456  3456 I LgeMiscReceiver: networkInfo.isConnected() = true
,08-30 15:30:21.873  3456  3456 D PhoneState: setPdpRejectCasuse : false
,08-30 15:30:21.882  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 15:30:21.882  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 15:30:21.883  7003  7449 V FormManager: Network unavailable.
08-30 15:30:21.890  7003  7449 V FormManager: Network unavailable.
08-30 15:30:21.893  7218  7218 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:21
,08-30 15:30:21.896  7218  7218 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:30:21.896  7218  7218 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:30:21.897  7218  7218 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:30:21.897  7218  7218 D WeatherAncestor: connectivity changed - connection : true
08-30 15:30:21.897  7218  7218 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3bdcecc7
08-30 15:30:21.898  7218  7218 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:30:21.898  7218  7218 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:30:21.898  7218  7218 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 15:30:21.898  7218  7218 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:30:21.898  7218  7218 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:21
08-30 15:30:22.685  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:22.686  1036  1960 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 15:30:22.715  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:30:22.715  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:30:22.715  1036  1036 D Ulp_jni : JNI:system_update. Event-4
,08-30 15:30:22.718  1036  1118 D BluetoothManagerService: Message: 1
08-30 15:30:22.718  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-30 15:30:22.748  1036  1118 D BluetoothManagerService: Message: 20
08-30 15:30:22.749  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2be89d44:true
,08-30 15:30:22.752  7021  7021 D BluetoothAdapterState: make
08-30 15:30:22.757  7021  7021 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 15:30:22.757  7021  7021 I bluedroid-qcom: init
08-30 15:30:22.758  7021  7476 I BluetoothAdapterState: Entering OffState
08-30 15:30:22.759  7021  7021 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 15:30:22.759  7021  7021 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 15:30:22.759  7021  7021 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 15:30:22.759  7021  7021 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 15:30:22.759  7021  7021 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 15:30:22.761  7021  7021 I bluedroid-qcom: get_profile_interface socket
08-30 15:30:22.761  7021  7021 I bluedroid-qcom: get_profile_interface map_client
,08-30 15:30:22.766  7021  7480 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 15:30:22.768  7021  7480 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 15:30:22.762  7479  7479 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:22.762  7479  7479 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:22.778  7479  7479 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 15:30:22.778  7479  7479 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 15:30:22.778  7479  7479 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-30 15:30:22.784  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 15:30:22.785  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 15:30:22.785  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:22.789  7479  7479 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 15:30:22.791  1036  1118 D Tethering: MasterInitialState.processMessage what=3
,08-30 15:30:22.797  7479  7479 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 15:30:22.797  7479  7479 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 15:30:22.800  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:22.804  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:22.806  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:22.811  1036  1118 D Tethering: MasterInitialState.processMessage what=3
08-30 15:30:22.813  7021  7480 D BluetoothAdapterProperties: Name is: G3
08-30 15:30:22.820  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:22.825  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-30 15:30:22.827  6455  6926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:30:22.829  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 15:30:22.830  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:22.830  1036  1118 D BluetoothManagerService: Message: 40
08-30 15:30:22.830  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 15:30:22.831  7021  7038 I bluedroid-qcom: config_hci_snoop_log
08-30 15:30:22.832  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 15:30:22.832  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-30 15:30:22.837  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-30 15:30:22.847  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 15:30:22.853  7021  7476 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 15:30:22.853  7021  7476 D BluetoothAdapterProperties: Setting state to 11
08-30 15:30:22.854  7021  7476 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 15:30:22.856  7021  7476 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 15:30:22.858  1036  1118 D BluetoothManagerService: Message: 60
08-30 15:30:22.858  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 15:30:22.858  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 15:30:22.859  5792  5792 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-30 15:30:22.864  7021  7476 D BluetoothBondStateMachine: make
08-30 15:30:22.866  6907  6907 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-30 15:30:22.869  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:22.870  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:22.870  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:30:22.871  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:22.873  7021  7476 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:22.873  7021  7476 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 15:30:22.873  7021  7476 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:22.873  7021  7476 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 15:30:22.874  7021  7496 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 15:30:22.874  7021  7476 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-30 15:30:22.879  7021  7476 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:30:22.884  7021  7021 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:30:22.884  7021  7021 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:22.885  7021  7021 V BluetoothPbapReceiver: ***********state = 11
08-30 15:30:22.890  7021  7476 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:30:22.893  7021  7021 D HeadsetService: Received start request. Starting profile...
08-30 15:30:22.894  7021  7021 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:30:22.894  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:30:22.894  7021  7021 D LGBluetoothHfpAdapter: Version 1.6
08-30 15:30:22.895  1036  1109 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:22.897  7021  7021 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 15:30:22.898  7021  7021 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:30:22.899  7021  7021 D HeadsetStateMachine: make
08-30 15:30:22.902  7021  7476 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:30:22.931  7021  7021 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:22.931  7021  7021 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:22.949  1036  1960 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7500 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-30 15:30:22.952  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:22.952  7021  7021 D HeadsetStateMachine: max_hf_connections = 1
08-30 15:30:22.952  7021  7021 I bluedroid-qcom: get_profile_interface handsfree
08-30 15:30:22.952  1036  1109 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:22.954  7021  7021 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 15:30:22.955   316  1782 V AudioPolicyService: registerClient() client 0xb0404660, uid 1002
08-30 15:30:22.955   316  1403 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 15:30:22.955   316  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:30:22.955   316  1403 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:30:22.955  7021  7021 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 15:30:22.956   316   316 V AudioFlinger: registerClient() client 0xb1433220, pid 7021
08-30 15:30:22.957   316  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:22.957   316  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:22.957  7021  7021 V ToneGenerator: Create Track: 0xb4928080
08-30 15:30:22.957  7021  7476 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:30:22.957  7021  7021 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 15:30:22.957  7021  7021 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 15:30:22.957   316  1403 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 15:30:22.957   316  1403 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 15:30:22.957   316  1403 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:30:22.957   316  1403 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:30:22.957  7021  7021 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 15:30:22.958  1036  1959 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:22.958  1036  1959 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:22.958  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:22.958  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:22.958  1602  3125 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:22.958   316  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:22.958   316  1395 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:22.958  1602  3125 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:22.958  7021  7038 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:22.958  1602  3125 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:22.959  7021  7038 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 15:30:22.959  1602  3125 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:22.959  7021  7038 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:22.959  7021  7038 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 15:30:22.959  1853  4020 V AudioSystem: ioConfigChanged() event 0, ,ioHandle 2
08-30 15:30:22.959  3456  3473 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:22.959  1853  4020 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:22.959  3456  3473 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:22.959  1036  1652 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:22.959  1036  1652 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:22.959  3456  3473 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:22.959  3456  3473 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:22.959   316  1402 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 15:30:22.959  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:22.960   316  1782 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 15:30:22.960   316  1782 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 15:30:22.960   316  1782 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:30:22.960   316  1782 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:30:22.960  7021  7021 V AudioSystem: getLatency() output 2, latency 50
08-30 15:30:22.960  7021  7021 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 15:30:22.960  7021  7021 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 15:30:22.960   316  1403 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 15:30:22.960   316  1403 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 15:30:22.960   316  1403 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 15:30:22.960   316  1403 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 15:30:22.960   316  1403 V AudioFlinger: createTrack() lSessionId: 20
08-30 15:30:22.966  7021  7021 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 15:30:22.966   316  1402 V AudioFlinger: acquiring 20 from 7021, for 7021
08-30 15:30:22.966   316  1402 V AudioFlinger:  added new entry for 20
08-30 15:30:22.966  7021  7021 V ToneGenerator: ToneGenerator INIT OK, time: 209837
08-30 15:30:22.967  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:22.968  7021  7476 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:30:22.969  7021  7499 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 15:30:22.969  7021  7499 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:30:22.969  7021  7499 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:30:22.970  7021  7499 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-30 15:30:22.970   316  1782 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7021
08-30 15:30:22.970   316  1782 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 15:30:22.970   316  1782 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 15:30:22.970   316  1782 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 15:30:22.970   316  1782 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 15:30:22.970   316  1782 V voice   : voice_set_parameters: exit with code(0)
08-30 15:30:22.970   316  1782 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 15:30:22.970   316  1782 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 15:30:22.970   316  1782 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 15:30:22.970   316  1782 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 15:30:22.970   316  1782 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 15:30:22.970   316  1782 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 15:30:22.971  7021  7499 V ToneGenerator: ToneGenerator destructor
08-30 15:30:22.971  7021  7499 V ToneGenerator: stopTone
08-30 15:30:22.971  7021  7499 V ToneGenerator: Delete Track: 0xb4928080
08-30 15:30:22.971  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:22.971  7021  7499 V AudioTrack: ~AudioTrack, releasing session id from 7021 on behalf of 7021
08-30 15:30:22.971   316  1402 V AudioFlinger: releasing 20 from 7021 for 7021
08-30 15:30:22.971   316  1402 V AudioFlinger:  decremented refcount to 0
08-30 15:30:22.971   316  1402 V AudioFlinger: purging stale effects
08-30 15:30:22.971   316  1402 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 15:30:22.971   316  1402 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 15:30:22.971   316  1275 V AudioPolicyService: AudioCommandThread() waking up
08-30 15:30:22.971   316  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 15:30:22.971   316  1275 V AudioPolicyManager: releaseOutput() 2
08-30 15:30:22.971   316  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 15:30:22.971   316  1402 V AudioFlinger: PlaybackThread::Track destructor
08-30 15:30:22.971   316  1402 V AudioFlinger: removeClient_l() pid 7021, calling pid 316
08-30 15:30:22.974  7021  7021 D A2dpService: Received start request. Starting profile...
08-30 15:30:22.975  7021  7021 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 15:30:22.975  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-30 15:30:22.975  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:22.975  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:30:22.975  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 15:30:22.976  7021  7021 V Avrcp   : make
08-30 15:30:22.976  7021  7021 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 15:30:22.976  7021  7476 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:30:22.976  7021  7021 I bluedroid-qcom: get_profile_interface avrcp
08-30 15:30:22.979  7087  7087 I AppUp4:CustModeStarterReceiver: onReceive
08-30 15:30:22.983  7087  7087 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@83a20e1
08-30 15:30:22.983  7087  7087 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:30:22.983  7087  7087 D AppUp4:CustFacade: isPhone : true
08-30 15:30:22.984  7087  7087 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:30:22.985  7087  7087 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 15:30:22.986  7021  7021 V AudioManager: registerRemoteController: size of Media player list: 0
08-30 15:30:22.985  7021  7476 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:30:22.988  7021  7021 E AudioManager: No RCC entry present to update
08-30 15:30:22.988  7021  7021 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 15:30:22.988  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:22.988  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 15:30:22.990  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:22.991  7021  7021 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-30 15:30:22.992  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:22.992  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 15:30:22.992  7021  7021 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 15:30:22.996  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 15:30:22.998  7021  7476 V LGMDMManager: Create singleton instance
08-30 15:30:23.000  7021  7476 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 15:30:23.005  4351  7522 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:30:23.008  4351  7523 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:23.008  4351  7523 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:30:23.045  7120  7120 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-30 15:30:23.080  7120  7524 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:30:23.087  3456  3456 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 15:30:23.087  3456  3456 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:23.087  3456  3456 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 15:30:23.091  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-30 15:30:23.092  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 15:30:23.093  7003  7526 W FormManager: Network not available. Please check & try again.
08-30 15:30:23.095  1036  1941 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:30:23.096  1036  1941 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:30:23.096  7003  7527 V FormManager: Network unavailable.
08-30 15:30:23.106  7500  7500 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-30 15:30:23.106  7500  7500 W LG Account v2.2: No ProfileInfo entries
08-30 15:30:23.106  7500  7500 I LG Account v2.2: isEnabled: false
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Country: EU
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Operator: OPEN
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Ranking support: false
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Comfort support: false
08-30 15:30:23.106  7003  7527 V FormManager: Network unavailable.
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Accessory: true
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Health device: true
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Extra Pedometer: false
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Blood glucose device: false
08-30 15:30:23.106  7500  7500 I Feature : [Lifetracker]Device Number: 3
,08-30 15:30:23.113  7218  7218 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:23
,08-30 15:30:23.115  7218  7218 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:30:23.115  7218  7218 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:30:23.116  7218  7218 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:30:23.116  7218  7218 D WeatherAncestor: connectivity changed - connection : true
08-30 15:30:23.116  7218  7218 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3bdcecc7
08-30 15:30:23.117  7218  7218 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:30:23.117  7218  7218 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:30:23.117  7218  7218 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 15:30:23.117  7218  7218 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:30:23.117  7218  7218 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:23
08-30 15:30:23.118  6907  6907 D BluetoothPermissionRequest: onReceive
08-30 15:30:23.125  6907  6907 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 15:30:23.136  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-30 15:30:23.137  6455  6926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-30 15:30:23.147  2210  2210 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:23.152  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-30 15:30:23.152  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:23.153  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-30 15:30:23.153  7087  7087 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-30 15:30:23.155  7087  7087 I AppUp4:CustModeStarterReceiver: onReceive
08-30 15:30:23.159  7087  7087 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@83a20e1
08-30 15:30:23.159  7087  7087 D AppUp4:CustFacade: isCustomizationCompleted : false
08-30 15:30:23.159  7087  7087 D AppUp4:CustFacade: isPhone : true
08-30 15:30:23.159  7087  7087 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:30:23.159  7087  7087 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-30 15:30:23.162  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:23.162  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-30 15:30:23.164  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-30 15:30:23.165  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:23.171  7120  7120 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-30 15:30:23.172  4351  7531 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-30 15:30:23.174  4351  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:23.174  4351  7532 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:30:23.187  1036  1575 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 15:30:23.188  7120  7533 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:30:23.191  3456  3456 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-30 15:30:23.191  3456  3456 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:23.192  3456  3456 I LgeMiscReceiver: networkInfo.isConnected() = false
08-30 15:30:23.194  7159  7159 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-30 15:30:23.194  7159  7159 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-30 15:30:23.195  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 15:30:23.200  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 15:30:23.200  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 15:30:23.200  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 15:30:23.201  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 15:30:23.201  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:30:23.201  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 15:30:23.201  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 15:30:23.201  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 15:30:23.201  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-30 15:30:23.201  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 15:30:23.201  7021  7021 I BluetoothA2dpServiceJni: classInitNative
08-30 15:30:23.201  7021  7021 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:30:23.201  7021  7021 D A2dpStateMachine: make
,08-30 15:30:23.203  7021  7021 I bluedroid-qcom: get_profile_interface a2dp
08-30 15:30:23.204  7021  7539 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 15:30:23.204  7003  7536 W FormManager: Network not available. Please check & try again.
08-30 15:30:23.206  7021  7021 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:30:23.206  7021  7021 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-30 15:30:23.207  7218  7218 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:23
08-30 15:30:23.208  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:23.208  7003  7537 V FormManager: Network unavailable.
08-30 15:30:23.209  7021  7538 D A2dpStateMachine: Enter Disconnected: -2
08-30 15:30:23.209  7021  7021 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 15:30:23.210  7003  7537 V FormManager: Network unavailable.
08-30 15:30:23.210  7021  7021 D HeadsetStateMachine: Proxy object connected
08-30 15:30:23.210  7218  7218 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-30 15:30:23.210  7218  7218 D Weather.Utils: 2 : All the weather widget is gone.
08-30 15:30:23.211  7218  7218 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 15:30:23.211  7021  7021 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 15:30:23.211  7218  7218 D WeatherAncestor: connectivity changed - connection : true
08-30 15:30:23.211  7021  7021 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 15:30:23.211  7218  7218 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3bdcecc7
08-30 15:30:23.212  7021  7021 D HidService: Received start request. Starting profile...
08-30 15:30:23.212  7021  7021 I bluedroid-qcom: get_profile_interface hidhost
08-30 15:30:23.212  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:23.213  7021  7021 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:30:23.215  7021  7021 D HealthService: Received start request. Starting profile...
,08-30 15:30:23.216  7021  7021 I bluedroid-qcom: get_profile_interface health
08-30 15:30:23.216  7021  7021 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:30:23.216  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:23.217  7021  7499 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 15:30:23.217  7218  7218 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-30 15:30:23.217  7218  7218 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-30 15:30:23.217  7218  7218 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-30 15:30:23.217  7218  7218 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 15:30:23.217  7218  7218 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:30:23
08-30 15:30:23.218  7021  7499 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 15:30:23.218  7021  7499 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 15:30:23.221  7021  7021 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:30:23.221  7021  7021 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 15:30:23.223  7021  7021 D PanService: Received start request. Starting profile...
08-30 15:30:23.223  7021  7021 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 15:30:23.223  7021  7021 I bluedroid-qcom: get_profile_interface pan
08-30 15:30:23.228  7021  7021 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-30 15:30:23.228  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:23.229  7021  7021 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-30 15:30:23.234  7021  7021 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 15:30:23.234  7021  7021 D BtGatt.GattService: Received start request. Starting profile...
08-30 15:30:23.234  7021  7021 D BtGatt.GattService: start()
08-30 15:30:23.234  7021  7021 I bluedroid-qcom: get_profile_interface gatt
08-30 15:30:23.235  7021  7021 D BtGatt.AdvertiseManager: advertise manager created
08-30 15:30:23.239  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:23.241  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:23.241  7021  7021 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 15:30:23.242  7021  7021 V BluetoothMapService: BluetoothMapBinder()
,08-30 15:30:23.242  7021  7021 D BluetoothMapService: Received start request. Starting profile...
,08-30 15:30:23.242  7021  7021 D BluetoothMapService: start()
08-30 15:30:23.245  7021  7021 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 15:30:23.245  7021  7021 D BluetoothMapEmailAppObserver: createReceiver()
08-30 15:30:23.246  7021  7021 D BluetoothMapEmailAppObserver: initObservers()
08-30 15:30:23.246  7021  7021 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 15:30:23.254  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
,08-30 15:30:23.260  7021  7021 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:30:23.262  7021  7021 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:30:23.266  7021  7021 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:30:23.266  7021  7021 V PanService: [BTUI] SIM Extra State :ABSENT
08-30 15:30:23.269  7021  7021 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 15:30:23.272  7021  7021 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 15:30:23.272  7021  7021 V BluetoothMapService: Handler(): got msg=1
08-30 15:30:23.273  7021  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 15:30:23.273  7021  7476 I bluedroid-qcom: enable
08-30 15:30:23.274  7021  7546 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 15:30:23.274  7021  7476 I bt_hci_bdroid: init
08-30 15:30:23.275  7021  7476 I bt_vendor: bt-vendor : init
08-30 15:30:23.275  7021  7476 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 15:30:23.275  7021  7021 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:23.275  7021  7476 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 15:30:23.275  7021  7476 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 15:30:23.275  7021  7476 D bt_userial_mct: userial_init
08-30 15:30:23.275  7021  7546 I bt-btu  : btu_task pending for preload complete event
08-30 15:30:23.275  7021  7476 D bt_hci_bdroid: set_power 1
08-30 15:30:23.275  7021  7476 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 15:30:23.275  7021  7476 I bt_vendor: Starting hciattach daemon
08-30 15:30:23.275  7021  7476 I bt_vendor: try to set true
08-30 15:30:23.262  7549  7549 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:23.278  7021  7021 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:30:23.278  7021  7021 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:30:23.279  7021  7021 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:30:23.279  7021  7021 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:23.279  7021  7021 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 15:30:23.262  7549  7549 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:23.301  7550  7550 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 15:30:23.408  7556  7556 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 15:30:23.434  7557  7557 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 15:30:23.478  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 15:30:23.496  7563  7563 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-30 15:30:23.515  7564  7564 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 15:30:23.537  7565  7565 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 15:30:23.563  7567  7567 I libmdmdetect: ESOC framework not supported
,08-30 15:30:23.564  7567  7567 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 15:30:23.572  7567  7567 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 15:30:23.572  7567  7567 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 15:30:23.572  7567  7567 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 15:30:23.572  7567  7567 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 15:30:23.572  7567  7567 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 15:30:23.572  7567  7567 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 15:30:23.572  7567  7567 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-30 15:30:23.612  7567  7568 E QC-QMI  : qmi_client [7567] 14: failed to locate client data
08-30 15:30:23.613   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 15:30:23.613   470   470 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-30 15:30:23.661  7569  7569 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 15:30:23.682  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 15:30:23.731  7021  7476 I bt_vendor: bluetooth satus is on
08-30 15:30:23.731  7021  7476 D bt_hci_bdroid: preload
08-30 15:30:23.731  7021  7548 D bt_userial_mct: userial_open(port:0)
08-30 15:30:23.731  7021  7548 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 15:30:23.735  7021  7548 I bt_vendor: Done intiailizing UART
08-30 15:30:23.736  7021  7548 I bt_vendor: Done intiailizing UART
08-30 15:30:23.736  7021  7548 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 15:30:23.737  7021  7548 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-30 15:30:23.737  7021  7572 D bt_userial_mct: Entering userial_read_thread()
08-30 15:30:23.737  7021  7546 I bt-btu  : btu_task received preload complete event
08-30 15:30:23.737  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 15:30:23.737  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 15:30:23.740  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 15:30:23.743  7021  7546 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 15:30:23.744  7021  7546 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 15:30:23.796  1036  1111 W ProcessCpuTracker: Skipping unknown process pid 7485
,08-30 15:30:23.798  1036  1111 W ProcessCpuTracker: Skipping unknown process pid 7488
08-30 15:30:23.812  7021  7546 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 15:30:23.812  7021  7546 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0240061 
08-30 15:30:23.812  7021  7546 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0240061 
,08-30 15:30:23.840  7021  7480 E bt-btif : Calling BTA_HhEnable
,08-30 15:30:23.841  7021  7480 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 15:30:23.841  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-30 15:30:23.841  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-30 15:30:23.841  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 15:30:23.841  7021  7480 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 15:30:23.842  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 15:30:23.842  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-30 15:30:23.848  7021  7480 D BluetoothAdapterProperties: Name is: G3
,08-30 15:30:23.851  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 15:30:23.852  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 15:30:23.853  7021  7480 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:30:23.854  7021  7480 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:30:23.854  7021  7480 D bt_hci_bdroid: postload
08-30 15:30:23.855  7021  7548 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:30:23.856  7021  7546 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-30 15:30:23.857  7021  7480 D bte_conf: Device ID record 1 : primary
08-30 15:30:23.857  7021  7480 D bte_conf:   vendorId            = 00c4
08-30 15:30:23.857  7021  7480 D bte_conf:   vendorIdSource      = 0001
08-30 15:30:23.858  7021  7480 D bte_conf:   product             = 13a1
08-30 15:30:23.858  7021  7480 D bte_conf:   version             = 1000
08-30 15:30:23.858  7021  7480 D bte_conf:   clientExecutableURL = 
08-30 15:30:23.858  7021  7480 D bte_conf:   serviceDescription  = 
08-30 15:30:23.858  7021  7480 D bte_conf:   documentationURL    = 
08-30 15:30:23.858  7021  7480 D bte_conf: bte_load_did_conf no section named DID2.
08-30 15:30:23.862  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:23.864  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:23.866  7021  7548 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:30:23.868  7021  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 15:30:23.868  7021  7476 D BluetoothAdapterProperties: ScanMode =  20
08-30 15:30:23.868  7021  7476 D BluetoothAdapterProperties: State =  11
08-30 15:30:23.869  7021  7476 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 15:30:23.870  7021  7476 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-30 15:30:23.870  7021  7476 D BluetoothAdapterProperties: Setting state to 12
08-30 15:30:23.870  7021  7476 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 15:30:23.870  7021  7480 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 15:30:23.871  7021  7480 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 15:30:23.872  7021  7548 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:30:23.872  7021  7548 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:30:23.873  1036  1118 D BluetoothManagerService: Message: 60
,08-30 15:30:23.873  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 15:30:23.873  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-30 15:30:23.862  7577  7577 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:23.862  7577  7577 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:23.877  7021  7548 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:30:23.877  7021  7548 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:30:23.878  7021  7476 I BluetoothAdapterState: Entering On State
08-30 15:30:23.881  7021  7476 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 15:30:23.881  7021  7476 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 15:30:23.881  7021  7476 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-30 15:30:23.884  7021  7476 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 15:30:23.886  7021  7572 E bt_mct  : hci lib postload completed
,08-30 15:30:23.887  6907  6923 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 15:30:23.890  7021  7480 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:30:23.890  7021  7480 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-30 15:30:23.892  6907  6996 D BluetoothPan: onBluetoothStateChange on: true
08-30 15:30:23.892  6907  6996 D BluetoothPan: onBluetoothStateChange call bindService
08-30 15:30:23.895  7021  7546 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:23.895  7021  7546 W bt-smp  : Plain text(LSB ~ MSB) = 7b 20 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:23.895  7021  7546 W bt-smp  : Encrypted text(LSB ~ MSB) = d1 06 d0 ed e9 b9 df dd b1 f2 e7 56 29 4a bf 51 
08-30 15:30:23.895  7021  7546 W bt-btm  : Stopping oneshot timer
08-30 15:30:23.897  6907  7346 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 15:30:23.899  6907  6907 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:30:23.899  6907  6907 D PanProfile: Bluetooth service connected
,08-30 15:30:23.907  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:23.922  1036  1036 D BluetoothHeadset: Proxy object connected
,08-30 15:30:23.927  7021  7546 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:23.927  7021  7546 W bt-smp  : Plain text(LSB ~ MSB) = 9d da 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:23.927  7021  7546 W bt-smp  : Encrypted text(LSB ~ MSB) = 78 9f ae 8c 25 6c 25 8c e5 59 4b d1 f7 4b 78 8c 
08-30 15:30:23.927  7021  7546 W bt-btm  : Stopping oneshot timer
08-30 15:30:23.928  7021  7476 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-30 15:30:23.931  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:30:23.934  1036  1036 D BluetoothA2dp: Proxy object connected
08-30 15:30:23.938  1853  4020 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:23.942  1853  1853 D BluetoothHeadset: Proxy object connected
08-30 15:30:23.942  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:23.944  1853  1853 D BluetoothHeadset: Proxy object connected
,08-30 15:30:23.945  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:23.947  1853  1853 D BluetoothHeadset: Proxy object connected
08-30 15:30:23.948  6907  6922 D BluetoothMap: onBluetoothStateChange: up=true
08-30 15:30:23.948  6907  6907 D BluetoothInputDevice: Proxy object connected
08-30 15:30:23.948  7588  7588 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-30 15:30:23.948  6907  6907 D HidProfile: Bluetooth service connected
08-30 15:30:23.952  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 15:30:23.952  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 15:30:23.953  6907  6907 D BluetoothMap: Proxy object connected
08-30 15:30:23.954  6907  6907 D MapProfile: Bluetooth service connected
08-30 15:30:23.954  6907  6907 D BluetoothMap: getConnectedDevices()
08-30 15:30:23.957  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:30:23.957  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:23.957  1942  2124 D LGBluetoothAPIService: Message: 1
08-30 15:30:23.957  1942  2124 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 15:30:23.958  7021  7546 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:23.958  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 15:30:23.958  7021  7546 W bt-smp  : Plain text(LSB ~ MSB) = ee b9 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:23.958  7021  7546 W bt-smp  : Encrypted text(LSB ~ MSB) = 69 08 4e 6c b2 a2 e6 c0 d3 11 8e c8 5b 72 52 74 
08-30 15:30:23.958  7021  7546 W bt-btm  : Stopping oneshot timer
08-30 15:30:23.958  1036  1118 D BluetoothManagerService: Message: 40
08-30 15:30:23.958  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 15:30:23.962  7021  7586 V BluetoothMapService: getConnectedDevices()
,08-30 15:30:23.964  6765  6765 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 15:30:23.971  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:23.971  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:23.971  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:23.971  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:23.971  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:23.971  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:23.971  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:23.971  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:23.973  1942  2124 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-30 15:30:23.974  7021  7021 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:23.974  7021  7021 D BluetoothMapService: STATE_ON
,08-30 15:30:23.976  7021  7546 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:23.976  7021  7546 W bt-smp  : Plain text(LSB ~ MSB) = ce 2d 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:23.976  7021  7546 W bt-smp  : Encrypted text(LSB ~ MSB) = 95 2f 5d 56 18 7e a9 77 7e b9 05 e0 3c 87 3a 68 
08-30 15:30:23.976  7021  7546 W bt-btm  : Stopping oneshot timer
08-30 15:30:23.977  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:23.981  6907  6907 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 15:30:23.984  7021  7546 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:23.984  7021  7546 W bt-smp  : Plain text(LSB ~ MSB) = 0f 85 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:23.984  7021  7546 W bt-smp  : Encrypted text(LSB ~ MSB) = b0 65 82 3b 8b 27 f8 2a 9b 1e 8c 82 e5 a8 82 a3 
08-30 15:30:23.984  7021  7546 W bt-btm  : Stopping oneshot timer
,08-30 15:30:23.984  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:23.984  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:23.984  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:23.984  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:23.984  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:23.984  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:23.984  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:23.984  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:23.988  1036  1118 D BluetoothManagerService: Message: 30
08-30 15:30:23.992  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:23.993  6907  6907 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-30 15:30:23.996  1036  1118 D BluetoothManagerService: Message: 30
08-30 15:30:23.999  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
,08-30 15:30:23.999  7021  7021 V BluetoothPbapService: Pbap Service onCreate
08-30 15:30:23.999  7021  7021 V BluetoothPbapService: Starting PBAP service
08-30 15:30:24.001  6907  6907 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 15:30:24.001  7021  7021 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 15:30:24.001  7021  7021 V BluetoothPbapService: Pbap Service onBind
08-30 15:30:24.002  7021  7021 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:24.002  7021  7021 V BluetoothPbapService: state: 12
08-30 15:30:24.003  6907  6907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-30 15:30:24.004  7021  7021 D LGBluetoothAPIServer: [BTUI] onCreate()
08-30 15:30:24.004  7021  7021 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 15:30:24.005  6907  6907 D BluetoothA2dp: Proxy object connected
08-30 15:30:24.006  6907  6907 D A2dpProfile: Bluetooth service connected
08-30 15:30:24.006  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 15:30:24.006  1942  2124 D LGBluetoothAPIService: Message: 100
08-30 15:30:24.006  1942  2124 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-30 15:30:24.007  7021  7021 V BluetoothMapService: Handler(): got msg=1
08-30 15:30:24.007  7021  7021 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 15:30:24.007  7021  7021 V BluetoothPbapService: Handler(): got msg=1
08-30 15:30:24.008  7021  7021 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 15:30:24.009  7021  7595 D BluetoothMapMasInstance: MAS initSocket()
08-30 15:30:24.009  6907  6907 D BluetoothHeadset: Proxy object connected
08-30 15:30:24.009  7021  7021 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:30:24.009  7021  7021 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:24.009  7021  7595 D BluetoothMapMasInstance:   masId = 00
08-30 15:30:24.009  7021  7595 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 15:30:24.009  7021  7595 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 15:30:24.009  7021  7595 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 15:30:24.009  7021  7021 V BluetoothPbapReceiver: ***********state = 12
08-30 15:30:24.010  7021  7596 V BluetoothPbapService: Pbap Service initSocket
08-30 15:30:24.010  6907  6907 D HeadsetProfile: Bluetooth service connected
,08-30 15:30:24.013  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:30:24.014  2210  2210 D c       : Getting all permits...
08-30 15:30:24.014  1036  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:24.014  2210  2210 D a       : Opening database...
08-30 15:30:24.014  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:24.015  6907  6907 D BluetoothPbap: Proxy object connected
08-30 15:30:24.016  7021  7596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:24.016  6907  6907 D PbapServerProfile: Bluetooth service connected
08-30 15:30:24.017  7021  7596 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 15:30:24.017  7021  7596 V BluetoothPbapService: Succeed to create listening socket 
08-30 15:30:24.017  7021  7596 V BluetoothPbapService: Accepting socket connection...
08-30 15:30:24.018  7021  7480 D BluetoothAdapterProperties: Scan Mode:21
08-30 15:30:24.018  7021  7480 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 15:30:24.020  7021  7595 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:24.021  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:24.021  7021  7595 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-30 15:30:24.021  7021  7595 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 15:30:24.021  7021  7595 D BluetoothMapMasInstance: Accepting socket connection...
08-30 15:30:24.022  6907  6907 D DockEventReceiver: finishStartingService: stopping service
08-30 15:30:24.022  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:24.023  2210  2210 D a       : Opening database auth.proximity.permit_store...
,08-30 15:30:24.024  2210  2210 D a       : Closing database...
08-30 15:30:24.038  6907  6907 D BluetoothPermissionRequest: onReceive
,08-30 15:30:24.040  6907  6907 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 15:30:24.042  6907  6907 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:30:24.045  7253  7306 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-30 15:30:24.046  7021  7021 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 15:30:24.047  7021  7021 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 15:30:24.052  7021  7021 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-30 15:30:24.069  7021  7021 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-30 15:30:24.069  7021  7021 V BtOppService: onCreate
08-30 15:30:24.073  7021  7021 V BluetoothOppNotification: send message
,08-30 15:30:24.076  7021  7021 V BtOppService: Starting RfcommListener
08-30 15:30:24.079  7021  7021 D BluetoothOppPreference: Dumping Names:  
08-30 15:30:24.080  7021  7021 D BluetoothOppPreference: {}
,08-30 15:30:24.080  7021  7021 D BluetoothOppPreference: Dumping Channels:  
08-30 15:30:24.080  7021  7021 D BluetoothOppPreference: {}
08-30 15:30:24.080  7021  7021 V BtOppService: onStartCommand
,08-30 15:30:24.084  7021  7021 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:24.085  7021  7021 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-30 15:30:24.088  7021  7021 V BluetoothOppNotification: new notify threadi!
08-30 15:30:24.088  7021  7606 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:30:24.089  7021  7021 V BluetoothOppNotification: send delay message
08-30 15:30:24.089  7021  7021 V BtOppService: start RfcommListener
08-30 15:30:24.092  7021  7602 V BtOppService: Deleted complete outbound shares, number =  0
08-30 15:30:24.092  7021  7021 V BtOppService: RfcommListener started
08-30 15:30:24.092  7021  7606 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 15:30:24.093  7021  7607 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 15:30:24.093  7021  7602 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 15:30:24.093  7021  7602 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-30 15:30:24.094  7021  7606 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@285541f0 on behalf of 
08-30 15:30:24.098  7021  7608 V BtOppRfcommListener: Starting RFCOMM listener....
08-30 15:30:24.098  7021  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16046369 on behalf of 
08-30 15:30:24.098  1036  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:30:24.099  7021  7602 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25e81ee on behalf of 
08-30 15:30:24.100  7021  7607 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 15:30:24.101  7021  7608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:24.101  7021  7606 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 15:30:24.102  7021  7608 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 15:30:24.102  7021  7607 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 15:30:24.102  7021  7608 V BtOppRfcommListener: Started RFCOMM listener....
,08-30 15:30:24.102  7021  7608 I BtOppRfcommListener: Accept thread started.
08-30 15:30:24.102  7021  7608 V BtOppRfcommListener: Accepting connection...
08-30 15:30:24.103  7021  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39e8068f on behalf of 
08-30 15:30:24.104  7021  7607 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 15:30:24.105  7021  7607 V BluetoothOppNotification: outbound notification was removed.
08-30 15:30:24.105  7021  7607 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 15:30:24.106  7021  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b648d1c on behalf of 
08-30 15:30:24.107  7021  7607 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 15:30:24.109  7021  7607 V BluetoothOppNotification: inbound notification was removed.
,08-30 15:30:24.110  7021  7607 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 15:30:24.111  7021  7607 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c76cd25 on behalf of 
08-30 15:30:24.112  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:24.112  7021  7021 V BluetoothFtpService: Ftp Service onCreate
08-30 15:30:24.112  7021  7021 I BluetoothFtpService: Ftp Service onCreate
08-30 15:30:24.112  7021  7021 V BluetoothFtpService: Ftp Service onStartCommand
08-30 15:30:24.112  7021  7021 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:24.113  7021  7021 V BluetoothFtpService: Starting Listening on sockets
08-30 15:30:24.113  7021  7021 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:30:24.113  7021  7021 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:30:24.113  7021  7021 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:30:24.113  7021  7021 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:30:24.113  7021  7021 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 15:30:24.114  7021  7021 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 15:30:24.115  7021  7021 V BtOppService: ContentObserver received notification
08-30 15:30:24.115  7021  7021 V BtOppService: ContentObserver received notification
08-30 15:30:24.116  7021  7021 V BluetoothFtpService: Handler(): got msg=1
08-30 15:30:24.117  7021  7609 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:30:24.117  7021  7609 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 15:30:24.119  7021  7021 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 15:30:24.119  7021  7021 V BluetoothFtpService: Ftp Service initSocket
08-30 15:30:24.121  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:24.122  7021  7021 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:24.123  7021  7609 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23687cab on behalf of 
08-30 15:30:24.123  7021  7609 V BluetoothOppNotification: update too frequent, put in queue
,08-30 15:30:24.124  7021  7609 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-30 15:30:24.126  7021  7021 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 15:30:24.126  7021  7021 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 15:30:24.128  7021  7610 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 15:30:24.162  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:24.162  7021  7021 V BluetoothSapService: Sap Service onCreate
08-30 15:30:24.165  7021  7021 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:24.165  7021  7021 V BluetoothSapService: state: 12
08-30 15:30:24.165  7021  7021 V BluetoothSapService: Starting SAP server process
,08-30 15:30:24.167  7021  7021 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 15:30:24.152  7611  7611 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:24.152  7611  7611 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:24.173  7021  7612 V BluetoothSapService: Sap Service initRfcommSocket
08-30 15:30:24.174  1036  2017 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:24.176  7021  7612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:24.179  7021  7612 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 15:30:24.179  7021  7612 V BluetoothSapService: Succeed to create listening socket 
08-30 15:30:24.180  7021  7612 V BluetoothSapService: Accepting socket connection...
,08-30 15:30:24.184  7611  7611 V BT_SAP  : Event pipe created
,08-30 15:30:24.184  7611  7611 V BT_SAP  : create_server_socket qcom.sap.server
08-30 15:30:24.184  7611  7611 V BT_SAP  : created socket fd 6
08-30 15:30:24.747  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:30:24.747  1036  1389 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 15:30:24.783  1036  1392 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 15:30:24.785  1036  1392 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-30 15:30:24.932  1036  1896 I ActivityManager: Killing 7405:com.lge.bnr/1000 (adj 15): empty #17
,08-30 15:30:24.970  1036  1652 W libprocessgroup: failed to open /acct/uid_1000/pid_7405/cgroup.procs: No such file or directory
,08-30 15:30:25.047  1036  1781 I ActivityManager: Killing 6659:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-30 15:30:25.079  6958  6958 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-30 15:30:25.082  6958  6958 W System.err: android.os.DeadObjectException
08-30 15:30:25.082  6958  6958 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 15:30:25.082  6958  6958 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 15:30:25.082  6958  6958 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-30 15:30:25.082  6958  6958 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-30 15:30:25.082  6958  6958 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 15:30:25.082  6958  6958 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 15:30:25.082  6958  6958 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:30:25.083  6958  6958 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:30:25.083  6958  6958 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:30:25.083  6958  6958 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:30:25.083  6958  6958 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:30:25.083  6958  6958 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:30:25.083  6958  6958 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:30:25.083  6958  6958 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:30:25.084  6958  6958 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-30 15:30:25.084  6958  6958 W System.err: android.os.DeadObjectException
08-30 15:30:25.085  6958  6958 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 15:30:25.085  6958  6958 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 15:30:25.085  6958  6958 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-30 15:30:25.085  6958  6958 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-30 15:30:25.085  6958  6958 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-30 15:30:25.085  6958  6958 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-30 15:30:25.085  6958  6958 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:30:25.085  6958  6958 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:30:25.085  6958  6958 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:30:25.085  6958  6958 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:30:25.085  6958  6958 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:30:25.085  6958  6958 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:30:25.085  6958  6958 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:30:25.085  6958  6958 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:30:25.085  6958  6958 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-30 15:30:25.086  6958  6958 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-30 15:30:25.090  7021  7021 V BluetoothOppNotification: new notify threadi!
08-30 15:30:25.090  7021  7021 V BluetoothOppNotification: send delay message
08-30 15:30:25.091  7021  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; ,sort is _id.
,08-30 15:30:25.098  7021  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c303887 on behalf of 
08-30 15:30:25.099  7021  7622 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 15:30:25.100  7021  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 15:30:25.140  1036  1936 W libprocessgroup: failed to open /acct/uid_1000/pid_6659/cgroup.procs: No such file or directory
08-30 15:30:25.141  1036  1936 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-30 15:30:25.158  6958  6958 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-30 15:30:25.158  6958  6958 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-30 15:30:25.268  1036  1652 I art     : Explicit concurrent mark sweep GC freed 93284(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.759ms total 157.813ms
,08-30 15:30:25.280  7021  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12b63b4 on behalf of 
08-30 15:30:25.280  7021  7622 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-30 15:30:25.305  1036  2033 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7623 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-30 15:30:25.335  6958  6958 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-30 15:30:25.337  7021  7622 V BluetoothOppNotification: outbound notification was removed.
08-30 15:30:25.343  7021  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 15:30:25.346  7021  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9127bdd on behalf of 
08-30 15:30:25.347  7021  7622 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-30 15:30:25.359  7021  7622 V BluetoothOppNotification: inbound notification was removed.
08-30 15:30:25.359  7021  7622 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-30 15:30:25.369  7021  7622 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@288a4352 on behalf of 
08-30 15:30:25.369  7623  7623 D UEI.SmartControl: Quickset Services start...
08-30 15:30:25.371  7623  7623 I UEI.SmartControl: Manufacture = LGE
08-30 15:30:25.371  7623  7623 D UEI.SmartControl: Id = LGNevo
08-30 15:30:25.372  7623  7623 D UEI.SmartControl: File observer start...
08-30 15:30:25.374  7623  7623 E UEI.SmartControl: IR Port is disabled: false
08-30 15:30:25.374  7623  7623 D UEI.SmartControl: Starting file observer...
08-30 15:30:25.374  7623  7623 D UEI.SmartControl: Extracting JNI libs...
08-30 15:30:25.374  7623  7623 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-30 15:30:25.442  7623  7623 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-30 15:30:25.442  7623  7623 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-30 15:30:25.443  7623  7623 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-30 15:30:25.485  7623  7623 I UEI.SmartControl: --- Selecting new region: 6
,08-30 15:30:25.488  7623  7623 I UEI.SmartControl: Model = LG-D855
08-30 15:30:25.490  7623  7623 D UEI.SmartControl: QS Service created
,08-30 15:30:25.508  7623  7623 I UEI.SmartControl: Service initServices...
,08-30 15:30:25.511  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2b55c6ef type 2 when 212364 com.google.android.gms} when 212364
08-30 15:30:25.515  7623  7623 D UEI.SmartControl: QS start get config
08-30 15:30:25.519  6958  6958 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-30 15:30:25.520  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3012
08-30 15:30:25.522   311  7657 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-30 15:30:25.523  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 15:30:25.569  7623  7623 D UEI.SmartControl: Loading JNI Libs...
,08-30 15:30:25.731  1036  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 15:30:25.731  1036  1575 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@21fcb5fc mBinding = false
,08-30 15:30:25.753  1036  1118 D BluetoothManagerService: Message: 2
08-30 15:30:25.755  1036  1118 D BluetoothManagerService: Sending off request.
08-30 15:30:25.755  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:30:25.755  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:30:25.755  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 15:30:25.756  7021  7510 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-30 15:30:25.756  7021  7476 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-30 15:30:25.756  7021  7476 D BluetoothAdapterProperties: Setting state to 13
08-30 15:30:25.756  7021  7476 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 15:30:25.757  7021  7476 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 15:30:25.757  7021  7476 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 15:30:25.759  7021  7480 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:30:25.760  7021  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 15:30:25.761  7021  7596 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:25.764  7021  7595 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-30 15:30:25.764  7021  7595 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:25.764  7021  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-30 15:30:25.764  7021  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-30 15:30:25.764  7021  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-30 15:30:25.764  7021  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-30 15:30:25.764  7021  7595 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-30 15:30:25.764  7021  7595 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-30 15:30:25.764  7021  7608 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:25.765  7021  7610 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 15:30:25.765  7021  7612 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 15:30:25.766  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-30 15:30:25.766  7021  7546 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-30 15:30:25.767  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-30 15:30:25.767  7021  7546 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 15:30:25.761  7021  7476 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 15:30:25.775  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:25.775  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:25.775  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:25.775  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:25.775  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:25.775  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:25.775  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:25.775  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:25.775  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:25.776  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:25.776  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:25.778  1036  1118 D BluetoothManagerService: Message: 60
08-30 15:30:25.778  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-30 15:30:25.778  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-30 15:30:25.780  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:25.780  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:25.780  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:25.780  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:25.780  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
08-30 15:30:25.780  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 15:30:25.780  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:25.780  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:25.780  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:25.780  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:25.781  6765  6765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 15:30:25.781  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 15:30:25.786  7021  7021 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:25.786  7021  7021 D BluetoothMapService: STATE_TURNING_OFF
08-30 15:30:25.787  7021  7021 V BluetoothMapService: Handler(): got msg=4
08-30 15:30:25.787  7021  7021 D BluetoothMapService: MAP Service closeService in
08-30 15:30:25.787  7021  7021 D BluetoothMapMasInstance: MAP Service shutdown
08-30 15:30:25.787  7021  7021 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:30:25.787  7021  7021 V BluetoothMapService: MAP Service closeService out
08-30 15:30:25.788  7021  7021 V BtOppService: Receiver DISABLED_ACTION 
08-30 15:30:25.788  7021  7021 I BtOppRfcommListener: stopping Accept Thread
08-30 15:30:25.788  7021  7021 V BtOppRfcommListener: close mBtServerSocket
08-30 15:30:25.788  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:30:25.788  7021  7021 V BtOppRfcommListener: waiting for thread to terminate
08-30 15:30:25.789  7021  7608 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 15:30:25.789  7021  7021 V BtOppRfcommListener: done waiting for thread to terminate
08-30 15:30:25.791  6907  6907 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-30 15:30:25.793  6907  6907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 ,
08-30 15:30:25.793  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:25.795  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:25.798  7021  7021 V BtOppService: onDestroy
08-30 15:30:25.809  7021  7021 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-30 15:30:25.809  7021  7021 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:30:25.809  7021  7021 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:25.809  7021  7021 V BluetoothPbapReceiver: ***********state = 13
,08-30 15:30:25.811  7021  7021 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-30 15:30:25.814  7021  7021 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:25.814  7021  7021 V BluetoothPbapService: state: 13
08-30 15:30:25.814  7021  7021 V BluetoothPbapService: Pbap Service closeService in
08-30 15:30:25.818  6907  6907 D DockEventReceiver: finishStartingService: stopping service
08-30 15:30:25.820  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:30:25.821  6907  6907 D BluetoothPbap: Proxy object disconnected
08-30 15:30:25.821  6907  6907 D PbapServerProfile: Bluetooth service disconnected
08-30 15:30:25.821  7021  7021 V BluetoothPbapService: successfully stopped pbap service
08-30 15:30:25.821  7021  7021 V BluetoothPbapService: Pbap Service closeService out
08-30 15:30:25.821  7021  7021 V BluetoothPbapService: Pbap Service onDestroy
,08-30 15:30:25.821  7021  7021 V BluetoothPbapService: Pbap Service closeService in
08-30 15:30:25.821  7021  7021 V BluetoothPbapService: Pbap Service closeService out
08-30 15:30:25.821  7021  7021 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-30 15:30:25.840  6907  6907 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-30 15:30:25.845  6907  6907 D BluetoothPermissionRequest: onReceive
08-30 15:30:25.845  6907  6907 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-30 15:30:25.851  6907  6907 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 15:30:25.857  7021  7021 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-30 15:30:25.857  7021  7021 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-30 15:30:25.860  7021  7021 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-30 15:30:25.864  7021  7021 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:25.864  7021  7021 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 15:30:25.867  7021  7021 V BluetoothFtpService: Ftp Service onStartCommand
,08-30 15:30:25.867  7021  7021 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:25.868  7021  7021 V BluetoothFtpService: Ftp Service closeService
08-30 15:30:25.868  7021  7021 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-30 15:30:25.869  7021  7021 V BluetoothFtpService: successfully stopped ftp service
08-30 15:30:25.869  7021  7021 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:30:25.869  7021  7021 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:30:25.869  7021  7021 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:30:25.869  7021  7021 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:25.869  7021  7021 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-30 15:30:25.869  7021  7021 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 15:30:25.870  7021  7021 V BluetoothFtpService: Ftp Service onDestroy
08-30 15:30:25.870  7021  7021 V BluetoothFtpService: Ftp Service closeService
08-30 15:30:25.872  7021  7021 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:25.872  7021  7021 V BluetoothSapService: state: 13
08-30 15:30:25.872  7021  7021 V BluetoothSapService: Stopping SAP server process
08-30 15:30:25.872  7021  7021 V BluetoothSapService: Sap Service closeSapService in
08-30 15:30:25.872  7021  7021 V BluetoothSapService: Close listen Socket : 
08-30 15:30:25.872  7021  7021 V BluetoothSapService: Close rfcomm Socket : 
08-30 15:30:25.873  7021  7021 V BluetoothSapService: Close sapd  Socket : 
08-30 15:30:25.874  7021  7021 V BluetoothSapService: Sap Service closeSapService out
08-30 15:30:25.874  7021  7021 V BluetoothSapService: Sap Service onDestroy
08-30 15:30:25.874  7021  7021 V BluetoothSapService: Sap Service closeSapService in
08-30 15:30:25.874  7021  7021 V BluetoothSapService: Close listen Socket : 
08-30 15:30:25.874  7021  7021 V BluetoothSapService: Close rfcomm Socket : 
08-30 15:30:25.874  7021  7021 V BluetoothSapService: Close sapd  Socket : 
08-30 15:30:25.875  7021  7021 V BluetoothSapService: Sap Service closeSapService out
08-30 15:30:25.978  7623  7623 I UEI.SmartControl: Supports setup maps: true
,08-30 15:30:25.982  7623  7623 D UEI.SmartControl: QS start statue = true Error code = 0
08-30 15:30:25.982  7623  7623 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-30 15:30:25.982  7623  7623 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-30 15:30:25.982  7623  7623 I UEI.SmartControl: ### init IR Blaster...
08-30 15:30:25.988  7623  7623 D serial_port: Configuring serial port
08-30 15:30:25.994  7623  7623 E UEI.SmartControl: UEIBLaster setting for 616
08-30 15:30:25.995  7623  7623 I UEI.SmartControl: Setting serial record hearder size = 2
08-30 15:30:25.996  7623  7623 I UEI.SmartControl: configuring settings for MAXQ616
08-30 15:30:25.996  7623  7623 I UEI.SmartControl: Get version...
,08-30 15:30:26.014  7623  7679 D UEI.SmartControl: serial port data available: 21
,08-30 15:30:26.043  7623  7623 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-30 15:30:26.043  7623  7623 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-30 15:30:26.043  7623  7623 I UEI.SmartControl: QS saving settings...
08-30 15:30:26.045  7623  7623 D UEI.SmartControl: IR Blaster version: 25672567
,08-30 15:30:26.062  7623  7679 D UEI.SmartControl: serial port data available: 4
,08-30 15:30:26.105  7623  7682 I UEI.SmartControl: Device manager: loading config....
,08-30 15:30:26.107  7623  7682 D UEI.SmartControl: ----------- loading internal config...
,08-30 15:30:26.112  7623  7623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-30 15:30:26.115  7623  7623 E UEI.SmartControl: Services init done
08-30 15:30:26.116  7623  7623 D UEI.SmartControl: QS Service init finished
08-30 15:30:26.120  7623  7623 D UEI.SmartControl: QS Service version name: 2.1.91
08-30 15:30:26.120  7623  7623 D UEI.SmartControl: QS Service version code: 201091
,08-30 15:30:26.121  7623  7623 D UEI.SmartControl: Service requested: Control
08-30 15:30:26.125  7623  7682 E UEI.SmartControl: Loading SETTINGS...
08-30 15:30:26.127  7623  7623 D UEI.SmartControl: Request IControl service: devices are loaded...
08-30 15:30:26.131  6958  6958 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-30 15:30:26.132  1036  1914 I ActivityManager: Killing 6927:com.lge.sync/1000 (adj 15): empty #17
08-30 15:30:26.132  7623  7638 I UEI.SmartControl: ------ IControl API: 11
08-30 15:30:26.134  7623  7638 I UEI.SmartControl: Registering callback...
,08-30 15:30:26.136  7623  7639 I UEI.SmartControl: ------ IControl API: 19
08-30 15:30:26.138  7623  7639 I UEI.SmartControl: Registering Services Ready callback...
08-30 15:30:26.146  7623  7682 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-30 15:30:26.160  7623  7681 I UEI.SmartControl: Notify AllClients services are ready: 0
08-30 15:30:26.160  6958  6974 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-30 15:30:26.161  6958  7051 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-30 15:30:26.161  6958  7051 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-30 15:30:26.161  7623  7681 D UEI.SmartControl: -----service ready thread exits
08-30 15:30:26.161  6958  6958 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,08-30 15:30:26.162  6958  6958 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-30 15:30:26.162  7623  7638 I UEI.SmartControl: ------ IControl API: 8
08-30 15:30:26.163  6958  6958 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-30 15:30:26.164  6958  6958 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-30 15:30:26.164  6958  6958 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,08-30 15:30:26.165  6958  6958 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-30 15:30:26.166  6958  6958 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-30 15:30:26.166  6958  6958 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-30 15:30:26.169  1036  1423 D WifiService: Client connection lost with reason: 4
08-30 15:30:26.201  7623  7623 D UEI.SmartControl: Internal service binding...
08-30 15:30:26.202  1036  1051 W libprocessgroup: failed to open /acct/uid_1000/pid_6927/cgroup.procs: No such file or directory
08-30 15:30:26.203  6958  6958 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-30 15:30:26.217  6958  6958 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-30 15:30:26.219  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-30 15:30:26.223  6958  6958 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 15:30:26.223  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-30 15:30:26.226  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-30 15:30:26.229  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-30 15:30:26.230  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-30 15:30:26.231  6958  6958 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472563826230]
,08-30 15:30:26.258  6958  7684 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-30 15:30:26.271  6958  6958 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-30 15:30:26.274  6958  6958 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-30 15:30:26.275  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-30 15:30:26.275  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-30 15:30:26.276  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-30 15:30:26.277  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-30 15:30:26.278  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-30 15:30:26.282  6958  6958 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-30 15:30:26.748  7021  7480 D bt_hci_bdroid: cleanup
,08-30 15:30:26.754  7021  7548 I bt_lpm  : LPM is already off!!!
08-30 15:30:26.755  7021  7572 I bt_userial_mct: exiting userial_read_thread
08-30 15:30:26.756  7021  7546 W bt-btif : ag scb idx 1 not allocated
08-30 15:30:26.756  7021  7546 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 15:30:26.756  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 15:30:26.757  7021  7546 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-30 15:30:26.758  7021  7546 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 15:30:26.758  7021  7546 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-30 15:30:26.755  7021  7572 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 15:30:26.761  7021  7480 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 15:30:26.761  7021  7548 I bt_vendor: hw_epilog_process
08-30 15:30:26.762  7021  7480 D bt_hci_bdroid: cleanup Finalizing cleanup
08-30 15:30:26.762  7021  7480 D bt_userial_mct: userial_close
08-30 15:30:26.762  7021  7480 E bt_userial_mct: pthread_join() FAILED result:3
08-30 15:30:26.762  7021  7480 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 15:30:26.770  7021  7480 D bt_hci_bdroid: set_power 0
08-30 15:30:26.770  7021  7480 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 15:30:26.770  7021  7480 I bt_vendor: bluetooth satus is on
,08-30 15:30:26.770  7021  7480 I bt_vendor: bt-vendor : resetting BT status
08-30 15:30:26.770  7021  7480 I bt_vendor: Starting hciattach daemon
08-30 15:30:26.770  7021  7480 I bt_vendor: try to set false
,08-30 15:30:26.777  7021  7480 I bt_vendor: Starting hciattach daemon
08-30 15:30:26.777  7021  7480 I bt_vendor: try to set false
08-30 15:30:26.779  7021  7480 I bt_vendor: cleanup
08-30 15:30:26.780  7021  7546 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 15:30:26.781  7021  7480 I GKI_LINUX: GKI_exit_task 0 done
08-30 15:30:26.781  7021  7480 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated,
08-30 15:30:26.782  7021  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 15:30:26.787  7021  7021 D HeadsetService: Received stop request...Stopping profile...
,08-30 15:30:26.792  7021  7021 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 15:30:26.792  7021  7021 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:30:26.792  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:26.794  7021  7499 D HeadsetStateMachine: Exit Disconnected: -1
08-30 15:30:26.798  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-30 15:30:26.798  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-30 15:30:26.798  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-30 15:30:26.800  1036  1036 D BluetoothHeadset: Proxy object disconnected
08-30 15:30:26.800  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 15:30:26.804  7021  7476 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 15:30:26.805  7021  7021 D A2dpService: Received stop request...Stopping profile...
08-30 15:30:26.806  7021  7538 D A2dpStateMachine: Exit Disconnected: -1
08-30 15:30:26.807  7021  7021 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-30 15:30:26.809  7021  7021 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-30 15:30:26.809  7021  7021 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:30:26.809  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:26.810  1036  1036 D BluetoothA2dp: Proxy object disconnected
08-30 15:30:26.810  1036  1036 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 15:30:26.811  7021  7021 D HidService: Received stop request...Stopping profile...
08-30 15:30:26.811  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:26.813  7021  7021 D HealthService: Received stop request...Stopping profile...
08-30 15:30:26.813  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
,08-30 15:30:26.817  7021  7021 D HeadsetStateMachine: Unbinding service...
08-30 15:30:26.820  7021  7021 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:30:26.820  7021  7021 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:30:26.820  7021  7021 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:30:26.820  7021  7021 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:30:26.820  7021  7021 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 15:30:26.820  7021  7021 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 15:30:26.820  7021  7021 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-30 15:30:26.822  7021  7021 D PanService: Received stop request...Stopping profile...
08-30 15:30:26.822  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:26.824  7021  7021 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:30:26.825  7021  7021 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 15:30:26.825  7021  7021 D BtGatt.GattService: stop()
08-30 15:30:26.825  7021  7021 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 15:30:26.828  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:26.831  7021  7021 D BluetoothMapService: Received stop request...Stopping profile...
08-30 15:30:26.831  7021  7021 D BluetoothMapService: stop()
08-30 15:30:26.833  7021  7021 D BluetoothMapEmailAppObserver: deinitObservers()
08-30 15:30:26.833  7021  7021 D BluetoothMapEmailAppObserver: removeReceiver()
08-30 15:30:26.834  7021  7021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bdcecc7
08-30 15:30:26.835  7021  7021 V BluetoothMapService: Handler(): got msg=4
08-30 15:30:26.835  7021  7021 D BluetoothMapService: MAP Service closeService in
08-30 15:30:26.835  7021  7021 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:30:26.835  7021  7021 V BluetoothMapService: MAP Service closeService out
08-30 15:30:26.835  7021  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-30 15:30:26.835  7021  7476 D BluetoothAdapterProperties: Setting state to 10
08-30 15:30:26.835  7021  7476 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 15:30:26.836  1036  1118 D BluetoothManagerService: Message: 60
08-30 15:30:26.836  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-30 15:30:26.836  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-30 15:30:26.837  7021  7476 I BluetoothAdapterState: Entering OffState
,08-30 15:30:26.840  6907  6922 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 15:30:26.841  6907  6922 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 15:30:26.841  6907  6922 D BluetoothPan: onBluetoothStateChange on: false
08-30 15:30:26.842  6907  6922 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 15:30:26.843  7021  7021 I BluetoothA2dpServiceJni: cleanupNative
08-30 15:30:26.844  7021  7539 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 15:30:26.845  7021  7021 I GKI_LINUX: GKI_exit_task 2 done
08-30 15:30:26.845  7021  7021 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 15:30:26.848  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:30:26.848  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 15:30:26.851  6907  6922 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:30:26.852  1853  4020 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:30:26.853  1853  2613 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:30:26.853  1853  4023 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 15:30:26.854  7021  7021 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 15:30:26.854  7021  7021 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 15:30:26.855  6907  6922 D BluetoothMap: onBluetoothStateChange: up=false
08-30 15:30:26.856  7021  7021 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 15:30:26.857  7021  7021 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:30:26.857  7021  7021 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 15:30:26.858  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-30 15:30:26.858  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-30 15:30:26.859  7021  7021 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 15:30:26.859  7021  7021 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 15:30:26.863  7021  7021 D BluetoothMapService: cleanup()
08-30 15:30:26.863  7021  7021 D BluetoothMapService: MAP Service closeService in
08-30 15:30:26.863  7021  7021 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-30 15:30:26.863  7021  7021 V BluetoothMapService: MAP Service closeService out
,08-30 15:30:26.866  1036  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-30 15:30:26.866  1036  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-30 15:30:26.866  1036  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@21fcb5fc mBinding = false
08-30 15:30:26.868  1036  1118 D BluetoothManagerService: Sending unbind request.
08-30 15:30:26.872  7021  7480 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 15:30:26.873  7021  7021 I GKI_LINUX: GKI_exit_task 1 done
08-30 15:30:26.873  7021  7021 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 15:30:26.873  7021  7021 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 15:30:26.873  7021  7021 I art     : --- WEIRD: removing null entry 248
08-30 15:30:26.873  7021  7021 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-30 15:30:26.873  7021  7021 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-30 15:30:26.874  7021  7021 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-30 15:30:26.878  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-30 15:30:26.881  7021  7021 I art     : System.exit called, status: 0
08-30 15:30:26.881  7021  7021 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 15:30:26.900   316  1402 V AudioFlinger: 7021 died, releasing its sessions
08-30 15:30:26.900   316  1402 V AudioFlinger:  pid 1853 @ 0
08-30 15:30:26.900   316  1402 V AudioFlinger:  pid 3456 @ 1
08-30 15:30:26.900   316  1402 V AudioFlinger:  pid 3456 @ 2
,08-30 15:30:26.903  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-30 15:30:26.903  1942  2124 D LGBluetoothAPIService: Message: 101
08-30 15:30:26.904  1942  2124 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-30 15:30:26.904  1942  2124 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-30 15:30:26.904  1942  2124 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-30 15:30:26.905  6907  6907 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-30 15:30:26.909  1036  1914 I ActivityManager: Process com.android.bluetooth (pid 7021) has died
08-30 15:30:26.910  1036  1914 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-30 15:30:26.910  1036  1914 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-30 15:30:26.915  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:30:26.918  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:30:26.919  1942  2124 D LGBluetoothAPIService: Message: 2
08-30 15:30:26.919  1942  2124 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-30 15:30:26.920  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:26.920  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:26.925  6907  6907 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-30 15:30:26.925  6907  6907 D LGBluetoothEventManager: [BTUI] clear device connection state
08-30 15:30:26.929  6907  6907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 15:30:26.944  1602  1602 D BluetoothAdapter: 92743774: getState() :  mService = null. Returning STATE_OFF
08-30 15:30:26.944  1602  1602 D BluetoothAdapter: 92743774: getState() :  mService = null. Returning STATE_OFF
,08-30 15:30:26.974  1036  1941 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7697 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-30 15:30:26.981  6907  6907 D DockEventReceiver: finishStartingService: stopping service
,08-30 15:30:27.026  7697  7697 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 15:30:27.027  7697  7697 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:30:27.027  7697  7697 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-30 15:30:27.027  7697  7697 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 15:30:27.044  7697  7697 D BluetoothAdapterApp: Loading JNI Library
,08-30 15:30:27.077  7697  7697 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@349b72cf Instance Count = 1
,08-30 15:30:27.085  7697  7697 D BluetoothAdapterApp: onCreate
08-30 15:30:27.111  7697  7697 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-30 15:30:27.111  7697  7697 D ProfileConfigQcom: Adding HeadsetService
08-30 15:30:27.112  7697  7697 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-30 15:30:27.112  7697  7697 D ProfileConfigQcom: Adding A2dpService
08-30 15:30:27.112  7697  7697 D ProfileConfigQcom: [BTUI] HidService is supported
08-30 15:30:27.112  7697  7697 D ProfileConfigQcom: Adding HidService
08-30 15:30:27.113  7697  7697 D ProfileConfigQcom: [BTUI] HealthService is supported
08-30 15:30:27.113  7697  7697 D ProfileConfigQcom: Adding HealthService
08-30 15:30:27.113  7697  7697 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-30 15:30:27.114  7697  7697 D ProfileConfigQcom: [BTUI] PanService is supported
08-30 15:30:27.115  7697  7697 D ProfileConfigQcom: Adding PanService
,08-30 15:30:27.116  7697  7697 D ProfileConfigQcom: [BTUI] GattService is supported
08-30 15:30:27.116  7697  7697 D ProfileConfigQcom: Adding GattService
08-30 15:30:27.117  7697  7697 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-30 15:30:27.117  7697  7697 D ProfileConfigQcom: Adding BluetoothMapService
08-30 15:30:27.118  7697  7697 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-30 15:30:27.122  7697  7697 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:30:27.123  7697  7697 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:27.123  7697  7697 V BluetoothPbapReceiver: ***********state = 10
08-30 15:30:27.125  7697  7697 V LGMDMManagerInternal: Create singleton instance
08-30 15:30:27.219  7697  7697 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-30 15:30:27.220  7697  7697 D LGBluetoothAPIServer: [BTUI] onBind()
08-30 15:30:27.222  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:30:27.235  1942  1942 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-30 15:30:27.236  1942  2124 D LGBluetoothAPIService: Message: 100
08-30 15:30:27.236  1942  2124 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-30 15:30:27.244  6907  6907 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-30 15:30:27.249  6907  6907 D BluetoothPermissionRequest: onReceive
08-30 15:30:27.252  6907  6907 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-30 15:30:27.252  6907  6907 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-30 15:30:27.256  6907  6907 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:30:27.263  7697  7697 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-30 15:30:27.270  7697  7697 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-30 15:30:27.278  7697  7697 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-30 15:30:27.279  7697  7697 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:30:27.280  7697  7697 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:30:27.283  7697  7697 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:27.283  7697  7697 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-30 15:30:27.286  6975  6975 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-30 15:30:28.755  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 15:30:28.755  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:30:28.885  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-30 15:30:28.898  1036  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 15:30:28.962  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 15:30:29.014  1036  1111 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7741 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 15:30:29.030  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-30 15:30:29.034  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-30 15:30:29.057  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:30:29.065  1036  1036 D administrator: Handling package changes for user 0
08-30 15:30:29.079  7741  7741 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 15:30:29.157  7741  7741 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:29.157  7741  7741 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:29.178  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-30 15:30:29.178  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-30 15:30:29.242  1036  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 15:30:29.250  1036  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 15:30:29.257  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 15:30:29.258  2507  2507 V GmsNetworkLocationProvi: DISABLE
08-30 15:30:29.260  7741  7785 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 15:30:29.260  7741  7785 I Babel   : MmsConfig.loadMmsSettings
08-30 15:30:29.278  7741  7785 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 15:30:29.278  7741  7785 I Babel   : MmsConfig.loadFromDatabase
,08-30 15:30:29.295  7741  7785 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-30 15:30:29.295  7741  7785 I Babel   : MmsConfig.loadFromResources
08-30 15:30:29.297  7741  7785 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-30 15:30:29.298  7741  7785 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-30 15:30:29.307  2507  2507 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-30 15:30:29.307  7741  7741 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:30:29.311  1036  1109 D LocationProviderProxy: applying state to connected service
08-30 15:30:29.331  7741  7784 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 15:30:29.333  7741  7784 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 15:30:29.334  7741  7784 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-30 15:30:29.340  7741  7784 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-30 15:30:29.341  7741  7784 W AudioCapabilities: Unsupported mime audio/qcelp
08-30 15:30:29.342  7741  7784 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 15:30:29.345  1817  7788 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-30 15:30:29.345  1817  7788 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-30 15:30:29.350  7087  7087 I AppUp4:CustModeStarterReceiver: onReceive
08-30 15:30:29.354  7087  7087 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@83a20e1
08-30 15:30:29.354  7087  7087 D AppUp4:CustFacade: isCustomizationCompleted : false
,08-30 15:30:29.354  7087  7087 D AppUp4:CustFacade: isPhone : true
08-30 15:30:29.354  7087  7087 D AppUp4:CustModeStarterReceiver: begin check event
08-30 15:30:29.354  7087  7087 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-30 15:30:29.358  1817  4793 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-30 15:30:29.359  7741  7784 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-30 15:30:29.360  7741  7784 W VideoCapabilities: Unsupported mime video/divx
08-30 15:30:29.361  7741  7784 W VideoCapabilities: Unsupported mime video/divx311
08-30 15:30:29.363  7741  7784 W VideoCapabilities: Unsupported mime video/divx4
08-30 15:30:29.366  7741  7784 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 15:30:29.385  1036  1936 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7792 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-30 15:30:29.393  1036  1941 I ActivityManager: Killing 7120:com.lge.email/u0a23 (adj 15): empty #17
,08-30 15:30:29.412  7741  7784 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 15:30:29.415  7741  7784 W AudioCapabilities: Unsupported mime audio/eac3
,08-30 15:30:29.416  7741  7784 W AudioCapabilities: Unsupported mime audio/ac3
,08-30 15:30:29.417  7741  7784 W AudioCapabilities: Unsupported mime audio/g726
08-30 15:30:29.418  7741  7784 W AudioCapabilities: Unsupported mime audio/wma-voice
08-30 15:30:29.419  7741  7784 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-30 15:30:29.420  7741  7784 W AudioCapabilities: Unsupported mime audio/adpcm
08-30 15:30:29.421  7741  7784 W VideoCapabilities: Unsupported mime video/theora
08-30 15:30:29.423  7741  7784 W VideoCapabilities: Unsupported mime video/mjpg
08-30 15:30:29.481  1036  1960 W libprocessgroup: failed to open /acct/uid_10023/pid_7120/cgroup.procs: No such file or directory
,08-30 15:30:29.523  7792  7792 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:30:29.524  7792  7792 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:30:29.525  7792  7792 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-30 15:30:29.528  7792  7792 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-30 15:30:29.529  7792  7792 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-30 15:30:29.618  7792  7792 I SystemConfig: BUILD Country: EU
08-30 15:30:29.618  7792  7792 I SystemConfig: BUILD Operator: OPEN
,08-30 15:30:29.682  1036  1998 I ActivityManager: Killing 7003:com.lge.formmanager/u0a26 (adj 15): empty #17,
,08-30 15:30:29.882  1036  1998 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7815 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-30 15:30:29.887  1036  2033 W libprocessgroup: failed to open /acct/uid_10026/pid_7003/cgroup.procs: No such file or directory
,08-30 15:30:29.905   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 479us total 23.200ms
,08-30 15:30:29.908  7792  7813 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-30 15:30:29.908  7792  7813 I SystemConfig: existFile = false
08-30 15:30:29.908  7792  7813 I SystemConfig: canReadFile = false
08-30 15:30:29.908  7792  7813 I SystemConfig: systemFeature RCS result false
08-30 15:30:29.909  7792  7813 D SystemConfig: refreshRcsSupport() :false
08-30 15:30:29.927   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 433us total 20.743ms
,08-30 15:30:29.948   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 20.318ms
,08-30 15:30:29.956  7815  7815 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:30:29.956  7815  7815 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 15:30:29.956  7815  7815 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 15:30:29.957  7815  7815 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 15:30:30.058  7815  7815 I AppConfig: Total System Memory = 2995761152
,08-30 15:30:30.068  7815  7815 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-30 15:30:30.168  1036  1652 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7834 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 15:30:30.170  1036  1652 I ActivityManager: Killing 6455:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-30 15:30:30.234  1036  2017 W libprocessgroup: failed to open /acct/uid_1000/pid_6455/cgroup.procs: No such file or directory
,08-30 15:30:30.242  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2a24ee87 type 2 when 217095 com.google.android.gms} when 217095
08-30 15:30:30.418  7834  7834 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 15:30:30.510  7834  7834 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:30.510  7834  7834 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:30.564  7834  7834 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 15:30:30.585  7834  7834 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 15:30:30.587  7834  7834 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 15:30:30.610  7834  7834 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 15:30:30.611  7834  7834 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 15:30:30.649  1036  1652 I ActivityManager: Killing 7159:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-30 15:30:30.731  1036  2033 W libprocessgroup: failed to open /acct/uid_10046/pid_7159/cgroup.procs: No such file or directory
,08-30 15:30:30.742  3528  3543 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-30 15:30:30.744  4628  7874 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-30 15:30:30.745  3528  3543 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2d584cb5 on behalf of 7834
08-30 15:30:30.794  1036  1781 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7875 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 15:30:30.842  7834  7834 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 15:30:30.868  7834  7834 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-30 15:30:30.898  7875  7875 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-30 15:30:30.919  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-30 15:30:30.919  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-30 15:30:30.919  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-30 15:30:30.919  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-30 15:30:30.919  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-30 15:30:30.919  7875  7875 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-30 15:30:30.934   311  7909 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-30 15:30:30.934  1036  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-30 15:30:30.939  1036  1781 I ActivityManager: Killing 7179:com.android.chrome/u0a57 (adj 15): empty #17
08-30 15:30:30.972  1036  1652 W libprocessgroup: failed to open /acct/uid_10057/pid_7179/cgroup.procs: No such file or directory
,08-30 15:30:31.104  7623  7683 D UEI.SmartControl: Internal timer expired: 1
08-30 15:30:31.105  7623  7683 D UEI.SmartControl: unbind internal service
,08-30 15:30:31.173  1036  1959 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:30:31.205  4628  7874 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 461 ms] updated apps [took 461 ms] 
,08-30 15:30:31.314  7623  7680 D serial_port: close(fd = 25)
,08-30 15:30:31.324  7623  7680 I UEI.SmartControl: Serial port is closed.
,08-30 15:30:31.772  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:31.772  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2eeba0cb added. We now have 6 listener(s)
08-30 15:30:31.772  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:30:31.783  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:31.783  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d5380a8 added. We now have 7 listener(s)
08-30 15:30:31.783  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:31.784  6765  6830 I System.out: IsBluetoothEnabled
08-30 15:30:31.785  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:31.785  1036  1051 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-30 15:30:31.786  1036  1118 D BluetoothManagerService: Message: 2
08-30 15:30:31.789  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:31.792  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:31.792  1036  1978 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-30 15:30:31.817  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 15:30:31.817  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-30 15:30:31.818  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 15:30:31.818  1036  1118 D BluetoothManagerService: Message: 1
08-30 15:30:31.818  1036  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-30 15:30:31.843  1036  1118 D BluetoothManagerService: Message: 20
08-30 15:30:31.843  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b439f68:true
,08-30 15:30:31.847  7697  7697 D BluetoothAdapterState: make
08-30 15:30:31.852  7697  7697 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-30 15:30:31.852  7697  7697 I bluedroid-qcom: init
08-30 15:30:31.854  7697  7922 I BluetoothAdapterState: Entering OffState
08-30 15:30:31.854  7697  7697 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-30 15:30:31.854  7697  7697 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 15:30:31.854  7697  7697 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 15:30:31.854  7697  7697 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 15:30:31.854  7697  7697 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-30 15:30:31.856  7697  7697 I bluedroid-qcom: get_profile_interface socket
08-30 15:30:31.856  7697  7697 I bluedroid-qcom: get_profile_interface map_client
,08-30 15:30:31.861  7697  7926 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 15:30:31.863  7697  7926 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-30 15:30:31.852  7925  7925 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:31.852  7925  7925 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:31.872  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-30 15:30:31.873  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 15:30:31.879  7697  7926 D BluetoothAdapterProperties: Name is: G3
08-30 15:30:31.880  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-30 15:30:31.881  1036  1118 D BluetoothManagerService: Message: 40
08-30 15:30:31.881  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-30 15:30:31.881  7697  7712 I bluedroid-qcom: config_hci_snoop_log
08-30 15:30:31.883  1036  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-30 15:30:31.883  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-30 15:30:31.883  7925  7925 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-30 15:30:31.883  7925  7925 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-30 15:30:31.883  7925  7925 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-30 15:30:31.886  7925  7925 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-30 15:30:31.894  7925  7925 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-30 15:30:31.894  7925  7925 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-30 15:30:31.896  7697  7922 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-30 15:30:31.897  7697  7922 D BluetoothAdapterProperties: Setting state to 11
08-30 15:30:31.897  7697  7922 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 15:30:31.898  7697  7922 I LGBluetoothServiceJni: classInitNative: succeeds
08-30 15:30:31.900  1036  1118 D BluetoothManagerService: Message: 60
08-30 15:30:31.900  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-30 15:30:31.900  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-30 15:30:31.906  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:31.906  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:30:31.909  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:31.912  6907  6907 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-30 15:30:31.918  7697  7697 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:30:31.918  7697  7697 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:31.918  7697  7697 V BluetoothPbapReceiver: ***********state = 11
,08-30 15:30:31.932  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 15:30:31.935  7697  7922 D BluetoothBondStateMachine: make
08-30 15:30:31.938  7697  7922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:31.938  7697  7940 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 15:30:31.938  7697  7922 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-30 15:30:31.938  7697  7922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:31.938  7697  7922 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-30 15:30:31.939  7697  7922 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-30 15:30:31.943  7697  7922 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:30:31.949  7697  7922 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:30:31.952  7697  7697 D HeadsetService: Received start request. Starting profile...
08-30 15:30:31.953  7697  7697 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:30:31.953  7697  7697 D LGBluetoothHfpAdapter: Version 1.6
08-30 15:30:31.955  6907  6907 D BluetoothPermissionRequest: onReceive
08-30 15:30:31.956  7697  7697 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 15:30:31.957  7697  7697 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 15:30:31.958  7697  7697 D HeadsetStateMachine: make
08-30 15:30:31.959  6907  6907 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-30 15:30:31.964  7697  7922 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:30:31.972  7697  7922 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:30:31.977  7697  7922 E BluetoothAdapterService: File transfer profiles supported!!
,08-30 15:30:31.982  7697  7922 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:30:31.986  7697  7922 E BluetoothAdapterService: File transfer profiles supported!!
08-30 15:30:31.995  7697  7697 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:31.995  7697  7697 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:32.000  7697  7697 D HeadsetStateMachine: max_hf_connections = 1
08-30 15:30:32.000  7697  7697 I bluedroid-qcom: get_profile_interface handsfree
08-30 15:30:32.002  7697  7922 V LGMDMManager: Create singleton instance
08-30 15:30:32.002  7697  7697 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-30 15:30:32.003   316  1782 V AudioPolicyService: registerClient() client 0xb04049a0, uid 1002
08-30 15:30:32.003   316  1402 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-30 15:30:32.003   316  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:30:32.003   316  1402 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:30:32.003  7697  7697 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-30 15:30:32.003  7697  7922 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-30 15:30:32.003   316  1403 V AudioFlinger: registerClient() client 0xb55815b0, pid 7697
08-30 15:30:32.004   316  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:32.004   316  1395 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:32.004   316  1398 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:32.004   316  1398 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:32.004  7697  7697 V ToneGenerator: Create Track: 0xb4928080
08-30 15:30:32.004  7697  7697 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-30 15:30:32.004  7697  7697 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-30 15:30:32.004   316  1402 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 15:30:32.004   316  1402 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-30 15:30:32.004   316  1402 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:30:32.004   316  1402 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:30:32.005  7697  7697 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-30 15:30:32.005  1036  1936 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:32.005  1036  1936 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:32.005  1036  1936 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:32.005  1602  2098 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:32.005  1036  1936 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:32.005  1602  2098 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:32.005  1602  2098 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:32.005  1602  2098 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:32.005   316   316 I AudioFlinger: isAudioPlaybackHookOn() false
08-30 15:30:32.005  7697  7713 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:32.005  7697  7713 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-30 15:30:32.005  7697  7713 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:32.005  7697  7713 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-30 15:30:32.005   316  1782 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-30 15:30:32.005   316  1782 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-30 15:30:32.005   316  1782 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-30 15:30:32.005   316  1782 V AudioPolicyManagerEx: getOutput() returns output 2
08-30 15:30:32.005  7697  7697 V AudioSystem: getLatency() output 2, latency 50
08-30 15:30:32.005  7697  7697 V AudioSystem: getFrameCount() output 2, frameCount 960
08-30 15:30:32.005  7697  7697 V AudioTrack: createTrack_l() output 2 afLatency 50
08-30 15:30:32.006   316  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 15:30:32.006   316  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 15:30:32.006   316  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-30 15:30:32.006   316  1402 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-30 15:30:32.006   316  1402 V AudioFlinger: createTrack() lSessionId: 21
08-30 15:30:32.006  3456  3472 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:32.006  3456  3472 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:32.006  3456  3472 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:32.006  3456  3472 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:32.006  1853  2613 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-30 15:30:32.006  1853  2613 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-30 15:30:32.006  1853  2613 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-30 15:30:32.006  1853  2613 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-30 15:30:32.007  7697  7697 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-30 15:30:32.007   316  1403 V AudioFlinger: acquiring 21 from 7697, for 7697
08-30 15:30:32.007   316  1403 V AudioFlinger:  added new entry for 21
08-30 15:30:32.007  7697  7697 V ToneGenerator: ToneGenerator INIT OK, time: 218877
08-30 15:30:32.007  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:32.008  7697  7942 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-30 15:30:32.008  7697  7942 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-30 15:30:32.008  7697  7942 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-30 15:30:32.009  7697  7942 D HeadsetStateMachine: [BTUI] change sampling ra,te to 8000 when device is disconnected
08-30 15:30:32.009  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:32.009   316   316 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7697
08-30 15:30:32.009   316   316 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-30 15:30:32.009   316   316 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-30 15:30:32.009   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-30 15:30:32.009   316   316 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 15:30:32.009   316   316 V voice   : voice_set_parameters: exit with code(0)
08-30 15:30:32.009   316   316 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-30 15:30:32.010   316   316 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-30 15:30:32.010   316   316 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 15:30:32.010   316   316 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 15:30:32.010   316   316 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 15:30:32.010   316   316 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-30 15:30:32.010  7697  7942 V ToneGenerator: ToneGenerator destructor
08-30 15:30:32.010  7697  7942 V ToneGenerator: stopTone
08-30 15:30:32.010  7697  7942 V ToneGenerator: Delete Track: 0xb4928080
08-30 15:30:32.011  7697  7697 D A2dpService: Received start request. Starting profile...
08-30 15:30:32.011   316  1782 V AudioPolicyService: AudioCommandThread() adding release output 2
08-30 15:30:32.011   316  1782 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-30 15:30:32.011   316  1275 V AudioPolicyService: AudioCommandThread() waking up
08-30 15:30:32.011   316  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-30 15:30:32.011   316  1275 V AudioPolicyManager: releaseOutput() 2
08-30 15:30:32.011   316  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 15:30:32.011   316  1782 V AudioFlinger: PlaybackThread::Track destructor
08-30 15:30:32.011  7697  7697 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 15:30:32.011   316  1782 V AudioFlinger: removeClient_l() pid 7697, calling pid 316
08-30 15:30:32.011  7697  7942 V AudioTrack: ~AudioTrack, releasing session id from 7697 on behalf of 7697
08-30 15:30:32.011   316   316 V AudioFlinger: releasing 21 from 7697 for 7697
08-30 15:30:32.011   316   316 V AudioFlinger:  decremented refcount to 0
08-30 15:30:32.012   316   316 V AudioFlinger: purging stale effects
08-30 15:30:32.012  7697  7697 V Avrcp   : make
08-30 15:30:32.013  7697  7697 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-30 15:30:32.013  7697  7697 I bluedroid-qcom: get_profile_interface avrcp
08-30 15:30:32.015  1036  2033 W Process : Unable to open /proc/7945/status
,08-30 15:30:32.025  7697  7697 V AudioManager: registerRemoteController: size of Media player list: 0
,08-30 15:30:32.027  7697  7697 E AudioManager: No RCC entry present to update
08-30 15:30:32.027  7697  7697 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 15:30:32.031  7697  7697 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-30 15:30:32.033  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-30 15:30:32.033  7697  7697 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-30 15:30:32.036  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 15:30:32.133  1036  2051 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:30:32.133  1036  2051 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:30:32.265  1036  2033 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-30 15:30:32.289  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-30 15:30:32.296  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 15:30:32.297  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 15:30:32.297  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 15:30:32.297  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 15:30:32.297  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:30:32.297  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 15:30:32.297  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 15:30:32.298  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 15:30:32.298  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:30:32.298  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 15:30:32.298  7697  7697 I BluetoothA2dpServiceJni: classInitNative
08-30 15:30:32.299  7697  7697 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:30:32.299  7697  7697 D A2dpStateMachine: make
08-30 15:30:32.302  7697  7697 I bluedroid-qcom: get_profile_interface a2dp
08-30 15:30:32.302  7697  7953 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 15:30:32.307  7697  7697 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-30 15:30:32.307  7697  7697 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-30 15:30:32.308  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:32.310  7697  7697 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 15:30:32.312  7697  7952 D A2dpStateMachine: Enter Disconnected: -2
08-30 15:30:32.313  7697  7697 D HidService: Received start request. Starting profile...
08-30 15:30:32.313  7697  7697 I bluedroid-qcom: get_profile_interface hidhost
08-30 15:30:32.313  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:32.314  7697  7697 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:30:32.316  7697  7697 D HealthService: Received start request. Starting profile...
08-30 15:30:32.320  7697  7697 I bluedroid-qcom: get_profile_interface health
,08-30 15:30:32.321  7697  7697 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-30 15:30:32.321  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:32.323  7697  7697 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 15:30:32.328  7697  7697 D PanService: Received start request. Starting profile...
08-30 15:30:32.328  7697  7697 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 15:30:32.328  7697  7697 I bluedroid-qcom: get_profile_interface pan
08-30 15:30:32.342  7697  7697 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-30 15:30:32.343  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:32.346  7697  7697 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-30 15:30:32.352  7697  7697 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 15:30:32.354  7697  7697 D BtGatt.GattService: Received start request. Starting profile...
08-30 15:30:32.354  7697  7697 D BtGatt.GattService: start()
08-30 15:30:32.354  7697  7697 I bluedroid-qcom: get_profile_interface gatt
08-30 15:30:32.355  7697  7697 D BtGatt.AdvertiseManager: advertise manager created
,08-30 15:30:32.364  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:32.367  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:32.368  7697  7697 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-30 15:30:32.369  7697  7697 V BluetoothMapService: BluetoothMapBinder()
,08-30 15:30:32.370  7697  7697 D BluetoothMapService: Received start request. Starting profile...
08-30 15:30:32.370  7697  7697 D BluetoothMapService: start()
08-30 15:30:32.376  7697  7697 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-30 15:30:32.376  7697  7697 D BluetoothMapEmailAppObserver: createReceiver()
08-30 15:30:32.378  7697  7697 D BluetoothMapEmailAppObserver: initObservers()
08-30 15:30:32.378  7697  7697 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-30 15:30:32.393  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
,08-30 15:30:32.394  7697  7697 D HeadsetStateMachine: Proxy object connected
08-30 15:30:32.395  7697  7697 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-30 15:30:32.395  7697  7697 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-30 15:30:32.397  7697  7942 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 15:30:32.398  7697  7942 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 15:30:32.398  7697  7942 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-30 15:30:32.403  7697  7697 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:30:32.406  7697  7697 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-30 15:30:32.411  7697  7697 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:30:32.413  7697  7697 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:32.418  7697  7697 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:30:32.419  7697  7697 V PanService: [BTUI] SIM Extra State :ABSENT
,08-30 15:30:32.422  7697  7697 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-30 15:30:32.425  7697  7697 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-30 15:30:32.425  7697  7697 V BluetoothMapService: Handler(): got msg=1
08-30 15:30:32.426  7697  7697 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:30:32.426  7697  7697 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:30:32.427  7697  7697 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:30:32.427  7697  7697 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:32.427  7697  7922 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-30 15:30:32.427  7697  7697 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-30 15:30:32.427  7697  7922 I bluedroid-qcom: enable
08-30 15:30:32.427  7697  7961 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-30 15:30:32.429  7697  7961 I bt-btu  : btu_task pending for preload complete event
08-30 15:30:32.430  7697  7922 I bt_hci_bdroid: init
08-30 15:30:32.431  7697  7922 I bt_vendor: bt-vendor : init
08-30 15:30:32.431  7697  7922 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 15:30:32.431  7697  7922 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 15:30:32.431  7697  7922 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-30 15:30:32.431  7697  7922 D bt_userial_mct: userial_init
08-30 15:30:32.431  7697  7922 D bt_hci_bdroid: set_power 1
08-30 15:30:32.431  7697  7922 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-30 15:30:32.431  7697  7922 I bt_vendor: Starting hciattach daemon
08-30 15:30:32.431  7697  7922 I bt_vendor: try to set true
08-30 15:30:32.422  7964  7964 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:30:32.422  7964  7964 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:32.466  7965  7965 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-30 15:30:32.590  7971  7971 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-30 15:30:32.604  7972  7972 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 15:30:32.634  7974  7974 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 15:30:32.647  7975  7975 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-30 15:30:32.660  7976  7976 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 15:30:32.672  7977  7977 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-30 15:30:32.698  7979  7979 I libmdmdetect: ESOC framework not supported
08-30 15:30:32.700  7979  7979 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-30 15:30:32.711  7979  7979 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-30 15:30:32.711  7979  7979 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-30 15:30:32.711  7979  7979 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-30 15:30:32.711  7979  7979 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-30 15:30:32.711  7979  7979 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-30 15:30:32.711  7979  7979 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-30 15:30:32.711  7979  7979 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-30 15:30:32.757  7979  7983 E QC-QMI  : qmi_client [7979] 15: failed to locate client data
,08-30 15:30:32.763   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-30 15:30:32.763   470   470 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-30 15:30:32.781  7987  7987 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-30 15:30:32.796  7988  7988 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-30 15:30:32.834  7697  7922 I bt_vendor: bluetooth satus is on
08-30 15:30:32.834  7697  7922 D bt_hci_bdroid: preload
,08-30 15:30:32.836  7697  7963 D bt_userial_mct: userial_open(port:0)
,08-30 15:30:32.836  7697  7963 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-30 15:30:32.841  7697  7963 I bt_vendor: Done intiailizing UART
08-30 15:30:32.846  7697  7963 I bt_vendor: Done intiailizing UART
,08-30 15:30:32.846  7697  7963 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 15:30:32.846  7697  7963 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 15:30:32.855  7697  7961 I bt-btu  : btu_task received preload complete event
,08-30 15:30:32.857  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-30 15:30:32.857  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-30 15:30:32.861  7697  7990 D bt_userial_mct: Entering userial_read_thread()
,08-30 15:30:32.864  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 15:30:32.868  7697  7961 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 15:30:32.974  7697  7961 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-30 15:30:32.974  7697  7961 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0240061 
08-30 15:30:32.974  7697  7961 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0240061 
,08-30 15:30:33.029  7697  7926 E bt-btif : Calling BTA_HhEnable
,08-30 15:30:33.030  7697  7926 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-30 15:30:33.030  7697  7926 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-30 15:30:33.041  1036  1036 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-30 15:30:33.043  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-30 15:30:33.043  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-30 15:30:33.043  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-30 15:30:33.043  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-30 15:30:33.044  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-30 15:30:33.045  7697  7926 D BluetoothAdapterProperties: Name is: G3
08-30 15:30:33.053  7697  7926 D BluetoothAdapterProperties: Scan Mode:20
08-30 15:30:33.053  7697  7926 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:30:33.054  7697  7926 D bt_hci_bdroid: postload
,08-30 15:30:33.062  7697  7963 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 15:30:33.063  7697  7961 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
,08-30 15:30:33.064  7697  7926 D bte_conf: Device ID record 1 : primary
08-30 15:30:33.064  7697  7926 D bte_conf:   vendorId            = 00c4
08-30 15:30:33.064  7697  7926 D bte_conf:   vendorIdSource      = 0001
08-30 15:30:33.064  7697  7926 D bte_conf:   product             = 13a1
08-30 15:30:33.064  7697  7926 D bte_conf:   version             = 1000
08-30 15:30:33.064  7697  7926 D bte_conf:   clientExecutableURL = 
08-30 15:30:33.064  7697  7926 D bte_conf:   serviceDescription  = 
08-30 15:30:33.064  7697  7926 D bte_conf:   documentationURL    = 
08-30 15:30:33.064  7697  7926 D bte_conf: bte_load_did_conf no section named DID2.
08-30 15:30:33.065  7697  7963 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:30:33.068  7697  7922 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-30 15:30:33.068  7697  7922 D BluetoothAdapterProperties: ScanMode =  20
08-30 15:30:33.068  7697  7922 D BluetoothAdapterProperties: State =  11
08-30 15:30:33.069  7697  7922 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-30 15:30:33.069  7697  7922 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
,08-30 15:30:33.069  7697  7922 D BluetoothAdapterProperties: Setting state to 12
08-30 15:30:33.069  7697  7922 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 15:30:33.070  7697  7926 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 15:30:33.070  7697  7926 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 15:30:33.062  7992  7992 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:33.079  1036  1118 D BluetoothManagerService: Message: 60
08-30 15:30:33.072  7992  7992 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:33.080  7697  7922 I BluetoothAdapterState: Entering On State
08-30 15:30:33.088  7697  7963 D bt_hci_bdroid: Used up Tx Cmd credits
,08-30 15:30:33.090  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-30 15:30:33.090  1036  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-30 15:30:33.093  7697  7922 D LGBluetoothServiceAdapter: [BTUI] OnState
08-30 15:30:33.093  7697  7922 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-30 15:30:33.093  7697  7922 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-30 15:30:33.094  7697  7922 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-30 15:30:33.100  7697  7961 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:33.100  7697  7961 W bt-smp  : Plain text(LSB ~ MSB) = 1b 7e 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:33.100  7697  7961 W bt-smp  : Encrypted text(LSB ~ MSB) = 9f 24 b2 f5 45 34 db 68 84 c7 7f 48 6f 89 31 60 
,08-30 15:30:33.103  7697  7963 D bt_hci_bdroid: Used up Tx Cmd credits
08-30 15:30:33.104  7697  7961 W bt-btm  : Stopping oneshot timer
08-30 15:30:33.105  7697  7990 E bt_mct  : hci lib postload completed
08-30 15:30:33.115  7697  7926 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 15:30:33.115  7697  7926 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-30 15:30:33.120  1036  1036 D BluetoothManagerService: Stored Bluetooth name: G3
08-30 15:30:33.130  7697  7922 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-30 15:30:33.135  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:33.135  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:33.135  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:33.135  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:33.135  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:33.135  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:33.135  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:33.135  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:33.142  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:33.146  7697  7961 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:33.146  7697  7961 W bt-smp  : Plain text(LSB ~ MSB) = 63 13 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:33.146  7697  7961 W bt-smp  : Encrypted text(LSB ~ MSB) = de ac b6 af e2 ed 41 da 70 cd a0 48 8f 75 57 c2 
,08-30 15:30:33.148  7697  7961 W bt-btm  : Stopping oneshot timer
08-30 15:30:33.150  6907  7346 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:30:33.185  7997  7997 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-30 15:30:33.195  6907  7346 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 15:30:33.197  6907  6922 D BluetoothPan: onBluetoothStateChange on: true
08-30 15:30:33.197  6907  6922 D BluetoothPan: onBluetoothStateChange call bindService
08-30 15:30:33.201  6907  7346 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 15:30:33.203  7697  7961 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:33.203  7697  7961 W bt-smp  : Plain text(LSB ~ MSB) = f4 52 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:33.204  7697  7961 W bt-smp  : Encrypted text(LSB ~ MSB) = 01 04 0b 0d 41 57 27 a5 f5 ae b2 3e 16 dc 78 72 
08-30 15:30:33.204  7697  7961 W bt-btm  : Stopping oneshot timer
08-30 15:30:33.208  6907  6907 D BluetoothA2dp: Proxy object connected
08-30 15:30:33.208  6907  6907 D A2dpProfile: Bluetooth service connected
08-30 15:30:33.209  1036  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:33.210  1036  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 15:30:33.216  7697  7961 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:33.216  7697  7961 W bt-smp  : Plain text(LSB ~ MSB) = f9 b8 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:33.216  7697  7961 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b eb 79 9e a5 f5 5f d4 9d 1f 8d 2f 1c 50 63 32 
08-30 15:30:33.216  7697  7961 W bt-btm  : Stopping oneshot timer
,08-30 15:30:33.224  6907  6922 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:33.225  1036  1036 D BluetoothA2dp: Proxy object connected
08-30 15:30:33.230  6907  6907 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 15:30:33.230  6907  6907 D PanProfile: Bluetooth service connected
,08-30 15:30:33.234  6907  6907 D BluetoothInputDevice: Proxy object connected
08-30 15:30:33.234  6907  6907 D HidProfile: Bluetooth service connected
08-30 15:30:33.240  7697  7961 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-30 15:30:33.240  7697  7961 W bt-smp  : Plain text(LSB ~ MSB) = fc 9f 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-30 15:30:33.240  7697  7961 W bt-smp  : Encrypted text(LSB ~ MSB) = 04 81 d2 36 8e 50 5f 92 c9 84 36 00 3e d6 72 19 
08-30 15:30:33.240  7697  7961 W bt-btm  : Stopping oneshot timer
08-30 15:30:33.326  1036  2017 I art     : Explicit concurrent mark sweep GC freed 27158(1321KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.924ms total 113.531ms
,08-30 15:30:33.328  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:33.328  1036  1036 D BluetoothHeadset: Proxy object connected
08-30 15:30:33.331  1853  4020 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:33.331  1853  1853 D BluetoothHeadset: Proxy object connected
08-30 15:30:33.332  6907  6907 D BluetoothHeadset: Proxy object connected
08-30 15:30:33.332  6907  6907 D HeadsetProfile: Bluetooth service connected
08-30 15:30:33.333  1853  1853 D BluetoothHeadset: Proxy object connected
08-30 15:30:33.333  1853  4023 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 15:30:33.336  1853  1853 D BluetoothHeadset: Proxy object connected
08-30 15:30:33.337  6907  6923 D BluetoothMap: onBluetoothStateChange: up=true
08-30 15:30:33.341  6907  6907 D BluetoothMap: Proxy object connected
08-30 15:30:33.341  6907  6907 D MapProfile: Bluetooth service connected
,08-30 15:30:33.341  6907  6907 D BluetoothMap: getConnectedDevices()
08-30 15:30:33.342  1036  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-30 15:30:33.342  1036  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-30 15:30:33.343  1036  1036 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-30 15:30:33.343  7697  7712 V BluetoothMapService: getConnectedDevices()
08-30 15:30:33.344  1036  1118 D BluetoothManagerService: Message: 40
08-30 15:30:33.344  1036  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-30 15:30:33.345  1942  1942 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:33.345  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-30 15:30:33.346  1942  2124 D LGBluetoothAPIService: Message: 1
08-30 15:30:33.346  1942  2124 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-30 15:30:33.346  1942  2124 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-30 15:30:33.346  1942  2124 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 15:30:33.348  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:33.350  7697  7697 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:33.350  7697  7697 D BluetoothMapService: STATE_ON
08-30 15:30:33.353  6907  6907 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-30 15:30:33.355  6907  6907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-30 15:30:33.360  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:33.360  7697  7697 V BluetoothPbapService: Pbap Service onCreate
08-30 15:30:33.360  7697  7697 V BluetoothPbapService: Starting PBAP service
08-30 15:30:33.362  7697  7697 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-30 15:30:33.362  7697  7697 V BluetoothPbapService: Pbap Service onBind
08-30 15:30:33.363  7697  7697 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:33.363  7697  7697 V BluetoothPbapService: state: 12
08-30 15:30:33.363  7697  7697 V BluetoothMapService: Handler(): got msg=1
08-30 15:30:33.363  7697  7697 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-30 15:30:33.363  6907  6907 D DockEventReceiver: finishStartingService: stopping service
08-30 15:30:33.364  7697  7697 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-30 15:30:33.364  7697  7697 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:33.364  7697  7697 V BluetoothPbapReceiver: ***********state = 12
08-30 15:30:33.364  7697  8016 D BluetoothMapMasInstance: MAS initSocket()
08-30 15:30:33.365  6907  6907 D BluetoothPbap: Proxy object connected
08-30 15:30:33.365  6907  6907 D PbapServerProfile: Bluetooth service connected
08-30 15:30:33.365  7697  7697 V BluetoothPbapService: Handler(): got msg=1
08-30 15:30:33.365  7697  8016 D BluetoothMapMasInstance:   masId = 00
08-30 15:30:33.365  7697  8016 D BluetoothMapMasInstance:   msgTypes = 0e
08-30 15:30:33.365  7697  8016 D BluetoothMapMasInstance:   masName = SMS/MMS
08-30 15:30:33.365  7697  8016 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-30 15:30:33.365  7697  7697 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-30 15:30:33.368  7697  8017 V BluetoothPbapService: Pbap Service initSocket
08-30 15:30:33.368  2210  2210 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 15:30:33.369  2210  2210 D c       : Getting all permits...
08-30 15:30:33.369  2210  2210 D a       : Opening database...
,08-30 15:30:33.373  2210  2210 D a       : Opening database auth.proximity.permit_store...
08-30 15:30:33.374  2210  2210 D a       : Closing database...
08-30 15:30:33.376  1036  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:33.376  1036  1959 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:33.377  7697  8016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:33.378  7697  8017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:33.380  7697  7926 D BluetoothAdapterProperties: Scan Mode:21
08-30 15:30:33.380  7697  7926 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-30 15:30:33.381  7697  8017 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-30 15:30:33.381  7697  8016 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-30 15:30:33.381  7697  8017 V BluetoothPbapService: Succeed to create listening socket 
08-30 15:30:33.381  7697  8017 V BluetoothPbapService: Accepting socket connection...
08-30 15:30:33.381  7697  8016 V BluetoothMapMasInstance: Succeed to create listening socket 
08-30 15:30:33.381  7697  8016 D BluetoothMapMasInstance: Accepting socket connection...
08-30 15:30:33.384  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:33.395  6907  6907 D BluetoothPermissionRequest: onReceive
08-30 15:30:33.397  6907  6907 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-30 15:30:33.399  6907  6907 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-30 15:30:33.401  7697  7697 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-30 15:30:33.402  7697  7697 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-30 15:30:33.409  7697  7697 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-30 15:30:33.445  7697  7697 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-30 15:30:33.445  7697  7697 V BtOppService: onCreate
,08-30 15:30:33.450  7697  7697 V BluetoothOppNotification: send message
08-30 15:30:33.454  7697  7697 V BtOppService: Starting RfcommListener
08-30 15:30:33.458  7697  7697 D BluetoothOppPreference: Dumping Names:  
08-30 15:30:33.459  7697  7697 D BluetoothOppPreference: {}
08-30 15:30:33.459  7697  7697 D BluetoothOppPreference: Dumping Channels:  
08-30 15:30:33.459  7697  7697 D BluetoothOppPreference: {}
,08-30 15:30:33.459  7697  7697 V BtOppService: onStartCommand
08-30 15:30:33.469  7697  8025 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:30:33.470  7697  8025 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 15:30:33.471  7697  8022 V BtOppService: Deleted complete outbound shares, number =  0
,08-30 15:30:33.474  7697  7697 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:33.474  7697  7697 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-30 15:30:33.475  7697  8025 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@285541f0 on behalf of 
08-30 15:30:33.475  7697  8022 V BtOppService: Deleted complete inbound failed shares, number = 0
08-30 15:30:33.476  7697  8022 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-30 15:30:33.477  7697  8022 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16046369 on behalf of 
08-30 15:30:33.479  7697  7697 V BluetoothOppNotification: new notify threadi!
08-30 15:30:33.480  7697  7697 V BluetoothOppNotification: send delay message
08-30 15:30:33.481  7697  7697 V BtOppService: start RfcommListener
08-30 15:30:33.481  7697  8026 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 15:30:33.483  7697  8026 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25e81ee on behalf of 
08-30 15:30:33.484  7697  8026 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 15:30:33.484  7697  7697 V BtOppService: RfcommListener started
08-30 15:30:33.485  7697  8026 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-30 15:30:33.486  7697  7697 V BtOppService: ContentObserver received notification
08-30 15:30:33.486  7697  7697 V BtOppService: ContentObserver received notification
08-30 15:30:33.486  7697  8027 V BtOppRfcommListener: Starting RFCOMM listener....
,08-30 15:30:33.489  7697  8025 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-30 15:30:33.490  7697  8025 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-30 15:30:33.500  1036  1998 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:33.501  7697  8027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 15:30:33.502  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
08-30 15:30:33.502  7697  7697 V BluetoothFtpService: Ftp Service onCreate
08-30 15:30:33.502  7697  7697 I BluetoothFtpService: Ftp Service onCreate
08-30 15:30:33.502  7697  7697 V BluetoothFtpService: Ftp Service onStartCommand
08-30 15:30:33.502  7697  7697 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:33.502  7697  7697 V BluetoothFtpService: Starting Listening on sockets
08-30 15:30:33.502  7697  8027 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-30 15:30:33.503  7697  7697 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-30 15:30:33.503  7697  7697 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-30 15:30:33.503  7697  7697 V BluetoothSapReceiver: SapReceiver onReceive 
08-30 15:30:33.503  7697  7697 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:33.503  7697  7697 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-30 15:30:33.503  7697  8027 V BtOppRfcommListener: Started RFCOMM listener....
08-30 15:30:33.503  7697  7697 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-30 15:30:33.503  7697  8027 I BtOppRfcommListener: Accept thread started.
08-30 15:30:33.503  7697  8027 V BtOppRfcommListener: Accepting connection...
08-30 15:30:33.504  7697  8026 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b648d1c on behalf of 
08-30 15:30:33.504  7697  8025 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c76cd25 on behalf of 
08-30 15:30:33.505  7697  7697 V BluetoothFtpService: Handler(): got msg=1
08-30 15:30:33.505  7697  8025 V BluetoothOppNotification: update too frequent, put in queue
08-30 15:30:33.505  7697  7697 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-30 15:30:33.506  7697  7697 V BluetoothFtpService: Ftp Service initSocket
08-30 15:30:33.506  7697  8025 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-30 15:30:33.509  7697  8026 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 15:30:33.511  7697  8026 V BluetoothOppNotification: outbound notification was removed.
08-30 15:30:33.511  7697  8026 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 15:30:33.511  1036  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:33.512  7697  7697 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:33.514  7697  7697 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-30 15:30:33.514  7697  7697 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-30 15:30:33.516  7697  8028 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-30 15:30:33.516  7697  8026 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30b4cefa on behalf of 
08-30 15:30:33.517  7697  8026 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 15:30:33.519  7697  8026 V BluetoothOppNotification: inbound notification was removed.
08-30 15:30:33.519  7697  8026 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 15:30:33.520  7697  8026 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23687cab on behalf of 
,08-30 15:30:33.529  7697  7697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@361fa2f4
,08-30 15:30:33.529  7697  7697 V BluetoothSapService: Sap Service onCreate
08-30 15:30:33.531  7697  7697 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-30 15:30:33.531  7697  7697 V BluetoothSapService: state: 12
08-30 15:30:33.531  7697  7697 V BluetoothSapService: Starting SAP server process
08-30 15:30:33.533  7697  7697 V BluetoothSapService: SAP Service startRfcommListenerThread
08-30 15:30:33.522  8029  8029 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:33.522  8029  8029 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:30:33.536  7697  8030 V BluetoothSapService: Sap Service initRfcommSocket
08-30 15:30:33.536  1036  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:33.537  7697  8030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 15:30:33.539  7697  8030 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-30 15:30:33.539  7697  8030 V BluetoothSapService: Succeed to create listening socket 
08-30 15:30:33.539  7697  8030 V BluetoothSapService: Accepting socket connection...
08-30 15:30:33.545  8029  8029 V BT_SAP  : Event pipe created
08-30 15:30:33.545  8029  8029 V BT_SAP  : create_server_socket qcom.sap.server
08-30 15:30:33.545  8029  8029 V BT_SAP  : created socket fd 6
,08-30 15:30:33.861  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:33.861  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:33.861  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:33.861  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 15:30:33.861  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:33.861  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:33.861  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:33.861  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 15:30:33.866  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:33.870  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:33.870  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27b127c1 added. We now have 8 listener(s)
08-30 15:30:33.870  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:33.873  1036  1781 D WifiServiceImplEx: setWifiEnabled: false pid=6765, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:30:33.873  1036  1781 D WifiService: setWifiEnabled: false pid=6765, uid=10118
08-30 15:30:33.873  1036  1781 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-30 15:30:33.878  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:33.883  1036  1052 D WifiServiceImplEx: setWifiEnabled: true pid=6765, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-30 15:30:33.883  1036  1052 D WifiService: setWifiEnabled: true pid=6765, uid=10118
08-30 15:30:33.883  1036  1052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 15:30:33.899  1036  1036 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-30 15:30:33.899  1036  1036 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-30 15:30:33.899  1036  1036 D Ulp_jni : JNI:system_update. Event-4
08-30 15:30:33.901  1036  1392 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-30 15:30:33.901  1036  1392 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-30 15:30:33.903  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-30 15:30:33.903  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-30 15:30:33.903  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): pid[1036] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-30 15:30:33.903  1036  1392 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-30 15:30:33.903  1036  1392 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-30 15:30:33.903  1036  1392 E WifiHW  : unknown target_country: EU , set to default,
,08-30 15:30:33.903  1036  1392 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-30 15:30:33.903  1036  1392 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-30 15:30:33.903  1036  1392 I WifiUtil: gEnableBmps=1
08-30 15:30:34.482  7697  7697 V BluetoothOppNotification: new notify threadi!
08-30 15:30:34.483  7697  7697 V BluetoothOppNotification: send delay message
,08-30 15:30:34.535   311   880 D SoftapController: Softap fwReload - Ok
,08-30 15:30:34.582  1036  1392 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (674ms)
,08-30 15:30:34.588  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 15:30:34.588  1036  1118 D Tethering: InitialState.processMessage what=4
,08-30 15:30:34.602   311   880 D CommandListener: Setting iface cfg
08-30 15:30:34.602   311   880 D CommandListener: Trying to bring down wlan0
08-30 15:30:34.606   311   880 D CommandListener: Clearing all IP addresses on wlan0
08-30 15:30:34.610  1036  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-30 15:30:34.620  1036  1392 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-30 15:30:34.622  8051  8051 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:30:34.622  8051  8051 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:34.640  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:30:34.640  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:30:34.640  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:30:34.645  1036  1392 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-30 15:30:34.645  1036  1392 D WifiMonitor: connecting to supplicant
,08-30 15:30:34.651  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:34.653  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-30 15:30:34.663  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-30 15:30:34.664  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:34.665  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:30:34.665  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:30:34.665  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:30:34.665  6907  6907 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:30:34.666  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 15:30:34.667  6907  6907 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:30:34.667  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 15:30:34.667  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:30:34.667  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:30:34.667  6907  6907 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:30:34.667  6907  6907 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:30:34.670  7697  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-30 15:30:34.670  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:30:34.670  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:30:34.670  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:30:34.670  6907  6907 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:30:34.674  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-30 15:30:34.675  8051  8051 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 15:30:34.681  6907  6907 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:30:34.681  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-30 15:30:34.681  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:30:34.681  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:30:34.681  6907  6907 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:30:34.681  6907  6907 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:30:34.682  7697  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2c303887 on behalf of 
08-30 15:30:34.685  7697  8049 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-30 15:30:34.686  7697  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-30 15:30:34.689  7697  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12b63b4 on behalf of 
08-30 15:30:34.690  7697  8049 V BluetoothOppNotification: outbound: succ-0  fail-0
08-30 15:30:34.691  7697  8049 V BluetoothOppNotification: outbound notification was removed.
08-30 15:30:34.691  7697  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-30 15:30:34.692  7697  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9127bdd on behalf of 
08-30 15:30:34.693  7697  8049 V BluetoothOppNotification: inbound: succ-0  fail-0
08-30 15:30:34.695  7697  8049 V BluetoothOppNotification: inbound notification was removed.
08-30 15:30:34.695  7697  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-30 15:30:34.700  7697  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@288a4352 on behalf of 
,08-30 15:30:34.710  8051  8051 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 15:30:34.710  8051  8051 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-30 15:30:34.727  1036  1998 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8069 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-30 15:30:34.768  8051  8051 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 15:30:34.802  8051  8051 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-30 15:30:34.807  8051  8051 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-30 15:30:34.809  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-30 15:30:34.809  1036  8097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-30 15:30:34.809  1036  8097 D WifiMonitor: Dropping event because (p2p0) is stopped
08-30 15:30:34.809  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-30 15:30:34.810  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-30 15:30:34.810  1036  1392 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-30 15:30:34.811  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:34.811  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:34.812  1036  1652 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8090 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 15:30:34.812  1036  1392 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:34.812  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-30 15:30:34.812  1036  1392 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-30 15:30:34.812  1036  1392 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-30 15:30:34.814  1036  1392 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-30 15:30:34.814  1036  1392 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-30 15:30:34.814  1036  1392 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-30 15:30:34.815  1036  1392 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-30 15:30:34.815  1036  1392 E WifiStateMachine: useWiFiOffloading() : false
08-30 15:30:34.815  1036  1392 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-30 15:30:34.815  1036  1392 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-30 15:30:34.816  1036  1392 D WifiNative-wlan0: SET update_config 1: returned true
08-30 15:30:34.816  1036  1392 D WifiConfigStore: Loading config and enabling all networks 
08-30 15:30:34.816  1036  1392 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-30 15:30:34.816  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.816  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.816  1036  1392 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-30 15:30:34.816  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.816  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.817  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:34.818  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-30 15:30:34.819  1942  1942 D WfdService: Waiting for WifiP2p enabling
08-30 15:30:34.820  1036  1036 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-30 15:30:34.821  1036  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-30 15:30:34.824  1036  1392 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-30 15:30:34.825  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:34.825  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:34.825  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:34.825  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:34.825  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:34.825  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:34.825  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:34.825  6765  6765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:34.826  8069  8088 W FormManager: Network not available. Please check & try again.
,08-30 15:30:34.829  6765  6765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:34.831  8051  8051 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 15:30:34.831  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 15:30:34.831  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 15:30:34.831  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-30 15:30:34.831  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-30 15:30:34.831  1036  8097 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-30 15:30:34.831  1036  8097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-30 15:30:34.833  8069  8089 V FormManager: Network unavailable.
08-30 15:30:34.834  1036  1392 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-30 15:30:34.834  1036  1392 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 15:30:34.835  1036  1392 D WifiStateMachine: enableVerboseLogging : level 2
08-30 15:30:34.835  1036  1392 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-30 15:30:34.835  8069  8089 V FormManager: Network unavailable.
08-30 15:30:34.835  1036  1392 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-30 15:30:34.835  1036  1392 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-30 15:30:34.836  1036  1392 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-30 15:30:34.836  1036  1392 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-30 15:30:34.836  1036  1392 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-30 15:30:34.836  1036  1392 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-30 15:30:34.837  1036  1392 D WifiNative-wlan0: SET model_number LG-D855: returned true
,08-30 15:30:34.837  1036  1392 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-30 15:30:34.837  1036  1392 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-30 15:30:34.837  1036  1392 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-30 15:30:34.838  1036  1392 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-30 15:30:34.838  1036  1392 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-30 15:30:34.838  1036  1392 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-30 15:30:34.839  1036  1392 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:30:34.839  1036  1392 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-30 15:30:34.840  1036  1392 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-30 15:30:34.840  1942  1942 D WfdsService: Supplicant Connection state is changed : true
08-30 15:30:34.840  1036  1392 D WifiNative-HAL: Setting external_sim to 1
08-30 15:30:34.840  1036  1392 D WifiNative-wlan0: doBoolean: SET external_sim 1
,08-30 15:30:34.840  1942  2352 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-30 15:30:34.840  1942  2352 D WfdsService: Set the WFDS Monitor: true
08-30 15:30:34.840  1942  2352 D WfdsMonitor: WfdsMonitorThread create
08-30 15:30:34.840  1036  1392 D WifiNative-wlan0: SET external_sim 1: returned true
08-30 15:30:34.840  1036  1392 I WifiNative-HAL: startHal
08-30 15:30:34.840  1942  2352 D WfdsMonitor: WFDS Monitor is created and started
08-30 15:30:34.840  1036  1392 D wifi    : setting scan oui 0xaf4f1e00
08-30 15:30:34.840  1942  2352 D WfdsService: WiFi: Supplicant connection re-established
08-30 15:30:34.841  1036  1392 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 15:30:34.841  1036  1392 I WifiNative-HAL: startHal
08-30 15:30:34.841  1036  1392 D wifi    : setting scan oui 0xaf4f1e00
08-30 15:30:34.841  1036  1392 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-30 15:30:34.841  7741  7741 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.841  1036  1392 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-30 15:30:34.841  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-30 15:30:34.842  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-30 15:30:34.842  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-30 15:30:34.843  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 15:30:34.843  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 15:30:34.843  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 15:30:34.843  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-30 15:30:34.843  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-30 15:30:34.844  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-30 15:30:34.844  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 15:30:34.844  1942  8109 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-30 15:30:34.844  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 15:30:34.844  1942  8109 E CtrlSupplicant: Succeed to open control connection
08-30 15:30:34.844  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 15:30:34.844  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-30 15:30:34.844  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-30 15:30:34.844  1942  8109 E CtrlSupplicant: Succeed to open monitor connection
08-30 15:30:34.845  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-30 15:30:34.845  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-30 15:30:34.845  8051  8051 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-30 15:30:34.845  1942  8109 D WfdsMonitor: Supplicant connection established
08-30 15:30:34.845  1942  2352 D WfdsService: Connected to the supplicant for wfds
08-30 15:30:34.845  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-30 15:30:34.845  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-30 15:30:34.845  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-30 15:30:34.846  1036  1392 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-30 15:30:34.846  1036  1392 E WifiNative: : [221,700,685 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-30 15:30:34.846  1036  1392 D WifiNative-wlan0: doBoolean: RECONNECT
08-30 15:30:34.847  1036  1392 D WifiNative-wlan0: RECONNECT: returned true
08-30 15:30:34.847  1036  1392 D WifiNative-wlan0: doString: [STATUS]
08-30 15:30:34.847  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-30 15:30:34.847  1036  8097 E WifiMonitor: WifiMonitor:wlan,0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-30 15:30:34.848  1036  1392 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 15:30:34.848  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
08-30 15:30:34.849  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:30:34.849  1036  1389 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.850   311   880 D CommandListener: Setting iface cfg
08-30 15:30:34.850   311   880 D CommandListener: Trying to bring up p2p0
08-30 15:30:34.850  1036  1389 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 15:30:34.850  1036  1389 D LGWifiP2pService: P2pEnablingState
08-30 15:30:34.850  1036  1389 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.850  1036  1389 D LGWifiP2pService: P2p socket connection successful
08-30 15:30:34.850  1036  1389 D LGWifiP2pService: P2pEnabledState
08-30 15:30:34.851  1036  1036 D WifiScanningService: SCAN_AVAILABLE : 3
,08-30 15:30:34.851  1036  1389 D LGWifiP2pService: sending p2p connection changed broadcast
08-30 15:30:34.851  1036  1036 D RttService: SCAN_AVAILABLE : 3
08-30 15:30:34.851  1036  1389 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-30 15:30:34.851  1036  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.852  1036  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.852  1036  1556 I WifiNative-HAL: startHal
08-30 15:30:34.852  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-30 15:30:34.852  1036  1392 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-30 15:30:34.852  1036  1392 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-30 15:30:34.853  1942  1942 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-30 15:30:34.853  1942  1942 D WfdsService: WifiP2pState is changed : true
08-30 15:30:34.853  1036  1392 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-30 15:30:34.853  1942  1942 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-30 15:30:34.853  1942  1942 D WfdsService: isConnected: false
08-30 15:30:34.853  1036  1392 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-30 15:30:34.853  1942  2352 D WfdsService: Receive the WFDS_ENABLE Method
08-30 15:30:34.853  1942  2352 D WfdsService: Set the WFDS Monitor: true
08-30 15:30:34.853  1942  2352 D WfdsService: Connected to the supplicant for wfds
08-30 15:30:34.853  1942  2352 D WfdsJNI : doCommand: WFDS_SET TRUE
08-30 15:30:34.853  8051  8051 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-30 15:30:34.853  1036  1392 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-30 15:30:34.854  1942  2352 D WfdsService: selectPreferredScanChannel [36]
08-30 15:30:34.854  1942  2352 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-30 15:30:34.854  1036  1392 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-30 15:30:34.854  1036  1392 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-30 15:30:34.854  8051  8051 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-30 15:30:34.855  1036  1389 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-30 15:30:34.855  1036  1389 D WifiNative-p2p0: doBoolean: SET device_name G3
08-30 15:30:34.855  1036  2017 I ActivityManager: Killing 7199:com.lge.drmservice/u0a62 (adj 15): empty #17
08-30 15:30:34.855  1036  1389 D WifiNative-p2p0: SET device_name G3: returned true
08-30 15:30:34.855  1036  1389 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-30 15:30:34.855  1036  1389 D LGWifiP2pService: before postfix = G3
08-30 15:30:34.856  1036  1389 D WifiServerServiceExt: postfix byte check : 2
08-30 15:30:34.856  1036  1389 D LGWifiP2pService: after postfix = G3
08-30 15:30:34.856  1036  1389 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-30 15:30:34.856  1036  1389 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-30 15:30:34.856  1036  1389 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-30 15:30:34.856  1036  1389 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-30 15:30:34.856  1036  1389 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-30 15:30:34.856  1036  1389 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-30 15:30:34.856  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-30 15:30:34.857  1036  1389 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-30 15:30:34.857  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress
08-30 15:30:34.857  1036  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf4f1e00
08-30 15:30:34.857  1036  1556 D wifi    : failed to get capabilities : -3
08-30 15:30:34.857  1036  1556 E WifiS,canningService: could not get scan capabilities
08-30 15:30:34.857  1036  1389 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-30 15:30:34.858  1036  1392 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-30 15:30:34.858  1036  1392 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-30 15:30:34.858  1036  1392 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-30 15:30:34.858  1036  1392 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-30 15:30:34.858  8051  8051 E wpa_supplicant: disconnect_rssi_lvl: -100
08-30 15:30:34.859  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=221713  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:30:34.886  8090  8090 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:30:34.902  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:30:34.903  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=221757  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:30:34.903  1036  1389 D LGWifiP2pService: DeviceAddress: 
08-30 15:30:34.903  1036  1389 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-30 15:30:34.903  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 15:30:34.903  1036  1389 D WifiNative-p2p0: P2P_FLUSH: returned true
08-30 15:30:34.903  1036  1389 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
,08-30 15:30:34.903  1036  1389 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-30 15:30:34.903  1036  1389 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-30 15:30:34.903  1036  1392 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 15:30:34.903  1036  1389 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-30 15:30:34.903  1036  1389 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-30 15:30:34.903  1036  1392 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-30 15:30:34.904  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-30 15:30:34.904  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:34.904  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:34.905  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:34.906  1036  2033 W libprocessgroup: failed to open /acct/uid_10062/pid_7199/cgroup.procs: No such file or directory
08-30 15:30:34.907  1942  1942 I WfdStateTracker: handleP2pThisDeviceChanged
08-30 15:30:34.907  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.907  1942  1942 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-30 15:30:34.907  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.907  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 15:30:34.907  1942  1942 D WfdsService: Update P2p Interface State: 3
08-30 15:30:34.913  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:34.914  1036  1389 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-30 15:30:34.914  1036  1389 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-30 15:30:34.914  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 15:30:34.914  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:34.914  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:34.914  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:34.914  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:34.914  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 15:30:34.914  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 15:30:34.914  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 15:30:34.915  1036  1914 I ActivityManager: Killing 7218:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-30 15:30:34.915  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 15:30:34.916  8051  8051 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:34.916  8051  8051 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 15:30:34.916  8051  8051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.916  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 15:30:34.916  8051  8051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.917  1942  8109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:34.917  1942  8109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:34.917  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:30:34.917  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:34.917  1036  8097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:34.917  1036  8097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:34.917  1036  8097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:34.917  1036  8097 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.917  1036  8097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.917  1036  8097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.917  1036  8097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:34.917  1036  8097 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.917  1036  8097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.917  1036  8097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.917  1036  1392 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-30 15:30:34.918  1036  1392 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:30:34.918  1036  1392 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:30:34.918  1036  1392 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-30 15:30:34.918  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-30 15:30:34.918  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-30 15:30:34.918  8051  8051 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:30:34.919  1036  8097 D WifiMonitor:, Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-30 15:30:34.919  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:30:34.919  1036  8097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:30:34.919  1036  8097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-30 15:30:34.919  1036  1392 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-30 15:30:34.919  1036  1392 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-30 15:30:34.919  1036  1392 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-30 15:30:34.919  1036  1392 D WifiNative-wlan0: doBoolean: SCAN
08-30 15:30:34.919  1036  1392 D WifiNative-wlan0: SCAN: returned false
08-30 15:30:34.920  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=221774  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:30:34.928  6765  6830 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-30 15:30:34.929  6765  6830 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 15:30:34.930  6765  6830 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2f0066db Bundle[{}]
08-30 15:30:34.931  6765  6830 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 15:30:34.931  6765  6830 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 15:30:34.931  6765  6830 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 15:30:34.932  6765  6830 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 15:30:34.932  6765  6830 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 15:30:34.932  6765  6830 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 15:30:34.936  6765  6830 I System.out: Running OutgoingSocketThread
08-30 15:30:34.936  6765  8113 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 877)
,08-30 15:30:34.940  6765  8113 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 34667
08-30 15:30:34.940  6765  8113 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-30 15:30:34.961  1036  1389 D LGWifiP2pService: InactiveState
08-30 15:30:34.961  1036  1389 D LGWifiP2pService: InactiveState{ when=-57ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.961  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-57ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.961  1036  1389 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-30 15:30:34.962  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-30 15:30:34.962  8051  8051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:34.962  8051  8051 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-30 15:30:34.962  8051  8051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.963  8051  8051 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-30 15:30:34.963  1036  1389 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-30 15:30:34.963  1942  8109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:30:34.963  1942  8109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:34.963  1942  8109 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:34.963  1036  8097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-30 15:30:34.963  1036  8097 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:34.963  1036  1389 D LGWifiP2pService: InactiveState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.963  1036  8097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:34.963  1036  8097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-30 15:30:34.963  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-46ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.963  1036  8097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:34.963  1036  8097 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.963  1036  8097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.963  1036  8097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.963  1036  1389 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.963  1036  8097 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-30 15:30:34.963  1036  8097 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.964  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.964  1036  8097 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.964  1036  8097 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-30 15:30:34.964  1036  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.964  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=221818  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-30 15:30:34.964  1036  1389 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.964  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.964  1036  1389 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.964  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.964  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.964  1036  1389 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.964  1036  1392 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:34.965  1036  1392 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:34.965  1036  1389 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=6 target,=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.965  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.965  1036  1389 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:34.965  1036  1392 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:34.966  1036  1036 E WifiServerServiceExt: No p2p device connected
08-30 15:30:34.966  1036  1392 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:34.966  1942  2352 W WfdsService: DefaultState - msg [9441285] is not handled
08-30 15:30:34.966  1036  2051 W libprocessgroup: failed to open /acct/uid_10085/pid_7218/cgroup.procs: No such file or directory
08-30 15:30:34.966  1036  1392 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-30 15:30:34.971  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:34.971  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:34.971  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.971  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:34.971  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-30 15:30:34.972  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:34.972  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:34.972  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-30 15:30:34.974  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:34.974  1036  1036 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-30 15:30:34.990  8090  8090 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-30 15:30:34.992  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-30 15:30:34.996  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:35.007  8069  8115 W FormManager: Network not available. Please check & try again.
,08-30 15:30:35.012  8069  8116 V FormManager: Network unavailable.
08-30 15:30:35.016  8069  8116 V FormManager: Network unavailable.
08-30 15:30:35.021  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:30:35.022  4351  4351 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-30 15:30:35.028  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:35.033  4351  4351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-30 15:30:35.042  4351  8117 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-30 15:30:35.048  4351  8118 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-30 15:30:35.048  4351  8118 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-30 15:30:35.101  1036  2017 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8119 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-30 15:30:35.247  8119  8119 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 15:30:35.247  8119  8119 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-30 15:30:35.263  8119  8119 V [BNRBootReceiver]: Boot Receiver Return
,08-30 15:30:35.264  8119  8119 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 15:30:35.315  1036  1998 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8140 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-30 15:30:35.316  1036  1998 I ActivityManager: Killing 7253:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-30 15:30:35.425  8051  8051 E wpa_supplicant: USIM:  scard_init function
,08-30 15:30:35.425  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-30 15:30:35.425  1036  8097 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-30 15:30:35.426  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-30 15:30:35.426  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-30 15:30:35.426  8051  8051 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-30 15:30:35.426  1036  8097 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-30 15:30:35.428  1036  1392 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 15:30:35.430  1036  1392 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 15:30:35.431  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-30 15:30:35.431  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-30 15:30:35.433  1036  1392 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,08-30 15:30:35.435  1036  1392 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-30 15:30:35.436  1036  1392 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-30 15:30:35.446  1036  1960 W libprocessgroup: failed to open /acct/uid_10093/pid_7253/cgroup.procs: No such file or directory
,08-30 15:30:35.460  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=222315  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-30 15:30:35.466  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 15:30:35.466  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:35.468  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.469  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=222324  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-30 15:30:35.470  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.470  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.470  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 15:30:35.471  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:35.471  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-30 15:30:35.505  8140  8140 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 15:30:35.537  8140  8140 D PluginManager: init()
,08-30 15:30:35.550  8051  8051 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 15:30:35.553  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-30 15:30:35.553  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-30 15:30:35.553  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-30 15:30:35.553  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-30 15:30:35.554  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:35.554  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:35.556  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=222410  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 15:30:35.557  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=222411  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-30 15:30:35.557  1036  1392 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222412
08-30 15:30:35.558  1036  1392 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222412
08-30 15:30:35.558  1036  1392 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222413
08-30 15:30:35.559  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222413
08-30 15:30:35.560  1036  1392 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=222414
08-30 15:30:35.560  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=222415  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 15:30:35.563  1036  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 15:30:35.563  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:35.563  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-30 15:30:35.564  8051  8051 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:30:35.564  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-30 15:30:35.564  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:30:35.564  1036  8097 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 15:30:35.564  8051  8051 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:30:35.565  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-30 15:30:35.565  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:30:35.565  1036  8097 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-30 15:30:35.569  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:35.569  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:35.570  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=222424  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-30 15:30:35.571  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:35.571  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:35.572  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.572  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.572  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-30 15:30:35.574  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.574  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.574  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-30 15:30:35.575  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:35.577  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:35.577  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:35.577  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:35.577  1036  1036 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-30 15:30:35.578  1036  1392 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=222433  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 15:30:35.579  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=222433  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-30 15:30:35.580  1036  1392 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=222434
08-30 15:30:35.580  1036  1392 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=222435
08-30 15:30:35.581  1036  1392 D WifiNative-wlan0: doString: [STATUS]
08-30 15:30:35.581  1036  8097 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-30 15:30:35.581  1036  8097 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-30 15:30:35.581  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.582  1036  1392 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-30 15:30:35.583  1036  1392 I WifiServiceExtension: setVHTCapabilityType  : false
08-30 15:30:35.588  1036  1392 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-30 15:30:35.588  1036  1392 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-30 15:30:35.592  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.592  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.592  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 15:30:35.598  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:35.598  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:35.598  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.599  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.599  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-30 15:30:35.599  1036  1377 V AlarmManager: RTC_WAKEUP set : Alarm{240cc607 type 0 when 1472563830044 com.google.android.gms} when 1472563830044
08-30 15:30:35.600  1036  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2e30a334 type 2 when 222165 android} when 222165
08-30 15:30:35.600  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.600  1036  1392 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-30 15:30:35.601  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:30:35.601  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-30 15:30:35.601  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:30:35.601  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:30:35.602  1036  1442 D ConnectivityService: Got NetworkAgent Messenger
08-30 15:30:35.602  1036  1442 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 15:30:35.602  1036  1442 D ConnectivityService: NetworkAgent connected
08-30 15:30:35.604  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:35.604  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:35.606  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.607  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-30 15:30:35.608  1036  1392 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 15:30:35.608  1036  1392 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-30 15:30:35.608  1036  1392 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-30 15:30:35.608  1036  1392 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-30 15:30:35.613  1036  1392 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-30 15:30:35.614   311   880 D CommandListener: Setting iface cfg
08-30 15:30:35.617  1036  1392 E WifiStateMachine: Start Dhcp Watchdog 3
08-30 15:30:35.618  1036  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=222472  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:35.618  1036  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=222473  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:35.619  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=222473  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:35.619  1036  8164 D DhcpStateMachine: StoppedState
08-30 15:30:35.620  1036  8164 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:35.620  1036  8164 D DhcpStateMachine: WaitBeforeStartState
08-30 15:30:35.620  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:35.620  1036  1036 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-30 15:30:35.621  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:35.622  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:35.622  1036  1392 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:35.622  1036  1392 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:35.623  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-30 15:30:35.623  1036  1392 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-30 15:30:35.625  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:35.625  1036  1036 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-30 15:30:35.625  1036  1392 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=222480  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-30 15:30:35.626  1036  1392 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=222480  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:35.626  1036  1392 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=222481  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-30 15:30:35.628  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14112] from screen [on:0 period:-609946901] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 15:30:35.629  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-609946900] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-30 15:30:35.629  1036  1392 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-30 15:30:35.632  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.633  1036  1442 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-30 15:30:35.633  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.633  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.634  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.634  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.635  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.635  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.635  1036  1442 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 15:30:35.636  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
08-30 15:30:35.636  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:35.636  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 15:30:35.636  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=102,0,0
08-30 15:30:35.636  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-30 15:30:35.637  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-30 15:30:35.637  1036  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-30 15:30:35.637  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 0
,08-30 15:30:35.638  1036  1392 D WifiNative-wlan0: SET ps 0: returned true
08-30 15:30:35.638  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-30 15:30:35.638  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-30 15:30:35.638  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-30 15:30:35.639  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29e715ef target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:35.639  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@29e715ef target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:35.639  1036  8164 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:35.639  1036  8164 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-30 15:30:35.639  1036  1392 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-30 15:30:35.639  1036  1392 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 15:30:35.640  1036  1392 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 15:30:35.641   311   880 D CommandListener: Setting iface cfg
08-30 15:30:35.641   311   880 D CommandListener: Trying to bring up wlan0
08-30 15:30:35.642  1036  1392 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-30 15:30:35.643  1036  1036 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-30 15:30:35.643  1036  1036 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-30 15:30:35.644  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.645  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.645  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.645  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.646  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.646  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-30 15:30:35.647  1036  1442 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 15:30:35.648  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 15:30:35.648  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-30 15:30:35.648  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-30 15:30:35.648  1036  1389 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:35.648  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-30 15:30:35.649  1036  1389 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:35.649  1036  1392 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-30 15:30:35.649  1036  1392 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-30 15:30:35.649  8051  8051 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-30 15:30:35.649  1036  1392 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-30 15:30:35.649  1036  1392 D WifiNative-wlan0: doBoolean: SET ps 1
,08-30 15:30:35.666  1036  1392 D WifiNative-wlan0: SET ps 1: returned true
08-30 15:30:35.666  1036  1442 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-30 15:30:35.667  1036  1392 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-30 15:30:35.667  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-30 15:30:35.667  1036  1392 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 15:30:35.668  1036  1442 D ConnectivityService: ignoring duplicate network state non-change
08-30 15:30:35.671  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:35.671  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:35.673  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.673  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.674  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 15:30:35.674  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.678  1036  1442 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-30 15:30:35.678  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 15:30:35.679  1036  1442 D ConnectivityService: Adding iface wlan0 to network 102
08-30 15:30:35.681  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.681  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-30 15:30:35.683  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 15:30:35.687  1942  1942 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-30 15:30:35.689  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.689  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.689  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 15:30:35.691  1036  1392 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 15:30:35.697  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:35.697  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-30 15:30:35.699  1036  1036 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-30 15:30:35.701  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:35.704  1036  1442 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 15:30:35.704  1036  1442 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-30 15:30:35.705  1036  1036 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.705  1036  1036 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 15:30:35.705  1036  1036 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-30 15:30:35.706  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:35.706  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 15:30:35.706  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.708  1036  1442 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-30 15:30:35.709   311   880 E Netd    : netlink response contains error (File exists)
08-30 15:30:35.709  1036  1442 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 15:30:35.710  1036  1442 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-30 15:30:35.710  1036  1442 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-30 15:30:35.710  1036  1442 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-30 15:30:35.711  1036  1442 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-30 15:30:35.711  1036  1442 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 15:30:35.711  1036  1442 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 15:30:35.712  1036  8162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:35.712  1036  8162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-30 15:30:35.712  1036  8162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 15:30:35.712  1036  8162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-30 15:30:35.713  1036  1442 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 15:30:35.714  1036  1442 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:35.714  1036  1442 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:35.714  1036  1442 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 15:30:35.714  1036  1442 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.714  1036  1442 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-30 15:30:35.714  1036  1442 D ConnectivityService: currentScore = 0, newScore = 20
08-30 15:30:35.714  1036  1442 D ConnectivityService:    accepting network in place of null
08-30 15:30:35.714  1036  1442 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.714  1036  1392 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.715  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.715  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:35.715  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:30:35.715  1036  1442 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 15:30:35.715   311  8168 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-30 15:30:35.715  1036  1442 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-30 15:30:35.716  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.C,ONNECTIVITY_CHANGE_IMMEDIATE
08-30 15:30:35.717  1036  1442 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-30 15:30:35.717  1036  1442 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,08-30 15:30:35.717  1036  1036 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-30 15:30:35.717  1036  1442 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-30 15:30:35.717  1036  1036 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-30 15:30:35.718  1036  1036 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-30 15:30:35.718  1036  1036 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-30 15:30:35.718  1036  1442 D ConnectivityService: validation of new default Network = false
08-30 15:30:35.718  1036  1442 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-30 15:30:35.718  1036  1442 D DSQN    : enableDataServiceNotify 
08-30 15:30:35.718  1036  1442 D DSQN    : start dsqn bin
08-30 15:30:35.722  1036  1442 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 15:30:35.723  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.723  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:35.723  1036  1442 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:35.724  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:30:35.725  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 15:30:35.725  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-30 15:30:35.725  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.712  8169  8169 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:35.712  8169  8169 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-30 15:30:35.734  8169  8169 E DSQN    : DSQN ssw
08-30 15:30:35.740  1036  1388 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-30 15:30:35.755  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-30 15:30:35.756  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-30 15:30:35.757  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.778   311  8168 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-30 15:30:35.810   311  8168 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-30 15:30:35.842  1036  8164 D DhcpStateMachine: DHCPV4 request on wlan0
,08-30 15:30:35.844  1036  8164 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-30 15:30:35.844  1036  8164 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-30 15:30:35.842  8173  8173 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:35.842  8173  8173 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-30 15:30:35.856   311   879 D LGDataListener: argv[0]=dsqncommand
08-30 15:30:35.856   311   879 D LGDataListener: argv[1]=wlan0
08-30 15:30:35.856   311   879 D LGDataListener: argv[2]=1
08-30 15:30:35.856   311   879 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-30 15:30:35.857  8173  8173 I dhcpcd  : version 5.5.6 starting
08-30 15:30:35.859  8173  8173 E dhcpcd  : get_duid: m
08-30 15:30:35.859  8173  8173 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-30 15:30:35.859  8173  8173 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-30 15:30:35.868  1036  1116 D DSQN    : DSQM DsqnNotification wlan0  1
08-30 15:30:35.868  1036  1116 D DSQN    : start to monitor internet connection
08-30 15:30:35.881  1036  8162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 13:30:35 GMT], X-Android-Received-Millis=[1472563835880], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472563835853]}
08-30 15:30:35.881  1036  8162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 15:30:35.881  1036  8162 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-30 15:30:35.884  1036  1442 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-30 15:30:35.884  1036  1442 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-30 15:30:35.884  1036  1442 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:35.884  1036  1442 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:35.884  1036  1442 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-30 15:30:35.885  1036  1442 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-30 15:30:35.885  1036  1442 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-30 15:30:35.885  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.885  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:35.885  1036  1442 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:35.886  1036  1442 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.886  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 15:30:35.886  1036  1392 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.886  1036  1442 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 15:30:35.886  1036  1392 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 15:30:35.887  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:35.887  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-30 15:30:35.899  8173  8173 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 15:30:35.899  8173  8173 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-30 15:30:35.899  8173  8173 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 15:30:35.899  8173  8173 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-30 15:30:35.899  8173  8173 D dhcpcd  : wlan0: sending REQUEST (xid 0x4af9431b), next in 4.15 seconds
08-30 15:30:35.907  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-30 15:30:35.908  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.908  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-30 15:30:35.937  6765  6830 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 878)
,08-30 15:30:35.937  6765  6830 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 878)
08-30 15:30:35.941  6765  6830 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 883)
08-30 15:30:35.941  6765  6830 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 15:30:35.942  6765  6830 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 884)
08-30 15:30:35.945  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:35.945  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20d0eb66 added. We now have 2 listener(s)
08-30 15:30:35.946  1036  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:35.948  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:35.948  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:35.948  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:35.948  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:35.948  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17917ea7 added. We now have 9 listener(s)
08-30 15:30:35.948  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:35.949  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:30:35.951  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:35.955  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:35.955  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:35.955  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:35.955  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:35.955  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:35.955  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:35.955  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:35.955  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:35.957  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:35.957  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:35.958  8173  8173 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-30 15:30:35.959  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:35.959  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38677efd added. We now have 3 listener(s)
08-30 15:30:35.959  1036  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:35.961  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:35.962  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:35.963  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:35.963  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:35.963  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:35.963  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:35.963  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17057f2 added. We now have 10 listener(s)
08-30 15:30:35.963  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:35.964  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:35.964  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:35.964  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:35.964  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:35.964  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:35.964  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:35.964  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:35.964  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20d0eb66 removed from the list
08-30 15:30:35.964  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:35.964  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17917ea7 removed from the list
08-30 15:30:35.964  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:35.964  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:35.969  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:35.969  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:35.971  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:35.971  6765  6830 I org.thaliproject.p2p.btconnect,orlib.DiscoveryManager: stopDiscovery
08-30 15:30:35.971  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:35.971  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17917ea7 not in the list
08-30 15:30:35.971  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:35.971  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:30:35.972  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:35.972  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:35.972  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:35.972  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17057f2 removed from the list
08-30 15:30:35.972  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:35.972  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:35.972  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:35.972  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:35.972  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38677efd removed from the list
08-30 15:30:35.973  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:35.973  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecd5e43 added. We now have 2 listener(s)
08-30 15:30:35.974  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:35.977  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:35.977  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:35.977  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:35.977  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:35.977  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afbbcc0 added. We now have 9 listener(s)
08-30 15:30:35.977  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:35.977  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:30:35.979  8173  8173 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-30 15:30:35.979  8173  8173 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-30 15:30:35.980  8173  8173 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-30 15:30:35.980  8173  8173 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-30 15:30:35.980  8173  8173 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-30 15:30:35.980  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:35.980  8173  8173 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-30 15:30:35.981  8173  8173 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-30 15:30:35.981  8173  8173 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-30 15:30:35.984  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:35.984  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: ,true
08-30 15:30:35.984  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:35.984  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:35.984  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:35.984  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:35.984  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:35.984  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 15:30:35.986  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:35.986  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:35.989  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:35.989  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:35.989  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3628013e added. We now have 3 listener(s)
08-30 15:30:35.990  1036  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:35.992  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:35.993  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:35.993  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:35.993  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:35.993  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:35.993  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@335d9b9f added. We now have 10 listener(s)
08-30 15:30:35.993  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:35.993  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:30:35.993  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:30:35.993  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:30:35.994  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:35.994  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:30:35.997  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 15:30:35.998  1036  1914 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.003  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:30:36.003  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:30:36.005  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:30:36.005  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:36.006  6765  6830 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:30:36.007  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:36.007  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:36.009  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:36.009  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:36.009  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:36.009  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:36.009  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.009  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:36.009  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:36.009  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecd5e43 removed from the list
08-30 15:30:36.009  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.009  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afbbcc0 removed from the list
08-30 15:30:36.009  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:36.009  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.010  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.010  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 15:30:36.010  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:36.010  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:36.011  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.011  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afbbcc0 not in the list
08-30 15:30:36.011  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.011  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.012  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:36.012  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:36.012  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:36.013  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:36.013  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.013  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@335d9b9f removed from the list
08-30 15:30:36.013  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:36.013  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.013  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.013  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:36.013  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3628013e removed from the list
08-30 15:30:36.013  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:36.014  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331ef34a added. We now have 2 listener(s)
08-30 15:30:36.019  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.023  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:36.023  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:36.023  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:36.023  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:36.023  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@278a52bb added. We now have 9 listener(s)
08-30 15:30:36.023  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:36.024  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 15:30:36.028  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:36.031  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:36.031  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:36.031  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:36.031  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:36.031  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:36.031  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:36.031  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:36.031  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:36.033  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:36.033  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:36.035  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:36.035  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11b28331 added. We now have 3 listener(s)
08-30 15:30:36.036  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:36.036  1036  1941 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.038  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:36.039  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:36.040  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:36.040  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:36.040  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:36.040  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e0fa16 added. We now have 10 listener(s)
08-30 15:30:36.040  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:36.040  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:30:36.041  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:30:36.041  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:30:36.041  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:30:36.041  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:36.041  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:30:36.045  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:30:36.045  1036  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.049  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:30:36.050  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 15:30:36.051  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:30:36.051  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:36.053  6765  6830 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:30:36.053  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:36.053  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:36.053  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 15:30:36.053  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:36.053  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.053  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:36.053  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:36.053  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331ef34a removed from the list
08-30 15:30:36.053  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.053  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@278a52bb removed from the list
08-30 15:30:36.053  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:36.053  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.054  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.054  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.055  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:36.055  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:36.055  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.055  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@278a52bb not in the list
08-30 15:30:36.055  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.055  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.056  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:36.057  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:36.057  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:36.057  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:36.057  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.057  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15e0fa16 removed from the list
08-,30 15:30:36.057  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:36.057  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.057  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.057  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:36.057  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11b28331 removed from the list
08-30 15:30:36.058  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:36.058  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@337b216d added. We now have 2 listener(s)
08-30 15:30:36.058  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.061  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:36.061  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:36.061  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:36.061  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:36.061  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36eaa1a2 added. We now have 9 listener(s)
08-30 15:30:36.061  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 15:30:36.066  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:30:36.067  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:36.070  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:36.070  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:36.070  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:36.070  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:36.070  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:36.070  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:36.070  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:36.070  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:36.071  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:36.071  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:36.071  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:36.071  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd7d5f0 added. We now have 3 listener(s)
08-30 15:30:36.071  1036  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.073  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:36.073  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:36.073  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:36.074  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:36.074  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35b56769 added. We now have 10 listener(s)
08-30 15:30:36.074  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:36.074  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:30:36.074  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 15:30:36.074  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 15:30:36.074  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 15:30:36.074  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 15:30:36.075  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 15:30:36.077  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:36.078  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 15:30:36.078  1036  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.082  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 15:30:36.083  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 15:30:36.084  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 15:30:36.085  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:36.086  6765  6830 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-30 15:30:36.089  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:36.089  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:36.089  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:30:36.089  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:36.089  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.089  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:36.089  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:36.090  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@337b216d removed from the list
08-30 15:30:36.090  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.090  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36eaa1a2 removed from the list
08-30 15:30:36.090  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:36.090  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.091  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.091  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.092  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:36.092  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:36.092  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.092  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36eaa1a2 not in the list
08-30 15:30:36.092  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.092  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.093  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:36.093  6765  6830 D BluetoothLeScanner: could not find callback wrapper
08-30 15:30:36.093  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 15:30:36.093  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:36.094  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.094  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35b56769 removed from the list
08-30 15:30:36.094  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:36.094  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.094  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.094  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:36.094  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd7d5f0 removed from the list
08-30 15:30:36.094  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:36.094  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionM,anagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@167c611c added. We now have 2 listener(s)
08-30 15:30:36.095  1036  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.097  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:36.097  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:36.097  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:36.097  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:36.097  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30341125 added. We now have 9 listener(s)
08-30 15:30:36.097  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:36.098  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 15:30:36.102  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 15:30:36.106  6765  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 15:30:36.106  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 15:30:36.106  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 15:30:36.106  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 15:30:36.106  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 15:30:36.106  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:36.106  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 15:30:36.106  6765  6830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 15:30:36.107  6765  6830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 15:30:36.108  6765  6830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 15:30:36.108  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 15:30:36.108  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef160ab added. We now have 3 listener(s)
08-30 15:30:36.109  1036  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 15:30:36.110  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:36.111  6765  6765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 15:30:36.113  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-30 15:30:36.113  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 15:30:36.113  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 15:30:36.113  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 15:30:36.114  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@177c7308 added. We now have 10 listener(s)
08-30 15:30:36.114  6765  6830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 15:30:36.114  6765  6830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 15:30:36.114  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:36.114  6765  6830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 15:30:36.115  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:36.115  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.115  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 15:30:36.115  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:36.116  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@167c611c removed from the list
08-30 15:30:36.116  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.116  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30341125 removed from the list
08-30 15:30:36.116  6765  6830 D io.jxcore.node.ConnectivityMonitor: stop
08-30 15:30:36.116  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.116  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.116  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.117  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:36.117  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:36.117  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.117  6765  6830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30341125 not in the list
08-30 15:30:36.117  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.117  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.118  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 15:30:36.118  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 15:30:36.118  6765  6830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 15:30:36.118  6765  6830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@177c7308 removed from the list
08-30 15:30:36.118  6765  6830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 15:30:36.118  6765  6830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 15:30:36.118  6765  6830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 15:30:36.118  6765  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 15:30:36.118  6765  6830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef160ab removed from the list
08-30 15:30:36.119  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 15:30:36.119  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: tru,e - Start operation: Should start/stop everything
08-30 15:30:36.120  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 15:30:36.120  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 15:30:36.120  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 15:30:36.120  6765  6830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 15:30:36.126  8140  8140 W ExternalStrings: load override strings
08-30 15:30:36.126  8140  8140 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:30:36.126  8140  8140 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:30:36.128  8140  8140 D StatusProvider: onCreate
,08-30 15:30:36.131  6765  8200 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 891, name: My test thread name)
08-30 15:30:36.131  6765  8200 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 891, thread name: My test thread name)
08-30 15:30:36.132  6765  8200 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 891, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 15:30:36.133  6765  8201 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 893, name: My test thread name)
08-30 15:30:36.134  6765  8201 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 893, thread name: My test thread name)
08-30 15:30:36.134  6765  8201 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 893, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 15:30:36.135  6765  6830 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 15:30:36.135  6765  6830 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 15:30:36.136  6765  6830 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 15:30:36.136  6765  6830 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 15:30:36.136  6765  6830 D com.test.thalitest.ThaliTestRunner: Total duration: 22971 ms
08-30 15:30:36.137  6765  6830 I jxcore-log: *Native tests were executed*
08-30 15:30:36.137  6765  6830 I jxcore-log: 
08-30 15:30:36.137  6765  6830 I jxcore-log: Total number of executed tests:  80
08-30 15:30:36.137  6765  6830 I jxcore-log: 
08-30 15:30:36.137  6765  6830 I jxcore-log: Number of passed tests:  80
08-30 15:30:36.137  6765  6830 I jxcore-log: 
08-30 15:30:36.137  6765  6830 I jxcore-log: Number of failed tests:  0
08-30 15:30:36.137  6765  6830 I jxcore-log: 
08-30 15:30:36.138  6765  6830 I jxcore-log: Number of ignored tests:  0
08-30 15:30:36.138  6765  6830 I jxcore-log: 
08-30 15:30:36.138  6765  6830 I jxcore-log: Total duration:  22971
08-30 15:30:36.138  6765  6830 I jxcore-log: 
08-30 15:30:36.138  6765  6830 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 15:30:36.138  6765  6830 I jxcore-log: 
08-30 15:30:36.149  6765  6765 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 15:30:36.150  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.150  6765  6830 I jxcore-log: 
,08-30 15:30:36.152  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.152  6765  6830 I jxcore-log: 
08-30 15:30:36.153  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.153  6765  6830 I jxcore-log: 
08-30 15:30:36.154  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.154  6765  6830 I jxcore-log: 
08-30 15:30:36.154  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.154  6765  6830 I jxcore-log: 
08-30 15:30:36.156  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.156  6765  6830 I jxcore-log: 
08-30 15:30:36.158  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:30:36.158  6765  6830 I jxcore-log: 
08-30 15:30:36.159  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.159  6765  6830 I jxcore-log: 
08-30 15:30:36.160  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:30:36.160  6765  6830 I jxcore-log: 
08-30 15:30:36.161  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.161  6765  6830 I jxcore-log: 
08-30 15:30:36.161  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.161  6765  6830 I jxcore-log: 
,08-30 15:30:36.162  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 15:30:36.162  6765  6830 I jxcore-log: 
08-30 15:30:36.163  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:30:36.163  6765  6830 I jxcore-log: 
08-30 15:30:36.164  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 15:30:36.164  6765  6830 I jxcore-log: 
08-30 15:30:36.164  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.164  6765  6830 I jxcore-log: 
08-30 15:30:36.165  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.165  6765  6830 I jxcore-log: 
08-30 15:30:36.165  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.165  6765  6830 I jxcore-log: 
08-30 15:30:36.166  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.166  6765  6830 I jxcore-log: 
08-30 15:30:36.166  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.166  6765  6830 I jxcore-log: 
08-30 15:30:36.167  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.167  6765  6830 I jxcore-log: 
08-30 15:30:36.168  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.168  6765  6830 I jxcore-log: 
08-30 15:30:36.168  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 15:30:36.168  6765  6830 I jxcore-log: 
08-30 15:30:36.169  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:30:36.169  6765  6830 I jxcore-log: 
08-30 15:30:36.169  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 15:30:36.169  6765  6830 I jxcore-log: 
08-30 15:30:36.170  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.170  6765  6830 I jxcore-log: 
08-30 15:30:36.171  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.171  6765  6830 I jxcore-log: 
08-30 15:30:36.171  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.171  6765  6830 I jxcore-log: 
08-30 15:30:36.172  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.172  6765  6830 I jxcore-log: 
08-30 15:30:36.172  6765  6830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHer,e","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 15:30:36.172  6765  6830 I jxcore-log: 
,08-30 15:30:36.181  8140  8140 V Signer  : override build config not found
08-30 15:30:36.181  8140  8140 D Signer  : value of property debug is false
08-30 15:30:36.214  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-30 15:30:36.214  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-30 15:30:36.215  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-30 15:30:36.215  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-30 15:30:36.215  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-30 15:30:36.215  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,08-30 15:30:36.215  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-30 15:30:36.216  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-30 15:30:36.216  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-30 15:30:36.216  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-30 15:30:36.216  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-30 15:30:36.216  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-30 15:30:36.216  8140  8140 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-30 15:30:36.226  8140  8140 V LGMDMManager: Create singleton instance
08-30 15:30:36.251  1036  8164 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-30 15:30:36.256  1036  8164 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-30 15:30:36.257  1036  8164 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-30 15:30:36.257  1036  8164 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-30 15:30:36.257  1036  8164 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-30 15:30:36.257  1036  8164 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-30 15:30:36.257  1036  8164 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-30 15:30:36.257  1036  8164 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-30 15:30:36.258  1036  8164 D DhcpStateMachine: RunningState
08-30 15:30:36.270  8140  8140 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-30 15:30:36.314  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:36.321  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:36.322  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:36.341  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:36.354  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:36.354  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:36.355  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-30 15:30:36.358  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:36.358  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:36.362  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:30:36.367  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:30:36.372  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:36.372  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:36.374  6958  6958 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-30 15:30:36.376  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-30 15:30:36.378  6907  6907 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-30 15:30:36.440  8204  8204 D AndroidRuntime: 
08-30 15:30:36.440  8204  8204 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 15:30:36.443  8204  8204 D AndroidRuntime: CheckJNI is OFF
,08-30 15:30:36.486  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:36.486  8140  8207 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 15:30:36.494  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:36.497  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:30:36.502  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:36.507  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:36.507  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:36.507  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 15:30:36.510  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:36.510  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:36.517  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:36.521  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:36.525  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:36.525  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:36.526  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:36.528  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-30 15:30:36.528  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-30 15:30:36.528  6907  6907 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-30 15:30:36.528  6907  6907 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-30 15:30:36.528  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-30 15:30:36.530  6907  6907 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-30 15:30:36.530  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-30 15:30:36.530  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-30 15:30:36.530  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-30 15:30:36.530  6907  6907 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-30 15:30:36.530  6907  6907 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-30 15:30:36.530  6907  6907 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-30 15:30:36.533  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:36.533  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:36.537  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:36.545  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:36.548  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:36.549  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:36.549  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:36.551  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-30 15:30:36.554  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:36.556  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:36.560  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:36.565  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:36.565  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:36.565  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:36.567  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:36.568  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 15:30:36.573  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:30:36.577  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:36.581  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:36.581  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:36.581  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-30 15:30:36.582  1036  1941 I ActivityManager: Killing 7283:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-30 15:30:36.614  8204  8204 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 15:30:36.706  1036  2033 W libprocessgroup: failed to open /acct/uid_10005/pid_7283/cgroup.procs: No such file or directory
,08-30 15:30:36.710  1036  1111 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-30 15:30:36.711  1036  1111 I ActivityManager: Killing 6765:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-30 15:30:36.787  1036  2033 I WindowState: WIN DEATH: Window{2a5fb972 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 15:30:36.788  1036  1423 D WifiService: Client connection lost with reason: 4
,08-30 15:30:36.799  1036  2033 D InputDispatcher: Window went away: Window{2a5fb972 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 15:30:36.926  1036  1111 I ActivityManager:   Force finishing activity ActivityRecord{2366cd3f u0 com.test.thalitest/.MainActivity t6}
,08-30 15:30:36.952   343   350 E GBMv2   : DFP En is all cleared set to be enabled
,08-30 15:30:36.970  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-30 15:30:36.978  1036  1124 I ActivityManager:   Force finishing activity ActivityRecord{2366cd3f u0 com.test.thalitest/.MainActivity t6 f}
08-30 15:30:36.978  1036  1124 W ActivityManager: Duplicate finish request for ActivityRecord{2366cd3f u0 com.test.thalitest/.MainActivity t6 f}
,08-30 15:30:37.007  1036  1914 W ActivityManager: Spurious death for ProcessRecord{1d01055c 6765:com.test.thalitest/u0a118}, curProc for 6765: null
,08-30 15:30:37.021  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-30 15:30:37.031  1036  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 15:30:37.034  2507  2676 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 15:30:37.036  3756  3756 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-30 15:30:37.037  1996  1996 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-30 15:30:37.052  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-30 15:30:37.053  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-30 15:30:37.058  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-30 15:30:37.058  2034  2126 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-30 15:30:37.060  4524  4524 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 15:30:37.060  4524  4524 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 15:30:37.060  4524  4524 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 15:30:37.060  4524  4524 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-30 15:30:37.060  4524  4524 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 15:30:37.060  4524  4524 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 15:30:37.060  4524  4524 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 15:30:37.060  4524  4524 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-30 15:30:37.060  4524  4524 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 15:30:37.061  4524  4524 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 15:30:37.061  4524  4524 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-30 15:30:37.061  4524  4524 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-30 15:30:37.062  7697  7697 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-30 15:30:37.063  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-30 15:30:37.070  4628  4628 I art     : Explicit concurrent mark sweep GC freed 8204(470KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 998us total 83.030ms
,08-30 15:30:37.094  1036  1575 V SIM_STK : Menu title from STK is T-Mobile
,08-30 15:30:37.135  1942  2304 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-30 15:30:37.135  1942  2304 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15a36244 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 15:30:37.136  1942  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-30 15:30:37.136  1942  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{319bf2d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-30 15:30:37.144  1036  1036 D administrator: Handling package changes for user 0
08-30 15:30:37.147  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-30 15:30:37.148  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-30 15:30:37.149  3756  4516 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-30 15:30:37.154  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 15:30:37.156  1602  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 15:30:37.156  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.156  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-30 15:30:37.157  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-30 15:30:37.159  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-30 15:30:37.161  1817  8234 I CheckinService: active receiver: enabled
,08-30 15:30:37.181  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-30 15:30:37.181  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-30 15:30:37.182  1602  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 15:30:37.182  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.183  3756  3771 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 15:30:37.183  3756  4516 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-30 15:30:37.185  1817  8234 I CheckinService: Preparing to send checkin request
08-30 15:30:37.185  1817  8234 I EventLogService: Accumulating logs since 1472563818815
08-30 15:30:37.193  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-30 15:30:37.194  1602  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:30:37.194  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 15:30:37.196  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 15:30:37.196  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:30:37.196  1602  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 15:30:37.205  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 15:30:37.205  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , display: false
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , animation: false }
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , display: false
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , animation: false }
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , create_time: 1472216588858
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , display: false
08-30 15:30:37.209  2034  2034 I GBoardWebViewUtils: , animation: false }
,08-30 15:30:37.222  1602  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 15:30:37.223  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.227  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-30 15:30:37.228  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:30:37.228  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-30 15:30:37.229  1870  1870 D SplitUIService: removed split : 
08-30 15:30:37.232  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:30:37.232  1602  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-30 15:30:37.235  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:30:37.235  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:30:37.254  2034  8250 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-30 15:30:37.259  1602  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 15:30:37.259  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.265  8140  8207 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:37.265  8140  8207 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:30:37.266  1602  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:30:37.266  1602  1660 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 15:30:37.266  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 15:30:37.267  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 15:30:37.267  1602  1660 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-30 15:30:37.267  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-30 15:30:37.271  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:30:37.271  1602  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 15:30:37.272  1870  1870 D SplitUIManager: split_name #11 / not available #0
,08-30 15:30:37.272  1870  1870 I SplitUIService: split app #11
08-30 15:30:37.272  1602  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 15:30:37.273  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.288  1817  8234 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-30 15:30:37.290  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-30 15:30:37.290  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-30 15:30:37.293  1036  1392 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:30:37.293  1036  1392 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:30:37.293  1036  1392 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:30:37.294  1036  1392 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:30:37.294  1036  1392 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:30:37.294  1036  1960 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-30 15:30:37.294  1036  1392 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-30 15:30:37.295  7697  7697 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-30 15:30:37.295  1036  1442 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-30 15:30:37.296  1036  1442 D ConnectivityService: identical MTU - not setting
08-30 15:30:37.296  1036  1442 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-30 15:30:37.296  1036  1442 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-30 15:30:37.296  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 15:30:37.296  1036  1442 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:37.297  1036  1442 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-30 15:30:37.297  1602  1660 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 15:30:37.297  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.299  1036  1575 V SIM_STK : Menu title from STK is T-Mobile
08-30 15:30:37.308  1602  1834 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 15:30:37.323  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 15:30:37.323  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 15:30:37.325  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 15:30:37.326  1602  1660 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 15:30:37.327  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.328  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:30:37.328  1602  1660 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 15:30:37.329  1602  1660 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 15:30:37.329  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.329  1036  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-30 15:30:37.330  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:30:37.330  1602  1660 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 15:30:37.331  1036  1109 W InputMethodInfo: Duplicated subtype definition found: , voice
08-30 15:30:37.331  1602  1660 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 15:30:37.331  1602  1660 D KeyguardModel: createShortcutInfo...
08-30 15:30:37.333  1602  1660 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 15:30:37.333  1602  1660 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 15:30:37.334  1602  1660 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 15:30:37.334  1602  1660 D KeyguardModel: createShortcutInfo...
,08-30 15:30:37.338  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-30 15:30:37.351  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-30 15:30:37.351  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-30 15:30:37.368  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:37.368  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:37.376  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:30:37.379   336   428 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-30 15:30:37.380  3207  8254 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-30 15:30:37.383  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-30 15:30:37.387  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:37.387  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:37.388  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:37.391  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:37.391  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-30 15:30:37.397  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:37.402  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:37.405  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:37.405  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:37.406  6958  6958 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-30 15:30:37.409  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:37.410  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:37.412  8090  8090 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 15:30:37.417  8090  8090 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:37.421  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-30 15:30:37.431  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:37.444  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-30 15:30:37.446  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:37.446  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:37.447  6958  6958 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 15:30:37.447  6958  6958 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-30 15:30:37.447  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:30:37.447  6958  6958 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 15:30:37.449  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-30 15:30:37.450  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-30 15:30:37.451  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-30 15:30:37.451  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-30 15:30:37.451  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:37.452  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-30 15:30:37.456  8090  8090 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-30 15:30:37.456  8090  8090 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-30 15:30:37.461  6907  6907 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-30 15:30:37.464  8140  8207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-30 15:30:37.465  6907  6907 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-30 15:30:37.470  6958  6958 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-30 15:30:37.470  6958  6958 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-30 15:30:37.470  6958  6958 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-30 15:30:37.471  6958  6958 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-30 15:30:37.471  6958  6958 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-30 15:30:37.474  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:30:37.475  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:30:37.476  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-30 15:30:37.476  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:30:37.476  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:30:37.476  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{15c441d1 u0 com.lge.launcher2/.Launcher t5} time:224347
08-30 15:30:37.477  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:30:37.478  2034  2209 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-30 15:30:37.478  2034  2209 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-30 15:30:37.478  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:30:37.480  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:30:37.482  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-30 15:30:37.482  8140  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-30 15:30:37.483  8140  8140 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-30 15:30:37.483  8140  8208 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-30 15:30:37.486  8140  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-30 15:30:37.486  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 15:30:37.489  8140  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-30 15:30:37.490  8140  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-30 15:30:37.490  8140  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-30 15:30:37.490  8140  8207 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-30 15:30:37.491  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-30 15:30:37.492  8140  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-30 15:30:37.492  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 15:30:37.492  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:30:37.493  1036  1124 I art     : Explicit concurrent mark sweep GC freed 84825(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.719ms total 285.451ms
08-30 15:30:37.495  8140  8207 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-30 15:30:37.500  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-30 15:30:37.508  1036  2017 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8260 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-30 15:30:37.509  2569  2569 D [Concierge]Service: onStartCommand(). Type : 8
08-30 15:30:37.509  2569  2569 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-30 15:30:37.510  2569  2569 D [Concierge]Service: Update widget ID : 11
08-30 15:30:37.512  2034  2034 D [Concierge]WidgetView: change position of spinner
08-30 15:30:37.513  2210  2210 I ConfigService: onCreate
08-30 15:30:37.513  2210  2210 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 15:30:37.514  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1472563837514
08-30 15:30:37.515  2569  2569 D [Concierge]Service: onStartCommand(). Type : 0
08-30 15:30:37.517  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 15:30:37.518  2210  2210 I ConfigService: onBind returning update interface
08-30 15:30:37.519  2210  2210 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 15:30:37.519  2210  2210 I ConfigService: onBind returning config service
,08-30 15:30:37.543  2210  2210 I ConfigService: onDestroy
,08-30 15:30:37.545  1817  8278 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 15:30:37.549  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 831211356
08-30 15:30:37.549  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-30 15:30:37.550  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 15:30:37.551  8260  8260 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 15:30:37.551  8260  8260 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-30 15:30:37.552  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1bb49829
08-30 15:30:37.552  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-30 15:30:37.554  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-30 15:30:37.554  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:30:37.563  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-30 15:30:37.564  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-30 15:30:37.564  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-30 15:30:37.565  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472563641259, New one : 1472563837514
08-30 15:30:37.565  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-30 15:30:37.565  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-30 15:30:37.567  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:30:37.568  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-30 15:30:37.570  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-30 15:30:37.571  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-30 15:30:37.572  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-30 15:30:37.573  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-30 15:30:37.574  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:30:37.574  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-30 15:30:37.575  5959  8284 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 15:30:37.580  1817  8285 I PeopleContactsSync: CP2 sync disabled
08-30 15:30:37.592  8260  8260 I MultiDex: VM with version 2.1.0 has multidex support
08-30 15:30:37.592  8260  8260 I MultiDex: install
08-30 15:30:37.592  8260  8260 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 15:30:37.595  1817  8283 W GmsApplication: Using Auth Proxy for data requests.
08-30 15:30:37.599  1817  8283 W GmsApplication: Using Auth Proxy for data requests.
,08-30 15:30:37.612  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-30 15:30:37.619  1817  4793 I Icing   : doRemovePackageData com.test.thalitest
08-30 15:30:37.619  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 15:30:37.619  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-30 15:30:37.621  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-30 15:30:37.623  2210  6564 I art     : Explicit concurrent mark sweep GC freed 7837(453KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 706us total 18.887ms
08-30 15:30:37.628  8260  8260 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-30 15:30:37.643  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3276ea11 time:224514
,08-30 15:30:37.661  8204  8204 D AndroidRuntime: Shutting down VM
,08-30 15:30:37.694  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8291 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 15:30:37.696  7087  7087 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 15:30:37.720  2308  8308 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 15:30:37.745  1036  1052 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8309 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-30 15:30:37.748  1036  1109 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 15:30:37.757  1036  1109 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-30 15:30:37.765  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 15:30:37.779  1036  2017 I ActivityManager: Killing 7741:com.google.android.talk/u0a72 (adj 15): empty #17
,08-30 15:30:37.826  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-30 15:30:37.853  1036  1914 W libprocessgroup: failed to open /acct/uid_10072/pid_7741/cgroup.procs: No such file or directory
08-30 15:30:37.866  8309  8309 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 15:30:37.866  8309  8309 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 15:30:37.867  8309  8309 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 15:30:37.867  8309  8309 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-30 15:30:37.871  2034  2870 I GBoardtInterface: onReloaded()
08-30 15:30:37.872  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-30 15:30:37.873  3756  3771 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 15:30:37.876  3756  3772 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 15:30:37.881  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-30 15:30:37.882  3756  4516 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 15:30:37.882  3756  4516 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 15:30:37.885  1905  1905 D ActionManagerService: notifyUserLog: 1000001
,08-30 15:30:37.886  3756  4516 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-30 15:30:37.886  3756  4516 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-30 15:30:37.886  3756  4516 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-30 15:30:37.887  3756  4516 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-30 15:30:37.887  3756  3771 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-30 15:30:37.889  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-30 15:30:37.889  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-30 15:30:37.890  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-30 15:30:37.890  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-30 15:30:37.892  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-30 15:30:37.892  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-30 15:30:37.905  8260  8276 D LgDataFeature: LgDataFeature() Constructor: none
,08-30 15:30:37.905  8260  8276 D LgDataFeature: LgDataFeature() Constructor Done, null
08-30 15:30:37.926  8309  8309 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 15:30:37.934  8309  8309 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-30 15:30:37.956  8309  8309 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 15:30:37.976   343   352 E GBMv2   : DFP En is all cleared set to be enabled
08-30 15:30:37.976  8309  8309 D LgDataFeature: LgDataFeature() Constructor: none
08-30 15:30:37.976   343   352 E GBMv2   : Set value is all cleared set the max
08-30 15:30:37.976   343   352 I GBMv2   : DFP Enabled. Ignore VFP set
08-30 15:30:37.976  8309  8309 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-30 15:30:38.024  8260  8276 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/app_fb): android.system.ErrnoException: chmod failed: ENOENT (No such file or directory)
08-30 15:30:38.026  8309  8309 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
