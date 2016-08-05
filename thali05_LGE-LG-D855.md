#### Test 79751015d1afc27_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-05 11:00:00.079  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:00:00.079  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:00:00.079  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:00:00.080  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:00:00.094  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:00:00.094  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:00:00.095  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:00:00.096  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:00:00.361  6181  6181 D AndroidRuntime: 
08-05 11:00:00.361  6181  6181 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 11:00:00.366  6181  6181 D AndroidRuntime: CheckJNI is OFF
08-05 11:00:00.481  6181  6181 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 11:00:00.496  1032  1955 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 11:00:00.508  1937  3889 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-05 11:00:00.510  1032  1955 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-05 11:00:00.511  1032  1955 D ActivityManager: setTaskToReturnTo : TaskRecord{250e474 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 11:00:00.511  1032  1955 D ActivityManager: setTaskToReturnTo : TaskRecord{250e474 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-05 11:00:00.513  1032  1955 D WindowStateEx: AppWindowTokenEx init.. 
08-05 11:00:00.513   340   352 E GBMv2   : DFP En is all cleared set to be enabled
08-05 11:00:00.543  1032  1955 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6201 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 11:00:00.544  6181  6181 D AndroidRuntime: Shutting down VM
08-05 11:00:00.615  1937  1952 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-05 11:00:00.615  1937  1952 D SplitWindowPolicy: topRunningActivity=ActivityInfo{29ead080 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 11:00:00.616  1937  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-05 11:00:00.617  1937  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2781f6b9 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-05 11:00:00.700  6201  6201 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-05 11:00:00.804  6201  6201 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 11:00:00.815  6201  6201 I LibraryLoader: Loading: webviewchromium
08-05 11:00:00.818  6201  6201 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 740-745)
,08-05 11:00:00.819  6201  6201 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:00:00.839  6201  6201 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b50cf5c}
,08-05 11:00:00.840  6201  6201 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:00:00.841  6201  6201 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 11:00:00.854  6201  6201 I BrowserStartupController: Initializing chromium process, renderers=0
08-05 11:00:00.855  6201  6201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 11:00:00.866  6201  6226 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-05 11:00:00.871  6201  6201 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-05 11:00:00.872  6201  6201 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-05 11:00:00.872  6201  6201 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-05 11:00:00.880   322  1385 V AudioPolicyService: registerClient() client 0xb0410420, uid 10118
08-05 11:00:00.891  6201  6201 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:00:00.891  6201  6201 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:00:00.891  6201  6201 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:00:00.891  6201  6201 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:00:00.891  6201  6201 I Adreno-EGL: Remote Branch: 
08-05 11:00:00.891  6201  6201 I Adreno-EGL: Local Patches: 
08-05 11:00:00.891  6201  6201 I Adreno-EGL: Reconstruct Branch: 
,08-05 11:00:00.902  1032  1115 D BluetoothManagerService: Message: 20
08-05 11:00:00.902  1032  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3020bd5e:true
,08-05 11:00:00.988  6201  6236 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-05 11:00:00.994  6201  6201 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-05 11:00:01.014  6201  6201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 11:00:01.019  6201  6201 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-05 11:00:01.023  6201  6201 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-05 11:00:01.027  6201  6201 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,08-05 11:00:01.027  6201  6201 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-05 11:00:01.044  6201  6201 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-05 11:00:01.052  6201  6201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 11:00:01.052  6201  6201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 11:00:01.092  6201  6249 D OpenGLRenderer: Render dirty regions requested: true
08-05 11:00:01.093  6201  6249 I OpenGLRenderer: Initialized EGL, version 1.4
08-05 11:00:01.101  6201  6249 D OpenGLRenderer: Enabling debug mode 0
,08-05 11:00:01.113  6201  6201 D Atlas   : Validating map...
08-05 11:00:01.114  1032  1089 W ActivityManager: Activity pause timeout for ActivityRecord{7c4cd9d u0 com.test.thalitest/.MainActivity t40}
,08-05 11:00:01.118  1032  1594 D SplitWindow: check instance of lgWin Window{39175628 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 11:00:01.167  6201  6247 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 11:00:01.167  6201  6247 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:00:01.245  1032  1116 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +631ms (total +731ms)
,08-05 11:00:01.248  1032  1116 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7c4cd9d u0 com.test.thalitest/.MainActivity t40} time:341174
08-05 11:00:01.258  6201  6201 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@51c0ddb time:341185
,08-05 11:00:01.369  6201  6201 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-05 11:00:01.369  6201  6201 I chromium: 
,08-05 11:00:01.437  6201  6201 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 11:00:01.589  6201  6261 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,08-05 11:00:01.607  6201  6261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 11:00:01.607  6201  6261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 11:00:01.607  6201  6261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 11:00:01.607  6201  6261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 11:00:01.607  6201  6261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 11:00:01.607  6201  6261 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1457baf added. We now have 1 listener(s)
,08-05 11:00:01.613  1032  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:01.617  6201  6261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-05 11:00:01.621  6201  6261 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-05 11:00:01.623  6201  6261 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:01.623  6201  6261 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-05 11:00:01.633  6201  6261 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@386c1e9a added. We now have 1 listener(s)
08-05 11:00:01.634  6201  6261 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:00:01.639  1032  1539 D WifiService: New client listening to asynchronous messages
08-05 11:00:01.643  6201  6261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:00:01.644  6201  6261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 11:00:01.644  6201  6261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 11:00:01.644  6201  6261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 11:00:01.644  6201  6261 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-05 11:00:01.648  6201  6261 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:01.648  1032  1571 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:00:01.649  6201  6261 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-05 11:00:01.658  6201  6261 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 11:00:01.658  6201  6261 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:01.658  6201  6261 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:01.658  6201  6261 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:01.658  6201  6261 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:01.658  6201  6261 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:01.658  6201  6261 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:01.658  6201  6261 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:01.658  6201  6261 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:01.658  6201  6261 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 11:00:01.658  6201  6261 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:01.659  6201  6261 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 11:00:01.660  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:00:01.703  6201  6247 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-05 11:00:01.703  6201  6247 I chromium: 
,08-05 11:00:01.764  6201  6201 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 11:00:01.922   340   354 E GBMv2   : DFP En is all cleared set to be enabled
08-05 11:00:01.922   340   354 E GBMv2   : Set value is all cleared set the max
08-05 11:00:01.922   340   354 I GBMv2   : DFP Enabled. Ignore VFP set
,08-05 11:00:02.787  6201  6264 W jxcore-log: Initializing JXcore engine
08-05 11:00:02.787  6201  6264 W jxcore-log: JXcore engine is ready
,08-05 11:00:02.823  6264  6264 W Thread-696: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[8379]" dev="sockfs" ino=8379 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 11:00:02.823  6264  6264 W Thread-696: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 11:00:02.823  6264  6264 W Thread-696: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8537]" dev="sockfs" ino=8537 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-05 11:00:02.823  6264  6264 W Thread-696: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-05 11:00:02.823  6264  6264 W Thread-696: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[30061]" dev="sockfs" ino=30061 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-05 11:00:02.849  6201  6264 W jxcore-log: Starting JXcore engine
,08-05 11:00:02.940  6201  6264 W jxcore-log: Platform android
08-05 11:00:02.940  6201  6264 W jxcore-log: 
08-05 11:00:02.940  6201  6264 W jxcore-log: Process ARCH arm
08-05 11:00:02.940  6201  6264 W jxcore-log: 
,08-05 11:00:03.265  6201  6264 I jxcore-log: JXcore Cordova bridge is ready!
08-05 11:00:03.265  6201  6264 I jxcore-log: 
08-05 11:00:03.266  6201  6264 W jxcore-log: JXcore engine is started
,08-05 11:00:03.275  6201  6261 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 11:00:03.278  6201  6201 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 11:00:05.086  1032  1375 D PowerManagerServiceEx: acquireWakeLockInternal: lock=426705868, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1032
,08-05 11:00:05.127  2567  2567 D [Concierge]Service: onStartCommand(). Type : 9
,08-05 11:00:05.159  1032  1032 D PowerManagerServiceEx: releaseWakeLockInternal: lock=426705868 [*alarm*], flags=0x0
,08-05 11:00:18.964  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 11:00:18.964  6201  6264 I jxcore-log: 
,08-05 11:00:18.967  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 11:00:18.967  6201  6264 I jxcore-log: 
08-05 11:00:18.971  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:18.971  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:18.971  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:18.971  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:18.971  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:18.971  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:18.971  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:18.971  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:18.974  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:18.976  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 11:00:18.976  6201  6264 I jxcore-log: 
08-05 11:00:18.977  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 11:00:18.977  6201  6264 I jxcore-log: 
,08-05 11:00:19.308  6201  6264 D ExecuteNativeTests: Running unit tests
,08-05 11:00:19.392  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:00:19.393  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 added. We now have 2 listener(s)
,08-05 11:00:19.393  1032  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:19.395  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:19.395  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:19.396  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:19.396  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:19.396  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e added. We now have 2 listener(s)
08-05 11:00:19.396  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:19.396  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:00:19.398  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.401  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:19.401  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:19.401  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:19.401  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:19.401  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:19.401  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:19.401  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:19.401  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:19.402  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:19.402  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:19.403  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:19.406  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 11:00:19.409  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:00:19.409  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-05 11:00:19.411  6201  6264 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-05 11:00:19.413  6201  6264 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 11:00:19.413  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:00:19.413  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:00:19.413  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:00:19.414  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.415  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.415  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.415  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.415  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.415  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:19.415  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:19.416  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 removed from the list
08-05 11:00:19.416  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.416  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e removed from the list
08-05 11:00:19.416  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.416  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.418  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.418  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.419  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.419  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.419  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.420  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.422  6201  6264 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-05 11:00:19.423  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.423  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.423  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operati,on, skipping...
08-05 11:00:19.423  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.423  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.423  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.423  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.423  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.423  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.423  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.423  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.423  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.423  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:00:19.423  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.424  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.424  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-05 11:00:19.424  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.424  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
,08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 11:00:19.428  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 11:00:19.428  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.428  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.428  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.429  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.429  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.429  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.429  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.429  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.429  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.429  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:00:19.429  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.429  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.429  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.429  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.430  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.430  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.430  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.430  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
,08-05 11:00:19.431  6201  6264 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 11:00:19.432  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.434  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:19.434  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:19.434  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:19.434  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:19.434  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:19.434  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:19.434  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:19.434  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:19.439  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:00:19.439  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:19.440  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:19.440  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:00:19.440  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:00:19.440  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:00:19.440  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.440  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 11:00:19.443  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:00:19.443  1032  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:19.447  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 11:00:19.451  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 11:00:19.452  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 11:00:19.453  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 11:00:19.454  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:19.455  6201  6264 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:00:19.455  6201  6264 I io.jxcore.node.ConnectionHelper: start: OK
08-05 11:00:19.458  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.458  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.458  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.458  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.458  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.458  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:19.458  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.458  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.459  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.459  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.459  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.459  6201  6264 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 11:00:19.460  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.462  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:19.462  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:19.462  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:19.462  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:19.462  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:19.462  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:19.462  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:19.462  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:19.462  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:19.462  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:19.463  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:19.463  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:00:19.463  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:00:19.463  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, sta,rt advertiser: false
08-05 11:00:19.463  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.463  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:00:19.466  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:00:19.466  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 11:00:19.467  6201  6264 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:00:19.467  6201  6264 I io.jxcore.node.ConnectionHelper: start: OK
08-05 11:00:19.468  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.468  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.468  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.468  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.468  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.468  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:19.468  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.468  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.468  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.468  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.468  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.469  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.469  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.469  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.469  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.471  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.471  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.471  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.471  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.471  6201  6264 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 11:00:19.472  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.474  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:19.474  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:19.474  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:19.474  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:19.474  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:19.474  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:19.474  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:19.474  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:19.475  6201  6264 D io.jx,core.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:19.475  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:19.475  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:00:19.475  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:00:19.475  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:00:19.475  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.475  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:00:19.476  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:19.477  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:00:19.478  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:19.478  6201  6264 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:00:19.479  6201  6264 I io.jxcore.node.ConnectionHelper: start: OK
08-05 11:00:19.479  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.479  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.479  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.479  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.479  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.480  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.480  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.480  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.480  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:19.480  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.480  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.480  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.480  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.480  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.480  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.480  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.481  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.481  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.481  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.481  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.481  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.481  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.482  6201  6264 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 11:00:19.482  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.482  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.482  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.482  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.482  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.482  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.483  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.483  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.483  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.483  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.483  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.483  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.483  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.483  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.483  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.483  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.484  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.484  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.484  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.484  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.485  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 11:00:19.485  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.485  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.485  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.485  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.485  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.485  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.485  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.485  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.485  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.485  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.485  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.485  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.485  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.485  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.486  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.486  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.486  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.486  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.486  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.486  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.487  6201  6264 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 11:00:19.487  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.487  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.487  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.487  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.487  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.487  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.487  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.487  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.487  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.487  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.487  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.487  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.487  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.487  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.488  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.488  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.488  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.488  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.488  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.488  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.489  6201  6264 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 11:00:19.489  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.489  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.489  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.489  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.489  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.489  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.489  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.489  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.489  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.489  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.489  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.489  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.489  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.489  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.490  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.490  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.490  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.490  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.490  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.490  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.491  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 11:00:19.492  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:00:19.492  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:00:19.492  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:00:19.492  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 11:00:19.492  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:00:19.492  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.492  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.492  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.496  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.496  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.496  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.496  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.496  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.496  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.496  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.496  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.496  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.496  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.496  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.499  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.499  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.499  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.499  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.499  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.499  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.502  6201  6264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:00:19.502  6201  6264 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 11:00:19.502  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 11:00:19.507  6201  6264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:00:19.507  6201  6264 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 11:00:19.507  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 11:00:19.507  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 11:00:19.507  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 11:00:19.507  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 11:00:19.507  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 11:00:19.507  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 11:00:19.507  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 11:00:19.508  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 11:00:19.509  6201  6264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 11:00:19.509  6201  6264 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 11:00:19.509  6201  6264 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 11:00:19.509  6201  6264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:00:19.509  6201  6264 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 11:00:19.509  6201  6264 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 11:00:19.509  6201  6264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:00:19.509  6201  6264 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 11:00:19.509  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 11:00:19.511  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-05 11:00:19.512  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 11:00:19.512  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 11:00:19.513  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 11:00:19.513  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 11:00:19.513  6201  6264 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 11:00:19.513  6201  6264 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:00:19.513  6201  6264 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 11:00:19.513  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.513  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.513  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.514  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.514  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.514  6201  6270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 760)
08-05 11:00:19.514  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.514  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 11:00:19.515  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.515  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.515  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.515  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.515  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.515  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.515  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.515  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.515  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.515  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.516  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.516  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.516  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.516  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.516  6201  6264 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 11:00:19.516  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.516  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.516  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.517  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.517  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.517  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.517  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.517  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.517  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.517  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.517  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.517  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.517  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.517  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.517  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.517  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.518  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.518  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.518  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.518  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.518  6201  6264 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 11:00:19.522  6201  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 760
08-05 11:00:19.523  6201  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 760)
08-05 11:00:19.520  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.524  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.524  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.524  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.524  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.524  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.524  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.524  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.524  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.524  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.524  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.524  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.524  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.524  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.525  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.525  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.526  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.526  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.526  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.526  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.526  6201  6264 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 11:00:19.526  6201  6264 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 11:00:19.526  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:00:19.526  6201  6264 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-05 11:00:19.527  6201  6264 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 11:00:19.527  6201  6264 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 11:00:19.527  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:00:19.527  6201  6264 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 11:00:19.527  6201  6264 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 11:00:19.527  6201  6264 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 11:00:19.527  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:00:19.527  6201  6264 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 11:00:19.527  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.527  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.527  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.527  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.528  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.528  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.528  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.528  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.528  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.528  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.528  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.528  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.528  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.528  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.523  6201  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 760)
08-05 11:00:19.528  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.528  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.529  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.529  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.529  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.529  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.529  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.529  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.529  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.529  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.529  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.529  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.529  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.529  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.529  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.530  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.530  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.530  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.530  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.530  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.530  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.530  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.530  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.530  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.530  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.530  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.530  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.530  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.530  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.530  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.530  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.531  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.531  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.531  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.531  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.531  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.531  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.532  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.532  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.532  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.532  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.537  6201  6264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 11:00:19.537  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.538  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 11:00:19.538  6201  6264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 11:00:19.538  6201  6264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 11:00:19.539  6201  6201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 11:00:19.539  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 11:00:19.539  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 11:00:19.540  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.540  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 11:00:19.540  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 11:00:19.540  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 11:00:19.540  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.540  6201  6264 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 11:00:19.541  6201  6272 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 11:00:19.541  6201  6272 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 11:00:19.541  6201  6201 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 11:00:19.541  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.541  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.541  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 11:00:19.541  6201  6264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 11:00:19.541  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 11:00:19.542  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 11:00:19.543  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:19.543  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:19.543  6201  6264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 11:00:19.543  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.543  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.543  6201  6264 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:00:19.544  6201  6201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:00:19.544  6201  6201 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 11:00:19.544  6201  6201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:00:19.544  6201  6201 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:00:19.546  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.546  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.546  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.546  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.546  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.546  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.546  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.546  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.546  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.546  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.546  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.546  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.546  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.546  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.546  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.547  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.547  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.547  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.547  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.548  6201  6264 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 11:00:19.548  6201  6264 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 11:00:19.548  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:00:19.548  6201  6264 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:00:19.549  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.549  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.549  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.549  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.549  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.549  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.549  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.549  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.549  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.549  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.549  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.549  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.549  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.549  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.550  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.550  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.550  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.550  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.551  1032  1882 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:19.551  1032  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:19.552  1032  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:19.552  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.552  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.552  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.552  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.552  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.552  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.552  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.553  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.553  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.553  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.553  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluet,oothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.553  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.553  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.553  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.553  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.553  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.553  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.553  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.554  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:19.554  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:19.554  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:19.555  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:19.555  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.555  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.555  6201  6264 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c10049 not in the list
08-05 11:00:19.555  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.555  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.555  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:19.555  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.555  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:19.555  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:19.555  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:00:19.560  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:19.560  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:19.560  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:19.560  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b98d4e not in the list
08-05 11:00:19.561  6201  6264 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 11:00:19.561  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:00:19.561  6201  6264 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 11:00:19.561  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:00:19.561  6201  6264 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 11:00:19.561  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:00:19.562  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 11:00:19.562  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 11:00:19.563  6201  6264 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 11:00:19.563  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 11:00:19.563  6201  6264 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 11:00:19.563  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 11:00:19.563  6201  6264 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 11:00:19.563  6201  6264 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 11:00:19.564  6201  6264 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-05 11:00:19.564  6201  6264 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 11:00:19.564  6201  6264 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 11:00:19.564  6201  6264 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 11:00:19.564  6201  6264 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 11:00:19.564  6201  6264 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 11:00:19.565  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:19.565  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@123a6c67 added. We now have 2 listener(s)
08-05 11:00:19.565  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:19.566  6201  6264 D BluetoothAdapter: enable(): BT is already enabled..!
08-05 11:00:19.569  1032  1594 D WifiServiceImplEx: setWifiEnabled: true pid=6201, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:00:19.569  1032  1594 D WifiService: setWifiEnabled: true pid=6201, uid=10118
08-05 11:00:19.569  1032  1594 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 11:00:19.570  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:19.570  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e91ba14 added. We now have 3 listener(s)
08-05 11:00:19.570  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:19.572  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:19.572  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a3682bd added. We now have 4 listener(s)
08-05 11:00:19.572  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:19.574  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:19.574  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@203970b2 added. We now have 5 listener(s)
08-05 11:00:19.574  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:19.575  1032  1571 D WifiServiceImplEx: setWifiEnabled: false pid=6201, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:00:19.575  1032  1571 D WifiService: setWifiEnabled: false pid=6201, uid=10118
08-05 11:00:19.575  1032  1571 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 11:00:19.583  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:00:19.584  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:00:19.584  1032  1534 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:19.584  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-05 11:00:19.584  1032  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:19.584  1032  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:19.584  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:19.585  1032  1532 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:19.585  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:19.585  1032  1532 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3ae5335a
08-05 11:00:19.585  1032  1532 D LGWifiP2pService: P2pDisablingState
08-05 11:00:19.586  1032  1532 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:19.586  1032  1532 D LGWifiP2pService: p2p socket connection lost
08-05 11:00:19.586  1032  1532 D LGWifiP2pService: P2pDisabledState
08-05 11:00:19.587  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 11:00:19.587  1937  1937 D WfdsService: WifiP2pState is changed : false
08-05 11:00:19.587  1937  2292 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 11:00:19.587  1937  2292 D WfdsService: Set the WFDS Monitor: false
08-05 11:00:19.587  1937  2292 D WfdsMonitor: WFDS Monitor is stopped
08-05 11:00:19.587  1937  2292 D WfdsService: STATE : WfdsDisabledState - enter
08-05 11:00:19.587  1937  2850 D CtrlSupplicant: Received on exit socket, terminate
08-05 11:00:19.588  1937  2850 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 11:00:19.588  1937  2850 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 11:00:19.588  1937  2850 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
,08-05 11:00:19.588  1937  2293 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 11:00:19.589  1937  2292 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 11:00:19.590  1032  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 11:00:19.590   318   890 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:00:19.590  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 11:00:19.591  1032  1032 D RttService: SCAN_AVAILABLE : 1
08-05 11:00:19.591  1032  1552 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:19.591  1032  1553 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:19.596  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 11:00:19.596  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:19.598  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:19.599  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-05 11:00:19.600  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:19.600  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:19.600  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:00:19.603  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-05 11:00:19.603  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:19.603  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:19.603  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:00:19.603  1032  1534 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 11:00:19.604  1032  1534 D WifiNative-p2p0: TERMINATE: returned true
08-05 11:00:19.604  1032  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:00:19.604  1032  1534 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:00:19.604  1032  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:00:19.605  1032  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:19.605  1032  1936 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d34dc2b mBinding = false
08-05 11:00:19.606  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 11:00:19.610  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:19.610  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:19.610  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:19.610  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:19.610  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:19.610  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:19.610  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:19.610  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-0,5 11:00:19.611  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:19.611  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 11:00:19.612  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:19.612  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-05 11:00:19.618  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:00:19.618  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-05 11:00:19.618  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-05 11:00:19.618  1032  1115 D BluetoothManagerService: Message: 2
08-05 11:00:19.619  1032  1115 D BluetoothManagerService: Sending off request.
08-05 11:00:19.619  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:19.620  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 11:00:19.620  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:19.621  3832  4179 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 11:00:19.622  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:19.622  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:19.622  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:19.622  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:19.622  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:19.622  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:19.622  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:19.622  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:19.622  3832  3918 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 11:00:19.622  3832  3918 D BluetoothAdapterProperties: Setting state to 13
08-05 11:00:19.622  3832  3918 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 11:00:19.622  3832  3918 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 11:00:19.622  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:19.622  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:19.622  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:19.625  3832  3921 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:00:19.626  3832  3918 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 11:00:19.626  3832  3918 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 11:00:19.627  3832  4183 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-05 11:00:19.627  3832  4260 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:19.628  3832  4259 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:19.628  3832  4182 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 11:00:19.628  3832  4182 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:19.628  3832  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 11:00:19.628  3832  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 11:00:19.628  3832  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 11:00:19.628  3832  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 11:00:19.628  3832  4182 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 11:00:19.628  3832  4182 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 11:00:19.628  3832  4262 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:19.628  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:19.628  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:19.628  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:19.628  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:19.628  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:19.628  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:00:19.628  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:19.628  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:19.628  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:19.629  3832  3918 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 11:00:19.629  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:19.629  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:19.630  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 11:00:19.630  3832  4055 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-05 11:00:19.630  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:19.630  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:19.630  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:19.630  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:19.631  3832  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:00:19.631  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:19.631  3832  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:00:19.631  38,32  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:19.631  3832  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:00:19.631  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 11:00:19.631  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 11:00:19.631  3832  4055 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 11:00:19.632  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:19.632  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:19.632  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:19.632  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:19.632  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:19.632  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:00:19.632  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:19.632  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:19.632  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:19.632  1032  1115 D BluetoothManagerService: Message: 60
08-05 11:00:19.632  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 11:00:19.632  1032  1115 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 11:00:19.632  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:19.632  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:19.635  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:19.636  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:19.637  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:19.642  3832  3832 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:19.642  3832  3832 D BluetoothMapService: STATE_TURNING_OFF
08-05 11:00:19.642  3832  3832 V BtOppService: Receiver DISABLED_ACTION 
08-05 11:00:19.642  3832  3832 V BluetoothMapService: Handler(): got msg=4
08-05 11:00:19.642  3832  3832 D BluetoothMapService: MAP Service closeService in
08-05 11:00:19.642  3832  3832 D BluetoothMapMasInstance: MAP Service shutdown
08-05 11:00:19.642  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:00:19.642  3832  3832 V BluetoothMapService: MAP Service closeService out
08-05 11:00:19.642  3832  3832 I BtOppRfcommListener: stopping Accept Thread
08-05 11:00:19.642  3832  3832 V BtOppRfcommListener: close mBtServerSocket
08-05 11:00:19.643  3832  3832 V BtOppRfcommListener: waiting for thread to terminate
08-05 11:00:19.643  3832  4259 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 11:00:19.644  3832  3832 V BtOppRfcommListener: done waiting for thread to terminate
08-05 11:00:19.644  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:00:19.645  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:00:19.648  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:19.652  6201  6270 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-05 11:00:19.652  6201  6270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 760)
08-05 11:00:19.672  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:19.675  1032  1089 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6286 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 11:00:19.675  3832  3832 V BtOppService: onDestroy
08-05 11:00:19.678  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:00:19.684  2713  2713 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 11:00:19.684  2713  2713 I wpa_supplicant: monitor socket send errors count : 1
08-05 11:00:19.684  2713  2713 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1937-2\x00 that cannot receive messages
,08-05 11:00:19.685  1032  2831 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 11:00:19.686  1032  2831 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 11:00:19.709  1032  1918 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6304 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 11:00:19.709  3832  3832 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
,08-05 11:00:19.721  2713  2713 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:00:19.721  2713  2713 W wpa_supplicant: USIM:  scard_deinit function
,08-05 11:00:19.723  1032  2831 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 11:00:19.723  1032  2831 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:00:19.723  1032  2831 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:00:19.724  1032  2831 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 11:00:19.724  1032  2831 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:19.724  1032  2831 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:19.724  1032  1534 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=359635
08-05 11:00:19.725  1032  1534 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=359635
08-05 11:00:19.725  1032  1534 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=359636  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 11:00:19.725  1032  1115 D Tethering: InitialState.processMessage what=4
08-05 11:00:19.725  1032  1534 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=359636  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 11:00:19.725  1032  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 11:00:19.727  1032  1534 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:19.727   318  6320 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 11:00:19.727  1032  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:19.727  1032  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 11:00:19.732  6286  6286 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:00:19.732  6286  6286 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-05 11:00:19.732  6286  6286 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:00:19.733  6286  6286 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-05 11:00:19.734  6286  6286 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-05 11:00:19.734  6286  6286 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 11:00:19.771  6304  6304 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-05 11:00:19.774  6304  6304 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:00:19.774  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:19.776  1032  1049 I ActivityManager: Killing 4843:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-05 11:00:19.806  2713  2713 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 11:00:19.806  1032  2831 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 11:00:19.806  1032  2831 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
,08-05 11:00:19.806  1032  2831 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 11:00:19.806  1032  1534 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
08-05 11:00:19.814  1032  2009 W libprocessgroup: failed to open /acct/uid_10014/pid_4843/cgroup.procs: No such file or directory
08-05 11:00:19.867  6286  6286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 11:00:19.873  3832  3832 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:00:19.874  3832  3832 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:19.874  3832  3832 V BluetoothPbapReceiver: ***********state = 13
08-05 11:00:19.875  3832  3832 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 11:00:19.876  3832  3832 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:19.876  3832  3832 V BluetoothPbapService: state: 13
08-05 11:00:19.876  3832  3832 V BluetoothPbapService: Pbap Service closeService in
08-05 11:00:19.879  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:00:19.881  3832  3832 V BluetoothPbapService: successfully stopped pbap service
,08-05 11:00:19.882  3832  3832 V BluetoothPbapService: Pbap Service closeService out
08-05 11:00:19.882  3832  3832 V BluetoothPbapService: Pbap Service onDestroy
08-05 11:00:19.882  3832  3832 V BluetoothPbapService: Pbap Service closeService in
08-05 11:00:19.882  3832  3832 V BluetoothPbapService: Pbap Service closeService out
08-05 11:00:19.882  3832  3832 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 11:00:19.901  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:19.950  1032  1954 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6327 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-05 11:00:19.952  1937  1937 D WfdsService: Supplicant Connection state is changed : false
08-05 11:00:19.952  1937  2292 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 11:00:19.952  1937  2292 D WfdsService: Set the WFDS Monitor: false
08-05 11:00:19.952  1937  2292 D WfdsMonitor: WFDS Monitor is stopped
08-05 11:00:19.953  1032  1534 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 11:00:19.953  1032  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:00:19.953  1032  1534 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:00:19.953  1032  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:00:19.956  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-05 11:00:19.956  1032  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 11:00:19.957  1032  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 11:00:19.957  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 11:00:19.959  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:19.959  2493  2493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:19.960  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:19.961  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:19.978  6286  6286 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:00:19.978  6286  6286 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:00:19.989  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:00:19.998  1032  1115 D BluetoothManagerService: Message: 20
08-05 11:00:19.998  1032  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@374fdf5d:true
08-05 11:00:20.012  1032  1115 D BluetoothManagerService: Message: 30
,08-05 11:00:20.018  1032  1115 D BluetoothManagerService: Message: 30
08-05 11:00:20.021  6286  6286 D LocalBluetoothProfileManager: Adding local MAP profile
08-05 11:00:20.022  6286  6286 D BluetoothMap: Create BluetoothMap proxy object
08-05 11:00:20.023  1032  1115 D BluetoothManagerService: Message: 30
08-05 11:00:20.027  1032  1115 D BluetoothManagerService: Message: 30
,08-05 11:00:20.030  6286  6286 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-05 11:00:20.032  6286  6286 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-05 11:00:20.044  6201  6201 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 11:00:20.049  6286  6286 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-05 11:00:20.054  6286  6286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-05 11:00:20.072  6286  6286 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:00:20.074  6327  6327 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-05 11:00:20.074  6327  6327 W LG Account v2.2: No ProfileInfo entries
08-05 11:00:20.074  6327  6327 I LG Account v2.2: isEnabled: false
08-05 11:00:20.075  6327  6327 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-05 11:00:20.075  6327  6327 I Feature : [Lifetracker]Country: EU
08-05 11:00:20.075  6327  6327 I Feature : [Lifetracker]Operator: OPEN
08-05 11:00:20.075  6327  6327 I Feature : [Lifetracker]Ranking support: false
08-05 11:00:20.075  6327  6327 I Feature : [Lifetracker]Comfort support: false
08-05 11:00:20.075  6327  6327 I Feature : [Lifetracker]Accessory: true
08-05 11:00:20.075  6327  6327 I Feature : [Lifetracker]Health device: true
08-05 11:00:20.075  6327  6327 I Feature : [Lifetracker]Extra Pedometer: false
08-05 11:00:20.076  6327  6327 I Feature : [Lifetracker]Blood glucose device: false
08-05 11:00:20.076  6327  6327 I Feature : [Lifetracker]Device Number: 3
08-05 11:00:20.079  1032  2009 I ActivityManager: Killing 2121:com.lge.music/u0a34 (adj 15): empty #17
08-05 11:00:20.087  6286  6286 D BluetoothInputDevice: Proxy object connected
,08-05 11:00:20.088  6286  6286 D HidProfile: Bluetooth service connected
08-05 11:00:20.089  6286  6286 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 11:00:20.091  6286  6286 D PanProfile: Bluetooth service connected
08-05 11:00:20.092  6286  6286 D BluetoothMap: Proxy object connected
08-05 11:00:20.093  6286  6286 D MapProfile: Bluetooth service connected
08-05 11:00:20.093  6286  6286 D BluetoothMap: getConnectedDevices()
08-05 11:00:20.093  6286  6286 D BluetoothMap: Bluetooth is Not enabled
08-05 11:00:20.094  6286  6286 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 11:00:20.100   322  1384 V AudioFlinger: 2121 died, releasing its sessions
08-05 11:00:20.100   322  1384 V AudioFlinger:  pid 1848 @ 0
08-05 11:00:20.100   322  1384 V AudioFlinger:  pid 3426 @ 1
08-05 11:00:20.100   322  1384 V AudioFlinger:  pid 3426 @ 2
,08-05 11:00:20.126  1032  1571 W libprocessgroup: failed to open /acct/uid_10034/pid_2121/cgroup.procs: No such file or directory
,08-05 11:00:20.138  6286  6286 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 11:00:20.146  6286  6286 D BluetoothPermissionRequest: onReceive
08-05 11:00:20.151  6286  6286 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 11:00:20.168  1032  1918 I ActivityManager: Killing 5714:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-05 11:00:20.168  6286  6286 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 11:00:20.207  3832  3832 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 11:00:20.207  3832  3832 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-05 11:00:20.208  3832  3832 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 11:00:20.305  1032  1918 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6356 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-05 11:00:20.307  1032  1973 W libprocessgroup: failed to open /acct/uid_10008/pid_5714/cgroup.procs: No such file or directory
08-05 11:00:20.317  3832  3832 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:20.317  3832  3832 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 11:00:20.318  3832  3832 V BluetoothFtpService: Ftp Service onStartCommand
08-05 11:00:20.319  3832  3832 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:20.319  3832  3832 V BluetoothFtpService: Ftp Service closeService
08-05 11:00:20.319  3832  3832 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-05 11:00:20.320  3832  3832 V BluetoothFtpService: successfully stopped ftp service
,08-05 11:00:20.321  3832  3832 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:00:20.321  3832  3832 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:00:20.321  3832  3832 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:00:20.322  3832  3832 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:20.322  3832  3832 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 11:00:20.322  3832  3832 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 11:00:20.325  3832  3832 V BluetoothFtpService: Ftp Service onDestroy
08-05 11:00:20.325  3832  3832 V BluetoothFtpService: Ftp Service closeService
08-05 11:00:20.376  1032  1900 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6373 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 11:00:20.376  3832  3832 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:20.376  3832  3832 V BluetoothSapService: state: 13
08-05 11:00:20.377  3832  3832 V BluetoothSapService: Stopping SAP server process
08-05 11:00:20.379  3832  3832 V BluetoothSapService: Sap Service closeSapService in
08-05 11:00:20.379  3832  3832 V BluetoothSapService: Close listen Socket : 
08-05 11:00:20.380  3832  3832 V BluetoothSapService: Close rfcomm Socket : 
08-05 11:00:20.380  3832  3832 V BluetoothSapService: Close sapd  Socket : 
,08-05 11:00:20.381  3832  3832 V BluetoothSapService: Sap Service closeSapService out
08-05 11:00:20.381  3832  3832 V BluetoothSapService: Sap Service onDestroy
08-05 11:00:20.381  3832  3832 V BluetoothSapService: Sap Service closeSapService in
08-05 11:00:20.381  3832  3832 V BluetoothSapService: Close listen Socket : 
08-05 11:00:20.381  3832  3832 V BluetoothSapService: Close rfcomm Socket : 
08-05 11:00:20.382  3832  3832 V BluetoothSapService: Close sapd  Socket : 
08-05 11:00:20.383  3832  3832 V BluetoothSapService: Sap Service closeSapService out
08-05 11:00:20.414  6356  6356 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 11:00:20.446  6356  6356 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-05 11:00:20.459  6373  6373 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-05 11:00:20.478  1032  1936 I ActivityManager: Killing 5748:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-05 11:00:20.482  6356  6356 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-05 11:00:20.483  6356  6356 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-05 11:00:20.483  6356  6356 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-05 11:00:20.484  6356  6356 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-05 11:00:20.484  6356  6356 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-05 11:00:20.485  6356  6356 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-05 11:00:20.489  6356  6356 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-05 11:00:20.509  1032  1973 W libprocessgroup: failed to open /acct/uid_10011/pid_5748/cgroup.procs: No such file or directory
,08-05 11:00:20.514  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:20.516  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:20.529  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 11:00:20.531  6356  6356 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-05 11:00:20.533  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:20.534  6356  6356 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-05 11:00:20.539  6304  6304 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 11:00:20.539  6304  6304 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:00:20.539  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:20.547  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:20.560  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:20.570  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:20.571  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 11:00:20.573  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:00:20.635  3832  3921 D bt_hci_bdroid: cleanup
08-05 11:00:20.635  3832  4055 W bt-btif : ag scb idx 1 not allocated
08-05 11:00:20.636  3832  4055 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:20.636  3832  4161 I bt_userial_mct: exiting userial_read_thread
08-05 11:00:20.636  3832  4161 D bt_userial_mct: Leaving userial_evt_read_thread()
,08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:00:20.636  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:20.637  3832  4055 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:00:20.637  3832  4055 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:20.637  3832  4055 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:00:20.637  3832  3921 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 11:00:20.637  3832  4055 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 11:00:20.637  3832  4057 I bt_lpm  : LPM is already off!!!
08-05 11:00:20.637  3832  4057 I bt_vendor: hw_epilog_process
08-05 11:00:20.638  3832  3921 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 11:00:20.638  3832  3921 D bt_userial_mct: userial_close
08-05 11:00:20.640  3832  3921 E bt_userial_mct: pthread_join() FAILED result:3
08-05 11:00:20.640  3832  3921 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 11:00:20.644  1032  1900 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6400 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-05 11:00:20.738  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:00:20.741  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 11:00:20.748  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:20.769  6400  6422 W FormManager: Network not available. Please check & try again.
,08-05 11:00:20.781  6400  6427 V FormManager: Network unavailable.
,08-05 11:00:20.783  6400  6427 V FormManager: Network unavailable.
08-05 11:00:20.783  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:00:20.783  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:00:20.784  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:00:20.784  6286  6286 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:00:20.784  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:00:20.793  6286  6286 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-05 11:00:20.793  3832  3921 D bt_hci_bdroid: set_power 0
08-05 11:00:20.793  3832  3921 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 11:00:20.793  3832  3921 I bt_vendor: bluetooth satus is on
08-05 11:00:20.793  3832  3921 I bt_vendor: bt-vendor : resetting BT status
08-05 11:00:20.793  3832  3921 I bt_vendor: Starting hciattach daemon
08-05 11:00:20.793  3832  3921 I bt_vendor: try to set false
08-05 11:00:20.793  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:00:20.794  3832  3921 I bt_vendor: Starting hciattach daemon
08-05 11:00:20.794  3832  3921 I bt_vendor: try to set false
08-05 11:00:20.795  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:00:20.795  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:00:20.795  6286  6286 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:00:20.795  3832  3921 I bt_vendor: cleanup
08-05 11:00:20.795  3832  4055 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 11:00:20.795  6286  6286 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:00:20.796  3832  3921 I GKI_LINUX: GKI_exit_task 0 done
08-05 11:00:20.796  3832  3921 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 11:00:20.797  3832  3918 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 11:00:20.798  1032  1955 I ActivityManager: Killing 5637:com.android.defcontainer/u0a4 (adj 15): empty #17
08-05 11:00:20.847  1032  1048 W libprocessgroup: failed to open /acct/uid_10004/pid_5637/cgroup.procs: No such file or directory
,08-05 11:00:20.850  3832  3832 D HeadsetService: Received stop request...Stopping profile...
08-05 11:00:20.854  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:00:20.855  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:00:20.862  3832  3832 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 11:00:20.862  3832  3832 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:00:20.863  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dbe8265
08-05 11:00:20.863  3832  3959 D HeadsetStateMachine: Exit Disconnected: -1
08-05 11:00:20.865  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-05 11:00:20.868  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-05 11:00:20.869  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-05 11:00:20.869  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-05 11:00:20.870  1032  1032 D BluetoothHeadset: Proxy object disconnected
08-05 11:00:20.870  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 11:00:20.873  3832  3832 D A2dpService: Received stop request...Stopping profile...
08-05 11:00:20.874  3832  4039 D A2dpStateMachine: Exit Disconnected: -1
08-05 11:00:20.875  3832  3832 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 11:00:20.877  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:20.878  3832  3832 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 11:00:20.878  3832  3832 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:00:20.878  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dbe8265
08-05 11:00:20.881  3832  3832 D HeadsetStateMachine: Unbinding service...
08-05 11:00:20.881  1032  1032 D BluetoothA2dp: Proxy object disconnected
08-05 11:00:20.881  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-05 11:00:20.886  3832  3832 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:00:20.886  3832  3832 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:00:20.886  3832  3832 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:00:20.886  3832  3832 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:00:20.886  3832  3832 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 11:00:20.886  3832  3832 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:00:20.886  3832  3832 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 11:00:20.887  3832  3832 D HidService: Received stop request...Stopping profile...
08-05 11:00:20.887  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dbe8265
08-05 11:00:20.894  3832  3918 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 11:00:20.895  6286  6286 D BluetoothInputDevice: Proxy object disconnected
08-05 11:00:20.895  6286  6286 D HidProfile: Bluetooth service disconnected
,08-05 11:00:20.897  3832  3832 D HealthService: Received stop request...Stopping profile...
08-05 11:00:20.897  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dbe8265
08-05 11:00:20.900  4238  6433 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:00:20.903  4238  6432 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:00:20.903  3832  3832 D PanService: Received stop request...Stopping profile...
08-05 11:00:20.904  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dbe8265
08-05 11:00:20.905  6304  6304 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-05 11:00:20.905  6304  6304 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:00:20.905  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:20.906  3832  3832 I BluetoothA2dpServiceJni: cleanupNative
08-05 11:00:20.906  3832  4041 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 11:00:20.907  3832  3832 I GKI_LINUX: GKI_exit_task 2 done
08-05 11:00:20.907  3832  3832 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 11:00:20.907  3832  3832 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 11:00:20.908  3832  3832 D BtGatt.GattService: Received stop request...Stopping profile...
,08-05 11:00:20.908  3832  3832 D BtGatt.GattService: stop()
08-05 11:00:20.908  3832  3832 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 11:00:20.908  4238  6433 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:00:20.909  6286  6286 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 11:00:20.909  6286  6286 D PanProfile: Bluetooth service disconnected
08-05 11:00:20.915  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:00:20.919  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dbe8265
,08-05 11:00:20.923  3832  3832 D BluetoothMapService: Received stop request...Stopping profile...
08-05 11:00:20.923  3832  3832 D BluetoothMapService: stop()
08-05 11:00:20.923  6400  6436 W FormManager: Network not available. Please check & try again.
08-05 11:00:20.924  3832  3832 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 11:00:20.924  3832  3832 D BluetoothMapEmailAppObserver: removeReceiver()
08-05 11:00:20.925  3832  3832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dbe8265
08-05 11:00:20.926  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:20.927  6286  6286 D BluetoothMap: Proxy object disconnected
08-05 11:00:20.927  6286  6286 D MapProfile: Bluetooth service disconnected
08-05 11:00:20.927  3832  3832 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 11:00:20.927  3832  3832 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 11:00:20.927  3832  3832 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 11:00:20.928  3832  3832 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:00:20.928  3832  3832 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:00:20.928  3832  3832 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 11:00:20.929  3832  3832 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 11:00:20.930  3832  3832 V BluetoothMapService: Handler(): got msg=4
08-05 11:00:20.930  3832  3832 D BluetoothMapService: MAP Service closeService in
08-05 11:00:20.930  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:00:20.930  3832  3832 V BluetoothMapService: MAP Service closeService out
08-05 11:00:20.930  6400  6437 V FormManager: Network unavailable.
08-05 11:00:20.930  3832  3832 D BluetoothMapService: cleanup()
08-05 11:00:20.930  3832  3832 D BluetoothMapService: MAP Service closeService in
08-05 11:00:20.930  3832  3832 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:00:20.930  3832  3832 V BluetoothMapService: MAP Service closeService out
08-05 11:00:20.930  3832  3918 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 11:00:20.930  3832  3918 D BluetoothAdapterProperties: Setting state to 10
08-05 11:00:20.930  3832  3918 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 11:00:20.931  1032  1115 D BluetoothManagerService: Message: 60
08-05 11:00:20.931  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 11:00:20.931  1032  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-05 11:00:20.931  3832  3918 I BluetoothAdapterState: Entering OffState
08-05 11:00:20.931  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 11:00:20.938  6286  6438 D BluetoothPan: onBluetoothStateChange on: false
08-05 11:00:20.939  1032  1115 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:00:20.939  1848  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:00:20.941  6286  6303 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 11:00:20.942  6400  6437 V FormManager: Network unavailable.
08-05 11:00:20.942  6286  6302 D BluetoothMap: onBluetoothStateChange: up=false
08-05 11:00:20.943  1032  1115 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:00:20.943  1848  2430 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 11:00:20.948  6286  6438 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 11:00:20.955  1032  1115 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 11:00:20.955  1032  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-05 11:00:20.958  1032  1115 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 11:00:20.958  6356  6356 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 11:00:20.959  1032  1115 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 11:00:20.959  1032  1115 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d34dc2b mBinding = false
08-05 11:00:20.960  1032  1115 D BluetoothManagerService: Sending unbind request.
08-05 11:00:20.961  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 11:00:20.962  6356  6356 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-05 11:00:20.962  1032  1115 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 11:00:20.964  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:20.965  1937  2131 D LGBluetoothAPIService: Message: 2
08-05 11:00:20.965  1937  2131 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@37989afe mBinding = false
08-05 11:00:20.965  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:00:20.965  1937  2131 D LGBluetoothAPIService: Sending unbind request.
08-05 11:00:20.967  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:20.968  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:20.968  3832  3921 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-05 11:00:20.969  3832  3832 I GKI_LINUX: GKI_exit_task 1 done
08-05 11:00:20.969  3832  3832 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 11:00:20.969  3832  3832 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 11:00:20.969  3832  3832 I art     : --- WEIRD: removing null entry 246
08-05 11:00:20.970  3832  3832 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-05 11:00:20.970  3832  3832 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 11:00:20.971  6286  6286 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 11:00:20.972  6286  6286 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 11:00:20.972  6286  6286 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 11:00:20.974  1599  1599 D BluetoothAdapter: 976700317: getState() :  mService = null. Returning STATE_OFF
08-05 11:00:20.974  1599  1599 D BluetoothAdapter: 976700317: getState() :  mService = null. Returning STATE_OFF
08-05 11:00:20.975  3832  3832 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 11:00:20.978  6286  6286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 11:00:20.979  3832  3832 I art     : System.exit called, status: 0
08-05 11:00:20.979  3832  3832 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 11:00:20.986  6286  6286 D DockEventReceiver: finishStartingService: stopping service
08-05 11:00:21.007   322   322 V AudioFlinger: 3832 died, releasing its sessions
08-05 11:00:21.007   322   322 V AudioFlinger:  pid 1848 @ 0
08-05 11:00:21.007   322   322 V AudioFlinger:  pid 3426 @ 1
08-05 11:00:21.007   322   322 V AudioFlinger:  pid 3426 @ 2
08-05 11:00:21.008  6286  6286 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-05 11:00:21.012  6356  6356 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:00:21.012  6356  6356 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:00:21.018  6356  6356 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-05 11:00:21.019  6356  6356 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-05 11:00:21.019  6356  6356 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-05 11:00:21.019  6356  6356 V SoundPool: doLoad: loading sample sampleID=1
,08-05 11:00:21.020  6356  6356 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 11:00:21.022  6356  6443 V SoundPool: Start decode
,08-05 11:00:21.022  6356  6443 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-05 11:00:21.023   322  1384 V MediaPlayerService: decode(23, 10857164, 17813)
08-05 11:00:21.023   322  1384 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-05 11:00:21.023   322  1384 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-05 11:00:21.023   322  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-05 11:00:21.023   322  1384 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-05 11:00:21.023   322  1384 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-05 11:00:21.023   322  1384 V MediaPlayerService: player type = 3
,08-05 11:00:21.023   322  1384 V AwesomePlayer: AwesomePlayer create()
08-05 11:00:21.023   322  1384 V AwesomePlayer: reset_l() 
08-05 11:00:21.023   322  1384 V AwesomePlayer: cancelPlayerEvents
08-05 11:00:21.023   322  1384 V AwesomePlayer: setAudioSink() 
08-05 11:00:21.023   322  1384 V AwesomePlayer: reset_l() 
08-05 11:00:21.023   322  1384 V AudioCache: notify(0xb10152c0, 8, 0, 0)
08-05 11:00:21.023   322  1384 V AudioCache: ignored
08-05 11:00:21.023   322  1384 V AwesomePlayer: cancelPlayerEvents
08-05 11:00:21.023   322  1384 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-05 11:00:21.023   322  1384 V AwesomePlayer: setDataSource_l dataSource
08-05 11:00:21.023   322  1384 V LGParserOSAL: SniffLGParser start
08-05 11:00:21.023   322  1384 V LGParserOSAL: MainType:5, SubType=0
,08-05 11:00:21.023   322  1384 V LGParserOSAL: #### check Mime : application/ogg
08-05 11:00:21.024   322  1384 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-05 11:00:21.024   322  1384 E MediaExtractor: Use LGExtractor :application/ogg 
08-05 11:00:21.059   322  1384 V LGParserOSAL: supported mime: application/ogg
08-05 11:00:21.059   322  1384 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-05 11:00:21.059   322  1384 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-05 11:00:21.059   322  1384 V AwesomePlayer: mBitrate = -1 bits/sec
,08-05 11:00:21.059   322  1384 V AwesomePlayer: AudioTrack Setting
08-05 11:00:21.059   322  1384 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-05 11:00:21.059   322  1384 V AwesomePlayer: setAudioSource() 
08-05 11:00:21.059   322  1384 V MediaPlayerService: prepare
08-05 11:00:21.059   322  1384 V AwesomePlayer: prepareAsync_l() 
,08-05 11:00:21.059   322  1384 V MediaPlayerService: wait for prepare
08-05 11:00:21.059   322  6444 V AwesomePlayer: onPrepareAsyncEvent() 
08-05 11:00:21.060   322  6444 V AwesomePlayer: initAudioDecoder() 
08-05 11:00:21.060   322  6444 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 11:00:21.060   322  6444 V AudioSystem: isOffloadSupported()
08-05 11:00:21.060   322  6444 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 11:00:21.060   322  6444 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-05 11:00:21.060   322  6444 I AudioFlinger: isAudioPlaybackHookOn() false
,08-05 11:00:21.060   322  6444 V AwesomePlayer: getUseOffload() = 0 
08-05 11:00:21.060   322  6444 V OMXCodec: OMXCodec::Create
08-05 11:00:21.060   322  6444 V OMXCodec: findMatchingCodecs()
08-05 11:00:21.060   322  6444 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-05 11:00:21.060   322  6444 V OMXCodec: matchingCodecs.size()=1
08-05 11:00:21.060   322  6444 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-05 11:00:21.062   322  6444 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-05 11:00:21.062   322  6444 V LGCodecAdapter: LG Codec Adapter start
,08-05 11:00:21.062   322  6444 V OMXCodec: OMXCodec Createtor,
,08-05 11:00:21.062   322  6444 V OMXCodec: setComponentRole
08-05 11:00:21.063   322  6444 V OMXCodec: configureCodec protected=0,
08-05 11:00:21.063   322  6444 V LGCodecAdapter: called getLGCodecSpecificData
,08-05 11:00:21.063   322  6444 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA,
08-05 11:00:21.063   322  6444 V LGCodecOSAL: Called LGconfigureCodecMETA
,08-05 11:00:21.063   322  6444 V LGCodecOSAL: Called LGconfigureCodecMSG
08-05 11:00:21.063   322  6444 V LGCodecOSAL: Not support LGCodec
,08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
,08-05 11:00:21.063   322  6444 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-05 11:00:21.063   322  6444 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
,08-05 11:00:21.063   322  6444 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-05 11:00:21.063   322  6444 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-05 11:00:21.063   322  6444 V AudioSystem: isOffloadSupported(),
08-05 11:00:21.063   322  6444 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-05 11:00:21.063   322  6444 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false,
08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-05 11:00:21.063   322  6444 V OMXCodec: init()
,08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-05 11:00:21.063   322  6444 V OMXCodec: allocateBuffers
,08-05 11:00:21.063   322  6444 V OMXCodec: allocateBuffersOnPort portIndex=0
08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on input port
08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
,08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-05 11:00:21.063   322  6444 V OMXCodec: allocateBuffersOnPort portIndex=1,
08-05 11:00:21.063   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 11:00:21.064   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port,
08-05 11:00:21.064   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-05 11:00:21.064   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-05 11:00:21.064   322  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fba0 on output port
08-05 11:00:21.064   322  6444 V OMXCodec: init() mAsyncCompletion wait!!! 
,08-05 11:00:21.064   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 11:00:21.064   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 11:00:21.064   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-05 11:00:21.064   322  6444 V OMXCodec: init() mAsyncCompletion wait!!! 
08-05 11:00:21.065   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
,08-05 11:00:21.065   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-05 11:00:21.065   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-05 11:00:21.065   322  6444 V OMXCodec: init() mAsyncCompletion wait free! 
08-05 11:00:21.065   322  6444 V AwesomePlayer: finishAsyncPrepare_l() 
,08-05 11:00:21.065   322  6444 V AudioCache: notify(0xb10152c0, 5, 0, 0)
08-05 11:00:21.065   322  6444 V AudioCache: ignored
08-05 11:00:21.065   322  6444 V AudioCache: notify(0xb10152c0, 1, 0, 0)
08-05 11:00:21.065   322  6444 V AudioCache: prepared
08-05 11:00:21.065   322  1384 V AudioCache: wait - success,
08-05 11:00:21.065   322  1384 V MediaPlayerService: start
08-05 11:00:21.065   322  1384 V AwesomePlayer: play_l() 
08-05 11:00:21.065   322  1384 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-05 11:00:21.065   322  1384 V AwesomePlayer: createAudioPlayer_l
08-05 11:00:21.065   322  1384 V AwesomePlayer: seekAudioIfNecessary_l() ,
08-05 11:00:21.065   322  1384 V AwesomePlayer: startAudioPlayer_l() 
08-05 11:00:21.065   322  1384 D AudioPlayer: start of Playback, useOffload 0
08-05 11:00:21.065   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data,
08-05 11:00:21.065   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
,08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048656
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048736
,08-05 11:00:21.067   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-05 11:00:21.068   322  6446 V OMXCodec: allocateBuffersOnPort portIndex=1
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fb50 on output port
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
,08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434380 on output port
08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-05 11:00:21.068   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-05 11:00:21.069   322  1384 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-05 11:00:21.069   322  1384 V AudioCache: notify(0xb10152c0, 6, 0, 0)
08-05 11:00:21.069   322  1384 V AudioCache: ignored
,08-05 11:00:21.070   322  1384 V MediaPlayerService: wait for playback complete
08-05 11:00:21.070   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.070   322  6447 V AudioCache: memcpy(0xaf004000, 0xb57ce000, 4096)
08-05 11:00:21.074   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.074   322  6447 V AudioCache: memcpy(0xaf005000, 0xb57ce000, 4096)
,08-05 11:00:21.074  1032  2028 I ActivityManager: Process com.android.bluetooth (pid 3832) has died
08-05 11:00:21.074   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.074   322  6447 V AudioCache: memcpy(0xaf006000, 0xb57ce000, 4096)
08-05 11:00:21.074  1032  2028 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-05 11:00:21.074   322  6447 V AudioCache: write(0xb57ce000, 4096)
,08-05 11:00:21.074   322  6447 V AudioCache: memcpy(0xaf007000, 0xb57ce000, 4096)
08-05 11:00:21.075   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.075   322  6447 V AudioCache: memcpy(0xaf008000, 0xb57ce000, 4096)
08-05 11:00:21.075   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.075   322  6447 V AudioCache: memcpy(0xaf009000, 0xb57ce000, 4096)
08-05 11:00:21.076   322  6447 V AudioCache: write(0xb57ce000, 4096)
,08-05 11:00:21.076   322  6447 V AudioCache: memcpy(0xaf00a000, 0xb57ce000, 4096)
08-05 11:00:21.076   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.076   322  6447 V AudioCache: memcpy(0xaf00b000, 0xb57ce000, 4096)
08-05 11:00:21.077   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.077   322  6447 V AudioCache: memcpy(0xaf00c000, 0xb57ce000, 4096)
08-05 11:00:21.077   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.077   322  6447 V AudioCache: memcpy(0xaf00d000, 0xb57ce000, 4096)
,08-05 11:00:21.078   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.078   322  6447 V AudioCache: memcpy(0xaf00e000, 0xb57ce000, 4096)
08-05 11:00:21.078   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.078   322  6447 V AudioCache: memcpy(0xaf00f000, 0xb57ce000, 4096)
08-05 11:00:21.078   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.078   322  6447 V AudioCache: memcpy(0xaf010000, 0xb57ce000, 4096)
,08-05 11:00:21.079   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.079   322  6447 V AudioCache: memcpy(0xaf011000, 0xb57ce000, 4096)
08-05 11:00:21.079   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.079   322  6447 V AudioCache: memcpy(0xaf012000, 0xb57ce000, 4096)
08-05 11:00:21.080   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.080   322  6447 V AudioCache: memcpy(0xaf013000, 0xb57ce000, 4096)
,08-05 11:00:21.080   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.080   322  6447 V AudioCache: memcpy(0xaf014000, 0xb57ce000, 4096)
08-05 11:00:21.081   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.081   322  6447 V AudioCache: memcpy(0xaf015000, 0xb57ce000, 4096)
08-05 11:00:21.081   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.081   322  6447 V AudioCache: memcpy(0xaf016000, 0xb57ce000, 4096)
,08-05 11:00:21.081   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.081   322  6447 V AudioCache: memcpy(0xaf017000, 0xb57ce000, 4096)
08-05 11:00:21.082   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.082   322  6447 V AudioCache: memcpy(0xaf018000, 0xb57ce000, 4096)
08-05 11:00:21.082   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.082   322  6447 V AudioCache: memcpy(0xaf019000, 0xb57ce000, 4096)
,08-05 11:00:21.083   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.083   322  6447 V AudioCache: memcpy(0xaf01a000, 0xb57ce000, 4096)
08-05 11:00:21.084   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.084   322  6447 V AudioCache: memcpy(0xaf01b000, 0xb57ce000, 4096)
08-05 11:00:21.085   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.085   322  6447 V AudioCache: memcpy(0xaf01c000, 0xb57ce000, 4096)
08-05 11:00:21.085   322  6447 V AudioCache: write(0xb57ce000, 4096)
,08-05 11:00:21.086   322  6447 V AudioCache: memcpy(0xaf01d000, 0xb57ce000, 4096)
08-05 11:00:21.086   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.086   322  6447 V AudioCache: memcpy(0xaf01e000, 0xb57ce000, 4096)
08-05 11:00:21.086   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.086   322  6447 V AudioCache: memcpy(0xaf01f000, 0xb57ce000, 4096)
08-05 11:00:21.087   322  6447 V AudioCache: write(0xb57ce000, 4096)
,08-05 11:00:21.087   322  6447 V AudioCache: memcpy(0xaf020000, 0xb57ce000, 4096)
08-05 11:00:21.087   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.087   322  6447 V AudioCache: memcpy(0xaf021000, 0xb57ce000, 4096)
08-05 11:00:21.087   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.087   322  6447 V AudioCache: memcpy(0xaf022000, 0xb57ce000, 4096)
08-05 11:00:21.088   322  6447 V AudioCache: write(0xb57ce000, 4096)
,08-05 11:00:21.088   322  6447 V AudioCache: memcpy(0xaf023000, 0xb57ce000, 4096)
08-05 11:00:21.088   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.088   322  6447 V AudioCache: memcpy(0xaf024000, 0xb57ce000, 4096)
08-05 11:00:21.089   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.089   322  6447 V AudioCache: memcpy(0xaf025000, 0xb57ce000, 4096)
08-05 11:00:21.089   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.089   322  6447 V AudioCache: memcpy(0xaf026000, 0xb57ce000, 4096)
,08-05 11:00:21.090   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.090   322  6447 V AudioCache: memcpy(0xaf027000, 0xb57ce000, 4096)
08-05 11:00:21.090   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.090   322  6447 V AudioCache: memcpy(0xaf028000, 0xb57ce000, 4096)
08-05 11:00:21.090   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.090   322  6447 V AudioCache: memcpy(0xaf029000, 0xb57ce000, 4096)
,08-05 11:00:21.091   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.091   322  6447 V AudioCache: memcpy(0xaf02a000, 0xb57ce000, 4096)
08-05 11:00:21.091   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.091   322  6447 V AudioCache: memcpy(0xaf02b000, 0xb57ce000, 4096)
08-05 11:00:21.092   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.092   322  6447 V AudioCache: memcpy(0xaf02c000, 0xb57ce000, 4096)
,08-05 11:00:21.092   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.092   322  6447 V AudioCache: memcpy(0xaf02d000, 0xb57ce000, 4096)
08-05 11:00:21.092  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:00:21.092   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.092   322  6447 V AudioCache: memcpy(0xaf02e000, 0xb57ce000, 4096)
08-05 11:00:21.093   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.093   322  6447 V AudioCache: memcpy(0xaf02f000, 0xb57ce000, 4096)
,08-05 11:00:21.093   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.093   322  6447 V AudioCache: memcpy(0xaf030000, 0xb57ce000, 4096)
08-05 11:00:21.094   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.094   322  6447 V AudioCache: memcpy(0xaf031000, 0xb57ce000, 4096)
08-05 11:00:21.094   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.094   322  6447 V AudioCache: memcpy(0xaf032000, 0xb57ce000, 4096)
08-05 11:00:21.095   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-05 11:00:21.095   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.095   322  6447 V AudioCache: memcpy(0xaf033000, 0xb57ce000, 4096)
08-05 11:00:21.095   322  6447 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 11:00:21.095   322  6447 V AudioCache: write(0xb57ce000, 4096)
08-05 11:00:21.095   322  6447 V AudioCache: memcpy(0xaf034000, 0xb57ce000, 4096)
08-05 11:00:21.095   322  6447 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 11:00:21.095   322  6447 V AudioCache: write(0xb57ce000, 4096)
,08-05 11:00:21.095   322  6447 V AudioCache: memcpy(0xaf035000, 0xb57ce000, 4096)
08-05 11:00:21.095   322  6447 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 11:00:21.095   322  6447 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-05 11:00:21.095   322  6447 V AwesomePlayer: postAudioEOS() 
08-05 11:00:21.096   322  6447 V AudioCache: write(0xb57ce000, 280)
08-05 11:00:21.096   322  6447 V AudioCache: memcpy(0xaf036000, 0xb57ce000, 280)
08-05 11:00:21.097   322  6444 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-05 11:00:21.097   322  6444 V AwesomePlayer: onStreamDone
,08-05 11:00:21.097   322  6444 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-05 11:00:21.097   322  6444 V AudioCache: notify(0xb10152c0, 2, 0, 0)
08-05 11:00:21.097   322  6444 V AudioCache: playback complete
08-05 11:00:21.097   322  6444 V AwesomePlayer: pause_l() 
08-05 11:00:21.097   322  6444 V AudioCache: notify(0xb10152c0, 7, 0, 0)
08-05 11:00:21.097   322  1384 V AudioCache: wait - success
08-05 11:00:21.097   322  6444 V AudioCache: ignored
08-05 11:00:21.097   322  6444 V AwesomePlayer: cancelPlayerEvents
08-05 11:00:21.097   322  1384 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
,08-05 11:00:21.098   322  6444 D AudioPlayer: Pause Playback at 1068125
08-05 11:00:21.098   322  1384 V AwesomePlayer: reset_l() 
08-05 11:00:21.098   322  1384 V AudioCache: notify(0xb10152c0, 8, 0, 0)
08-05 11:00:21.098   322  1384 V AudioCache: ignored
08-05 11:00:21.098   322  1384 V AwesomePlayer: cancelPlayerEvents
08-05 11:00:21.098   322  1384 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-05 11:00:21.098   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-05 11:00:21.098   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
,08-05 11:00:21.098   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-05 11:00:21.098   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
,08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 0
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434380 on port 1
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
,08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fb50 on port 1
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-05 11:00:21.099   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-05 11:00:21.100   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 11:00:21.100   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,08-05 11:00:21.100   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-05 11:00:21.100   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-05 11:00:21.100   322  6446 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-05 11:00:21.100   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-05 11:00:21.100   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-05 11:00:21.100   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-05 11:00:21.101   322  1384 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-05 11:00:21.101   322  1384 D AudioPlayer: AudioPlayer releasing audio source
,08-05 11:00:21.101   322  1384 D AudioPlayer: AudioPlayer done releasing audio source
08-05 11:00:21.101   322  1384 V AwesomePlayer: reset_l() 
08-05 11:00:21.101   322  1384 V AwesomePlayer: cancelPlayerEvents
08-05 11:00:21.101   322  1384 V AwesomePlayer: ~AwesomePlayer call
08-05 11:00:21.101   322  1384 V AwesomePlayer: reset_l() 
08-05 11:00:21.101   322  1384 V AwesomePlayer: cancelPlayerEvents
08-05 11:00:21.102  6356  6443 V SoundPool: close(31)
08-05 11:00:21.102  6356  6443 V SoundPool: pointer = 0x9ffd6000, size = 205080, sampleRate = 48000, numChannels = 2
,08-05 11:00:21.103  6079  6079 D UEI.SmartControl: QS Service created
08-05 11:00:21.105  6286  6286 D BluetoothPermissionRequest: onReceive
08-05 11:00:21.106  6356  6356 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-05 11:00:21.109  6286  6286 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 11:00:21.109  6286  6286 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-05 11:00:21.113  6286  6286 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-05 11:00:21.114  6079  6079 I UEI.SmartControl: Service initServices...,
08-05 11:00:21.115  6079  6079 D UEI.SmartControl: QS start get config
08-05 11:00:21.115  6356  6356 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:00:21.118  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 11:00:21.138  6356  6356 V LGMDMManager: Create singleton instance
,08-05 11:00:21.157  1032  1918 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6448 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-05 11:00:21.205  6448  6448 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 11:00:21.205  6448  6448 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:00:21.205  6448  6448 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 11:00:21.206  6448  6448 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-05 11:00:21.220  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-05 11:00:21.222  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-05 11:00:21.223  6448  6448 D BluetoothAdapterApp: Loading JNI Library
08-05 11:00:21.223  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5603
08-05 11:00:21.250  6448  6448 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1f9891e2 Instance Count = 1
,08-05 11:00:21.254  6448  6448 D BluetoothAdapterApp: onCreate
08-05 11:00:21.274  6448  6448 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-05 11:00:21.275  6448  6448 D ProfileConfigQcom: Adding HeadsetService
08-05 11:00:21.275  6448  6448 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 11:00:21.276  6448  6448 D ProfileConfigQcom: Adding A2dpService
08-05 11:00:21.276  6448  6448 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 11:00:21.277  6448  6448 D ProfileConfigQcom: Adding HidService
08-05 11:00:21.277  6448  6448 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 11:00:21.278  6448  6448 D ProfileConfigQcom: Adding HealthService
08-05 11:00:21.279  6448  6448 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 11:00:21.280  6448  6448 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 11:00:21.280  6448  6448 D ProfileConfigQcom: Adding PanService
08-05 11:00:21.281  6448  6448 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 11:00:21.281  6448  6448 D ProfileConfigQcom: Adding GattService
08-05 11:00:21.281  6448  6448 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 11:00:21.281  6448  6448 D ProfileConfigQcom: Adding BluetoothMapService
08-05 11:00:21.281  6448  6448 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 11:00:21.282  6448  6448 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 11:00:21.287  6448  6448 V LGMDMManagerInternal: Create singleton instance
08-05 11:00:21.288  6286  6286 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 11:00:21.337  6448  6448 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:00:21.341  6448  6448 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:00:21.342  6448  6448 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-05 11:00:21.342  6448  6448 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:00:21.342  6448  6448 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:21.343  6448  6448 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 11:00:21.355  6373  6373 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-05 11:00:21.379  6079  6079 I UEI.SmartControl: Supports setup maps: true
,08-05 11:00:21.381  6079  6079 D UEI.SmartControl: QS start statue = true Error code = 0,
08-05 11:00:21.381  6079  6079 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-05 11:00:21.381  6079  6079 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-05 11:00:21.382  6079  6079 I UEI.SmartControl: ### init IR Blaster...
08-05 11:00:21.385  6079  6079 D serial_port: Configuring serial port
08-05 11:00:21.385  6079  6079 E UEI.SmartControl: UEIBLaster setting for 616
08-05 11:00:21.385  6079  6079 I UEI.SmartControl: Setting serial record hearder size = 2
08-05 11:00:21.385  6079  6079 I UEI.SmartControl: configuring settings for MAXQ616
08-05 11:00:21.385  6079  6079 I UEI.SmartControl: Get version...
08-05 11:00:21.404  6079  6467 D UEI.SmartControl: serial port data available: 21
,08-05 11:00:21.430  6079  6079 D UEI.SmartControl: MAXQ616 A2-X4 software.,
,08-05 11:00:21.431  6079  6079 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-05 11:00:21.431  6079  6079 I UEI.SmartControl: QS saving settings...
,08-05 11:00:21.432  6079  6079 D UEI.SmartControl: IR Blaster version: 25672567
,08-05 11:00:21.449  6079  6467 D UEI.SmartControl: serial port data available: 4,
,08-05 11:00:21.481  6079  6470 I UEI.SmartControl: Device manager: loading config....,
,08-05 11:00:21.483  6079  6470 D UEI.SmartControl: ----------- loading internal config...
08-05 11:00:21.483  6079  6079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-05 11:00:21.487  6079  6079 E UEI.SmartControl: Services init done
08-05 11:00:21.487  6079  6079 D UEI.SmartControl: QS Service init finished
08-05 11:00:21.489  6079  6079 D UEI.SmartControl: QS Service version name: 2.1.91
08-05 11:00:21.490  6079  6079 D UEI.SmartControl: QS Service version code: 201091
08-05 11:00:21.491  6079  6079 D UEI.SmartControl: Service requested: Control
08-05 11:00:21.497  6079  6470 E UEI.SmartControl: Loading SETTINGS...
08-05 11:00:21.497  6079  6079 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-05 11:00:21.502  6356  6356 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-05 11:00:21.505  6079  6079 D UEI.SmartControl: Internal service binding...
08-05 11:00:21.506  6079  6094 I UEI.SmartControl: ------ IControl API: 11
08-05 11:00:21.506  6079  6094 D UEI.SmartControl: File observer start...
08-05 11:00:21.508  6079  6094 E UEI.SmartControl: IR Port is disabled: false
08-05 11:00:21.508  6079  6094 D UEI.SmartControl: Starting file observer...
08-05 11:00:21.511  6079  6470 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-05 11:00:21.511  6079  6094 I UEI.SmartControl: Registering callback...
08-05 11:00:21.513  6079  6095 I UEI.SmartControl: ------ IControl API: 19
,08-05 11:00:21.516  6079  6095 I UEI.SmartControl: Registering Services Ready callback...
08-05 11:00:21.540  6079  6469 I UEI.SmartControl: Notify AllClients services are ready: 0
08-05 11:00:21.540  6079  6469 D UEI.SmartControl: -----service ready thread exits
,08-05 11:00:21.541  6356  6371 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-05 11:00:21.543  6356  6441 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-05 11:00:21.543  6356  6441 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-05 11:00:21.544  6356  6356 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-05 11:00:21.546  6356  6356 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-05 11:00:21.546  6079  6094 I UEI.SmartControl: ------ IControl API: 8
08-05 11:00:21.550  6356  6356 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-05 11:00:21.551  6356  6356 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-05 11:00:21.552  6356  6356 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-05 11:00:21.553  6356  6356 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-05 11:00:21.554  6356  6356 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-05 11:00:21.555  6356  6356 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-05 11:00:21.556  6356  6356 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-05 11:00:21.560  6356  6356 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-05 11:00:21.562  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-05 11:00:21.563  6356  6356 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:00:21.563  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-05 11:00:21.564  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-05 11:00:21.565  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-05 11:00:21.566  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-05 11:00:21.567  6356  6356 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470387621566]
08-05 11:00:21.568  6356  6356 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-05 11:00:21.576  1032  1048 I ActivityManager: Killing 5796:com.lge.email/u0a23 (adj 15): empty #17
08-05 11:00:21.595  6356  6472 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-05 11:00:21.633  1032  1048 I ActivityManager: Killing 5766:com.android.contacts/u0a19 (adj 15): empty #18
,08-05 11:00:21.678  1032  1900 W libprocessgroup: failed to open /acct/uid_10019/pid_5766/cgroup.procs: No such file or directory
08-05 11:00:21.680  6356  6356 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-05 11:00:21.681  1032  1049 W libprocessgroup: failed to open /acct/uid_10023/pid_5796/cgroup.procs: No such file or directory
08-05 11:00:21.682  6356  6356 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-05 11:00:21.684  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-05 11:00:21.685  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-05 11:00:21.685  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-05 11:00:21.686  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-05 11:00:21.687  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-05 11:00:21.700  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-05 11:00:22.637  1032  1955 D WifiServiceImplEx: setWifiEnabled: true pid=6201, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:00:22.639  1032  1955 D WifiService: setWifiEnabled: true pid=6201, uid=10118
08-05 11:00:22.639  1032  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:00:22.665  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:00:22.665  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:00:22.665  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,08-05 11:00:22.669  1032  1534 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 11:00:22.669  1032  1534 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-05 11:00:22.671  1032  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 11:00:22.671  1032  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 11:00:22.672  1032  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 11:00:22.672  1032  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 11:00:22.672  1032  1534 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 11:00:22.672  1032  1534 E WifiHW  : unknown target_country: EU , set to default
08-05 11:00:22.672  1032  1534 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 11:00:22.672  1032  1534 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 11:00:22.672  1032  1534 I WifiUtil: gEnableBmps=1
08-05 11:00:23.257  1032  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 11:00:23.257  1032  1115 D Tethering: InitialState.processMessage what=4
08-05 11:00:23.258  1032  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 11:00:23.274   318   890 D SoftapController: Softap fwReload - Ok
,08-05 11:00:23.279  1032  1534 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (603ms)
08-05 11:00:23.284   318   890 D CommandListener: Setting iface cfg
08-05 11:00:23.284   318   890 D CommandListener: Trying to bring down wlan0
08-05 11:00:23.295   318   890 D CommandListener: Clearing all IP addresses on wlan0
,08-05 11:00:23.298   318  6490 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 11:00:23.302  1032  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 11:00:23.304  1032  1534 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-05 11:00:23.323  1032  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:00:23.323  1032  1534 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:00:23.323  1032  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-05 11:00:23.313  6491  6491 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:23.313  6491  6491 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:23.335  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:23.338  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-05 11:00:23.344  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:23.364  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-05 11:00:23.366  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:23.370  1032  1534 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 11:00:23.370  1032  1534 D WifiMonitor: connecting to supplicant
08-05 11:00:23.373  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:00:23.373  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:00:23.373  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:00:23.373  6286  6286 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:00:23.377  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-05 11:00:23.386  6286  6286 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:00:23.386  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:00:23.386  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:00:23.386  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:00:23.386  6286  6286 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:00:23.387  6286  6286 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:00:23.389  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:00:23.389  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:00:23.389  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:00:23.389  6286  6286 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-05 11:00:23.392  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:00:23.404  6491  6491 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 11:00:23.420  6286  6286 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:00:23.421  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:00:23.421  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:00:23.421  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:00:23.421  6286  6286 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:00:23.422  6286  6286 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:00:23.445  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:00:23.451  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:00:23.452  6491  6491 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 11:00:23.452  6491  6491 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-05 11:00:23.455  6400  6509 W FormManager: Network not available. Please check & try again.
08-05 11:00:23.455  6400  6510 V FormManager: Network unavailable.
08-05 11:00:23.458  6400  6510 V FormManager: Network unavailable.
08-05 11:00:23.458  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:00:23.647  6491  6491 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 11:00:23.668  6491  6491 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 11:00:23.675  6491  6491 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-05 11:00:23.676  6491  6491 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-05 11:00:23.677  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 11:00:23.678  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 11:00:23.678  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 11:00:23.679  1032  1534 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 11:00:23.679  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:23.680  1032  6515 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-05 11:00:23.680  1032  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:23.680  1032  6515 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 11:00:23.680  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 11:00:23.680  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 11:00:23.680  1032  1534 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 11:00:23.680  1032  1534 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 11:00:23.680  1032  6515 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:00:23.680  1032  6515 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:00:23.681  1032  1534 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 11:00:23.682  1032  1534 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 11:00:23.682  1032  1534 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 11:00:23.684  1032  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:00:23.684  1032  1534 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:00:23.684  1032  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-05 11:00:23.685  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:23.685  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:23.686  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:23.686  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:00:23.686  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:00:23.689  1032  1534 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 11:00:23.693  1937  1937 D WfdService: Waiting for WifiP2p enabling
08-05 11:00:23.694  1032  1534 D WifiNative-wlan0: SET update_config 1: returned true
08-05 11:00:23.694  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:23.695  1032  1534 D WifiConfigStore: Loading config and enabling all networks 
08-05 11:00:23.695  1032  1534 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 11:00:23.696  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:00:23.696  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:23.696  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:23.696  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:23.696  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:23.696  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:00:23.696  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:23.696  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:23.696  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:23.696  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:23.696  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:23.698  1032  1534 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-05 11:00:23.698  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:23.698  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:23.698  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:23.698  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:23.698  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:23.698  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:00:23.698  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:23.698  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:23.698  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:23.698  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:23.698  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:23.699  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 11:00:23.699  1032  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 11:00:23.709  1032  1534 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-05 11:00:23.714  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:23.721  1032  1534 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-05 11:00:23.722  1032  1534 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 11:00:23.723  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:00:23.723  1032  1534 D WifiStateMachine: enableVerboseLogging : level 2
08-05 11:00:23.723  1032  1534 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 11:00:23.724  1032  1534 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 11:00:23.724  1032  1534 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 11:00:23.724  1032  1534 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 11:00:23.725  1032  1534 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 11:00:23.725  1032  1534 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 11:00:23.725  1032  1534 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 11:00:23.726  1032  1534 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 11:00:23.726  1032  1534 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-05 11:00:23.726  1032  1534 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 11:00:23.726  1032  1534 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 11:00:23.727  1032  1534 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-05 11:00:23.727  1032  1534 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 11:00:23.727  1032  1534 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-05 11:00:23.728  1032  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 11:00:23.728  1032  1534 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 11:00:23.728  1937  1937 D WfdsService: Supplicant Connection state is changed : true
08-05 11:00:23.728  1032  1534 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 11:00:23.728  1937  2292 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 11:00:23.728  1032  1534 D WifiNative-HAL: Setting external_sim to 1
08-05 11:00:23.728  1937  2292 D WfdsService: Set the WFDS Monitor: true
08-05 11:00:23.728  1937  2292 D WfdsMonitor: WfdsMonitorThread create
08-05 11:00:23.729  1032  1534 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 11:00:23.729  1937  2292 D WfdsMonitor: WFDS Monitor is created and started
08-05 11:00:23.729  1937  2292 D WfdsService: WiFi: Supplicant connection re-established
08-05 11:00:23.729  1032  1534 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 11:00:23.729  1032  1534 I WifiNative-HAL: startHal
08-05 11:00:23.729  1032  1534 D wifi    : setting scan oui 0xaf59bf80
08-05 11:00:23.730  1937  6517 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 11:00:23.730  1032  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 11:00:23.730  1032  1534 I WifiNative-HAL: startHal
08-05 11:00:23.730  1032  1534 D wifi    : setting scan oui 0xaf59bf80
08-05 11:00:23.730  1937  6517 E CtrlSupplicant: Succeed to open control connection
08-05 11:00:23.730  1032  1534 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 11:00:23.730  1937  6517 E CtrlSupplicant: Succeed to open monitor connection
08-05 11:00:23.730  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:23.731  1937  6517 D WfdsMonitor: Supplicant connection established
08-05 11:00:23.731  1937  2292 D WfdsService: Connected to the supplicant for wfds
08-05 11:00:23.731  1032  1534 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 11:00:23.731  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 11:00:23.732  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 11:00:23.732  1032  1534 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 11:00:23.732  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 11:00:23.732  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 11:00:23.733  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 11:00:23.733  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 11:00:23.733  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 11:00:23.733  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 11:00:23.733  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 11:00:23.733  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 11:00:23.734  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 11:00:23.734  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 11:00:23.734  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 11:00:23.734  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 11:00:23.734  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
,08-05 11:00:23.734  6491  6491 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 11:00:23.735  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 11:00:23.735  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 11:00:23.735  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 11:00:23.735  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 11:00:23.736  1032  1534 E WifiNative: : [363,646,337 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 11:00:23.736  1032  1534 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 11:00:23.737  1032  1534 D WifiNative-wlan0: RECONNECT: returned true
08-05 11:00:23.737  1032  1534 D WifiNative-wlan0: doString: [STATUS]
08-05 11:00:23.739  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 11:00:23.739  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 11:00:23.739  1032  1534 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 11:00:23.739  1032  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:00:23.740  1032  1534 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:00:23.740  1032  1532 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.742   318   890 D CommandListener: Setting iface cfg
08-05 11:00:23.742   318   890 D CommandListener: Trying to bring up p2p0
08-05 11:00:23.742  1032  1532 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 11:00:23.742  1032  1532 D LGWifiP2pService: P2pEnablingState
08-05 11:00:23.742  1032  1532 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.742  1032  1532 D LGWifiP2pService: P2p socket connection successful
08-05 11:00:23.742  1032  1532 D LGWifiP2pService: P2pEnabledState
08-05 11:00:23.743  1032  1532 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 11:00:23.743  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 11:00:23.744  1937  1937 D WfdsService: WifiP2pState is changed : true
08-05 11:00:23.744  1937  2292 D WfdsService: Receive the WFDS_ENABLE Method
08-05 11:00:23.744  1937  2292 D WfdsService: Set the WFDS Monitor: true
08-05 11:00:23.744  1937  2292 D WfdsService: Connected to the supplicant for wfds
08-05 11:00:23.744  1937  2292 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 11:00:23.744  6491  6491 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 11:00:23.745  1937  2292 D WfdsService: selectPreferredScanChannel [36]
08-05 11:00:23.745  1937  2292 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 11:00:23.746  1032  1534 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 11:00:23.747  1032  1534 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 11:00:23.747  1032  1534 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 11:00:23.748  1032  1534 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-05 11:00:23.748  1032  1534 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 11:00:23.749  1032  1532 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 11:00:23.750  1032  1534 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 11:00:23.751  1032  1534 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 11:00:23.751  1032  1534 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 11:00:23.751  6491  6491 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 11:00:23.751  1032  1532 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 11:00:23.751  1032  1532 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 11:00:23.752  1032  1534 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 11:00:23.752  1032  1532 D WifiNative-p2p0: SET device_name G3: returned true
08-05 11:00:23.752  1032  1532 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 11:00:23.752  1032  1532 D LGWifiP2pService: before postfix = G3
08-05 11:00:23.752  1032  1532 D WifiServerServiceExt: postfix byte check : 2
08-05 11:00:23.752  1032  1532 D LGWifiP2pService: after postfix = G3
08-05 11:00:23.752  1032  1532 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-05 11:00:23.752  1032  1532 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 11:00:23.752  1032  1532 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 11:00:23.753  1032  1534 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 11:00:23.753  1032  1532 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 11:00:23.753  1032  1532 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 11:00:23.753  1032  1534 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 11:00:23.753  1032  1534 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 11:00:23.753  6491  6491 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 11:00:23.753  1032  1532 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 11:00:23.753  1032  1532 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 11:00:23.754  1032  1532 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 11:00:23.754  1032  1532 D WifiNative-HAL: p2pGetDeviceAddress
08-05 11:00:23.755  1937  1937 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 11:00:23.755  1937  1937 D WfdsService: isConnected: false
08-05 11:00:23.756  1032  1532 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-05 11:00:23.756  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 11:00:23.756  1032  1032 D RttService: SCAN_AVAILABLE : 3
08-05 11:00:23.756  1032  1534 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 11:00:23.757  1032  1552 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:00:23.757  1032  1552 I WifiNative-HAL: startHal
08-05 11:00:23.757  1032  1552 D wifi    : getting scan capabilities on interface[1] = 0xaf59bf80
08-05 11:00:23.757  1032  1534 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 11:00:23.757  1032  1552 D wifi    : failed to get capabilities : -3
08-05 11:00:23.757  1032  1552 E WifiScanningService: could not get scan capabilities
08-05 11:00:23.757  1032  1534 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-05 11:00:23.757  1032  1553 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.757  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 11:00:23.758  6400  6518 W FormManager: Network not available. Please check & try again.
08-05 11:00:23.758  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 11:00:23.759  6491  6491 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-05 11:00:23.759  6491  6491 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 11:00:23.759  6491  6491 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.760  6491  6491 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.761  1032  1534 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
,08-05 11:00:23.761  1937  6517 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:23.761  1032  1534 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:00:23.761  1937  6517 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:23.762  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:00:23.762  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:23.762  1032  6515 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:23.762  1032  6515 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-05 11:00:23.762  1032  1534 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:00:23.762  1032  6515 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:23.762  1032  6515 E WifiMonitor: WifiMonitor:p2p0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.762  1032  6515 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.762  1032  6515 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.762  1032  6515 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:23.762  1032  6515 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.762  1032  6515 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-05 11:00:23.762  1032  1534 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:00:23.762  1032  6515 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.762  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 11:00:23.763  1032  1532 D LGWifiP2pService: DeviceAddress: 
08-05 11:00:23.763  1032  1532 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 11:00:23.763  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 11:00:23.763  6491  6491 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:00:23.765  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 11:00:23.765  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN,
08-05 11:00:23.765  1032  6515 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:00:23.765  1032  6515 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:00:23.765  1032  1534 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 11:00:23.765  1032  1534 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-05 11:00:23.766  1937  1937 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 11:00:23.766  1937  1937 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-05 11:00:23.766  1937  1937 D WfdsService: Update P2p Interface State: 3
08-05 11:00:23.767  1032  1534 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 11:00:23.767  1032  1534 D WifiNative-wlan0: doBoolean: SCAN
08-05 11:00:23.767  1032  1532 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 11:00:23.767  1032  1532 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 11:00:23.768  1032  1534 D WifiNative-wlan0: SCAN: returned false
08-05 11:00:23.768  1032  1532 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 11:00:23.768  1032  1532 D WifiNative-p2p0: doString: [LIST_NETWORKS]
,08-05 11:00:23.768  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=363679  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:00:23.769  1032  1532 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 11:00:23.769  1032  1532 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 11:00:23.769  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=363680  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:00:23.770  1032  1534 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:23.770  1032  1534 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:23.770  1032  1534 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:23.771  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:00:23.771  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:00:23.771  1032  1534 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:23.771  1032  1534 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:23.774  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:23.774  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:23.775  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:23.775  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:23.775  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 11:00:23.776  1032  1532 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 11:00:23.776  1032  1532 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 11:00:23.776  1032  1532 D LGWifiP2pService: InactiveState
08-05 11:00:23.776  1032  1532 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.776  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.776  1032  1532 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 11:00:23.776  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:23.777  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 11:00:23.778  6491  6491 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:23.779  6491  6491 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ,
08-05 11:00:23.779  6491  6491 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.780  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:23.780  6491  6491 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-05 11:00:23.780  1937  6517 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:00:23.780  1937  6517 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:23.781  1937  6517 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:23.781  1032  6515 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:00:23.781  1032  6515 E WifiMonitor: WifiMonitor:p2p0 cnt=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:23.781  1032  6515 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:23.781  1032  6515 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:23.781  1032  6515 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:23.781  1032  6515 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.781  1032  6515 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.781  1032  6515 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.781  1032  6515 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:23.781  1032  6515 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.781  1032  6515 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.781  1032  6515 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:23.783  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:23.783  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 11:00:23.783  1032  1532 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.784  1032  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.785  1032  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.785  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.785  1032  1532 ,D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:23.786  1937  2292 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 11:00:23.786  1032  1032 E WifiServerServiceExt: No p2p device connected
08-05 11:00:23.787  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:23.794  6051  6051 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 11:00:23.794  6051  6051 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-05 11:00:23.794  6400  6519 V FormManager: Network unavailable.
,08-05 11:00:23.796  6400  6519 V FormManager: Network unavailable.
08-05 11:00:23.805  4238  6524 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:00:23.806  4238  6526 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:00:23.806  4238  6526 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:00:23.807  6051  6051 V [BNRBootReceiver]: Boot Receiver Return
,08-05 11:00:23.814  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:23.820  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:23.825  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:23.831  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:00:23.832  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:23.833  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:00:24.349  6491  6491 E wpa_supplicant: USIM:  scard_init function
08-05 11:00:24.350  6491  6491 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-05 11:00:24.357  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 11:00:24.358  1032  6515 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 11:00:24.358  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 11:00:24.358  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: WPS-AP-AVAILABLE 
08-05 11:00:24.358  1032  6515 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 11:00:24.358  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 11:00:24.358  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 11:00:24.359  1032  1534 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-05 11:00:24.360  1032  1534 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-05 11:00:24.360  1032  1534 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-05 11:00:24.361  1032  1534 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-05 11:00:24.361  1032  1534 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 11:00:24.380  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=364291  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 11:00:24.389  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.389  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.389  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 11:00:24.390  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=364301  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 11:00:24.391  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:24.391  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:24.394  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:24.403  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.403  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.403  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 11:00:24.404  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:24.404  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 11:00:24.408  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-05 11:00:24.417  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:24.417  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:24.420  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:24.428  6286  6286 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 11:00:24.432  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:00:24.447  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:24.454  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:24.463  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:00:24.465  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:24.467  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:00:24.474  6491  6491 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 11:00:24.480  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 11:00:24.480  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 11:00:24.480  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 11:00:24.480  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 11:00:24.480  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:24.480  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:24.483  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=364394  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 11:00:24.484  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=364394  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 11:00:24.486  6491  6491 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:00:24.486  6491  6491 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-05 11:00:24.490  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:24.490  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:24.491  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 11:00:24.491  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:00:24.491  1032  6515 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:00:24.491  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 11:00:24.491  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 11:00:24.494  1032  1534 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=364405
08-05 11:00:24.494  1032  1534 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=364405
08-05 11:00:24.495  1032  1534 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=364405
08-05 11:00:24.495  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=364406
08-05 11:00:24.496  1032  6515 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 11:00:24.496  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:24.496  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:24.498  1032  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-05 11:00:24.508  1032  1534 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 27 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=364406
08-05 11:00:24.508  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=364419  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 11:00:24.511  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.512  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.512  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-05 11:00:24.515  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:24.515  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:24.517  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:24.522  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.522  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.522  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-05 11:00:24.531  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:24.533  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=364443  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 11:00:24.537  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:24.537  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:24.538  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:24.542  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=364453  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-05 11:00:24.542  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:24.542  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 11:00:24.543  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=364453  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 11:00:24.543  1032  1534 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=364454
08-05 11:00:24.544  1032  1534 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=364454
08-05 11:00:24.545  1032  1534 D WifiNative-wlan0: doString: [STATUS]
08-05 11:00:24.546  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:24.546  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:24.546  1032  1534 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 11:00:24.547  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:24.548  1032  1534 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 11:00:24.552  1032  1534 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 11:00:24.552  1032  1534 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 11:00:24.555  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:24.558  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.558  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.559  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 11:00:24.559  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.559  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:24.559  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 11:00:24.561  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:24.561  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:24.562  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:24.563  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:24.563  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:24.564  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:24.571  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:24.571  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:24.571  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:00:24.573  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:00:24.573  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:00:24.573  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:00:24.573  6286  6286 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:00:24.575  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:00:24.575  6286  6286 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:00:24.576  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 11:00:24.576  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:00:24.576  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-05 11:00:24.576  6286  6286 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:00:24.576  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 11:00:24.576  6286  6286 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:00:24.580  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:24.584  1032  1534 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 11:00:24.584  1032  1540 D ConnectivityService: Got NetworkAgent Messenger
08-05 11:00:24.585  1032  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 11:00:24.585  1032  1540 D ConnectivityService: NetworkAgent connected
08-05 11:00:24.585  1032  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:00:24.586  1032  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 11:00:24.586  1032  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:24.586  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:24.586  1032  1532 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:24.586  1032  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:00:24.586  1032  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 11:00:24.589  1032  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 11:00:24.589  1032  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:00:24.589  1032  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-05 11:00:24.591  1032  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:00:24.591  1032  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 11:00:24.592  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:24.594  1032  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 11:00:24.597  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:24.597   318   890 D CommandListener: Setting iface cfg
08-05 11:00:24.603  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:24.603  1032  1534 E WifiStateMachine: Start Dhcp Watchdog 1
08-05 11:00:24.603  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:24.603  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:00:24.604  1032  1534 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=364514  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:24.604  1032  1534 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=364515  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:24.605  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=364515  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:24.605  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:24.606  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
,08-05 11:00:24.606  1032  1534 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-05 11:00:24.606  1032  1534 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:24.607  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:24.607  1032  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:24.607  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:24.608  1032  6553 D DhcpStateMachine: StoppedState
08-05 11:00:24.608  1032  6553 D DhcpStateMachine: StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:24.608  1032  6553 D DhcpStateMachine: WaitBeforeStartState
08-05 11:00:24.610  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:24.610  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-05 11:00:24.611  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:24.611  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-05 11:00:24.612  1032  1534 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=364522  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:24.612  1032  1534 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=364523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:24.613  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=364523  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:24.614  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:24.616  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1508809384] from screen [on:0 period:1508809384]
,08-05 11:00:24.617  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1508809385]
08-05 11:00:24.617  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 11:00:24.618  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:24.621  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:24.623  1032  1540 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-05 11:00:24.623  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:24.624  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:24.624  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:24.624  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:24.624  1032  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:24.624  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:00:24.624  1032  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:24.625  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:24.625  1032  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:24.626  1032  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-05 11:00:24.627  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:00:24.627  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:24.627  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:00:24.628  1032  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:00:24.628  1032  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:00:24.628  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:00:24.629  1032  1534 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-05 11:00:24.629  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-05 11:00:24.630  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-05 11:00:24.630  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 11:00:24.630  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-05 11:00:24.630  1032  1534 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 11:00:24.631  1032  1534 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 11:00:24.631  1032  1534 D WifiNative-wlan0: SET ps 0: returned true
08-05 11:00:24.631  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 11:00:24.631  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 11:00:24.632  1032  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 11:00:24.632  1032  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fa9e142 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:24.632  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@fa9e142 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:00:24.632  1032  6553 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:24.633  1032  6553 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 11:00:24.634  1032  1534 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 11:00:24.634  1032  1534 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 11:00:24.634  1032  1534 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 11:00:24.634  1032  1534 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-05 11:00:24.635  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:24.635  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-05 11:00:24.638  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:24.649  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:24.655  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:24.655  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:24.655  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 11:00:24.659  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:24.663  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:24.669  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:24.673  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:24.673  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:24.674  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:00:24.836  1032  6553 D DhcpStateMachine: DHCPV4 request on wlan0
08-05 11:00:24.838  1032  6553 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-05 11:00:24.838  1032  6553 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 11:00:24.833  6555  6555 W dhcpcd  : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 11:00:24.843  6555  6555 W dhcpcd  : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:24.885  6555  6555 I dhcpcd  : version 5.5.6 starting
,08-05 11:00:24.890  6555  6555 E dhcpcd  : get_duid: m
08-05 11:00:24.891  6555  6555 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 11:00:24.891  6555  6555 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-05 11:00:25.008  6555  6555 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 11:00:25.009  6555  6555 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-05 11:00:25.009  6555  6555 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-05 11:00:25.012  6555  6555 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 11:00:25.013  6555  6555 D dhcpcd  : wlan0: sending REQUEST (xid 0xec1d66b4), next in 4.34 seconds
08-05 11:00:25.094  6555  6555 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-05 11:00:25.103  6555  6555 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
,08-05 11:00:25.103  6555  6555 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 11:00:25.106  6555  6555 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-05 11:00:25.107  6555  6555 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 11:00:25.107  6555  6555 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 11:00:25.108  6555  6555 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-05 11:00:25.109  6555  6555 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
,08-05 11:00:25.109  6555  6555 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 11:00:25.109  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.111  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.112  1032  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.117  1032  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.118  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.120  1032  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.121  1032  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-05 11:00:25.646  1032  6553 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-05 11:00:25.665  1032  6553 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 11:00:25.665  1032  6553 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 11:00:25.665  1032  6553 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 11:00:25.665  1032  6553 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 11:00:25.665  1032  6553 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 11:00:25.665  1032  6553 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-05 11:00:25.667  1032  6553 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 11:00:25.668  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 11:00:25.669  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 11:00:25.669  1032  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.669  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.669  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:00:25.670  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:00:25.672  1032  1936 D WifiServiceImplEx: setWifiEnabled: false pid=6201, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:00:25.672  1032  1936 D WifiService: setWifiEnabled: false pid=6201, uid=10118
08-05 11:00:25.672  1032  1936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:00:25.677  1032  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:00:25.677  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 11:00:25.677  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 11:00:25.678  1032  6553 D DhcpStateMachine: RunningState
08-05 11:00:25.679  1032  1534 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 11:00:25.679  1032  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:00:25.687  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:00:25.687  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:00:25.687  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,08-05 11:00:25.695  1032  1534 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:00:25.696  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:25.696  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:25.697  1032  1534 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:25.697  1032  1534 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:25.697  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-05 11:00:25.697  1032  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:00:25.697  1032  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 11:00:25.698  1032  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-05 11:00:25.698  1032  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:00:25.699  1032  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-05 11:00:25.705  1032  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 11:00:25.706  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:00:25.706  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:00:25.708  1032  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.708  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.709  1032  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:00:25.709  1032  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:00:25.709  1032  1534 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:00:25.710   318   890 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:00:25.723  1032  6553 D DhcpStateMachine: RunningState{ when=-14ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:00:25.817  1032  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
08-05 11:00:25.818  1032  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 0
08-05 11:00:25.818  1032  1540 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-05 11:00:25.819  1032  1540 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-05 11:00:25.822  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-05 11:00:25.823  1032  6552 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.823  1032  6552 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 11:00:25.834  1032  1540 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 11:00:25.835  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:25.835  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:25.835  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:00:25.837  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:25.837  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 11:00:25.839  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:25.840  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:25.842  1032  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 11:00:25.843  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 11:00:25.843  1032  1532 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.843  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.843  1032  1532 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@3ae5335a
08-05 11:00:25.843  1032  1532 D LGWifiP2pService: P2pDisablingState
08-05 11:00:25.843  1032  1532 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.843  1032  1532 D LGWifiP2pService: p2p socket connection lost
08-05 11:00:25.844  1032  1532 D LGWifiP2pService: P2pDisabledState
08-05 11:00:25.847  1032  1534 E WifiStateMachine:  DefaultState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 11:00:25.848  1032  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.848  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.848  1032  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.849  1032  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.849  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:25.850  1032  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-05 11:00:25.850  1032  1534 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 11:00:25.851  1032  1534 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-05 11:00:25.852  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:00:25.852  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-05 11:00:25.853  6491  6491 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:00:25.853  1032  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:00:25.853  1032  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:00:25.854  1032  1534 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:00:25.854   318   890 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:00:25.856  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:25.856  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:25.856  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:00:25.856  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 11:00:25.857  1032  1032 D RttService: SCAN_AVAILABLE : 1
08-05 11:00:25.858  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 11:00:25.858  1937  1937 D WfdsService: WifiP2pState is changed : false
08-05 11:00:25.859  1937  2292 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-05 11:00:25.859  1937  2292 D WfdsService: Set the WFDS Monitor: false
08-05 11:00:25.859  1937  2292 D WfdsMonitor: WFDS Monitor is stopped
08-05 11:00:25.860  1937  2292 D WfdsService: STATE : WfdsDisabledState - enter
08-05 11:00:25.860  1937  6517 D CtrlSupplicant: Received on exit socket, terminate
08-05 11:00:25.860  1937  6517 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-05 11:00:25.860  1937  6517 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-05 11:00:25.860  1937  6517 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-05 11:00:25.860  1937  2293 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-05 11:00:25.862  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:25.862  1937  2292 W WfdsService: DefaultState - msg [9445378] is not handled
08-05 11:00:25.862  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 11:00:25.863  1032  1534 D WifiNative-p2p0: doBoolean: TERMINATE
08-05 11:00:25.864  1032  1534 D WifiNative-p2p0: TERMINATE: returned true
08-05 11:00:25.864  1032  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:00:25.864  1032  1534 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:00:25.864  1032  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:00:25.864  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:25.865  1032  1532 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.865  1032  1552 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.865  1032  1532 D LGWifiP2pService: DefaultState{ when=-14ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.866  1032  1553 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.866  1032  1032 D WifiHS20: hidePasspointNotification off =false
08-05 11:00:25.869  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:25.869  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:25.869  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:00:25.872  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-05 11:00:25.873  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-05 11:00:25.874  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-05 11:00:25.874  1032  1032 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-05 11:00:25.874  6304  6304 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 11:00:25.874  6304  6304 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:00:25.874  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:25.876  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:25.876  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:25.876  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:25.876  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:25.876  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:25.876  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:00:25.876  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:25.876  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:25.876  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:25.876  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:25.876  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:25.878  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:25.878  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:25.878  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:25.878  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:25.878  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:25.878  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:00:25.878  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:25.878  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:25.878  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:25.878  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:25.878  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:25.881  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:25.885  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 11:00:25.885  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 11:00:25.886  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:25.887  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:25.889  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:25.897  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-05 11:00:25.897  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:25.901  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-05 11:00:25.904  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:25.908  6304  6304 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-05 11:00:25.908  6304  6304 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:00:25.908  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:25.912  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:25.919  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:25.925  6491  6491 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 11:00:25.925  6491  6491 I wpa_supplicant: monitor socket send errors count : 1
08-05 11:00:25.925  6491  6491 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1937-4\x00 that cannot receive messages
,08-05 11:00:25.927  1032  6515 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-05 11:00:25.927  1032  6515 D WifiMonitor: Dropping event because (p2p0) is stopped
08-05 11:00:25.928  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:25.928  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:25.930  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:00:25.933  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:25.937  6304  6304 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-05 11:00:25.937  6304  6304 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:00:25.937  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:25.941  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:25.946  1032  6553 D DhcpStateMachine: StoppedState
08-05 11:00:25.946  1032  6553 D DhcpStateMachine: StoppedState{ when=-92ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:25.947  1032  1534 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-05 11:00:25.948  1032  1534 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-05 11:00:25.949  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:25.961  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:25.961  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 11:00:25.963  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:00:25.964  6491  6491 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:00:25.965  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-05 11:00:25.965  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:00:25.965  1032  6515 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:00:25.965  1032  6515 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-05 11:00:25.966  1032  1534 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=365877
08-05 11:00:25.967  1032  1115 D Tethering: InitialState.processMessage what=4
08-05 11:00:25.967  1032  1534 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=365877
08-05 11:00:25.967  6491  6491 W wpa_supplicant: USIM:  scard_deinit function
08-05 11:00:25.967  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:25.967  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:25.968  1032  1534 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=365879  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 11:00:25.969  1032  1534 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=365880  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-05 11:00:25.974  1032  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 11:00:25.978  1032  1534 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:25.978  1032  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:25.979   318  6612 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 11:00:25.979  1032  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 11:00:25.984  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:25.990  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 11:00:25.994  6400  6614 W FormManager: Network not available. Please check & try again.
08-05 11:00:25.997  6400  6615 V FormManager: Network unavailable.
08-05 11:00:25.997  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:26.005  6400  6615 V FormManager: Network unavailable.
,08-05 11:00:26.017  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-05 11:00:26.017  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:00:26.017  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:00:26.017  6286  6286 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:00:26.018  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:00:26.018  6286  6286 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:00:26.019  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:00:26.019  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:00:26.019  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:00:26.019  6286  6286 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:00:26.019  6286  6286 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:00:26.024  6491  6491 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 11:00:26.024  1032  6515 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-05 11:00:26.024  1032  6515 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-TERMINATING 
08-05 11:00:26.024  1032  6515 D WifiMonitor: Disconnecting from the supplicant, no more events
08-05 11:00:26.025  1032  1534 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 36 0
08-05 11:00:26.128  1937  1937 D WfdsService: Supplicant Connection state is changed : false
08-05 11:00:26.129  1937  2292 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-05 11:00:26.129  1937  2292 D WfdsService: Set the WFDS Monitor: false
08-05 11:00:26.129  1937  2292 D WfdsMonitor: WFDS Monitor is stopped
,08-05 11:00:26.135  1032  1534 D WifiOffDelayIfNotUsed: stopMonitoring
08-05 11:00:26.136  1032  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:00:26.136  1032  1534 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:00:26.136  1032  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:00:26.137  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:00:26.138  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:00:26.140  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-05 11:00:26.141  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:26.145  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:26.146  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-05 11:00:26.147  1032  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-05 11:00:26.147  1032  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-05 11:00:26.149  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:26.151  2493  2493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:26.153  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:26.155  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:26.164  4238  6616 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-05 11:00:26.174  4238  6617 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:00:26.174  4238  6617 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:00:26.179  6304  6304 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-05 11:00:26.179  6304  6304 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-05 11:00:26.179  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:00:26.184  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:00:26.187  6400  6619 W FormManager: Network not available. Please check & try again.
08-05 11:00:26.192  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:00:26.202  6400  6620 V FormManager: Network unavailable.
08-05 11:00:26.206  6400  6620 V FormManager: Network unavailable.
,08-05 11:00:26.482  6079  6471 D UEI.SmartControl: Internal timer expired: 2
08-05 11:00:26.482  6079  6471 D UEI.SmartControl: unbind internal service
,08-05 11:00:26.724  6079  6468 D serial_port: close(fd = 24)
,08-05 11:00:26.733  6079  6468 I UEI.SmartControl: Serial port is closed.
08-05 11:00:27.626  1032  1534 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1508812394] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 11:00:27.628  1032  1534 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1508812396] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-05 11:00:28.692  1032  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:00:28.698  1032  1954 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 11:00:28.720  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:00:28.720  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:00:28.720  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-05 11:00:28.721  1032  1115 D BluetoothManagerService: Message: 1
08-05 11:00:28.721  1032  1115 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 11:00:28.748  1032  1115 D BluetoothManagerService: Message: 20
08-05 11:00:28.748  1032  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a1fbcb:true
,08-05 11:00:28.752  6448  6448 D BluetoothAdapterState: make
08-05 11:00:28.757  6448  6448 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 11:00:28.757  6448  6448 I bluedroid-qcom: init
08-05 11:00:28.759  6448  6631 I BluetoothAdapterState: Entering OffState
08-05 11:00:28.759  6448  6448 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 11:00:28.759  6448  6448 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 11:00:28.759  6448  6448 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 11:00:28.759  6448  6448 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 11:00:28.759  6448  6448 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 11:00:28.761  6448  6448 I bluedroid-qcom: get_profile_interface socket
08-05 11:00:28.761  6448  6448 I bluedroid-qcom: get_profile_interface map_client
,08-05 11:00:28.765  6448  6635 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 11:00:28.754  6634  6634 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:28.754  6634  6634 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:28.775  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-05 11:00:28.777  1032  1115 D BluetoothManagerService: Message: 40
08-05 11:00:28.777  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 11:00:28.779  6448  6463 I bluedroid-qcom: config_hci_snoop_log
08-05 11:00:28.780  1032  1115 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 11:00:28.780  1032  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 11:00:28.787  6634  6634 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 11:00:28.787  6634  6634 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 11:00:28.787  6634  6634 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-05 11:00:28.793  6448  6631 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 11:00:28.794  6448  6631 D BluetoothAdapterProperties: Setting state to 11
08-05 11:00:28.794  6634  6634 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 11:00:28.794  6448  6631 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 11:00:28.798  6634  6634 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 11:00:28.798  6634  6634 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-05 11:00:28.801  6448  6635 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 11:00:28.804  1032  1115 D BluetoothManagerService: Message: 60
08-05 11:00:28.804  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 11:00:28.804  1032  1115 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 11:00:28.806  6448  6631 I LGBluetoothServiceJni: classInitNative: succeeds
08-05 11:00:28.813  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:00:28.816  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:00:28.818  6448  6635 D BluetoothAdapterProperties: Name is: G3
08-05 11:00:28.819  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:28.821  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:28.822  6286  6286 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-05 11:00:28.831  6448  6448 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:00:28.832  6448  6448 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:28.832  6448  6448 V BluetoothPbapReceiver: ***********state = 11
,08-05 11:00:28.843  6448  6631 D BluetoothBondStateMachine: make
08-05 11:00:28.855  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-05 11:00:28.855  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:00:28.855  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
,08-05 11:00:28.859  6448  6649 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 11:00:28.860  6448  6631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:28.860  6448  6631 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 11:00:28.860  6448  6631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:28.861  6448  6631 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 11:00:28.864  6448  6631 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-05 11:00:28.869  6448  6631 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:00:28.874  6286  6286 D BluetoothPermissionRequest: onReceive
08-05 11:00:28.877  6286  6286 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:00:28.888  6448  6631 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:00:28.889  6448  6448 D HeadsetService: Received start request. Starting profile...
08-05 11:00:28.889  6448  6448 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 11:00:28.890  6448  6448 D LGBluetoothHfpAdapter: Version 1.6
08-05 11:00:28.892  1599  1599 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-05 11:00:28.893  1599  1599 I [SystemUI]LGPowerUI: On Skip Timer : true
08-05 11:00:28.895  6448  6448 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 11:00:28.896  6448  6631 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:00:28.896  6448  6448 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 11:00:28.897  6448  6448 D HeadsetStateMachine: make
08-05 11:00:28.902  1599  1599 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
08-05 11:00:28.902  1599  1599 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-05 11:00:28.906  1032  1539 D WifiController: battery changed pluggedType: 2
08-05 11:00:28.906  1937  2115 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-05 11:00:28.906  1937  2115 D LEDHandler: Battery Level Remaining: 100%
08-05 11:00:28.906  1937  2115 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
08-05 11:00:28.908  1599  1599 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-05 11:00:28.910  6448  6631 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:00:28.913  6051  6051 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-05 11:00:28.915  6448  6631 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:00:28.921  6448  6631 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:00:28.926  6448  6631 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:00:28.935  6448  6448 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:00:28.935  6448  6448 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:00:28.939  6448  6448 D HeadsetStateMachine: max_hf_connections = 1
08-05 11:00:28.939  6448  6448 I bluedroid-qcom: get_profile_interface handsfree
,08-05 11:00:28.941  6448  6631 V LGMDMManager: Create singleton instance
08-05 11:00:28.942  6448  6448 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 11:00:28.942   322  1385 V AudioPolicyService: registerClient() client 0xb0410380, uid 1002
08-05 11:00:28.942  6448  6631 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 11:00:28.942   322  2139 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 11:00:28.942   322  2139 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:00:28.942   322  2139 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:00:28.943  6448  6448 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 11:00:28.943   322   322 V AudioFlinger: registerClient() client 0xb55818c8, pid 6448
08-05 11:00:28.944   322  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:28.944   322  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:28.944  6448  6448 V ToneGenerator: Create Track: 0xb4928a80
08-05 11:00:28.944  6448  6448 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 11:00:28.944  1599  3052 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:28.944  6448  6448 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 11:00:28.944  1599  3052 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:28.944  3426  3441 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:28.944  3426  3441 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:28.944  1032  1594 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:28.944  1032  1594 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:28.944   322   322 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 11:00:28.944   322   322 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 11:00:28.944   322   322 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:00:28.944   322   322 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:00:28.944  6448  6464 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:28.944  6448  6464 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 11:00:28.944  1848  2735 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:28.944  1848  2735 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:28.945   322  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:28.945   322  1384 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 11:00:28.945   322  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:00:28.945  1599  1619 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:28.945  1599  1619 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:00:28.945   322  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 11:00:28.945   322  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 11:00:28.945   322  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:00:28.945   322  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:00:28.945  1848  1863 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:28.945  1848  1863 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:00:28.945  3426  3442 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:28.945  3426  3442 V AudioSystem: i,oConfigChanged() opening already existing output! 4
08-05 11:00:28.945  6448  6448 V AudioSystem: getLatency() output 2, latency 50
08-05 11:00:28.945  1032  1954 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:28.945  6448  6448 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 11:00:28.945  6448  6448 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 11:00:28.945  1032  1954 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:00:28.945  6448  6636 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:28.945  6448  6636 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 11:00:28.945   322  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 11:00:28.945   322  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 11:00:28.945   322  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 11:00:28.945   322  1384 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 11:00:28.945   322  1384 V AudioFlinger: createTrack() lSessionId: 22
08-05 11:00:28.946  6448  6448 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 11:00:28.946   322   322 V AudioFlinger: acquiring 22 from 6448, for 6448
08-05 11:00:28.946   322   322 V AudioFlinger:  added new entry for 22
08-05 11:00:28.946  6448  6448 V ToneGenerator: ToneGenerator INIT OK, time: 368873
08-05 11:00:28.947  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:28.947  6448  6656 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 11:00:28.948  6448  6656 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:00:28.948  6448  6656 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:00:28.948  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:28.948  6448  6656 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 11:00:28.949   322  2139 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6448
08-05 11:00:28.949   322  2139 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 11:00:28.949   322  2139 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 11:00:28.949   322  2139 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 11:00:28.949   322  2139 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 11:00:28.949   322  2139 V voice   : voice_set_parameters: exit with code(0)
08-05 11:00:28.949   322  2139 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 11:00:28.949   322  2139 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 11:00:28.949   322  2139 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 11:00:28.949   322  2139 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 11:00:28.949   322  2139 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 11:00:28.949   322  2139 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 11:00:28.949  6448  6656 V ToneGenerator: ToneGenerator destructor
08-05 11:00:28.949  6448  6656 V ToneGenerator: stopTone
08-05 11:00:28.949  6448  6656 V ToneGenerator: Delete Track: 0xb4928a80
,08-05 11:00:28.949  6448  6448 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:28.950  6448  6656 V AudioTrack: ~AudioTrack, releasing session id from 6448 on behalf of 6448
08-05 11:00:28.950   322   322 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 11:00:28.950   322   322 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 11:00:28.950   322  1267 V AudioPolicyService: AudioCommandThread() waking up
08-05 11:00:28.950   322  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 11:00:28.950   322  1267 V AudioPolicyManager: releaseOutput() 2
08-05 11:00:28.950   322  1267 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 11:00:28.950   322   322 V AudioFlinger: PlaybackThread::Track destructor
08-05 11:00:28.950   322   322 V AudioFlinger: removeClient_l() pid 6448, calling pid 322
08-05 11:00:28.950   322  2139 V AudioFlinger: releasing 22 from 6448 for 6448
08-05 11:00:28.950   322  2139 V AudioFlinger:  decremented refcount to 0
08-05 11:00:28.950   322  2139 V AudioFlinger: purging stale effects
,08-05 11:00:28.951  6448  6448 D A2dpService: Received start request. Starting profile...
08-05 11:00:28.952  6448  6448 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-05 11:00:28.953  6448  6448 V Avrcp   : make
08-05 11:00:28.953  6448  6448 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 11:00:28.953  6448  6448 I bluedroid-qcom: get_profile_interface avrcp
08-05 11:00:28.954  1032  1594 W Process : Unable to open /proc/6657/status
08-05 11:00:28.961  6448  6448 V AudioManager: registerRemoteController: size of Media player list: 0
08-05 11:00:28.962  6448  6448 E AudioManager: No RCC entry present to update
08-05 11:00:28.962  6448  6448 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-05 11:00:28.966  6448  6448 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-05 11:00:28.966  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-05 11:00:28.966  6448  6448 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 11:00:28.970  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 11:00:29.073  1032  1882 V SIM_STK : Menu title from STK is T-Mobile
08-05 11:00:29.074  1032  1882 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:00:29.190  1032  1594 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 11:00:29.204  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 11:00:29.209  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 11:00:29.209  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-05 11:00:29.210  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 11:00:29.210  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 11:00:29.210  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:00:29.210  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 11:00:29.210  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 11:00:29.210  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 11:00:29.210  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:00:29.210  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 11:00:29.211  6448  6448 I BluetoothA2dpServiceJni: classInitNative
08-05 11:00:29.211  6448  6448 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:00:29.211  6448  6448 D A2dpStateMachine: make
08-05 11:00:29.216  6448  6448 I bluedroid-qcom: get_profile_interface a2dp
08-05 11:00:29.216  6448  6665 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 11:00:29.219  6448  6448 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:00:29.219  6448  6448 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 11:00:29.220  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:29.221  6448  6448 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 11:00:29.221  6448  6664 D A2dpStateMachine: Enter Disconnected: -2
08-05 11:00:29.223  6448  6448 D HidService: Received start request. Starting profile...
08-05 11:00:29.223  6448  6448 I bluedroid-qcom: get_profile_interface hidhost
08-05 11:00:29.223  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:29.223  6448  6448 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:00:29.224  6448  6448 D HealthService: Received start request. Starting profile...
08-05 11:00:29.225  6448  6448 I bluedroid-qcom: get_profile_interface health
08-05 11:00:29.226  6448  6448 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:00:29.226  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
,08-05 11:00:29.226  6448  6448 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 11:00:29.231  6448  6448 D PanService: Received start request. Starting profile...
08-05 11:00:29.231  6448  6448 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 11:00:29.231  6448  6448 I bluedroid-qcom: get_profile_interface pan
08-05 11:00:29.240  6448  6448 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 11:00:29.240  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
,08-05 11:00:29.244  6448  6448 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-05 11:00:29.257  6448  6448 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 11:00:29.260  6448  6448 D BtGatt.GattService: Received start request. Starting profile...
08-05 11:00:29.260  6448  6448 D BtGatt.GattService: start()
08-05 11:00:29.260  6448  6448 I bluedroid-qcom: get_profile_interface gatt
08-05 11:00:29.261  6448  6448 D BtGatt.AdvertiseManager: advertise manager created
08-05 11:00:29.270  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:29.272  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:29.272  6448  6448 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 11:00:29.274  6448  6448 V BluetoothMapService: BluetoothMapBinder()
,08-05 11:00:29.276  6448  6448 D BluetoothMapService: Received start request. Starting profile...
08-05 11:00:29.276  6448  6448 D BluetoothMapService: start()
08-05 11:00:29.282  6448  6448 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 11:00:29.282  6448  6448 D BluetoothMapEmailAppObserver: createReceiver()
08-05 11:00:29.284  6448  6448 D BluetoothMapEmailAppObserver: initObservers()
08-05 11:00:29.284  6448  6448 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 11:00:29.294  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:29.294  6448  6448 D HeadsetStateMachine: Proxy object connected
08-05 11:00:29.295  6448  6448 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 11:00:29.295  6448  6448 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-05 11:00:29.297  6448  6656 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 11:00:29.298  6448  6656 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 11:00:29.298  6448  6656 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 11:00:29.302  6448  6448 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:00:29.302  6448  6448 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:00:29.303  6448  6448 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:00:29.303  6448  6448 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:00:29.303  6448  6448 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:29.303  6448  6448 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 11:00:29.308  6448  6448 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 11:00:29.313  6448  6448 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:00:29.317  6448  6448 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 11:00:29.318  6448  6448 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 11:00:29.322  6448  6448 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 11:00:29.327  6448  6448 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 11:00:29.328  6448  6448 V BluetoothMapService: Handler(): got msg=1
08-05 11:00:29.329  6448  6631 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 11:00:29.329  6448  6631 I bluedroid-qcom: enable
08-05 11:00:29.330  6448  6631 I bt_hci_bdroid: init
08-05 11:00:29.330  6448  6675 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 11:00:29.330  6448  6675 I bt-btu  : btu_task pending for preload complete event
08-05 11:00:29.331  6448  6631 I bt_vendor: bt-vendor : init
08-05 11:00:29.331  6448  6631 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 11:00:29.331  6448  6631 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 11:00:29.331  6448  6631 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 11:00:29.331  6448  6631 D bt_userial_mct: userial_init
08-05 11:00:29.331  6448  6631 D bt_hci_bdroid: set_power 1
08-05 11:00:29.331  6448  6631 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 11:00:29.331  6448  6631 I bt_vendor: Starting hciattach daemon
08-05 11:00:29.331  6448  6631 I bt_vendor: try to set true
08-05 11:00:29.323  6678  6678 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:29.323  6678  6678 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 11:00:29.358  6679  6679 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 11:00:29.430  6685  6685 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 11:00:29.444  6686  6686 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 11:00:29.482  6688  6688 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 11:00:29.494  6689  6689 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 11:00:29.506  6690  6690 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 11:00:29.522  6691  6691 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 11:00:29.543  6693  6693 I libmdmdetect: ESOC framework not supported
,08-05 11:00:29.544  6693  6693 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-05 11:00:29.555  6693  6693 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 11:00:29.555  6693  6693 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 11:00:29.555  6693  6693 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 11:00:29.555  6693  6693 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 11:00:29.555  6693  6693 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 11:00:29.555  6693  6693 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 11:00:29.555  6693  6693 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-05 11:00:29.597  6693  6694 E QC-QMI  : qmi_client [6693] 14: failed to locate client data
08-05 11:00:29.598   486   486 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-05 11:00:29.598   486   486 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-05 11:00:29.641  6695  6695 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 11:00:29.655  6696  6696 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-05 11:00:29.684  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 6678
,08-05 11:00:29.685  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 6695
08-05 11:00:29.686  6448  6631 I bt_vendor: bluetooth satus is on
08-05 11:00:29.686  6448  6631 D bt_hci_bdroid: preload
08-05 11:00:29.687  6448  6677 D bt_userial_mct: userial_open(port:0)
08-05 11:00:29.687  6448  6677 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-05 11:00:29.690  6448  6677 I bt_vendor: Done intiailizing UART
08-05 11:00:29.691  6448  6677 I bt_vendor: Done intiailizing UART
08-05 11:00:29.691  6448  6677 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 11:00:29.691  6448  6677 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-05 11:00:29.691  6448  6675 I bt-btu  : btu_task received preload complete event
08-05 11:00:29.692  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 11:00:29.692  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 11:00:29.694  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 11:00:29.694  6448  6698 D bt_userial_mct: Entering userial_read_thread()
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_GATT
,08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 11:00:29.697  6448  6675 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 11:00:29.793  6448  6675 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 11:00:29.794  6448  6675 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e4061 
08-05 11:00:29.794  6448  6675 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e4061 
,08-05 11:00:29.855  6448  6635 E bt-btif : Calling BTA_HhEnable
08-05 11:00:29.855  6448  6635 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 11:00:29.856  6448  6635 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 11:00:29.864  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-05 11:00:29.864  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 11:00:29.864  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 11:00:29.865  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 11:00:29.865  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 11:00:29.868  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 11:00:29.869  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 11:00:29.871  6448  6635 D BluetoothAdapterProperties: Name is: G3
,08-05 11:00:29.884  6448  6635 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:00:29.884  6448  6635 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:00:29.884  6448  6635 D bt_hci_bdroid: postload
08-05 11:00:29.885  6448  6677 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:00:29.886  6448  6675 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 11:00:29.887  6448  6635 D bte_conf: Device ID record 1 : primary
08-05 11:00:29.887  6448  6635 D bte_conf:   vendorId            = 00c4
08-05 11:00:29.887  6448  6635 D bte_conf:   vendorIdSource      = 0001
08-05 11:00:29.887  6448  6635 D bte_conf:   product             = 13a1
08-05 11:00:29.887  6448  6635 D bte_conf:   version             = 1000
08-05 11:00:29.887  6448  6635 D bte_conf:   clientExecutableURL = 
08-05 11:00:29.887  6448  6635 D bte_conf:   serviceDescription  = 
08-05 11:00:29.887  6448  6635 D bte_conf:   documentationURL    = 
08-05 11:00:29.887  6448  6635 D bte_conf: bte_load_did_conf no section named DID2.
08-05 11:00:29.888  6448  6677 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:00:29.891  6448  6631 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-05 11:00:29.891  6448  6631 D BluetoothAdapterProperties: ScanMode =  20
08-05 11:00:29.895  6448  6631 D BluetoothAdapterProperties: State =  11
08-05 11:00:29.895  6448  6631 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 11:00:29.896  6448  6631 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 11:00:29.896  6448  6631 D BluetoothAdapterProperties: Setting state to 12
08-05 11:00:29.896  6448  6631 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 11:00:29.897  6448  6635 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 11:00:29.898  6448  6635 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 11:00:29.883  6703  6703 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:29.883  6703  6703 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:29.904  1032  1115 D BluetoothManagerService: Message: 60
08-05 11:00:29.904  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 11:00:29.904  1032  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-05 11:00:29.907  6448  6677 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:00:29.916  6448  6675 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:29.916  6448  6675 W bt-smp  : Plain text(LSB ~ MSB) = e1 f6 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:29.916  6448  6675 W bt-smp  : Encrypted text(LSB ~ MSB) = b5 cd a5 84 7e de e3 3a ed 7d 9c e1 2a f9 6e 24 
,08-05 11:00:29.919  6448  6677 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:00:29.919  6448  6675 W bt-btm  : Stopping oneshot timer
08-05 11:00:29.919  6448  6698 E bt_mct  : hci lib postload completed
08-05 11:00:29.926  6448  6635 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:00:29.928  1848  2430 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:00:29.931  6448  6631 I BluetoothAdapterState: Entering On State
08-05 11:00:29.932  6448  6635 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 11:00:29.936  6448  6631 D LGBluetoothServiceAdapter: [BTUI] OnState
08-05 11:00:29.936  6448  6631 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 11:00:29.936  6448  6631 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-05 11:00:29.940  6448  6631 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 11:00:29.953  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:29.953  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:29.953  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:29.953  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:29.953  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:29.953  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:29.953  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:29.953  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:00:29.960  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:29.961  6448  6675 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:29.961  6448  6675 W bt-smp  : Plain text(LSB ~ MSB) = 4f 04 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:29.961  6448  6675 W bt-smp  : Encrypted text(LSB ~ MSB) = 30 3e c8 93 b0 a9 4f 8b fb aa 7d 1d 0e 81 ab 41 
08-05 11:00:29.961  6448  6675 W bt-btm  : Stopping oneshot timer
08-05 11:00:29.973  6448  6675 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:29.973  6448  6675 W bt-smp  : Plain text(LSB ~ MSB) = 59 77 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:29.973  6448  6675 W bt-smp  : Encrypted text(LSB ~ MSB) = e6 0e 1d 24 15 b4 a3 1e d3 8a dd 6f 32 50 71 a9 
,08-05 11:00:29.976  6448  6675 W bt-btm  : Stopping oneshot timer
08-05 11:00:29.977  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:29.977  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:29.977  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:29.977  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:29.977  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:29.977  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:29.977  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:29.977  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:29.980  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:29.980  6448  6631 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 11:00:29.989  6448  6675 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:29.989  6448  6675 W bt-smp  : Plain text(LSB ~ MSB) = 08 97 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:29.989  6448  6675 W bt-smp  : Encrypted text(LSB ~ MSB) = b9 9a e0 bb 1e 07 e5 d2 55 f9 7b 75 cf 2f c9 ec 
,08-05 11:00:29.992  6448  6675 W bt-btm  : Stopping oneshot timer
08-05 11:00:29.997  1848  1848 D BluetoothHeadset: Proxy object connected
08-05 11:00:29.999  6286  6303 D BluetoothPan: onBluetoothStateChange on: true
08-05 11:00:29.999  6286  6303 D BluetoothPan: onBluetoothStateChange call bindService
08-05 11:00:30.015  6448  6675 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:30.015  6448  6675 W bt-smp  : Plain text(LSB ~ MSB) = c9 61 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:30.015  6448  6675 W bt-smp  : Encrypted text(LSB ~ MSB) = cc 58 67 ad 93 48 a1 3c c6 8d f3 23 01 58 04 05 
08-05 11:00:30.015  6448  6675 W bt-btm  : Stopping oneshot timer
,08-05 11:00:30.020  1032  1115 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:00:30.023  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:00:30.024  1032  1032 D BluetoothHeadset: Proxy object connected
08-05 11:00:30.029  1848  1848 D BluetoothHeadset: Proxy object connected
08-05 11:00:30.030  6286  6286 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 11:00:30.030  6286  6286 D PanProfile: Bluetooth service connected
,08-05 11:00:30.032  6286  6303 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 11:00:30.037  6286  6303 D BluetoothMap: onBluetoothStateChange: up=true
08-05 11:00:30.041  1032  1115 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 11:00:30.042  6718  6718 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-05 11:00:30.043  1032  1032 D BluetoothA2dp: Proxy object connected
,08-05 11:00:30.045  1848  2735 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:00:30.046  6286  6286 D BluetoothInputDevice: Proxy object connected
08-05 11:00:30.046  6286  6286 D HidProfile: Bluetooth service connected
08-05 11:00:30.048  1848  1848 D BluetoothHeadset: Proxy object connected
08-05 11:00:30.049  6286  6438 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 11:00:30.050  6286  6286 D BluetoothMap: Proxy object connected
08-05 11:00:30.050  6286  6286 D MapProfile: Bluetooth service connected
08-05 11:00:30.050  6286  6286 D BluetoothMap: getConnectedDevices()
08-05 11:00:30.051  1032  1115 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 11:00:30.052  1032  1115 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 11:00:30.053  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:30.054  1937  2131 D LGBluetoothAPIService: Message: 1
08-05 11:00:30.054  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:00:30.055  1937  2131 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,08-05 11:00:30.064  6201  6201 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 11:00:30.066  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:30.067  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:30.068  6448  6725 V BluetoothMapService: getConnectedDevices()
08-05 11:00:30.071  6286  6286 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-05 11:00:30.183  1032  1594 I art     : Explicit concurrent mark sweep GC freed 94549(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.896ms total 128.849ms
08-05 11:00:30.183  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 11:00:30.183  1032  1115 D BluetoothManagerService: Message: 40
08-05 11:00:30.183  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-05 11:00:30.185  6448  6448 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:30.185  6448  6448 D BluetoothMapService: STATE_ON
08-05 11:00:30.185  6448  6448 V BluetoothMapService: Handler(): got msg=1
08-05 11:00:30.186  6448  6448 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-05 11:00:30.187  1032  1115 D BluetoothManagerService: Message: 30
08-05 11:00:30.191  1937  2131 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-05 11:00:30.193  6448  6728 D BluetoothMapMasInstance: MAS initSocket()
08-05 11:00:30.193  6448  6728 D BluetoothMapMasInstance:   masId = 00
08-05 11:00:30.193  6448  6728 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 11:00:30.193  6448  6728 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 11:00:30.193  6448  6728 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 11:00:30.195  1032  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:30.196  6448  6728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 11:00:30.198  6448  6728 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 11:00:30.198  6448  6728 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 11:00:30.198  6448  6728 D BluetoothMapMasInstance: Accepting socket connection...
08-05 11:00:30.198  6286  6286 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-05 11:00:30.201  6448  6635 D BluetoothAdapterProperties: Scan Mode:21
08-05 11:00:30.201  6448  6635 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 11:00:30.202  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:30.203  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:30.206  1032  1115 D BluetoothManagerService: Message: 30
08-05 11:00:30.214  6286  6286 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-05 11:00:30.215  6286  6286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 11:00:30.215  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:30.216  6448  6448 V BluetoothPbapService: Pbap Service onCreate
08-05 11:00:30.216  6448  6448 V BluetoothPbapService: Starting PBAP service
08-05 11:00:30.217  6448  6448 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 11:00:30.218  6448  6448 V BluetoothPbapService: Pbap Service onBind
08-05 11:00:30.218  6286  6286 D BluetoothA2dp: Proxy object connected
08-05 11:00:30.218  6448  6448 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:30.218  6448  6448 V BluetoothPbapService: state: 12
08-05 11:00:30.219  6286  6286 D A2dpProfile: Bluetooth service connected
08-05 11:00:30.220  6286  6286 D BluetoothHeadset: Proxy object connected
08-05 11:00:30.220  6448  6448 D LGBluetoothAPIServer: [BTUI] onCreate()
08-05 11:00:30.220  6448  6448 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 11:00:30.220  6286  6286 D HeadsetProfile: Bluetooth service connected
08-05 11:00:30.221  6448  6448 V BluetoothPbapService: Handler(): got msg=1
08-05 11:00:30.221  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 11:00:30.221  6448  6448 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 11:00:30.221  1937  2131 D LGBluetoothAPIService: Message: 100
08-05 11:00:30.221  1937  2131 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 11:00:30.222  6448  6448 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:00:30.222  6448  6448 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:30.222  6448  6448 V BluetoothPbapReceiver: ***********state = 12
08-05 11:00:30.222  6448  6729 V BluetoothPbapService: Pbap Service initSocket
08-05 11:00:30.223  1032  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:30.223  6448  6729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:30.225  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:00:30.225  6448  6729 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 11:00:30.226  6448  6729 V BluetoothPbapService: Succeed to create listening socket 
08-05 11:00:30.226  6448  6729 V BluetoothPbapService: Accepting socket connection...
08-05 11:00:30.226  2179  2179 D c       : Getting all permits...
08-05 11:00:30.226  2179  2179 D a       : Opening database...
08-05 11:00:30.227  6286  6286 D DockEventReceiver: finishStartingService: stopping service
08-05 11:00:30.228  6286  6286 D BluetoothPbap: Proxy object connected
08-05 11:00:30.228  6286  6286 D PbapServerProfile: Bluetooth service connected
08-05 11:00:30.231  2179  2179 D a       : Opening database auth.proximity.permit_store...
08-05 11:00:30.232  2179  2179 D a       : Closing database...
08-05 11:00:30.240  6286  6286 D BluetoothPermissionRequest: onReceive
,08-05 11:00:30.242  6286  6286 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 11:00:30.243  6286  6286 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:00:30.246  6448  6448 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-05 11:00:30.247  6448  6448 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 11:00:30.251  6448  6448 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-05 11:00:30.262  6448  6448 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 11:00:30.262  6448  6448 V BtOppService: onCreate
,08-05 11:00:30.264  6448  6448 V BluetoothOppNotification: send message
08-05 11:00:30.266  6448  6448 V BtOppService: Starting RfcommListener
08-05 11:00:30.270  6448  6448 D BluetoothOppPreference: Dumping Names:  
08-05 11:00:30.270  6448  6448 D BluetoothOppPreference: {}
08-05 11:00:30.270  6448  6448 D BluetoothOppPreference: Dumping Channels:  
08-05 11:00:30.270  6448  6448 D BluetoothOppPreference: {}
08-05 11:00:30.270  6448  6448 V BtOppService: onStartCommand
08-05 11:00:30.271  6448  6736 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 11:00:30.273  6448  6448 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:30.274  6448  6448 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 11:00:30.276  6448  6448 V BluetoothOppNotification: new notify threadi!
,08-05 11:00:30.277  6448  6448 V BluetoothOppNotification: send delay message
08-05 11:00:30.277  6448  6448 V BtOppService: start RfcommListener
08-05 11:00:30.281  6448  6448 V BtOppService: RfcommListener started
08-05 11:00:30.283  6448  6738 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 11:00:30.283  1032  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:30.284  6448  6738 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:30.285  6448  6738 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-05 11:00:30.285  6448  6737 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 11:00:30.286  6448  6736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:00:30.287  6448  6738 V BtOppRfcommListener: Started RFCOMM listener....
08-05 11:00:30.287  6448  6738 I BtOppRfcommListener: Accept thread started.
08-05 11:00:30.287  6448  6733 V BtOppService: Deleted complete outbound shares, number =  0
08-05 11:00:30.287  6448  6738 V BtOppRfcommListener: Accepting connection...
,08-05 11:00:30.291  6448  6736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@368edc84 on behalf of 
08-05 11:00:30.292  6448  6733 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 11:00:30.292  6448  6737 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa5d297 on behalf of 
08-05 11:00:30.293  6448  6733 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 11:00:30.293  6448  6737 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 11:00:30.294  6448  6736 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 11:00:30.294  6448  6736 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:00:30.294  6448  6733 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@141c4c6d on behalf of 
08-05 11:00:30.295  6448  6737 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 11:00:30.295  6448  6736 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38a3f0a2 on behalf of 
08-05 11:00:30.296  6448  6736 V BluetoothOppNotification: update too frequent, put in queue
08-05 11:00:30.297  6448  6736 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 11:00:30.298  6448  6737 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@106b0133 on behalf of 
08-05 11:00:30.298  6448  6737 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-05 11:00:30.301  6448  6737 V BluetoothOppNotification: outbound notification was removed.
08-05 11:00:30.301  6448  6737 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 11:00:30.302  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:30.302  6448  6448 V BluetoothFtpService: Ftp Service onCreate
08-05 11:00:30.302  6448  6448 I BluetoothFtpService: Ftp Service onCreate
08-05 11:00:30.302  6448  6448 V BluetoothFtpService: Ftp Service onStartCommand
08-05 11:00:30.302  6448  6448 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:30.302  6448  6448 V BluetoothFtpService: Starting Listening on sockets
08-05 11:00:30.303  6448  6448 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:00:30.303  6448  6448 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:00:30.303  6448  6448 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:00:30.303  6448  6448 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:30.303  6448  6448 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 11:00:30.303  6448  6448 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 11:00:30.304  6448  6737 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16be4269 on behalf of 
08-05 11:00:30.305  6448  6737 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 11:00:30.306  6448  6448 V BtOppService: ContentObserver received notification
08-05 11:00:30.308  6448  6448 V BtOppService: ContentObserver received notification
08-05 11:00:30.308  6448  6448 V BluetoothFtpService: Handler(): got msg=1
08-05 11:00:30.309  6448  6739 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 11:00:30.309  6448  6739 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:00:30.309  6448  6737 V BluetoothOppNotification: inbound notification was removed.
08-05 11:00:30.309  6448  6448 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 11:00:30.310  6448  6737 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 11:00:30.310  6448  6448 V BluetoothFtpService: Ftp Service initSocket
08-05 11:00:30.311  6448  6739 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d7474ee on behalf of 
08-05 11:00:30.311  6448  6737 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@344a7d8f on behalf of 
08-05 11:00:30.312  6448  6739 V BluetoothOppNotification: update too frequent, put in queue
,08-05 11:00:30.313  6448  6739 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-05 11:00:30.314  1032  1048 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:30.315  6448  6448 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:30.316  6448  6448 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-05 11:00:30.316  6448  6448 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-05 11:00:30.320  6448  6740 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-05 11:00:30.334  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:30.334  6448  6448 V BluetoothSapService: Sap Service onCreate
,08-05 11:00:30.337  6448  6448 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:30.337  6448  6448 V BluetoothSapService: state: 12
08-05 11:00:30.337  6448  6448 V BluetoothSapService: Starting SAP server process
08-05 11:00:30.339  6448  6448 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 11:00:30.323  6741  6741 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:30.323  6741  6741 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:30.341  6448  6742 V BluetoothSapService: Sap Service initRfcommSocket
08-05 11:00:30.342  1032  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:30.343  6448  6742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:30.346  6448  6742 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-05 11:00:30.346  6448  6742 V BluetoothSapService: Succeed to create listening socket 
08-05 11:00:30.346  6448  6742 V BluetoothSapService: Accepting socket connection...
,08-05 11:00:30.352  6741  6741 V BT_SAP  : Event pipe created
,08-05 11:00:30.352  6741  6741 V BT_SAP  : create_server_socket qcom.sap.server
08-05 11:00:30.352  6741  6741 V BT_SAP  : created socket fd 6
08-05 11:00:30.849  1032  1532 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:30.849  1032  1532 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:00:30.869  1032  1534 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-05 11:00:30.871  1032  1534 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-05 11:00:31.278  6448  6448 V BluetoothOppNotification: new notify threadi!
,08-05 11:00:31.279  6448  6448 V BluetoothOppNotification: send delay message
,08-05 11:00:31.290  6448  6752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 11:00:31.294  6448  6752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26fb63ab on behalf of 
08-05 11:00:31.296  6448  6752 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 11:00:31.302  6448  6752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-05 11:00:31.306  6448  6752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32a9ba08 on behalf of 
08-05 11:00:31.307  6448  6752 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 11:00:31.309  6448  6752 V BluetoothOppNotification: outbound notification was removed.
08-05 11:00:31.309  6448  6752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 11:00:31.310  6448  6752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3322d5a1 on behalf of 
08-05 11:00:31.311  6448  6752 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 11:00:31.314  6448  6752 V BluetoothOppNotification: inbound notification was removed.
08-05 11:00:31.314  6448  6752 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 11:00:31.315  6448  6752 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e7233c6 on behalf of 
08-05 11:00:31.737  1032  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:31.738  1032  2028 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@a865bf1 mBinding = false
,08-05 11:00:31.769  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:00:31.769  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:00:31.769  1032  1032 D Ulp_jni : JNI:system_update. Event-4
,08-05 11:00:31.773  1032  1115 D BluetoothManagerService: Message: 2
08-05 11:00:31.774  1032  1115 D BluetoothManagerService: Sending off request.
08-05 11:00:31.774  6448  6636 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-05 11:00:31.775  6448  6631 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-05 11:00:31.775  6448  6631 D BluetoothAdapterProperties: Setting state to 13
08-05 11:00:31.775  6448  6631 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 11:00:31.776  6448  6631 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 11:00:31.776  6448  6631 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-05 11:00:31.778  6448  6635 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:00:31.779  6448  6631 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 11:00:31.782  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-05 11:00:31.782  6448  6675 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-05 11:00:31.786  6448  6728 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-05 11:00:31.786  6448  6728 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:31.786  6448  6728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-05 11:00:31.786  6448  6728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-05 11:00:31.786  6448  6728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-05 11:00:31.786  6448  6728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-05 11:00:31.786  6448  6728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-05 11:00:31.786  6448  6728 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-05 11:00:31.786  6448  6729 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:31.787  6448  6738 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:31.788  6448  6631 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-05 11:00:31.789  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-05 11:00:31.789  6448  6675 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 11:00:31.800  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:31.800  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:31.800  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:31.800  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:31.800  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:31.800  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:00:31.800  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:31.800  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:31.800  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:00:31.807  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:31.807  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:31.812  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:31.812  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:31.812  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:31.812  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:31.812  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:31.812  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:00:31.812  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:31.812  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:31.812  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:31.814  6201  6201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:00:31.814  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:00:31.816  1032  1115 D BluetoothManagerService: Message: 60
08-05 11:00:31.817  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-05 11:00:31.817  1032  1115 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-05 11:00:31.820  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:31.821  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:00:31.826  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:00:31.830  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:31.831  6448  6448 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:31.832  6448  6448 D BluetoothMapService: STATE_TURNING_OFF
08-05 11:00:31.832  6448  6448 V BluetoothMapService: Handler(): got msg=4
08-05 11:00:31.832  6448  6448 D BluetoothMapService: MAP Service closeService in
08-05 11:00:31.832  6448  6448 D BluetoothMapMasInstance: MAP Service shutdown
08-05 11:00:31.832  6448  6448 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:00:31.832  6448  6448 V BluetoothMapService: MAP Service closeService out
08-05 11:00:31.834  6448  6448 V BtOppService: Receiver DISABLED_ACTION 
08-05 11:00:31.834  6448  6448 I BtOppRfcommListener: stopping Accept Thread
08-05 11:00:31.834  6448  6448 V BtOppRfcommListener: close mBtServerSocket
08-05 11:00:31.834  6448  6738 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 11:00:31.835  6448  6448 V BtOppRfcommListener: waiting for thread to terminate
08-05 11:00:31.835  6448  6448 V BtOppRfcommListener: done waiting for thread to terminate
08-05 11:00:31.838  6286  6286 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-05 11:00:31.845  6448  6740 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:31.848  6448  6742 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:00:31.853  6286  6286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 11:00:31.857  6448  6448 V BtOppService: onDestroy
08-05 11:00:31.858  6448  6448 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-05 11:00:31.863  6448  6448 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:00:31.863  6448  6448 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:31.863  6448  6448 V BluetoothPbapReceiver: ***********state = 13
08-05 11:00:31.864  6448  6448 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-05 11:00:31.866  6448  6448 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:31.866  6448  6448 V BluetoothPbapService: state: 13
08-05 11:00:31.866  6448  6448 V BluetoothPbapService: Pbap Service closeService in
,08-05 11:00:31.873  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:00:31.874  6448  6448 V BluetoothPbapService: successfully stopped pbap service
08-05 11:00:31.874  6448  6448 V BluetoothPbapService: Pbap Service closeService out
08-05 11:00:31.875  6448  6448 V BluetoothPbapService: Pbap Service onDestroy
08-05 11:00:31.875  6448  6448 V BluetoothPbapService: Pbap Service closeService in
08-05 11:00:31.875  6448  6448 V BluetoothPbapService: Pbap Service closeService out
08-05 11:00:31.875  6448  6448 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-05 11:00:31.888  6286  6286 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:00:31.892  6286  6286 D BluetoothPbap: Proxy object disconnected
08-05 11:00:31.892  6286  6286 D PbapServerProfile: Bluetooth service disconnected
08-05 11:00:31.916  6286  6286 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-05 11:00:31.921  6286  6286 D BluetoothPermissionRequest: onReceive
08-05 11:00:31.922  6286  6286 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-05 11:00:31.928  6286  6286 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:00:31.931  6448  6448 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-05 11:00:31.931  6448  6448 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-05 11:00:31.931  6448  6448 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-05 11:00:31.936  6448  6448 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:31.936  6448  6448 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 11:00:31.937  6448  6448 V BluetoothFtpService: Ftp Service onStartCommand
08-05 11:00:31.937  6448  6448 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:31.937  6448  6448 V BluetoothFtpService: Ftp Service closeService
08-05 11:00:31.937  6448  6448 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-05 11:00:31.939  6448  6448 V BluetoothFtpService: successfully stopped ftp service
08-05 11:00:31.939  6448  6448 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:00:31.939  6448  6448 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:00:31.939  6448  6448 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:00:31.939  6448  6448 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:31.939  6448  6448 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-05 11:00:31.939  6448  6448 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 11:00:31.941  6448  6448 V BluetoothFtpService: Ftp Service onDestroy
08-05 11:00:31.941  6448  6448 V BluetoothFtpService: Ftp Service closeService
08-05 11:00:31.946  6448  6448 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:31.946  6448  6448 V BluetoothSapService: state: 13
08-05 11:00:31.946  6448  6448 V BluetoothSapService: Stopping SAP server process
08-05 11:00:31.946  6448  6448 V BluetoothSapService: Sap Service closeSapService in
,08-05 11:00:31.946  6448  6448 V BluetoothSapService: Close listen Socket : 
08-05 11:00:31.947  6448  6448 V BluetoothSapService: Close rfcomm Socket : 
08-05 11:00:31.947  6448  6448 V BluetoothSapService: Close sapd  Socket : 
08-05 11:00:31.951  6448  6448 V BluetoothSapService: Sap Service closeSapService out
08-05 11:00:31.951  6448  6448 V BluetoothSapService: Sap Service onDestroy
08-05 11:00:31.951  6448  6448 V BluetoothSapService: Sap Service closeSapService in
08-05 11:00:31.951  6448  6448 V BluetoothSapService: Close listen Socket : 
08-05 11:00:31.951  6448  6448 V BluetoothSapService: Close rfcomm Socket : 
08-05 11:00:31.951  6448  6448 V BluetoothSapService: Close sapd  Socket : 
08-05 11:00:31.952  6448  6448 V BluetoothSapService: Sap Service closeSapService out
,08-05 11:00:32.706  6448  6635 D bt_hci_bdroid: cleanup
,08-05 11:00:32.714  6448  6677 I bt_lpm  : LPM is already off!!!
08-05 11:00:32.715  6448  6698 I bt_userial_mct: exiting userial_read_thread
08-05 11:00:32.715  6448  6698 D bt_userial_mct: Leaving userial_evt_read_thread()
08-05 11:00:32.716  6448  6675 W bt-btif : ag scb idx 1 not allocated
08-05 11:00:32.716  6448  6675 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:32.716  6448  6675 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:00:32.717  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:32.717  6448  6675 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:00:32.717  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-05 11:00:32.717  6448  6675 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:00:32.717  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-05 11:00:32.717  6448  6675 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:00:32.717  6448  6675 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-05 11:00:32.717  6448  6675 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 11:00:32.717  6448  6675 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-05 11:00:32.718  6448  6635 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-05 11:00:32.718  6448  6677 I bt_vendor: hw_epilog_process
08-05 11:00:32.718  6448  6635 D bt_hci_bdroid: cleanup Finalizing cleanup
08-05 11:00:32.718  6448  6635 D bt_userial_mct: userial_close
08-05 11:00:32.718  6448  6635 E bt_userial_mct: pthread_join() FAILED result:3
08-05 11:00:32.718  6448  6635 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-05 11:00:32.724  6448  6635 D bt_hci_bdroid: set_power 0
08-05 11:00:32.724  6448  6635 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-05 11:00:32.724  6448  6635 I bt_vendor: bluetooth satus is on
08-05 11:00:32.724  6448  6635 I bt_vendor: bt-vendor : resetting BT status
08-05 11:00:32.724  6448  6635 I bt_vendor: Starting hciattach daemon
08-05 11:00:32.724  6448  6635 I bt_vendor: try to set false
,08-05 11:00:32.730  6448  6635 I bt_vendor: Starting hciattach daemon
08-05 11:00:32.730  6448  6635 I bt_vendor: try to set false
08-05 11:00:32.731  6448  6635 I bt_vendor: cleanup
08-05 11:00:32.732  6448  6675 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 11:00:32.732  6448  6635 I GKI_LINUX: GKI_exit_task 0 done
08-05 11:00:32.733  6448  6635 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-05 11:00:32.734  6448  6631 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 11:00:32.741  6448  6448 D HeadsetService: Received stop request...Stopping profile...
,08-05 11:00:32.746  6448  6448 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 11:00:32.746  6448  6448 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:00:32.746  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:32.746  6448  6656 D HeadsetStateMachine: Exit Disconnected: -1
08-05 11:00:32.749  6448  6631 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 11:00:32.751  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-05 11:00:32.751  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-05 11:00:32.751  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-05 11:00:32.751  1032  1032 D BluetoothHeadset: Proxy object disconnected
08-05 11:00:32.751  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 11:00:32.752  6448  6448 D A2dpService: Received stop request...Stopping profile...
08-05 11:00:32.754  6448  6664 D A2dpStateMachine: Exit Disconnected: -1
,08-05 11:00:32.758  6448  6448 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-05 11:00:32.760  6448  6448 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-05 11:00:32.760  6448  6448 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:00:32.760  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:32.761  1032  1032 D BluetoothA2dp: Proxy object disconnected
08-05 11:00:32.761  1032  1032 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 11:00:32.762  6448  6448 D HidService: Received stop request...Stopping profile...
08-05 11:00:32.762  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:32.767  6448  6448 D HealthService: Received stop request...Stopping profile...
,08-05 11:00:32.770  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:32.772  6448  6448 D PanService: Received stop request...Stopping profile...
08-05 11:00:32.773  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:32.774  6448  6448 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 11:00:32.775  6448  6448 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 11:00:32.775  6448  6448 D BtGatt.GattService: stop()
08-05 11:00:32.775  6448  6448 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 11:00:32.776  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:32.778  6448  6448 D BluetoothMapService: Received stop request...Stopping profile...
08-05 11:00:32.778  6448  6448 D BluetoothMapService: stop()
08-05 11:00:32.778  6448  6448 D BluetoothMapEmailAppObserver: deinitObservers()
08-05 11:00:32.778  6448  6448 D BluetoothMapEmailAppObserver: removeReceiver()
,08-05 11:00:32.782  6448  6448 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34f67b3a
08-05 11:00:32.784  6448  6448 D HeadsetStateMachine: Unbinding service...
08-05 11:00:32.785  6448  6448 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:00:32.785  6448  6448 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:00:32.785  6448  6448 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:00:32.785  6448  6448 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:00:32.785  6448  6448 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 11:00:32.785  6448  6448 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:00:32.785  6448  6448 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-05 11:00:32.786  6448  6448 I BluetoothA2dpServiceJni: cleanupNative
08-05 11:00:32.786  6448  6665 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 11:00:32.787  6448  6448 I GKI_LINUX: GKI_exit_task 2 done
08-05 11:00:32.787  6448  6448 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 11:00:32.787  6448  6448 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 11:00:32.787  6448  6448 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 11:00:32.787  6448  6448 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 11:00:32.788  6448  6448 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:00:32.788  6448  6448 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:00:32.788  6448  6448 V BluetoothMapService: Handler(): got msg=4
08-05 11:00:32.788  6448  6448 D BluetoothMapService: MAP Service closeService in
08-05 11:00:32.788  6448  6448 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:00:32.788  6448  6448 V BluetoothMapService: MAP Service closeService out
08-05 11:00:32.789  6448  6631 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-05 11:00:32.789  6448  6631 D BluetoothAdapterProperties: Setting state to 10
08-05 11:00:32.789  6448  6631 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 11:00:32.789  6448  6448 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 11:00:32.789  6448  6448 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 11:00:32.791  1032  1115 D BluetoothManagerService: Message: 60
08-05 11:00:32.791  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-05 11:00:32.791  1032  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
,08-05 11:00:32.796  6448  6631 I BluetoothAdapterState: Entering OffState
08-05 11:00:32.797  6448  6448 D BluetoothMapService: cleanup()
08-05 11:00:32.797  6448  6448 D BluetoothMapService: MAP Service closeService in
08-05 11:00:32.797  6448  6448 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-05 11:00:32.797  6448  6448 V BluetoothMapService: MAP Service closeService out
08-05 11:00:32.798  6286  6302 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:00:32.799  1848  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:00:32.800  6286  6302 D BluetoothPan: onBluetoothStateChange on: false
08-05 11:00:32.800  1032  1115 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:00:32.800  6286  6302 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:00:32.801  1848  2430 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:00:32.804  6286  6302 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-05 11:00:32.808  6286  6302 D BluetoothMap: onBluetoothStateChange: up=false
08-05 11:00:32.808  1032  1115 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:00:32.809  1848  2735 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:00:32.809  6286  6302 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 11:00:32.810  1032  1115 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-05 11:00:32.810  1032  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-05 11:00:32.813  1032  1115 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-05 11:00:32.813  1032  1115 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-05 11:00:32.813  1032  1115 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@a865bf1 mBinding = false
08-05 11:00:32.814  1032  1115 D BluetoothManagerService: Sending unbind request.
08-05 11:00:32.818  6448  6635 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-05 11:00:32.821  6448  6448 I GKI_LINUX: GKI_exit_task 1 done
08-05 11:00:32.821  6448  6448 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-05 11:00:32.822  6448  6448 I BluetoothServiceJni: cleanupNative: return from cleanup
08-05 11:00:32.822  6448  6448 I art     : --- WEIRD: removing null entry 248
08-05 11:00:32.822  6448  6448 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-05 11:00:32.823  6448  6448 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-05 11:00:32.823  6448  6448 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-05 11:00:32.825  1032  1115 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-05 11:00:32.827  6448  6448 I art     : System.exit called, status: 0
08-05 11:00:32.827  6448  6448 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-05 11:00:32.846   322  1385 V AudioFlinger: 6448 died, releasing its sessions
08-05 11:00:32.846   322  1385 V AudioFlinger:  pid 1848 @ 0
08-05 11:00:32.846   322  1385 V AudioFlinger:  pid 3426 @ 1
08-05 11:00:32.846   322  1385 V AudioFlinger:  pid 3426 @ 2
,08-05 11:00:32.850  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-05 11:00:32.850  1937  2131 D LGBluetoothAPIService: Message: 101
08-05 11:00:32.850  1937  2131 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-05 11:00:32.851  1937  2131 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-05 11:00:32.851  1937  2131 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-05 11:00:32.854  6286  6286 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-05 11:00:32.970  1032  2001 I ActivityManager: Process com.android.bluetooth (pid 6448) has died
08-05 11:00:32.970  1032  2001 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-05 11:00:32.971  1032  2001 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-05 11:00:32.982  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:00:32.983  1937  2131 D LGBluetoothAPIService: Message: 2
08-05 11:00:32.983  1937  2131 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-05 11:00:32.984  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:00:32.989  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:32.990  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:00:32.996  6286  6286 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-05 11:00:32.996  6286  6286 D LGBluetoothEventManager: [BTUI] clear device connection state
08-05 11:00:32.999  1599  1599 D BluetoothAdapter: 976700317: getState() :  mService = null. Returning STATE_OFF
08-05 11:00:32.999  1599  1599 D BluetoothAdapter: 976700317: getState() :  mService = null. Returning STATE_OFF
08-05 11:00:33.001  6286  6286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-05 11:00:33.052  1032  2009 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6796 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-05 11:00:33.054  6286  6286 D DockEventReceiver: finishStartingService: stopping service
08-05 11:00:33.074   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 463us total 22.868ms
,08-05 11:00:33.097   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 446us total 20.727ms
,08-05 11:00:33.110  6796  6796 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-05 11:00:33.111  6796  6796 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:00:33.111  6796  6796 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-05 11:00:33.112  6796  6796 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 11:00:33.119   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 21.450ms
08-05 11:00:33.131  6796  6796 D BluetoothAdapterApp: Loading JNI Library
,08-05 11:00:33.167  6796  6796 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1f9891e2 Instance Count = 1
,08-05 11:00:33.173  6796  6796 D BluetoothAdapterApp: onCreate
,08-05 11:00:33.200  6796  6796 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-05 11:00:33.200  6796  6796 D ProfileConfigQcom: Adding HeadsetService
08-05 11:00:33.200  6796  6796 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-05 11:00:33.201  6796  6796 D ProfileConfigQcom: Adding A2dpService
08-05 11:00:33.201  6796  6796 D ProfileConfigQcom: [BTUI] HidService is supported
08-05 11:00:33.201  6796  6796 D ProfileConfigQcom: Adding HidService
08-05 11:00:33.201  6796  6796 D ProfileConfigQcom: [BTUI] HealthService is supported
08-05 11:00:33.202  6796  6796 D ProfileConfigQcom: Adding HealthService
08-05 11:00:33.202  6796  6796 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-05 11:00:33.203  6796  6796 D ProfileConfigQcom: [BTUI] PanService is supported
08-05 11:00:33.203  6796  6796 D ProfileConfigQcom: Adding PanService
08-05 11:00:33.203  6796  6796 D ProfileConfigQcom: [BTUI] GattService is supported
08-05 11:00:33.203  6796  6796 D ProfileConfigQcom: Adding GattService
08-05 11:00:33.204  6796  6796 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-05 11:00:33.204  6796  6796 D ProfileConfigQcom: Adding BluetoothMapService
08-05 11:00:33.204  6796  6796 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-05 11:00:33.205  6796  6796 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:00:33.206  6796  6796 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:33.207  6796  6796 V BluetoothPbapReceiver: ***********state = 10
08-05 11:00:33.209  6796  6796 V LGMDMManagerInternal: Create singleton instance
08-05 11:00:33.301  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:00:33.313  6286  6286 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-05 11:00:33.317  6796  6796 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-05 11:00:33.317  6796  6796 D LGBluetoothAPIServer: [BTUI] onBind()
08-05 11:00:33.321  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-05 11:00:33.321  1937  2131 D LGBluetoothAPIService: Message: 100
08-05 11:00:33.321  1937  2131 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-05 11:00:33.327  6286  6286 D BluetoothPermissionRequest: onReceive
08-05 11:00:33.331  6286  6286 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 11:00:33.331  6286  6286 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-05 11:00:33.335  6286  6286 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:00:33.341  6796  6796 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-05 11:00:33.346  6796  6796 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:00:33.351  6796  6796 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:00:33.351  6796  6796 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:00:33.352  6796  6796 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:00:33.353  6796  6796 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:33.354  6796  6796 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-05 11:00:33.357  6373  6373 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-05 11:00:34.851  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:34.852  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:00:37.868  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:37.868  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1949e5fe added. We now have 6 listener(s)
08-05 11:00:37.868  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:00:37.877  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:37.877  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28fe815f added. We now have 7 listener(s)
08-05 11:00:37.877  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:37.877  6201  6264 I System.out: IsBluetoothEnabled
08-05 11:00:37.878  1032  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:37.878  1032  1955 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-05 11:00:37.879  1032  1115 D BluetoothManagerService: Message: 2
08-05 11:00:37.882  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:37.882  1032  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:37.882  1032  2001 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-05 11:00:37.899  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-05 11:00:37.900  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:00:37.900  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-05 11:00:37.901  1032  1115 D BluetoothManagerService: Message: 1
08-05 11:00:37.901  1032  1115 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-05 11:00:37.924  1032  1115 D BluetoothManagerService: Message: 20
08-05 11:00:37.924  1032  1115 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@370151b0:true
,08-05 11:00:37.928  6796  6796 D BluetoothAdapterState: make
08-05 11:00:37.933  6796  6796 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-05 11:00:37.933  6796  6796 I bluedroid-qcom: init
08-05 11:00:37.934  6796  6823 I BluetoothAdapterState: Entering OffState
08-05 11:00:37.935  6796  6796 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 11:00:37.935  6796  6796 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 11:00:37.935  6796  6796 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 11:00:37.935  6796  6796 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 11:00:37.935  6796  6796 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-05 11:00:37.937  6796  6796 I bluedroid-qcom: get_profile_interface socket
08-05 11:00:37.937  6796  6796 I bluedroid-qcom: get_profile_interface map_client
,08-05 11:00:37.941  6796  6827 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 11:00:37.933  6826  6826 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:37.946  6796  6827 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-05 11:00:37.933  6826  6826 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:37.956  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-05 11:00:37.958  1032  1115 D BluetoothManagerService: Message: 40
08-05 11:00:37.958  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-05 11:00:37.961  6826  6826 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-05 11:00:37.961  6826  6826 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-05 11:00:37.961  6826  6826 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-05 11:00:37.962  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 11:00:37.963  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 11:00:37.963  6796  6811 I bluedroid-qcom: config_hci_snoop_log
08-05 11:00:37.965  1032  1115 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-05 11:00:37.965  1032  1115 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-05 11:00:37.965  6826  6826 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-05 11:00:37.969  6826  6826 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-05 11:00:37.969  6826  6826 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-05 11:00:37.977  6796  6823 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-05 11:00:37.978  6796  6827 D BluetoothAdapterProperties: Name is: G3
08-05 11:00:37.978  6796  6823 D BluetoothAdapterProperties: Setting state to 11
08-05 11:00:37.978  6796  6823 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 11:00:37.979  1032  1115 D BluetoothManagerService: Message: 60
08-05 11:00:37.979  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-05 11:00:37.979  1032  1115 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-05 11:00:37.983  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:00:37.986  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:00:37.989  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:37.995  6796  6823 I LGBluetoothServiceJni: classInitNative: succeeds
,08-05 11:00:38.002  6796  6823 D BluetoothBondStateMachine: make
08-05 11:00:38.003  6286  6286 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-05 11:00:38.010  6796  6796 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:00:38.010  6796  6796 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:38.010  6796  6796 V BluetoothPbapReceiver: ***********state = 11
,08-05 11:00:38.025  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:00:38.025  6796  6823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.025  6796  6823 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-05 11:00:38.026  6796  6823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.026  6796  6823 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-05 11:00:38.027  6796  6823 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
,08-05 11:00:38.029  6796  6828 I BluetoothBondStateMachine: StableState(): Entering Off State
08-05 11:00:38.035  6796  6823 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:00:38.042  6796  6823 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:00:38.042  6796  6796 D HeadsetService: Received start request. Starting profile...
08-05 11:00:38.044  6796  6796 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-05 11:00:38.044  6286  6286 D BluetoothPermissionRequest: onReceive
08-05 11:00:38.045  6796  6796 D LGBluetoothHfpAdapter: Version 1.6
08-05 11:00:38.048  6796  6796 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-05 11:00:38.049  6796  6796 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 11:00:38.049  6796  6796 D HeadsetStateMachine: make
08-05 11:00:38.050  6796  6823 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:00:38.051  6286  6286 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:00:38.058  6796  6823 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:00:38.065  6796  6823 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:00:38.070  6796  6823 E BluetoothAdapterService: File transfer profiles supported!!
,08-05 11:00:38.076  6796  6823 E BluetoothAdapterService: File transfer profiles supported!!
08-05 11:00:38.085  6796  6796 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 11:00:38.085  6796  6796 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:00:38.089  6796  6796 D HeadsetStateMachine: max_hf_connections = 1
08-05 11:00:38.089  6796  6796 I bluedroid-qcom: get_profile_interface handsfree
08-05 11:00:38.091  6796  6796 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-05 11:00:38.091   322  1385 V AudioPolicyService: registerClient() client 0xb04102e0, uid 1002
08-05 11:00:38.091   322  1384 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-05 11:00:38.091   322  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:00:38.091   322  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:00:38.092  6796  6796 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-05 11:00:38.092   322   322 V AudioFlinger: registerClient() client 0xb14330a0, pid 6796
08-05 11:00:38.092   322  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:38.092   322  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:00:38.093  6796  6796 V ToneGenerator: Create Track: 0xb4928080
,08-05 11:00:38.093  6796  6796 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-05 11:00:38.093  6796  6796 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-05 11:00:38.093  1032  2028 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:38.093  1032  2028 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:00:38.093  1848  1863 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:38.093  1848  1863 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:00:38.093  3426  3441 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:38.093  3426  3441 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-05 11:00:38.093   322  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:38.093   322  1377 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:38.093  6796  6811 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:38.093  6796  6811 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-05 11:00:38.093  3426  3442 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:38.093  3426  3442 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:38.093  1032  1954 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:38.093  1032  1954 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:38.094   322  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 11:00:38.094   322  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-05 11:00:38.094  1848  1864 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:38.094   322  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:00:38.094  1848  1864 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:38.094   322  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:00:38.094  1599  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-05 11:00:38.094  1599  1621 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-05 11:00:38.094  1599  1621 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:38.094  1599  1621 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-05 11:00:38.094  6796  6812 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-05 11:00:38.094  6796  6812 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-05 11:00:38.094  6796  6823 V LGMDMManager: Create singleton instance
08-05 11:00:38.095   322  2139 I AudioFlinger: isAudioPlaybackHookOn() false
08-05 11:00:38.095   322  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-05 11:00:38.095   322  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-05 11:00:38.095   322  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-05 11:00:38.095   322  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-05 11:00:38.095  6796  6796 V AudioSystem: getLatency() output 2, latency 50
08-05 11:00:38.095  6796  6796 V AudioSystem: getFrameCount() output 2, frameCount 960
08-05 11:00:38.095  6796  6796 V AudioTrack: createTrack_l() output 2 afLatency 50
08-05 11:00:38.096  6796  6823 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-05 11:00:38.096   322  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 11:00:38.096   322  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 11:00:38.096   322  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-05 11:00:38.096   322  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-05 11:00:38.096   322  1385 V AudioFlinger: createTrack() lSessionId: 23
08-05 11:00:38.097  6796  6796 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-05 11:00:38.097   322   322 V AudioFlinger: acquiring 23 from 6796, for 6796
08-05 11:00:38.097   322   322 V AudioFlinger:  added new entry for 23
08-05 11:00:38.097  6796  6796 V ToneGenerator: ToneGenerator INIT OK, time: 378024
08-05 11:00:38.097  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
,08-05 11:00:38.098  6796  6844 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-05 11:00:38.098  6796  6844 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-05 11:00:38.098  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.101  6796  6796 D A2dpService: Received start request. Starting profile...
08-05 11:00:38.101  6796  6844 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-05 11:00:38.101  6796  6796 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 11:00:38.101  6796  6844 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-05 11:00:38.102   322  2139 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6796
08-05 11:00:38.102   322  2139 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-05 11:00:38.102   322  2139 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-05 11:00:38.102   322  2139 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-05 11:00:38.102   322  2139 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-05 11:00:38.102   322  2139 V voice   : voice_set_parameters: exit with code(0)
08-05 11:00:38.102   322  2139 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-05 11:00:38.102   322  2139 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-05 11:00:38.102  6796  6796 V Avrcp   : make
08-05 11:00:38.102   322  2139 V msm8974_platform: platform_set_parameters: exit with code(0)
08-05 11:00:38.102   322  2139 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-05 11:00:38.102   322  2139 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-05 11:00:38.102   322  2139 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-05 11:00:38.102  6796  6796 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-05 11:00:38.102  6796  6796 I bluedroid-qcom: get_profile_interface avrcp
08-05 11:00:38.103  6796  6844 V ToneGenerator: ToneGenerator destructor
08-05 11:00:38.104  6796  6844 V ToneGenerator: stopTone
08-05 11:00:38.104  6796  6844 V ToneGenerator: Delete Track: 0xb4928080
08-05 11:00:38.105   322  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-05 11:00:38.105   322  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-05 11:00:38.105   322  1384 V AudioFlinger: PlaybackThread::Track destructor
08-05 11:00:38.105   322  1267 V AudioPolicyService: AudioCommandThread() waking up
08-05 11:00:38.105   322  1267 V AudioPolicyService: AudioCommandThread() processing release output 2
08-05 11:00:38.105   322  1384 V AudioFlinger: removeClient_l() pid 6796, calling pid 322
08-05 11:00:38.105   322  1267 V AudioPolicyManager: releaseOutput() 2
08-05 11:00:38.105   322  1267 V AudioPolicyService: AudioCommandThread() going to sleep
08-05 11:00:38.106  6796  6844 V AudioTrack: ~AudioTrack, releasing session id from 6796 on behalf of 6796
08-05 11:00:38.106   322  2139 V AudioFlinger: releasing 23 from 6796 for 6796
08-05 11:00:38.106   322  2139 V AudioFlinger:  decremented refcount to 0
08-05 11:00:38.106   322  2139 V AudioFlinger: purging stale effects
08-05 11:00:38.110  6796  6796 V AudioManager: registerRemoteController: size of Media player list: 0
08-05 11:00:38.111  6796  6796 E AudioManager: No RCC entry present to update
08-05 11:00:38.111  6796  6796 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-05 11:00:38.114  6796  6796 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-05 11:00:38.115  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-05 11:00:38.115  6796  6796 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-05 11:00:38.118  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 11:00:38.206  1032  1936 V SIM_STK : Menu title from STK is T-Mobile
08-05 11:00:38.206  1032  1936 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:00:38.283  1032  1955 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-05 11:00:38.292  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 11:00:38.297  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 11:00:38.297  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 11:00:38.297  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 11:00:38.297  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 11:00:38.298  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:00:38.298  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 11:00:38.298  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 11:00:38.298  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 11:00:38.298  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:00:38.298  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 11:00:38.299  6796  6796 I BluetoothA2dpServiceJni: classInitNative
08-05 11:00:38.299  6796  6796 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:00:38.299  6796  6796 D A2dpStateMachine: make
,08-05 11:00:38.304  6796  6796 I bluedroid-qcom: get_profile_interface a2dp
08-05 11:00:38.305  6796  6851 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 11:00:38.307  6796  6796 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:00:38.307  6796  6796 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-05 11:00:38.308  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.309  6796  6796 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 11:00:38.311  6796  6796 D HidService: Received start request. Starting profile...
08-05 11:00:38.311  6796  6796 I bluedroid-qcom: get_profile_interface hidhost
08-05 11:00:38.311  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.311  6796  6850 D A2dpStateMachine: Enter Disconnected: -2
08-05 11:00:38.311  6796  6796 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:00:38.312  6796  6796 D HealthService: Received start request. Starting profile...
,08-05 11:00:38.316  6796  6796 I bluedroid-qcom: get_profile_interface health
08-05 11:00:38.316  6796  6796 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:00:38.316  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.317  6796  6796 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-05 11:00:38.318  6796  6796 D PanService: Received start request. Starting profile...
08-05 11:00:38.319  6796  6796 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 11:00:38.319  6796  6796 I bluedroid-qcom: get_profile_interface pan
08-05 11:00:38.326  6796  6796 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-05 11:00:38.326  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.327  6796  6796 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-05 11:00:38.331  6796  6796 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 11:00:38.332  6796  6796 D BtGatt.GattService: Received start request. Starting profile...
08-05 11:00:38.332  6796  6796 D BtGatt.GattService: start()
08-05 11:00:38.332  6796  6796 I bluedroid-qcom: get_profile_interface gatt
08-05 11:00:38.332  6796  6796 D BtGatt.AdvertiseManager: advertise manager created
08-05 11:00:38.341  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.342  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.342  6796  6796 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-05 11:00:38.343  6796  6796 V BluetoothMapService: BluetoothMapBinder()
08-05 11:00:38.343  6796  6796 D BluetoothMapService: Received start request. Starting profile...
08-05 11:00:38.344  6796  6796 D BluetoothMapService: start()
,08-05 11:00:38.346  6796  6796 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-05 11:00:38.346  6796  6796 D BluetoothMapEmailAppObserver: createReceiver()
08-05 11:00:38.347  6796  6796 D BluetoothMapEmailAppObserver: initObservers()
08-05 11:00:38.347  6796  6796 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-05 11:00:38.353  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:38.353  6796  6796 D HeadsetStateMachine: Proxy object connected
08-05 11:00:38.354  6796  6796 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-05 11:00:38.354  6796  6796 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-05 11:00:38.359  6796  6796 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-05 11:00:38.359  6796  6844 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-05 11:00:38.361  6796  6844 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 11:00:38.361  6796  6844 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-05 11:00:38.364  6796  6796 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:00:38.370  6796  6796 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:00:38.371  6796  6796 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:00:38.375  6796  6796 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:00:38.378  6796  6796 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-05 11:00:38.378  6796  6796 V PanService: [BTUI] SIM Extra State :ABSENT
08-05 11:00:38.381  6796  6796 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-05 11:00:38.381  6796  6796 V BluetoothMapService: Handler(): got msg=1
08-05 11:00:38.382  6796  6796 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:00:38.382  6796  6796 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:00:38.382  6796  6796 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:00:38.382  6796  6796 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:38.382  6796  6796 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-05 11:00:38.383  6796  6823 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-05 11:00:38.384  6796  6823 I bluedroid-qcom: enable
08-05 11:00:38.384  6796  6861 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-05 11:00:38.387  6796  6823 I bt_hci_bdroid: init
08-05 11:00:38.387  6796  6861 I bt-btu  : btu_task pending for preload complete event
08-05 11:00:38.388  6796  6823 I bt_vendor: bt-vendor : init
08-05 11:00:38.388  6796  6823 I bt_vendor: bt-vendor : get_bt_soc_type
08-05 11:00:38.388  6796  6823 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-05 11:00:38.388  6796  6823 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-05 11:00:38.388  6796  6823 D bt_userial_mct: userial_init
08-05 11:00:38.389  6796  6823 D bt_hci_bdroid: set_power 1
08-05 11:00:38.389  6796  6823 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-05 11:00:38.389  6796  6823 I bt_vendor: Starting hciattach daemon
08-05 11:00:38.389  6796  6823 I bt_vendor: try to set true
08-05 11:00:38.373  6864  6864 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:38.373  6864  6864 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:38.443  6865  6865 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-05 11:00:38.564  6872  6872 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-05 11:00:38.579  6873  6873 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 11:00:38.610  6875  6875 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 11:00:38.623  6876  6876 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-05 11:00:38.637  6877  6877 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-05 11:00:38.650  6878  6878 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-05 11:00:38.675  6880  6880 I libmdmdetect: ESOC framework not supported
,08-05 11:00:38.678  6880  6880 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-05 11:00:38.690  6880  6880 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-05 11:00:38.691  6880  6880 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-05 11:00:38.691  6880  6880 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-05 11:00:38.691  6880  6880 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-05 11:00:38.691  6880  6880 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-05 11:00:38.691  6880  6880 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-05 11:00:38.691  6880  6880 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-05 11:00:38.745  6880  6884 E QC-QMI  : qmi_client [6880] 15: failed to locate client data
,08-05 11:00:38.749   486   486 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-05 11:00:38.749   486   486 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-05 11:00:38.779  6888  6888 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-05 11:00:38.795  6889  6889 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-05 11:00:38.851  6796  6823 I bt_vendor: bluetooth satus is on
08-05 11:00:38.851  6796  6823 D bt_hci_bdroid: preload
,08-05 11:00:38.857  6796  6863 D bt_userial_mct: userial_open(port:0)
08-05 11:00:38.857  6796  6863 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-05 11:00:38.863  6796  6863 I bt_vendor: Done intiailizing UART
08-05 11:00:38.868  6796  6863 I bt_vendor: Done intiailizing UART
08-05 11:00:38.868  6796  6863 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-05 11:00:38.868  6796  6863 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-05 11:00:38.871  6796  6861 I bt-btu  : btu_task received preload complete event
08-05 11:00:38.871  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-05 11:00:38.872  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-05 11:00:38.874  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-05 11:00:38.876  6796  6891 D bt_userial_mct: Entering userial_read_thread()
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_HCI
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 11:00:38.878  6796  6861 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 11:00:38.988  6796  6861 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-05 11:00:38.988  6796  6861 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01e4061 
08-05 11:00:38.988  6796  6861 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01e4061 
,08-05 11:00:39.017  6796  6827 E bt-btif : Calling BTA_HhEnable
08-05 11:00:39.017  6796  6827 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-05 11:00:39.017  6796  6827 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-05 11:00:39.019  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-05 11:00:39.020  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-05 11:00:39.020  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-05 11:00:39.020  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-05 11:00:39.020  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-05 11:00:39.021  1032  1032 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-05 11:00:39.022  1032  1032 D BluetoothManagerService: Stored Bluetooth name: G3
08-05 11:00:39.022  6796  6827 D BluetoothAdapterProperties: Name is: G3
08-05 11:00:39.024  6796  6827 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:00:39.024  6796  6827 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:00:39.025  6796  6827 D bt_hci_bdroid: postload
08-05 11:00:39.025  6796  6863 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:00:39.025  6796  6863 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:00:39.026  6796  6827 D bte_conf: Device ID record 1 : primary
08-05 11:00:39.026  6796  6827 D bte_conf:   vendorId            = 00c4
08-05 11:00:39.026  6796  6827 D bte_conf:   vendorIdSource      = 0001
08-05 11:00:39.026  6796  6827 D bte_conf:   product             = 13a1
08-05 11:00:39.026  6796  6827 D bte_conf:   version             = 1000
08-05 11:00:39.026  6796  6861 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-05 11:00:39.027  6796  6863 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:00:39.026  6796  6827 D bte_conf:   clientExecutableURL = 
08-05 11:00:39.027  6796  6827 D bte_conf:   serviceDescription  = 
08-05 11:00:39.027  6796  6827 D bte_conf:   documentationURL    = 
08-05 11:00:39.027  6796  6827 D bte_conf: bte_load_did_conf no section named DID2.
08-05 11:00:39.013  6893  6893 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 11:00:39.039  6796  6861 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:39.039  6796  6861 W bt-smp  : Plain text(LSB ~ MSB) = d8 ba 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:39.039  6796  6861 W bt-smp  : Encrypted text(LSB ~ MSB) = 8c 12 c7 19 74 c2 2e 01 0d d2 24 57 86 b5 d2 ea 
08-05 11:00:39.039  6796  6863 D bt_hci_bdroid: Used up Tx Cmd credits
08-05 11:00:39.039  6796  6861 W bt-btm  : Stopping oneshot timer
08-05 11:00:39.039  6796  6823 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 11:00:39.040  6796  6823 D BluetoothAdapterProperties: ScanMode =  20
08-05 11:00:39.040  6796  6823 D BluetoothAdapterProperties: State =  11
08-05 11:00:39.040  6796  6823 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-05 11:00:39.040  6796  6823 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-05 11:00:39.040  6796  6823 D BluetoothAdapterProperties: Setting state to 12
08-05 11:00:39.040  6796  6823 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 11:00:39.041  6796  6827 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-05 11:00:39.041  6796  6827 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-05 11:00:39.023  6893  6893 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:39.047  6796  6891 E bt_mct  : hci lib postload completed
,08-05 11:00:39.051  1032  1115 D BluetoothManagerService: Message: 60
08-05 11:00:39.051  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-05 11:00:39.051  1032  1115 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-05 11:00:39.074  6796  6823 I BluetoothAdapterState: Entering On State
,08-05 11:00:39.085  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:39.085  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:39.085  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:39.085  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:39.085  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:39.085  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:39.085  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:39.085  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:39.086  6796  6827 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:00:39.086  6796  6827 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-05 11:00:39.092  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:00:39.100  6796  6861 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:39.100  6796  6861 W bt-smp  : Plain text(LSB ~ MSB) = e8 af 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:39.100  6796  6861 W bt-smp  : Encrypted text(LSB ~ MSB) = a7 df b4 30 6c f7 9f fa 63 23 f8 68 7f 61 20 72 
08-05 11:00:39.100  6796  6861 W bt-btm  : Stopping oneshot timer
08-05 11:00:39.104  6796  6823 D LGBluetoothServiceAdapter: [BTUI] OnState
,08-05 11:00:39.107  6796  6823 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-05 11:00:39.107  6796  6823 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-05 11:00:39.109  6796  6823 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-05 11:00:39.143  6898  6898 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-05 11:00:39.148  6796  6823 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-05 11:00:39.148  6796  6861 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:39.148  6796  6861 W bt-smp  : Plain text(LSB ~ MSB) = b0 12 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:39.148  6796  6861 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 c6 50 52 6d ec 9d ec 55 89 7d 62 99 70 36 e8 
08-05 11:00:39.148  6796  6861 W bt-btm  : Stopping oneshot timer
08-05 11:00:39.151  6286  6302 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:00:39.155  1848  2735 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:00:39.159  1848  1848 D BluetoothHeadset: Proxy object connected
08-05 11:00:39.160  6796  6861 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:39.160  6796  6861 W bt-smp  : Plain text(LSB ~ MSB) = db dd 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:39.160  6796  6861 W bt-smp  : Encrypted text(LSB ~ MSB) = 92 88 09 c6 05 b7 c3 6c 5b da a5 47 85 c9 67 f1 
08-05 11:00:39.160  6796  6861 W bt-btm  : Stopping oneshot timer
08-05 11:00:39.161  6286  6303 D BluetoothPan: onBluetoothStateChange on: true
08-05 11:00:39.161  6286  6303 D BluetoothPan: onBluetoothStateChange call bindService
08-05 11:00:39.165  1032  1115 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:00:39.165  6286  6286 D BluetoothHeadset: Proxy object connected
08-05 11:00:39.165  6286  6286 D HeadsetProfile: Bluetooth service connected
08-05 11:00:39.166  1032  1032 D BluetoothHeadset: Proxy object connected
08-05 11:00:39.167  6286  6302 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 11:00:39.170  6796  6861 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-05 11:00:39.170  6796  6861 W bt-smp  : Plain text(LSB ~ MSB) = 5d 96 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-05 11:00:39.170  6796  6861 W bt-smp  : Encrypted text(LSB ~ MSB) = 47 5c 0b ca 59 ab 6d 3a fb 43 2e e5 21 c4 31 e3 
08-05 11:00:39.170  6796  6861 W bt-btm  : Stopping oneshot timer
,08-05 11:00:39.183  1848  1864 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:00:39.187  6286  6286 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 11:00:39.187  6286  6286 D PanProfile: Bluetooth service connected
,08-05 11:00:39.189  6286  6286 D BluetoothA2dp: Proxy object connected
08-05 11:00:39.189  6286  6286 D A2dpProfile: Bluetooth service connected
08-05 11:00:39.191  1848  1848 D BluetoothHeadset: Proxy object connected
08-05 11:00:39.191  6286  6438 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 11:00:39.194  6286  6303 D BluetoothMap: onBluetoothStateChange: up=true
08-05 11:00:39.195  1032  1115 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 11:00:39.197  6286  6286 D BluetoothInputDevice: Proxy object connected
08-05 11:00:39.197  6286  6286 D HidProfile: Bluetooth service connected
08-05 11:00:39.198  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:00:39.198  1032  1032 D BluetoothA2dp: Proxy object connected
,08-05 11:00:39.202  1848  1848 D BluetoothHeadset: Proxy object connected
08-05 11:00:39.202  6286  6302 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 11:00:39.203  6286  6286 D BluetoothMap: Proxy object connected
08-05 11:00:39.203  6286  6286 D MapProfile: Bluetooth service connected
08-05 11:00:39.203  6286  6286 D BluetoothMap: getConnectedDevices()
08-05 11:00:39.203  6796  6899 V BluetoothMapService: getConnectedDevices()
08-05 11:00:39.207  1032  1115 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-05 11:00:39.207  1032  1115 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-05 11:00:39.207  1032  1032 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-05 11:00:39.208  1032  1115 D BluetoothManagerService: Message: 40
08-05 11:00:39.208  1032  1115 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-05 11:00:39.210  1599  1599 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-05 11:00:39.211  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:39.212  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:39.212  1937  2131 D LGBluetoothAPIService: Message: 1
08-05 11:00:39.212  1937  2131 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-05 11:00:39.212  1937  2131 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-05 11:00:39.212  1937  2131 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-05 11:00:39.216  6796  6796 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:39.216  6796  6796 D BluetoothMapService: STATE_ON
08-05 11:00:39.217  6286  6286 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-05 11:00:39.219  6286  6286 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-05 11:00:39.226  6286  6286 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:00:39.229  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:39.229  6796  6796 V BluetoothPbapService: Pbap Service onCreate
08-05 11:00:39.229  6796  6796 V BluetoothPbapService: Starting PBAP service
08-05 11:00:39.230  6796  6796 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-05 11:00:39.230  6796  6796 V BluetoothPbapService: Pbap Service onBind
08-05 11:00:39.231  6796  6796 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:39.231  6796  6796 V BluetoothPbapService: state: 12
08-05 11:00:39.231  6286  6286 D BluetoothPbap: Proxy object connected
08-05 11:00:39.231  6286  6286 D PbapServerProfile: Bluetooth service connected
08-05 11:00:39.231  6796  6796 V BluetoothMapService: Handler(): got msg=1
08-05 11:00:39.232  6796  6796 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-05 11:00:39.232  6796  6796 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-05 11:00:39.232  6796  6796 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:39.232  6796  6796 V BluetoothPbapReceiver: ***********state = 12
08-05 11:00:39.234  6796  6796 V BluetoothPbapService: Handler(): got msg=1
08-05 11:00:39.236  2179  2179 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:00:39.236  6796  6796 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-05 11:00:39.236  2179  2179 D c       : Getting all permits...
08-05 11:00:39.236  6796  6916 D BluetoothMapMasInstance: MAS initSocket()
08-05 11:00:39.236  2179  2179 D a       : Opening database...
08-05 11:00:39.237  6796  6916 D BluetoothMapMasInstance:   masId = 00
08-05 11:00:39.237  6796  6916 D BluetoothMapMasInstance:   msgTypes = 0e
08-05 11:00:39.237  6796  6916 D BluetoothMapMasInstance:   masName = SMS/MMS
08-05 11:00:39.237  6796  6916 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-05 11:00:39.237  6796  6917 V BluetoothPbapService: Pbap Service initSocket
08-05 11:00:39.238  1032  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:39.238  1032  1882 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:39.240  2179  2179 D a       : Opening database auth.proximity.permit_store...
08-05 11:00:39.240  6796  6916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:39.240  6796  6917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:39.241  2179  2179 D a       : Closing database...
,08-05 11:00:39.243  6796  6916 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-05 11:00:39.244  6796  6916 V BluetoothMapMasInstance: Succeed to create listening socket 
08-05 11:00:39.244  6796  6916 D BluetoothMapMasInstance: Accepting socket connection...
08-05 11:00:39.245  6796  6917 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-05 11:00:39.245  6796  6917 V BluetoothPbapService: Succeed to create listening socket 
08-05 11:00:39.245  6796  6917 V BluetoothPbapService: Accepting socket connection...
08-05 11:00:39.246  6796  6827 D BluetoothAdapterProperties: Scan Mode:21
08-05 11:00:39.246  6796  6827 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-05 11:00:39.248  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:39.255  6286  6286 D BluetoothPermissionRequest: onReceive
,08-05 11:00:39.257  6286  6286 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-05 11:00:39.259  6286  6286 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-05 11:00:39.262  6796  6796 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-05 11:00:39.264  6796  6796 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-05 11:00:39.268  6796  6796 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-05 11:00:39.284  6796  6796 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-05 11:00:39.284  6796  6796 V BtOppService: onCreate
08-05 11:00:39.287  6796  6796 V BluetoothOppNotification: send message
08-05 11:00:39.290  6796  6796 V BtOppService: Starting RfcommListener
08-05 11:00:39.293  6796  6796 D BluetoothOppPreference: Dumping Names:  
08-05 11:00:39.293  6796  6796 D BluetoothOppPreference: {}
08-05 11:00:39.293  6796  6796 D BluetoothOppPreference: Dumping Channels:  
08-05 11:00:39.293  6796  6796 D BluetoothOppPreference: {}
08-05 11:00:39.294  6796  6796 V BtOppService: onStartCommand
08-05 11:00:39.295  6796  6925 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-05 11:00:39.302  6796  6796 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:39.303  6796  6796 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-05 11:00:39.303  6796  6922 V BtOppService: Deleted complete outbound shares, number =  0
08-05 11:00:39.303  6796  6925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:00:39.305  6796  6925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa5d297 on behalf of 
08-05 11:00:39.305  6796  6922 V BtOppService: Deleted complete inbound failed shares, number = 0
08-05 11:00:39.305  6796  6922 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-05 11:00:39.306  6796  6796 V BluetoothOppNotification: new notify threadi!
08-05 11:00:39.306  6796  6796 V BluetoothOppNotification: send delay message
08-05 11:00:39.307  6796  6925 V BluetoothOppNotification: update too frequent, put in queue
08-05 11:00:39.307  6796  6796 V BtOppService: start RfcommListener
08-05 11:00:39.307  6796  6922 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@368edc84 on behalf of 
08-05 11:00:39.309  6796  6926 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 11:00:39.309  6796  6796 V BtOppService: RfcommListener started
08-05 11:00:39.310  6796  6796 V BtOppService: ContentObserver received notification
08-05 11:00:39.310  6796  6796 V BtOppService: ContentObserver received notification
08-05 11:00:39.311  6796  6927 V BtOppRfcommListener: Starting RFCOMM listener....
08-05 11:00:39.311  1032  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:00:39.312  6796  6927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:39.313  6796  6927 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-05 11:00:39.314  6796  6927 V BtOppRfcommListener: Started RFCOMM listener....
08-05 11:00:39.314  6796  6927 I BtOppRfcommListener: Accept thread started.
08-05 11:00:39.314  6796  6927 V BtOppRfcommListener: Accepting connection...
08-05 11:00:39.317  6796  6925 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-05 11:00:39.317  6796  6925 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-05 11:00:39.317  6796  6926 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@141c4c6d on behalf of 
08-05 11:00:39.318  6796  6925 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@38a3f0a2 on behalf of 
08-05 11:00:39.318  6796  6926 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 11:00:39.319  6796  6925 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-05 11:00:39.319  6796  6926 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 11:00:39.321  6796  6926 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@106b0133 on behalf of 
08-05 11:00:39.322  6796  6926 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 11:00:39.322  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:39.322  6796  6796 V BluetoothFtpService: Ftp Service onCreate
08-05 11:00:39.322  6796  6796 I BluetoothFtpService: Ftp Service onCreate
,08-05 11:00:39.322  6796  6796 V BluetoothFtpService: Ftp Service onStartCommand
08-05 11:00:39.322  6796  6796 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:39.322  6796  6796 V BluetoothFtpService: Starting Listening on sockets
08-05 11:00:39.322  6796  6796 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-05 11:00:39.323  6796  6796 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-05 11:00:39.323  6796  6796 V BluetoothSapReceiver: SapReceiver onReceive 
08-05 11:00:39.323  6796  6796 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:00:39.323  6796  6796 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-05 11:00:39.323  6796  6796 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-05 11:00:39.324  6796  6926 V BluetoothOppNotification: outbound notification was removed.
08-05 11:00:39.324  6796  6926 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 11:00:39.325  6796  6796 V BluetoothFtpService: Handler(): got msg=1
08-05 11:00:39.326  6796  6926 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16be4269 on behalf of 
08-05 11:00:39.326  6796  6796 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-05 11:00:39.326  6796  6796 V BluetoothFtpService: Ftp Service initSocket
08-05 11:00:39.327  6796  6926 V BluetoothOppNotification: inbound: succ-0  fail-0
08-05 11:00:39.330  6796  6926 V BluetoothOppNotification: inbound notification was removed.
08-05 11:00:39.330  6796  6926 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 11:00:39.330  1032  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:39.331  6796  6796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:39.332  6796  6796 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-05 11:00:39.332  6796  6796 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-05 11:00:39.333  6796  6928 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-05 11:00:39.335  6796  6926 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d7474ee on behalf of 
08-05 11:00:39.348  6796  6796 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f5a53eb
08-05 11:00:39.348  6796  6796 V BluetoothSapService: Sap Service onCreate
,08-05 11:00:39.350  6796  6796 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:00:39.350  6796  6796 V BluetoothSapService: state: 12
08-05 11:00:39.351  6796  6796 V BluetoothSapService: Starting SAP server process
08-05 11:00:39.353  6796  6796 V BluetoothSapService: SAP Service startRfcommListenerThread
08-05 11:00:39.333  6930  6930 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:39.343  6930  6930 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:39.354  6796  6931 V BluetoothSapService: Sap Service initRfcommSocket
08-05 11:00:39.354  1032  1882 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:39.355  6796  6931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:00:39.356  6796  6931 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-05 11:00:39.356  6796  6931 V BluetoothSapService: Succeed to create listening socket 
08-05 11:00:39.356  6796  6931 V BluetoothSapService: Accepting socket connection...
08-05 11:00:39.364  6930  6930 V BT_SAP  : Event pipe created
08-05 11:00:39.364  6930  6930 V BT_SAP  : create_server_socket qcom.sap.server
08-05 11:00:39.364  6930  6930 V BT_SAP  : created socket fd 6
,08-05 11:00:39.929  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:39.929  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:39.929  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:39.929  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:00:39.929  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:39.929  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:39.929  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:39.929  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:00:39.941  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:39.945  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:39.945  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e4237ac added. We now have 8 listener(s)
08-05 11:00:39.945  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:39.953  1032  1918 D WifiServiceImplEx: setWifiEnabled: false pid=6201, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:00:39.954  1032  1918 D WifiService: setWifiEnabled: false pid=6201, uid=10118
08-05 11:00:39.954  1032  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:00:39.960  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:39.962  1032  1594 D WifiServiceImplEx: setWifiEnabled: true pid=6201, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-05 11:00:39.963  1032  1594 D WifiService: setWifiEnabled: true pid=6201, uid=10118
08-05 11:00:39.963  1032  1594 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:00:39.981  1032  1032 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-05 11:00:39.982  1032  1032 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-05 11:00:39.982  1032  1032 D Ulp_jni : JNI:system_update. Event-4
08-05 11:00:39.983  1032  1534 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-05 11:00:39.983  1032  1534 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-05 11:00:39.986  1032  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-05 11:00:39.986  1032  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 11:00:39.986  1032  1534 E WifiUtil: wfc_util_ffile_check_copy(): pid[1032] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-05 11:00:39.986  1032  1534 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-05 11:00:39.986  1032  1534 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-05 11:00:39.986  1032  1534 E WifiHW  : unknown target_country: EU , set to default
08-05 11:00:39.986  1032  1534 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-05 11:00:39.986  1032  1534 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-05 11:00:39.987  1032  1534 I WifiUtil: gEnableBmps=1
08-05 11:00:40.308  6796  6796 V BluetoothOppNotification: new notify threadi!
08-05 11:00:40.309  6796  6796 V BluetoothOppNotification: send delay message
,08-05 11:00:40.326  6796  6944 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-05 11:00:40.333  6796  6944 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22b6f1fa on behalf of 
,08-05 11:00:40.336  6796  6944 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-05 11:00:40.337  6796  6944 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-05 11:00:40.339  6796  6944 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26fb63ab on behalf of 
08-05 11:00:40.339  6796  6944 V BluetoothOppNotification: outbound: succ-0  fail-0
08-05 11:00:40.341  6796  6944 V BluetoothOppNotification: outbound notification was removed.
08-05 11:00:40.341  6796  6944 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-05 11:00:40.342  6796  6944 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32a9ba08 on behalf of 
08-05 11:00:40.343  6796  6944 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-05 11:00:40.379  6796  6944 V BluetoothOppNotification: inbound notification was removed.
08-05 11:00:40.379  6796  6944 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-05 11:00:40.381  6796  6944 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3322d5a1 on behalf of 
08-05 11:00:40.551   318   890 D SoftapController: Softap fwReload - Ok
,08-05 11:00:40.561  1032  1534 E NetdConnector: NDC Command {54 softap fwreload wlan0 STA} took too long (571ms)
08-05 11:00:40.564   318   890 D CommandListener: Setting iface cfg
08-05 11:00:40.564   318   890 D CommandListener: Trying to bring down wlan0
08-05 11:00:40.571   318   890 D CommandListener: Clearing all IP addresses on wlan0
,08-05 11:00:40.594  1032  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 11:00:40.594  1032  1115 D Tethering: InitialState.processMessage what=4
08-05 11:00:40.595  1032  1115 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 11:00:40.598   318  6952 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-05 11:00:40.607  1032  1534 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-05 11:00:40.609  1032  1113 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-05 11:00:40.603  6953  6953 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 11:00:40.613  6953  6953 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:40.626  1032  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:00:40.626  1032  1534 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:00:40.626  1032  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-05 11:00:40.654  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:40.658  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-05 11:00:40.664  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:40.664  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-05 11:00:40.665  1032  1534 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-05 11:00:40.665  1032  1534 D WifiMonitor: connecting to supplicant
08-05 11:00:40.690  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:00:40.691  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:00:40.691  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:00:40.691  6286  6286 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:00:40.693  6953  6953 I wpa_supplicant: Successfully initialized wpa_supplicant
08-05 11:00:40.695  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-05 11:00:40.699  6286  6286 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:00:40.699  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:00:40.699  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:00:40.699  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:00:40.699  6286  6286 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:00:40.700  6286  6286 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:00:40.705  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:00:40.705  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:00:40.705  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:00:40.705  6286  6286 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:00:40.706  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-05 11:00:40.707  6286  6286 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-05 11:00:40.707  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-05 11:00:40.707  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:00:40.708  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:00:40.708  6286  6286 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:00:40.708  6286  6286 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:00:40.715  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:40.721  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-05 11:00:40.725  6400  6973 W FormManager: Network not available. Please check & try again.
08-05 11:00:40.726  6953  6953 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-05 11:00:40.726  6953  6953 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-05 11:00:40.727  6400  6974 V FormManager: Network unavailable.
08-05 11:00:40.730  6400  6974 V FormManager: Network unavailable.
08-05 11:00:40.731  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:40.780  6953  6953 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 11:00:40.826  6953  6953 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-05 11:00:40.834  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-05 11:00:40.835  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-05 11:00:40.836  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-05 11:00:40.838  1032  1534 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-05 11:00:40.839  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-05 11:00:40.840  1032  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:40.841  1032  1534 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:40.842  1032  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:40.843  1032  1534 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-05 11:00:40.844  1032  1534 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-05 11:00:40.844  1032  1534 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-05 11:00:40.845  1032  1534 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-05 11:00:40.845  1032  1534 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-05 11:00:40.845  1032  1534 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-05 11:00:40.845  1032  1534 E WifiStateMachine: useWiFiOffloading() : false
08-05 11:00:40.845  1032  1534 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true,
08-05 11:00:40.845  1032  1534 D WifiNative-wlan0: doBoolean: SET update_config 1
08-05 11:00:40.846  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:00:40.846  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:40.846  6953  6953 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-05 11:00:40.846  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 11:00:40.846  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 11:00:40.847  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-05 11:00:40.847  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-05 11:00:40.847  1032  6975 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:00:40.847  1032  6975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-05 11:00:40.847  1032  1534 D WifiNative-wlan0: SET update_config 1: returned true
08-05 11:00:40.847  1032  1534 D WifiConfigStore: Loading config and enabling all networks 
08-05 11:00:40.847  1032  1534 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-05 11:00:40.847  1032  1534 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-05 11:00:40.848  1937  1937 D WfdService: Waiting for WifiP2p enabling
08-05 11:00:40.850  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:40.852  1032  1534 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-05 11:00:40.853  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:40.854  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:40.854  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-05 11:00:40.861  1032  1534 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-05 11:00:40.861  1032  1534 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 11:00:40.862  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:40.862  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:40.862  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:40.862  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:40.862  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:40.862  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:40.862  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:40.862  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:00:40.865  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:40.865  1032  1032 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-05 11:00:40.865  1032  1538 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-05 11:00:40.866  1032  1534 D WifiStateMachine: enableVerboseLogging : level 2
08-05 11:00:40.866  1032  1534 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-05 11:00:40.866  1032  1534 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-05 11:00:40.866  1032  1534 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-05 11:00:40.867  1032  1534 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-05 11:00:40.867  1032  1534 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-05 11:00:40.867  1032  1534 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-05 11:00:40.867  1032  1534 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-05 11:00:40.867  1032  1534 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-05 11:00:40.868  1032  1534 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
,08-05 11:00:40.868  1032  1534 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-05 11:00:40.868  1032  1534 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-05 11:00:40.868  1032  1534 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,08-05 11:00:40.868  1032  1534 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-05 11:00:40.869  1032  1534 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-05 11:00:40.871  1032  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 11:00:40.871  1032  1534 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-05 11:00:40.871  1032  1534 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-05 11:00:40.871  1032  1534 D WifiNative-HAL: Setting external_sim to 1
08-05 11:00:40.871  1032  1534 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-05 11:00:40.872  1032  1534 D WifiNative-wlan0: SET external_sim 1: returned true
08-05 11:00:40.872  1032  1534 I WifiNative-HAL: startHal
08-05 11:00:40.872  1032  1534 D wifi    : setting scan oui 0xaf59bf80
08-05 11:00:40.872  1937  1937 D WfdsService: Supplicant Connection state is changed : true
08-05 11:00:40.873  1032  1534 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 11:00:40.873  1937  2292 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-05 11:00:40.873  1032  1534 I WifiNative-HAL: startHal
08-05 11:00:40.873  1937  2292 D WfdsService: Set the WFDS Monitor: true
08-05 11:00:40.873  1937  2292 D WfdsMonitor: WfdsMonitorThread create
08-05 11:00:40.873  1032  1534 D wifi    : setting scan oui 0xaf59bf80
08-05 11:00:40.873  1937  2292 D WfdsMonitor: WFDS Monitor is created and started
08-05 11:00:40.873  1937  2292 D WfdsService: WiFi: Supplicant connection re-established
08-05 11:00:40.873  1032  1534 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-05 11:00:40.874  1032  1534 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-05 11:00:40.874  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-05 11:00:40.874  1937  6976 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-05 11:00:40.874  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-05 11:00:40.874  1032  1534 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-05 11:00:40.874  1937  6976 E CtrlSupplicant: Succeed to open control connection
08-05 11:00:40.874  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 11:00:40.875  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 11:00:40.875  1937  6976 E CtrlSupplicant: Succeed to open monitor connection
08-05 11:00:40.875  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 11:00:40.875  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-05 11:00:40.875  1937  6976 D WfdsMonitor: Supplicant connection established
08-05 11:00:40.875  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-05 11:00:40.875  1937  2292 D WfdsService: Connected to the supplicant for wfds
08-05 11:00:40.875  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-05 11:00:40.875  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 11:00:40.876  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 11:00:40.876  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:40.876  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 11:00:40.876  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-05 11:00:40.876  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-05 11:00:40.876  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-05 11:00:40.876  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-05 11:00:40.877  6953  6953 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-05 11:00:40.877  1032  1534 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-05 11:00:40.877  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-05 11:00:40.877  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-05 11:00:40.878  10,32  1534 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-05 11:00:40.879  1032  1534 E WifiNative: : [380,789,164 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-05 11:00:40.879  1032  1534 D WifiNative-wlan0: doBoolean: RECONNECT
08-05 11:00:40.879  1032  1534 D WifiNative-wlan0: RECONNECT: returned true
08-05 11:00:40.879  1032  1534 D WifiNative-wlan0: doString: [STATUS]
08-05 11:00:40.880  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-05 11:00:40.880  1032  1534 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 11:00:40.880  1032  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:00:40.880  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-05 11:00:40.880  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-05 11:00:40.881  1032  1534 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:00:40.881  1032  1532 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.882  1032  1032 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 11:00:40.882  1032  1032 D RttService: SCAN_AVAILABLE : 3
08-05 11:00:40.883  1032  1553 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:00:40.883  1032  1552 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.883  1032  1552 I WifiNative-HAL: startHal
08-05 11:00:40.883  1032  1552 D wifi    : getting scan capabilities on interface[1] = 0xaf59bf80
08-05 11:00:40.884  1032  1552 D wifi    : failed to get capabilities : -3
08-05 11:00:40.884  1032  1552 E WifiScanningService: could not get scan capabilities
08-05 11:00:40.884  1032  1534 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-05 11:00:40.884  1032  1534 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-05 11:00:40.884  1032  1534 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-05 11:00:40.884   318   890 D CommandListener: Setting iface cfg
08-05 11:00:40.885  1032  1534 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-05 11:00:40.885   318   890 D CommandListener: Trying to bring up p2p0
08-05 11:00:40.885  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=380796  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:00:40.886  1032  1532 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 11:00:40.887  1032  1532 D LGWifiP2pService: P2pEnablingState
08-05 11:00:40.887  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=380798  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:00:40.887  1032  1532 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.887  1032  1532 D LGWifiP2pService: P2p socket connection successful
08-05 11:00:40.887  1032  1532 D LGWifiP2pService: P2pEnabledState
08-05 11:00:40.887  1032  1534 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-05 11:00:40.888  1032  1534 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-05 11:00:40.888  1032  1532 D LGWifiP2pService: sending p2p connection changed broadcast
08-05 11:00:40.888  1032  1534 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-05 11:00:40.888  1032  1534 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-05 11:00:40.888  6953  6953 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-05 11:00:40.888  1032  1532 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-05 11:00:40.889  1032  1534 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-05 11:00:40.889  1032  1532 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-05 11:00:40.889  1032  1532 D WifiNative-p2p0: doBoolean: SET device_name G3
08-05 11:00:40.889  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:40.889  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:40.890  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:40.891  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:40.891  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 11:00:40.891  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:40.891  1032  1532 D WifiNative-p2p0: SET device_name G3: returned true
08-05 11:00:40.891  1032  1532 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-05 11:00:40.891  1032  1532 D LGWifiP2pService: before postfix = G3
08-05 11:00:40.891  1032  1532 D WifiServerServiceExt: postfix byte check : 2
08-05 11:00:40.891  1032  1532 D LGWifiP2pService: after postfix = G3
08-05 11:00:40.891  1032  1532 D WifiNative-p2p0,: doBoolean: SET p2p_ssid_postfix -G3
08-05 11:00:40.892  1032  1532 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-05 11:00:40.892  1032  1532 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-05 11:00:40.892  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-05 11:00:40.892  1937  1937 D WfdsService: WifiP2pState is changed : true
08-05 11:00:40.893  1937  2292 D WfdsService: Receive the WFDS_ENABLE Method
08-05 11:00:40.893  1032  1532 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-05 11:00:40.893  1937  2292 D WfdsService: Set the WFDS Monitor: true
08-05 11:00:40.893  1032  1532 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-05 11:00:40.893  1937  2292 D WfdsService: Connected to the supplicant for wfds
08-05 11:00:40.893  1032  1534 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-05 11:00:40.893  1937  2292 D WfdsJNI : doCommand: WFDS_SET TRUE
08-05 11:00:40.893  1937  1937 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-05 11:00:40.894  6953  6953 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-05 11:00:40.894  1937  2292 D WfdsService: selectPreferredScanChannel [36]
08-05 11:00:40.894  1937  2292 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-05 11:00:40.894  1937  1937 D WfdsService: isConnected: false
08-05 11:00:40.894  1032  1532 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-05 11:00:40.894  1032  1532 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-05 11:00:40.895  1032  1532 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-05 11:00:40.895  1032  1532 D WifiNative-HAL: p2pGetDeviceAddress
08-05 11:00:40.895  1032  1534 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-05 11:00:40.895  1032  1534 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-05 11:00:40.895  6953  6953 E wpa_supplicant: disconnect_rssi_lvl: -100
08-05 11:00:40.895  1032  1532 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-05 11:00:40.896  1032  1532 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-05 11:00:40.896  1032  1532 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-05 11:00:40.896  1032  1534 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 11:00:40.897  1032  1534 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 11:00:40.897  1032  1534 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-05 11:00:40.897  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-05 11:00:40.897  1937  1937 I WfdStateTracker: handleP2pThisDeviceChanged
08-05 11:00:40.897  1937  1937 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,08-05 11:00:40.897  1937  1937 D WfdsService: Update P2p Interface State: 3
08-05 11:00:40.898  1032  1532 D WifiNative-p2p0: P2P_FLUSH: returned true
08-05 11:00:40.898  1032  1532 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-05 11:00:40.898  1032  1532 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-05 11:00:40.898  1032  1532 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-05 11:00:40.898  1032  1532 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-05 11:00:40.898  1032  1532 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-05 11:00:40.899  6400  6978 W FormManager: Network not available. Please check & try again.
08-05 11:00:40.904  1032  1532 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-05 11:00:40.904  1032  1532 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-05 11:00:40.904  1032  1532 D LGWifiP2pService: InactiveState
08-05 11:00:40.904  1032  1532 D LGWifiP2pService: InactiveState{ when=-6ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.904  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.904  1032  1532 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-05 11:00:40.905  6400  6979 V FormManager: Network unavailable.
08-05 11:00:40.905  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 11:00:40.905  6953  6953 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:40.905  1032  6975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:00:40.905  1032  6975 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:40.905  1032  6975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:40.905  1032  6975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:40.906  1937  6976 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:00:40.906  6953  6953 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 11:00:40.906  6953  6953 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.906  1937  6976 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:40.906  1032  6975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:40.906  1032  6975 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.906  1032  6975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.906  1032  6975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.906  1032  1532 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-05 11:00:40.906  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:40.906  1032  1532 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.906  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.906  6953  6953 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.906  1032  1532 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 11:00:40.907  1032  1532 D LGWifiP2pService: InactiveState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1532 D LGWifiP2pService: DefaultState{ when=-2ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1532 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1532 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1532 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1532 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.907  1032  1032 E WifiServerServiceExt: No p2p device connected
08-05 11:00:40.907  1937  2292 W WfdsService: DefaultState - msg [9441285] is not handled
08-05 11:00:40.908  1937  6976 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:40.908  1032  6975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:40.908  1032  6975 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.908  1032  6975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.908  1032  6975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.908  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-05 11:00:40.909  6953  6953 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:40.909  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-05 11:00:40.909  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:40.909  1032  6975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:40.909  1032  6975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-05 11:00:40.910  6953  6953 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-05 11:00:40.910  6953  6953 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.910  1032  1534 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-05 11:00:40.910  6953  6953 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.911  1032  1534 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:00:40.911  1032  1534 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:00:40.911  1032  1534 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-05 11:00:40.911  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-05 11:00:40.911  1032  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.911  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:40.911  1937  6976 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:40.911  1937  6976 D WfdsMonitor: Event [CT,RL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:40.911  1032  6975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:40.911  1032  6975 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.912  1032  6975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.912  1032  6975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.912  1032  6975 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-05 11:00:40.912  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-05 11:00:40.912  1032  6975 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.912  6953  6953 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:00:40.912  1032  6975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.912  1032  6975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-05 11:00:40.912  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-05 11:00:40.912  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:00:40.912  1032  6975 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:00:40.912  1032  6975 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-05 11:00:40.913  1032  1534 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-05 11:00:40.913  1032  1534 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-05 11:00:40.913  1032  1534 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-05 11:00:40.913  1032  1534 D WifiNative-wlan0: doBoolean: SCAN
08-05 11:00:40.914  1032  1534 D WifiNative-wlan0: SCAN: returned false
08-05 11:00:40.914  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=380825  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-05 11:00:40.919  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:40.919  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:40.919  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-05 11:00:40.919  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:40.919  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:40.920  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=380831  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-05 11:00:40.921  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:40.921  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:40.921  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
08-05 11:00:40.922  1032  1534 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:40.923  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:00:40.923  1032  1534 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:40.923  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:00:40.923  6400  6979 V FormManager: Network unavailable.
08-05 11:00:40.924  1032  1534 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:40.924  1032  1534 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:40.924  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:40.925  1032  1534 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-05 11:00:40.927  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:40.927  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:40.927  1032  1032 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-05 11:00:40.932  4238  6980 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:00:40.932  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:40.937  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:40.937  4238  6981 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-05 11:00:40.937  4238  6981 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-05 11:00:40.942  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:40.947  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:40.947  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:40.948  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:00:40.951  6051  6051 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 11:00:40.951  6051  6051 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-05 11:00:40.951  6051  6051 V [BNRBootReceiver]: Boot Receiver Return
,08-05 11:00:40.954  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:40.960  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:40.965  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:40.970  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:40.971  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:40.972  6356  6356 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-05 11:00:40.998  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:40.998  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:40.998  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:40.998  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:40.998  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:40.998  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:00:40.998  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:00:40.998  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:00:41.001  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:00:41.013  6201  6264 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-05 11:00:41.014  6201  6264 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-05 11:00:41.016  6201  6264 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@20833ade Bundle[{}]
,08-05 11:00:41.018  6201  6264 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 11:00:41.018  6201  6264 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-05 11:00:41.019  6201  6264 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-05 11:00:41.020  6201  6264 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-05 11:00:41.021  6201  6264 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-05 11:00:41.021  6201  6264 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-05 11:00:41.028  6201  6264 I System.out: Running OutgoingSocketThread
08-05 11:00:41.031  6201  6982 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 790)
08-05 11:00:41.034  6201  6982 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50510
08-05 11:00:41.035  6201  6982 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-05 11:00:41.529  6953  6953 E wpa_supplicant: USIM:  scard_init function
08-05 11:00:41.530  6953  6953 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-05 11:00:41.539  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-05 11:00:41.539  1032  6975 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-05 11:00:41.540  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-05 11:00:41.540  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
08-05 11:00:41.540  1032  6975 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-05 11:00:41.540  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-05 11:00:41.540  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-05 11:00:41.541  1032  1534 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-05 11:00:41.542  1032  1534 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-05 11:00:41.542  1032  1534 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-05 11:00:41.543  1032  1534 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-05 11:00:41.545  1032  1534 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-05 11:00:41.561  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=381472  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-05 11:00:41.568  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=381479  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-05 11:00:41.571  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.572  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.572  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 11:00:41.572  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:41.572  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:41.576  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:41.581  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:41.581  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-05 11:00:41.586  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-05 11:00:41.594  6286  6286 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-05 11:00:41.602  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:00:41.615  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:41.622  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:41.630  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:41.630  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:41.631  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 11:00:41.659  6953  6953 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 11:00:41.670  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-05 11:00:41.670  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-05 11:00:41.670  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-05 11:00:41.670  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-05 11:00:41.671  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:41.671  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:41.675  6953  6953 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:00:41.675  6953  6953 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-05 11:00:41.681  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=381592  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 11:00:41.683  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=381593  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-05 11:00:41.684  1032  1534 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=381594
08-05 11:00:41.684  1032  1534 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=381595
08-05 11:00:41.685  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:41.686  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:41.686  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-05 11:00:41.686  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:00:41.686  1032  6975 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 11:00:41.686  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-05 11:00:41.686  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 11:00:41.686  1032  6975 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-05 11:00:41.686  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:41.686  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:41.688  1032  1534 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=381599
08-05 11:00:41.688  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=381599
08-05 11:00:41.694  1032  1115 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 11:00:41.705  1032  1534 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=381600
08-05 11:00:41.705  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=381616  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 11:00:41.710  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.710  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.710  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-05 11:00:41.712  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:41.712  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:41.716  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.725  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.725  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.725  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-05 11:00:41.727  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=381638  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-05 11:00:41.729  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:41.729  1032  1032 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-05 11:00:41.731  1032  1534 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=381641  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 11:00:41.732  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=381642  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-05 11:00:41.732  1032  1534 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=381643
08-05 11:00:41.733  1032  1534 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=381643
08-05 11:00:41.737  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:41.737  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 11:00:41.739  1032  1534 D WifiNative-wlan0: doString: [STATUS]
08-05 11:00:41.740  1032  6975 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-05 11:00:41.741  1032  6975 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-05 11:00:41.742  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.743  1032  1534 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-05 11:00:41.745  1032  1534 I WifiServiceExtension: setVHTCapabilityType  : false
08-05 11:00:41.748  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-05 11:00:41.748  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-05 11:00:41.748  6286  6286 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-05 11:00:41.748  6286  6286 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-05 11:00:41.750  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-05 11:00:41.755  1032  1534 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-05 11:00:41.755  1032  1534 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-05 11:00:41.760  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.760  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.760  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-05 11:00:41.768  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:41.768  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-05 11:00:41.782  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.782  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.782  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-05 11:00:41.783  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.785  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:41.785  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:41.786  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.789  1032  1534 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-05 11:00:41.789  1032  1540 D ConnectivityService: Got NetworkAgent Messenger
08-05 11:00:41.789  1032  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 11:00:41.789  1032  1540 D ConnectivityService: NetworkAgent connected
08-05 11:00:41.790  1032  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:00:41.790  1032  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-05 11:00:41.793  1032  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:00:41.793  1032  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 11:00:41.795  6286  6286 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-05 11:00:41.795  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-05 11:00:41.795  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-05 11:00:41.795  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-05 11:00:41.795  6286  6286 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-05 11:00:41.796  6286  6286 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-05 11:00:41.796  6286  6286 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-05 11:00:41.799  1032  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-05 11:00:41.799  1032  1534 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:00:41.799  1032  1534 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-05 11:00:41.800  1032  1534 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-05 11:00:41.800  1032  1534 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-05 11:00:41.802  1032  1534 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-05 11:00:41.816   318   890 D CommandListener: Setting iface cfg
,08-05 11:00:41.831  1032  1534 E WifiStateMachine: Start Dhcp Watchdog 2
,08-05 11:00:41.832  1032  1534 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=381743  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-05 11:00:41.839  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:41.840  1032  6993 D DhcpStateMachine: StoppedState
08-05 11:00:41.840  1032  6993 D DhcpStateMachine: StoppedState{ when=-9ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:41.840  1032  6993 D DhcpStateMachine: WaitBeforeStartState
08-05 11:00:41.842  1032  1534 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=381752  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:41.843  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=381753  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:41.844  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:41.845  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:41.847  1032  1534 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:41.848  1032  1534 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:41.849  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-05 11:00:41.850  1032  1534 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-05 11:00:41.854  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:41.856  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:41.856  1032  1032 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-05 11:00:41.857  1032  1534 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=381767  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:41.857  1032  1534 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=381768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:41.858  1032  1534 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=381768  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-05 11:00:41.859  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14230] from screen [on:0 period:1508826627] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 11:00:41.860  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1508826628] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 11:00:41.860  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 11:00:41.860  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:41.860  1032  1032 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-05 11:00:41.863  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:41.865  1032  1540 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-05 11:00:41.866  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.866  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:41.866  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.866  1032  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.867  1032  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.867  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.868  1032  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.868  1032  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 11:00:41.869  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=4,0,0
08-05 11:00:41.869  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=4,0,0
08-05 11:00:41.869  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-05 11:00:41.870  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-05 11:00:41.870  1032  1534 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-05 11:00:41.870  1032  1534 D WifiNative-wlan0: doBoolean: SET ps 0
08-05 11:00:41.870  1032  1534 D WifiNative-wlan0: SET ps 0: returned true
08-05 11:00:41.870  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-05 11:00:41.871  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-05 11:00:41.871  1032  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-05 11:00:41.871  1032  1534 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-05 11:00:41.871  1032  1534 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 11:00:41.871  1032  1532 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d29ee8a target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:41.871  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d29ee8a target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:41.871  1032  1534 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 11:00:41.872  1032  6993 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:41.872  1032  6993 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-05 11:00:41.872   318   890 D CommandListener: Setting iface cfg
08-05 11:00:41.873   318   890 D CommandListener: Trying to bring up wlan0
08-05 11:00:41.874  1032  1534 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-05 11:00:41.876  1032  1032 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-05 11:00:41.876  1032  1032 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-05 11:00:41.877  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.877  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.877  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:41.877  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:41.877  1032  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.878  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:00:41.878  1032  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.878  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.878  1032  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-05 11:00:41.879  1032  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 11:00:41.880  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 11:00:41.880  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-05 11:00:41.880  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-05 11:00:41.880  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-05 11:00:41.881  1032  1534 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-05 11:00:41.881  1032  1534 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-05 11:00:41.881  6953  6953 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-05 11:00:41.882  1032  1534 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-05 11:00:41.882  1032  1534 D WifiNative-wlan0: doBoolean: SET ps 1
08-05 11:00:41.882  1032  1532 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:41.882  1032  1532 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:41.883  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:41.889  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:41.894  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:41.897  1032  1534 D WifiNative-wlan0: SET ps 1: returned true
08-05 11:00:41.897  1032  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-05 11:00:41.898  1032  1534 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 11:00:41.898  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-05 11:00:41.898  1032  1534 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 11:00:41.898  1032  1540 D ConnectivityService: ignoring duplicate network state non-change
08-05 11:00:41.900  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:41.900  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:41.900  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 11:00:41.904  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.904  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:41.904  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:41.904  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.904  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 11:00:41.905  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.907  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:41.911  1032  1540 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-05 11:00:41.912  1032  1540 D ConnectivityService: Adding iface wlan0 to network 101
08-05 11:00:41.916  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.916  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.916  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-05 11:00:41.919  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:41.920  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-05 11:00:41.921  1937  1937 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-05 11:00:41.922  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.922  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.922  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 11:00:41.923  1032  1534 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-05 11:00:41.924  1032  1032 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-05 11:00:41.928  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:41.928  1599  1599 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-05 11:00:41.929  1032  1032 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.929  1032  1032 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:00:41.929  1032  1032 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-05 11:00:41.929  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.929  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-05 11:00:41.932  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 11:00:41.935  1032  1540 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 11:00:41.935  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:41.936  1032  1540 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-05 11:00:41.936  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:41.936  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:00:41.937  1032  1540 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-05 11:00:41.938   318   890 E Netd    : netlink response contains error (File exists)
08-05 11:00:41.938  1032  1540 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-05 11:00:41.938  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:41.939  1032  1540 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-05 11:00:41.939  1032  1540 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-05 11:00:41.939  1032  1540 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-05 11:00:41.939  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 11:00:41.940  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.941  1032  1540 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 11:00:41.941  1032  1540 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 11:00:41.941  1032  1540 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-05 11:00:41.941  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:41.941  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-05 11:00:41.941  1032  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 11:00:41.941  1032  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:00:41.941  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:41.941  1032  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:41.942  1032  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 11:00:41.942  1032  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:41.942  1032  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-05 11:00:41.942  1032  1540 D ConnectivityService: currentScore = 0, newScore = 20
08-05 11:00:41.942  1032  1540 D ConnectivityService:    accepting network in place of null
08-05 11:00:41.942  1032  1540 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:41.943  1032  1534 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:41.943  1032  1534 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-05 11:00:41.945  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 11:00:41.945  1032  1540 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-05 11:00:41.948  1848  1848 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:41.948  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 11:00:41.949   318  7015 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-05 11:00:41.951  1599  1599 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:41.951  1599  1599 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-05 11:00:41.951  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.952  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:41.954  1032  1540 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-05 11:00:41.954  1032  1540 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-05 11:00:41.954  1032  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 11:00:41.955  1032  1540 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:00:41.955  1032  1540 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
,08-05 11:00:41.955  1032  1032 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-05 11:00:41.955  1032  1540 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-05 11:00:41.955  1032  1032 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-05 11:00:41.956  1032  1032 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-05 11:00:41.956  1032  1032 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-05 11:00:41.956  1032  1032 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-05 11:00:41.957  1032  1540 D ConnectivityService: validation of new default Network = false
08-05 11:00:41.957  1032  1540 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-05 11:00:41.957  1032  1540 D DSQN    : enableDataServiceNotify 
08-05 11:00:41.958  1032  1540 D DSQN    : start dsqn bin
08-05 11:00:41.959   318  7016 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 11:00:41.959   318  7016 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-05 11:00:41.961  1032  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 11:00:41.961   318  7018 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 11:00:41.961  1032  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:41.961  1032  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:41.962   318  7018 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-05 11:00:41.962  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:41.962  1032  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:41.962  1599  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 11:00:41.953  7019  7019 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:41.953  7019  7019 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:41.971  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:41.972  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:41.972  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 11:00:41.980  7019  7019 E DSQN    : DSQN ssw
08-05 11:00:41.983  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-05 11:00:41.993  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 11:00:41.994  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.994  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:41.995  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:41.999  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:41.999   318  7015 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 11:00:42.001   318  7016 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-05 11:00:42.005  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:42.005  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:42.007  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-05 11:00:42.010  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:42.015  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-05 11:00:42.019   318  7018 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
08-05 11:00:42.020  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:42.025  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:42.025  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:42.026  6356  6356 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-05 11:00:42.028  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:42.029  6201  6264 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 791)
08-05 11:00:42.029  6201  6264 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 791)
,08-05 11:00:42.031   318  7015 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-05 11:00:42.032  6201  6264 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 796)
08-05 11:00:42.033  6201  6264 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-05 11:00:42.033  6201  6264 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 797)
08-05 11:00:42.035  6304  6304 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 11:00:42.036  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:00:42.036  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a304c75 added. We now have 2 listener(s)
08-05 11:00:42.036  1032  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.038  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.038  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.038  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.038  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.038  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@355a640a added. We now have 9 listener(s)
08-05 11:00:42.038  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.042  1032  1531 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-05 11:00:42.043  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:00:42.046  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:42.050  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-05 11:00:42.051  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:42.051  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:42.051  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:42.051  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:42.051  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:42.051  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.051  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:00:42.051  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:00:42.053  1032  7017 D LocSvc_java: NTP server : europe.pool.ntp.org
08-05 11:00:42.053  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.053  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:42.053  1032  7017 D LocSvc_java: NTP server returned: 1470387641651 (Fri Aug 05 11:00:41 GMT+02:00 2016) reference: 381963 certainty: 16 system time offset: -402
08-05 11:00:42.053  1032  7017 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-05 11:00:42.053  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:00:42.053  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38712298 added. We now have 3 listener(s)
,08-05 11:00:42.055  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:42.056  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:42.057  1032  1882 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.060  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:42.061  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.061  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.061  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.061  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.061  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a463af1 added. We now have 10 listener(s)
08-05 11:00:42.062  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.062  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:42.062  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:42.062  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:42.062  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.062  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.062  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:42.062  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.062  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a304c75 removed from the list
08-05 11:00:42.063  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.063  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@355a640a removed from the list
08-05 11:00:42.063  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:42.063  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.066  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:00:42.067  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.070  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.070  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.070  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.070  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@355a640a not in the list
08-05 11:00:42.070  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.070  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.071  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.071  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.071  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.071  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a463af1 removed from the list
08-05 11:00:42.071  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.071  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.071  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.072  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-05 11:00:42.072  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38712298 removed from the list,
08-05 11:00:42.072  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:00:42.072  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d42b6d6 added. We now have 2 listener(s)
08-05 11:00:42.074  1032  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.075  1032  6993 D DhcpStateMachine: DHCPV4 request on wlan0
08-05 11:00:42.075  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:42.075  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-05 11:00:42.076  1032  6993 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-05 11:00:42.076  1032  6993 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-05 11:00:42.076  6356  6356 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 11:00:42.077  6356  6356 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 11:00:42.077  6356  6356 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 11:00:42.079   318   889 D LGDataListener: argv[0]=dsqncommand
08-05 11:00:42.079   318   889 D LGDataListener: argv[1]=wlan0
08-05 11:00:42.079   318   889 D LGDataListener: argv[2]=1
,08-05 11:00:42.079   318   889 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-05 11:00:42.079  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.079  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.079  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.079  1032  1113 D DSQN    : DSQM DsqnNotification wlan0  1
08-05 11:00:42.079  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.079  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a13d57 added. We now have 9 listener(s)
08-05 11:00:42.079  1032  1113 D DSQN    : start to monitor internet connection,
08-05 11:00:42.079  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.080  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:00:42.063  7024  7024 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-05 11:00:42.063  7024  7024 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-05 11:00:42.088  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:42.089  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-05 11:00:42.092  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:42.092  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:42.092  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:42.092  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:42.092  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:42.092  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.092  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:00:42.092  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:00:42.094  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.094  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:42.095  6304  6304 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-05 11:00:42.096  6304  6304 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-05 11:00:42.096  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:00:42.096  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bf2952d added. We now have 3 listener(s)
08-05 11:00:42.096  1032  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.098  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:00:42.099  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.099  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.099  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.099  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.099  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8b6a62 added. We now have 10 listener(s)
08-05 11:00:42.100  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.100  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:00:42.100  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:00:42.100  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:00:42.100  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:42.100  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:00:42.100  6286  6286 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-05 11:00:42.102  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:00:42.102  1032  1973 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.102  7024  7024 I dhcpcd  : version 5.5.6 starting
08-05 11:00:42.105  6286  6286 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-05 11:00:42.109  7024  7024 E dhcpcd  : get_duid: m
08-05 11:00:42.109  7024  7024 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-05 11:00:42.109  7024  7024 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-05 11:00:42.111  6356  6356 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-05 11:00:42.111  6356  6356 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-05 11:00:42.112  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 11:00:42.112  6356  6356 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-05 11:00:42.112  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 11:00:42.113  6356  6356 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-05 11:00:42.113  6356  6356 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-05 11:00:42.114  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:00:42.116  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:42.118  6201  6264 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:00:42.118  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:42.118  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:42.119  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:42.120  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:42.120  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:42.120  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.120  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.120  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:42.120  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.120  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d42b6d6 removed from the list
08-05 11:00:42.120  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.120  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a13d57 removed from the list
08-05 11:00:42.120  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:42.120  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.121  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.121  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.121  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.121 , 6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.122  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.122  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a13d57 not in the list
08-05 11:00:42.122  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.122  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:00:42.124  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 11:00:42.125  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:42.125  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:42.125  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.125  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.125  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8b6a62 removed from the list
08-05 11:00:42.125  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.125  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.125  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.125  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.125  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bf2952d removed from the list
08-05 11:00:42.126  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:00:42.126  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e905729 added. We now have 2 listener(s)
08-05 11:00:42.126  1032  1954 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.129  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.129  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.129  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.129  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.129  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b9caae added. We now have 9 listener(s)
08-05 11:00:42.129  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.129  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 09:00:41 GMT], X-Android-Received-Millis=[1470387642129], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470387642078]}
08-05 11:00:42.129  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:00:42.130  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 11:00:42.130  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-05 11:00:42.130  1032  1540 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 11:00:42.130  1032  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 11:00:42.130  1032  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:00:42.130  1032  1540 D ConnectivityService:   chec,king if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:42.130  1032  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 11:00:42.131  1032  1540 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 11:00:42.131  1032  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 11:00:42.131  1032  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:42.131  1032  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:42.131  1032  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:42.132  1032  1540 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:42.132  1599  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 11:00:42.132  1032  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 11:00:42.132  1848  1848 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:42.132  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-05 11:00:42.132  1032  1534 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:42.132  1032  1534 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:00:42.134  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:00:42.143  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:42.143  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:42.143  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:42.143  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:42.143  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:42.143  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.143  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:00:42.143  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:00:42.145  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.146  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:42.146  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:00:42.146  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1218e3dc added. We now have 3 listener(s)
08-05 11:00:42.146  1032  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.147  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:00:42.151  1599  1599 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-05 11:00:42.152  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:42.152  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-05 11:00:42.153  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.153  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.153  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.153  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.153  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@222e3ce5 added. We now have 10 listener(s)
08-05 11:00:42.154  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.154  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:00:42.155  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:00:42.155  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:00:42.155  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:00:42.155  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:42.155  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:00:42.157  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:00:42.157  1032  2001 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.160  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 11:00:42.161  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 11:00:42.163  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:00:42.163  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:42.164  6201  6264 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 11:00:42.164  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:42.164  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:42.164  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:42.165  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.165  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.165  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:42.165  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.165  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e905729 removed from the list
08-05 11:00:42.165  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.165  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b9caae removed from the list
08-05 11:00:42.165  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:42.165  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.165  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.165  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.166  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.166  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.166  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.166  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10b9caae not in the list
08-05 11:00:42.166  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.166  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.166  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.167  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:42.167  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:00:42.167  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.167  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.167  620,1  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@222e3ce5 removed from the list
08-05 11:00:42.167  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.167  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.167  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.167  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.167  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1218e3dc removed from the list
08-05 11:00:42.167  7024  7024 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 11:00:42.167  7024  7024 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 11:00:42.167  7024  7024 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 11:00:42.167  7024  7024 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-05 11:00:42.167  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:00:42.168  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e61c8 added. We now have 2 listener(s)
08-05 11:00:42.168  7024  7024 D dhcpcd  : wlan0: sending REQUEST (xid 0x69a8f22c), next in 4.65 seconds
08-05 11:00:42.168  1032  1882 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.169  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17",
08-05 11:00:42.169  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.169  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.170  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.170  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ac261 added. We now have 9 listener(s)
08-05 11:00:42.170  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.170  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:00:42.171  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:00:42.175  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:42.175  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-05 11:00:42.175  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:42.175  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:42.175  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:42.175  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.175  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:00:42.175  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:00:42.177  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.177  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:42.179  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:42.179  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:00:42.179  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b962a47 added. We now have 3 listener(s)
,08-05 11:00:42.179  1032  1594 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.181  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.181  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.181  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.181  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.181  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29bbd274 added. We now have 10 listener(s)
08-05 11:00:42.181  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.181  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 11:00:42.181  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:00:42.181  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:00:42.181  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:42.181  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:00:42.183  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:00:42.184  1032  1936 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:00:42.187  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 11:00:42.188  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-05 11:00:42.190  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:00:42.190  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:42.191  6201  6264 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 11:00:42.192  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:42.192  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:42.192  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:42.192  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.192  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.193  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 11:00:42.193  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.193  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23e61c8 removed from the list
08-05 11:00:42.193  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.193  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ac261 removed from the list
,08-05 11:00:42.193  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:42.193  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.193  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.193  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:00:42.194  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.194  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.194  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.194  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f0ac261 not in the list
08-05 11:00:42.194  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:00:42.194  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.195  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.195  6201  6264 D BluetoothLeScanner: could not find callback wrapper
08-05 11:00:42.195  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 11:00:42.195  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.195  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.195  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29bbd274 removed from the list
08-05 11:00:42.195  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.195  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.195  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:00:42.195  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.195  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b962a47 removed from the list
08-05 11:00:42.196  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:00:42.196  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a0123e3 added. We now have 2 listener(s)
08-05 11:00:42.196  1032  1571 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-05 11:00:42.198  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.198  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 11:00:42.198  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.198  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.198  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffda1e0 added. We now have 9 listener(s)
08-05 11:00:42.198  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.200  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:00:42.202  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:00:42.205  6201  6264 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:00:42.205  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:42.205  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:42.205  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:42.205  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:42.205  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.205  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:00:42.205  6201  6264 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:00:42.206  6201  6264 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:42.206  6201  6264 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:00:42.207  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:00:42.207  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:00:42.207  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26043b5e added. We now have 3 listener(s)
08-05 11:00:42.208  1032  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-05 11:00:42.209  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-05 11:00:42.209  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:00:42.209  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:00:42.209  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:00:42.209  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2981b3f added. We now have 10 listener(s)
08-05 11:00:42.209  6201  6264 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:00:42.210  6201  6264 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:00:42.210  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:42.210  6201  6264 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:00:42.210  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:00:42.210  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.210  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:00:42.210  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.210  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a0123e3 removed from the list
08-05 11:00:42.210  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:00:42.210  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffda1e0 removed from the list
08-05 11:00:42.210  6201  6264 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:00:42.210  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.211  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.211  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.212  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.212  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.212  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.212  6201  6264 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ffda1e0 not in the list
08-05 11:00:42.212  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.212  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.213  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:00:42.213  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:00:42.213  6201  6264 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:00:42.213  6201  6264 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2981b3f removed from the list
,08-05 11:00:42.213  6201  6264 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 11:00:42.213  6201  6264 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:00:42.213  6201  6264 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:00:42.213  6201  6264 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:00:42.213  6201  6264 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26043b5e removed from the list
,08-05 11:00:42.214  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 11:00:42.214  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 11:00:42.214  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-05 11:00:42.214  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 11:00:42.214  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 11:00:42.215  6201  6264 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 11:00:42.223  6201  7032 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 804, name: My test thread name)
08-05 11:00:42.223  6201  7032 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 804, thread name: My test thread name),
08-05 11:00:42.224  6201  7032 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 804, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 11:00:42.227  7024  7024 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-05 11:00:42.228  6201  7033 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 806, name: My test thread name)
,08-05 11:00:42.228  6201  7033 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 806, thread name: My test thread name)
08-05 11:00:42.228  6201  7033 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 806, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 11:00:42.231  6201  6264 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-05 11:00:42.231  6201  6264 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 11:00:42.231  6201  6264 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-05 11:00:42.231  6201  6264 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 11:00:42.231  6201  6264 D com.test.thalitest.ThaliTestRunner: Total duration: 22840 ms
08-05 11:00:42.232  6201  6264 I jxcore-log: Total number of executed tests:  80
08-05 11:00:42.232  6201  6264 I jxcore-log: 
08-05 11:00:42.232  6201  6264 I jxcore-log: Number of passed tests:  80
08-05 11:00:42.232  6201  6264 I jxcore-log: 
08-05 11:00:42.233  6201  6264 I jxcore-log: Number of failed tests:  0
08-05 11:00:42.233  6201  6264 I jxcore-log: 
08-05 11:00:42.233  6201  6264 I jxcore-log: Number of ignored tests:  0
08-05 11:00:42.233  6201  6264 I jxcore-log: 
08-05 11:00:42.233  6201  6264 I jxcore-log: Total duration:  22840
08-05 11:00:42.233  6201  6264 I jxcore-log: 
08-05 11:00:42.236  6201  6264 I jxcore-log: Unit Test app is loaded
08-05 11:00:42.236  6201  6264 I jxcore-log: 
08-05 11:00:42.248  6201  6201 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 11:00:42.251  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.251  6201  6264 I jxcore-log: 
,08-05 11:00:42.259  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.259  6201  6264 I jxcore-log: 
08-05 11:00:42.261  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.261  6201  6264 I jxcore-log: 
08-05 11:00:42.263  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.263  6201  6264 I jxcore-log: 
,08-05 11:00:42.264  7024  7024 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-05 11:00:42.264  7024  7024 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-05 11:00:42.265  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.265  6201  6264 I jxcore-log: 
08-05 11:00:42.265  7024  7024 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-05 11:00:42.265  7024  7024 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-05 11:00:42.266  7024  7024 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-05 11:00:42.266  7024  7024 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-05 11:00:42.266  7024  7024 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-05 11:00:42.266  7024  7024 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-05 11:00:42.268  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.268  6201  6264 I jxcore-log: 
08-05 11:00:42.274  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.274  6201  6264 I jxcore-log: 
,08-05 11:00:42.276  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.276  6201  6264 I jxcore-log: 
08-05 11:00:42.277  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.277  6201  6264 I jxcore-log: 
,08-05 11:00:42.278  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 11:00:42.278  6201  6264 I jxcore-log: 
08-05 11:00:42.279  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.279  6201  6264 I jxcore-log: 
08-05 11:00:42.280  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.280  6201  6264 I jxcore-log: 
08-05 11:00:42.281  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.281  6201  6264 I jxcore-log: 
,08-05 11:00:42.281  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.281  6201  6264 I jxcore-log: 
08-05 11:00:42.282  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.282  6201  6264 I jxcore-log: 
08-05 11:00:42.283  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.283  6201  6264 I jxcore-log: 
08-05 11:00:42.284  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.284  6201  6264 I jxcore-log: 
08-05 11:00:42.285  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.285  6201  6264 I jxcore-log: 
,08-05 11:00:42.285  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.285  6201  6264 I jxcore-log: 
,08-05 11:00:42.286  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:00:42.286  6201  6264 I jxcore-log: 
,08-05 11:00:42.287  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.287  6201  6264 I jxcore-log: 
,08-05 11:00:42.287  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:00:42.287  6201  6264 I jxcore-log: 
,08-05 11:00:42.288  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:00:42.288  6201  6264 I jxcore-log: 
08-05 11:00:42.289  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:00:42.289  6201  6264 I jxcore-log: 
08-05 11:00:42.290  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:00:42.290  6201  6264 I jxcore-log: 
08-05 11:00:42.290  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:00:42.290  6201  6264 I jxcore-log: 
08-05 11:00:42.291  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:00:42.291  6201  6264 I jxcore-log: 
08-05 11:00:42.295  6201  6264 I jxcore-log: My device name is: LGE-LG-D855
08-05 11:00:42.295  6201  6264 I jxcore-log: 
08-05 11:00:42.684  1032  6993 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-05 11:00:42.687  1032  6993 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-05 11:00:42.687  1032  6993 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-05 11:00:42.687  1032  6993 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-05 11:00:42.687  1032  6993 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-05 11:00:42.687  1032  6993 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-05 11:00:42.687  1032  6993 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-05 11:00:42.688  1032  6993 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-05 11:00:42.688  1032  6993 D DhcpStateMachine: RunningState
,08-05 11:00:42.869  1032  1534 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 11:00:42.870  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 11:00:42.871  1032  1534 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 11:00:42.873  1032  1534 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-05 11:00:42.875  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-05 11:00:42.879  1032  1534 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-05 11:00:42.881  1032  1540 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-05 11:00:42.882  1032  1540 D ConnectivityService: identical MTU - not setting
,08-05 11:00:42.882  1032  1540 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-05 11:00:42.883  1032  1540 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 11:00:42.884  1032  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:42.884  1032  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:42.886  1032  1540 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:42.888  1599  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-05 11:00:44.789  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 11:00:44.789  6201  6264 I jxcore-log: 
,08-05 11:00:44.870  1032  1534 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1508829638] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 11:00:44.872  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-46 f=2447 sc=60 link=72 tx=2.0, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1508829640] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 11:00:44.872  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 11:00:44.892  1599  1599 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-05 11:00:44.922  1032  1535 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-05 11:00:44.957  1032  1540 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:00:44.969  1032  1115 D Tethering: MasterInitialState.processMessage what=3
08-05 11:00:44.969  1032  1088 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:00:44.979  1032  1823 D AlarmManagerService: Setting time of day to sec=1470387644
,08-05 11:00:44.591  1032  1823 W AlarmManagerService: Unable to set rtc to 1470387644: Invalid argument
08-05 11:00:44.607  6201  6201 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:00:44.607  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:00:44.607  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 11:00:44.607  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:00:44.607  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:00:44.607  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:44.607  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:00:44.607  6201  6201 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:00:44.610  6201  6201 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:00:44.628  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 11:00:44.630  1937  1937 I SecureClockService: Intent.ACTION_TIME_CHANGED 
08-05 11:00:44.631  1599  1599 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
08-05 11:00:44.636  3698  3698 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
08-05 11:00:44.637  3698  3698 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-08-05 11:00:44...... Request
08-05 11:00:44.637  3698  3698 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 8, total count : 46, new day : false...... Request
08-05 11:00:44.637  3698  3698 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 46
08-05 11:00:44.637  3698  3698 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 8
08-05 11:00:44.638  3698  3698 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-08-05 11:00:44
08-05 11:00:44.642  1032  1780 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
,08-05 11:00:44.646  2029  2029 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=5 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
08-05 11:00:44.649  2029  2029 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 5
08-05 11:00:44.650  1599  1599 I LgeClockWidgetControlView: time changed, timezoneChanged : false
08-05 11:00:44.658  2029  2029 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 5
08-05 11:00:44.658  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 11:00:44.673  1032  1088 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 11:00:44.678  5347  5347 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-05 11:00:44.679  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-05 11:00:44.680  3730  6285 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-05 11:00:44.686  2567  2567 D [Concierge]Service: onStartCommand(). Type : 9
08-05 11:00:44.690  1032  1088 E GpsLocationProvider: No APN found to select.
,08-05 11:00:44.718  2179  2179 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:00:44.725   318  7076 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 11:00:44.726   318  7076 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 11:00:44.726  1032  1882 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-05 11:00:44.727  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:44.727  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:44.727  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 11:00:44.727  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 11:00:44.727  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-05 11:00:44.750  1032  1049 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7077 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-05 11:00:44.768   318  7076 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-05 11:00:44.780  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 09:00:44 GMT], X-Android-Received-Millis=[1470387644780], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470387644728]}
08-05 11:00:44.780  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 11:00:44.781  1032  6992 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-05 11:00:44.781  1032  1540 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-05 11:00:44.781  1032  1540 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-05 11:00:44.781  1032  1540 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 11:00:44.781  1032  1540 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:44.781  1032  1540 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-05 11:00:44.781  1032  1540 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-05 11:00:44.781  1032  1540 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-05 11:00:44.781  1032  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 11:00:44.781  1032  1540 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:44.781  1032  1540 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 11:00:44.782  1599  2067 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 11:00:44.812  7077  7077 I AppUp4:AppBoxCP: onCreate
08-05 11:00:44.813  7077  7077 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-05 11:00:44.820  7077  7077 I AppUp4:DB:  setFingerPrint start
08-05 11:00:44.820  7077  7077 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-05 11:00:44.826  7077  7077 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-05 11:00:44.826  7077  7077 I AppUp4:DB:  SDK version = 21
08-05 11:00:44.826  7077  7077 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-05 11:00:44.827  7077  7077 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-05 11:00:44.828  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-05 11:00:44.828  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:00:44.830  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-05 11:00:44.830  7077  7077 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-05 11:00:44.836  7077  7077 I AppUp4:CustModeStarterReceiver: onReceive
,08-05 11:00:44.865  7077  7077 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:00:44.865  7077  7077 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:00:44.873  7077  7077 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@3b50cf5c
08-05 11:00:44.873  7077  7077 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 11:00:44.873  7077  7077 D AppUp4:CustFacade: isPhone : true
08-05 11:00:44.874  7077  7077 D AppUp4:CustModeStarterReceiver: begin check event
08-05 11:00:44.874  7077  7077 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-05 11:00:44.874  7077  7077 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-05 11:00:44.881  7077  7096 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-05 11:00:44.881  7077  7096 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-05 11:00:44.881  7077  7096 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-05 11:00:44.884  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-05 11:00:44.884  4238  4238 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-05 11:00:44.885  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:44.886  4238  4238 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-05 11:00:44.890  3475  3475 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-05 11:00:44.891  4238  7098 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-05 11:00:44.891  4238  7099 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-05 11:00:44.891  4238  7099 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-05 11:00:44.893  4238  7098 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,08-05 11:00:44.897  3475  3475 V DownloadManager: DownloadService onCreate
08-05 11:00:44.901  3475  7101 I DownloadManager: in removeSpuriousFiles
08-05 11:00:44.903  3475  7101 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-05 11:00:44.906  3475  7101 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@386c1e9a on behalf of 3475
,08-05 11:00:44.908  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-05 11:00:44.908  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-05 11:00:44.908  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-05 11:00:44.908  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-05 11:00:44.909  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-05 11:00:44.909  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-05 11:00:44.909  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-05 11:00:44.909  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-05 11:00:44.909  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-05 11:00:44.910  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-05 11:00:44.910  3475  7101 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-05 11:00:44.910  3475  7101 I DownloadManager: in trimDatabase
08-05 11:00:44.911  3475  7101 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-05 11:00:44.911  3475  7101 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@141147a8 on behalf of 3475
08-05 11:00:44.941  2179  7075 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-05 11:00:44.947  1032  1955 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7104 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-05 11:00:44.949  3475  3475 V DownloadManager: DownloadService onStartCommand
08-05 11:00:44.949  3475  7102 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-05 11:00:44.951  3475  7102 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1c5d8a66 on behalf of 3475
08-05 11:00:44.956  3475  7102 V DownloadManager: processing inserted download 1
08-05 11:00:44.957  3475  7102 V DownloadManager: processing inserted download 4
08-05 11:00:44.958  3475  7102 V DownloadManager: processing inserted download 7
08-05 11:00:44.959  4238  7098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-05 11:00:44.960  3475  7102 V DownloadManager: processing inserted download 8
,08-05 11:00:44.961  3475  7102 V DownloadManager: processing inserted download 9
08-05 11:00:44.962  3475  7102 V DownloadManager: processing inserted download 10
08-05 11:00:44.964  3475  7102 V DownloadManager: processing inserted download 11
08-05 11:00:44.966  4238  4238 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-05 11:00:44.966  4238  4238 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-05 11:00:44.966  4238  4238 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-05 11:00:44.970  4238  4238 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-05 11:00:44.972  4238  4238 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
,08-05 11:00:44.975  3475  7102 V DownloadManager: processing inserted download 12
08-05 11:00:44.976  3475  7102 V DownloadManager: processing inserted download 13
08-05 11:00:44.977  3475  7102 V DownloadManager: processing inserted download 14
08-05 11:00:44.978  3475  7102 V DownloadManager: processing inserted download 16
08-05 11:00:44.981  3475  3475 V DownloadManager: DownloadService onDestroy
,08-05 11:00:45.004  7104  7104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:00:45.005  7104  7104 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:00:45.005  7104  7104 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 11:00:45.006  7104  7104 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 11:00:45.077  7104  7104 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 11:00:45.087  7104  7104 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 11:00:45.147  7104  7104 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 11:00:45.179  7104  7104 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 11:00:45.179  7104  7104 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:00:45.197  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 11:00:45.197  6201  6264 I jxcore-log: 
,08-05 11:00:45.221  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 11:00:45.221  6201  6264 I jxcore-log: 
,08-05 11:00:45.312  7104  7104 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-05 11:00:45.357  3426  3426 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-05 11:00:45.357  3426  3426 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:00:45.363  3426  3426 I LgeMiscReceiver: networkInfo.isConnected() = true
08-05 11:00:45.364  3426  3426 D PhoneState: setPdpRejectCasuse : false
08-05 11:00:45.366  7104  7104 I HubEmail: JNI_OnLoad()
08-05 11:00:45.366  7104  7104 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 11:00:45.366  7104  7104 I HubEmail: registerNatives()
08-05 11:00:45.366  7104  7104 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 11:00:45.366  7104  7104 I HubEmail: registerNativeMethods()
08-05 11:00:45.366  7104  7104 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-05 11:00:45.368  7104  7104 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-05 11:00:45.397   318  7136 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-05 11:00:45.401   318  7136 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-05 11:00:45.402  1032  1049 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7137 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-05 11:00:45.412  7104  7134 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:00:45.440   318  7136 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-05 11:00:45.508  6400  7133 V FormManager: There are no updated forms. The schedule will be deleted.
,08-05 11:00:45.513  6400  7133 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-05 11:00:45.550  1032  1900 I art     : Explicit concurrent mark sweep GC freed 80080(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.019ms total 107.303ms
,08-05 11:00:45.586  1032  1936 I ActivityManager: Killing 5837:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-05 11:00:45.609  7137  7137 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:00:45.609  7137  7137 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:00:45.611  7137  7137 D PhoneMonitor: Register our PhoneStateListener
,08-05 11:00:45.731  1032  1882 W libprocessgroup: failed to open /acct/uid_10027/pid_5837/cgroup.procs: No such file or directory
,08-05 11:00:45.740   318  7161 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 11:00:45.741   318  7161 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-05 11:00:45.750  7137  7137 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-05 11:00:45.756  7137  7137 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-05 11:00:45.772   318  7161 D libc-netbsd: res_queryN name = www.google.com succeed
08-05 11:00:45.777   318  7165 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 11:00:45.777  7137  7137 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-05 11:00:45.777   318  7165 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-05 11:00:45.777   318  7165 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-05 11:00:45.779  7137  7137 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-05 11:00:45.780  7137  7137 D TelephonyAutoProfiling: [parse] Load xml
08-05 11:00:45.787  7137  7137 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-05 11:00:45.787  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-05 11:00:45.788  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-05 11:00:45.788  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-05 11:00:45.788  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-05 11:00:45.788  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-05 11:00:45.788  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-05 11:00:45.788  7137  7137 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-05 11:00:45.788  7137  7137 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-05 11:00:45.794  1032  1780 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7166 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 11:00:45.796  1032  1780 I ActivityManager: Killing 5912:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-05 11:00:45.801  7137  7137 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-05 11:00:45.863  1032  1536 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-05 11:00:45.911  1032  2009 W libprocessgroup: failed to open /acct/uid_10061/pid_5912/cgroup.procs: No such file or directory
,08-05 11:00:45.956  1813  7183 I CheckinService: active receiver: enabled
,08-05 11:00:45.968  1813  7183 I CheckinService: Preparing to send checkin request
08-05 11:00:45.969  1813  7183 I EventLogService: Accumulating logs since 1470387415347
08-05 11:00:46.002  1813  7183 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-05 11:00:46.007  1032  1539 D WifiService: New client listening to asynchronous messages
,08-05 11:00:46.153  1032  2001 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7187 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-05 11:00:46.219  7187  7187 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-05 11:00:46.220  7187  7187 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-05 11:00:46.235  7187  7187 I MultiDex: VM with version 2.1.0 has multidex support
08-05 11:00:46.236  7187  7187 I MultiDex: install
08-05 11:00:46.236  7187  7187 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-05 11:00:46.238  1032  1049 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7204 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-05 11:00:46.239  1032  1049 I ActivityManager: Killing 5960:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-05 11:00:46.362  1032  1571 W libprocessgroup: failed to open /acct/uid_10080/pid_5960/cgroup.procs: No such file or directory
,08-05 11:00:46.385  7187  7187 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-05 11:00:46.434  7204  7204 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION,
,08-05 11:00:46.436  7204  7204 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
08-05 11:00:46.442  7204  7204 V DrmService: Service onCreate
,08-05 11:00:46.442  7204  7204 D DrmService: Received new request = 2
,08-05 11:00:46.447  7204  7222 I DrmSntpClient: Start Sync process
08-05 11:00:46.447  7204  7222 D DrmSntpClient: Server : 0
08-05 11:00:46.458   318  7223 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 11:00:46.458   318  7223 D libc-netbsd: res_queryN name = pool.ntp.org, class = 1, type = 1
,08-05 11:00:46.480  1032  1780 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7224 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 11:00:46.496   318  7223 D libc-netbsd: res_queryN name = pool.ntp.org succeed
,08-05 11:00:46.511  7204  7222 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
08-05 11:00:46.512   327   895 V ILGDrmService: eDRM_SetDRMTime +++
08-05 11:00:46.512   327   895 I LGDRM   : [DRM] SET TIME : YR=2016, MON=8, DAY=5
08-05 11:00:46.512   327   895 I LGDRM   : [DRM] SET TIME : HR=9, MIN=0, SEC=45
,08-05 11:00:46.522   327   895 V ILGDrmService: eDRM_SetDRMTime ---
08-05 11:00:46.522  7204  7222 I DrmSntpClient: Synched
08-05 11:00:46.525  7204  7204 D DrmService: Completed !! request = 2
08-05 11:00:46.525  7204  7204 D DrmService: Request count = 0
,08-05 11:00:46.528  7204  7204 V DrmService: Service onDestroy
08-05 11:00:46.529  1032  1955 I ActivityManager: Killing 6028:com.lge.eula/1000 (adj 15): empty #17
08-05 11:00:46.550  7224  7224 I art     : Almond Protected OAT
,08-05 11:00:46.611  1032  1780 W libprocessgroup: failed to open /acct/uid_1000/pid_6028/cgroup.procs: No such file or directory
,08-05 11:00:46.613  7224  7224 D WeatherApplication: removeAccount
,08-05 11:00:46.614  7224  7224 D WeatherApplication: Account.length = 0
08-05 11:00:46.614  7224  7224 E WeatherApplication: OPERATOR:OPEN
08-05 11:00:46.617  7224  7224 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:0:46
08-05 11:00:46.620  7224  7224 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 11:00:46.620  7224  7224 D Weather.Utils: 2 : All the weather widget is gone.
08-05 11:00:46.622  7224  7224 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 11:00:46.624  7224  7224 D WeatherAncestor: connectivity changed - connection : true
08-05 11:00:46.625  7224  7224 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-05 11:00:46.631  7224  7224 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-05 11:00:46.632  7224  7224 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 11:00:46.632  7224  7224 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-05 11:00:46.652  7224  7224 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-05 11:00:46.652  7224  7224 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:0:46
,08-05 11:00:46.680  1032  1973 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7242 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 11:00:46.682  1032  1973 I ActivityManager: Killing 5986:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-05 11:00:46.724  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 11:00:46.724  6201  6264 I jxcore-log: 
,08-05 11:00:46.761  1032  1918 W libprocessgroup: failed to open /acct/uid_10097/pid_5986/cgroup.procs: No such file or directory
,08-05 11:00:46.810  7259  7259 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-05 11:00:46.853   278   419 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 11:00:46.854   278   419 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-05 11:00:46.854   278   419 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 11:00:46.854  7242  7266 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 11:00:46.854  7259  7259 I dex2oat : dex2oat took 43.599ms (threads: 4)
08-05 11:00:46.857   278   419 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 11:00:46.857   278   419 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 11:00:46.857   278   419 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 11:00:46.857  7242  7266 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 11:00:46.866   278   419 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 11:00:46.866   278   419 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-05 11:00:46.866   278   419 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 11:00:46.866  7242  7268 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-05 11:00:46.867   278   419 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-05 11:00:46.867   278   419 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-05 11:00:46.867   278   419 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 11:00:46.867  7242  7268 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-05 11:00:46.867  7187  7202 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:00:46.867  7187  7202 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:00:46.867  7187  7202 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:00:46.867  7187  7202 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:00:46.867  7187  7202 I Adreno-EGL: Remote Branch: 
08-05 11:00:46.867  7187  7202 I Adreno-EGL: Local Patches: 
08-05 11:00:46.867  7187  7202 I Adreno-EGL: Reconstruct Branch: 
,08-05 11:00:46.954  7187  7202 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:00:46.954  7187  7202 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:00:46.954  7187  7202 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:00:46.954  7187  7202 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:00:46.954  7187  7202 I Adreno-EGL: Remote Branch: 
08-05 11:00:46.954  7187  7202 I Adreno-EGL: Local Patches: 
08-05 11:00:46.954  7187  7202 I Adreno-EGL: Reconstruct Branch: 
,08-05 11:00:46.960  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 11:00:46.960  6201  6264 I jxcore-log: 
08-05 11:00:46.965  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 11:00:46.965  6201  6264 I jxcore-log: 
08-05 11:00:46.981  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 11:00:46.981  6201  6264 I jxcore-log: 
,08-05 11:00:46.984  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 11:00:46.984  6201  6264 I jxcore-log: 
,08-05 11:00:47.014  7242  7242 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-05 11:00:47.024  7242  7242 I LibraryLoader: Loading: webviewchromium
08-05 11:00:47.027  7242  7242 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7344-7348)
08-05 11:00:47.027  7242  7242 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 11:00:47.033  7242  7242 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {543acb7}
08-05 11:00:47.034  7242  7242 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:00:47.034  7242  7242 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 11:00:47.057  7242  7242 I BrowserStartupController: Initializing chromium process, renderers=0
,08-05 11:00:47.060  7242  7242 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 11:00:47.076  7242  7242 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-05 11:00:47.077  7242  7242 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-05 11:00:47.077  7242  7242 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-05 11:00:47.084   322  1385 V AudioPolicyService: registerClient() client 0xb04104a0, uid 10093
08-05 11:00:47.085  7242  7291 W AudioManagerAndroid: Requires BLUETOOTH permission
08-05 11:00:47.094  7242  7242 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:00:47.094  7242  7242 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:00:47.094  7242  7242 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:00:47.094  7242  7242 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:00:47.094  7242  7242 I Adreno-EGL: Remote Branch: 
08-05 11:00:47.094  7242  7242 I Adreno-EGL: Local Patches: 
08-05 11:00:47.094  7242  7242 I Adreno-EGL: Reconstruct Branch: 
,08-05 11:00:47.169  7242  7242 I NSApplication: Starting up...
,08-05 11:00:47.176  7187  7202 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:00:47.176  7187  7202 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:00:47.209  1032  1955 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7304 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-05 11:00:47.212  1032  1955 I ActivityManager: Killing 5860:com.android.vending/u0a44 (adj 15): empty #17
08-05 11:00:47.284  7187  7202 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-05 11:00:47.284  7187  7202 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-05 11:00:47.284  7187  7202 I Adreno-EGL: Build Date: 12/12/14 금
08-05 11:00:47.284  7187  7202 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-05 11:00:47.284  7187  7202 I Adreno-EGL: Remote Branch: 
08-05 11:00:47.284  7187  7202 I Adreno-EGL: Local Patches: 
08-05 11:00:47.284  7187  7202 I Adreno-EGL: Reconstruct Branch: 
,08-05 11:00:47.331  1032  1048 W libprocessgroup: failed to open /acct/uid_10044/pid_5860/cgroup.procs: No such file or directory
08-05 11:00:47.359  7304  7304 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 11:00:47.403   318  7322 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 11:00:47.403   318  7322 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-05 11:00:47.441   318  7322 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-05 11:00:47.500  1032  1534 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:2610] from screen [on:0 period:1508832268] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 11:00:47.501  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-42 f=2447 sc=60 link=72 tx=7.0, 0.0, 0.0  rx=5.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1508832269] gl rssi=-42 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 11:00:47.501  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 11:00:47.611  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,08-05 11:00:47.626  1813  7183 I CheckinTask: Sending checkin request (8042 bytes)
,08-05 11:00:47.661  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 11:00:47.661  6201  6264 I jxcore-log: 
,08-05 11:00:47.673  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-05 11:00:47.673  6201  6264 I jxcore-log: 
08-05 11:00:47.675  1032  1973 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7334 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-05 11:00:47.683  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 11:00:47.683  6201  6264 I jxcore-log: 
08-05 11:00:47.689  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 11:00:47.689  6201  6264 I jxcore-log: 
,08-05 11:00:47.766  7334  7361 D ALBootInit: ====action==>android.intent.action.TIME_SET
,08-05 11:00:47.769  7334  7361 D ALBootInit: Alarm ALBootInit: TIME_SET
08-05 11:00:47.772  7334  7361 D Alarms  : [setNextAlert] start
,08-05 11:00:47.787  7334  7361 D Alarms  : [setNextAlert] (1)
08-05 11:00:47.789  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 11:00:47.789  6201  6264 I jxcore-log: 
,08-05 11:00:47.790  7334  7361 D Alarms  :  minTime  = 0
08-05 11:00:47.792  7334  7361 D Alarms  :  -- OK multi -- 0
08-05 11:00:47.793  7334  7361 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
08-05 11:00:47.793  7334  7361 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
08-05 11:00:47.810  7334  7361 I CommonUtil: BUILD Country: EU
,08-05 11:00:47.811  7334  7361 D Alarms  : broadcastToWidgetProvider : false
08-05 11:00:47.814  7334  7361 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
08-05 11:00:47.822  1032  1900 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,08-05 11:00:47.826  7334  7334 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
08-05 11:00:47.827  7334  7334 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1dbe8265
08-05 11:00:47.829  7334  7334 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1dbe8265
08-05 11:00:47.836  7334  7334 D QuickCoverProvider: onReceiver
,08-05 11:00:47.841  1554  1554 I indal   : SmartCoverWidgetContext createApplicationContext
08-05 11:00:47.841  1554  1554 I indal   : SmartCoverWidgetContext createApplicationContext
,08-05 11:00:47.853  7224  7224 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:0:47
08-05 11:00:47.860  7224  7224 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 11:00:47.860  7224  7224 D Weather.Utils: 2 : All the weather widget is gone.
08-05 11:00:47.860  7224  7224 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-05 11:00:47.862  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-05 11:00:47.862  6201  6264 I jxcore-log: 
08-05 11:00:47.865  7224  7224 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@34f67b3a
08-05 11:00:47.865  7224  7224 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-05 11:00:47.865  7224  7224 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-05 11:00:47.866  7224  7224 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-05 11:00:47.868  7224  7224 D Weather_cast: 2 : set auto-update time : 8/5 14:0
08-05 11:00:47.869  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 11:00:47.869  6201  6264 I jxcore-log: 
,08-05 11:00:47.873  7224  7224 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:0:47
,08-05 11:00:47.947  1032  1780 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7366 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-05 11:00:47.954  1032  1780 I ActivityManager: Killing 6327:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-05 11:00:47.961   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 456us total 20.710ms
,08-05 11:00:47.980   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 400us total 18.281ms
,08-05 11:00:47.997   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 349us total 15.996ms
,08-05 11:00:48.036  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 11:00:48.036  6201  6264 I jxcore-log: 
,08-05 11:00:48.060  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 11:00:48.060  6201  6264 I jxcore-log: 
,08-05 11:00:48.064  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 11:00:48.064  6201  6264 I jxcore-log: 
08-05 11:00:48.069  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 11:00:48.069  6201  6264 I jxcore-log: 
08-05 11:00:48.087  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 11:00:48.087  6201  6264 I jxcore-log: 
,08-05 11:00:48.167  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 11:00:48.167  6201  6264 I jxcore-log: 
,08-05 11:00:48.179  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 11:00:48.179  6201  6264 I jxcore-log: 
,08-05 11:00:48.206  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 11:00:48.206  6201  6264 I jxcore-log: 
,08-05 11:00:48.219  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 11:00:48.219  6201  6264 I jxcore-log: 
,08-05 11:00:48.239  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 11:00:48.239  6201  6264 I jxcore-log: 
,08-05 11:00:48.245  1032  1048 W libprocessgroup: failed to open /acct/uid_10037/pid_6327/cgroup.procs: No such file or directory
,08-05 11:00:48.276  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 11:00:48.276  6201  6264 I jxcore-log: 
,08-05 11:00:48.281  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 11:00:48.281  6201  6264 I jxcore-log: 
08-05 11:00:48.286  1813  7183 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-05 11:00:48.301  1813  7183 I CheckinService: active receiver: disabled
,08-05 11:00:48.303  7366  7366 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470387648303
08-05 11:00:48.304  7366  7366 D         : TimeServiceNative: User Time to be set is 1470387648303
08-05 11:00:48.304  7366  7366 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-05 11:00:48.304  7366  7366 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-05 11:00:48.304  7366  7366 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470387648303
08-05 11:00:48.305   360  1031 D QC-time-services: Daemon: Connection accepted:time_genoff
08-05 11:00:48.305  7366  7366 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-05 11:00:48.305   360  7383 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470387648303
08-05 11:00:48.305   360  7383 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470387648303, operation = 0
08-05 11:00:48.305   360  7383 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/15/70 3:28:28
08-05 11:00:48.305   360  7383 D QC-time-services: Daemon:Value read from RTC seconds = 3900508000
08-05 11:00:48.305   360  7383 D QC-time-services: Daemon:new time 1470387648303 
08-05 11:00:48.306   360  7383 D QC-time-services: Daemon: delta 1466487140303 genoff 1466487140303 
08-05 11:00:48.306   360  7383 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487140303 to memory
08-05 11:00:48.306   360  7383 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-05 11:00:48.306   360  7383 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-05 11:00:48.312   360  7383 D QC-time-services: Updating the TOD offset
08-05 11:00:48.312   360  7383 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487140303 to memory
08-05 11:00:48.312   360  7383 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-05 11:00:48.312   360  7383 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-05 11:00:48.319   360  7383 E QC-time-services: Daemon:Update to modem bit set
08-05 11:00:48.319   360  7383 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-05 11:00:48.320   360  7383 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522340303
08-05 11:00:48.320  7366  7366 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-05 11:00:48.322   360  1029 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-05 11:00:48.322   360  1031 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-05 11:00:48.324  6051  6051 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,08-05 11:00:48.326  6051  6051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-05 11:00:48.328  1599  1599 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-05 11:00:48.328  1599  1599 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-05 11:00:48.328  1599  1599 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-05 11:00:48.332  1813  7384 I CheckinService: active receiver: disabled
,08-05 11:00:48.342  6051  6051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
,08-05 11:00:48.343  6051  6051 V [BNRBootReceiver]: Boot Receiver Return
08-05 11:00:48.391  1032  1780 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7385 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
08-05 11:00:48.393  1032  1780 I ActivityManager: Killing 6373:com.lge.settings.easy/1000 (adj 15): empty #17
,08-05 11:00:48.467  6201  6264 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 11:00:48.467  6201  6264 I jxcore-log: 
,08-05 11:00:48.476  6201  6264 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-05 11:00:48.477  6201  6264 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-05 11:00:48.477  6201  6264 I jxcore-log: 
08-05 11:00:48.529  6201  6264 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:00:48.529  6201  6264 I jxcore-log: 
,08-05 11:00:48.537  1032  1955 W libprocessgroup: failed to open /acct/uid_1000/pid_6373/cgroup.procs: No such file or directory
08-05 11:00:48.594  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 7351
08-05 11:00:48.595  1032  1089 W ProcessCpuTracker: Skipping unknown process pid 7354
,08-05 11:00:48.600  7385  7385 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:00:48.639  7385  7385 D CalendarApplication: CalendarApplication.onCreate()
,08-05 11:00:48.648  7385  7385 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
08-05 11:00:48.649  7385  7385 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2635e030, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@45f44a9, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2731ea2e, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@332ee9cf, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3b50cf5c, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1dbe8265, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@34f67b3a, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2f5a53eb, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1c98548, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@719dfe1, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@31411106, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3c8843c7, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3d95adf4, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1273991d, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1d4d3792, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@dbb5563, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1a59b560, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@35b5aa19, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@20833ade, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3983e4bf, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1794c78c, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@16dced5, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1e8426ea, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@51c0ddb, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@b8cd078, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@7498351, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@21f5c7b6, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@543acb7, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@28fa7c24, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2c52038d, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@280ea942, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@30dc5d53, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@33753690, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@22e84b89, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@18e2178e, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1457baf, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@e9f2bbc, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@8811745, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@386c1e9a, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3c7823cb, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.Prefer,enceKey$KeyData@141147a8, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2320e2c1, 
08-05 11:00:48.652  7385  7385 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,08-05 11:00:48.660  7385  7385 D Config  : [init]
08-05 11:00:48.661  7385  7385 I Config  : LGCalendar ver.4.40.16
08-05 11:00:48.661  7385  7385 I Config  : start check model
,08-05 11:00:48.661  7385  7385 I Config  : start check native_ca
08-05 11:00:48.662  7385  7385 I Config  : Config Operator=OPEN, Country=EU
08-05 11:00:48.662  7385  7385 D Config  : [setDefaultValuesToPref]
08-05 11:00:48.662  7385  7385 D Config  : [parseProfiles]
08-05 11:00:48.666  7385  7385 D ProfilesParser: [debug_displayParseInfos] profile.country = null
08-05 11:00:48.666  7385  7385 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
08-05 11:00:48.666  7385  7385 D Config  : [updateProfiletoCountryInfo]
08-05 11:00:48.667  7385  7385 D GeneralPreference: [checkAndMigrateOldPreference]
08-05 11:00:48.678  7385  7385 E AgendaWidgetManager: [updateWidgets] 
,08-05 11:00:48.689  7385  7415 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
08-05 11:00:48.692  7385  7415 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
,08-05 11:00:48.711  7385  7415 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,08-05 11:00:48.717  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
08-05 11:00:48.720  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
08-05 11:00:48.723  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,08-05 11:00:48.728  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
08-05 11:00:48.736  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,08-05 11:00:48.741  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
08-05 11:00:48.744  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
08-05 11:00:48.748  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,08-05 11:00:48.759  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
08-05 11:00:48.763  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,08-05 11:00:48.820  7385  7385 D MonthWidgetProvider: [onReceive]
08-05 11:00:48.820  7385  7385 D CalendarWidgetProvider: [onReceive]
,08-05 11:00:48.820  7385  7385 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
08-05 11:00:48.822  7385  7416 W HolidayIntentService: onHandleIntent
08-05 11:00:48.823  7385  7416 D HolidayDataLoader: readJsonAsset : holiday.json
08-05 11:00:48.826  7385  7385 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-05 11:00:48.828  7385  7385 D WeekWidgetProvider: [onReceive]
08-05 11:00:48.829  7385  7385 D CalendarWidgetProvider: [onReceive]
08-05 11:00:48.829  7385  7385 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
08-05 11:00:48.829  7385  7385 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-05 11:00:48.833  6356  6356 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-05 11:00:48.833  6356  6356 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5603
,08-05 11:00:48.840  2179  2179 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-05 11:00:48.850  2179  2179 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-05 11:00:48.850  2179  2179 D c       : Getting all permits...
08-05 11:00:48.850  2179  2179 D a       : Opening database...
08-05 11:00:48.853  2179  2179 D a       : Opening database auth.proximity.permit_store...
08-05 11:00:48.855  2179  2179 D a       : Closing database...
08-05 11:00:48.865  7334  7334 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,08-05 11:00:48.867  1032  1571 I art     : Explicit concurrent mark sweep GC freed 18802(960KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.056ms total 100.251ms
08-05 11:00:48.868  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
08-05 11:00:48.869  7224  7224 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 11:0:48
08-05 11:00:48.872  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
08-05 11:00:48.875  7224  7224 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-05 11:00:48.875  7224  7224 D Weather.Utils: 2 : All the weather widget is gone.
08-05 11:00:48.876  7224  7224 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-05 11:00:48.877  7224  7224 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
08-05 11:00:48.877  7224  7224 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 11:0:48
,08-05 11:00:48.880  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
08-05 11:00:48.880  2029  2029 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
08-05 11:00:48.883  2029  2778 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-05 11:00:48.883  2029  2778 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-05 11:00:48.884  2179  2179 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-05 11:00:48.884  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
08-05 11:00:48.885  2029  2778 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-05 11:00:48.886  2029  2778 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-05 11:00:48.887  2029  2778 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-05 11:00:48.889  7385  7415 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
08-05 11:00:48.889  7385  7415 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,08-05 11:00:48.891  7385  7415 I AlertUtils: set default noti to content://media/internal/audio/media/41
08-05 11:00:48.894  7385  7415 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
08-05 11:00:48.895  2179  2179 I GCM     : GCM config loaded
08-05 11:00:48.900   318  7425 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-05 11:00:48.900   318  7425 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-05 11:00:48.900   318  7425 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-05 11:00:48.909  7385  7416 E HolidayIntentService: onHandleIntent:holiday data empty
08-05 11:00:48.910  7137  7137 V SetupWizard: Connected to Gservices successfully
,08-05 11:00:48.919  6051  6051 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
08-05 11:00:48.919  6051  6051 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-05 11:00:48.920  1599  1599 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-05 11:00:48.920  1599  1599 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-05 11:00:48.921  1599  1599 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,08-05 11:00:48.922  6051  6051 V [BNRBootReceiver]: Boot Receiver Return
08-05 11:00:48.924  1032  1954 I ActivityManager: Killing 6304:com.lge.sync/1000 (adj 15): empty #17
08-05 11:00:48.959  1032  1973 W libprocessgroup: failed to open /acct/uid_1000/pid_6304/cgroup.procs: No such file or directory
,08-05 11:00:48.963  2029  2029 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
08-05 11:00:48.967  2029  5380 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-05 11:00:48.968  2029  5380 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-05 11:00:48.968  2029  5380 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-05 11:00:48.970  2029  5380 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-05 11:00:48.970  2029  5380 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,08-05 11:00:49.223  2179  7434 D GCM     : Connected
,08-05 11:00:49.286  2179  7434 D GCM     : Message class com.google.e.a.a.q
,08-05 11:00:50.513  1032  1534 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=16.0, 0.0, 0.0  rx=12.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1508835280] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 11:00:50.516  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=16.0, 0.0, 0.0  rx=12.2 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:1508835284] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 11:00:50.516  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 11:00:51.878  7242  7269 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-05 11:00:52.368  1032  1780 I ActivityManager: Killing 6286:com.android.settings/1000 (adj 15): empty #17
,08-05 11:00:52.438  1032  1882 W libprocessgroup: failed to open /acct/uid_1000/pid_6286/cgroup.procs: No such file or directory
,08-05 11:00:52.631  1032  1973 I ActivityManager: Killing 7077:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-05 11:00:52.662  1032  2028 W libprocessgroup: failed to open /acct/uid_10011/pid_7077/cgroup.procs: No such file or directory
,08-05 11:00:53.536  1032  1534 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=22.0, 0.0, 0.0  rx=17.6 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1508838304] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 11:00:53.547  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=22.0, 0.0, 0.0  rx=17.6 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1508838315] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 11:00:53.547  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 11:00:56.009  1599  1599 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 11:00:56.058  1032  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 11:00:56.106  1032  1089 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7446 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 11:00:56.113  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-05 11:00:56.114  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-05 11:00:56.126  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 11:00:56.154  1032  1032 D administrator: Handling package changes for user 0
,08-05 11:00:56.165  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 11:00:56.191  7446  7446 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 11:00:56.267  7446  7446 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 11:00:56.268  7446  7446 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:00:56.287  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-05 11:00:56.287  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-05 11:00:56.341  1032  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 11:00:56.347  1032  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-05 11:00:56.355  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 11:00:56.357  2493  2493 V GmsNetworkLocationProvi: DISABLE
,08-05 11:00:56.373  7446  7491 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 11:00:56.373  7446  7491 I Babel   : MmsConfig.loadMmsSettings
08-05 11:00:56.382  7446  7491 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 11:00:56.382  7446  7491 I Babel   : MmsConfig.loadFromDatabase
,08-05 11:00:56.397  7446  7446 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:00:56.404  7446  7491 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-05 11:00:56.404  7446  7491 I Babel   : MmsConfig.loadFromResources
08-05 11:00:56.407  2493  2493 E GCoreFlp: Bound FusedProviderService with LocationManager
08-05 11:00:56.409  7446  7489 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 11:00:56.410  7446  7491 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-05 11:00:56.411  7446  7491 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-05 11:00:56.413  7446  7489 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 11:00:56.415  7446  7489 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-05 11:00:56.425  7446  7489 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-05 11:00:56.426  7446  7489 W AudioCapabilities: Unsupported mime audio/qcelp
08-05 11:00:56.430  1813  7495 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-05 11:00:56.431  1813  7495 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-05 11:00:56.432  7446  7489 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 11:00:56.443  1032  1955 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7498 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-05 11:00:56.448  1032  1088 D LocationProviderProxy: applying state to connected service
08-05 11:00:56.451  1032  1882 I ActivityManager: Killing 6400:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-05 11:00:56.457  1813  4659 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-05 11:00:56.458  7446  7489 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-05 11:00:56.463  7446  7489 W VideoCapabilities: Unsupported mime video/divx
,08-05 11:00:56.465  7446  7489 W VideoCapabilities: Unsupported mime video/divx311
08-05 11:00:56.467  7446  7489 W VideoCapabilities: Unsupported mime video/divx4
08-05 11:00:56.472  7446  7489 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-05 11:00:56.485  7446  7489 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 11:00:56.489  7446  7489 W AudioCapabilities: Unsupported mime audio/eac3
08-05 11:00:56.490  7446  7489 W AudioCapabilities: Unsupported mime audio/ac3
08-05 11:00:56.491  7446  7489 W AudioCapabilities: Unsupported mime audio/g726
08-05 11:00:56.492  7446  7489 W AudioCapabilities: Unsupported mime audio/wma-voice
08-05 11:00:56.492  7446  7489 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 11:00:56.493  7446  7489 W AudioCapabilities: Unsupported mime audio/adpcm
08-05 11:00:56.495  7446  7489 W VideoCapabilities: Unsupported mime video/theora
08-05 11:00:56.496  7446  7489 W VideoCapabilities: Unsupported mime video/mjpg
08-05 11:00:56.531  1032  1780 W libprocessgroup: failed to open /acct/uid_10026/pid_6400/cgroup.procs: No such file or directory
,08-05 11:00:56.567  1032  1534 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=11.5, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1508841335] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-05 11:00:56.569  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=11.5, 0.0, 0.0  rx=8.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1508841337] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 11:00:56.569  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 11:00:56.590  7498  7498 I AppUp4:AppBoxCP: onCreate
,08-05 11:00:56.591  7498  7498 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-05 11:00:56.597  7498  7498 I AppUp4:DB:  setFingerPrint start
08-05 11:00:56.597  7498  7498 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-05 11:00:56.603  7498  7498 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-05 11:00:56.603  7498  7498 I AppUp4:DB:  SDK version = 21
,08-05 11:00:56.603  7498  7498 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-05 11:00:56.604  7498  7498 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-05 11:00:56.611  7498  7498 I AppUp4:CustModeStarterReceiver: onReceive
08-05 11:00:56.655  7498  7498 D LgDataFeature: LgDataFeature() Constructor: none
08-05 11:00:56.655  7498  7498 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:00:56.664  7498  7498 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@45f44a9
08-05 11:00:56.664  7498  7498 D AppUp4:CustFacade: isCustomizationCompleted : false
08-05 11:00:56.664  7498  7498 D AppUp4:CustFacade: isPhone : true
08-05 11:00:56.664  7498  7498 D AppUp4:CustModeStarterReceiver: begin check event
08-05 11:00:56.665  7498  7498 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-05 11:00:56.720  1032  1973 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7518 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-05 11:00:56.730  1032  1973 I ActivityManager: Killing 7166:com.android.chrome/u0a57 (adj 15): empty #17
08-05 11:00:56.792  1032  1048 W libprocessgroup: failed to open /acct/uid_10057/pid_7166/cgroup.procs: No such file or directory
,08-05 11:00:56.815  7518  7518 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:00:56.815  7518  7518 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:00:56.816  7518  7518 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-05 11:00:56.817  7518  7518 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-05 11:00:56.817  7518  7518 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 11:00:56.893  7518  7518 I SystemConfig: BUILD Country: EU
08-05 11:00:56.893  7518  7518 I SystemConfig: BUILD Operator: OPEN
,08-05 11:00:56.946  1032  1900 I ActivityManager: Killing 7204:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-05 11:00:57.038  1032  2001 W libprocessgroup: failed to open /acct/uid_10062/pid_7204/cgroup.procs: No such file or directory
,08-05 11:00:57.060  7518  7538 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-05 11:00:57.060  7518  7538 I SystemConfig: existFile = false
08-05 11:00:57.060  7518  7538 I SystemConfig: canReadFile = false
08-05 11:00:57.060  7518  7538 I SystemConfig: systemFeature RCS result false
08-05 11:00:57.061  7518  7538 D SystemConfig: refreshRcsSupport() :false
,08-05 11:00:57.105  1032  1900 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7543 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-05 11:00:57.168  7543  7543 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
08-05 11:00:57.168  7543  7543 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 11:00:57.169  7543  7543 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 11:00:57.170  7543  7543 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-05 11:00:57.277  7543  7543 I AppConfig: Total System Memory = 2995761152
,08-05 11:00:57.300  7543  7543 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-05 11:00:57.389  1032  1049 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7562 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 11:00:57.394  1032  1049 I ActivityManager: Killing 7242:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-05 11:00:57.505  1032  1973 W libprocessgroup: failed to open /acct/uid_10093/pid_7242/cgroup.procs: No such file or directory
,08-05 11:00:57.722  7562  7562 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-05 11:00:57.826  7562  7562 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 11:00:57.826  7562  7562 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-05 11:00:57.890  7562  7562 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-05 11:00:57.909  7562  7562 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-05 11:00:57.910  7562  7562 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-05 11:00:57.927  7562  7562 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-05 11:00:57.927  7562  7562 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-05 11:00:57.960  1032  1936 I ActivityManager: Killing 7304:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-05 11:00:58.014  1032  2001 W libprocessgroup: failed to open /acct/uid_10097/pid_7304/cgroup.procs: No such file or directory
,08-05 11:00:58.027  4518  7599 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-05 11:00:58.028  3475  4399 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-05 11:00:58.036  3475  4399 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1c073654 on behalf of 7562
,08-05 11:00:58.070  1032  1954 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7600 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-05 11:00:58.108  7562  7562 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-05 11:00:58.140  7562  7562 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-05 11:00:58.159  7600  7600 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-05 11:00:58.182  7600  7600 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-05 11:00:58.182  7600  7600 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-05 11:00:58.182  7600  7600 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-05 11:00:58.182  7600  7600 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-05 11:00:58.182  7600  7600 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-05 11:00:58.182  7600  7600 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-05 11:00:58.230  1032  2001 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7631 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-05 11:00:58.231  1032  2001 I ActivityManager: Killing 7104:com.lge.email/u0a23 (adj 15): empty #17
,08-05 11:00:58.292  1032  1973 W libprocessgroup: failed to open /acct/uid_10023/pid_7104/cgroup.procs: No such file or directory
,08-05 11:00:58.353  7631  7631 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 11:00:58.520  1032  2009 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:00:58.543  4518  7599 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 513 ms] updated apps [took 513 ms] 
,08-05 11:00:59.577  1032  1534 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=6.8, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1508844344] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 11:00:59.587  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=6.8, 0.0, 0.0  rx=4.9 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1508844354] gl rssi=-43 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-05 11:00:59.587  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-05 11:00:59.658  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:00:59.658  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:00:59.659  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-05 11:00:59.668  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:00:59.674  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:00:59.675  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:00:59.677  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:00:59.679  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:01:00.055  1599  1599 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-05 11:01:00.055  1599  1599 I KeyguardUpdateMonitor: called onTimeUpdated()
08-05 11:01:00.055  1599  1599 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-05 11:01:00.056  1599  1599 I [SystemUI]Clock: called onTimeUpdated()
,08-05 11:01:00.070  1599  1599 I LgeClockWidgetControlView: called onTimeUpdated()
08-05 11:01:00.070  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:01:00.072  1599  1599 I [SystemUI]DateView: called onTimeUpdated()
08-05 11:01:00.074  1599  1599 D KeyguardUpdateMonitor: handleTimeUpdate
08-05 11:01:02.437  6201  6264 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-05 11:01:02.437  6201  6264 I jxcore-log: 
,08-05 11:01:02.611  1032  1534 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1508847379] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 11:01:02.612  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-43 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1508847380] gl rssi=-43 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-05 11:01:02.612  1032  1534 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-05 11:01:02.832  7671  7671 D AndroidRuntime: 
08-05 11:01:02.832  7671  7671 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 11:01:02.836  7671  7671 D AndroidRuntime: CheckJNI is OFF
08-05 11:01:03.055  7671  7671 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 11:01:03.069  1032  1089 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-05 11:01:03.070  1032  1089 I ActivityManager: Killing 6201:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-05 11:01:03.130  1032  2009 I WindowState: WIN DEATH: Window{39175628 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 11:01:03.134  1032  1539 D WifiService: Client connection lost with reason: 4
,08-05 11:01:03.142  1032  2009 D InputDispatcher: Window went away: Window{39175628 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-05 11:01:03.298  1032  1089 I ActivityManager:   Force finishing activity ActivityRecord{7c4cd9d u0 com.test.thalitest/.MainActivity t40}
,08-05 11:01:03.369   340   352 E GBMv2   : DFP En is all cleared set to be enabled
08-05 11:01:03.370  1032  1048 W ActivityManager: Spurious death for ProcessRecord{384dae2a 6201:com.test.thalitest/u0a118}, curProc for 6201: null
08-05 11:01:03.373  2029  2029 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-05 11:01:03.375  2029  2029 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-05 11:01:03.377  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-05 11:01:03.379  1032  1121 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-05 11:01:03.381  2029  2120 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-05 11:01:03.384  1032  1121 I ActivityManager:   Force finishing activity ActivityRecord{7c4cd9d u0 com.test.thalitest/.MainActivity t40 f}
08-05 11:01:03.385  1032  1121 W ActivityManager: Duplicate finish request for ActivityRecord{7c4cd9d u0 com.test.thalitest/.MainActivity t40 f}
08-05 11:01:03.400  1937  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-05 11:01:03.400  1937  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35c24575 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,08-05 11:01:03.402  1937  3886 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-05 11:01:03.403  1937  3886 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25f690a co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-05 11:01:03.406  1901  1901 D ActionManagerService: notifyUserLog: 1000003
08-05 11:01:03.407  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-05 11:01:03.412  1032  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 11:01:03.417  6796  6796 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-05 11:01:03.417  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-05 11:01:03.420  2029  2029 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-05 11:01:03.421  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-05 11:01:03.421  3698  3698 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-05 11:01:03.421  3698  4398 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-05 11:01:03.430  3730  3730 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-05 11:01:03.436  1032  1088 W InputMethodInfo: Duplicated subtype definition found: , voice
08-05 11:01:03.422  1991  1991 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-05 11:01:03.457  4518  4518 I art     : Explicit concurrent mark sweep GC freed 7936(461KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 546us total 67.345ms
,08-05 11:01:03.479  2029  2029 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-05 11:01:03.485  2493  2666 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 11:01:03.486  1599  1599 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-05 11:01:03.488  1813  1813 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-05 11:01:03.488  4412  4412 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-05 11:01:03.488  4412  4412 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-05 11:01:03.488  4412  4412 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-05 11:01:03.488  4412  4412 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-05 11:01:03.488  4412  4412 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 11:01:03.488  4412  4412 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 11:01:03.488  4412  4412 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 11:01:03.488  4412  4412 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 11:01:03.488  4412  4412 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:01:03.489  4412  4412 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 11:01:03.489  4412  4412 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 11:01:03.489  4412  4412 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 11:01:03.490  2029  2029 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-05 11:01:03.503  1901  1901 D ActionManagerService: notifyUserLog: 1000004
08-05 11:01:03.504  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-05 11:01:03.504  3698  4398 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-05 11:01:03.506  1599  1599 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-05 11:01:03.515  1599  1599 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-05 11:01:03.532  1032  1954 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:01:03.536  3698  3714 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 11:01:03.536  1032  1032 I art     : Explicit concurrent mark sweep GC freed 35139(1972KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.638ms total 138.956ms
08-05 11:01:03.549  1032  2009 V SIM_STK : Menu title from STK is T-Mobile
08-05 11:01:03.549  1032  2009 V SIM_STK : Menu title from STK is T-Mobile
,08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , create_time: 1430832262123
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , display: false
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , animation: false }
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , create_time: 1430832262287
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , display: false
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , animation: false }
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , create_time: 1469801565454
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , expire_time: 0
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , display: false
08-05 11:01:03.551  2029  2029 I GBoardWebViewUtils: , animation: false }
08-05 11:01:03.563  2029  7711 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-05 11:01:03.567  1599  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 11:01:03.567  1599  1655 D KeyguardModel: createShortcutInfo...
08-05 11:01:03.574  1032  1032 D administrator: Handling package changes for user 0
08-05 11:01:03.577  1599  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 11:01:03.577  1599  1655 D KeyguardModel: createShortcutInfo...
,08-05 11:01:03.578  1865  1865 D SplitUIManager: split_name #11 / not available #0
08-05 11:01:03.578  1865  1865 D SplitUIService: removed split : 
08-05 11:01:03.585  1599  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 11:01:03.586  1599  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:01:03.586  1599  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-05 11:01:03.587  1599  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 11:01:03.589  1599  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 11:01:03.590  1599  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 11:01:03.600  1599  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 11:01:03.600  1599  1655 D KeyguardModel: createShortcutInfo...
,08-05 11:01:03.605  1865  1865 D SplitUIManager: split_name #11 / not available #0
08-05 11:01:03.605  1865  1865 I SplitUIService: split app #11
08-05 11:01:03.605  1599  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-05 11:01:03.606  1599  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:01:03.608  1599  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 11:01:03.608  1599  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 11:01:03.613  1599  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 11:01:03.613  1599  1655 D KeyguardModel: createShortcutInfo...
,08-05 11:01:03.618  1599  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:01:03.618  1599  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-05 11:01:03.618  1599  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-05 11:01:03.618  1599  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 11:01:03.619  1599  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 11:01:03.619  1599  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 11:01:03.622  1032  1900 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-05 11:01:03.622  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-05 11:01:03.623  1599  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-05 11:01:03.623  1599  1655 D KeyguardModel: createShortcutInfo...
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-05 11:01:03.623  6796  6796 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-05 11:01:03.629  1599  1599 D KeyguardModel: handleShortcutListChanged...
08-05 11:01:03.629  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-05 11:01:03.641  1599  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-05 11:01:03.641  1599  1655 D KeyguardModel: createShortcutInfo...
08-05 11:01:03.647  1599  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-05 11:01:03.647  1599  1655 D KeyguardModel: createShortcutInfo...
,08-05 11:01:03.649  1599  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 11:01:03.649  1599  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-05 11:01:03.650  1599  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-05 11:01:03.650  1599  1655 D KeyguardModel: createShortcutInfo...
08-05 11:01:03.652  1599  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 11:01:03.652  1599  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-05 11:01:03.653  1599  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-05 11:01:03.653  1599  1655 D KeyguardModel: createShortcutInfo...
08-05 11:01:03.655  1599  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-05 11:01:03.655  1599  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-05 11:01:03.669  1599  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-05 11:01:03.669  1599  1655 D KeyguardModel: createShortcutInfo...
,08-05 11:01:03.680  1599  1599 D KeyguardModel: handleShortcutListChanged...
08-05 11:01:03.680  1599  1599 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-05 11:01:03.681  1032  1918 I art     : Explicit concurrent mark sweep GC freed 7230(398KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.669ms total 144.510ms
08-05 11:01:03.681  1032  1121 I art     : WaitForGcToComplete blocked for 131.359ms for cause Explicit
,08-05 11:01:03.704  1813  1813 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-05 11:01:03.706  2029  2029 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-05 11:01:03.707  1032  1049 V SIM_STK : Menu title from STK is T-Mobile
08-05 11:01:03.714  1032  2001 I ActivityManager: Killing 7366:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-05 11:01:03.716  2179  2179 I ConfigService: onCreate
08-05 11:01:03.717  2179  2179 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-05 11:01:03.729  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-05 11:01:03.729  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-05 11:01:03.730  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 11:01:03.733  2179  2179 I ConfigService: onBind returning update interface
08-05 11:01:03.766  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-05 11:01:03.790  1032  1048 W libprocessgroup: failed to open /acct/uid_1000/pid_7366/cgroup.procs: No such file or directory
,08-05 11:01:03.792  2179  2179 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-05 11:01:03.792  2179  2179 I ConfigService: onBind returning config service
08-05 11:01:03.794  2029  2029 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-05 11:01:03.795  1032  1573 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-05 11:01:03.795  2179  2179 I ConfigService: onDestroy
08-05 11:01:03.805  1813  7716 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-05 11:01:03.831  5503  7721 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-05 11:01:03.834  7498  7498 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-05 11:01:03.841  2351  7724 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-05 11:01:03.844  1813  7723 I PeopleContactsSync: CP2 sync disabled
08-05 11:01:03.854  1032  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:01:03.869  1032  2009 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7725 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-05 11:01:03.882  1813  4659 I Icing   : doRemovePackageData com.test.thalitest
,08-05 11:01:03.885  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-05 11:01:03.888  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 11:01:03.890  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-05 11:01:03.891  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-05 11:01:03.892  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-05 11:01:03.893  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-05 11:01:03.894  1813  7722 W GmsApplication: Using Auth Proxy for data requests.
08-05 11:01:03.901  1813  7722 W GmsApplication: Using Auth Proxy for data requests.
,08-05 11:01:03.907  1032  1116 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26651d47 u0 com.lge.launcher2/.Launcher t39} time:404227
08-05 11:01:03.909  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-05 11:01:03.909  2029  2151 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-05 11:01:03.909  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 11:01:03.909  2029  2151 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-05 11:01:03.910  7725  7725 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 11:01:03.910  7725  7725 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-05 11:01:03.911  7725  7725 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-05 11:01:03.911  7725  7725 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-05 11:01:03.913  1032  1121 I art     : Explicit concurrent mark sweep GC freed 9760(685KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 7.034ms total 226.772ms
,08-05 11:01:03.922  1032  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-05 11:01:03.925  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-05 11:01:03.926  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 11:01:03.927  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 11:01:03.929   334   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-05 11:01:03.930  3131  7745 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-05 11:01:03.934  2029  2029 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-05 11:01:03.935  2567  2567 D [Concierge]Service: onStartCommand(). Type : 8
08-05 11:01:03.935  2567  2567 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-05 11:01:03.937  2567  2567 D [Concierge]Service: Update widget ID : 11
,08-05 11:01:03.938  2029  2029 D [Concierge]WidgetView: change position of spinner
08-05 11:01:03.939  2029  2029 I [Concierge]WidgetView: initWebView(). Time : 1470387663939
08-05 11:01:03.939  2567  2567 D [Concierge]Service: onStartCommand(). Type : 0
08-05 11:01:03.972  7725  7725 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-05 11:01:03.977  2029  2029 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 703761634
08-05 11:01:03.978  2029  2029 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-05 11:01:03.978  2029  2029 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-05 11:01:03.979  7725  7725 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-05 11:01:03.980  2029  2029 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@cc0a62
08-05 11:01:03.980  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-05 11:01:03.981  2029  2029 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-05 11:01:03.982  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 11:01:03.986  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-05 11:01:03.987  2029  2029 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-05 11:01:03.987  2029  2029 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-05 11:01:03.988  2029  2029 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-05 11:01:03.988  2029  2029 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470387287646, New one : 1470387663939
08-05 11:01:03.988  2029  2029 D [Concierge]WidgetView: Unregister all receivers
08-05 11:01:03.988  2029  2029 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-05 11:01:03.989  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 11:01:03.991  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-05 11:01:03.992  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-05 11:01:03.993  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-05 11:01:03.994  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-05 11:01:03.995  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-05 11:01:03.998  7671  7671 D AndroidRuntime: Shutting down VM
08-05 11:01:03.998  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-05 11:01:03.998  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 11:01:04.009  7725  7725 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-05 11:01:04.029  1032  1121 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7749 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-05 11:01:04.029  2029  2029 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-05 11:01:04.037  2029  2029 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-05 11:01:04.037  2029  2029 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-05 11:01:04.038  2029  2029 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-05 11:01:04.059  2029  2029 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ea2e04c time:404379
08-05 11:01:04.064  7725  7725 D LgDataFeature: LgDataFeature() Constructor: none
,08-05 11:01:04.065  7725  7725 D LgDataFeature: LgDataFeature() Constructor Done, null
08-05 11:01:04.078  1032  1973 I ActivityManager: Killing 6079:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-05 11:01:04.087  6356  6356 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-05 11:01:04.087  6356  6356 W System.err: android.os.DeadObjectException
08-05 11:01:04.087  6356  6356 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 11:01:04.087  6356  6356 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 11:01:04.087  6356  6356 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-05 11:01:04.087  6356  6356 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-05 11:01:04.087  6356  6356 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 11:01:04.087  6356  6356 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 11:01:04.087  6356  6356 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 11:01:04.087  6356  6356 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 11:01:04.087  6356  6356 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 11:01:04.087  6356  6356 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 11:01:04.087  6356  6356 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-05 11:01:04.087  6356  6356 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 11:01:04.087  6356  6356 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 11:01:04.087  6356  6356 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 11:01:04.088  6356  6356 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-05 11:01:04.088  6356  6356 W System.err: android.os.DeadObjectException
08-05 11:01:04.088  6356  6356 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 11:01:04.088  6356  6356 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 11:01:04.088  6356  6356 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-05 11:01:04.088  6356  6356 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-05 11:01:04.088  6356  6356 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-05 11:01:04.088  6356  6356 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-05 11:01:04.088  6356  6356 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 11:01:04.088  6356  6356 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 11:01:04.088  6356  6356 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-05 11:01:04.088  6356  6356 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-05 11:01:04.088  6356  6356 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:01:04.088  6356  6356 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 11:01:04.088  6356  6356 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-05 11:01:04.088  6356  6356 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-05 11:01:04.088  6356  6356 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-05 11:01:04.088  6356  6356 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-05 11:01:04.183  2029  2029 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-05 11:01:04.211  1032  1534 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-05 11:01:04.211  1032  1534 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 11:01:04.212  1032  1534 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 11:01:04.212  1032  1534 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 11:01:04.212  1032  1534 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 11:01:04.212  1032  1534 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-05 11:01:04.218  2029  2854 I GBoardtInterface: onReloaded()
08-05 11:01:04.219  2029  2029 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-05 11:01:04.287  1032  2028 W libprocessgroup: failed to open /acct/uid_1000/pid_6079/cgroup.procs: No such file or directory
,08-05 11:01:04.287  1032  2028 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-05 11:01:04.291  6356  6356 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-05 11:01:04.291  6356  6356 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-05 11:01:04.291  3698  3714 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 11:01:04.312  1032  1594 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7774 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-05 11:01:04.313  6356  6356 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-05 11:01:04.314  3698  4160 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 11:01:04.321  1901  1901 D ActionManagerService: notifyUserLog: 1000001
08-05 11:01:04.322  3698  4398 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-05 11:01:04.322  3698  4398 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 11:01:04.323   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 201us total 9.201ms
08-05 11:01:04.325  1901  1901 D ActionManagerService: notifyUserLog: 1000001
08-05 11:01:04.327  3698  4398 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-05 11:01:04.327  3698  4398 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-05 11:01:04.327  3698  4398 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-05 11:01:04.327  3698  4398 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-05 11:01:04.328  4412  4463 E SQLiteLog: (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
08-05 11:01:04.329  3698  3714 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-05 11:01:04.331  2029  2029 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-05 11:01:04.331  2029  2029 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-05 11:01:04.333   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 9.188ms
08-05 11:01:04.333  2029  2029 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-05 11:01:04.333  2029  2029 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-05 11:01:04.336  2029  2029 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-05 11:01:04.336  2029  2029 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: Error inserting f004=14 f005=7774 f002=1470387664325 f003=com.uei.lg.quicksetsdk.maxq616 f006=1000
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at com.lge,.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-05 11:01:04.336  4412  4463 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
,08-05 11:01:04.342   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 181us total 8.780ms
,08-05 11:01:04.364  7725  7725 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)

```
