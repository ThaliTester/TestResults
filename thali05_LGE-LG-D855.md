#### Test 796897753515520_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-08 11:22:57.431  1025  3503 I LocationManagerService: remove d00c53a
08-08 11:22:57.432  1025  3503 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-08 11:22:57.433  1025  3503 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-08 11:22:57.434  1025  3503 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-08 11:22:57.436  1025  3503 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-08 11:22:57.436  1025  3503 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-08 11:22:57.739  5972  5972 D AndroidRuntime: 
08-08 11:22:57.739  5972  5972 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-08 11:22:57.743  5972  5972 D AndroidRuntime: CheckJNI is OFF
08-08 11:22:57.872  5972  5972 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-08 11:22:57.884  1025  2618 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-08 11:22:57.895  1937  3766 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-08 11:22:57.898  1025  2618 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-08 11:22:57.900  1025  2618 D ActivityManager: setTaskToReturnTo : TaskRecord{832e033 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-08 11:22:57.900  1025  2618 D ActivityManager: setTaskToReturnTo : TaskRecord{832e033 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-08 11:22:57.901  1025  2618 D WindowStateEx: AppWindowTokenEx init.. 
08-08 11:22:57.902   334   379 E GBMv2   : DFP En is all cleared set to be enabled
08-08 11:22:57.937  1025  2618 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5992 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-08 11:22:57.939  5972  5972 D AndroidRuntime: Shutting down VM
08-08 11:22:57.985  1937  1954 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-08 11:22:57.985  1937  1954 D SplitWindowPolicy: topRunningActivity=ActivityInfo{ab9f29d co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-08 11:22:57.986  1937  1953 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-08 11:22:57.986  1937  1953 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3b865312 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-08 11:22:58.135  1025  1977 I art     : Explicit concurrent mark sweep GC freed 27140(1314KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.185ms total 143.185ms
,08-08 11:22:58.198  5992  5992 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-08 11:22:58.264  5992  5992 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-08 11:22:58.272  5992  5992 I LibraryLoader: Loading: webviewchromium
08-08 11:22:58.274  5992  5992 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6452-6455)
08-08 11:22:58.275  5992  5992 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 11:22:58.286  5992  5992 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39609c9a}
,08-08 11:22:58.287  5992  5992 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 11:22:58.288  5992  5992 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-08 11:22:58.294  5992  5992 I BrowserStartupController: Initializing chromium process, renderers=0
08-08 11:22:58.295  5992  5992 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 11:22:58.301  5992  6012 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,08-08 11:22:58.305  5992  5992 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-08 11:22:58.305  5992  5992 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-08 11:22:58.306  5992  5992 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-08 11:22:58.308   313  1377 V AudioPolicyService: registerClient() client 0xb1019500, uid 10118
08-08 11:22:58.316  5992  5992 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-08 11:22:58.316  5992  5992 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-08 11:22:58.316  5992  5992 I Adreno-EGL: Build Date: 12/12/14 금
08-08 11:22:58.316  5992  5992 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-08 11:22:58.316  5992  5992 I Adreno-EGL: Remote Branch: 
08-08 11:22:58.316  5992  5992 I Adreno-EGL: Local Patches: 
08-08 11:22:58.316  5992  5992 I Adreno-EGL: Reconstruct Branch: 
08-08 11:22:58.317  1025  1087 D BluetoothManagerService: Message: 20
08-08 11:22:58.318  1025  1087 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3aa08325:true
08-08 11:22:58.318  5992  6016 D BluetoothAdapter: 385206731: getState() :  mService = null. Returning STATE_OFF
,08-08 11:22:58.381  5992  6022 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-08 11:22:58.384  5992  5992 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-08 11:22:58.399  5992  5992 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-08 11:22:58.404  5992  5992 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-08 11:22:58.407  5992  5992 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-08 11:22:58.411  5992  5992 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-08 11:22:58.411  5992  5992 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-08 11:22:58.426  5992  5992 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-08 11:22:58.432  5992  5992 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 11:22:58.432  5992  5992 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-08 11:22:58.470  5992  6034 D OpenGLRenderer: Render dirty regions requested: true
08-08 11:22:58.470  5992  6034 I OpenGLRenderer: Initialized EGL, version 1.4
08-08 11:22:58.479  5992  6034 D OpenGLRenderer: Enabling debug mode 0
08-08 11:22:58.485  1025  1082 W ActivityManager: Activity pause timeout for ActivityRecord{186b2ff0 u0 com.test.thalitest/.MainActivity t40}
,08-08 11:22:58.490  5992  5992 D Atlas   : Validating map...
08-08 11:22:58.495  1025  1641 D SplitWindow: check instance of lgWin Window{19abd777 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-08 11:22:58.554  1025  1088 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +570ms (total +652ms)
08-08 11:22:58.555  1025  1088 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{186b2ff0 u0 com.test.thalitest/.MainActivity t40} time:336735
,08-08 11:22:58.566  5992  6032 D LgDataFeature: LgDataFeature() Constructor: none
08-08 11:22:58.567  5992  6032 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-08 11:22:58.573  5992  5992 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b653716 time:336754
08-08 11:22:58.740  5992  5992 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-08 11:22:58.831  5992  6032 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-08 11:22:58.831  5992  6032 I chromium: 
,08-08 11:22:58.974  5992  6044 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435149312
,08-08 11:22:58.991  5992  6044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-08 11:22:58.991  5992  6044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-08 11:22:58.991  5992  6044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-08 11:22:58.991  5992  6044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-08 11:22:58.991  5992  6044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-08 11:22:58.991  5992  6044 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc26ffa added. We now have 1 listener(s)
,08-08 11:22:58.997  5992  5992 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-08 11:22:58.997  5992  5992 I chromium: 
08-08 11:22:59.001  1025  1912 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:22:59.003  5992  6044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-08 11:22:59.006  5992  6044 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-08 11:22:59.008  5992  6044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 11:22:59.008  5992  6044 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-08 11:22:59.016  5992  6044 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ecaeba1 added. We now have 1 listener(s)
08-08 11:22:59.018  5992  6044 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:22:59.022  1025  1536 D WifiService: New client listening to asynchronous messages
08-08 11:22:59.027  5992  6044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 11:22:59.027  5992  6044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-08 11:22:59.029  5992  6044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-08 11:22:59.029  5992  6044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-08 11:22:59.029  5992  6044 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-08 11:22:59.032  5992  6044 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:22:59.032  1025  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:22:59.032  5992  6044 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-08 11:22:59.039  5992  6044 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:22:59.039  5992  6044 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:22:59.039  5992  6044 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:22:59.039  5992  6044 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:22:59.039  5992  6044 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:22:59.039  5992  6044 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:22:59.039  5992  6044 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:22:59.039  5992  6044 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:22:59.039  5992  6044 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:22:59.039  5992  6044 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-08 11:22:59.039  5992  6044 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 11:22:59.040  5992  6044 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-08 11:22:59.081  5992  5992 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-08 11:22:59.849   334   381 E GBMv2   : DFP En is all cleared set to be enabled
08-08 11:22:59.850   334   381 E GBMv2   : Set value is all cleared set the max
08-08 11:22:59.850   334   381 I GBMv2   : DFP Enabled. Ignore VFP set
,08-08 11:23:00.045  5992  6047 W jxcore-log: Initializing JXcore engine
08-08 11:23:00.045  5992  6047 W jxcore-log: JXcore engine is ready
,08-08 11:23:00.049  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:23:00.049  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:23:00.049  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:23:00.049  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
08-08 11:23:00.050  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:23:00.050  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:23:00.050  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:23:00.051  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:23:00.069  6047  6047 W Thread-672: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9901]" dev="sockfs" ino=9901 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-08 11:23:00.069  6047  6047 W Thread-672: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-08 11:23:00.069  6047  6047 W Thread-672: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7489]" dev="sockfs" ino=7489 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-08 11:23:00.069  6047  6047 W Thread-672: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-08 11:23:00.069  6047  6047 W Thread-672: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29237]" dev="sockfs" ino=29237 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-08 11:23:00.099  5992  6047 W jxcore-log: Starting JXcore engine
08-08 11:23:00.178  5992  6047 W jxcore-log: Platform android
08-08 11:23:00.178  5992  6047 W jxcore-log: 
08-08 11:23:00.178  5992  6047 W jxcore-log: Process ARCH arm
08-08 11:23:00.178  5992  6047 W jxcore-log: 
,08-08 11:23:00.405  5992  6047 I jxcore-log: JXcore Cordova bridge is ready!
08-08 11:23:00.405  5992  6047 I jxcore-log: 
08-08 11:23:00.405  5992  6047 W jxcore-log: JXcore engine is started
,08-08 11:23:00.414  5992  6044 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-08 11:23:00.419  5992  5992 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-08 11:23:06.751  1025  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=235384520, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-08 11:23:06.790  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,08-08 11:23:06.828  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=235384520 [*alarm*], flags=0x0
,08-08 11:23:16.176  5992  6047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-08 11:23:16.176  5992  6047 I jxcore-log: 
08-08 11:23:16.178  5992  6047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-08 11:23:16.178  5992  6047 I jxcore-log: 
,08-08 11:23:16.182  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:23:16.182  5992  6047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:23:16.182  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:16.182  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:23:16.182  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:23:16.182  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:16.182  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:16.182  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:16.182  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:16.183  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.183  5992  6047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:16.186  5992  6047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-08 11:23:16.186  5992  6047 I jxcore-log: 
08-08 11:23:16.188  5992  6047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-08 11:23:16.188  5992  6047 I jxcore-log: 
08-08 11:23:16.517  5992  6047 D ExecuteNativeTests: Running unit tests
,08-08 11:23:16.605  5992  6047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-08 11:23:16.605  5992  6047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 added. We now have 2 listener(s)
08-08 11:23:16.605  1025  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-08 11:23:16.606  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-08 11:23:16.606  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 11:23:16.606  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 11:23:16.606  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:23:16.606  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba added. We now have 2 listener(s)
08-08 11:23:16.606  5992  6047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:23:16.607  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 11:23:16.608  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:23:16.608  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.608  5992  6047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:23:16.608  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:16.608  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:23:16.608  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:23:16.608  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:16.608  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:16.608  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:16.608  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:16.608  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.609  5992  6047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:16.609  5992  6047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 11:23:16.612  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 11:23:16.612  5992  6047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 11:23:16.612  5992  6047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 11:23:16.614  5992  6047 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-08 11:23:16.614  5992  6047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-08 11:23:16.614  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 11:23:16.615  5992  6047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-,08 11:23:16.615  5992  6047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 11:23:16.615  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.616  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.616  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.617  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.617  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.617  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:23:16.617  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 11:23:16.617  5992  6047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 removed from the list
08-08 11:23:16.617  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-08 11:23:16.617  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba removed from the list
08-08 11:23:16.617  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 11:23:16.617  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.618  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.618  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.619  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-08 11:23:16.619  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.619  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 11:23:16.620  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.621  5992  6047 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-08 11:23:16.622  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.622  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.622  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.622  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.622  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.622  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.622  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.622  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.622  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.622  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.622  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.622  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.622  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.622  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.623  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.623  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.623  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.623  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.628  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-08 11:23:16.628  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-08 11:23:16.628  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 11:23:16.628  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 11:23:16.629  5992  6047 D ,io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-08 11:23:16.629  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 11:23:16.630  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-08 11:23:16.630  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 11:23:16.630  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 11:23:16.630  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-08 11:23:16.630  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 11:23:16.630  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-08 11:23:16.630  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 11:23:16.630  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.630  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.630  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 11:23:16.630  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.630  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.631  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.631  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.631  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.631  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.631  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.631  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.631  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.631  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.632  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.632  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.632  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.632  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.632  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.633  5992  6047 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 11:23:16.633  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:23:16.634  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.634  5992  6047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:23:16.634  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:16.634  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:23:16.634  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:23:16.634  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:16.634  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:16.634  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:16.634  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:16.634  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.634  5992  6047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:16.634  5992  6047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 11:23:16.634  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity:, NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 11:23:16.634  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 11:23:16.635  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 11:23:16.635  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:23:16.635  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 11:23:16.636  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 11:23:16.636  5992  6047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 11:23:16.637  5992  5992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 11:23:16.637  5992  6047 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-08 11:23:16.638  5992  6047 I io.jxcore.node.ConnectionHelper: start: OK
08-08 11:23:16.639  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.639  5992  6047 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-08 11:23:16.641  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.641  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.641  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-08 11:23:16.641  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.641  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 11:23:16.641  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 11:23:16.641  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 11:23:16.642  5992  6047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 11:23:16.642  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-08 11:23:16.643  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 11:23:16.643  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:23:16.643  5992  6047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:23:16.644  5992  5992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:23:16.644  5992  5992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:23:16.644  5992  5992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:23:16.644  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.644  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.644  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:23:16.644  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.644  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.644  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.644  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.644  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.645  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.645  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.645  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.645  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.645  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.645  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.646  5992  6047 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 11:23:16.647  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:23:16.647  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.647  5992  6047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:23:16.647  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:16.647  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:23:16.647  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:23:16.647  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:16.647  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:16.647  5992  6047 V io.jxcore.node.Connect,ivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:16.647  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:16.647  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.647  5992  6047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:16.648  5992  6047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 11:23:16.648  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 11:23:16.648  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 11:23:16.648  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 11:23:16.648  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:23:16.648  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 11:23:16.649  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 11:23:16.649  5992  6047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 11:23:16.649  5992  5992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 11:23:16.649  5992  6047 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-08 11:23:16.649  5992  6047 I io.jxcore.node.ConnectionHelper: start: OK
08-08 11:23:16.649  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.649  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.649  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-08 11:23:16.649  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.649  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 11:23:16.649  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 11:23:16.649  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 11:23:16.649  5992  6047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 11:23:16.649  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 11:23:16.650  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 11:23:16.650  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:23:16.650  5992  6047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:23:16.650  5992  5992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:23:16.650  5992  5992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:23:16.650  5992  5992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:23:16.651  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.651  5992  6047 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-08 11:23:16.651  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.651  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.652  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.652  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.652  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:23:16.652  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.652  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.652  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.652  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.652  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.652  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.652  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.652  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.652  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.652  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.652  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.653  5992  6047 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-08 11:23:16.653  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.653  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.653  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.653  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.653  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.653  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.653  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.653  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.654  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.654  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.654  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.654  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.654  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.654  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.655  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.655  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.655  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.655  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.656  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 11:23:16.656  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.656  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.656  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.656  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.656  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.656  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.656  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.656  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.656  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.656  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.656  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.656  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.656  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.656  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.657  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.657  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.657  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.657  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.658  5992  6047 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-08 11:23:16.658  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.658  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.658  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.658  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.658  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.658  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.658  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.658  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.658  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.658  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.658  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.658  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.658  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.658  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.659  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.659  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.659  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.659  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.660  5992  6047 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-08 11:23:16.660  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.660  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.660  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.660  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.660  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.660  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.660  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.660  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.660  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.660  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.660  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.660  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.660  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.660  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.661  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.661  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.661  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.661  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.661  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 11:23:16.662  5992  6047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 11:23:16.662  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 11:23:16.662  5992  6047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 11:23:16.663  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 11:23:16.663  5992  6047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 11:23:16.663  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.663  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.663  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.663  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.663  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.663  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.663  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.663  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.663  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.663  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.663  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.663  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.663  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.663  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.664  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.664  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.664  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.664  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.664  5992  6047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:23:16.664  5992  6047 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 11:23:16.664  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-08 11:23:16.666  5992  6047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:23:16.666  5992  6047 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-08 11:23:16.666  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-08 11:23:16.667  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 11:23:16.667  5992  6047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-08 11:23:16.667  5992  6047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 11:23:16.667  5992  6047 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-08 11:23:16.667  5992  6047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:23:16.667  5992  6047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 11:23:16.667  5992  6047 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-08 11:23:16.667  5992  6047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:23:16.667  5992  6047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 11:23:16.667  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-08 11:23:16.668  5992  6047 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-08 11:23:16.669  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-08 11:23:16.672  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-08 11:23:16.672  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-08 11:23:16.674  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-08 11:23:16.674  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-08 11:23:16.674  5992  6047 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-08 11:23:16.674  5992  6047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:23:16.674  5992  6047 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-08 11:23:16.674  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.674  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.674  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.675  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.675  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.675  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.675  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-08 11:23:16.675  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.675  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.675  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.675  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.675  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.675  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.675  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.675  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.680  5992  6054 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 736)
,08-08 11:23:16.682  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.682  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.682  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.682  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.682  5992  6055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 736
08-08 11:23:16.682  5992  6055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 736)
08-08 11:23:16.682  5992  6055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 736)
08-08 11:23:16.683  5992  6047 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-08 11:23:16.683  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.683  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.683  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.683  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.683  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.683  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.683  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.683  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.683  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.683  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.684  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.684  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.684  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.684  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.689  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.689  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.689  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.690  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.692  5992  6047 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-08 11:23:16.692  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.692  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.692  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.692  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.692  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.692  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.692  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.692  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.693  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.693  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.693  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.693  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.693  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.693  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.697  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.697  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.697  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.697  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.699  5992  6047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-08 11:23:16.699  5992  6047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-08 11:23:16.700  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 11:23:16.700  5992  6047 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-08 11:23:16.700  5992  6047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 11:23:16.701  5992  6047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-08 11:23:16.701  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 11:23:16.701  5992  6047 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-08 11:23:16.701  5992  6047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 11:23:16.701  5992  6047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 11:23:16.701  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 11:23:16.701  5992  6047 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-08 11:23:16.702  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.702  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.702  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.703  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.703  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.703  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.703  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.703  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.703  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.703  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.703  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.703  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.703  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.703  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.704  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.704  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.704  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.704  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.706  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.706  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.706  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.706  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.706  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.706  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.707  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.707  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.707  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.707  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.708  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.708  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.708  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.708  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.708  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.708  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.708  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.708  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.710  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.711  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.711  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.711  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.711  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.711  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.711  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.711  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.711  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.711  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.711  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.712  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.712  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.712  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.712  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.713  5992  6047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-08 11:23:16.713  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:23:16.713  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-08 11:23:16.713  5992  6047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 11:23:16.713  5992  5992 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 11:23:16.714  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 11:23:16.714  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.714  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-08 11:23:16.714  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.714  5992  6047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-08 11:23:16.714  5992  5992 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-08 11:23:16.714  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.714  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.714  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 11:23:16.714  5992  6047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 11:23:16.714  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 11:23:16.715  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.716  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.716  5992  6047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:23:16.716  5992  5992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:23:16.716  5992  5992 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:23:16.716  5992  5992 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:23:16.716  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.716  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.716  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.716  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.716  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.716  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.716  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.716  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.716  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.716  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.716  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.716  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.716  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.717  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.717  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.717  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.717  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.717  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.717  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.717  5992  6047 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-08 11:23:16.718  5992  6047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-08 11:23:16.718  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 11:23:16.718  5992  6047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 11:23:16.718  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.718  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.718  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.718  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.718  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.718  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.718  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.718  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.718  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.718  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.718  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.718  5992  6047 D org.thaliproject.p,2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.718  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.718  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.718  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.718  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.718  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.718  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.719  1025  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:16.719  1025  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:16.720  1025  1955 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:16.720  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.720  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.720  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.720  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.720  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.720  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.720  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.720  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.720  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.720  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.720  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.720  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.720  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.720  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.720  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.720  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.720  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 11:23:16.720  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.721  5992  6047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:23:16.728  5992  6047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:23:16.728  5992  6047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:23:16.728  5992  6047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:23:16.728  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.728  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.728  5992  6047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9ef2e5 not in the list
08-08 11:23:16.728  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.729  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.729  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:16.729  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.729  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.729  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:23:16.729  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:23:16.729  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:23:16.729  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:23:16.729  5992  6047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:23:16.729  5992  6047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fcd61ba not in the list
08-08 11:23:16.730  5992  6047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-08 11:23:16.730  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 11:23:16.731  5992  6047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-08 11:23:16.731  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 11:23:16.731  5992  6047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-08 11:23:16.731  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 11:23:16.732  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 11:23:16.732  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-08 11:23:16.733  5992  6047 I io.jxcore.node.ConnectionModel: closeAndRemoveIncom,ingConnectionThread: Closing and removing incoming connection thread with ID 1
08-08 11:23:16.733  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 11:23:16.733  5992  6047 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-08 11:23:16.733  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 11:23:16.733  5992  6047 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-08 11:23:16.733  5992  6047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-08 11:23:16.733  5992  6047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-08 11:23:16.733  5992  6047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-08 11:23:16.734  5992  6047 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-08 11:23:16.734  5992  6047 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-08 11:23:16.734  5992  6047 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-08 11:23:16.734  5992  6047 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-08 11:23:16.735  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:23:16.735  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16f16074 added. We now have 2 listener(s)
08-08 11:23:16.735  5992  6047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:23:16.736  1025  1640 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:16.736  1025  1640 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-08 11:23:16.743  1025  1087 D BluetoothManagerService: Message: 1
08-08 11:23:16.744  1025  1087 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-08 11:23:16.746  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-08 11:23:16.746  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-08 11:23:16.747  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-08 11:23:16.777  1025  1087 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6063 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-08 11:23:16.778  1025  1977 D WifiServiceImplEx: setWifiEnabled: true pid=5992, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-08 11:23:16.778  1025  1977 D WifiService: setWifiEnabled: true pid=5992, uid=10118
08-08 11:23:16.779  1025  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 11:23:16.787  5992  6054 E BluetoothDevice: BT not enabled. Cannot get bond state
08-08 11:23:16.787  5992  6054 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-08 11:23:16.787  5992  6054 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 736)
08-08 11:23:16.791  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-08 11:23:16.792  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-08 11:23:16.793  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-08 11:23:16.793  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:23:16.793  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1de1999d added. We now have 3 listener(s)
08-08 11:23:16.793  5992  6047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:23:16.793  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.793  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.793  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:23:16.793  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@224a6e12 added. We now have 4 listener(s)
08-08 11:23:16.794  5992  6047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:23:16.794  1025  1531 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-08 11:23:16.794  1025  1531 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-08 11:23:16.794  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:23:16.794  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b2689e3 added. We now have 5 listener(s)
08-08 11:23:16.794  5992  6047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:23:16.795  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-08 11:23:16.795  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-08 11:23:16.795  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-08 11:23:16.795  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-08 11:23:16.795  1025  1531 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-08 11:23:16.795  1025  1531 E WifiHW  : unknown target_country: EU , set to default
08-08 11:23:16.795  1025  2028 D WifiServiceImplEx: setWifiEnabled: true pid=5992, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-08 11:23:16.795  1025  1531 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-08 11:23:16.795  1025  1531 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-08 11:23:16.795  1025  1531 I WifiUtil: gEnableBmps=1
08-08 11:23:16.796  1025  2028 D WifiService: setWifiEnabled: true pid=5992, uid=10118
08-08 11:23:16.796  1025  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-08 11:23:16.796  1025  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:16.796  1025  1641 D BluetoothManagerService: enable():  mBluetooth =null mBinding = true
08-08 11:23:16.796  1025  1087 D BluetoothManagerService: Message: 1
08-08 11:23:16.796  1025  1087 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-08 11:23:16.797  5992  6047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:23:16.797  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bl,uetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.797  5992  6047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:23:16.797  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:16.797  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:23:16.797  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:23:16.797  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:16.797  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:16.797  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:16.797  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:16.797  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:16.798  5992  6047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:16.798  1025  1536 D WifiController: Mismatch in the state 1
08-08 11:23:16.798  5992  6047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-08 11:23:16.840  6063  6063 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-08 11:23:16.841  6063  6063 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-08 11:23:16.841  6063  6063 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-08 11:23:16.841  6063  6063 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-08 11:23:16.861  6063  6063 D BluetoothAdapterApp: Loading JNI Library
,08-08 11:23:16.889  6063  6063 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1cb92490 Instance Count = 1
,08-08 11:23:16.896  6063  6063 D BluetoothAdapterApp: onCreate
08-08 11:23:16.917  6063  6063 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-08 11:23:16.917  6063  6063 D ProfileConfigQcom: Adding HeadsetService
08-08 11:23:16.917  6063  6063 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-08 11:23:16.917  6063  6063 D ProfileConfigQcom: Adding A2dpService
08-08 11:23:16.917  6063  6063 D ProfileConfigQcom: [BTUI] HidService is supported
08-08 11:23:16.918  6063  6063 D ProfileConfigQcom: Adding HidService
08-08 11:23:16.918  6063  6063 D ProfileConfigQcom: [BTUI] HealthService is supported
08-08 11:23:16.918  6063  6063 D ProfileConfigQcom: Adding HealthService
08-08 11:23:16.918  6063  6063 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-08 11:23:16.919  6063  6063 D ProfileConfigQcom: [BTUI] PanService is supported
08-08 11:23:16.919  6063  6063 D ProfileConfigQcom: Adding PanService
08-08 11:23:16.919  6063  6063 D ProfileConfigQcom: [BTUI] GattService is supported
08-08 11:23:16.919  6063  6063 D ProfileConfigQcom: Adding GattService
08-08 11:23:16.919  6063  6063 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-08 11:23:16.919  6063  6063 D ProfileConfigQcom: Adding BluetoothMapService
08-08 11:23:16.919  6063  6063 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-08 11:23:16.941  1025  1087 D BluetoothManagerService: Message: 20
08-08 11:23:16.942  1025  1087 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f547044:true
08-08 11:23:16.942  6063  6063 D BluetoothAdapterState: make
,08-08 11:23:16.947  6063  6063 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-08 11:23:16.947  6063  6063 I bluedroid-qcom: init
08-08 11:23:16.948  6063  6094 I BluetoothAdapterState: Entering OffState
08-08 11:23:16.951  6063  6063 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-08 11:23:16.952  6063  6063 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-08 11:23:16.953  6063  6063 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-08 11:23:16.953  6063  6063 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-08 11:23:16.953  6063  6063 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-08 11:23:16.957  6063  6063 I bluedroid-qcom: get_profile_interface socket
08-08 11:23:16.957  6063  6098 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-08 11:23:16.957  6063  6063 I bluedroid-qcom: get_profile_interface map_client
08-08 11:23:16.949  6097  6097 W bdaddr_loader: type=1400 audit(0.0:153): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:16.949  6097  6097 W bdaddr_loader: type=1400 audit(0.0:154): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:16.965  6097  6097 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
,08-08 11:23:16.965  6097  6097 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-08 11:23:16.965  6097  6097 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-08 11:23:16.965  6063  6098 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-08 11:23:16.965  6097  6097 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-08 11:23:16.966  1025  1025 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-08 11:23:16.966  1025  1087 D BluetoothManagerService: Message: 40
08-08 11:23:16.966  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-08 11:23:16.968  6097  6097 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-08 11:23:16.968  6097  6097 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-08 11:23:16.973  6063  6098 D BluetoothAdapterProperties: Name is: G3
08-08 11:23:16.974  1025  1025 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-08 11:23:16.974  1025  1025 D BluetoothManagerService: Stored Bluetooth name: G3
08-08 11:23:16.979  6063  6085 I bluedroid-qcom: config_hci_snoop_log
08-08 11:23:16.981  1025  1087 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-08 11:23:16.981  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
,08-08 11:23:16.991  6063  6086 V LGMDMManagerInternal: Create singleton instance
08-08 11:23:16.993   309   899 D SoftapController: Softap fwReload - Ok
,08-08 11:23:16.995   309   899 D CommandListener: Setting iface cfg
08-08 11:23:16.995   309   899 D CommandListener: Trying to bring down wlan0
08-08 11:23:16.995   309   899 D CommandListener: Clearing all IP addresses on wlan0
08-08 11:23:17.000  1025  1531 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-08 11:23:17.001  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-08 11:23:17.001  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-08 11:23:17.001  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-08 11:23:17.002  1025  1531 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-08 11:23:17.002  1025  1531 D WifiMonitor: connecting to supplicant
08-08 11:23:17.005  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:17.005  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-08 11:23:17.006  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:23:17.006  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:16.989  6100  6100 W wpa_supplicant: type=1400 audit(0.0:155): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:16.989  6100  6100 W wpa_supplicant: type=1400 audit(0.0:156): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:17.020  6100  6100 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-08 11:23:17.036  6100  6100 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-08 11:23:17.036  6100  6100 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-08 11:23:17.054  1025  1082 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6102 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-08 11:23:17.055  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-08 11:23:17.069   338   338 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 219us total 12.752ms
,08-08 11:23:17.080   338   338 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 9.722ms
08-08 11:23:17.090   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 197us total 9.527ms
,08-08 11:23:17.097  6063  6094 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-08 11:23:17.097  6063  6094 D BluetoothAdapterProperties: Setting state to 11
08-08 11:23:17.098  6063  6094 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-08 11:23:17.098  1025  1087 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-08 11:23:17.098  1025  1087 D Tethering: InitialState.processMessage what=4
08-08 11:23:17.098  6063  6094 I LGBluetoothServiceJni: classInitNative: succeeds
08-08 11:23:17.099  1025  1087 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-08 11:23:17.099  1025  1087 D BluetoothManagerService: Message: 60
08-08 11:23:17.099  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-08 11:23:17.099  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-08 11:23:17.101   309  6119 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-08 11:23:17.102  1025  1085 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-08 11:23:17.102  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-08 11:23:17.102  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-08 11:23:17.105  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:17.105  6100  6100 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-08 11:23:17.106  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:17.138  1025  1082 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6120 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-08 11:23:17.140  6063  6094 D BluetoothBondStateMachine: make
08-08 11:23:17.144  6063  6094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.144  6063  6094 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-08 11:23:17.144  6063  6094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.144  6063  6094 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-08 11:23:17.144  6063  6094 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-08 11:23:17.145  6063  6129 I BluetoothBondStateMachine: StableState(): Entering Off State
08-08 11:23:17.151  6063  6094 E BluetoothAdapterService: File transfer profiles supported!!
,08-08 11:23:17.161  6100  6100 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-08 11:23:17.167  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-08 11:23:17.167  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-08 11:23:17.167  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-08 11:23:17.168  1025  1531 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-08 11:23:17.168  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_SUPPLICANT 0 0
08-08 11:23:17.168  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:17.170  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:17.170  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:17.170  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:17.170  1025  1531 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-08 11:23:17.171  1025  1531 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-08 11:23:17.171  1025  1531 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-08 11:23:17.171  1025  1531 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-08 11:23:17.171  1025  1531 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-08 11:23:17.178  1025  1041 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6143 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-08 11:23:17.180  6100  6100 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-08 11:23:17.182  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-08 11:23:17.182  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-08 11:23:17.182  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-08 11:23:17.182  1025  1531 D WifiNative-wlan0: doBoolean: SET update_config 1
08-08 11:23:17.181  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-08 11:23:17.183  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-08 11:23:17.184  1937  1937 D WfdService: Waiting for WifiP2p enabling
08-08 11:23:17.184  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-08 11:23:17.184  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-08 11:23:17.184  1025  6142 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-08 11:23:17.184  1025  6142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-08 11:23:17.184  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.184  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.184  6100  6100 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-08 11:23:17.184  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-08 11:23:17.185  1025  6142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-08 11:23:17.185  1025  1531 D WifiNative-wlan0: SET update_config 1: returned true
08-08 11:23:17.185  1025  1531 D WifiConfigStore: Loading config and enabling all networks 
08-08 11:23:17.185  1025  1531 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-08 11:23:17.185  1025  1531 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-08 11:23:17.186  1848  1848 D BluetoothHeadset: Proxy object connected
08-08 11:23:17.186  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:17.186  1848  1848 D BluetoothHeadset: Proxy object connected
08-08 11:23:17.186  1848  1848 D BluetoothHeadset: Proxy object connected
08-08 11:23:17.186  1025  6142 D WifiMonitor: Dropping event because (p2p0) is stopped
08-08 11:23:17.187  6063  6063 D HeadsetService: Received start request. Starting profile...
08-08 11:23:17.187  6063  6063 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-08 11:23:17.188  6063  6063 D LGBluetoothHfpAdapter: Version 1.6
08-08 11:23:17.188  1025  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-08 11:23:17.188  6063  6094 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:17.188  1025  1025 D BluetoothHeadset: Proxy object connected
08-08 11:23:17.190  6063  6063 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-08 11:23:17.190  6063  6063 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-08 11:23:17.191  6063  6063 D HeadsetStateMachine: make
08-08 11:23:17.192  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:17.192  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:17.192  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:17.192  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:23:17.192  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:17.192  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:17.192  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:17.192  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:17.192  5992  5992 V io.jxco,re.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:17.192  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:17.192  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:23:17.194  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:17.194  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:17.194  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:17.194  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:23:17.194  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:17.194  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:17.194  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:17.194  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:17.194  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:17.195  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:17.195  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:17.196  1025  1531 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-08 11:23:17.202  6063  6094 E BluetoothAdapterService: File transfer profiles supported!!
,08-08 11:23:17.209  6063  6094 E BluetoothAdapterService: File transfer profiles supported!!
,08-08 11:23:17.212  1025  1531 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-08 11:23:17.212  1025  1531 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-08 11:23:17.213  6063  6094 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:17.213  1025  1531 D WifiStateMachine: enableVerboseLogging : level 2
08-08 11:23:17.213  1025  1531 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-08 11:23:17.213  1025  1531 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-08 11:23:17.213  1025  1531 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-08 11:23:17.213  1025  1531 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-08 11:23:17.213  1025  1531 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-08 11:23:17.214  1025  1531 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-08 11:23:17.214  1025  1531 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-08 11:23:17.214  1025  1531 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-08 11:23:17.214  1025  1531 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-08 11:23:17.214  1025  1531 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-08 11:23:17.215  1025  1531 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-08 11:23:17.215  1025  1531 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-08 11:23:17.215  1025  1531 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-08 11:23:17.215  1025  1531 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-08 11:23:17.216  1025  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-08 11:23:17.216  1025  1531 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-08 11:23:17.216  1025  1531 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-08 11:23:17.216  1937  1937 D WfdsService: Supplicant Connection state is changed : true
08-08 11:23:17.216  1025  1531 D WifiNative-HAL: Setting external_sim to 1
,08-08 11:23:17.216  6063  6094 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:17.216  1025  1531 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-08 11:23:17.216  1937  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-08 11:23:17.216  1025  1531 D WifiNative-wlan0: SET external_sim 1: returned true
08-08 11:23:17.216  1937  2299 D WfdsService: Set the WFDS Monitor: true
08-08 11:23:17.216  1025  1531 I WifiNative-HAL: startHal
08-08 11:23:17.216  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x988428dc
08-08 11:23:17.217  1025  1531 E WifiHAL : Could not connect handle
08-08 11:23:17.217  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x601a56
08-08 11:23:17.217  1025  1531 I WifiNative-HAL: Could not start hal
08-08 11:23:17.217  1025  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-08 11:23:17.217  1025  1531 I WifiNative-HAL: startHal
08-08 11:23:17.217  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x9884285c
08-08 11:23:17.217  1025  1531 E WifiHAL : Could not connect handle
08-08 11:23:17.217  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x201a3e
08-08 11:23:17.217  1025  1531 I WifiNative-HAL: Could not start hal
08-08 11:23:17.217  1025  1531 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-08 11:23:17.217  5992  5992 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-08 11:23:17.217  1937  2299 D WfdsMonitor: WfdsMonitorThread create
08-08 11:23:17.217  1937  2299 D WfdsMonitor: WFDS Monitor is created and started
08-08 11:23:17.217  1937  2299 D WfdsService: WiFi: Supplicant connection re-established
08-08 11:23:17.218  6063  6063 D LgDataFeature: LgDataFeature() Constructor: none
08-08 11:23:17.218  1025  1531 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-08 11:23:17.218  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-08 11:23:17.218  6063  6063 D LgDataFeature: LgDataFeature() Constructor Done, null
08-08 11:23:17.218  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-08 11:23:17.218  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-08 11:23:17.220  1937  6162 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-08 11:23:17.220  1937  6162 E CtrlSupplicant: Succeed to open control connection
08-08 11:23:17.220  1937  6162 E CtrlSupplicant: Succeed to open monitor connection
08-08 11:23:17.221  6063  6094 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:17.221  6063  6063 D HeadsetStateMachine: max_hf_connections = 1
08-08 11:23:17.221  6063  6063 I bluedroid-qcom: get_profile_interface handsfree
,08-08 11:23:17.222  6102  6141 V FormManager: Network unavailable.
08-08 11:23:17.222  6063  6063 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-08 11:23:17.224  1025  1025 D WifiHS20: hidePasspointNotification off =false
,08-08 11:23:17.224   313  2139 V AudioPolicyService: registerClient() client 0xb558a280, uid 1002
08-08 11:23:17.224  6120  6120 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-08 11:23:17.224   313  2136 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-08 11:23:17.224   313  2136 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-08 11:23:17.224   313  2136 V AudioPolicyManagerEx: getOutput() returns output 2
08-08 11:23:17.225  6120  6120 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-08 11:23:17.225  6063  6063 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-08 11:23:17.226  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.226  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.226  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-08 11:23:17.226   313  1377 V AudioFlinger: registerClient() client 0xb101a070, pid 6063
08-08 11:23:17.227  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:17.227  6063  6063 V ToneGenerator: Create Track: 0xb4928a80
08-08 11:23:17.227  6063  6063 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-08 11:23:17.227  6063  6063 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-08 11:23:17.227  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-08 11:23:17.227  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:17.227   313  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-08 11:23:17.227   313  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-08 11:23:17.227   313  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-08 11:23:17.227   313  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-08 11:23:17.227  6063  6063 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-08 11:23:17.227  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-08 11:23:17.227   313  2136 I AudioFlinger: isAudioPlaybackHookOn() false
08-08 11:23:17.227   313  1377 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-08 11:23:17.227   313  1377 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-08 11:23:17.227   313  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-08 11:23:17.227   313  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-08 11:23:17.227  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-08 11:23:17.227  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-08 11:23:17.228  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-08 11:23:17.228  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-08 11:23:17.228  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-08 11:23:17.228  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-08 11:23:17.228  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-08 11:23:17.228  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-08, 11:23:17.228  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-08 11:23:17.228  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-08 11:23:17.228  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-08 11:23:17.228  6100  6100 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-08 11:23:17.228  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-08 11:23:17.228  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-08 11:23:17.228  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-08 11:23:17.229  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-08 11:23:17.229   313  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:17.229   313  1371 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:17.229  1848  2456 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:17.229  1848  2456 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:17.229  1025  1977 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:17.229  1025  1977 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:17.229  2126  2143 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:17.229  2126  2143 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:17.229   313  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:17.229   313  1372 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:17.230  3409  3424 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:17.230  3409  3424 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:17.230  1025  1946 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:17.230  3409  3424 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:17.230  1025  1946 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:17.230  3409  3424 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:17.230  6063  6063 V AudioSystem: getLatency() output 2, latency 50
08-08 11:23:17.230  1597  1615 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:17.230  6063  6086 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:17.230  1597  1615 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:17.230  1597  1615 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:17.230  1597  1615 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:17.230  6063  6086 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-08 11:23:17.230  6063  6086 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:17.230  6063  6086 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-08 11:23:17.230  6063  6063 V AudioSystem: getFrameCount() output 2, frameCount 960
08-08 11:23:17.230  6063  6063 V AudioTrack: createTrack_l() output 2 afLatency 50
08-08 11:23:17.230  1848  4095 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:17.230  1848  4095 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:17.230  2126  4141 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:17.230  2126  4141 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:17.230  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:17.230   313  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-08 11:23:17.230   313  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-08 11:23:17.230   313  2136 V AudioFlinger: [MABL_,AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-08 11:23:17.230   313  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-08 11:23:17.230   313  2136 V AudioFlinger: createTrack() lSessionId: 21
08-08 11:23:17.231  6102  6141 V FormManager: Network unavailable.
08-08 11:23:17.231  6063  6063 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-08 11:23:17.231  1025  1531 E WifiNative: : [355,398,681 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-08 11:23:17.231  1025  1531 D WifiNative-wlan0: doBoolean: RECONNECT
08-08 11:23:17.232   313  2136 V AudioFlinger: acquiring 21 from 6063, for 6063
08-08 11:23:17.232   313  2136 V AudioFlinger:  added new entry for 21
08-08 11:23:17.232  6063  6063 V ToneGenerator: ToneGenerator INIT OK, time: 355413
08-08 11:23:17.232  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.232  1025  1531 D WifiNative-wlan0: RECONNECT: returned true
08-08 11:23:17.232  1025  1531 D WifiNative-wlan0: doString: [STATUS]
08-08 11:23:17.232  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-08 11:23:17.232  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-08 11:23:17.232  1025  1531 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-08 11:23:17.232  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-08 11:23:17.233  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-08 11:23:17.233  1025  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-08 11:23:17.233  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-08 11:23:17.233  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.233  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-08 11:23:17.233  1025  1529 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.234  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-08 11:23:17.234  1025  1025 D WifiScanningService: SCAN_AVAILABLE : 3
08-08 11:23:17.234  1025  1531 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-08 11:23:17.234  1025  1025 D RttService: SCAN_AVAILABLE : 3
08-08 11:23:17.234  1025  1548 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.234  1025  1548 I WifiNative-HAL: startHal
08-08 11:23:17.234  1025  1548 E wifi    : getStaticLongField sWifiHalHandle 0x94c9e99c
08-08 11:23:17.234  1025  1531 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-08 11:23:17.234  1025  1548 E WifiHAL : Could not connect handle
08-08 11:23:17.234  1025  1548 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x50190a
08-08 11:23:17.234  1025  1548 I WifiNative-HAL: Could not start hal
08-08 11:23:17.234  1025  1548 E WifiScanningService: could not start HAL
08-08 11:23:17.234  1025  1531 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-08 11:23:17.234  1025  1549 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.235  1025  1531 E WifiStateMachine:  DisconnectedState CMD_START_SUPPLICANT 0 0
08-08 11:23:17.235   309   899 D CommandListener: Setting iface cfg
08-08 11:23:17.235  1025  1531 E WifiStateMachine:  ConnectModeState CMD_START_SUPPLICANT 0 0
08-08 11:23:17.235   309   899 D CommandListener: Trying to bring up p2p0
08-08 11:23:17.235  6063  6063 D A2dpService: Received start request. Starting profile...
08-08 11:23:17.235  1025  1531 E WifiStateMachine:  DriverStartedState CMD_START_SUPPLICANT 0 0
08-08 11:23:17.235  1025  1025 D BluetoothA2dp: Proxy object connected
08-08 11:23:17.235  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_START_SUPPLICANT 0 0
08-08 11:23:17.235  6063  6063 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-08 11:23:17.235  1025  1531 E WifiStateMachine:  DefaultState CMD_START_SUPPLICANT 0 0
08-08 11:23:17.236  1025  1529 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-08 11:23:17.236  1025  1529 D LGWifiP2pService: P2pEnablingState
08-08 11:23:17.236  1025  1529 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.236  1025  1529 D LGWifiP2pService: P2p socket connection successful
08-08 11:23:17.236  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=355404  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-08 11:23:17.236  1025  1529 D LGWifiP2pService: P2pEnabledState
08-08 11:23:17.236  6063  6063 V Avrcp   : make
08-08 11:23:17.236  1025  1529 D LGWifiP2pService: sending p2p connection changed broadcast
08-08 11:23:17.237  6063  6094 V LGMDMManager: Create singleton instance
08-08 11:23:17.237  6063  6063 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-08 11:23:17.237  6063  6063 I bluedroid-qcom: get_profile_interface avrcp
08-08 11:23:17.237  1937  6162 D WfdsMonitor: Supplicant connection established
08-08 11:23:17.237  1025  1529 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-08 11:23:17.237  6120  6120 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-08 11:23:17.237  6120  6120 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-08 11:23:17.238  1937  2299 D WfdsService: Connected to the supplicant for wfds
08-08 11:23:17.238  6120  6120 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-08 11:23:17.238  6063  6159 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-08 11:23:17.239  6120  6120 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-08 11:23:17.239  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-08 11:23:17.239  1937  1937 D WfdsService: WifiP2pState is changed : true
08-08 11:23:17.240  6063  6159 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-08 11:23:17.240  6063  6159 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-08 11:23:17.240  6063  6159 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-08 11:23:17.241  1937  1937 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-08 11:23:17.242  1937  2299 D WfdsService: Receive the WFDS_ENABLE Method
08-08 11:23:17.242  1937  2299 D WfdsService: Set the WFDS Monitor: true
08-08 11:23:17.242  1937  2299 D WfdsService: Connected to the supplicant for wfds
08-08 11:23:17.242  1937  2299 D WfdsJNI : doCommand: WFDS_SET TRUE
08-08 11:23:17.242  6100  6100 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-08 11:23:17.242  1025  1529 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-08 11:23:17.242  1937  2299 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
08-08 11:23:17.242  6100  6100 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
08-08 11:23:17.242  1025  1529 D WifiNative-p2p0: doBoolean: SET device_name G3
08-08 11:23:17.242  1937  2299 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
08-08 11:23:17.242  1937  2299 D WfdsService: selectPreferredScanChannel [36]
08-08 11:23:17.242  1937  2299 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-08 11:23:17.242  1025  1529 D WifiNative-p2p0: SET device_name G3: returned true
08-08 11:23:17.243  1025  1529 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-08 11:23:17.243  1025  1529 D LGWifiP2pService: before postfix = G3
08-08 11:23:17.243  1025  1529 D WifiServerServiceExt: postfix byte check : 2
08-08 11:23:17.243  1025  1529 D LGWifiP2pService: after postfix = G3
08-08 11:23:17.243  1025  1529 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-08 11:23:17.243  1025  1529 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-08 11:23:17.243  1025  1529 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-08 11:23:17.244  1025  1529 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-08 11:23:17.244  1025  1529 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-08 11:23:17.244  1025  1529 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-08 11:23:17.244  1025  1529 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-08 11:23:17.244  1025  1529 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-08 11:23:17.245  1025  1529 D WifiNative-HAL: p2pGetDeviceAddress
08-08 11:23:17.245  6063  6063 V AudioManager: registerRemoteController: size of Media player list: 0
08-08 11:23:17.245  1025  1529 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-08 11:23:17.246   313  1377 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6063
08-08 11:23:17.247  6063  6094 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-08 11:23:17.248  1937  1937 D WfdsService: isConnected: false
08-08 11:23:17.250  1025  1529 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-08 11:23:17.250  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=355418  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-08 11:23:17.250  1025  1529 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-08 11:23:17.250  1025  1529 D WifiNative-p2p0: P2P_FLUSH: returned true
08-08 11:23:17.250  1025  1529 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-08 11:23:17.250  1025  1531 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-08 11:23:17.251  1025  1529 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-08 11:23:17.251  1025  1531 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-08 11:23:17.251  1025  1529 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-08 11:23:17.251  1025  1531 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-08 11:23:17.251  1025  1531 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-08 11:23:17.251  1025  1529 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-08 11:23:17.251  1025  1529 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-08 11:23:17.251  6100  6100 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-08 11:23:17.251  1025  1529 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-08 11:23:17.251  1025  1529 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-08 11:23:17.251   313  1377 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-08 11:23:17.251   313  1377 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-08 11:23:17.251   313  1377 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-08 11:23:17.251   313  1377 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-08 11:23:17.251   313  1377 V voice   : voice_set_parameters: exit with code(0)
08-08 11:23:17.251   313  1377 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-08 11:23:17.251   313  1377 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-08 11:23:17.252   313  1377 V msm8974_platform: platform_set_parameters: exit with code(0)
08-08 11:23:17.252   313  1377 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-08 11:23:17.252   313  1377 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-08 11:23:17.252   313  1377 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-08 11:23:17.252  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:17.252  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:17.253  6063  6159 V ToneGenerator: ToneGenerator destructor
08-08 11:23:17.253  6063  6159 V ToneGenerator: stopTone
08-08 11:23:17.253  6063  6159 V ToneGenerator: Delete Track: 0xb4928a80
08-08 11:23:17.254  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.254  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.254  1025  1529 D LGWifiP2pService: InactiveState
08-08 11:23:17.254  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-08 11:23:17.254  6063  6159 V AudioTrack: ~AudioTrack, releasing session id from 6063 on behalf of 6063
08-08 11:23:17.255   313   313 V AudioPolicyService: AudioCommandThread() adding release output 2
08-08 11:23:17.255   313   313 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-08 11:23:17.255  1937  1937 I WfdStateTracker: handleP2pThisDeviceChanged
08-08 11:23:17.255  1937  1937 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-08 11:23:17.255  1937  1937 D WfdsService: Update P2p Interface State: 3
08-08 11:23:17.255   313   313 V AudioFlinger: PlaybackThread::Track destructor
08-08 11:23:17.255   313   313 V AudioFlinger: removeClient_l() pid 6063, calling pid 313
08-08 11:23:17.255   313  1096 V AudioPolicyService: AudioCommandThread() waking up
08-08 11:23:17.255   313  1096 V AudioPolicyService: AudioCommandThread() processing release output 2
08-08 11:23:17.255   313  1096 V AudioPolicyManager: releaseOutput() 2
08-08 11:23:17.255   313  1096 V AudioPolicyService: AudioCommandThread() going to sleep
08-08 11:23:17.255  1025  1529 D LGWifiP2pService: InactiveState{ when=-4ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.255  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.255  1025  1529 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-08 11:23:17.256   313  1377 V AudioFlinger: releasing 21 from 6063 for 6063
08-08 11:23:17.256   313  1377 V AudioFlinger:  decremented refcount to 0
08-08 11:23:17.256   313  1377 V AudioFlinger: purging stale effects
08-08 11:23:17.257  6063  6063 E AudioManager: No RCC entry present to update
08-08 11:23:17.257  6063  6063 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-08 11:23:17.258  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:17.259  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-08 11:23:17.259  1025  1531 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-08 11:23:17.259  6063  6063 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-08 11:23:17.259  6100  6100 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:17.260  6100  6100 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-08 11:23:17.260  6100  6100 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.260  1937  6162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-08 11:23:17.260  1937  6162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:17.260  1025  6142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-08 11:23:17.260  1025  6142 E WifiMonitor: WifiMonitor:p2p0 cnt=3 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:17.260  1025  6142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:17.260  1025  6142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:17.260  6100  6100 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.260  1025  6142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:17.260  1025  6142 E WifiMonitor: WifiMonitor:p2p0 cnt=4 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.260  1025  6142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.260  1025  6142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.260  1025  6142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:17.260  1025  6142 E WifiMonitor: WifiMonitor:p2p0 cnt=5 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.260  1025  6142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.260  1025  6142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.260  1937  6162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:17.261  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-08 11:23:17.261  6063  6063 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-08 11:23:17.261  1025  1531 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-08 11:23:17.261  1025  1531 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-08 11:23:17.261  1025  1531 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-08 11:23:17.261  6100  6100 E wpa_supplicant: disconnect_rssi_lvl: -100
08-08 11:23:17.262  1025  1529 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: InactiveState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.262  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.263  1025  1529 D LGWifiP2pService: DefaultState{ when=0 what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.263  6102  6139 W FormManager: Network not available. Please check & try again.
08-08 11:23:17.263  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-08 11:23:17.263  1937  2299 W WfdsService: DefaultState - msg [9441285] is not handled
08-08 11:23:17.263  1025  1025 E WifiServerServiceExt: No p2p device connected
08-08 11:23:17.264  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 1 0 cz
08-08 11:23:17.264  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 1 0 cz
08-08 11:23:17.264  1025  1531 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 1 0 cz
08-08 11:23:17.264  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-08 11:23:17.265  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-08 11:23:17.265  6100  6100 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:17.265  6100  6100 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-08 11:23:17.265  6100  6100 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.266  6100  6100 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.266  1937  6162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:17.266  1937  6162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-08 11:23:17.266  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-08 11:23:17.266  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=6 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:17.266  1025  6142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:17.266  1025  6142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:17.266  1025  6142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:17.267  1025  6142 E WifiMonitor: WifiMonitor:p2p0 cnt=7 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.267  1025  6142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.267  1025  6142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.267  1025  6142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:17.267  1025  6142 E WifiMonitor: WifiMonitor:p2p0 cnt=8 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.267  1025  6142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.267  1025  6142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:17.267  1025  1531 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-08 11:23:17.267  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-08 11:23:17.267  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-08 11:23:17.268  1025  1531 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-08 11:23:17.268  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-08 11:23:17.268  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-08 11:23:17.268  6100  6100 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-08 11:23:17.269  1025  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.269  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:17.269  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-08 11:23:17.269  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=9 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-08 11:23:17.269  1025  6142 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-08 11:23:17.269  1025  6142 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-08 11:23:17.269  1025  1531 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-08 11:23:17.269  1025  1531 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-08 11:23:17.270  1025  1531 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-08 11:23:17.270  1025  1531 D WifiNative-wlan0: doBoolean: SCAN
08-08 11:23:17.270  1025  1531 D WifiNative-wlan0: SCAN: returned false
08-08 11:23:17.270  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 2 0 rt=355438  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-08 11:23:17.271  1025  1536 D WifiService: New client listening to asynchronous messages
08-08 11:23:17.294  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 2 0 rt=355462  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-08 11:23:17.295  1025  1531 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:17.295  1025  1531 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:17.295  1025  1531 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:17.295  1025  1531 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:17.295  1025  1531 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-08 11:23:17.298  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.298  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.298  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-08 11:23:17.298  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-08 11:23:17.299  1025  1025 D WifiServerServiceExt: setSupplicantStateSCANNING
08-08 11:23:17.300  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:17.300  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:17.301  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:17.301  1025  1977 I ActivityManager: Killing 4626:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-08 11:23:17.305  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-08 11:23:17.337  1025  1991 V SIM_STK : Menu title from STK is T-Mobile
08-08 11:23:17.337  1025  1991 V SIM_STK : Menu title from STK is T-Mobile
,08-08 11:23:17.384  1025  1977 I ActivityManager: Killing 2126:com.lge.music/u0a34 (adj 15): empty #17
,08-08 11:23:17.407   313  2136 V AudioFlinger: 2126 died, releasing its sessions
08-08 11:23:17.407   313  2136 V AudioFlinger:  pid 1848 @ 0
08-08 11:23:17.407   313  2136 V AudioFlinger:  pid 3409 @ 1
08-08 11:23:17.407   313  2136 V AudioFlinger:  pid 3409 @ 2
,08-08 11:23:17.425  1025  1955 W libprocessgroup: failed to open /acct/uid_10034/pid_2126/cgroup.procs: No such file or directory
,08-08 11:23:17.428  1025  1568 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-08 11:23:17.428  1025  1883 W libprocessgroup: failed to open /acct/uid_10014/pid_4626/cgroup.procs: No such file or directory
,08-08 11:23:17.449  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-08 11:23:17.453  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-08 11:23:17.454  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-08 11:23:17.455  6063  6063 I BluetoothA2dpServiceJni: classInitNative
08-08 11:23:17.455  6063  6063 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 11:23:17.455  6063  6063 D A2dpStateMachine: make
08-08 11:23:17.456  6063  6063 I bluedroid-qcom: get_profile_interface a2dp
08-08 11:23:17.456  6063  6170 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-08 11:23:17.459  6063  6063 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-08 11:23:17.460  6063  6063 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-08 11:23:17.461  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.461  6063  6169 D A2dpStateMachine: Enter Disconnected: -2
08-08 11:23:17.462  6063  6063 I BluetoothHidServiceJni: classInitNative: succeeds
,08-08 11:23:17.466  6063  6063 D HidService: Received start request. Starting profile...
08-08 11:23:17.466  6063  6063 I bluedroid-qcom: get_profile_interface hidhost
08-08 11:23:17.466  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.467  6063  6063 I BluetoothHealthServiceJni: classInitNative: succeeds
08-08 11:23:17.469  6063  6063 D HealthService: Received start request. Starting profile...
08-08 11:23:17.472  6063  6063 I bluedroid-qcom: get_profile_interface health
08-08 11:23:17.473  6063  6063 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-08 11:23:17.473  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.474  6063  6063 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-08 11:23:17.476  6063  6063 D PanService: Received start request. Starting profile...
08-08 11:23:17.476  6063  6063 D BluetoothPanServiceJni: initializeNative(L110): pan
08-08 11:23:17.476  6063  6063 I bluedroid-qcom: get_profile_interface pan
,08-08 11:23:17.484  6063  6063 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-08 11:23:17.484  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.485  6063  6063 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-08 11:23:17.492  6063  6063 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 11:23:17.492  6063  6063 D BtGatt.GattService: Received start request. Starting profile...
08-08 11:23:17.492  6063  6063 D BtGatt.GattService: start()
08-08 11:23:17.492  6063  6063 I bluedroid-qcom: get_profile_interface gatt
08-08 11:23:17.493  6063  6063 D BtGatt.AdvertiseManager: advertise manager created
08-08 11:23:17.495  1025  1040 I ActivityManager: Killing 5544:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-08 11:23:17.521  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-08 11:23:17.528  1025  1536 D WifiService: New client listening to asynchronous messages
08-08 11:23:17.551  1025  1991 W libprocessgroup: failed to open /acct/uid_10008/pid_5544/cgroup.procs: No such file or directory
,08-08 11:23:17.557  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.558  6063  6063 D HeadsetStateMachine: Proxy object connected
08-08 11:23:17.558  6120  6120 D LgDataFeature: LgDataFeature() Constructor: none
08-08 11:23:17.558  6063  6063 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-08 11:23:17.558  6120  6120 D LgDataFeature: LgDataFeature() Constructor Done, null
08-08 11:23:17.558  6063  6063 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-08 11:23:17.560  1848  1848 D BluetoothPhoneService.BluetoothLTECall:  call mBluetoothHeadset.phoneStateChanged()
08-08 11:23:17.560  1848  1848 W BluetoothHeadset: Proxy not attached to service
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: java.lang.Throwable
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.handleQueryPhoneState(BluetoothPhoneService.java:1527)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$BluetoothLTECall.access$700(BluetoothPhoneService.java:1360)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:268)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at android.os.Looper.loop(Looper.java:135)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-08 11:23:17.561  1848  1848 D BluetoothHeadset: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-08 11:23:17.561  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:17.561  6063  6063 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-08 11:23:17.563  6063  6063 V BluetoothMapService: BluetoothMapBinder()
08-08 11:23:17.563  6063  6063 D BluetoothMapService: Received start request. Starting profile...
08-08 11:23:17.563  6063  6063 D BluetoothMapService: start()
,08-08 11:23:17.567  6120  6120 D WiFiOffLoadUpdatePriority: remove : truetruetrue
08-08 11:23:17.568  6063  6063 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-08 11:23:17.568  6063  6063 D BluetoothMapEmailAppObserver: createReceiver()
08-08 11:23:17.571  6063  6063 D BluetoothMapEmailAppObserver: initObservers()
08-08 11:23:17.571  6063  6063 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-08 11:23:17.573  1025  1531 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-08 11:23:17.574  1025  1531 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-08 11:23:17.577  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
,08-08 11:23:17.578  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
08-08 11:23:17.578  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-08 11:23:17.586  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
,08-08 11:23:17.591  6063  6063 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-08 11:23:17.591  6063  6159 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-08 11:23:17.592  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-08 11:23:17.592  6063  6159 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-08 11:23:17.592  6063  6159 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-08 11:23:17.593  6120  6120 D WiFiOffLoadUpdatePriority: remove1
08-08 11:23:17.593  6120  6120 V WiFiOffLoadSharedPrefsUtils: save remove
08-08 11:23:17.595  6063  6063 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-08 11:23:17.598  6063  6063 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-08 11:23:17.600  6120  6120 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
08-08 11:23:17.600  6120  6120 D WiFiOffLoadBroadcast: S: false, R: false
08-08 11:23:17.601  6063  6063 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-08 11:23:17.601  1025  1531 E WifiStateMachine:  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-08 11:23:17.602  1025  1531 E WifiStateMachine:  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
08-08 11:23:17.603  6120  6120 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
08-08 11:23:17.603  6120  6120 D WiFiOffLoadUpdatePriority: connected SSID: null
,08-08 11:23:17.603  6120  6120 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
08-08 11:23:17.604  6063  6063 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-08 11:23:17.605  6063  6063 V PanService: [BTUI] SIM Extra State :ABSENT
08-08 11:23:17.605  6063  6063 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-08 11:23:17.606  6063  6063 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:17.606  6063  6063 V BluetoothPbapReceiver: ***********state = 11
08-08 11:23:17.606  1025  1040 D WifiServiceImplEx: addOrUpdateNetwork pid=6120, uid=1000, packageName=android.uid.system:1000
08-08 11:23:17.608  1025  1040 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
08-08 11:23:17.608  1025  1531 E WifiStateMachine:  DisconnectedState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
08-08 11:23:17.609  1025  1531 E WifiStateMachine:  ConnectModeState CMD_ADD_OR_UPDATE_NETWORK uid=1000 0 0 "NG700"WPA_PSK prio=300 status=2
08-08 11:23:17.609  1025  1531 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
08-08 11:23:17.609  1025  1531 D WifiServerServiceExt: addOrUpdateNetwork: mThisIsFirstEnableing = false
08-08 11:23:17.610  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 ssid 4e47373030
08-08 11:23:17.610  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:23:17.612  6063  6063 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-08 11:23:17.612  6063  6063 V BluetoothMapService: Handler(): got msg=1
08-08 11:23:17.613  6063  6094 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-08 11:23:17.613  6063  6094 I bluedroid-qcom: enable
08-08 11:23:17.613  6063  6180 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-08 11:23:17.613  6063  6180 I bt-btu  : btu_task pending for preload complete event
08-08 11:23:17.614  6063  6094 I bt_hci_bdroid: init
08-08 11:23:17.624  6063  6094 I bt_vendor: bt-vendor : init
08-08 11:23:17.625  6063  6094 I bt_vendor: bt-vendor : get_bt_soc_type
08-08 11:23:17.625  6063  6094 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-08 11:23:17.625  6063  6094 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-08 11:23:17.625  6063  6094 D bt_userial_mct: userial_init
08-08 11:23:17.625  6063  6094 D bt_hci_bdroid: set_power 1
08-08 11:23:17.625  6063  6094 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-08 11:23:17.625  6063  6094 I bt_vendor: Starting hciattach daemon
08-08 11:23:17.625  6063  6094 I bt_vendor: try to set true
,08-08 11:23:17.609  6183  6183 W sh      : type=1400 audit(0.0:157): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-08 11:23:17.609  6183  6183 W sh      : type=1400 audit(0.0:158): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:17.645  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 ssid 4e47373030: returned true
08-08 11:23:17.646  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 key_mgmt WPA-PSK
,08-08 11:23:17.647  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 key_mgmt WPA-PSK: returned true
08-08 11:23:17.647  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 proto WPA RSN
08-08 11:23:17.648  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 proto WPA RSN: returned true
08-08 11:23:17.648  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 pairwise TKIP CCMP
08-08 11:23:17.649  6184  6184 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
08-08 11:23:17.649  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 pairwise TKIP CCMP: returned true
08-08 11:23:17.649  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP
08-08 11:23:17.650  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 group WEP40 WEP104 TKIP CCMP: returned true
08-08 11:23:17.650  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 priority 300
08-08 11:23:17.651  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 priority 300: returned true
08-08 11:23:17.652  1025  1531 E WifiConfigStore: will read network variables netId=0
08-08 11:23:17.658  1025  1531 E WifiConfigStore: writeIpAndProxyConfigurationsOnChange: "NG700" -> "NG700" path: /data/misc/wifi/ipconfig.txt
,08-08 11:23:17.659  1025  1531 E WifiConfigStore:  writeKnownNetworkHistory() num networks:1 needWrite=false
08-08 11:23:17.665  1025  1640 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6186 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-08 11:23:17.668  6120  6120 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
08-08 11:23:17.668  6120  6120 D WiFiOffLoadUpdatePriority: configuration updated: 0
08-08 11:23:17.669  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SAVE_CONFIG uid=1000 0 0
08-08 11:23:17.669  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SAVE_CONFIG uid=1000 0 0
08-08 11:23:17.670  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-08 11:23:17.683  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-08 11:23:17.683  6120  6120 D WiFiOffLoadUpdatePriority: configuration saved: true
08-08 11:23:17.697  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-08 11:23:17.697  6120  6120 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-08 11:23:17.697  6120  6120 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-08 11:23:17.697  6120  6120 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-08 11:23:17.699  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-08 11:23:17.711  6207  6207 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-08 11:23:17.715  6120  6120 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-08 11:23:17.715  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-08 11:23:17.716  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-08 11:23:17.716  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-08 11:23:17.716  6120  6120 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-08 11:23:17.717  6120  6120 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-08 11:23:17.721  6209  6209 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-08 11:23:17.724  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-08 11:23:17.729  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-08 11:23:17.735  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:17.737  6102  6212 W FormManager: Network not available. Please check & try again.
,08-08 11:23:17.740  6214  6214 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-08 11:23:17.741  6102  6213 V FormManager: Network unavailable.
08-08 11:23:17.743  6102  6213 V FormManager: Network unavailable.
08-08 11:23:17.749  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-08 11:23:17.749  6215  6215 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-08 11:23:17.749  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-08 11:23:17.751  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:17.756  6216  6216 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-08 11:23:17.758  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:17.763  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:17.763  3254  6218 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-08 11:23:17.763  6217  6217 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-08 11:23:17.764  3254  6219 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-08 11:23:17.765  3254  6219 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-08 11:23:17.771  6143  6143 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-08 11:23:17.774  6143  6143 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-08 11:23:17.774  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-08 11:23:17.777  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:17.780  6100  6100 E wpa_supplicant: USIM:  scard_init function
08-08 11:23:17.780  6100  6100 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-08 11:23:17.780  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=10 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-08 11:23:17.780  1025  6142 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-08 11:23:17.781  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-08 11:23:17.781  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=11 dispatchEvent: WPS-AP-AVAILABLE 
08-08 11:23:17.781  1025  6142 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-08 11:23:17.781  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-08 11:23:17.781  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-08 11:23:17.782  1025  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-08 11:23:17.782  1025  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-08 11:23:17.782  1025  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-08 11:23:17.783  1025  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=0 bcn=0
08-08 11:23:17.783  1025  1531 I WifiNative-HAL: startHal
08-08 11:23:17.783  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x988428cc
08-08 11:23:17.783  1025  1531 E WifiHAL : Could not connect handle
08-08 11:23:17.783  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x20182a
08-08 11:23:17.783  1025  1531 I WifiNative-HAL: Could not start hal
08-08 11:23:17.783  1025  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-08 11:23:17.783  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:17.786  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=355954  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-08 11:23:17.787  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 12 0 rt=355955  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-08 11:23:17.787  6222  6222 I libmdmdetect: ESOC framework not supported
08-08 11:23:17.788  6222  6222 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-08 11:23:17.788  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:17.788  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-08 11:23:17.791  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:17.792  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.792  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.792  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-08 11:23:17.792  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-08 11:23:17.792  1025  1025 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-08 11:23:17.798  6222  6222 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-08 11:23:17.798  6222  6222 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-08 11:23:17.798  6222  6222 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-08 11:23:17.798  6222  6222 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-08 11:23:17.798  6222  6222 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-08 11:23:17.798  6222  6222 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-08 11:23:17.798  6222  6222 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-08 11:23:17.840  1025  2026 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6227 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-08 11:23:17.841  6186  6186 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-08 11:23:17.842  6186  6186 W LG Account v2.2: No ProfileInfo entries
08-08 11:23:17.842  6186  6186 I LG Account v2.2: isEnabled: false
08-08 11:23:17.842  6186  6186 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-08 11:23:17.842  6186  6186 I Feature : [Lifetracker]Country: EU
08-08 11:23:17.842  6186  6186 I Feature : [Lifetracker]Operator: OPEN
08-08 11:23:17.842  6186  6186 I Feature : [Lifetracker]Ranking support: false
08-08 11:23:17.843  6186  6186 I Feature : [Lifetracker]Comfort support: false
08-08 11:23:17.843  6186  6186 I Feature : [Lifetracker]Accessory: true
08-08 11:23:17.843  6186  6186 I Feature : [Lifetracker]Health device: true
08-08 11:23:17.843  6186  6186 I Feature : [Lifetracker]Extra Pedometer: false
08-08 11:23:17.843  6186  6186 I Feature : [Lifetracker]Blood glucose device: false
08-08 11:23:17.843  6186  6186 I Feature : [Lifetracker]Device Number: 3
,08-08 11:23:17.871  6120  6120 D BluetoothPermissionRequest: onReceive
08-08 11:23:17.872  6120  6120 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-08 11:23:17.883  6227  6227 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-08 11:23:17.885  1025  1087 D BluetoothManagerService: Message: 20
08-08 11:23:17.885  1025  1087 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3837143b:true
08-08 11:23:17.890  6120  6120 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-08 11:23:17.891  1025  1568 I ActivityManager: Killing 5577:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-08 11:23:17.904  6100  6100 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-08 11:23:17.906  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-08 11:23:17.906  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-08 11:23:17.906  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-08 11:23:17.906  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-08 11:23:17.906  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-08 11:23:17.906  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-08 11:23:17.907  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=356075  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-08 11:23:17.908  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=356076  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-08 11:23:17.909  1025  1531 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 14 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356077
08-08 11:23:17.909  1025  1531 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 14 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356078
08-08 11:23:17.910  1025  1531 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 14 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356078
08-08 11:23:17.910  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 14 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356079
08-08 11:23:17.911  1025  1531 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 14 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=356079
08-08 11:23:17.911  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-08 11:23:17.911  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-08 11:23:17.911  6100  6100 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-08 11:23:17.911  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-08 11:23:17.911  6100  6100 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-08 11:23:17.911  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-08 11:23:17.911  1025  6142 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-08 11:23:17.911  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-08 11:23:17.911  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-08 11:23:17.911  1025  6142 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-08 11:23:17.912  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-08 11:23:17.912  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-08 11:23:17.912  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=356080  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-08 11:23:17.931  1025  1041 W libprocessgroup: failed to open /acct/uid_10011/pid_5577/cgroup.procs: No such file or directory
08-08 11:23:17.931  6063  6063 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppA,dapter]
,08-08 11:23:17.934  1025  1087 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-08 11:23:17.936  6227  6227 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-08 11:23:17.941  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:17.941  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:17.943  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-08 11:23:17.945  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.945  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.945  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-08 11:23:17.947  6063  6063 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:17.947  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 15 0 rt=356115  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-08 11:23:17.951  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.951  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:17.951  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-08 11:23:17.955  6063  6063 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-08 11:23:17.956  6063  6063 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-08 11:23:17.956  6063  6063 V BluetoothSapReceiver: SapReceiver onReceive 
08-08 11:23:17.957  6063  6063 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:17.957  6063  6063 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-08 11:23:17.962  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-08 11:23:17.962  1025  1025 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-08 11:23:17.962  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=356130  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-08 11:23:17.963  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=356131  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-08 11:23:17.964  1025  1531 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=356132
08-08 11:23:17.964  1025  1531 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=356132
08-08 11:23:17.965  1025  1531 D WifiNative-wlan0: doString: [STATUS]
08-08 11:23:17.966  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-08 11:23:17.966  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-08 11:23:17.969  1025  1531 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-08 11:23:17.972  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:17.972  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:17.973  1025  1531 I WifiServiceExtension: setVHTCapabilityType  : false
08-08 11:23:17.974  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:18.003  6227  6227 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-08 11:23:18.003  6227  6227 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-08 11:23:18.004  6227  6227 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-08 11:23:18.004  6227  6227 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-08 11:23:18.004  6227  6227 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-08 11:23:18.007  6227  6227 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-08 11:23:18.014  6227  6227 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-08 11:23:18.014  1025  1883 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6246 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-08 11:23:18.016  1025  1531 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-08 11:23:18.016  1025  1531 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-08 11:23:18.020  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:18.020  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:18.021  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-08 11:23:18.022  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:18.022  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:18.022  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-08 11:23:18.024  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:18.024  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:18.026  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:18.026  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:18.026  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-08 11:23:18.026  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:18.031  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:18.033  1025  1531 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-08 11:23:18.033  1025  1537 D ConnectivityService: Got NetworkAgent Messenger
08-08 11:23:18.034  1025  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-08 11:23:18.034  1025  1537 D ConnectivityService: NetworkAgent connected
08-08 11:23:18.035  1025  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-08 11:23:18.035  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-08 11:23:18.035  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-08 11:23:18.035  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-08 11:23:18.037  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:18.041  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-08 11:23:18.041  1025  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-08 11:23:18.041  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-08 11:23:18.042  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-08 11:23:18.042  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-08 11:23:18.047  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-08 11:23:18.050   309   899 D CommandListener: Setting iface cfg
,08-08 11:23:18.054  1025  6265 D DhcpStateMachine: StoppedState
08-08 11:23:18.054  1025  1531 E WifiStateMachine: Start Dhcp Watchdog 1
08-08 11:23:18.054  1025  6265 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:18.054  1025  6265 D DhcpStateMachine: WaitBeforeStartState
08-08 11:23:18.055  1025  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=356223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-08 11:23:18.055  1025  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=356223  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-08 11:23:18.058  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=356226  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-08 11:23:18.058  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:18.058  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:18.059  1025  1531 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:18.059  1025  1531 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:18.059  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:18.060  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:18.062  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-08 11:23:18.062  1025  1025 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-08 11:23:18.064  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-08 11:23:18.064  1025  1025 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-08 11:23:18.066  1025  1531 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=356234  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-08 11:23:18.067  1025  1531 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=356235  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-08 11:23:18.068  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 20 0 rt=356236  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-08 11:23:18.071  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1769382839] from screen [on:0 period:1769382839]
08-08 11:23:18.072  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1769382840]
08-08 11:23:18.072  1025  1531 I WifiNative-HAL: startHal
08-08 11:23:18.072  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x988428bc
08-08 11:23:18.072  1025  1531 E WifiHAL : Could not connect handle
08-08 11:23:18.072  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x7015de
08-08 11:23:18.072  1025  1531 I WifiNative-HAL: Could not start hal
08-08 11:23:18.072  1025  1531 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-08 11:23:18.078  6246  6246 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-08 11:23:18.080  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:18.082  1025  1537 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-08 11:23:18.082  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.083  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.083  1025  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.083  1025  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.084  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.084  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.084  1025  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-08 11:23:18.085  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-08 11:23:18.085  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-08 11:23:18.085  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-08 11:23:18.092  1025  1991 I ActivityManager: Killing 5474:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-08 11:23:18.109  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-08 11:23:18.109  1025  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-08 11:23:18.109  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 0
08-08 11:23:18.110  1025  1531 D WifiNative-wlan0: SET ps 0: returned true
08-08 11:23:18.110  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-08 11:23:18.110  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-08 11:23:18.110  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-08 11:23:18.111  1025  1529 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31b1d1b8 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:18.111  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31b1d1b8 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:18.111  1025  6265 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:18.111  1025  1531 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-08 11:23:18.111  1025  1531 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-08 11:23:18.111  1025  6265 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-08 11:23:18.111  1025  1531 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-08 11:23:18.111  1025  1531 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-08 11:23:18.131  6227  6227 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-08 11:23:18.132  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-08 11:23:18.132  1025  1025 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-08 11:23:18.136  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-08 11:23:18.136  1025  1025 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-08 11:23:18.136  5850  5850 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-08 11:23:18.136  5850  5850 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-08 11:23:18.136  1025  1955 W libprocessgroup: failed to open /acct/uid_10004/pid_5474/cgroup.procs: No such file or directory
08-08 11:23:18.141  6227  6227 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-08 11:23:18.145  6227  6227 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-08 11:23:18.145  5850  5850 V [BNRBootReceiver]: Boot Receiver Return
,08-08 11:23:18.150  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:18.161  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:18.169  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-08 11:23:18.182  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:18.183  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-08 11:23:18.186  6227  6227 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-08 11:23:18.192  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:18.205  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:18.220  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:18.236  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-08 11:23:18.237  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:18.241  6227  6227 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-08 11:23:18.246  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-08 11:23:18.254  6120  6120 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-08 11:23:18.262  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:18.280  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:18.295  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-08 11:23:18.311  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:18.312  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:18.313  6227  6227 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-08 11:23:18.315  1025  6265 D DhcpStateMachine: DHCPV4 request on wlan0
08-08 11:23:18.316  1025  6265 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-08 11:23:18.316  1025  6265 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-08 11:23:18.321  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-08 11:23:18.322  6120  6120 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-08 11:23:18.322  6120  6120 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-08 11:23:18.323  6120  6120 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-08 11:23:18.324  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-08 11:23:18.326  6120  6120 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-08 11:23:18.326  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-08 11:23:18.326  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-08 11:23:18.326  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-08 11:23:18.326  6120  6120 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-08 11:23:18.327  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-08 11:23:18.328  6120  6120 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-08 11:23:18.335  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:18.319  6269  6269 W dhcpcd  : type=1400 audit(0.0:159): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-08 11:23:18.319  6269  6269 W dhcpcd  : type=1400 audit(0.0:160): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:18.347  6269  6269 I dhcpcd  : version 5.5.6 starting
08-08 11:23:18.353  6269  6269 E dhcpcd  : get_duid: m
08-08 11:23:18.353  6269  6269 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-08 11:23:18.353  6269  6269 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-08 11:23:18.358  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-08 11:23:18.364  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:18.371  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:18.372  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-08 11:23:18.372  6227  6227 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-08 11:23:18.376  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:18.382  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:18.389  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:18.396  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:18.396  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:18.397  6227  6227 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-08 11:23:18.401  6227  6227 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-08 11:23:18.404  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-08 11:23:18.404  6227  6227 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-08 11:23:18.443  6227  6227 D LgDataFeature: LgDataFeature() Constructor: none
08-08 11:23:18.443  6227  6227 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-08 11:23:18.451  6227  6227 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-08 11:23:18.452  6269  6269 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-08 11:23:18.452  6269  6269 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-08 11:23:18.452  6269  6269 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-08 11:23:18.453  6227  6227 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-08 11:23:18.453  6227  6227 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-08 11:23:18.453  6227  6227 V SoundPool: doLoad: loading sample sampleID=1
08-08 11:23:18.454  6227  6281 V SoundPool: Start decode
08-08 11:23:18.454  6227  6281 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-08 11:23:18.454   313   313 V MediaPlayerService: decode(23, 10857164, 17813)
08-08 11:23:18.454   313   313 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-08 11:23:18.454   313   313 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-08 11:23:18.454   313   313 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-08 11:23:18.454  6269  6269 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-08 11:23:18.454   313   313 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-08 11:23:18.455   313   313 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-08 11:23:18.455   313   313 V MediaPlayerService: player type = 3
08-08 11:23:18.455   313   313 V AwesomePlayer: AwesomePlayer create()
08-08 11:23:18.455  6269  6269 D dhcpcd  : wlan0: sending REQUEST (xid 0x12510334), next in 3.93 seconds
08-08 11:23:18.455   313   313 V AwesomePlayer: reset_l() 
08-08 11:23:18.455   313   313 V AwesomePlayer: cancelPlayerEvents
08-08 11:23:18.455   313   313 V AwesomePlayer: setAudioSink() 
08-08 11:23:18.455   313   313 V AwesomePlayer: reset_l() 
08-08 11:23:18.455   313   313 V AudioCache: notify(0xb16a6840, 8, 0, 0)
08-08 11:23:18.455   313   313 V AudioCache: ignored
08-08 11:23:18.455   313   313 V AwesomePlayer: cancelPlayerEvents
08-08 11:23:18.455   313   313 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-08 11:23:18.455   313   313 V AwesomePlayer: setDataSource_l dataSource
08-08 11:23:18.455   313   313 V LGParserOSAL: SniffLGParser start
08-08 11:23:18.455   313   313 V LGParserOSAL: MainType:5, SubType=0
08-08 11:23:18.455   313   313 V LGParserOSAL: #### check Mime : application/ogg
08-08 11:23:18.455   313   313 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-08 11:23:18.455   313   313 E MediaExtractor: Use LGExtractor :application/ogg 
08-08 11:23:18.456  6227  6227 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-08 11:23:18.459  5874  5874 D UEI.SmartControl: QS Service created
08-08 11:23:18.460  6227  6227 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-08 11:23:18.461  6227  6227 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-08 11:23:18.462  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-08 11:23:18.477  5874  5874 I UEI.SmartControl: Service initServices...
08-08 11:23:18.477  5874  5874 D UEI.SmartControl: QS start get config
08-08 11:23:18.484  6227  6227 V LGMDMManager: Create singleton instance
,08-08 11:23:18.494   313   313 V LGParserOSAL: supported mime: application/ogg
08-08 11:23:18.494   313   313 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-08 11:23:18.494   313   313 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-08 11:23:18.494   313   313 V AwesomePlayer: mBitrate = -1 bits/sec
08-08 11:23:18.494   313   313 V AwesomePlayer: AudioTrack Setting
08-08 11:23:18.494   313   313 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-08 11:23:18.494   313   313 V AwesomePlayer: setAudioSource() 
08-08 11:23:18.494   313   313 V MediaPlayerService: prepare
08-08 11:23:18.494   313   313 V AwesomePlayer: prepareAsync_l() 
08-08 11:23:18.494   313   313 V MediaPlayerService: wait for prepare
08-08 11:23:18.494   313  6282 V AwesomePlayer: onPrepareAsyncEvent() 
08-08 11:23:18.494   313  6282 V AwesomePlayer: initAudioDecoder() 
08-08 11:23:18.494   313  6282 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-08 11:23:18.494   313  6282 V AudioSystem: isOffloadSupported()
08-08 11:23:18.494   313  6282 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-08 11:23:18.494   313  6282 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-08 11:23:18.494   313  6282 I AudioFlinger: isAudioPlaybackHookOn() false
08-08 11:23:18.494   313  6282 V AwesomePlayer: getUseOffload() = 0 
08-08 11:23:18.494   313  6282 V OMXCodec: OMXCodec::Create
08-08 11:23:18.494   313  6282 V OMXCodec: findMatchingCodecs()
08-08 11:23:18.494   313  6282 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-08 11:23:18.494   313  6282 V OMXCodec: matchingCodecs.size()=1
08-08 11:23:18.494   313  6282 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-08 11:23:18.496   313  6282 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-08 11:23:18.496   313  6282 V LGCodecAdapter: LG Codec Adapter start
08-08 11:23:18.496   313  6282 V OMXCodec: OMXCodec Createtor
08-08 11:23:18.496   313  6282 V OMXCodec: setComponentRole
08-08 11:23:18.496   313  6282 V OMXCodec: configureCodec protected=0
08-08 11:23:18.496   313  6282 V LGCodecAdapter: called getLGCodecSpecificData
08-08 11:23:18.496   313  6282 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-08 11:23:18.496   313  6282 V LGCodecOSAL: Called LGconfigureCodecMETA
08-08 11:23:18.496   313  6282 V LGCodecOSAL: Called LGconfigureCodecMSG
08-08 11:23:18.496   313  6282 V LGCodecOSAL: Not support LGCodec
08-08 11:23:18.496   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-08 11:23:18.496   313  6282 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-08 11:23:18.496   313  6282 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-08 11:23:18.496   313  6282 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-08 11:23:18.496   313  6282 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-08 11:23:18.497   313  6282 V AudioSystem: isOffloadSupported()
08-08 11:23:18.497   313  6282 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-08 11:23:18.497   313  6282 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-08 11:23:18.497   313  6282 V OMXCodec: init()
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-08 11:23:18.497   313  6282 V OMXCodec: allocateBuffers
08-08 11:23:18.497   313  6282 V OMXCodec: allocateBuffersOnPort portIndex=0
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-08 11:23:18.497   313  6282 V OMXCodec: allocateBuffersOnPort portIndex=1
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
,08-08 11:23:18.497   313  6282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-08 11:23:18.497   313  6282 V OMXCodec: init() mAsyncCompletion wait!!! 
08-08 11:23:18.497   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-08 11:23:18.497   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-08 11:23:18.498   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-08 11:23:18.498   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-08 11:23:18.498   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-08 11:23:18.498   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,08-08 11:23:18.499   313  6282 V OMXCodec: init() mAsyncCompletion wait free! 
08-08 11:23:18.499   313  6282 V AwesomePlayer: finishAsyncPrepare_l() 
08-08 11:23:18.499   313  6282 V AudioCache: notify(0xb16a6840, 5, 0, 0)
08-08 11:23:18.499   313  6282 V AudioCache: ignored
,08-08 11:23:18.499   313  6282 V AudioCache: notify(0xb16a6840, 1, 0, 0)
08-08 11:23:18.499   313  6282 V AudioCache: prepared
08-08 11:23:18.499   313   313 V AudioCache: wait - success
08-08 11:23:18.499   313   313 V MediaPlayerService: start
08-08 11:23:18.499   313   313 V AwesomePlayer: play_l() 
08-08 11:23:18.499   313   313 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-08 11:23:18.499   313   313 V AwesomePlayer: createAudioPlayer_l
08-08 11:23:18.499   313   313 V AwesomePlayer: seekAudioIfNecessary_l() 
,08-08 11:23:18.499   313   313 V AwesomePlayer: startAudioPlayer_l() 
08-08 11:23:18.499   313   313 D AudioPlayer: start of Playback, useOffload 0
08-08 11:23:18.499   313   313 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-08 11:23:18.499   313   313 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-08 11:23:18.501   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-08 11:23:18.501   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-08 11:23:18.501   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
,08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
,08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-08 11:23:18.502   313  6284 V OMXCodec: allocateBuffersOnPort portIndex=1,
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-08 11:23:18.502   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-08 11:23:18.503   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-08 11:23:18.503   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-08 11:23:18.503   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on output port
08-08 11:23:18.503   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-08 11:23:18.503   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
,08-08 11:23:18.504   313   313 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-08 11:23:18.504   313   313 V AudioCache: notify(0xb16a6840, 6, 0, 0)
08-08 11:23:18.504   313   313 V AudioCache: ignored
08-08 11:23:18.505   313   313 V MediaPlayerService: wait for playback complete
08-08 11:23:18.505   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.505   313  6285 V AudioCache: memcpy(0xac300000, 0xb17fa000, 4096)
,08-08 11:23:18.507   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.507   313  6285 V AudioCache: memcpy(0xac301000, 0xb17fa000, 4096)
08-08 11:23:18.507   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.507   313  6285 V AudioCache: memcpy(0xac302000, 0xb17fa000, 4096)
08-08 11:23:18.508   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.508   313  6285 V AudioCache: memcpy(0xac303000, 0xb17fa000, 4096)
08-08 11:23:18.508   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.508   313  6285 V AudioCache: memcpy(0xac304000, 0xb17fa000, 4096)
08-08 11:23:18.509   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.509   313  6285 V AudioCache: memcpy(0xac305000, 0xb17fa000, 4096),
08-08 11:23:18.512   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.512   313  6285 V AudioCache: memcpy(0xac306000, 0xb17fa000, 4096)
08-08 11:23:18.512   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.512   313  6285 V AudioCache: memcpy(0xac307000, 0xb17fa000, 4096)
08-08 11:23:18.513   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.513   313  6285 V AudioCache: memcpy(0xac308000, 0xb17fa000, 4096)
08-08 11:23:18.514   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.514   313  6285 V AudioCache: memcpy(0xac309000, 0xb17fa000, 4096)
08-08 11:23:18.515   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.515   313  6285 V AudioCache: memcpy(0xac30a000, 0xb17fa000, 4096)
08-08 11:23:18.516   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.516   313  6285 V AudioCache: memcpy(0xac30b000, 0xb17fa000, 4096)
08-08 11:23:18.517   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.517   313  6285 V AudioCache: memcpy(0xac30c000, 0xb17fa000, 4096)
08-08 11:23:18.517   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.517   313  6285 V AudioCache: memcpy(0xac30d000, 0xb17fa000, 4096)
08-08 11:23:18.518   313  6285 V AudioCache: write(0xb17fa000, 4096)
,08-08 11:23:18.518   313  6285 V AudioCache: memcpy(0xac30e000, 0xb17fa000, 4096)
08-08 11:23:18.519   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.519   313  6285 V AudioCache: memcpy(0xac30f000, 0xb17fa000, 4096)
08-08 11:23:18.520   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.520   313  6285 V AudioCache: memcpy(0xac310000, 0xb17fa000, 4096)
08-08 11:23:18.521   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.521   313  6285 V AudioCache: memcpy(0xac311000, 0xb17fa000, 4096)
08-08 11:23:18.522   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.522   313  6285 V AudioCache: memcpy(0xac312000, 0xb17fa000, 4096)
08-08 11:23:18.523   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.523   313  6285 V AudioCache: memcpy(0xac313000, 0xb17fa000, 4096)
08-08 11:23:18.524   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.524   313  6285 V AudioCache: memcpy(0xac314000, 0xb17fa000, 4096)
08-08 11:23:18.524   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.525   313  6285 V AudioCache: memcpy(0xac315000, 0xb17fa000, 4096)
08-08 11:23:18.525   313  6285 V AudioCache: write(0xb17fa000, 4096)
,08-08 11:23:18.525   313  6285 V AudioCache: memcpy(0xac316000, 0xb17fa000, 4096)
08-08 11:23:18.526   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.526   313  6285 V AudioCache: memcpy(0xac317000, 0xb17fa000, 4096)
08-08 11:23:18.527   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.527   313  6285 V AudioCache: memcpy(0xac318000, 0xb17fa000, 4096)
08-08 11:23:18.527   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.527   313  6285 V AudioCache: memcpy(0xac319000, 0xb17fa000, 4096)
08-08 11:23:18.528   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.528   313  6285 V AudioCache: memcpy(0xac31a000, 0xb17fa000, 4096)
08-08 11:23:18.529   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.529   313  6285 V AudioCache: memcpy(0xac31b000, 0xb17fa000, 4096)
08-08 11:23:18.529  6269  6269 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-08 11:23:18.530   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.530   313  6285 V AudioCache: memcpy(0xac31c000, 0xb17fa000, 4096)
,08-08 11:23:18.531   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.531   313  6285 V AudioCache: memcpy(0xac31d000, 0xb17fa000, 4096)
08-08 11:23:18.531   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.531   313  6285 V AudioCache: memcpy(0xac31e000, 0xb17fa000, 4096)
08-08 11:23:18.532   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.532   313  6285 V AudioCache: memcpy(0xac31f000, 0xb17fa000, 4096)
08-08 11:23:18.533   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.533   313  6285 V AudioCache: memcpy(0xac320000, 0xb17fa000, 4096)
08-08 11:23:18.535   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.535   313  6285 V AudioCache: memcpy(0xac321000, 0xb17fa000, 4096)
08-08 11:23:18.535   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.535   313  6285 V AudioCache: memcpy(0xac322000, 0xb17fa000, 4096)
08-08 11:23:18.536   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.536   313  6285 V AudioCache: memcpy(0xac323000, 0xb17fa000, 4096)
08-08 11:23:18.537   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.537   313  6285 V AudioCache: memcpy(0xac324000, 0xb17fa000, 4096)
08-08 11:23:18.537   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.537   313  6285 V AudioCache: memcpy(0xac325000, 0xb17fa000, 4096)
08-08 11:23:18.538   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.538   313  6285 V AudioCache: memcpy(0xac326000, 0xb17fa000, 4096)
08-08 11:23:18.539   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.539   313  6285 V AudioCache: memcpy(0xac327000, 0xb17fa000, 4096)
08-08 11:23:18.540   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.540   313  6285 V AudioCache: memcpy(0xac328000, 0xb17fa000, 4096)
08-08 11:23:18.540   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.540   313  6285 V AudioCache: memcpy(0xac329000, 0xb17fa000, 4096)
08-08 11:23:18.541   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.541   313  6285 V AudioCache: memcpy(0xac32a000, 0xb17fa000, 4096)
08-08 11:23:18.542   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.542   313  6285 V AudioCache: memcpy(0xac32b000, 0xb17fa000, 4096)
08-08 11:23:18.543   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.543   313  6285 V AudioCache: memcpy(0xac32c000, 0xb17fa000, 4096)
08-08 11:23:18.543   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.543   313  6285 V AudioCache: memcpy(0xac32d000, 0xb17fa000, 4096)
08-08 11:23:18.544   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.544   313  6285 V AudioCache: memcpy(0xac32e000, 0xb17fa000, 4096)
08-08 11:23:18.545   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.545   313  6285 V AudioCache: memcpy(0xac32f000, 0xb17fa000, 4096)
08-08 11:23:18.546   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.546   313  6285 V AudioCache: memcpy(0xac330000, 0xb17fa000, 4096)
08-08 11:23:18.547   313  6285 V AudioCache: write(0xb17fa000, 4096)
08-08 11:23:18.547   313  6285 V AudioCache: memcpy(0xac331000, 0xb17fa000, 4096)
08-08 11:23:18.547   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-08 11:23:18.547   313  6285 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-08 11:23:18.547   313  6285 V AwesomePlayer: postAudioEOS() 
,08-08 11:23:18.547   313  6285 V AudioCache: write(0xb17fa000, 280)
08-08 11:23:18.547   313  6285 V AudioCache: memcpy(0xac332000, 0xb17fa000, 280)
08-08 11:23:18.549   313  6282 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
,08-08 11:23:18.549   313  6282 V AwesomePlayer: onStreamDone
08-08 11:23:18.549   313  6282 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-08 11:23:18.549   313  6282 V AudioCache: notify(0xb16a6840, 2, 0, 0)
08-08 11:23:18.549   313  6282 V AudioCache: playback complete
08-08 11:23:18.549   313  6282 V AwesomePlayer: pause_l() 
08-08 11:23:18.549   313  6282 V AudioCache: notify(0xb16a6840, 7, 0, 0)
08-08 11:23:18.549   313  6282 V AudioCache: ignored
08-08 11:23:18.549   313  6282 V AwesomePlayer: cancelPlayerEvents
08-08 11:23:18.549   313  6282 D AudioPlayer: Pause Playback at 1068125
08-08 11:23:18.550   313   313 V AudioCache: wait - success
08-08 11:23:18.550   313   313 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-08 11:23:18.550   313   313 V AwesomePlayer: reset_l() 
08-08 11:23:18.550   313   313 V AudioCache: notify(0xb16a6840, 8, 0, 0)
08-08 11:23:18.550   313   313 V AudioCache: ignored
08-08 11:23:18.550   313   313 V AwesomePlayer: cancelPlayerEvents
08-08 11:23:18.550   313   313 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-08 11:23:18.550   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-08 11:23:18.550   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-08 11:23:18.550   313   313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-08 11:23:18.550   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 1
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-08 11:23:18.550   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-08 11:23:18.551   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-08 11:23:18.551   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-08 11:23:18.551   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-08 11:23:18.551   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-08 11:23:18.551   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-08 11:23:18.551   313  6284 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-08 11:23:18.551   313   313 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-08 11:,23:18.551   313   313 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-08 11:23:18.551   313   313 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-08 11:23:18.554   313   313 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-08 11:23:18.554   313   313 D AudioPlayer: AudioPlayer releasing audio source
08-08 11:23:18.554   313   313 D AudioPlayer: AudioPlayer done releasing audio source
08-08 11:23:18.554   313   313 V AwesomePlayer: reset_l() 
08-08 11:23:18.554   313   313 V AwesomePlayer: cancelPlayerEvents
08-08 11:23:18.554   313   313 V AwesomePlayer: ~AwesomePlayer call
08-08 11:23:18.555   313   313 V AwesomePlayer: reset_l() 
08-08 11:23:18.555   313   313 V AwesomePlayer: cancelPlayerEvents
08-08 11:23:18.555  6227  6281 V SoundPool: close(31)
08-08 11:23:18.555  6227  6281 V SoundPool: pointer = 0x9ffe4000, size = 205080, sampleRate = 48000, numChannels = 2
08-08 11:23:18.560  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-08 11:23:18.561  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-08 11:23:18.563  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5520
,08-08 11:23:18.569  6269  6269 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-08 11:23:18.569  6269  6269 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-08 11:23:18.570  6269  6269 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-08 11:23:18.570  6269  6269 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-08 11:23:18.570  6269  6269 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-08 11:23:18.570  6269  6269 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-08 11:23:18.571  6269  6269 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-08 11:23:18.571  6269  6269 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-08 11:23:18.572  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:18.578  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-08 11:23:18.579  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.579  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-08 11:23:18.580  1025  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.580  1025  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.581  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.581  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:18.582  1025  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-08 11:23:18.588  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:18.593  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:18.594  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-08 11:23:18.594  6227  6227 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-08 11:23:18.596  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:18.603  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:18.609  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:18.615  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:18.615  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:18.615  6227  6227 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-08 11:23:18.819  6222  6225 E QC-QMI  : qmi_client [6222] 13: failed to locate client data
,08-08 11:23:18.820   472   472 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-08 11:23:18.820   472   472 E QC-QMI  : QMUX qmux_client_id=13 not found in qmux client list, unable to remove
08-08 11:23:18.844  5874  5874 I UEI.SmartControl: Supports setup maps: true
,08-08 11:23:18.846  5874  5874 D UEI.SmartControl: QS start statue = true Error code = 0
08-08 11:23:18.847  5874  5874 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-08 11:23:18.847  5874  5874 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-08 11:23:18.847  5874  5874 I UEI.SmartControl: ### init IR Blaster...
08-08 11:23:18.885  5874  5874 D serial_port: Configuring serial port
08-08 11:23:18.886  5874  5874 E UEI.SmartControl: UEIBLaster setting for 616
08-08 11:23:18.886  5874  5874 I UEI.SmartControl: Setting serial record hearder size = 2
08-08 11:23:18.886  5874  5874 I UEI.SmartControl: configuring settings for MAXQ616
08-08 11:23:18.886  5874  5874 I UEI.SmartControl: Get version...
,08-08 11:23:18.901  5874  6315 D UEI.SmartControl: serial port data available: 21
,08-08 11:23:18.908  6316  6316 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
08-08 11:23:18.924  1025  6265 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-08 11:23:18.924  6317  6317 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-08 11:23:18.927  1025  6265 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-08 11:23:18.928  1025  6265 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-08 11:23:18.929  5874  5874 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-08 11:23:18.929  5874  5874 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-08 11:23:18.929  5874  5874 I UEI.SmartControl: QS saving settings...
08-08 11:23:18.929  1025  6265 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-08 11:23:18.930  5874  5874 D UEI.SmartControl: IR Blaster version: 25672567
08-08 11:23:18.930  1025  6265 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-08 11:23:18.930  1025  6265 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-08 11:23:18.930  1025  6265 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-08 11:23:18.932  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-08 11:23:18.933  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-08 11:23:18.934  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-08 11:23:18.934  1025  1529 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:18.934  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:18.934  1025  6265 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-08 11:23:18.934  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-08 11:23:18.935  1025  6265 D DhcpStateMachine: RunningState
08-08 11:23:18.935  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-08 11:23:18.935  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-08 11:23:18.936  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-08 11:23:18.937  1025  1531 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-08 11:23:18.937  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-08 11:23:18.943  5874  6315 D UEI.SmartControl: serial port data available: 4
,08-08 11:23:18.954  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-08 11:23:18.956  1025  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-08 11:23:18.957  1025  1531 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-08 11:23:18.960  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-08 11:23:18.960  1025  1531 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-08 11:23:18.962  1025  1537 D ConnectivityService: ignoring duplicate network state non-change
,08-08 11:23:18.978  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:18.979  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:18.979  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-08 11:23:18.983  1025  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-08 11:23:18.984  6063  6094 I bt_vendor: bluetooth satus is on
08-08 11:23:18.984  6063  6094 D bt_hci_bdroid: preload
08-08 11:23:18.984  6063  6182 D bt_userial_mct: userial_open(port:0)
08-08 11:23:18.984  6063  6182 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-08 11:23:18.984  1025  1537 D ConnectivityService: Adding iface wlan0 to network 100
08-08 11:23:18.985  6063  6182 I bt_vendor: Done intiailizing UART
08-08 11:23:18.986  6063  6182 I bt_vendor: Done intiailizing UART
08-08 11:23:18.986  6063  6182 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-08 11:23:18.986  6063  6182 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-08 11:23:18.987  6063  6180 I bt-btu  : btu_task received preload complete event
08-08 11:23:18.987  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-08 11:23:18.987  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-08 11:23:18.990  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-08 11:23:18.996  6063  6180 I         : BTE_InitTraceLevels -- TRC_HCI
08-08 11:23:18.996  6063  6180 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-08 11:23:18.996  6063  6320 D bt_userial_mct: Entering userial_read_thread()
08-08 11:23:18.996  6063  6180 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_AVDT
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_AVRC
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_A2D
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_BTM
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_GAP
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_SDP
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_GATT
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_SMP
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 11:23:18.997  6063  6180 I         : BTE_InitTraceLevels -- TRC_BTIF
08-08 11:23:18.999  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:18.999  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:18.999  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-08 11:23:19.000  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:19.000  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:19.002  1025  1531 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-08 11:23:19.004  1025  1025 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-08 11:23:19.011  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.014  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:19.015  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:19.015  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:19.016  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.017  5874  5874 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-08 11:23:19.020  5874  6324 I UEI.SmartControl: Device manager: loading config....
08-08 11:23:19.020  5874  6324 D UEI.SmartControl: ----------- loading internal config...
08-08 11:23:19.021  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:19.024  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-08 11:23:19.025  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.026  1937  1937 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-08 11:23:19.030  1025  1537 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-08 11:23:19.030  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.030  1025  1537 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-08 11:23:19.030  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.030  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-08 11:23:19.031  1025  1025 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-08 11:23:19.032  1025  1537 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-08 11:23:19.034  1025  1537 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
08-08 11:23:19.035  5874  6324 E UEI.SmartControl: Loading SETTINGS...
08-08 11:23:19.035  1025  1537 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-08 11:23:19.035  1025  1537 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-08 11:23:19.036  1025  1537 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-08 11:23:19.037  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.037  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.037  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-08 11:23:19.042  1025  1537 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-08 11:23:19.042  1025  1537 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.042  1025  1537 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.042  1025  1537 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.043  1025  1537 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-08 11:23:19.043  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.043  1025  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.043  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-08 11:23:19.043  5874  6324 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-08 11:23:19.043  1025  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-08 11:23:19.043  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.043  1025  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.043  1025  1537 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-08 11:23:19.043  1025  1537 D ConnectivityService: currentScore = 0, newScore = 20
08-08 11:23:19.043  1025  1537 D ConnectivityService:    accepting network in place of null
08-08 11:23:19.044  1025  1537 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.044  1025  1531 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.044  1025  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-08 11:23:19.044  1025  1537 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-08 11:23:19.045  1848  1848 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.045  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-08 11:23:19.051  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-08 11:23:19.057   309  6327 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-08 11:23:19.058  5874  5874 E UEI.SmartControl: Services init done
08-08 11:23:19.058  5874  5874 D UEI.SmartControl: QS Service init finished
08-08 11:23:19.061  1025  1537 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-08 11:23:19.061  1025  1537 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-08 11:23:19.062  1025  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-08 11:23:19.062  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-08 11:23:19.062  1597  1597 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-08 11:23:19.063  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.065  1025  1025 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-08 11:23:19.065  1025  1025 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-08 11:23:19.066  5874  5874 D UEI.SmartControl: QS Service version name: 2.1.91
08-08 11:23:19.066  5874  5874 D UEI.SmartControl: QS Service version code: 201091
08-08 11:23:19.066  5874  5874 D UEI.SmartControl: Service requested: Control
,08-08 11:23:19.067  5874  6323 I UEI.SmartControl: Notify AllClients services are ready: 0
08-08 11:23:19.067  5874  6323 D UEI.SmartControl: -----service ready thread exits
08-08 11:23:19.067  1025  1025 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-08 11:23:19.068   309  6328 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-08 11:23:19.068   309  6328 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-08 11:23:19.068  1025  1025 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-08 11:23:19.068  1025  1025 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-08 11:23:19.069   309  6328 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
08-08 11:23:19.070  1025  1085 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-08 11:23:19.074  1025  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:19.074  1025  1537 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-08 11:23:19.075  1025  1537 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-08 11:23:19.075  6227  6227 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-08 11:23:19.075  6063  6180 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-08 11:23:19.075  6063  6180 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f2061 
08-08 11:23:19.075  6063  6180 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f2061 
08-08 11:23:19.078   309  6334 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-08 11:23:19.078   309  6334 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,08-08 11:23:19.079  5874  5890 I UEI.SmartControl: ------ IControl API: 11
08-08 11:23:19.079  5874  5874 D UEI.SmartControl: Internal service binding...
08-08 11:23:19.079  5874  5890 D UEI.SmartControl: File observer start...
08-08 11:23:19.080  5874  5890 E UEI.SmartControl: IR Port is disabled: false
08-08 11:23:19.080  5874  5890 D UEI.SmartControl: Starting file observer...
08-08 11:23:19.082  5874  5890 I UEI.SmartControl: Registering callback...
08-08 11:23:19.084  5874  5889 I UEI.SmartControl: ------ IControl API: 19
08-08 11:23:19.086  6063  6098 E bt-btif : Calling BTA_HhEnable
08-08 11:23:19.086  6063  6098 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-08 11:23:19.086  6063  6098 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-08 11:23:19.086  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-08 11:23:19.086  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-08 11:23:19.086  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-08 11:23:19.087  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-08 11:23:19.087  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-08 11:23:19.084  1025  1537 D ConnectivityService: validation of new default Network = false
08-08 11:23:19.087  1025  1537 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-08 11:23:19.088  1025  1537 D DSQN    : enableDataServiceNotify 
08-08 11:23:19.088  1025  1537 D DSQN    : start dsqn bin
08-08 11:23:19.089  6063  6098 D BluetoothAdapterProperties: Name is: G3
08-08 11:23:19.089  1025  1025 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-08 11:23:19.090  1025  1025 D BluetoothManagerService: Stored Bluetooth name: G3
08-08 11:23:19.091  5874  5889 I UEI.SmartControl: Registering Services Ready callback...
08-08 11:23:19.091  5874  5889 I UEI.SmartControl: Notify client services are ready...
08-08 11:23:19.091  6227  6242 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,08-08 11:23:19.092  6227  6279 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-08 11:23:19.093  6063  6180 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-08 11:23:19.093  6063  6180 W bt-smp  : Plain text(LSB ~ MSB) = af e9 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-08 11:23:19.093  6063  6180 W bt-smp  : Encrypted text(LSB ~ MSB) = e8 89 93 d8 1e e4 73 7b 7d d8 41 4e 04 fc d8 89 
08-08 11:23:19.093  6063  6180 W bt-btm  : Stopping oneshot timer
08-08 11:23:19.093  6227  6279 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
,08-08 11:23:19.098  1025  1528 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-08 11:23:19.098  1025  1537 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.098  1025  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.098  1025  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.099  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-08 11:23:19.099  1025  1537 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.099  1597  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-08 11:23:19.100  6063  6098 D BluetoothAdapterProperties: Scan Mode:20
08-08 11:23:19.100  6063  6098 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 11:23:19.100  6063  6098 D bt_hci_bdroid: postload
08-08 11:23:19.089  6336  6336 W dsqn    : type=1400 audit(0.0:161): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:19.101  6063  6180 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-08 11:23:19.101  6063  6182 D bt_hci_bdroid: Used up Tx Cmd credits
08-08 11:23:19.102  6063  6320 E bt_mct  : hci lib postload completed
08-08 11:23:19.089  6336  6336 W dsqn    : type=1400 audit(0.0:162): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:19.102  6063  6098 D bte_conf: Device ID record 1 : primary
08-08 11:23:19.102  6063  6098 D bte_conf:   vendorId            = 00c4
08-08 11:23:19.102  6063  6098 D bte_conf:   vendorIdSource      = 0001
08-08 11:23:19.102  6063  6098 D bte_conf:   product             = 13a1
08-08 11:23:19.102  6063  6098 D bte_conf:   version             = 1000
08-08 11:23:19.103  6063  6098 D bte_conf:   clientExecutableURL = 
08-08 11:23:19.103  6063  6098 D bte_conf:   serviceDescription  = 
08-08 11:23:19.103  6063  6098 D bte_conf:   documentationURL    = 
08-08 11:23:19.103  6063  6098 D bte_conf: bte_load_did_conf no section named DID2.
08-08 11:23:19.105  6063  6094 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-08 11:23:19.106  6063  6094 D BluetoothAdapterProperties: ScanMode =  20
08-08 11:23:19.089  6338  6338 W sh      : type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:19.106  6063  6094 D BluetoothAdapterProperties: State =  11
08-08 11:23:19.106  6063  6094 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-08 11:23:19.106  6227  6227 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-08 11:23:19.089  6338  6338 W sh      : type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:19.106  6063  6098 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-08 11:23:19.107  6227  6227 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-08 11:23:19.107   309  6327 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-08 11:23:19.107  6063  6094 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-08 11:23:19.107  6063  6094 D BluetoothAdapterProperties: Setting state to 12
08-08 11:23:19.107  6063  6094 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 11:23:19.108  6063  6098 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-08 11:23:19.115  1025  1087 D BluetoothManagerService: Message: 60
08-08 11:23:19.115  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-08 11:23:19.115  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 5 receivers.
08-08 11:23:19.115  1025  1087 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:23:19.116  5874  5911 I UEI.SmartControl: ------ IControl API: 8
08-08 11:23:19.116  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:23:19.116  1025  1087 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 11:23:19.117  1848  2456 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:23:19.117  5992  5992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-08 11:23:19.117  1848  4095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:23:19.117  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:19.117  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:19.117  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:19.117  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:19.117  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:19.117  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 11:23:19.117  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 11:23:19.117  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 11:23:19.119  6063  6094 I BluetoothAdapterState: Entering On State
08-08 11:23:19.120  6227  6227 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-08 11:23:19.120  6227  6227 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-08 11:23:19.120  6227  6227 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,08-08 11:23:19.123  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 11:23:19.123  6336  6336 E DSQN    : DSQN ssw
08-08 11:23:19.124  6227  6227 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-08 11:23:19.126  1025  1087 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-08 11:23:19.126  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-08 11:23:19.127  6227  6227 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-08 11:23:19.129   309  6334 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
08-08 11:23:19.131  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:19.131  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:19.131  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:19.131  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:19.131  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:19.131  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 11:23:19.131  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 11:23:19.131  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 11:23:19.131  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:19.131  6063  6094 D LGBluetoothServiceAdapter: [BTUI] OnState
08-08 11:23:19.131  6063  6094 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-08 11:23:19.131  6063  6094 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-08 11:23:19.132  1937  2116 D LGBluetoothAPIService: Message: 1
08-08 11:23:19.132  1937  2116 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-08 11:23:19.133  6063  6094 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-08 11:23:19.135  6227  6227 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-08 11:23:19.136  1025  1025 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-08 11:23:19.139   309  6327 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-08 11:23:19.144  6063  6063 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:19.144  6063  6063 D BluetoothMapService: STATE_ON
,08-08 11:23:19.149  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 11:23:19.151  1937  2116 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-08 11:23:19.152  5992  5992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-08 11:23:19.153  5992  5992 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-08 11:23:19.154  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:19.158  1025  1087 D BluetoothManagerService: Message: 40
08-08 11:23:19.158  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-08 11:23:19.160  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:19.160  6063  6063 V BluetoothPbapService: Pbap Service onCreate
08-08 11:23:19.160  6063  6063 V BluetoothPbapService: Starting PBAP service
08-08 11:23:19.160  6227  6227 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-08 11:23:19.163  6347  6347 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-08 11:23:19.165  6063  6063 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-08 11:23:19.165  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:19.165  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:19.165  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:19.165  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:19.165  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:19.165  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 11:23:19.165  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 11:23:19.165  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 11:23:19.165  6063  6063 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:19.165  6063  6063 V BluetoothPbapService: state: 12
08-08 11:23:19.165  6063  6063 V BluetoothMapService: Handler(): got msg=1
08-08 11:23:19.166  6063  6063 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-08 11:23:19.167  6227  6227 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-08 11:23:19.167  6063  6348 D BluetoothMapMasInstance: MAS initSocket()
08-08 11:23:19.168  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 11:23:19.168  6063  6348 D BluetoothMapMasInstance:   masId = 00
08-08 11:23:19.168  6063  6348 D BluetoothMapMasInstance:   msgTypes = 0e
08-08 11:23:19.168  6063  6348 D BluetoothMapMasInstance:   masName = SMS/MMS
08-08 11:23:19.168  6063  6348 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-08 11:23:19.168  6063  6063 D LGBluetoothAPIServer: [BTUI] onCreate()
08-08 11:23:19.168  6063  6094 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-08 11:23:19.169  6063  6063 D LGBluetoothAPIServer: [BTUI] onBind()
08-08 11:23:19.170  1025  1955 I ActivityManager: Killing 5595:com.android.contacts/u0a19 (adj 15): empty #17
08-08 11:23:19.170  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:19.172  1025  6329 D LocSvc_java: NTP server : europe.pool.ntp.org
08-08 11:23:19.172  1025  6329 D LocSvc_java: NTP server returned: 1470648198854 (Mon Aug 08 11:23:18 GMT+02:00 2016) reference: 357340 certainty: 20 system time offset: -318
08-08 11:23:19.172  1025  6329 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
,08-08 11:23:19.174  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-08 11:23:19.176  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.177  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.177  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-08 11:23:19.182   309   898 D LGDataListener: argv[0]=dsqncommand
08-08 11:23:19.182   309   898 D LGDataListener: argv[1]=wlan0
08-08 11:23:19.182   309   898 D LGDataListener: argv[2]=1
08-08 11:23:19.182   309   898 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-08 11:23:19.183  1025  1085 D DSQN    : DSQM DsqnNotification wlan0  1
08-08 11:23:19.183  1025  1085 D DSQN    : start to monitor internet connection
08-08 11:23:19.199  1025  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-08 11:23:19.200  6063  6063 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-08 11:23:19.200  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-08 11:23:19.200  6063  6063 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:19.200  6063  6063 V BluetoothPbapReceiver: ***********state = 12
08-08 11:23:19.200  1937  2116 D LGBluetoothAPIService: Message: 100
08-08 11:23:19.200  1937  2116 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-08 11:23:19.201  1025  1041 W libprocessgroup: failed to open /acct/uid_10019/pid_5595/cgroup.procs: No such file or directory
08-08 11:23:19.201  6120  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-08 11:23:19.201  6063  6063 V BluetoothPbapService: Handler(): got msg=1
08-08 11:23:19.202  6063  6348 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:19.202  6063  6063 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-08 11:23:19.203  6063  6348 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-08 11:23:19.203  6063  6348 V BluetoothMapMasInstance: Succeed to create listening socket 
08-08 11:23:19.203  6063  6348 D BluetoothMapMasInstance: Accepting socket connection...
08-08 11:23:19.204  6063  6352 V BluetoothPbapService: Pbap Service initSocket
08-08 11:23:19.204  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:23:19.204  1025  2618 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:19.204  2203  2203 D c       : Getting all permits...
08-08 11:23:19.204  2203  2203 D a       : Opening database...
08-08 11:23:19.205  6063  6352 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:19.208  2203  2203 D a       : Opening database auth.proximity.permit_store...
08-08 11:23:19.208  6063  6352 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-08 11:23:19.208  6063  6352 V BluetoothPbapService: Succeed to create listening socket 
08-08 11:23:19.208  6063  6352 V BluetoothPbapService: Accepting socket connection...
08-08 11:23:19.209  2203  2203 D a       : Closing database...
08-08 11:23:19.224  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Aug 2016 09:23:18 GMT], X-Android-Received-Millis=[1470648199223], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470648199182]}
08-08 11:23:19.224  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-08 11:23:19.224  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-08 11:23:19.224  6120  6120 D LocalBluetoothProfileManager: Adding local A2DP profile
08-08 11:23:19.224  1025  1537 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.224  1025  1537 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.224  1025  1537 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-08 11:23:19.224  1025  1537 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.224  1025  1537 D Connectivity,Service:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-08 11:23:19.225  1025  1537 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-08 11:23:19.225  1025  1537 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.225  1025  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.225  1025  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.225  1025  1537 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.225  1025  1537 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.225  1597  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-08 11:23:19.225  1025  1531 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.225  1025  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-08 11:23:19.225  1025  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-08 11:23:19.226  1848  1848 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.226  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-08 11:23:19.226  1025  1087 D BluetoothManagerService: Message: 30
08-08 11:23:19.230  6120  6120 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-08 11:23:19.232  1025  1087 D BluetoothManagerService: Message: 30
08-08 11:23:19.237  1025  1087 D BluetoothManagerService: Message: 30
,08-08 11:23:19.242  1025  1087 D BluetoothManagerService: Message: 30
08-08 11:23:19.244  6120  6120 D LocalBluetoothProfileManager: Adding local MAP profile
08-08 11:23:19.245  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-08 11:23:19.245  6120  6120 D BluetoothMap: Create BluetoothMap proxy object
08-08 11:23:19.245  6063  6098 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 11:23:19.245  6063  6098 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-08 11:23:19.245  1025  1087 D BluetoothManagerService: Message: 30
,08-08 11:23:19.246  6063  6098 D BluetoothAdapterProperties: Scan Mode:21
08-08 11:23:19.246  6063  6098 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-08 11:23:19.247  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:19.248  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.248  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.248  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:19.250  1025  1087 D BluetoothManagerService: Message: 30
,08-08 11:23:19.251  6120  6120 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-08 11:23:19.251  6063  6063 V BluetoothPbapService: Pbap Service onBind
08-08 11:23:19.254  6120  6120 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-08 11:23:19.256  6120  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-08 11:23:19.261  6120  6120 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:23:19.263  6120  6120 D BluetoothA2dp: Proxy object connected
08-08 11:23:19.264  6120  6120 D A2dpProfile: Bluetooth service connected
08-08 11:23:19.266  6120  6120 D BluetoothHeadset: Proxy object connected
08-08 11:23:19.267  6120  6120 D HeadsetProfile: Bluetooth service connected
08-08 11:23:19.268  6120  6120 D BluetoothInputDevice: Proxy object connected
08-08 11:23:19.268  6120  6120 D HidProfile: Bluetooth service connected
08-08 11:23:19.269  6120  6120 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 11:23:19.270  6120  6120 D PanProfile: Bluetooth service connected
08-08 11:23:19.271  6120  6120 D BluetoothMap: Proxy object connected
08-08 11:23:19.271  6120  6120 D MapProfile: Bluetooth service connected
08-08 11:23:19.271  6120  6120 D BluetoothMap: getConnectedDevices()
08-08 11:23:19.271  6063  6101 V BluetoothMapService: getConnectedDevices()
08-08 11:23:19.272  6120  6120 D BluetoothPbap: Proxy object connected
08-08 11:23:19.272  6120  6120 D PbapServerProfile: Bluetooth service connected
,08-08 11:23:19.272  6120  6120 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-08 11:23:19.273  6120  6120 D BluetoothPermissionRequest: onReceive
08-08 11:23:19.275  6120  6120 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-08 11:23:19.275  6120  6120 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-08 11:23:19.275  6120  6120 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-08 11:23:19.277  6063  6063 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-08 11:23:19.278  6063  6063 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-08 11:23:19.279  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:19.279  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:19.283  6227  6227 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-08 11:23:19.286  6063  6063 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-08 11:23:19.286  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:19.291  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:19.296  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:19.298  6063  6063 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-08 11:23:19.298  6063  6063 V BtOppService: onCreate
08-08 11:23:19.301  6063  6063 V BluetoothOppNotification: send message
08-08 11:23:19.303  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:19.303  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:19.304  6063  6063 V BtOppService: Starting RfcommListener
08-08 11:23:19.304  6227  6227 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-08 11:23:19.307  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:19.308  6063  6063 D BluetoothOppPreference: Dumping Names:  
08-08 11:23:19.308  6063  6063 D BluetoothOppPreference: {}
08-08 11:23:19.308  6063  6063 D BluetoothOppPreference: Dumping Channels:  
08-08 11:23:19.308  6063  6063 D BluetoothOppPreference: {}
08-08 11:23:19.309  6063  6063 V BtOppService: onStartCommand
08-08 11:23:19.309  6063  6362 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-08 11:23:19.310  6143  6143 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-08 11:23:19.312  6063  6063 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:19.312  6063  6063 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-08 11:23:19.314  6063  6063 V BluetoothOppNotification: new notify threadi!
08-08 11:23:19.314  6063  6063 V BluetoothOppNotification: send delay message
08-08 11:23:19.315  6063  6063 V BtOppService: start RfcommListener
08-08 11:23:19.317  6063  6063 V BtOppService: RfcommListener started
08-08 11:23:19.318  6063  6364 V BtOppRfcommListener: Starting RFCOMM listener....
08-08 11:23:19.319  1025  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:19.319  6063  6364 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:19.320  1025  1531 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-08 11:23:19.321  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-08 11:23:19.321  1025  1531 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-08 11:23:19.322  1025  1531 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-08 11:23:19.322  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-08 11:23:19.323  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-08 11:23:19.323  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-08 11:23:19.324  6063  6364 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-08 11:23:19.324  1025  1537 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
08-08 11:23:19.324  6063  6364 V BtOppRfcommListener: Started RFCOMM listener....
08-08 11:23:19.324  6063  6364 I BtOppRfcommListener: Accept thread started.
08-08 11:23:19.324  6063  6364 V BtOppRfcommListener: Accepting connection...
08-08 11:23:19.324  1025  1537 D ConnectivityService: identical MTU - not setting
08-08 11:23:19.324  1025  1537 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-08 11:23:19.324  1025  1537 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.324  1025  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.324  1025  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.325  6063  6362 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-08 11:23:19.325  1025  1537 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.325  6063  6363 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-08 11:23:19.327  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-08 11:23:19.327  1597  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-08 11:23:19.327  6063  6362 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32d97b4d on behalf of 
08-08 11:23:19.329  6063  6363 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14b92602 on behalf of 
08-08 11:23:19.330  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:19.330  6063  6063 V BluetoothFtpService: Ftp Service onCreate
08-08 11:23:19.330  6063  6063 I BluetoothFtpService: Ftp Service onCreate
08-08 11:23:19.330  6063  6063 V BluetoothFtpService: Ftp Service onStartCommand
08-08 11:23:19.330  6063  6063 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:19.330  6063  6063 V BluetoothFtpService: Starting Listening on sockets
08-08 11:23:19.330  6063  6063 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-08 11:23:19.330  6063  6063 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-08 11:23:19.330  6063  6063 V BluetoothSapReceiver: SapReceiver onReceive 
08-08 11:23:19.330  6063  6063 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:19.330  6063  6063 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-08 11:23:19.331  6063  6063 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-08 11:23:19.332  6063  6359 V BtOppService: Deleted complete outbound shares, number =  0
08-08 11:23:19.332  6063  6063 V BluetoothFtpService: Handler(): got msg=1
,08-08 11:23:19.333  6063  6063 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-08 11:23:19.333  6063  6063 V BluetoothFtpService: Ftp Service initSocket
08-08 11:23:19.333  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:19.335  1025  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:19.335  6063  6063 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:19.335  6063  6362 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-08 11:23:19.335  6063  6362 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-08 11:23:19.337  6063  6363 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-08 11:23:19.339  6063  6363 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-08 11:23:19.340  6063  6359 V BtOppService: Deleted complete inbound failed shares, number = 0
08-08 11:23:19.341  6063  6359 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-08 11:23:19.341  6063  6362 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5ede150 on behalf of 
08-08 11:23:19.341  6063  6363 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14cf7f49 on behalf of 
08-08 11:23:19.341  6063  6063 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-08 11:23:19.341  6063  6063 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-08 11:23:19.342  6063  6362 V BluetoothOppNotification: update too frequent, put in queue
08-08 11:23:19.342  6063  6363 V BluetoothOppNotification: outbound: succ-0  fail-0
08-08 11:23:19.343  6063  6365 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-08 11:23:19.343  6063  6359 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1097a04e on behalf of 
08-08 11:23:19.344  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:19.344  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:19.344  6063  6362 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-08 11:23:19.345  6227  6227 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-08 11:23:19.346  6227  6227 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-08 11:23:19.346  6227  6227 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-08 11:23:19.348  6063  6363 V BluetoothOppNotification: outbound notification was removed.
08-08 11:23:19.348  6063  6363 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-08 11:23:19.349  6063  6363 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dbb356f on behalf of 
08-08 11:23:19.350  6063  6363 V BluetoothOppNotification: inbound: succ-0  fail-0
08-08 11:23:19.350  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:19.351  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:19.351  6063  6063 V BluetoothSapService: Sap Service onCreate
08-08 11:23:19.351  6063  6363 V BluetoothOppNotification: inbound notification was removed.
08-08 11:23:19.351  6063  6363 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-08 11:23:19.353  6143  6143 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-08 11:23:19.353  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-08 11:23:19.354  6063  6063 V BtOppService: ContentObserver received notification
08-08 11:23:19.354  6063  6063 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:19.354  6063  6063 V BluetoothSapService: state: 12
08-08 11:23:19.354  6063  6063 V BluetoothSapService: Starting SAP server process
08-08 11:23:19.355  6063  6063 V BtOppService: ContentObserver received notification
08-08 11:23:19.355  6063  6366 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-08 11:23:19.356  6063  6366 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-08 11:23:19.339  6367  6367 W sapd    : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-08 11:23:19.339  6367  6367 W sapd    : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:19.361  6063  6063 V BluetoothSapService: SAP Service startRfcommListenerThread
08-08 11:23:19.362  6063  6368 V BluetoothSapService: Sap Service initRfcommSocket
,08-08 11:23:19.362  1025  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:19.363  6063  6368 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:19.364  6063  6368 V BluetoothSapService: Succeed to create listening socket 
08-08 11:23:19.364  6063  6368 V BluetoothSapService: Accepting socket connection...
08-08 11:23:19.366  6367  6367 V BT_SAP  : Event pipe created
08-08 11:23:19.367  6367  6367 V BT_SAP  : create_server_socket qcom.sap.server
08-08 11:23:19.367  6367  6367 V BT_SAP  : created socket fd 6
08-08 11:23:19.452  1025  1977 I art     : Explicit concurrent mark sweep GC freed 78981(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.870ms total 99.314ms
08-08 11:23:19.454  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-08 11:23:19.455  6063  6363 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@11efb98b on behalf of 
08-08 11:23:19.455  6063  6366 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a1c8a68 on behalf of 
,08-08 11:23:19.458  6063  6366 V BluetoothOppNotification: update too frequent, put in queue
08-08 11:23:19.460  6063  6366 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-08 11:23:19.461  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:19.467  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:19.467  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-08 11:23:19.467  6227  6227 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-08 11:23:19.468  6227  6227 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-08 11:23:19.468  6227  6227 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-08 11:23:19.485  6227  6227 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-08 11:23:19.486  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-08 11:23:19.487  6227  6227 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-08 11:23:19.487  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-08 11:23:19.488  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-08 11:23:19.488  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-08 11:23:19.489  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-08 11:23:19.489  6227  6227 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470648199489]
08-08 11:23:19.530  6227  6369 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-08 11:23:19.537  6227  6227 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-08 11:23:19.539  6227  6227 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-08 11:23:19.540  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-08 11:23:19.541  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-08 11:23:19.541  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-08 11:23:19.542  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-08 11:23:19.543  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-08 11:23:19.562  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-08 11:23:19.805  1025  1883 D WifiServiceImplEx: setWifiEnabled: false pid=5992, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-08 11:23:19.805  1025  1883 D WifiService: setWifiEnabled: false pid=5992, uid=10118
08-08 11:23:19.805  1025  1883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 11:23:19.825  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-08 11:23:19.825  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-08 11:23:19.826  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-08 11:23:19.827  1025  1531 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-08 11:23:19.828  1025  1531 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-08 11:23:19.828  1025  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-08 11:23:19.829  1025  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-08 11:23:19.829  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-08 11:23:19.829  1025  1531 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-08 11:23:19.830  1025  1531 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-08 11:23:19.830  1025  1531 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-08 11:23:19.830  1025  1531 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-08 11:23:19.830  1025  1531 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-08 11:23:19.837  1025  1531 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-08 11:23:19.837  1025  1529 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.837  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.837  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-08 11:23:19.838  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-08 11:23:19.838  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-08 11:23:19.838  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
,08-08 11:23:19.839  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-08 11:23:19.840  1025  6265 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.844   309   899 D CommandListener: Clearing all IP addresses on wlan0
08-08 11:23:19.879  1025  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-08 11:23:19.880  1025  1537 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-08 11:23:19.902  1025  1025 D WifiHS20: hidePasspointNotification off =false
,08-08 11:23:19.908  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:19.909  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:19.914  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.916  1937  1937 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-08 11:23:19.921  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-08 11:23:19.922  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.922  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-08 11:23:19.926  1025  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:19.926  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:19.927  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:19.927  1025  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:19.928  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-08 11:23:19.928  1025  1531 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-08 11:23:19.934  1025  1529 D LGWifiP2pService: InactiveState{ when=-8ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.934  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.934  1025  1529 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2e97cac8
08-08 11:23:19.934  1025  1529 D LGWifiP2pService: P2pDisablingState
08-08 11:23:19.935  1025  1529 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.935  1025  1529 D LGWifiP2pService: p2p socket connection lost
08-08 11:23:19.935  1025  1529 D LGWifiP2pService: P2pDisabledState
08-08 11:23:19.935  1025  1025 D WifiHS20: hidePasspointNotification off =false
08-08 11:23:19.935  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.935  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.936  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-08 11:23:19.936  1025  1025 D WifiScanningService: SCAN_AVAILABLE : 1
08-08 11:23:19.936  1025  1025 D RttService: SCAN_AVAILABLE : 1
08-08 11:23:19.936  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:19.938  1025  1548 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.939  1025  1549 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.940  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-08 11:23:19.940  1937  1937 D WfdsService: WifiP2pState is changed : false
08-08 11:23:19.941  1937  2299 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-08 11:23:19.941  1937  2299 D WfdsService: Set the WFDS Monitor: false
08-08 11:23:19.942  1937  2299 D WfdsMonitor: WFDS Monitor is stopped
08-08 11:23:19.942  1937  2299 D WfdsService: STATE : WfdsDisabledState - enter
08-08 11:23:19.942  1937  6162 D CtrlSupplicant: Received on exit socket, terminate
08-08 11:23:19.942  1937  6162 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-08 11:23:19.942  1937  6162 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-08 11:23:19.942  1937  2302 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-08 11:23:19.943  1937  6162 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-08 11:23:19.944  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:19.944  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-08 11:23:19.945  6143  6143 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-08 11:23:19.945  6143  6143 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-08 11:23:19.945  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-08 11:23:19.947  1937  2299 W WfdsService: DefaultState - msg [9445378] is not handled
08-08 11:23:19.948  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.949  1025  1531 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-08 11:23:19.950  1025  1531 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-08 11:23:19.950  1025  1529 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.950  1025  1529 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.951  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-08 11:23:19.951  6100  6100 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-08 11:23:19.953  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-08 11:23:19.953  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
08-08 11:23:19.954  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-08 11:23:19.957   309   899 D CommandListener: Clearing all IP addresses on wlan0
08-08 11:23:19.957  1025  1537 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-08 11:23:19.957  1025  1537 D DSQN    : disableDataServiceNotify
08-08 11:23:19.957  1025  1537 D DSQN    : stop dsqn bin
,08-08 11:23:19.963  1025  1531 D WifiNative-p2p0: doBoolean: TERMINATE
08-08 11:23:19.963  1025  1025 D WifiHS20: hidePasspointNotification off =false
08-08 11:23:19.964  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-08 11:23:19.965  1025  1537 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-08 11:23:19.965  1025  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.965  1025  1537 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.965  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-08 11:23:19.965  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:19.965  1025  1537 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-08 11:23:19.966  1025  1531 D WifiNative-p2p0: TERMINATE: returned true
08-08 11:23:19.966  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-08 11:23:19.966  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-08 11:23:19.966  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-08 11:23:19.967  1597  2066 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-08 11:23:19.967  1025  1537 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-08 11:23:19.967  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.967  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:19.967  1025  6255 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-08 11:23:19.968  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:19.969  1025  1537 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-08 11:23:19.969  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.969  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.969  1025  1537 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-08 11:23:19.970  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-08 11:23:19.970  1025  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-08 11:23:19.971  1025  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:19.971  1025  1537 D, ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-08 11:23:19.973  1025  1528 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-08 11:23:19.973  1025  1025 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-08 11:23:19.978  1025  1537 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:19.978  1025  1537 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.979  1025  1537 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.979  1025  1528 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-08 11:23:19.979  1025  1537 D NetworkManagementService: Removing idletimer
08-08 11:23:19.979  1848  1848 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.980  1848  1848 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-08 11:23:19.980  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-08 11:23:19.980  1025  1531 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-08 11:23:19.980  1025  1025 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-08 11:23:19.980  1025  1531 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-08 11:23:19.980  1025  1025 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-08 11:23:19.980  1025  1025 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-08 11:23:19.980  1025  1537 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:19.980  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-08 11:23:19.980  1025  1025 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-08 11:23:19.981  1025  1025 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-08 11:23:19.981  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-08 11:23:19.981  1025  1537 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-08 11:23:19.981  1025  1025 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-08 11:23:19.981  1025  1025 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-08 11:23:19.982  1025  1025 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-08 11:23:19.984  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:19.984  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:19.984  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:19.984  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:23:19.984  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:19.984  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:19.984  5992  5992 V io.jxcore.node.ConnectivityMonitor:,     - is connected/connecting to active network: false
08-08 11:23:19.984  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 11:23:19.987  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:19.989  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:19.991  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:19.991  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:19.991  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:19.991  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:23:19.991  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:19.991  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:19.991  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:19.991  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:19.992  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:19.999  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:19.999  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-08 11:23:20.002  6227  6227 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-08 11:23:20.004  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:20.007  6143  6143 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-08 11:23:20.007  6143  6143 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-08 11:23:20.007  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-08 11:23:20.011  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:20.013  6100  6100 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-08 11:23:20.014  6100  6100 I wpa_supplicant: monitor socket send errors count : 1
08-08 11:23:20.014  6100  6100 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1937-2\x00 that cannot receive messages
08-08 11:23:20.014  1025  6142 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-08 11:23:20.014  1025  6142 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-08 11:23:20.024  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:20.030  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-08 11:23:20.030  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:20.031  6227  6227 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-08 11:23:20.031  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-08 11:23:20.032  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:20.033  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-08 11:23:20.033  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:20.035  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:20.038  6143  6143 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-08 11:23:20.038  6143  6143 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-08 11:23:20.038  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-08 11:23:20.038  6100  6100 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-08 11:23:20.039  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-08 11:23:20.039  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-08 11:23:20.039  1025  6142 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-08 11:23:20.039  6100  6100 W wpa_supplicant: USIM:  scard_deinit function
08-08 11:23:20.039  1025  6142 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-08 11:23:20.039  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-08 11:23:20.040  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-08 11:23:20.040  1025  1531 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=358208
08-08 11:23:20.040  1025  1531 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=358209
08-08 11:23:20.041  1025  1531 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=358209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-08 11:23:20.041  1025  1531 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=358209  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-08 11:23:20.042  1025  1087 D Tethering: InitialState.processMessage what=4
08-08 11:23:20.043  1025  1087 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-08 11:23:20.043  1025  1531 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:20.044  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:20.046  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-08 11:23:20.053  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:20.059  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-08 11:23:20.059  1025  6265 D DhcpStateMachine: StoppedState
08-08 11:23:20.059  1025  6265 D DhcpStateMachine: StoppedState{ when=-105ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:20.059  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-08 11:23:20.060  1025  1531 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-08 11:23:20.060  1025  1531 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-08 11:23:20.061  1597  1597 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-08 11:23:20.062  6227  6227 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-08 11:23:20.062  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:20.062  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:20.070  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-08 11:23:20.073  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-08 11:23:20.078  6102  6395 W FormManager: Network not available. Please check & try again.
,08-08 11:23:20.082  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:20.087  6102  6396 V FormManager: Network unavailable.
08-08 11:23:20.090  6102  6396 V FormManager: Network unavailable.
,08-08 11:23:20.095  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-08 11:23:20.095  6120  6120 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-08 11:23:20.095  6120  6120 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-08 11:23:20.095  6120  6120 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-08 11:23:20.096  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-08 11:23:20.100  6100  6100 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-08 11:23:20.100  1025  6142 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-08 11:23:20.100  1025  6142 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-TERMINATING 
08-08 11:23:20.100  1025  6142 D WifiMonitor: Disconnecting from the supplicant, no more events
08-08 11:23:20.101  1025  1531 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 23 0
08-08 11:23:20.101  6120  6120 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-08 11:23:20.101  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-08 11:23:20.101  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-08 11:23:20.101  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-08 11:23:20.101  6120  6120 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-08 11:23:20.102  6120  6120 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-08 11:23:20.205  1937  1937 D WfdsService: Supplicant Connection state is changed : false
08-08 11:23:20.206  1937  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-08 11:23:20.207  1937  2299 D WfdsService: Set the WFDS Monitor: false
08-08 11:23:20.207  1937  2299 D WfdsMonitor: WFDS Monitor is stopped
,08-08 11:23:20.209  1025  1531 D WifiOffDelayIfNotUsed: stopMonitoring
08-08 11:23:20.211  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-08 11:23:20.211  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-08 11:23:20.211  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-08 11:23:20.211  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-08 11:23:20.212  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-08 11:23:20.217  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:20.217  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:20.218  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-08 11:23:20.224  2477  2477 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:20.225  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-08 11:23:20.230  1025  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
,08-08 11:23:20.231  1025  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-08 11:23:20.235  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:20.235  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:20.235  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:20.235  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:23:20.235  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:20.235  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:20.235  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:20.235  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:20.236  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:20.236  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:20.247  3254  6397 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-08 11:23:20.247  3254  6398 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-08 11:23:20.247  3254  6398 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-08 11:23:20.255  6143  6143 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-08 11:23:20.255  6143  6143 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-08 11:23:20.255  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-08 11:23:20.261  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-08 11:23:20.268  6102  6400 W FormManager: Network not available. Please check & try again.
08-08 11:23:20.270  6102  6401 V FormManager: Network unavailable.
08-08 11:23:20.271  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:20.280  6102  6401 V FormManager: Network unavailable.
,08-08 11:23:20.316  6063  6063 V BluetoothOppNotification: new notify threadi!
08-08 11:23:20.316  6063  6063 V BluetoothOppNotification: send delay message
,08-08 11:23:20.319  6063  6402 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-08 11:23:20.321  6063  6402 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24c2ce81 on behalf of 
08-08 11:23:20.322  6063  6402 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-08 11:23:20.323  6063  6402 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-08 11:23:20.325  6063  6402 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa36b26 on behalf of 
08-08 11:23:20.326  6063  6402 V BluetoothOppNotification: outbound: succ-0  fail-0
08-08 11:23:20.328  6063  6402 V BluetoothOppNotification: outbound notification was removed.
08-08 11:23:20.328  6063  6402 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-08 11:23:20.330  6063  6402 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@79e6367 on behalf of 
08-08 11:23:20.331  6063  6402 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-08 11:23:20.334  6063  6402 V BluetoothOppNotification: inbound notification was removed.
08-08 11:23:20.334  6063  6402 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-08 11:23:20.335  6063  6402 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@963e514 on behalf of 
08-08 11:23:21.085  1025  1531 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1769385852] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-08 11:23:21.087  1025  1531 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1769385855] gl rssi=-46 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-08 11:23:22.077  1025  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:23:22.093  1025  1087 D Tethering: MasterInitialState.processMessage what=3
,08-08 11:23:22.109  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:23:22.113  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:22.129  1025  1081 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:23:22.154  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-08 11:23:22.164  5077  6220 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-08 11:23:22.182  5180  5180 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-08 11:23:22.243  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:23:22.270  1025  1081 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-08 11:23:22.310  1025  1640 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6428 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-08 11:23:22.327  1025  1081 E GpsLocationProvider: No APN found to select.
,08-08 11:23:22.390  6428  6428 I AppUp4:AppBoxCP: onCreate
08-08 11:23:22.390  6428  6428 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-08 11:23:22.400  6428  6428 I AppUp4:DB:  setFingerPrint start
08-08 11:23:22.400  6428  6428 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-08 11:23:22.408  6428  6428 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-08 11:23:22.408  6428  6428 I AppUp4:DB:  SDK version = 21
08-08 11:23:22.408  6428  6428 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-08 11:23:22.410  6428  6428 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-08 11:23:22.411  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-08 11:23:22.411  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:23:22.413  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-08 11:23:22.413  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-08 11:23:22.421  6428  6428 I AppUp4:CustModeStarterReceiver: onReceive
,08-08 11:23:22.465  6428  6428 D LgDataFeature: LgDataFeature() Constructor: none
08-08 11:23:22.465  6428  6428 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-08 11:23:22.475  6428  6428 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@39609c9a
08-08 11:23:22.476  6428  6428 D AppUp4:CustFacade: isCustomizationCompleted : false
08-08 11:23:22.476  6428  6428 D AppUp4:CustFacade: isPhone : true
08-08 11:23:22.476  6428  6428 D AppUp4:CustModeStarterReceiver: begin check event
08-08 11:23:22.477  6428  6428 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-08 11:23:22.477  6428  6428 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-08 11:23:22.484  6428  6449 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-08 11:23:22.485  6428  6449 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,08-08 11:23:22.485  6428  6449 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-08 11:23:22.497  1025  1911 I ActivityManager: Killing 5621:com.lge.email/u0a23 (adj 15): empty #17
,08-08 11:23:22.597  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:22.597  1025  1912 W libprocessgroup: failed to open /acct/uid_10023/pid_5621/cgroup.procs: No such file or directory
,08-08 11:23:22.600  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-08 11:23:22.605  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:22.609  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:22.617  3254  6454 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-08 11:23:22.622  3254  6455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:22.622  3254  6455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-08 11:23:22.674  1025  2028 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6456 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-08 11:23:22.745  6456  6456 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-08 11:23:22.746  6456  6456 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-08 11:23:22.747  6456  6456 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-08 11:23:22.747  6456  6456 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-08 11:23:22.831  1025  1912 D WifiServiceImplEx: setWifiEnabled: true pid=5992, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-08 11:23:22.832  1025  1912 D WifiService: setWifiEnabled: true pid=5992, uid=10118
08-08 11:23:22.832  1025  1912 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 11:23:22.844  6456  6456 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-08 11:23:22.853  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-08 11:23:22.854  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-08 11:23:22.854  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-08 11:23:22.855  1025  1531 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-08 11:23:22.855  1025  1531 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-08 11:23:22.859  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-08 11:23:22.859  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-08 11:23:22.859  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): pid[1025] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-08 11:23:22.859  1025  1531 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-08 11:23:22.859  1025  1531 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-08 11:23:22.859  1025  1531 E WifiHW  : unknown target_country: EU , set to default
08-08 11:23:22.859  1025  1531 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-08 11:23:22.859  1025  1531 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-08 11:23:22.859  1025  1531 I WifiUtil: gEnableBmps=1
08-08 11:23:22.861  6456  6456 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-08 11:23:22.904  6456  6456 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-08 11:23:22.942  6456  6456 D LgDataFeature: LgDataFeature() Constructor: none
,08-08 11:23:22.943  6456  6456 D LgDataFeature: LgDataFeature() Constructor Done, null
08-08 11:23:22.972  1025  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:23:22.978  1025  1087 D Tethering: MasterInitialState.processMessage what=3
08-08 11:23:22.979  1025  1537 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:22.984  1025  1081 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:22.986  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-08 11:23:22.988  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:22.992  1025  1087 D Tethering: MasterInitialState.processMessage what=3
08-08 11:23:22.994  5180  5180 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-08 11:23:23.000  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:23.001  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:23:23.001  5180  5180 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-08 11:23:23.003  1025  1081 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:23.003  1025  1081 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:23.003  1025  1081 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-08 11:23:23.078  6456  6456 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-08 11:23:23.112  6456  6456 I HubEmail: JNI_OnLoad()
08-08 11:23:23.112  6456  6456 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-08 11:23:23.112  6456  6456 I HubEmail: registerNatives()
,08-08 11:23:23.112  6456  6456 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-08 11:23:23.112  6456  6456 I HubEmail: registerNativeMethods()
08-08 11:23:23.112  6456  6456 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-08 11:23:23.113  6456  6456 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-08 11:23:23.127  3409  3409 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-08 11:23:23.127  3409  3409 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:23.127  6456  6482 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:23.130  3409  3409 I LgeMiscReceiver: networkInfo.isConnected() = true
,08-08 11:23:23.130  3409  3409 D PhoneState: setPdpRejectCasuse : false
,08-08 11:23:23.190  1025  1946 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6483 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-08 11:23:23.199  6102  6479 W FormManager: Network not available. Please check & try again.
08-08 11:23:23.203  6102  6480 V FormManager: Network unavailable.
08-08 11:23:23.206  6102  6480 V FormManager: Network unavailable.
,08-08 11:23:23.216  1025  1977 I ActivityManager: Killing 5654:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-08 11:23:23.248  1025  1946 W libprocessgroup: failed to open /acct/uid_10027/pid_5654/cgroup.procs: No such file or directory
08-08 11:23:23.318  6483  6483 D LgDataFeature: LgDataFeature() Constructor: none
08-08 11:23:23.318  6483  6483 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-08 11:23:23.322  6483  6483 D PhoneMonitor: Register our PhoneStateListener
08-08 11:23:23.344  6483  6483 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-08 11:23:23.350  6483  6483 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-08 11:23:23.373  6483  6483 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-08 11:23:23.375  6483  6483 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-08 11:23:23.376  6483  6483 D TelephonyAutoProfiling: [parse] Load xml
08-08 11:23:23.381  6483  6483 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-08 11:23:23.382  6483  6483 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-08 11:23:23.382  6483  6483 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-08 11:23:23.393  6483  6483 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-08 11:23:23.428  1025  1911 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6509 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-08 11:23:23.428  1025  1911 I ActivityManager: Killing 5716:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-08 11:23:23.500  1025  2618 W libprocessgroup: failed to open /acct/uid_10061/pid_5716/cgroup.procs: No such file or directory
,08-08 11:23:23.546  1025  1087 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-08 11:23:23.546  1025  1087 D Tethering: InitialState.processMessage what=4
08-08 11:23:23.546  1025  1087 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-08 11:23:23.551   309   899 D SoftapController: Softap fwReload - Ok
08-08 11:23:23.552  1025  1531 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (685ms)
08-08 11:23:23.554   309  6533 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-08 11:23:23.554   309   899 D CommandListener: Setting iface cfg
08-08 11:23:23.554   309   899 D CommandListener: Trying to bring down wlan0
08-08 11:23:23.555  1025  1085 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-08 11:23:23.555   309   899 D CommandListener: Clearing all IP addresses on wlan0
08-08 11:23:23.557  1025  1531 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-08 11:23:23.559  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-08 11:23:23.559  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-08 11:23:23.559  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-08 11:23:23.560  1025  1531 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-08 11:23:23.560  1025  1531 D WifiMonitor: connecting to supplicant
08-08 11:23:23.561  1025  1531 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-08 11:23:23.549  6534  6534 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:23.549  6534  6534 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:23.564  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:23.564  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-08 11:23:23.566  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-08 11:23:23.568  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:23.569  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:23.588  6534  6534 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-08 11:23:23.622  6534  6534 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-08 11:23:23.622  6534  6534 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-08 11:23:23.658  6534  6534 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-08 11:23:23.712  6534  6534 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-08 11:23:23.731  6534  6534 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-08 11:23:23.911  1025  1977 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6539 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-08 11:23:23.911  1025  1977 I ActivityManager: Killing 5767:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-08 11:23:23.970  1025  1568 W libprocessgroup: failed to open /acct/uid_10080/pid_5767/cgroup.procs: No such file or directory
,08-08 11:23:24.016  5874  6325 D UEI.SmartControl: Internal timer expired: 2
08-08 11:23:24.016  5874  6325 D UEI.SmartControl: unbind internal service
,08-08 11:23:24.026  6539  6539 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
08-08 11:23:24.028  6539  6539 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,08-08 11:23:24.038  6539  6539 V DrmService: Service onCreate
08-08 11:23:24.039  6539  6539 D DrmService: Received new request = 2
08-08 11:23:24.045  6539  6559 I DrmSntpClient: Start Sync process
,08-08 11:23:24.045  6539  6559 D DrmSntpClient: Server : 0
08-08 11:23:24.093  1025  1641 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6560 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-08 11:23:24.113  6539  6559 D DrmSntpClient: Automatic sync but WiFi isn't enabled
,08-08 11:23:24.121   338   338 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 461us total 28.868ms
08-08 11:23:24.143   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 21.126ms
,08-08 11:23:24.151  5874  6319 D serial_port: close(fd = 24)
08-08 11:23:24.155  6539  6539 D DrmService: Completed !! request = 2
08-08 11:23:24.155  6539  6539 D DrmService: Request count = 0
08-08 11:23:24.157  5874  6319 I UEI.SmartControl: Serial port is closed.
,08-08 11:23:24.161  6539  6539 V DrmService: Service onDestroy
,08-08 11:23:24.162  1025  1640 I ActivityManager: Killing 5792:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-08 11:23:24.172   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 27.841ms
,08-08 11:23:24.188  6560  6560 I art     : Almond Protected OAT
,08-08 11:23:24.250  1025  2618 W libprocessgroup: failed to open /acct/uid_10097/pid_5792/cgroup.procs: No such file or directory
,08-08 11:23:24.254  6560  6560 D WeatherApplication: removeAccount
,08-08 11:23:24.255  6560  6560 D WeatherApplication: Account.length = 0
08-08 11:23:24.256  6560  6560 E WeatherApplication: OPERATOR:OPEN
08-08 11:23:24.261  6560  6560 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:23:24
08-08 11:23:24.264  6560  6560 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-08 11:23:24.264  6560  6560 D Weather.Utils: 2 : All the weather widget is gone.
,08-08 11:23:24.266  6560  6560 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-08 11:23:24.269  6560  6560 D WeatherAncestor: connectivity changed - connection : true
08-08 11:23:24.270  6560  6560 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-08 11:23:24.282  6560  6560 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-08 11:23:24.282  6560  6560 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-08 11:23:24.282  6560  6560 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-08 11:23:24.300  6534  6534 E wpa_supplicant: USIM:  scard_init function
,08-08 11:23:24.300  6534  6534 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-08 11:23:24.319  6560  6560 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-08 11:23:24.319  6560  6560 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:23:24
,08-08 11:23:24.368  1025  1946 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6589 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-08 11:23:24.370  1025  1946 I ActivityManager: Killing 5831:com.lge.eula/1000 (adj 15): empty #17
,08-08 11:23:24.413  6534  6534 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-08 11:23:24.427  6534  6534 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-08 11:23:24.427  6534  6534 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-08 11:23:24.441  1025  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_5831/cgroup.procs: No such file or directory
,08-08 11:23:24.450  1025  1087 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-08 11:23:24.543   280   465 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-08 11:23:24.543   280   465 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-08 11:23:24.543   280   465 W Vold    : Returning OperationFailed - no handler for errno 0
,08-08 11:23:24.543  6589  6608 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-08 11:23:24.545   280   465 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-08 11:23:24.545   280   465 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-08 11:23:24.545   280   465 W Vold    : Returning OperationFailed - no handler for errno 0
08-08 11:23:24.546  6589  6608 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-08 11:23:24.559   280   465 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-08 11:23:24.559   280   465 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-08 11:23:24.559   280   465 W Vold    : Returning OperationFailed - no handler for errno 0
,08-08 11:23:24.561  6589  6610 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-08 11:23:24.566   280   465 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-08 11:23:24.566   280   465 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-08 11:23:24.566   280   465 W Vold    : Returning OperationFailed - no handler for errno 0
08-08 11:23:24.567  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-08 11:23:24.568  6589  6610 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-08 11:23:24.568  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-08 11:23:24.569  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-08 11:23:24.570  1025  1531 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-08 11:23:24.571  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:24.572  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:24.572  1025  1531 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:24.573  1025  1531 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-08 11:23:24.573  1025  1531 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-08 11:23:24.573  1025  1531 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-08 11:23:24.574  1025  1531 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-08 11:23:24.575  1025  1531 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-08 11:23:24.575  1025  1531 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-08 11:23:24.576  1025  1531 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-08 11:23:24.576  1025  1531 E WifiStateMachine: useWiFiOffloading() : false
08-08 11:23:24.576  1025  1531 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-08 11:23:24.576  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:24.577  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:24.577  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:24.577  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:24.577  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-08 11:23:24.579  1937  1937 D WfdService: Waiting for WifiP2p enabling
08-08 11:23:24.580  1025  1531 D WifiNative-wlan0: doBoolean: SET update_config 1
08-08 11:23:24.580  1025  1531 D WifiNative-wlan0: SET update_config 1: returned true
08-08 11:23:24.580  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:24.580  1025  1531 D WifiConfigStore: Loading config and enabling all networks 
08-08 11:23:24.580  1025  1531 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-08 11:23:24.581  1025  1531 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
,08-08 11:23:24.585  1025  1025 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-08 11:23:24.586  1025  1535 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-08 11:23:24.588  1025  1531 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-08 11:23:24.593  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:24.593  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:24.593  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:24.593  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:24.593  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:24.593  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:24.593  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:24.593  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:24.596  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:24.597  1025  1531 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-08 11:23:24.597  1025  1531 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-08 11:23:24.599  1025  1531 D WifiStateMachine: enableVerboseLogging : level 2
08-08 11:23:24.599  1025  1531 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-08 11:23:24.600  1025  1531 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-08 11:23:24.600  1025  1531 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-08 11:23:24.601  1025  1531 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-08 11:23:24.601  1025  1531 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-08 11:23:24.602  1025  1531 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-08 11:23:24.602  1025  1531 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-08 11:23:24.602  1025  1531 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-08 11:23:24.602  1025  1531 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-08 11:23:24.603  1025  1531 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-08 11:23:24.603  1025  1531 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-08 11:23:24.603  1025  1531 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-08 11:23:24.603  1025  1531 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-08 11:23:24.603  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:24.603  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:24.603  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:24.603  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:24.603  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:24.603  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:24.603  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:24.603  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:24.604  1025  1531 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-08 11:23:24.605  1937  1937 D WfdsService: Supplicant Connection state is changed : true
,08-08 11:23:24.605  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:24.605  1937  2299 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-08 11:23:24.606  1937  2299 D WfdsService: Set the WFDS Monitor: true
08-08 11:23:24.606  1937  2299 D WfdsMonitor: WfdsMonitorThread create
08-08 11:23:24.606  1937  2299 D WfdsMonitor: WFDS Monitor is created and started
08-08 11:23:24.606  1937  2299 D WfdsService: WiFi: Supplicant connection re-established
08-08 11:23:24.606  1025  1531 D WifiStateMachine: Setting OUI to DA-A1-19
08-08 11:23:24.606  1025  1531 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-08 11:23:24.607  1025  1531 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-08 11:23:24.607  1025  1531 D WifiNative-HAL: Setting external_sim to 1
08-08 11:23:24.607  1025  1531 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-08 11:23:24.607  1937  6615 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-08 11:23:24.607  1025  1531 D WifiNative-wlan0: SET external_sim 1: returned true
08-08 11:23:24.607  1025  1531 I WifiNative-HAL: startHal
08-08 11:23:24.607  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x988428dc
08-08 11:23:24.607  1937  6615 E CtrlSupplicant: Succeed to open control connection
08-08 11:23:24.608  1025  1531 E WifiHAL : Could not connect handle
08-08 11:23:24.608  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x600bde
08-08 11:23:24.608  1937  6615 E CtrlSupplicant: Succeed to open monitor connection
08-08 11:23:24.608  1025  1531 I WifiNative-HAL: Could not start hal
08-08 11:23:24.608  1025  1531 D WifiStateMachine: Setting OUI to DA-A1-19
,08-08 11:23:24.608  1025  1531 I WifiNative-HAL: startHal
08-08 11:23:24.608  1025  1531 E wifi    : getStaticLongField sWifiHalHandle 0x9884285c
08-08 11:23:24.608  1937  6615 D WfdsMonitor: Supplicant connection established
08-08 11:23:24.608  1025  1531 E WifiHAL : Could not connect handle
08-08 11:23:24.608  1025  1531 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x400b86
08-08 11:23:24.608  1025  1531 I WifiNative-HAL: Could not start hal
08-08 11:23:24.608  1937  2299 D WfdsService: Connected to the supplicant for wfds
08-08 11:23:24.608  1025  1531 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-08 11:23:24.609  1025  1531 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-08 11:23:24.609  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-08 11:23:24.609  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-08 11:23:24.610  1025  1531 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-08 11:23:24.610  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-08 11:23:24.610  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-08 11:23:24.610  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-08 11:23:24.610  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-08 11:23:24.610  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-08 11:23:24.611  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-08 11:23:24.611  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-08 11:23:24.611  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-08 11:23:24.611  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-08 11:23:24.611  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-08 11:23:24.611  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-08 11:23:24.612  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-08 11:23:24.612  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-08 11:23:24.612  6534  6534 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-08 11:23:24.612  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-08 11:23:24.612  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-08 11:23:24.612  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-08 11:23:24.613  1025  1531 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-08 11:23:24.613  1025  1531 E WifiNative: : [362,781,419 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-08 11:23:24.614  1025  1531 D WifiNative-wlan0: doBoolean: RECONNECT
08-08 11:23:24.614  1025  1531 D WifiNative-wlan0: RECONNECT: returned true
08-08 11:23:24.614  1025  1531 D WifiNative-wlan0: doString: [STATUS]
08-08 11:23:24.614  1025  6613 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-08 11:23:24.615  1025  6613 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-08 11:23:24.615  1025  1531 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-08 11:23:24.615  1025  1531 D WifiNative-wlan0: doBoolean: SET ps 1
,08-08 11:23:24.616  1025  1531 D WifiNative-wlan0: SET ps 1: returned true
08-08 11:23:24.616  1025  1529 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.617  1025  1025 D WifiScanningService: SCAN_AVAILABLE : 3
08-08 11:23:24.617  1025  1025 D RttService: SCAN_AVAILABLE : 3
08-08 11:23:24.617  1025  1548 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.617  1025  1548 I WifiNative-HAL: startHal
08-08 11:23:24.617  1025  1548 E wifi    : getStaticLongField sWifiHalHandle 0x94c9e99c
08-08 11:23:24.617  1025  1548 E WifiHAL : Could not connect handle
08-08 11:23:24.617  1025  1548 D wifi    : halHandle = 0x0, mVM = 0xb487c280, mCls = 0x800a9a
08-08 11:23:24.617  1025  1548 I WifiNative-HAL: Could not start hal
08-08 11:23:24.617  1025  1548 E WifiScanningService: could not start HAL
08-08 11:23:24.617  1025  1549 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.618   309   899 D CommandListener: Setting iface cfg
08-08 11:23:24.618   309   899 D CommandListener: Trying to bring up p2p0
08-08 11:23:24.618  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-08 11:23:24.618  1025  1529 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-08 11:23:24.618  1025  1529 D LGWifiP2pService: P2pEnablingState
08-08 11:23:24.618  1025  1529 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.618  1025  1529 D LGWifiP2pService: P2p socket connection successful
08-08 11:23:24.618  1025  1529 D LGWifiP2pService: P2pEnabledState
08-08 11:23:24.618  1025  1531 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-08 11:23:24.619  1025  1531 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-08 11:23:24.620  1025  1531 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-08 11:23:24.620  1025  1531 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-08 11:23:24.620  1937  1937 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-08 11:23:24.620  1937  1937 D WfdsService: WifiP2pState is changed : true
08-08 11:23:24.620  1937  2299 D WfdsService: Receive the WFDS_ENABLE Method
08-08 11:23:24.620  1025  1531 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-08 11:23:24.620  1937  2299 D WfdsService: Set the WFDS Monitor: true
08-08 11:23:24.620  1937  2299 D WfdsService: Connected to the supplicant for wfds
08-08 11:23:24.621  1937  2299 D WfdsJNI : doCommand: WFDS_SET TRUE
08-08 11:23:24.621  6534  6534 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-08 11:23:24.621  1025  1531 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-08 11:23:24.621  1937  2299 D WfdsService: selectPreferredScanChannel [36]
08-08 11:23:24.621  1025  1531 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-08 11:23:24.621  1937  2299 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-08 11:23:24.621  6534  6534 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-08 11:23:24.622  1025  1529 D LGWifiP2pService: sending p2p connection changed broadcast
08-08 11:23:24.623  1025  1529 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-08 11:23:24.623  1025  1529 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-08 11:23:24.623  1025  1529 D WifiNative-p2p0: doBoolean: SET device_name G3
08-08 11:23:24.623  1937  1937 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-08 11:23:24.624  1025  1529 D WifiNative-p2p0: SET device_name G3: returned true
08-08 11:23:24.624  1025  1529 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-08 11:23:24.624  1025  1529 D LGWifiP2pService: before postfix = G3
08-08 11:23:24.624  1025  1529 D WifiServerServiceExt: postfix byte check : 2
08-08 11:23:24.,624  1025  1529 D LGWifiP2pService: after postfix = G3
08-08 11:23:24.624  1025  1529 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-08 11:23:24.624  1937  1937 D WfdsService: isConnected: false
08-08 11:23:24.624  1025  1529 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-08 11:23:24.624  1025  1529 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-08 11:23:24.625  1025  1529 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-08 11:23:24.625  1025  1529 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-08 11:23:24.625  1025  1531 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-08 11:23:24.625  1025  1529 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-08 11:23:24.625  1025  1529 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-08 11:23:24.625  1025  1531 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-08 11:23:24.625  1025  1529 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-08 11:23:24.625  1025  1529 D WifiNative-HAL: p2pGetDeviceAddress
08-08 11:23:24.625  1025  1531 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-08 11:23:24.625  1025  1531 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-08 11:23:24.626  6534  6534 E wpa_supplicant: disconnect_rssi_lvl: -100
08-08 11:23:24.626  1025  1529 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-08 11:23:24.626  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-08 11:23:24.626  1025  1529 D LGWifiP2pService: DeviceAddress: 
08-08 11:23:24.626  1025  1529 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-08 11:23:24.626  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
,08-08 11:23:24.626  1025  1529 D WifiNative-p2p0: P2P_FLUSH: returned true
08-08 11:23:24.627  1025  1529 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-08 11:23:24.627  1025  1531 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-08 11:23:24.627  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-08 11:23:24.627  1025  1529 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-08 11:23:24.627  1025  1529 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-08 11:23:24.627  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-08 11:23:24.628  6534  6534 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:24.629  6534  6534 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-08 11:23:24.629  1937  1937 I WfdStateTracker: handleP2pThisDeviceChanged
08-08 11:23:24.629  6534  6534 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.629  1937  1937 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-08 11:23:24.629  6534  6534 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.629  1937  1937 D WfdsService: Update P2p Interface State: 3
08-08 11:23:24.630  1937  6615 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:24.630  1937  6615 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:24.630  1025  6613 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-08 11:23:24.631  1025  6613 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:24.631  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:24.631  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:24.631  1025  6613 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:24.631  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.631  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.631  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.631  1025  6613 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:24.631  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.631  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.631  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.631  1025  1531 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-08 11:23:24.632  1025  1531 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-08 11:23:24.632  1025  1531 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-08 11:23:24.633  1025  1531 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-08 11:23:24.633  1025  1531 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-08 11:23:24.633  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-08 11:23:24.633  6534  6534 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-08 11:23:24.634  1025  6613 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-08 11:23:24.634  1025  6613 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-08 11:23:24.634  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-08 11:23:24.634  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-08, 11:23:24.634  1025  1531 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-08 11:23:24.634  1025  1531 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-08 11:23:24.635  1025  1531 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-08 11:23:24.635  1025  1529 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-08 11:23:24.635  1025  1529 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-08 11:23:24.636  1025  1531 D WifiNative-wlan0: doBoolean: SCAN
08-08 11:23:24.648  1025  1529 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-08 11:23:24.649  1025  1529 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-08 11:23:24.649  1025  1529 D LGWifiP2pService: InactiveState
08-08 11:23:24.649  1025  1529 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.649  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.649  1025  1529 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-08 11:23:24.649  6534  6534 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-08 11:23:24.650  1025  6613 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-08 11:23:24.650  1025  6613 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-08 11:23:24.650  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-08 11:23:24.650  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-08 11:23:24.650  1025  1531 D WifiNative-wlan0: SCAN: returned true
08-08 11:23:24.651  1025  1531 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=362819  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-08 11:23:24.652  1025  1531 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=362820  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-08 11:23:24.652  1597  1597 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 11:23:24.652  1597  1597 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-08 11:23:24.653  1025  1531 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:24.653  6534  6534 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-08 11:23:24.653  6534  6534 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:24.653  1025  6613 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-08 11:23:24.654  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:24.654  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:24.654  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-08 11:23:24.654  1597  1597 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-08 11:23:24.654  6534  6534 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-08 11:23:24.654  6534  6534 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.654  1025  1531 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:24.654  1025  6613 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:24.654  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.654  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.654  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.655  6534  6534 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.655  1025  1529 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: InactiveState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.655  1025  6613 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-24ms what=143376 obj=CZ target=com.android.internal.util.StateMach,ine$SmHandler }
08-08 11:23:24.655  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.655  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.655  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.655  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.655  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:24.655  1025  1531 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:24.655  1025  1025 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-08 11:23:24.655  1025  1529 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.656  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.656  1025  1529 D LGWifiP2pService: DefaultState{ when=-6ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.656  1025  1529 D LGWifiP2pService: InactiveState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.656  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.656  1025  1531 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:24.656  1025  1529 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.656  1025  1025 E WifiServerServiceExt: No p2p device connected
08-08 11:23:24.656  1025  1531 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-08 11:23:24.656  1937  6615 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-08 11:23:24.656  1937  2299 W WfdsService: DefaultState - msg [9441285] is not handled
08-08 11:23:24.656  1937  6615 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:24.656  1937  6615 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-08 11:23:24.657  1025  1025 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-08 11:23:24.657  1025  1025 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-08 11:23:24.806  6589  6589 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-08 11:23:24.819  6589  6589 I LibraryLoader: Loading: webviewchromium
,08-08 11:23:24.823  6589  6589 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2999-3004)
08-08 11:23:24.823  6589  6589 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-08 11:23:24.833  6589  6589 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e55897}
,08-08 11:23:24.835  6589  6589 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 11:23:24.835  6589  6589 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-08 11:23:24.847  6589  6589 I BrowserStartupController: Initializing chromium process, renderers=0
,08-08 11:23:24.848  6589  6589 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-08 11:23:24.872  6589  6589 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-08 11:23:24.876  6589  6589 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-08 11:23:24.877  6589  6589 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-08 11:23:24.881   313  1376 V AudioPolicyService: registerClient() client 0xb0410520, uid 10093
08-08 11:23:24.882  6589  6634 W AudioManagerAndroid: Requires BLUETOOTH permission
08-08 11:23:24.904  6589  6589 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-08 11:23:24.904  6589  6589 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-08 11:23:24.904  6589  6589 I Adreno-EGL: Build Date: 12/12/14 금
08-08 11:23:24.904  6589  6589 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-08 11:23:24.904  6589  6589 I Adreno-EGL: Remote Branch: 
08-08 11:23:24.904  6589  6589 I Adreno-EGL: Local Patches: 
08-08 11:23:24.904  6589  6589 I Adreno-EGL: Reconstruct Branch: 
,08-08 11:23:24.934  1025  1529 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.934  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:24.935  1025  1529 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-08 11:23:24.968  1025  1531 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-08 11:23:24.969  1025  1531 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-08 11:23:24.971  1025  1531 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-08 11:23:24.972  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-08 11:23:24.973  1025  1531 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-08 11:23:24.993  6589  6589 I NSApplication: Starting up...
,08-08 11:23:25.059  1025  2026 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6650 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-08 11:23:25.061  1025  2026 I ActivityManager: Killing 5678:com.android.vending/u0a44 (adj 15): empty #17
08-08 11:23:25.117  1025  1778 W libprocessgroup: failed to open /acct/uid_10044/pid_5678/cgroup.procs: No such file or directory
,08-08 11:23:25.158  6650  6650 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-08 11:23:25.514  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-08 11:23:25.516  5077  6220 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-08 11:23:25.535  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:23:25.547  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-08 11:23:25.547  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:25.547  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-08 11:23:25.547  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-08 11:23:25.549  6428  6428 I AppUp4:CustModeStarterReceiver: onReceive
,08-08 11:23:25.555  6428  6428 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@39609c9a
08-08 11:23:25.555  6428  6428 D AppUp4:CustFacade: isCustomizationCompleted : false
08-08 11:23:25.555  6428  6428 D AppUp4:CustFacade: isPhone : true
08-08 11:23:25.555  6428  6428 D AppUp4:CustModeStarterReceiver: begin check event
08-08 11:23:25.556  6428  6428 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-08 11:23:25.560  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:25.561  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-08 11:23:25.562  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:25.564  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-08 11:23:25.572  6456  6456 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-08 11:23:25.573  3254  6678 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-08 11:23:25.586  3254  6679 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:25.586  3254  6679 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-08 11:23:25.594  3409  3409 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-08 11:23:25.594  3409  3409 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:25.594  3409  3409 I LgeMiscReceiver: networkInfo.isConnected() = false
08-08 11:23:25.604  6483  6483 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-08 11:23:25.604  6483  6483 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-08 11:23:25.605  6102  6687 W FormManager: Network not available. Please check & try again.
08-08 11:23:25.616  6560  6560 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:23:25
08-08 11:23:25.618  6560  6560 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-08 11:23:25.618  6560  6560 D Weather.Utils: 2 : All the weather widget is gone.
08-08 11:23:25.619  6102  6688 V FormManager: Network unavailable.
,08-08 11:23:25.620  6560  6560 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-08 11:23:25.621  6560  6560 D WeatherAncestor: connectivity changed - connection : true
08-08 11:23:25.621  6560  6560 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@824f5a8
08-08 11:23:25.623  6456  6680 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:25.624  6102  6688 V FormManager: Network unavailable.
08-08 11:23:25.626  6560  6560 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-08 11:23:25.626  6560  6560 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-08 11:23:25.626  6560  6560 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-08 11:23:25.626  6560  6560 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-08 11:23:25.626  6560  6560 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:23:25
08-08 11:23:25.666  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-08 11:23:25.671  5077  6220 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-08 11:23:25.694  2203  2203 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:23:25.709  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-08 11:23:25.710  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:25.710  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-08 11:23:25.710  6428  6428 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-08 11:23:25.714  6428  6428 I AppUp4:CustModeStarterReceiver: onReceive
08-08 11:23:25.719  6428  6428 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@39609c9a
08-08 11:23:25.719  6428  6428 D AppUp4:CustFacade: isCustomizationCompleted : false
08-08 11:23:25.719  6428  6428 D AppUp4:CustFacade: isPhone : true
08-08 11:23:25.721  6428  6428 D AppUp4:CustModeStarterReceiver: begin check event
08-08 11:23:25.721  6428  6428 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-08 11:23:25.729  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:25.729  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-08 11:23:25.732  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:25.737  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:25.750  6456  6456 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-08 11:23:25.755  3254  6699 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-08 11:23:25.756  3254  6700 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:23:25.756  3254  6700 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-08 11:23:25.772  6456  6701 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-08 11:23:25.784  3409  3409 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-08 11:23:25.784  3409  3409 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-08 11:23:25.784  3409  3409 I LgeMiscReceiver: networkInfo.isConnected() = false
08-08 11:23:25.788  6483  6483 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-08 11:23:25.788  6483  6483 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-08 11:23:25.790  6102  6703 W FormManager: Network not available. Please check & try again.
08-08 11:23:25.791  6102  6704 V FormManager: Network unavailable.
08-08 11:23:25.799  6102  6704 V FormManager: Network unavailable.
08-08 11:23:25.802  6560  6560 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:23:25
,08-08 11:23:25.806  6560  6560 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-08 11:23:25.806  6560  6560 D Weather.Utils: 2 : All the weather widget is gone.
08-08 11:23:25.806  6560  6560 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-08 11:23:25.807  6560  6560 D WeatherAncestor: connectivity changed - connection : true
08-08 11:23:25.807  6560  6560 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@824f5a8
08-08 11:23:25.807  6560  6560 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-08 11:23:25.807  6560  6560 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-08 11:23:25.808  6560  6560 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-08 11:23:25.808  6560  6560 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-08 11:23:25.808  6560  6560 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:23:25
08-08 11:23:25.831  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-08 11:23:25.831  6120  6120 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-08 11:23:25.831  6120  6120 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-08 11:23:25.831  6120  6120 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-08 11:23:25.833  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-08 11:23:25.834  6120  6120 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-08 11:23:25.834  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-08 11:23:25.834  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-08 11:23:25.834  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-08 11:23:25.834  6120  6120 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-08 11:23:25.834  6120  6120 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-08 11:23:25.835  6120  6120 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-08 11:23:25.854  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-08 11:23:25.863  1025  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:25.863  1025  2026 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@37f46681 mBinding = false
08-08 11:23:25.864  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-08 11:23:25.871  6102  6709 W FormManager: Network not available. Please check & try again.
08-08 11:23:25.876  6102  6710 V FormManager: Network unavailable.
08-08 11:23:25.878  6102  6710 V FormManager: Network unavailable.
,08-08 11:23:25.880  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:25.885  1025  1087 D BluetoothManagerService: Message: 2
08-08 11:23:25.886  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-08 11:23:25.887  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-08 11:23:25.887  1025  1087 D BluetoothManagerService: Sending off request.
08-08 11:23:25.887  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-08 11:23:25.888  6063  6086 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-08 11:23:25.889  6063  6094 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-08 11:23:25.889  6063  6094 D BluetoothAdapterProperties: Setting state to 13
08-08 11:23:25.889  6063  6094 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-08 11:23:25.890  1025  1087 D BluetoothManagerService: Message: 60
08-08 11:23:25.890  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-08 11:23:25.890  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-08 11:23:25.890  6063  6094 D BluetoothAdapterProperties: onBluetoothDisable()
08-08 11:23:25.890  6063  6094 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-08 11:23:25.899  6063  6098 D BluetoothAdapterProperties: Scan Mode:20
08-08 11:23:25.900  6063  6094 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-08 11:23:25.902  6063  6365 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:25.902  6063  6094 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-08 11:23:25.902  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-08 11:23:25.903  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-08 11:23:25.905  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-08 11:23:25.907  6063  6180 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-08 11:23:25.907  6120  6120 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-08 11:23:25.908  6063  6352 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:25.908  6063  6063 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:25.909  6063  6368 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:25.909  6063  6063 D BluetoothMapService: STATE_TURNING_OFF
08-08 11:23:25.910  6063  6063 V BtOppService: Receiver DISABLED_ACTION 
08-08 11:23:25.910  6063  6063 V BluetoothMapService: Handler(): got msg=4
08-08 11:23:25.910  6063  6063 D BluetoothMapService: MAP Service closeService in
08-08 11:23:25.910  6063  6063 D BluetoothMapMasInstance: MAP Service shutdown
08-08 11:23:25.910  6063  6364 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-08 11:23:25.912  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-08 11:23:25.912  6063  6180 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-08 11:23:25.915  6063  6348 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-08 11:23:25.915  6063  6348 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:25.915  6063  6348 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-08 11:23:25.915  6063  6348 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-08 11:23:25.915  6063  6348 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-08 11:23:25.915  6063  6348 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-08 11:23:25.915  6063  6348 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-08 11:23:25.915  6063  6348 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-08 11:23:25.915  6063  6063 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-08 11:23:25.915  6063  6063 V BluetoothMapService: MAP Service closeService out
08-08 11:23:25.915  6063  6063 I BtOppRfcommListener: stopping Accept Thread
08-08 11:23:25.916  6063  6063 V BtOppRfcommListener: close mBtServerSocket
08-08 11:23:25.916  6063  6063 V BtOppRfcommListener: waiting for thread to terminate
08-08 11:23:25.916  6063  6364 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 11:23:25.917  6063  6063 V BtOppRfcommListener: done waiting for thread to terminate
08-08 11:23:25.917  6120  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-08 11:23:25.918  6063  6063 V BtOppService: onDestroy
08-08 11:23:25.924  6063  6063 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-08 11:23:25.932  6063  6063 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-08 11:23:25.932  6063  6063 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:25.932  6063  6063 V BluetoothPbapReceiver: ***********state = 13
08-08 11:23:25.934  6063  6063 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-08 11:23:25.934  6120  6120 D DockEventReceiver: finishStartingService: stopping service
08-08 11:23:25.940  6063  6063 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:25.940  6063  6063 V BluetoothPbapService: state: 13
08-08 11:23:25.940  6063  6063 V BluetoothPbapService: Pbap Service closeService in
08-08 11:23:25.942  6120  6120 D BluetoothPbap: Proxy object disconnected
08-08 11:23:25.942  6120  6120 D PbapServerProfile: Bluetooth service disconnected
08-08 11:23:25.942  6063  6063 V BluetoothPbapService: successfully stopped pbap service
08-08 11:23:25.942  6063  6063 V BluetoothPbapService: Pbap Service closeService out
08-08 11:23:25.943  6063  6063 V BluetoothPbapService: Pbap Service onDestroy
08-08 11:23:25.943  6063  6063 V BluetoothPbapService: Pbap Service closeService in
08-08 11:23:25.943  6063  6063 V BluetoothPbapService: Pbap Service closeService out
,08-08 11:23:25.943  6063  6063 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-08 11:23:25.945  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:25.945  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:25.945  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:25.945  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:25.945  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:25.945  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:25.945  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:25.945  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:25.945  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:25.945  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:25.945  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:25.946  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 11:23:25.948  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:25.948  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:25.948  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:25.948  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:25.948  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:25.948  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:25.948  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:25.948  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:25.948  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:25.948  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:25.949  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:25.950  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:25.951  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:25.965  6143  6143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-08 11:23:25.975  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-08 11:23:25.978  6102  6715 W FormManager: Network not available. Please check & try again.
,08-08 11:23:25.981  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-08 11:23:25.982  6120  6120 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-08 11:23:25.983  6102  6716 V FormManager: Network unavailable.
,08-08 11:23:25.985  6102  6716 V FormManager: Network unavailable.
08-08 11:23:25.989  6120  6120 D BluetoothPermissionRequest: onReceive
08-08 11:23:25.989  6120  6120 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-08 11:23:25.993  6120  6120 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-08 11:23:25.996  6063  6063 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-08 11:23:25.996  6063  6063 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-08 11:23:25.997  6063  6063 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-08 11:23:26.004  6063  6063 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:26.004  6063  6063 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-08 11:23:26.005  6063  6063 V BluetoothFtpService: Ftp Service onStartCommand
08-08 11:23:26.005  6063  6063 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:26.005  6063  6063 V BluetoothFtpService: Ftp Service closeService
08-08 11:23:26.005  6063  6063 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-08 11:23:26.008  6063  6063 V BluetoothFtpService: successfully stopped ftp service
08-08 11:23:26.008  6063  6063 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-08 11:23:26.008  6063  6063 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-08 11:23:26.008  6063  6063 V BluetoothSapReceiver: SapReceiver onReceive 
08-08 11:23:26.008  6063  6063 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:26.009  6063  6063 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-08 11:23:26.009  6063  6063 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-08 11:23:26.010  6063  6063 V BluetoothFtpService: Ftp Service onDestroy
08-08 11:23:26.010  6063  6063 V BluetoothFtpService: Ftp Service closeService
08-08 11:23:26.013  6063  6063 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:26.013  6063  6063 V BluetoothSapService: state: 13
08-08 11:23:26.013  6063  6063 V BluetoothSapService: Stopping SAP server process
08-08 11:23:26.014  6063  6063 V BluetoothSapService: Sap Service closeSapService in
08-08 11:23:26.014  6063  6063 V BluetoothSapService: Close listen Socket : 
08-08 11:23:26.014  6063  6063 V BluetoothSapService: Close rfcomm Socket : 
,08-08 11:23:26.015  6063  6063 V BluetoothSapService: Close sapd  Socket : 
,08-08 11:23:26.017  6063  6063 V BluetoothSapService: Sap Service closeSapService out
08-08 11:23:26.018  6063  6063 V BluetoothSapService: Sap Service onDestroy
08-08 11:23:26.018  6063  6063 V BluetoothSapService: Sap Service closeSapService in
08-08 11:23:26.018  6063  6063 V BluetoothSapService: Close listen Socket : 
08-08 11:23:26.018  6063  6063 V BluetoothSapService: Close rfcomm Socket : 
08-08 11:23:26.018  6063  6063 V BluetoothSapService: Close sapd  Socket : 
08-08 11:23:26.018  6063  6063 V BluetoothSapService: Sap Service closeSapService out
08-08 11:23:26.021  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-08 11:23:26.021  3254  3254 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-08 11:23:26.023  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:26.025  3254  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-08 11:23:26.028  5850  5850 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-08 11:23:26.028  5850  5850 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-08 11:23:26.028  5850  5850 V [BNRBootReceiver]: Boot Receiver Return
08-08 11:23:26.030  3254  6717 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-08 11:23:26.031  3254  6718 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-08 11:23:26.032  3254  6718 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-08 11:23:26.032  5077  5077 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-08 11:23:26.037  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-08 11:23:26.042  6120  6120 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-08 11:23:26.046  6227  6227 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-08 11:23:26.046  6227  6227 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-08 11:23:26.047  6227  6227 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-08 11:23:26.917  6063  6098 D bt_hci_bdroid: cleanup
,08-08 11:23:26.926  6063  6182 I bt_lpm  : LPM is already off!!!
08-08 11:23:26.927  6063  6320 I bt_userial_mct: exiting userial_read_thread
08-08 11:23:26.927  6063  6320 D bt_userial_mct: Leaving userial_evt_read_thread()
08-08 11:23:26.928  6063  6180 W bt-btif : ag scb idx 1 not allocated
08-08 11:23:26.929  6063  6180 E bt-btif : BTA AG is already disabled, ignoring ...
08-08 11:23:26.929  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:26.929  6063  6180 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:23:26.930  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019,
,08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:26.931  6063  6180 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-08 11:23:26.931  6063  6180 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-08 11:23:26.935  6063  6098 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0,
,08-08 11:23:26.940  6063  6182 I bt_vendor: hw_epilog_process
08-08 11:23:26.944  6063  6098 D bt_hci_bdroid: cleanup Finalizing cleanup
08-08 11:23:26.944  6063  6098 D bt_userial_mct: userial_close
08-08 11:23:26.944  6063  6098 E bt_userial_mct: pthread_join() FAILED result:3
08-08 11:23:26.945  6063  6098 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-08 11:23:26.950  6063  6098 D bt_hci_bdroid: set_power 0
08-08 11:23:26.950  6063  6098 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-08 11:23:26.951  6063  6098 I bt_vendor: bluetooth satus is on
08-08 11:23:26.951  6063  6098 I bt_vendor: bt-vendor : resetting BT status
08-08 11:23:26.951  6063  6098 I bt_vendor: Starting hciattach daemon
08-08 11:23:26.951  6063  6098 I bt_vendor: try to set false
,08-08 11:23:26.956  6063  6098 I bt_vendor: Starting hciattach daemon
08-08 11:23:26.956  6063  6098 I bt_vendor: try to set false
08-08 11:23:26.957  6063  6098 I bt_vendor: cleanup
08-08 11:23:26.957  6063  6180 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-08 11:23:26.958  6063  6098 I GKI_LINUX: GKI_exit_task 0 done
08-08 11:23:26.958  6063  6098 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-08 11:23:26.960  6063  6094 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-08 11:23:26.964  6063  6063 D HeadsetService: Received stop request...Stopping profile...
,08-08 11:23:26.968  6063  6063 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-08 11:23:26.968  6063  6063 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 11:23:26.968  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:26.969  6063  6159 D HeadsetStateMachine: Exit Disconnected: -1
08-08 11:23:26.972  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-08 11:23:26.972  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-08 11:23:26.972  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-08 11:23:26.973  1025  1025 D BluetoothHeadset: Proxy object disconnected
08-08 11:23:26.973  1025  1025 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-08 11:23:26.975  6063  6063 D A2dpService: Received stop request...Stopping profile...
08-08 11:23:26.975  6063  6169 D A2dpStateMachine: Exit Disconnected: -1
08-08 11:23:26.977  6063  6063 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-08 11:23:26.983  6063  6063 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-08 11:23:26.983  6063  6063 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 11:23:26.983  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:26.986  1025  1025 D BluetoothA2dp: Proxy object disconnected
08-08 11:23:26.986  1025  1025 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-08 11:23:26.987  6063  6063 D HidService: Received stop request...Stopping profile...
08-08 11:23:26.987  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:26.990  6063  6094 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-08 11:23:26.993  6063  6063 D HeadsetStateMachine: Unbinding service...
08-08 11:23:26.994  6063  6063 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-08 11:23:26.994  6063  6063 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-08 11:23:26.994  6063  6063 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-08 11:23:26.994  6063  6063 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-08 11:23:26.994  6063  6063 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-08 11:23:26.994  6063  6063 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 11:23:26.994  6063  6063 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-08 11:23:26.997  6063  6063 D HealthService: Received stop request...Stopping profile...
08-08 11:23:26.997  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:26.999  6063  6063 D PanService: Received stop request...Stopping profile...
08-08 11:23:27.000  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:27.001  6063  6063 D BtGatt.DebugUtils: handleDebugAction() action=null
08-08 11:23:27.003  6063  6063 D BtGatt.GattService: Received stop request...Stopping profile...
08-08 11:23:27.003  6063  6063 D BtGatt.GattService: stop()
08-08 11:23:27.003  6063  6063 D BtGatt.AdvertiseManager: advertise clients cleared
,08-08 11:23:27.006  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:27.007  6063  6063 I BluetoothA2dpServiceJni: cleanupNative
08-08 11:23:27.007  6063  6170 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-08 11:23:27.008  6063  6063 I GKI_LINUX: GKI_exit_task 2 done
08-08 11:23:27.008  6063  6063 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-08 11:23:27.010  6063  6063 D BluetoothMapService: Received stop request...Stopping profile...
08-08 11:23:27.010  6063  6063 D BluetoothMapService: stop()
08-08 11:23:27.010  6063  6063 D BluetoothMapEmailAppObserver: deinitObservers()
08-08 11:23:27.011  6063  6063 D BluetoothMapEmailAppObserver: removeReceiver()
08-08 11:23:27.011  6063  6063 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5c9cb
08-08 11:23:27.012  6063  6063 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 11:23:27.012  6063  6063 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-08 11:23:27.015  6063  6063 V BluetoothMapService: Handler(): got msg=4
08-08 11:23:27.015  6063  6063 D BluetoothMapService: MAP Service closeService in
08-08 11:23:27.015  6063  6063 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-08 11:23:27.015  6063  6063 V BluetoothMapService: MAP Service closeService out
,08-08 11:23:27.018  6063  6094 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-08 11:23:27.018  6063  6094 D BluetoothAdapterProperties: Setting state to 10
08-08 11:23:27.018  6063  6094 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-08 11:23:27.019  1025  1087 D BluetoothManagerService: Message: 60
08-08 11:23:27.019  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-08 11:23:27.019  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-08 11:23:27.020  1025  1087 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:27.020  6063  6094 I BluetoothAdapterState: Entering OffState
08-08 11:23:27.020  1848  4095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:27.021  6063  6063 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-08 11:23:27.022  6063  6063 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 11:23:27.022  6063  6063 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 11:23:27.022  6120  6140 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 11:23:27.023  6063  6063 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-08 11:23:27.023  6063  6063 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-08 11:23:27.025  6063  6063 D BluetoothMapService: cleanup()
08-08 11:23:27.025  6063  6063 D BluetoothMapService: MAP Service closeService in
08-08 11:23:27.025  6063  6063 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-08 11:23:27.025  6063  6063 V BluetoothMapService: MAP Service closeService out
08-08 11:23:27.028  6120  6138 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 11:23:27.031  6120  6140 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 11:23:27.031  1025  1087 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:23:27.032  6120  6138 D BluetoothMap: onBluetoothStateChange: up=false
08-08 11:23:27.032  6120  6140 D BluetoothPan: onBluetoothStateChange on: false
08-08 11:23:27.033  6120  6138 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:23:27.034  1848  2628 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:27.035  1848  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:27.036  1025  1087 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-08 11:23:27.036  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-08 11:23:27.039  1025  1087 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,08-08 11:23:27.042  1025  1087 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-08 11:23:27.042  1025  1087 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@37f46681 mBinding = false
08-08 11:23:27.043  1025  1087 D BluetoothManagerService: Sending unbind request.
08-08 11:23:27.051  6063  6098 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-08 11:23:27.053  6063  6063 I GKI_LINUX: GKI_exit_task 1 done
08-08 11:23:27.053  6063  6063 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-08 11:23:27.054  6063  6063 I BluetoothServiceJni: cleanupNative: return from cleanup
08-08 11:23:27.055  6063  6063 I art     : --- WEIRD: removing null entry 246
08-08 11:23:27.055  6063  6063 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-08 11:23:27.055  6063  6063 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-08 11:23:27.055  6063  6063 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-08 11:23:27.057  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-08 11:23:27.059  6063  6063 I art     : System.exit called, status: 0
08-08 11:23:27.059  6063  6063 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-08 11:23:27.078   313  2136 V AudioFlinger: 6063 died, releasing its sessions
08-08 11:23:27.078   313  2136 V AudioFlinger:  pid 1848 @ 0
08-08 11:23:27.078   313  2136 V AudioFlinger:  pid 3409 @ 1
08-08 11:23:27.078   313  2136 V AudioFlinger:  pid 3409 @ 2
,08-08 11:23:27.081  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-08 11:23:27.082  1937  2116 D LGBluetoothAPIService: Message: 101
08-08 11:23:27.082  1937  2116 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-08 11:23:27.082  1937  2116 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-08 11:23:27.082  1937  2116 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-08 11:23:27.088  6120  6120 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-08 11:23:27.110  1025  1568 I ActivityManager: Process com.android.bluetooth (pid 6063) has died
08-08 11:23:27.110  1025  1568 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-08 11:23:27.111  1025  1568 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-08 11:23:27.118  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:27.118  1937  2116 D LGBluetoothAPIService: Message: 2
08-08 11:23:27.119  1937  2116 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-08 11:23:27.120  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-08 11:23:27.120  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:27.120  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:27.121  6120  6120 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-08 11:23:27.121  6120  6120 D LGBluetoothEventManager: [BTUI] clear device connection state
08-08 11:23:27.124  6120  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-08 11:23:27.135  1597  1597 D BluetoothAdapter: 658691523: getState() :  mService = null. Returning STATE_OFF
,08-08 11:23:27.135  1597  1597 D BluetoothAdapter: 658691523: getState() :  mService = null. Returning STATE_OFF
08-08 11:23:27.164  1025  1991 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6747 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-08 11:23:27.167  6120  6120 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:23:27.200  6747  6747 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-08 11:23:27.201  6747  6747 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-08 11:23:27.201  6747  6747 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-08 11:23:27.202  6747  6747 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-08 11:23:27.217  6747  6747 D BluetoothAdapterApp: Loading JNI Library
,08-08 11:23:27.249  6747  6747 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1cb92490 Instance Count = 1
,08-08 11:23:27.253  6747  6747 D BluetoothAdapterApp: onCreate
08-08 11:23:27.274  6747  6747 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-08 11:23:27.274  6747  6747 D ProfileConfigQcom: Adding HeadsetService
,08-08 11:23:27.275  6747  6747 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-08 11:23:27.275  6747  6747 D ProfileConfigQcom: Adding A2dpService
08-08 11:23:27.275  6747  6747 D ProfileConfigQcom: [BTUI] HidService is supported
08-08 11:23:27.275  6747  6747 D ProfileConfigQcom: Adding HidService
08-08 11:23:27.275  6747  6747 D ProfileConfigQcom: [BTUI] HealthService is supported
08-08 11:23:27.275  6747  6747 D ProfileConfigQcom: Adding HealthService
08-08 11:23:27.276  6747  6747 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-08 11:23:27.276  6747  6747 D ProfileConfigQcom: [BTUI] PanService is supported
08-08 11:23:27.276  6747  6747 D ProfileConfigQcom: Adding PanService
08-08 11:23:27.277  6747  6747 D ProfileConfigQcom: [BTUI] GattService is supported
08-08 11:23:27.277  6747  6747 D ProfileConfigQcom: Adding GattService
08-08 11:23:27.277  6747  6747 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-08 11:23:27.277  6747  6747 D ProfileConfigQcom: Adding BluetoothMapService
08-08 11:23:27.277  6747  6747 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported,
08-08 11:23:27.278  6747  6747 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-08 11:23:27.279  6747  6747 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:27.279  6747  6747 V BluetoothPbapReceiver: ***********state = 10
08-08 11:23:27.281  6747  6747 V LGMDMManagerInternal: Create singleton instance
08-08 11:23:27.346  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:23:27.346  6747  6747 D LGBluetoothAPIServer: [BTUI] onCreate()
08-08 11:23:27.346  6747  6747 D LGBluetoothAPIServer: [BTUI] onBind()
,08-08 11:23:27.361  1937  1937 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-08 11:23:27.361  1937  2116 D LGBluetoothAPIService: Message: 100
08-08 11:23:27.361  1937  2116 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-08 11:23:27.373  6120  6120 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-08 11:23:27.377  6120  6120 D BluetoothPermissionRequest: onReceive
,08-08 11:23:27.379  6120  6120 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-08 11:23:27.380  6120  6120 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-08 11:23:27.382  6120  6120 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-08 11:23:27.386  6747  6747 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-08 11:23:27.390  6747  6747 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:27.394  6747  6747 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-08 11:23:27.394  6747  6747 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-08 11:23:27.394  6747  6747 V BluetoothSapReceiver: SapReceiver onReceive 
08-08 11:23:27.396  6747  6747 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-08 11:23:27.396  6747  6747 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-08 11:23:27.407  6246  6246 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-08 11:23:28.165  1025  6613 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-08 11:23:28.165  1025  6613 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-08 11:23:28.165  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=33 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-08 11:23:28.165  1025  6613 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-08 11:23:28.178  1025  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-08 11:23:28.180  1937  6615 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-08 11:23:28.180  1937  6615 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-08 11:23:28.181  1025  1529 D LGWifiP2pService: InactiveState{ when=-16ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:28.181  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:28.182  1025  1529 D LGWifiP2pService: DefaultState{ when=-16ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:23:28.182  1025  6613 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-08 11:23:28.182  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=34 dispatchEvent: WPS-AP-AVAILABLE 
08-08 11:23:28.182  1025  6613 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-08 11:23:28.183  1025  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-08 11:23:28.183  1025  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-08 11:23:28.183  1025  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-08 11:23:28.184  1025  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-08 11:23:28.205  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-08 11:23:28.213  6120  6120 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-08 11:23:28.887  1025  1883 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:28.887  1025  1883 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-08 11:23:28.916  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-08 11:23:28.916  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-08 11:23:28.916  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-08 11:23:28.917  1025  1087 D BluetoothManagerService: Message: 1
08-08 11:23:28.917  1025  1087 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-08 11:23:29.089  1025  1087 I art     : Explicit concurrent mark sweep GC freed 98629(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.932ms total 163.075ms
,08-08 11:23:29.112  1025  1087 D BluetoothManagerService: Message: 20
08-08 11:23:29.112  1025  1087 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3564b05f:true
,08-08 11:23:29.117  6747  6747 D BluetoothAdapterState: make
08-08 11:23:29.122  6747  6747 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-08 11:23:29.122  6747  6747 I bluedroid-qcom: init
08-08 11:23:29.123  6747  6779 I BluetoothAdapterState: Entering OffState
08-08 11:23:29.124  6747  6747 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-08 11:23:29.124  6747  6747 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-08 11:23:29.124  6747  6747 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-08 11:23:29.124  6747  6747 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-08 11:23:29.124  6747  6747 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-08 11:23:29.127  6747  6747 I bluedroid-qcom: get_profile_interface socket
08-08 11:23:29.127  6747  6747 I bluedroid-qcom: get_profile_interface map_client
08-08 11:23:29.129  6747  6783 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-08 11:23:29.130  6747  6783 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-08 11:23:29.119  6782  6782 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:29.119  6782  6782 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:29.137  6782  6782 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-08 11:23:29.137  6782  6782 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-08 11:23:29.137  6782  6782 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-08 11:23:29.142  1025  1025 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-08 11:23:29.143  1025  1025 D BluetoothManagerService: Stored Bluetooth name: G3
,08-08 11:23:29.146  1025  1025 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-08 11:23:29.146  1025  1087 D BluetoothManagerService: Message: 40
08-08 11:23:29.147  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-08 11:23:29.148  6747  6764 I bluedroid-qcom: config_hci_snoop_log
08-08 11:23:29.149  6747  6783 D BluetoothAdapterProperties: Name is: G3
08-08 11:23:29.149  6782  6782 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-08 11:23:29.155  1025  1087 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-08 11:23:29.155  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-08 11:23:29.156  6782  6782 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-08 11:23:29.156  6782  6782 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-08 11:23:29.166  6747  6779 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-08 11:23:29.166  6747  6779 D BluetoothAdapterProperties: Setting state to 11
08-08 11:23:29.166  6747  6779 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-08 11:23:29.167  1025  1087 D BluetoothManagerService: Message: 60
08-08 11:23:29.167  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-08 11:23:29.167  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-08 11:23:29.168  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-08 11:23:29.169  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-08 11:23:29.172  6120  6120 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-08 11:23:29.172  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:29.175  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:29.178  6747  6747 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-08 11:23:29.178  6747  6747 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:29.178  6747  6747 V BluetoothPbapReceiver: ***********state = 11
08-08 11:23:29.178  6747  6779 I LGBluetoothServiceJni: classInitNative: succeeds
08-08 11:23:29.181  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 11:23:29.187  6747  6779 D BluetoothBondStateMachine: make
08-08 11:23:29.199  6747  6779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.200  6747  6779 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
,08-08 11:23:29.200  6747  6779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.200  6747  6779 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-08 11:23:29.200  6747  6779 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-08 11:23:29.201  6747  6790 I BluetoothBondStateMachine: StableState(): Entering Off State
08-08 11:23:29.204  6747  6779 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:29.214  6747  6747 D HeadsetService: Received start request. Starting profile...
08-08 11:23:29.215  6747  6747 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-08 11:23:29.215  6747  6747 D LGBluetoothHfpAdapter: Version 1.6
08-08 11:23:29.218  6747  6779 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:29.218  6747  6747 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-08 11:23:29.219  6747  6747 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-08 11:23:29.220  6747  6747 D HeadsetStateMachine: make
08-08 11:23:29.225  6120  6120 D BluetoothPermissionRequest: onReceive
,08-08 11:23:29.233  6120  6120 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-08 11:23:29.234  6747  6779 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:29.239  6747  6779 E BluetoothAdapterService: File transfer profiles supported!!
,08-08 11:23:29.245  6747  6779 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:29.250  6747  6779 E BluetoothAdapterService: File transfer profiles supported!!
08-08 11:23:29.254  6747  6779 E BluetoothAdapterService: File transfer profiles supported!!
,08-08 11:23:29.260  6747  6747 D LgDataFeature: LgDataFeature() Constructor: none
08-08 11:23:29.260  6747  6747 D LgDataFeature: LgDataFeature() Constructor Done, null
08-08 11:23:29.264  6747  6747 D HeadsetStateMachine: max_hf_connections = 1
,08-08 11:23:29.265  6747  6747 I bluedroid-qcom: get_profile_interface handsfree
08-08 11:23:29.267  6747  6747 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-08 11:23:29.267   313   313 V AudioPolicyService: registerClient() client 0xb558a600, uid 1002
,08-08 11:23:29.268   313  2139 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-08 11:23:29.268   313  2139 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-08 11:23:29.268   313  2139 V AudioPolicyManagerEx: getOutput() returns output 2
08-08 11:23:29.268  6747  6747 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-08 11:23:29.268   313  1377 V AudioFlinger: registerClient() client 0xb1433148, pid 6747
08-08 11:23:29.269   313  1371 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:29.269   313  1371 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:29.269  1597  1618 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:29.269  1597  1618 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:29.270  1025  1641 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:29.270   313  1372 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:29.270  3409  3425 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:29.270   313  1372 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:29.270  1025  1641 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:29.270  3409  3425 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:29.270  6747  6747 V ToneGenerator: Create Track: 0xb4928a80
08-08 11:23:29.270  1025  1641 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:29.270  6747  6747 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-08 11:23:29.270  6747  6747 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-08 11:23:29.270  1025  1641 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:29.270  1597  2088 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:29.270  1597  2088 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:29.270   313  1376 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-08 11:23:29.270   313  1376 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-08 11:23:29.270   313  1376 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-08 11:23:29.270   313  1376 V AudioPolicyManagerEx: getOutput() returns output 2
08-08 11:23:29.270  3409  3424 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:29.270  3409  3424 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:29.270  6747  6747 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-08 11:23:29.270  1848  1863 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:29.271  1848  1863 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-08 11:23:29.271   313  2139 I AudioFlinger: isAudioPlaybackHookOn() false
08-08 11:23:29.271  1848  1863 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:29.271  6747  6764 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-08 11:23:29.271  6747  6764 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-08 11:23:29.271  1848  1863 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-08 11:23:29.271  6747  6764 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-08 11:23:29.271  6747  6764 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-08 11:23:29.271   313  1377 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-08 11:23:29.271   313  1377 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-08 11:23:29.271   313  1377 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-08 11:23:29.271   313  1377 V AudioPolicyManagerEx: getOutput() returns output 2
08-08 11:23:29.272  6747  6747 V AudioSystem: getLatenc,y() output 2, latency 50
08-08 11:23:29.272  6747  6747 V AudioSystem: getFrameCount() output 2, frameCount 960
08-08 11:23:29.272  6747  6747 V AudioTrack: createTrack_l() output 2 afLatency 50
08-08 11:23:29.272   313  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-08 11:23:29.272   313  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-08 11:23:29.272   313  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-08 11:23:29.272   313  2136 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-08 11:23:29.272   313  2136 V AudioFlinger: createTrack() lSessionId: 22
08-08 11:23:29.273  6747  6747 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-08 11:23:29.273   313  2136 V AudioFlinger: acquiring 22 from 6747, for 6747
08-08 11:23:29.273   313  2136 V AudioFlinger:  added new entry for 22
08-08 11:23:29.274  6747  6747 V ToneGenerator: ToneGenerator INIT OK, time: 367454
08-08 11:23:29.274  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.274  6747  6800 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-08 11:23:29.274  6747  6800 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-08 11:23:29.275  6747  6800 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-08 11:23:29.275  6747  6800 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-08 11:23:29.275   313  1376 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6747
08-08 11:23:29.275   313  1376 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-08 11:23:29.275   313  1376 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-08 11:23:29.275   313  1376 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-08 11:23:29.275   313  1376 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-08 11:23:29.275   313  1376 V voice   : voice_set_parameters: exit with code(0)
08-08 11:23:29.275   313  1376 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-08 11:23:29.275   313  1376 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-08 11:23:29.276   313  1376 V msm8974_platform: platform_set_parameters: exit with code(0)
08-08 11:23:29.276   313  1376 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-08 11:23:29.276   313  1376 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-08 11:23:29.276   313  1376 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-08 11:23:29.276  6747  6800 V ToneGenerator: ToneGenerator destructor
08-08 11:23:29.276  6747  6800 V ToneGenerator: stopTone
08-08 11:23:29.276  6747  6800 V ToneGenerator: Delete Track: 0xb4928a80
08-08 11:23:29.276  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.278  6747  6747 D A2dpService: Received start request. Starting profile...
08-08 11:23:29.278  6747  6800 V AudioTrack: ~AudioTrack, releasing session id from 6747 on behalf of 6747
08-08 11:23:29.279   313   313 V AudioPolicyService: AudioCommandThread() adding release output 2
08-08 11:23:29.279   313   313 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-08 11:23:29.279  6747  6779 V LGMDMManager: Create singleton instance
08-08 11:23:29.279   313   313 V AudioFlinger: PlaybackThread::Track destructor
08-08 11:23:29.279   313  1096 V AudioPolicyService: AudioCommandThread() waking up
08-08 11:23:29.279   313  1096 V AudioPolicyService: AudioCommandThread() processing release output 2
08-08 11:23:29.279   313   313 V AudioFlinger: removeClient_l() pid 6747, calling pid 313
,08-08 11:23:29.279   313  1096 V AudioPolicyManager: releaseOutput() 2
08-08 11:23:29.279   313  1096 V AudioPolicyService: AudioCommandThread() going to sleep
08-08 11:23:29.279   313  2136 V AudioFlinger: releasing 22 from 6747 for 6747
08-08 11:23:29.279   313  2136 V AudioFlinger:  decremented refcount to 0
08-08 11:23:29.279   313  2136 V AudioFlinger: purging stale effects
08-08 11:23:29.279  6747  6747 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-08 11:23:29.281  6747  6747 V Avrcp   : make
08-08 11:23:29.282  6747  6747 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-08 11:23:29.282  6747  6747 I bluedroid-qcom: get_profile_interface avrcp
,08-08 11:23:29.288  6747  6779 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-08 11:23:29.288  1025  1946 W Process : Unable to open /proc/6803/status
08-08 11:23:29.297  6747  6747 V AudioManager: registerRemoteController: size of Media player list: 0
08-08 11:23:29.298  6747  6747 E AudioManager: No RCC entry present to update
08-08 11:23:29.298  6747  6747 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-08 11:23:29.302  6747  6747 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-08 11:23:29.304  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-08 11:23:29.304  6747  6747 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-08 11:23:29.309  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-08 11:23:29.411  1025  2026 V SIM_STK : Menu title from STK is T-Mobile
08-08 11:23:29.411  1025  2026 V SIM_STK : Menu title from STK is T-Mobile
,08-08 11:23:29.486  1025  1778 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-08 11:23:29.495  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-08 11:23:29.499  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-08 11:23:29.500  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-08 11:23:29.501  6747  6747 I BluetoothA2dpServiceJni: classInitNative
08-08 11:23:29.501  6747  6747 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 11:23:29.501  6747  6747 D A2dpStateMachine: make
08-08 11:23:29.504  6747  6747 I bluedroid-qcom: get_profile_interface a2dp
08-08 11:23:29.504  6747  6808 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-08 11:23:29.507  6747  6747 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-08 11:23:29.507  6747  6747 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-08 11:23:29.507  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.508  6747  6807 D A2dpStateMachine: Enter Disconnected: -2
08-08 11:23:29.508  6747  6747 I BluetoothHidServiceJni: classInitNative: succeeds
08-08 11:23:29.510  6747  6747 D HidService: Received start request. Starting profile...
08-08 11:23:29.510  6747  6747 I bluedroid-qcom: get_profile_interface hidhost
08-08 11:23:29.510  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.510  6747  6747 I BluetoothHealthServiceJni: classInitNative: succeeds
08-08 11:23:29.512  6747  6747 D HealthService: Received start request. Starting profile...
08-08 11:23:29.514  6747  6747 I bluedroid-qcom: get_profile_interface health
,08-08 11:23:29.515  6747  6747 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-08 11:23:29.515  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.515  6747  6747 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-08 11:23:29.519  6747  6747 D PanService: Received start request. Starting profile...
,08-08 11:23:29.519  6747  6747 D BluetoothPanServiceJni: initializeNative(L110): pan
08-08 11:23:29.519  6747  6747 I bluedroid-qcom: get_profile_interface pan
08-08 11:23:29.525  6747  6747 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-08 11:23:29.525  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.526  6747  6747 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-08 11:23:29.532  6747  6747 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 11:23:29.532  6747  6747 D BtGatt.GattService: Received start request. Starting profile...
08-08 11:23:29.532  6747  6747 D BtGatt.GattService: start()
08-08 11:23:29.532  6747  6747 I bluedroid-qcom: get_profile_interface gatt
08-08 11:23:29.533  6747  6747 D BtGatt.AdvertiseManager: advertise manager created
08-08 11:23:29.538  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.539  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.539  6747  6747 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-08 11:23:29.540  6747  6747 V BluetoothMapService: BluetoothMapBinder()
08-08 11:23:29.541  6747  6747 D BluetoothMapService: Received start request. Starting profile...
08-08 11:23:29.541  6747  6747 D BluetoothMapService: start()
08-08 11:23:29.544  6747  6747 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-08 11:23:29.545  6747  6747 D BluetoothMapEmailAppObserver: createReceiver()
08-08 11:23:29.546  6747  6747 D BluetoothMapEmailAppObserver: initObservers()
08-08 11:23:29.546  6747  6747 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-08 11:23:29.555  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:29.556  6747  6747 D HeadsetStateMachine: Proxy object connected
08-08 11:23:29.557  6747  6747 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-08 11:23:29.557  6747  6747 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-08 11:23:29.558  6747  6800 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-08 11:23:29.558  6747  6800 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-08 11:23:29.559  6747  6800 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-08 11:23:29.561  6747  6747 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-08 11:23:29.566  6747  6747 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-08 11:23:29.568  6747  6747 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:29.571  6747  6747 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-08 11:23:29.575  6747  6747 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-08 11:23:29.575  6747  6747 V PanService: [BTUI] SIM Extra State :ABSENT
08-08 11:23:29.579  6747  6747 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-08 11:23:29.581  6747  6747 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-08 11:23:29.581  6589  6611 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-08 11:23:29.581  6747  6747 V BluetoothMapService: Handler(): got msg=1
08-08 11:23:29.582  6747  6747 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-08 11:23:29.582  6747  6747 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-08 11:23:29.582  6747  6747 V BluetoothSapReceiver: SapReceiver onReceive 
08-08 11:23:29.582  6747  6747 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:29.583  6747  6747 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-08 11:23:29.583  6747  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-08 11:23:29.583  6747  6779 I bluedroid-qcom: enable
08-08 11:23:29.583  6747  6817 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-08 11:23:29.583  6747  6779 I bt_hci_bdroid: init
08-08 11:23:29.585  6747  6779 I bt_vendor: bt-vendor : init
08-08 11:23:29.585  6747  6779 I bt_vendor: bt-vendor : get_bt_soc_type
08-08 11:23:29.585  6747  6779 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-08 11:23:29.585  6747  6779 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-08 11:23:29.585  6747  6779 D bt_userial_mct: userial_init
08-08 11:23:29.585  6747  6817 I bt-btu  : btu_task pending for preload complete event
08-08 11:23:29.585  6747  6779 D bt_hci_bdroid: set_power 1
08-08 11:23:29.585  6747  6779 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-08 11:23:29.585  6747  6779 I bt_vendor: Starting hciattach daemon
08-08 11:23:29.585  6747  6779 I bt_vendor: try to set true
,08-08 11:23:29.569  6820  6820 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:29.569  6820  6820 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:29.599  6821  6821 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-08 11:23:29.664  6827  6827 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-08 11:23:29.682  6828  6828 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-08 11:23:29.740  6830  6830 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-08 11:23:29.754  6831  6831 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-08 11:23:29.769  6832  6832 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-08 11:23:29.795  6833  6833 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-08 11:23:29.824  6835  6835 I libmdmdetect: ESOC framework not supported
,08-08 11:23:29.824  6835  6835 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-08 11:23:29.833  6835  6835 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-08 11:23:29.833  6835  6835 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-08 11:23:29.833  6835  6835 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-08 11:23:29.833  6835  6835 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-08 11:23:29.833  6835  6835 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-08 11:23:29.833  6835  6835 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-08 11:23:29.833  6835  6835 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-08 11:23:29.866  6835  6836 E QC-QMI  : qmi_client [6835] 14: failed to locate client data
08-08 11:23:29.866   472   472 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-08 11:23:29.866   472   472 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-08 11:23:29.934  6843  6843 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-08 11:23:29.947  6844  6844 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-08 11:23:29.985  1025  1537 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-08 11:23:29.987  6747  6779 I bt_vendor: bluetooth satus is on
08-08 11:23:29.988  6747  6779 D bt_hci_bdroid: preload
08-08 11:23:29.988  6747  6819 D bt_userial_mct: userial_open(port:0)
08-08 11:23:29.988  6747  6819 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-08 11:23:29.989  6747  6819 I bt_vendor: Done intiailizing UART,
08-08 11:23:29.989  6747  6819 I bt_vendor: Done intiailizing UART,
08-08 11:23:29.989  6747  6819 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
08-08 11:23:29.990  6747  6819 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
,08-08 11:23:29.990  6747  6846 D bt_userial_mct: Entering userial_read_thread()
,08-08 11:23:29.990  6747  6817 I bt-btu  : btu_task received preload complete event
,08-08 11:23:29.991  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-08 11:23:29.991  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-08 11:23:29.994  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-08 11:23:29.998  6747  6817 I         : BTE_InitTraceLevels -- TRC_HCI
,08-08 11:23:29.998  6747  6817 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-08 11:23:29.998  6747  6817 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-08 11:23:29.998  6747  6817 I         : BTE_InitTraceLevels -- TRC_AVDT
08-08 11:23:29.998  6747  6817 I         : BTE_InitTraceLevels -- TRC_AVRC
08-08 11:23:29.998  6747  6817 I         : BTE_InitTraceLevels -- TRC_A2D
08-08 11:23:29.998  6747  6817 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 11:23:29.998  6747  6817 I         : BTE_InitTraceLevels -- TRC_BTM
08-08 11:23:29.999  6747  6817 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-08 11:23:29.999  6747  6817 I         : BTE_InitTraceLevels -- TRC_GAP
08-08 11:23:29.999  6747  6817 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 11:23:29.999  6747  6817 I         : BTE_InitTraceLevels -- TRC_SDP
08-08 11:23:29.999  6747  6817 I         : BTE_InitTraceLevels -- TRC_GATT
08-08 11:23:29.999  6747  6817 I         : BTE_InitTraceLevels -- TRC_SMP
08-08 11:23:30.002  6747  6817 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 11:23:30.002  6747  6817 I         : BTE_InitTraceLevels -- TRC_BTIF
08-08 11:23:30.044  6747  6817 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-08 11:23:30.045  6747  6817 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f2061 
08-08 11:23:30.045  6747  6817 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f2061 
,08-08 11:23:30.066  6747  6783 E bt-btif : Calling BTA_HhEnable
,08-08 11:23:30.066  6747  6783 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-08 11:23:30.067  6747  6783 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-08 11:23:30.069  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-08 11:23:30.069  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-08 11:23:30.069  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-08 11:23:30.070  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-08 11:23:30.070  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-08 11:23:30.071  6747  6783 D BluetoothAdapterProperties: Name is: G3
08-08 11:23:30.073  1025  1025 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-08 11:23:30.074  1025  1025 D BluetoothManagerService: Stored Bluetooth name: G3
08-08 11:23:30.077  6747  6783 D BluetoothAdapterProperties: Scan Mode:20
08-08 11:23:30.077  6747  6783 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 11:23:30.078  6747  6783 D bt_hci_bdroid: postload
08-08 11:23:30.079  6747  6817 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-08 11:23:30.079  6747  6817 W bt-smp  : Plain text(LSB ~ MSB) = 24 63 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-08 11:23:30.079  6747  6817 W bt-smp  : Encrypted text(LSB ~ MSB) = fa 94 4c 0c 6c 9e 71 99 5c f8 a3 f2 ee 82 21 44 
08-08 11:23:30.079  6747  6817 W bt-btm  : Stopping oneshot timer
08-08 11:23:30.080  6747  6819 D bt_hci_bdroid: Used up Tx Cmd credits
08-08 11:23:30.080  6747  6817 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-08 11:23:30.080  6747  6783 D bte_conf: Device ID record 1 : primary
08-08 11:23:30.080  6747  6783 D bte_conf:   vendorId            = 00c4
08-08 11:23:30.080  6747  6783 D bte_conf:   vendorIdSource      = 0001
08-08 11:23:30.080  6747  6783 D bte_conf:   product             = 13a1
08-08 11:23:30.080  6747  6783 D bte_conf:   version             = 1000
08-08 11:23:30.080  6747  6783 D bte_conf:   clientExecutableURL = 
08-08 11:23:30.080  6747  6783 D bte_conf:   serviceDescription  = 
08-08 11:23:30.080  6747  6783 D bte_conf:   documentationURL    = 
08-08 11:23:30.080  6747  6783 D bte_conf: bte_load_did_conf no section named DID2.
08-08 11:23:30.080  6747  6819 D bt_hci_bdroid: Used up Tx Cmd credits
08-08 11:23:30.080  6747  6819 D bt_hci_bdroid: Used up Tx Cmd credits
08-08 11:23:30.082  6747  6819 D bt_hci_bdroid: Used up Tx Cmd credits
08-08 11:23:30.082  6747  6846 E bt_mct  : hci lib postload completed
08-08 11:23:30.084  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:30.086  6747  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-08 11:23:30.086  6747  6779 D BluetoothAdapterProperties: ScanMode =  20
08-08 11:23:30.086  6747  6779 D BluetoothAdapterProperties: State =  11
08-08 11:23:30.086  6747  6779 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
,08-08 11:23:30.069  6853  6853 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:30.069  6853  6853 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:30.091  6747  6779 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-08 11:23:30.091  6747  6779 D BluetoothAdapterProperties: Setting state to 12
08-08 11:23:30.092  6747  6779 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 11:23:30.093  1025  1087 D BluetoothManagerService: Message: 60
,08-08 11:23:30.093  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-08 11:23:30.093  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-08 11:23:30.093  1025  1087 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:23:30.095  6747  6779 I BluetoothAdapterState: Entering On State
08-08 11:23:30.097  6747  6783 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-08 11:23:30.097  6747  6783 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-08 11:23:30.102  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:30.102  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:30.102  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:30.102  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:30.102  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:30.102  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:30.102  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:30.102  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:23:30.107  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:30.108  1848  4095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:23:30.117  1025  1025 D BluetoothHeadset: Proxy object connected
,08-08 11:23:30.119  6747  6779 D LGBluetoothServiceAdapter: [BTUI] OnState
,08-08 11:23:30.120  6747  6779 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-08 11:23:30.120  6747  6779 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-08 11:23:30.120  6747  6779 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-08 11:23:30.122  1848  1848 D BluetoothHeadset: Proxy object connected
08-08 11:23:30.122  6120  6138 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 11:23:30.124  6120  6140 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 11:23:30.127  6120  6120 D BluetoothHeadset: Proxy object connected
08-08 11:23:30.127  6120  6120 D HeadsetProfile: Bluetooth service connected
08-08 11:23:30.128  6120  6138 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 11:23:30.128  6747  6783 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 11:23:30.128  6747  6783 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-08 11:23:30.132  1025  1087 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 11:23:30.132  6120  6120 D BluetoothInputDevice: Proxy object connected
,08-08 11:23:30.132  6120  6120 D HidProfile: Bluetooth service connected
,08-08 11:23:30.139  1025  1025 D BluetoothA2dp: Proxy object connected
08-08 11:23:30.141  6120  6140 D BluetoothMap: onBluetoothStateChange: up=true
08-08 11:23:30.145  6747  6779 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-08 11:23:30.146  6120  6138 D BluetoothPan: onBluetoothStateChange on: true
,08-08 11:23:30.146  6120  6138 D BluetoothPan: onBluetoothStateChange call bindService
08-08 11:23:30.152  6120  6140 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 11:23:30.155  1848  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:23:30.158  1848  1848 D BluetoothHeadset: Proxy object connected
08-08 11:23:30.158  1848  1863 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:23:30.160  1848  1848 D BluetoothHeadset: Proxy object connected
08-08 11:23:30.161  1025  1087 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-08 11:23:30.162  1025  1025 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-08 11:23:30.161  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-08 11:23:30.165  6861  6861 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-08 11:23:30.168  6120  6120 D BluetoothMap: Proxy object connected
08-08 11:23:30.168  6120  6120 D MapProfile: Bluetooth service connected
08-08 11:23:30.168  6120  6120 D BluetoothMap: getConnectedDevices()
08-08 11:23:30.169  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:30.169  6747  6764 V BluetoothMapService: getConnectedDevices()
08-08 11:23:30.169  1937  2116 D LGBluetoothAPIService: Message: 1
08-08 11:23:30.169  1937  2116 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-08 11:23:30.170  1937  2116 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-08 11:23:30.170  1937  2116 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-08 11:23:30.171  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-08 11:23:30.173  1025  1087 D BluetoothManagerService: Message: 40
08-08 11:23:30.173  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-08 11:23:30.176  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:30.176  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:30.176  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:30.176  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:30.176  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:23:30.176  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:30.176  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:30.176  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:23:30.178  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:30.180  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:30.181  6120  6120 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 11:23:30.181  6120  6120 D PanProfile: Bluetooth service connected
08-08 11:23:30.183  6747  6747 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:30.183  6747  6747 D BluetoothMapService: STATE_ON
08-08 11:23:30.190  6120  6120 D BluetoothA2dp: Proxy object connected
08-08 11:23:30.190  6120  6120 D A2dpProfile: Bluetooth service connected
,08-08 11:23:30.195  6120  6120 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-08 11:23:30.197  6120  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-08 11:23:30.200  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:30.200  6747  6747 V BluetoothPbapService: Pbap Service onCreate
08-08 11:23:30.200  6747  6747 V BluetoothPbapService: Starting PBAP service
08-08 11:23:30.202  6747  6747 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-08 11:23:30.202  6747  6747 V BluetoothPbapService: Pbap Service onBind
08-08 11:23:30.203  6747  6747 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:30.203  6747  6747 V BluetoothPbapService: state: 12
08-08 11:23:30.203  6747  6747 V BluetoothMapService: Handler(): got msg=1
,08-08 11:23:30.204  6747  6747 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-08 11:23:30.204  6747  6747 V BluetoothPbapService: Handler(): got msg=1
08-08 11:23:30.205  6120  6120 D DockEventReceiver: finishStartingService: stopping service
08-08 11:23:30.205  6747  6747 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-08 11:23:30.205  6120  6120 D BluetoothPbap: Proxy object connected
08-08 11:23:30.206  6120  6120 D PbapServerProfile: Bluetooth service connected
,08-08 11:23:30.207  6747  6870 D BluetoothMapMasInstance: MAS initSocket()
08-08 11:23:30.207  6747  6747 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-08 11:23:30.207  6747  6747 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:30.207  6747  6747 V BluetoothPbapReceiver: ***********state = 12
08-08 11:23:30.208  6747  6870 D BluetoothMapMasInstance:   masId = 00
08-08 11:23:30.208  6747  6870 D BluetoothMapMasInstance:   msgTypes = 0e
08-08 11:23:30.208  6747  6870 D BluetoothMapMasInstance:   masName = SMS/MMS
08-08 11:23:30.208  6747  6870 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-08 11:23:30.208  6747  6871 V BluetoothPbapService: Pbap Service initSocket
08-08 11:23:30.211  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:23:30.211  2203  2203 D c       : Getting all permits...
08-08 11:23:30.211  2203  2203 D a       : Opening database...
08-08 11:23:30.213  1025  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:30.213  1025  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:30.214  6747  6871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:30.215  6747  6870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:30.216  6747  6871 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-08 11:23:30.216  6747  6871 V BluetoothPbapService: Succeed to create listening socket 
08-08 11:23:30.216  6747  6871 V BluetoothPbapService: Accepting socket connection...
08-08 11:23:30.217  6747  6870 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-08 11:23:30.217  6747  6870 V BluetoothMapMasInstance: Succeed to create listening socket 
08-08 11:23:30.217  6747  6870 D BluetoothMapMasInstance: Accepting socket connection...
08-08 11:23:30.217  2203  2203 D a       : Opening database auth.proximity.permit_store...
08-08 11:23:30.217  6747  6783 D BluetoothAdapterProperties: Scan Mode:21
,08-08 11:23:30.217  6747  6783 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-08 11:23:30.219  2203  2203 D a       : Closing database...
08-08 11:23:30.222  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:30.223  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:30.232  6120  6120 D BluetoothPermissionRequest: onReceive
,08-08 11:23:30.235  6120  6120 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-08 11:23:30.236  6120  6120 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-08 11:23:30.240  6747  6747 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-08 11:23:30.242  6747  6747 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-08 11:23:30.251  6747  6747 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-08 11:23:30.278  6747  6747 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-08 11:23:30.279  6747  6747 V BtOppService: onCreate
,08-08 11:23:30.284  6747  6747 V BluetoothOppNotification: send message
08-08 11:23:30.288  6747  6747 V BtOppService: Starting RfcommListener
08-08 11:23:30.298  6747  6747 D BluetoothOppPreference: Dumping Names:  
08-08 11:23:30.298  6747  6747 D BluetoothOppPreference: {}
08-08 11:23:30.298  6747  6747 D BluetoothOppPreference: Dumping Channels:  
,08-08 11:23:30.298  6747  6747 D BluetoothOppPreference: {}
08-08 11:23:30.301  6747  6747 V BtOppService: onStartCommand
,08-08 11:23:30.303  6747  6877 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-08 11:23:30.309  6747  6747 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:30.310  6747  6747 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-08 11:23:30.317  6747  6877 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-08 11:23:30.317  6747  6747 V BluetoothOppNotification: new notify threadi!
08-08 11:23:30.319  6747  6874 V BtOppService: Deleted complete outbound shares, number =  0
08-08 11:23:30.319  6747  6747 V BluetoothOppNotification: send delay message
08-08 11:23:30.320  6747  6877 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32d97b4d on behalf of 
08-08 11:23:30.320  6747  6747 V BtOppService: start RfcommListener
08-08 11:23:30.323  6747  6877 V BluetoothOppNotification: update too frequent, put in queue
08-08 11:23:30.323  6747  6874 V BtOppService: Deleted complete inbound failed shares, number = 0
08-08 11:23:30.324  6747  6747 V BtOppService: RfcommListener started
08-08 11:23:30.324  6747  6874 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-08 11:23:30.325  6747  6877 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-08 11:23:30.325  6747  6877 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-08 11:23:30.326  6747  6874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14b92602 on behalf of 
08-08 11:23:30.327  6747  6879 V BtOppRfcommListener: Starting RFCOMM listener....
,08-08 11:23:30.330  6747  6878 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-08 11:23:30.331  6747  6877 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23f5fb13 on behalf of 
08-08 11:23:30.332  1025  1911 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:30.333  6747  6879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:30.334  6747  6877 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-08 11:23:30.334  6747  6879 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-08 11:23:30.335  6747  6879 V BtOppRfcommListener: Started RFCOMM listener....
08-08 11:23:30.336  6747  6878 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5ede150 on behalf of 
08-08 11:23:30.336  6747  6879 I BtOppRfcommListener: Accept thread started.
08-08 11:23:30.336  6747  6879 V BtOppRfcommListener: Accepting connection...
08-08 11:23:30.336  6747  6878 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-08 11:23:30.338  6747  6878 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-08 11:23:30.339  6747  6878 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14cf7f49 on behalf of 
08-08 11:23:30.340  6747  6878 V BluetoothOppNotification: outbound: succ-0  fail-0
08-08 11:23:30.342  6747  6878 V BluetoothOppNotification: outbound notification was removed.
,08-08 11:23:30.342  6747  6878 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-08 11:23:30.345  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:30.345  6747  6747 V BluetoothFtpService: Ftp Service onCreate
08-08 11:23:30.345  6747  6747 I BluetoothFtpService: Ftp Service onCreate
08-08 11:23:30.345  6747  6747 V BluetoothFtpService: Ftp Service onStartCommand
08-08 11:23:30.346  6747  6747 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:30.346  6747  6878 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@dbb356f on behalf of 
08-08 11:23:30.346  6747  6747 V BluetoothFtpService: Starting Listening on sockets
08-08 11:23:30.346  6747  6747 V BtOppService: ContentObserver received notification
08-08 11:23:30.346  6747  6878 V BluetoothOppNotification: inbound: succ-0  fail-0
08-08 11:23:30.346  6747  6747 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-08 11:23:30.346  6747  6747 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-08 11:23:30.347  6747  6747 V BluetoothSapReceiver: SapReceiver onReceive 
08-08 11:23:30.347  6747  6747 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:30.347  6747  6747 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-08 11:23:30.347  6747  6747 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-08 11:23:30.349  6747  6747 V BtOppService: ContentObserver received notification
08-08 11:23:30.351  6747  6880 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-08 11:23:30.351  6747  6878 V BluetoothOppNotification: inbound notification was removed.
08-08 11:23:30.351  6747  6878 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-08 11:23:30.351  6747  6747 V BluetoothFtpService: Handler(): got msg=1
,08-08 11:23:30.353  6747  6747 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-08 11:23:30.353  6747  6747 V BluetoothFtpService: Ftp Service initSocket
08-08 11:23:30.354  6747  6878 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@25d7c27c on behalf of 
08-08 11:23:30.355  6747  6880 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-08 11:23:30.357  6747  6880 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@207c705 on behalf of 
08-08 11:23:30.358  1025  1640 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:30.358  6747  6880 V BluetoothOppNotification: update too frequent, put in queue
08-08 11:23:30.359  6747  6880 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-08 11:23:30.359  6747  6747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:23:30.359  6747  6880 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-08 11:23:30.360  6747  6880 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ed1735a on behalf of 
08-08 11:23:30.361  6747  6880 V BluetoothOppNotification: update too frequent, put in queue
08-08 11:23:30.361  6747  6747 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-08 11:23:30.362  6747  6880 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-08 11:23:30.362  6747  6747 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-08 11:23:30.364  6747  6881 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-08 11:23:30.388  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
,08-08 11:23:30.388  6747  6747 V BluetoothSapService: Sap Service onCreate
08-08 11:23:30.390  6747  6747 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:30.390  6747  6747 V BluetoothSapService: state: 12
08-08 11:23:30.390  6747  6747 V BluetoothSapService: Starting SAP server process
08-08 11:23:30.392  6747  6747 V BluetoothSapService: SAP Service startRfcommListenerThread
08-08 11:23:30.393  6747  6882 V BluetoothSapService: Sap Service initRfcommSocket
08-08 11:23:30.379  6883  6883 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:30.379  6883  6883 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-08 11:23:30.399  1025  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:30.400  6747  6882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 11:23:30.401  6747  6882 V BluetoothSapService: Succeed to create listening socket 
08-08 11:23:30.402  6747  6882 V BluetoothSapService: Accepting socket connection...
08-08 11:23:30.410  6883  6883 V BT_SAP  : Event pipe created
08-08 11:23:30.410  6883  6883 V BT_SAP  : create_server_socket qcom.sap.server
08-08 11:23:30.410  6883  6883 V BT_SAP  : created socket fd 6
08-08 11:23:30.517  1025  2028 I ActivityManager: Killing 6428:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-08 11:23:30.574  1025  1946 W libprocessgroup: failed to open /acct/uid_10011/pid_6428/cgroup.procs: No such file or directory
,08-08 11:23:30.827  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-08 11:23:30.828  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-08 11:23:30.841  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-08 11:23:30.842  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-08 11:23:30.846  1937  2064 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-08 11:23:30.846  1937  2064 D LEDHandler: Battery Level Remaining: 100%
08-08 11:23:30.846  1937  2064 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-08 11:23:30.847  1025  1536 D WifiController: battery changed pluggedType: 2
08-08 11:23:30.848  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-08 11:23:30.853  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:30.853  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:23:30.854  6747  6800 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-08 11:23:30.857  5850  5850 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-08 11:23:31.321  6747  6747 V BluetoothOppNotification: new notify threadi!
,08-08 11:23:31.321  6747  6747 V BluetoothOppNotification: send delay message
,08-08 11:23:31.334  6747  6893 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-08 11:23:31.338  6747  6893 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3aa36b26 on behalf of 
08-08 11:23:31.342  6747  6893 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-08 11:23:31.345  6747  6893 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-08 11:23:31.347  6747  6893 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@79e6367 on behalf of 
08-08 11:23:31.348  6747  6893 V BluetoothOppNotification: outbound: succ-0  fail-0
08-08 11:23:31.349  6747  6893 V BluetoothOppNotification: outbound notification was removed.
08-08 11:23:31.349  6747  6893 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-08 11:23:31.350  6747  6893 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@963e514 on behalf of 
08-08 11:23:31.351  6747  6893 V BluetoothOppNotification: inbound: succ-0  fail-0
08-08 11:23:31.354  6747  6893 V BluetoothOppNotification: inbound notification was removed.
08-08 11:23:31.354  6747  6893 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-08 11:23:31.357  6747  6893 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30ccd1bd on behalf of 
,08-08 11:23:31.930  5992  6047 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:23:31.930  5992  6047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 11:23:34.945  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:23:34.945  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27ade13f added. We now have 6 listener(s)
08-08 11:23:34.945  5992  6047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 11:23:34.954  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:23:34.954  5992  6047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15644a0c added. We now have 7 listener(s)
08-08 11:23:34.954  5992  6047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:23:34.955  5992  6047 I System.out: IsBluetoothEnabled
08-08 11:23:34.956  1025  1778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:34.956  1025  1778 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@142206e mBinding = false
,08-08 11:23:34.982  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-08 11:23:34.982  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-08 11:23:34.982  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-08 11:23:34.983  1025  1087 D BluetoothManagerService: Message: 2
08-08 11:23:34.983  1025  1087 D BluetoothManagerService: Sending off request.
08-08 11:23:34.984  6747  6763 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-08 11:23:34.985  6747  6779 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-08 11:23:34.985  6747  6779 D BluetoothAdapterProperties: Setting state to 13
08-08 11:23:34.985  6747  6779 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-08 11:23:34.986  6747  6779 D BluetoothAdapterProperties: onBluetoothDisable()
08-08 11:23:34.986  6747  6779 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-08 11:23:34.987  6747  6783 D BluetoothAdapterProperties: Scan Mode:20
08-08 11:23:34.989  6747  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-08 11:23:34.990  6747  6871 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-08 11:23:34.994  6747  6870 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-08 11:23:34.994  6747  6870 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:34.994  6747  6870 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-08 11:23:34.994  6747  6870 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-08 11:23:34.994  6747  6870 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-08 11:23:34.994  6747  6870 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-08 11:23:34.994  6747  6870 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-08 11:23:34.994  6747  6870 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-08 11:23:34.995  6747  6879 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:34.995  6747  6881 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:34.996  6747  6882 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:23:34.997  6747  6779 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-08 11:23:34.999  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-08 11:23:34.999  6747  6817 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-08 11:23:35.002  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-08 11:23:35.002  6747  6817 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-08 11:23:35.006  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:35.006  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:35.006  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:35.006  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:35.006  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:35.006  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:35.006  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:35.006  5992  5992 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:35.006  5992  5992 V io.jxcore.node.ConnectivityM,onitor:     - active network type is Wi-Fi: false
,08-08 11:23:35.017  5992  5992 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:35.017  5992  5992 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:35.023  1025  1087 D BluetoothManagerService: Message: 60
08-08 11:23:35.023  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-08 11:23:35.023  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-08 11:23:35.030  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.031  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-08 11:23:35.035  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:23:35.038  6747  6747 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.038  6747  6747 D BluetoothMapService: STATE_TURNING_OFF
08-08 11:23:35.038  6747  6747 V BluetoothMapService: Handler(): got msg=4
08-08 11:23:35.038  6747  6747 D BluetoothMapService: MAP Service closeService in
08-08 11:23:35.038  6747  6747 D BluetoothMapMasInstance: MAP Service shutdown
08-08 11:23:35.038  6747  6747 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-08 11:23:35.038  6747  6747 V BluetoothMapService: MAP Service closeService out
,08-08 11:23:35.042  6747  6747 V BtOppService: Receiver DISABLED_ACTION 
08-08 11:23:35.042  6747  6747 I BtOppRfcommListener: stopping Accept Thread
08-08 11:23:35.042  6747  6747 V BtOppRfcommListener: close mBtServerSocket
08-08 11:23:35.043  6747  6879 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 11:23:35.043  6747  6747 V BtOppRfcommListener: waiting for thread to terminate
08-08 11:23:35.043  6747  6747 V BtOppRfcommListener: done waiting for thread to terminate
08-08 11:23:35.046  6120  6120 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-08 11:23:35.056  6120  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-08 11:23:35.060  6747  6747 V BtOppService: onDestroy
08-08 11:23:35.062  6747  6747 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-08 11:23:35.066  6747  6747 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-08 11:23:35.066  6747  6747 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.067  6747  6747 V BluetoothPbapReceiver: ***********state = 13
08-08 11:23:35.068  6747  6747 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-08 11:23:35.073  6747  6747 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.073  6747  6747 V BluetoothPbapService: state: 13
08-08 11:23:35.073  6747  6747 V BluetoothPbapService: Pbap Service closeService in
08-08 11:23:35.075  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:23:35.076  6747  6747 V BluetoothPbapService: successfully stopped pbap service
08-08 11:23:35.077  6747  6747 V BluetoothPbapService: Pbap Service closeService out
08-08 11:23:35.079  6747  6747 V BluetoothPbapService: Pbap Service onDestroy
08-08 11:23:35.079  6747  6747 V BluetoothPbapService: Pbap Service closeService in
08-08 11:23:35.079  6747  6747 V BluetoothPbapService: Pbap Service closeService out
08-08 11:23:35.080  6747  6747 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-08 11:23:35.087  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:35.087  5992  6047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:23:35.087  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:23:35.087  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 11:23:35.087  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:23:35.087  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:23:35.087  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:23:35.087  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:23:35.087  5992  6047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:23:35.097  5992  6047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:23:35.097  5992  6047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:23:35.102  6747  6783 D bt_hci_bdroid: cleanup
08-08 11:23:35.102  6747  6817 W bt-btif : ag scb idx 1 not allocated
,08-08 11:23:35.102  6747  6817 E bt-btif : BTA AG is already disabled, ignoring ...
08-08 11:23:35.102  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:35.102  6747  6817 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:23:35.102  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:35.102  6747  6817 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:23:35.102  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:35.102  6747  6817 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-08 11:23:35.102  6747  6819 I bt_lpm  : LPM is already off!!!
08-08 11:23:35.102  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:23:35.103  6747  6846 I bt_userial_mct: exiting userial_read_thread
08-08 11:23:35.103  6747  6846 D bt_userial_mct: Leaving userial_evt_read_thread()
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-08 11:23:35.103  6747  6783 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:23:35.103  6747  6819 I bt_vendor: hw_epilog_process
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-08 11:23:35.103  6747  6817 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-08 11:23:35.103  6747  6817 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-08 11:23:35.103  6747  6783 D bt_hci_bdroid: cleanup Finalizing cleanup
08-08 11:23:35.103  6747  6783 D bt_userial_mct: userial_close
08-08 11:23:35.103  6747  6783 E bt_userial_mct: pthread_join() FAILED result:3
08-08 11:23:35.103  6747  6783 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-08 11:23:35.110  1025  1946 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 11:23:35.110  6120  6120 D DockEventReceiver: finishStartingService: stopping service
08-08 11:23:35.111  1025  1946 D BluetoothManagerService: enable():  mBluetooth =android.bluetooth.IBluetooth$Stub$Proxy@142206e mBinding = false
08-08 11:23:35.112  6120  6120 D BluetoothPbap: Proxy object disconnected
08-08 11:23:35.112  6120  6120 D PbapServerProfile: Bluetooth service disconnected
08-08 11:23:35.117  6120  6120 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-08 11:23:35.122  6120  6120 D BluetoothPermissionRequest: onReceive
08-08 11:23:35.122  6120  6120 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-08 11:23:35.122  1025  1087 D BluetoothManagerService: Message: 1
08-08 11:23:35.122  1025  1087 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@142206e
08-08 11:23:35.123  1025  1025 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-08 11:23:35.123  1025  1025 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-08 11:23:35.123  1025  1025 D Ulp_jni : JNI:system_update. Event-4
08-08 11:23:35.125  6747  6866 D BluetoothAdapterService: enable() : BT State is not STATE_OFF. Can't enable BT
08-08 11:23:35.125  1025  1087 E BluetoothManagerService: IBluetooth.enable() returned false
08-08 11:23:35.128  6120  6120 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-08 11:23:35.131  6747  6747 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-08 11:23:35.131  6747  6747 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-08 11:23:35.132  6747  6747 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-08 11:23:35.136  6747  6747 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.136  6747  6747 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-08 11:23:35.137  6747  6747 V BluetoothFtpService: Ftp Service onStartCommand
08-08 11:23:35.137  6747  6747 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.137  6747  6747 V BluetoothFtpService: Ftp Service closeService
08-08 11:23:35.137  6747  6747 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-08 11:23:35.139  6747  6747 V BluetoothFtpService: successfully stopped ftp service
08-08 11:23:35.139  6747  6747 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-08 11:23:35.139  6747  6747 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-08 11:23:35.139  6747  6747 V BluetoothSapReceiver: SapReceiver onReceive 
08-08 11:23:35.139  6747  6747 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.139  6747  6747 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-08 11:23:35.139  6747  6747 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-08 11:23:35.140  6747  6747 V BluetoothFtpService: Ftp Service onDestroy
08-08 11:23:35.140  6747  6747 V BluetoothFtpService: Ftp Service closeService
08-08 11:23:35.144  6747  6747 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.144  6747  6747 V BluetoothSapService: state: 13
08-08 11:23:35.145  6747  6747 V BluetoothSapService: Stopping SAP server process
08-08 11:23:35.146  6747  6747 V BluetoothSapService: Sap Service closeSapService in
08-08 11:23:35.146  6747  6747 V BluetoothSapService: Close listen Socket : 
08-08 11:23:35.146  6747  6747 V BluetoothSapService: Close rfcomm Socket : 
08-08 11:23:35.146  6747  6747 V BluetoothSapService: Close sapd  Socket : 
,08-08 11:23:35.148  6747  6747 V BluetoothSapService: Sap Service closeSapService out
08-08 11:23:35.148  6747  6747 V BluetoothSapService: Sap Service onDestroy
08-08 11:23:35.148  6747  6747 V BluetoothSapService: Sap Service closeSapService in
08-08 11:23:35.148  6747  6747 V BluetoothSapService: Close listen Socket : 
08-08 11:23:35.148  6747  6747 V BluetoothSapService: Close rfcomm Socket : 
08-08 11:23:35.148  6747  6747 V BluetoothSapService: Close sapd  Socket : 
08-08 11:23:35.148  6747  6747 V BluetoothSapService: Sap Service closeSapService out
08-08 11:23:35.200  6747  6783 D bt_hci_bdroid: set_power 0
,08-08 11:23:35.200  6747  6783 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-08 11:23:35.200  6747  6783 I bt_vendor: bluetooth satus is on
08-08 11:23:35.200  6747  6783 I bt_vendor: bt-vendor : resetting BT status
08-08 11:23:35.200  6747  6783 I bt_vendor: Starting hciattach daemon
08-08 11:23:35.200  6747  6783 I bt_vendor: try to set false
08-08 11:23:35.205  6747  6783 I bt_vendor: Starting hciattach daemon
08-08 11:23:35.205  6747  6783 I bt_vendor: try to set false
08-08 11:23:35.208  6747  6783 I bt_vendor: cleanup
08-08 11:23:35.209  6747  6817 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-08 11:23:35.213  6747  6783 I GKI_LINUX: GKI_exit_task 0 done
08-08 11:23:35.213  6747  6783 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-08 11:23:35.218  6747  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-08 11:23:35.222  6747  6747 D HeadsetService: Received stop request...Stopping profile...
08-08 11:23:35.224  6747  6747 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-08 11:23:35.224  6747  6747 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 11:23:35.224  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:35.225  6747  6800 D HeadsetStateMachine: Exit Disconnected: -1
08-08 11:23:35.227  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-08 11:23:35.227  1848  1848 D BluetoothHeadset: Proxy object disconnected
,08-08 11:23:35.230  1025  1025 D BluetoothHeadset: Proxy object disconnected
,08-08 11:23:35.231  6747  6747 D A2dpService: Received stop request...Stopping profile...
08-08 11:23:35.231  1025  1025 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-08 11:23:35.232  6747  6747 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-08 11:23:35.233  1848  1848 D BluetoothHeadset: Proxy object disconnected
08-08 11:23:35.232  6747  6807 D A2dpStateMachine: Exit Disconnected: -1
08-08 11:23:35.233  6120  6120 D BluetoothHeadset: Proxy object disconnected
08-08 11:23:35.233  6120  6120 D HeadsetProfile: Bluetooth service disconnected
08-08 11:23:35.238  6747  6747 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-08 11:23:35.238  6747  6747 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 11:23:35.238  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:35.238  6747  6779 D BluetoothAdapterState: Stopping profile services that were post enabled
08-08 11:23:35.239  6120  6120 D BluetoothA2dp: Proxy object disconnected
08-08 11:23:35.239  1025  1025 D BluetoothA2dp: Proxy object disconnected
08-08 11:23:35.239  6120  6120 D A2dpProfile: Bluetooth service disconnected
08-08 11:23:35.239  1025  1025 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-08 11:23:35.241  6747  6747 D HidService: Received stop request...Stopping profile...
08-08 11:23:35.241  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:35.243  6120  6120 D BluetoothInputDevice: Proxy object disconnected
08-08 11:23:35.243  6120  6120 D HidProfile: Bluetooth service disconnected
08-08 11:23:35.245  6747  6747 D HealthService: Received stop request...Stopping profile...
08-08 11:23:35.245  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:35.247  6747  6747 D HeadsetStateMachine: Unbinding service...
08-08 11:23:35.248  6747  6747 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-08 11:23:35.248  6747  6747 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-08 11:23:35.248  6747  6747 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-08 11:23:35.248  6747  6747 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-08 11:23:35.249  6747  6747 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-08 11:23:35.249  6747  6747 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 11:23:35.249  6747  6747 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-08 11:23:35.250  6747  6747 D PanService: Received stop request...Stopping profile...
08-08 11:23:35.250  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:35.252  6747  6747 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 11:23:35.253  6747  6747 D BtGatt.GattService: Received stop request...Stopping profile...
08-08 11:23:35.253  6747  6747 D BtGatt.GattService: stop()
08-08 11:23:35.253  6747  6747 D BtGatt.AdvertiseManager: advertise clients cleared
08-08 11:23:35.254  6120  6120 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 11:23:35.254  6120  6120 D PanProfile: Bluetooth service disconnected
08-08 11:23:35.255  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:35.257  6747  6747 D BluetoothMapService: Received stop request...Stopping profile...
08-08 11:23:35.257  6747  6747 D BluetoothMapService: stop()
08-08 11:23:35.258  6747  6747 D BluetoothMapEmailAppObserver: deinitObservers()
08-08 11:23:35.259  6747  6747 D BluetoothMapEmailAppObserver: removeReceiver()
08-08 11:23:35.260  6747  6747 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2285f8c1
08-08 11:23:35.261  6120  6120 D BluetoothMap: Proxy object disconnected
08-08 11:23:35.261  6120  6120 D MapProfile: Bluetooth service disconnected
08-08 11:23:35.262  6747  6747 I BluetoothA2dpServiceJni: cleanupNative
08-08 11:23:35.262  6747  6808 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-08 11:23:35.263  6747  6747 I GKI_LINUX: GKI_exit_task 2 done
,08-08 11:23:35.263  6747  6747 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-08 11:23:35.263  6747  6747 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 11:23:35.263  6747  6747 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-08 11:23:35.264  6747  6747 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-08 11:23:35.264  6747  6747 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 11:23:35.265  6747  6747 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 11:23:35.265  6747  6747 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-08 11:23:35.265  6747  6747 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-08 11:23:35.267  6747  6747 V BluetoothMapService: Handler(): got msg=4
08-08 11:23:35.268  6747  6747 D BluetoothMapService: MAP Service closeService in
08-08 11:23:35.268  6747  6747 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-08 11:23:35.268  6747  6747 V BluetoothMapService: MAP Service closeService out
08-08 11:23:35.268  6747  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-08 11:23:35.269  6747  6779 D BluetoothAdapterProperties: Setting state to 10
08-08 11:23:35.269  6747  6779 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-08 11:23:35.270  1025  1087 D BluetoothManagerService: Message: 60
08-08 11:23:35.270  1025  1087 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-08 11:23:35.270  1025  1087 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-08 11:23:35.270  1025  1087 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:35.271  6747  6747 D BluetoothMapService: cleanup()
08-08 11:23:35.271  6747  6747 D BluetoothMapService: MAP Service closeService in
08-08 11:23:35.271  6747  6747 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-08 11:23:35.271  6747  6747 V BluetoothMapService: MAP Service closeService out
08-08 11:23:35.272  6747  6779 I BluetoothAdapterState: Entering OffState
08-08 11:23:35.273  1848  2628 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:35.275  6120  6140 D BluetoothPbap: onBluetoothStateChange: up=false
,08-08 11:23:35.276  6120  6858 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:35.278  6120  6138 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 11:23:35.279  1025  1087 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:23:35.279  6120  6140 D BluetoothMap: onBluetoothStateChange: up=false
08-08 11:23:35.280  6120  6858 D BluetoothPan: onBluetoothStateChange on: false
08-08 11:23:35.281  6120  6138 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:23:35.283  1848  4093 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:35.284  1848  1865 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:23:35.285  1025  1087 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-08 11:23:35.288  1937  1937 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.290  1937  2116 D LGBluetoothAPIService: Message: 2
08-08 11:23:35.290  1937  2116 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@779070c mBinding = false
,08-08 11:23:35.291  1937  2116 D LGBluetoothAPIService: Sending unbind request.
08-08 11:23:35.292  5992  5992 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:23:35.292  1597  1597 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-08 11:23:35.295  6120  6120 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-08 11:23:35.295  6120  6120 D LGBluetoothEventManager: [BTUI] clear device connection state
08-08 11:23:35.298  6747  6747 D LGBluetoothAPIServer: [BTUI] onUnbind()
08-08 11:23:35.298  6747  6747 D LGBluetoothAPIServer: [BTUI] cleanup() done
08-08 11:23:35.298  6747  6747 D LGBluetoothAPIServer: [BTUI] onDestroy()
08-08 11:23:35.300  6120  6120 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-08 11:23:35.307  6747  6747 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-08 11:23:35.307  6747  6747 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.307  6747  6747 V BluetoothPbapReceiver: ***********state = 10
08-08 11:23:35.310  6120  6120 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:23:35.315  2203  2203 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:23:35.331  6120  6120 D BluetoothPermissionRequest: onReceive
,08-08 11:23:35.333  6120  6120 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-08 11:23:35.333  6120  6120 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-08 11:23:35.337  6120  6120 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-08 11:23:35.345  6747  6747 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-08 11:23:35.347  6747  6747 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-08 11:23:35.347  6747  6747 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-08 11:23:35.347  6747  6747 V BluetoothSapReceiver: SapReceiver onReceive 
08-08 11:23:35.348  6747  6747 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:23:35.348  6747  6747 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-08 11:23:35.350  6246  6246 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-08 11:23:58.064  1025  1531 E WifiStateMachine:  DisconnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-08 11:23:58.065  1025  1531 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0,
08-08 11:23:58.066  1025  1531 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-08 11:23:58.068  1025  1531 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-08 11:23:58.082  1025  1531 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-08 11:24:00.003  1025  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=235384520, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-08 11:24:00.030  6227  6227 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-08 11:24:00.030  6227  6227 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5520
,08-08 11:24:00.059  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,08-08 11:24:00.069  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:24:00.069  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:24:00.069  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:24:00.070  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
08-08 11:24:00.073  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:24:00.073  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:24:00.074  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:24:00.077  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:24:00.113  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=235384520 [*alarm*], flags=0x0
,08-08 11:24:30.982  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-08 11:24:30.982  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-08 11:24:30.998  1025  1536 D WifiController: battery changed pluggedType: 2
,08-08 11:24:31.003  1937  2064 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-08 11:24:31.003  1937  2064 D LEDHandler: Battery Level Remaining: 100%
08-08 11:24:31.003  1937  2064 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
08-08 11:24:31.005  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
08-08 11:24:31.005  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-08 11:24:31.007  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-08 11:24:31.010  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:24:31.011  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:24:31.013  5850  5850 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-08 11:25:00.057  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:25:00.057  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:25:00.057  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:25:00.058  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:25:00.071  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:25:00.071  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:25:00.072  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:25:00.074  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:25:37.240  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-08 11:25:37.244  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
08-08 11:25:37.252  1937  2064 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-08 11:25:37.252  1937  2064 D LEDHandler: Battery Level Remaining: 100%
08-08 11:25:37.252  1937  2064 D LEDHandler: Battery Temp: 282, mChargingStatus=5, mChargingStop=false
08-08 11:25:37.255  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
08-08 11:25:37.255  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-08 11:25:37.260  1025  1536 D WifiController: battery changed pluggedType: 2
08-08 11:25:37.261  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-08 11:25:37.267  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:25:37.267  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:25:37.270  5850  5850 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-08 11:26:00.072  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:26:00.073  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:26:00.073  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:26:00.073  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:26:00.087  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:26:00.087  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:26:00.091  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:26:00.093  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:27:00.113  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:27:00.113  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-08 11:27:00.114  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:27:00.114  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:27:00.130  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:27:00.131  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:27:00.131  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:27:00.134  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:28:00.115  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:28:00.115  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:28:00.115  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:28:00.116  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:28:00.130  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:28:00.130  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:28:00.132  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:28:00.134  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:28:45.764  1025  1370 V AlarmManager: RTC_WAKEUP set : Alarm{304bdda5 type 0 when 1470648204817 android} when 1470648204817
,08-08 11:28:45.772  1025  1531 E WifiStateMachine:  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):3 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:324684] from screen [on:0 period:1769710540]
08-08 11:28:45.773  1025  1531 E WifiStateMachine:  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):18 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1769710541]
08-08 11:28:45.774  1025  1531 E WifiStateMachine:  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):19 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1769710542]
08-08 11:28:45.774  1025  1531 D WifiNative-wlan0: doBoolean: SCAN
08-08 11:28:45.775  6534  6534 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-08 11:28:45.778  1025  6613 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-08 11:28:45.778  1025  6613 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-08 11:28:45.778  1025  6613 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-08 11:28:45.778  1025  6613 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-08 11:28:45.789  1025  1531 D WifiNative-wlan0: SCAN: returned true
,08-08 11:28:45.815  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,08-08 11:28:46.102  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-08 11:28:46.102  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-08 11:28:49.333  1025  6613 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-08 11:28:49.333  1025  6613 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-08 11:28:49.334  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-08 11:28:49.334  1025  6613 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-08 11:28:49.334  1025  6613 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-08 11:28:49.334  1025  6613 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: WPS-AP-AVAILABLE 
08-08 11:28:49.335  1025  6613 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-08 11:28:49.346  1025  1531 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=10 known=0 got=10 bcn=0
08-08 11:28:49.348  1025  1531 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=10 known=0 got=10 bcn=0
08-08 11:28:49.350  1025  1529 D LGWifiP2pService: InactiveState{ when=-16ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:28:49.351  1025  1529 D LGWifiP2pService: P2pEnabledState{ when=-16ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:28:49.351  1025  1529 D LGWifiP2pService: DefaultState{ when=-16ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-08 11:28:49.352  1937  6615 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-08 11:28:49.352  1937  6615 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-08 11:28:49.352  1025  1531 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=10 known=0 got=10 bcn=0
08-08 11:28:49.353  1025  1531 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=10 known=0 got=10 bcn=0
08-08 11:28:49.353  1025  1531 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-08 11:28:49.370  6120  6120 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-08 11:28:49.377  6120  6120 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-08 11:29:00.066  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:29:00.067  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:29:00.067  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:29:00.067  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:29:00.081  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-08 11:29:00.081  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:29:00.083  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:29:00.085  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:30:00.111  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:30:00.111  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:30:00.111  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-08 11:30:00.112  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:30:00.128  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:30:00.128  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:30:00.132  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:30:00.133  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:31:00.116  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:31:00.116  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:31:00.116  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:31:00.117  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:31:00.130  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-08 11:31:00.131  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:31:00.131  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:31:00.132  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:32:00.109  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:32:00.110  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:32:00.110  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-08 11:32:00.110  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:32:00.128  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:32:00.128  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:32:00.132  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:32:00.133  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:33:00.117  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:33:00.118  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:33:00.118  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:33:00.118  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:33:00.132  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-08 11:33:00.132  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:33:00.133  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:33:00.134  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:34:00.111  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:34:00.111  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:34:00.111  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:34:00.112  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:34:00.126  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:34:00.126  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:34:00.128  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:34:00.132  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:35:00.114  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:35:00.114  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:35:00.115  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:35:00.115  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:35:00.130  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-08 11:35:00.130  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:35:00.131  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:35:00.132  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:36:00.111  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:36:00.112  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:36:00.112  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-08 11:36:00.112  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:36:00.128  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:36:00.128  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:36:00.132  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:36:00.133  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:37:00.114  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:37:00.114  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:37:00.114  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:37:00.115  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:37:00.128  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:37:00.129  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:37:00.131  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:37:00.132  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:37:42.010  1025  1081 I UsageStatsService: User[0] Flushing usage stats to disk
,08-08 11:38:00.111  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:38:00.111  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:38:00.111  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:38:00.112  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:38:00.125  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:38:00.125  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:38:00.128  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:38:00.131  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:38:30.017  1025  1370 D PowerManagerServiceEx: acquireWakeLockInternal: lock=235384520, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1025
,08-08 11:38:30.033  1025  1370 V AlarmManager: ELAPSED_WAKEUP set : Alarm{73d57a type 2 when 1268184 com.android.bluetooth} when 1268184
08-08 11:38:30.069  2588  2588 D [Concierge]Service: onStartCommand(). Type : 9
,08-08 11:38:30.098  1025  1025 D PowerManagerServiceEx: releaseWakeLockInternal: lock=235384520 [*alarm*], flags=0x0
,08-08 11:39:00.077  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:39:00.077  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:39:00.078  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:39:00.078  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:39:00.094  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-08 11:39:00.095  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:39:00.097  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
,08-08 11:39:00.099  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:40:00.081  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:40:00.081  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:40:00.081  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:40:00.082  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:40:00.100  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:40:00.100  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:40:00.101  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:40:00.103  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:41:00.116  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:41:00.116  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:41:00.116  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:41:00.117  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:41:00.130  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-08 11:41:00.130  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:41:00.131  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:41:00.132  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:42:00.058  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:42:00.058  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-08 11:42:00.059  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:42:00.068  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
08-08 11:42:00.072  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:42:00.072  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:42:00.073  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:42:00.074  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:42:33.861  1597  1597 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-08 11:42:33.865  1597  1597 I [SystemUI]LGPowerUI: On Skip Timer : true
08-08 11:42:33.878  1025  1536 D WifiController: battery changed pluggedType: 2
,08-08 11:42:33.883  1597  1597 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
08-08 11:42:33.883  1597  1597 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-08 11:42:33.885  1937  2064 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-08 11:42:33.885  1937  2064 D LEDHandler: Battery Level Remaining: 100%
08-08 11:42:33.885  1937  2064 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
08-08 11:42:33.887  1597  1597 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-08 11:42:33.890  1025  1025 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:42:33.890  1025  1025 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:42:33.892  5850  5850 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-08 11:43:00.070  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:43:00.070  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:43:00.070  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:43:00.071  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:43:00.084  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-08 11:43:00.084  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:43:00.087  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:43:00.089  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:44:00.081  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:44:00.081  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:44:00.082  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:44:00.082  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:44:00.096  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
08-08 11:44:00.097  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:44:00.102  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:44:00.103  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 11:45:00.092  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-08 11:45:00.092  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:45:00.093  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:45:00.093  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,08-08 11:45:00.107  1597  1597 I LgeClockWidgetControlView: called onTimeUpdated()
,08-08 11:45:00.107  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:45:00.111  1597  1597 I [SystemUI]DateView: called onTimeUpdated()
08-08 11:45:00.111  1597  1597 D KeyguardUpdateMonitor: handleTimeUpdate
08-08 11:46:00.103  1597  1597 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-08 11:46:00.104  1597  1597 I KeyguardUpdateMonitor: called onTimeUpdated()
08-08 11:46:00.104  1597  1597 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-08 11:46:00.104  1597  1597 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
