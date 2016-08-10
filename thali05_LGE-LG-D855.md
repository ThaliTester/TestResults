#### Test 797510157a5d8bb_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-10 07:40:00.072  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 07:40:00.076  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 07:40:00.077  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
08-10 07:40:00.084  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 07:40:00.084  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-10 07:40:00.084  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-10 07:40:00.085  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
,08-10 07:40:44.044  6940  6940 D AndroidRuntime: 
08-10 07:40:44.044  6940  6940 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-10 07:40:44.047  6940  6940 D AndroidRuntime: CheckJNI is OFF
08-10 07:40:44.163  6940  6940 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 07:40:44.168  1037  1925 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 07:40:44.195  1944  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-10 07:40:44.199  1037  1925 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-10 07:40:44.200  1037  1925 D ActivityManager: setTaskToReturnTo : TaskRecord{5d8d376 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 07:40:44.200  1037  1925 D ActivityManager: setTaskToReturnTo : TaskRecord{5d8d376 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 07:40:44.201  1037  1925 D WindowStateEx: AppWindowTokenEx init.. 
08-10 07:40:44.202   339   364 E GBMv2   : DFP En is all cleared set to be enabled
08-10 07:40:44.221  1037  1925 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6960 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-10 07:40:44.222  6940  6940 D AndroidRuntime: Shutting down VM
08-10 07:40:44.247  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 07:40:44.247  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
08-10 07:40:44.254  1037  1546 D WifiController: battery changed pluggedType: 2
08-10 07:40:44.255  1944  2103 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 07:40:44.255  1944  2103 D LEDHandler: Battery Level Remaining: 100%
08-10 07:40:44.255  1944  2103 D LEDHandler: Battery Temp: 279, mChargingStatus=5, mChargingStop=false
08-10 07:40:44.256  1605  1605 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
08-10 07:40:44.256  1605  1605 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-10 07:40:44.258  1605  1605 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-10 07:40:44.259  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:40:44.259  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:40:44.261  4186  4332 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 07:40:44.263  6821  6821 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-10 07:40:44.283  1944  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-10 07:40:44.283  1944  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{8f6d6f4 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
08-10 07:40:44.285  1944  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-10 07:40:44.285  1944  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3b500e1d co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
08-10 07:40:44.328  6960  6960 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-10 07:40:44.433  6960  6960 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 07:40:44.443  6960  6960 I LibraryLoader: Loading: webviewchromium
08-10 07:40:44.446  6960  6960 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5700-5704)
,08-10 07:40:44.447  6960  6960 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 07:40:44.464  6960  6960 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7297cc2}
,08-10 07:40:44.465  6960  6960 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 07:40:44.465  6960  6960 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 07:40:44.474  6960  6960 I BrowserStartupController: Initializing chromium process, renderers=0
08-10 07:40:44.475  6960  6960 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 07:40:44.487  6960  6960 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-10 07:40:44.487  6960  6960 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-10 07:40:44.487  6960  6960 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-10 07:40:44.489   315   315 V AudioPolicyService: registerClient() client 0xb558ae00, uid 10118
08-10 07:40:44.498  1037  1119 D BluetoothManagerService: Message: 20
08-10 07:40:44.499  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d49e450:true
,08-10 07:40:44.504  6960  6960 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:40:44.504  6960  6960 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:40:44.504  6960  6960 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:40:44.504  6960  6960 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:40:44.504  6960  6960 I Adreno-EGL: Remote Branch: 
08-10 07:40:44.504  6960  6960 I Adreno-EGL: Local Patches: 
08-10 07:40:44.504  6960  6960 I Adreno-EGL: Reconstruct Branch: 
08-10 07:40:44.575  6960  6996 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-10 07:40:44.576  6960  6960 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-10 07:40:44.590  6960  6960 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 07:40:44.593  6960  6960 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 07:40:44.596  6960  6960 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-10 07:40:44.599  6960  6960 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-10 07:40:44.599  6960  6960 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-10 07:40:44.611  6960  6960 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-10 07:40:44.620  6960  6960 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 07:40:44.620  6960  6960 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-10 07:40:44.641  6960  7008 D OpenGLRenderer: Render dirty regions requested: true
08-10 07:40:44.642  6960  7008 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 07:40:44.660  6960  7008 D OpenGLRenderer: Enabling debug mode 0
,08-10 07:40:44.678  6960  6960 D Atlas   : Validating map...
,08-10 07:40:44.684  1037  1900 D SplitWindow: check instance of lgWin Window{3b72120a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 07:40:44.717  6960  7006 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:40:44.717  6960  7006 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:40:44.862  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +582ms (total +660ms)
08-10 07:40:44.863  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11042d77 u0 com.test.thalitest/.MainActivity t4} time:306121
,08-10 07:40:44.875  6960  6960 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@187d1279 time:306132
,08-10 07:40:44.992  6960  6960 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-10 07:40:44.992  6960  6960 I chromium: 
,08-10 07:40:45.043  6960  6960 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 07:40:45.114  6960  7006 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-10 07:40:45.114  6960  7006 I chromium: 
,08-10 07:40:45.256  6960  7021 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435064832
,08-10 07:40:45.273  6960  7021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 07:40:45.273  6960  7021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 07:40:45.273  6960  7021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 07:40:45.273  6960  7021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 07:40:45.273  6960  7021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-10 07:40:45.274  6960  7021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32efded added. We now have 1 listener(s)
08-10 07:40:45.282  1037  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 07:40:45.286  6960  7021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-10 07:40:45.290  6960  7021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:40:45.293  6960  7021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:40:45.294  6960  7021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 07:40:45.306  6960  7021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2670bc70 added. We now have 1 listener(s)
08-10 07:40:45.307  6960  7021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 07:40:45.313  1037  1546 D WifiService: New client listening to asynchronous messages
08-10 07:40:45.318  6960  7021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 07:40:45.318  6960  7021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 07:40:45.320  6960  7021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 07:40:45.320  6960  7021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 07:40:45.321  6960  7021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-10 07:40:45.333  6960  7021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:40:45.334  1037  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 07:40:45.338  6960  7021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-10 07:40:45.348  6960  7021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-10 07:40:45.351  6960  7021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:40:45.351  6960  7021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:40:45.351  6960  7021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:40:45.351  6960  7021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:40:45.351  6960  7021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:40:45.351  6960  7021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:40:45.351  6960  7021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:40:45.351  6960  7021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:40:45.351  6960  7021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 07:40:45.351  6960  7021 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:40:45.354  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:40:45.356  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:40:45.358  6960  7021 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 07:40:45.414  6960  6960 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 07:40:45.849   339   366 E GBMv2   : DFP En is all cleared set to be enabled
08-10 07:40:45.850   339   366 E GBMv2   : Set value is all cleared set the max
08-10 07:40:45.850   339   366 I GBMv2   : DFP Enabled. Ignore VFP set
,08-10 07:40:46.371  6960  7027 W jxcore-log: Initializing JXcore engine
08-10 07:40:46.371  6960  7027 W jxcore-log: JXcore engine is ready
,08-10 07:40:46.410  7027  7027 W Thread-816: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8468]" dev="sockfs" ino=8468 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-10 07:40:46.410  7027  7027 W Thread-816: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-10 07:40:46.410  7027  7027 W Thread-816: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8559]" dev="sockfs" ino=8559 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-10 07:40:46.410  7027  7027 W Thread-816: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-10 07:40:46.410  7027  7027 W Thread-816: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[32650]" dev="sockfs" ino=32650 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-10 07:40:46.434  6960  7027 W jxcore-log: Starting JXcore engine
08-10 07:40:46.583  6960  7027 W jxcore-log: Platform android
08-10 07:40:46.583  6960  7027 W jxcore-log: 
08-10 07:40:46.583  6960  7027 W jxcore-log: Process ARCH arm
08-10 07:40:46.583  6960  7027 W jxcore-log: 
,08-10 07:40:46.659  1037  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1010898462, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,08-10 07:40:46.660  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{229dcab0 type 2 when 242071 android} when 242071
08-10 07:40:46.695  2621  2621 D [Concierge]Service: onStartCommand(). Type : 9
,08-10 07:40:46.724  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1010898462 [*alarm*], flags=0x0
,08-10 07:40:46.977  6960  7027 I jxcore-log: JXcore Cordova bridge is ready!
08-10 07:40:46.977  6960  7027 I jxcore-log: 
08-10 07:40:46.977  6960  7027 W jxcore-log: JXcore engine is started
,08-10 07:40:46.983  6960  7021 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 07:40:46.990  6960  6960 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 07:41:00.059  1605  1605 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-10 07:41:00.060  1605  1605 I KeyguardUpdateMonitor: called onTimeUpdated()
08-10 07:41:00.060  1605  1605 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-10 07:41:00.060  1605  1605 I [SystemUI]Clock: called onTimeUpdated()
,08-10 07:41:00.067  1605  1605 I LgeClockWidgetControlView: called onTimeUpdated()
08-10 07:41:00.067  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-10 07:41:00.069  1605  1605 I [SystemUI]DateView: called onTimeUpdated()
08-10 07:41:00.070  1605  1605 D KeyguardUpdateMonitor: handleTimeUpdate
08-10 07:41:02.674  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 07:41:02.674  6960  7027 I jxcore-log: 
,08-10 07:41:02.677  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 07:41:02.677  6960  7027 I jxcore-log: 
08-10 07:41:02.685  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:02.685  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:02.685  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:02.685  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:02.685  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:02.685  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:02.685  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:02.685  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:02.690  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 07:41:02.693  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 07:41:02.693  6960  7027 I jxcore-log: 
08-10 07:41:02.696  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 07:41:02.696  6960  7027 I jxcore-log: 
08-10 07:41:03.028  6960  7027 D ExecuteNativeTests: Running unit tests
,08-10 07:41:03.095  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,08-10 07:41:03.095  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad added. We now have 2 listener(s)
,08-10 07:41:03.096  1037  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 07:41:03.097  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-10 07:41:03.097  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:03.097  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-10 07:41:03.097  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 07:41:03.097  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 added. We now have 2 listener(s)
,08-10 07:41:03.097  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-10 07:41:03.098  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 07:41:03.100  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-10 07:41:03.102  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:03.102  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.102  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.102  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:03.102  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:03.102  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-10 07:41:03.102  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:03.102  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:03.103  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:03.103  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:41:03.104  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:03.105  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.107  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-10 07:41:03.108  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 07:41:03.108  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 07:41:03.110  6960  7027 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 07:41:03.112  6960  7027 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 07:41:03.112  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 07:41:03.112  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 07:41:03.112  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 07:41:03.113  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.113  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.113  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.114  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.114  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.114  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:03.114  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:03.114  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad removed from the list
08-10 07:41:03.114  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.114  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 removed from the list
08-10 07:41:03.114  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.114  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.115  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.115  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.115  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.116  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.116  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.116  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.117  6960  7027 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 07:41:03.118  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.119  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STAR,TED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.119  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.122  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.122  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.122  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.122  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.122  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.122  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.122  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.122  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.122  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.122  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.122  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.123  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.123  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.123  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.123  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 07:41:03.127  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 07:41:03.128  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 07:41:03.128  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.128  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.128  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.129  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.129  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.129  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.129  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.129  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.129  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.129  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.129  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.129  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.129  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.129  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.130  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.130  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.130  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.130  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.131  6960  7027 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 07:41:03.133  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:03.135  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:03.135  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.135  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.135  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:03.135  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:03.135  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:03.135  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:03.135  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:03.136  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:03.136  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:41:03.137  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.138  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.138  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 07:41:03.138  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 07:41:03.139  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 07:41:03.139  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:03.139  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 07:41:03.141  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 07:41:03.142  1037  1879 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:03.145  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 07:41:03.149  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 07:41:03.151  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 07:41:03.152  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 07:41:03.152  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:03.153  6960  7027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 07:41:03.154  6960  7027 I io.jxcore.node.ConnectionHelper: start: OK
08-10 07:41:03.156  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.156  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.156  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.156  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.156  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.156  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:03.156  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.156  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.156  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.156  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.156  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.156  6960  7027 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 07:41:03.158  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:03.159  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:03.159  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.159  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.159  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:03.159  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:03.159  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:03.159  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:03.159  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:03.161  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:03.161  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:41:03.161  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 07:41:03.161  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 07:41:03.161  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 07:41:03.161  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:03.161  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 07:41:03.163  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.165  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.166  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 07:41:03.166  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:03.169  6960  7027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 07:41:03.169  6960  7027 I io.jxcore.node.ConnectionHelper: start: OK
08-10 07:41:03.170  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.170  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.170  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.171  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.171  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.171  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:03.171  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.171  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.171  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.171  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.171  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.171  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.171  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.172  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.172  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.173  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.173  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.173  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.173  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.173  6960  7027 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 07:41:03.174  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:03.176  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:03.176  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.176  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.176  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:03.176  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:03.176  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:03.176  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:03.176  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:03.177  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:03.177  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:41:03.177  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 07:41:03.177  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 07:41:03.177  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 07:41:03.177  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:03.177  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 07:41:03.179  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.181  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 07:41:03.182  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.182  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 07:41:03.183  6960  7027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 07:41:03.183  6960  7027 I io.jxcore.node.ConnectionHelper: start: OK
08-10 07:41:03.183  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.183  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.183  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.184  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.184  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.184  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.184  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.184  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.184  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:03.184  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.184  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.184  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.184  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.184  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.185  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.185  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.185  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.185  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.186  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.186  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.186  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.186  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.187  6960  7027 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-10 07:41:03.187  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.187  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.187  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, sk,ipping...
08-10 07:41:03.187  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.187  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.187  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.187  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.187  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.187  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.187  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.187  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.187  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.187  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.188  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.188  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.188  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.189  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.189  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.189  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-10 07:41:03.189  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.190  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 07:41:03.190  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 07:41:03.190  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.190  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.190  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.190  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.190  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.190  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.190  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.190  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.190  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.190  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.190  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.190  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.190  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.191  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.191  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 07:41:03.191  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.191  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.191  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.191  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.192  6960  7027 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
08-10 07:41:03.192  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.192  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.192  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.192  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.192  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.192  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.192  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.192  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 07:41:03.192  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.192  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.192  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.192  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.192  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.192  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.193  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.193  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.195  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.195  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.195  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.195  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.195  6960  7027 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 07:41:03.195  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.195  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.195  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.196  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.196  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.196  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.196  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
,08-10 07:41:03.196  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.196  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.196  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.196  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.196  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.196  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.196  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.197  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-10 07:41:03.197  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.197  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.197  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.197  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.197  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.197  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-10 07:41:03.199  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 07:41:03.199  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 07:41:03.199  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 07:41:03.199  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 07:41:03.199  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 07:41:03.199  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 07:41:03.199  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.199  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.199  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.199  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.199  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.199  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.199  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 07:41:03.199  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.199  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.199  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.199  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.199  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.200  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 07:41:03.200  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.200  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.201  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.201  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.201  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.201  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.201  6960  7027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 07:41:03.202  6960  7027 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 07:41:03.202  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 07:41:03.205  6960  7027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 07:41:03.205  6960  7027 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 07:41:03.205  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 07:41:03.205  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-10 07:41:03.205  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 07:41:03.205  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 07:41:03.205  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 07:41:03.205  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 07:41:03.205  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 07:41:03.207  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 07:41:03.208  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 07:41:03.209  6960  7027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 07:41:03.209  6960  7027 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 07:41:03.209  6960  7027 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 07:41:03.209  6960  7027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 07:41:03.209  6960  7027 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 07:41:03.210  6960  7027 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 07:41:03.210  6960  7027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 07:41:03.210  6960  7027 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 07:41:03.210  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 07:41:03.211  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 07:41:03.212  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 07:41:03.212  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 07:41:03.212  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-10 07:41:03.213  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 07:41:03.213  6960  7027 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 07:41:03.213  6960  7027 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 07:41:03.213  6960  7027 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 07:41:03.213  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.213  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.213  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.214  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 07:41:03.214  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.214  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.214  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 07:41:03.216  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.216  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.216  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.216  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.216  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.216  6960  7052 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 880)
,08-10 07:41:03.216  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.216  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.216  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.218  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.218  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.219  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.219  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.219  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.219  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
,08-10 07:41:03.219  6960  7027 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 07:41:03.219  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.219  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.219  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.220  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.220  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.220  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.220  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
,08-10 07:41:03.220  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.220  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.220  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.220  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.220  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.220  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.220  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 07:41:03.221  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-10 07:41:03.221  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.221  6960  7053 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 880
08-10 07:41:03.221  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.221  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.221  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-10 07:41:03.221  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.221  6960  7053 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 880)
08-10 07:41:03.222  6960  7027 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 07:41:03.222  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.222  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 07:41:03.222  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.222  6960  7053 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 880)
08-10 07:41:03.223  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.223  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.223  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 07:41:03.223  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.223  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.223  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.223  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.223  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.223  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 07:41:03.223  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.223  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.223  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.223  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.224  6960  7027 D BluetoothLeScanner: could not find callback wrapper
,08-10 07:41:03.224  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.224  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.224  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.225  6960  7027 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 07:41:03.225  6960  7027 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-10 07:41:03.226  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 07:41:03.226  6960  7027 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 07:41:03.227  6960  7027 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 07:41:03.227  6960  7027 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 07:41:03.227  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 07:41:03.227  6960  7027 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 07:41:03.227  6960  7027 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-10 07:41:03.227  6960  7027 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 07:41:03.227  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 07:41:03.227  6960  7027 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 07:41:03.227  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.227  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.227  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 07:41:03.232  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.232  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.232  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.232  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.232  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.232  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.232  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.232  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.232  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.232  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 07:41:03.232  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.233  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.233  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 07:41:03.234  6960  7027 D BluetoothLeScanner: could not find callback wrapper
,08-10 07:41:03.234  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.234  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.234  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.234  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.234  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.234  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.234  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
,08-10 07:41:03.234  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.234  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.234  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.234  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.234  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.235  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.235  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
,08-10 07:41:03.235  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.235  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.235  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.235  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.235  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.235  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.235  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 07:41:03.235  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.235  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.235  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.235  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.235  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.235  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.235  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.235  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.235  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.235  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.235  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.236  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.236  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.236  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.236  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 07:41:03.236  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.237  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.238  6960  7027 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 07:41:03.238  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:03.238  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 07:41:03.239  6960  7027 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-10 07:41:03.239  6960  7027 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 07:41:03.240  6960  6960 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-10 07:41:03.241  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 07:41:03.241  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 07:41:03.241  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 07:41:03.241  6960  7055 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 07:41:03.242  4186  4205 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-10 07:41:03.244  6960  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-10 07:41:03.253  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.253  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 07:41:03.253  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 07:41:03.253  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-10 07:41:03.253  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 07:41:03.253  6960  7027 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 07:41:03.254  6960  6960 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 07:41:03.254  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.254  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.254  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 07:41:03.254  6960  7027 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 07:41:03.254  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 07:41:03.255  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 07:41:03.256  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:03.256  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:03.256  6960  7027 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 07:41:03.256  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 07:41:03.256  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.257  6960  7055 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-10 07:41:03.258  6960  7055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-10 07:41:03.258  6960  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-10 07:41:03.260  6960  7027 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 07:41:03.261  6960  6960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 07:41:03.261  6960  6960 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 07:41:03.261  6960  6960 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 07:41:03.261  6960  6960 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 07:41:03.261  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.261  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.261  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 07:41:03.261  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.261  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.262  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.262  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.262  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.262  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 07:41:03.262  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.262  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.262  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.262  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.262  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.262  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 07:41:03.263  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.263  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.263  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.263  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.265  6960  7027 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 07:41:03.265  6960  7027 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-10 07:41:03.265  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 07:41:03.265  6960  7027 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 07:41:03.265  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.265  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.265  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 07:41:03.266  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.266  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.266  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.266  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.266  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.266  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.266  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.266  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.266  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.266  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.266  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.268  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.269  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.269  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.269  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.273  1037  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:03.274  1037  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:03.275  1037  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:03.276  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.276  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.276  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.276  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.276  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.276  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.276  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.276  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.276  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.276  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.276  6960  7027 W or,g.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.276  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.276  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.276  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.277  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.277  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.277  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.277  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
,08-10 07:41:03.278  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:03.278  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:03.278  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:03.278  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:03.278  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.278  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.278  6960  7027 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c8c6ad not in the list
08-10 07:41:03.278  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.278  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.278  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:03.278  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.278  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.278  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:03.278  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:03.279  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:03.279  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:03.279  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:03.279  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26d37de2 not in the list
08-10 07:41:03.281  6960  7027 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 07:41:03.281  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 07:41:03.281  6960  7027 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 07:41:03.281  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 07:41:03.281  6960  7027 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 07:41:03.281  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 07:41:03.283  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 07:41:03.283  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 07:41:03.283  6960  7027 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 07:41:03.283  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming conn,ection(s) left
08-10 07:41:03.283  6960  7027 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 07:41:03.283  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 07:41:03.284  6960  7027 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 07:41:03.284  6960  7027 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 07:41:03.284  6960  7027 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 07:41:03.284  6960  7027 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 07:41:03.285  6960  7027 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 07:41:03.285  6960  7027 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 07:41:03.285  6960  7027 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 07:41:03.285  6960  7027 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 07:41:03.286  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:03.286  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@392c4feb added. We now have 2 listener(s)
08-10 07:41:03.286  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:03.287  6960  7027 D BluetoothAdapter: enable(): BT is already enabled..!
08-10 07:41:03.288  1037  1954 D WifiServiceImplEx: setWifiEnabled: true pid=6960, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-10 07:41:03.289  1037  1954 D WifiService: setWifiEnabled: true pid=6960, uid=10118
08-10 07:41:03.289  1037  1954 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 07:41:03.290  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:03.290  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12f9d148 added. We now have 3 listener(s)
,08-10 07:41:03.291  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:03.296  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:03.296  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17d23be1 added. We now have 4 listener(s)
08-10 07:41:03.296  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:03.297  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:03.297  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23c83d06 added. We now have 5 listener(s)
08-10 07:41:03.297  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:03.301  1037  1954 D WifiServiceImplEx: setWifiEnabled: false pid=6960, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 07:41:03.301  1037  1954 D WifiService: setWifiEnabled: false pid=6960, uid=10118
,08-10 07:41:03.301  1037  1954 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
08-10 07:41:03.312  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 07:41:03.312  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 07:41:03.312  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-10 07:41:03.313  1037  1052 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:03.313  1037  1052 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2ddb5d6a mBinding = false
08-10 07:41:03.313  1037  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:03.314  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:03.314  1037  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
,08-10 07:41:03.316  1037  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:03.316  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:03.317  1037  1541 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 07:41:03.317  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 07:41:03.317  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 07:41:03.318  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 07:41:03.318  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 07:41:03.318  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 07:41:03.318  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 07:41:03.318  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-10 07:41:03.319  1037  1119 D BluetoothManagerService: Message: 2
08-10 07:41:03.319  1037  1119 D BluetoothManagerService: Sending off request.
08-10 07:41:03.320  4186  4337 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 07:41:03.320  4186  4272 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 07:41:03.320  4186  4272 D BluetoothAdapterProperties: Setting state to 13
08-10 07:41:03.320  4186  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 07:41:03.320  4186  4272 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 07:41:03.320  4186  4272 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-10 07:41:03.321  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 07:41:03.322  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.322  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.322  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 07:41:03.323  2675  2675 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 07:41:03.323  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 07:41:03.323  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 07:41:03.323  1037  1119 D BluetoothManagerService: Message: 60
08-10 07:41:03.323  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 07:41:03.323  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-10 07:41:03.323  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-10 07:41:03.324  4186  4277 D BluetoothAdapterProperties: Scan Mode:20
08-10 07:41:03.324  1037  2828 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.324  4186  4272 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-10 07:41:03.325  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:03.325  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 07:41:03.325  4186  4425 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-10 07:41:03.325  4186  4272 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 07:41:03.326  4186  4575 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 07:41:03.326  4186  4575 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:03.326  4186  4575 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 07:41:03.326  4186  4575 ,V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 07:41:03.326  4186  4575 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 07:41:03.326  4186  4575 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 07:41:03.326  4186  4575 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 07:41:03.326  4186  4575 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-10 07:41:03.327  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 07:41:03.328  4186  4577 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:03.328  4186  4630 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:03.328  4186  4634 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:03.328  4186  4632 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 07:41:03.330  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 07:41:03.330  4186  4425 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 07:41:03.330  4186  4186 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:03.331  4186  4186 D BluetoothMapService: STATE_TURNING_OFF
08-10 07:41:03.331  4186  4186 V BluetoothMapService: Handler(): got msg=4
08-10 07:41:03.331  4186  4186 D BluetoothMapService: MAP Service closeService in
08-10 07:41:03.331  4186  4186 D BluetoothMapMasInstance: MAP Service shutdown
08-10 07:41:03.331  4186  4186 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 07:41:03.331  4186  4186 V BluetoothMapService: MAP Service closeService out
08-10 07:41:03.332  4186  4186 V BtOppService: Receiver DISABLED_ACTION 
08-10 07:41:03.333  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.333  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:03.333  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.333  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.333  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:03.333  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:03.333  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:03.333  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:03.333  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:03.334  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.334  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22,:99:3e
08-10 07:41:03.335  4186  4186 I BtOppRfcommListener: stopping Accept Thread
08-10 07:41:03.335  4186  4186 V BtOppRfcommListener: close mBtServerSocket
08-10 07:41:03.335  4186  4186 V BtOppRfcommListener: waiting for thread to terminate
08-10 07:41:03.335  4186  4630 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 07:41:03.336  4186  4186 V BtOppRfcommListener: done waiting for thread to terminate
08-10 07:41:03.338   310   895 D CommandListener: Clearing all IP addresses on wlan0
,08-10 07:41:03.346  6960  7052 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-10 07:41:03.346  6960  7052 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 880)
08-10 07:41:03.363  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 07:41:03.363  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-10 07:41:03.370  1037  2034 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-10 07:41:03.370  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.370  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.370  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-10 07:41:03.370  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.370  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-10 07:41:03.375  1037  1100 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7062 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 07:41:03.380  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.380  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:03.380  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.380  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.380  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:03.380  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:03.380  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:03.380  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:03.380  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 07:41:03.382  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.382  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:03.409  1037  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-10 07:41:03.409   310  7081 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 07:41:03.409  1037  1547 D DSQN    : disableDataServiceNotify
08-10 07:41:03.409  1037  1547 D DSQN    : stop dsqn bin
08-10 07:41:03.409  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 07:41:03.410  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,08-10 07:41:03.414  1037  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 07:41:03.414  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:03.414  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:03.415  1037  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:03.415  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-10 07:41:03.415  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.415  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.415  1037  2822 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-10 07:41:03.416  1605  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-10 07:41:03.416  1037  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-10 07:41:03.416  1037  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-10 07:41:03.417  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 07:41:03.418  1037  1100 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7084 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-10 07:41:03.419  4186  4186 V BtOppService: onDestroy
08-10 07:41:03.419  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:03.419  4186  4186 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-10 07:41:03.420  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.420  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.420  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.421  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.421  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.421  1037  1539 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1a0f0730
08-10 07:41:03.421  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.421  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.421  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:03.,421  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.421  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.421  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:03.421  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:03.421  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:03.421  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:03.421  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:03.421  1037  1539 D LGWifiP2pService: P2pDisablingState
08-10 07:41:03.421  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.421  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.421  1037  1539 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.421  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:03.421  1037  1539 D LGWifiP2pService: p2p socket connection lost
08-10 07:41:03.421  1037  1539 D LGWifiP2pService: P2pDisabledState
08-10 07:41:03.421  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:41:03.421  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.423  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:03.423  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 07:41:03.423  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:03.424  1037  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:03.424  1037  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:03.424  1037  1547 D NetworkManagementService: Removing idletimer
08-10 07:41:03.424  1037  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:03.424  1037  1037 D WifiHS20: hidePasspointNotification off =false
,08-10 07:41:03.426  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-10 07:41:03.426  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:03.426  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:03.426  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:03.426  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 07:41:03.426  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 07:41:03.428  1037  1547 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-10 07:41:03.428  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-10 07:41:03.429  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:03.429  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:03.429  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:03.430  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:03.430  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:03.430  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 07:41:03.431  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-10 07:41:03.431  1037  1559 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.431  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-10 07:41:03.431  1037  1560 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.431  1037  1541 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 07:41:03.432  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 07:41:03.432  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.432  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.432  1944  1944 D WfdsService: WifiP2pState is changed : false
08-10 07:41:03.432  1944  2358 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-10 07:41:03.432  1944  2358 D WfdsService: Set the WFDS Monitor: false
08-10 07:41:03.432  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:03.433  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-10 07:41:03.433  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.433  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.433  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 07:41:03.433  2675  2675 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 07:41:03.434  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 07:41:03.434  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 07:41:03.434  ,1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-10 07:41:03.435  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 07:41:03.435   310   895 D CommandListener: Clearing all IP addresses on wlan0
08-10 07:41:03.435  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 07:41:03.435  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 07:41:03.435  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 07:41:03.435  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 07:41:03.436  1944  2358 D WfdsMonitor: WFDS Monitor is stopped
08-10 07:41:03.436  1944  2358 D WfdsService: STATE : WfdsDisabledState - enter
08-10 07:41:03.436  1944  2733 D CtrlSupplicant: Received on exit socket, terminate
08-10 07:41:03.436  1944  2733 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-10 07:41:03.436  1944  2733 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-10 07:41:03.436  1944  2733 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-10 07:41:03.436  1944  2359 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-10 07:41:03.437  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 07:41:03.437  1944  2358 W WfdsService: DefaultState - msg [9445378] is not handled
,08-10 07:41:03.437  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 07:41:03.437  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 07:41:03.437  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 07:41:03.437  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 07:41:03.440  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.441  1037  1541 D WifiNative-p2p0: doBoolean: TERMINATE
08-10 07:41:03.441  1037  1541 D WifiNative-p2p0: TERMINATE: returned true
08-10 07:41:03.441  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 07:41:03.441  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-10 07:41:03.441  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 07:41:03.442  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.442  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:03.442  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.442  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.442  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:03.442  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:03.442  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:03.442  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:03.442  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:03.442  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-10 07:41:03.444  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:03.444  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:03.447  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 07:41:03.448  1037  1541 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 07:41:03.448  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:03.448  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:03.448  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 07:41:03.451  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:03.454  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-10 07:41:03.454  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-10 07:41:03.454  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:03.454  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-10 07:41:03.456  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.456  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:03.456  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.456  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.456  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:03.456  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:03.456  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:03.456  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:03.456  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:03.458  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.458  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 07:41:03.460  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.460  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:03.460  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:03.460  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:03.460  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:03.460  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:03.460  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:03.460  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:03.460  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:03.460  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:03.461  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 07:41:03.479  7062  7062 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:03.479  7062  7062 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-10 07:41:03.479  7062  7062 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:03.479  7062  7062 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-10 07:41:03.480  7062  7062 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 07:41:03.480  7062  7062 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 07:41:03.481  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 07:41:03.482  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:03.482  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:03.493  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 07:41:03.494  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:03.495  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:03.495  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-10 07:41:03.495  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:03.496  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:03.499  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:03.512  7084  7084 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-10 07:41:03.512  7084  7084 W LG Account v2.2: No ProfileInfo entries
08-10 07:41:03.512  7084  7084 I LG Account v2.2: isEnabled: false
08-10 07:41:03.512  7084  7084 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Country: EU
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Operator: OPEN
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Ranking support: false
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Comfort support: false
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Accessory: true
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Health device: true
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Extra Pedometer: false
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Blood glucose device: false
08-10 07:41:03.513  7084  7084 I Feature : [Lifetracker]Device Number: 3
08-10 07:41:03.519  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:03.543  2675  2675 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-10 07:41:03.543  2675  2675 I wpa_supplicant: monitor socket send errors count : 1
08-10 07:41:03.543  2675  2675 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-2\x00 that cannot receive messages
08-10 07:41:03.545  1037  2713 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-10 07:41:03.545  1037  2713 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-10 07:41:03.551  1037  1052 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7104 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 07:41:03.551  1037  2828 D DhcpStateMachine: StoppedState
08-10 07:41:03.551  1037  2828 D DhcpStateMachine: StoppedState{ when=-116ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:03.551  1037  1052 I ActivityManager: Killing 6249:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-10 07:41:03.559  7062  7062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 07:41:03.583  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-10 07:41:03.584  1037  1541 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-10 07:41:03.584  2675  2675 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 07:41:03.584  1037  2713 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-10 07:41:03.585  2675  2675 W wpa_supplicant: USIM:  scard_deinit function
08-10 07:41:03.585  1037  1119 D Tethering: InitialState.processMessage what=4
08-10 07:41:03.586  1037  2713 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 07:41:03.586  1037  2713 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 07:41:03.587  1037  2713 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-10 07:41:03.587  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 07:41:03.587  1037  2713 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:03.587  1037  2713 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:03.588  1037  1541 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=324832
08-10 07:41:03.588  1037  1541 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=324833
08-10 07:41:03.588  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=324833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 07:41:03.588  1037  1541 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=324833  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 07:41:03.589  4186  4186 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 07:41:03.589  4186  4186 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:03.589  4186  4186 V BluetoothPbapReceiver: ***********state = 13
08-10 07:41:03.590  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:03.590  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:03.591  4186  4186 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-10 07:41:03.593  1037  1119 D BluetoothManagerService: Message: 20
08-10 07:41:03.594  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@831940d:true
08-10 07:41:03.597  1037  1974 W libprocessgroup: failed to open /acct/uid_10014/pid_6249/cgroup.procs: No such file or directory
08-10 07:41:03.598  4186  4186 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:03.598  4186  4186 V BluetoothPbapService: state: 13
08-10 07:41:03.598  4186  4186 V BluetoothPbapService: Pbap Service closeService in
,08-10 07:41:03.601  4186  4186 V BluetoothPbapService: successfully stopped pbap service
08-10 07:41:03.601  4186  4186 V BluetoothPbapService: Pbap Service closeService out
08-10 07:41:03.601  4186  4186 V BluetoothPbapService: Pbap Service onDestroy
08-10 07:41:03.601  4186  4186 V BluetoothPbapService: Pbap Service closeService in
08-10 07:41:03.601  4186  4186 V BluetoothPbapService: Pbap Service closeService out
08-10 07:41:03.601  4186  4186 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-10 07:41:03.604  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 07:41:03.613  1037  1119 D BluetoothManagerService: Message: 30
,08-10 07:41:03.617  1037  1119 D BluetoothManagerService: Message: 30
08-10 07:41:03.620  7062  7062 D LocalBluetoothProfileManager: Adding local MAP profile
08-10 07:41:03.621  7062  7062 D BluetoothMap: Create BluetoothMap proxy object
08-10 07:41:03.621  1037  1119 D BluetoothManagerService: Message: 30
08-10 07:41:03.625  1037  1119 D BluetoothManagerService: Message: 30
,08-10 07:41:03.627  7062  7062 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-10 07:41:03.628  7062  7062 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-10 07:41:03.641  7062  7062 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-10 07:41:03.644  7062  7062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-10 07:41:03.647  7104  7104 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 07:41:03.653  2675  2675 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-10 07:41:03.653  7062  7062 D DockEventReceiver: finishStartingService: stopping service
08-10 07:41:03.654  1037  2713 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-10 07:41:03.654  1037  2713 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-10 07:41:03.654  1037  2713 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-10 07:41:03.655  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-10 07:41:03.658  7104  7104 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 07:41:03.658  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:03.660  1037  2054 I ActivityManager: Killing 2129:com.lge.music/u0a34 (adj 15): empty #17
08-10 07:41:03.665  7062  7062 D BluetoothInputDevice: Proxy object connected
08-10 07:41:03.666  7062  7062 D HidProfile: Bluetooth service connected
,08-10 07:41:03.667  7062  7062 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 07:41:03.669  7062  7062 D PanProfile: Bluetooth service connected
,08-10 07:41:03.670  7062  7062 D BluetoothMap: Proxy object connected
08-10 07:41:03.671  7062  7062 D MapProfile: Bluetooth service connected
08-10 07:41:03.671  7062  7062 D BluetoothMap: getConnectedDevices()
,08-10 07:41:03.672  7062  7062 D BluetoothMap: Bluetooth is Not enabled
08-10 07:41:03.672  7062  7062 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-10 07:41:03.681   315  2147 V AudioFlinger: 2129 died, releasing its sessions
08-10 07:41:03.681   315  2147 V AudioFlinger:  pid 1853 @ 0
08-10 07:41:03.681   315  2147 V AudioFlinger:  pid 3350 @ 1
08-10 07:41:03.681   315  2147 V AudioFlinger:  pid 3350 @ 2
,08-10 07:41:03.708  1037  1974 W libprocessgroup: failed to open /acct/uid_10034/pid_2129/cgroup.procs: No such file or directory
,08-10 07:41:03.718  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 07:41:03.758  1037  1541 D WifiOffDelayIfNotUsed: stopMonitoring
08-10 07:41:03.758  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 07:41:03.758  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-10 07:41:03.758  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-10 07:41:03.759  1944  1944 D WfdsService: Supplicant Connection state is changed : false
08-10 07:41:03.759  1944  2358 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-10 07:41:03.760  1944  2358 D WfdsService: Set the WFDS Monitor: false
08-10 07:41:03.760  1944  2358 D WfdsMonitor: WFDS Monitor is stopped
08-10 07:41:03.761  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-10 07:41:03.761  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:03.762  6960  6960 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 07:41:03.763  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 07:41:03.764  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-10 07:41:03.767  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-10 07:41:03.767  7062  7062 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:03.767  7062  7062 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 07:41:03.773  2460  2460 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:03.773  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:03.775  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:03.780  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:03.784  7062  7062 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 07:41:03.790  7062  7062 D BluetoothPermissionRequest: onReceive
08-10 07:41:03.793  7062  7062 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 07:41:03.800  1037  1897 I ActivityManager: Killing 6516:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-10 07:41:03.802  7062  7062 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 07:41:03.858  4186  4186 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-10 07:41:03.859  4186  4186 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-10 07:41:03.860  4186  4186 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-10 07:41:03.862  1037  1053 W libprocessgroup: failed to open /acct/uid_10008/pid_6516/cgroup.procs: No such file or directory
08-10 07:41:03.951  1037  2011 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7134 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-10 07:41:03.958  4186  4186 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:03.958  4186  4186 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 07:41:03.961  4186  4186 V BluetoothFtpService: Ftp Service onStartCommand
08-10 07:41:03.961  4186  4186 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:03.962  4186  4186 V BluetoothFtpService: Ftp Service closeService
08-10 07:41:03.963  4186  4186 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-10 07:41:03.966  4186  4186 V BluetoothFtpService: successfully stopped ftp service
08-10 07:41:03.967  4186  4186 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-10 07:41:03.967  4186  4186 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 07:41:03.967  4186  4186 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 07:41:03.967  4186  4186 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:03.968  4186  4186 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 07:41:03.968  4186  4186 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 07:41:03.970  4186  4186 V BluetoothFtpService: Ftp Service onDestroy
08-10 07:41:03.970  4186  4186 V BluetoothFtpService: Ftp Service closeService
08-10 07:41:04.074  1037  1649 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7155 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 07:41:04.075  4186  4186 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:04.075  4186  4186 V BluetoothSapService: state: 13
08-10 07:41:04.076  4186  4186 V BluetoothSapService: Stopping SAP server process
08-10 07:41:04.078  4186  4186 V BluetoothSapService: Sap Service closeSapService in
08-10 07:41:04.078  4186  4186 V BluetoothSapService: Close listen Socket : 
08-10 07:41:04.078  4186  4186 V BluetoothSapService: Close rfcomm Socket : 
08-10 07:41:04.079  4186  4186 V BluetoothSapService: Close sapd  Socket : 
08-10 07:41:04.086  4186  4186 V BluetoothSapService: Sap Service closeSapService out
08-10 07:41:04.086  4186  4186 V BluetoothSapService: Sap Service onDestroy
08-10 07:41:04.086  4186  4186 V BluetoothSapService: Sap Service closeSapService in
08-10 07:41:04.086  4186  4186 V BluetoothSapService: Close listen Socket : 
08-10 07:41:04.086  4186  4186 V BluetoothSapService: Close rfcomm Socket : 
08-10 07:41:04.086  4186  4186 V BluetoothSapService: Close sapd  Socket : 
08-10 07:41:04.087  4186  4186 V BluetoothSapService: Sap Service closeSapService out
08-10 07:41:04.105  7134  7134 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 07:41:04.132  7134  7134 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-10 07:41:04.136  7155  7155 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:04.154  1037  2054 I ActivityManager: Killing 6561:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-10 07:41:04.172  7134  7134 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-10 07:41:04.172  7134  7134 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-10 07:41:04.173  7134  7134 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-10 07:41:04.173  7134  7134 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-10 07:41:04.173  7134  7134 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-10 07:41:04.175  7134  7134 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-10 07:41:04.181  7134  7134 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-10 07:41:04.238  1037  2011 W libprocessgroup: failed to open /acct/uid_10011/pid_6561/cgroup.procs: No such file or directory
,08-10 07:41:04.253  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:04.260  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:04.279  7134  7134 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 07:41:04.284  7134  7134 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-10 07:41:04.284  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:04.288  7134  7134 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-10 07:41:04.293  7104  7104 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 07:41:04.293  7104  7104 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-10 07:41:04.293  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:04.302  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:04.317  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:04.326  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:04.326  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:04.328  7134  7134 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 07:41:04.333  4186  4277 D bt_hci_bdroid: cleanup
08-10 07:41:04.333  4186  4427 I bt_lpm  : LPM is already off!!!
08-10 07:41:04.334  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:04.335  4186  4425 W bt-btif : ag scb idx 1 not allocated
08-10 07:41:04.335  4186  4425 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:04.335  4186  4425 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 07:41:04.335  4186  4425 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 07:41:04.336  4186  4564 I bt_userial_mct: exiting userial_read_thread
08-10 07:41:04.336  4186  4564 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 07:41:04.336  4186  4277 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 07:41:04.336  4186  4427 I bt_vendor: hw_epilog_process
08-10 07:41:04.337  4186  4277 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 07:41:04.337  4186  4277 D bt_userial_mct: userial_close
08-10 07:41:04.337  4186  4277 E bt_userial_mct: pthread_join() FAILED result:3
08-10 07:41:04.337  4186  4277 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-10 07:41:04.341  7104  7104 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 07:41:04.341  7104  7104 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 07:41:04.341  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:04.346  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:04.358  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:04.372  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:04.373  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:04.375  7134  7134 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-10 07:41:04.392  4186  4277 D bt_hci_bdroid: set_power 0
,08-10 07:41:04.392  4186  4277 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-10 07:41:04.392  4186  4277 I bt_vendor: bluetooth satus is on
,08-10 07:41:04.393  4186  4277 I bt_vendor: bt-vendor : resetting BT status
,08-10 07:41:04.393  4186  4277 I bt_vendor: Starting hciattach daemon
08-10 07:41:04.393  4186  4277 I bt_vendor: try to set false
08-10 07:41:04.394  4186  4277 I bt_vendor: Starting hciattach daemon
08-10 07:41:04.394  4186  4277 I bt_vendor: try to set false
08-10 07:41:04.395  4186  4277 I bt_vendor: cleanup
08-10 07:41:04.396  4186  4425 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 07:41:04.397  4186  4277 I GKI_LINUX: GKI_exit_task 0 done
08-10 07:41:04.397  4186  4277 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 07:41:04.399  4186  4272 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-10 07:41:04.445  1037  1926 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7176 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-10 07:41:04.450  4186  4186 D HeadsetService: Received stop request...Stopping profile...
08-10 07:41:04.453  4186  4186 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 07:41:04.453  4186  4186 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 07:41:04.453  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30b96ad3
08-10 07:41:04.454  4186  4332 D HeadsetStateMachine: Exit Disconnected: -1
08-10 07:41:04.456  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-10 07:41:04.456  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-10 07:41:04.458  1853  1853 D BluetoothHeadset: Proxy object disconnected
,08-10 07:41:04.458  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-10 07:41:04.458  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-10 07:41:04.459  4186  4186 D A2dpService: Received stop request...Stopping profile...
08-10 07:41:04.460  4186  4409 D A2dpStateMachine: Exit Disconnected: -1
08-10 07:41:04.464  4186  4272 D BluetoothAdapterState: Stopping profile services that were post enabled
08-10 07:41:04.464  4186  4186 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-10 07:41:04.465  4186  4186 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 07:41:04.466  4186  4186 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 07:41:04.466  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30b96ad3
08-10 07:41:04.466  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-10 07:41:04.466  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-10 07:41:04.468  4186  4186 D HidService: Received stop request...Stopping profile...
08-10 07:41:04.468  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30b96ad3
08-10 07:41:04.470   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 466us total 21.792ms
08-10 07:41:04.472  7062  7062 D BluetoothInputDevice: Proxy object disconnected
08-10 07:41:04.472  7062  7062 D HidProfile: Bluetooth service disconnected
,08-10 07:41:04.473  4186  4186 D HealthService: Received stop request...Stopping profile...
08-10 07:41:04.473  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30b96ad3
08-10 07:41:04.475  4186  4186 D PanService: Received stop request...Stopping profile...
08-10 07:41:04.477  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30b96ad3
08-10 07:41:04.478  4186  4186 D HeadsetStateMachine: Unbinding service...
08-10 07:41:04.481  4186  4186 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 07:41:04.481  4186  4186 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 07:41:04.481  4186  4186 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 07:41:04.481  4186  4186 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 07:41:04.481  4186  4186 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 07:41:04.481  4186  4186 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 07:41:04.481  4186  4186 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 07:41:04.481  4186  4186 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 07:41:04.483  4186  4186 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 07:41:04.483  4186  4186 D BtGatt.GattService: stop()
08-10 07:41:04.483  4186  4186 D BtGatt.AdvertiseManager: advertise clients cleared
08-10 07:41:04.484  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30b96ad3
,08-10 07:41:04.488  7062  7062 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 07:41:04.488  7062  7062 D PanProfile: Bluetooth service disconnected
08-10 07:41:04.488  4186  4186 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 07:41:04.488  4186  4186 D BluetoothMapService: stop()
08-10 07:41:04.490  4186  4186 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 07:41:04.490  4186  4186 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 07:41:04.491  4186  4186 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@30b96ad3
08-10 07:41:04.491   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.591ms
08-10 07:41:04.493  4186  4186 I BluetoothA2dpServiceJni: cleanupNative
08-10 07:41:04.494  4186  4410 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-10 07:41:04.494  4186  4186 I GKI_LINUX: GKI_exit_task 2 done
08-10 07:41:04.494  4186  4186 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-10 07:41:04.494  4186  4186 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 07:41:04.494  4186  4186 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 07:41:04.495  4186  4186 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 07:41:04.495  4186  4186 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-10 07:41:04.495  4186  4186 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 07:41:04.495  4186  4186 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 07:41:04.495  4186  4186 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 07:41:04.496  4186  4186 V BluetoothMapService: Handler(): got msg=4
08-10 07:41:04.496  4186  4186 D BluetoothMapService: MAP Service closeService in
08-10 07:41:04.496  4186  4186 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 07:41:04.496  4186  4186 V BluetoothMapService: MAP Service closeService out
08-10 07:41:04.497  4186  4186 D BluetoothMapService: cleanup()
08-10 07:41:04.497  4186  4186 D BluetoothMapService: MAP Service closeService in
08-10 07:41:04.497  4186  4186 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 07:41:04.497  4186  4186 V BluetoothMapService: MAP Service closeService out
08-10 07:41:04.498  4186  4272 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 07:41:04.498  4186  4272 D BluetoothAdapterProperties: Setting state to 10
08-10 07:41:04.498  4186  4272 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 07:41:04.498  1037  1119 D BluetoothManagerService: Message: 60
08-10 07:41:04.498  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 07:41:04.498  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-10 07:41:04.499  4186  4272 I BluetoothAdapterState: Entering OffState
08-10 07:41:04.499  7062  7083 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 07:41:04.500  7062  7082 D BluetoothMap: onBluetoothStateChange: up=false
08-10 07:41:04.502  7062  7083 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 07:41:04.502  1853  2414 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 07:41:04.503  7062  7082 D BluetoothPan: onBluetoothStateChange on: false
08-10 07:41:04.504  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 07:41:04.504  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 07:41:04.505  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 07:41:04.505  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 07:41:04.506  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-10 07:41:04.506  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-10 07:41:04.509  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-10 07:41:04.509  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-10 07:41:04.510  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2ddb5d6a mBinding = false
08-10 07:41:04.510  1037  1119 D BluetoothManagerService: Sending unbind request.
08-10 07:41:04.513   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 19.865ms
08-10 07:41:04.520  4186  4277 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-10 07:41:04.520  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-10 07:41:04.520  4186  4186 I GKI_LINUX: GKI_exit_task 1 done
08-10 07:41:04.520  4186  4186 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-10 07:41:04.521  4186  4186 I BluetoothServiceJni: cleanupNative: return from cleanup
08-10 07:41:04.521  4186  4186 I art     : --- WEIRD: removing null entry 246
08-10 07:41:04.521  4186  4186 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-10 07:41:04.521  4186  4186 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-10 07:41:04.527  4186  4186 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-10 07:41:04.530  4186  4186 I art     : System.exit called, status: 0
08-10 07:41:04.530  4186  4186 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-10 07:41:04.532  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:04.532  7062  7062 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 07:41:04.533  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:04.533  7062  7062 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-10 07:41:04.533  7062  7062 D LGBluetoothEventManager: [BTUI] clear device connection state
08-10 07:41:04.534  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:04.535  1944  2144 D LGBluetoothAPIService: Message: 2
08-10 07:41:04.535  1944  2144 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2cd10892 mBinding = false
08-10 07:41:04.535  1944  2144 D LGBluetoothAPIService: Sending unbind request.
08-10 07:41:04.537  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 07:41:04.540  7062  7062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 07:41:04.553  1605  1605 D BluetoothAdapter: 745553867: getState() :  mService = null. Returning STATE_OFF
,08-10 07:41:04.553  1605  1605 D BluetoothAdapter: 745553867: getState() :  mService = null. Returning STATE_OFF
08-10 07:41:04.559  7062  7062 D DockEventReceiver: finishStartingService: stopping service
08-10 07:41:04.564   315  1387 V AudioFlinger: 4186 died, releasing its sessions
08-10 07:41:04.564   315  1387 V AudioFlinger:  pid 1853 @ 0
08-10 07:41:04.564   315  1387 V AudioFlinger:  pid 3350 @ 1
08-10 07:41:04.564   315  1387 V AudioFlinger:  pid 3350 @ 2
,08-10 07:41:04.565  7062  7062 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-10 07:41:04.592  1037  2011 I ActivityManager: Process com.android.bluetooth (pid 4186) has died
08-10 07:41:04.593  1037  2011 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-10 07:41:04.598  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 07:41:04.609  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:04.625  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 07:41:04.635  7176  7202 W FormManager: Network not available. Please check & try again.
,08-10 07:41:04.639  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:04.643  7062  7062 D BluetoothPermissionRequest: onReceive
08-10 07:41:04.646  7062  7062 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 07:41:04.647  7062  7062 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-10 07:41:04.649  7062  7062 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 07:41:04.705  1037  1879 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7205 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-10 07:41:04.725  7176  7204 V FormManager: Network unavailable.
,08-10 07:41:04.734  7176  7204 V FormManager: Network unavailable.
08-10 07:41:04.745  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 07:41:04.746  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 07:41:04.746  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 07:41:04.746  7062  7062 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 07:41:04.748  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-10 07:41:04.759  7062  7062 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 07:41:04.759  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 07:41:04.759  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 07:41:04.759  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 07:41:04.759  7062  7062 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 07:41:04.759  7062  7062 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-10 07:41:04.773  1037  1974 I ActivityManager: Killing 6411:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-10 07:41:04.781  7205  7205 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-10 07:41:04.782  7205  7205 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 07:41:04.782  7205  7205 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-10 07:41:04.783  7205  7205 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 07:41:04.801  7205  7205 D BluetoothAdapterApp: Loading JNI Library
,08-10 07:41:04.832  7205  7205 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@7de1ff8 Instance Count = 1
,08-10 07:41:04.844  1037  1578 W libprocessgroup: failed to open /acct/uid_10004/pid_6411/cgroup.procs: No such file or directory
,08-10 07:41:04.850  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 07:41:04.851  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:04.852  7205  7205 D BluetoothAdapterApp: onCreate
08-10 07:41:04.856  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:04.861  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 07:41:04.875  7104  7104 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-10 07:41:04.875  7104  7104 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 07:41:04.876  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:04.880  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 07:41:04.884  4638  7225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 07:41:04.885  7176  7229 W FormManager: Network not available. Please check & try again.
08-10 07:41:04.887  7205  7205 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-10 07:41:04.887  7205  7205 D ProfileConfigQcom: Adding HeadsetService
08-10 07:41:04.888  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 07:41:04.888  7205  7205 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-10 07:41:04.888  4638  7225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:04.889  7205  7205 D ProfileConfigQcom: Adding A2dpService
08-10 07:41:04.889  4638  7224 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 07:41:04.889  7205  7205 D ProfileConfigQcom: [BTUI] HidService is supported
08-10 07:41:04.890  7205  7205 D ProfileConfigQcom: Adding HidService
08-10 07:41:04.890  7205  7205 D ProfileConfigQcom: [BTUI] HealthService is supported
08-10 07:41:04.891  7205  7205 D ProfileConfigQcom: Adding HealthService
08-10 07:41:04.892  7205  7205 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-10 07:41:04.893  7205  7205 D ProfileConfigQcom: [BTUI] PanService is supported
08-10 07:41:04.893  7205  7205 D ProfileConfigQcom: Adding PanService
08-10 07:41:04.894  7205  7205 D ProfileConfigQcom: [BTUI] GattService is supported
08-10 07:41:04.894  7205  7205 D ProfileConfigQcom: Adding GattService
08-10 07:41:04.894  7205  7205 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-10 07:41:04.894  7205  7205 D ProfileConfigQcom: Adding BluetoothMapService
08-10 07:41:04.895  7205  7205 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-10 07:41:04.896  7205  7205 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-10 07:41:04.897  7176  7230 V FormManager: Network unavailable.
,08-10 07:41:04.901  7062  7062 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-10 07:41:04.903  7205  7205 V LGMDMManagerInternal: Create singleton instance
08-10 07:41:04.905  7176  7230 V FormManager: Network unavailable.
08-10 07:41:04.907  7134  7134 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 07:41:04.909  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 07:41:04.909  7134  7134 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-10 07:41:04.941  7134  7134 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:04.941  7134  7134 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:04.947  7134  7134 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-10 07:41:04.949  7134  7134 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-10 07:41:04.949  7134  7134 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-10 07:41:04.949  7134  7134 V SoundPool: doLoad: loading sample sampleID=1
08-10 07:41:04.949  7134  7134 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 07:41:04.950  7134  7233 V SoundPool: Start decode
08-10 07:41:04.950  7134  7233 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-10 07:41:04.951   315  2147 V MediaPlayerService: decode(23, 10857164, 17813)
08-10 07:41:04.951   315  2147 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-10 07:41:04.951   315  2147 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-10 07:41:04.951   315  2147 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-10 07:41:04.951   315  2147 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-10 07:41:04.951   315  2147 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-10 07:41:04.951   315  2147 V MediaPlayerService: player type = 3
08-10 07:41:04.951   315  2147 V AwesomePlayer: AwesomePlayer create()
08-10 07:41:04.952   315  2147 V AwesomePlayer: reset_l() 
08-10 07:41:04.952   315  2147 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:04.952   315  2147 V AwesomePlayer: setAudioSink() 
08-10 07:41:04.952   315  2147 V AwesomePlayer: reset_l() 
08-10 07:41:04.952   315  2147 V AudioCache: notify(0xb1432300, 8, 0, 0)
08-10 07:41:04.952   315  2147 V AudioCache: ignored
08-10 07:41:04.952   315  2147 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:04.952   315  2147 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-10 07:41:04.952   315  2147 V AwesomePlayer: setDataSource_l dataSource
08-10 07:41:04.952   315  2147 V LGParserOSAL: SniffLGParser start
08-10 07:41:04.952   315  2147 V LGParserOSAL: MainType:5, SubType=0
08-10 07:41:04.952   315  2147 V LGParserOSAL: #### check Mime : application/ogg
08-10 07:41:04.952   315  2147 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-10 07:41:04.952   315  2147 E MediaExtractor: Use LGExtractor :application/ogg 
08-10 07:41:04.953  7134  7134 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-10 07:41:04.953  6852  6852 D UEI.SmartControl: QS Service created
,08-10 07:41:04.954  7134  7134 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 07:41:04.954  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 07:41:04.964  6852  6852 I UEI.SmartControl: Service initServices...
08-10 07:41:04.964  6852  6852 D UEI.SmartControl: QS start get config
08-10 07:41:04.966  7134  7134 V LGMDMManager: Create singleton instance
,08-10 07:41:04.981  7205  7205 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:04.984  7205  7205 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 07:41:04.984  7205  7205 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 07:41:04.984  7205  7205 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 07:41:04.985  7205  7205 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:04.985  7205  7205 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 07:41:04.992  7155  7155 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-10 07:41:05.000   315  2147 V LGParserOSAL: supported mime: application/ogg
08-10 07:41:05.000   315  2147 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-10 07:41:05.000   315  2147 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-10 07:41:05.000   315  2147 V AwesomePlayer: mBitrate = -1 bits/sec
08-10 07:41:05.000   315  2147 V AwesomePlayer: AudioTrack Setting
08-10 07:41:05.000   315  2147 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-10 07:41:05.000   315  2147 V AwesomePlayer: setAudioSource() 
08-10 07:41:05.000   315  2147 V MediaPlayerService: prepare
08-10 07:41:05.000   315  2147 V AwesomePlayer: prepareAsync_l() 
08-10 07:41:05.001   315  2147 V MediaPlayerService: wait for prepare
,08-10 07:41:05.001   315  7235 V AwesomePlayer: onPrepareAsyncEvent() 
08-10 07:41:05.001   315  7235 V AwesomePlayer: initAudioDecoder() 
08-10 07:41:05.001   315  7235 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 07:41:05.001   315  7235 V AudioSystem: isOffloadSupported()
08-10 07:41:05.001   315  7235 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 07:41:05.001   315  7235 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 07:41:05.001   315  7235 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 07:41:05.001   315  7235 V AwesomePlayer: getUseOffload() = 0 
08-10 07:41:05.001   315  7235 V OMXCodec: OMXCodec::Create
08-10 07:41:05.001   315  7235 V OMXCodec: findMatchingCodecs()
08-10 07:41:05.001   315  7235 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-10 07:41:05.001   315  7235 V OMXCodec: matchingCodecs.size()=1
08-10 07:41:05.001   315  7235 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-10 07:41:05.003   315  7235 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-10 07:41:05.003   315  7235 V LGCodecAdapter: LG Codec Adapter start
08-10 07:41:05.004   315  7235 V OMXCodec: OMXCodec Createtor
08-10 07:41:05.004   315  7235 V OMXCodec: setComponentRole
08-10 07:41:05.004   315  7235 V OMXCodec: configureCodec protected=0
08-10 07:41:05.004   315  7235 V LGCodecAdapter: called getLGCodecSpecificData
08-10 07:41:05.004   315  7235 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-10 07:41:05.004   315  7235 V LGCodecOSAL: Called LGconfigureCodecMETA
08-10 07:41:05.004   315  7235 V LGCodecOSAL: Called LGconfigureCodecMSG
08-10 07:41:05.004   315  7235 V LGCodecOSAL: Not support LGCodec
08-10 07:41:05.004   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 07:41:05.004   315  7235 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-10 07:41:05.004   315  7235 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-10 07:41:05.004   315  7235 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-10 07:41:05.004   315  7235 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,08-10 07:41:05.004   315  7235 V AudioSystem: isOffloadSupported()
08-10 07:41:05.004   315  7235 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 07:41:05.004   315  7235 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 07:41:05.004   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-10 07:41:05.004   315  7235 V OMXCodec: init()
08-10 07:41:05.004   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-10 07:41:05.004   315  7235 V OMXCodec: allocateBuffers
08-10 07:41:05.004   315  7235 V OMXCodec: allocateBuffersOnPort portIndex=0
08-10 07:41:05.004   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-10 07:41:05.004   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-10 07:41:05.004   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-10 07:41:05.004   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-10 07:41:05.004   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-10 07:41:05.004   315  7235 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 07:41:05.005   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 07:41:05.005   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-10 07:41:05.005   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
08-10 07:41:05.005   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-10 07:41:05.005   315  7235 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cb060 on output port
08-10 07:41:05.005   315  7235 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 07:41:05.005   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 07:41:05.005   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 07:41:05.005   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-10 07:41:05.005   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-10 07:41:05.005   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-10 07:41:05.005   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-10 07:41:05.005   315  7235 V OMXCodec: init() mAsyncCompletion wait free! 
08-10 07:41:05.005   315  7235 V AwesomePlayer: finishAsyncPrepare_l() 
08-10 07:41:05.005   315  7235 V AudioCache: notify(0xb1432300, 5, 0, 0)
08-10 07:41:05.005   315  7235 V AudioCache: ignored
08-10 07:41:05.005   315  7235 V AudioCache: notify(0xb1432300, 1, 0, 0)
08-10 07:41:05.005   315  7235 V AudioCache: prepared
08-10 07:41:05.005   315  2147 V AudioCache: wait - success
08-10 07:41:05.005   315  2147 V MediaPlayerService: start
08-10 07:41:05.005   315  2147 V AwesomePlayer: play_l() 
08-10 07:41:05.005   315  2147 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-10 07:41:05.005   315  2147 V AwesomePlayer: createAudioPlayer_l
08-10 07:41:05.005   315  2147 V AwesomePlayer: seekAudioIfNecessary_l() 
08-10 07:41:05.005   315  2147 V AwesomePlayer: startAudioPlayer_l() 
08-10 07:41:05.005   315  2147 D AudioPlayer: start of Playback, useOffload 0
08-10 07:41:05.005   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 07:41:05.005   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.dec,oder] setState mState=4 , newState=7
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885888
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044847712
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-10 07:41:05.007   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
,08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-10 07:41:05.008   315  7237 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on output port
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-10 07:41:05.008   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-10 07:41:05.008   315  2147 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-10 07:41:05.009   315  2147 V AudioCache: notify(0xb1432300, 6, 0, 0)
08-10 07:41:05.009   315  2147 V AudioCache: ignored
08-10 07:41:05.009   315  2147 V MediaPlayerService: wait for playback complete
08-10 07:41:05.009   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.009   315  7238 V AudioCache: memcpy(0xaf004000, 0xb16e4000, 4096)
08-10 07:41:05.011   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.011   315  7238 V AudioCache: memcpy(0xaf005000, 0xb16e4000, 4096)
08-10 07:41:05.011   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.011   315  7238 V AudioCache: memcpy(0xaf006000, 0xb16e4000, 4096)
08-10 07:41:05.011   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.011   315  7238 V AudioCache: memcpy(0xaf007000, 0xb16e4000, 4096)
08-10 07:41:05.012   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.012   315  7238 V AudioCache: memcpy(0xaf008000, 0xb16e4000, 4096)
08-10 07:41:05.012   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.012   315  7238 V AudioCache: memcpy(0xaf009000, 0xb16e4000, 4096)
08-10 07:41:05.012   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.012   315  7238 V AudioCache: memcpy(0xaf00a000, 0xb16e4000, 4096)
08-10 07:41:05.013   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.013   315  7238 V AudioCache: memcpy(0xaf00b000, 0xb16e4000, 4096)
08-10 07:41:05.013   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.013   315  7238 V AudioCache: memcpy(0xaf00c000, 0xb16e4000, 4096)
08-10 07:41:05.014   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.014   315  7238 V AudioCache: memcpy(0xaf00d000, 0xb16e4000, 4096)
08-10 07:41:05.014   315  7238 V AudioCache: write(0xb16e4000, 4096)
,08-10 07:41:05.014   315  7238 V AudioCache: memcpy(0xaf00e000, 0xb16e4000, 4096)
08-10 07:41:05.014   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.014   315  7238 V AudioCache: memcpy(0xaf00f000, 0xb16e4000, 4096)
,08-10 07:41:05.015   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.015   315  7238 V AudioCache: memcpy(0xaf010000, 0xb16e4000, 4096)
08-10 07:41:05.015   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.015   315  7238 V AudioCache: memcpy(0xaf011000, 0xb16e4000, 4096)
08-10 07:41:05.015   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.015   315  7238 V AudioCache: memcpy(0xaf012000, 0xb16e4000, 4096)
08-10 07:41:05.016   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.016   315  7238 V AudioCache: memcpy(0xaf013000, 0xb16e4000, 4096)
08-10 07:41:05.016   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.016   315  7238 V AudioCache: memcpy(0xaf014000, 0xb16e4000, 4096)
08-10 07:41:05.016   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.016   315  7238 V AudioCache: memcpy(0xaf015000, 0xb16e4000, 4096)
08-10 07:41:05.017   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.017   315  7238 V AudioCache: memcpy(0xaf016000, 0xb16e4000, 4096)
08-10 07:41:05.017   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.017   315  7238 V AudioCache: memcpy(0xaf017000, 0xb16e4000, 4096)
08-10 07:41:05.018   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.018   315  7238 V AudioCache: memcpy(0xaf018000, 0xb16e4000, 4096)
08-10 07:41:05.018   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.018   315  7238 V AudioCache: memcpy(0xaf019000, 0xb16e4000, 4096)
08-10 07:41:05.018   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.018   315  7238 V AudioCache: memcpy(0xaf01a000, 0xb16e4000, 4096)
08-10 07:41:05.019   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.019   315  7238 V AudioCache: memcpy(0xaf01b000, 0xb16e4000, 4096)
08-10 07:41:05.019   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.019   315  7238 V AudioCache: memcpy(0xaf01c000, 0xb16e4000, 4096)
08-10 07:41:05.019   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.019   315  7238 V AudioCache: memcpy(0xaf01d000, 0xb16e4000, 4096)
08-10 07:41:05.020   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.020   315  7238 V AudioCache: memcpy(0xaf01e000, 0xb16e4000, 4096)
08-10 07:41:05.020   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.020   315  7238 V AudioCache: memcpy(0xaf01f000, 0xb16e4000, 4096)
08-10 07:41:05.020   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.020   315  7238 V AudioCache: memcpy(0xaf020000, 0xb16e4000, 4096)
08-10 07:41:05.021   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.021   315  7238 V AudioCache: memcpy(0xaf021000, 0xb16e4000, 4096)
08-10 07:41:05.021   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.021   315  7238 V AudioCache: memcpy(0xaf022000, 0xb16e4000, 4096)
08-10 07:41:05.022   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.022   315  7238 V AudioCache: memcpy(0xaf023000, 0xb16e4000, 4096)
08-10 07:41:05.022   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.022   315  7238 V AudioCache: memcpy(0xaf024000, 0xb16e4000, 4096)
08-10 07:41:05.027   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.027   315  7238 V AudioCache: memcpy(0xaf025000, 0xb16e4000, 4096)
08-10 07:41:05.027   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.027   315  7238 V AudioCache: memcpy(0xaf026000, 0xb16e4000, 4096)
08-10 07:41:05.028   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.028   315  7238 V AudioCache: memcpy(0xaf027000, 0xb16e4000, 4096)
08-10 07:41:05.028   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.028   315  7238 V AudioCache: memcpy(0xaf028000, 0xb16e4000, 4096)
08-10 07:41:05.029   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.029   315  7238 V AudioCache: memcpy(0xaf029000, 0xb16e4000, 4096)
08-10 07:41:05.029   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.029   315  7238 V AudioCache: mem,cpy(0xaf02a000, 0xb16e4000, 4096)
08-10 07:41:05.030   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.030   315  7238 V AudioCache: memcpy(0xaf02b000, 0xb16e4000, 4096)
08-10 07:41:05.030   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.030   315  7238 V AudioCache: memcpy(0xaf02c000, 0xb16e4000, 4096)
08-10 07:41:05.030   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.031   315  7238 V AudioCache: memcpy(0xaf02d000, 0xb16e4000, 4096)
08-10 07:41:05.031   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.031   315  7238 V AudioCache: memcpy(0xaf02e000, 0xb16e4000, 4096)
08-10 07:41:05.031  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 07:41:05.031   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.032   315  7238 V AudioCache: memcpy(0xaf02f000, 0xb16e4000, 4096)
08-10 07:41:05.032  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-10 07:41:05.032   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.032   315  7238 V AudioCache: memcpy(0xaf030000, 0xb16e4000, 4096)
08-10 07:41:05.033   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.033   315  7238 V AudioCache: memcpy(0xaf031000, 0xb16e4000, 4096)
08-10 07:41:05.033   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.033   315  7238 V AudioCache: memcpy(0xaf032000, 0xb16e4000, 4096)
08-10 07:41:05.033   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.033   315  7238 V AudioCache: memcpy(0xaf033000, 0xb16e4000, 4096)
08-10 07:41:05.034  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5444
08-10 07:41:05.034   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.034   315  7238 V AudioCache: memcpy(0xaf034000, 0xb16e4000, 4096)
08-10 07:41:05.034   315  7238 V AudioCache: write(0xb16e4000, 4096)
08-10 07:41:05.034   315  7238 V AudioCache: memcpy(0xaf035000, 0xb16e4000, 4096)
08-10 07:41:05.034   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-10 07:41:05.034   315  7238 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-10 07:41:05.034   315  7238 V AwesomePlayer: postAudioEOS() 
08-10 07:41:05.034   315  7238 V AudioCache: write(0xb16e4000, 280)
08-10 07:41:05.034   315  7238 V AudioCache: memcpy(0xaf036000, 0xb16e4000, 280)
08-10 07:41:05.036   315  7235 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-10 07:41:05.036   315  7235 V AwesomePlayer: onStreamDone
08-10 07:41:05.036   315  7235 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-10 07:41:05.036   315  7235 V AudioCache: notify(0xb1432300, 2, 0, 0)
08-10 07:41:05.036   315  7235 V AudioCache: playback complete
08-10 07:41:05.036   315  7235 V AwesomePlayer: pause_l() 
08-10 07:41:05.036   315  7235 V AudioCache: notify(0xb1432300, 7, 0, 0)
08-10 07:41:05.036   315  7235 V AudioCache: ignored
08-10 07:41:05.036   315  7235 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:05.036   315  2147 V AudioCache: wait - success
08-10 07:41:05.036   315  2147 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,08-10 07:41:05.036   315  7235 D AudioPlayer: Pause Playback at 1068125
08-10 07:41:05.036   315  2147 V AwesomePlayer: reset_l() 
08-10 07:41:05.036   315  2147 V AudioCache: notify(0xb1432300, 8, 0, 0)
08-10 07:41:05.036   315  2147 V AudioCache: ignored
08-10 07:41:05.036   315  2147 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:05.036   315  2147 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-10 07:41:05.036   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-10 07:41:05.036   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-10 07:41:05.036   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-10 07:41:05.037   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
,08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
,08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 1
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
,08-10 07:41:05.037   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 07:41:05.037   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-10 07:41:05.037   315  7237 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-10 07:41:05.037   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 07:41:05.037   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-10 07:41:05.037   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-10 07:41:05.038   315  2147 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-10 07:41:05.038   315  2147 D AudioPlayer: AudioPlayer releasing audio source
08-10 07:41:05.039   315  2147 D AudioPlayer: AudioPlayer done releasing audio source
08-10 07:41:05.039   315  2147 V AwesomePlayer: reset_l() 
08-10 07:41:05.039   315  2147 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:05.039   315  2147 V AwesomePlayer: ~AwesomePlayer call
08-10 07:41:05.039   315  2147 V AwesomePlayer: reset_l() 
08-10 07:41:05.039   315  2147 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:05.039  7134  7233 V SoundPool: close(31)
08-10 07:41:05.039  7134  7233 V SoundPool: pointer = 0xa0034000, size = 205080, sampleRate = 48000, numChannels = 2
,08-10 07:41:05.200  6852  6852 I UEI.SmartControl: Supports setup maps: true
,08-10 07:41:05.203  6852  6852 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 07:41:05.203  6852  6852 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 07:41:05.203  6852  6852 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-10 07:41:05.203  6852  6852 I UEI.SmartControl: ### init IR Blaster...
,08-10 07:41:05.206  6852  6852 D serial_port: Configuring serial port
08-10 07:41:05.207  6852  6852 E UEI.SmartControl: UEIBLaster setting for 616
08-10 07:41:05.207  6852  6852 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 07:41:05.207  6852  6852 I UEI.SmartControl: configuring settings for MAXQ616
08-10 07:41:05.207  6852  6852 I UEI.SmartControl: Get version...
08-10 07:41:05.226  6852  7239 D UEI.SmartControl: serial port data available: 21
,08-10 07:41:05.253  6852  6852 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-10 07:41:05.253  6852  6852 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-10 07:41:05.253  6852  6852 I UEI.SmartControl: QS saving settings...
08-10 07:41:05.256  6852  6852 D UEI.SmartControl: IR Blaster version: 25672567
08-10 07:41:05.274  6852  7239 D UEI.SmartControl: serial port data available: 4
,08-10 07:41:05.307  6852  7245 I UEI.SmartControl: Device manager: loading config....
,08-10 07:41:05.309  6852  6852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 07:41:05.311  6852  7245 D UEI.SmartControl: ----------- loading internal config...
08-10 07:41:05.314  6852  6852 E UEI.SmartControl: Services init done
08-10 07:41:05.314  6852  6852 D UEI.SmartControl: QS Service init finished
08-10 07:41:05.316  6852  6852 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 07:41:05.316  6852  6852 D UEI.SmartControl: QS Service version code: 201091
08-10 07:41:05.317  6852  6852 D UEI.SmartControl: Service requested: Control
08-10 07:41:05.326  6852  7245 E UEI.SmartControl: Loading SETTINGS...
08-10 07:41:05.328  6852  6852 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-10 07:41:05.333  6852  6852 D UEI.SmartControl: Internal service binding...
08-10 07:41:05.333  7134  7134 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-10 07:41:05.336  6852  6867 I UEI.SmartControl: ------ IControl API: 11
08-10 07:41:05.336  6852  6867 D UEI.SmartControl: File observer start...
08-10 07:41:05.338  6852  6867 E UEI.SmartControl: IR Port is disabled: false
08-10 07:41:05.339  6852  6867 D UEI.SmartControl: Starting file observer...
08-10 07:41:05.339  6852  6867 I UEI.SmartControl: Registering callback...
08-10 07:41:05.340  6852  6868 I UEI.SmartControl: ------ IControl API: 19
08-10 07:41:05.344  6852  6868 I UEI.SmartControl: Registering Services Ready callback...
08-10 07:41:05.345  6852  7245 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-10 07:41:05.365  6852  7244 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 07:41:05.366  6852  7244 D UEI.SmartControl: -----service ready thread exits
08-10 07:41:05.367  7134  7150 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-10 07:41:05.368  7134  7231 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-10 07:41:05.368  7134  7231 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-10 07:41:05.372  7134  7134 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-10 07:41:05.373  7134  7134 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-10 07:41:05.374  6852  6867 I UEI.SmartControl: ------ IControl API: 8
08-10 07:41:05.377  7134  7134 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-10 07:41:05.378  7134  7134 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-10 07:41:05.379  7134  7134 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,08-10 07:41:05.379  7134  7134 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-10 07:41:05.381  7134  7134 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-10 07:41:05.386  7134  7134 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-10 07:41:05.390  7134  7134 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-10 07:41:05.395  7134  7134 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 07:41:05.396  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 07:41:05.397  7134  7134 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 07:41:05.398  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-10 07:41:05.405  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 07:41:05.406  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-10 07:41:05.407  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-10 07:41:05.408  7134  7134 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470807665408]
08-10 07:41:05.409  7134  7134 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-10 07:41:05.411  1037  1897 I ActivityManager: Killing 6617:com.lge.email/u0a23 (adj 15): empty #17
08-10 07:41:05.437  7134  7250 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-10 07:41:05.443  1037  1897 I ActivityManager: Killing 6589:com.android.contacts/u0a19 (adj 15): empty #18
08-10 07:41:05.472  1037  1649 W libprocessgroup: failed to open /acct/uid_10023/pid_6617/cgroup.procs: No such file or directory
,08-10 07:41:05.477  1037  1997 W libprocessgroup: failed to open /acct/uid_10019/pid_6589/cgroup.procs: No such file or directory
08-10 07:41:05.483  7134  7134 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-10 07:41:05.483  7134  7134 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-10 07:41:05.484  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-10 07:41:05.484  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-10 07:41:05.485  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-10 07:41:05.485  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-10 07:41:05.485  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-10 07:41:05.498  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-10 07:41:06.428  1037  1954 D WifiServiceImplEx: setWifiEnabled: true pid=6960, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-10 07:41:06.429  1037  1954 D WifiService: setWifiEnabled: true pid=6960, uid=10118
,08-10 07:41:06.429  1037  1954 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 07:41:06.444  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:06.448  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-10 07:41:06.453  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:06.456  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:06.461  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:06.468  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,08-10 07:41:06.471  1037  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:06.480  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:06.484  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:06.487  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 07:41:06.494  1037  1541 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-10 07:41:06.494  1037  1541 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-10 07:41:06.496  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-10 07:41:06.496  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 07:41:06.496  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-10 07:41:06.496  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 07:41:06.496  1037  1541 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-10 07:41:06.496  1037  1541 E WifiHW  : unknown target_country: EU , set to default
08-10 07:41:06.496  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-10 07:41:06.496  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-10 07:41:06.496  1037  1541 I WifiUtil: gEnableBmps=1
,08-10 07:41:06.509  6461  7103 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-10 07:41:06.513  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 07:41:06.513  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 07:41:06.513  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-10 07:41:06.523  5753  5753 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 07:41:06.530  5753  5753 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-10 07:41:06.557  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:06.590  1037  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:06.639  1037  1997 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7269 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-10 07:41:06.644  1037  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:06.646  1037  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 07:41:06.709  7269  7269 I AppUp4:AppBoxCP: onCreate
08-10 07:41:06.710  7269  7269 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-10 07:41:06.719  7269  7269 I AppUp4:DB:  setFingerPrint start
,08-10 07:41:06.720  7269  7269 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-10 07:41:06.728  7269  7269 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-10 07:41:06.728  7269  7269 I AppUp4:DB:  SDK version = 21
08-10 07:41:06.728  7269  7269 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-10 07:41:06.731  7269  7269 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-10 07:41:06.733  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 07:41:06.733  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:06.735  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-10 07:41:06.736  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 07:41:06.743  7269  7269 I AppUp4:CustModeStarterReceiver: onReceive
08-10 07:41:06.793  7269  7269 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:06.793  7269  7269 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:06.808  7269  7269 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7297cc2
08-10 07:41:06.808  7269  7269 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 07:41:06.808  7269  7269 D AppUp4:CustFacade: isPhone : true
08-10 07:41:06.810  7269  7269 D AppUp4:CustModeStarterReceiver: begin check event
08-10 07:41:06.810  7269  7269 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-10 07:41:06.810  7269  7269 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-10 07:41:06.812  7269  7289 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-10 07:41:06.812  7269  7289 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,08-10 07:41:06.813  7269  7289 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-10 07:41:06.818  1037  1925 I ActivityManager: Killing 6641:com.android.gallery3d/u0a27 (adj 15): empty #17
08-10 07:41:06.854  1037  1052 W libprocessgroup: failed to open /acct/uid_10027/pid_6641/cgroup.procs: No such file or directory
08-10 07:41:06.856  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:06.857  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-10 07:41:06.863  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:06.865  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:06.872  4638  7292 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 07:41:06.877  4638  7293 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:06.877  4638  7293 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:06.961  1037  2034 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7297 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 07:41:07.019  7297  7297 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:07.020  7297  7297 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:07.021  7297  7297 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 07:41:07.022  7297  7297 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 07:41:07.114  7297  7297 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 07:41:07.131  7297  7297 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-10 07:41:07.167  7297  7297 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 07:41:07.195  7297  7297 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:07.195  7297  7297 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:07.275  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-10 07:41:07.278   310   895 D SoftapController: Softap fwReload - Ok
08-10 07:41:07.281  1037  1541 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (780ms)
08-10 07:41:07.285   310   895 D CommandListener: Setting iface cfg
08-10 07:41:07.285   310   895 D CommandListener: Trying to bring down wlan0
08-10 07:41:07.285   310   895 D CommandListener: Clearing all IP addresses on wlan0
08-10 07:41:07.287  1037  1541 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-10 07:41:07.280  7328  7328 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 07:41:07.293  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 07:41:07.293  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-10 07:41:07.293  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 07:41:07.293  1037  1119 D Tethering: InitialState.processMessage what=4
08-10 07:41:07.294  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-10 07:41:07.290  7328  7328 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:07.302  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-10 07:41:07.303  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:07.304  1037  1541 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-10 07:41:07.304  1037  1541 D WifiMonitor: connecting to supplicant
08-10 07:41:07.305  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:07.306  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:07.313  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-10 07:41:07.339  7328  7328 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-10 07:41:07.380  7328  7328 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-10 07:41:07.380  7328  7328 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-10 07:41:07.382  1037  1879 I art     : Explicit concurrent mark sweep GC freed 68325(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 1.340ms total 144.065ms
,08-10 07:41:07.443  7297  7297 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 07:41:07.466  7328  7328 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-10 07:41:07.477  3350  3350 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 07:41:07.477  3350  3350 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:07.477  3350  3350 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-10 07:41:07.479  7297  7297 I HubEmail: JNI_OnLoad()
08-10 07:41:07.479  7297  7297 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 07:41:07.479  7297  7297 I HubEmail: registerNatives()
08-10 07:41:07.479  7297  7297 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 07:41:07.479  7297  7297 I HubEmail: registerNativeMethods()
08-10 07:41:07.479  7297  7297 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 07:41:07.479  7297  7297 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-10 07:41:07.485  7176  7343 V FormManager: Network unavailable.
08-10 07:41:07.485  7176  7342 W FormManager: Network not available. Please check & try again.
08-10 07:41:07.495  7328  7328 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-10 07:41:07.500  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-10 07:41:07.502  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-10 07:41:07.503  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-10 07:41:07.503  1037  7345 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-10 07:41:07.503  1037  7345 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 07:41:07.503  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-10 07:41:07.503  1037  1541 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-10 07:41:07.504  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:07.504  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:07.505  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:07.505  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:07.505  1037  1541 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-10 07:41:07.505  1037  1541 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-10 07:41:07.506  1037  1541 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-10 07:41:07.506  1037  1541 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-10 07:41:07.507  1037  1541 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-10 07:41:07.516  7328  7328 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-10 07:41:07.517  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 07:41:07.517  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 07:41:07.517  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 07:41:07.517  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,08-10 07:41:07.517  1037  7345 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 07:41:07.517  1037  7345 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-10 07:41:07.535  1037  2036 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7346 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-10 07:41:07.537  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 07:41:07.537  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-10 07:41:07.537  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 07:41:07.537  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.537  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.538  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.538  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.538  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 07:41:07.538  1037  1541 D WifiNative-wlan0: doBoolean: SET update_config 1
08-10 07:41:07.539  1944  1944 D WfdService: Waiting for WifiP2p enabling
,08-10 07:41:07.539  1037  1541 D WifiNative-wlan0: SET update_config 1: returned true
08-10 07:41:07.539  1037  1541 D WifiConfigStore: Loading config and enabling all networks 
08-10 07:41:07.540  1037  1541 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-10 07:41:07.540  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:07.540  1037  1541 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-10 07:41:07.541  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:07.541  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:07.541  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:07.541  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:07.541  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:07.541  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:07.541  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:07.541  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:07.541  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:07.541  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:07.541  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:07.543  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:07.543  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:07.543  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:07.543  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:07.543  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:07.543  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:07.543  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:07.543  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:07.543  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:07.543  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:07.543  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:07.544  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-10 07:41:07.544  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-10 07:41:07.547  7176  7343 V FormManager: Network unavailable.
08-10 07:41:07.549  1037  1541 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-10 07:41:07.556  1037  2011 I ActivityManager: Killing 6700:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-10 07:41:07.557  1037  1541 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-10 07:41:07.557  1037  1541 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-10 07:41:07.557  7297  7344 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.593  1037  1541 D WifiStateMachine: enableVerboseLogging : level 2
08-10 07:41:07.593  1037  1541 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-10 07:41:07.594  1037  1541 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-10 07:41:07.594  1037  1541 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-10 07:41:07.594  1037  1541 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-10 07:41:07.594  1037  1541 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-10 07:41:07.594  1037  1541 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-10 07:41:07.594  1037  1541 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-10 07:41:07.595  1037  1541 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-10 07:41:07.595  1037  1541 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-10 07:41:07.595  1037  1541 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-10 07:41:07.595  1037  1541 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-10 07:41:07.595  1037  1541 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-10 07:41:07.595  1037  1541 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-10 07:41:07.596  1037  1541 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-10 07:41:07.599  1037  1954 W libprocessgroup: failed to open /acct/uid_10061/pid_6700/cgroup.procs: No such file or directory
08-10 07:41:07.601  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
,08-10 07:41:07.602  1037  1541 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-10 07:41:07.602  1037  1541 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
,08-10 07:41:07.602  1944  1944 D WfdsService: Supplicant Connection state is changed : true
08-10 07:41:07.602  1037  1541 D WifiNative-HAL: Setting external_sim to 1
08-10 07:41:07.602  1037  1541 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-10 07:41:07.602  1944  2358 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-10 07:41:07.602  1944  2358 D WfdsService: Set the WFDS Monitor: true
08-10 07:41:07.602  1944  2358 D WfdsMonitor: WfdsMonitorThread create
08-10 07:41:07.602  1944  2358 D WfdsMonitor: WFDS Monitor is created and started
08-10 07:41:07.602  1944  2358 D WfdsService: WiFi: Supplicant connection re-established
08-10 07:41:07.602  1037  1541 D WifiNative-wlan0: SET external_sim 1: returned true
08-10 07:41:07.602  1037  1541 I WifiNative-HAL: startHal
08-10 07:41:07.602  1037  1541 D wifi    : setting scan oui 0xaf730500
08-10 07:41:07.603  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 07:41:07.603  1037  1541 I WifiNative-HAL: startHal
08-10 07:41:07.603  1037  1541 D wifi    : setting scan oui 0xaf730500
08-10 07:41:07.603  1037  1541 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-10 07:41:07.603  1944  7364 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-10 07:41:07.603  1037  1541 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-10 07:41:07.603  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-10 07:41:07.603  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-10 07:41:07.604  1944  7364 E CtrlSupplicant: Succeed to open control connection
08-10 07:41:07.604  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-10 07:41:07.604  1944  7364 E CtrlSupplicant: Succeed to open monitor connection
08-10 07:41:07.604  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 07:41:07.604  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 07:41:07.604  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 07:41:07.604  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-10 07:41:07.604  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-10 07:41:07.605  1944  7364 D WfdsMonitor: Supplicant connection established
08-10 07:41:07.605  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-10 07:41:07.605  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 07:41:07.605  1944  2358 D WfdsService: Connected to the supplicant for wfds
08-10 07:41:07.605  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 07:41:07.605  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 07:41:07.605  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 07:41:07.605  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 07:41:07.606  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 07:41:07.606  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-10 07:41:07.606  7328  7328 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-10 07:41:07.606  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-10 07:41:07.606  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 07:41:07.606  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 07:41:07.606  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 07:41:07.607  1037  1541 E WifiNative: : [328,851,688 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-10 07:41:07.607  1037  1541 D WifiNative-wlan0: doBoolean: RECONNECT
08-10 07:41:07.608  1037  1541 D WifiNative-wlan0: RECONNECT: returned true
08-10 07:41:07.608  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-10 07:41:07.608  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 ,SSID=]
08-10 07:41:07.608  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 07:41:07.608  1037  1541 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 07:41:07.608  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
,08-10 07:41:07.609  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-10 07:41:07.609  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.609  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
,08-10 07:41:07.609  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-10 07:41:07.610  1037  1560 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.610  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-10 07:41:07.610  1037  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.610  1037  1559 I WifiNative-HAL: startHal
08-10 07:41:07.610  1037  1559 D wifi    : getting scan capabilities on interface[1] = 0xaf730500
08-10 07:41:07.610  1037  1559 D wifi    : failed to get capabilities : -3
08-10 07:41:07.610  1037  1559 E WifiScanningService: could not get scan capabilities
08-10 07:41:07.610  1037  1541 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-10 07:41:07.610   310   895 D CommandListener: Setting iface cfg
08-10 07:41:07.610   310   895 D CommandListener: Trying to bring up p2p0
08-10 07:41:07.611  1037  1541 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-10 07:41:07.611  1037  1539 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 07:41:07.611  1037  1539 D LGWifiP2pService: P2pEnablingState
08-10 07:41:07.611  1037  1539 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.611  1037  1539 D LGWifiP2pService: P2p socket connection successful
08-10 07:41:07.611  1037  1539 D LGWifiP2pService: P2pEnabledState
08-10 07:41:07.611  1037  1541 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-10 07:41:07.611  1037  1539 D LGWifiP2pService: sending p2p connection changed broadcast
08-10 07:41:07.611  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=328856  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 07:41:07.611  1037  1539 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-10 07:41:07.612  1037  1539 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-10 07:41:07.612  1037  1539 D WifiNative-p2p0: doBoolean: SET device_name G3
08-10 07:41:07.613  1037  1539 D WifiNative-p2p0: SET device_name G3: returned true
08-10 07:41:07.613  1037  1539 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-10 07:41:07.613  1037  1539 D LGWifiP2pService: before postfix = G3
08-10 07:41:07.613  1037  1539 D WifiServerServiceExt: postfix byte check : 2
08-10 07:41:07.613  1037  1539 D LGWifiP2pService: after postfix = G3
08-10 07:41:07.613  1037  1539 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-10 07:41:07.613  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-10 07:41:07.613  1037  1539 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-10 07:41:07.613  1037  1539 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-10 07:41:07.613  1944  1944 D WfdsService: WifiP2pState is changed : true
08-10 07:41:07.613  1944  2358 D WfdsService: Receive the WFDS_ENABLE Method
08-10 07:41:07.613  1944  2358 D WfdsService: Set the WFDS Monitor: true
08-10 07:41:07.613  1944  2358 D WfdsService: Connected to the supplicant for wfds
08-10 07:41:07.614  1944  2358 D WfdsJNI : doCommand: WFDS_SET TRUE
08-10 07:41:07.614  1037  1539 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-10 07:41:07.614  1037  1539 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-10 07:41:07.614  7328  7328 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-10 07:41:07.614  1944  2358 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-10 07:41:07.614  1037  1539 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-10 07:41:07.614  7328  7328 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-10 07:41:07.614  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=328859  SSID:  ,BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 07:41:07.614  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-10 07:41:07.614  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-10 07:41:07.614  1944  2358 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-10 07:41:07.614  1037  1539 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-10 07:41:07.615  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress
08-10 07:41:07.615  1944  1944 D WfdsService: isConnected: false
08-10 07:41:07.615  1037  1541 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-10 07:41:07.615  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-10 07:41:07.615  1944  2358 D WfdsService: selectPreferredScanChannel [36]
08-10 07:41:07.615  1944  2358 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-10 07:41:07.615  1037  1541 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-10 07:41:07.615  1037  1541 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-10 07:41:07.615  1037  1541 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-10 07:41:07.616  7328  7328 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-10 07:41:07.616  1037  1539 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-10 07:41:07.616  1037  1539 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-10 07:41:07.617  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:07.617  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:07.617  1037  1539 D WifiNative-p2p0: P2P_FLUSH: returned true
08-10 07:41:07.617  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-10 07:41:07.617  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.617  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.617  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 07:41:07.617  1037  1539 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-10 07:41:07.617  1037  1539 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-10 07:41:07.618  1037  1539 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-10 07:41:07.618  1037  1539 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-10 07:41:07.619  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:07.619  1037  1541 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,08-10 07:41:07.621  1037  1541 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-10 07:41:07.622  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
08-10 07:41:07.623  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-10 07:41:07.623  1944  1944 D WfdsService: Update P2p Interface State: 3
08-10 07:41:07.624  1037  1541 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-10 07:41:07.624  1037  1541 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-10 07:41:07.626  7328  7328 E wpa_supplicant: disconnect_rssi_lvl: -100
08-10 07:41:07.627  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 07:41:07.627  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 07:41:07.628  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-10 07:41:07.628  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-10 07:41:07.628  1037  1539 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-10 07:41:07.628  1037  1539 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-10 07:41:07.628  1037  1539 D LGWifiP2pService: InactiveState
08-10 07:41:07.628  1037  1539 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.628  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.629  1037  1539 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-10 07:41:07.629  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 07:41:07.630  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:07.630  1944  7364 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 07:41:07.630  1037  7345 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 07:41:07.630  1037  7345 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:07.630  1037  7345 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:07.630  1037  7345 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:07.631  7328  7328 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 07:41:07.631  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.631  1944  7364 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:07.632  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.632  1944  7364 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:07.633  1037  7345 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:07.633  1037  7345 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.633  1037  7345 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.633  1037  7345 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.633  1037  1539 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-10 07:41:07.633  1037  7345 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:07.633  1037  7345 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.633  1037  7345 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.633  1037  1539 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.633  1037  7345 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-10 07:41:07.633  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.633  1037  1539 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1944  2358 W WfdsService: DefaultState - msg [9441285] is not handled
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  1037  1539 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.634  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 07:41:07.635  7328  7328 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:07.635  1037  1037 E WifiServerServiceExt: No p2p device connected
08-10 07:41:07.636  7328  7328 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 07:41:07.636  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.637  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-10 07:41:07.637  1944  7364 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-10 07:41:07.638  1944  7364 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:07.638  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 07:41:07.638  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:07.638  1037  7345 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:07.638  1037  7345 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:07.638  1037  7345 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:07.638  1037  7345 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.638  1037  7345 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.638  1037  7345 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.638  1037  7345 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:07.638  1037  7345 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.638  1037  7345 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.638  1037  7345 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:07.638  1037  1541 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-10 07:41:07.639  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-10 07:41:07.639  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.639  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:07.639  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-10 07:41:07.640  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-10 07:41:07.640  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-10 07:41:07.640  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-10 07:41:07.640  7328  7328 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 07:41:07.640  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-10 07:41:07.640  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 07:41:07.641  1037  7345 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 07:41:07.641  1037  7345 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 07:41:07.641  1037  1541 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-10 07:41:07.641  1037  1541 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-10 07:41:07.642  1037  1541 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-10 07:41:07.642  1037  1541 D WifiNative-wlan0: doBoolean: SCAN
08-10 07:41:07.642  1037  1541 D WifiNative-wlan0: SCAN: returned false
08-10 07:41:07.642  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=328887  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 07:41:07.643  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=328888  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 07:41:07.644  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:07.644  1605  1605 I StatusBar.NetworkController: mWifi,Connected = false, mWifiLevel = 0
08-10 07:41:07.644  1037  1541 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:07.644  1037  1541 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:07.645  1037  1541 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:07.645  1037  1541 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:07.646  1037  1541 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:07.646  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:07.646  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.646  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:07.646  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 07:41:07.647  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:07.647  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 07:41:07.671  7346  7346 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:07.672  7346  7346 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:07.674  7346  7346 D PhoneMonitor: Register our PhoneStateListener
,08-10 07:41:07.691  7346  7346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-10 07:41:07.693  7346  7346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 07:41:07.709  7346  7346 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-10 07:41:07.710  7346  7346 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-10 07:41:07.710  7346  7346 D TelephonyAutoProfiling: [parse] Load xml
08-10 07:41:07.712  7346  7346 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-10 07:41:07.712  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-10 07:41:07.712  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-10 07:41:07.713  7346  7346 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-10 07:41:07.713  7346  7346 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-10 07:41:07.721  7346  7346 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-10 07:41:07.744  1037  2036 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7367 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 07:41:07.746  1037  2036 I ActivityManager: Killing 6746:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-10 07:41:07.775  1037  1578 W libprocessgroup: failed to open /acct/uid_10080/pid_6746/cgroup.procs: No such file or directory
,08-10 07:41:08.069  1037  2036 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7391 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-10 07:41:08.082  1037  2036 I ActivityManager: Killing 6772:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-10 07:41:08.123  1037  1578 W libprocessgroup: failed to open /acct/uid_10097/pid_6772/cgroup.procs: No such file or directory
,08-10 07:41:08.233  1037  1052 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7408 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 07:41:08.234  1037  1052 I ActivityManager: Killing 6803:com.lge.eula/1000 (adj 15): empty #17
,08-10 07:41:08.266  7328  7328 E wpa_supplicant: USIM:  scard_init function
08-10 07:41:08.266  7328  7328 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-10 07:41:08.269  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-10 07:41:08.269  1037  7345 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 07:41:08.270  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-10 07:41:08.270  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-10 07:41:08.270  1037  7345 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-10 07:41:08.270  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-10 07:41:08.270  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-10 07:41:08.271  1037  1541 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-10 07:41:08.271  1037  1541 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-10 07:41:08.272  1037  1541 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-10 07:41:08.272  1037  1541 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-10 07:41:08.272  1037  1541 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 07:41:08.294  1037  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_6803/cgroup.procs: No such file or directory
,08-10 07:41:08.299  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=329544  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-10 07:41:08.300  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=329545  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-10 07:41:08.302  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.302  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:08.304  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.304  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.304  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.304  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 07:41:08.308  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-10 07:41:08.308  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-10 07:41:08.347  7408  7408 I art     : Almond Protected OAT
,08-10 07:41:08.381  7328  7328 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 07:41:08.384  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-10 07:41:08.384  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-10 07:41:08.385  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-10 07:41:08.385  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-10 07:41:08.386  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-10 07:41:08.386  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:08.386  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:08.387  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=329631  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 07:41:08.387  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=329632  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 07:41:08.388  1037  1541 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=329633
08-10 07:41:08.388  1037  1541 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=329633
08-10 07:41:08.389  1037  1541 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=329634
08-10 07:41:08.389  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=329634
08-10 07:41:08.390  1037  1541 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=329634
08-10 07:41:08.390  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=329635  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 07:41:08.392  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.392  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:08.393  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.393  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.393  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 07:41:08.394  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:08.394  7328  7328 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 07:41:08.394  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:08.394  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.394  7328  7328 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 07:41:08.394  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-10 07:41:08.394  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 07:41:08.394  1037  7345 W WifiMonitor: couldn't identify event type - ,WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 07:41:08.397  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-10 07:41:08.397  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 07:41:08.397  1037  7345 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 07:41:08.397  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:08.397  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:08.399  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.399  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.399  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-10 07:41:08.399  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=329644  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 07:41:08.400  1037  1541 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:08.400  1037  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:08.401  1037  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:08.401  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:08.402  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:08.403  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:08.403  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-10 07:41:08.403  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=329648  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 07:41:08.404  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=329649  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 07:41:08.405  1037  1541 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=329649
08-10 07:41:08.405  1037  1541 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=329650
08-10 07:41:08.405  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-10 07:41:08.406  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:08.406  1037  1541 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 07:41:08.406  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:08.407  1037  1541 I WifiServiceExtension: setVHTCapabilityType  : false
08-10 07:41:08.414  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.414  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:08.415  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.418  1037  1541 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-10 07:41:08.418  1037  1541 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-10 07:41:08.420  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.420  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.420  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 07:41:08.422  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.422  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.422  1037  1539 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.424  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.424  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.424  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 07:41:08.428  7408  7408 D WeatherApplication: removeAccount
08-10 07:41:08.430  7408  7408 D WeatherApplication: Account.length = 0
08-10 07:41:08.430  7408  7408 E WeatherApplication: OPERATOR:OPEN
08-10 07:41:08.432  1037  1541 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-10 07:41:08.433  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 07:41:08.433  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 07:41:08.433  1037  1547 D ConnectivityService: Got NetworkAgent Messenger
08-10 07:41:08.433  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 07:41:08.433  1037  1547 D ConnectivityService: NetworkAgent connected
08-10 07:41:08.433  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 07:41:08.433  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 07:41:08.435  7408  7408 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:8
08-10 07:41:08.437  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.437  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:08.437  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 07:41:08.437  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 07:41:08.437  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 07:41:08.437  7408  7408 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 07:41:08.438  7408  7408 D Weather.Utils: 2 : All the weather widget is gone.
08-10 07:41:08.438  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 07:41:08.438  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 07:41:08.439  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.440  7408  7408 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 07:41:08.441  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 07:41:08.441  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.441  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:08.442   310   895 D CommandListener: Setting iface cfg
08-10 07:41:08.442  7408  7408 D WeatherAncestor: connectivity changed - connection : true
08-10 07:41:08.443  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.443  7408  7408 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-10 07:41:08.445  1037  1541 E WifiStateMachine: Start Dhcp Watchdog 2
08-10 07:41:08.446  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=329690  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:08.446  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=329691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:08.446  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=329691  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:08.447  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=329692  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:08.447  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:08.447  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-10 07:41:08.448  1037  7437 D DhcpStateMachine: StoppedState
08-10 07:41:08.448  1037  7437 D DhcpStateMachine: StoppedState{ when=-2ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.448  1037  7437 D DhcpStateMachine: WaitBeforeStartState
08-10 07:41:08.448  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=329693  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:08.448  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=329693  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:08.449  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:283964] from screen [on:0 period:1928853217] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 07:41:08.450  7408  7408 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 07:41:08.450  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1928853218] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 07:41:08.450  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 07:41:08.450  7408  7408 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 07:41:08.450  7408  7408 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-10 07:41:08.454  1037  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-10 07:41:08.455  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 07:41:08.455  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 07:41:08.456  1037  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 07:41:08.456  1037  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 07:41:08.456  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-10 07:41:08.457  1037  1541 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-10 07:41:08.457  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.457  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.458  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.458  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.459  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.459  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.459  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.459  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-10 07:41:08.460  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
08-10 07:41:08.460  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
08-10 07:41:08.460  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:08.460  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-10 07:41:08.460  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 07:41:08.461  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-10 07:41:08.462  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-10 07:41:08.462  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 0
08-10 07:41:08.463  1037  1541 D WifiNative-wlan0: SET ps 0: returned true
08-10 07:41:08.463  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-10 07:41:08.463  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-10 07:41:08.463  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-10 07:41:08.463  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ae5bf3a target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.463  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ae5bf3a target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.464  1037  7437 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.464  1037  7437 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-10 07:41:08.465  1037  1541 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-10 07:41:08.465  1037  1541 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 07:41:08.465  1037  1541 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 07:41:08.466   310   895 D CommandListener: Setting iface cfg
08-10 07:41:08.466   310   895 D CommandListener: Trying to bring up wlan0
08-10 07:41:08.467  1037  1541 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-10 07:41:08.468  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.468  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:08.468  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 07:41:08.469  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.469  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.469  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.470  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_L,INKPROPERTIES 0 0
08-10 07:41:08.471  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:08.472  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-10 07:41:08.472  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 07:41:08.473  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 07:41:08.473  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.473  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.473  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 07:41:08.473  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 07:41:08.474  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 07:41:08.474  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-10 07:41:08.474  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-10 07:41:08.475  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-10 07:41:08.475  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
,08-10 07:41:08.476  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-10 07:41:08.476  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 07:41:08.477  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 07:41:08.477  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-10 07:41:08.477  1037  1541 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-10 07:41:08.477  1037  1547 D ConnectivityService: ignoring duplicate network state non-change
08-10 07:41:08.480  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.480  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:08.481  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.483  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.483  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.483  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 07:41:08.484  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 07:41:08.485  1037  1547 D ConnectivityService: Adding iface wlan0 to network 101
08-10 07:41:08.486  1037  1541 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-10 07:41:08.488  7408  7408 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 07:41:08.488  7408  7408 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:8
,08-10 07:41:08.496  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.496  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.496  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 07:41:08.498  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-10 07:41:08.503  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-10 07:41:08.504  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.504  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:08.505  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.505  1037  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 07:41:08.505  1037  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-10 07:41:08.506  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.506  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.506  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 07:41:08.506  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 07:41:08.506  1037  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-10 07:41:08.507   310   895 E Netd    : netlink response contains error (File exists)
08-10 07:41:08.507  1037  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-10 07:41:08.508  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.508  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:08.508  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 07:41:08.508  1037  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-10 07:41:08.508  1037  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-10 07:41:08.509  1037  1547 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-10 07:41:08.511  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.511  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 07:41:08.511  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.526  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:08.526  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 07:41:08.527  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:08.547  1037  1926 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7442 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-10 07:41:08.550  1037  1926 I ActivityManager: Killing 6821:com.lge.bnr/1000 (adj 15): empty #17
08-10 07:41:08.647  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 07:41:08.647  1037  1053 W libprocessgroup: failed to open /acct/uid_1000/pid_6821/cgroup.procs: No such file or directory
08-10 07:41:08.647  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-10 07:41:08.647  1037  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-10 07:41:08.647  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-10 07:41:08.647  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 07:41:08.647  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.647  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-10 07:41:08.647  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:08.648  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 07:41:08.648  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:08.648  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.648  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 07:41:08.648  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-10 07:41:08.648  1037  1547 D ConnectivityService: currentScore = 0, newScore = 20
08-10 07:41:08.648  1037  1547 D ConnectivityService:    accepting network in place of null
08-10 07:41:08.648  1037  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.649  1037  1541 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.649  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 07:41:08.650  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.650  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-10 07:41:08.656   310  7460 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-10 07:41:08.659  1037  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-10 07:41:08.659  1037  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 07:41:08.660  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 07:41:08.666  1037  7437 D DhcpStateMachine: DHCPV4 request on wlan0
08-10 07:41:08.660  7461  7461 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:08.667  1037  7437 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-10 07:41:08.667  1037  7437 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-10 07:41:08.660  7461  7461 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 07:41:08.673  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:08.673  1037  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-10 07:41:08.674  1037  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-10 07:41:08.675  1037  1547 D ConnectivityService: validation of new default Network = false
08-10 07:41:08.675  1037  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-10 07:41:08.675  1037  1547 D DSQN    : enableDataServiceNotify 
08-10 07:41:08.675  1037  1547 D DSQN    : start dsqn bin
08-10 07:41:08.680  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-10 07:41:08.680  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.680  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:08.681  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:08.682  1605  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 07:41:08.682  7461  7461 I dhcpcd  : version 5.5.6 starting
08-10 07:41:08.684  7461  7461 E dhcpcd  : get_duid: m
08-10 07:41:08.684  7461  7461 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-10 07:41:08.680  7462  7462 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:08.680  7462  7462 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 07:41:08.689  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-10 07:41:08.689  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 07:41:08.689  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 07:41:08.689  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 07:41:08.698   310  7460 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-10 07:41:08.720  1037  1538 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-10 07:41:08.720  7462  7462 E DSQN    : DSQN ssw
,08-10 07:41:08.733   310  7460 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-10 07:41:08.736  1818  7467 I CheckinService: active receiver: enabled
08-10 07:41:08.739  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 07:41:08.740  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.740  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.741   310   894 D LGDataListener: argv[0]=dsqncommand
08-10 07:41:08.741   310   894 D LGDataListener: argv[1]=wlan0
08-10 07:41:08.741   310   894 D LGDataListener: argv[2]=1
08-10 07:41:08.741   310   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-10 07:41:08.742  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-10 07:41:08.742  1037  1117 D DSQN    : start to monitor internet connection
08-10 07:41:08.748  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 05:41:08 GMT], X-Android-Received-Millis=[1470807668748], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470807668741]}
08-10 07:41:08.749  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 07:41:08.749  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-10 07:41:08.749  1037  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-10 07:41:08.749  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-10 07:41:08.749  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-10 07:41:08.749  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:08.749  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 07:41:08.749  1037  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-10 07:41:08.749  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-10 07:41:08.749  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.749  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:08.750  7461  7461 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 07:41:08.750  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:08.750  7461  7461 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 07:41:08.750  7461  7461 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 07:41:08.750  1037  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.750  7461  7461 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-10 07:41:08.750  7461  7461 D dhcpcd  : wlan0: sending REQUEST (xid 0x231ddfbb), next in 3.33 seconds
08-10 07:41:08.750  1605  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 07:41:08.750  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.750  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 07:41:08.751  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 07:41:08.751  1037  1541 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:08.751  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 07:41:08.752  1818  7467 I CheckinService: Preparing to send checkin request
08-10 07:41:08.752  1818  7467 I EventLogService: Accumulating logs since 1470807382389
08-10 07:41:08.766  1818  7467 W EventLogAggregator: Unknown tag: snet_gcore
08-10 07:41:08.766  1818  7467 W EventLogAggregator: Unknown tag: snet_launch_service
,08-10 07:41:08.779  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 07:41:08.780  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.781  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:08.782  7461  7461 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-10 07:41:08.793  7461  7461 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-10 07:41:08.793  7461  7461 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-10 07:41:08.793  7461  7461 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-10 07:41:08.793  7461  7461 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-10 07:41:08.794  7461  7461 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-10 07:41:08.794  7461  7461 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 07:41:08.794  7461  7461 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 07:41:08.794  7461  7461 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-10 07:41:08.799   279   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 07:41:08.799   279   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 07:41:08.799   279   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 07:41:08.800  7442  7477 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 07:41:08.803   279   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-10 07:41:08.803   279   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 07:41:08.803   279   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 07:41:08.803  7442  7477 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 07:41:08.808   279   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 07:41:08.808   279   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 07:41:08.808   279   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 07:41:08.809  7442  7483 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 07:41:08.811   279   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 07:41:08.811   279   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 07:41:08.811   279   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 07:41:08.812  7442  7483 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-10 07:41:08.819  1818  7467 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-10 07:41:08.928  1037  1974 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7509 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-10 07:41:08.972  7509  7509 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-10 07:41:08.972  7509  7509 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-10 07:41:08.987  7509  7509 I MultiDex: VM with version 2.1.0 has multidex support
08-10 07:41:08.988  7509  7509 I MultiDex: install
08-10 07:41:08.988  7509  7509 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-10 07:41:08.994  7509  7509 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-10 07:41:09.009  7442  7442 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 07:41:09.021  7442  7442 I LibraryLoader: Loading: webviewchromium
,08-10 07:41:09.024  7442  7442 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 278-282)
08-10 07:41:09.025  7442  7442 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 07:41:09.033  7442  7442 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fb35d35}
08-10 07:41:09.037  7442  7442 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 07:41:09.038  7442  7442 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 07:41:09.065  7442  7442 I BrowserStartupController: Initializing chromium process, renderers=0
,08-10 07:41:09.066  7442  7442 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 07:41:09.071  1037  7437 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-10 07:41:09.072  1037  7437 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-10 07:41:09.072  1037  7437 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 07:41:09.072  1037  7437 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-10 07:41:09.072  1037  7437 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-10 07:41:09.072  1037  7437 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 07:41:09.072  1037  7437 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-10 07:41:09.072  1037  7437 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-10 07:41:09.072  1037  7437 D DhcpStateMachine: RunningState
08-10 07:41:09.079  7442  7442 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 07:41:09.080  7442  7442 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-10 07:41:09.081  7442  7442 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-10 07:41:09.083   315  1387 V AudioPolicyService: registerClient() client 0xb558a260, uid 10093
08-10 07:41:09.092  7442  7539 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 07:41:09.105  7442  7442 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:41:09.105  7442  7442 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:41:09.105  7442  7442 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:41:09.105  7442  7442 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:41:09.105  7442  7442 I Adreno-EGL: Remote Branch: 
08-10 07:41:09.105  7442  7442 I Adreno-EGL: Local Patches: 
08-10 07:41:09.105  7442  7442 I Adreno-EGL: Reconstruct Branch: 
,08-10 07:41:09.170  7442  7442 I NSApplication: Starting up...
,08-10 07:41:09.221  1037  1954 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7553 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-10 07:41:09.225  1037  1954 I ActivityManager: Killing 6662:com.android.vending/u0a44 (adj 15): empty #17
08-10 07:41:09.279  7509  7528 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:09.280  7509  7528 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:09.295  1037  1997 W libprocessgroup: failed to open /acct/uid_10044/pid_6662/cgroup.procs: No such file or directory
,08-10 07:41:09.319  7553  7553 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 07:41:09.384  7570  7570 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-10 07:41:09.461  7570  7570 I dex2oat : dex2oat took 77.286ms (threads: 4)
,08-10 07:41:09.479  7509  7528 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:41:09.479  7509  7528 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:41:09.479  7509  7528 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:41:09.479  7509  7528 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:41:09.479  7509  7528 I Adreno-EGL: Remote Branch: 
08-10 07:41:09.479  7509  7528 I Adreno-EGL: Local Patches: 
08-10 07:41:09.479  7509  7528 I Adreno-EGL: Reconstruct Branch: 
,08-10 07:41:09.503  1037  1974 D WifiServiceImplEx: setWifiEnabled: false pid=6960, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 07:41:09.503  1037  1974 D WifiService: setWifiEnabled: false pid=6960, uid=10118
08-10 07:41:09.503  1037  1974 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 07:41:09.527  1037  1541 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:09.527  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:09.528  1037  1541 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:09.528  1037  1541 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:09.528  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 07:41:09.529  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-10 07:41:09.529  1037  1541 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 07:41:09.529  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 07:41:09.529  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 07:41:09.529  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 07:41:09.529  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-10 07:41:09.531  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 07:41:09.531  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 07:41:09.543  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 07:41:09.543  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 07:41:09.543  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 07:41:09.544  1037  1539 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 07:41:09.544  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.545  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 07:41:09.545  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 07:41:09.545  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-10 07:41:09.546  1037  7437 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.550   310   895 D CommandListener: Clearing all IP addresses on wlan0
08-10 07:41:09.566  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 07:41:09.567  6461  7103 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-10 07:41:09.583  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 07:41:09.583  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-10 07:41:09.586  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-10 07:41:09.586  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:09.586  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:09.586  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 07:41:09.586  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-10 07:41:09.586  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:09.586  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:09.586  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 07:41:09.588  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:09.588  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:09.589  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-10 07:41:09.590  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:09.591  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:09.591  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:09.592  7509  7528 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:41:09.592  7509  7528 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:41:09.592  7509  7528 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:41:09.592  7509  7528 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:41:09.592  7509  7528 I Adreno-EGL: Remote Branch: 
08-10 07:41:09.592  7509  7528 I Adreno-EGL: Local Patches: 
08-10 07:41:09.592  7509  7528 I Adreno-EGL: Reconstruct Branch: 
08-10 07:41:09.592  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:09.593  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:09.593  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:09.593  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:09.593  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:09.594  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 1
08-10 07:41:09.594  1037  1037 D RttService: SCAN_AVAILABLE : 1
08-10 07:41:09.594  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:09.594  1037  1541 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 07:41:09.594  1037  1559 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.594  1037  1560 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.594  1037  1539 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.594  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.594  1037  1539 D WifiMonit,or: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1a0f0730
08-10 07:41:09.594  1037  1539 D LGWifiP2pService: P2pDisablingState
08-10 07:41:09.595  1037  1539 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.595  1037  1539 D LGWifiP2pService: p2p socket connection lost
08-10 07:41:09.595  1037  1539 D LGWifiP2pService: P2pDisabledState
08-10 07:41:09.596  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:09.596  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 07:41:09.596  1944  1944 D WfdsService: WifiP2pState is changed : false
08-10 07:41:09.597  1944  2358 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-10 07:41:09.597  1944  2358 D WfdsService: Set the WFDS Monitor: false
08-10 07:41:09.597  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:09.598  1944  2358 D WfdsMonitor: WFDS Monitor is stopped
08-10 07:41:09.598  1944  2358 D WfdsService: STATE : WfdsDisabledState - enter
08-10 07:41:09.598  2182  2182 W GCM     : ACTIVE NETWORK NOT CONNECTED
08-10 07:41:09.599  1944  7364 D CtrlSupplicant: Received on exit socket, terminate
08-10 07:41:09.599  1944  7364 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-10 07:41:09.599  1944  7364 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-10 07:41:09.599  1944  7364 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-10 07:41:09.599  1944  2359 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-10 07:41:09.599  1944  2358 W WfdsService: DefaultState - msg [9445378] is not handled
08-10 07:41:09.600  1037  1541 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-10 07:41:09.600  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 07:41:09.600  7328  7328 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 07:41:09.600  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.600  1037  1539 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.601  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 07:41:09.601  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 07:41:09.601  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-10 07:41:09.605  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 07:41:09.605  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:09.606  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 07:41:09.606  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 07:41:09.608  7269  7269 I AppUp4:CustModeStarterReceiver: onReceive
08-10 07:41:09.612  1037  1897 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,08-10 07:41:09.613  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.613  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.613  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-10 07:41:09.613  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.613  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-10 07:41:09.626  7269  7269 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7297cc2
08-10 07:41:09.626  7269  7269 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 07:41:09.626  7269  7269 D AppUp4:CustFacade: isPhone : true
08-10 07:41:09.627  7269  7269 D AppUp4:CustModeStarterReceiver: begin check event
08-10 07:41:09.627  7269  7269 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 07:41:09.629  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:09.629  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:09.630  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:09.632   310   895 D CommandListener: Clearing all IP addresses on wlan0
08-10 07:41:09.632   310  7590 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 07:41:09.633  1037  1547 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-10 07:41:09.633  1037  1547 D DSQN    : disableDataServiceNotify
08-10 07:41:09.633  1037  1547 D DSQN    : stop dsqn bin
08-10 07:41:09.633  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 07:41:09.633  1037  1541 D WifiNative-p2p0: doBoolean: TERMINATE
08-10 07:41:09.634  1037  1541 D WifiNative-p2p0: TERMINATE: returned true
08-10 07:41:09.634  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 07:41:09.634  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-10 07:41:09.634  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 07:41:09.634  1037  1037 D WifiHS20: hidePasspointNotification off =false
08-10 07:41:09.634  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:09.634  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:09.634  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-10 07:41:09.634  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:09.634  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 07:41:09.635  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-10 07:41:09.636  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:09.636  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:09.637  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-10 07:41:09.637  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:09.637  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:09.637  1037  1037 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-10 07:41:09.642  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:09.642  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:09.642  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:09.642  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:09.642  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:09.642  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:09.642  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:09.642  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:09.642  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:09.642  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:09.642  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:09.643  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:09.643  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:09.643  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:09.643  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:09.643  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:09.643  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:09.643  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:09.643  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:09.643  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:09.643  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:09.644  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:09.645  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.SocketException: Binding socket to network 101 failed: errno 64 (Machine is not on the network)
08-10 07:41:09.645  4638  7592 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 07:41:09.646  7297  7297 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 07:41:09.646  4638  7593 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:09.646  4638  7593 D ,LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:09.646  7509  7528 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:41:09.646  7509  7528 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:41:09.646  7509  7528 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:41:09.646  7509  7528 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:41:09.646  7509  7528 I Adreno-EGL: Remote Branch: 
08-10 07:41:09.646  7509  7528 I Adreno-EGL: Local Patches: 
08-10 07:41:09.646  7509  7528 I Adreno-EGL: Reconstruct Branch: 
08-10 07:41:09.650  1037  1547 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-10 07:41:09.650  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:09.650  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-10 07:41:09.651  1037  1547 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:09.651  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-10 07:41:09.651  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.651  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.651  1037  7436 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-10 07:41:09.651  1037  1547 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-10 07:41:09.651  1037  1547 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 07:41:09.651  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 07:41:09.652  1605  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-10 07:41:09.653  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 07:41:09.654  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 07:41:09.654  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 07:41:09.654  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 07:41:09.654  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 07:41:09.655  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:09.655  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-10 07:41:09.657  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:09.657  1037  1547 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:09.657  1037  1547 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:09.657  1037  1547 D NetworkManagementService: Removing idletimer
08-10 07:41:09.657  1037  1547 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:09.657  1037  1547 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-10 07:41:09.658  1037  1541 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:09.658  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps Li,nkDnBandwidth>=1048576Kbps]
08-10 07:41:09.658  1037  1538 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-10 07:41:09.658  1037  1037 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-10 07:41:09.658  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:09.658  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 07:41:09.658  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 07:41:09.658  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 07:41:09.658  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-10 07:41:09.671  7297  7594 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:09.681  1037  1547 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-10 07:41:09.683  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 07:41:09.684  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:09.684  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:09.699  3350  3350 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 07:41:09.699  3350  3350 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:09.699  3350  3350 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-10 07:41:09.701  7346  7346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 07:41:09.701  7346  7346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 07:41:09.703  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 07:41:09.704  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:09.704  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:09.705  7176  7598 W FormManager: Network not available. Please check & try again.
08-10 07:41:09.709  7408  7408 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:9
08-10 07:41:09.714  7176  7600 V FormManager: Network unavailable.
08-10 07:41:09.715  7408  7408 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 07:41:09.715  7408  7408 D Weather.Utils: 2 : All the weather widget is gone.
08-10 07:41:09.715  7408  7408 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 07:41:09.715  7408  7408 D WeatherAncestor: connectivity changed - connection : true
08-10 07:41:09.715  7408  7408 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2fb0f610
,08-10 07:41:09.716  7408  7408 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 07:41:09.716  7408  7408 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 07:41:09.716  7408  7408 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 07:41:09.716  7408  7408 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 07:41:09.716  7408  7408 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:9
08-10 07:41:09.719  7176  7600 V FormManager: Network unavailable.
08-10 07:41:09.733  7328  7328 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-10 07:41:09.733  7328  7328 I wpa_supplicant: monitor socket send errors count : 1
08-10 07:41:09.733  7328  7328 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1944-4\x00 that cannot receive messages
,08-10 07:41:09.735  1037  7345 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-10 07:41:09.735  1037  7345 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 07:41:09.735  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 07:41:09.735  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 07:41:09.735  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 07:41:09.735  7062  7062 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 07:41:09.736  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 07:41:09.737  7062  7062 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 07:41:09.737  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 07:41:09.737  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 07:41:09.737  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 07:41:09.737  7062  7062 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 07:41:09.737  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 07:41:09.737  7062  7062 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 07:41:09.745  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:09.746  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 07:41:09.752  7176  7607 V FormManager: Network unavailable.
08-10 07:41:09.752  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:09.753  1037  7437 D DhcpStateMachine: StoppedState
08-10 07:41:09.753  1037  7437 D DhcpStateMachine: StoppedState{ when=-151ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:09.755  7176  7606 W FormManager: Network not available. Please check & try again.
08-10 07:41:09.755  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-10 07:41:09.756  1037  1541 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-10 07:41:09.764  7176  7607 V FormManager: Network unavailable.
,08-10 07:41:09.769  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:09.771  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 07:41:09.773  7328  7328 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 07:41:09.774  7328  7328 W wpa_supplicant: USIM:  scard_deinit function
08-10 07:41:09.774  7176  7609 W FormManager: Network not available. Please check & try again.
08-10 07:41:09.774  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-10 07:41:09.774  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 07:41:09.774  1037  7345 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 07:41:09.774  1037  7345 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-10 07:41:09.775  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:09.775  1037  1119 D Tethering: InitialState.processMessage what=4
08-10 07:41:09.775  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:09.775  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 07:41:09.775  1037  1541 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=331020
08-10 07:41:09.776  1037  1541 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=331021
08-10 07:41:09.776  7176  7610 V FormManager: Network unavailable.
08-10 07:41:09.776  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=331021  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 07:41:09.777  1037  1541 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=331021  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-10 07:41:09.777  1037  1541 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:09.777  7176  7610 V FormManager: Network unavailable.
08-10 07:41:09.777  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-10 07:41:09.783  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:09.791  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-10 07:41:09.791  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:09.792  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:09.794  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:09.799  4638  7611 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 07:41:09.800  4638  7612 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 07:41:09.800  4638  7612 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:09.833  1037  1974 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7613 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-10 07:41:09.848   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 286us total 11.440ms
,08-10 07:41:09.863   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 266us total 12.822ms
08-10 07:41:09.876   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 11.657ms
,08-10 07:41:09.904  7613  7613 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-10 07:41:09.904  7613  7613 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-10 07:41:09.913  7613  7613 V [BNRBootReceiver]: Boot Receiver Return
08-10 07:41:09.915  7613  7613 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-10 07:41:09.916  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:09.926  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:09.931  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:09.931  7328  7328 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-10 07:41:09.932  1037  7345 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-10 07:41:09.932  1037  7345 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-10 07:41:09.932  1037  7345 D WifiMonitor: Disconnecting from the supplicant, no more events
08-10 07:41:09.933  1037  1541 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-10 07:41:09.951  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:09.951  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:09.952   310  7632 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-10 07:41:09.953  1037  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-10 07:41:09.955  1818  7467 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-10 07:41:09.956  7134  7134 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 07:41:09.961  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:09.967  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 07:41:09.968  1818  7467 I CheckinService: active receiver: disabled
08-10 07:41:09.973  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 07:41:09.988  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:09.988  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:09.990  7134  7134 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 07:41:09.994  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-10 07:41:09.999  7062  7062 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-10 07:41:10.003  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:10.015  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.026  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.041  1037  1541 D WifiOffDelayIfNotUsed: stopMonitoring
08-10 07:41:10.042  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 07:41:10.042  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-10 07:41:10.042  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-10 07:41:10.043  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:10.043  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:10.044  1037  1380 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1010898462, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
08-10 07:41:10.044  7134  7134 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:10.047  1944  1944 D WfdsService: Supplicant Connection state is changed : false
08-10 07:41:10.047  1944  2358 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-10 07:41:10.048  1944  2358 D WfdsService: Set the WFDS Monitor: false
08-10 07:41:10.048  1944  2358 D WfdsMonitor: WFDS Monitor is stopped
08-10 07:41:10.049  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:10.050  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-10 07:41:10.051  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-10 07:41:10.051  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-10 07:41:10.051  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-10 07:41:10.053  2460  2460 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:10.054  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:10.054  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:10.054  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:10.054  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:10.054  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:10.054  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:10.054  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:10.054  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:10.054  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:10.056  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 07:41:10.056  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:10.056  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:10.056  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:10.056  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:10.056  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:10.056  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-10 07:41:10.056  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:10.056  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:10.064  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:10.075  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE,
,08-10 07:41:10.082  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.090  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:10.090  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:10.091  7134  7134 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:10.097  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:10.106  2621  2621 D [Concierge]Service: onStartCommand(). Type : 9
08-10 07:41:10.115  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.129  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.141  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:10.142  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:10.142  7134  7134 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 07:41:10.146  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:10.159  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.169  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.182  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:10.182  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:10.183  7134  7134 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 07:41:10.191  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:10.203  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.213  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.226  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:10.227  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:10.228  7134  7134 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:10.243  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:10.269  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.280  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.296  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:10.297  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:10.306  7134  7134 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:10.308  6852  7246 D UEI.SmartControl: Internal timer expired: 2
08-10 07:41:10.308  6852  7246 D UEI.SmartControl: unbind internal service
,08-10 07:41:10.315  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:10.336  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.362  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 07:41:10.381  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:10.382  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:10.384  7134  7134 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:10.393  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:10.401  7104  7104 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-10 07:41:10.416  1037  1546 D WifiService: New client listening to asynchronous messages
08-10 07:41:10.416  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:10.424  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.439  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.454  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:10.455  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:10.460  7134  7134 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 07:41:10.462  7134  7134 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 07:41:10.463  7134  7134 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-10 07:41:10.473  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:10.484  7104  7104 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 07:41:10.487  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:10.490  6852  7240 D serial_port: close(fd = 24)
08-10 07:41:10.494  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 07:41:10.495  6852  7240 I UEI.SmartControl: Serial port is closed.
,08-10 07:41:10.504  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.512  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:10.513  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:10.513  7134  7134 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.,
,08-10 07:41:10.514  7134  7134 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-10 07:41:10.515  7134  7134 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-10 07:41:10.516  1037  1380 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2047ced8 type 2 when 331761 com.google.android.gms} when 331761
08-10 07:41:10.520  1037  1900 I ActivityManager: Killing 7084:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-10 07:41:10.588  1037  1053 W libprocessgroup: failed to open /acct/uid_10037/pid_7084/cgroup.procs: No such file or directory
,08-10 07:41:10.603  2182  2182 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-10 07:41:10.626  2182  2182 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-10 07:41:10.629  2182  2182 D c       : Getting all permits...
08-10 07:41:10.629  2182  2182 D a       : Opening database...
08-10 07:41:10.644  2182  2182 D a       : Opening database auth.proximity.permit_store...
,08-10 07:41:10.645  2182  2182 D a       : Closing database...
08-10 07:41:10.667  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:10.673  7104  7104 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 07:41:10.673  7104  7104 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 07:41:10.673  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:10.680  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.692  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.704  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:10.705  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:10.709  7134  7134 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 07:41:10.717  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:10.724  7104  7104 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 07:41:10.725  7104  7104 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 07:41:10.725  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:10.733  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 07:41:10.742  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 07:41:10.751  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:10.751  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:10.754  7134  7134 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 07:41:10.761  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:10.771  7104  7104 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-10 07:41:10.771  7104  7104 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 07:41:10.771  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:10.778  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:10.791  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.803  7134  7134 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:10.804  7134  7134 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:10.807  7134  7134 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 07:41:10.819  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:10.829  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 07:41:10.840  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:10.854  7176  7640 W FormManager: Network not available. Please check & try again.
,08-10 07:41:10.861  7176  7641 V FormManager: Network unavailable.
08-10 07:41:10.868  7176  7641 V FormManager: Network unavailable.
08-10 07:41:10.874  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-10 07:41:10.874  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 07:41:10.874  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 07:41:10.874  7062  7062 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 07:41:10.875  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 07:41:10.876  7062  7062 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 07:41:10.876  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 07:41:10.876  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 07:41:10.876  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 07:41:10.876  7062  7062 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 07:41:10.876  7062  7062 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 07:41:10.887  2182  2182 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-10 07:41:10.906  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 07:41:10.906  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:10.908  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 07:41:10.911  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:10.915  4638  7642 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 07:41:10.918  4638  7643 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 07:41:10.918  4638  7643 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:10.922  7104  7104 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-10 07:41:10.922  7104  7104 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-10 07:41:10.923  7104  7104 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:10.928  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 07:41:10.934  7176  7645 W FormManager: Network not available. Please check & try again.
08-10 07:41:10.935  7176  7646 V FormManager: Network unavailable.
,08-10 07:41:10.938  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 07:41:10.944  7176  7646 V FormManager: Network unavailable.
08-10 07:41:10.960  7134  7134 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-10 07:41:10.960  7134  7134 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5444
08-10 07:41:10.964  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1010898462 [*alarm*], flags=0x0
,08-10 07:41:11.460  1037  1541 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:1928856228] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 07:41:11.471  1037  1541 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1928856230] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 07:41:11.676  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:11.706  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,08-10 07:41:11.714  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:11.715  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:11.720  1037  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:11.726  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 07:41:11.729  6461  7103 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 07:41:11.736  5753  5753 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 07:41:11.755  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:11.798  1037  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 07:41:11.803  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 07:41:11.803  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:11.803  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 07:41:11.803  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 07:41:11.805  7269  7269 I AppUp4:CustModeStarterReceiver: onReceive
08-10 07:41:11.809  7269  7269 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7297cc2
08-10 07:41:11.809  7269  7269 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 07:41:11.809  7269  7269 D AppUp4:CustFacade: isPhone : true
08-10 07:41:11.810  7269  7269 D AppUp4:CustModeStarterReceiver: begin check event
08-10 07:41:11.810  7269  7269 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 07:41:11.817  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:11.817  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:11.819  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 07:41:11.824  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 07:41:11.837  7297  7297 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 07:41:11.859  4638  7663 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 07:41:11.864  4638  7668 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:11.864  4638  7668 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:11.874  3350  3350 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 07:41:11.874  3350  3350 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:11.874  3350  3350 I LgeMiscReceiver: networkInfo.isConnected() = true
08-10 07:41:11.874  3350  3350 D PhoneState: setPdpRejectCasuse : false
,08-10 07:41:11.877  7346  7346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 07:41:11.878  7297  7666 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:11.878  7346  7346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 07:41:11.892  7408  7408 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:11
,08-10 07:41:11.895  7408  7408 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-10 07:41:11.895  7408  7408 D Weather.Utils: 2 : All the weather widget is gone.
08-10 07:41:11.896  7176  7671 W FormManager: Network not available. Please check & try again.
08-10 07:41:11.896  7408  7408 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 07:41:11.896  7408  7408 D WeatherAncestor: connectivity changed - connection : true
08-10 07:41:11.896  7408  7408 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2fb0f610
08-10 07:41:11.897  7408  7408 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 07:41:11.897  7408  7408 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 07:41:11.897  7408  7408 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 07:41:11.897  7408  7408 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 07:41:11.897  7408  7408 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:11
08-10 07:41:11.912  7176  7672 V FormManager: Network unavailable.
,08-10 07:41:11.922  7176  7672 V FormManager: Network unavailable.
,08-10 07:41:12.531  1037  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:12.532  1037  1649 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-10 07:41:12.565  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 07:41:12.566  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 07:41:12.566  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-10 07:41:12.566  1037  1119 D BluetoothManagerService: Message: 1
08-10 07:41:12.566  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-10 07:41:12.594  1037  1119 D BluetoothManagerService: Message: 20
08-10 07:41:12.594  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b35b7c6:true
,08-10 07:41:12.599  7205  7205 D BluetoothAdapterState: make
08-10 07:41:12.607  7205  7205 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-10 07:41:12.607  7205  7205 I bluedroid-qcom: init
08-10 07:41:12.610  7205  7680 I BluetoothAdapterState: Entering OffState
,08-10 07:41:12.612  7205  7205 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 07:41:12.612  7205  7205 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 07:41:12.612  7205  7205 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 07:41:12.613  7205  7205 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 07:41:12.613  7205  7205 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-10 07:41:12.615  7205  7205 I bluedroid-qcom: get_profile_interface socket
08-10 07:41:12.615  7205  7205 I bluedroid-qcom: get_profile_interface map_client
08-10 07:41:12.616  7205  7684 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-10 07:41:12.610  7683  7683 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:12.610  7683  7683 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:12.630  7683  7683 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-10 07:41:12.630  7683  7683 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-10 07:41:12.630  7683  7683 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-10 07:41:12.635  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-10 07:41:12.637  1037  1119 D BluetoothManagerService: Message: 40
08-10 07:41:12.637  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-10 07:41:12.638  7205  7222 I bluedroid-qcom: config_hci_snoop_log
08-10 07:41:12.639  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-10 07:41:12.639  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-10 07:41:12.642  7683  7683 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-10 07:41:12.648  7205  7680 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-10 07:41:12.648  7205  7680 D BluetoothAdapterProperties: Setting state to 11
08-10 07:41:12.649  7205  7680 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-10 07:41:12.652  7205  7680 I LGBluetoothServiceJni: classInitNative: succeeds
08-10 07:41:12.652  1037  1119 D BluetoothManagerService: Message: 60
08-10 07:41:12.652  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-10 07:41:12.652  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-10 07:41:12.655  7205  7684 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-10 07:41:12.657  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:12.659  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:12.660  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 07:41:12.661  7683  7683 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-10 07:41:12.661  7683  7683 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-10 07:41:12.669  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:12.673  7062  7062 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-10 07:41:12.676  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:12.679  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:12.693  1037  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:12.693  7205  7205 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 07:41:12.694  1037  1119 D Tethering: MasterInitialState.processMessage what=3
08-10 07:41:12.694  7205  7205 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:12.694  7205  7205 V BluetoothPbapReceiver: ***********state = 11
,08-10 07:41:12.708  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,08-10 07:41:12.714  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:12.715  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:12.716  7205  7684 D BluetoothAdapterProperties: Name is: G3
08-10 07:41:12.718  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:12.719  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 07:41:12.722  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:12.723  7205  7680 D BluetoothBondStateMachine: make
,08-10 07:41:12.725  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 07:41:12.725  7205  7701 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 07:41:12.725  7205  7680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:12.726  7205  7680 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-10 07:41:12.726  7205  7680 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:12.726  7205  7680 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-10 07:41:12.726  5753  5753 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-10 07:41:12.726  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 07:41:12.726  6461  7103 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 07:41:12.726  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 07:41:12.726  7205  7680 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-10 07:41:12.730  7205  7680 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:12.735  5753  5753 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-10 07:41:12.783  1037  2034 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7703 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-10 07:41:12.794  7205  7205 D HeadsetService: Received start request. Starting profile...
08-10 07:41:12.795  7205  7205 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 07:41:12.795  7205  7205 D LGBluetoothHfpAdapter: Version 1.6
08-10 07:41:12.798  7205  7205 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 07:41:12.799  7205  7205 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 07:41:12.799  7205  7205 D HeadsetStateMachine: make
08-10 07:41:12.799  1037  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:12.801  1037  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:12.801  1037  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:12.803  7205  7680 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 07:41:12.810  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:12.822  7205  7680 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:12.830  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 07:41:12.830  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:12.830  7205  7680 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:12.830  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 07:41:12.830  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 07:41:12.832  7205  7205 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:12.833  7205  7205 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 07:41:12.833  7269  7269 I AppUp4:CustModeStarterReceiver: onReceive
08-10 07:41:12.840  7269  7269 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7297cc2
08-10 07:41:12.840  7269  7269 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 07:41:12.840  7269  7269 D AppUp4:CustFacade: isPhone : true
08-10 07:41:12.840  7269  7269 D AppUp4:CustModeStarterReceiver: begin check event
08-10 07:41:12.841  7269  7269 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-10 07:41:12.953  1037  2034 I art     : Explicit concurrent mark sweep GC freed 130021(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.672ms total 119.173ms
,08-10 07:41:12.955  7205  7205 D HeadsetStateMachine: max_hf_connections = 1
08-10 07:41:12.955  7205  7205 I bluedroid-qcom: get_profile_interface handsfree
08-10 07:41:12.956  7205  7680 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:12.958  7205  7205 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-10 07:41:12.960   315  1386 V AudioPolicyService: registerClient() client 0xb1427160, uid 1002
08-10 07:41:12.960   315  2147 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-10 07:41:12.960   315  2147 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 07:41:12.960   315  2147 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 07:41:12.961  7205  7205 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 07:41:12.962   315  2147 V AudioFlinger: registerClient() client 0xb101b070, pid 7205
08-10 07:41:12.962   315  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:12.962   315  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:12.963   315  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:12.963  1605  1625 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:12.963  1605  1625 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:12.963   315  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:12.964  1037  1925 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:12.964  1037  1925 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:12.964  7205  7205 V ToneGenerator: Create Track: 0xb4928080
08-10 07:41:12.964  7205  7205 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
,08-10 07:41:12.964  7205  7205 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-10 07:41:12.964  7205  7221 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:12.964  7205  7221 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-10 07:41:12.964   315  2146 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 07:41:12.964   315  2146 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-10 07:41:12.964   315  2146 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 07:41:12.964   315  2146 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 07:41:12.964   315  1387 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 07:41:12.965   315  1386 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 07:41:12.965   315  1386 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-10 07:41:12.965   315  1386 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 07:41:12.965   315  1386 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 07:41:12.965  7205  7205 V AudioSystem: getLatency() output 2, latency 50
08-10 07:41:12.965  7205  7205 V AudioSystem: getFrameCount() output 2, frameCount 960
08-10 07:41:12.965  7205  7205 V AudioTrack: createTrack_l() output 2 afLatency 50
08-10 07:41:12.965  3350  3371 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:12.965  3350  3371 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:12.965   315  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 07:41:12.965   315  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 07:41:12.965   315  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 07:41:12.965   315  2146 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 07:41:12.965   315  2146 V AudioFlinger: createTrack() lSessionId: 22
08-10 07:41:12.966  1853  2752 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:12.966  1853  2752 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:12.966  1605  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:12.966  1605  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:12.966  1037  1900 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:12.966  1037  1900 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:12.966  7205  7697 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:12.966  7205  7697 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-10 07:41:12.966  1853  2752 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:12.966  1853  2752 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:12.966  3350  3367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:12.966  3350  3367 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:12.967  7205  7205 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-10 07:41:12.968   315   315 V AudioFlinger: acquiring 22 from 7205, for 7205
08-10 07:41:12.968   315   315 V AudioFlinger:  added new entry for 22
08-10 07:41:12.968  7205  7205 V ToneGenerator: ToneGenerator INIT OK, time: 334226
08-10 07:41:12.968  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:12.969  7205  7720 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-10 07:41:12.970  7205  7720 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 07:41:12.,970  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:12.970  7205  7720 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 07:41:12.970  7205  7720 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-10 07:41:12.971  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:12.971   315  1387 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7205
08-10 07:41:12.972   315  1387 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-10 07:41:12.972   315  1387 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-10 07:41:12.972   315  1387 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-10 07:41:12.972   315  1387 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-10 07:41:12.972   315  1387 V voice   : voice_set_parameters: exit with code(0)
08-10 07:41:12.972   315  1387 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-10 07:41:12.972   315  1387 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-10 07:41:12.972   315  1387 V msm8974_platform: platform_set_parameters: exit with code(0)
08-10 07:41:12.972   315  1387 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-10 07:41:12.972   315  1387 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-10 07:41:12.972  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:12.974  7205  7205 D A2dpService: Received start request. Starting profile...
08-10 07:41:12.975  7205  7205 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 07:41:12.976  7205  7205 V Avrcp   : make
08-10 07:41:12.976  7205  7205 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-10 07:41:12.976  7205  7205 I bluedroid-qcom: get_profile_interface avrcp
08-10 07:41:12.977   315  1387 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-10 07:41:12.977  7205  7720 V ToneGenerator: ToneGenerator destructor
08-10 07:41:12.977  7205  7720 V ToneGenerator: stopTone
08-10 07:41:12.977  7205  7720 V ToneGenerator: Delete Track: 0xb4928080
08-10 07:41:12.978  7205  7720 V AudioTrack: ~AudioTrack, releasing session id from 7205 on behalf of 7205
08-10 07:41:12.978  7205  7680 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:12.978   315  1386 V AudioFlinger: releasing 22 from 7205 for 7205
08-10 07:41:12.978   315  1386 V AudioFlinger:  decremented refcount to 0
08-10 07:41:12.978   315  1386 V AudioFlinger: purging stale effects
08-10 07:41:12.978   315  1386 V AudioPolicyService: AudioCommandThread() adding release output 2
08-10 07:41:12.978   315  1386 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-10 07:41:12.978   315  1386 V AudioFlinger: PlaybackThread::Track destructor
08-10 07:41:12.978   315  1275 V AudioPolicyService: AudioCommandThread() waking up
,08-10 07:41:12.978   315  1386 V AudioFlinger: removeClient_l() pid 7205, calling pid 315
08-10 07:41:12.978   315  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-10 07:41:12.978   315  1275 V AudioPolicyManager: releaseOutput() 2
08-10 07:41:12.978   315  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-10 07:41:12.983  7205  7680 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:12.984  7205  7205 V AudioManager: registerRemoteController: size of Media player list: 0
08-10 07:41:12.984  7703  7703 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-10 07:41:12.985  7703  7703 W LG Account v2.2: No ProfileInfo entries
08-10 07:41:12.985  7703  7703 I LG Account v2.2: isEnabled: false
08-10 07:41:12.985  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:12.986  7205  7205 E AudioManager: No RCC entry present to update
08-10 07:41:12.986  7205  7205 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-10 07:41:12.989  7205  7205 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-10 07:41:12.990  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-10 07:41:12.990  7205  7205 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-10 07:41:12.991  7703  7703 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 07:41:12.991  7703  7703 I Feature : [Lifetracker]Country: EU
08-10 07:41:12.991  7703  7703 I Feature : [Lifetracker]Operator: OPEN
08-10 07:41:12.992  7703  7703 I Feature : [Lifetracker]Ranking support: false
08-10 07:41:12.992  7703  7703 I Feature : [Lifetracker]Comfort support: false
08-10 07:41:12.992  7703  7703 I Feature : [Lifetracker]Accessory: true
08-10 07:41:12.992  7703  7703 I Feature : [Lifetracker]Health device: true
08-10 07:41:12.992  7703  7703 I Feature : [Lifetracker]Extra Pedometer: false
08-10 07:41:12.992  7703  7703 I Feature : [Lifetracker]Blood glucose device: false
,08-10 07:41:12.993  7703  7703 I Feature : [Lifetracker]Device Number: 3
08-10 07:41:12.994  7205  7680 V LGMDMManager: Create singleton instance
08-10 07:41:12.995  7205  7680 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-10 07:41:12.998  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:12.998  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 07:41:13.004  4638  7727 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-10 07:41:13.006  4638  7728 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:13.006  4638  7728 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:13.052  7062  7062 D BluetoothPermissionRequest: onReceive
,08-10 07:41:13.067  7297  7297 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 07:41:13.070  7062  7062 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 07:41:13.093  3350  3350 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 07:41:13.093  3350  3350 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:13.093  3350  3350 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-10 07:41:13.096  7346  7346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 07:41:13.097  7346  7346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 07:41:13.099  7176  7731 W FormManager: Network not available. Please check & try again.
08-10 07:41:13.099  7297  7729 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:13.105  7176  7732 V FormManager: Network unavailable.
,08-10 07:41:13.108  1037  1900 V SIM_STK : Menu title from STK is T-Mobile
08-10 07:41:13.108  1037  1900 V SIM_STK : Menu title from STK is T-Mobile
08-10 07:41:13.108  7408  7408 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:13
08-10 07:41:13.109  7408  7408 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 07:41:13.109  7408  7408 D Weather.Utils: 2 : All the weather widget is gone.
08-10 07:41:13.110  7408  7408 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 07:41:13.110  7408  7408 D WeatherAncestor: connectivity changed - connection : true
08-10 07:41:13.110  7408  7408 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2fb0f610
08-10 07:41:13.110  7408  7408 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 07:41:13.110  7408  7408 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 07:41:13.110  7176  7732 V FormManager: Network unavailable.
08-10 07:41:13.110  7408  7408 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 07:41:13.110  7408  7408 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 07:41:13.110  7408  7408 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:13
08-10 07:41:13.131  6461  6461 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-10 07:41:13.133  6461  7103 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-10 07:41:13.146  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:13.159  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 07:41:13.159  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:13.159  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 07:41:13.159  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-10 07:41:13.160  1037  1879 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-10 07:41:13.162  7269  7269 I AppUp4:CustModeStarterReceiver: onReceive
08-10 07:41:13.164  7269  7269 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7297cc2
08-10 07:41:13.164  7269  7269 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 07:41:13.164  7269  7269 D AppUp4:CustFacade: isPhone : true
08-10 07:41:13.164  7269  7269 D AppUp4:CustModeStarterReceiver: begin check event
08-10 07:41:13.164  7269  7269 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 07:41:13.165  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 07:41:13.166  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:13.166  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 07:41:13.168  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 07:41:13.169  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 07:41:13.169  7205  7205 I BluetoothA2dpServiceJni: classInitNative
08-10 07:41:13.169  7205  7205 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 07:41:13.169  7205  7205 D A2dpStateMachine: make
08-10 07:41:13.169  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:13.171  7205  7205 I bluedroid-qcom: get_profile_interface a2dp
08-10 07:41:13.171  7205  7735 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-10 07:41:13.171  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-10 07:41:13.174  7205  7205 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-10 07:41:13.174  7205  7205 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-10 07:41:13.175  7205  7734 D A2dpStateMachine: Enter Disconnected: -2
,08-10 07:41:13.175  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:13.175  7297  7297 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-10 07:41:13.176  7205  7205 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 07:41:13.177  7205  7205 D HidService: Received start request. Starting profile...
08-10 07:41:13.178  7205  7205 I bluedroid-qcom: get_profile_interface hidhost
08-10 07:41:13.178  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:13.178  7205  7205 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 07:41:13.180  4638  7738 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 07:41:13.180  7205  7205 D HealthService: Received start request. Starting profile...
08-10 07:41:13.181  7205  7205 I bluedroid-qcom: get_profile_interface health
08-10 07:41:13.182  7205  7205 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-10 07:41:13.182  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:13.183  4638  7739 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:13.183  4638  7739 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:13.183  7205  7205 D HeadsetStateMachine: Proxy object connected
08-10 07:41:13.184  7205  7205 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-10 07:41:13.184  7205  7205 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-10 07:41:13.186  7205  7205 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-10 07:41:13.188  7205  7205 D PanService: Received start request. Starting profile...
08-10 07:41:13.188  7205  7205 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 07:41:13.188  7205  7205 I bluedroid-qcom: get_profile_interface pan
08-10 07:41:13.188  7297  7743 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:13.190  3350  3350 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 07:41:13.190  3350  3350 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:13.190  3350  3350 I LgeMiscReceiver: networkInfo.isConnected() = false
08-10 07:41:13.193  7346  7346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 07:41:13.193  7346  7346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-10 07:41:13.194  7205  7205 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-10 07:41:13.194  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:13.197  7205  7205 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:13.197  7205  7720 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 07:41:13.198  7205  7720 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 07:41:13.198  7205  7720 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-10 07:41:13.198  7205  7205 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-10 07:41:13.200  7176  7746 W FormManager: Network not available. Please check & try again.
08-10 07:41:13.203  7205  7205 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 07:41:13.204  7205  7205 D BtGatt.GattService: Received start request. Starting profile...
08-10 07:41:13.204  7205  7205 D BtGatt.GattService: start()
08-10 07:41:13.204  7205  7205 I bluedroid-qcom: get_profile_interface gatt
08-10 07:41:13.204  7205  7205 D BtGatt.AdvertiseManager: advertise manager created
08-10 07:41:13.205  7408  7408 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:13
08-10 07:41:13.207  7408  7408 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-10 07:41:13.207  7408  7408 D Weather.Utils: 2 : All the weather widget is gone.
08-10 07:41:13.207  7408  7408 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 07:41:13.207  7408  7408 D WeatherAncestor: connectivity changed - connection : true
08-10 07:41:13.207  7408  7408 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2fb0f610
08-10 07:41:13.208  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:13.208  7408  7408 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 07:41:13.208  7408  7408 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 07:41:13.208  7408  7408 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-10 07:41:13.208  7408  7408 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 07:41:13.208  7408  7408 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:13
08-10 07:41:13.209  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:13.209  7205  7205 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-10 07:41:13.209  7205  7205 V BluetoothMapService: BluetoothMapBinder()
08-10 07:41:13.210  7205  7205 D BluetoothMapService: Received start request. Starting profile...
08-10 07:41:13.210  7205  7205 D BluetoothMapService: start()
08-10 07:41:13.213  7205  7205 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-10 07:41:13.213  7205  7205 D BluetoothMapEmailAppObserver: createReceiver()
08-10 07:41:13.214  7176  7747 V FormManager: Network unavailable.
08-10 07:41:13.216  7205  7205 D BluetoothMapEmailAppObserver: initObservers()
08-10 07:41:13.216  7205  7205 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-10 07:41:13.218  7176  7747 V FormManager: Network unavailable.
08-10 07:41:13.221  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
,08-10 07:41:13.226  7205  7205 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:13.228  7205  7205 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:13.230  7205  7205 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:13.232  7205  7205 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:13.232  7205  7205 V PanService: [BTUI] SIM Extra State :ABSENT
08-10 07:41:13.234  7205  7205 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-10 07:41:13.234  7205  7205 V BluetoothMapService: Handler(): got msg=1
08-10 07:41:13.235  7205  7680 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-10 07:41:13.235  7205  7680 I bluedroid-qcom: enable
08-10 07:41:13.235  7205  7750 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-10 07:41:13.235  7205  7680 I bt_hci_bdroid: init
08-10 07:41:13.236  7205  7205 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:13.236  7205  7680 I bt_vendor: bt-vendor : init
08-10 07:41:13.236  7205  7680 I bt_vendor: bt-vendor : get_bt_soc_type
08-10 07:41:13.236  7205  7680 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-10 07:41:13.236  7205  7680 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-10 07:41:13.236  7205  7680 D bt_userial_mct: userial_init
08-10 07:41:13.236  7205  7750 I bt-btu  : btu_task pending for preload complete event
08-10 07:41:13.236  7205  7680 D bt_hci_bdroid: set_power 1
08-10 07:41:13.236  7205  7680 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-10 07:41:13.236  7205  7680 I bt_vendor: Starting hciattach daemon
08-10 07:41:13.236  7205  7680 I bt_vendor: try to set true
08-10 07:41:13.237  7205  7205 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 07:41:13.237  7205  7205 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 07:41:13.237  7205  7205 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 07:41:13.237  7205  7205 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-10 07:41:13.237  7205  7205 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-10 07:41:13.230  7753  7753 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:13.230  7753  7753 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:13.240  1037  3484 I LocationManagerService: remove 178a3d4b
08-10 07:41:13.240  1037  3484 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-10 07:41:13.240  1037  3484 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 07:41:13.240  1037  3484 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-10 07:41:13.241  1037  3484 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-10 07:41:13.241  1037  3484 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-10 07:41:13.252  7754  7754 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-10 07:41:13.294  7760  7760 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-10 07:41:13.304  7761  7761 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-10 07:41:13.320  7763  7763 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 07:41:13.331  7764  7764 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-10 07:41:13.342  7765  7765 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-10 07:41:13.353  7766  7766 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-10 07:41:13.389  7768  7768 I libmdmdetect: ESOC framework not supported
,08-10 07:41:13.391  7768  7768 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-10 07:41:13.404  7768  7768 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-10 07:41:13.404  7768  7768 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-10 07:41:13.404  7768  7768 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-10 07:41:13.404  7768  7768 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-10 07:41:13.404  7768  7768 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-10 07:41:13.404  7768  7768 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-10 07:41:13.404  7768  7768 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-10 07:41:13.450  7768  7769 E QC-QMI  : qmi_client [7768] 14: failed to locate client data
08-10 07:41:13.452   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-10 07:41:13.452   485   485 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-10 07:41:13.517  7770  7770 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-10 07:41:13.535  7771  7771 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 07:41:13.589  7205  7680 I bt_vendor: bluetooth satus is on
08-10 07:41:13.590  7205  7680 D bt_hci_bdroid: preload
08-10 07:41:13.590  7205  7752 D bt_userial_mct: userial_open(port:0)
08-10 07:41:13.590  7205  7752 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-10 07:41:13.594  7205  7752 I bt_vendor: Done intiailizing UART
,08-10 07:41:13.598  7205  7752 I bt_vendor: Done intiailizing UART
,08-10 07:41:13.598  7205  7752 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-10 07:41:13.598  7205  7752 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-10 07:41:13.599  7205  7750 I bt-btu  : btu_task received preload complete event
08-10 07:41:13.600  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-10 07:41:13.600  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-10 07:41:13.602  7205  7773 D bt_userial_mct: Entering userial_read_thread()
08-10 07:41:13.607  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 07:41:13.616  7205  7750 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 07:41:13.617  7205  7750 I         : BTE_InitTraceLevels -- TRC_BTIF
08-10 07:41:13.710  7205  7750 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-10 07:41:13.710  7205  7750 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01bd061 
08-10 07:41:13.711  7205  7750 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01bd061 
,08-10 07:41:13.740  7205  7684 E bt-btif : Calling BTA_HhEnable
,08-10 07:41:13.740  7205  7684 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-10 07:41:13.740  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-10 07:41:13.740  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-10 07:41:13.740  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-10 07:41:13.741  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-10 07:41:13.741  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-10 07:41:13.741  7205  7684 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 07:41:13.744  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 07:41:13.744  7205  7684 D BluetoothAdapterProperties: Name is: G3
08-10 07:41:13.745  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 07:41:13.746  7205  7684 D BluetoothAdapterProperties: Scan Mode:20
08-10 07:41:13.747  7205  7684 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 07:41:13.747  7205  7684 D bt_hci_bdroid: postload
08-10 07:41:13.749  7205  7750 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-10 07:41:13.750  7205  7684 D bte_conf: Device ID record 1 : primary
08-10 07:41:13.750  7205  7684 D bte_conf:   vendorId            = 00c4
08-10 07:41:13.750  7205  7684 D bte_conf:   vendorIdSource      = 0001
08-10 07:41:13.750  7205  7684 D bte_conf:   product             = 13a1
08-10 07:41:13.750  7205  7684 D bte_conf:   version             = 1000
08-10 07:41:13.750  7205  7684 D bte_conf:   clientExecutableURL = 
08-10 07:41:13.750  7205  7684 D bte_conf:   serviceDescription  = 
08-10 07:41:13.750  7205  7684 D bte_conf:   documentationURL    = 
08-10 07:41:13.750  7205  7684 D bte_conf: bte_load_did_conf no section named DID2.
08-10 07:41:13.751  7205  7752 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:13.751  7205  7752 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:13.751  7205  7752 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:13.753  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:13.755  7205  7752 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:13.755  7205  7752 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:13.750  7779  7779 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:13.750  7779  7779 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:13.761  7205  7750 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:13.761  7205  7750 W bt-smp  : Plain text(LSB ~ MSB) = ba 47 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:13.761  7205  7750 W bt-smp  : Encrypted text(LSB ~ MSB) = 92 22 74 d4 00 95 f4 f8 63 e6 b8 41 ca 9f cb 11 
08-10 07:41:13.761  7205  7750 W bt-btm  : Stopping oneshot timer
08-10 07:41:13.763  7205  7752 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:13.763  7205  7752 D bt_hci_bdroid: Used up Tx Cmd credits
,08-10 07:41:13.764  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:13.766  7205  7684 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 07:41:13.766  7205  7680 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-10 07:41:13.767  7205  7773 E bt_mct  : hci lib postload completed
08-10 07:41:13.767  7205  7680 D BluetoothAdapterProperties: ScanMode =  20
08-10 07:41:13.767  7205  7680 D BluetoothAdapterProperties: State =  11
08-10 07:41:13.768  7205  7680 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-10 07:41:13.768  7205  7680 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-10 07:41:13.768  7205  7680 D BluetoothAdapterProperties: Setting state to 12
08-10 07:41:13.768  7205  7680 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 07:41:13.769  7205  7684 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 07:41:13.772  1037  1119 D BluetoothManagerService: Message: 60
08-10 07:41:13.772  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-10 07:41:13.772  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-10 07:41:13.772  7205  7680 I BluetoothAdapterState: Entering On State
08-10 07:41:13.772  7062  7083 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 07:41:13.777  7205  7680 D LGBluetoothServiceAdapter: [BTUI] OnState
08-10 07:41:13.777  7205  7680 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-10 07:41:13.777  7205  7680 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-10 07:41:13.778  7205  7680 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-10 07:41:13.780  7205  7684 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 07:41:13.780  7205  7684 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-10 07:41:13.781  7062  7082 D BluetoothMap: onBluetoothStateChange: up=true
08-10 07:41:13.785  7062  7083 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 07:41:13.787  1853  2752 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 07:41:13.787  7062  7062 D BluetoothMap: Proxy object connected
08-10 07:41:13.787  7062  7062 D MapProfile: Bluetooth service connected
08-10 07:41:13.788  7062  7062 D BluetoothMap: getConnectedDevices()
08-10 07:41:13.789  7205  7222 V BluetoothMapService: getConnectedDevices()
08-10 07:41:13.790  7062  7062 D BluetoothInputDevice: Proxy object connected
08-10 07:41:13.790  7062  7062 D HidProfile: Bluetooth service connected
08-10 07:41:13.791  7205  7750 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:13.791  7205  7750 W bt-smp  : Plain text(LSB ~ MSB) = a1 1b 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:13.791  7205  7750 W bt-smp  : Encrypted text(LSB ~ MSB) = 07 ed 44 57 0f 2d b7 11 e7 43 2d 17 60 b2 6a 6a 
08-10 07:41:13.791  7205  7750 W bt-btm  : Stopping oneshot timer
,08-10 07:41:13.794  1853  1853 D BluetoothHeadset: Proxy object connected
08-10 07:41:13.796  7062  7083 D BluetoothPan: onBluetoothStateChange on: true
08-10 07:41:13.797  7062  7083 D BluetoothPan: onBluetoothStateChange call bindService
08-10 07:41:13.799  1853  2752 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 07:41:13.802  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 07:41:13.802  1853  1853 D BluetoothHeadset: Proxy object connected
,08-10 07:41:13.806  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 07:41:13.806  7205  7750 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:13.806  7205  7750 W bt-smp  : Plain text(LSB ~ MSB) = 89 4f 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:13.806  7205  7750 W bt-smp  : Encrypted text(LSB ~ MSB) = 29 99 68 94 03 84 7a ce 9f f9 9c 05 c3 e6 bc f4 
08-10 07:41:13.806  7205  7750 W bt-btm  : Stopping oneshot timer
08-10 07:41:13.806  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 07:41:13.806  1853  1853 D BluetoothHeadset: Proxy object connected
08-10 07:41:13.807  1037  1037 D BluetoothHeadset: Proxy object connected
08-10 07:41:13.808  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-10 07:41:13.808  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-10 07:41:13.815  6960  6960 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 07:41:13.815  7062  7062 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 07:41:13.815  7062  7062 D PanProfile: Bluetooth service connected
08-10 07:41:13.815  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 07:41:13.816  7205  7750 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:13.816  7205  7750 W bt-smp  : Plain text(LSB ~ MSB) = 90 14 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:13.816  7205  7750 W bt-smp  : Encrypted text(LSB ~ MSB) = d8 83 37 49 fc 6d 2e fc 5c ac 79 f2 64 70 2a 54 
08-10 07:41:13.816  7205  7750 W bt-btm  : Stopping oneshot timer
08-10 07:41:13.820  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:13.821  1944  2144 D LGBluetoothAPIService: Message: 1
08-10 07:41:13.821  1944  2144 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-10 07:41:13.821  7205  7680 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-10 07:41:13.827  1944  2144 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-10 07:41:13.833  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:13.833  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:13.833  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:13.833  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:13.833  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:13.833  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:13.833  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:13.833  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:13.835  7205  7750 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:13.835  7205  7750 W bt-smp  : Plain text(LSB ~ MSB) = 35 17 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:13.835  7205  7750 W bt-smp  : Encrypted text(LSB ~ MSB) = 6b fd 1c 15 dd 93 3a 6a 21 be 18 57 54 9c bd 05 
08-10 07:41:13.835  7205  7750 W bt-btm  : Stopping oneshot timer
,08-10 07:41:13.838  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:13.841  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:13.841  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:13.841  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:13.841  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:13.841  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:13.841  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:13.841  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:13.841  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:13.843  1037  1037 D BluetoothA2dp: Proxy object connected
08-10 07:41:13.844  7205  7205 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:13.844  7205  7205 D BluetoothMapService: STATE_ON
08-10 07:41:13.846  7788  7788 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-10 07:41:13.846  7205  7205 D LGBluetoothAPIServer: [BTUI] onCreate()
08-10 07:41:13.846  7205  7205 D LGBluetoothAPIServer: [BTUI] onBind()
08-10 07:41:13.850  7442  7480 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-10 07:41:13.850  7205  7205 V BluetoothMapService: Handler(): got msg=1
08-10 07:41:13.851  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-10 07:41:13.851  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:13.851  1944  2144 D LGBluetoothAPIService: Message: 100
08-10 07:41:13.851  1944  2144 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-10 07:41:13.852  7205  7205 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-10 07:41:13.853  7205  7789 D BluetoothMapMasInstance: MAS initSocket()
08-10 07:41:13.854  7205  7789 D BluetoothMapMasInstance:   masId = 00
08-10 07:41:13.854  7205  7789 D BluetoothMapMasInstance:   msgTypes = 0e
08-10 07:41:13.854  7205  7789 D BluetoothMapMasInstance:   masName = SMS/MMS
08-10 07:41:13.854  7205  7789 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-10 07:41:13.863  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-10 07:41:13.863  1037  1119 D BluetoothManagerService: Message: 40
08-10 07:41:13.863  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-10 07:41:13.864  7062  7062 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 07:41:13.869  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:13.869  7205  7205 V BluetoothPbapService: Pbap Service onCreate
08-10 07:41:13.869  7205  7205 V BluetoothPbapService: Starting PBAP service
08-10 07:41:13.870  1037  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:13.870  1037  1119 D BluetoothManagerService: Message: 30
08-10 07:41:13.871  7205  7205 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-10 07:41:13.871  7205  7205 V BluetoothPbapService: Pbap Service onBind
08-10 07:41:13.872  7205  7789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 07:41:13.872  7205  7205 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:13.873  7205  7205 V BluetoothPbapService: state: 12
08-10 07:41:13.873  7205  7205 V BluetoothPbapService: Handler(): got msg=1
08-10 07:41:13.874  7205  7789 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-10 07:41:13.875  7205  7789 V BluetoothMapMasInstance: Succeed to create listening socket 
08-10 07:41:13.875  7205  7789 D BluetoothMapMasInstance: Accepting socket connection...
08-10 07:41:13.875  7205  7205 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-10 07:41:13.876  7205  7684 D BluetoothAdapterProperties: Scan Mode:21
08-10 07:41:13.876  7205  7684 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-10 07:41:13.878  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:13.878  7205  7795 V BluetoothPbapService: Pbap Service initSocket
08-10 07:41:13.881  1037  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:13.882  7062  7062 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-10 07:41:13.882  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:13.883  7205  7795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 07:41:13.885  1037  1119 D BluetoothManagerService: Message: 30
08-10 07:41:13.886  7205  7795 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-10 07:41:13.886  7205  7795 V BluetoothPbapService: Succeed to create listening socket 
08-10 07:41:13.886  7205  7795 V BluetoothPbapService: Accepting socket connection...
08-10 07:41:13.896  7062  7062 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-10 07:41:13.898  7062  7062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 07:41:13.903  7062  7062 D BluetoothPbap: Proxy object connected
08-10 07:41:13.903  7205  7205 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 07:41:13.903  7205  7205 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:13.903  7205  7205 V BluetoothPbapReceiver: ***********state = 12
08-10 07:41:13.903  7062  7062 D PbapServerProfile: Bluetooth service connected
08-10 07:41:13.904  7062  7062 D BluetoothA2dp: Proxy object connected
08-10 07:41:13.905  7062  7062 D A2dpProfile: Bluetooth service connected
08-10 07:41:13.907  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 07:41:13.908  2182  2182 D c       : Getting all permits...
08-10 07:41:13.908  2182  2182 D a       : Opening database...
08-10 07:41:13.908  7062  7062 D BluetoothHeadset: Proxy object connected
08-10 07:41:13.909  7062  7062 D HeadsetProfile: Bluetooth service connected
08-10 07:41:13.915  2182  2182 D a       : Opening database auth.proximity.permit_store...
08-10 07:41:13.916  7062  7062 D DockEventReceiver: finishStartingService: stopping service
08-10 07:41:13.916  2182  2182 D a       : Closing database...
08-10 07:41:13.934  7062  7062 D BluetoothPermissionRequest: onReceive
,08-10 07:41:13.938  7062  7062 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 07:41:13.942  7062  7062 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 07:41:13.951  7205  7205 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-10 07:41:13.954  7205  7205 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-10 07:41:13.963  7205  7205 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-10 07:41:14.001  7205  7205 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 07:41:14.001  7205  7205 V BtOppService: onCreate
,08-10 07:41:14.007  7205  7205 V BluetoothOppNotification: send message
08-10 07:41:14.012  7205  7205 V BtOppService: Starting RfcommListener
08-10 07:41:14.026  7205  7205 D BluetoothOppPreference: Dumping Names:  
08-10 07:41:14.026  7205  7205 D BluetoothOppPreference: {}
,08-10 07:41:14.026  7205  7205 D BluetoothOppPreference: Dumping Channels:  
08-10 07:41:14.026  7205  7205 D BluetoothOppPreference: {}
08-10 07:41:14.030  7205  7205 V BtOppService: onStartCommand
,08-10 07:41:14.033  7205  7804 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 07:41:14.038  7205  7205 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:14.039  7205  7205 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 07:41:14.043  7205  7205 V BluetoothOppNotification: new notify threadi!
08-10 07:41:14.046  7205  7801 V BtOppService: Deleted complete outbound shares, number =  0
,08-10 07:41:14.047  7205  7205 V BluetoothOppNotification: send delay message
08-10 07:41:14.048  7205  7205 V BtOppService: start RfcommListener
08-10 07:41:14.048  7205  7804 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 07:41:14.052  7205  7205 V BtOppService: RfcommListener started
08-10 07:41:14.053  7205  7805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 07:41:14.055  7205  7801 V BtOppService: Deleted complete inbound failed shares, number = 0
08-10 07:41:14.055  7205  7806 V BtOppRfcommListener: Starting RFCOMM listener....
08-10 07:41:14.055  7205  7801 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-10 07:41:14.056  1037  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:14.057  7205  7805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c31312a on behalf of 
08-10 07:41:14.057  7205  7801 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e68eb1b on behalf of 
08-10 07:41:14.057  7205  7804 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@375b9a15 on behalf of 
08-10 07:41:14.059  7205  7806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 07:41:14.061  7205  7804 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 07:41:14.061  7205  7806 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-10 07:41:14.061  7205  7804 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-10 07:41:14.063  7205  7806 V BtOppRfcommListener: Started RFCOMM listener....
08-10 07:41:14.063  7205  7806 I BtOppRfcommListener: Accept thread started.
08-10 07:41:14.063  7205  7806 V BtOppRfcommListener: Accepting connection...
08-10 07:41:14.064  7205  7805 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 07:41:14.066  7205  7804 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c3084b8 on behalf of 
08-10 07:41:14.066  7205  7805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 07:41:14.067  7205  7804 V BluetoothOppNotification: update too frequent, put in queue
08-10 07:41:14.070  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:14.070  7205  7205 V BluetoothFtpService: Ftp Service onCreate
08-10 07:41:14.070  7205  7205 I BluetoothFtpService: Ftp Service onCreate
08-10 07:41:14.070  7205  7205 V BluetoothFtpService: Ftp Service onStartCommand
08-10 07:41:14.070  7205  7205 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:14.070  7205  7205 V BluetoothFtpService: Starting Listening on sockets
,08-10 07:41:14.071  7205  7205 V BtOppService: ContentObserver received notification
08-10 07:41:14.071  7205  7205 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 07:41:14.071  7205  7205 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 07:41:14.071  7205  7205 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 07:41:14.071  7205  7205 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:14.071  7205  7205 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-10 07:41:14.071  7205  7205 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 07:41:14.073  7205  7804 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 07:41:14.074  7205  7804 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-10 07:41:14.076  7205  7805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@300935f6 on behalf of 
08-10 07:41:14.076  7205  7205 V BtOppService: ContentObserver received notification
08-10 07:41:14.076  7205  7205 V BluetoothFtpService: Handler(): got msg=1
08-10 07:41:14.077  7205  7804 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34a11df7 on behalf of 
08-10 07:41:14.077  7205  7205 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-10 07:41:14.080  7205  7205 V BluetoothFtpService: Ftp Service initSocket
08-10 07:41:14.081  7205  7804 V BluetoothOppNotification: update too frequent, put in queue
08-10 07:41:14.082  7205  7805 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 07:41:14.083  1037  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:14.084  7205  7205 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 07:41:14.086  7205  7805 V BluetoothOppNotification: outbound notification was removed.
08-10 07:41:14.086  7205  7805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 07:41:14.087  7205  7205 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-10 07:41:14.088  7205  7205 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-10 07:41:14.089  7205  7804 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 07:41:14.089  7205  7804 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 07:41:14.089  7205  7805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23c53464 on behalf of 
08-10 07:41:14.090  7205  7804 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a45f6cd on behalf of 
08-10 07:41:14.091  7205  7807 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-10 07:41:14.091  7205  7804 V BluetoothOppNotification: update too frequent, put in queue
08-10 07:41:14.092  7205  7805 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 07:41:14.093  7205  7804 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 07:41:14.094  7205  7805 V BluetoothOppNotification: inbound notification was removed.
,08-10 07:41:14.094  7205  7805 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 07:41:14.095  7205  7805 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@108abb82 on behalf of 
08-10 07:41:14.119  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:14.119  7205  7205 V BluetoothSapService: Sap Service onCreate
,08-10 07:41:14.121  7205  7205 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:14.121  7205  7205 V BluetoothSapService: state: 12
08-10 07:41:14.122  7205  7205 V BluetoothSapService: Starting SAP server process
08-10 07:41:14.124  7205  7205 V BluetoothSapService: SAP Service startRfcommListenerThread
08-10 07:41:14.120  7808  7808 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 07:41:14.120  7808  7808 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:14.126  7205  7809 V BluetoothSapService: Sap Service initRfcommSocket
08-10 07:41:14.126  1037  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:14.128  7205  7809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 07:41:14.129  7205  7809 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-10 07:41:14.129  7205  7809 V BluetoothSapService: Succeed to create listening socket 
08-10 07:41:14.129  7205  7809 V BluetoothSapService: Accepting socket connection...
08-10 07:41:14.138  7808  7808 V BT_SAP  : Event pipe created
08-10 07:41:14.138  7808  7808 V BT_SAP  : create_server_socket qcom.sap.server
08-10 07:41:14.138  7808  7808 V BT_SAP  : created socket fd 6
,08-10 07:41:14.584  1037  2054 I ActivityManager: Killing 7613:com.lge.bnr/1000 (adj 15): empty #17
,08-10 07:41:14.598  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:14.598  1037  1539 D LGWifiP2pService: DefaultState{ when=-4ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 07:41:14.617  1037  1649 W libprocessgroup: failed to open /acct/uid_1000/pid_7613/cgroup.procs: No such file or directory
,08-10 07:41:14.637  1037  1541 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-10 07:41:14.641  1037  1541 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-10 07:41:14.956  1037  2011 I ActivityManager: Killing 7104:com.lge.sync/1000 (adj 15): empty #17
,08-10 07:41:14.983  1037  1546 D WifiService: Client connection lost with reason: 4
,08-10 07:41:14.993  1037  1974 W libprocessgroup: failed to open /acct/uid_1000/pid_7104/cgroup.procs: No such file or directory
,08-10 07:41:15.049  7205  7205 V BluetoothOppNotification: new notify threadi!
,08-10 07:41:15.049  7205  7205 V BluetoothOppNotification: send delay message
,08-10 07:41:15.064  7205  7819 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 07:41:15.067  7205  7819 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ad0dce on behalf of 
08-10 07:41:15.068  7205  7819 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 07:41:15.069  7205  7819 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-10 07:41:15.073  7205  7819 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@637d4ef on behalf of 
08-10 07:41:15.074  7205  7819 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 07:41:15.076  7205  7819 V BluetoothOppNotification: outbound notification was removed.
08-10 07:41:15.076  7205  7819 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 07:41:15.077  7205  7819 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@880abfc on behalf of 
08-10 07:41:15.078  7205  7819 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-10 07:41:15.083  7205  7819 V BluetoothOppNotification: inbound notification was removed.
,08-10 07:41:15.084  7205  7819 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 07:41:15.085  7205  7819 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14183285 on behalf of 
,08-10 07:41:15.586  1037  1578 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 07:41:15.586  1037  1578 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@8804872 mBinding = false
,08-10 07:41:15.618  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 07:41:15.618  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 07:41:15.618  1037  1037 D Ulp_jni : JNI:system_update. Event-4
08-10 07:41:15.619  1037  1119 D BluetoothManagerService: Message: 2
08-10 07:41:15.620  1037  1119 D BluetoothManagerService: Sending off request.
08-10 07:41:15.621  7205  7787 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-10 07:41:15.621  7205  7680 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-10 07:41:15.622  7205  7680 D BluetoothAdapterProperties: Setting state to 13
08-10 07:41:15.622  7205  7680 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 07:41:15.622  7205  7680 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 07:41:15.623  7205  7680 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-10 07:41:15.624  7205  7684 D BluetoothAdapterProperties: Scan Mode:20
08-10 07:41:15.626  7205  7680 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-10 07:41:15.631  7205  7680 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-10 07:41:15.633  7205  7789 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-10 07:41:15.633  7205  7789 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:15.633  7205  7789 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-10 07:41:15.633  7205  7789 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-10 07:41:15.633  7205  7789 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-10 07:41:15.633  7205  7789 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-10 07:41:15.633  7205  7789 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-10 07:41:15.633  7205  7789 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-10 07:41:15.634  7205  7795 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:15.634  7205  7807 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:15.635  7205  7806 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:15.635  7205  7809 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 07:41:15.636  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-10 07:41:15.636  7205  7750 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-10 07:41:15.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-10 07:41:15.637  7205  7750 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 07:41:15.648  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 07:41:15.653  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:15.653  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:15.653  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:15.653  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:15.653  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:15.653  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:15.653  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:15.653  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:15.654  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:15.654  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:15.657  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:15.657  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:15.657  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:15.657  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:15.657  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:15.657  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 07:41:15.657  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:15.657  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:15.657  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:15.658  6960  6960 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 07:41:15.659  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:15.663  1037  1119 D BluetoothManagerService: Message: 60
08-10 07:41:15.663  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-10 07:41:15.663  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-10 07:41:15.669  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:15.669  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 07:41:15.673  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:15.675  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:15.678  7205  7205 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:15.678  7205  7205 D BluetoothMapService: STATE_TURNING_OFF
08-10 07:41:15.678  7205  7205 V BluetoothMapService: Handler(): got msg=4
08-10 07:41:15.678  7205  7205 D BluetoothMapService: MAP Service closeService in
08-10 07:41:15.678  7205  7205 D BluetoothMapMasInstance: MAP Service shutdown
08-10 07:41:15.678  7205  7205 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 07:41:15.679  7205  7205 V BluetoothMapService: MAP Service closeService out
,08-10 07:41:15.682  7205  7205 V BtOppService: Receiver DISABLED_ACTION 
08-10 07:41:15.682  7205  7205 I BtOppRfcommListener: stopping Accept Thread
08-10 07:41:15.682  7205  7205 V BtOppRfcommListener: close mBtServerSocket
08-10 07:41:15.683  7205  7806 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 07:41:15.684  7205  7205 V BtOppRfcommListener: waiting for thread to terminate
08-10 07:41:15.684  7205  7205 V BtOppRfcommListener: done waiting for thread to terminate
08-10 07:41:15.686  7062  7062 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-10 07:41:15.711  7062  7062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-10 07:41:15.717  7205  7205 V BtOppService: onDestroy
08-10 07:41:15.719  7205  7205 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-10 07:41:15.723  7205  7205 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 07:41:15.724  7205  7205 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:15.724  7205  7205 V BluetoothPbapReceiver: ***********state = 13
08-10 07:41:15.726  7205  7205 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-10 07:41:15.730  7205  7205 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:15.730  7205  7205 V BluetoothPbapService: state: 13
08-10 07:41:15.730  7205  7205 V BluetoothPbapService: Pbap Service closeService in
08-10 07:41:15.733  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 07:41:15.734  7205  7205 V BluetoothPbapService: successfully stopped pbap service
08-10 07:41:15.734  7205  7205 V BluetoothPbapService: Pbap Service closeService out
08-10 07:41:15.735  7205  7205 V BluetoothPbapService: Pbap Service onDestroy
08-10 07:41:15.735  7205  7205 V BluetoothPbapService: Pbap Service closeService in
08-10 07:41:15.735  7205  7205 V BluetoothPbapService: Pbap Service closeService out
08-10 07:41:15.735  7205  7205 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-10 07:41:15.764  7062  7062 D DockEventReceiver: finishStartingService: stopping service
,08-10 07:41:15.767  7062  7062 D BluetoothPbap: Proxy object disconnected
08-10 07:41:15.767  7062  7062 D PbapServerProfile: Bluetooth service disconnected
08-10 07:41:15.773  7062  7062 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-10 07:41:15.780  7062  7062 D BluetoothPermissionRequest: onReceive
08-10 07:41:15.781  7062  7062 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-10 07:41:15.788  7062  7062 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 07:41:15.792  7205  7205 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-10 07:41:15.793  7205  7205 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-10 07:41:15.794  7205  7205 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-10 07:41:15.798  7205  7205 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:15.798  7205  7205 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 07:41:15.799  7205  7205 V BluetoothFtpService: Ftp Service onStartCommand
08-10 07:41:15.799  7205  7205 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:15.800  7205  7205 V BluetoothFtpService: Ftp Service closeService
08-10 07:41:15.800  7205  7205 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-10 07:41:15.801  7205  7205 V BluetoothFtpService: successfully stopped ftp service
08-10 07:41:15.802  7205  7205 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 07:41:15.802  7205  7205 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 07:41:15.802  7205  7205 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 07:41:15.802  7205  7205 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:15.802  7205  7205 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-10 07:41:15.802  7205  7205 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-10 07:41:15.803  7205  7205 V BluetoothFtpService: Ftp Service onDestroy
08-10 07:41:15.803  7205  7205 V BluetoothFtpService: Ftp Service closeService
08-10 07:41:15.808  7205  7205 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:15.808  7205  7205 V BluetoothSapService: state: 13
08-10 07:41:15.808  7205  7205 V BluetoothSapService: Stopping SAP server process
,08-10 07:41:15.810  7205  7205 V BluetoothSapService: Sap Service closeSapService in
,08-10 07:41:15.810  7205  7205 V BluetoothSapService: Close listen Socket : 
08-10 07:41:15.810  7205  7205 V BluetoothSapService: Close rfcomm Socket : 
08-10 07:41:15.810  7205  7205 V BluetoothSapService: Close sapd  Socket : 
08-10 07:41:15.811  7205  7205 V BluetoothSapService: Sap Service closeSapService out
08-10 07:41:15.811  7205  7205 V BluetoothSapService: Sap Service onDestroy
,08-10 07:41:15.812  7205  7205 V BluetoothSapService: Sap Service closeSapService in
08-10 07:41:15.812  7205  7205 V BluetoothSapService: Close listen Socket : 
08-10 07:41:15.812  7205  7205 V BluetoothSapService: Close rfcomm Socket : 
08-10 07:41:15.812  7205  7205 V BluetoothSapService: Close sapd  Socket : 
08-10 07:41:15.813  7205  7205 V BluetoothSapService: Sap Service closeSapService out
08-10 07:41:16.624  7205  7684 D bt_hci_bdroid: cleanup
,08-10 07:41:16.635  7205  7752 I bt_lpm  : LPM is already off!!!
08-10 07:41:16.636  7205  7773 I bt_userial_mct: exiting userial_read_thread
08-10 07:41:16.636  7205  7773 D bt_userial_mct: Leaving userial_evt_read_thread()
08-10 07:41:16.637  7205  7750 W bt-btif : ag scb idx 1 not allocated
08-10 07:41:16.637  7205  7750 E bt-btif : BTA AG is already disabled, ignoring ...
08-10 07:41:16.637  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:16.637  7205  7750 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-10 07:41:16.638  7205  7750 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-10 07:41:16.639  7205  7750 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-10 07:41:16.641  7205  7684 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-10 07:41:16.644  7205  7752 I bt_vendor: hw_epilog_process
,08-10 07:41:16.647  7205  7684 D bt_hci_bdroid: cleanup Finalizing cleanup
08-10 07:41:16.647  7205  7684 D bt_userial_mct: userial_close
08-10 07:41:16.647  7205  7684 E bt_userial_mct: pthread_join() FAILED result:3
08-10 07:41:16.647  7205  7684 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-10 07:41:16.653  7205  7684 D bt_hci_bdroid: set_power 0
08-10 07:41:16.653  7205  7684 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-10 07:41:16.653  7205  7684 I bt_vendor: bluetooth satus is on
08-10 07:41:16.653  7205  7684 I bt_vendor: bt-vendor : resetting BT status
08-10 07:41:16.653  7205  7684 I bt_vendor: Starting hciattach daemon
08-10 07:41:16.653  7205  7684 I bt_vendor: try to set false
08-10 07:41:16.656  7205  7684 I bt_vendor: Starting hciattach daemon
08-10 07:41:16.656  7205  7684 I bt_vendor: try to set false
,08-10 07:41:16.660  7205  7684 I bt_vendor: cleanup
08-10 07:41:16.661  7205  7750 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-10 07:41:16.661  7205  7684 I GKI_LINUX: GKI_exit_task 0 done
08-10 07:41:16.661  7205  7684 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-10 07:41:16.663  7205  7680 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-10 07:41:16.668  7205  7205 D HeadsetService: Received stop request...Stopping profile...
08-10 07:41:16.670  7205  7205 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 07:41:16.670  7205  7205 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 07:41:16.670  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
,08-10 07:41:16.673  7205  7720 D HeadsetStateMachine: Exit Disconnected: -1
08-10 07:41:16.677  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-10 07:41:16.677  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-10 07:41:16.677  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-10 07:41:16.677  1037  1037 D BluetoothHeadset: Proxy object disconnected
08-10 07:41:16.677  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-10 07:41:16.680  7205  7205 D A2dpService: Received stop request...Stopping profile...
08-10 07:41:16.681  7205  7734 D A2dpStateMachine: Exit Disconnected: -1
08-10 07:41:16.685  7205  7205 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-10 07:41:16.688  7205  7680 D BluetoothAdapterState: Stopping profile services that were post enabled
08-10 07:41:16.690  7205  7205 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-10 07:41:16.690  7205  7205 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 07:41:16.690  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:16.693  7205  7205 D HidService: Received stop request...Stopping profile...
08-10 07:41:16.693  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:16.694  1037  1037 D BluetoothA2dp: Proxy object disconnected
08-10 07:41:16.694  1037  1037 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-10 07:41:16.696  7205  7205 D HeadsetStateMachine: Unbinding service...
,08-10 07:41:16.700  7205  7205 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 07:41:16.700  7205  7205 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 07:41:16.700  7205  7205 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-10 07:41:16.700  7205  7205 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 07:41:16.700  7205  7205 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 07:41:16.700  7205  7205 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 07:41:16.700  7205  7205 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-10 07:41:16.702  7205  7205 D HealthService: Received stop request...Stopping profile...
08-10 07:41:16.702  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:16.704  7205  7205 D PanService: Received stop request...Stopping profile...
08-10 07:41:16.705  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:16.707  7205  7205 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 07:41:16.708  7205  7205 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 07:41:16.708  7205  7205 D BtGatt.GattService: stop()
08-10 07:41:16.708  7205  7205 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 07:41:16.712  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:16.714  7205  7205 D BluetoothMapService: Received stop request...Stopping profile...
08-10 07:41:16.714  7205  7205 D BluetoothMapService: stop()
08-10 07:41:16.714  7205  7205 D BluetoothMapEmailAppObserver: deinitObservers()
08-10 07:41:16.714  7205  7205 D BluetoothMapEmailAppObserver: removeReceiver()
08-10 07:41:16.715  7205  7205 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2fb0f610
08-10 07:41:16.716  7205  7205 I BluetoothA2dpServiceJni: cleanupNative
08-10 07:41:16.716  7205  7735 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-10 07:41:16.718  7205  7205 I GKI_LINUX: GKI_exit_task 2 done
08-10 07:41:16.718  7205  7205 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-10 07:41:16.718  7205  7205 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 07:41:16.718  7205  7205 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 07:41:16.719  7205  7205 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 07:41:16.719  7205  7205 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 07:41:16.719  7205  7205 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 07:41:16.719  7205  7205 V BluetoothMapService: Handler(): got msg=4
08-10 07:41:16.719  7205  7205 D BluetoothMapService: MAP Service closeService in
08-10 07:41:16.721  7205  7205 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 07:41:16.721  7205  7205 V BluetoothMapService: MAP Service closeService out
,08-10 07:41:16.724  7205  7680 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-10 07:41:16.724  7205  7680 D BluetoothAdapterProperties: Setting state to 10
08-10 07:41:16.725  7205  7680 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-10 07:41:16.727  1037  1119 D BluetoothManagerService: Message: 60
08-10 07:41:16.727  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-10 07:41:16.727  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-10 07:41:16.729  7205  7205 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 07:41:16.729  7205  7205 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 07:41:16.731  7205  7680 I BluetoothAdapterState: Entering OffState
08-10 07:41:16.732  7205  7205 D BluetoothMapService: cleanup()
08-10 07:41:16.732  7205  7205 D BluetoothMapService: MAP Service closeService in
08-10 07:41:16.732  7205  7205 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-10 07:41:16.732  7205  7205 V BluetoothMapService: MAP Service closeService out
08-10 07:41:16.733  7062  7781 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 07:41:16.736  7062  7781 D BluetoothMap: onBluetoothStateChange: up=false
08-10 07:41:16.737  7062  7781 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 07:41:16.737  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 07:41:16.738  7062  7781 D BluetoothPan: onBluetoothStateChange on: false
08-10 07:41:16.739  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 07:41:16.739  7062  7781 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 07:41:16.740  1853  2414 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 07:41:16.740  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 07:41:16.740  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 07:41:16.741  7062  7781 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 07:41:16.743  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-10 07:41:16.743  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-10 07:41:16.745  1037  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-10 07:41:16.745  1037  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-10 07:41:16.745  1037  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@8804872 mBinding = false
,08-10 07:41:16.747  1037  1119 D BluetoothManagerService: Sending unbind request.
08-10 07:41:16.752  7205  7684 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-10 07:41:16.754  7205  7205 I GKI_LINUX: GKI_exit_task 1 done
08-10 07:41:16.754  7205  7205 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-10 07:41:16.754  7205  7205 I BluetoothServiceJni: cleanupNative: return from cleanup
08-10 07:41:16.754  7205  7205 I art     : --- WEIRD: removing null entry 248
08-10 07:41:16.754  7205  7205 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-10 07:41:16.754  7205  7205 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-10 07:41:16.755  7205  7205 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-10 07:41:16.756  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-10 07:41:16.760  7205  7205 I art     : System.exit called, status: 0
08-10 07:41:16.760  7205  7205 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-10 07:41:16.779   315  1387 V AudioFlinger: 7205 died, releasing its sessions
08-10 07:41:16.779   315  1387 V AudioFlinger:  pid 1853 @ 0
08-10 07:41:16.779   315  1387 V AudioFlinger:  pid 3350 @ 1
08-10 07:41:16.779   315  1387 V AudioFlinger:  pid 3350 @ 2
,08-10 07:41:16.783  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-10 07:41:16.783  1944  2144 D LGBluetoothAPIService: Message: 101
08-10 07:41:16.783  1944  2144 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-10 07:41:16.783  1944  2144 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-10 07:41:16.784  1944  2144 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-10 07:41:16.786  7062  7062 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-10 07:41:16.792  1037  1997 I ActivityManager: Process com.android.bluetooth (pid 7205) has died
08-10 07:41:16.792  1037  1997 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-10 07:41:16.793  1037  1997 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-10 07:41:16.800  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:16.801  1944  2144 D LGBluetoothAPIService: Message: 2
08-10 07:41:16.801  1944  2144 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-10 07:41:16.802  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:16.802  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:16.803  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 07:41:16.810  7062  7062 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-10 07:41:16.810  7062  7062 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-10 07:41:16.821  7062  7062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 07:41:16.827  1605  1605 D BluetoothAdapter: 745553867: getState() :  mService = null. Returning STATE_OFF
,08-10 07:41:16.828  1605  1605 D BluetoothAdapter: 745553867: getState() :  mService = null. Returning STATE_OFF
08-10 07:41:16.881  1037  2054 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7864 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-10 07:41:16.884  7062  7062 D DockEventReceiver: finishStartingService: stopping service
,08-10 07:41:16.972  7864  7864 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-10 07:41:16.977  7864  7864 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:16.978  7864  7864 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-10 07:41:16.980  7864  7864 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-10 07:41:17.018  7864  7864 D BluetoothAdapterApp: Loading JNI Library
,08-10 07:41:17.052  7864  7864 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@7de1ff8 Instance Count = 1
,08-10 07:41:17.059  7864  7864 D BluetoothAdapterApp: onCreate
08-10 07:41:17.083  7864  7864 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-10 07:41:17.083  7864  7864 D ProfileConfigQcom: Adding HeadsetService
08-10 07:41:17.083  7864  7864 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-10 07:41:17.083  7864  7864 D ProfileConfigQcom: Adding A2dpService
08-10 07:41:17.083  7864  7864 D ProfileConfigQcom: [BTUI] HidService is supported
,08-10 07:41:17.084  7864  7864 D ProfileConfigQcom: Adding HidService
,08-10 07:41:17.084  7864  7864 D ProfileConfigQcom: [BTUI] HealthService is supported
08-10 07:41:17.084  7864  7864 D ProfileConfigQcom: Adding HealthService
08-10 07:41:17.084  7864  7864 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-10 07:41:17.086  7864  7864 D ProfileConfigQcom: [BTUI] PanService is supported
08-10 07:41:17.087  7864  7864 D ProfileConfigQcom: Adding PanService
08-10 07:41:17.087  7864  7864 D ProfileConfigQcom: [BTUI] GattService is supported
08-10 07:41:17.087  7864  7864 D ProfileConfigQcom: Adding GattService
08-10 07:41:17.087  7864  7864 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-10 07:41:17.087  7864  7864 D ProfileConfigQcom: Adding BluetoothMapService
08-10 07:41:17.089  7864  7864 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-10 07:41:17.090  7864  7864 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 07:41:17.091  7864  7864 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:17.092  7864  7864 V BluetoothPbapReceiver: ***********state = 10
08-10 07:41:17.094  7864  7864 V LGMDMManagerInternal: Create singleton instance
08-10 07:41:17.163  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 07:41:17.167  7062  7062 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-10 07:41:17.173  7864  7864 D LGBluetoothAPIServer: [BTUI] onCreate()
08-10 07:41:17.173  7864  7864 D LGBluetoothAPIServer: [BTUI] onBind()
08-10 07:41:17.185  1944  1944 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-10 07:41:17.185  1944  2144 D LGBluetoothAPIService: Message: 100
08-10 07:41:17.185  1944  2144 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-10 07:41:17.200  7062  7062 D BluetoothPermissionRequest: onReceive
,08-10 07:41:17.203  7062  7062 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 07:41:17.203  7062  7062 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-10 07:41:17.207  7062  7062 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 07:41:17.212  7864  7864 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-10 07:41:17.219  7864  7864 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-10 07:41:17.222  7864  7864 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-10 07:41:17.223  7864  7864 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-10 07:41:17.223  7864  7864 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 07:41:17.225  7864  7864 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:17.225  7864  7864 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-10 07:41:17.230  7155  7155 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-10 07:41:18.711  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 07:41:18.711  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 07:41:18.825  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-10 07:41:18.874  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-10 07:41:18.889  1037  1037 D administrator: Handling package changes for user 0
,08-10 07:41:18.918  1037  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 07:41:18.970  1037  1100 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7907 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-10 07:41:18.982  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-10 07:41:18.983  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-10 07:41:19.007  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 07:41:19.036  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-10 07:41:19.036  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-10 07:41:19.037  7907  7907 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-10 07:41:19.091  1037  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 07:41:19.096  7907  7907 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:19.096  7907  7907 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 07:41:19.096  1037  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-10 07:41:19.101  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-10 07:41:19.102  2460  2460 V GmsNetworkLocationProvi: DISABLE
08-10 07:41:19.133  1037  1098 D LocationProviderProxy: applying state to connected service
,08-10 07:41:19.141  2460  2460 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-10 07:41:19.185  7907  7940 I Babel   : MmsConfig: mnc/mcc: 0/0
08-10 07:41:19.185  7907  7940 I Babel   : MmsConfig.loadMmsSettings
,08-10 07:41:19.190  7907  7940 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-10 07:41:19.190  7907  7940 I Babel   : MmsConfig.loadFromDatabase
,08-10 07:41:19.201  7907  7940 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-10 07:41:19.201  7907  7940 I Babel   : MmsConfig.loadFromResources
08-10 07:41:19.203  7907  7940 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-10 07:41:19.204  7907  7940 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-10 07:41:19.218  7907  7907 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:19.229  7907  7939 W AudioCapabilities: Unsupported mime audio/evrc
,08-10 07:41:19.231  7907  7939 W AudioCapabilities: Unsupported mime audio/qcelp
,08-10 07:41:19.234  7907  7939 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-10 07:41:19.244  7907  7939 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-10 07:41:19.245  7907  7939 W AudioCapabilities: Unsupported mime audio/qcelp
08-10 07:41:19.248  7907  7939 W AudioCapabilities: Unsupported mime audio/evrc
08-10 07:41:19.249  1818  7943 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-10 07:41:19.249  1818  7943 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-10 07:41:19.261  7269  7269 I AppUp4:CustModeStarterReceiver: onReceive
,08-10 07:41:19.264  1818  4995 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-10 07:41:19.266  7269  7269 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7297cc2
08-10 07:41:19.266  7269  7269 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 07:41:19.266  7269  7269 D AppUp4:CustFacade: isPhone : true
08-10 07:41:19.266  7269  7269 D AppUp4:CustModeStarterReceiver: begin check event
08-10 07:41:19.267  7269  7269 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-10 07:41:19.270  7907  7939 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-10 07:41:19.275  7907  7939 W VideoCapabilities: Unsupported mime video/divx
,08-10 07:41:19.283  7907  7939 W VideoCapabilities: Unsupported mime video/divx311
,08-10 07:41:19.286  7907  7939 W VideoCapabilities: Unsupported mime video/divx4
,08-10 07:41:19.301  7907  7939 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-10 07:41:19.311  1037  1578 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7946 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-10 07:41:19.315  1037  1897 I ActivityManager: Killing 6852:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-10 07:41:19.323  7134  7134 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-10 07:41:19.323  7134  7134 W System.err: android.os.DeadObjectException
08-10 07:41:19.323  7134  7134 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-10 07:41:19.324  7134  7134 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 07:41:19.324  7134  7134 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-10 07:41:19.324  7134  7134 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-10 07:41:19.324  7134  7134 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 07:41:19.324  7134  7134 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 07:41:19.324  7134  7134 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 07:41:19.324  7134  7134 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 07:41:19.324  7134  7134 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:19.324  7134  7134 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:19.324  7134  7134 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:19.324  7134  7134 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:19.324  7134  7134 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:19.324  7134  7134 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 07:41:19.325  7134  7134 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-10 07:41:19.325  7134  7134 W System.err: android.os.DeadObjectException
08-10 07:41:19.325  7134  7134 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 07:41:19.325  7134  7134 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 07:41:19.325  7134  7134 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-10 07:41:19.325  7134  7134 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-10 07:41:19.325  7134  7134 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 07:41:19.325  7134  7134 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 07:41:19.325  7134  7134 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 07:41:19.325  7134  7134 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 07:41:19.325  7134  7134 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:19.325  7134  7134 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:19.325  7134  7134 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:19.325  7134  7134 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:19.325  7134  7134 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:19.325  7134  7134 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 07:41:19.325  7134  7134 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-10 07:41:19.325  7134  7134 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-10 07:41:19.337  7907  7939 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-10 07:41:19.340  7907  7939 W AudioCapabilities: Unsupported mime audio/eac3
08-10 07:41:19.340  7907  7939 W AudioCapabilities: Unsupported mime audio/ac3
08-10 07:41:19.341  7907  7939 W AudioCapabilities: Unsupported mime audio/g726
,08-10 07:41:19.341  7907  7939 W AudioCapabilities: Unsupported mime audio/wma-voice
08-10 07:41:19.342  7907  7939 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-10 07:41:19.343  7907  7939 W AudioCapabilities: Unsupported mime audio/adpcm
08-10 07:41:19.344  7907  7939 W VideoCapabilities: Unsupported mime video/theora
08-10 07:41:19.345  7907  7939 W VideoCapabilities: Unsupported mime video/mjpg
08-10 07:41:19.566   277   277 E lowmemorykiller: Error opening /proc/6852/oom_score_adj; errno=2
,08-10 07:41:19.571  1037  1925 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-10 07:41:19.571  1037  1925 W ActivityManager: android.os.DeadObjectException
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-10 07:41:19.571  1037  1925 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-10 07:41:19.576  7134  7134 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-10 07:41:19.577  7134  7134 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 07:41:19.591  1037  1954 W libprocessgroup: failed to open /acct/uid_1000/pid_6852/cgroup.procs: No such file or directory
,08-10 07:41:19.626  7946  7946 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:19.626  7946  7946 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:19.627  7946  7946 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-10 07:41:19.628  7946  7946 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-10 07:41:19.628  7946  7946 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-10 07:41:19.656  1037  1052 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 07:41:19.656  7134  7134 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-10 07:41:19.731  7967  7967 D UEI.SmartControl: Quickset Services start...
,08-10 07:41:19.734  7967  7967 I UEI.SmartControl: Manufacture = LGE
08-10 07:41:19.734  7967  7967 D UEI.SmartControl: Id = LGNevo
08-10 07:41:19.736  7967  7967 D UEI.SmartControl: File observer start...
08-10 07:41:19.737  7967  7967 E UEI.SmartControl: IR Port is disabled: false
08-10 07:41:19.739  7967  7967 D UEI.SmartControl: Starting file observer...
08-10 07:41:19.740  7967  7967 D UEI.SmartControl: Extracting JNI libs...
08-10 07:41:19.741  7967  7967 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-10 07:41:19.748  7946  7946 I SystemConfig: BUILD Country: EU
08-10 07:41:19.748  7946  7946 I SystemConfig: BUILD Operator: OPEN
08-10 07:41:19.815  1037  1879 I ActivityManager: Killing 7134:com.lge.qremote/u0a112 (adj 15): empty #17
,08-10 07:41:19.832  7967  7967 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-10 07:41:19.832  7967  7967 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-10 07:41:19.832  7967  7967 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-10 07:41:19.859  7967  7967 I UEI.SmartControl: --- Selecting new region: 6
,08-10 07:41:19.860  7967  7967 I UEI.SmartControl: Model = LG-D855
,08-10 07:41:19.861  7967  7967 D UEI.SmartControl: QS Service created
08-10 07:41:19.899  1037  2034 W libprocessgroup: failed to open /acct/uid_10112/pid_7134/cgroup.procs: No such file or directory
,08-10 07:41:19.918  7946  7991 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-10 07:41:19.920  7946  7991 I SystemConfig: existFile = false
08-10 07:41:19.920  7946  7991 I SystemConfig: canReadFile = false
08-10 07:41:19.921  7946  7991 I SystemConfig: systemFeature RCS result false
,08-10 07:41:19.922  7946  7991 D SystemConfig: refreshRcsSupport() :false
08-10 07:41:19.933  7967  7967 I UEI.SmartControl: Service initServices...
,08-10 07:41:19.951  7967  7967 D UEI.SmartControl: QS start get config
,08-10 07:41:19.973  1037  1879 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7993 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-10 07:41:20.047  7967  7967 D UEI.SmartControl: Loading JNI Libs...
,08-10 07:41:20.050  7993  7993 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:20.050  7993  7993 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 07:41:20.051  7993  7993 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 07:41:20.051  7993  7993 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 07:41:20.120  7993  7993 I AppConfig: Total System Memory = 2995761152
,08-10 07:41:20.126  7993  7993 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-10 07:41:20.193  1037  1925 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8013 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 07:41:20.194  1037  1925 I ActivityManager: Killing 7297:com.lge.email/u0a23 (adj 15): empty #17
,08-10 07:41:20.304  7967  7967 I UEI.SmartControl: Supports setup maps: true
,08-10 07:41:20.310  7967  7967 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 07:41:20.310  7967  7967 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 07:41:20.310  7967  7967 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-10 07:41:20.310  7967  7967 I UEI.SmartControl: ### init IR Blaster...
08-10 07:41:20.320  7967  7967 D serial_port: Configuring serial port
08-10 07:41:20.331  7967  7967 E UEI.SmartControl: UEIBLaster setting for 616
08-10 07:41:20.332  7967  7967 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 07:41:20.333  7967  7967 I UEI.SmartControl: configuring settings for MAXQ616
08-10 07:41:20.334  7967  7967 I UEI.SmartControl: Get version...
,08-10 07:41:20.351  7967  8030 D UEI.SmartControl: serial port data available: 21
,08-10 07:41:20.355  1037  1897 W libprocessgroup: failed to open /acct/uid_10023/pid_7297/cgroup.procs: No such file or directory
,08-10 07:41:20.390  7967  7967 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-10 07:41:20.390  7967  7967 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-10 07:41:20.391  7967  7967 I UEI.SmartControl: QS saving settings...
08-10 07:41:20.394  7967  7967 D UEI.SmartControl: IR Blaster version: 25672567
08-10 07:41:20.413  7967  8030 D UEI.SmartControl: serial port data available: 4
,08-10 07:41:20.446  7967  8033 I UEI.SmartControl: Device manager: loading config....
,08-10 07:41:20.446  7967  7967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 07:41:20.447  7967  8033 D UEI.SmartControl: ----------- loading internal config...
,08-10 07:41:20.454  7967  7967 E UEI.SmartControl: Services init done
08-10 07:41:20.455  7967  7967 D UEI.SmartControl: QS Service init finished
08-10 07:41:20.456  7967  7967 D UEI.SmartControl: QS Service version name: 2.1.91
,08-10 07:41:20.456  7967  7967 D UEI.SmartControl: QS Service version code: 201091
08-10 07:41:20.457  7967  7967 D UEI.SmartControl: Service requested: Control
08-10 07:41:20.461  7967  8033 E UEI.SmartControl: Loading SETTINGS...
08-10 07:41:20.463  7967  7967 D UEI.SmartControl: Request IControl service: devices are loaded...
08-10 07:41:20.467  7967  7967 D UEI.SmartControl: Service.onUnbind: IControl
,08-10 07:41:20.470  7967  7967 D UEI.SmartControl: Service.onDestroy
08-10 07:41:20.470  7967  7967 D UEI.SmartControl: Lock is in USE false
08-10 07:41:20.473  7967  7967 D UEI.SmartControl: unbind internal service
08-10 07:41:20.474  7967  7967 D serial_port: close(fd = 25)
08-10 07:41:20.477  7967  7967 I UEI.SmartControl: Serial port is closed.
08-10 07:41:20.477  7967  7967 I UEI.SmartControl: Serial port is closed.
08-10 07:41:20.477  7967  7967 D UEI.SmartControl: Blaster closed
08-10 07:41:20.477  7967  7967 D UEI.SmartControl: Shut down QS...
08-10 07:41:20.477  7967  7967 D UEI.SmartControl: Stopping QS lib
08-10 07:41:20.478  7967  7967 D UEI.SmartControl: QS lib stop result = true
08-10 07:41:20.478  7967  7967 D UEI.SmartControl: Stopped QS lib
08-10 07:41:20.478  7967  8033 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-10 07:41:20.481  7967  7967 D UEI.SmartControl: Stopped file observer...
08-10 07:41:20.481  7967  7967 D UEI.SmartControl: QS shutdown complete
08-10 07:41:20.482  7967  7967 D UEI.SmartControl: QS Service created
08-10 07:41:20.483  7967  8032 I UEI.SmartControl: Notify AllClients services are ready: 11
08-10 07:41:20.483  7967  8032 D UEI.SmartControl: -----service ready thread exits
,08-10 07:41:20.500  7967  7967 I UEI.SmartControl: Service initServices...
08-10 07:41:20.500  7967  7967 D UEI.SmartControl: QS start get config
,08-10 07:41:20.586  8013  8013 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-10 07:41:20.676  8013  8013 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:20.676  8013  8013 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:20.722  8013  8013 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-10 07:41:20.742  8013  8013 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 07:41:20.743  8013  8013 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-10 07:41:20.756  8013  8013 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-10 07:41:20.757  8013  8013 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-10 07:41:20.771  1037  2011 I ActivityManager: Killing 7176:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-10 07:41:20.791  7967  7967 I UEI.SmartControl: Supports setup maps: true
08-10 07:41:20.794  7967  7967 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 07:41:20.794  7967  7967 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-10 07:41:20.794  7967  7967 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 07:41:20.794  7967  7967 I UEI.SmartControl: ### init IR Blaster...
08-10 07:41:20.798  7967  7967 D serial_port: Configuring serial port
,08-10 07:41:20.798  7967  7967 E UEI.SmartControl: UEIBLaster setting for 616
08-10 07:41:20.798  7967  7967 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 07:41:20.798  7967  7967 I UEI.SmartControl: configuring settings for MAXQ616
08-10 07:41:20.798  7967  7967 I UEI.SmartControl: Get version...
08-10 07:41:20.815  7967  8058 D UEI.SmartControl: serial port data available: 21
,08-10 07:41:20.825  1037  1052 W libprocessgroup: failed to open /acct/uid_10026/pid_7176/cgroup.procs: No such file or directory
08-10 07:41:20.835  4910  8060 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-10 07:41:20.841  7967  7967 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-10 07:41:20.841  7967  7967 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 07:41:20.841  7967  7967 I UEI.SmartControl: QS saving settings...
08-10 07:41:20.843  7967  7967 D UEI.SmartControl: IR Blaster version: 25672567
08-10 07:41:20.860  7967  8058 D UEI.SmartControl: serial port data available: 4
,08-10 07:41:20.890  7967  7967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 07:41:20.890  7967  8063 I UEI.SmartControl: Device manager: loading config....
08-10 07:41:20.890  7967  8063 D UEI.SmartControl: ----------- loading internal config...
,08-10 07:41:20.896  7967  8063 E UEI.SmartControl: Loading SETTINGS...
08-10 07:41:20.901  7967  8063 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-10 07:41:20.902  1037  1997 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8065 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-10 07:41:20.909  7967  7967 E UEI.SmartControl: Services init done
08-10 07:41:20.909  7967  7967 D UEI.SmartControl: QS Service init finished
,08-10 07:41:20.913  7967  8062 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 07:41:20.913  7967  8062 D UEI.SmartControl: -----service ready thread exits
08-10 07:41:20.918  7967  7967 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 07:41:20.919  7967  7967 D UEI.SmartControl: QS Service version code: 201091
08-10 07:41:20.919  7967  7967 D UEI.SmartControl: Service requested: Control
08-10 07:41:20.921  1037  1053 I ActivityManager: Killing 6461:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-10 07:41:20.921  2849  2870 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-10 07:41:20.923  2849  2870 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@4a06f46 on behalf of 8013
08-10 07:41:20.974  7967  7967 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2d96a30e that was originally bound here
08-10 07:41:20.974  7967  7967 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2d96a30e that was originally bound here
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:20.974  7967  7967 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-10 07:41:20.977  1037  1974 W libprocessgroup: failed to open /acct/uid_1000/pid_6461/cgroup.procs: No such file or directory
08-10 07:41:20.991  7967  7967 D UEI.SmartControl: Internal service binding...
,08-10 07:41:21.029  8065  8065 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-10 07:41:21.146  1037  1052 I art     : Explicit concurrent mark sweep GC freed 44770(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.243ms total 147.525ms
,08-10 07:41:21.153  8013  8013 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-10 07:41:21.188  8065  8065 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-10 07:41:21.188  8065  8065 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-10 07:41:21.188  8065  8065 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-10 07:41:21.188  8065  8065 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-10 07:41:21.188  8065  8065 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-10 07:41:21.188  8065  8065 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-10 07:41:21.190  8013  8013 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-10 07:41:21.205  1037  1052 I ActivityManager: Killing 7346:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-10 07:41:21.225  1037  2034 W libprocessgroup: failed to open /acct/uid_10046/pid_7346/cgroup.procs: No such file or directory
,08-10 07:41:21.454  1037  2011 V SIM_STK : Menu title from STK is T-Mobile
,08-10 07:41:21.470  7967  8036 D UEI.SmartControl: Internal timer expired: 2
,08-10 07:41:21.513  4910  8060 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 678 ms] updated apps [took 678 ms] 
,08-10 07:41:21.730  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 07:41:21.730  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f7eb9f4 added. We now have 6 listener(s)
,08-10 07:41:21.731  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 07:41:21.744  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:21.744  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c55b51d added. We now have 7 listener(s)
08-10 07:41:21.744  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:21.745  6960  7027 I System.out: IsBluetoothEnabled
08-10 07:41:21.746  1037  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:21.746  1037  1974 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-10 07:41:21.748  1037  1119 D BluetoothManagerService: Message: 2
08-10 07:41:21.752  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:21.755  1037  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:21.755  1037  1900 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-10 07:41:21.768  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-10 07:41:21.769  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 07:41:21.769  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-10 07:41:21.772  1037  1119 D BluetoothManagerService: Message: 1
08-10 07:41:21.772  1037  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-10 07:41:21.799  1037  1119 D BluetoothManagerService: Message: 20
08-10 07:41:21.799  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@303256b5:true
,08-10 07:41:21.803  7864  7864 D BluetoothAdapterState: make
08-10 07:41:21.808  7864  7864 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-10 07:41:21.808  7864  7864 I bluedroid-qcom: init
08-10 07:41:21.809  7864  8095 I BluetoothAdapterState: Entering OffState
08-10 07:41:21.810  7864  7864 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 07:41:21.810  7864  7864 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 07:41:21.810  7864  7864 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 07:41:21.810  7864  7864 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 07:41:21.810  7864  7864 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-10 07:41:21.812  7864  7864 I bluedroid-qcom: get_profile_interface socket
08-10 07:41:21.812  7864  7864 I bluedroid-qcom: get_profile_interface map_client
,08-10 07:41:21.817  7864  8099 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-10 07:41:21.820  7864  8099 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-10 07:41:21.810  8098  8098 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:21.810  8098  8098 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:21.832  8098  8098 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-10 07:41:21.832  8098  8098 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-10 07:41:21.832  8098  8098 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-10 07:41:21.836  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 07:41:21.837  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 07:41:21.838  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-10 07:41:21.838  1037  1119 D BluetoothManagerService: Message: 40
08-10 07:41:21.838  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-10 07:41:21.839  7864  7881 I bluedroid-qcom: config_hci_snoop_log
08-10 07:41:21.840  1037  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-10 07:41:21.840  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-10 07:41:21.844  8098  8098 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-10 07:41:21.850  7864  8095 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-10 07:41:21.852  7864  8099 D BluetoothAdapterProperties: Name is: G3
08-10 07:41:21.852  7864  8095 D BluetoothAdapterProperties: Setting state to 11
08-10 07:41:21.853  7864  8095 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-10 07:41:21.853  1037  1119 D BluetoothManagerService: Message: 60
08-10 07:41:21.853  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-10 07:41:21.853  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-10 07:41:21.855  7864  8095 I LGBluetoothServiceJni: classInitNative: succeeds
08-10 07:41:21.857  8098  8098 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-10 07:41:21.857  8098  8098 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-10 07:41:21.863  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-10 07:41:21.865  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 07:41:21.868  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:21.872  7062  7062 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-10 07:41:21.879  7864  7864 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 07:41:21.879  7864  7864 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:21.879  7864  7864 V BluetoothPbapReceiver: ***********state = 11
,08-10 07:41:21.896  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 07:41:21.908  7864  8095 D BluetoothBondStateMachine: make
08-10 07:41:21.912  7062  7062 D BluetoothPermissionRequest: onReceive
,08-10 07:41:21.914  7864  8095 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:21.914  7864  8095 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-10 07:41:21.914  7864  8095 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:21.914  7864  8095 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-10 07:41:21.915  7864  8113 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 07:41:21.916  7864  8095 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-10 07:41:21.917  7062  7062 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 07:41:21.923  7864  8095 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 07:41:21.924  7864  7864 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:21.927  7864  7864 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 07:41:21.927  7864  7864 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 07:41:21.927  7864  7864 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 07:41:21.927  7864  7864 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:21.927  7864  7864 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-10 07:41:21.934  7864  7864 D HeadsetService: Received start request. Starting profile...
08-10 07:41:21.934  7864  7864 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 07:41:21.934  7864  7864 D LGBluetoothHfpAdapter: Version 1.6
08-10 07:41:21.935  7864  8095 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:21.938  7864  7864 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-10 07:41:21.939  7864  7864 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 07:41:21.940  7864  7864 D HeadsetStateMachine: make
08-10 07:41:21.949  7864  8095 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:21.959  7864  8095 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 07:41:21.971  7864  8095 E BluetoothAdapterService: File transfer profiles supported!!
,08-10 07:41:21.979  7864  8095 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:21.982  7864  7864 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:21.982  7864  7864 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:21.988  7864  8095 E BluetoothAdapterService: File transfer profiles supported!!
08-10 07:41:21.989  7864  7864 D HeadsetStateMachine: max_hf_connections = 1
08-10 07:41:21.989  7864  7864 I bluedroid-qcom: get_profile_interface handsfree
08-10 07:41:21.991  7864  7864 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-10 07:41:21.992   315   315 V AudioPolicyService: registerClient() client 0xb558ade0, uid 1002
08-10 07:41:21.992   315   315 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-10 07:41:21.993   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 07:41:21.993   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 07:41:21.993  7864  7864 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 07:41:21.994   315  1387 V AudioFlinger: registerClient() client 0xb101b058, pid 7864
,08-10 07:41:21.994   315  1382 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:21.994   315  1382 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:21.995  1605  1624 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:21.995  1605  1624 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:21.995   315  1381 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:21.995   315  1381 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:21.995  1605  2096 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:21.995  1605  2096 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:21.995  7864  7864 V ToneGenerator: Create Track: 0xb4928080
08-10 07:41:21.995  7864  7864 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-10 07:41:21.995  7864  7864 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-10 07:41:21.996  3350  3371 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:21.996  1037  1997 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:21.996   315  2147 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 07:41:21.996  1037  1997 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:21.996   315  2147 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-10 07:41:21.996  3350  3371 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:21.996   315  2147 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 07:41:21.996   315  2147 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 07:41:21.996  1037  1997 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:21.996  1037  1997 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:21.996  7864  7864 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-10 07:41:21.996  7864  7881 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:21.996  7864  7881 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-10 07:41:21.996  3350  3371 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:21.996  3350  3371 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:21.996  7864  7881 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:21.996  7864  7881 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-10 07:41:21.996   315  2147 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 07:41:21.997  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-10 07:41:21.997  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-10 07:41:21.997  1853  1868 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-10 07:41:21.997  1853  1868 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-10 07:41:21.997   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-10 07:41:21.997   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-10 07:41:21.997   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-10 07:41:21.997   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-10 07:41:21.997  7864  7864 V AudioSystem: getLatency() output 2, latency 50
08-10 07:41:21.997  7864  7864 V AudioSystem: getFrameCount() output 2, frameCount 960
08-10 07:41:21.997  7864  7864 V AudioTrack: createTrack_l() output 2 afLatency 50
08-10 07:41:21.998   315  2147 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(,), enable = 0 
08-10 07:41:21.998   315  2147 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 07:41:21.998   315  2147 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-10 07:41:21.998   315  2147 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-10 07:41:21.998   315  2147 V AudioFlinger: createTrack() lSessionId: 23
08-10 07:41:21.999  7864  7864 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-10 07:41:21.999   315  2146 V AudioFlinger: acquiring 23 from 7864, for 7864
08-10 07:41:21.999   315  2146 V AudioFlinger:  added new entry for 23
08-10 07:41:21.999  7864  7864 V ToneGenerator: ToneGenerator INIT OK, time: 343257
08-10 07:41:21.999  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.000  7864  8115 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-10 07:41:22.000  7864  8115 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,08-10 07:41:22.001  7864  8115 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-10 07:41:22.001  7864  8115 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-10 07:41:22.002  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.003   315   315 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7864
08-10 07:41:22.003   315   315 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-10 07:41:22.003   315   315 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-10 07:41:22.003   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-10 07:41:22.003   315   315 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-10 07:41:22.003   315   315 V voice   : voice_set_parameters: exit with code(0)
08-10 07:41:22.004   315   315 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-10 07:41:22.004   315   315 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-10 07:41:22.004   315   315 V msm8974_platform: platform_set_parameters: exit with code(0)
08-10 07:41:22.004   315   315 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-10 07:41:22.004   315   315 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-10 07:41:22.004   315   315 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-10 07:41:22.004  7864  8115 V ToneGenerator: ToneGenerator destructor
08-10 07:41:22.004  7864  8115 V ToneGenerator: stopTone
08-10 07:41:22.004  7864  8115 V ToneGenerator: Delete Track: 0xb4928080
08-10 07:41:22.004  7864  8115 V AudioTrack: ~AudioTrack, releasing session id from 7864 on behalf of 7864
08-10 07:41:22.005   315  1386 V AudioFlinger: releasing 23 from 7864 for 7864
08-10 07:41:22.005   315  1386 V AudioFlinger:  decremented refcount to 0
08-10 07:41:22.005   315  1386 V AudioFlinger: purging stale effects
08-10 07:41:22.005   315  1386 V AudioPolicyService: AudioCommandThread() adding release output 2
08-10 07:41:22.005   315  1386 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-10 07:41:22.005  7864  7864 D A2dpService: Received start request. Starting profile...
08-10 07:41:22.006  7864  7864 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 07:41:22.006   315  1275 V AudioPolicyService: AudioCommandThread() waking up
08-10 07:41:22.007   315  1275 V AudioPolicyService: AudioCommandThread() processing release output 2
08-10 07:41:22.007   315  1275 V AudioPolicyManager: releaseOutput() 2
08-10 07:41:22.007   315  1275 V AudioPolicyService: AudioCommandThread() going to sleep
08-10 07:41:22.007   315  1386 V AudioFlinger: PlaybackThread::Track destructor
08-10 07:41:22.007   315  1386 V AudioFlinger: removeClient_l() pid 7864, calling pid 315
08-10 07:41:22.007  7864  7864 V Avrcp   : make
08-10 07:41:22.007  7864  7864 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-10 07:41:22.007  7864  7864 I bluedroid-qcom: get_profile_interface avrcp
08-10 07:41:22.009  1037  2036 W Process : Unable to open /proc/8117/status
08-10 07:41:22.014  7864  8095 V LGMDMManager: Create singleton instance
08-10 07:41:22.016  7864  8095 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-10 07:41:22.019  7864  7864 V AudioManager: registerRemoteController: size of Media player list: 0
08-10 07:41:22.022  7864  7864 E AudioManager: No RCC entry present to update
08-10 07:41:22.022  7864  7864 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-10 07:41:22.026  7864  7864 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-10 07:41:22.027  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-10 07:41:22.027  7864  7864 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-10 07:41:22.033  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-10 07:41:22.144  1037  1897 V SIM_STK : Menu title from STK is T-Mobile
08-10 07:41:22.144  1037  1897 V SIM_STK : Menu title from STK is T-Mobile
,08-10 07:41:22.246  1037  2054 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-10 07:41:22.256  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 07:41:22.260  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 07:41:22.262  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-10 07:41:22.263  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 07:41:22.263  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 07:41:22.263  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 07:41:22.263  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 07:41:22.264  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 07:41:22.264  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 07:41:22.264  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 07:41:22.265  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 07:41:22.265  7864  7864 I BluetoothA2dpServiceJni: classInitNative
08-10 07:41:22.265  7864  7864 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 07:41:22.265  7864  7864 D A2dpStateMachine: make
08-10 07:41:22.266  7864  7864 I bluedroid-qcom: get_profile_interface a2dp
08-10 07:41:22.267  7864  8126 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-10 07:41:22.269  7864  7864 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-10 07:41:22.269  7864  7864 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-10 07:41:22.270  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.271  7864  8125 D A2dpStateMachine: Enter Disconnected: -2
08-10 07:41:22.271  7864  7864 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 07:41:22.272  7864  7864 D HidService: Received start request. Starting profile...
08-10 07:41:22.273  7864  7864 I bluedroid-qcom: get_profile_interface hidhost
08-10 07:41:22.273  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.273  7864  7864 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 07:41:22.274  7864  7864 D HealthService: Received start request. Starting profile...
08-10 07:41:22.276  7864  7864 I bluedroid-qcom: get_profile_interface health
08-10 07:41:22.276  7864  7864 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-10 07:41:22.276  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.277  7864  7864 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 07:41:22.279  7864  7864 D PanService: Received start request. Starting profile...
08-10 07:41:22.279  7864  7864 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 07:41:22.279  7864  7864 I bluedroid-qcom: get_profile_interface pan
08-10 07:41:22.287  7864  7864 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-10 07:41:22.287  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.290  7864  7864 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-10 07:41:22.307  7864  7864 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 07:41:22.308  7864  7864 D BtGatt.GattService: Received start request. Starting profile...
08-10 07:41:22.309  7864  7864 D BtGatt.GattService: start()
,08-10 07:41:22.309  7864  7864 I bluedroid-qcom: get_profile_interface gatt
08-10 07:41:22.310  7864  7864 D BtGatt.AdvertiseManager: advertise manager created
08-10 07:41:22.320  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.320  7864  7864 D HeadsetStateMachine: Proxy object connected
08-10 07:41:22.321  7864  7864 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-10 07:41:22.321  7864  7864 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-10 07:41:22.324  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.325  7864  7864 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-10 07:41:22.326  7864  7864 V BluetoothMapService: BluetoothMapBinder()
08-10 07:41:22.327  7864  7864 D BluetoothMapService: Received start request. Starting profile...
08-10 07:41:22.327  7864  7864 D BluetoothMapService: start()
08-10 07:41:22.331  7864  7864 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-10 07:41:22.331  7864  7864 D BluetoothMapEmailAppObserver: createReceiver()
08-10 07:41:22.333  7864  7864 D BluetoothMapEmailAppObserver: initObservers()
08-10 07:41:22.333  7864  7864 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-10 07:41:22.342  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:22.348  7864  7864 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-10 07:41:22.349  7864  8115 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 07:41:22.350  7864  8115 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 07:41:22.350  7864  8115 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-10 07:41:22.355  7864  7864 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:22.360  7864  7864 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:22.364  7864  7864 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:22.365  7864  7864 V PanService: [BTUI] SIM Extra State :ABSENT
,08-10 07:41:22.371  7864  7864 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-10 07:41:22.376  7864  7864 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-10 07:41:22.376  7864  7864 V BluetoothMapService: Handler(): got msg=1
08-10 07:41:22.379  7864  8095 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-10 07:41:22.379  7864  8095 I bluedroid-qcom: enable
08-10 07:41:22.379  7864  8095 I bt_hci_bdroid: init
,08-10 07:41:22.381  7864  8136 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-10 07:41:22.381  7864  8136 I bt-btu  : btu_task pending for preload complete event
08-10 07:41:22.383  7864  8095 I bt_vendor: bt-vendor : init
08-10 07:41:22.383  7864  8095 I bt_vendor: bt-vendor : get_bt_soc_type
08-10 07:41:22.383  7864  8095 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-10 07:41:22.383  7864  8095 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-10 07:41:22.383  7864  8095 D bt_userial_mct: userial_init
08-10 07:41:22.384  7864  8095 D bt_hci_bdroid: set_power 1
08-10 07:41:22.384  7864  8095 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-10 07:41:22.384  7864  8095 I bt_vendor: Starting hciattach daemon
08-10 07:41:22.384  7864  8095 I bt_vendor: try to set true
08-10 07:41:22.380  8139  8139 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:22.380  8139  8139 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 07:41:22.414  8140  8140 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-10 07:41:22.486  8146  8146 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-10 07:41:22.511  8147  8147 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 07:41:22.540  8149  8149 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 07:41:22.553  8150  8150 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-10 07:41:22.565  8151  8151 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-10 07:41:22.589  8152  8152 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-10 07:41:22.613  8154  8154 I libmdmdetect: ESOC framework not supported
08-10 07:41:22.615  8154  8154 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-10 07:41:22.625  8154  8154 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-10 07:41:22.625  8154  8154 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-10 07:41:22.625  8154  8154 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-10 07:41:22.625  8154  8154 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-10 07:41:22.625  8154  8154 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-10 07:41:22.625  8154  8154 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-10 07:41:22.625  8154  8154 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-10 07:41:22.670  8154  8155 E QC-QMI  : qmi_client [8154] 15: failed to locate client data
,08-10 07:41:22.671   485   485 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-10 07:41:22.671   485   485 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-10 07:41:22.737  8156  8156 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-10 07:41:22.751  8157  8157 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-10 07:41:22.792  7864  8095 I bt_vendor: bluetooth satus is on
08-10 07:41:22.792  7864  8095 D bt_hci_bdroid: preload
08-10 07:41:22.792  7864  8138 D bt_userial_mct: userial_open(port:0)
08-10 07:41:22.792  7864  8138 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-10 07:41:22.796  7864  8138 I bt_vendor: Done intiailizing UART
,08-10 07:41:22.798  7864  8138 I bt_vendor: Done intiailizing UART
08-10 07:41:22.798  7864  8138 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-10 07:41:22.799  7864  8138 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-10 07:41:22.799  7864  8159 D bt_userial_mct: Entering userial_read_thread()
08-10 07:41:22.800  7864  8136 I bt-btu  : btu_task received preload complete event
08-10 07:41:22.801  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-10 07:41:22.801  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-10 07:41:22.816  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-10 07:41:22.828  7864  8136 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 07:41:22.828  7864  8136 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-10 07:41:22.828  7864  8136 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 07:41:22.828  7864  8136 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 07:41:22.828  7864  8136 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 07:41:22.828  7864  8136 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 07:41:22.828  7864  8136 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 07:41:22.828  7864  8136 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 07:41:22.829  7864  8136 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-10 07:41:22.829  7864  8136 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 07:41:22.829  7864  8136 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 07:41:22.829  7864  8136 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 07:41:22.829  7864  8136 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 07:41:22.829  7864  8136 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 07:41:22.829  7864  8136 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 07:41:22.829  7864  8136 I         : BTE_InitTraceLevels -- TRC_BTIF
08-10 07:41:22.935  7864  8136 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-10 07:41:22.935  7864  8136 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01bd061 
08-10 07:41:22.935  7864  8136 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01bd061 
,08-10 07:41:22.995  7864  8099 E bt-btif : Calling BTA_HhEnable
,08-10 07:41:22.996  7864  8099 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-10 07:41:22.996  7864  8099 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-10 07:41:23.004  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-10 07:41:23.006  1037  1037 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-10 07:41:23.007  1037  1037 D BluetoothManagerService: Stored Bluetooth name: G3
08-10 07:41:23.007  7864  8099 D BluetoothAdapterProperties: Name is: G3
08-10 07:41:23.008  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-10 07:41:23.008  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-10 07:41:23.008  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-10 07:41:23.008  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-10 07:41:23.009  7864  8099 D BluetoothAdapterProperties: Scan Mode:20
08-10 07:41:23.009  7864  8099 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 07:41:23.009  7864  8099 D bt_hci_bdroid: postload
08-10 07:41:23.009  7864  8138 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:23.010  7864  8099 D bte_conf: Device ID record 1 : primary
08-10 07:41:23.010  7864  8099 D bte_conf:   vendorId            = 00c4
,08-10 07:41:23.010  7864  8099 D bte_conf:   vendorIdSource      = 0001
08-10 07:41:23.010  7864  8099 D bte_conf:   product             = 13a1
,08-10 07:41:23.010  7864  8099 D bte_conf:   version             = 1000
08-10 07:41:23.010  7864  8099 D bte_conf:   clientExecutableURL = 
08-10 07:41:23.010  7864  8099 D bte_conf:   serviceDescription  = 
08-10 07:41:23.010  7864  8099 D bte_conf:   documentationURL    = 
08-10 07:41:23.013  7864  8136 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-10 07:41:23.014  7864  8099 D bte_conf: bte_load_did_conf no section named DID2.
,08-10 07:41:23.023  7864  8095 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-10 07:41:23.024  7864  8095 D BluetoothAdapterProperties: ScanMode =  20
08-10 07:41:23.024  7864  8095 D BluetoothAdapterProperties: State =  11
08-10 07:41:23.024  7864  8095 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-10 07:41:23.024  7864  8095 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-10 07:41:23.024  7864  8095 D BluetoothAdapterProperties: Setting state to 12
08-10 07:41:23.024  7864  8095 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 07:41:23.028  7864  8099 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 07:41:23.028  7864  8099 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-10 07:41:23.030  8164  8164 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:23.030  8164  8164 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:23.054  1037  1119 D BluetoothManagerService: Message: 60
08-10 07:41:23.054  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-10 07:41:23.054  1037  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-10 07:41:23.058  7864  8138 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:23.063  7864  8138 D bt_hci_bdroid: Used up Tx Cmd credits
08-10 07:41:23.068  7864  8138 D bt_hci_bdroid: Used up Tx Cmd credits
,08-10 07:41:23.070  7864  8159 E bt_mct  : hci lib postload completed
08-10 07:41:23.079  7864  8136 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:23.079  7864  8136 W bt-smp  : Plain text(LSB ~ MSB) = d0 90 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:23.079  7864  8136 W bt-smp  : Encrypted text(LSB ~ MSB) = 76 6f 8f d3 48 1c 8e 1e a7 c6 a8 8b 44 dc 58 73 
08-10 07:41:23.079  7864  8136 W bt-btm  : Stopping oneshot timer
08-10 07:41:23.085  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:23.085  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:23.085  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:23.085  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:23.085  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:23.085  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:23.085  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:23.085  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 07:41:23.090  7864  8095 I BluetoothAdapterState: Entering On State
08-10 07:41:23.099  7864  8099 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 07:41:23.099  7864  8099 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-10 07:41:23.108  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:23.111  7864  8136 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:23.111  7864  8136 W bt-smp  : Plain text(LSB ~ MSB) = b4 9d 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:23.111  7864  8136 W bt-smp  : Encrypted text(LSB ~ MSB) = 19 8c 8f cf 01 d8 9b f5 bd 1e 20 5f 1f 08 ab 52 
,08-10 07:41:23.112  7864  8136 W bt-btm  : Stopping oneshot timer
08-10 07:41:23.125  7864  8095 D LGBluetoothServiceAdapter: [BTUI] OnState
08-10 07:41:23.125  7864  8095 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-10 07:41:23.125  7864  8095 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-10 07:41:23.131  7864  8095 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-10 07:41:23.148  7864  8095 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-10 07:41:23.151  7062  7083 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 07:41:23.161  7062  7781 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 07:41:23.164  8182  8182 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-10 07:41:23.165  7864  8136 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:23.166  7864  8136 W bt-smp  : Plain text(LSB ~ MSB) = eb fe 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:23.166  7864  8136 W bt-smp  : Encrypted text(LSB ~ MSB) = 3d 47 e0 59 4a 00 a2 53 6f 38 be ae 5d 49 e0 42 
08-10 07:41:23.166  7864  8136 W bt-btm  : Stopping oneshot timer
08-10 07:41:23.169  7062  7082 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 07:41:23.170  7062  7062 D BluetoothMap: Proxy object connected
08-10 07:41:23.170  7062  7062 D MapProfile: Bluetooth service connected
08-10 07:41:23.170  7062  7062 D BluetoothMap: getConnectedDevices()
08-10 07:41:23.171  1853  2752 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 07:41:23.171  7864  7882 V BluetoothMapService: getConnectedDevices()
08-10 07:41:23.173  7062  7062 D BluetoothInputDevice: Proxy object connected
08-10 07:41:23.173  7062  7062 D HidProfile: Bluetooth service connected
08-10 07:41:23.173  7062  7083 D BluetoothPan: onBluetoothStateChange on: true
08-10 07:41:23.173  7062  7083 D BluetoothPan: onBluetoothStateChange call bindService
08-10 07:41:23.175  1853  1853 D BluetoothHeadset: Proxy object connected
,08-10 07:41:23.177  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 07:41:23.179  1853  1853 D BluetoothHeadset: Proxy object connected
08-10 07:41:23.179  7062  7062 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 07:41:23.179  7062  7062 D PanProfile: Bluetooth service connected
08-10 07:41:23.179  7864  8136 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-10 07:41:23.179  7864  8136 W bt-smp  : Plain text(LSB ~ MSB) = 6c 1e 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:23.179  7864  8136 W bt-smp  : Encrypted text(LSB ~ MSB) = cf a0 52 8c 30 fa 8c da 29 9d d0 56 a8 57 da 16 
08-10 07:41:23.179  7864  8136 W bt-btm  : Stopping oneshot timer
08-10 07:41:23.180  7062  7083 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 07:41:23.184  1853  2752 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 07:41:23.184  7062  7062 D BluetoothA2dp: Proxy object connected
08-10 07:41:23.184  7062  7062 D A2dpProfile: Bluetooth service connected
08-10 07:41:23.186  1037  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 07:41:23.186  1853  1853 D BluetoothHeadset: Proxy object connected
08-10 07:41:23.186  1037  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 07:41:23.187  1037  1037 D BluetoothHeadset: Proxy object connected
08-10 07:41:23.187  7062  7781 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 07:41:23.189  7864  8136 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-10 07:41:23.189  7864  8136 W bt-smp  : Plain text(LSB ~ MSB) = b5 bd 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-10 07:41:23.189  7864  8136 W bt-smp  : Encrypted text(LSB ~ MSB) = 4b 39 be 81 c8 c7 7b 42 04 61 75 d6 ad f6 aa 61 
08-10 07:41:23.189  7864  8136 W bt-btm  : Stopping oneshot timer
08-10 07:41:23.190  1037  1037 D BluetoothA2dp: Proxy object connected
08-10 07:41:23.190  7062  7062 D BluetoothHeadset: Proxy object connected
08-10 07:41:23.190  7062  7062 D HeadsetProfile: Bluetooth service connected
08-10 07:41:23.191  1037  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-10 07:41:23.191  1037  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-10 07:41:23.194  1037  1037 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-10 07:41:23.195  1605  1605 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-10 07:41:23.195  1037  1119 D BluetoothManagerService: Message: 40
08-10 07:41:23.195  1037  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-10 07:41:23.198  1944  1944 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:23.198  1944  2144 D LGBluetoothAPIService: Message: 1
08-10 07:41:23.198  1944  2144 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-10 07:41:23.198  1944  2144 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-10 07:41:23.199  1944  2144 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-10 07:41:23.200  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:23.202  7864  7864 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:23.202  7864  7864 D BluetoothMapService: STATE_ON
08-10 07:41:23.202  7864  7864 V BluetoothMapService: Handler(): got msg=1
08-10 07:41:23.203  7864  7864 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-10 07:41:23.206  7864  8187 D BluetoothMapMasInstance: MAS initSocket()
08-10 07:41:23.206  7062  7062 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-10 07:41:23.207  7864  8187 D BluetoothMapMasInstance:   masId = 00
08-10 07:41:23.207  7864  8187 D BluetoothMapMasInstance:   msgTypes = 0e
08-10 07:41:23.207  7864  8187 D BluetoothMapMasInstance:   masName = SMS/MMS
08-10 07:41:23.207  7864  8187 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-10 07:41:23.208  7062  7062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-10 07:41:23.210  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:23.211  7864  8187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 07:41:23.217  7062  7062 D DockEventReceiver: finishStartingService: stopping service
08-10 07:41:23.217  7864  8187 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-10 07:41:23.218  7864  8187 V BluetoothMapMasInstance: Succeed to create listening socket 
08-10 07:41:23.218  7864  8187 D BluetoothMapMasInstance: Accepting socket connection...
08-10 07:41:23.219  7864  8099 D BluetoothAdapterProperties: Scan Mode:21
08-10 07:41:23.219  7864  8099 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-10 07:41:23.221  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:23.221  7864  7864 V BluetoothPbapService: Pbap Service onCreate
08-10 07:41:23.221  7864  7864 V BluetoothPbapService: Starting PBAP service
08-10 07:41:23.224  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:23.226  7864  7864 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-10 07:41:23.226  7864  7864 V BluetoothPbapService: Pbap Service onBind
08-10 07:41:23.227  7864  7864 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:23.227  7864  7864 V BluetoothPbapService: state: 12
08-10 07:41:23.227  7864  7864 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-10 07:41:23.227  7864  7864 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:23.228  7864  7864 V BluetoothPbapReceiver: ***********state = 12
08-10 07:41:23.229  7062  7062 D BluetoothPbap: Proxy object connected
08-10 07:41:23.229  7062  7062 D PbapServerProfile: Bluetooth service connected
08-10 07:41:23.229  7864  7864 V BluetoothPbapService: Handler(): got msg=1
08-10 07:41:23.229  7864  7864 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-10 07:41:23.231  7864  8189 V BluetoothPbapService: Pbap Service initSocket
08-10 07:41:23.233  1037  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:23.233  2182  2182 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 07:41:23.234  2182  2182 D c       : Getting all permits...
08-10 07:41:23.234  2182  2182 D a       : Opening database...
08-10 07:41:23.234  7864  8189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 07:41:23.236  7864  8189 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-10 07:41:23.236  7864  8189 V BluetoothPbapService: Succeed to create listening socket 
08-10 07:41:23.236  7864  8189 V BluetoothPbapService: Accepting socket connection...
,08-10 07:41:23.237  2182  2182 D a       : Opening database auth.proximity.permit_store...
08-10 07:41:23.237  2182  2182 D a       : Closing database...
08-10 07:41:23.249  7062  7062 D BluetoothPermissionRequest: onReceive
,08-10 07:41:23.252  7062  7062 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-10 07:41:23.253  7062  7062 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-10 07:41:23.257  7864  7864 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-10 07:41:23.258  7864  7864 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-10 07:41:23.265  7864  7864 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-10 07:41:23.285  7864  7864 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-10 07:41:23.285  7864  7864 V BtOppService: onCreate
,08-10 07:41:23.290  7864  7864 V BluetoothOppNotification: send message
08-10 07:41:23.294  7864  7864 V BtOppService: Starting RfcommListener
08-10 07:41:23.302  7864  7864 D BluetoothOppPreference: Dumping Names:  
08-10 07:41:23.302  7864  7864 D BluetoothOppPreference: {}
,08-10 07:41:23.302  7864  7864 D BluetoothOppPreference: Dumping Channels:  
08-10 07:41:23.302  7864  7864 D BluetoothOppPreference: {}
08-10 07:41:23.303  7864  7864 V BtOppService: onStartCommand
,08-10 07:41:23.307  7864  8196 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 07:41:23.307  7864  8193 V BtOppService: Deleted complete outbound shares, number =  0
08-10 07:41:23.311  7864  8193 V BtOppService: Deleted complete inbound failed shares, number = 0
08-10 07:41:23.312  7864  7864 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:23.312  7864  8193 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-10 07:41:23.312  7864  7864 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-10 07:41:23.311  7864  8196 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 07:41:23.314  7864  8196 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c31312a on behalf of 
08-10 07:41:23.314  7864  8193 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@375b9a15 on behalf of 
08-10 07:41:23.315  7864  8196 V BluetoothOppNotification: update too frequent, put in queue
08-10 07:41:23.318  7864  7864 V BluetoothOppNotification: new notify threadi!
08-10 07:41:23.319  7864  7864 V BluetoothOppNotification: send delay message
,08-10 07:41:23.320  7864  7864 V BtOppService: start RfcommListener
,08-10 07:41:23.321  7864  8197 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-10 07:41:23.323  7864  8197 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e68eb1b on behalf of 
08-10 07:41:23.323  7864  8196 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-10 07:41:23.323  7864  8196 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 07:41:23.325  7864  8197 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-10 07:41:23.325  7864  7864 V BtOppService: RfcommListener started
08-10 07:41:23.325  7864  7864 V BtOppService: ContentObserver received notification
08-10 07:41:23.325  7864  7864 V BtOppService: ContentObserver received notification
08-10 07:41:23.326  7864  8198 V BtOppRfcommListener: Starting RFCOMM listener....
08-10 07:41:23.327  7864  8196 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@c3084b8 on behalf of 
,08-10 07:41:23.327  1037  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:23.327  7864  8197 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 07:41:23.330  7864  8197 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1768c291 on behalf of 
08-10 07:41:23.330  7864  8198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 07:41:23.331  7864  8197 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 07:41:23.333  7864  8196 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-10 07:41:23.333  7864  8196 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-10 07:41:23.334  7864  8198 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-10 07:41:23.335  7864  8198 V BtOppRfcommListener: Started RFCOMM listener....
08-10 07:41:23.335  7864  8198 I BtOppRfcommListener: Accept thread started.
08-10 07:41:23.336  7864  8196 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@300935f6 on behalf of 
08-10 07:41:23.336  7864  8198 V BtOppRfcommListener: Accepting connection...
08-10 07:41:23.337  7864  8196 V BluetoothOppNotification: update too frequent, put in queue
08-10 07:41:23.337  7864  8197 V BluetoothOppNotification: outbound notification was removed.
08-10 07:41:23.337  7864  8197 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 07:41:23.339  7864  8196 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-10 07:41:23.339  7864  8197 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34a11df7 on behalf of 
08-10 07:41:23.341  7864  8197 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 07:41:23.343  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:23.343  7864  7864 V BluetoothFtpService: Ftp Service onCreate
08-10 07:41:23.343  7864  7864 I BluetoothFtpService: Ftp Service onCreate
08-10 07:41:23.343  7864  7864 V BluetoothFtpService: Ftp Service onStartCommand
08-10 07:41:23.344  7864  8197 V BluetoothOppNotification: inbound notification was removed.
08-10 07:41:23.344  7864  7864 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:23.344  7864  7864 V BluetoothFtpService: Starting Listening on sockets
08-10 07:41:23.344  7864  8197 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 07:41:23.344  7864  7864 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-10 07:41:23.344  7864  7864 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-10 07:41:23.344  7864  7864 V BluetoothSapReceiver: SapReceiver onReceive 
08-10 07:41:23.344  7864  7864 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:23.344  7864  7864 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-10 07:41:23.344  7864  7864 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-10 07:41:23.347  7864  8197 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a45f6cd on behalf of 
08-10 07:41:23.347  7864  7864 V BluetoothFtpService: Handler(): got msg=1
08-10 07:41:23.348  7864  7864 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-10 07:41:23.348  7864  7864 V BluetoothFtpService: Ftp Service initSocket
08-10 07:41:23.354  1037  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:23.356  7864  7864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 07:41:23.357  7864  7864 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-10 07:41:23.357  7864  7864 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-10 07:41:23.360  7864  8199 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-10 07:41:23.379  7864  7864 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19b1d509
08-10 07:41:23.379  7864  7864 V BluetoothSapService: Sap Service onCreate
,08-10 07:41:23.383  7864  7864 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-10 07:41:23.383  7864  7864 V BluetoothSapService: state: 12
08-10 07:41:23.384  7864  7864 V BluetoothSapService: Starting SAP server process
08-10 07:41:23.388  7864  7864 V BluetoothSapService: SAP Service startRfcommListenerThread
08-10 07:41:23.380  8200  8200 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:23.380  8200  8200 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:23.391  7864  8201 V BluetoothSapService: Sap Service initRfcommSocket
08-10 07:41:23.392  1037  1925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 07:41:23.396  7864  8201 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 07:41:23.398  7864  8201 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-10 07:41:23.398  7864  8201 V BluetoothSapService: Succeed to create listening socket 
08-10 07:41:23.399  7864  8201 V BluetoothSapService: Accepting socket connection...
08-10 07:41:23.405  8200  8200 V BT_SAP  : Event pipe created
08-10 07:41:23.405  8200  8200 V BT_SAP  : create_server_socket qcom.sap.server
08-10 07:41:23.406  8200  8200 V BT_SAP  : created socket fd 6
,08-10 07:41:23.803  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:23.803  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:23.803  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:23.803  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 07:41:23.803  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:23.803  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:23.803  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:23.803  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 07:41:23.817  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:23.819  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:23.819  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1b2392 added. We now have 8 listener(s)
08-10 07:41:23.819  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:23.823  1037  1925 D WifiServiceImplEx: setWifiEnabled: false pid=6960, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 07:41:23.823  1037  1925 D WifiService: setWifiEnabled: false pid=6960, uid=10118
08-10 07:41:23.823  1037  1925 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 07:41:23.833  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:23.835  1037  1926 D WifiServiceImplEx: setWifiEnabled: true pid=6960, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-10 07:41:23.835  1037  1926 D WifiService: setWifiEnabled: true pid=6960, uid=10118
08-10 07:41:23.835  1037  1926 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 07:41:23.855  1037  1037 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-10 07:41:23.855  1037  1037 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-10 07:41:23.855  1037  1037 D Ulp_jni : JNI:system_update. Event-4
,08-10 07:41:23.857  1037  1541 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-10 07:41:23.857  1037  1541 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-10 07:41:23.860  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-10 07:41:23.860  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 07:41:23.860  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): pid[1037] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-10 07:41:23.860  1037  1541 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-10 07:41:23.860  1037  1541 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-10 07:41:23.860  1037  1541 E WifiHW  : unknown target_country: EU , set to default
08-10 07:41:23.860  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-10 07:41:23.860  1037  1541 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-10 07:41:23.860  1037  1541 I WifiUtil: gEnableBmps=1
08-10 07:41:24.322  7864  7864 V BluetoothOppNotification: new notify threadi!
,08-10 07:41:24.336  7864  7864 V BluetoothOppNotification: send delay message
,08-10 07:41:24.341  7864  8221 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-10 07:41:24.349  7864  8221 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@94832c9 on behalf of 
08-10 07:41:24.351  7864  8221 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-10 07:41:24.356  7864  8221 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-10 07:41:24.359  7864  8221 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ad0dce on behalf of 
08-10 07:41:24.359  7864  8221 V BluetoothOppNotification: outbound: succ-0  fail-0
08-10 07:41:24.361  7864  8221 V BluetoothOppNotification: outbound notification was removed.
08-10 07:41:24.361  7864  8221 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-10 07:41:24.362  7864  8221 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@637d4ef on behalf of 
08-10 07:41:24.363  7864  8221 V BluetoothOppNotification: inbound: succ-0  fail-0
08-10 07:41:24.364  7864  8221 V BluetoothOppNotification: inbound notification was removed.
08-10 07:41:24.365  7864  8221 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-10 07:41:24.366  7864  8221 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@880abfc on behalf of 
,08-10 07:41:24.422   310   895 D SoftapController: Softap fwReload - Ok
,08-10 07:41:24.431  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-10 07:41:24.431  1037  1119 D Tethering: InitialState.processMessage what=4
08-10 07:41:24.443  1037  1541 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (579ms)
,08-10 07:41:24.462  1037  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-10 07:41:24.467   310   895 D CommandListener: Setting iface cfg
08-10 07:41:24.467   310   895 D CommandListener: Trying to bring down wlan0
08-10 07:41:24.467   310   895 D CommandListener: Clearing all IP addresses on wlan0
08-10 07:41:24.482  1037  1541 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-10 07:41:24.480  8223  8223 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:24.493  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 07:41:24.493  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-10 07:41:24.493  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 07:41:24.500  8223  8223 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 07:41:24.514  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:24.518  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-10 07:41:24.548  1037  1541 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-10 07:41:24.549  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-10 07:41:24.556  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:24.557  1037  1541 D WifiMonitor: connecting to supplicant
08-10 07:41:24.557  8223  8223 I wpa_supplicant: Successfully initialized wpa_supplicant
08-10 07:41:24.560  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 07:41:24.560  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 07:41:24.560  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 07:41:24.560  7062  7062 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 07:41:24.563  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-10 07:41:24.584  7062  7062 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 07:41:24.584  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 07:41:24.584  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 07:41:24.584  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-10 07:41:24.584  7062  7062 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 07:41:24.584  7062  7062 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 07:41:24.587  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 07:41:24.588  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-10 07:41:24.588  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 07:41:24.588  7062  7062 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 07:41:24.597  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 07:41:24.598  7062  7062 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 07:41:24.598  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-10 07:41:24.598  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 07:41:24.598  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-10 07:41:24.598  7062  7062 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 07:41:24.598  7062  7062 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-10 07:41:24.614  8223  8223 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-10 07:41:24.615  8223  8223 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-10 07:41:24.634  1037  1879 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8240 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-10 07:41:24.671  8223  8223 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-10 07:41:24.704  7967  7978 E UEI.SmartControl: file observer is disposed!
,08-10 07:41:24.736  8223  8223 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-10 07:41:24.744  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-10 07:41:24.744  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-10 07:41:24.745  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-10 07:41:24.745  1037  1541 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-10 07:41:24.745  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:24.746  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:24.746  1037  1541 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:24.747  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:24.747  1037  1541 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-10 07:41:24.747  1037  1541 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-10 07:41:24.747  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-10 07:41:24.748  8223  8223 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-10 07:41:24.748  1037  1541 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-10 07:41:24.748  1037  8262 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-10 07:41:24.749  1037  8262 D WifiMonitor: Dropping event because (p2p0) is stopped
08-10 07:41:24.749  1037  1541 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-10 07:41:24.749  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 07:41:24.749  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 07:41:24.749  1037  1541 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-10 07:41:24.749  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-10 07:41:24.749  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-10 07:41:24.749  1037  8262 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-10 07:41:24.749  1037  8262 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-10 07:41:24.761  1037  2054 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8263 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 07:41:24.765  1037  1541 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-10 07:41:24.765  1037  1541 E WifiStateMachine: useWiFiOffloading() : false
08-10 07:41:24.765  1037  1541 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-10 07:41:24.766  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.766  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.766  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.766  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.767  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-10 07:41:24.768  8240  8260 W FormManager: Network not available. Please check & try again.
08-10 07:41:24.768  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:24.768  1037  1037 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-10 07:41:24.769  1037  1545 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-10 07:41:24.769  1037  1541 D WifiNative-wlan0: doBoolean: SET update_config 1
08-10 07:41:24.769  1944  1944 D WfdService: Waiting for WifiP2p enabling
08-10 07:41:24.769  1037  1541 D WifiNative-wlan0: SET update_config 1: returned true
08-10 07:41:24.769  1037  1541 D WifiConfigStore: Loading config and enabling all networks 
08-10 07:41:24.769  1037  1541 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-10 07:41:24.770  1037  1541 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-10 07:41:24.775  1037  1541 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-10 07:41:24.778  8240  8261 V FormManager: Network unavailable.
08-10 07:41:24.781  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:24.781  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:24.781  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:24.781  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:24.781  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:24.781  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:24.781  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:24.781  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:24.782  8240  8261 V FormManager: Network unavailable.
08-10 07:41:24.782  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:24.784  1037  1541 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-10 07:41:24.784  1037  1541 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-10 07:41:24.785  1037  1541 D WifiStateMachine: enableVerboseLogging : level 2
08-10 07:41:24.785  1037  1541 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-10 07:41:24.786  1037  1541 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-10 07:41:24.786  1037  1541 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-10 07:41:24.786  1037  1541 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-10 07:41:24.786  1037  1541 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-10 07:41:24.787  1037  1541 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-10 07:41:24.787  1037  1541 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-10 07:41:24.787  1037  1541 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-10 07:41:24.787  1037  1541 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-10 07:41:24.788  1037  1541 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-10 07:41:24.788  1037  1541 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-10 07:41:24.788  1037  1541 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-10 07:41:24.788  1037  1541 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-10 07:41:24.788  1037  1541 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-10 07:41:24.789  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 07:41:24.789  1037  1541 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-10 07:41:24.789  1944  1944 D WfdsService: Supplicant Connection state is changed : true
08-10 07:41:24.789  1944  2358 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-10 07:41:24.789  1944  2358 D WfdsService: Set the WFDS Monitor: true
08-10 07:41:24.790  1944  2358 D WfdsMonitor: WfdsMonitorThread create
08-10 07:41:24.790  1037  1541 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-10 07:41:24.790  1037  1541 D WifiNative-HAL: Setting external_sim to 1
08-10 07:41:24.790  1037  1541 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-10 07:41:24.790  1944  2358 D WfdsMonitor: WFDS Monitor is created and started
08-10 07:41:24.790  1944  2358 D WfdsService: WiFi: Supplicant connection re-established
08-10 07:41:24.790  1037  1541 D WifiNative-wlan0: SET external_sim 1: returned true
08-10 07:41:24.790  1037  1541 I WifiNative-HAL: startHal
08-10 07:41:24.790  1037  1541 D wifi    : setting scan oui 0xaf730500
08-10 07:41:24.791  1037  1541 D WifiStateMachine: Setting OUI to DA-A1-19
08-10 07:41:24.791  1037  1541 I WifiNative-HAL: startHal
08-10 07:41:24.791  1037  1541 D wifi    : setting scan oui 0xaf730500
08-10 07:41:24.791  1037  1541 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-10 07:41:24.791  7907  7907 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.793  1944  8281 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
,08-10 07:41:24.793  1944  8281 E CtrlSupplicant: Succeed to open control connection
08-10 07:41:24.793  1037  1541 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-10 07:41:24.793  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-10 07:41:24.793  1944  8281 E CtrlSupplicant: Succeed to open monitor connection
08-10 07:41:24.793  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-10 07:41:24.793  1944  8281 D WfdsMonitor: Supplicant connection established
08-10 07:41:24.794  1944  2358 D WfdsService: Connected to the supplicant for wfds
08-10 07:41:24.794  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-10 07:41:24.794  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 07:41:24.794  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 07:41:24.795  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 07:41:24.795  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-10 07:41:24.795  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-10 07:41:24.795  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-10 07:41:24.795  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 07:41:24.795  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-10 07:41:24.796  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 07:41:24.796  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-10 07:41:24.796  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-10 07:41:24.796  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-10 07:41:24.796  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-10 07:41:24.796  8223  8223 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-10 07:41:24.797  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-10 07:41:24.797  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-10 07:41:24.797  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-10 07:41:24.797  1037  1541 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-10 07:41:24.798  1037  1897 I ActivityManager: Killing 7367:com.android.chrome/u0a57 (adj 15): empty #17
08-10 07:41:24.798  1037  1541 E WifiNative: : [346,042,674 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-10 07:41:24.798  1037  1541 D WifiNative-wlan0: doBoolean: RECONNECT
08-10 07:41:24.799  1037  1541 D WifiNative-wlan0: RECONNECT: returned true
08-10 07:41:24.799  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-10 07:41:24.799  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-10 07:41:24.799  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-10 07:41:24.799  1037  1541 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 07:41:24.799  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 07:41:24.800  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-10 07:41:24.800  1037  1539 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 07:41:24.802   310   895 D CommandListener: Setting iface cfg
08-10 07:41:24.802   310   895 D CommandListener: Trying to bring up p2p0
08-10 07:41:24.802  1037  1539 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 07:41:24.802  1037  1539 D LGWifiP2pService: P2pEnablingState
08-10 07:41:24.802  1037  1539 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.802  1037  1539 D LGWifiP2pService: P2p socket connection successful
08-10 07:41:24.803  1037  1539 D LGWifiP2pService: P2pEnabledState
08-10 07:41:24.823  1037  1037 D WifiScanningService: SCAN_AVAILABLE : 3
,08-10 07:41:24.823  1037  1037 D RttService: SCAN_AVAILABLE : 3
08-10 07:41:24.824  1037  1560 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.824  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-10 07:41:24.824  1037  1559 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.824  1037  1559 I WifiNative-HAL: startHal
08-10 07:41:24.824  1037  1559 D wifi    : getting scan capabilities on interface[1] = 0xaf730500
08-10 07:41:24.824  1037  1559 D wifi    : failed to get capabilities : -3
08-10 07:41:24.824  1037  1559 E WifiScanningService: could not get scan capabilities
08-10 07:41:24.824  1037  1541 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-10 07:41:24.824  1037  1541 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-10 07:41:24.825  1037  1541 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-10 07:41:24.825  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=346070  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 07:41:24.826  1037  1578 W libprocessgroup: failed to open /acct/uid_10057/pid_7367/cgroup.procs: No such file or directory
08-10 07:41:24.829  1037  1539 D LGWifiP2pService: sending p2p connection changed broadcast
08-10 07:41:24.830  1037  1539 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-10 07:41:24.830  1037  1539 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-10 07:41:24.830  1037  1539 D WifiNative-p2p0: doBoolean: SET device_name G3
08-10 07:41:24.830  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=346075  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 07:41:24.830  1037  1539 D WifiNative-p2p0: SET device_name G3: returned true
08-10 07:41:24.830  1037  1539 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-10 07:41:24.830  1037  1539 D LGWifiP2pService: before postfix = G3
08-10 07:41:24.830  1037  1539 D WifiServerServiceExt: postfix byte check : 2
08-10 07:41:24.830  1037  1539 D LGWifiP2pService: after postfix = G3
08-10 07:41:24.830  1037  1539 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-10 07:41:24.831  1037  1541 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-10 07:41:24.831  1944  1944 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-10 07:41:24.831  1944  1944 D WfdsService: WifiP2pState is changed : true
08-10 07:41:24.831  1037  1541 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-10 07:41:24.831  1944  1944 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-10 07:41:24.831  1037  1539 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-10 07:41:24.831  1037  1539 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-10 07:41:24.831  1037  1539 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-10 07:41:24.831  1037  1539 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-10 07:41:24.831  1037  1541 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-10 07:41:24.832  1037  1541 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-10 07:41:24.832  1944  1944 D WfdsService: isConnected: false
08-10 07:41:24.832  8223  8223 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-10 07:41:24.832  1037  1539 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-10 07:41:24.832  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-10 07:41:24.832  1037  1541 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-10 07:41:24.832  1944  2358 D WfdsService: Receive the WFDS_ENABLE Method
08-10 07:41:24.832  1944  2358 D WfdsService: Set the WFDS Monitor: true
08-10 07:41:24.832  1037  1541 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-10 07:4,1:24.832  1944  2358 D WfdsService: Connected to the supplicant for wfds
08-10 07:41:24.832  1037  1539 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-10 07:41:24.833  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress
08-10 07:41:24.833  1944  2358 D WfdsJNI : doCommand: WFDS_SET TRUE
08-10 07:41:24.833  8223  8223 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-10 07:41:24.833  1037  1541 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-10 07:41:24.833  1037  1541 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-10 07:41:24.833  8223  8223 E wpa_supplicant: disconnect_rssi_lvl: -100
08-10 07:41:24.833  1944  2358 D WfdsService: selectPreferredScanChannel [36]
08-10 07:41:24.833  1944  2358 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-10 07:41:24.833  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:24.833  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:24.833  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 07:41:24.833  1037  1539 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-10 07:41:24.834  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 07:41:24.834  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.834  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:24.834  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-10 07:41:24.834  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.834  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-10 07:41:24.834  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 07:41:24.835  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-10 07:41:24.836  8223  8223 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:24.836  8223  8223 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 07:41:24.837  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.837  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.837  1037  1539 D LGWifiP2pService: DeviceAddress: 
08-10 07:41:24.837  1037  1539 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-10 07:41:24.837  1944  8281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:24.838  1944  8281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:24.838  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 07:41:24.838  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:24.838  1037  8262 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:24.838  1037  8262 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:24.838  1037  8262 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:24.838  1037  8262 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.838  1037  8262 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.838  1037  8262 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.838  1037  8262 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:24.838  1037  8262 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.838  1037  8262 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.838  1037  1541 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-10 07:41:24.839  1037  1539 D WifiNative-p2p0: P2P_FLUSH: returned true
08-10 07:41:24.839  1037  1539 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-10 07:41:24.839  1037  1539 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-10 07:41:24.839  1037  1539 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-10 07:41:24.839  1037  8262 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.839  1037  1541 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-10 07:41:24.839  1944  1944 I WfdStateTracker: handleP2pThisDeviceChanged
08-10 07:41:24.839  1037  1539 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-10 07:41:24.839  1037  1539 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-10 07:41:24.839  1944  1944 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-10 07:41:24.839  1944  1944 D WfdsService: Update P2p Interface State: 3
08-10 07:41:24.840  1037  1541 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-10 07:41:24.840  1037  1541 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-10 07:41:24.840  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-10 07:41:24.848  1037  1539 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-10 07:41:24.848  1037  1539 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-10 07:41:24.848  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-10 07:41:24.848  8223  8223 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 07:41:24.849  1037  1539 D LGWifiP2pService: InactiveState
08-10 07:41:24.849  1037  1539 D LGWifiP2pService: InactiveState{ when=-11ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.849  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.849  1037  1539 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-10 07:41:24.849  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-10 07:41:24.849  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 07:41:24.849  1037  8262 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 07:41:24.849  1037  8262 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-10 07:41:24.850  1037  1541 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-10 07:41:24.850  1037  1541 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-10 07:41:24.850  1037  1541 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-10 07:41:24.850  1037  1541 D WifiNative-wlan0: doBoolean: SCAN
08-10 07:41:24.850  1037  1541 D WifiNative-wlan0: SCAN: returned false
08-10 07:41:24.851  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=346095  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 07:41:24.851  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-10 07:41:24.852  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:24.852  8223  8223 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-10 07:41:24.852  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.853  8223  8223 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.853  1037  1539 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-10 07:41:24.853  1037  1539 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.854  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.854  1037  1539 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.854  1944  8281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 07:41:24.854  1944  8281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:24.854  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.854  1944  8281 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:24.854  1037  1539 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.854  1037  8262 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-10 07:41:24.854  1037  8262 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:24.854  1037  8262 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:24.854  1037  8262 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-10 07:41:24.854  1037  8262 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDO,M-CHANGE init=DRIVER type=WORLD]
08-10 07:41:24.854  1037  8262 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.854  1037  8262 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.854  1037  8262 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.854  1037  8262 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-10 07:41:24.854  1037  8262 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.854  1037  8262 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.854  1037  8262 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-10 07:41:24.855  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:24.855  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:24.855  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.855  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:24.855  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-10 07:41:24.855  1037  1539 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.855  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.855  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.856  1037  1539 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.856  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.856  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.856  1037  1539 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.856  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.856  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:24.856  1037  1539 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:24.856  1037  1037 E WifiServerServiceExt: No p2p device connected
08-10 07:41:24.857  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=346102  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-10 07:41:24.857  1944  2358 W WfdsService: DefaultState - msg [9441285] is not handled
08-10 07:41:24.857  1037  1541 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:24.857  1037  1541 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:24.858  1037  1541 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:24.858  1037  1541 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:24.858  1037  1541 E WifiStat,eMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-10 07:41:24.859  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:24.859  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 07:41:24.860  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:24.860  1037  1037 D WifiServerServiceExt: setSupplicantStateSCANNING
08-10 07:41:24.869  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:24.869  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:24.869  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:24.869  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:24.869  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:24.869  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 07:41:24.869  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 07:41:24.869  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 07:41:24.870  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 07:41:24.874  6960  7027 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-10 07:41:24.874  6960  7027 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-10 07:41:24.875  6960  7027 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3ddeddd4 Bundle[{}]
08-10 07:41:24.876  6960  7027 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 07:41:24.876  6960  7027 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-10 07:41:24.876  8263  8263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:24.877  6960  7027 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-10 07:41:24.878  6960  7027 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-10 07:41:24.878  6960  7027 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-10 07:41:24.879  6960  7027 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-10 07:41:24.879  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-10 07:41:24.884  6960  7027 I System.out: Running OutgoingSocketThread
08-10 07:41:24.885  6960  8285 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 910)
08-10 07:41:24.886  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:24.886  6960  8285 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60009
08-10 07:41:24.886  6960  8285 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-10 07:41:24.887  1037  1954 I ActivityManager: Killing 7391:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-10 07:41:24.916  1037  2034 W libprocessgroup: failed to open /acct/uid_10062/pid_7391/cgroup.procs: No such file or directory
,08-10 07:41:24.929  8263  8263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-10 07:41:24.932  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-10 07:41:24.938  8240  8287 W FormManager: Network not available. Please check & try again.
08-10 07:41:24.940  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:24.953  8240  8288 V FormManager: Network unavailable.
,08-10 07:41:24.955  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 07:41:24.956  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:24.959  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:24.960  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:24.961  8240  8288 V FormManager: Network unavailable.
08-10 07:41:24.965  4638  8289 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 07:41:24.969  4638  8290 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-10 07:41:24.969  4638  8290 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-10 07:41:25.021  1037  1926 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8291 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-10 07:41:25.048   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 24.530ms,
,08-10 07:41:25.069   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 414us total 19.821ms
,08-10 07:41:25.087   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 376us total 18.462ms
,08-10 07:41:25.132  8291  8291 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-10 07:41:25.132  8291  8291 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-10 07:41:25.142  8291  8291 V [BNRBootReceiver]: Boot Receiver Return
,08-10 07:41:25.143  8291  8291 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-10 07:41:25.227  1037  1879 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8309 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 07:41:25.229  1037  1879 I ActivityManager: Killing 7408:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-10 07:41:25.285  1037  1925 W libprocessgroup: failed to open /acct/uid_10085/pid_7408/cgroup.procs: No such file or directory
,08-10 07:41:25.311  8309  8309 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 07:41:25.348  8309  8309 D PluginManager: init()
,08-10 07:41:25.427  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-10 07:41:25.428  8223  8223 E wpa_supplicant: USIM:  scard_init function
08-10 07:41:25.428  1037  8262 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-10 07:41:25.428  8223  8223 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-10 07:41:25.428  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-10 07:41:25.428  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-10 07:41:25.428  1037  8262 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-10 07:41:25.428  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-10 07:41:25.429  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-10 07:41:25.431  1037  1541 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 07:41:25.432  1037  1541 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 07:41:25.433  1037  1541 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 07:41:25.434  1037  1541 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-10 07:41:25.435  1037  1541 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-10 07:41:25.446  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=346691  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-10 07:41:25.449  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=346693  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-10 07:41:25.454  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-10 07:41:25.454  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 07:41:25.455  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:25.458  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.458  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.458  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 07:41:25.459  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:25.459  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-10 07:41:25.545  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-10 07:41:25.546  8223  8223 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-10 07:41:25.546  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-10 07:41:25.546  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-10 07:41:25.546  1037  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-10 07:41:25.547  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-10 07:41:25.554  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=346799  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 07:41:25.555  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=346800  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-10 07:41:25.555  1037  1541 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:25.556  1037  1541 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:25.556  1037  1541 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:25.556  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:25.557  1037  1541 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-10 07:41:25.557  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:25.558  1037  1037 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-10 07:41:25.558  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:25.558  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:25.558  1037  1541 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=346803
08-10 07:41:25.559  1037  1541 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=346804
08-10 07:41:25.559  1037  1541 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=346804
08-10 07:41:25.560  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=346804
08-10 07:41:25.560  1037  1541 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=346805
08-10 07:41:25.560  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=346805  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 07:41:25.563  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.563  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.563  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-10 07:41:25.563  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:25.563  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:25.564  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=346808  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-10 07:41:25.565  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:25.570  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.570  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.570  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-10 07:41:25.570  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:25.570  1037  1037 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-10 07:41:25.572  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:25.572  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:25.573  8223  8223 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 07:41:25.573  1037  1541 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=346817  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 07:41:25.573  8223  8223 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 07:41:25.574  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-10 07:41:25.574  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 07:41:25.574  1037  8262 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-10 07:41:25.574  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-10 07:41:25.574  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 07:41:25.574  1037  8262 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-10 07:41:25.574  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:25.574  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:25.575  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=346820  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-10 07:41:25.576  1037  1541 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=346821
08-10 07:41:25.576  1037  1541 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=346821
,08-10 07:41:25.577  1037  1541 D WifiNative-wlan0: doString: [STATUS]
08-10 07:41:25.577  1037  8262 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-10 07:41:25.577  1037  8262 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-10 07:41:25.580  1037  1541 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-10 07:41:25.581  1037  1541 I WifiServiceExtension: setVHTCapabilityType  : false
08-10 07:41:25.588  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:25.588  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-10 07:41:25.590  1037  1541 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-10 07:41:25.590  1037  1541 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-10 07:41:25.594  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.595  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.595  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 07:41:25.595  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.595  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.595  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-10 07:41:25.598  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:25.600  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:25.600  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:25.600  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:25.604  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:25.604  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:25.604  1037  1541 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-10 07:41:25.604  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 07:41:25.604  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-10 07:41:25.604  1037  1547 D ConnectivityService: Got NetworkAgent Messenger
08-10 07:41:25.604  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 07:41:25.604  1037  1547 D ConnectivityService: NetworkAgent connected
08-10 07:41:25.605  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 07:41:25.605  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 07:41:25.605  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:25.614  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 07:41:25.615  1037  1541 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 07:41:25.615  1037  1541 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-10 07:41:25.617  1037  1541 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-10 07:41:25.617  1037  1541 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-10 07:41:25.621  1037  1541 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-10 07:41:25.623   310   895 D CommandListener: Setting iface cfg
08-10 07:41:25.625  1037  1541 E WifiStateMachine: Start Dhcp Watchdog 3
08-10 07:41:25.625  1037  8334 D DhcpStateMachine: StoppedState
08-10 07:41:25.625  1037  8334 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:25.625  1037  8334 D DhcpStateMachine: WaitBeforeStartState
08-10 07:41:25.626  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=346870  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:25.626  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=346871  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:25.627  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=346871  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:25.627  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:25.627  1037  1037 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-10 07:41:25.627  1037  1541 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=346872  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:25.628  1037  1541 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=346873  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:25.628  1037  1541 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=346873  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-10 07:41:25.629  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14155] from screen [on:0 period:1928870397] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 07:41:25.630  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1928870398] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 07:41:25.630  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 07:41:25.635  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:25.635  1037  1547 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-10 07:41:25.636  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.636  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.636  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.637  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.637  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.638  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.638  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-10 07:41:25.638  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=152,0,0
08-10 07:41:25.638  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=152,0,0
08-10 07:41:25.639  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-10 07:41:25.639  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-10 07:41:25.639  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-10 07:41:25.639  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 0
08-10 07:41:25.640  1037  1541 D WifiNative-wlan0: SET ps 0: returned true
08-10 07:41:25.640  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-10 07:41:25.640  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-10 07:41:25.640  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-10 07:41:25.641  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@17be8372 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:25.641  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@17be8372 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:25.641  1037  8334 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:25.641  1037  8334 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-10 07:41:25.641  1037  1541 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-10 07:41:25.641  1037  1541 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 07:41:25.641  1037  1541 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 07:41:25.642   310   895 D CommandListener: Setting iface cfg
08-10 07:41:25.642   310   895 D CommandListener: Trying to bring up wlan0
08-10 07:41:25.643  1037  1541 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-10 07:41:25.643  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:25.643  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-10 07:41:25.645  1037  1037 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-10 07:41:25.645  1037  1037 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-10 07:41:25.645  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.646  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.646  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.646  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.647  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.647  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-10 07:41:25.647  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-10 07:41:25.648  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 07:41:25.648  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-10 07:41:25.648  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-10 07:41:25.648  1037  1539 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-10 07:41:25.648  1037  1539 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:25.648  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-10 07:41:25.649  1037  1541 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-10 07:41:25.649  1037  1541 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-10 07:41:25.649  8223  8223 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-10 07:41:25.650  1037  1541 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-10 07:41:25.650  1037  1541 D WifiNative-wlan0: doBoolean: SET ps 1
08-10 07:41:25.666  1037  1541 D WifiNative-wlan0: SET ps 1: returned true
08-10 07:41:25.666  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-10 07:41:25.667  1037  1541 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 07:41:25.667  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-10 07:41:25.667  1037  1541 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-10 07:41:25.667  1037  1547 D ConnectivityService: ignoring duplicate network state non-change
08-10 07:41:25.670  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.670  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.670  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 07:41:25.670  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:25.670  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:25.671  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:25.674  1037  1547 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 07:41:25.675  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.675  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.675  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-10 07:41:25.675  1037  1547 D ConnectivityService: Adding iface wlan0 to network 102
08-10 07:41:25.676  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 07:41:25.678  1944  1944 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-10 07:41:25.679  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.679  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.679  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-10 07:41:25.680  1037  1037 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-10 07:41:25.683  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.683  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:25.683  1037  1037 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-10 07:41:25.684  1037  1541 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-10 07:41:25.690  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:25.690  1605  1605 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-10 07:41:25.691  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:25.692  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:25.692  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 07:41:25.692  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:25.694  1605  1605 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:25.694  1605  1605 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-10 07:41:25.694  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:25.714  1037  1547 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-10 07:41:25.714  1037  1547 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-10 07:41:25.716  1037  1547 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-10 07:41:25.716   310   895 E Netd    : netlink response contains error (File exists)
08-10 07:41:25.717  1037  1547 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-10 07:41:25.718  1037  1547 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-10 07:41:25.718  1037  1547 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-10 07:41:25.718  1037  1547 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-10 07:41:25.719  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-10 07:41:25.719  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-10 07:41:25.719  1037  1547 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-10 07:41:25.719  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-10 07:41:25.719  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 07:41:25.719  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:25.719  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 07:41:25.719  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.719  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-10 07:41:25.720  1037  1547 D ConnectivityService: currentScore = 0, newScore = 20
08-10 07:41:25.720  1037  1547 D ConnectivityService:    accepting network in place of null
08-10 07:41:25.720  1037  1547 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.721  1037  8329 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:25.721  1037  8329 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-10 07:41:25.721  1037  8329 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-10 07:41:25.721  1037  8329 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-10 07:41:25.721  1037  1547 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-10 07:41:25.721  1037  1547 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-10 07:41:25.721  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,_IMMEDIATE
08-10 07:41:25.721  1037  1547 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:25.722  1037  1547 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-10 07:41:25.722  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.722  1037  1547 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-10 07:41:25.722  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 07:41:25.723  1037  1541 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.723  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 07:41:25.723   310  8339 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-10 07:41:25.723  1037  1547 D ConnectivityService: validation of new default Network = false
08-10 07:41:25.723  1037  1547 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-10 07:41:25.723  1037  1547 D DSQN    : enableDataServiceNotify 
08-10 07:41:25.723  1037  1547 D DSQN    : start dsqn bin
08-10 07:41:25.724  1037  1037 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-10 07:41:25.725  1037  1037 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-10 07:41:25.725  1037  1037 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-10 07:41:25.725  1037  1037 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-10 07:41:25.720  8340  8340 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:25.720  8340  8340 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:25.728  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-10 07:41:25.728  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.728  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:25.729  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:25.731  1037  1538 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-10 07:41:25.732  1605  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 07:41:25.741  8340  8340 E DSQN    : DSQN ssw
08-10 07:41:25.752  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 07:41:25.753  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-10 07:41:25.754  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:25.775   310  8339 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-10 07:41:25.793  8309  8309 W ExternalStrings: load override strings
08-10 07:41:25.793  8309  8309 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:25.793  8309  8309 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-10 07:41:25.796  8309  8309 D StatusProvider: onCreate
08-10 07:41:25.813   310  8339 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-10 07:41:25.830   310   894 D LGDataListener: argv[0]=dsqncommand
08-10 07:41:25.830   310   894 D LGDataListener: argv[1]=wlan0
08-10 07:41:25.830   310   894 D LGDataListener: argv[2]=1
08-10 07:41:25.830   310   894 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-10 07:41:25.832  1037  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-10 07:41:25.832  1037  1117 D DSQN    : start to monitor internet connection
08-10 07:41:25.836  1037  8329 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 05:41:25 GMT], X-Android-Received-Millis=[1470807685836], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470807685829]}
08-10 07:41:25.837  1037  8329 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-10 07:41:25.837  1037  8329 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-10 07:41:25.839  1037  1547 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-10 07:41:25.839  1037  1547 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-10 07:41:25.839  1037  1547 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 07:41:25.839  1037  1547 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:25.839  1037  1547 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-10 07:41:25.839  1037  1547 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-10 07:41:25.839  1037  1547 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-10 07:41:25.839  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.840  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:25.840  1037  1547 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:25.840  1037  1547 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.841  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 07:41:25.842  1605  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-10 07:41:25.842  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.843  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-10 07:41:25.843  1037  1541 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-10 07:41:25.843  1037  1541 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-10 07:41:25.843  1037  8334 D DhcpStateMachine: DHCPV4 request on wlan0
08-10 07:41:25.845  1037  8334 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-10 07:41:25.845  1037  8334 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-10 07:41:25.840  8347  8347 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-10 07:41:25.840  8347  8347 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-10 07:41:25.864  8347  8347 I dhcpcd  : version 5.5.6 starting
08-10 07:41:25.866  8347  8347 E dhcpcd  : get_duid: m
08-10 07:41:25.866  8347  8347 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-10 07:41:25.866  8347  8347 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-10 07:41:25.870  1605  1605 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-10 07:41:25.871  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:25.872  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:25.885  6960  7027 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 911)
08-10 07:41:25.885  6960  7027 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 911)
08-10 07:41:25.889  6960  7027 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 916)
08-10 07:41:25.889  7967  8064 D UEI.SmartControl: Internal timer expired: 3
08-10 07:41:25.889  7967  8064 D UEI.SmartControl: unbind internal service
,08-10 07:41:25.891  6960  7027 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-10 07:41:25.891  6960  7027 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 917)
08-10 07:41:25.893  7967  7967 D UEI.SmartControl: Service.onUnbind: IControl
08-10 07:41:25.893  7967  7967 D UEI.SmartControl: Service.onDestroy
08-10 07:41:25.893  7967  7967 D UEI.SmartControl: Lock is in USE false
08-10 07:41:25.893  7967  7967 D UEI.SmartControl: unbind internal service
08-10 07:41:25.894  7967  7967 D serial_port: close(fd = 24)
08-10 07:41:25.895  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:25.895  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@850d163 added. We now have 2 listener(s)
08-10 07:41:25.896  1037  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:25.898  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:25.898  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:25.898  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:25.899  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:25.899  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc78160 added. We now have 9 listener(s)
08-10 07:41:25.899  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:25.902  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 07:41:25.905  7967  7967 I UEI.SmartControl: Serial port is closed.
08-10 07:41:25.905  7967  7967 I UEI.SmartControl: Serial port is closed.
,08-10 07:41:25.905  7967  7967 D UEI.SmartControl: Blaster closed
08-10 07:41:25.905  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:25.905  7967  7967 D UEI.SmartControl: Shut down QS...
08-10 07:41:25.905  7967  7967 D UEI.SmartControl: Stopping QS lib
08-10 07:41:25.905  7967  7967 D UEI.SmartControl: QS lib stop result = true
08-10 07:41:25.905  7967  7967 D UEI.SmartControl: Stopped QS lib
08-10 07:41:25.905  7967  7967 D UEI.SmartControl: QS shutdown complete
08-10 07:41:25.911  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:25.911  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:25.911  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:25.911  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:25.911  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:25.911  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:25.911  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:25.911  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:25.913  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:25.914  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:41:25.914  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:25.915  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f43e6de added. We now have 3 listener(s)
08-10 07:41:25.915  8309  8309 V Signer  : override build config not found
08-10 07:41:25.915  8309  8309 D Signer  : value of property debug is false
08-10 07:41:25.916  1037  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:25.916  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:25.918  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:25.920  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:25.920  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:25.920  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:25.920  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:25.920  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df520bf added. We now have 10 listener(s)
08-10 07:41:25.920  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:25.921  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:25.921  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:25.921  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:25.922  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:25.922  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 07:41:25.922  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:25.922  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:25.922  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@850d163 removed from the list
08-10 07:41:25.922  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:25.922  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc78160 removed from the list
08-10 07:41:25.922  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:25.922  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:25.923  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:25.923  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:25.925  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:25.925  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:25.925  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:25.925  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fc78160 not in the list
08-10 07:41:25.925  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:25.925  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:25.926  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:25.926  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:25.926  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:25.926  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df520bf removed from the list
08-10 07:41:25.926  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:25.926  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:25.926  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:25.926  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:25.926  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f43e6de removed from the list
08-10 07:41:25.927  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:25.927  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1413538c added. We now have 2 listener(s)
08-10 07:41:25.928  1037  1897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:25.930  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth, MAC address: "58:3F:54:73:BA:17"
08-10 07:41:25.930  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:25.930  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:25.931  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:25.931  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f76ad5 added. We now have 9 listener(s)
08-10 07:41:25.931  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 07:41:25.935  8347  8347 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 07:41:25.935  8347  8347 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 07:41:25.935  8347  8347 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 07:41:25.935  8347  8347 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-10 07:41:25.935  8347  8347 D dhcpcd  : wlan0: sending REQUEST (xid 0xe57a64a9), next in 3.67 seconds
08-10 07:41:25.936  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 07:41:25.938  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:25.943  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:25.943  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:25.943  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:25.943  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:25.943  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:25.943  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:25.943  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:25.943  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:25.945  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:25.945  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 07:41:25.945  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:25.945  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@156509db added. We now have 3 listener(s)
08-10 07:41:25.946  1037  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:25.949  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:25.949  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:25.949  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:25.949  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:25.949  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:25.949  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f681c78 added. We now have 10 listener(s)
,08-10 07:41:25.949  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:25.949  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 07:41:25.949  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 07:41:25.949  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 07:41:25.950  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:25.950  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 07:41:25.955  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 07:41:25.955  1037  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:25.955  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:25.961  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 07:41:25.961  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 07:41:25.965  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 07:41:25.965  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:25.968  6960  7027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 07:41:25.968  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:25.968  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:25.971  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:25.971  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:25.971  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 07:41:25.971  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:25.971  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:25.971  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:25.971  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:25.971  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1413538c removed from the list
08-10 07:41:25.971  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 07:41:25.971  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f76ad5 removed from the list
08-10 07:41:25.971  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:25.971  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:25.972  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:25.972  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:25.973  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:25.973  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:25.973  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:25.973  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f76ad5 not in the list
08-10 07:41:25.973  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:25.973  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:25.973  8347  8347 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-10 07:41:25.974  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:25.975  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:25.975  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:25.975  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:25.975  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:25.975  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f681c78 removed from the list
08-10 07:41:25.975  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:25.975  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 07:41:25.975  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:25.975  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:25.975  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@156509db removed from the list
08-10 07:41:25.976  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:25.976  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372068b7 added. We now have 2 listener(s)
08-10 07:41:25.976  1037  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:25.979  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-10 07:41:25.979  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:25.979  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:25.979  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:25.979  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:25.979  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-10 07:41:25.979  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3e8824 added. We now have 9 listener(s)
08-10 07:41:25.979  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:25.980  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-10 07:41:25.980  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 07:41:25.980  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-10 07:41:25.980  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-10 07:41:25.980  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-10 07:41:25.981  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-10 07:41:25.981  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-10 07:41:25.981  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-10 07:41:25.981  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-10 07:41:25.982  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-10 07:41:25.982  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:25.983  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-10 07:41:25.983  8309  8309 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-10 07:41:25.986  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:25.986  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:25.986  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:25.986  6960,  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:25.986  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:25.986  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:25.986  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:25.986  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:25.988  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:25.988  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:41:25.989  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:25.989  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2f9542 added. We now have 3 listener(s)
08-10 07:41:25.989  1037  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 07:41:25.992  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:25.993  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:25.993  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:25.993  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:25.993  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:25.993  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c8d953 added. We now have 10 listener(s)
08-10 07:41:25.993  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:25.993  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 07:41:25.994  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:25.994  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 07:41:25.994  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 07:41:25.994  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 07:41:25.994  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:25.994  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 07:41:26.002  8309  8309 V LGMDMManager: Create singleton instance
,08-10 07:41:26.002  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 07:41:26.003  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:26.007  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 07:41:26.008  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 07:41:26.010  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 07:41:26.011  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:26.012  8347  8347 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-10 07:41:26.013  6960  7027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-10 07:41:26.013  8347  8347 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-10 07:41:26.013  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:26.013  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:26.013  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:26.013  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:26.013  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.013  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:26.013  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:26.013  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372068b7 removed from the list
08-10 07:41:26.013  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.013  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3e8824 removed from the list
08-10 07:41:26.013  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:26.013  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.013  8347  8347 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-10 07:41:26.014  8347  8347 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-10 07:41:26.014  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.014  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.014  8347  8347 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-10 07:41:26.015  8347  8347 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-10 07:41:26.016  8347  8347 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-10 07:41:26.016  8347  8347 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-10 07:41:26.022  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:26.022  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:26.023  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.023  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3e8824 not in the list
,08-10 07:41:26.023  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.023  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.023  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:26.024  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:26.024  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:26.024  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:26.024  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.024  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c8d953 removed from the list
08-10 07:41:26.024  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 07:41:26.024  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.024  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.024  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:26.024  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2f9542 removed from the list
08-10 07:41:26.025  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:26.025  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f25c38e added. We now have 2 listener(s),
08-10 07:41:26.025  1037  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:26.028  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:26.028  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:26.028  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-10 07:41:26.028  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:26.028  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27db7af added. We now have 9 listener(s)
08-10 07:41:26.028  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:26.029  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 07:41:26.034  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:26.037  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:26.037  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:26.037  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:26.037  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:26.037  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:26.037  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:26.037  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:26.037  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:26.038  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:26.038  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 07:41:26.040  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:26.040  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14a9b345 added. We now have 3 listener(s)
08-10 07:41:26.040  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:26.041  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 07:41:26.042  1037  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:26.044  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:26.044  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:26.044  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:26.044  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:26.044  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d3e8a9a added. We now have 10 listener(s)
08-10 07:41:26.044  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:26.044  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 07:41:26.044  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 07:41:26.044  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 07:41:26.044  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:26.044  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 07:41:26.048  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 07:41:26.048  1037  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:26.052  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 07:41:26.053  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 07:41:26.054  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 07:41:26.056  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:26.058  6960  7027 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 07:41:26.060  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:26.060  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:26.060  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:26.060  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:26.060  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.060  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:26.060  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:26.060  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f25c38e removed from the list
08-10 07:41:26.060  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.060  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27db7af removed from the list
08-10 07:41:26.060  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:26.060  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.060  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.060  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.061  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:26.061  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:26.061  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.061  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27db7af not in the list
08-10 07:41:26.061  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.061  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.062  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:26.062  6960  7027 D BluetoothLeScanner: could not find callback wrapper
08-10 07:41:26.062  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 07:41:26.062  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:26.062  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.062  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d3e8a9a removed from the list
08-10 07:41:26.062  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:26.062  6960  7027 W org.thaliproject.p2p.btcon,nectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.062  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.062  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:26.062  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14a9b345 removed from the list
08-10 07:41:26.063  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:26.063  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f373ec1 added. We now have 2 listener(s)
08-10 07:41:26.063  1037  1649 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:26.065  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:26.065  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:26.065  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:26.065  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:26.065  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eab666 added. We now have 9 listener(s)
08-10 07:41:26.065  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:26.066  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 07:41:26.068  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 07:41:26.071  6960  7027 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 07:41:26.071  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:26.071  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:26.071  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:26.071  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:26.071  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:26.071  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:26.071  6960  7027 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:26.079  6960  7027 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:26.079  6960  7027 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 07:41:26.079  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 07:41:26.079  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664254 added. We now have 3 listener(s)
08-10 07:41:26.080  1037  1997 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 07:41:26.082  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-10 07:41:26.082  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:26.082  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 07:41:26.082  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 07:41:26.082  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 07:41:26.082  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17b805fd added. We now have 10 listener(s)
08-10 07:41:26.083  6960  7027 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 07:41:26.083  6960  7027 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 07:41:26.083  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:26.083  6960  7027 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 07:41:26.083  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:26.083  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.083  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 07:41:26.083  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:26.083  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f373ec1 removed from the list
08-10 07:41:26.083  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.083  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eab666 removed from the list
08-10 07:41:26.084  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 07:41:26.084  6960  7027 D io.jxcore.node.ConnectivityMonitor: stop
08-10 07:41:26.084  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.084  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.084  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.085  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:26.085  6960  7027 I org.thaliproject.p2p.btconnecto,rlib.DiscoveryManager: stopDiscovery
08-10 07:41:26.085  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.085  6960  7027 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9eab666 not in the list
08-10 07:41:26.085  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.086  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.087  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 07:41:26.087  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 07:41:26.087  6960  7027 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 07:41:26.087  6960  7027 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17b805fd removed from the list
08-10 07:41:26.087  6960  7027 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 07:41:26.087  6960  7027 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 07:41:26.087  6960  7027 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 07:41:26.087  6960  7027 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 07:41:26.087  6960  7027 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f664254 removed from the list
08-10 07:41:26.088  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-10 07:41:26.088  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-10 07:41:26.088  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-10 07:41:26.089  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 07:41:26.089  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-10 07:41:26.089  6960  7027 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 07:41:26.095  8309  8309 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-10 07:41:26.102  6960  8363 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 924, name: My test thread name)
08-10 07:41:26.102  6960  8363 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 924, thread name: My test thread name)
08-10 07:41:26.102  6960  8363 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 924, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 07:41:26.106  6960  8365 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 926, name: My test thread name)
08-10 07:41:26.106  6960  8365 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 926, thread name: My test thread name)
08-10 07:41:26.106  6960  8365 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 926, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 07:41:26.107  6960  7027 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-10 07:41:26.107  6960  7027 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-10 07:41:26.107  6960  7027 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-10 07:41:26.108  6960  7027 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-10 07:41:26.108  6960  7027 D com.test.thalitest.ThaliTestRunner: Total duration: 23014 ms
08-10 07:41:26.109  6960  7027 I jxcore-log: Total number of executed tests:  80
08-10 07:41:26.109  6960  7027 I jxcore-log: 
08-10 07:41:26.109  6960  7027 I jxcore-log: Number of passed tests:  80
08-10 07:41:26.109  6960  7027 I jxcore-log: 
08-10 07:41:26.109  6960  7027 I jxcore-log: Number of failed tests:  0
08-10 07:41:26.109  6960  7027 I jxcore-log: 
08-10 07:41:26.109  6960  7027 I jxcore-log: Number of ignored tests:  0
08-10 07:41:26.109  6960  7027 I jxcore-log: 
08-10 07:41:26.109  6960  7027 I jxcore-log: Total duration:  23014
08-10 07:41:26.109  6960  7027 I jxcore-log: 
08-10 07:41:26.111  6960  7027 I jxcore-log: Unit Test app is loaded
08-10 07:41:26.111  6960  7027 I jxcore-log: 
,08-10 07:41:26.124  6960  6960 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-10 07:41:26.125  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.125  6960  7027 I jxcore-log: 
,08-10 07:41:26.129  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.129  6960  7027 I jxcore-log: 
08-10 07:41:26.130  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.130  6960  7027 I jxcore-log: 
08-10 07:41:26.131  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.131  6960  7027 I jxcore-log: 
08-10 07:41:26.132  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.132  6960  7027 I jxcore-log: 
08-10 07:41:26.134  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.134  6960  7027 I jxcore-log: 
08-10 07:41:26.137  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 07:41:26.137  6960  7027 I jxcore-log: 
08-10 07:41:26.139  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 07:41:26.139  6960  7027 I jxcore-log: 
08-10 07:41:26.140  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.140  6960  7027 I jxcore-log: 
08-10 07:41:26.140  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.140  6960  7027 I jxcore-log: 
08-10 07:41:26.141  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 07:41:26.141  6960  7027 I jxcore-log: 
08-10 07:41:26.143  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 07:41:26.143  6960  7027 I jxcore-log: 
,08-10 07:41:26.144  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 07:41:26.144  6960  7027 I jxcore-log: 
08-10 07:41:26.145  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.145  6960  7027 I jxcore-log: 
08-10 07:41:26.146  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.146  6960  7027 I jxcore-log: 
08-10 07:41:26.146  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.146  6960  7027 I jxcore-log: 
08-10 07:41:26.147  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.147  6960  7027 I jxcore-log: 
08-10 07:41:26.148  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.148  6960  7027 I jxcore-log: 
08-10 07:41:26.149  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.149  6960  7027 I jxcore-log: 
08-10 07:41:26.149  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.149  6960  7027 I jxcore-log: 
08-10 07:41:26.150  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 07:41:26.150  6960  7027 I jxcore-log: 
08-10 07:41:26.151  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 07:41:26.151  6960  7027 I jxcore-log: 
08-10 07:41:26.152  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 07:41:26.152  6960  7027 I jxcore-log: 
08-10 07:41:26.152  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.152  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.153  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.153  6960  7027 I jxcore-log: 
08-10 07:41:26.154  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.154  6960  7027 I jxcore-log: 
,08-10 07:41:26.154  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.154  6960  7027 I jxcore-log: 
08-10 07:41:26.155  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.155  6960  7027 I jxcore-log: 
08-10 07:41:26.156  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:26.156  6960  7027 I jxcore-log: 
08-10 07:41:26.159  6960  7027 I jxcore-log: My device name is: LGE-LG-D855
08-10 07:41:26.159  6960  7027 I jxcore-log: 
08-10 07:41:26.166  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:26.170  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.218  1037  1578 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8381 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-10 07:41:26.218  1037  1578 I ActivityManager: Killing 7442:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-10 07:41:26.250  1037  8334 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-10 07:41:26.251  1037  8334 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-10 07:41:26.251  1037  8334 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-10 07:41:26.251  1037  8334 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-10 07:41:26.251  1037  8334 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-10 07:41:26.251  1037  8334 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-10 07:41:26.251  1037  8334 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-10 07:41:26.251  1037  8334 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-10 07:41:26.251  1037  8334 D DhcpStateMachine: RunningState
,08-10 07:41:26.306  8309  8370 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-10 07:41:26.484  1037  1954 W libprocessgroup: failed to open /acct/uid_10093/pid_7442/cgroup.procs: No such file or directory
,08-10 07:41:26.544  8381  8381 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 07:41:26.572  8381  8381 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-10 07:41:26.611  8381  8381 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-10 07:41:26.611  8381  8381 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-10 07:41:26.611  8381  8381 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-10 07:41:26.612  8381  8381 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-10 07:41:26.612  8381  8381 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-10 07:41:26.614  8381  8381 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-10 07:41:26.615  8309  8370 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:26.615  8309  8370 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 07:41:26.620  8381  8381 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-10 07:41:26.629  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:26.634  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:26.648  8381  8381 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 07:41:26.650  8381  8381 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-10 07:41:26.650  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.650  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.656  8381  8381 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-10 07:41:26.658  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:26.663  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.669  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:26.670  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:26.672  8381  8381 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-10 07:41:26.674  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-10 07:41:26.677  7062  7062 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-10 07:41:26.679  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.680  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.688  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 07:41:26.692  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.698  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:26.698  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:26.699  8381  8381 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:26.702  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-10 07:41:26.702  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-10 07:41:26.702  7062  7062 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-10 07:41:26.702  7062  7062 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-10 07:41:26.703  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-10 07:41:26.703  7062  7062 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-10 07:41:26.703  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-10 07:41:26.703  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-10 07:41:26.704  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-10 07:41:26.704  7062  7062 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-10 07:41:26.704  7062  7062 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-10 07:41:26.704  7062  7062 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-10 07:41:26.706  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.707  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.713  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 07:41:26.725  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.729  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:26.729  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:26.730  8381  8381 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 07:41:26.732  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.733  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.736  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 07:41:26.739  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.743  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:26.743  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:26.743  8381  8381 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-10 07:41:26.746  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.746  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.751  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:26.756  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.761  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:26.761  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:26.762  8381  8381 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:26.764  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.764  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.767  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:26.773  8309  8370 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-10 07:41:26.787  8309  8370 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-10 07:41:26.793  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-10 07:41:26.801  8309  8370 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-10 07:41:26.802  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:26.802  8309  8370 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-10 07:41:26.803  8309  8370 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-10 07:41:26.803  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:26.803  8309  8370 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-10 07:41:26.804  8309  8370 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-10 07:41:26.804  8381  8381 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:26.809  8309  8370 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-10 07:41:26.811  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.812  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.816  8309  8370 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-10 07:41:26.825  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-10 07:41:26.831  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.838  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:26.839  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-10 07:41:26.845  8381  8381 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:26.849  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.849  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.856  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:26.864  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.876  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-10 07:41:26.877  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:26.879  8381  8381 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-10 07:41:26.883  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.883  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.887  8263  8263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 07:41:26.891  8263  8263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:26.894  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:26.904  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.911  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:26.911  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:26.913  8381  8381 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 07:41:26.916  8381  8381 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 07:41:26.917  8381  8381 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-10 07:41:26.924  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:26.924  8309  8371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-10 07:41:26.929  8263  8263 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-10 07:41:26.930  8263  8263 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-10 07:41:26.933  7062  7062 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-10 07:41:26.944  7062  7062 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-10 07:41:26.953  8381  8381 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-10 07:41:26.953  8381  8381 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-10 07:41:26.954  8381  8381 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-10 07:41:26.955  8381  8381 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-10 07:41:26.955  8381  8381 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-10 07:41:26.960  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:27.002  8381  8381 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-10 07:41:27.004  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-10 07:41:27.004  8381  8381 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-10 07:41:27.044  8381  8381 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:27.044  8381  8381 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:27.052  8381  8381 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-10 07:41:27.054  8381  8381 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-10 07:41:27.054  8381  8381 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-10 07:41:27.054  8381  8381 V SoundPool: doLoad: loading sample sampleID=1
08-10 07:41:27.054  8381  8381 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 07:41:27.056  8381  8425 V SoundPool: Start decode
08-10 07:41:27.056  8381  8425 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-10 07:41:27.057   315  2146 V MediaPlayerService: decode(23, 10857164, 17813)
08-10 07:41:27.057   315  2146 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-10 07:41:27.057   315  2146 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-10 07:41:27.057   315  2146 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-10 07:41:27.058   315  2146 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-10 07:41:27.058   315  2146 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-10 07:41:27.058   315  2146 V MediaPlayerService: player type = 3
08-10 07:41:27.058   315  2146 V AwesomePlayer: AwesomePlayer create()
08-10 07:41:27.058   315  2146 V AwesomePlayer: reset_l() 
08-10 07:41:27.058   315  2146 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:27.058   315  2146 V AwesomePlayer: setAudioSink() 
08-10 07:41:27.058   315  2146 V AwesomePlayer: reset_l() 
08-10 07:41:27.058   315  2146 V AudioCache: notify(0xb100e4c0, 8, 0, 0)
08-10 07:41:27.058   315  2146 V AudioCache: ignored
08-10 07:41:27.058   315  2146 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:27.058   315  2146 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-10 07:41:27.058   315  2146 V AwesomePlayer: setDataSource_l dataSource
,08-10 07:41:27.058   315  2146 V LGParserOSAL: SniffLGParser start
,08-10 07:41:27.058   315  2146 V LGParserOSAL: MainType:5, SubType=0
08-10 07:41:27.058   315  2146 V LGParserOSAL: #### check Mime : application/ogg
08-10 07:41:27.058   315  2146 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
,08-10 07:41:27.058   315  2146 E MediaExtractor: Use LGExtractor :application/ogg 
08-10 07:41:27.062  7967  7967 D UEI.SmartControl: QS Service created
,08-10 07:41:27.069  8381  8381 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-10 07:41:27.074  8381  8381 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 07:41:27.074  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 07:41:27.091  7967  7967 I UEI.SmartControl: Service initServices...
08-10 07:41:27.091  7967  7967 D UEI.SmartControl: QS start get config
,08-10 07:41:27.097   315  2146 V LGParserOSAL: supported mime: application/ogg
08-10 07:41:27.097   315  2146 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-10 07:41:27.097   315  2146 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-10 07:41:27.097   315  2146 V AwesomePlayer: mBitrate = -1 bits/sec
,08-10 07:41:27.097   315  2146 V AwesomePlayer: AudioTrack Setting
08-10 07:41:27.097   315  2146 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-10 07:41:27.097   315  2146 V AwesomePlayer: setAudioSource() 
08-10 07:41:27.097   315  2146 V MediaPlayerService: prepare
08-10 07:41:27.097   315  2146 V AwesomePlayer: prepareAsync_l() 
08-10 07:41:27.097   315  2146 V MediaPlayerService: wait for prepare
08-10 07:41:27.097   315  8426 V AwesomePlayer: onPrepareAsyncEvent() 
08-10 07:41:27.097   315  8426 V AwesomePlayer: initAudioDecoder() 
08-10 07:41:27.097   315  8426 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 07:41:27.097   315  8426 V AudioSystem: isOffloadSupported()
08-10 07:41:27.097   315  8426 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 07:41:27.097   315  8426 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 07:41:27.097   315  8426 I AudioFlinger: isAudioPlaybackHookOn() false
08-10 07:41:27.098   315  8426 V AwesomePlayer: getUseOffload() = 0 
08-10 07:41:27.098   315  8426 V OMXCodec: OMXCodec::Create
08-10 07:41:27.098   315  8426 V OMXCodec: findMatchingCodecs()
08-10 07:41:27.098   315  8426 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-10 07:41:27.098   315  8426 V OMXCodec: matchingCodecs.size()=1
08-10 07:41:27.098   315  8426 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-10 07:41:27.099   315  8426 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-10 07:41:27.099   315  8426 V LGCodecAdapter: LG Codec Adapter start
08-10 07:41:27.099   315  8426 V OMXCodec: OMXCodec Createtor
08-10 07:41:27.099   315  8426 V OMXCodec: setComponentRole
08-10 07:41:27.099   315  8426 V OMXCodec: configureCodec protected=0
08-10 07:41:27.099   315  8426 V LGCodecAdapter: called getLGCodecSpecificData
08-10 07:41:27.099   315  8426 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-10 07:41:27.099   315  8426 V LGCodecOSAL: Called LGconfigureCodecMETA
08-10 07:41:27.099   315  8426 V LGCodecOSAL: Called LGconfigureCodecMSG
08-10 07:41:27.100   315  8426 V LGCodecOSAL: Not support LGCodec
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 07:41:27.100   315  8426 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-10 07:41:27.100   315  8426 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-10 07:41:27.100   315  8426 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-10 07:41:27.100   315  8426 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-10 07:41:27.100   315  8426 V AudioSystem: isOffloadSupported()
08-10 07:41:27.100   315  8426 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-10 07:41:27.100   315  8426 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-10 07:41:27.100   315  8426 V OMXCodec: init()
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-10 07:41:27.100   315  8426 V OMXCodec: allocateBuffers
08-10 07:41:27.100   315  8426 V OMXCodec: allocateBuffersOnPort portIndex=0
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorb,is.decoder] allocated buffer 0xb54f7bf0 on input port
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on input port
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ec0 on input port
08-10 07:41:27.100   315  8426 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cb380 on output port
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cb420 on output port
08-10 07:41:27.100   315  8426 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cb4c0 on output port
08-10 07:41:27.100   315  8426 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 07:41:27.101   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 07:41:27.101   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 07:41:27.101   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-10 07:41:27.101   315  8426 V OMXCodec: init() mAsyncCompletion wait!!! 
08-10 07:41:27.101   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-10 07:41:27.101   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-10 07:41:27.101   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-10 07:41:27.101   315  8426 V OMXCodec: init() mAsyncCompletion wait free! 
08-10 07:41:27.101   315  8426 V AwesomePlayer: finishAsyncPrepare_l() 
08-10 07:41:27.101   315  8426 V AudioCache: notify(0xb100e4c0, 5, 0, 0)
08-10 07:41:27.101   315  8426 V AudioCache: ignored
08-10 07:41:27.101   315  8426 V AudioCache: notify(0xb100e4c0, 1, 0, 0)
08-10 07:41:27.101   315  8426 V AudioCache: prepared
08-10 07:41:27.101   315  2146 V AudioCache: wait - success
08-10 07:41:27.101   315  2146 V MediaPlayerService: start
08-10 07:41:27.101   315  2146 V AwesomePlayer: play_l() 
08-10 07:41:27.101   315  2146 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-10 07:41:27.101   315  2146 V AwesomePlayer: createAudioPlayer_l
08-10 07:41:27.101   315  2146 V AwesomePlayer: seekAudioIfNecessary_l() 
08-10 07:41:27.101   315  2146 V AwesomePlayer: startAudioPlayer_l() 
08-10 07:41:27.101   315  2146 D AudioPlayer: start of Playback, useOffload 0
08-10 07:41:27.101   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,08-10 07:41:27.101   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-10 07:41:27.102  8381  8381 V LGMDMManager: Create singleton instance
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044848512
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044848672
,08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044848832
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:27.104   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-10 07:41:27.105   315  8428 V OMXCodec: allocateBuffersOnPort portIndex=1
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cb420 on output port
,08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cb380 on output port
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57cb740 on output port
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-10 07:41:27.105   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,08-10 07:41:27.108   315  2146 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-10 07:41:27.111   315  2146 V AudioCache: notify(0xb100e4c0, 6, 0, 0)
08-10 07:41:27.111   315  2146 V AudioCache: ignored
08-10 07:41:27.112   315  2146 V MediaPlayerService: wait for playback complete
08-10 07:41:27.112   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.112   315  8429 V AudioCache: memcpy(0xabf08000, 0xb17f9000, 4096)
08-10 07:41:27.113   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.113   315  8429 V AudioCache: memcpy(0xabf09000, 0xb17f9000, 4096)
08-10 07:41:27.113   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.113   315  8429 V AudioCache: memcpy(0xabf0a000, 0xb17f9000, 4096)
08-10 07:41:27.114   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.114   315  8429 V AudioCache: memcpy(0xabf0b000, 0xb17f9000, 4096)
08-10 07:41:27.114   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.114   315  8429 V AudioCache: memcpy(0xabf0c000, 0xb17f9000, 4096)
08-10 07:41:27.114   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.114   315  8429 V AudioCache: memcpy(0xabf0d000, 0xb17f9000, 4096)
08-10 07:41:27.115   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.115   315  8429 V AudioCache: memcpy(0xabf0e000, 0xb17f9000, 4096)
08-10 07:41:27.115   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.115   315  8429 V AudioCache: memcpy(0xabf0f000, 0xb17f9000, 4096)
08-10 07:41:27.116   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.116   315  8429 V AudioCache: memcpy(0xabf10000, 0xb17f9000, 4096)
08-10 07:41:27.116   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.116   315  8429 V AudioCache: memcpy(0xabf11000, 0xb17f9000, 4096)
08-10 07:41:27.116   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.116   315  8429 V AudioCache: memcpy(0xabf12000, 0xb17f9000, 4096)
08-10 07:41:27.117   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.117   315  8429 V AudioCache: memcpy(0xabf13000, 0xb17f9000, 4096)
08-10 07:41:27.117   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.117   315  8429 V AudioCache: memcpy(0xabf14000, 0xb17f9000, 4096)
08-10 07:41:27.117   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.117   315  8429 V AudioCache: memcpy(0xabf15000, 0xb17f9000, 4096)
08-10 07:41:27.117   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.117   315  8429 V AudioCache: memcpy(0xabf16000, 0xb17f9000, 4096)
08-10 07:41:27.118   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.118   315  8429 V AudioCache: memcpy(0xabf17000, 0xb17f9000, 4096)
08-10 07:41:27.118   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.118   315  8429 V AudioCache: memcpy(0xabf18000, 0xb17f9000, 4096)
08-10 07:41:27.118   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.118   315  8429 V AudioCache: memcpy(0xabf19000, 0xb17f9000, 4096)
08-10 07:41:27.119   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.119   315  8429 V AudioCache: memcpy(0xabf1a000, 0xb17f9000, 4096)
08-10 07:41:27.119   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.119   315  8429 V AudioCache: memcpy(0xabf1b000, 0xb17f9000, 4096)
08-10 07:41:27.119   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.119   315  8429 V AudioCache: memcpy(0xabf1c000, 0xb17f9000, 4096)
08-10 07:41:27.119   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.119   315  8429 V AudioCache: memcpy(0xabf1d000, 0xb17f9000, 4096)
08-10 07:41:27.120   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.120   315  8429 V AudioCache: memcpy(0xabf1e000, 0xb17f9000, 4096)
08-10 07:41:27.120   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.120   315  8429 V AudioCache: memcpy(0xabf1f000, 0xb17f9000, 4096)
08-10 07:41:27.120   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.120   315  8429 V AudioCache: memcpy(0xabf20000, 0xb17f900,0, 4096)
08-10 07:41:27.120   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.120   315  8429 V AudioCache: memcpy(0xabf21000, 0xb17f9000, 4096)
08-10 07:41:27.121   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.121   315  8429 V AudioCache: memcpy(0xabf22000, 0xb17f9000, 4096)
08-10 07:41:27.121   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.121   315  8429 V AudioCache: memcpy(0xabf23000, 0xb17f9000, 4096)
08-10 07:41:27.121   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.121   315  8429 V AudioCache: memcpy(0xabf24000, 0xb17f9000, 4096)
08-10 07:41:27.121   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.121   315  8429 V AudioCache: memcpy(0xabf25000, 0xb17f9000, 4096)
08-10 07:41:27.132   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.132   315  8429 V AudioCache: memcpy(0xabf26000, 0xb17f9000, 4096)
08-10 07:41:27.133   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.133   315  8429 V AudioCache: memcpy(0xabf27000, 0xb17f9000, 4096)
08-10 07:41:27.133   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.133   315  8429 V AudioCache: memcpy(0xabf28000, 0xb17f9000, 4096)
,08-10 07:41:27.133   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.133   315  8429 V AudioCache: memcpy(0xabf29000, 0xb17f9000, 4096)
08-10 07:41:27.133   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.133   315  8429 V AudioCache: memcpy(0xabf2a000, 0xb17f9000, 4096)
08-10 07:41:27.134   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.134   315  8429 V AudioCache: memcpy(0xabf2b000, 0xb17f9000, 4096)
08-10 07:41:27.134   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.134   315  8429 V AudioCache: memcpy(0xabf2c000, 0xb17f9000, 4096)
08-10 07:41:27.134   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.134   315  8429 V AudioCache: memcpy(0xabf2d000, 0xb17f9000, 4096)
08-10 07:41:27.135   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.135   315  8429 V AudioCache: memcpy(0xabf2e000, 0xb17f9000, 4096)
08-10 07:41:27.135   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.135   315  8429 V AudioCache: memcpy(0xabf2f000, 0xb17f9000, 4096)
08-10 07:41:27.135   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.135   315  8429 V AudioCache: memcpy(0xabf30000, 0xb17f9000, 4096)
08-10 07:41:27.136   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.136   315  8429 V AudioCache: memcpy(0xabf31000, 0xb17f9000, 4096)
08-10 07:41:27.136   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.136   315  8429 V AudioCache: memcpy(0xabf32000, 0xb17f9000, 4096)
08-10 07:41:27.136   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.136   315  8429 V AudioCache: memcpy(0xabf33000, 0xb17f9000, 4096)
08-10 07:41:27.137   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.137   315  8429 V AudioCache: memcpy(0xabf34000, 0xb17f9000, 4096)
08-10 07:41:27.137   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.137   315  8429 V AudioCache: memcpy(0xabf35000, 0xb17f9000, 4096)
08-10 07:41:27.137   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.137   315  8429 V AudioCache: memcpy(0xabf36000, 0xb17f9000, 4096)
08-10 07:41:27.137   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.138   315  8429 V AudioCache: memcpy(0xabf37000, 0xb17f9000, 4096)
08-10 07:41:27.138   315  8429 V AudioCache: write(0xb17f9000, 4096)
,08-10 07:41:27.138   315  8429 V AudioCache: memcpy(0xabf38000, 0xb17f9000, 4096)
08-10 07:41:27.138   315  8429 V AudioCache: write(0xb17f9000, 4096)
08-10 07:41:27.138   315  8429 V AudioCache: memcpy(0xabf39000, 0xb17f9000, 4096)
08-10 07:41:27.138   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-10 07:41:27.138   315  8429 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-10 07:41:27.138   315  8429 V AwesomePlayer: postAudioEOS() 
08-10 07:41:27.138   315  8429 V AudioCache: write(0xb17f9000, 280)
08-10 07:41:27.138   315  8429 V AudioCache: memcpy(0xabf3a000, 0xb17f9000, 280)
08-10 07:41:27.140   315  8426 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-10 07:41:27.140   315  8426 V AwesomePlayer: onStreamDone
08-10 07:41:27.140   315  8426 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-10 07:41:27.140   315  8426 V AudioCache: notify(0xb100e4c0, 2, 0, 0)
08-10 07:41:27.140   315  8426 V AudioCache: playback complete
08-10 07:41:27.140   315  8426 V AwesomePlayer: pause_l() 
08-10 07:41:27.140   315  8426 V AudioCache: notify(0xb100e4c0, 7, 0, 0)
08-10 07:41:27.140   315  8426 V AudioCache: ignored
08-10 07:41:27.140   315  8426 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:27.140   315  8426 D AudioPlayer: Pause Playback at 1068125
08-10 07:41:27.140   315  2146 V AudioCache: wait - success
08-10 07:41:27.140   315  2146 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-10 07:41:27.140   315  2146 V AwesomePlayer: reset_l() 
08-10 07:41:27.141   315  2146 V AudioCache: notify(0xb100e4c0, 8, 0, 0)
08-10 07:41:27.141   315  2146 V AudioCache: ignored
08-10 07:41:27.141   315  2146 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:27.141   315  2146 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-10 07:41:27.141   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-10 07:41:27.141   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-10 07:41:27.141   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-10 07:41:27.141   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ec0 on port 0
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 0
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57cb740 on port 1
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57cb380 on port 1
08-10 07:41:27.141   315  8428 V, OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57cb420 on port 1
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-10 07:41:27.141   315  8428 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-10 07:41:27.141   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-10 07:41:27.141   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-10 07:41:27.142   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-10 07:41:27.143   315  2146 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-10 07:41:27.144   315  2146 D AudioPlayer: AudioPlayer releasing audio source
08-10 07:41:27.144   315  2146 D AudioPlayer: AudioPlayer done releasing audio source
08-10 07:41:27.144   315  2146 V AwesomePlayer: reset_l() 
08-10 07:41:27.144   315  2146 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:27.144   315  2146 V AwesomePlayer: ~AwesomePlayer call
08-10 07:41:27.144   315  2146 V AwesomePlayer: reset_l() 
08-10 07:41:27.144   315  2146 V AwesomePlayer: cancelPlayerEvents
08-10 07:41:27.145  8381  8425 V SoundPool: close(31)
08-10 07:41:27.145  8381  8425 V SoundPool: pointer = 0xa0034000, size = 205080, sampleRate = 48000, numChannels = 2
08-10 07:41:27.170  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 07:41:27.171  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-10 07:41:27.173  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5093
08-10 07:41:27.176  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.177  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.179  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.180  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.181  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.183  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-10 07:41:27.186  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.189  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.191  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.193  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-10 07:41:27.253  1037  1541 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 07:41:27.254  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 07:41:27.254  1037  1541 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 07:41:27.254  1037  1541 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-10 07:41:27.254  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 07:41:27.255  1037  1541 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-10 07:41:27.256  1037  1547 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-10 07:41:27.256  1037  1547 D ConnectivityService: identical MTU - not setting
08-10 07:41:27.256  1037  1547 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
,08-10 07:41:27.256  1037  1547 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-10 07:41:27.256  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 07:41:27.256  1037  1547 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:27.256  1037  1547 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-10 07:41:27.257  1605  2051 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-10 07:41:27.343  7967  7967 I UEI.SmartControl: Supports setup maps: true
08-10 07:41:27.346  7967  7967 D UEI.SmartControl: QS start statue = true Error code = 0
,08-10 07:41:27.346  7967  7967 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 07:41:27.346  7967  7967 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 07:41:27.346  7967  7967 I UEI.SmartControl: ### init IR Blaster...
,08-10 07:41:27.350  7967  7967 D serial_port: Configuring serial port
08-10 07:41:27.350  7967  7967 E UEI.SmartControl: UEIBLaster setting for 616
08-10 07:41:27.350  7967  7967 I UEI.SmartControl: Setting serial record hearder size = 2,
08-10 07:41:27.350  7967  7967 I UEI.SmartControl: configuring settings for MAXQ616
08-10 07:41:27.350  7967  7967 I UEI.SmartControl: Get version...
,08-10 07:41:27.371  7967  8431 D UEI.SmartControl: serial port data available: 21
,08-10 07:41:27.400  7967  7967 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-10 07:41:27.400  7967  7967 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 07:41:27.400  7967  7967 I UEI.SmartControl: QS saving settings...
,08-10 07:41:27.406  7967  7967 D UEI.SmartControl: IR Blaster version: 25672567
,08-10 07:41:27.423  7967  8431 D UEI.SmartControl: serial port data available: 4
,08-10 07:41:27.453  7967  7967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-10 07:41:27.456  7967  8437 I UEI.SmartControl: Device manager: loading config....
08-10 07:41:27.457  7967  8437 D UEI.SmartControl: ----------- loading internal config...
08-10 07:41:27.458  7967  7967 E UEI.SmartControl: Services init done
08-10 07:41:27.458  7967  7967 D UEI.SmartControl: QS Service init finished
08-10 07:41:27.458  7967  7967 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 07:41:27.458  7967  7967 D UEI.SmartControl: QS Service version code: 201091
,08-10 07:41:27.463  7967  7967 D UEI.SmartControl: Service requested: Control
08-10 07:41:27.467  7967  8437 E UEI.SmartControl: Loading SETTINGS...
08-10 07:41:27.470  7967  7967 D UEI.SmartControl: Request IControl service: devices are loaded...
08-10 07:41:27.472  7967  7967 D UEI.SmartControl: Internal service binding...
08-10 07:41:27.473  8381  8381 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-10 07:41:27.475  7967  7982 I UEI.SmartControl: ------ IControl API: 11
08-10 07:41:27.475  7967  7982 D UEI.SmartControl: File observer start...
,08-10 07:41:27.476  7967  7982 E UEI.SmartControl: IR Port is disabled: false
08-10 07:41:27.476  7967  7982 D UEI.SmartControl: Starting file observer...
08-10 07:41:27.477  7967  7982 I UEI.SmartControl: Registering callback...
08-10 07:41:27.479  7967  7983 I UEI.SmartControl: ------ IControl API: 19
08-10 07:41:27.479  7967  8437 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-10 07:41:27.481  7967  7983 I UEI.SmartControl: Registering Services Ready callback...
08-10 07:41:27.492  7967  8436 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 07:41:27.492  7967  8436 D UEI.SmartControl: -----service ready thread exits
,08-10 07:41:27.493  8381  8397 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-10 07:41:27.494  8381  8423 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-10 07:41:27.494  8381  8423 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-10 07:41:27.495  8381  8381 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-10 07:41:27.495  8381  8381 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-10 07:41:27.495  7967  7982 I UEI.SmartControl: ------ IControl API: 8
08-10 07:41:27.498  8381  8381 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-10 07:41:27.499  8381  8381 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-10 07:41:27.500  8381  8381 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-10 07:41:27.500  8381  8381 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-10 07:41:27.502  8381  8381 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-10 07:41:27.502  8381  8381 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-10 07:41:27.504  8381  8381 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-10 07:41:27.511  8381  8381 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-10 07:41:27.511  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-10 07:41:27.513  8381  8381 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 07:41:27.514  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-10 07:41:27.523  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-10 07:41:27.525  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-10 07:41:27.526  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-10 07:41:27.527  8381  8381 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470807687527]
,08-10 07:41:27.529  8381  8381 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-10 07:41:27.535  1037  2034 I ActivityManager: Killing 7509:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-10 07:41:27.558  8381  8439 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-10 07:41:27.771  1037  1926 W libprocessgroup: failed to open /acct/uid_10005/pid_7509/cgroup.procs: No such file or directory
,08-10 07:41:27.775  8381  8381 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-10 07:41:27.778  8381  8381 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-10 07:41:27.780  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-10 07:41:27.780  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-10 07:41:27.781  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,08-10 07:41:27.782  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-10 07:41:27.783  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-10 07:41:27.793  8381  8381 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-10 07:41:28.639  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=76.0, 0.0, 0.0  rx=75.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1928873407] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 07:41:28.641  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=76.0, 0.0, 0.0  rx=75.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1928873409] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 07:41:28.642  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 07:41:28.656  1605  1605 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-10 07:41:28.678  1037  1542 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-10 07:41:28.723  1037  1547 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:28.729  1037  1098 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:28.731  1037  1119 D Tethering: MasterInitialState.processMessage what=3
,08-10 07:41:28.744  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-10 07:41:28.751  6960  6960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 07:41:28.751  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 07:41:28.751  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 07:41:28.751  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 07:41:28.751  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 07:41:28.751  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:28.751  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 07:41:28.751  6960  6960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 07:41:28.751  5753  5753 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-10 07:41:28.753  6960  6960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 07:41:28.762  2182  2182 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-10 07:41:28.772  8309  8370 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-10 07:41:28.776  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-10 07:41:28.776  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:28.776  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-10 07:41:28.776  7269  7269 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-10 07:41:28.778  7269  7269 I AppUp4:CustModeStarterReceiver: onReceive
08-10 07:41:28.780  7269  7269 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7297cc2
,08-10 07:41:28.780  7269  7269 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 07:41:28.780  7269  7269 D AppUp4:CustFacade: isPhone : true
08-10 07:41:28.780  7269  7269 D AppUp4:CustModeStarterReceiver: begin check event
08-10 07:41:28.781  7269  7269 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-10 07:41:28.783  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:28.783  4638  4638 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-10 07:41:28.784  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:28.785  4638  4638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-10 07:41:28.789   310  8445 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 07:41:28.790   310  8445 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
,08-10 07:41:28.795  1037  1098 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-10 07:41:28.796  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-10 07:41:28.796  6960  7027 I jxcore-log: 
08-10 07:41:28.797  2849  2849 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:28.799  2849  2849 V DownloadManager: DownloadService onCreate
,08-10 07:41:28.801  4638  8452 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-10 07:41:28.802  2849  8450 I DownloadManager: in removeSpuriousFiles
08-10 07:41:28.807  2849  8450 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-10 07:41:28.808  4638  8452 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-10 07:41:28.829   310  8445 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-10 07:41:28.831  1037  1926 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8456 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 07:41:28.834  4638  8453 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:28.834  4638  8453 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-10 07:41:28.838  4638  8452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,08-10 07:41:28.932  1037  1578 I art     : Explicit concurrent mark sweep GC freed 75963(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.131ms total 119.010ms
08-10 07:41:28.940  4638  4638 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-10 07:41:28.941  2849  8450 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@13583c5d on behalf of 2849
,08-10 07:41:28.942  4638  4638 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-10 07:41:28.942  4638  4638 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,08-10 07:41:28.944  4638  4638 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-10 07:41:28.946  2849  2849 V DownloadManager: DownloadService onStartCommand
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-10 07:41:28.948  2849  8450 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-10 07:41:28.950  2849  8450 I DownloadManager: in trimDatabase
08-10 07:41:28.950  2849  8450 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-10 07:41:28.951  2849  8451 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-10 07:41:28.955  4638  4638 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-10 07:41:28.960  2849  8450 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2be439d2 on behalf of 2849
08-10 07:41:28.960  2849  8451 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@436caa3 on behalf of 2849
08-10 07:41:28.962  2849  8451 V DownloadManager: processing inserted download 1
08-10 07:41:28.963  2849  8451 V DownloadManager: processing inserted download 4
08-10 07:41:28.964  2849  8451 V DownloadManager: processing inserted download 7
08-10 07:41:28.964  2849  8451 V DownloadManager: processing inserted download 8
08-10 07:41:28.965  2849  8451 V DownloadManager: processing inserted download 9
08-10 07:41:28.966  2849  8451 V DownloadManager: processing inserted download 10
08-10 07:41:28.966  2849  8451 V DownloadManager: processing inserted download 11
08-10 07:41:28.967  2849  8451 V DownloadManager: processing inserted download 12
08-10 07:41:28.968  2849  8451 V DownloadManager: processing inserted download 13
08-10 07:41:28.969  2849  8451 V DownloadManager: processing inserted download 14
08-10 07:41:28.969  2849  8451 V DownloadManager: processing inserted download 16
,08-10 07:41:28.972  2849  2849 V DownloadManager: DownloadService onDestroy
08-10 07:41:28.973  8456  8456 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:28.974  8456  8456 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:28.975  8456  8456 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 07:41:28.975  8456  8456 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 07:41:29.042  8456  8456 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 07:41:29.051  8456  8456 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-10 07:41:29.065  2182  8480 D GCM     : Connected
,08-10 07:41:29.084  2182  8480 D GCM     : Message class com.google.e.a.a.q
,08-10 07:41:29.110  8456  8456 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 07:41:29.141  8456  8456 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:29.141  8456  8456 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:29.268  8456  8456 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-10 07:41:29.313  8456  8456 I HubEmail: JNI_OnLoad()
08-10 07:41:29.314  8456  8456 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 07:41:29.314  8456  8456 I HubEmail: registerNatives()
08-10 07:41:29.314  8456  8456 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 07:41:29.314  8456  8456 I HubEmail: registerNativeMethods()
08-10 07:41:29.314  8456  8456 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-10 07:41:29.314  8456  8456 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-10 07:41:29.323  8456  8489 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 07:41:29.351  3350  3350 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-10 07:41:29.351  3350  3350 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-10 07:41:29.352  3350  3350 I LgeMiscReceiver: networkInfo.isConnected() = true
08-10 07:41:29.352  3350  3350 D PhoneState: setPdpRejectCasuse : false
,08-10 07:41:29.372   310  8495 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-10 07:41:29.374   310  8495 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-10 07:41:29.390  1037  1900 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8496 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-10 07:41:29.405   310  8495 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-10 07:41:29.478  8496  8496 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:29.478  8496  8496 D LgDataFeature: LgDataFeature() Constructor Done, null
08-10 07:41:29.481  8496  8496 D PhoneMonitor: Register our PhoneStateListener
,08-10 07:41:29.492  8240  8492 V FormManager: There are no updated forms. The schedule will be deleted.
,08-10 07:41:29.496  8240  8492 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-10 07:41:29.499  8496  8496 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-10 07:41:29.504  8496  8496 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-10 07:41:29.531  8496  8496 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-10 07:41:29.532  8496  8496 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-10 07:41:29.532  8496  8496 D TelephonyAutoProfiling: [parse] Load xml
08-10 07:41:29.535  8496  8496 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-10 07:41:29.536  8496  8496 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-10 07:41:29.536  8496  8496 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-10 07:41:29.545  8496  8496 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-10 07:41:29.568  1037  2011 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8522 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 07:41:29.569  1037  2011 I ActivityManager: Killing 7907:com.google.android.talk/u0a72 (adj 15): empty #17
,08-10 07:41:29.652  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-10 07:41:29.652  6960  7027 I jxcore-log: 
,08-10 07:41:29.677  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-10 07:41:29.677  6960  7027 I jxcore-log: 
,08-10 07:41:29.697  1037  2054 W libprocessgroup: failed to open /acct/uid_10072/pid_7907/cgroup.procs: No such file or directory
,08-10 07:41:29.727  1037  2034 I ActivityManager: Killing 7946:com.android.contacts/u0a19 (adj 15): empty #17
,08-10 07:41:29.885   310  8541 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 07:41:29.886   310  8541 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-10 07:41:29.892  1037  1578 W libprocessgroup: failed to open /acct/uid_10019/pid_7946/cgroup.procs: No such file or directory
,08-10 07:41:29.899  1818  8539 I CheckinService: active receiver: enabled
,08-10 07:41:29.915  1818  8539 I CheckinService: Preparing to send checkin request
08-10 07:41:29.915  1818  8539 I EventLogService: Accumulating logs since 1470807668766
,08-10 07:41:29.925   310  8541 D libc-netbsd: res_queryN name = www.google.com succeed
08-10 07:41:29.930   310  8544 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 07:41:29.930   310  8544 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-10 07:41:29.930   310  8544 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-10 07:41:29.941  1037  1543 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-10 07:41:29.981  1037  1649 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8545 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-10 07:41:29.982  1037  1649 I ActivityManager: Killing 7993:com.android.gallery3d/u0a27 (adj 15): empty #17
08-10 07:41:30.095  1037  1974 W libprocessgroup: failed to open /acct/uid_10027/pid_7993/cgroup.procs: No such file or directory
08-10 07:41:30.095  1818  8539 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-10 07:41:30.221  1037  2011 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8562 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 07:41:30.224  1037  2011 I ActivityManager: Killing 8065:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-10 07:41:30.436  1037  1997 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8579 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-10 07:41:30.437  1037  1926 W libprocessgroup: failed to open /acct/uid_10080/pid_8065/cgroup.procs: No such file or directory
08-10 07:41:30.468  8562  8562 I art     : Almond Protected OAT
,08-10 07:41:30.497  8579  8579 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-10 07:41:30.497  8579  8579 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-10 07:41:30.512  1037  1380 V AlarmManager: RTC_WAKEUP set : Alarm{3dce753a type 0 when 1470807679955 com.google.android.gms} when 1470807679955
,08-10 07:41:30.516  8579  8579 I MultiDex: VM with version 2.1.0 has multidex support
08-10 07:41:30.516  8579  8579 I MultiDex: install
08-10 07:41:30.516  8579  8579 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-10 07:41:30.517  8562  8562 D WeatherApplication: removeAccount
08-10 07:41:30.518  8562  8562 D WeatherApplication: Account.length = 0
08-10 07:41:30.518  8562  8562 E WeatherApplication: OPERATOR:OPEN
08-10 07:41:30.523  8562  8562 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:30
08-10 07:41:30.524  8579  8579 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-10 07:41:30.527  8562  8562 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-10 07:41:30.527  8562  8562 D Weather.Utils: 2 : All the weather widget is gone.
,08-10 07:41:30.535  8562  8562 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-10 07:41:30.536  8562  8562 D WeatherAncestor: connectivity changed - connection : true
08-10 07:41:30.537  8562  8562 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-10 07:41:30.543  8562  8562 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-10 07:41:30.543  8562  8562 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-10 07:41:30.543  8562  8562 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-10 07:41:30.564  8562  8562 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-10 07:41:30.564  8562  8562 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 7:41:30
,08-10 07:41:30.620  1037  1649 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8598 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 07:41:30.621  1037  1649 I ActivityManager: Killing 8013:com.android.vending/u0a44 (adj 15): empty #17
,08-10 07:41:30.730  8579  8595 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:30.731  8579  8595 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:30.733  1037  1974 W libprocessgroup: failed to open /acct/uid_10044/pid_8013/cgroup.procs: No such file or directory
08-10 07:41:30.757  2182  2202 I art     : Explicit concurrent mark sweep GC freed 6255(390KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 811us total 16.151ms
,08-10 07:41:30.797  8616  8616 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-10 07:41:30.841  8616  8616 I dex2oat : dex2oat took 44.340ms (threads: 4)
08-10 07:41:30.843   279   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 07:41:30.843   279   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 07:41:30.843   279   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 07:41:30.843  8598  8622 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-10 07:41:30.845   279   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 07:41:30.845   279   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,08-10 07:41:30.845   279   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 07:41:30.851  8579  8595 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:41:30.851  8579  8595 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:41:30.851  8579  8595 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:41:30.851  8579  8595 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:41:30.851  8579  8595 I Adreno-EGL: Remote Branch: 
08-10 07:41:30.851  8579  8595 I Adreno-EGL: Local Patches: 
08-10 07:41:30.851  8579  8595 I Adreno-EGL: Reconstruct Branch: 
08-10 07:41:30.852  8598  8622 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-10 07:41:30.866   279   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 07:41:30.866   279   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-10 07:41:30.866   279   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 07:41:30.866  8598  8626 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-10 07:41:30.870   279   454 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-10 07:41:30.870   279   454 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-10 07:41:30.870   279   454 W Vold    : Returning OperationFailed - no handler for errno 0
08-10 07:41:30.870  8598  8626 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-10 07:41:30.918  8579  8595 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:41:30.918  8579  8595 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:41:30.918  8579  8595 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:41:30.918  8579  8595 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:41:30.918  8579  8595 I Adreno-EGL: Remote Branch: 
08-10 07:41:30.918  8579  8595 I Adreno-EGL: Local Patches: 
08-10 07:41:30.918  8579  8595 I Adreno-EGL: Reconstruct Branch: 
,08-10 07:41:30.953  8579  8595 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:41:30.953  8579  8595 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:41:30.953  8579  8595 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:41:30.953  8579  8595 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:41:30.953  8579  8595 I Adreno-EGL: Remote Branch: 
08-10 07:41:30.953  8579  8595 I Adreno-EGL: Local Patches: 
08-10 07:41:30.953  8579  8595 I Adreno-EGL: Reconstruct Branch: 
,08-10 07:41:31.053  8598  8598 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-10 07:41:31.061  8598  8598 I LibraryLoader: Loading: webviewchromium
08-10 07:41:31.064  8598  8598 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2318-2322)
08-10 07:41:31.064  8598  8598 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 07:41:31.069  8598  8598 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fb35d35}
08-10 07:41:31.070  8598  8598 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 07:41:31.070  8598  8598 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 07:41:31.078  8598  8598 I BrowserStartupController: Initializing chromium process, renderers=0
08-10 07:41:31.078  8598  8598 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 07:41:31.091  8598  8598 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-10 07:41:31.091  8598  8598 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-10 07:41:31.092  8598  8598 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-10 07:41:31.098   315  1386 V AudioPolicyService: registerClient() client 0xb558a8a0, uid 10093
08-10 07:41:31.099  8598  8647 W AudioManagerAndroid: Requires BLUETOOTH permission
08-10 07:41:31.108  8598  8598 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 07:41:31.108  8598  8598 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 07:41:31.108  8598  8598 I Adreno-EGL: Build Date: 12/12/14 금
08-10 07:41:31.108  8598  8598 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-10 07:41:31.108  8598  8598 I Adreno-EGL: Remote Branch: 
08-10 07:41:31.108  8598  8598 I Adreno-EGL: Local Patches: 
08-10 07:41:31.108  8598  8598 I Adreno-EGL: Reconstruct Branch: 
,08-10 07:41:31.152  8598  8598 I NSApplication: Starting up...
,08-10 07:41:31.167  1037  1649 I ActivityManager: Killing 7703:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-10 07:41:31.253  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-10 07:41:31.253  6960  7027 I jxcore-log: 
,08-10 07:41:31.280  1037  1974 W libprocessgroup: failed to open /acct/uid_10037/pid_7703/cgroup.procs: No such file or directory
,08-10 07:41:31.311   310  8661 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-10 07:41:31.311   310  8661 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-10 07:41:31.324  2182  2182 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-10 07:41:31.343   310  8661 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-10 07:41:31.348  2182  2182 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-10 07:41:31.349  2182  2182 D c       : Getting all permits...
08-10 07:41:31.349  2182  2182 D a       : Opening database...
08-10 07:41:31.357  2182  2182 D a       : Opening database auth.proximity.permit_store...
08-10 07:41:31.358  2182  2182 D a       : Closing database...
,08-10 07:41:31.485  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-10 07:41:31.485  6960  7027 I jxcore-log: 
08-10 07:41:31.490  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-10 07:41:31.490  6960  7027 I jxcore-log: 
,08-10 07:41:31.503  1818  8539 I CheckinTask: Sending checkin request (7974 bytes),
08-10 07:41:31.509  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-10 07:41:31.509  6960  7027 I jxcore-log: 
08-10 07:41:31.513  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-10 07:41:31.513  6960  7027 I jxcore-log: 
,08-10 07:41:31.660  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=42.5, 0.0, 0.0  rx=40.5 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1928876428] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 07:41:31.661  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-40 f=2447 sc=60 link=72 tx=42.5, 0.0, 0.0  rx=40.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1928876429] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 07:41:31.661  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 07:41:31.693  1818  8539 I art     : Explicit concurrent mark sweep GC freed 30222(2007KB) AllocSpace objects, 16(248KB) LOS objects, 51% free, 29MB/61MB, paused 1.137ms total 44.083ms
,08-10 07:41:31.736  1818  8539 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-10 07:41:31.742  1818  8539 I CheckinService: active receiver: disabled
,08-10 07:41:31.763  1818  8673 I CheckinService: active receiver: disabled
08-10 07:41:31.773  2182  2182 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-10 07:41:31.785  2182  2182 I GCM     : GCM config loaded
08-10 07:41:31.803  8496  8496 V SetupWizard: Connected to Gservices successfully
,08-10 07:41:32.266  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-10 07:41:32.266  6960  7027 I jxcore-log: 
,08-10 07:41:32.285  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-10 07:41:32.285  6960  7027 I jxcore-log: 
,08-10 07:41:32.298  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-10 07:41:32.298  6960  7027 I jxcore-log: 
,08-10 07:41:32.306  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-10 07:41:32.306  6960  7027 I jxcore-log: 
,08-10 07:41:32.363  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-10 07:41:32.363  6960  7027 I jxcore-log: 
,08-10 07:41:32.424  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-10 07:41:32.424  6960  7027 I jxcore-log: 
,08-10 07:41:32.433  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-10 07:41:32.433  6960  7027 I jxcore-log: 
08-10 07:41:32.452  7967  8438 D UEI.SmartControl: Internal timer expired: 4
08-10 07:41:32.453  7967  8438 D UEI.SmartControl: unbind internal service
,08-10 07:41:32.493  7967  8432 D serial_port: close(fd = 24)
,08-10 07:41:32.501  7967  8432 I UEI.SmartControl: Serial port is closed.
,08-10 07:41:32.598  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-10 07:41:32.598  6960  7027 I jxcore-log: 
,08-10 07:41:32.625  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-10 07:41:32.625  6960  7027 I jxcore-log: 
,08-10 07:41:32.630  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-10 07:41:32.630  6960  7027 I jxcore-log: 
,08-10 07:41:32.635  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-10 07:41:32.635  6960  7027 I jxcore-log: 
,08-10 07:41:32.653  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-10 07:41:32.653  6960  7027 I jxcore-log: 
,08-10 07:41:32.732  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-10 07:41:32.732  6960  7027 I jxcore-log: 
,08-10 07:41:32.745  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-10 07:41:32.745  6960  7027 I jxcore-log: 
,08-10 07:41:32.771  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-10 07:41:32.771  6960  7027 I jxcore-log: 
,08-10 07:41:32.784  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-10 07:41:32.784  6960  7027 I jxcore-log: 
08-10 07:41:32.802  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-10 07:41:32.802  6960  7027 I jxcore-log: 
,08-10 07:41:32.835  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-10 07:41:32.835  6960  7027 I jxcore-log: 
,08-10 07:41:32.841  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-10 07:41:32.841  6960  7027 I jxcore-log: 
,08-10 07:41:33.038  6960  7027 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-10 07:41:33.038  6960  7027 I jxcore-log: 
,08-10 07:41:33.048  6960  7027 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-10 07:41:33.050  6960  7027 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-10 07:41:33.050  6960  7027 I jxcore-log: 
08-10 07:41:33.108  6960  7027 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 07:41:33.108  6960  7027 I jxcore-log: 
,08-10 07:41:34.669  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=40.8, 0.0, 0.0  rx=35.8 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1928879437] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 07:41:34.682  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=40.8, 0.0, 0.0  rx=35.8 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1928879450] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 07:41:34.683  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 07:41:35.882  8598  8624 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-10 07:41:36.295  1037  2054 I ActivityManager: Killing 7155:com.lge.settings.easy/1000 (adj 15): empty #17
,08-10 07:41:36.327  1037  2036 W libprocessgroup: failed to open /acct/uid_1000/pid_7155/cgroup.procs: No such file or directory
,08-10 07:41:37.699  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=24.9, 0.0, 0.0  rx=21.9 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1928882467] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 07:41:37.710  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=24.9, 0.0, 0.0  rx=21.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1928882477] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 07:41:37.710  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 07:41:39.957  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-10 07:41:39.961  1605  1605 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
08-10 07:41:39.974  1037  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 07:41:40.060  1037  1100 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8692 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-10 07:41:40.067  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-10 07:41:40.068  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-10 07:41:40.114  1037  1037 D administrator: Handling package changes for user 0
,08-10 07:41:40.152  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 07:41:40.177  8692  8692 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-10 07:41:40.239  8692  8692 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:40.240  8692  8692 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:40.269  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-10 07:41:40.269  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-10 07:41:40.314  1037  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 07:41:40.322  1037  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-10 07:41:40.330  2460  2460 V GmsNetworkLocationProvi: DISABLE
,08-10 07:41:40.333  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-10 07:41:40.353  2460  2460 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-10 07:41:40.365  8692  8737 I Babel   : MmsConfig: mnc/mcc: 0/0
08-10 07:41:40.365  8692  8737 I Babel   : MmsConfig.loadMmsSettings
08-10 07:41:40.375  8692  8737 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-10 07:41:40.375  8692  8737 I Babel   : MmsConfig.loadFromDatabase
,08-10 07:41:40.386  8692  8737 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-10 07:41:40.386  8692  8737 I Babel   : MmsConfig.loadFromResources
08-10 07:41:40.388  8692  8737 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-10 07:41:40.392  8692  8737 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-10 07:41:40.408  1037  1098 D LocationProviderProxy: applying state to connected service
08-10 07:41:40.410  8692  8692 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:40.416  8692  8735 W AudioCapabilities: Unsupported mime audio/evrc
08-10 07:41:40.416  8692  8735 W AudioCapabilities: Unsupported mime audio/qcelp
,08-10 07:41:40.418  8692  8735 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-10 07:41:40.426  8692  8735 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-10 07:41:40.427  8692  8735 W AudioCapabilities: Unsupported mime audio/qcelp
08-10 07:41:40.427  8692  8735 W AudioCapabilities: Unsupported mime audio/evrc
,08-10 07:41:40.433  1818  8738 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-10 07:41:40.433  1818  8738 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-10 07:41:40.435  7269  7269 I AppUp4:CustModeStarterReceiver: onReceive
08-10 07:41:40.439  7269  7269 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@7297cc2
08-10 07:41:40.439  7269  7269 D AppUp4:CustFacade: isCustomizationCompleted : false
08-10 07:41:40.439  7269  7269 D AppUp4:CustFacade: isPhone : true
08-10 07:41:40.439  7269  7269 D AppUp4:CustModeStarterReceiver: begin check event
08-10 07:41:40.439  7269  7269 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-10 07:41:40.453  1818  4995 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-10 07:41:40.463  8692  8735 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-10 07:41:40.463  1037  2054 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8742 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-10 07:41:40.469  8692  8735 W VideoCapabilities: Unsupported mime video/divx
08-10 07:41:40.476   344   344 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 242us total 11.530ms
08-10 07:41:40.478  1037  1926 I ActivityManager: Killing 8291:com.lge.bnr/1000 (adj 15): empty #17
,08-10 07:41:40.489   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 314us total 11.946ms
08-10 07:41:40.493  8692  8735 W VideoCapabilities: Unsupported mime video/divx311
,08-10 07:41:40.496  8692  8735 W VideoCapabilities: Unsupported mime video/divx4
08-10 07:41:40.499   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 10.179ms
08-10 07:41:40.500  8692  8735 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-10 07:41:40.513  8692  8735 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-10 07:41:40.516  8692  8735 W AudioCapabilities: Unsupported mime audio/eac3
08-10 07:41:40.516  8692  8735 W AudioCapabilities: Unsupported mime audio/ac3
08-10 07:41:40.517  8692  8735 W AudioCapabilities: Unsupported mime audio/g726
08-10 07:41:40.517  8692  8735 W AudioCapabilities: Unsupported mime audio/wma-voice
08-10 07:41:40.518  8692  8735 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-10 07:41:40.518  8692  8735 W AudioCapabilities: Unsupported mime audio/adpcm
08-10 07:41:40.520  8692  8735 W VideoCapabilities: Unsupported mime video/theora
08-10 07:41:40.521  8692  8735 W VideoCapabilities: Unsupported mime video/mjpg
08-10 07:41:40.554  1037  1974 W libprocessgroup: failed to open /acct/uid_1000/pid_8291/cgroup.procs: No such file or directory
,08-10 07:41:40.590  8742  8742 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 07:41:40.591  8742  8742 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:40.591  8742  8742 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-10 07:41:40.593  8742  8742 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-10 07:41:40.593  8742  8742 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 07:41:40.672  8742  8742 I SystemConfig: BUILD Country: EU
08-10 07:41:40.672  8742  8742 I SystemConfig: BUILD Operator: OPEN
,08-10 07:41:40.717  1037  1649 I ActivityManager: Killing 8263:com.lge.sync/1000 (adj 15): empty #17
,08-10 07:41:40.733  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=12.9, 0.0, 0.0  rx=10.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1928885500] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 07:41:40.736  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=12.9, 0.0, 0.0  rx=10.9 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1928885504] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-10 07:41:40.736  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 07:41:40.825  1037  2011 W libprocessgroup: failed to open /acct/uid_1000/pid_8263/cgroup.procs: No such file or directory
,08-10 07:41:40.894  1037  1649 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8766 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-10 07:41:40.901  8742  8761 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-10 07:41:40.902  8742  8761 I SystemConfig: existFile = false
08-10 07:41:40.902  8742  8761 I SystemConfig: canReadFile = false
08-10 07:41:40.902  8742  8761 I SystemConfig: systemFeature RCS result false
08-10 07:41:40.902  8742  8761 D SystemConfig: refreshRcsSupport() :false
,08-10 07:41:40.981  8766  8766 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 07:41:40.982  8766  8766 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 07:41:40.982  8766  8766 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 07:41:40.983  8766  8766 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-10 07:41:41.088  8766  8766 I AppConfig: Total System Memory = 2995761152
,08-10 07:41:41.104  8766  8766 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-10 07:41:41.217  1037  1954 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8788 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-10 07:41:41.218  1037  1954 I ActivityManager: Killing 7062:com.android.settings/1000 (adj 15): empty #17
,08-10 07:41:41.275  1037  1900 W libprocessgroup: failed to open /acct/uid_1000/pid_7062/cgroup.procs: No such file or directory
,08-10 07:41:41.442  1037  1052 I art     : Explicit concurrent mark sweep GC freed 30653(1617KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.926ms total 161.220ms
,08-10 07:41:41.632  8788  8788 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-10 07:41:41.727  8788  8788 D LgDataFeature: LgDataFeature() Constructor: none
,08-10 07:41:41.727  8788  8788 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:41.789  8788  8788 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-10 07:41:41.816  8788  8788 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 07:41:41.817  8788  8788 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-10 07:41:41.838  8788  8788 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-10 07:41:41.838  8788  8788 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-10 07:41:41.864  1037  1578 I ActivityManager: Killing 7967:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-10 07:41:41.887  8381  8381 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-10 07:41:41.888  8381  8381 W System.err: android.os.DeadObjectException
08-10 07:41:41.890  8381  8381 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 07:41:41.890  8381  8381 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-10 07:41:41.890  8381  8381 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-10 07:41:41.890  8381  8381 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-10 07:41:41.891  8381  8381 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 07:41:41.891  8381  8381 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 07:41:41.891  8381  8381 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 07:41:41.891  8381  8381 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 07:41:41.891  8381  8381 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:41.891  8381  8381 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:41.891  8381  8381 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:41.891  8381  8381 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:41.891  8381  8381 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:41.891  8381  8381 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 07:41:41.891  8381  8381 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-10 07:41:41.892  8381  8381 W System.err: android.os.DeadObjectException
08-10 07:41:41.892  8381  8381 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 07:41:41.893  8381  8381 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 07:41:41.893  8381  8381 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-10 07:41:41.893  8381  8381 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-10 07:41:41.893  8381  8381 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-10 07:41:41.893  8381  8381 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-10 07:41:41.893  8381  8381 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 07:41:41.893  8381  8381 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 07:41:41.893  8381  8381 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:41.893  8381  8381 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:41.893  8381  8381 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:41.893  8381  8381 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:41.893  8381  8381 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:41.893  8381  8381 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 07:41:41.894  8381  8381 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-10 07:41:41.894  8381  8381 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-10 07:41:41.989   277   277 E lowmemorykiller: Error opening /proc/7967/oom_score_adj; errno=2
,08-10 07:41:41.995  1037  2036 W ActivityManager: Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
08-10 07:41:41.995  1037  2036 W ActivityManager: android.os.DeadObjectException
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-10 07:41:41.995  1037  2036 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
08-10 07:41:41.998  1037  2054 W libprocessgroup: failed to open /acct/uid_1000/pid_7967/cgroup.procs: No such file or directory
08-10 07:41:42.003  8381  8381 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-10 07:41:42.004  8381  8381 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-10 07:41:42.009  2849  2956 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-10 07:41:42.010  2849  2956 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@5614159 on behalf of 8788
,08-10 07:41:42.017  4910  8825 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-10 07:41:42.059  1037  1954 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8826 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-10 07:41:42.067  8381  8381 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-10 07:41:42.127  1037  1879 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8846 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-10 07:41:42.165  8788  8788 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-10 07:41:42.178  8788  8788 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-10 07:41:42.193  8826  8826 D UEI.SmartControl: Quickset Services start...
08-10 07:41:42.194  8826  8826 I UEI.SmartControl: Manufacture = LGE
,08-10 07:41:42.194  8826  8826 D UEI.SmartControl: Id = LGNevo
08-10 07:41:42.196  8826  8826 D UEI.SmartControl: File observer start...
,08-10 07:41:42.197  8826  8826 E UEI.SmartControl: IR Port is disabled: false
08-10 07:41:42.197  8826  8826 D UEI.SmartControl: Starting file observer...
08-10 07:41:42.197  8826  8826 D UEI.SmartControl: Extracting JNI libs...
08-10 07:41:42.197  8826  8826 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-10 07:41:42.203  8846  8846 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-10 07:41:42.227  8846  8846 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-10 07:41:42.227  8846  8846 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-10 07:41:42.227  8846  8846 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-10 07:41:42.227  8846  8846 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-10 07:41:42.227  8846  8846 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-10 07:41:42.227  8846  8846 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-10 07:41:42.244  1037  1997 I ActivityManager: Killing 8381:com.lge.qremote/u0a112 (adj 15): empty #17
,08-10 07:41:42.247  8826  8826 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-10 07:41:42.247  8826  8826 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-10 07:41:42.247  8826  8826 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-10 07:41:42.268  8826  8826 I UEI.SmartControl: --- Selecting new region: 6
08-10 07:41:42.270  8826  8826 I UEI.SmartControl: Model = LG-D855
,08-10 07:41:42.270  8826  8826 D UEI.SmartControl: QS Service created
08-10 07:41:42.284  1037  1900 W libprocessgroup: failed to open /acct/uid_10112/pid_8381/cgroup.procs: No such file or directory
,08-10 07:41:42.318  8826  8826 I UEI.SmartControl: Service initServices...
,08-10 07:41:42.323  8826  8826 D UEI.SmartControl: QS start get config
08-10 07:41:42.373  8826  8826 D UEI.SmartControl: Loading JNI Libs...
,08-10 07:41:42.496  1037  1053 V SIM_STK : Menu title from STK is T-Mobile
,08-10 07:41:42.508  4910  8825 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 491 ms] updated apps [took 491 ms] 
,08-10 07:41:42.590  8826  8826 I UEI.SmartControl: Supports setup maps: true
,08-10 07:41:42.594  8826  8826 D UEI.SmartControl: QS start statue = true Error code = 0
,08-10 07:41:42.594  8826  8826 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 07:41:42.594  8826  8826 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 07:41:42.594  8826  8826 I UEI.SmartControl: ### init IR Blaster...
,08-10 07:41:42.601  8826  8826 D serial_port: Configuring serial port
08-10 07:41:42.611  8826  8826 E UEI.SmartControl: UEIBLaster setting for 616
,08-10 07:41:42.611  8826  8826 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 07:41:42.613  8826  8826 I UEI.SmartControl: configuring settings for MAXQ616
08-10 07:41:42.613  8826  8826 I UEI.SmartControl: Get version...
08-10 07:41:42.633  8826  8877 D UEI.SmartControl: serial port data available: 21
,08-10 07:41:42.662  8826  8826 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-10 07:41:42.663  8826  8826 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 07:41:42.664  8826  8826 I UEI.SmartControl: QS saving settings...
08-10 07:41:42.669  8826  8826 D UEI.SmartControl: IR Blaster version: 25672567
08-10 07:41:42.687  8826  8877 D UEI.SmartControl: serial port data available: 4
,08-10 07:41:42.735  8826  8826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-10 07:41:42.744  8826  8826 E UEI.SmartControl: Services init done
08-10 07:41:42.745  8826  8826 D UEI.SmartControl: QS Service init finished
08-10 07:41:42.747  8826  8826 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 07:41:42.747  8826  8826 D UEI.SmartControl: QS Service version code: 201091
08-10 07:41:42.748  8826  8826 D UEI.SmartControl: Service requested: Control
08-10 07:41:42.749  8826  8886 I UEI.SmartControl: Device manager: loading config....
08-10 07:41:42.751  8826  8886 D UEI.SmartControl: ----------- loading internal config...
08-10 07:41:42.760  8826  8886 E UEI.SmartControl: Loading SETTINGS...
,08-10 07:41:42.764  8826  8826 D UEI.SmartControl: Request IControl service: devices are loaded...
08-10 07:41:42.765  8826  8826 D UEI.SmartControl: Service.onUnbind: IControl
08-10 07:41:42.766  8826  8826 D UEI.SmartControl: Service.onDestroy
08-10 07:41:42.767  8826  8826 D UEI.SmartControl: Lock is in USE false
08-10 07:41:42.767  8826  8826 D UEI.SmartControl: unbind internal service
08-10 07:41:42.770  8826  8826 D serial_port: close(fd = 25)
08-10 07:41:42.773  8826  8886 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-10 07:41:42.777  8826  8826 I UEI.SmartControl: Serial port is closed.
08-10 07:41:42.778  8826  8826 I UEI.SmartControl: Serial port is closed.
08-10 07:41:42.778  8826  8826 D UEI.SmartControl: Blaster closed
08-10 07:41:42.778  8826  8826 D UEI.SmartControl: Shut down QS...
08-10 07:41:42.778  8826  8826 D UEI.SmartControl: Stopping QS lib
08-10 07:41:42.778  8826  8826 D UEI.SmartControl: QS lib stop result = true
08-10 07:41:42.778  8826  8826 D UEI.SmartControl: Stopped QS lib
08-10 07:41:42.780  8826  8826 D UEI.SmartControl: Stopped file observer...
08-10 07:41:42.780  8826  8826 D UEI.SmartControl: QS shutdown complete
08-10 07:41:42.781  8826  8826 D UEI.SmartControl: QS Service created
08-10 07:41:42.784  8826  8882 I UEI.SmartControl: Notify AllClients services are ready: 11
08-10 07:41:42.784  8826  8882 D UEI.SmartControl: -----service ready thread exits
08-10 07:41:42.796  8826  8826 I UEI.SmartControl: Service initServices...
08-10 07:41:42.796  8826  8826 D UEI.SmartControl: QS start get config
,08-10 07:41:43.104  8826  8826 I UEI.SmartControl: Supports setup maps: true
,08-10 07:41:43.107  8826  8826 D UEI.SmartControl: QS start statue = true Error code = 0
08-10 07:41:43.107  8826  8826 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-10 07:41:43.107  8826  8826 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-10 07:41:43.107  8826  8826 I UEI.SmartControl: ### init IR Blaster...
08-10 07:41:43.110  8826  8826 D serial_port: Configuring serial port
08-10 07:41:43.111  8826  8826 E UEI.SmartControl: UEIBLaster setting for 616
08-10 07:41:43.111  8826  8826 I UEI.SmartControl: Setting serial record hearder size = 2
08-10 07:41:43.111  8826  8826 I UEI.SmartControl: configuring settings for MAXQ616
08-10 07:41:43.111  8826  8826 I UEI.SmartControl: Get version...
08-10 07:41:43.131  8826  8889 D UEI.SmartControl: serial port data available: 21
,08-10 07:41:43.157  8826  8826 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-10 07:41:43.161  8826  8826 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-10 07:41:43.161  8826  8826 I UEI.SmartControl: QS saving settings...
08-10 07:41:43.165  8826  8826 D UEI.SmartControl: IR Blaster version: 25672567
08-10 07:41:43.183  8826  8889 D UEI.SmartControl: serial port data available: 4
,08-10 07:41:43.213  8826  8826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-10 07:41:43.214  8826  8826 E UEI.SmartControl: Services init done
08-10 07:41:43.215  8826  8826 D UEI.SmartControl: QS Service init finished
08-10 07:41:43.216  8826  8826 D UEI.SmartControl: QS Service version name: 2.1.91
08-10 07:41:43.216  8826  8826 D UEI.SmartControl: QS Service version code: 201091
08-10 07:41:43.218  8826  8892 I UEI.SmartControl: Device manager: loading config....
08-10 07:41:43.218  8826  8826 D UEI.SmartControl: Service requested: Control
08-10 07:41:43.218  8826  8892 D UEI.SmartControl: ----------- loading internal config...
08-10 07:41:43.226  8826  8892 E UEI.SmartControl: Loading SETTINGS...
08-10 07:41:43.228  8826  8826 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-10 07:41:43.234  1037  1900 I ActivityManager: Killing 8456:com.lge.email/u0a23 (adj 15): empty #17
08-10 07:41:43.238  8826  8892 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-10 07:41:43.255  8826  8891 I UEI.SmartControl: Notify AllClients services are ready: 0
08-10 07:41:43.255  8826  8891 D UEI.SmartControl: -----service ready thread exits
,08-10 07:41:43.263  1037  1578 W libprocessgroup: failed to open /acct/uid_10023/pid_8456/cgroup.procs: No such file or directory
08-10 07:41:43.266  8826  8826 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2d96a30e that was originally bound here
08-10 07:41:43.266  8826  8826 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@2d96a30e that was originally bound here
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:43.266  8826  8826 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 07:41:43.267  8826  8826 D UEI.SmartControl: Internal service binding...
,08-10 07:41:43.754  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1928888522] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 07:41:43.757  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=6.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1928888525] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-10 07:41:43.757  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 07:41:43.771  8826  8888 D UEI.SmartControl: Internal timer expired: 2
,08-10 07:41:46.781  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1928891549] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-10 07:41:46.797  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.2 bcn=0 [on:0 tx:0 rx:0 period:15] from screen [on:0 period:1928891564] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 07:41:46.797  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-10 07:41:47.198  8826  8837 E UEI.SmartControl: file observer is disposed!
,08-10 07:41:47.585  1605  1605 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-10 07:41:47.585  1605  1605 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-10 07:41:47.602  1037  1546 D WifiController: battery changed pluggedType: 2
,08-10 07:41:47.606  1944  2103 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-10 07:41:47.606  1944  2103 D LEDHandler: Battery Level Remaining: 100%
08-10 07:41:47.606  1944  2103 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-10 07:41:47.609  1605  1605 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-10 07:41:47.609  1605  1605 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-10 07:41:47.612  7864  8115 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-10 07:41:47.613  1605  1605 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-10 07:41:47.614  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 07:41:47.614  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 07:41:48.213  8826  8893 D UEI.SmartControl: Internal timer expired: 3
,08-10 07:41:48.213  8826  8893 D UEI.SmartControl: unbind internal service
,08-10 07:41:48.238  8826  8826 D UEI.SmartControl: Service.onUnbind: IControl
,08-10 07:41:48.244  8826  8826 D UEI.SmartControl: Service.onDestroy
08-10 07:41:48.244  8826  8826 D UEI.SmartControl: Lock is in USE false
08-10 07:41:48.244  8826  8826 D UEI.SmartControl: unbind internal service
08-10 07:41:48.245  8826  8826 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@35621c41
08-10 07:41:48.245  8826  8826 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-10 07:41:48.245  8826  8826 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-10 07:41:48.245  8826  8826 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-10 07:41:48.245  8826  8826 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-10 07:41:48.246  8826  8826 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-10 07:41:48.246  8826  8826 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-10 07:41:48.246  8826  8826 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-10 07:41:48.246  8826  8826 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-10 07:41:48.246  8826  8826 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 07:41:48.246  8826  8826 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:48.246  8826  8826 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:48.246  8826  8826 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:48.246  8826  8826 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:48.246  8826  8826 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:48.247  8826  8826 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 07:41:48.247  8826  8826 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@35621c41
08-10 07:41:48.248  8826  8826 D serial_port: close(fd = 24)
08-10 07:41:48.251  8826  8826 I UEI.SmartControl: Serial port is closed.
08-10 07:41:48.251  8826  8826 I UEI.SmartControl: Serial port is closed.
08-10 07:41:48.251  8826  8826 D UEI.SmartControl: Blaster closed
08-10 07:41:48.251  8826  8826 D UEI.SmartControl: Shut down QS...
08-10 07:41:48.251  8826  8826 D UEI.SmartControl: Stopping QS lib
08-10 07:41:48.253  8826  8826 D UEI.SmartControl: QS lib stop result = true
08-10 07:41:48.254  8826  8826 D UEI.SmartControl: Stopped QS lib
08-10 07:41:48.254  8826  8826 D UEI.SmartControl: QS shutdown complete
08-10 07:41:48.447  1037  1541 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 07:41:48.447  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 07:41:48.448  1037  1541 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 07:41:48.449  1037  1541 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 07:41:48.449  1037  1541 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-10 07:41:48.450  1037  1541 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-10 07:41:49.523  6960  7027 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-10 07:41:49.523  6960  7027 I jxcore-log: 
,08-10 07:41:49.814  1037  1541 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1928894582] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 07:41:49.815  1037  1541 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2447 sc=60 link=72 tx=1.9, 0.0, 0.0  rx=1.6 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1928894583] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-10 07:41:49.815  1037  1541 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-10 07:41:49.874  8898  8898 D AndroidRuntime: 
08-10 07:41:49.874  8898  8898 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-10 07:41:49.879  8898  8898 D AndroidRuntime: CheckJNI is OFF
08-10 07:41:50.004  8898  8898 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 07:41:50.015  1037  1100 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-10 07:41:50.015  1037  1100 I ActivityManager: Killing 6960:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-10 07:41:50.054  1037  1546 D WifiService: Client connection lost with reason: 4
,08-10 07:41:50.058  1037  1926 I WindowState: WIN DEATH: Window{3b72120a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 07:41:50.084  1037  1926 D InputDispatcher: Window went away: Window{3b72120a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 07:41:50.234  1037  1100 I ActivityManager:   Force finishing activity ActivityRecord{11042d77 u0 com.test.thalitest/.MainActivity t4}
,08-10 07:41:50.267   339   364 E GBMv2   : DFP En is all cleared set to be enabled
,08-10 07:41:50.274  1037  1974 W ActivityManager: Spurious death for ProcessRecord{2ce8ba10 6960:com.test.thalitest/u0a118}, curProc for 6960: null
08-10 07:41:50.275  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-10 07:41:50.277  1037  1125 I ActivityManager:   Force finishing activity ActivityRecord{11042d77 u0 com.test.thalitest/.MainActivity t4 f}
08-10 07:41:50.277  1037  1125 W ActivityManager: Duplicate finish request for ActivityRecord{11042d77 u0 com.test.thalitest/.MainActivity t4 f}
,08-10 07:41:50.308  1944  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-10 07:41:50.309  1944  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2fb4b1bf co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
08-10 07:41:50.310  1944  4295 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-10 07:41:50.311  1944  4295 D SplitWindowPolicy: topRunningActivity=ActivityInfo{16d2108c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
08-10 07:41:50.321  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-10 07:41:50.324  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-10 07:41:50.326  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-10 07:41:50.338  2460  2645 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 07:41:50.342  1037  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-10 07:41:50.343  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-10 07:41:50.345  4798  4798 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-10 07:41:50.345  4798  4798 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-10 07:41:50.346  4798  4798 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-10 07:41:50.346  4798  4798 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-10 07:41:50.346  4798  4798 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 07:41:50.346  4798  4798 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 07:41:50.346  4798  4798 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:50.346  4798  4798 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-10 07:41:50.346  4798  4798 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 07:41:50.346  4798  4798 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 07:41:50.346  4798  4798 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-10 07:41:50.346  4798  4798 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-10 07:41:50.348  3800  3800 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-10 07:41:50.348  7864  7864 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-10 07:41:50.349  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-10 07:41:50.372  4910  4910 I art     : Explicit concurrent mark sweep GC freed 15658(895KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 618us total 84.800ms
,08-10 07:41:50.388  1037  1098 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-10 07:41:50.414  8309  8309 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-10 07:41:50.416  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-10 07:41:50.417  2035  2128 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-10 07:41:50.431  1037  1997 V SIM_STK : Menu title from STK is T-Mobile
,08-10 07:41:50.439  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-10 07:41:50.439  1908  1908 D ActionManagerService: notifyUserLog: 1000003
08-10 07:41:50.440  3800  4789 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-10 07:41:50.442  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-10 07:41:50.443  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-10 07:41:50.443  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-10 07:41:50.444  1605  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 07:41:50.444  1605  1665 D KeyguardModel: createShortcutInfo...
,08-10 07:41:50.449  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-10 07:41:50.450  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-10 07:41:50.451  1605  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 07:41:50.451  1605  1665 D KeyguardModel: createShortcutInfo...
08-10 07:41:50.452  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-10 07:41:50.452  1870  1870 D SplitUIService: removed split : 
08-10 07:41:50.456  2182  2182 I ConfigService: onCreate
,08-10 07:41:50.463  1605  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-10 07:41:50.463  1605  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:50.463  1605  1665 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-10 07:41:50.464  1605  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 07:41:50.469  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-10 07:41:50.471  2182  2182 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-10 07:41:50.471  2182  2182 I ConfigService: onBind returning update interface
08-10 07:41:50.472  3800  4785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 07:41:50.473  1908  1908 D ActionManagerService: notifyUserLog: 1000004
08-10 07:41:50.473  3800  4789 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-10 07:41:50.474  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , display: false
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , animation: false }
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , display: false
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , animation: false }
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1470393742816
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , create_time: 1470393743569
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , display: false
08-10 07:41:50.475  2035  2035 I GBoardWebViewUtils: , animation: false }
08-10 07:41:50.476  1605  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 07:41:50.476  1605  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 07:41:50.483  1818  1818 I ConfigFetchService: service connected
,08-10 07:41:50.489  2182  2182 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-10 07:41:50.489  2182  2182 I ConfigService: onBind returning config service
08-10 07:41:50.491  2035  8932 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-10 07:41:50.492  1605  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 07:41:50.492  1605  1665 D KeyguardModel: createShortcutInfo...
08-10 07:41:50.493  1037  1037 I art     : Explicit concurrent mark sweep GC freed 27219(1750KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 3.101ms total 191.104ms
08-10 07:41:50.495  2182  2182 I ConfigService: onDestroy
,08-10 07:41:50.496  1037  1125 I art     : WaitForGcToComplete blocked for 185.741ms for cause Explicit
08-10 07:41:50.499  1605  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-10 07:41:50.499  1605  1665 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:50.500  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-10 07:41:50.500  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-10 07:41:50.500  1605  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 07:41:50.500  1605  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 07:41:50.501  1605  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 07:41:50.501  1605  1665 D KeyguardModel: createShortcutInfo...
08-10 07:41:50.505  1605  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:50.505  1605  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 07:41:50.505  1605  1665 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 07:41:50.505  1605  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 07:41:50.505  1605  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 07:41:50.505  1605  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 07:41:50.510  1605  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 07:41:50.511  1605  1665 D KeyguardModel: createShortcutInfo...
,08-10 07:41:50.513  1818  8933 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-10 07:41:50.513  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-10 07:41:50.513  1870  1870 I SplitUIService: split app #11
08-10 07:41:50.525  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-10 07:41:50.525  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-10 07:41:50.529  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 07:41:50.529  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-10 07:41:50.538  1605  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 07:41:50.538  1605  1665 D KeyguardModel: createShortcutInfo...
08-10 07:41:50.553  1037  1578 V SIM_STK : Menu title from STK is T-Mobile
,08-10 07:41:50.553  1037  1578 V SIM_STK : Menu title from STK is T-Mobile
08-10 07:41:50.565  7269  7269 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-10 07:41:50.578  1037  1897 V SIM_STK : Menu title from STK is T-Mobile
,08-10 07:41:50.592  5785  8940 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-10 07:41:50.605  1037  1578 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-10 07:41:50.607  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-10 07:41:50.608  7864  7864 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-10 07:41:50.608  1605  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 07:41:50.608  1605  1665 D KeyguardModel: createShortcutInfo...
08-10 07:41:50.610  1605  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 07:41:50.610  1605  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 07:41:50.610  1818  8942 I PeopleContactsSync: CP2 sync disabled
08-10 07:41:50.612  2329  8943 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-10 07:41:50.614  1605  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 07:41:50.614  1605  1665 D KeyguardModel: createShortcutInfo...
08-10 07:41:50.615  1605  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 07:41:50.616  1605  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 07:41:50.617  1605  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 07:41:50.617  1605  1665 D KeyguardModel: createShortcutInfo...
08-10 07:41:50.619  1605  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 07:41:50.619  1605  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-10 07:41:50.620  1605  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 07:41:50.620  1605  1665 D KeyguardModel: createShortcutInfo...
08-10 07:41:50.626  1037  1037 D administrator: Handling package changes for user 0
08-10 07:41:50.637  1037  1926 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8944 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-10 07:41:50.637  2035  2050 I art     : Background partial concurrent mark sweep GC freed 7138(325KB) AllocSpace objects, 6(19MB) LOS objects, 34% free, 60MB/92MB, paused 12.639ms total 35.090ms
,08-10 07:41:50.642  1818  4995 I Icing   : doRemovePackageData com.test.thalitest
08-10 07:41:50.653  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-10 07:41:50.653  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-10 07:41:50.658   325   433 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-10 07:41:50.658  3244  8961 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-10 07:41:50.684  1818  8939 W GmsApplication: Using Auth Proxy for data requests.
,08-10 07:41:50.697  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-10 07:41:50.698  1818  8939 W GmsApplication: Using Auth Proxy for data requests.
08-10 07:41:50.700  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-10 07:41:50.702  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-10 07:41:50.703  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-10 07:41:50.704  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-10 07:41:50.705  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-10 07:41:50.721  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-10 07:41:50.721  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 07:41:50.722  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9d960a7 u0 com.lge.launcher2/.Launcher t3} time:371980
08-10 07:41:50.726  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-10 07:41:50.726  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-10 07:41:50.727  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 07:41:50.728  1037  1580 D TaskPersister: removeObsoleteFile: deleting file=4_task.xml
08-10 07:41:50.734  2035  2195 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-10 07:41:50.734  2035  2195 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-10 07:41:50.736  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-10 07:41:50.737  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-10 07:41:50.737  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 07:41:50.744  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-10 07:41:50.748  2035  2035 D [Concierge]WidgetView: change position of spinner
08-10 07:41:50.750  2621  2621 D [Concierge]Service: onStartCommand(). Type : 8
08-10 07:41:50.750  2621  2621 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-10 07:41:50.750  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1470807710750
08-10 07:41:50.751  8944  8944 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:50.751  8944  8944 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 07:41:50.752  8944  8944 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 07:41:50.752  8944  8944 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-10 07:41:50.753  2621  2621 D [Concierge]Service: Update widget ID : 11
08-10 07:41:50.753  2621  2621 D [Concierge]Service: onStartCommand(). Type : 0
08-10 07:41:50.764  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 376994111
08-10 07:41:50.765  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-10 07:41:50.765  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-10 07:41:50.768  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@16fcd51d
08-10 07:41:50.768  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-10 07:41:50.769  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-10 07:41:50.770  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 07:41:50.775  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-10 07:41:50.775  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-10 07:41:50.776  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470807366527, New one : 1470807710750
08-10 07:41:50.776  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-10 07:41:50.776  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-10 07:41:50.776  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-10 07:41:50.776  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 07:41:50.778  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-10 07:41:50.779  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-10 07:41:50.781  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-10 07:41:50.782  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-10 07:41:50.783  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-10 07:41:50.786  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 07:41:50.786  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 07:41:50.817  1037  1098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 07:41:50.818  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-10 07:41:50.821  1037  1098 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-10 07:41:50.823  8944  8944 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-10 07:41:50.826  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-10 07:41:50.826  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-10 07:41:50.827  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-10 07:41:50.831  8944  8944 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-10 07:41:50.849  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-10 07:41:50.855  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@101f72e7 time:372112
08-10 07:41:50.857  1037  1125 I art     : Explicit concurrent mark sweep GC freed 10974(575KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.069ms total 361.402ms
08-10 07:41:50.863  8944  8944 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 07:41:50.881  8944  8944 D LgDataFeature: LgDataFeature() Constructor: none
08-10 07:41:50.882  8944  8944 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-10 07:41:50.924  8898  8898 D AndroidRuntime: Shutting down VM
08-10 07:41:50.927  8898  8910 W art     : No such thread id for suspend: 13
,08-10 07:41:50.939  8944  8944 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-10 07:41:50.948  1037  1053 I ActivityManager: Killing 8240:com.lge.formmanager/u0a26 (adj 15): empty #17
08-10 07:41:50.991  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-10 07:41:51.024  1998  1998 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-10 07:41:51.024  1998  1998 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-10 07:41:51.024  1037  1997 W libprocessgroup: failed to open /acct/uid_10026/pid_8240/cgroup.procs: No such file or directory
,08-10 07:41:51.025  1998  1998 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-10 07:41:51.028  8309  8309 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-10 07:41:51.029  2035  2887 I GBoardtInterface: onReloaded()
08-10 07:41:51.030  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-10 07:41:51.060  1037  2011 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8971 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-10 07:41:51.062  3800  4785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 07:41:51.065  3800  3819 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 07:41:51.073  1908  1908 D ActionManagerService: notifyUserLog: 1000001
,08-10 07:41:51.074  3800  4789 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-10 07:41:51.074  3800  4789 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-10 07:41:51.078  1908  1908 D ActionManagerService: notifyUserLog: 1000001
08-10 07:41:51.078  3800  4789 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-10 07:41:51.079  3800  4789 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-10 07:41:51.079  3800  4789 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-10 07:41:51.079  3800  4789 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-10 07:41:51.079  3800  4785 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-10 07:41:51.081  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-10 07:41:51.081  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-10 07:41:51.083  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-10 07:41:51.083  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-10 07:41:51.085  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-10 07:41:51.085  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1470393742816&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-10 07:41:51.124  8971  8971 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-10 07:41:51.124  8971  8971 W LG Account v2.2: No ProfileInfo entries
08-10 07:41:51.124  8971  8971 I LG Account v2.2: isEnabled: false
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Country: EU
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Operator: OPEN
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Ranking support: false
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Comfort support: false
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Accessory: true
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Health device: true
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Extra Pedometer: false
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Blood glucose device: false
08-10 07:41:51.124  8971  8971 I Feature : [Lifetracker]Device Number: 3
08-10 07:41:51.125  8971  8971 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-10 07:41:51.156  1037  1925 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8990 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-10 07:41:51.156  1037  1925 I ActivityManager: Killing 8522:com.android.chrome/u0a57 (adj 15): empty #17
,08-10 07:41:51.262  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=9012 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-10 07:41:51.265  1037  2036 W libprocessgroup: failed to open /acct/uid_10057/pid_8522/cgroup.procs: No such file or directory
08-10 07:41:51.268  4798  4825 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: Error inserting f004=14 f005=9012 f002=1470807711265 f003=com.android.defcontainer f006=10004
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-10 07:41:51.269  4798  4825 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)

```
