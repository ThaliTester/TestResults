#### Test 82337235c858ce8_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 15:44:50.093  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-23 15:44:50.093  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-23 15:44:50.118  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
08-23 15:44:50.118  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
--------- beginning of system
08-23 15:44:50.120  1942  2108 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-23 15:44:50.120  1942  2108 D LEDHandler: Battery Level Remaining: 100%
08-23 15:44:50.120  1942  2108 D LEDHandler: Battery Temp: 283, mChargingStatus=5, mChargingStop=false
08-23 15:44:50.122  1035  1543 D WifiController: battery changed pluggedType: 2
08-23 15:44:50.123  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-23 15:44:50.126  1035  1035 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 15:44:50.126  1035  1035 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 15:44:50.127  3821  3945 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-23 15:44:50.133  6635  6635 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-23 15:44:50.389  6739  6739 D AndroidRuntime: 
08-23 15:44:50.389  6739  6739 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 15:44:50.392  6739  6739 D AndroidRuntime: CheckJNI is OFF
08-23 15:44:50.518  6739  6739 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 15:44:50.523  1035  2014 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 15:44:50.532  1942  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 15:44:50.536  1035  2014 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 15:44:50.537  1035  2014 D ActivityManager: setTaskToReturnTo : TaskRecord{13def9af #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 15:44:50.537  1035  2014 D ActivityManager: setTaskToReturnTo : TaskRecord{13def9af #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 15:44:50.538  1035  2014 D WindowStateEx: AppWindowTokenEx init.. 
08-23 15:44:50.538   342   355 E GBMv2   : DFP En is all cleared set to be enabled
08-23 15:44:50.579  1035  2014 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6759 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 15:44:50.581  6739  6739 D AndroidRuntime: Shutting down VM
08-23 15:44:50.624  1942  3918 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 15:44:50.625  1942  3918 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1c5d2e30 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 15:44:50.625  1942  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 15:44:50.625  1942  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{20df7aa9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 15:44:50.678  6759  6759 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 15:44:50.747  6759  6759 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-23 15:44:50.754  6759  6759 I LibraryLoader: Loading: webviewchromium
08-23 15:44:50.757  6759  6759 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9185-9188)
08-23 15:44:50.757  6759  6759 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 15:44:50.773  6759  6759 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1602835e}
08-23 15:44:50.774  6759  6759 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 15:44:50.774  6759  6759 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 15:44:50.782  6759  6759 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 15:44:50.783  6759  6759 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:44:50.792  6759  6759 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-23 15:44:50.793  6759  6759 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-23 15:44:50.799  6759  6759 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-23 15:44:50.808   326  2138 V AudioPolicyService: registerClient() client 0xb1054ce0, uid 10118
08-23 15:44:50.812  6759  6759 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 15:44:50.812  6759  6759 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 15:44:50.812  6759  6759 I Adreno-EGL: Build Date: 12/12/14 금
08-23 15:44:50.812  6759  6759 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 15:44:50.812  6759  6759 I Adreno-EGL: Remote Branch: 
08-23 15:44:50.812  6759  6759 I Adreno-EGL: Local Patches: 
08-23 15:44:50.812  6759  6759 I Adreno-EGL: Reconstruct Branch: 
,08-23 15:44:50.821  1035  1111 D BluetoothManagerService: Message: 20
08-23 15:44:50.821  1035  1111 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c3e70c1:true
08-23 15:44:50.880  6759  6795 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-23 15:44:50.882  6759  6759 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-23 15:44:50.897  6759  6759 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:44:50.901  6759  6759 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 15:44:50.904  6759  6759 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 15:44:50.906  6759  6759 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 15:44:50.906  6759  6759 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-23 15:44:50.919  6759  6759 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-23 15:44:50.924  6759  6759 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:44:50.924  6759  6759 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:44:50.964  6759  6810 D OpenGLRenderer: Render dirty regions requested: true
08-23 15:44:50.964  6759  6810 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 15:44:50.975  6759  6810 D OpenGLRenderer: Enabling debug mode 0
,08-23 15:44:50.986  6759  6759 D Atlas   : Validating map...
08-23 15:44:50.990  1035  1996 D SplitWindow: check instance of lgWin Window{2aef9f33 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 15:44:51.053  6759  6805 D LgDataFeature: LgDataFeature() Constructor: none
,08-23 15:44:51.053  6759  6805 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 15:44:51.115  1035  1112 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +492ms (total +577ms)
08-23 15:44:51.116  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{325dd1bc u0 com.test.thalitest/.MainActivity t6} time:189547
08-23 15:44:51.116  6759  6759 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2612f9c5 time:189547
,08-23 15:44:51.216  6759  6759 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 15:44:51.369  6759  6821 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,08-23 15:44:51.390  6759  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 15:44:51.390  6759  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 15:44:51.390  6759  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 15:44:51.390  6759  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 15:44:51.390  6759  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 15:44:51.390  6759  6821 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c628379 added. We now have 1 listener(s)
08-23 15:44:51.401  1035  1051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 15:44:51.404  6759  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-23 15:44:51.405  6759  6821 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 15:44:51.407  6759  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 15:44:51.407  6759  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 15:44:51.415  6759  6821 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@134cf86c added. We now have 1 listener(s)
,08-23 15:44:51.416  6759  6821 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 15:44:51.420  1035  1543 D WifiService: New client listening to asynchronous messages
08-23 15:44:51.424  6759  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 15:44:51.424  6759  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 15:44:51.425  6759  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 15:44:51.425  6759  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 15:44:51.425  6759  6821 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 15:44:51.430  6759  6821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 15:44:51.430  1035  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 15:44:51.431  6759  6821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 15:44:51.442  6759  6821 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 15:44:51.443  6759  6821 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:44:51.443  6759  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:44:51.443  6759  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 15:44:51.443  6759  6821 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:44:51.443  6759  6821 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:44:51.443  6759  6821 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:44:51.443  6759  6821 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:44:51.443  6759  6821 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 15:44:51.443  6759  6821 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 15:44:51.443  6759  6821 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 15:44:51.446  6759  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 15:44:51.448  6759  6759 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 15:44:51.449  6759  6821 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 15:44:51.491  6759  6805 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 15:44:51.491  6759  6805 I chromium: 
,08-23 15:44:51.554  6759  6759 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 15:44:51.631  6759  6759 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 15:44:51.631  6759  6759 I chromium: 
,08-23 15:44:52.256  6759  6824 W jxcore-log: Initializing JXcore engine
08-23 15:44:52.256  6759  6824 W jxcore-log: JXcore engine is ready
,08-23 15:44:52.296  6824  6824 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8360]" dev="sockfs" ino=8360 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 15:44:52.296  6824  6824 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 15:44:52.296  6824  6824 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10617]" dev="sockfs" ino=10617 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 15:44:52.296  6824  6824 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-23 15:44:52.296  6824  6824 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[29362]" dev="sockfs" ino=29362 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-23 15:44:52.314  6759  6824 W jxcore-log: Starting JXcore engine
08-23 15:44:52.392  6759  6824 W jxcore-log: Platform android
08-23 15:44:52.392  6759  6824 W jxcore-log: 
08-23 15:44:52.392  6759  6824 W jxcore-log: Process ARCH arm
08-23 15:44:52.392  6759  6824 W jxcore-log: 
,08-23 15:44:52.521   342   358 E GBMv2   : DFP En is all cleared set to be enabled
08-23 15:44:52.522   342   358 E GBMv2   : Set value is all cleared set the max
08-23 15:44:52.522   342   358 I GBMv2   : DFP Enabled. Ignore VFP set
,08-23 15:44:52.577  6759  6824 I jxcore-log: JXcore Cordova bridge is ready!
08-23 15:44:52.577  6759  6824 I jxcore-log: 
08-23 15:44:52.577  6759  6824 W jxcore-log: JXcore engine is started
,08-23 15:44:52.590  6759  6821 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 15:44:52.610  6759  6759 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 15:45:00.058  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 15:45:00.058  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 15:45:00.058  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-23 15:45:00.063  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-23 15:45:00.066  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 15:45:00.066  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-23 15:45:00.068  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-23 15:45:00.069  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 15:45:01.118  1035  1386 D PowerManagerServiceEx: acquireWakeLockInternal: lock=368949111, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,08-23 15:45:01.157  1035  1092 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6833 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-23 15:45:01.184  2592  2592 D [Concierge]Service: onStartCommand(). Type : 9
,08-23 15:45:01.292  6833  6833 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-23 15:45:01.297  6833  6833 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2dbb4be3
08-23 15:45:01.297  1035  1035 D PowerManagerServiceEx: releaseWakeLockInternal: lock=368949111 [*alarm*], flags=0x0
08-23 15:45:01.297  1035  2034 I ActivityManager: Killing 6213:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-23 15:45:01.413  1035  1574 W libprocessgroup: failed to open /acct/uid_10014/pid_6213/cgroup.procs: No such file or directory
,08-23 15:45:03.335  6759  6824 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 15:45:03.335  6759  6824 I jxcore-log: 
,08-23 15:45:05.121  6759  6824 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 15:45:05.121  6759  6824 I jxcore-log: 
,08-23 15:45:05.152  6759  6824 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 15:45:05.152  6759  6824 I jxcore-log: 
,08-23 15:45:05.170  6759  6824 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 15:45:05.170  6759  6824 I jxcore-log: 
,08-23 15:45:05.193  6759  6824 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 15:45:05.193  6759  6824 I jxcore-log: 
,08-23 15:45:05.197  6759  6824 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 15:45:05.197  6759  6824 I jxcore-log: 
08-23 15:45:07.992  6759  6824 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 15:45:07.992  6759  6824 I jxcore-log: 
08-23 15:45:07.996  6759  6824 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 15:45:07.996  6759  6824 I jxcore-log: 
,08-23 15:45:07.999  6759  6824 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:45:07.999  6759  6824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:45:07.999  6759  6824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 15:45:07.999  6759  6824 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:45:07.999  6759  6824 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:45:07.999  6759  6824 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:45:07.999  6759  6824 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:45:07.999  6759  6824 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 15:45:08.001  6759  6824 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 15:45:08.003  6759  6824 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 15:45:08.003  6759  6824 I jxcore-log: 
,08-23 15:45:08.005  6759  6824 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 15:45:08.005  6759  6824 I jxcore-log: 
08-23 15:45:11.650  6759  6824 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 15:45:11.650  6759  6824 I jxcore-log: 
,08-23 15:45:11.777  6759  6824 I jxcore-log: ERROR runTests: 
08-23 15:45:11.777  6759  6824 I jxcore-log: 
,08-23 15:45:11.780  6759  6824 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'
08-23 15:45:11.780  6759  6824 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-23 15:45:11.786  6759  6824 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 15:45:11.786  6759  6824 I jxcore-log: 
08-23 15:45:11.792  6759  6759 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\nError: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\n    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-23 15:45:11.792  6759  6759 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 15:45:11.799  1035  1778 I ActivityManager: Killing 6340:com.android.defcontainer/u0a4 (adj 15): empty #17
08-23 15:45:11.816  1035  1976 W libprocessgroup: failed to open /acct/uid_10004/pid_6340/cgroup.procs: No such file or directory
,08-23 15:45:11.818  6759  6759 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 15:45:11.818  6759  6759 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 15:45:11.818  6759  6759 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 15:45:11.818  6759  6759 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 15:45:11.818  6759  6759 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 15:45:11.818  6759  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 15:45:11.819  6759  6759 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c628379 removed from the list
08-23 15:45:11.819  6759  6759 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 15:45:11.819  6759  6759 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@134cf86c removed from the list
08-23 15:45:11.819  6759  6759 D io.jxcore.node.ConnectivityMonitor: stop
08-23 15:45:11.819  6759  6759 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 15:45:11.820  6759  6821 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 15:45:11.836   342   355 E GBMv2   : DFP En is all cleared set to be enabled
08-23 15:45:11.840  1942  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-23 15:45:11.841  1942  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e3ce82e co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 15:45:11.842  6759  6759 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 15:45:11.844  1942  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-23 15:45:11.845  1942  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{30410fcf co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 15:45:11.847  6759  6759 W ScreenOrientationListener: Removing an inexistent observer!
08-23 15:45:11.856  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-23 15:45:11.858  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-23 15:45:11.860  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-23 15:45:11.861  2035  2128 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-23 15:45:11.871  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-23 15:45:11.873  1905  1905 D ActionManagerService: notifyUserLog: 1000003
08-23 15:45:11.874  3769  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-23 15:45:12.008  1035  1778 I art     : Explicit concurrent mark sweep GC freed 30337(1426KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.807ms total 133.560ms
,08-23 15:45:12.010  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 15:45:12.015  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-23 15:45:12.018  1035  1976 D InputDispatcher: Window went away: Window{2aef9f33 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 15:45:12.036  1035  1092 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6879 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 15:45:12.036  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-23 15:45:12.050  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-23 15:45:12.051  3769  3786 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , display: false
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , display: false
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , create_time: 1471602816196
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , display: false
08-23 15:45:12.054  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 15:45:12.057  2035  6895 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-23 15:45:12.059  1905  1905 D ActionManagerService: notifyUserLog: 1000004
08-23 15:45:12.059  3769  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-23 15:45:12.070  6867  6867 D AndroidRuntime: 
08-23 15:45:12.070  6867  6867 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 15:45:12.073  6867  6867 D AndroidRuntime: CheckJNI is OFF
,08-23 15:45:12.085  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-23 15:45:12.094  6879  6879 I art     : Almond Protected OAT
,08-23 15:45:12.128  6879  6879 D WeatherApplication: removeAccount
,08-23 15:45:12.129  6879  6879 D WeatherApplication: Account.length = 0
08-23 15:45:12.129  6879  6879 E WeatherApplication: OPERATOR:OPEN
08-23 15:45:12.132  6879  6879 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:45:12
08-23 15:45:12.134  6879  6879 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 15:45:12.134  6879  6879 D Weather.Utils: 2 : All the weather widget is gone.
08-23 15:45:12.140  6879  6879 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 15:45:12.141  6879  6879 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 15:45:12.141  6879  6879 D Weather.Utils: 2 : All the weather widget is gone.
08-23 15:45:12.142  6879  6879 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:45:12
,08-23 15:45:12.143  1035  2034 I ActivityManager: Killing 6488:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-23 15:45:12.180  6867  6867 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 15:45:12.221  1035  1949 W libprocessgroup: failed to open /acct/uid_10008/pid_6488/cgroup.procs: No such file or directory
,08-23 15:45:12.226  1035  1092 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-23 15:45:12.227  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-23 15:45:12.227  1035  1092 I ActivityManager: Killing 6759:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
,08-23 15:45:12.298  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-23 15:45:12.301  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 15:45:12.303  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 15:45:12.304  1035  1543 D WifiService: Client connection lost with reason: 4
08-23 15:45:12.304  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-23 15:45:12.306  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 15:45:12.306  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 15:45:12.329  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-23 15:45:12.329  2035  2225 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 15:45:12.329  2035  2225 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-23 15:45:12.329  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 15:45:12.360  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-23 15:45:12.361  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 15:45:12.362  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 15:45:12.374  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-23 15:45:12.449  1035  1887 W ActivityManager: Spurious death for ProcessRecord{25fcd4b4 6759:com.test.thalitest/u0a118}, curProc for 6759: null
,08-23 15:45:12.453  2592  2592 D [Concierge]Service: onStartCommand(). Type : 8
08-23 15:45:12.453  2592  2592 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-23 15:45:12.454  1035  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-23 15:45:12.457  2592  2592 D [Concierge]Service: Update widget ID : 11
,08-23 15:45:12.471  2035  2035 D [Concierge]WidgetView: change position of spinner
,08-23 15:45:12.477  1035  1112 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a5dbf45 u0 com.lge.launcher2/.Launcher t5} time:210908
08-23 15:45:12.481  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1471959912481
08-23 15:45:12.482  2592  2592 D [Concierge]Service: onStartCommand(). Type : 0
,08-23 15:45:12.486  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-23 15:45:12.498  2483  2644 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 15:45:12.498  1997  1997 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 15:45:12.499  3769  3769 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-23 15:45:12.499  3821  3821 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-23 15:45:12.499  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-23 15:45:12.525  4590  4590 I art     : Explicit concurrent mark sweep GC freed 459(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 493us total 58.198ms
,08-23 15:45:12.527  1035  1455 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 15:45:12.539  1035  1923 V SIM_STK : Menu title from STK is T-Mobile
,08-23 15:45:12.553  6451  6451 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-23 15:45:12.559  1035  1091 W InputMethodInfo: Duplicated subtype definition found: , voice
08-23 15:45:12.563  4465  4465 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 15:45:12.563  4465  4465 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 15:45:12.563  4465  4465 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 15:45:12.563  4465  4465 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-23 15:45:12.563  4465  4465 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:45:12.563  4465  4465 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:45:12.563  4465  4465 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 15:45:12.563  4465  4465 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 15:45:12.563  4465  4465 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:45:12.563  4465  4465 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:45:12.563  4465  4465 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 15:45:12.563  4465  4465 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 15:45:12.570  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-23 15:45:12.576  1817  1817 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-23 15:45:12.595  1035  1035 D administrator: Handling package changes for user 0
,08-23 15:45:12.597  1602  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 15:45:12.597  1602  1663 D KeyguardModel: createShortcutInfo...
08-23 15:45:12.606  1602  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 15:45:12.606  1602  1663 D KeyguardModel: createShortcutInfo...
,08-23 15:45:12.612  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 15:45:12.613  1602  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:45:12.613  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 15:45:12.614  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 15:45:12.616  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 15:45:12.616  1602  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 15:45:12.617  1602  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 15:45:12.617  1602  1663 D KeyguardModel: createShortcutInfo...
,08-23 15:45:12.618  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-23 15:45:12.619  1870  1870 D SplitUIService: removed split : 
,08-23 15:45:12.632  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-23 15:45:12.632  1602  1602 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-23 15:45:12.636  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 15:45:12.636  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 15:45:12.637  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 15:45:12.637  1602  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 15:45:12.638  1602  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 15:45:12.638  1602  1663 D KeyguardModel: createShortcutInfo...
08-23 15:45:12.639  2215  2215 I ConfigService: onCreate
08-23 15:45:12.640  2215  2215 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-23 15:45:12.641  1817  1817 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 15:45:12.644  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 326554269
08-23 15:45:12.644  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-23 15:45:12.645  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 15:45:12.645  1602  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:45:12.645  1602  1663 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 15:45:12.645  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 15:45:12.645  1602  1663 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-23 15:45:12.647  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@29c71ef4
08-23 15:45:12.648  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-23 15:45:12.648  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 15:45:12.648  1602  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 15:45:12.652  1035  2034 V SIM_STK : Menu title from STK is T-Mobile
08-23 15:45:12.652  1035  2034 V SIM_STK : Menu title from STK is T-Mobile
08-23 15:45:12.653  2215  2215 I ConfigService: onBind returning update interface
08-23 15:45:12.656  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 15:45:12.656  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 15:45:12.656  2215  2215 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 15:45:12.656  2215  2215 I ConfigService: onBind returning config service
08-23 15:45:12.660  1602  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 15:45:12.660  1602  1663 D KeyguardModel: createShortcutInfo...
,08-23 15:45:12.666  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 15:45:12.667  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-23 15:45:12.667  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 15:45:12.667  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-23 15:45:12.668  1817  6917 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 15:45:12.668  2215  2215 I ConfigService: onDestroy
08-23 15:45:12.669  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 15:45:12.670  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-23 15:45:12.670  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 15:45:12.671  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471959729899, New one : 1471959912481
08-23 15:45:12.671  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-23 15:45:12.671  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 15:45:12.671  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-23 15:45:12.671  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 15:45:12.673  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-23 15:45:12.675  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-23 15:45:12.676  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-23 15:45:12.677  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-23 15:45:12.679  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-23 15:45:12.687  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-23 15:45:12.687  1870  1870 I SplitUIService: split app #11
08-23 15:45:12.688  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 15:45:12.689  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 15:45:12.703  1602  1663 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 15:45:12.703  1602  1663 D KeyguardModel: createShortcutInfo...
08-23 15:45:12.705  1035  1778 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-23 15:45:12.705  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-23 15:45:12.705  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 15:45:12.706  3821  3821 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 15:45:12.706  1602  1663 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 15:45:12.706  1602  1663 D KeyguardModel: createShortcutInfo...
08-23 15:45:12.707  5925  6921 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-23 15:45:12.708  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 15:45:12.708  1602  1663 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 15:45:12.709  1602  1663 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 15:45:12.709  1602  1663 D KeyguardModel: createShortcutInfo...
08-23 15:45:12.711  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 15:45:12.711  1602  1663 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 15:45:12.712  1602  1663 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 15:45:12.712  1602  1663 D KeyguardModel: createShortcutInfo...
08-23 15:45:12.713  1602  1663 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 15:45:12.713  1602  1663 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 15:45:12.714  1602  1663 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 15:45:12.714  1602  1663 D KeyguardModel: createShortcutInfo...
08-23 15:45:12.720  1035  1052 V SIM_STK : Menu title from STK is T-Mobile
,08-23 15:45:12.734  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created,
08-23 15:45:12.734  1817  6924 I PeopleContactsSync: CP2 sync disabled
08-23 15:45:12.747  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 15:45:12.747  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-23 15:45:12.749  1817  4654 I Icing   : doRemovePackageData com.test.thalitest
,08-23 15:45:12.749  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 15:45:12.777  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10bfeace time:211208
08-23 15:45:12.777  5992  5992 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-23 15:45:12.778  1602  1602 D KeyguardModel: handleShortcutListChanged...
08-23 15:45:12.778  1602  1602 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-23 15:45:12.784  1817  6923 W GmsApplication: Using Auth Proxy for data requests.
,08-23 15:45:12.801  6535  6535 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-23 15:45:12.810  1817  6923 W GmsApplication: Using Auth Proxy for data requests.
08-23 15:45:12.812   336   424 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-23 15:45:12.813  3260  6928 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-23 15:45:12.803  2339  6927 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 15:45:12.842  1997  1997 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 15:45:12.842  1997  1997 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-23 15:45:12.843  1997  1997 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-23 15:45:12.848  6451  6451 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 15:45:12.858  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-23 15:45:12.858  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 15:45:12.859  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 15:45:12.880  1035  1996 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6930 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-23 15:45:12.885  1035  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-23 15:45:12.901  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-23 15:45:12.942  2035  2879 I GBoardtInterface: onReloaded()
,08-23 15:45:12.944  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-23 15:45:12.945  3769  3786 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 15:45:12.947  3769  3785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 15:45:12.950  1035  1091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:45:12.954  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-23 15:45:12.954  3769  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 15:45:12.955  3769  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-23 15:45:12.957  1035  1091 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-23 15:45:12.957  1905  1905 D ActionManagerService: notifyUserLog: 1000001
08-23 15:45:12.958  3769  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 15:45:12.958  3769  4489 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 15:45:12.958  3769  4489 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-23 15:45:12.958  3769  4489 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-23 15:45:12.959  3769  3786 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 15:45:12.961  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-23 15:45:12.961  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-23 15:45:12.963  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-23 15:45:12.963  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 15:45:12.965  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-23 15:45:12.965  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 15:45:12.967  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-23 15:45:12.971  6930  6930 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 15:45:12.972  6930  6930 W LG Account v2.2: No ProfileInfo entries
08-23 15:45:12.972  6930  6930 I LG Account v2.2: isEnabled: false
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Country: EU
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Operator: OPEN
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Ranking support: false
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Comfort support: false
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Accessory: true
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Health device: true
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Extra Pedometer: false
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Blood glucose device: false
08-23 15:45:12.972  6930  6930 I Feature : [Lifetracker]Device Number: 3
08-23 15:45:12.973  6930  6930 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-23 15:45:12.988  1035  1124 I art     : Explicit concurrent mark sweep GC freed 24289(1734KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.458ms total 406.155ms
,08-23 15:45:13.008  1035  1650 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6950 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 15:45:13.012   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 881us total 9.841ms
08-23 15:45:13.021   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 188us total 8.989ms
,08-23 15:45:13.031  6867  6867 D AndroidRuntime: Shutting down VM
08-23 15:45:13.032   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 9.304ms
,08-23 15:45:13.053  6950  6950 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 15:45:13.053  6950  6950 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-23 15:45:13.053  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 15:45:13.053  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-23 15:45:13.054  6950  6950 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 15:45:13.054  6950  6950 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 15:45:13.074  1035  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6967 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 15:45:13.114  1035  1923 I ActivityManager: Killing 6576:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-23 15:45:13.137  6950  6950 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-23 15:45:13.181  1035  1949 W libprocessgroup: failed to open /acct/uid_10061/pid_6576/cgroup.procs: No such file or directory
,08-23 15:45:13.198  6950  6950 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-23 15:45:13.198  6950  6950 D HideNavigationAppsReceiver: replacing : false
,08-23 15:45:13.200  6950  6950 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-23 15:45:13.201  6950  6950 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-23 15:45:13.202  6950  6950 D ButtonCombinationReceiver: replacing : false
08-23 15:45:13.206  1035  2014 I ActivityManager: Killing 6128:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-23 15:45:13.244  2035  2879 I GBoardtInterface: exportHTML()
,08-23 15:45:13.270  2035  2879 I GBoardtInterface: exportHTML()
,08-23 15:45:13.290  1035  1778 W libprocessgroup: failed to open /acct/uid_10097/pid_6128/cgroup.procs: No such file or directory
,08-23 15:45:13.294  4590  6985 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 15:45:13.297  2035  2879 I GBoardtInterface: exportHTML()
08-23 15:45:13.318  1035  2033 V SIM_STK : Menu title from STK is T-Mobile
,08-23 15:45:13.327  1035  2053 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6987 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 15:45:13.377  4590  6985 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 84 ms] updated apps [took 84 ms] 
,08-23 15:45:13.385  6987  6987 D DocsApplication: Installing DEX configuration.
08-23 15:45:13.388  6987  6987 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-23 15:45:13.390  6987  6987 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{198e5a74 com.google.android.apps.docs}

```
